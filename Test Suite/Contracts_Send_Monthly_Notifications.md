# Contracts_Send_Monthly_Notifications

### Usage

### Test Steps
 1. In app launcher search Contracts and Leases and click Contracts and Leases
 2. Open any existing record
 3. Update the below fields
   - Status = **Final Agreement Processing**
   - Service Start Date = remove the value, if any
   - Service End Date = Today's date
   - Amended End Date = Tomorrow's date
 4. Click Save
 5. Click the lookup link of ""Related Partner"" to open the partner record 
 6. Update the below field on partner
   - Contract Term Notification Sent Date = remove the value, if any
   - Advisor = choose yourself
   - Associate = choose yourself
 7. Click Save
 8. Now let's call this auto-launch flow
    Note. Open the flow and update change FirstofMonth (flow variables) to true during testing
 
 9. Click Gear icon and Click Setup
 10. In quick find search Flow and Click Flows
 11. Click Contracts_Send_Monthly_Notifications flow
 12. Click Run

### Expected Result
- Subject line of email is **Notification of Upcoming Contract Terminations - 1012 - Young Center for Immigrant Children's Rights**

### TestClass Name / % of coverage (if applicable)
 
### Additional Information
- https://app.devstride.com/tenger-ways/items/I2641

