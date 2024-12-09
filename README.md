# Clone User in Salesforce via Flow 

In Salesforce, there isn’t a direct out-of-the-box feature to clone a user, which can be a time-consuming task if you need to create a new user with similar attributes to an existing one. Fortunately, Salesforce Flows can be leveraged to automate this process and save time by replicating user details efficiently.

  <p align="center" dir="auto">
    <a href="https://www.youtube.com/watch?v=RHanLdoOQhg" rel="nofollow">
      <img src="https://camo.githubusercontent.com/3c3917ecdd25528d0a4a4f408fcba200335a13e640c3256258e63f65f5238526/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2532305669657725323044656d6f2d626c75653f7374796c653d666c61742d737175617265266c6f676f3d796f7574756265" alt="View Demo" data-canonical-src="https://img.shields.io/badge/%20View%20Demo-blue?style=flat-square&amp;logo=youtube" style="max-width: 100%;">
    </a>
  </p>


## How to Deploy this Flow to your Sandbox with 3 clicks !

<div align="center" dir="auto">
  <a href="https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5e0000012JBP" rel="nofollow">
    <img src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png" alt="Deploy to Salesforce" style="max-width: 100%;">
  </a>
</div>

Click on above button, login to your org, on Installation screen,  Select **Install for Admins Only** & Click on Install.  
After Installation, In your Org, you should see a new flow called 'Clone User via Screen Flow'  and new custom Link Button called 'Clone This User' on user object.  
Add this custom button on, user Page layout under Custom Link Section to make it visible on user record detail page.

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


