
# CCSA Data Dictionary

The BIC Maintains 15 Charities datasets from the Colorado Department of State on CIM. These datasets are commonly referred to as CCSA data, for the [Charitable Solicitations Act](https://www.sos.state.co.us/pubs/info_center/laws/Title6/Title6Article16.html).

## Charity Extension Requests

[https://data.colorado.gov/Business/Charity-Extension-Requests/icqv-mi3c](https://data.colorado.gov/Business/Charity-Extension-Requests/icqv-mi3c)

Charitable organization requests for an extension of the deadline for filing a financial report. Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| authorizedOfficer | Name of person making request |
| filesForm990T | Form 990-T corporation? |
| extendedDueDate | New due date: three months added to renewal date |
| dateFiled | Date request was created |
| fiscalYearend | Fiscal year-end date request is being asked for |
| extensionRequestReason | Reason for extension request |
| IRSRequires990 | Does IRS require organization to file an Exempt Organization Return? |
| form8868Filed | Did you file a Form 8868 with the IRS? |

## Paid Solicitors Disclosed on Charity Registration Forms in Colorado

[https://data.colorado.gov/Business/Paid-Solicitors-Disclosed-on-Charity-Registration-/wwbh-7bpa](https://data.colorado.gov/Business/Paid-Solicitors-Disclosed-on-Charity-Registration-/wwbh-7bpa)

Paid Solicitors and Professional Fundraising Consultants Disclosed on Charity Registration Forms. Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| nameofPS-PFC-CCV | If solicitor is organization, name |
| title | If individual, title |
| firstName | First name of officer etc. |
| middleName | Middle name of officer etc. |
| lastName | Last name of officer etc. |
| registrantType | Type of person: PS (Paid Solicitor), PFC (Professional Fundraising Consultant) or Commercial Co-Venture |
| registrantTypeAbbr | Type of person: PS (Paid Solicitor), PFC (Professional Fundraising Consultant) or Commercial Co-Venture |
| address | Address; blank if personal address |
| city | City; blank if personal address |
| state | Two-letter state code; blank if personal address |
| zipCode | Zip code; blank if personal address |
| zipCode4 | Zip code 4; blank if personal address |
| mailingAddress | Mailing address |
| mailingCity | Mailing city |
| mailingState | Mailing two-letter state code |
| mailingZipCode | Mailing zip code |
| mailingZipCode4 | Mailing zip code 4 |
| performedAddress | Address where work is performed |
| performedCity | City where work is performed |
| performedState | State where work is performed |
| performedZipCode | Zip where work is performed |
| performedZipCode4 | Zip where work is performed |
| phone | Phone |

## Other Names a Registered Entity Uses to Solicit Contributions

[https://data.colorado.gov/Business/Other-Names-a-Registered-Entity-Uses-to-Solicit-Co/q2av-rpr5](https://data.colorado.gov/Business/Other-Names-a-Registered-Entity-Uses-to-Solicit-Co/q2av-rpr5)

All names other than registered entity name under which charities, paid solicitors, and professional fundraising consultants will solicit contributions or provide fundraising consulting services in Colorado.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| otherName | Other name organization solicits under |

## Charitable Organizations&#39; Offices in Colorado

[https://data.colorado.gov/Business/Charitable-Organizations-Offices-in-Colorado/3qtu-edua](https://data.colorado.gov/Business/Charitable-Organizations-Offices-in-Colorado/3qtu-edua)

Charitable organizations data consisting of mailing address, phone, fax, website of organization&#39;s offices in Colorado. Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| entityType | Entity type: CO (Charitable Organization), PS (Paid Solicitor), or PFC (Professional Fundraising Consultant) |
| documentId | Filing Id |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| isParentOrganization | Identifies record as a branch, affiliate, or chapter of parent organization. |
| organizationName | If consultant is not an individual but an organization |
| firstName | If consultant is individual (first name) |
| middleName | If consultant is individual (middle name or initial) |
| lastName | If consultant is individual (last name) |
| principalAddress | Principal street address |
| principalCity | Principal city |
| principalCounty | Principal county |
| principalState | Principal state |
| principalZipCode | Principal zip |
| principalZipCode4 | Principal zip4 |
| mailingAddress | Mailing address |
| mailingCity | Mailing city |
| mailingState | Mailing state |
| mailingZipCode | Mailing zip |
| mailingZipCode4 | Mailing zip4 |
| phone | Phone |
| fax | Fax number |
| website | Web site (URL) |

## Persons Associated with Charitable Organizations, Paid Solicitors, and Professional Fundraising Consultants in Colorado

[https://data.colorado.gov/Business/Persons-Associated-with-Charitable-Organizations-P/mr4v-jz8u](https://data.colorado.gov/Business/Persons-Associated-with-Charitable-Organizations-P/mr4v-jz8u)

Non-profit organization (NPO) data of registrants&#39; officers, directors, trustees, professional fundraising consultants from the Colorado Department of State Division of Charity (SOS).

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| entityType | Entity type: CO (Charitable Organization), PS (Paid Solicitor), or PFC (Professional Fundraising Consultant) |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| title | Title of officer or other key person |
| businessName | Business name if organization and not individual |
| firstName | First name of officer |
| middleName | Middle name of officer |
| lastName | Last name of officer |
| principalAddress | Principal address; blank if personal address |
| principalCity | Principal city; blank if personal address |
| principalState | Principal two-letter state code; blank if personal address |
| principalZipCode | Principal zip code; blank if personal address |
| principalZipCode4 | Principal zip4 |
| mailingAddress | Mailing address (PO box); blank if personal address |
| mailingCity | Mailing city; blank if personal address |
| mailingState | Mailing two-letter state code; blank if personal address |
| mailingZipCode | Mailing zip code; blank if personal address |
| mailingZipCode4 | Mailing zip4 code; blank if personal address |
| phone | Phone |
| subcontractor | If a subcontractor, then &#39;Y&#39; |
| inBusiness | Officer in business? |

## Solicitation Campaign Supervisors Listed on Solicitation Notices in Colorado

[https://data.colorado.gov/Business/Solicitation-Campaign-Supervisors-Listed-on-Solici/hyr8-d3v9](https://data.colorado.gov/Business/Solicitation-Campaign-Supervisors-Listed-on-Solici/hyr8-d3v9)

Non-profit organization (NPO) data of associated directors, officers, trustees, professional consultants, paid solicitors from the Colorado Department of State (CDOS) Division of Charity.

| **CIM Field Name** | **Description** |
| --- | --- |
| solicitationNoticeId | Solicitation Notice ID |
| charityName | Charitable Organization Name |
| solicitorName | Paid Solicitor Name |
| officerTitle | Title of officer or other key person |
| businessName | Business name if organization and not individual |
| firstName | First name of officer |
| middleName | Middle name of officer |
| lastName | Last name of officer |
| principalAddress | Principal address; blank if personal address |
| principalCity | Principal city; blank if personal address |
| principalState | Principal two-letter state code; blank if personal address |
| principalZipCode | Principal zip code; blank if personal address |
| mailingAddress | Mailing address (PO box); blank if personal address |
| mailingCity | Mailing city; blank if personal address |
| mailingState | Mailing two-letter state code; blank if personal address |
| mailingZipCode | Mailing zip code; blank if personal address |
| phone | Phone |
| natureOfViolation | Nature of violation |
| dateOfViolatioin | Date of violation |
| courtWithJurisdiction | Court having jurisdiction in the violation |
| dispostitionOfOffense | Disposition of the offense |
| dateOfConviction | Date of conviction of violation |
| dateOfInjunction | Date of the injunction |
| courtIssuingInjunction | Court issuing the injunction |
| isSubcontractor | If a subcontractor, then &#39;Y&#39; |
| officerInBusiness | Officer in business? |
| otherNamesOfOrganization | Other name organization solicits under |

## Charitable Purpose of the Charity in Colorado

[https://data.colorado.gov/Business/Charitable-Purpose-of-the-Charity-in-Colorado/7jm9-f28m](https://data.colorado.gov/Business/Charitable-Purpose-of-the-Charity-in-Colorado/7jm9-f28m)

Charities data consisting of a charitable organization&#39;s registration number, federal employer Identification number (EIN), charitable purpose, filing date. Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| filingDate | Filing Date |
| statementOfPurpose | Statement of purpose of Charitable Organization and description of program services |

## Registration of Charities, Paid Solicitors, Professional Fundraising Consultants, and for-profit Public Benefit Corporations in ColoradoBusiness

[https://data.colorado.gov/Business/Registration-of-Charities-Paid-Solicitors-Professi/37wu-kn3g](https://data.colorado.gov/Business/Registration-of-Charities-Paid-Solicitors-Professi/37wu-kn3g)

Charitable Solicitations Registration Information Filed by Charities, Paid Solicitors, and Professional Fundraising Consultants. Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| registrantTypeAbbr | Entity type: CO (Charitable Organization), PS (Paid Solicitor), or PFC (Professional Fundraising Consultant) |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| fein | Federal Employer Identification Number |
| documentId | Accounting ID (Registration Number) |
| amendmentEntityId | If filing type is Amendment, then filing ID of the record it is amending |
| externalFilingFromNccs | If record is an external filing from NCCS or the IRS, then &#39;Y&#39; else &#39;N&#39; |
| filingType | Filing type: Initial Registration, Initial Registration – Estimates, Amendment, Amendment – Estimates, Renewal, Reinstate Renewal, Extension, Fiscal Year Change, Estimate Extension, Exemption, Exemption Amendment, Financial Form |
| actualFinancialsProvided | If actual financials are provided then &#39;Y&#39; else &#39;N&#39; |
| principalAddress | Principal address |
| principalAddress2 | Principal address 2 |
| principalCity | Principal city |
| principalState | Principal two-letter state code |
| principalProvince | Principle province |
| principalZipcode | Principal zip code |
| principalZipcode4 | Principal zip code |
| residentialCounty | Principle county |
| principalCountry | Principle country |
| mailingAddress | Mailing address (PO box) |
| mailingAddress2 | Mailing address 2 |
| mailingCity | Mailing city |
| mailingState | Mailing two-letter state code |
| mailingProvince | Mailing province |
| mailingZipcode | Mailing zip code |
| mailingZipcode4 | Mailing zip code |
| mailingCountry | Mailing Country |
| phone | Phone (this is an unformatted text field) |
| fax | Fax number |
| website | Website(URL) |
| authorizedOfficerName | Authorized Officer first and last name |
| authorizedOfficerSignedDate | Date Authorized Officer signed registration |
| cfoName | For Charitable Organizations, CFO first and last name |
| cfoSignedDate | For Charitable Organizations, date CFO signed registration |
| registrationApprovedDate | Date and time at which registration was approved |
| paymentProcessedDate | Date and time payment was processed |
| nextRenewalRegistrationDate | Due date for entity&#39;s next renewal of registration |
| fiscalYearStartDate | Beginning of fiscal year |
| fiscalYearEndDate | End of fiscal year |
| NTEECode1 | National Taxonomy of Exempt Entities Code Description |
| NTEECode2 | National Taxonomy of Exempt Entities Code Description |
| NTEECode3 | National Taxonomy of Exempt Entities Code Description |
| taxExemptStatus | If tax exempt organization, then &#39;Y&#39; |
| taxExemptCode | Tax exempt code |
| IRSDeterminationDate | Date of application for exemption or dateof letter of determination of exemption |
| donationsTaxDeductible | If donations to organization are tax deductible, then &#39;Y&#39; |
| extensionFiled | If extension was filed, then &#39;Y&#39; |
| consolidatedRegistrationStatement | Is organization&#39;s registration a consolidatedRegistration statement (&#39;Y&#39; or &#39;N&#39;) |
| publicBenefitCorporation | Is organization a (PBC) public benefit corporation (&#39;Y&#39; or &#39;N&#39;) |
| reportingPeriodBegin | Beginning tax year this report covers |
| reportingPeriodEnd | Ending tax year this report covers |
| newCharity | If organization is providing estimates because charity is new, then &#39;Y&#39; |
| outsideProfessionalFundraiserFees | Outside professional fundraisers fees |
| totalContributionsRaisedPreviousYear | Total contributions raised in previous year |
| totalFundraisingExpensesPreviousYear | Total fundraising costs in previous year |
| totalManagementGeneralExpensesPreviousYear | Total management and general costs in previous year |
| expensesDividedByContributions | Total fundraising costs divided by total contributions |
| totalExpensesPlusManagementGeneralDividedByContributions | (Total fundraising costs + total management and general costs) divided by total contributions |
| relatedOrganizationName | Name of related organization |
| relatedToOtherOrganization | If organization is related to any other organization, then &#39;Y&#39; |
| relatedOrganizationTaxExempt | If related organization is tax exempt, then &#39;Y&#39; |
| solicitedNonTaxDeductibleGifts | If organization solicited any non-tax-deductible gifts or contributions, then &#39;Y&#39; |
| statedGiftNotTaxDeductible | If organization state clearly gifts or contributions were not tax deductible, then &#39;Y&#39; |
| pbcRecordingMethod | For PBC organizations, recording method (&#39;ACCRUAL&#39;, &#39;CASH&#39;, or customer input) |
| pbcPromotedBenifit | For PBC organizations, promoted benefit information |
| pbcIssuesStockShares | For PBC organizations, whether the organization issues stock shares (&#39;Y&#39; or &#39;N&#39;, null if non-pbc) |
| pbcStockSharesAvailable | For PBC organizations, number of stock shares available |
| pbcBenefitReportSent | For PBC organizations, whether benefit report was sent to stockholders (YES, NO, NA, null if non-pbc) |
| pbcAnnualBenefitReport | For PBC organizations, instructions on obtaining the annual benefit report |
| revenueFromContibutions | Revenue from contributions |
| revenueFromGovernment | Revenue from government |
| programServiceRevenue | Program service revenue |
| revenueFromInvestments | Revenue from investments |
| revenueFromSpecialEvents | Revenue from special events and activities |
| tRow[&quot;revenueFromSales&quot;] = row[&#39;Os Rev Sales&#39;].replace(/,/g,&quot;&quot;); | Revenue from sales |
| revenueOther | Other revenue |
| revenueTotal | Total of all revenues |
| expensesFromProgramServices | Expenses from program services |
| expensesFromAdministrativeOther | Administrative and other general expenses |
| expensesFundraising | Fundraising expenses |
| expensesAffiliates | Payment to affiliates expenses |
| expensesOther | Other expenses |
| expensesOtherComment | Other expenses comment |
| expensesTotal | Total of all expenses |
| endOfYearAssests | Total end of year assets |
| endOfYearTotalLiabilities | Total end of year liabilities |
| endOfYearAssestsMinusLiabilities | End of year assets minus end of year liabilities |
| unrestrictedAssests | Unrestricted assets |
| temporarilyRestrictedAssets | Temporarily restricted assets |
| permanentlyRestrictedAssets | Permanently restricted assets |
| conflictOfInterest | Paid Solicitor conflict of interest Flag (&#39;Y&#39; or &#39;N&#39;, null if not a PS) |
| conflictOfInterestAffirmation | Paid Solicitor Conflict of interest affirmation (&#39;Y&#39; or &#39;N&#39;, null if not a PS) |
| legalBusinessFormation | Legal business formation |
| placeFormed | Place Formed |
| dateFormed | Date Formed |
| currentStatus | Current Status |
| statusDate | Status Date |
| expirationDate | Expiration Date of Filing |
| programServiceRatio | Program Service Ratio Program Service Expenses/Total Expenses |

## Campaign Reports for Solicitation Notices to Charities in Colorado

[https://data.colorado.gov/Business/Campaign-Reports-for-Solicitation-Notices-to-Chari/fdcw-ei67](https://data.colorado.gov/Business/Campaign-Reports-for-Solicitation-Notices-to-Chari/fdcw-ei67)

Non-profit organization (NPO) data of campaign reports for solicitation notices from the Colorado Department of State (CDOS) Division of Charity.

| **CIM Field Name** | **Description** |
| --- | --- |
| solicitationNoticeId | Solicitation Notice ID |
| campaignReportId | Solicitation Notice Campaign Report ID |
| filingType | Filing Type: Master, Amendment, Renewal |
| filingStatus | Filing Status |
| campaignDateFiled | Date campaign report was filed |
| charityName | Charitable Organization Official first and last name |
| charitySignedDate | Date Charitable Organization Official signed campaign report |
| solicitorName | Paid Solicitor first and last name |
| solicitorSignedDate | Date Paid Solicitor signed campaign report |
| grossContributions | Gross proceed; contributions |
| grossTicketSales | Gross proceed: ticket sales |
| grossAdvertisingSales | Gross proceed: advertising sales |
| grossInKind | Gross proceed: in kind |
| grossTotal | Total of gross proceed columns |
| inKindDescription | Description of in-kind proceeds |
| grossOther | Gross proceed: other revenue |
| expenseSalaryCommision | Expenses: salaries and commissions |
| expensePrinting | Expenses: printing of solicitation materials |
| expensePostage | Expenses: postage |
| expenseTelephone | Expenses: telephone |
| expenseOfficeRental | Expenses: office rental |
| expenseOfficeExpenses | Expenses: office expenses |
| expenseTotal | Total of all expense columns |
| expenseAuditoriumRental | Direct event expenses: auditorium rental |
| expenseEventFee | Direct event expenses: show fee for performers |
| expenseEventPrinting | Direct event expenses: printing costs for tickets and program books |
| expenseEventOther | Direct event expenses: other expenses |
| proceedsNet | Net proceeds to charity (gross proceeds minus expenses + direct event expenses) |
| proceedsPercentToCharity | Percentage of proceeds to charity (net charity divided by (expenses + direct even expenses X 100)) |
| isFinancialLocalOnly | Does financial information reflect solicitation activity in Colorado only or nationally? |
| bookkeeper | Person who is caretaker of books and records |
| bookkeeperAddress | Address of bookkeeper |
| bookkeeperCity | City of bookkeeper |
| bookkeeperState | State of bookkeeper |
| bookkeeperZipcode | Zip of bookkeeper |
| activityFlag | Activity flag |
| comments | Comments |

## Solicitation Campaign Supervisors Listed on Solicitation Notices in Colorado

[https://data.colorado.gov/Business/Solicitation-Campaign-Supervisors-Listed-on-Solici/hyr8-d3v9](https://data.colorado.gov/Business/Solicitation-Campaign-Supervisors-Listed-on-Solici/hyr8-d3v9)

Non-profit organization (NPO) data of associated directors, officers, trustees, professional consultants, paid solicitors from the Colorado Department of State (CDOS) Division of Charity.

| **CIM Field Name** | **Description** |
| --- | --- |
| solicitationNoticeId | Solicitation Notice ID |
| charityName | Charitable Organization Name |
| charityEntityID | Charitable Organization Entity ID |
| solicitorName | Paid Solicitor Name |
| paidSolicitorEntityId | Paid Solicitor Entity ID |
| filingType | Filing type: Master, Amendment, Renewal |
| documentId | Filing Status |
| amendmentDocumentID | Accounting ID (Solicitation Notice Registration Number) |
| solicitationApprovedDate | If filing type is Amendment, then Id of the filing it amended |
| paymentProcessedDate | Date and time at which solicitation notice was approved |
| campaignCommencementDate | Date and time payment was processed |
| campaignConclusionDate | Commencement date of campaign |
| charityOfficerName | Conclusion date of campaign |
| charitySignedDate | Charitable Organization Official first and last name |
| custodyOfContributions | Date Charitable Organization Official signed solicitation notice |
| custodyOfFinancialRecords | Will Paid Solicitor ever have custody of contributions? |
| eventCampaignDescription | Will Paid Solicitor ever have custody of financial records of contributions? |
| accountingRecordsAddress | Description of any event the campaign will lead up to |
| accountingRecordsCity | Address where accounting records are kept |
| accountingRecordsState | City where accounting records are kept |
| accountingRecordsZipCode | State where accounting records are kept |
| charityControlsFunds | Zip where accounting records are kept |
| financialInstitutionEntityId | Does Charitable Organization control administering and withdrawing from the account |
| contractEffectiveDate | Effective date of the contract |
| contractTerminationDate | Termination date of the contract |
| percentageBasedContract | Will percentage of gross receipts be remitted to charitable organization? |
| minimumPercentageOfGrossReceiptsRemitted | Minimum percentage of gross receipts remitted to charitable organization |
| percentageEventPriceRemitted | Will percentage of purchase price to event be remitted to the charitable organization? |
| minimumPercentageSaleRemitted | Minimum percentage of sale remitted to Charitable Organization |
| specifiedPercentageGrossRevenueReceivedBySolicitor | Specified percentage of gross revenue received by Paid Solicitor |
| solicitorCompensationPercentageBased | Is Paid Solicitor&#39;s compensation contingent upon number of contributions or amount received |
| estimatedPercentofGrossRevenue | Percentage of gross revenue constituting Paid Solicitor&#39;s compensation |
| campaignPurpose | Charitable purpose for which the campaign is being conducted |
| respectiveObligations | Respective obligations of Paid Solicitor and Charitable Organization |
| solicitorCompensationAssumptions | Assumptions upon which estimate of solicitor&#39;s compensation is based |
| contractSigner1FirstName | First name of signer number 1 |
| contractSigner1LastName | Last name of signer number 1 |
| contractSigner1Title | Title of signer number 1 |
| contractSigner1Organization | Organization of signer number 1 |
| contractSigner2FirstName | First name of signer number 2 |
| contractSigner2LastName | Last name of signer number 2 |
| contractSigner2Title | Title of signer number 2 |
| contractSigner2Organization | Organization of signer number 2 |
| contractSigner3FirstName | First name of signer number 3 |
| contractSigner3LastName | Last name of signer number 3 |
| contractSigner3Title | Title of signer number 3 |
| contractSigner3Organization | Organization of signer number 3 |
| contractSigner4FirstName | First name of signer number 4 |
| contractSigner4LastName | Last name of signer number 4 |
| contractSigner4Title | Title of signer number 4 |
| contractSigner4Organization | Organization of signer number 4 |

## Charitable Solicitation Call Center Locations in Colorado

[https://data.colorado.gov/Business/Charitable-Solicitation-Call-Center-Locations-in-C/wwhd-vg25](https://data.colorado.gov/Business/Charitable-Solicitation-Call-Center-Locations-in-C/wwhd-vg25)

Locations and phone numbers from which telephone solicitations will be made into Colorado. Reported on solicitation notices filed with the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| solicitationNoticeId | Solicitation Notice ID |
| charityName | Charitable Organization Name |
| charityEntityId | Charitable Organization Entity ID |
| solicitorName | Paid Solicitor Name |
| solicitorEntityId | Paid Solicitor Entity ID |
| solicitationAddress | Address where solicitation takes place |
| solicitationCity | City where solicitation takes place |
| solicitationState | State where solicitation takes place |
| solicitationZipcode | Zip where solicitation takes place |
| solicitationZipcode4 | Zip last 4, where solicitation takes place |
| solicitationUsedPhonenumber | Phone number being used to solicit |

## Communication Methods Used in Solicitation Campaigns in Colorado

[https://data.colorado.gov/Business/Communication-Methods-Used-in-Solicitation-Campaig/w6kb-3vsj](https://data.colorado.gov/Business/Communication-Methods-Used-in-Solicitation-Campaig/w6kb-3vsj)

Communication methods to be used in a particular solicitation campaign as listed in solicitation notices filed by paid solicitors and signed by charity.Data collected by the Colorado Department of State&#39;s Charities Program.

| **CIM Field Name** | **Description** |
| --- | --- |
| entity\_id | Entity ID |
| org\_name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| sol\_type\_dscrp | Type of communication; i.e. door to door, direct mail, telephone, etc. |

## Charities Solicitation Type by Solicitation in Colorado

[https://data.colorado.gov/Business/Charities-Solicitation-Type-by-Solicitation-in-Col/34aw-ny67](https://data.colorado.gov/Business/Charities-Solicitation-Type-by-Solicitation-in-Col/34aw-ny67)

Non-profit organizations (NPO) communication data of paid solicitations and their description for each solicitation. From the Colorado Department of State (CDOS) Division of Charity.

| **CIM Field Name** | **Description** |
| --- | --- |
| sols\_notice\_id | Entity ID |
| ce\_name | Federal Employer Identification Number |
| ps\_name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| sol\_type\_dscrp | Type of communication; i.e. door to door, direct mail, telephone, etc. |

## Other State Solicitation of Charities&#39; Registrants in Colorado

[https://data.colorado.gov/Business/Other-State-Solicitation-of-Charities-Registrants-/5wyf-xqw7](https://data.colorado.gov/Business/Other-State-Solicitation-of-Charities-Registrants-/5wyf-xqw7)

Non-profit organizations (NPO) data consisting of authorized solicitation, and registration data in Colorado by the Colorado Department of State (CDOS).

| **CIM Field Name** | **Description** |
| --- | --- |
| entityId | Entity ID |
| fein | Federal Employer Identification Number |
| name | Charitable Organization, Paid Solicitor or Professional Fundraising Consultant name |
| stateAbbreviation | State abbreviation |
| authorizedSoliciting | If soliciting authorized in state, then &#39;Y&#39;. If soliciting suspended in state, then &#39;N&#39; |
| registrantTypeAbbr | Entity type: CO (Charitable Organization), PS (Paid Solicitor), or PFC (Professional Fundraising Consultant) abbreviation |
| registrantType | Entity type: CO (Charitable Organization), PS (Paid Solicitor), or PFC (Professional Fundraising Consultant) |

## Federal Tax-Exempt Subsection Codes in Colorado

[https://data.colorado.gov/Business/Federal-Tax-Exempt-Subsection-Codes-in-Colorado/2z9k-uy4q](https://data.colorado.gov/Business/Federal-Tax-Exempt-Subsection-Codes-in-Colorado/2z9k-uy4q)

Description of IRS tax-exempt subsection codes and the type of federal return each type must file.

| **CIM Field Name** | **Description** |
| --- | --- |
| taxExemptCode | Tax exempt code under section 501(c) |
| description | Description of activities of charity |
| returnsType | Type of return(s) filed |