![gcc_logo_2020](https://github.com/GoCodeColorado/GoCodeColorado-kbase-public/blob/master/Images/GC20_Logo_Condensed_transp%20-%20Copy.png)

![oedit_1](./images/oedit_1.PNG)

![oedit_2](./images/oedit_2.PNG)

# Events Data

API endpoint summary for events and festivals in Colorado for Colorado Information Marketplace and Gocode Event

[Events and Festivals in Colorado](https://data.colorado.gov/Economic-Growth/Events-and-Festivals-in-Colorado-API-Endpoint/xiem-he2v)

API endpoint for location, description, dates, and contact information for events and festivals in Colorado from the Colorado Tourism Office.

### Available GET Parameters:

| Parameter | Description                                                     | Type    | Default value |
|-----------|-----------------------------------------------------------------|---------|---------------|
| start     | The starting date for the range of events to be returned        | String  | ‘today’       |
| end       | The ending date for the range of events to be returned          | String  | NULL          |
| duration  | The ending date for the range of events to be returned          | String  | ‘next week’   |
| page      | Returns all the results on the declared page.                   | Integer | 1             |
| pagesize  | Determines that amount of events that can be displayed per page | Integer | 50            |
| ot        | Output type (json, jsonh, xml, php)                             | String  | ‘xml’         |
| json      | JSON with text header                                           | json    | N/A           |
| jsonh     | JSON with JSON header                                           | json    | N/A           |
| xml       | Extensive Markup Language                                       | xml     | N/A           |
| php       | Serialized php                                                  | php     | N/A           |

### Notes

Date strings can be anything that can be parsed by php's strtotime function. 'Today', 'Next Week', 'First Thursday of last Month', '2018-01-04' are valid. See this [documentation](Data.doi.gov/harvest) for more information

start dates are automatically altered to start on the previous Monday, unless start actually falls on a Monday

\* end and duration are similar, if both are passed, the greatest parsed date will be used. Duration is calculated from start date.

### Examples

To return all events in February:

Start = ‘2018-02-01’

End = ‘2020-02-29’ - sets range from Feb 1 to Feb 28

Pagesize = 100 - allows for up to 100 events to be displayed per page

`https://codataengine.milesmedia.com/api/feeds/events?start=2018-02-01&end=2018-02-28&pagesize=100`

To return all events from now through May:

Start = ‘today’ - default value

End = ‘2020-05-30’ - sets range from the day of the GET request to May 30, 2018

Pagesize = 500 - allows for up to 500 events to be displayed per page

`https://codataengine.milesmedia.com/api/feeds/events?end=2018-05-30&pagesize=500`
