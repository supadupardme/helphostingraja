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

G Suite split delivery
<p>step 1: Add a mail route for a domain</p>

  In your Google Admin console (at admin.google.com)...
  Go to Apps > G Suite > Gmail > Advanced settings.
  Click Hosts.
  Click Add Route.
  Enter a route name. Use anything that'll help you keep track of the route.
  Specify any email servers for the route.
  If you select Single host, enter the route's hostname or IP address. We recommend you use the hostname. Also, enter the port number: 25, 587, or a number between 1024 and 65535.
  E.g pluto.dnsindia.net:25

<p /></p>

<p>Source: [https://support.google.com/a/answer/2614757](https://support.google.com/a/answer/2614757)</p>

<p /></p>

step 2: Set up routing for your domain or organization

<p /></p>

<p>Initial step: Go to Apps > G Suite > Gmail > Advanced settings in the admin.google.com</p>

<p /></p>

<p>Go to General settings>Routing>Routing>configuration> follow below snapshot on next page</p>

<p /></p>

<p>Step 1: Enter email messages to affect Step 2: Set up an envelope filter</p>
<p>Step 3: Specify what happens to the messages > refer two snapshots below.</p>

<p /></p>

<p>[https://support.google.com/a/answer/6297084#initial-step](https://support.google.com/a/answer/6297084#initial-step)</p>

<p></p>
  <br />

  

  <br />

  <br />

  <br />

  <br />

  <br />

  

  <br />

  <br />

  <br />

  <br />

  <br />

  

  <br />

  <br />

  <br />

  <br />

  <br />

  

  <br />

  <br />

  <br />

  <br />

  <br />

  

  <br />

  <br />

  <br />

  <br />

  <br />

<p>step 3: Setup Email Forwarder from legacy email service</p>

<p /></p>

<p>set email forwarder for<strong>  </strong>in legacy email service (cpanel/plesk or RC), note: you need to create email forwarders for all Email accounts which are created in G suite panel.</p>

<p /></p>

<p>step 4: Change MX record and point it to Google</p>

<p /></p>

<p>step 5: Kindly ensure the email routing should be “Local Mail Exchanger” in cPanel.</p>

<p /></p>

<p>update SPF record <strong>v=spf1 include:\_spf.google.com \~all </strong>with existing SPF record and save update DKIM record></p>

<p /></p>

<p>step1> Apps> G Suite> settings for gmail>authenticate email>Generate new record</p>

<p /></p>

<p>step2> go to cpanel dns> add txt record name “google.\_domainkey” and paste the same value which generated from G Suite panel> keep TTL 300 or as low as possible.</p>

<p /></p>

<p>Step3> go to admin.google.com>apps>g suite settings for gmail>authenticate email> start authentication.</p>
<p><br />you can cross-check records with this tool: [https://toolbox.googleapps.com/apps/checkmx/](https://toolbox.googleapps.com/apps/checkmx/)</p>

  
    
      <span>Next</span> <span class="icon-chevron-right" /></span>