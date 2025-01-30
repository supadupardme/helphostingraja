---
title: How to Protect Directories with a Password in cPanel
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
    <h1 style="text-align: center;"><span style="font-size: xx-large;"><strong>How to Protect Directories with a Password in cPanel</strong></span></h1>
    <p dir="ltr"><span style="font-size: large;"><br/>In this tutorial we are going to discuss how to <strong>protect directories with a password</strong> using cPanel. Visit to your <strong>password protected directory</strong> must type username and password in order to see the contents of those directories.<br/><br/>It is very important to protect your WordPress admin (wp-admin) section. Though our <a href="https://www.hostingraja.in/hosting/wordpress-hosting/">wordpress hosting plan</a> comes with many security features, But still we strongly recommend to protect your admin section even in the PHP or any other CMS based websites.<br/></span></p>
    <br/>
    <p dir="ltr" style="text-align: left;"><span style="font-size: x-large;"><strong>How Password Protection works?</strong></span></p>
    <div><span style="font-size: large;">The password protection is used to secure your website hosting and files. <br/><br/></span></div>
    <p><span style="font-size: large;">We provide cPanel in all our <a href="https://www.hostingraja.in/">linux shared web hosting</a>. Kindly follow the below steps to protect your directory</span></p>
    <p><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;">A directory can be protected with a password from your Linux server with cPanel</span></p>
    <p dir="ltr"><span style="font-size: large;">cPanel &gt;Security &gt;Password Protect Directories.</span></p>
    <p dir="ltr"><span style="font-size: large;">Once the page is opened, you should see a list of the directories on your hosting account. You can open a directory in order to view its contents by clicking on the folder icon next to its name. Once you have browsed to the directory you are planning to protect, simply click on its name. This should open a new page on which you will be able to create an account that has access privileges to that directory once it has been password protected. Once you have created an account, simply check the box next to “Password Protect This Directory” and save your settings. Password protecting directories is recursive, meaning that once a directory is password protected all sub-directories in it will also be locked.</span></p>
    <p dir="ltr"><span style="font-size: large;">It is very crucial to <strong>understand how password protection</strong> actually works. When you opt to protect a directory with password using cPanel, cPanel then creates a rule in <strong>.htaccess file</strong> of your website. This rule states that the particular folder or directory is protected with a password and the visitor require to use the accurate username and password to see the files of that particular directory.</span></p>
    <br/><strong><span style="font-size: large;"><span style="font-size: x-large;">Steps to Protect a Directory with Password:</span><br/><br/></span></strong>
    <ul>
        <li><span style="font-size: large;"><strong>Login to cPanel</strong>.</span></li>
        <li><span style="font-size: large;">Locate to the Files area and hit <strong>directory privacy</strong>.</span></li>
    </ul>
    <p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/protect-directories1.png" width="800" height="175" border="0" /></span></p>
    <br/>
    <ul>
        <li><span style="font-size: large;">Choose the directory you wish to protect with a <strong>password</strong> and once you click any option it will redirect you to <strong>Set Permissions window</strong>.</span></li>
    </ul>
    <p dir="ltr"><span style="font-size: large;"><br/><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/protect-directories2.png" width="799" height="477" border="0" /></span></p>
    <br/>
    <ul>
        <li><span style="font-size: large;">On this hit the check box labeled as <strong>Password protect the directory</strong>. Don’t forget to enter the <strong>name for the folder</strong> you are going to protect with a password.</span></li>
    </ul>
    <br/>
    <p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/protect-directories3.png" width="805" height="277" border="0" /></span></p>
    <br/>
    <ul>
        <li><span style="font-size: large;">Click <strong>save button</strong> to save the process you have completed above.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">Now on this step you need to create a <strong>username and password</strong> to access the password protected directory.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">Hi <strong>save button</strong> to save the user that you have created.</span></li>
    </ul>
    <p dir="ltr"><span style="font-size: large;"><br/><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/help/protect-directories4.png" width="800" height="325" border="0" /></span></p>
    <br/>
    <ul>
        <li><span style="font-size: large;">Now you have <strong>protected your directory</strong> using a password and when a user provide correct user name password can view the contents of your directory.</span></li>
    </ul>
    <br/>
    <p dir="ltr" style="text-align: left;"><span style="color: #000000; font-size: x-large;"><strong>Removing password protection from a directory</strong></span></p>
    <div><strong><span style="font-size: large;"> </span></strong></div>
    <p dir="ltr"><span style="font-size: large;">You can also <strong>remove password from protected directory</strong> when you don’t wish to protect any directory with a password. In order to delete protection of a directory you don’t have to remove username and password that you created for protecting the directories. The username and password is reserved when you remove a password protection from your directory, it will just become inactive. If in future you want to <strong>re enable password protection</strong> for the directory, you can then use the same username and password.</span></p>
    <br/>
    <p dir="ltr"><span style="font-size: x-large;"><strong>Follow below instructions to remove password protection from a directory: </strong></span></p>
    <ul>
        <li><span style="font-size: large;"><strong>Login to cPanel account</strong>.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">Go to the <strong>files area</strong> of cPanel, click <strong>Directory Privacy</strong>.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">Then hit the <strong>directory name</strong> for which you are going to remove password protection.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">Under the<strong> security settings</strong>, hit the checkbox labeled as <strong>clear the password protect this directory</strong>.</span></li>
    </ul>
    <ul>
        <li><span style="font-size: large;">And then click <strong>save</strong>.</span></li>
    </ul>
    <br/>
    <p dir="ltr"><span style="font-size: large;">If you need more information, feel free to <strong>contact our support team</strong>.</span></p>
</div>
<ul class="pager pagenav">
    <li class="previous">
        <a class="hasTooltip" title="How to Install Applications in cPanel?" aria-label="Previous article: How to Install Applications in cPanel?" href="/docs/how-to-install-applications-in-cpanel" rel="prev">
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
    </li>
    <li class="next">
        <a class="hasTooltip" title="How to Create Custom Error Pages in cPanel?" aria-label="Next article: How to Create Custom Error Pages in cPanel?" href="/docs/how-to-create-custom-error-pages-in-cpanel" rel="next">
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
    </li>
</ul>
</div>