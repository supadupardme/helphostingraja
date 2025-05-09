---
title: How to add a DKIM TXT record to the domain?
excerpt: >-
  Secure your email with DKIM: Follow these steps to add DKIM TXT records to
  your domain
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

How to add a DKIM TXT record to the domain? 
</div>

<span class="icon-calendar" aria-hidden="true"></span>

Last Updated: 03 January 2024 

<div itemprop="articleBody">
<span style={{fontSize: "xx-large"}}>How to add a DKIM TXT record to the domain?</span><br /><br /><br />
<p>Here you will be shown on how to add <strong>domain name keys Identified Mail (DKIM)</strong> TXT records to the domain. DKIM is the method by which one can fight spam which works by associating outgoing email with a domain through a digital signature. In this case, sending mail server attaches the “signature” to an email which has been encoded with a private key.</p>
<p><br />If the receiving mail server is being configured to check the DKIM it will be using a corresponding public key for decoding the signature and verify the authenticity. When DKIM is enabled email will be less spammy, and the recipient mail servers are less likely to filter any type of the email. Hence it will improve the deliverability.<br /><br /></p>
<p>One should remember that you must be having HostingRaja name servers.</p>
<p><strong>NS1.YOURDOMAINNAME.COM</strong><br /><strong>NS2.YOURDOMAINNAME.COM</strong></p>
<p><br />You need to login to the Account center and then click on the domain name that you would like to add the DKIM TXT records too. Or you can hover the domains tab at the top of the Account center and then click show all. Now you need to select the relevant domain from the list.</p>
<p>Now you need to edit the DNS file zone option. Which is under the <strong>DNS and Zone Files Menu</strong>.<br /><br /><br /><br /><br /><br />Then click on the <strong>+Add Row</strong> for creating a new record. This record will tell the mail server that all the email message associated with this domain name use DKIM.<br /><br /><br /></p>

<p dir="ltr">Subdomain (Name): _domainkey</p>

<p dir="ltr">Type: TXT</p>

<p dir="ltr">Data: o=-</p>

<div><br />Now you need to click on the +Add row for creating a new record and then add the DKIM key. This is the public key which is used to decode the email associated <strong>digital signature</strong>. Once it has been added to both records you need to click on Save Changes. Now you need to allow up to 24 hours for propagation, after which the DKIM is enabled for this domain name.<br /><br /><br /><span id="docs-internal-guid-d49deb9c-e1aa-1276-56e4-5e75bd8a8770"></span><br /><br /><br />

Subdomain (Name): default._domainkey

Type: TXT

Data: Your DKIM key.

<div> </div>
<p>This is the process of adding DKIM TXT record for adding the domain name in a server.<br /><br /><strong>Additional Notes :</strong> <br /> Plesk contains a built-in way to toggle DKIM on and off. Yet, allowing DKIM for outgoing email requests that you reach the associated TXT record from Plesk and count it to your Media file. <br /><br />As for as cPanel is concerned cPanel provisions SPF and DKIM for new accounts by default. Yet, the system does not automatically provide these DNS records for existing accounts. You can allow DKIM for all accounts simultaneously via WHM, or for unique domains via cPanel. The DKIM TXT file you get from cPanel needs to be saved as part of your Media file if you want to allow DKIM for outgoing email.</p>
</div> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>