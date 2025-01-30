---
title: How to configure email authentication in cPanel
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
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-08-27T13:23:30+00:00" itemprop="dateModified">
Last Updated: 27 August 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">
<h1 dir="ltr"><span style="font-size: xx-large;">How to configure e-mail authentication in cPanel</span></h1>
<div> </div>
<p dir="ltr">This article describes how to set up e-mail authentication in <a href="/cpanel-help/cpanel-hosting/">cPanel</a> to help reduce unwanted e-mail (spam). E-mail authentication in cPanel is based upon two complementary technologies, DKIM and SPF, that help reduce the amount of spam.</p>
<h2 dir="ltr">DOMAINKEYS IDENTIFIED MAIL (DKIM)</h2>
<p dir="ltr">You can use DKIM to verify that an incoming e-mail message is actually from the stated sender, and that the message has not been altered during transit. When DKIM is enabled, the sender digitally signs a message using a private key. The recipient uses DNS to retrieve the sender's public key and verify the message's signature. If the signature is invalid, then the message is assumed to be forged and therefore spam.</p>
<h2 dir="ltr">Enabling DKIM</h2>
<p dir="ltr">To enable DKIM, follow these steps:</p>
<ol>
<li dir="ltr">
<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>
</li>
<li dir="ltr">
<p dir="ltr">Under DKIM, click Enable.</p>
</li>
</ol>
<h2 dir="ltr">Disabling DKIM</h2>
<p dir="ltr">To disable DKIM, follow these steps:</p>
<ol>
<li dir="ltr">
<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>
</li>
<li dir="ltr">
<p dir="ltr">Under DKIM, click Disable.</p>
</li>
</ol>
<h2 dir="ltr">SENDER POLICY FRAMEWORK (SPF)</h2>
<p dir="ltr">SPF helps prevent spammers from forging messages that implicate your domain as the sender. As a result, SPF can also reduce the amount of bounce messages that you receive (also known as backscatter spam). SPF uses DNS records that specify the mail servers and IP addresses that are authorized to send e-mail messages from a domain.</p>
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
<p dir="ltr">If you have a shared hosting or <a href="https://www.hostingraja.in/hosting/reseller-web-hosting/">reseller hosting</a> account, confirm that the raw SPF record includes one of the following configuration lines after you enable SPF:</p>
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
<p dir="ltr">Click Update.</p>
</li>
</ol>
<h2 dir="ltr">Disabling SPF</h2>
<p dir="ltr">To disable SPF, follow these steps:</p>
<ol>
<li dir="ltr">
<p dir="ltr">In the Mail section of the cPanel home screen, click Email Authentication.</p>
</li>
<li dir="ltr">
<p dir="ltr">Under SPF, click Disable.</p>
</li>
</ol> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="how-to-run-the-virus-scanner-in-cpanel" aria-label="Previous article: how-to-run-the-virus-scanner-in-cpanel" href="/docs/how-to-run-the-virus-scanner-in-cpanel" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How to set up Email Default Address in cPanel" aria-label="Next article: How to set up Email Default Address in cPanel" href="/docs/how-to-set-up-email-default-address-in-cpanel" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>