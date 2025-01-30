---
title: How to Create Custom Error Pages in cPanel?
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
    <h1 style="text-align: center;"><span style="font-size: xx-large;"><strong>How to Create Custom Error Pages in cPanel?</strong></span></h1>
    <p dir="ltr"><span style="font-size: large;">Sometime when a visitor to your website gets an error message, for example <strong>400</strong> (Bad request), 403 (Forbidden), or 500 (Internal<a href="/error-troubleshoot/internal-server-error-linux"><b> server error</b></a>), they will be seeing the default error pages. But if you want you can easily customize these pages using<strong> cPanel’s error pages</strong> option. Here in this help section we are going to discuss about how to create custom error page in your <strong><a href="https://www.hostingraja.in/">web hosting</a> account.</strong></span></p>
    <p dir="ltr"><span style="font-size: large;"><strong> </strong></span></p>
    <h2 dir="ltr" style="text-align: left;"><strong><span style="font-size: large;">Creating a Custom Error page in cPanel</span></strong></h2>
    <p dir="ltr"><span style="font-size: large;"><strong>Login to cPanel</strong> of your website.</span></p>
    <p dir="ltr"><span style="font-size: large;">Locate <strong>Advanced section</strong> in cPanel and click error pages.</span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/create-custom-error-pages1.png" width="700" height="124" border="0" /></span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;">You may have <strong>multiple <a href="https://www.hostingraja.in/domains/">domain name</a></strong> under one <a href="/cpanel-article/how-to-create-a-cpanel-account-in-whm"><b>cPanel account</b>, select the one for which you want to create <strong>custom error pages</strong> from the Managing menu.</a></span></p>
    <p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/create-custom-error-pages2.png" width="700" height="403" border="0" /></span></p>
    <p dir="ltr"><span style="font-size: large;">Here on this step you will find the list of most common errors, hit the one you are planning to design a <strong>customized error page</strong> for. The available options to choose from are 400 (Bad request), 401 (Authorization required), 403 (Forbidden), 404 (Not found) etc. Hit show all HTTP code if you want to see additional error codes. Hit the option you want to edit. Here I am going to select 404 error code.</span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;">Once you hit your desired option you will be landed on editor page. You can type HTML program in the text box given or just insert redefined tags if you wish. <br/></span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Once you are done hit the save button.</strong><br/><br/></span></p>
    <h2 dir="ltr" style="text-align: left;"><strong><span style="font-size: large;">Setting up your  .htaccess File</span></strong></h2>
    <p dir="ltr"><span style="font-size: large;">By pressing right click of your mouse edit the<strong> .htaccess file</strong> and create a rule for the error pages you created. You can file .htaccess file inside the public_html of your file manager. Given below is the sample of the file formatting: <br/></span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;">ErrorDocument 404 /404.shtml</span></p>
    <p dir="ltr"><span style="font-size: large;">ErrorDocument 402 /402.shtml</span></p>
    <p dir="ltr"><span style="font-size: large;">ErrorDocument 410 /410.shtml</span></p>
    <p dir="ltr"><span style="font-size: large;">ErrorDocument 414 /414.shtml</span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Save your .htaccess file</strong> and now when someone visit your website and an error message trigger, it will display your custom error page which you created for particular error code.</span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Facing any difficulty?</strong> Don’t worry our <strong>support team</strong> is here to help. Contact our <strong>Support team now</strong>.</span></p>
</div>
<ul class="pager pagenav">
    <li class="previous">
        <a class="hasTooltip" title="How to protect directories with a password" aria-label="Previous article: How to protect directories with a password" href="/docs/how-to-protect-directories-with-a-password-in-cpanel" rel="prev">
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
    </li>
    <li class="next">
        <a class="hasTooltip" title="Setting up AutoResponders in cPanel" aria-label="Next article: Setting up AutoResponders in cPanel" href="/docs/setting-up-autoresponders-in-cpanel" rel="next">
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
    </li>
</ul>
</div>
