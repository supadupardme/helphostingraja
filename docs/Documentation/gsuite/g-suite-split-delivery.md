---
title: G Suite split delivery
excerpt: >-
  Know about Gsuite split delivery and know the steps of setting up the routing
  for your domain or organization.
deprecated: false
hidden: false
metadata:
  title: ''
  description: >-
    The document outlines the steps to set up G Suite split delivery, including
    adding a mail route, configuring domain routing, setting up email
    forwarders, changing MX records, and updating SPF and DKIM records.
  robots: index
next:
  description: ''
---
<h2>G Suite split delivery</h2>
<p><b>step 1: </b>Add a mail route for a domain</p>

<ol>
  <li>In your Google <b>Admin console </b>(at <a href="http://admin.google.com/" target="_blank">admin.google.com</a>)...</li>
  <li>Go to Apps > G Suite > Gmail > Advanced settings.</li>
  <li>Click <b>Hosts</b>.</li>
  <li>Click <b>Add Route</b>.</li>
  <li>Enter a route name. Use anything that'll help you keep track of the route.</li>
  <li>Specify any email servers for the route.</li>
  <li>If you select <b>Single host</b>, enter the route's hostname or IP address. We recommend you use the hostname. Also, enter the port number: 25, 587, or a number between 1024 and 65535.</li>
  <li>E.g pluto.dnsindia.net:25</li>
</ol>

<p />

<p>Source: <a target="_blank" href="https://support.google.com/a/answer/2614757">[https://support.google.com/a/answer/2614757](https://support.google.com/a/answer/2614757)</a></p>

<p />

<h2><b>step 2: </b>Set up routing for your domain or organization</h2>

<p />

<p>Initial step: Go to Apps > G Suite > Gmail > Advanced settings in the admin.google.com</p>

<p />

<p>Go to General settings>Routing>Routing>configuration> follow below snapshot on next page</p>

<p />

<p>Step 1: Enter email messages to affect Step 2: Set up an envelope filter</p>
<p>Step 3: Specify what happens to the messages > refer two snapshots below.</p>

<p />

<p>[https://support.google.com/a/answer/6297084#initial-step](https://support.google.com/a/answer/6297084#initial-step)</p>

<p>
  <br />

  <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-spli-delivery-1.jpg" />

  <br />

  <br />

  <br />

  <br />

  <br />

  <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-split-delivery-31.PNG" />

  <br />

  <br />

  <br />

  <br />

  <br />

  <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-split-delivery-4.PNG" />

  <br />

  <br />

  <br />

  <br />

  <br />

  <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-split-delivery-5.PNG" />

  <br />

  <br />

  <br />

  <br />

  <br />

  <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-split-delivery-6.PNG" />

  <br />

  <br />

  <br />

  <br />

  <br />
</p>

<p><b>step 3</b><b>: Setup Email Forwarder from legacy email service</b></p>

<p />

<p>set email forwarder for<strong> <img src="https://image.hostingraja.in/images/articles/gsuite-split-delivery/gsuite-spli-delivery-3.jpg" /> </strong>in legacy email service (cpanel/plesk or RC), note: you need to create email forwarders for all Email accounts which are created in G suite panel.</p>

<p />

<p><b>step 4</b><b>: </b>Change MX record and point it to Google</p>

<p />

<p><b>step 5</b><b>: </b>Kindly ensure the email routing should be “Local Mail Exchanger” in cPanel.</p>

<p />

<p>update SPF record <strong>v=spf1 include:\_spf.google.com \~all </strong>with existing SPF record and save update DKIM record></p>

<p />

<p>step1> Apps> G Suite> settings for gmail>authenticate email>Generate new record</p>

<p />

<p>step2> go to cpanel dns> add txt record name “google.\_domainkey” and paste the same value which generated from G Suite panel> keep TTL 300 or as low as possible.</p>

<p />

<p>Step3> go to admin.google.com>apps>g suite settings for gmail>authenticate email> start authentication.</p>
<p><br />you can cross-check records with this tool: <a href="https://toolbox.googleapps.com/apps/checkmx/" target="_blank">[https://toolbox.googleapps.com/apps/checkmx/](https://toolbox.googleapps.com/apps/checkmx/)</a></p>

<ul class="pager pagenav">
  <li class="next">
    <a class="hasTooltip" href="/docs/g-suite-data-migration-1/">
      <span>Next</span> <span class="icon-chevron-right" />
    </a>
  </li>
</ul>