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
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
</dl>
<div itemprop="articleBody">
<h1 dir="ltr"><span style="font-size: xx-large;">Configure e-mail authentication in cPanel</span></h1>
<div> </div>
<p dir="ltr">This article describes how to set up e-mail authentication in <a href="/cpanel-article/cpanel-hosting">cPanel</a> to help reduce unwanted e-mail (spam). E-mail authentication in cPanel is based upon two complementary technologies, DKIM and SPF, that help reduce the amount of spam.</p>
<p dir="ltr"><strong>For Email Authentication or <span class="page-title">Email Deliverability validation in Cpanel:</span></strong></p>
<p dir="ltr"><span class="page-title"><strong>STEP1:</strong> Login to your Cpanel.</span></p>
<p dir="ltr"><span class="page-title"><strong>STEP2:</strong> Click the Email Authentication or Email Deliverability option from your Cpanel</span></p>
<p dir="ltr"><img src="https://image.hostingraja.in/images/emailauth0.png" alt="email delivery " width="255" height="266" /></p>
<h2 dir="ltr"> </h2>
<h2 dir="ltr"><strong>STEP3: </strong>Check the <span class="page-title">Email Deliverability status is <strong>valid</strong> or showing error.</span></h2>
<p dir="ltr"><img src="https://image.hostingraja.in/images/emailauth2.png" alt="email delivery " width="247" height="226" /></p>
<h2 dir="ltr"> </h2>
<h2 dir="ltr"><strong>DOMAIN KEYS IDENTIFIED MAIL (DKIM)</strong></h2>
<p dir="ltr">You can use DKIM to verify that an incoming e-mail message is actually from the stated sender and that the message has not been altered during transit. When DKIM is enabled, the sender digitally signs a message using a private key. The recipient uses DNS to retrieve the sender's public key and verify the message's signature. If the signature is invalid, then the message is assumed to be forged and therefore spam.</p>
<p dir="ltr"> </p>
<h2 dir="ltr"><strong>SENDER POLICY FRAMEWORK (SPF)</strong></h2>
<p dir="ltr">SPF helps prevent spammers from forging messages that implicate your domain as the sender. As a result, SPF can also reduce the number of bounce messages that you receive (also known as backscatter spam). SPF uses DNS records that specify the mail servers and IP addresses that are authorized to send e-mail messages from a domain.</p>
<h2 dir="ltr">Enabling SPF</h2>
<p dir="ltr">To enable SPF, follow these steps:</p>
<ol>
<li dir="ltr">
<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>
</li>
<li dir="ltr">
<p dir="ltr">Under SPF, click Enable.</p>
</li>
<li dir="ltr">
<p dir="ltr">If you have a shared <a href="https://www.hostingraja.in/">hosting plans</a> or reseller hosting account, confirm that the raw SPF record includes one of the following configuration lines after you enable SPF:</p>
</li>
<li dir="ltr">
<p dir="ltr">If one of these configuration lines is not in the raw SPF record, follow these steps:</p>
</li>
<ol>
<li dir="ltr">
<p dir="ltr">Under Advanced Settings, in the Include List (INCLUDE) row, click Add.</p>
</li>
<li dir="ltr">
<p dir="ltr">In the Enter a new item text box, type one of the following lines</p>
</li>
<li dir="ltr">
<p dir="ltr">Click OK.</p>
</li>
<li dir="ltr">
<p dir="ltr">Under Save Your Changes, click Update.</p>
</li>
</ol>
</ol>
<h2 dir="ltr">Changing SPF advanced settings</h2>
<p dir="ltr">After you have enabled SPF, you can modify its configuration. You can add additional IP addresses or mail servers that are authorized to send e-mail for your domain. For example, you may want to do this if you use a third-party mail server.</p>
<p dir="ltr">Make sure that you include in the ticket the exact lines that you want to add to the zone file.</p>
<p dir="ltr">To change SPF advanced settings, follow these steps:</p>
<ol>
<li dir="ltr">
<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>
</li>
<li dir="ltr">
<p dir="ltr">To add additional hosts, servers, IP blocks, or include lists to your SPF configuration, click Add in the corresponding section. Alternatively, to remove hosts, servers, IP blocks, or include lists from your SPF configuration, click Remove in the corresponding section.</p>
</li>
<li dir="ltr">
<p dir="ltr">To exclude all other domains that are not specifically defined in your configuration, select the All Entry (ALL) check box.</p>
</li>
<li dir="ltr">
<p dir="ltr">To overwrite all existing SPF records, select the Overwrite Existing Entries check box.</p>
</li>
<li dir="ltr">
<p dir="ltr">Click Update. </p>
</li>
</ol>
<h2 dir="ltr"><strong>Reverse DNS (PTR)</strong></h2>
<p>For Reverse DNS from your Cpanel, There is no Option its available from the Cpanel. Raise ticket to us using <a href="https://support.hostingraja.in/">https://support.hostingraja.in/</a> We will set the reverse DNS for your account.</p>
<p> </p>
<p> </p> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="How To Set Up Cron Jobs In cPanel" aria-label="Previous article: How To Set Up Cron Jobs In cPanel" href="/docs/how-to-set-up-cron-jobs-in-cpanel" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How Do I Increase The PHP Upload Limits in cPanel?" aria-label="Next article: How Do I Increase The PHP Upload Limits in cPanel?" href="/docs/how-do-i-increase-the-php-upload-limits-in-cpanel" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>