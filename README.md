# Clone User in Salesforce via Flow 

In Salesforce, there isn’t a direct out-of-the-box feature to clone a user, which can be a time-consuming task if you need to create a new user with similar attributes to an existing one. Fortunately, Salesforce Flows can be leveraged to automate this process and save time by replicating user details efficiently.

## How to Deploy this Flow to your Sandbox with 3 clicks !

<a href="https://githubsfdeploy.herokuapp.com?owner=phlakhani&repo=Clone-User-via-Flow">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

Clicking on above button, will take you to Salesforce github Deploy tool, Select which kind of org you want this flow to be deployed and Login to your selected org. After authorization,  Click on **'Deploy'** button on Top Right.  

## **Solution & Understanding the Flow**

I’ve created a custom **Flow** to solve this challenge. This flow automates the process of duplicating an existing user's details and creating a new user with the similar configuration. 

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

**This screen flow is being invoked from User record detail page via Custom Link Button called 'Clone This user'**

**Read Full Article here  [How to Clone User via Flow by SalesforceFox](https://salesforcefox.com/how-to-clone-a-user-in-salesforce-deploy-solution-in-your-sandbox/) , In order to understand Flow Implementation.** 


