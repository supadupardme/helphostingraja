---
title: How to find DNS nameserver from whm panel
excerpt: >-
  Make panel changes much easier by learning how to find, manage and configure
  nameservers and DNS records from the panel.
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
    <h1 style="text-align: center;"><span style="font-size: xx-large;"><strong>How to find DNS nameserver from whm panel</strong></span></h1>
    <div><span id="docs-internal-guid-cecdf0a4-de27-5366-f2ca-2dd4f55980c2"><br /></span>
        <p><span style="font-weight: 400; font-size: 14pt;">In this page, we will discuss how to find nameserver from the WHM panel. Before that let us understand what is Nameserver.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">A nameserver is a component of DNS(domain name system) which allows the website to be browsed by its domain name instead of its IP address. When we type the domain name in the browser the nameserver will translate the domain into its corresponding IP address </span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">For example, when you type the Domain name “Abxy.com” in the browser, there will be a request sent to domain’s Nameserver and will return the IP address of the domain, this IP address is used by the browser to fetch the website. Every website will have at least two nameservers, the general format of the nameserver will be ns1.nameofserver.in and ns2.nameofserver.in where nameofserver will be the name of the server. And generally, ns1.nameofserver.in (the first nameserver ) will be the primary server and ns2.nameofserver.in (the second nameserver) will be the backup server when the first nameserver is not responding. The nameservers are used to translate the domain name into IP address as IP address are hard for us to remember.<br /><br /><img src="https://image.hostingraja.in/images/helphostingraja/find-dns-nameserver1.webp" /><br /></span></p>
        <p><span style="font-size: 14pt;"><b>Step to find nameserver details in your WHM panel:</b></span></p> <br />
        <p><span style="font-size: 14pt;"><b>Step 1:</b><span style="font-weight: 400;"> Log in to the server using the WHM username and password through</span></span></p>
        <p><span style="font-size: 14pt;"><span style="font-weight: 400;">If The </span><a href="https://www.hostingraja.in/domains/"><span style="font-weight: 400;">Domain</span></a><span style="font-weight: 400;"> is not propagated you can use with </span><b>https://yourserverip:2087</b></span></p>
        <p><span style="font-size: 14pt;"><span style="font-weight: 400;">If The Domain is propagated you can use with </span><b>http://yourdomainname:2087</b></span></p> <br />
        <p><span style="font-size: 14pt;"><b>Step 2:</b><span style="font-weight: 400;"> After you login into your WHM panel &gt;&gt; Click on DNS Functions as shown below:<br /><br /><img src="https://image.hostingraja.in/images/helphostingraja/whm-panel.webp" width="775" height="472" /><br /></span></span></p> <br />
        <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 3</strong>: After you click on DNS function &gt;&gt; Click on Edit DNS Zone as shown below<br /><br /><img src="https://image.hostingraja.in/images/helphostingraja/find-dns-nameserver3.webp" width="758" height="259" /><br /></span></p> <br />
        <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 4</strong>: After you click on Edit DNS Zone &gt;&gt; Select the domain name for which you need nameserver, and then click Edit as shown<br /><br /><img src="https://image.hostingraja.in/images/helphostingraja/find-dns-nameserver4.webp" width="531" height="511" /><br /></span></p> <br />
        <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 5</strong>: you can see the nameserver details in the menu. For editing the nameserver details you can do it by clicking on edit on the next to the nameserver, example : For the two lines with the menu showcasing NS(nameserver details), click on edit the right-most columns to ns1.yourdomainname.com and ns2.your domain name.com which Has to be edited .</span></p> <br />
        <p><span style="font-weight: 400; font-size: 14pt;">Follow the above steps to find the nameservers in WHM panel. You can add the nameservers as shown below </span></p> <br /><br />
        <p><span style="font-size: 14pt;"><b><span style="font-size: 18pt;">To Add New Records nameserver record</span> </b></span></p>
        <p dir="ltr"> </p>
        <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 1</strong>: You can add new record in the below the Path section, fill the following appropriately </span></p>
        <p dir="ltr"> </p>
        <p><span style="font-size: 14pt;"><b>First field:</b><span style="font-weight: 400;"> Nameserver details or record which has to be updated eg: ns1.domainname.com</span></span></p>
        <p><span style="font-size: 14pt;"><b>Second field:</b><span style="font-weight: 400;"> TTL(time to live - this value in IP packet which tell network router if or not the packet is there in the network and it should be discarded ) eg:14400</span></span></p>
        <p><span style="font-size: 14pt;"><b>Third field: </b><span style="font-weight: 400;">Record type which added eg: Select A Record</span></span></p>
        <p><span style="font-size: 14pt;"><b>Fourth field:</b><span style="font-weight: 400;"> IP address(Enter your server's IP address)</span></span></p>
        <p dir="ltr"><br /><img src="https://image.hostingraja.in/images/helphostingraja/find-dns-nameserver5.webp" width="748" height="140" /><br /> </p>
        <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 2</strong>: After you fill the appropriate details &gt;&gt; Click on Save.</span></p>
        <p><span style="font-size: 14pt;"><b>Note: </b></span><b style="font-size: 14pt;">After you update the nameservers it will take 24-48 hours for the nameserver to reflect globally. The time taken for the nameserver to reflect globally is called DNS propagation time </b></p>
        <p><span style="font-size: 14pt;"><b>If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call, chat, <a href="https://support.hostingraja.in/" target="_blank" rel="noopener noreferrer">ticket system</a>. We will be happy to help you.</b></span></p>
    </div>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How To Add And Edit Text In HostingRaja Site Builder?" aria-label="Previous article: How To Add And Edit Text In HostingRaja Site Builder?" href="/how-tos/how-to-add-and-edit-text-in-hostingraja-site-builder" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to Host a Website in Windows?" aria-label="Next article: How to Host a Website in Windows?" href="/how-tos/how-to-host-a-website-in-windows" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>
