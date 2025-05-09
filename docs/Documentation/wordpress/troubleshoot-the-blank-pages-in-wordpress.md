---
title: Troubleshoot the blank pages in wordpress
excerpt: >-
  Resolve WordPress blank page issues by troubleshooting plugins and themes for
  seamless website functionality
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
Troubleshoot the blank pages in wordpress
</div>

<span class="icon-calendar" aria-hidden="true"></span>

Last Updated: 03 January 2024 

<div itemprop="articleBody">
<span style={{fontSize: "large"}}><span style={{fontSize: "xx-large"}} data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Troubleshoot the blank pages in wordpress&quot;}" data-sheets-userformat="{&quot;2&quot;:769,&quot;3&quot;:{&quot;1&quot;:0},&quot;11&quot;:4,&quot;12&quot;:0}">Troubleshoot the blank pages in wordpress</span><br /><br /></span>
<span style={{fontSize: "large"}}>Problem</span>
<div><span style={{fontSize: "large"}}> </span></div>
<p dir="ltr"><span style={{fontSize: "large"}}>The blank page will occur when you try to view the wordpress website, This may occur on single page, on multiple pages and on entire site. You may also unable to login to the admin panel.</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<span style={{fontSize: "large"}}>Resolution</span>
<div><span style={{fontSize: "large"}}> </span></div>
<p dir="ltr"><span style={{fontSize: "large"}}>The general causes for this problem on wordpress sites are:</span></p>
<p><span style={{fontSize: "large"}}> </span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>A malfunctioning plugin </span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>A malfunctioning Theme</span></p>

<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>To resolve this problem you can disable the plugins one by one by selecting individually until the blank pages disappear. Apart from this if you notice that the current theme is causing the issue then you need to suspect the current theme by reverting back to its default theme.<br /><br /></span></p>
<span style={{fontSize: "large"}}>Disabling plugins</span>
<div><span style={{fontSize: "large"}}> </span></div>
<p dir="ltr"><span style={{fontSize: "large"}}>You can disable the plugins if you login to the wordpress as a administrator from the plugins options. If you are not an administrator you need to disable the plugins manually from the cPanel provided with your website hosting, To do this follow the below steps:<br /><br /></span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Login to your cPanel</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Click on file manager and then go to the path public_html/wp-content/plugins.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Each plugin will be in a separate directory, To disable the plugins you need to rename the plugin for example: to disable the Akismet plugin just rename it as Akismet_bak</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>You need to repeat the above process for all the plugins one by one, If you notice that the particular plugin is causing the issue then it's well and good.</span></p>

<span style={{fontSize: "large"}}> </span>
<span style={{fontSize: "large"}}>Reverting to the default theme</span>
<div><span style={{fontSize: "large"}}> </span></div>
<p dir="ltr"><span style={{fontSize: "large"}}>If you login as an administrator you can disable the themes in the admin panel from the optio Appearances---&gt;Themes, but if you are not an administrator you need to follow the same process as we have mentioned for plugins.</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>Follow the below steps to reverting to the default theme:</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Login to your shared hosting cPanel.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Go to the directory public_html/wp-content/themes</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Note down the default theme, If there are several themes you need to revert back to the most recently used theme.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Go back to the cPanel home screen.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Open the phpmyadmin in the databases section.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Expand the database which you have assigned to the website.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Click on wp_options.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>You will see the template and stylesheet rows in the option_name column, In the option_value row you will see your current theme.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Double click on option_value in the template row, Type the default theme which you got from the step 3.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>Repeat step 9 for the stylesheet row. The default theme is now active.</span></p>

<p dir="ltr"><span style={{fontSize: "large"}}>If the previous theme was causing the issue the site should work now.</span></p>

<div><span style={{fontSize: "large"}}><span style={{fontSize: "large"}}><br />If you want to buy hosting, please see our hosting page.<br /> <br /><br /><br /></span></span><span style={{fontSize: "large"}}> </span></div> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>