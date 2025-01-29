# People_Resources_Forms

### Usage

### Test Steps
 - **Verify 1st lookup**
 
 1. Go to the Tides CRM LEX app
 2. Click the Contacts tab and open **Project Directorson** contact
 3. Click to the **Log in to Experience as User** button
 4. Click on **People and Payroll** navigation element
 5. Under the **Forms and Resources** section - click the **Fill Out Form** link in the **Employee Change** field
 6. Here it is (see the below screenshot)
    ![image](https://github.com/user-attachments/assets/063ee94e-d2fe-4723-8bda-3fef6ee2ef2f)
 
 - **Steps to verify 2nd lookup**

 1. Go to the Tides CRM LEX app
 2. Click the Contacts tab and open **Project Directorson** contact
 3. Click to the **Log in to Experience as User** button
 4. Click on **People and Payroll** navigation element
 5. Under the **Forms and Resources** section - click the **Fill Out Form** link in the **Termination Request** field
 6. Here it is (see the below screenshot)
    ![image](https://github.com/user-attachments/assets/f3821a5a-7d2e-4dac-97ce-0ebcd5c64aa3)

 - **Steps to verify datatable**
 - Prep steps:

 1. Go to the Tides CRM LEX app
 2. Click Cases tab open a case record with **Project: Recurring Payment Request** record type
 3. Update the below case fields
 
   - Payment Type = EOM - Active
   - Employee Name = choose any contact record

 - Test steps:

 1. Go to the Tides CRM LEX app
 2. Click Contacts tab and open **Project Directorson** record
 3. Click on **Log in to Experience as User** button
 4. Click **People and Payroll** navigation element
 5. Under the **Forms and Resources** tab, click the "Fill Out Form" link of the **Termination Request** field in **Employee and Advisory Board Forms** section
 6. **Employee Name** lookup - choose the one that we also used on the case record in the prep steps above
 7. Click Next
 8. Here you can see the following two datatables

   - Change End of Month Payment End Dates - (we replaced this with ers_datatablecontroller code based table) - See the below screenshot
   - Cancel End of Month Payments - this is a OOB datatable (See the below screenshot)
  ![image](https://github.com/user-attachments/assets/12dc8817-69a3-46a3-8a55-7fecab9999d2)


### Expected Result


### TestClass Name / % of coverage (if applicable)
 
### Additional Information
- https://app.devstride.com/tenger-ways/items/I2648


