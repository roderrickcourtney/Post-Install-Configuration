<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This lab is part 2 to the "OsTicket-Prerequisites and Installation" lab<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments & Teams
- Allow Users to Create Tickets
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/FmvoAxO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/z2AQ9EF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/eBHmSbN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel up top that means you are currently the admin panel and vice versa) reference picture # 1. Click "agents" then "roles". Next click "add new role" to create a "super admin" whom can do every task since he/she will have all permissions and access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create "System Administrators department" & "level II Support team"). Please reference screenshots above.
</p>
<br />

<p>
<img src="https://imgur.com/qbqLOEx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to settings, Users, settings again and make sure the box titled "Require registration and login to create tickets" is unchecked. This is will allow everyone access to make tickets without restrictions. 
</p>
<br />

<p>
<img src="https://imgur.com/cBXIjCJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://imgur.com/AJRxGyZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/plHrj8I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create two test agents ("John Doe" and "Jane Doe"). Assign John to "System Administrators" department with "Super administrator" permission level & added her to Level II support team, all of these options are located under the access & Teams tabs on the same agent screen. Next add "Jane Doe" the same way as previously completed for John. Please reference pictures above in order.
</p>
<br />

<p>
<img src="https://imgur.com/8Eu5ZBn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step you will configure how customers and employees use the ticketing system software. Go to the "agent panel" by clicking the "admin panel" up top. Next click the "Users" tab then "create new user" button. Create two new generic users ("Jerry" and "Kim") with email addresses. Any name or email combonation is fine since these are just test accounts. 
</p>
<br />

<p>
<img src="https://imgur.com/axEMi5X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next a Service Level Agreement (SLA) needs to be created. Here are the layouts: "Sevice Level I" - helpdesk tickets must be responded to within 1 hour on a 24/7 schedule. "Service Level II" - within 4 hours on a 24/7 schedule. "Service level III"- within 8 hours on a regular business hour time frame. Go to admin panel -> manage -> SLA to create these stipulations. 
</p>
<br />

<p>
<img src="https://imgur.com/DKVAXHN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/qifHwMA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The last step is to configure help topics. In this step you will create the help ticket names in OsTicketing for users to select when they're having specific issues.  The tickets will also need to be assigned to a department along with a SLA priority. You can even auto-assign that particular help desk ticket topic to a group like Support level I or level II depending on the severity. Ex: "Network Outage" with priority level "High" with "Service level I" SLA plan sent to the "System Administrators" group and auto-assigned to the "support team" or to an individual agent like John or Jane. This concludeds how to setup help desk support tickets from the admin level post Installation. 
