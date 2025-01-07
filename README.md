# leave-Master-documentation
using sharepoint make a leave management system



date=> jan 1 2025


task=> Explore About the MicroSoft SharePoint and Create basic pages and lists for understanding.

work=>

1. Create Lists
Leave_Master List:

Employee Name (Title): Tracks the name of the employee requesting leave.

Leave Type (Choice): Specifies the type of leave (e.g., Sick, Vacation, etc.).

Start Date: The date when the leave begins.

End Date: The date when the leave ends.

Reason: A brief description or reason for the leave.

Approval Status (Choice): Shows the status of the leave request (e.g., Pending, Approved, Rejected).

Linked Holiday (Lookup): A lookup column that links to the Holiday_List_MD, allowing employees to cross-reference holidays when applying for leave.

Holiday_List_MD:

Holiday Name (Title): The name of the public holiday.

Date: The specific date of the holiday.

Description: Additional information about the holiday (e.g., national holiday, company-wide holiday, etc.).


2. Create Document Library
Added a document library to store leave-related documents (e.g., medical certificates, leave approval letters).
Linked Column to Employee Name: This column links the document to the employee, helping to associate leave-related files with their corresponding requests in the Leave_Master list.


3. Create a View
Pending Leave View: Created a customized view called Pending Leave to filter and display only the leave requests that are still in the Pending status. This allows managers or HR to quickly review and act on pending leave requests.


4. Add List View to the SharePoint Site
The Leave_Master list, Holiday_List_MD, and Leave Documents are centralized and displayed on a single SharePoint page.
View all leave requests and their statuses.
Check the holidays from the Holiday_List_MD.
Access any supporting documents related to leave requests.
By adding these lists and views to the page, users can interact with the leave management system in one place.

