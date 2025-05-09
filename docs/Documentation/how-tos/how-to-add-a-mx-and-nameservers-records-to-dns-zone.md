---
title: How to Add A, MX, And Nameservers Records To DNS Zone
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
    <span style={{fontSize: "24pt"}}><br />Add A, MX, And Nameservers Records To DNS Zone:<br /><br /><br /></span>
    <span style={{fontSize: "18pt", color: "#000000"}}>A Records:</span>
    
        <span style={{fontWeight: 400, fontSize: "12pt"}}> In order to add A records to DNS Zone, right-click on the DNS Zone name and select New Host (A or AAAA). A specifies that you are adding an IP version 4 (IPv4) host resource record type of the record. AAAA specifies that you are adding an IP version 6 (IPv6)host resource record type of the record.</span>
    
    <div></div> <br />
    
        <span style={{fontWeight: 400, fontSize: "14pt"}}> In New Host Window, enter the name of the record (If you keep it blank, it will use the parent domain).</span>
    
    <div></div> <br />
    
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}> Enter the IP address of your server name. If you check the checkbox </span><span style={{fontWeight: 400}}>Create Associated pointer (PTR) Record</span><span style={{fontWeight: 400}}> and click Add Host, you may receive a dialog box that appears with the message </span><span style={{fontWeight: 400}}>You can only create PTR records if the corresponding reverse lookup zone is available</span><span style={{fontWeight: 400}}>. This error indicates that you have not created a corresponding reverse lookup zone, created with an incorrect zone name or network ID.</span><span style={{fontWeight: 400}}><br /></span></span><span style={{fontWeight: 400}}><br /></span><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>In some cases, ISP or </span><span style={{fontWeight: 400}}>Web Hosting</span><span style={{fontWeight: 400}}> providers do not allow the end customers to add a reverse lookup zone. In such cases, even if you add a reverse lookup zone, it would not get into effect until your ISP/</span><span style={{fontWeight: 400}}>Web Hosting</span><span style={{fontWeight: 400}}> providers add them at the main DNS Zone. By checking this option, A record will be created without creating a corresponding PTR record. By following the steps, you need to add the following A records.</span></span><span style={{fontWeight: 400}}><br /><br /></span>
    
    
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>*.........(*.yourdomainname</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>com)...........Host-IP-Address</span></span>
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>FTP......(FTP.yourdomainname</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>com)........Host-IP-Address</span></span>
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>WWW</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>..(WWW</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>yourdomainname</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>com).</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>..Host-IP-Address</span></span>
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Mail......(Mail.yourdomainname</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>com).......Host-IP-Address</span></span>
     <span style={{fontWeight: 400}}><span style={{fontWeight: 400}}><span style={{fontSize: "12pt"}}><strong>4. To edit/delete existing records, select the DNS record your wish to edit/delete and right-click on it. Click the Delete button to delete it and the Properties button to edit it.</strong></span><br /></span></span>
    <span style={{fontSize: "18pt", color: "#000000"}}><strong>MX Record:</strong></span>
    
        <span style={{fontWeight: 400, fontSize: "14pt"}}> In order to add MX records to DNS Zone, right-click on the Zone name and select New Mail Exchanger (MX) record.</span>
    
    <div><span style={{fontWeight: 400}}><br /></span></div>
    <p style={{textAlign: "left"}}><span style={{fontSize: "24pt"}}><br /><span style={{fontSize: "10pt"}}><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>2. Keep the Host or Child Domain field blank. Enter the Fully Qualified Domain Name (mail</span><span style={{fontWeight: 400}}>.</span><span style={{fontWeight: 400}}>yourdomainname</span><span style={{fontWeight: 400}}>.</span></span><span style={{fontWeight: 400}}><span style={{fontSize: "14pt"}}>com) of the mail server and set priority ( 0 = Highest priority ). Similarly, you can also add CNAME and other new records.</span><br /><br /><br /><br /><br /></span></span></span></p>
    <span style={{fontSize: "18pt", color: "#000000"}}>Update Nameservers:</span><br /><br />
    
        <span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}> Double-click on Zone name, and Click on Name Server (NS) type.</span><span style={{fontWeight: 400}}><br /></span></span><span style={{fontWeight: 400}}><br /><br /></span><span style={{fontWeight: 400}}><br /></span><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>2. Select the Name Server tab. Select "Fully Qualified Domain name" and click on Edit.</span><span style={{fontWeight: 400}}><br /></span></span><span style={{fontWeight: 400}}><br /><br /><br /></span><span style={{fontWeight: 400}}><br /></span><span style={{fontWeight: 400, fontSize: "14pt"}}>3. Enter your desired nameservers and add an IP address. Repeat the above steps for other nameservers. Please note that you can use the same or different IP address for both nameservers. If your domain registrar is giving an error of the same IP address, then you have to purchase an additional IP address.</span>
      
       
    <span style={{fontSize: "24pt"}}> </span></div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>