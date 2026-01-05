<h1>Demonstrating Complex SQL Techniques</h1>
<img width="410" alt="SQL Project 1" src="https://github.com/jciwilliams/SQL_Techniques/assets/152811710/0cd14067-3a89-44f3-84d1-e1396f436c7d">

### SQL projects demonstrate complex skills like: 
 - <b>Retrieving Data using Conditional Comparison Operators for Filtering</b>
 - <b>Extracting Data from a Date and Numbers</b>
 - <b>Retrieving Data from Multiple Tables Using Union and Subqueries</b>
 - <b>Retrieving Data using Case Statements </b>


<h2>SQL Project 1</h2>
The Intake Director just left a strategy meeting with the Chief Health Officer (CHO).
The CHO emphasized an urgent initiative focused on patients residing in California, Montana, and Minnesota, as new state-specific health policy changes will go into effect on November 1, 2025.
To support this initiative, she needs a report that identifies active patients covered under:
-Medicaid in California, or
-Blue Cross–affiliated insurance plans in Montana and Minnesota.
The report will be used to estimate how many patients may be impacted by these upcoming policy changes. The list should show active patients that have Medicaid in CA OR BCBS in MT and MN.<br />


###
<p align="center">
Extracting Multiple Conditions Comparison: <br/>
<img width="850" height="185" alt="Image" src="https://github.com/user-attachments/assets/13bb69c4-3dce-4c1d-a5d7-8c07743ace7b" />
<br />
<br />


<h2>SQL Project 2</h2>
The Director of Community Health Outreach just met with the Chief Marketing Officer (CMO) to plan upcoming patient engagement events in key metropolitan areas across the Southeast.
The marketing team wants to focus on major cities and their surrounding suburbs where outreach campaigns will be launched.
Specifically, they’re targeting patients who reside in or near:
Atlanta, GA, Dallas, TX, Miami, FL, and Greenville, SC
Because many patients live in suburban or directional areas (for example, “North Atlanta,” “South Miami,” “Greenville Heights”), he emphasized that the search should include any record where the city name contains those target city names — not just exact matches.<br />


###
<p align="center">
Extracting Multiple Conditions Comparison: <br/>
<img width="556" height="159" alt="Image" src="https://github.com/user-attachments/assets/f9d25948-ca50-49de-9b3e-5d0cc838cc5f" />
<br />
<br />


<h2>SQL Project 3</h2>
A Senior Financial Analyst is working on a mid-year review with the Chief Revenue Officer (CRO).
The CRO has requested a focused audit on mid-range payments (those between $800 and $1,200) from key commercial payers — UHC and Aetna.
The purpose of the audit is to identify consistent payment patterns and ensure these remits are not being reduced by contractual adjustments (CO codes), which could indicate underpayments or misapplied contractual logic. He’s task is to isolate all remittances that meet the following criteria:
The dataset will be reviewed by both the Billing Audit and Contracting teams to evaluate payment consistency before contract renegotiations begin. The list should show mid-range payments between $800 and $1200, payers (UHC and Aetna), and not being reduced by CO codes.<br />


###
<p align="center">
Extracting Multiple Conditions Comparison: <br/>
<img width="711" height="191" alt="Image" src="https://github.com/user-attachments/assets/b0b58701-56a2-4ed4-a2ef-abb5223216bb" />
<br />
<br />


<h2>SQL Project 4</h2>
The Enrollment Manager is preparing annual compliance reports for the state health agency. She needs to confirm the enrollment year and month for every active patient to ensure proper record-keeping. The list should show the enrollment year, enrollment month, and every patient being active.<br />


###
<p align="center">
Filtering Data and Date Functions: <br/>
<img width="605" height="229" alt="Image" src="https://github.com/user-attachments/assets/94b37004-27f9-4488-8248-713904a0cc2c" />
<br />
<br />


<h2>SQL Project 5</h2>
Auditors are now requesting all claims to be discarded 36 months after the claim deposit date. May you provide auditors with a list of the claim discard date for each claim that we have in our system for non-P04 and P06 providers? The list should show a list of claims, the discard date with 36 months after the deposit date, and Non P04 and P06 providers.<br />


###
<p align="center">
Extracting, Sorting, Limiting, Filtering Data, and Date Functions: <br/>
<img width="805" height="177" alt="Image" src="https://github.com/user-attachments/assets/f7f5d4b6-7476-4ddd-bb55-13ae00fdeea3" />
<br />
<br />

<h2>SQL Project 6</h2>
An analyst is evaluating UnitedHealthcare (UHC) payment patterns to forecast revenue for next year. Management wants to see the average payment amount per year for claims with payer “UHC” with CO and PR pay codes who are on manual payments or UHC with OA pay codes who are on auto payment. The list should show UnitedHealthcare payments and average payment amount per year. Payer claims (UHC) with CO/PR codes and on manual payments OR claims with UHC OA pay codes who are on auto payments.<br />


