# getWrapData2

### Usage
- This Apex Class is utilized to present pending approval requests for the currently logged-in user.

### Test Steps
 1. In app launcher search Money Out and click Money Out
 2. Open an existing record and set Related Funder Partner Entity = Tides Advocacy and Status = Draft
 3. Click on Submit for Approval button
 4. Login as user which has the Actual Approver. In our case it's **Tara Hackenberg**
    ![image](https://github.com/user-attachments/assets/a658ff3c-a36c-4362-978c-986feb237015)
 6. Go to Tides CRM LEX app
 7. Click on Pending Approvals tab

### Expected Result
 1. Present our currently submitted approval request with today's date indicated in the date column.
   ![image](https://github.com/user-attachments/assets/45fca6de-b50c-4cf3-b466-d3313a25c569)

### TestClass Name / % of coverage (if applicable)
- TestApprovals2 / 85%

### Additional Information
- https://app.devstride.com/tenger-ways/items/I2060
- https://app.devstride.com/tenger-ways/items/I3109
