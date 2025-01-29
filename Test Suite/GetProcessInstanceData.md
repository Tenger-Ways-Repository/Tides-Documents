# GetProcessInstanceData

### Usage
- This Apex Class serves the purpose of presenting pending approval requests associated with the current logged-in user in the role of approver.

### Test Steps
 1. Search for Money Out tab in AppLauncher
 2. Open an existing record which status is Draft and set  Related Funder Partner Entity = Tides Advocacy
 3. Click on Submit for Approval button
 4. Login as an Approver (see who the request is assigned to)
 5. Search and click Mass Approval Tab in AppLauncher
 6. Select any reocrd from datatable and click Manage for approve and reject reocrd

### Expected Result
 1. Display the approval requests for approve or reject
  ![image](https://github.com/user-attachments/assets/9391df0e-ef80-4da5-aaaa-dd2d14d92b30)
 2. After approve or rejct that record remove from the datatable
  ![image](https://github.com/user-attachments/assets/0603499d-c0a0-4c71-8856-896a36cc6ec2)

### TestClass Name / % of coverage (if applicable)
 - GetProcessInstanceDataTest / 85%

### Additional Information
- https://app.devstride.com/tenger-ways/items/I2023
- https://app.devstride.com/tenger-ways/items/I2365

