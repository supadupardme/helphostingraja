---
title: Upload your website files in cPanel
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
    <span style={{fontSize: "24pt"}}><strong>Upload your website files in cPanel</strong></span>
    <p><span style={{fontSize: "14pt"}}>C-Panel is the abbreviation of Control Panel.<span style={{fontWeight: 400}}> cPanel is a very powerful interface used by the webmasters to do their regular jobs in their web hosting account it could be a shared, vps server or dedicated server. cPanel makes it simple for the users to generate emails for their domains, and easy to make numerous FTP accounts. cPanel helps in checking the disk space and bandwidth you have been used for the month. cPanel additionally offers you with the information like how many emails have been used and how many domains have been attached to your account and also the current state of the server you have been hosted on.</span></span></p>
    </p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>As a website owner in some situations, it is very important to upload files to a cPanel account.  This process can be easily achieved via </span>File Manager available inside the cPanel tool.</p>
        <span
        style={{fontWeight: 400}}> You must have provided with </span><span style={{fontWeight: 400}}>cPanel</span><span style={{fontWeight: 400}}> by your hosting provider.</span></span>
    </p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>There are many advantages of using Cpanel, it is easy to learn and has an easy to use interface, has wide forum where you get access to many tutorials and support for using Cpanel, It has an auto installer software to install software easily, and you can access a range of modules including Files, Preferences, Databases, Web Applications, Domains, Metrics, Security, Software, Advanced and Email modules .</span></p>
    <p><span style={{fontSize: "14pt"}}>Here on this page, we are going to this process through an example so that it will be easy for you to understand: <span style={{fontWeight: 400}}>Suppose you want to upload the xyz.html file to the public_html folder in your file manager. When you upload the file and visit the same file through w browser, you'd go to yourdomain.com/xyz.html. If you want to put the file inside a subfolder of your website called XYZ, then to open that file in a web browser you need to go to yourdomain.com/xyz/xyz.html</span></span></p>
    </p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Steps for Uploading a File using the cPanel:</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Step 1:<span style={{fontWeight: 400}}> Log into </span>cPanel<span style={{fontWeight: 400}}> of your website</span></span></p>
    </p>
    <p><span style={{fontSize: "14pt"}}>Step 2:<span style={{fontWeight: 400}}> On the main page of cPanel’s files section &gt;&gt; choose </span>File Manager<span style={{fontWeight: 400}}> under the files section. </span></span></p>
    </p>
    <p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}><br /><br /></span></p>
    <p dir="ltr"><span style={{fontSize: "14pt"}}><strong>Step-3:</strong> Click <strong>setting</strong> option in the Window of file manager</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}> </span></p>
    <p dir="ltr"></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}><span style={{fontSize: "14pt"}}>Step 4:<span style={{fontWeight: 400}}> On this step choose where you want to start (root folder for your domain). Like we are going to use the root folder as the public_html folder. Considering we are going to upload to the </span>public_html</p>
        <span
        style={{fontWeight: 400}}> we did not have to navigate to any other place:</span>
            </span>
            <br />
            <br />
            </span>
    </p>
    <p dir="ltr"></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Generally, the root folder for your primary domain will be public_html and for add-on domain, the root folder will be /public_html/addon_domain.com or /addon_domain.com (public_html or in the home directory) </span></p>
    <p><span style={{fontSize: "14pt"}}>Step 5: After you navigate to the folder where you need to upload file &gt;&gt; Click on the Upload icon on the top as shown:</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}> </span></p>
    <p dir="ltr"><span style={{fontSize: "x-large"}}><br /><br /></span></p>
    <p><span style={{fontSize: "14pt"}}>Step 6:<span style={{fontWeight: 400}}> You will navigate to the file you want to </span>upload<span style={{fontWeight: 400}}> from your system, select the file and click Choose file button.</span></span></p>
    </p>
    <p><span style={{fontSize: "14pt"}}>Step 7:<span style={{fontWeight: 400}}> Then </span>click upload<span style={{fontWeight: 400}}> on next screen &gt;&gt; and the file will be uploaded.Now in the </span>browser<span style={{fontWeight: 400}}> of your system visit the file and check it uploaded correctly or not.</span></span></p>
    </p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Common problems while uploading your website files in cPanel:</span></p>
    <p><span style={{fontSize: "14pt"}}>Uploaded images not showing in the PrestaShop?</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>The simple reason for this problem is that the images are uploaded with wrong permissions. So, the Apache service will not be able to access correctly and ends up with 403 error. To avoid these users need to access the account through FTP or File Manager in cPanel and look for the images.inc.php file.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Uploaded your files but the site is not opening in the browser?</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>While logging in to your FTP account, you can see folders like mail, public_html, tmp, public_ftp, www etc. All the files have to be uploaded to the "public_ftp directory”. And need to ensure the main page is known as "index.php". All the file must be in the lowercase letters. Once the files are uploaded, the website can be accessed with a temporary URL which will be mentioned in the "Account Setup" letter. Once the domain name points to HostingRaja's DNS nameservers, the website can be accessed with your domain name.</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Note:</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>&gt;&gt; When you are uploading the file in cpanel ensure that you uploading the file in the correct path.Most of them commonly face a issue when they uploaded the file path in the wrong directory.</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>&gt;&gt; Also, ensure that you have updated the DNS of your website.Your Domain should point to hosting account </span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>And today with HostingRaja VPS server you get Free Cpanel where<span style={{fontWeight: 400}}> you can easily manage and handle your website as per your requirements. Not only that we also provide </span></p>
        highly secured VPS Server<span style={{fontWeight: 400}}> for our customers at an affordable price with amazing features, offers, and discounts. With our VPS server, we provide the latest security features.</span></span>
    </p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>If you need any assistance while uploading your website files in cPanel feel free to contact our technical team members as they are available 24/7 via phone call, email, ticket system https://support.hostingraja.in/ or login to client area to raise ticket.</span></p>
    <p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
</div>

    
        
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 
    
    
        
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 
    

</div>