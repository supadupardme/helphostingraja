---
title: How to set up Email Default Address in cPanel
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
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-07-08T11:14:20+00:00" itemprop="dateModified">
Last Updated: 08 July 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">
<h1 style="text-align: center; font-size: x-large;"><span style="font-size: x-large;"><strong>How to set up Email Default Address in cPanel</strong></span></h1>
<p dir="ltr"> </p>
<p dir="ltr"><span style="font-size: large;">This option of cPanel <strong>email’s default address</strong> is also known as catch all address. This option will catch any email message that is sent to an invalid email id related to your domain. To give an instance if your default address address is <span id="cloakc12169e68d68a745c5c1d83da1072915">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="8375f2b64f0ce2f0a013899a-text/javascript">
				document.getElementById('cloakc12169e68d68a745c5c1d83da1072915').innerHTML = '';
				var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
				var path = 'hr' + 'ef' + '=';
				var addyc12169e68d68a745c5c1d83da1072915 = 'j&#105;mmy' + '&#64;';
				addyc12169e68d68a745c5c1d83da1072915 = addyc12169e68d68a745c5c1d83da1072915 + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';
				var addy_textc12169e68d68a745c5c1d83da1072915 = 'j&#105;mmy' + '&#64;' + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';document.getElementById('cloakc12169e68d68a745c5c1d83da1072915').innerHTML += '<a ' + path + '\'' + prefix + ':' + addyc12169e68d68a745c5c1d83da1072915 + '\'>'+addy_textc12169e68d68a745c5c1d83da1072915+'<\/a>';
		</script> and someone send emails to a misplaced address like <span id="cloak37d6749ea2d5d6648dda66384c512388">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="8375f2b64f0ce2f0a013899a-text/javascript">
				document.getElementById('cloak37d6749ea2d5d6648dda66384c512388').innerHTML = '';
				var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
				var path = 'hr' + 'ef' + '=';
				var addy37d6749ea2d5d6648dda66384c512388 = 'j&#117;mmy' + '&#64;';
				addy37d6749ea2d5d6648dda66384c512388 = addy37d6749ea2d5d6648dda66384c512388 + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';
				var addy_text37d6749ea2d5d6648dda66384c512388 = 'j&#117;mmy' + '&#64;' + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';document.getElementById('cloak37d6749ea2d5d6648dda66384c512388').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy37d6749ea2d5d6648dda66384c512388 + '\'>'+addy_text37d6749ea2d5d6648dda66384c512388+'<\/a>';
		</script>  in that case cPanel forwards that email to <span id="cloak9fa2ba29e430a74c5c2970e3e3c9c716">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="8375f2b64f0ce2f0a013899a-text/javascript">
				document.getElementById('cloak9fa2ba29e430a74c5c2970e3e3c9c716').innerHTML = '';
				var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
				var path = 'hr' + 'ef' + '=';
				var addy9fa2ba29e430a74c5c2970e3e3c9c716 = 'j&#105;mmy' + '&#64;';
				addy9fa2ba29e430a74c5c2970e3e3c9c716 = addy9fa2ba29e430a74c5c2970e3e3c9c716 + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';
				var addy_text9fa2ba29e430a74c5c2970e3e3c9c716 = 'j&#105;mmy' + '&#64;' + 'y&#111;&#117;rd&#111;m&#97;&#105;n' + '&#46;' + 'c&#111;m';document.getElementById('cloak9fa2ba29e430a74c5c2970e3e3c9c716').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy9fa2ba29e430a74c5c2970e3e3c9c716 + '\'>'+addy_text9fa2ba29e430a74c5c2970e3e3c9c716+'<\/a>';
		</script>.</span></p>
<p dir="ltr"><span style="font-size: large;"> </span></p>
<p dir="ltr"><strong><span style="font-size: large;">A Detailed Tutorial on How to Set up a Default Email Address: </span></strong></p>
<p dir="ltr"><span style="font-size: large;">Login to <strong>cPanel</strong>.</span></p>
<p dir="ltr"><span style="font-size: large;">In order to access default address feature, click the <strong>Default Address</strong> option from the mail screen of you cPanel:</span></p>
<p dir="ltr"><span style="font-size: large;">From drag &amp; drop option choose the <strong>domain</strong> or <strong>subdomain</strong> for which you want to set up a default address. Here you will have multiple options.</span></p>
<p dir="ltr"><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">If you want to forward all <strong>unrouted emails</strong> to an email id then you should enter the address in the field.</span></p>
<p dir="ltr"><span style="font-size: large;">You can also reject all <strong>unrouted email messages</strong> with an error to the senders of emails, in this situation you should enter the message which you want to send to the senders.</span></p>
<p dir="ltr"><span style="font-size: large;">From the <strong>advanced option</strong> of default address section you can discard all <strong>unrouted email</strong>, pipe them to a program or forward them to the system email account.</span></p>
<p dir="ltr"><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">Hit Change to <strong>apply</strong> your current settings.</span></p>
<p dir="ltr"><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">If you facing any difficulty in setting up default address for your account, contact our <strong>support team today</strong>.</span></p> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="How to configure Email authentication in cPanel" aria-label="Previous article: How to configure Email authentication in cPanel" href="/docs/how-to-configure-email-authentication-in-cpanel" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="cPanel Price hike and its impact on prices" aria-label="Next article: cPanel Price hike and its impact on prices" href="/docs/cpanel-price-hike-and-its-impact-on-prices" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>