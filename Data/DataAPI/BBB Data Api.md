![gcc_logo_2021](../../Images/GCC_Logo_2021.png)
![bbb_1](./images/BBB_1.PNG)

# Quick Start

To get setup on the BBB API, you should go to this link and fill out your information:

[Go Code Better Business Bureau API signup](https://docs.google.com/forms/d/e/1FAIpQLSd8boTpU1bblDJemCP_NF8C0awEffIAJoIm1C_NwAElur-noQ/viewform)

Be sure to review the agreement closely, and consider copying for your own records.
The limits are pretty strict on the number of requests and the amount of information you can extract, so be careful (and multiple team members might want/need to get an API key to get more API calls).
If anyone is worried about legal stuff, you can use the data offline (ie download and store in your own database) as long as you give BBB attribution and refresh the data within 24 hours. Check out their user agreement for more info.

**Note**: Their public link is broken. The only way to view it is to start to sign up, and pull it up from the checkbox area "I have read the user agreement".

The API limits might constrict extensive testing based on area or type. For a long term solution or for exploratory purposes, try downloading all of the CO data and then putting it in some csv/database format that you can explore and look at different things that might be of interest -- type, location, standing, etc.

# Better Business Bureau

The Better Business Bureau tracks businesses of all types, including building location, rating, and various other information. This can be extremely helpful for contestants participating in GoCode, as this type of data is typically proprietary. BBB offers a free tier of their API, which allows participants to access this rich data!
We would suggest building a copy/database of this information for your own use, as using the API directly could lead to over-usage of the API and getting stopped/blocked. You could pay for access to the API if that becomes a more cost-effective approach.
You can sign up by following the directions at this site: https://developer.bbb.org/. While there is documentation on how to access and use the API, the information is sparse.

### Initial  Sign-up and Test

After signing up (using the register link above) look for an active token on the user account [main page](https://developer.bbb.org/user/account/api). If not, request/reload for a new token. These tokens allow users to authenticate, and allow the BBB to assure users are following their rules and not making too many requests. You can test using almost any url system, though we suggest using a tool like Postman for initial testing.

There are examples of how to use the API in various languages [here](https://developer.bbb.org/documentation/openapi#api-OrganizationSearch), for a series of examples on Postman you can contact @jamesbrown on slack to share the tests with you (you will need to attach your API token as a variable, documentation [here](https://learning.getpostman.com/docs/postman/variables-and-environments/variables/)). Please post your Postman username!

### Fields and Searching

You can search on various fields, which are listed under the Parameters section [here](https://developer.bbb.org/documentation/openapi#api-OrganizationSearch) (just below the API examples in the above link). Here are a few hints/notes:

- Assuming you want to filter to Colorado, use the stateProvince field, and set equal to CO: `https://api.bbb.org/api/orgs/search?stateProvince=CO`
- The page size defaults to 50, so by default 50 (or less) records will be returned at once. You can request more by changing the pageSize field, and you can move through the different number of results with pageNumber. You can know how many page numbers you will need to request by the results, the TotalResults field divided by your pageSize value will give you the number of requests necessary to get all the data.
- Organization Name is the primary field that is always filled out for any organization.
- Note the bottom of the page about the API, there is a schema which denotes the fields that are in arrays: business url’s, phone numbers, etc.
