---
TOCTitle: 'MS14-OCT'
Title: 'Microsoft 安全公告摘要（2014 年 10 月）'
ms:assetid: 'ms14-oct'
ms:contentKeyID: 63172105
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-oct(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 10 月）
=======================================

发布日期： 2014 年 10 月 14 日

**版本：** 1.0

本公告摘要列出了 2014 年 10 月发布的安全公告。

对于 2014 年 10 月发布的安全公告，本公告摘要替代 2014 年 10 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 10 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。要查看每月网络广播和其他安全公告网络广播的链接，请参阅 [Microsoft 安全公告网络广播](https://technet.microsoft.com/security/dn756352)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2987107)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中 14 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许远程执行代码 (3000414)<br />
<br />
</strong>此安全更新可解决 Microsoft .NET Framework 中三个秘密报告的漏洞。如果攻击者将包含国际字符的特制 URI 请求发送到 .NET Web 应用程序，则其中最严重的漏洞可能允许远程执行代码。在 .NET 4.0 应用程序中，容易受到攻击的功能 (iriParsing) 默认情况下被禁用；要利用该漏洞，应用程序必须明确启用此功能。在 .NET 4.5 应用程序中，iriParsing 默认情况下启用，不能被禁用。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></p></td>
<td style="border:1px solid black;"><p><strong>内核模式驱动程序中的漏洞可能允许远程执行代码 (3000061)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果攻击者诱使用户打开特制文档或访问包含嵌入 TrueType 字体的不受信任的网站，则其中较为严重的漏洞可能允许远程执行代码。但是在所有情况下，攻击者无法强制用户执行这些操作。相反，攻击者必须说服用户这样做，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></p></td>
<td style="border:1px solid black;"><p><strong>ASP.NET MVC 中的漏洞可能允许绕过安全功能 (2990942)<br />
<br />
</strong>此安全更新解决了 ASP.NET MVC 中一个公开披露的漏洞。如果攻击者诱使用户单击特制链接或访问包含旨在利用漏洞的特制内容的网页，则此漏洞可能允许绕过安全功能。在基于 Web 的攻击情形中，攻击者可能拥有一个旨在通过 Web 浏览器利用漏洞的特制网站，然后诱使用户查看该网站。攻击者还可能利用受到破坏的网站以及接受或宿主用户提供的内容或广告的网站。这些网站可能包含可以利用此漏洞的特制内容。但是在所有情况下，攻击者无法强制用户查看由攻击者控制的内容。相反，攻击者必须诱使用户采取行动，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站，或者让用户打开通过电子邮件发送的附件。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft 开发工具</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows OLE 中的漏洞可能允许远程执行代码 (3000869)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开包含特制 OLE 对象的 Microsoft Office 文件，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以在当前用户的上下文中运行任意代码。如果当前用户使用管理用户权限登录，则攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Word 和 Office Web Apps 中的漏洞可能允许远程执行代码 (3000434)<br />
<br />
</strong>此安全更新可解决 Microsoft Office 中一个秘密报告的漏洞。如果攻击者诱使用户打开特制 Microsoft Word 文件，此漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office，<br />
Microsoft Office 服务，<br />
Microsoft Office Web Apps</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></p></td>
<td style="border:1px solid black;"><p><strong>消息队列服务中的漏洞可能允许特权提升 (2993254)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果攻击者向消息队列服务发送特制输入/输出控制 (IOCTL) 请求，则该漏洞可能允许特权提升。成功利用此漏洞便可完全访问受影响的系统。默认情况下，消息队列组件不安装在任何受影响的操作系统版本上，而仅由具有管理特权的用户启用。只有手动启用“消息队列服务”组件的客户才可能受此问题的影响。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></p></td>
<td style="border:1px solid black;"><p><strong>FAT32 磁盘分区驱动程序中的漏洞可能允许特权提升 (2998579)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。Windows FASTFAT 系统驱动程序与 FAT32 磁盘分区进行交互的方式中存在一个特权提升漏洞。成功利用此漏洞的攻击者可以使用提升的特权执行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>最新软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4123">CVE-2014-4123</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是通过绕过 IE 沙盒实现的特权提升漏洞。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4124">CVE-2014-4124</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4126">CVE-2014-4126</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4127">CVE-2014-4127</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4128">CVE-2014-4128</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4129">CVE-2014-4129</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4130">CVE-2014-4130</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4132">CVE-2014-4132</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4133">CVE-2014-4133</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4134">CVE-2014-4134</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4137">CVE-2014-4137</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4138">CVE-2014-4138</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4140">CVE-2014-4140</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4141">CVE-2014-4141</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></p></td>
<td style="border:1px solid black;"><p>.NET ClickOnce 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4073">CVE-2014-4073</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></p></td>
<td style="border:1px solid black;"><p>.NET Framework 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4121">CVE-2014-4121</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></p></td>
<td style="border:1px solid black;"><p>.NET ASLR 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4122">CVE-2014-4122</a></p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></p></td>
<td style="border:1px solid black;"><p>Win32k.sys 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4113">CVE-2014-4113</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。<br />
<br />
Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4148">CVE-2014-4148</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></p></td>
<td style="border:1px solid black;"><p>MVC XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4075">CVE-2014-4075</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。<br />
<br />
此漏洞已公开披露。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></p></td>
<td style="border:1px solid black;"><p>Windows OLE 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4114">CVE-2014-4114</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Word 文件格式漏洞 </p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4117">CVE-2014-4117</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></p></td>
<td style="border:1px solid black;"><p>MQAC 任意写入特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4971">CVE-2014-4971</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。<br />
<br />
此漏洞已公开披露。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 磁盘分区驱动程序特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4115">CVE-2014-4115</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
</tbody>  
</table>
  
 
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
（中等）  
Internet Explorer 7  
(2987107)  
（中等）  
Internet Explorer 8  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993254)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
（中等）  
Internet Explorer 7  
(2987107)  
（中等）  
Internet Explorer 8  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993254)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
（中等）  
Internet Explorer 7  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2993254)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
（严重）  
Internet Explorer 8  
(2987107)  
（严重）  
Internet Explorer 9  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
（严重）  
Internet Explorer 8  
(2987107)  
（严重）  
Internet Explorer 9  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
（中等）  
Internet Explorer 8  
(2987107)  
（中等）  
Internet Explorer 9  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
（中等）  
Internet Explorer 8  
(2987107)  
（中等）  
Internet Explorer 9  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
（严重）  
Internet Explorer 9  
(2987107)  
（严重）  
Internet Explorer 10  
(2987107)  
（严重）  
Internet Explorer 11  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2972100)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2979570)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
（严重）  
Internet Explorer 9  
(2987107)  
（严重）  
Internet Explorer 10  
(2987107)  
（严重）  
Internet Explorer 11  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2972100)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2979570)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
（中等）  
Internet Explorer 9  
(2987107)  
（中等）  
Internet Explorer 10  
(2987107)  
（中等）  
Internet Explorer 11  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2972100)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2979570)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2972100)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2979570)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
（重要）  
Microsoft .NET Framework 3.5  
(2972101)  
（严重）  
Microsoft .NET Framework 3.5  
(2979571)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
（重要）  
Microsoft .NET Framework 3.5  
(2972101)  
（严重）  
Microsoft .NET Framework 3.5  
(2979571)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
（重要）  
Microsoft .NET Framework 3.5  
(2972103)  
（严重）  
Microsoft .NET Framework 3.5  
(2979573)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
（严重）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
（重要）  
Microsoft .NET Framework 3.5  
(2972103)  
（严重）  
Microsoft .NET Framework 3.5  
(2979573)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
（严重）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
（重要）  
Microsoft .NET Framework 3.5  
(2972101)  
（严重）  
Microsoft .NET Framework 3.5  
(2979571)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
（重要）  
Microsoft .NET Framework 3.5  
(2972103)  
（严重）  
Microsoft .NET Framework 3.5  
(2979573)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
（严重）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
（严重）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2998579)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2972100)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2979570)  
（重要）  
Microsoft .NET Framework 4  
(2972106)  
（严重）  
Microsoft .NET Framework 4  
(2979575)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
（重要）  
Microsoft .NET Framework 3.5  
(2972101)  
（严重）  
Microsoft .NET Framework 3.5  
(2979571)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
（重要）  
Microsoft .NET Framework 3.5  
(2972103)  
（严重）  
Microsoft .NET Framework 3.5  
(2979573)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
（严重）  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3000061)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

 

### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET MVC**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-059**](https://go.microsoft.com/fwlink/?linkid=507673)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 2.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 2.0  
(2993939)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 3.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 3.0  
(2993937)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 4.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 4.0  
(2993928)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.0  
(2992080)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.1

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.1  
(2994397)  
（重要）

</td>
</tr>
</table>

 

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2883031)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(2883032)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2883008)  
（重要）  
Microsoft Word 2010 Service Pack 1（32 位版本）  
(2883013)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2883008)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2883013)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2883008)  
（重要）  
Microsoft Word 2010 Service Pack 1（64 位版本）  
(2883013)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2883008)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2883013)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3004865)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2883031)  
（重要）

</td>
</tr>
</table>

**MS14-061 注释**

这些公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office Services 和 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010  
(2889827)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 Service Pack 1  
(2889827)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 Service Pack 2  
(2889827)  
（重要）

</td>
</tr>
</table>

**MS14-061 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

管理员可使用 Microsoft Baseline Security Analyzer (MBSA) 在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/security/cc297183)。 

鸣谢
----

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS14-056**

-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2014-4123)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2014-4124)
-   Rohit Mothe 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4126)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4127)
-   Omair 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4128)
-   Jason Kratzer 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4128)
-   [Adlab of Venustech](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4129)
-   Sky 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4130)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4132)
-   Yenteasy - Security Research 的 José A. Vázquez 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4132)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4133)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4134)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4137)
-   SkyLined 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4138)
-   John Villamil (@day6reak) 报告了 Internet Explorer ASLR 绕过漏洞 (CVE-2014-4140)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4141)

**MS14-057**

-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 .NET ClickOnce 特权提升漏洞 (CVE-2014-4073)

**MS14-058**

-   [CrowdStrike Intelligence Team](https://www.crowdstrike.com/) 与我们一起努力处理了 Win32k.sys 特权提升漏洞 (CVE-2014-4113)
-   [FireEye, Inc.](https://www.fireeye.com/) 与我们一起努力处理了 Win32k.sys 特权提升漏洞 (CVE-2014-4113)
-   [FireEye, Inc.](https://www.fireeye.com/) 与我们一起努力处理了 TrueType 字体分析特权提升漏洞 (CVE-2014-4148)

**MS14-060**

-   [iSIGHT Partners](https://www.isightpartners.com/) 报告了 Windows OLE 远程执行代码漏洞 (CVE-2014-4114)

**MS14-061**

-   3S Labs 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Microsoft Word 文件格式漏洞 (CVE-2014-4117)

**MS14-063**

-   [Cisco Talos](https://www.sourcefire.com/solutions/research) 的 Marcin 'Icewall' Noga 报告了 Windows 磁盘分区驱动程序特权提升漏洞 (CVE-2014-4115)

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617)

帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)

本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2014 年 10 月 14 日）： 已发布公告摘要。

*页面生成时间 2014-10-13 14:39Z-07:00。*
