---
title: Installing a Free SSL via the cPanel AutoSSL Feature
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

```mdx
<div class="page-header">
</div>
<dl class="article-info muted">
  <dt class="article-info-term">
  </dt>
</dl>
<div itemprop="articleBody">
  <h1>
    <span style={{ fontWeight: "400" }}>
      Installing a Free SSL via the cPanel AutoSSL Feature
    </span>
  </h1>
  <br />
  <p>Here is how to initiate an AutoSSL check from your cPanel account.</p>
  <ol>
    <li>
      <span style={{ fontWeight: "400" }}>
        Log into your cPanel account and navigate to SSL/TLS Status in the Security section.
      </span>
    </li>
  </ol>
  <img
    title="cPanel SSL Installation"
    src="https://image.hostingraja.in/images/articles/cpanel-help/install-ssl-cpanel-one.jpg"
    alt="cPanel SSL Installation"
    width="1202"
    height="251"
  />
  <br />
  <br />
  <ol start="2">
    <li>
      <span style={{ fontWeight: "400" }}>
        Click the domain(s) you'd like to install a SSL on and click Run AutoSSL.
      </span>
    </li>
  </ol>
  <img
    title="cPanel SSL Installation"
    src="https://image.hostingraja.in/images/articles/cpanel-help/install-ssl-cpanel-two.jpg"
    alt="cPanel SSL Installation"
    width="1122"
    height="377"
  />
  <br />
  <br />
  <ol start="3">
    <li>
      <span style={{ fontWeight: "400" }}>
        AutoSSL will take a few minutes to finish. When it completes successfully the page will update with a success notification.
      </span>
    </li>
  </ol>
  <br />
  <ol start="4">
    <li>
      <span style={{ fontWeight: "400" }}>
        Next cPanel will automatically poll Comodo for a new SSL. This polling process usually takes a few minutes but can last up to a day or more (since there are restrictions on the number of requests that can be made per day). Once it has completed your domain will have a new valid AutoSSL installed.
      </span>
    </li>
  </ol>
</div>
<ul class="pager pagenav">
  <li class="previous">
    <a
      class="hasTooltip"
      title="How to Reset cPanel password from HostingRaja ClientArea"
      aria-label="Previous article: How to Reset cPanel password from HostingRaja ClientArea"
      href="/docs/how-to-reset-cpanel-password-from-hostingraja-clientarea"
      rel="prev"
    >
      <span class="icon-chevron-left" aria-hidden="true"></span>
      <span aria-hidden="true">Prev</span>
    </a>
  </li>
  <li class="next">
    <a
      class="hasTooltip"
      title="Reseller cPanel invoice credits"
      aria-label="Next article: Reseller cPanel invoice credits"
      href="/docs/reseller-cpanel-invoice-credits"
      rel="next"
    >
      <span aria-hidden="true">Next</span>
      <span class="icon-chevron-right" aria-hidden="true"></span>
    </a>
  </li>
</ul>
```