###
<p align="center">
Filtering Data, Date Functions, and Calculated Fields: <br/>
<img width="872" height="251" alt="Image" src="https://github.com/user-attachments/assets/b1013ae9-388f-4ede-af31-537af0074ee2" />
<br />
<br />


<h2>SQL Project 7</h2>
For all EDI claim submissions that were submitted with an E primary diagnosis code that took at least 30 days to be adjudicated, we need the provider who submitted these claims as long as the providers have been active with us for at least 5 years. The should show all  claim submission, E primary diagnoses codes, providers names, took at least 30 days to be adjudicated, and providers need to be active with the company for at least 5 years. <br />


###
<p align="center">
Advanced Joins: <br/>
<img width="1145" height="451" alt="Image" src="https://github.com/user-attachments/assets/2fbabb92-c0e7-4f1c-82da-2294398d5e39" />
<br />
<br />


<h2>SQL Project 8</h2>
New patients have a 90-day waiting period before certain benefits become active. The Eligibility team needs to determine when each patient’s waiting period ends along with the day of the week for the waiting period end date. The list should show each patient’s waiting period end date with 90 days after they enrolled and day of the week for the waiting period end date.<br />


###
<p align="center">
Filtering Data and Date Functions: <br/>
<img width="653" height="105" alt="Image" src="https://github.com/user-attachments/assets/4bfe7cd8-6fec-4bda-8b56-fc83fe11589b" />
<br />
<br />

<h2>SQL Project 9</h2>
For all Endocrinology providers whose NPIs start with 7 or Dermatology providers whose NPIs start with 1 or 2 who have not completed a procedure but have visits recorded, may you let us know how long each of these providers have been active providers with us? The list should show all endocrinology providers, NPIs need to start with 7 OR all dermatology providers, NPIs need to start with 1 or 2, DID NOT complete a procedure, but have visits on records and how long each provider has been active (years).<br />


###
<p align="center">
Advanced Joins: <br/>
<img width="886" height="580" alt="Image" src="https://github.com/user-attachments/assets/48c062ea-e2fc-4a49-8518-dbf563d8e8b5" />
<br />
<br />

<h2>SQL Project 10</h2>
Identify all applicants who completed online registration and determine the core attributes required to analyze digital engagement. We need this for applicants who have at least a 750 credit score and reside in the Southwest region OR applicants who are not located in NY, CA, and/or HI. Your output should include: Member ID, First and Last Name, Method of Sign-Up (channel of enrollment), Credit score, and Email address (if they have one on record). Consider how isolating online sign-ups could help the credit union assess digital adoption trends and improve member acquisition strategies.<br />


###
<p align="center">
UNIONS: <br/>
<img width="948" height="640" alt="Image" src="https://github.com/user-attachments/assets/b85083bb-c6a7-4cfc-83ef-5773b41d8752" />

<img width="1327" height="629" alt="Image" src="https://github.com/user-attachments/assets/82c99f7f-7015-436f-b9a7-f7a219f54204" />
<br />
<br />

<h2>SQL Project 11</h2>
Identify B2B and Government non - standard customer orders that were not returned and placed by customers who are active and have been customers for at least 5 years. The list should show orders, B2B customers, government customers, non-standard, orders not returned, active customers ‘True’, and customers at least 5 years.

Thanks, but with the lists you provided for the non-returned orders and the returned orders, we need a consolidated list in order for the Supply Chain to complete a comparative analysis to identify trends in product performance and operational accuracy.<br />


###
<p align="center">
UNIONS: <br/>
<img width="888" height="668" alt="Image" src="https://github.com/user-attachments/assets/1d6d5219-906a-4646-ac86-fda62293487e" />

<img width="898" height="411" alt="Image" src="https://github.com/user-attachments/assets/a7513d59-d283-4923-ae0f-f22b9f509faf" />
<br />
<br />

<h2>SQL Project 12</h2>
From the following consolidated list that you provided a few days ago, may you provide the following: number of individuals in the list, average credit score, highest credit score, and lowest credit score.
The consolidated list that you provided included the following groups: Identify all applicants who completed online registration and determine the core attributes required to analyze digital engagement. We need this for applicants who have at least a 750-credit score and reside in the Southwest region OR applicants who are not located in NY, CA, and/or HI. 
Identify all customers in our market who registered in person at a physical branch location and extract the fields necessary to evaluate member engagement through face-to-face channels. We need this for individuals who have at least a 700-credit score, didn’t require a co-signer, and have had their account for at least 7 years OR customers who are younger than 65 years old who have had their account for at least 10 years. <br />


###
<p align="center">
Subqueries, Calculated Fields, and Unions: <br/>
<img width="1007" height="645" alt="Image" src="https://github.com/user-attachments/assets/16c8edf3-db04-4a22-b782-4de92220c9b0" />

