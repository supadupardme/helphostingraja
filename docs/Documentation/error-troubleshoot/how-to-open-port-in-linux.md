---
title: How to Open Port in Linux
excerpt: >-
  Learn how to safely open ports on your Linux server's firewall for improved
  network access
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---

<div class="page-header">

How to Open Port in Linux ? 
</div>

<span class="icon-calendar" aria-hidden="true"></span>

Last Updated: 20 August 2021 

<div itemprop="articleBody">
<strong>How to Open Port in Linux</strong>
What is Port?
<p dir="ltr">Port numbers are associated with TCP/IP network connections. A port number is a way to identify a specific process to which an Internet or other network message is to be forwarded when it arrives at a server. They allow different applications on the same computer to share network resources simultaneously. Home network routers and computer software work with these ports and sometimes support configuring port number settings.</p>
How Does Port Numbers Work?
<p dir="ltr">Port numbers relate to network addressing. In TCP/IP networking, both TCP and UDP utilize their own set of ports that work together with IP addresses.</p>
<p>In both TCP and UDP, port numbers start at 0 and go up to 65535. Numbers in the lower ranges are dedicated to common Internet protocols (like port 80 for HTTP and port 443 for HTTPS).</p>
To open a port in Linux Firewall
<p dir="ltr">This article will be showing you how to open ports in your Linux Web Hosting India servers firewall. This can be very useful, and also dangerous, so be sure you know what port you want to open up. Hackers can use these open ports to gain unauthorized access to your Linux VPS server, so be careful!</p>
<p> </p>
<p><strong>STEP1: Login SSH into your server as Root</strong></p>
<p><strong><br /><br /></strong>  <br /><br /><strong>STEP2: </strong>Get to the directory where the configuration file is for CSF</p>
<p><strong><br />cd /etc/</strong>csf</p>
<p dir="ltr"> </p>
<p dir="ltr">This is where CSF keeps all of its files, not just the configuration file.</p>
<p></p>
<p>Open the configuration file so that we can edit it. Something like "Vim" or vi editor vim csf.conf or vi csf.conf</p>
<p dir="ltr"><strong>Find TCP_IN Line on the file csf.conf</strong></p>
<p dir="ltr"> </p>
<p dir="ltr"></p>
<p> </p>
<p>Once you have the file open, you will see a "TCP_IN" and "TCP_OUT" section. It will look like this:</p>
Allow incoming TCP ports
<p>TCP_IN = "20,21,1122, 25, 26, 53, 80, 110, 143, 443, 465, 587, 993, 995, 2077, 2078, 2082, 2083, 2086, 2087, 2095, 2096, 8010"</p>
<p><br /><br /></p>
Allow incoming TCP ports
<p>TCP_IN = "20,21,1122, 25, 26, 53, 80, 110, 143, 443, 465, 587, 993, 995, 2077, 2078, 2082, 2083, 2086, 2087, 2095, 2096, 8010" <br /><br /> <br /><br />All those numbers there are ports that are currently "open". Yours may look different so don't panic! It all depends on your configuration.<br /><br />  <br /><br /><strong>Save and get out of this file (:wq!)</strong> <strong>Restart the firewall so that your changes take effect!</strong> <strong>csf -r</strong> <br /><br /> <strong>Stopping CSF</strong> <strong>csf -x</strong></p>
<p><strong> </strong></p>
<p><strong>Related Open Port other Panel:</strong></p>
<p>Refer the below links for Port Plesk Panel,</p>
<p>https://help.hostingraja.in/other-help/how-to-block-and-allow-port-in-windows-server</p>
<p>Refer the below links for Port Cpanel Panel,</p>
<p>https://help.hostingraja.in/how-tos/how-to-enable-disable-firewall</p> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>