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
    <h2 style="text-align: center;"><span style="font-size: 24pt;"><b><br />Add A, MX, And Nameservers Records To DNS Zone:<br /><br /><br /></b></span></h2>
    <h3><span style="font-size: 18pt; color: #000000;">A Records:</span></h3>
    <ol>
        <li><span style="font-weight: 400; font-size: 12pt;"> In order to add A records to DNS Zone, right-click on the DNS Zone name and select New Host (A or AAAA). A specifies that you are adding an IP version 4 (IPv4) host resource record type of the record. AAAA specifies that you are adding an IP version 6 (IPv6)host resource record type of the record.</span></li>
    </ol>
    <div><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-add-a-records.webp" /></div> <br />
    <ol start="2">
        <li><span style="font-weight: 400; font-size: 14pt;"> In New Host Window, enter the name of the record (If you keep it blank, it will use the parent domain).</span></li>
    </ol>
    <div><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-new-host-Window.webp" /></div> <br />
    <ol start="3">
        <li><span style="font-size: 14pt;"><span style="font-weight: 400;"> Enter the IP address of your server name. If you check the checkbox </span><i><span style="font-weight: 400;">Create Associated pointer (PTR) Record</span></i><span style="font-weight: 400;"> and click Add Host, you may receive a dialog box that appears with the message </span><i><span style="font-weight: 400;">You can only create PTR records if the corresponding reverse lookup zone is available</span></i><span style="font-weight: 400;">. This error indicates that you have not created a corresponding reverse lookup zone, created with an incorrect zone name or network ID.</span><span style="font-weight: 400;"><br /></span></span><span style="font-weight: 400;"><br /></span><span style="font-size: 14pt;"><span style="font-weight: 400;">In some cases, ISP or </span><a href="https://www.accuwebhosting.com/web-hosting"><i><span style="font-weight: 400;">Web Hosting</span></i></a><span style="font-weight: 400;"> providers do not allow the end customers to add a reverse lookup zone. In such cases, even if you add a reverse lookup zone, it would not get into effect until your ISP/</span><i><span style="font-weight: 400;">Web Hosting</span></i><span style="font-weight: 400;"> providers add them at the main DNS Zone. By checking this option, A record will be created without creating a corresponding PTR record. By following the steps, you need to add the following A records.</span></span><span style="font-weight: 400;"><br /><br /></span></li>
    </ol>
    <ul>
        <li style="font-weight: 400;"><span style="font-size: 14pt;"><span style="font-weight: 400;">*.........(*.yourdomainname</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">com)...........Host-IP-Address</span></span></li>
        <li style="font-weight: 400;"><span style="font-size: 14pt;"><span style="font-weight: 400;">FTP......(FTP.yourdomainname</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">com)........Host-IP-Address</span></span></li>
        <li style="font-weight: 400;"><span style="font-size: 14pt;"><span style="font-weight: 400;">WWW</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">..(WWW</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">yourdomainname</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">com).</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">..Host-IP-Address</span></span></li>
        <li style="font-weight: 400;"><span style="font-size: 14pt;"><span style="font-weight: 400;">Mail......(Mail.yourdomainname</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">com).......Host-IP-Address</span></span></li>
    </ul> <span style="font-weight: 400;"><span style="font-weight: 400;"><span style="font-size: 12pt;"><strong>4. To edit/delete existing records, select the DNS record your wish to edit/delete and right-click on it. Click the Delete button to delete it and the Properties button to edit it.</strong></span><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-edit-records.webp" /></span></span>
    <h3><span style="font-size: 18pt; color: #000000;"><strong>MX Record:</strong></span></h3>
    <ol>
        <li><span style="font-weight: 400; font-size: 14pt;"> In order to add MX records to DNS Zone, right-click on the Zone name and select New Mail Exchanger (MX) record.</span></li>
    </ol>
    <div><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-mx-records.webp" /><span style="font-weight: 400;"><br /></span></div>
    <p style="text-align: left;"><span style="font-size: 24pt;"><b><br /><span style="font-size: 10pt;"><span style="font-size: 14pt;"><span style="font-weight: 400;">2. Keep the Host or Child Domain field blank. Enter the Fully Qualified Domain Name (mail</span><i><span style="font-weight: 400;">.</span></i><span style="font-weight: 400;">yourdomainname</span><i><span style="font-weight: 400;">.</span></i></span><span style="font-weight: 400;"><span style="font-size: 14pt;">com) of the mail server and set priority ( 0 = Highest priority ). Similarly, you can also add CNAME and other new records.</span><br /><br /><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-cname-records.webp" /><br /><br /></span></span></b></span></p>
    <h3><b><span style="font-size: 18pt; color: #000000;">Update Nameservers:</span><br /><br /></b></h3>
    <ol>
        <li><span style="font-size: 14pt;"><span style="font-weight: 400;"> Double-click on Zone name, and Click on Name Server (NS) type.</span><span style="font-weight: 400;"><br /></span></span><span style="font-weight: 400;"><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-ns-records.webp" /><br /></span><span style="font-weight: 400;"><br /></span><span style="font-size: 14pt;"><span style="font-weight: 400;">2. Select the Name Server tab. Select "Fully Qualified Domain name" and click on Edit.</span><span style="font-weight: 400;"><br /></span></span><span style="font-weight: 400;"><br /><br /><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/dns-zone-edit-ns-records.webp" /><br /></span><span style="font-weight: 400;"><br /></span><span style="font-weight: 400; font-size: 14pt;">3. Enter your desired nameservers and add an IP address. Repeat the above steps for other nameservers. Please note that you can use the same or different IP address for both nameservers. If your domain registrar is giving an error of the same IP address, then you have to purchase an additional IP address.</span></li>
    </ol>  
    <h3> </h3>  
    <h2 style="text-align: left;"><span style="font-size: 24pt;"><b> </b></span></h2></div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to Reset SA Password in SQL Server" aria-label="Previous article: How to Reset SA Password in SQL Server" href="/docs/how-to-reset-sa-password-in-sql-server" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How To Add A New DNS Zone And Manage DNS Records For A Domain Hosted On Windows VPS in RDP" aria-label="Next article: How To Add A New DNS Zone And Manage DNS Records For A Domain Hosted On Windows VPS in RDP" href="/docs/how-to-add-a-new-dns-zone-and-manage-dns-records-for-a-domain-hosted-on-windows-vps-in-rdp" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>
