# Deliver_Payment_is_Paid_Notification

### Usage

### Test Steps
 1. In app launcher search Payment and click Payments
 2. Open a record and update the below fields
 - Paid Date = Today's date
 - Payment is Paid Delivery List Generated = checked
 - Payment Paid Notifications Sent = unchecked
 - Payment is Paid Notifications List = write your email
 - Payment is Paid BCC Notification List = write email to add in BCC
 - Payment is Paid CC Notification List = write email to add in CC
 - Click Save

 3. Now let's call this auto-launch flow
    Note. first find the way to set the record id on run the flow
    - Click Gear icon and Click Setup
    - In quick find search Flow and Click Flows
    - Click Deliver_Payment_is_Paid_Notification flow
    - Click Run

### Expected Result
- Subject line of email is **Tides Grant Installment Payment Notice - Fund for the City of New York Inc - TC1434-17-04223**

### TestClass Name / % of coverage (if applicable)
 
### Additional Information
- https://app.devstride.com/tenger-ways/items/I2642