<img width="1016" height="637" alt="Image" src="https://github.com/user-attachments/assets/daa7d32d-7ea6-40ab-9f0b-741d507123db" />

<img width="1398" height="155" alt="Image" src="https://github.com/user-attachments/assets/cd5018aa-901d-4be3-91a6-d2fbd9948894" />
<br />
<br />

<h2>SQL Project 13</h2>
From the following consolidated list that you provided a few days ago, may you provide the number of orders? The consolidated list that you provided included the following groups: Identify all order numbers that were not returned and contain SKUs belonging to the 2-family SKU group. Identify B2C customer orders that were returned as duplicates during Q1 2023, where the order included product keys beginning with 3 or 7. Identify B2B and Government non - standard customer orders that were not returned and placed by customers who are active and have been customers for at least 5 years.

Thanks, but I actually need the number of orders by warehouse and shipping status from 1 and 5 family product key orders that were ordered in 2025.<br />


###
<p align="center">
Subqueries and Unions: <br/>
<img width="981" height="478" alt="Image" src="https://github.com/user-attachments/assets/8f7da49b-5c0a-4107-aa50-745ea5dd4b9e" />

<img width="953" height="515" alt="Image" src="https://github.com/user-attachments/assets/c58f7bba-cc87-4295-a5b9-bde78fb46def" />

<img width="958" height="585" alt="Image" src="https://github.com/user-attachments/assets/71d23681-f614-4b9f-ab39-278d97c71961" />
<br />
<br />

<h2>SQL Project 14</h2>
The Billing Department needs to categorize insurance types to determine reimbursement workflows and government reporting requirements.
- If a patient’s insurance type is Medicaid or Medicare, label it as Government Insured
- Otherwise, label it as Non-Government Insured. The list should show all patients, that have Medicaid or Medicare label it as Government Insured. Otherwise, label it as Non-Government Insured.<br />


###
<p align="center">
Case Statements: <br/>
<img width="1381" height="160" alt="Image" src="https://github.com/user-attachments/assets/7a2459f1-515f-47f3-ad69-eb76a22041e8" />
<br />
<br />

<h2>SQL Project 15</h2>
The Customer Loyalty team is going to $X off in honor of our annual customer appreciation. The discount will be allocated based on the customer tier level for active customers who have been customers for at least 2 years. May you apply the $X off based on the customer’s tier level:
- Standard: $100 off
- Silver: $250 off
- Gold: $500 off
- Platinum: $1,000 off

Once you have this, please provide them with the number of customers at each discount level, along with the total expected discounts at each discount level so Finance can properly forecast the burdened cost of these holiday discounts. The list should show active customers, customers for at least 2 years, by tier level, number of customers at each tier/discount level and total expected discounts at each tier /discount level.<br />


###
<p align="center">
Case statements, Dates, and Calculated Fields: <br/>
<img width="545" height="549" alt="Image" src="https://github.com/user-attachments/assets/2ca7dbe6-dd41-4b44-ac9f-d40681c516c2" />
<br />
<br />


<h2>SQL Project 16</h2>
Thanks for sending over this list. The regional assignments used in your previous list are now outdated. Going forward, please apply the updated regional structure provided below:
East
Delaware (DE)
Maryland (MD)
Washington, D.C. (DC)
West Virginia (WV)
West
Colorado (CO)
Idaho (ID)
Montana (MT)
Nevada (NV)
Utah (UT)
Wyoming (WY)
Arizona (AZ)
New Mexico (NM)
Pacific West
Alaska (AK)
California (CA)
Hawaii (HI)
Oregon (OR)
Washington (WA)
Midwest
Illinois (IL)
Indiana (IN)
Iowa (IA)
Kansas (KS)
Michigan (MI)
Minnesota (MN)
Missouri (MO)
Nebraska (NE)
North Dakota (ND)
Ohio (OH)
South Dakota (SD)
Wisconsin (WI)
North
Connecticut (CT)
Massachusetts (MA)
New Hampshire (NH)
Rhode Island (RI)
Vermont (VT)
Northeast
Maine (ME)
New Jersey (NJ)
New York (NY)
Pennsylvania (PA)
South
Alabama (AL)
Arkansas (AR)
Kentucky (KY)
Louisiana (LA)
Mississippi (MS)
Oklahoma (OK)
Tennessee (TN)
Texas (TX)
Southeast
Florida (FL)
Georgia (GA)
North Carolina (NC)
South Carolina (SC)
Virginia (VA)
<br />


###
<p align="center">
Case Statements, Subqueries, Unions, Joins and Calculated Fields: <br/>
<img width="470" alt="Image" src="https://github.com/user-attachments/assets/734a08ff-89d5-41a3-91d6-05e15a5ee1e9" />
<br />
<br />



</p>



