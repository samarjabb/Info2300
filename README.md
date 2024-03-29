# Info2300A3

Game Store Website
About the website
The proposed project is aimed at creating an online game-selling website that offers users a variety of features to enhance their gaming experience. Users can browse and choose their favorite games from a wide selection of options, add them to their shopping cart, and easily purchase and download them using various payment methods. Once users have downloaded a game, they can review and rate it to help other users make informed decisions. Users can also choose their favorite gaming platforms and select preferred game categories to quickly find games that match their preferences. In addition to these features, the website provides membership management options, including a joining feature for visitors, the ability to add friends and family members to a list and view their wish lists, and the option to register for events. Members can also share their wish lists through one social media network.
To ensure an optimal user experience, the system's objectives include a less than 2-second response time for all transactions, a forget password link that sends an email in under 1-minute, user-friendly error messages, and automatic saving of content when the window is unexpectedly turned off. The project's critical success factors include completing work on time, good communication among team members, and a clear understanding of the project's purpose and goal. The preliminary technical architecture of the system includes C#, the .NET Framework, and a Microsoft SQL database server. Overall, the proposed online game-selling website provides a comprehensive solution for gamers who want to easily find, purchase, and download their favorite games. With its user-friendly interface, robust feature set, and a wide selection of games, the website is poised to become a popular destination for gaming enthusiasts around the world.

Quick Start

This website requires a server that uses Windows and has Microsoft SQL Server 2005 and Internet Information Services (IIS) installed on it. It will also require an administrator user of the Windows operating system to run the database scripts and install the package into IIS. This server should be always on to allow for constant access to the website.  

How to Create the Database
 
To create the application database on a server computer that already has Microsoft SQL Server 2005 installed on it, follow instruction bellow.
1.	Locate the database scripts folder
2.	Right click the powershell script setup.ps1, and click Run with Powershell.
Notes:
This script expects two inputs: name of the SQL server and the full path directory of the create scripts folder. It will prompt you for them.
The script uses Windows Authentication to connect to the SQL server. Ensure that your windows user has permission to connect to the SQL server and run the script as administrator.
 
How to Install and Configure the Web Site

Instructions to deploy the website on a server computer that has IIS installed on it:
1.	Open the IIS Manager from Windows Menu
2.	Right click on sites in IIS, then add new website. A new dialogue should appear.
3.	Under Site name, fill in the form with your site name.
4.	Click the select.. button near the Application Pool field and choose the DefaultAppPool
5.	Click on the … button next to the Physical path field and select the folder of the published site code we provided
6.	Under host name, add a host name for the website. 
7.	Choose a Port for the application to use (we recommend Port 80 as default).
8.	Everything else can remain as default in this dialogue. Click OK to create.
9.	You should be able to navigate to the website using a browser now. 
 
To access the web site with a browser.
1.	Open a browser and go to the hostname that your provided in the previous section.



