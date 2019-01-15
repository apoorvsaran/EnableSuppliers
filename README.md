# EnableSuppliers
A code to generate query file for enabling suppliers

1.Create a folder by any name(here, in code, "Automate")

2.Change the value of "commonPath" variable with your folder path. (with "\\" at the end)

3.Change the Depot ID, variable named "depotId" with the depot code. Example: Thatcham-5012068059086

4.Change the "startDate" and "endDate", which are the "test_allocation_effective_start_date" and "test_allocation_effective_end_date" respectively in the query, as per your requirement. 

5.Create a "suppliers.txt" file in the above created folder, containing the list of Suppliers to enable. Make sure all suppliers are separated by a space or are in different lines preferably.

6.Create a "mapping.txt" file in the above created folder, containing the suppliers and their GLN Code written in front of it, separated by a space or tab.
Each "Supplier,GLN Code" pair should be in one line.
If one supplier has many GLN codes, mention them in different lines.

*Better copy from excel or spreadsheet into a text file for steps 4 and 5.

Comments are mentioned in the code for any quick references.
