---
title: How to configure e-mail authentication in cPanel
excerpt: ''
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
</div>

<div itemprop="articleBody">
<span style={{fontSize: "xx-large"}}>Configure e-mail authentication in cPanel</span>
<div> </div>
<p dir="ltr">This article describes how to set up e-mail authentication in cPanel to help reduce unwanted e-mail (spam). E-mail authentication in cPanel is based upon two complementary technologies, DKIM and SPF, that help reduce the amount of spam.</p>
<p dir="ltr"><strong>For Email Authentication or <span class="page-title">Email Deliverability validation in Cpanel:</span></strong></p>
<p dir="ltr"><span class="page-title"><strong>STEP1:</strong> Login to your Cpanel.</span></p>
<p dir="ltr"><span class="page-title"><strong>STEP2:</strong> Click the Email Authentication or Email Deliverability option from your Cpanel</span></p>
<p dir="ltr"></p>
 
<strong>STEP3: </strong>Check the <span class="page-title">Email Deliverability status is <strong>valid</strong> or showing error.</span>
<p dir="ltr"></p>
 
<strong>DOMAIN KEYS IDENTIFIED MAIL (DKIM)</strong>
<p dir="ltr">You can use DKIM to verify that an incoming e-mail message is actually from the stated sender and that the message has not been altered during transit. When DKIM is enabled, the sender digitally signs a message using a private key. The recipient uses DNS to retrieve the sender's public key and verify the message's signature. If the signature is invalid, then the message is assumed to be forged and therefore spam.</p>
<p dir="ltr"> </p>
<strong>SENDER POLICY FRAMEWORK (SPF)</strong>
<p dir="ltr">SPF helps prevent spammers from forging messages that implicate your domain as the sender. As a result, SPF can also reduce the number of bounce messages that you receive (also known as backscatter spam). SPF uses DNS records that specify the mail servers and IP addresses that are authorized to send e-mail messages from a domain.</p>
Enabling SPF
<p dir="ltr">To enable SPF, follow these steps:</p>

<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>

<p dir="ltr">Under SPF, click Enable.</p>

<p dir="ltr">If you have a shared hosting plans or reseller hosting account, confirm that the raw SPF record includes one of the following configuration lines after you enable SPF:</p>

<p dir="ltr">If one of these configuration lines is not in the raw SPF record, follow these steps:</p>

<p dir="ltr">Under Advanced Settings, in the Include List (INCLUDE) row, click Add.</p>

<p dir="ltr">In the Enter a new item text box, type one of the following lines</p>

<p dir="ltr">Click OK.</p>

<p dir="ltr">Under Save Your Changes, click Update.</p>

Changing SPF advanced settings
<p dir="ltr">After you have enabled SPF, you can modify its configuration. You can add additional IP addresses or mail servers that are authorized to send e-mail for your domain. For example, you may want to do this if you use a third-party mail server.</p>
<p dir="ltr">Make sure that you include in the ticket the exact lines that you want to add to the zone file.</p>
<p dir="ltr">To change SPF advanced settings, follow these steps:</p>

<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>

<p dir="ltr">To add additional hosts, servers, IP blocks, or include lists to your SPF configuration, click Add in the corresponding section. Alternatively, to remove hosts, servers, IP blocks, or include lists from your SPF configuration, click Remove in the corresponding section.</p>

<p dir="ltr">To exclude all other domains that are not specifically defined in your configuration, select the All Entry (ALL) check box.</p>

<p dir="ltr">To overwrite all existing SPF records, select the Overwrite Existing Entries check box.</p>

<p dir="ltr">Click Update. </p>

<strong>Reverse DNS (PTR)</strong>
<p>For Reverse DNS from your Cpanel, There is no Option its available from the Cpanel. Raise ticket to us using https://support.hostingraja.in/ We will set the reverse DNS for your account.</p>
<p> </p>
<p> </p> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>