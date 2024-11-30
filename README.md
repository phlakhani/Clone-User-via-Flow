# Clone User in Salesforce via Flow 

In Salesforce, there isn’t a direct out-of-the-box feature to clone a user, which can be a time-consuming task if you need to create a new user with similar attributes to an existing one. Fortunately, Salesforce Flows can be leveraged to automate this process and save time by replicating user details efficiently.

## How to Deploy this Flow to your Org

<a href="https://githubsfdeploy.herokuapp.com?owner=phlakhani&repo=Clone-User-via-Flow" target="_blank">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

Click on below button, 

## **Solution & Understanding the Flow**

I’ve created a custom **Flow** to solve this challenge. This flow automates the process of duplicating an existing user's details and creating a new user with the same or similar configuration. 

The flow takes care of copying key fields such as:

- Profile
- Title
- Role
- Time Zone
- Locale
- Langauge
- Company
- Department
- Division

User can also select to copy : 
- Manager
- Permission Set & Permisision Group
- Permission Set License Assignment
- Public Groups & Queue Membership

**This screen flow is being invoked from User record detail's  via Custom Link Button 'Clone this user'**


