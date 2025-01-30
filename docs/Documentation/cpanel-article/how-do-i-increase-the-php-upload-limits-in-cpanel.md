---
title: How Do I Increase The PHP Upload Limits in cPanel?
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
    <h1 style="text-align: center;"><span style="font-size: 24pt;">How Do I Increase The PHP Upload Limits in cPanel?</span></h1>
    <div>
        <p><span style="font-size: 14pt;"> </span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">In this article, we will learn how to increase the PHP upload limit in the Cpanel. You can increase using Select a PHP version. Using this interface you can also change the PHP version which is required for the website and it also has a set of the most commonly-referenced configuration options for PHP. It will also help you to diagnose problems with how your web site handles PHP packages. PHP has several configuration options to limit resources consumed by scripts. By default, PHP is set to allow uploads of files with a size of 2MB or less.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;"> With default size, you will be only able to upload small files in webmail or with a PHP script, but larger files cannot be uploaded or you get "The page cannot be displayed" error when you push the "Send Message" button.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;"> While there are several ways to remove this cap on file size, we’ll be working with three settings within PHP that should deal with the upload limit. Let’s define the settings first so that you know what you’re actually doing.</span></p>
        <p> </p>
        <ol>
            <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-weight: 400; font-size: 14pt;">Upload_max_filesize: This defines the maximum upload limit for files.</span></li>
            <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-weight: 400; font-size: 14pt;">Post_max_size: This defines the maximum upload limit that will be handled in a POST request</span><span style="font-weight: 400; font-size: 14pt;">.</span></li>
            <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-weight: 400; font-size: 14pt;">Memory_limit: This defines how much memory is allocated for PHP. This number should be equal to or higher than upload_max_filesize.</span></li>
        </ol>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>Steps to increase PHP Upload Limit and Post Max Size and Memory Limit:</b></span></p>
        <p><span style="font-size: 14pt;"><b>Step 1: </b><span style="font-weight: 400;">Login to </span><span style="font-weight: 400;">cPanel Server</span><span style="font-weight: 400;"> &gt;&gt; search for  ‘Select PHP Version’</span></span>
        </p>
        <p> </p>
        <p><span style="font-size: 14pt;"><span style="font-weight: 400;"><img src="https://image.hostingraja.in/images/helphostingraja/php-ipload-limits.webp" /></span></span>
        </p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>Step 2:</b><span style="font-weight: 400;"> click on select PHP version under software  &gt;&gt; Click on ‘Switch To PHP Options’</span></span>
        </p>
        <p> </p>
        <p><img src="https://image.hostingraja.in/images/helphostingraja/php-upload-limit-two.webp" /></p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>Step 3: </b><span style="font-weight: 400;">After clicking on Switch to PHP Options &gt;&gt; then you need to set the following values  and after making the changes remember to click on apply </span></span>
        </p>
        <ol>
            <ol>
                <ol>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>Memory_limit</b><span style="font-weight: 400;"> : Set memory_limit to </span><b>256M</b><span style="font-weight: 400;">. memory_limit describes the maximum amount of memory a script can allocate. It is recommended to set this to the maximum available value.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>Upload_max_filesize: </b><span style="font-weight: 400;">Set upload_max_filesize to </span><b>32M</b><span style="font-weight: 400;">. upload_max_filesize describes the maximum size of an uploaded file. It must be larger than the theme file mentioned in the example.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>Post_max_size: </b><span style="font-weight: 400;">Set post_max_size to </span><b>64M</b><span style="font-weight: 400;">. post_max_size has a similar functionality to upload_max_filesize. Make it larger than 19 MB (theme file) as well.</span></span>
                    </li>
                </ol>
            </ol>
        </ol>
        <p> </p>
        <p><span style="font-size: 14pt;"><span style="font-weight: 400;"><img src="https://image.hostingraja.in/images/helphostingraja/php-upload-limit-three.webp" /></span></span>
        </p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>Step 4:</b><span style="font-weight: 400;"> After you do required changes &gt;&gt; Click ‘Save’ button to save the changes.</span></span>
        </p>
        <p><span style="font-weight: 400; font-size: 14pt;">The other PHP directives that are provided by way the select PHP version interface are listed with their description for each of the directives :</span></p>
        <ol>
            <ol>
                <ol>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>file_uploads: </b><span style="font-weight: 400;">You can specify whether the server should allow PHP scripts to receive files through HTTP.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>include_path: </b><span style="font-weight: 400;">Specifies the Directories for that they require &amp; include, fopen(), file(), readfile(), and file_get_contents() functions query.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>max_execution_time: </b><span style="font-weight: 400;">his is used specify the max amount of time in seconds that the server should allow a PHP script to execute before the script is terminated, this is used to ensure that the server is not lacking or slow down because of poorly written scripts </span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>max_input_time:</b><span style="font-weight: 400;"> this is used to specify the  max time in seconds to process information which submit to PHP scripts like file uploads, and it ensures that server does not slow down or lacking because of overloaded scripts.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>memory_limit: I</b><span style="font-weight: 400;">t is used to ensure that the server’s memory is not overload with poorly written script hence the maximum number of bytes of memory that script can use is specified. If the value is -1 then it indicates that no memory limit exists </span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>upload_max_filesize: </b><span style="font-weight: 400;">Specifies the maximum number of bytes which can be uploaded.</span></span>
                    </li>
                    <li style="font-weight: 400; line-height: 1.2; padding-bottom: 12px;"><span style="font-size: 14pt;"><b>session.save_path: </b><span style="font-weight: 400;">the path where the system stores visitors' unique user IDs and these IDs are used to store information about the user's session, or time spent on your website, using PHP you to create web content specific to a given visitor and session.</span></span>
                    </li>
                </ol>
            </ol>
        </ol>
        <p><span style="font-size: 14pt;"><b>cPanel server change php.ini using the command line</b></span></p>
        <p> </p>
        <p><span style="font-weight: 400; font-size: 14pt;">You can change the PHP.INI config values by logging into to your command line, using SSH or putty program or directly logging into server console.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">Once you login into your server in SSH, You will reach the bash prompt or shell.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;"> You can find out the PHP.INI file using the following command</span></p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>php -i | grep "php.ini"</b></span></p>
        <p> </p>
        <p><span style="font-weight: 400; font-size: 14pt;">Configuration File (php.ini) Path =&gt; /etc/php5/cli</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">Loaded Configuration File =&gt; /etc/php5/cli/php.ini</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">As you can see the loaded config file above, Edit it using an editor such as vim/emacs/nano and modify the desired values.</span></p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>$ vim </b><b> /etc/php5/cli/php.ini</b></span></p>
        <p> </p>
        <p><span style="font-weight: 400; font-size: 14pt;">You can write a simple test.php file with the following content to know the php.ini path.</span></p>
        <p> </p>
        <p><span style="font-size: 14pt;"><b>&lt;?php</b></span></p>
        <p><span style="font-size: 14pt;"><b>phpinfo();</b></span></p>
        <p><span style="font-size: 14pt;"><b>?&gt;</b></span></p>
        <p> </p>
        <p><span style="font-weight: 400; font-size: 14pt;">When you execute the command, You will know the loaded php.ini file and edit it.</span></p>
        <p><span style="font-weight: 400; font-size: 14pt;">If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call, email, ticket system or call out to our toll-free number.</span></p>
        <p><span style="font-weight: 400;"> </span></p>
    </div>
</div>
<ul class="pager pagenav">
    <li class="previous">
        <a class="hasTooltip" title="How to configure e-mail authentication in cPanel" aria-label="Previous article: How to configure e-mail authentication in cPanel" href="/docs/how-to-configure-e-mail-authentication-in-cpanel" rel="prev">
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
    </li>
</ul>
</div>
