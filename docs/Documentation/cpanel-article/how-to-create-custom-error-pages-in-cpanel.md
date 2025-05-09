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

    

<div itemprop="articleBody">
    <span style={{fontSize: "xx-large"}}><strong>How to Create Custom Error Pages in cPanel?</strong></span>
    <p dir="ltr"><span style={{fontSize: "large"}}>Sometime when a visitor to your website gets an error message, for example <strong>400</strong> (Bad request), 403 (Forbidden), or 500 (Internal server error), they will be seeing the default error pages. But if you want you can easily customize these pages using<strong> cPanel’s error pages</strong> option. Here in this help section we are going to discuss about how to create custom error page in your <strong>web hosting account.</strong></span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong> </strong></span></p>
    <strong><span style={{fontSize: "large"}}>Creating a Custom Error page in cPanel</span></strong>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong>Login to cPanel</strong> of your website.</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>Locate <strong>Advanced section</strong> in cPanel and click error pages.</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}></span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>You may have <strong>multiple domain name</strong> under one cPanel account, select the one for which you want to create <strong>custom error pages</strong> from the Managing menu.</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}></span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>Here on this step you will find the list of most common errors, hit the one you are planning to design a <strong>customized error page</strong> for. The available options to choose from are 400 (Bad request), 401 (Authorization required), 403 (Forbidden), 404 (Not found) etc. Hit show all HTTP code if you want to see additional error codes. Hit the option you want to edit. Here I am going to select 404 error code.</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>Once you hit your desired option you will be landed on editor page. You can type HTML program in the text box given or just insert redefined tags if you wish. <br /></span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong>Once you are done hit the save button.</strong><br /><br /></span></p>
    <strong><span style={{fontSize: "large"}}>Setting up your  .htaccess File</span></strong>
    <p dir="ltr"><span style={{fontSize: "large"}}>By pressing right click of your mouse edit the<strong> .htaccess file</strong> and create a rule for the error pages you created. You can file .htaccess file inside the public_html of your file manager. Given below is the sample of the file formatting: <br /></span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>ErrorDocument 404 /404.shtml</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>ErrorDocument 402 /402.shtml</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>ErrorDocument 410 /410.shtml</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}>ErrorDocument 414 /414.shtml</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong>Save your .htaccess file</strong> and now when someone visit your website and an error message trigger, it will display your custom error page which you created for particular error code.</span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong>Facing any difficulty?</strong> Don’t worry our <strong>support team</strong> is here to help. Contact our <strong>Support team now</strong>.</span></p>
</div>

    
        
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 
    
    
        
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 
    

</div>