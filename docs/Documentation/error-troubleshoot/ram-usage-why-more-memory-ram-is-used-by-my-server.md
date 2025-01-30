---
title: RAM Usage / Why more memory (RAM) is used by my server?
excerpt: >-
  Understand why your server's RAM usage may seem high even when idle or lightly
  used
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
```mdx
<div class="page-header">
  <h2 itemprop="headline">
    RAM Usage / Why more memory (RAM) is used by my server?
  </h2>
</div>
<dl class="article-info muted">
  <dt class="article-info-term"></dt>
  <dd class="modified">
    <span class="icon-calendar" aria-hidden="true"></span>
    <time datetime="2021-07-08T11:09:27+00:00" itemprop="dateModified">
      Last Updated: 08 July 2021
    </time>
  </dd>
</dl>
<div itemprop="articleBody">
  <p>
    <span style={{ fontWeight: "400" }}>
      We have written this article for customers who are having a concern that, Why Virtual Memory (RAM) usage is more when I don't run any application or I have not even started my website or I get only less traffic now, but RAM usage is more.
    </span>
  </p>
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      First of all, You need to understand the various technical things involved in memory, for example when it comes to memory in larger terms, RAM, Virtual memory, Paging, Cache memory and so many other things are involved.
    </span>
  </p>
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      If you are not willing to learn all these technical things, In simple terms the OS (operating system) will use the RAM(memory) as lavishly as possible like any rich kid and when RAM is less and not sufficient to run all the applications, It uses all the technique mentioned above to manage the show within the given RAM size. If not enough, it will kill the process, it's called (OOM) out of memory. If OOM occurs often then you must update/increase your RAM.
    </span>
  </p>
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      When any server is installed with any control panel, when not in use, these could be the usage scenario.
    </span>
  </p>
  <img src="https://image.hostingraja.in/images/articles/about-ram-usage.png" alt="" />
  <br />
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      Used Memory is 122M, which is needed for your OS and other essential softwares.
    </span>
  </p>
  <p>
    <span style={{ fontWeight: "400" }}>
      The most important thing to note is the load average. When the load average goes beyond 2.x or 3.x, that's when you need to upgrade or increase your RAM and CPU.
    </span>
  </p>
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      Apart from the explanation given above, There could be 100 reasons why more RAM usage. Please read some of the following.
    </span>
  </p>
  <br />
  <ol>
    <li style={{ fontWeight: "400" }}>
      <span style={{ fontWeight: "400" }}>System might be running some software updates</span>
    </li>
    <li style={{ fontWeight: "400" }}>
      <span style={{ fontWeight: "400" }}>System might be doing some routine task (crontab, scheduled task)</span>
    </li>
  </ol>
  <br />
  <br />
  <p>
    <span style={{ fontWeight: "400" }}>
      If you are interested to know more about RAM, Virtual Memory, refer the following links.
    </span>
  </p>
  <br />
  <ol>
    <li style={{ fontWeight: "400" }}>
      <a href="https://searchstorage.techtarget.com/definition/virtual-memory">
        <span style={{ fontWeight: "400" }}>https://searchstorage.techtarget.com/definition/virtual-memory</span>
      </a>
    </li>
    <li style={{ fontWeight: "400" }}>
      <a href="https://www.tutorialspoint.com/operating_system/os_virtual_memory.htm">
        <span style={{ fontWeight: "400" }}>https://www.tutorialspoint.com/operating_system/os_virtual_memory.htm</span>
      </a>
    </li>
  </ol>
</div>
<ul class="pager pagenav">
  <li class="next">
    <a class="hasTooltip" title="Filezilla not connecting, Connecting Error" aria-label="Next article: Filezilla not connecting, Connecting Error" href="/docs/filezilla-not-connecting-connecting-error" rel="next">
      <span aria-hidden="true">Next</span>
      <span class="icon-chevron-right" aria-hidden="true"></span>
    </a>
  </li>
</ul>
```