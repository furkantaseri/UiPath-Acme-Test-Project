1-Log in to "https://acme-test.uipath.com/login"

2-Download the Vendor List excel file by following the steps Vendors->Download Vendor List

3-Change the name of the downloaded file to "ddMMyyyy_VendorList.xlsx" according to the date of that day

4-Create a column titled "Status" in the "Vendor list" sheet

5-For each vendor, search Vendors ->Search for Vendor, then "Vendor TaxID" on the Acme page

If the search was successful:

Fill the Status column in Excel with "Successful"

In the same file, create a new sheet named Vendor Name and search
print the resulting table

If the search is unsuccessful:

In Excel, fill the Status column with "Failed"

6-Delete Vendor Inventory sheet

7-Save the Excel file and send it to "to_mail" mail address

8-Log out of the Acme page
