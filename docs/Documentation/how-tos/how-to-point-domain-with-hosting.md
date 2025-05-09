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
    <p dir="ltr" style={{textAlign: "center"}}><span style={{fontSize: "24pt"}}><strong>How to point Domain with Hosting</strong></span></p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>Pointing a domain name is a very simple task. </span>Once your domain name is registered, you need to connect it to your <strong>hosting server</strong>.<span style={{fontWeight: 400}}> While registering a domain name with a hosting account (like in HostingRaja or switching to our hosting services), your domain name has to be pointed to your hosting account. And this process is known as delegation and it is easy to perform. </span></p>
    <p><span style={{fontWeight: 400}}>While pointing the domain to the hosting, ‘A’ record and name servers play a major role in pointing your domain to the hosting, These A record and nameservers are components of DNS (Domain name system). </span></p>
    <p><span style={{fontWeight: 400}}>A </span>nameserver<span style={{fontWeight: 400}}> of domain translates the domain names into IP address when entered the browser or in other words. A nameserver can be defined as a server Which stores the DNS records of a given domain name. Nameservers are part of DNS, which stands for </span>“Domain Name System<span style={{fontWeight: 400}}>” which acts like a database that works like a phone book for computers: it converts a domain name into a machine-readable IP address. Example when you type “www.justanexample.com” in your browser it will be translated to a machine-readable IP address like “23.369.561.456”</span></p>
    <p><span style={{fontWeight: 400}}>Every server has at least two nameservers, example ns1.name_of_server.com and ns2.name_of_server.com, The first name server (ns1.name_of_server.com) will be the primary server, and the second nameserver(ns2.name_of_server.com) will be the backup server for the primary server. </span></p>
    <p> </p>
    <p><br /><br /></p>
    <p>“A” Records<span style={{fontWeight: 400}}> is basically an address record, it translates the domain name to the IP address and determines which IP address belongs to a domain name. In other words, it maps the domain name to the IP address.</span></p>
    <p> </p>
    <p>Example of an A-record:</p>
    <p>Domain: www.justanexample.com</p>
    <p>Type: A record </p>
    <p>TTL: 3600 </p>
    <p>Points to (IP-address): 23.369.561.456</p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>TTL stands for time-to-live in seconds, it is the amount of time the record is allowed to be cached by a resolver.</span></p>
    <p>How do I connect or point the domain which is in HostingRaja to another server</p>
    <p><span style={{fontWeight: 400}}>You might have purchased a domain from Hostingraja  and you might have a <strong>web hosting</strong> from other company, In such cases you can to point your domain which is registered in HostingRaja to another hosting service, you can do this by two ways:</span></p>
    <p>By updating the nameservers: <span style={{fontWeight: 400}}>If the Domain is purchased in hostingraja and you are hosting your domain in another server then you need to update the nameservers of the server of your hosting service in the HostingRaja’s domain provider panel in DNS Management.The steps to update the nameservers in HostingRaja’s domain control panel is discussed below </span></p>
    <p>By updating the “A” record: <span style={{fontWeight: 400}}>Another way to point your domain is by updating the ‘A’ Record of the domain this can be done only if the nameserver of the domain are default nameservers of the domain provide are updated for the domain and you can update the server IP address of your hosting service as an “A” record in the “hostingraja” domain control panel in DNS Management.</span></p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>After the updation of the DNS, it will take 48 hours to propagate globally. </span></p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>These are the two ways to point your domain which is purchased from hostingraja to another server.</span></p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>When you have a domain which is registered with other domain provider and purchased the Domain with HostingRaja then </span>there are two methods to point the domain name to HostingRaja:</p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>1) The first method is by </span>changing the nameservers at your domain name registrar.<span style={{fontWeight: 400}}> This particular approach is suggested as your DNS zone will be automatically configured. Pointing the domain name to HostingRaja nameservers will help in assisting the DNS zone at HostingRaja's control panel.</span></p>
    <p> </p>
    <p><span style={{fontWeight: 400}}>2) The second method is by </span>pointing the domain name through an "A record".<span style={{fontWeight: 400}}> This procedure needs technical knowledge as you need to change the DNS records manually. And also, your DNS zone will not be automatically updated. Eg: If created a subdomain name in HostingRaja, then need to create a relevant "A record" in your DNS zone manually. </span></p>
    <p> </p>
    <p>If you want to point a domain with other hosting services to your Hostingraja hosting account then you need to follow below steps:</p>
    
        <span style={{fontWeight: 400}}> You have to update name-servers or A record for that domain in the domain control panel. You will get name-servers details from the Hosting provider.</span>
        <span style={{fontWeight: 400}}> Once name-servers has been updated you have to create addon domain under the hosting account and if it is your primary domain of our hosting then your domain will be added by default you don't need to add it as an &lt;a href="https://help.hostingraja.in/other-help/procedures-to-create-and-manage-addon-domains"&gt;&lt;b&gt;addon domain.&lt;/b&gt;&lt;/a&gt;</span>
    
    <p> </p>
    <p> </p>
    <p> </p>
    <p>How to update the nameserver for the domain with hosting</p>
    <p><span style={{fontWeight: 400}}>You need to change the nameserver of your</span><span style={{fontWeight: 400}}> registrar domain name</span><span style={{fontWeight: 400}}> to ensure that, Your website is pointing to hosting server.</span></p>
    <p> </p>
    <p>If your domain registrar is Hostingraja then follow the below steps to update the nameservers:</p>
    <p>Steps to update nameservers in HostingRaja’s domain control panel:</p>
    <p>Step 1:<span style={{fontWeight: 400}}> Login to domain control panel using the Your Email ID and Password.</span></p>
    <p>Step 2:<span style={{fontWeight: 400}}> Once you log in, Click on the My Domain</span></p>
    <p> </p>
    <p></p>
    <p><br />Step 3:<span style={{fontWeight: 400}}> Once you click My Domain You will get a list of domains and click on the Edit icon on the right side.</span></p>
    <p> <br /><br /><br /></p>
    <p>Steps 4:<span style={{fontWeight: 400}}> Change the name server which you got from Hosting provider And after that click on the save button.</span></p>
    <p> </p>
    <p>Step to add the domain as Addon domain under the Hosting account</p>
    <p> </p>
    <p>Step 1:<span style={{fontWeight: 400}}> Login to cpanel.</span></p>
    <p>Step 2:<span style={{fontWeight: 400}}> Once you will log in to cpanel &gt;&gt; Kindly go to Domains section from there you will get Addon Domain options.<br /><br /><br /><br /> </span></p>
    <p>Step 3:<span style={{fontWeight: 400}}> Click on Addon domain &gt;&gt; From there enter your domain name which has to be added.<br /><br /><br /><br /> </span></p>
    <p>Step 4:<span style={{fontWeight: 400}}> Once you will fill the domain name &gt;&gt; After that click on Add domain name.</span></p>
    <p> </p>
    <p>Note: </p>
    <p>Any changes to the DNS Records it will take 24 -48 hours to get reflected or affected globally, this time taken for DNS record to get reflected is called as DNS propagation time </p>
    <p> </p>
    <p>You check if DNS is updated properly, by using the below links, this will let you know if you have updated the DNS properly:</p>
    <p>&gt;&gt;https://intodns.com</p>
    <p>&gt;&gt;https://mxtoolbox.com</p>
    <p> </p>
    <p>You can also check if the DNS propagation using :</p>
    <p>&gt;&gt;https://www.whatsmydns.net/ </p>
    <p><br /><br /></p>
    <p><span style={{fontWeight: 400}}>If you are looking to buy the best and catchy domain names for your website then think of us.</span> Here at HostingRaja, we provide you with all types of domain extensions like .com, .in, .org, .net etc at an affordable price.<span style={{fontWeight: 400}}> We also provide hosting services for you with huge offers and discounts up to 55%. Get your domain name and hosting plan today from HostingRaja.</span></p>
</div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>