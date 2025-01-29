# ers_DatatableController

### Usage
- This Apex Class serves the purpose of presenting record details within a data table.

### Test Steps
 1. In app launcher search Grant Out Amendment and click Grant Out Amendment
 2. Open any record.
 3. Click Files & Community File Sharing beside Details tab/section (If the Files Related List is empty, please add a file before proceeding with the subsequent steps.)
 4. Community File Sharing Component has our datatable
   ![image](https://github.com/user-attachments/assets/61033942-729e-4c47-8e2c-2d98a7f99f9a)
 5. Check checkbox of **Shared with Community Users?** and Click Save
 6. Click Update Community File Sharing Status

### Expected Result
 1. Click the file name (which we share using test steps) and click share
 2. Under Who Can See Customer Access redio button is on

  Before
  ![image](https://github.com/user-attachments/assets/03acad90-7bb1-4d2d-956e-e28de45f3b35)

  After
  ![image](https://github.com/user-attachments/assets/0e2588da-f664-45a1-b4f1-ee01127b033a)
 

### TestClass Name / % of coverage (if applicable)
- ers_DatatableControllerTest / 86%

### Additional Information
- https://app.devstride.com/tenger-ways/items/I2145
- https://app.devstride.com/tenger-ways/items/I2384
