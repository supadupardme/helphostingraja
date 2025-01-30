---
title: How to Reset SA Password in SQL Server
excerpt: Best Linux, Windows, Unlimited plans wirh 55% OFFER
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
<div itemprop="articleBody">
    <h1 style="text-align: center;"><span style="font-size: 24pt; color: #000000;"><a style="color: #000000;" href="https://www.wikihow.com/Reset-SA-Password-in-SQL-Server"><b>How to Reset SA Password in SQL Server</b></a></span><b><span style="font-size: 24pt; color: #000000;">:</span><br /><br /><br /></b></h1>
    <p><span style="font-weight: 400; font-size: 14pt;">Log in to your VPS via Remote Desktop. Please refer to how to reset password in<a href="https://www.hostingraja.in/server/vps-servers/windows-vps-servers/"><b> windows VPS</b></a> using RDP for more details.</span></p>
    <h1><b> </b></h1>
    <p><span style="font-weight: 400; font-size: 14pt;"> 1. Please login your rdp </span></p>
    <h1><b> </b></h1>
    <p><span style="font-weight: 400;"><span style="font-size: 14pt;">2. Open SQL Server Management Studio.</span><br /><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/sql-server-management-studio.webp" /></span></p>
    <h1><b> </b></h1> <span style="font-size: 14pt;"><span style="font-weight: 400;">4. The Connect to Server dialog opens. Select Windows Authentication and select </span><i><span style="font-weight: 400;">Connect</span></i><span style="font-weight: 400;"> to log into the server dashboard.</span></span><br />
    <h1><b><br /><br /></b></h1> <span style="font-weight: 400; font-size: 14pt;">5. The Object Explorer opens. The SQL Server Instance name opens and several options should expand below it. If the list doesn’t expand, click on the [+] icon to expand it.</span><br />
    <div><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/sql-instance-name.webp" /></div> <br /><span style="font-weight: 400; font-size: 14pt;">6. Click on the [+] beside Security to expand the folder.</span><br />
    <div><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/sql-security-expand.webp" /></div> <br /><span style="font-weight: 400; font-size: 14pt;">7. Click on the [+] beside Logins to expand the folder.</span><br />
    <div><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/sql-expand-folder.webp" /></div> <br /><br /><span style="font-weight: 400; font-size: 14pt;">8. Double-click on the user login; [sa]. The properties window for the login [sa] opens.</span><br />
    <div><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/sql-properties-windows.webp" /></div>
    <h1><b> </b></h1> <span style="font-size: 14pt;"><strong>9. Enter the new password and enter again to confirm. Note that the deSfault password used in the original install is [RPSsql12345].</strong></span><br /><span style="font-weight: 400; font-size: 14pt;"> <br /><strong>10.Press OK.</strong></span><br />
    <h2><span style="font-weight: 400; font-size: 14pt;">11. Disconnect from the database instance.</span></h2>
    <p><span style="font-size: 14pt;"><b>12. Reconnect to the database instance using the </b><b><i>SQL Server Authentication</i></b><b>, the user name SA, and the new password.</b></span></p>
    <p> </p>
    <div style="text-align: center;"><span style="font-size: 14pt;"><strong>NOTE: once reset the password if it's not working, please restart the SQL Server and check</strong></span></div>
    <h1> </h1>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to Create SQL Database  " aria-label="Previous article: How to Create SQL Database  " href="/docs/how-to-create-sql-database" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to Add A, MX, And Nameservers Records To DNS Zone" aria-label="Next article: How to Add A, MX, And Nameservers Records To DNS Zone" href="/docs/how-to-add-a-mx-and-nameservers-records-to-dns-zone" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>