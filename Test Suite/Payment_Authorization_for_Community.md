# Payment_Authorization_for_Community

### Usage

### Test Steps

 1. Go to Setup and search Flow in quick find and click Flows
 2. Open Payment_Authorization_for_Community Flow and Click Debug
 3. Select a Funding Allocation Record that meets the following criteria
 
 - Has a lookup with Money Out
 - The parent Money Out has minimum 2 other Funding Allocations which must be approved or rejected
 
 4. Select the Payment record that is linked with your Funding Allocation selected in step 2 and add the Payment record id in recordId variable
 5. Click Run
 6. Select **Payment Updates Requested** in the **Payment Authorization** and click next
 7. Add any text in the Partner Authorization Instructions and click Next
 8. Select a Funding Allocation and click the **Edit Selected Funding Allocation** button
 9. Verify that there is 5 lookup of Funding Allocation and change the all or more then one lookup and click next

### Expected Result
- Funding Allocation record is updated in Step 8 visible datatable

### TestClass Name / % of coverage (if applicable)
 
### Additional Information

