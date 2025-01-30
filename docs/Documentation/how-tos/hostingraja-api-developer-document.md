---
title: HostingRaja API Developer Document
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
<div class="page-header">
    <h2 itemprop="headline">
HostingRaja API Developer Document </h2>
</div>
<dl class="article-info muted">
    <dt class="article-info-term">
</dt>
</dl>
<div itemprop="articleBody">
    <h2 dir="rtl" style="text-align: center;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"> </span></strong></span></h2>
    <div style="text-align: center;"><span style="font-size: 24pt; color: #000000; background-color: #ffffff;"><strong>HostingRaja API Developer Document</strong></span></div>
    <p><span style="font-size: 12pt; color: #000000; background-color: #ffffff;">HostingRaja offers an API service that allows you to easily create cloud servers. However, before you can use our API service, you'll need to pay a security deposit of Rs. 1000/- from your client area dashboard. Once you've completed the payment, you can start creating cloud servers through our API, making it quick and easy to manage your cloud infrastructure. With our API service, you can easily scale your cloud servers up or down, add or remove resources, and much more, all from a simple and intuitive interface.</span></p>
    <p style="text-align: left;"><span style="font-size: 18pt; color: #000000; background-color: #ffffff;"><strong><br/>To generate API keys for accessing our API services, please follow these steps:<br/></strong></span>
        <br/><span style="font-size: 12pt;"><strong>1) Log in to your client area using your HostingRaja credentials.</strong></span></p>
    <span style="font-size: 14pt; color: #000000; background-color: #ffffff;">2) From the left-side menu, click on the "API" option.   <img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/client-area-api.webp" /><br/><br/>3) Click on the button provided to generate a payment link for making a security deposit.<br/></span>
    <h1 dir="rtl" style="text-align: left;"><strong style="color: #000000; font-size: 14pt; font-family: Tahoma, Helvetica, Arial, sans-serif;"> </strong></h1>
    <span style="font-size: 14pt; color: #000000; background-color: #ffffff;"><strong><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/my-api.webp" /><br/></strong><span style="font-size: 12pt;">4) Once you click the button to pay the security deposit, a payment link will be generated. You can then proceed to complete the payment by clicking on the link provided.</span>
    <br/><strong><br/></strong></span><span style="font-weight: 400;"><span style="font-size: 14pt; color: #000000; background-color: #ffffff;"><strong><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/generate-api-key.webp" /><br/></strong></span></span>
    <span
    style="font-size: 14pt; background-color: #ffffff;"><strong><br/></strong><span style="color: #000000;">5) To access our API, you need to whitelist your IP address by providing a comma-separated list of your IP addresses.</span></span>
        <br/>
        <h1 dir="rtl" style="text-align: left;"><span style="color: #000000;">.Once you generated the authorization token &amp; secret key. You need to whitelist your IP address separated by comma to access our API</span></h1>
        <h1 dir="rtl" style="text-align: left;"><span style="font-size: 24pt; background-color: #ffffff;"><span style="color: #000000;"> </span></span></h1>
        <h1 dir="rtl" style="text-align: left;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b>Note : Please note that if you do not whitelist your IP address using the above steps, you will not be able to connect to our API</b></span></span></strong></span></h1>
        <h1 dir="rtl" style="text-align: left;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/helphostingraja/whitelist-ips.webp" /><br/></b></span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;">API Access URL</span></span></strong></span>: <a href="https://www.hostingraja.in/api/"><b>https://www.hostingraja.in/api</b></a></h1>
        <h1 dir="rtl" style="text-align: left;"><span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 14pt; background-color: #ffffff;"><strong><span style="color: #000000;">Authentication</span></strong></span><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span></strong></span></h1>
        <p><span style="font-size: 12pt; color: #000000; background-color: #ffffff;"><strong><span style="background-color: #ffffff;">You have to pass your auth token &amp; secret key to each API request. For that use the below post request method for all API.</span>
            <br/>
            <br/>
            <br/><span style="font-size: 14pt;">Post Request :</span></strong>
            <br/><strong><br/></strong></span>
        </p>
        <table style="height: 158px;" border="1O" width="801">
            <caption> </caption>
            <tbody>
                <tr>
                    <td style="width: 193.25px; text-align: center;"><span style="font-size: 12pt; background-color: #ffffff; color: #333399;"><strong>Parameter</strong></span></td>
                    <td style="width: 193.25px; text-align: center;"><span style="font-size: 12pt; background-color: #ffffff; color: #333399;"><b>Type</b></span></td>
                    <td style="width: 193.25px; text-align: center;"><span style="font-size: 12pt; background-color: #ffffff; color: #333399;"><strong>Description</strong></span></td>
                    <td style="width: 193.25px; text-align: center;"><span style="font-size: 12pt; background-color: #ffffff; color: #333399;"><b>Required</b></span></td>
                </tr>
                <tr>
                    <td style="width: 193.25px; text-align: center;"><strong>auth_key</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>string</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>Your API Auth Token</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>Required</strong></td>
                </tr>
                <tr>
                    <td style="width: 193.25px; text-align: center;"><strong>secret_key</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>string</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>Your secret Key</strong></td>
                    <td style="width: 193.25px; text-align: center;"><strong>Required</strong></td>
                </tr>
            </tbody>
        </table>
        <div class="full-width-block gray-color-bg p-2" style="text-align: left;">
            <br/><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><br/><strong>   Example Request (CURL):</strong><br/> <br/></span></span>
            </span>
            <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-weight: 400; font-size: 14pt;">curl -X POST \<br/></span><span style="font-size: 12pt;">-H "Content-Type: application/json"  \</span><br/><span style="font-size: 12pt;">-d ' {</span><br/><span style="font-size: 12pt;">      "auth_token": "YOUT_AUTH_TOKEN",</span><br/><span style="font-size: 12pt;">      "secret_key": "YOUR_SECRET_KEY"</span><br/><span style="font-weight: 400; font-size: 12pt;">}' \</span></pre>
            <p style="text-align: center;"><span style="font-size: 18pt; color: #000000;"><strong>Get Available Images</strong></span></p>
            <p><span style="font-size: 12pt; color: #000000;"><strong>This API will provide a list of Operating Systems that we offer for creating Cloud Servers.</strong></span></p>
            <span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #999999;"><span style="background-color: #ffffff;"><strong>Post Request : </strong></span>
            <br/>
            <br/>
            </span>
            </span>
            </span>
            </span>
            </span>
            </span>
            <table style="height: 158px;" border="1O" width="801">
                <caption> </caption>
                <tbody>
                    <tr>
                        <td style="width: 194.703px; text-align: center;"><span style="font-size: 12pt; color: #333399;"><strong>Parameter</strong></span></td>
                        <td style="width: 175.828px; text-align: center;"><span style="font-size: 12pt; color: #333399;"><b>Type</b></span></td>
                        <td style="width: 197.922px; text-align: center;"><span style="font-size: 12pt; color: #333399;"><b>Description</b></span></td>
                        <td style="width: 189.547px; text-align: center;"><span style="font-size: 12pt; color: #333399;"><b>Required</b></span></td>
                    </tr>
                    <tr>
                        <td style="width: 194.703px; text-align: center;"><span style="color: #000000;"><strong>request</strong></span></td>
                        <td style="width: 175.828px; text-align: center;"><span style="color: #000000;"><strong>string</strong></span></td>
                        <td style="width: 197.922px; text-align: center;"><span style="color: #000000;"><strong>get Available Images</strong></span></td>
                        <td style="width: 189.547px; text-align: center;"><span style="color: #000000;"><strong>Required</strong></span></td>
                    </tr>
                </tbody>
            </table>
            <span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #ffffff; color: #000000; font-size: 14pt;"><span style="background-color: #999999;"><br/></span></span>
            </span>
            </span>
        </div>
        <p style="text-align: left;"><span style="font-size: 12pt; color: #000000; background-color: #ffffff;"><strong> </strong></span></p>
        <h3><span style="font-size: 14pt;"><strong><span style="color: #000000;">Example Request (CURL):<br/><br/></span></strong></span></h3>
        <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 14pt;"><i><span style="font-weight: 400;">curl  -X POST \</span></i></span>
