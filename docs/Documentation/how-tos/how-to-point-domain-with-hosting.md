---
title: Domain hosting how to point domain with hosting
excerpt: >-
  Know how to connect a domain name with the hosting account. Information on
  connecting or pointing the domain which is in HostingRaja to another server.
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
    <p dir="ltr" style="text-align: center;"><span style="font-size: 24pt;"><strong>How to point Domain with Hosting</strong></span></p>
    <p> </p>
    <p><span style="font-weight: 400;">Pointing a domain name is a very simple task. </span><b>Once your domain name is registered, you need to connect it to your </b><strong><a title="hosting server" href="https://www.indianhostingprices.in/hostingraja-reviews/">hosting server</a></strong><b>.</b><span style="font-weight: 400;"> While registering a domain name with a hosting account (like in HostingRaja or switching to our hosting services), your domain name has to be pointed to your hosting account. And this process is known as delegation and it is easy to perform. </span></p>
    <p><span style="font-weight: 400;">While pointing the domain to the hosting, ‘A’ record and name servers play a major role in pointing your domain to the hosting, These A record and nameservers are components of DNS (Domain name system). </span></p>
    <p><span style="font-weight: 400;">A </span><b>nameserver</b><span style="font-weight: 400;"> of domain translates the domain names into IP address when entered the browser or in other words. A nameserver can be defined as a server Which stores the DNS records of a given domain name. Nameservers are part of DNS, which stands for </span><b>“Domain Name System</b><span style="font-weight: 400;">” which acts like a database that works like a phone book for computers: it converts a domain name into a machine-readable IP address. Example when you type “www.justanexample.com” in your browser it will be translated to a machine-readable IP address like “23.369.561.456”</span></p>
    <p><span style="font-weight: 400;">Every server has at least two nameservers, example ns1.name_of_server.com and ns2.name_of_server.com, The first<a href="/dns/name-server-details-of-hostingraja"><b> name server</b></a> (ns1.name_of_server.com) will be the primary server, and the second nameserver(ns2.name_of_server.com) will be the backup server for the primary server. </span></p>
    <p> </p>
    <p><img src="https://image.hostingraja.in/images/articles/aisa-help/connect-point-domain-in-hostingraja-to-another-server.png" width="509" height="452" /><br /><br /></p>
    <p><b>“A” Records</b><span style="font-weight: 400;"> is basically an address record, it translates the domain name to the IP address and determines which IP address belongs to a domain name. In other words, it maps the domain name to the IP address.</span></p>
    <p> </p>
    <p><b>Example of an A-record:</b></p>
    <p><b>Domain: www.justanexample.com</b></p>
    <p><b>Type: A record </b></p>
    <p><b>TTL: 3600 </b></p>
    <p><b>Points to (IP-address): 23.369.561.456</b></p>
    <p> </p>
    <p><span style="font-weight: 400;">TTL stands for time-to-live in seconds, it is the amount of time the record is allowed to be cached by a resolver.</span></p>
    <p><b>How do I connect or point the domain which is in HostingRaja to another server</b></p>
    <p><span style="font-weight: 400;">You might have purchased a domain from<a href="https://www.hostingraja.in/hosting/compare-hosting-plans/"><b> Hostingraja </b></a> and you might have a <a href="https://www.hostingraja.in/"><strong>web hosting</strong></a> from other company, In such cases you can to point your domain which is registered in HostingRaja to another hosting service, you can do this by two ways:</span></p>
    <p><b>By updating the nameservers: </b><span style="font-weight: 400;">If the Domain is purchased in hostingraja and you are hosting your domain in another server then you need to update the nameservers of the server of your hosting service in the HostingRaja’s domain provider panel in DNS Management.The steps to update the nameservers in HostingRaja’s domain control panel is discussed below </span></p>
    <p><b>By updating the “A” record: </b><span style="font-weight: 400;">Another way to point your domain is by updating the ‘A’ Record of the domain this can be done only if the nameserver of the domain are default nameservers of the domain provide are updated for the domain and you can update the server IP address of your hosting service as an “A” record in the “hostingraja” domain control panel in DNS Management.</span></p>
    <p> </p>
    <p><span style="font-weight: 400;">After the updation of the DNS, it will take 48 hours to propagate globally. </span></p>
    <p> </p>
    <p><span style="font-weight: 400;">These are the two ways to point your domain which is purchased from hostingraja to another server.</span></p>
    <p> </p>
    <p><span style="font-weight: 400;">When you have a domain which is registered with other domain provider and <a title="purchased the Domain with HostingRaja" href="https://www.webshosting.review/hostingraja-reviews">purchased the Domain with HostingRaja</a> then </span><b>there are two methods to point the domain name to HostingRaja:</b></p>
    <p> </p>
    <p><span style="font-weight: 400;">1) The first method is by </span><b>changing the nameservers at your domain name registrar.</b><span style="font-weight: 400;"> This particular approach is suggested as your DNS zone will be automatically configured. Pointing the domain name to HostingRaja nameservers will help in assisting the DNS zone at HostingRaja's control panel.</span></p>
    <p> </p>
    <p><span style="font-weight: 400;">2) The second method is by </span><b>pointing the domain name through an "A record".</b><span style="font-weight: 400;"> This procedure needs technical knowledge as you need to change the DNS records manually. And also, your DNS zone will not be automatically updated. Eg: If created a subdomain name in HostingRaja, then need to create a relevant "A record" in your DNS zone manually. </span></p>
    <p> </p>
    <p><b>If you want to point a domain with other hosting services to your Hostingraja hosting account then you need to follow below steps:</b></p>
    <ol>
        <li><span style="font-weight: 400;"> You have to update name-servers or A record for that domain in the domain control panel. You will get name-servers details from the Hosting provider.</span></li>
        <li><span style="font-weight: 400;"> Once name-servers has been updated you have to create addon domain under the hosting account and if it is your primary domain of our hosting then your domain will be added by default you don't need to add it as an &lt;a href="https://help.hostingraja.in/other-help/procedures-to-create-and-manage-addon-domains"&gt;&lt;b&gt;addon domain.&lt;/b&gt;&lt;/a&gt;</span></li>
    </ol>
    <p> </p>
    <p> </p>
    <p> </p>
    <p><b>How to update the nameserver for the domain with hosting</b></p>
    <p><span style="font-weight: 400;">You need to change the nameserver of your</span><a href="https://www.hostingraja.in/domains/"><span style="font-weight: 400;"> registrar domain name</span></a><span style="font-weight: 400;"> to ensure that, Your website is pointing to hosting server.</span></p>
    <p> </p>
    <p><b>If your domain registrar is Hostingraja then follow the below steps to update the nameservers:</b></p>
    <p><b>Steps to update nameservers in HostingRaja’s domain control panel:</b></p>
    <p><b>Step 1:</b><span style="font-weight: 400;"> Login to domain control panel using the Your Email ID and Password.</span></p>
    <p><b>Step 2:</b><span style="font-weight: 400;"> Once you log in, Click on the My Domain</span></p>
    <p> </p>
    <p><img src="https://image.hostingraja.in/images/article/help/domain-with-hosting1.png" width="603" height="376" /></p>
    <p><b><br />Step 3:</b><span style="font-weight: 400;"> Once you click My Domain You will get a list of domains and click on the Edit icon on the right side.</span></p>
    <p> <br /><img src="https://image.hostingraja.in/images/article/help/domain-with-hosting2.png" width="708" height="378" /><br /><br /></p>
    <p><b>Steps 4:</b><span style="font-weight: 400;"> Change the name server which you got from Hosting provider And after that click on the save button.</span></p>
    <p> </p>
    <p><b>Step to add the domain as Addon domain under the Hosting account</b></p>
    <p> </p>
    <p><b>Step 1:</b><span style="font-weight: 400;"> Login to cpanel.</span></p>
    <p><b>Step 2:</b><span style="font-weight: 400;"> Once you will log in to cpanel &gt;&gt; Kindly go to Domains section from there you will get Addon Domain options.<br /><br /><img src="https://image.hostingraja.in/images/article/help/domain-with-hosting3.png" /><br /><br /> </span></p>
    <p><b>Step 3:</b><span style="font-weight: 400;"> Click on Addon domain &gt;&gt; From there enter your domain name which has to be added.<br /><br /><img src="https://image.hostingraja.in/images/article/help/domain-with-hosting4.png" /><br /><br /> </span></p>
    <p><b>Step 4:</b><span style="font-weight: 400;"> Once you will fill the domain name &gt;&gt; After that click on Add domain name.</span></p>
    <p> </p>
    <p><b>Note: </b></p>
    <p><b>Any changes to the DNS Records it will take 24 -48 hours to get reflected or affected globally, this time taken for DNS record to get reflected is called as DNS propagation time </b></p>
    <p> </p>
    <p><b>You check if DNS is updated properly, by using the below links, this will let you know if you have updated the DNS properly:</b></p>
    <p><b>&gt;&gt;https://intodns.com</b></p>
    <p><b>&gt;&gt;https://mxtoolbox.com</b></p>
    <p> </p>
    <p><b>You can also check if the DNS propagation using :</b></p>
    <p><b>&gt;&gt;https://www.whatsmydns.net/ </b></p>
    <p><br /><br /></p>
    <p><span style="font-weight: 400;">If you are looking to buy the best and catchy domain names for your website then think of us.</span><b> Here at HostingRaja, we provide you with all types of domain extensions like .com, .in, .org, .net etc at an affordable price.</b><span style="font-weight: 400;"> We also provide <a href="https://www.hostingraja.in/" target="_blank" rel="noopener noreferrer">hosting services</a> for you with huge offers and discounts up to 55%. Get your domain name and hosting plan today from HostingRaja.</span></p>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to Reduce Page Load Time in Wordpress" aria-label="Previous article: How to Reduce Page Load Time in Wordpress" href="/docs/how-to-reduce-page-load-time-in-wordpress" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to Enable/Disable Firewall" aria-label="Next article: How to Enable/Disable Firewall" href="/docs/how-to-enable-disable-firewall" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>