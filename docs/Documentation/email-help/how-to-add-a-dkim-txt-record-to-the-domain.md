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
<h2 itemprop="headline">
How to add a DKIM TXT record to the domain? </h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2024-01-03T12:50:56+00:00" itemprop="dateModified">
Last Updated: 03 January 2024 </time>
</dd>
</dl>
<div itemprop="articleBody">
<h1><span style="font-size: xx-large;">How to add a DKIM TXT record to the domain?</span><br/><br/><br/></h1>
<p>Here you will be shown on how to add <strong><a href="https://www.hostingraja.in/domains/">domain name </a>keys Identified Mail (DKIM)</strong> TXT records to the domain. DKIM is the method by which one can fight spam which works by associating outgoing email with a domain through a digital signature. In this case, sending mail server attaches the “signature” to an email which has been encoded with a private key.</p>
<p><br/>If the receiving mail server is being configured to check the DKIM it will be using a corresponding public key for decoding the signature and verify the authenticity. When DKIM is enabled email will be less spammy, and the recipient mail servers are less likely to filter any type of the email. Hence it will improve the deliverability.<br/><br/></p>
<p>One should remember that you must be having<a href="https://www.hostingraja.in/hosting/compare-hosting-plans/"><b> HostingRaja</b></a> name servers.</p>
<p><strong>NS1.YOURDOMAINNAME.COM</strong><br/><strong>NS2.YOURDOMAINNAME.COM</strong></p>
<p><br/>You need to login to the Account center and then click on the domain name that you would like to add the DKIM TXT records too. Or you can hover the domains tab at the top of the Account center and then click show all. Now you need to select the relevant domain from the list.</p>
<p>Now you need to edit the DNS file zone option. Which is under the <strong>DNS and Zone Files Menu</strong>.<br/><br/><br/><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/articles/how-to-add-a-dkim-txt-record-to-the-domain-one.png" alt="How to add a dkim txt record to the domain one" width="247" height="145" border="0" /><br/><br/><br/>Then click on the <strong>+Add Row</strong> for creating a new record. This record will tell the mail server that all the email message associated with this domain name use DKIM.<br/><br/><br/></p>
<img src="https://image.hostingraja.in/images/articles/how-to-add-a-dkim-txt-record-to-the-domain-two.png" alt width="436" height="38" />
<ul id="docs-internal-guid-d49deb9c-e1a9-8caa-61f6-8314e15faec0">
<li dir="ltr">
<p dir="ltr">Subdomain (Name): _domainkey</p>
</li>
<li dir="ltr">
<p dir="ltr">Type: TXT</p>
</li>
<li dir="ltr">
<p dir="ltr">Data: o=-</p>
</li>
</ul>
<div><br/>Now you need to click on the +Add row for creating a new record and then add the DKIM key. This is the public key which is used to decode the email associated <strong>digital signature</strong>. Once it has been added to both records you need to click on Save Changes. Now you need to allow up to 24 hours for propagation, after which the DKIM is enabled for this domain name.<br/><br/><br/><span id="docs-internal-guid-d49deb9c-e1aa-1276-56e4-5e75bd8a8770"><img src="https://image.hostingraja.in/images/articles/how-to-add-a-dkim-txt-record-to-the-domain-three.png" alt="How to add a dkim txt record to the domain three" width="579" height="38" border="0" /></span><br/><br/><br/>
<ul>
<li>Subdomain (Name): default._domainkey</li>
</ul>
<ul>
<li>Type: TXT</li>
</ul>
<ul>
<li>Data: Your DKIM key.</li>
</ul>
<div> </div>
<p>This is the process of adding DKIM TXT record for adding the domain name in a server.<br/><br/><strong>Additional Notes :</strong> <br/> Plesk contains a built-in way to toggle DKIM on and off. Yet, allowing DKIM for outgoing email requests that you reach the associated TXT record from Plesk and count it to your Media file. <br/><br/>As for as cPanel is concerned cPanel provisions SPF and DKIM for new accounts by default. Yet, the system does not automatically provide these DNS records for existing accounts. You can allow DKIM for all accounts simultaneously via WHM, or for unique domains via cPanel. The DKIM TXT file you get from cPanel needs to be saved as part of your Media file if you want to allow DKIM for outgoing email.</p>
</div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="Get unsolicited Emails or phone calls after registering the domain name and web hosting with us." aria-label="Previous article: Get unsolicited Emails or phone calls after registering the domain name and web hosting with us." href="/docs/get-unsolicited-emails-or-phone-calls-after-registering-the-domain-name-and-web-hosting-with-us" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How to create a mailing list in Plesk?" aria-label="Next article: How to create a mailing list in Plesk?" href="/docs/how-to-create-a-mailing-list-in-plesk" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>