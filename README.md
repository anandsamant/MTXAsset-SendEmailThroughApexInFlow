# MTXAsset - Send Email Through Apex Invocable Method In Salesforce FlowsScenario : 

We want to send a Email to contact’s email address when contact record is created or updated with particular fields values.

# Conditions to trigger flow : 
1. Contact - Active Picklist field is ‘Yes’
2. Contact - Email Field is not NULL
3. Conatct - Send Email Checkbox field is True

# What we have to make to send email :
1. Record-Triggered Flow on Contact Object.
2. Email Template ( use contact’s merge Fields)
3. Apex Class with an Invocable method annotation which is then invoked by our flow.