<span style="font-size: 12pt;"><i><span style="font-weight: 400;">  -H "Content-Type: application/json" \</span></i>
<i><span style="font-weight: 400;">  -d '{</span></i>
<i><span style="font-weight: 400;">       "request ": "getAvailableImage"</span></i>
</span><i><span style="font-weight: 400;"><span style="font-size: 12pt;">  }' \</span> </span></i></pre>
        <h1 dir="rtl" style="text-align: left;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;">:Response Format</span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/><span style="font-weight: 400; color: #000000;">.The API will respond with JSON data</span><br/><br/></b></span></span></strong></span></h1>
        <h4><span style="font-size: 14pt; color: #000000;"><strong>Example response data:</strong></span></h4>
        <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 14pt;"><i><span style="font-weight: 400;">{</span></i></span>
<span style="font-size: 12pt;"><i><span style="font-weight: 400;">   "status": "success",</span></i>
<i><span style="font-weight: 400;">   "available_image":</span></i>
<i><span style="font-weight: 400;">       {</span></i></span>
<i><span style="font-weight: 400;"><span style="font-size: 12pt;"> "centos7": "CentOS-7-x64",</span> </span></i>
<span style="font-size: 12pt;"><i><span style="font-weight: 400;"> "centos7": "CentOS-7-x64-cPanel",</span></i>
</span><i><span style="font-weight: 400;"><span style="font-size: 12pt;">  }</span> <br/></span></i><span style="font-size: 12pt;"><i><span style="font-weight: 400;">}</span></i></span></pre>
        <p dir="rtl" style="text-align: center;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="font-size: 18pt;"><span style="color: #000000;"><span style="background-color: #ffffff;"><br/>:Create Server </span></span>
            </span>
            </strong>
            </span>
        </p>
        <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">The Cloud deployment API streamlines the process of setting up and managing your Cloud infrastructure. It's fast, flexible, and secure, with built-in scalability and redundancy features. Whether you're deploying a small or large-scale Cloud environment, the Cloud deployment API makes it easy to get started and achieve your goals.</span></p>
        <h3><span style="font-size: 14pt; color: #000000;"><strong>Post Request : </strong></span></h3>
        <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span>
        </strong>
        </span>
        </span>
        <table class="create" style="height: 158px;" border="1O" width="801">
            <tbody>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px; text-align: center;"> <span style="color: #333399;"><strong>Parameter</strong></span></td>
                    <td style="width: 91.25px; height: 15px; text-align: center;"><span style="color: #333399;"> <b>Type</b></span></td>
                    <td style="width: 91.25px; height: 15px; text-align: center;"> <span style="color: #333399;"><b>Description</b></span></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"> <strong>request</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>string</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>CreateVM</strong></td>
                </tr>
                <tr style="height: 25px;">
                    <td style="width: 91.25px; height: 25px;"> <strong>hostname</strong></td>
                    <td style="width: 91.25px; height: 25px;"> <strong>string</strong></td>
                    <td style="width: 91.25px; height: 25px;"><strong> Hostname for server</strong></td>
                </tr>
                <tr style="height: 9.70312px;">
                    <td style="width: 91.25px; height: 9.70312px;"> <strong>configuration</strong></td>
                    <td style="width: 91.25px; height: 9.70312px;">
                        <p><span style="font-weight: 400;"><strong>array</strong>[]</span></p>
                    </td>
                    <td style="width: 91.25px; height: 9.70312px;"><strong> Configuration Data in array, by passing below elements</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"> <strong>ram</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>int</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong> Maximum 128 GB RAM for passing configuration array elements</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"> <strong>disk</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>int</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong> Configuration array requires 40-1024 GB disk space.</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"> <strong>cpu</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>int</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong> Max 16 CPU cores for configuration array</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"> <strong>bandwidth</strong></td>
                    <td style="width: 91.25px; height: 15px;"> <strong>int</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong> Max 10 TB bandwidth for config array.</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"><strong>managed_support</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong>true/false</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong>Managed Support. Default will be false.</strong></td>
                </tr>
                <tr style="height: 15px;">
                    <td style="width: 91.25px; height: 15px;"><strong>image</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong>string</strong></td>
                    <td style="width: 91.25px; height: 15px;"><strong>Output OS key name from "getAvailableImage"</strong></td>
                </tr>
            </tbody>
        </table>
        <span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/><br/>Example Request (CURL):<br/></span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span>
        </strong>
        </span>
        <pre style="border: 1px solid #ddd; padding: 12px;"><i><span style="font-weight: 400;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" \<br/>-d '{ "request": "CreateVM",</span><span style="font-size: 12pt;"><br/>"data": {</span><br/><span style="font-size: 12pt;">            "hostname":<br/>           "YOUR_HOST_NAME", </span><span style="font-size: 12pt;">"configuration": {<br/></span><span style="font-size: 12pt;">           "ram": 2,<br/></span><span style="font-size: 12pt;">          "cpu": 1,</span><span style="font-size: 12pt;"><br/>       "disk": 50,</span><span style="font-size: 12pt;"><br/>      "bandwidth": 2,</span><span style="font-size: 12pt;"><br/>       "image":<br/>       "ubuntu",</span><span style="font-size: 12pt;"><br/>      “scaling” :<br/>      “vertical”</span><span style="font-size: 12pt;"><br/>    },</span><span style="font-size: 12pt;"><br/>     “Managed_support” : true</span><span style="font-size: 12pt;"><br/>   }<br/></span><span style="font-size: 12pt;">}' \</span></span></i></pre>
        <span style="font-size: 12pt;"><i><span style="font-weight: 400;"><br/></span></i>
        </span> <span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;">Response Format:</span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span>
        <span
        style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span>
            </strong>
            </span><span style="font-size: 12pt; color: #000000;"><strong>The API will respond with JSON data.<br/><br/>Example response data:</strong><br/><strong><br/><br/></strong></span>
            <pre style="border: 1px solid #ddd; padding: 12px;"><i><span style="font-weight: 400;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;">"status": "success", </span><br/><span style="font-size: 12pt;"> "vmid": "1234", </span><br/><span style="font-size: 12pt;"> "message": </span><br/><span style="font-size: 12pt;">"Server creation initiated successfully. You will get credentials shortly." </span><br/><span style="font-size: 12pt;">    </span><br/><span style="font-size: 12pt;">} </span><strong><span style="font-size: 12pt;"> <br/></span><br/></strong></span></i></pre>
            <span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/>Get My Servers<br/></span></span><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><br/></span></span>
            </strong>
            </span><span style="font-size: 12pt; color: #000000;"><strong>This API returns a list of servers that were created using the API request.<br/><br/></strong></span><span style="font-size: 14pt; color: #000000;"><strong>Post Request : </strong></span>
            <span
            style="font-size: 12pt; color: #000000;"><span style="font-size: 12pt; color: #000000;"><span style="font-size: 12pt; color: #000000;"><strong> <br/><br/></strong></span></span>
                </span>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 118.812px;"><span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 118.812px;"><span style="color: #333399;"><b>Type</b></span></td>
                            <td style="width: 122.531px;"><span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 118.844px;"><span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 118.812px;"><strong>request</strong></td>
                            <td style="width: 118.812px;"><strong>string</strong></td>
                            <td style="width: 122.531px;"><strong>getMyServers</strong></td>
                            <td style="width: 118.844px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 118.812px;"><strong>product_id</strong></td>
                            <td style="width: 118.812px;"><strong>int</strong></td>
                            <td style="width: 122.531px;"><strong>To get Specific server</strong></td>
                            <td style="width: 118.844px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 12pt; color: #000000;"><span style="font-size: 12pt; color: #000000;"><strong><br/></strong></span></span><span style="font-size: 12pt; color: #000000;"><strong><br/></strong></span><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b>Example Request (CURL):</b></span></span>
                </strong>
                </span>
                <pre style="border: 1px solid #ddd; padding: 12px;"><i><span style="font-weight: 400;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" \<br/>-d '{ <br/>      "request": "getMyServers",</span><span style="font-size: 12pt;"><br/></span><span style="font-size: 12pt;">“data” <br/>     ‘{<br/>         “product_id” : 1234<br/>     }’\<br/>}' \<br/></span></span></i></pre>
                <pre><br/><span style="font-size: 14pt; color: #000000;"><strong>Response Format: </strong></span><br/><span style="font-size: 14pt; color: #000000;">The API will respond with JSON data.</span><br/><span style="font-size: 14pt; color: #000000;"><strong>Example response data:</strong></span><br/><br/></pre>
                <pre style="border: 1px solid #ddd; padding: 12px;"><i><span style="font-weight: 400;"><span style="font-size: 12pt;">{<br/> "status": "success",<br/> "Data" :<br/>{<br/>“product_id1” : <br/>{ <br/>“product_id” : 1234,<br/>“hostname” : “example1.com”,<br/>“product_status” : “Active”,<br/>“created_on” : “2023-02-24”,<br/>“expired_on” : “2023-03-24”,<br/>“plan_name” : “Custom Cloud Server”,<br/>“configuration” : {<br/> “image” : “Windows 2019”,<br/> “ram” : “10 GB”,<br/> “core” : “10 Core”,<br/> “disk” : “500 GB”,<br/> “band” : “1 TB”<br/>},<br/>“current_status” : “Current Server status as per API request”,<br/>},<br/>“product_id2” <br/>{<br/> “product_id” : 4567,<br/>“hostname” : “example2.com”,<br/>“product_status” : “Product Status of<a href="https://www.hostingraja.in/"><b> HostingRaja”</b></a>,<br/>“created_on” : “2023-02-24”,<br/>“expired_on” : “2023-03-24”,<br/>“plan_name” : “Custom Cloud Server”,<br/><br/>“configuration” : {<br/> “image” : “Windows 2019”,<br/> “ram” : “10 GB”,<br/> “core” : “10 Core”,<br/> “disk” : “500 GB”,<br/> “band” : “1 TB”<br/>}<br/>“Addons” : <br/>{<br/> “addon_id1” : <br/> {<br/> “addon_id1”: “1234”,<br/> “addon_name” : “Managed Support”,<br/> “”recurring” : “500”,<br/> “billingcycle” : “Monthly”,<br/> “regdate” : “2023-02-25”,<br/> “nextduedate” : “2023-03-25”<br/>}<br/>},<br/>“current_status” : “Current Server status as per API request”,<br/>}<br/>}<br/>}<br/></span></span></i></pre>
                <span style="font-size: 12pt; color: #000000;"><span style="font-size: 12pt; color: #000000;"><strong><br/></strong></span></span>
                <div style="text-align: center;"><span style="font-size: 14pt; color: #000000;"><strong>getMaxServerCount</strong></span></div>
                <p><span style="font-weight: 400; color: #000000; font-size: 12pt;">This API allocates a specified number of servers for creation, with a maximum limit of 10.</span></p>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Post Request : </strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 145.609px;"> <span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 98.9062px;"> <span style="color: #000080;"><b>Type</b></span></td>
                            <td style="width: 157.172px;"> <span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 126.312px;"> <span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 145.609px;"><strong>request</strong></td>
                            <td style="width: 98.9062px;"><strong>string</strong></td>
                            <td style="width: 157.172px;"><strong>startServer</strong></td>
                            <td style="width: 126.312px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 145.609px;"><strong>product_id</strong></td>
                            <td style="width: 98.9062px;"><strong>int</strong></td>
                            <td style="width: 157.172px;"><strong>Product id to be start</strong></td>
                            <td style="width: 126.312px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 12pt; color: #000000;"><strong><br/></strong></span><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b>Example Request (CURL):<br/><br/></b></span></span>
                </strong>
                </span>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "getMaxServerCount"</span><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Response Format: </strong></span></h3>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">The API will respond with JSON data.</span></p>
                <h4><span style="font-size: 14pt; color: #000000;"><strong>Example response data:</strong></span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success",</span><br/><span style="font-size: 12pt;"> "count": “count in number”</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 12pt; color: #000000;"><strong><br/></strong></span><span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><span style="font-size: 18pt;">stopServer</span>
                <br/>
                </b>
                </span>
                </span>
                </strong>
                </span>
                </span>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">With this API, you can initiate a server stop action to gracefully shut down your server. This API ensures that all processes are terminated and any pending data is saved before shutting down the server.</span></p>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Post Request : </strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 120.234px;"><span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 110.672px;"><span style="color: #000080;"><b>Type</b></span></td>
                            <td style="width: 130.391px;"><span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 110.703px;"><span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 120.234px;"><strong>request</strong></td>
                            <td style="width: 110.672px;"><strong>string</strong></td>
                            <td style="width: 130.391px;"><strong>stopServer</strong></td>
                            <td style="width: 110.703px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 120.234px;"><strong>product_id</strong></td>
                            <td style="width: 110.672px;"><strong>int</strong></td>
                            <td style="width: 130.391px;"><strong>Product id to be stop</strong></td>
                            <td style="width: 110.703px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/>Example Request (CURL):<br/></b></span></span>
                </strong>
                </span>
                </span>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "stopServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Response Format: </strong></span></h3>
                <p><span style="font-weight: 400; font-size: 14pt; color: #000000;">The API will respond with JSON data.</span></p>
                <h4><span style="font-weight: 400; font-size: 14pt; color: #000000;">Example response data:</span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <p><span style="font-size: 18pt; color: #000000;"><strong>startServer</strong></span></p>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">This API allows you to start your server after it has been stopped or shut down. The API initiates the boot process of the server, allowing it to become operational again.</span></p>
                <h3><span style="color: #000000; font-size: 14pt;"><strong>Post Request : </strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 145.609px;"> <span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 98.9062px;"> <span style="color: #000080;"><b>Type</b></span></td>
                            <td style="width: 157.172px;"> <span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 126.312px;"> <span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 145.609px;"><strong>request</strong></td>
                            <td style="width: 98.9062px;"><strong>string</strong></td>
                            <td style="width: 157.172px;"><strong>startServer</strong></td>
                            <td style="width: 126.312px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 145.609px;"><strong>product_id</strong></td>
                            <td style="width: 98.9062px;"><strong>int</strong></td>
                            <td style="width: 157.172px;"><strong>Product id to be start</strong></td>
                            <td style="width: 126.312px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Example Request (CURL)</strong></span></h3>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "startServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Response Format: </strong></span></h3>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">The API will respond with JSON data.</span></p>
                <h4><span style="font-size: 14pt; color: #000000;"><strong>Example response data:</strong></span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <p><span style="font-size: 14pt;"><strong>rebootServer</strong></span></p>
                <p><span style="font-weight: 400; font-size: 12pt;">Use this API to initiate a server reboot. When you reboot your server, it shuts down and then automatically starts back up, allowing any pending updates or changes to take effect.</span></p>
                <h3><span style="font-weight: 400; font-size: 14pt; color: #000000;"><strong>Post Request :</strong> </span></h3>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 141.719px;"> <span style="color: #333333;"><strong>Parameter</strong></span></td>
                            <td style="width: 127.641px;"> <span style="color: #333399;"><b>Type</b></span></td>
                            <td style="width: 152.969px;"> <span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 127.672px;"> <span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 141.719px;"><strong>request</strong></td>
                            <td style="width: 127.641px;"><strong>string</strong></td>
                            <td style="width: 152.969px;"><strong>rebootServer</strong></td>
                            <td style="width: 127.672px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 141.719px;"><strong>product_id</strong></td>
                            <td style="width: 127.641px;"><strong>int</strong></td>
                            <td style="width: 152.969px;"><strong>Product id to be stop</strong></td>
                            <td style="width: 127.672px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/><span style="font-weight: 400;">Example Request (CURL)</span>
                <br/>
                <br/>
                </b>
                </span>
                </span>
                </strong>
                </span>
                </span>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "rebootServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-size: 14pt;"><strong><span style="color: #000000;">Response Format: </span></strong></span></h3>
                <p><span style="font-weight: 400; color: #000000;">The API will respond with JSON data.</span></p>
                <h4><span style="font-weight: 400; color: #000000; font-size: 14pt;">Example response data:<br/><br/></span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 14pt;">{</span><br/><span style="font-size: 14pt;"> "status": "success"</span><br/><span style="font-size: 14pt;">}</span></pre>
                <p style="text-align: center;"><span style="font-size: 14pt;"><strong>suspendServer</strong></span></p>
                <p><span style="font-weight: 400; font-size: 12pt;">This API initiates a server suspension action, which saves the current state of the server and stops all processes, allowing you to temporarily halt your server. When you're ready to resume operations, you can use the start API to boot the server backup and restore its state to the point of suspension.</span></p>
                <h3><span style="font-size: 14pt;"><strong><span style="color: #000000;">Post Request : </span></strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 127.109px;"> <span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 104.438px;"> <span style="color: #333399;"><b>Type</b></span></td>
                            <td style="width: 151.25px;"> <span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 110.203px;"> <span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 127.109px;"><strong>request</strong></td>
                            <td style="width: 104.438px;"><strong>string</strong></td>
                            <td style="width: 151.25px;"><strong>suspendServer</strong></td>
                            <td style="width: 110.203px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 127.109px;"><strong>product_id</strong></td>
                            <td style="width: 104.438px;"><strong>int</strong></td>
                            <td style="width: 151.25px;">
                                <p><strong>Product id to be suspend</strong></p>
                            </td>
                            <td style="width: 110.203px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Example Request (CURL)</strong></span></h3>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "suspendServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <h3><span style="font-size: 14pt;"><strong><span style="color: #000000;">Response Format: </span></strong></span></h3>
                <p><span style="font-weight: 400; color: #000000; font-size: 12pt;">The API will respond with JSON data.</span></p>
                <h4><span style="font-size: 14pt;"><strong><span style="color: #000000;">Example response data:</span></strong></span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <div style="text-align: center;"><span style="font-size: 14pt; color: #000000;"><strong>unsuspendServer</strong></span></div>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">Use this API to unsuspend your server.</span></p>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">When a server is suspended, it is in a halted state, and all processes are stopped. Using the unsuspend API initiates the process of resuming the server, allowing you to restore the state of the server to the point at which it was suspended.</span></p>
                <h3><span style="color: #000000; font-size: 14pt;"><strong>Post Request : </strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 154.484px;"> <span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 143.078px;"> <span style="color: #333399;"><b>Type</b></span></td>
                            <td style="width: 214.328px;"><span style="color: #333399;"> <b>Description</b></span></td>
                            <td style="width: 143.109px;"> <span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 154.484px;"><strong>request</strong></td>
                            <td style="width: 143.078px;"><strong>string</strong></td>
                            <td style="width: 214.328px;"><strong>unsuspendServer</strong></td>
                            <td style="width: 143.109px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 154.484px;"><strong>product_id</strong></td>
                            <td style="width: 143.078px;"><strong>int</strong></td>
                            <td style="width: 214.328px;">
                                <p><strong>Product id to be un suspend</strong></p>
                            </td>
                            <td style="width: 143.109px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Example Request (CURL)</strong></span></h3>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "unsuspendServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-size: 12pt; color: #000000;"><strong>Response Format: </strong></span></h3>
                <p><span style="font-weight: 400; font-size: 12pt; color: #000000;">The API will respond with JSON data.</span></p>
                <h4><span style="font-weight: 400; font-size: 12pt; color: #000000;">Example response data:<br/><br/></span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                </span>
                <p><span style="font-size: 14pt;"><strong>terminateServer</strong></span></p>
                <p><span style="font-weight: 400; font-size: 12pt;">This API allows you to initiate a server termination action, which permanently deletes the server and all associated data. It is an irreversible action, so be sure to take any necessary backups or data exports before proceeding with the termination.<br/><br/><strong>Post Request :</strong><br/></span></p>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 189.406px;"> <span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 123.734px;"><span style="color: #333399;"> <b>Type</b></span></td>
                            <td style="width: 204.359px;"> <span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 164.5px;"><span style="color: #333399;"><b>Required</b> </span></td>
                        </tr>
                        <tr>
                            <td style="width: 189.406px;"><strong>request</strong></td>
                            <td style="width: 123.734px;"><strong>string</strong></td>
                            <td style="width: 204.359px;"><strong>terminateServer</strong></td>
                            <td style="width: 164.5px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 189.406px;"><strong>product_id</strong></td>
                            <td style="width: 123.734px;"><strong>int</strong></td>
                            <td style="width: 204.359px;"><strong>Product id to be delete</strong></td>
                            <td style="width: 164.5px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Example Request (CURL)</strong></span></h3>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">"request ": "terminateServer"</span><br/><span style="font-size: 12pt;">“data” ‘{</span><br/><span style="font-size: 12pt;"> "product_id": "1234",</span><br/><span style="font-size: 12pt;">}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <h3><span style="font-weight: 400; color: #000000; font-size: 12pt;">Response Format: </span></h3>
                <p><span style="font-weight: 400; color: #000000; font-size: 12pt;">The API will respond with JSON data.</span></p>
                <h4><span style="font-weight: 400; color: #000000; font-size: 12pt;">Example response data:</span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre>
                <span style="font-size: 24pt; background-color: #ffffff;"><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong><span style="font-size: 14pt;"><strong><span style="color: #000000;"><span style="background-color: #ffffff;">Recreate Server<br/><br/></span></span>
                </strong>
                </span>
                </span>
                </span>
                <p><span style="font-weight: 400; font-size: 14pt;">This API will be used to recreate your server. It will delete the current server and create a new server with the same configuration.</span></p>
                <p><span style="font-weight: 400; font-size: 14pt;">So make sure that you have taken backup of the current server, before proceeding with the recreate server.<br/><br/></span></p>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Post Request : </strong></span></h3>
                <table style="height: 158px;" border="1O" width="801">
                    <tbody>
                        <tr>
                            <td style="width: 119.75px;"><span style="color: #333399;"><b>Parameter</b></span></td>
                            <td style="width: 119.75px;"><span style="color: #333399;"><b>Type</b></span></td>
                            <td style="width: 119.75px;"><span style="color: #333399;"><b>Description</b></span></td>
                            <td style="width: 119.75px;"><span style="color: #333399;"><b>Required</b></span></td>
                        </tr>
                        <tr>
                            <td style="width: 119.75px;"><strong>request</strong></td>
                            <td style="width: 119.75px;"><strong>string</strong></td>
                            <td style="width: 119.75px;"><strong>recreateServer</strong></td>
                            <td style="width: 119.75px;"><strong>Required</strong></td>
                        </tr>
                        <tr>
                            <td style="width: 119.75px;"><strong>product_id</strong></td>
                            <td style="width: 119.75px;"><strong>int</strong></td>
                            <td style="width: 119.75px;"><strong>Product id to be recreate</strong></td>
                            <td style="width: 119.75px;"><strong>Required</strong></td>
                        </tr>
                    </tbody>
                </table>
                <strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/>Example Request (CURL):</b></span></span></strong><span style="font-size: 24pt; background-color: #ffffff;"><strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span>
                </strong>
                </span>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">curl -X POST \</span><br/><span style="font-size: 12pt;">-H "Content-Type: application/json" </span><br/><span style="font-size: 12pt;">-d '{</span><br/><span style="font-size: 12pt;">       "request ": "recreateServer"</span><br/><span style="font-size: 12pt;">“data” <br/>‘{</span><br/><span style="font-size: 12pt;">  "product_id": "1234",</span><br/><span style="font-size: 12pt;">  <br/>}’</span><br/><br/><span style="font-size: 12pt;">}' \</span></pre>
                <strong><span style="color: #000000;"><span style="font-size: 14pt; background-color: #ffffff;"><b><br/></b></span></span></strong>
                <h3><span style="font-size: 14pt; color: #000000;"><strong>Response Format: </strong></span></h3>
                <p><span style="font-weight: 400; font-size: 12pt;">The API will respond with JSON data.</span></p>
                <h4><span style="font-weight: 400; font-size: 14pt;">Example response data:</span></h4>
                <pre style="border: 1px solid #ddd; padding: 12px;"><span style="font-size: 12pt;">{</span><br/><span style="font-size: 12pt;"> "status": "success"</span><br/><span style="font-size: 12pt;">}</span></pre> </div>
<ul class="pager pagenav">
    <li class="next">
        <a class="hasTooltip" title="How to Create SQL Database  " aria-label="Next article: How to Create SQL Database  " href="/how-tos/how-to-create-sql-database" rel="next">
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
    </li>
</ul>
</div>