---
title: >-
  How to set redirection for without WWW to with WWW URL in Tomcat using
  UrlRewriteFilter
excerpt: >-
  Essentials of launching your Cloud Office startup with this comprehensive
  tutorial. Hosted by HostingRaja.
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
<div itemprop="articleBody">
    <h1 dir="ltr" style="text-align: center;"><span style="font-size: x-large;"><strong>How to set redirection for without WWW to with WWW URL in Tomcat using UrlRewriteFilter</strong></span></h1>
    <div> </div>
    <p dir="ltr"><strong><span style="font-size: x-large; font-family: helvetica; color: #000000;">What is the meaning of WWW?</span><br /><br /></strong></p>
    <p dir="ltr">WWW stands for World Wide Web is an information space with the combination of <strong>all resources and users on the Internet</strong>. Which allows the retrieval and display of text and media to your computer. It is a basically a system of <a href="https://www.hostingraja.in/server/dedicated-servers/">Internet web servers</a> where the documents are formatted into an HTML language which supports links to other documents as well as graphics audio and videos.<br /><br /></p>
    <p dir="ltr"><strong><span style="font-size: x-large; font-family: helvetica; color: #000000;">Difference between WWW vs non-WWW?</span><br /><br /></strong></p>
    <p dir="ltr">When adding www in front of the <a href="https://www.hostingraja.in/domains/">domain name registration india</a> or <strong>website it acts has a hostname</strong>. Which helps with DNS flexibility. Which restrict cookies when using multiple subdomains. The reasons to use www primarily apply to the largest websites which receive millions of page views per day, websites with a large number of services across several subdomains, and virtually any website hosted in “the vps or cloud server” by an application service provider.<span style="font-size: 12.16px;"> <br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Whereas non-WWW domains also referred has naked domains do not have a technical advantage.<br /><br /></strong></span></p>
    <p dir="ltr"><span style="font-family: helvetica; font-size: x-large;"><strong>What is the use of www.?<br /><br /></strong></span></p>
    <p dir="ltr">Using www makes you more prepared to handle the challenges of a growing website beyond a single server which is good for <strong>SEO to improve the page ranking.<br /><br /></strong></p>
    <div class="domain-register-middle-area-block-full-width">
        <div class="domain-register-middle-blocks one">
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/web-hosting.jpg" alt="Web Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title"><a href="https://www.hostingraja.in/">Web Hosting</a></div> at a very Affordable Price
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 69</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/">Get it Now</a></div>
                </div>
            </div>
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/vps-hosting.jpg" alt="VPS Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title">VPS Hosting</div> Customized for all technologies
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 732</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/server/vps-servers/">Get it Now</a></div>
                </div>
            </div>
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/cloud-hosting.jpg" alt="Cloud Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title">Cloud Hosting</div> Security &amp; Performance Guaranteed
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 2680</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/cloud/">Get it Now</a></div>
                </div>
            </div>
        </div>
        <div class="domain-register-middle-blocks">
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/windows-hosting.jpg" alt="Windows Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title">Windows Hosting</div> Reliable Windows Hosting
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 199</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/">Get it Now</a></div>
                </div>
            </div>
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/dedicated-hosting.jpg" alt="Dedicated Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title"><a href="https://www.hostingraja.in/server/dedicated-servers">Dedicated Server</a></div> Fully managed Servers in India
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 4499</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/server/dedicated-servers">Get it Now</a></div>
                </div>
            </div>
            <div class="domain-register-middle-block">
                <div class="domain-register-middle-block-top">
                    <div class="domain-register-middle-block-top-img"><img src="https://image.hostingraja.in/images/articles/registerdomains/middle-blocks/linux-hosting.jpg" alt="Linux Hosting" border="0" /></div>
                    <div class="domain-register-middle-block-top-titles">
                        <div class="domain-register-middle-block-top-title">Linux Hosting</div> Reliable Linux hosting plans
                    </div>
                </div>
                <div class="domain-register-middle-block-bottom">
                    <div class="domain-register-middle-block-bottom-price">Starts at Rs. 69</div>
                    <div class="domain-register-middle-block-top-button"><a href="https://www.hostingraja.in/">Get it Now</a></div>
                </div>
            </div>
        </div>
    </div>
    <p dir="ltr"><span style="font-size: x-large; font-family: helvetica;"><strong>What is UrlRewriteFilter?<br /></strong><br /><span style="font-size: 12pt;">UrlRewriteFilter is a java web Filter for any compliant web application servers like Tomcat, JBoss, resin running in HostingRaja they provide <a href="https://www.hostingraja.in/server/vps-servers/">cheap vps hosting India </a><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;cheap vps hosting india&quot;}" data-sheets-userformat="{&quot;2&quot;:14979,&quot;3&quot;:{&quot;1&quot;:0},&quot;4&quot;:[null,2,16573901],&quot;10&quot;:0,&quot;12&quot;:0,&quot;14&quot;:[null,2,0],&quot;15&quot;:&quot;Calibri&quot;,&quot;16&quot;:12}">solution</span> which enables rewrite URLs before they get to your code. It is just like an Apache's mod_rewrite.</span><br /><span style="font-size: 12pt;">Resolution.<br /></span><br /></span></p>
    <p><span style="font-size: 14pt;"><b>Follow the below steps :</b></span></p>
    <p><span style="font-size: 14pt;"><b>Step 1: </b><span style="font-weight: 400;"> Download UrlRewriteFilter jar file from http://hostingraja.info/urlrewritefilter-4.0.3.jar and upload this file into </span><b>WEB-INF/lib</b><span style="font-weight: 400;"> directory of your website. </span></span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">Example your website folder is /home/hostingraja/public_html, kindly upload this file to /home/hostingraja/public_html/WEB-INF/lib this directory </span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">Or </span></p>
    <p><span style="font-size: 14pt;"><span style="font-weight: 400;">You can also add the maven dependency in your </span><b>pom.xml</b><span style="font-weight: 400;"> file under your website folder </span></span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: helvetica;"><br /><span style="font-size: 12pt;"><code>&lt;dependency&gt;</code></span><br /><span style="font-size: 12pt;"><code> &lt;groupId&gt;org.tuckey&lt;/groupId&gt;</code></span><br /><span style="font-size: 12pt;"><code> &lt;artifactId&gt;urlrewritefilter&lt;/artifactId&gt;</code></span><br /><span style="font-size: 12pt;"><code> &lt;version&gt;4.0.3&lt;/version&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;/dependency&gt;</code></span><br /><br /></span></p>
    <p><span style="font-size: 14pt;"><b>Step 2:</b><b> After you add jar or maven dependency &gt;&gt; </b><span style="font-weight: 400;">Go to </span><b>WEB-INF/web.xml</b><span style="font-weight: 400;"> in your website folder and add below code (near the top above any Servlet mappings):</span></span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: helvetica;"><br /><span style="font-size: 12pt;"><code>&lt;filter&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;filter-name&gt;UrlRewriteFilter&lt;/filter-name&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;filter-class&gt;org.tuckey.web.filters.urlrewrite.UrlRewriteFilter&lt;/filter-class&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;/filter&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;filter-mapping&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;filter-name&gt;UrlRewriteFilter&lt;/filter-name&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;url-pattern&gt;/*&lt;/url-pattern&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;dispatcher&gt;REQUEST&lt;/dispatcher&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;dispatcher&gt;FORWARD&lt;/dispatcher&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;/filter-mapping&gt;<br /></code></span><br /><span style="font-size: 12pt;">Refer the below screenshot <br /></span><br /><img src="https://image.hostingraja.in/images/helphostingraja/tomcat-url-redirection.webp" alt /><br /><br /><br /></span></p>
    <p><span style="font-size: 14pt;"><b>Step 3:</b> <span style="font-weight: 400;">Create file </span><b>urlrewrite.xml</b><span style="font-weight: 400;"> in WEB-INF and add below code:</span></span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: helvetica;"><br /><span style="font-size: 12pt;"><code>&lt;urlrewrite&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;rule&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;name&gt;Domain Name Check for example.com&lt;/name&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;condition name=”host” operator=”equal”&gt;^example.com&lt;/condition&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;from&gt;^(.*)$&lt;/from&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;to type=”redirect”&gt;http://www.example.com$1&lt;/to&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;/rule&gt;</code></span><br /><span style="font-size: 12pt;"><code>&lt;/urlrewrite&gt;<br /></code></span><br /></span></p>
    <p><span style="font-size: 14pt;"><b>Note: Replace example.com with the original domain name.</b></span></p>
    <p><span style="font-size: 14pt;"> </span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">The above code snippet helpful to redirect the domain from without www to with www . if you want to some other rule then write a proper rule on this file too. </span></p>
    <p><span style="font-size: 14pt;"> </span></p>
    <p><span style="font-size: 14pt;"><b>Step 4:</b><span style="font-weight: 400;"> Restart Tomcat service to reflect the changes. Go to your tomcat folder and run the below command for restarting the tomcat </span></span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">Example (/usr/local/tomcat8 or /usr/local/tomcat9 like that )</span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: helvetica;"><span style="font-size: 12pt;"><br /><code>sh bin/shutdown.sh </code></span><br /><span style="font-size: 12pt;"><code>sh bin/startup.sh<strong> <br /></strong></code></span></span></p>
    <p dir="ltr"><span style="font-size: 12pt;"><code> <br /></code></span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">Following the above steps you can set redirection for URL without WWW to with WWW</span></p>
    <p dir="ltr"><span style="font-size: 14pt;"><code><br /></code><b>If you need any assistance , feel free to contact our technical team members as they are available 24/7 via phone call, email, ticket system or call out toll-free no 1800-123-8642.</b></span></p>
    <p dir="ltr"><span style="font-size: 12pt;"><code> </code></span></p>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to solve ERROR: Connection dropped by imap server Query: SELECT &quot;INBOX&quot; in Webmail " aria-label="Previous article: How to solve ERROR: Connection dropped by imap server Query: SELECT &quot;INBOX&quot; in Webmail " href="/docs/how-to-solve-error-connection-dropped-by-imap-server-query-select-inbox-in-webmail-cpanel" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to install WordPress Theme Manually" aria-label="Next article: How to install WordPress Theme Manually" href="/docs/how-to-install-wordpress-theme-manually" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>