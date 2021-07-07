# Develop Environment
1. UiPath Studio Comunity, Profile is UiPath Studio Pro
2. Chrome browser
3. ACME URL (need register firstly): https://acme-test.uipath.com
4. UiPath Orchestrator : https://cloud.uipath.com/altersvdfxhd/portal_/home

# GenerateYearlyReport
 UiPath RPA Develop Advance Practice 2
Generate Yearly Report for Vendor
Download all the monthly reports for a specific vendor and generate a yearly report. 

As 2021 year has no more Monthly Report, so, I just used 2020 as Report year.
If don't find Monthly Report for a month, it will record it in Log.

Steps: 
1.1 Open the ACME System 1 web application.

1.2 Log in to System 1. Required input data: email and password.

1.3 Access the Dashboard - the central location, where the user can pick a specific menu item.

1.4 Access the Work Items Listing to view all the available tasks to be performed (Output data: list of tasks ).

1.5 For each activity of the WI4 type perform the following steps:

1.5.A Open the Details page of the selected activity to retrieve the Vendor Tax ID (Output data: TaxID).

1.5.B Go back to the Dashboard and access the Download Monthly Report section in the Reports menu.

1.5.C Fill in the Vender TaxID and download all the corresponding monthly reports for Current Year

1.5.D Group all the downloaded monthly reports into a single Excel yearly report with the
“Yearly-Report-2020- TAXID.xlsx” name.

1.5.E Upload the resulting Excel yearly report in the “Upload Yearly Report” section in the Reports menu.

1.5.F Fill in the Vendor TaxID, set the year as Current Year (Top 1 Item), and select the file on your hard drive. This will return a unique upload ID. Out upload ID. 

1.5.G Go back to the Work Item Details page and select Update Work Item

1.5.H Set the status to “Completed”. Add the following comment: “Uploaded with ID uploadID”. 
.
1.6 Continue with the next WI4 activity. 

1.7 log out ACME
 
# Author
Zhen (Evan) Wang, Tel:18901599114, WeChat: 18901599114, EmaiL: 18901599114@163.com

MIT

Please keep the author's information.
