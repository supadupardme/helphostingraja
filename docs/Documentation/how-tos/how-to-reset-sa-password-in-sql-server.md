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
    <span style={{fontSize: "24pt", color: "#000000"}}>How to Reset SA Password in SQL Server</span><span style={{fontSize: "24pt", color: "#000000"}}>:</span><br /><br /><br />
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Log in to your VPS via Remote Desktop. Please refer to how to reset password in windows VPS using RDP for more details.</span></p>
     
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}> 1. Please login your rdp </span></p>
     
    <p><span style={{fontWeight: 400}}><span style={{fontSize: "14pt"}}>2. Open SQL Server Management Studio.</span><br /><br /></span></p>
      <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>4. The Connect to Server dialog opens. Select Windows Authentication and select </span><span style={{fontWeight: 400}}>Connect</span><span style={{fontWeight: 400}}> to log into the server dashboard.</span></span><br />
    <br /><br /> <span style={{fontWeight: 400, fontSize: "14pt"}}>5. The Object Explorer opens. The SQL Server Instance name opens and several options should expand below it. If the list doesn’t expand, click on the [+] icon to expand it.</span><br />
    <div></div> <br /><span style={{fontWeight: 400, fontSize: "14pt"}}>6. Click on the [+] beside Security to expand the folder.</span><br />
    <div></div> <br /><span style={{fontWeight: 400, fontSize: "14pt"}}>7. Click on the [+] beside Logins to expand the folder.</span><br />
    <div><br /></div> <br /><br /><span style={{fontWeight: 400, fontSize: "14pt"}}>8. Double-click on the user login; `[sa]`. The properties window for the login `[sa]` opens.</span><br />
    <div><br /></div>
      <span style={{fontSize: "14pt"}}><strong>9. Enter the new password and enter again to confirm. Note that the deSfault password used in the original install is `[RPSsql12345]`.</strong></span><br /><span style={{fontWeight: 400, fontSize: "14pt"}}> <br /><strong>10.Press OK.</strong></span><br />
    <span style={{fontWeight: 400, fontSize: "14pt"}}>11. Disconnect from the database instance.</span>
    <p><span style={{fontSize: "14pt"}}>12. Reconnect to the database instance using the SQL Server Authentication, the user name SA, and the new password.</span></p>
    <p> </p>
    <div style={{textAlign: "center"}}><span style={{fontSize: "14pt"}}><strong>NOTE: once reset the password if it's not working, please restart the SQL Server and check</strong></span></div>
     
</div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>