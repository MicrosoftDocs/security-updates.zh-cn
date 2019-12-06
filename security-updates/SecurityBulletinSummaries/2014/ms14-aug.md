---
TOCTitle: 'MS14-AUG'
Title: 'Microsoft 安全公告摘要（2014 年 8 月）'
ms:assetid: 'ms14-aug'
ms:contentKeyID: 62757327
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-aug(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 8 月）
======================================

发布日期：2014 年 8 月 12 日 | 更新时间：2014 年 12 月 19 日

**版本：** 2.2

本公告摘要列出了 2014 年 8 月发布的安全公告。

对于 2014 年 8 月发布的安全公告，本公告摘要替代 2014 年 8 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 8 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。要查看每月网络广播和其他安全公告网络广播的链接，请参阅 [Microsoft 安全公告网络广播](https://technet.microsoft.com/security/dn756352)。

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
<thead>
<tr class="header">
<th><p>公告 ID</p></th>
<th><p>公告标题和摘要</p></th>
<th><p>最高严重等级和漏洞影响</p></th>
<th><p>重新启动要求</p></th>
<th><p>受影响的软件</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2976627)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中一个公开披露的漏洞和 25 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Media Center 中的漏洞可能允许远程执行代码 (2978742)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开可调用 Windows Media Center 资源的特制 Microsoft Office 文件，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></p></td>
<td style="border:1px solid black;"><p><strong>OneNote 中的漏洞可能允许远程执行代码 (2977201)</strong><br />
<br />
此安全更新可解决 Microsoft OneNote 中一个秘密报告的漏洞。如果特制文件在 Microsoft OneNote 的受影响版本中打开，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></p></td>
<td style="border:1px solid black;"><p><strong>SQL Server 中的漏洞可能允许特权提升 (2984340)</strong><br />
<br />
此安全更新可解决 Microsoft SQL Server 中两个秘密报告的漏洞（SQL Server Master Data Services 中一个，SQL Server 关系数据库管理系统中一个）。其中较严重的漏洞影响 SQL Server Master Data Services，如果用户访问会将客户端脚本注入用户的 Internet Explorer 实例中的特制网站，该漏洞可能允许特权提升。在所有情况下，攻击者无法强制用户查看由攻击者控制的内容。相反，攻击者必须诱使用户采取行动，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站，或者让用户打开通过电子邮件发送的附件。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft SQL Server</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></p></td>
<td style="border:1px solid black;"><p><strong>内核模式驱动程序中的漏洞可能允许特权提升 (2984615)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中三个秘密报告的漏洞。<strong></strong> 如果攻击者登录系统并运行特制应用程序，最严重的漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Installer 服务中的漏洞可能允许特权提升 (2962490)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密披露的漏洞。如果攻击者运行特制的应用程序而试图修复以前安装的应用程序，该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft SharePoint Server 中的漏洞可能允许特权提升 (2977202)</strong><br />
<br />
此安全更新可解决 Microsoft SharePoint Server 中一个秘密报告的漏洞。经过身份验证的攻击者如果成功利用此漏洞，就可以使用特制的应用程序在当前 SharePoint 网站上该用户的上下文中运行任意 JavaScript。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Server 软件</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许绕过安全功能 (2984625)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 中的一个秘密报告的漏洞。如果用户访问特制网站，此漏洞可能允许绕过安全功能。在 Web 浏览攻击情形中，成功利用此漏洞的攻击者可能会绕过地址空间布局随机化 (ASLR) 安全功能，它有助于保护用户免遭多种漏洞。该安全功能绕过本身不允许执行任意代码。但是，攻击者可以将此 ASLR 绕过漏洞与另一个漏洞（如远程执行代码漏洞）组合使用，从而利用 ASLR 绕过漏洞来运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></p></td>
<td style="border:1px solid black;"><p><strong>LRPC 中的漏洞可能允许绕过安全功能 (2978668)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者将此漏洞与另一个漏洞（如远程执行代码漏洞）结合使用，就可以利用 ASLR 绕过漏洞来运行任意代码，那么此漏洞可能允许绕过安全功能。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
如何使用该表？
  
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
<thead>  
<tr class="header">  
<th><p>公告 ID</p></th>  
<th><p>漏洞标题</p></th>  
<th><p>CVE ID</p></th>  
<th><p>最新软件版本的利用评估</p></th>  
<th><p>较旧软件版本的利用评估</p></th>  
<th><p>拒绝服务利用评估</p></th>  
<th><p>重要注意事项</p></th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507337">MS14-043</a></p></td>
<td style="border:1px solid black;"><p>CSyncBasePlayer 释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4060">CVE-2014-4060</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></p></td>
<td style="border:1px solid black;"><p>SQL Master Data Services XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1820">CVE-2014-1820</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507036">MS14-044</a></p></td>
<td style="border:1px solid black;"><p>Microsoft SQL Server 堆栈溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4061">CVE-2014-4061</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0318">CVE-2014-0318</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></p></td>
<td style="border:1px solid black;"><p>字体双重提取漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1819">CVE-2014-1819</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507035">MS14-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 内核池分配漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4064">CVE-2014-4064</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507038">MS14-046</a></p></td>
<td style="border:1px solid black;"><p>.NET ASLR 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4062">CVE-2014-4062</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。<br />
<br />
在最初发布此安全公告时，Microsoft 未收到任何表明此漏洞已公开用于攻击用户的信息。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507336">MS14-047</a></p></td>
<td style="border:1px solid black;"><p>LRPC ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0316">CVE-2014-0316</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。<br />
<br />
在最初发布此安全公告时，Microsoft 未收到任何表明此漏洞已公开用于攻击用户的信息。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=402461">MS14-048</a></p></td>
<td style="border:1px solid black;"><p>OneNote 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2815">CVE-2014-2815</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396822">MS14-049</a></p></td>
<td style="border:1px solid black;"><p>Windows Installer 修复漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1814">CVE-2014-1814</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=402463">MS14-050</a></p></td>
<td style="border:1px solid black;"><p>SharePoint 页面内容漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2816">CVE-2014-2816</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2774">CVE-2014-2774</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2784">CVE-2014-2784</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2796">CVE-2014-2796</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2808">CVE-2014-2808</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2810">CVE-2014-2810</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2811">CVE-2014-2811</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2817">CVE-2014-2817</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测到利用</p></td>
<td style="border:1px solid black;"><p>0 - 检测到利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的有限攻击。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2818">CVE-2014-2818</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2819">CVE-2014-2819</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2820">CVE-2014-2820</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2821">CVE-2014-2821</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2822">CVE-2014-2822</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2823">CVE-2014-2823</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2824">CVE-2014-2824</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2825">CVE-2014-2825</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2826">CVE-2014-2826</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2827">CVE-2014-2827</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4050">CVE-2014-4050</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4051">CVE-2014-4051</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4052">CVE-2014-4052</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4055">CVE-2014-4055</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4056">CVE-2014-4056</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4057">CVE-2014-4057</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4058">CVE-2014-4058</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4063">CVE-2014-4063</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4067">CVE-2014-4067</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4145">CVE-2014-4145</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=507027">MS14-051</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6354">CVE-2014-6354</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>无</p></td>
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
  
**Windows 操作系统和组件**

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="7" style="border:1px solid black;">  
Windows Server 2003
  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
（中等）  
Internet Explorer 7  
(2976627)  
（中等）  
Internet Explorer 8  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993651)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2918614)  
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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
（中等）  
Internet Explorer 7  
(2976627)  
（中等）  
Internet Explorer 8  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993651)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2918614)  
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
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2976627)  
（中等）  
Internet Explorer 7  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2993651)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2918614)  
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
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
（严重）  
Internet Explorer 8  
(2976627)  
（严重）  
Internet Explorer 9  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993651)  
（重要）  
Windows Vista Service Pack 2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
（严重）  
Internet Explorer 8  
(2976627)  
（严重）  
Internet Explorer 9  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993651)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
（中等）  
Internet Explorer 8  
(2976627)  
（中等）  
Internet Explorer 9  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2993651)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
（中等）  
Internet Explorer 8  
(2976627)  
（中等）  
Internet Explorer 9  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2993651)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2993651)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2937608)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2943344)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
（严重）  
Internet Explorer 9  
(2976627)  
（严重）  
Internet Explorer 10  
(2976627)  
（严重）  
Internet Explorer 11  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
（除简易版和家庭普通版之外的所有版本）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2993651)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2943357)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
（严重）  
Internet Explorer 9  
(2976627)  
（严重）  
Internet Explorer 10  
(2976627)  
（严重）  
Internet Explorer 11  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
（除简易版和家庭普通版之外的所有版本）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2993651)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2943357)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2978668)  
（重要）

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
（中等）  
Internet Explorer 9  
(2976627)  
（中等）  
Internet Explorer 10  
(2976627)  
（中等）  
Internet Explorer 11  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2993651)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2943357)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2993651)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2943357)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2978668)  
（重要）

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Windows 8（用于 32 位系统）上的 Windows Media Center（仅专业版）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2993651)  
（重要）  
Windows 8（用于 32 位系统）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
（重要）  
Microsoft .NET Framework 3.5  
(2966827)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Windows 8（用于基于 x64 的系统）上的 Windows Media Center（仅专业版）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2993651)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
（重要）  
Microsoft .NET Framework 3.5  
(2966827)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Windows 8.1（用于 32 位系统）上的 Windows Media Center（仅专业版）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2993651)  
（重要）  
Windows 8.1（用于 32 位系统）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
（重要）  
Microsoft .NET Framework 3.5  
(2966828)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Windows 8.1（用于基于 x64 的系统）上的 Windows Media Center（仅专业版）  
(2978742)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2993651)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
（重要）  
Microsoft .NET Framework 3.5  
(2966828)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2978668)  
（重要）

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993651)  
（重要）  
Windows Server 2012  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
（重要）  
Microsoft .NET Framework 3.5  
(2966827)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993651)  
（重要）  
Windows Server 2012 R2  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
（重要）  
Microsoft .NET Framework 3.5  
(2966828)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2978668)  
（重要）

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(2993651)  
（重要）  
Windows RT  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(2978668)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2976627)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993651)  
（重要）  
Windows RT 8.1  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2978668)  
（重要）

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
[**MS14-051**](https://go.microsoft.com/fwlink/?linkid=507027)

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
<td style="border:1px solid black;">
[**MS14-045**](https://go.microsoft.com/fwlink/?linkid=507035)

</td>
<td style="border:1px solid black;">
[**MS14-049**](https://go.microsoft.com/fwlink/?linkid=396822)

</td>
<td style="border:1px solid black;">
[**MS14-046**](https://go.microsoft.com/fwlink/?linkid=507038)

</td>
<td style="border:1px solid black;">
[**MS14-047**](https://go.microsoft.com/fwlink/?linkid=507336)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(2993651)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2918614)  
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
(2993651)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2918614)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2993651)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2937610)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2943357)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2978668)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2993651)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966825)  
（重要）  
Microsoft .NET Framework 3.5  
(2966827)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2978668)  
（重要）

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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2993651)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(2976897)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2918614)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2966826)  
（重要）  
Microsoft .NET Framework 3.5  
(2966828)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2978668)  
（重要）

</td>
</tr>
</table>

**MS14-043 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

**Microsoft Office 软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
**Microsoft Office 软件**

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-048**](https://go.microsoft.com/fwlink/?linkid=402461)

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
Microsoft OneNote 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft OneNote 2007 Service Pack 3  
(2596857)  
（重要）

</td>
</tr>
</table>

 

**Microsoft SQL Server**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-044**](https://go.microsoft.com/fwlink/?linkid=507036)

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
Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）  
(GDR)  
(2977321)  
（重要）  
Microsoft SQL Server 2008 Service Pack 3（用于 32 位系统）  
(QFE)  
(2977322)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）  
(GDR)  
(2977321)  
（重要）  
Microsoft SQL Server 2008 Service Pack 3（用于基于 x64 的系统）  
(QFE)  
(2977322)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）  
(GDR)  
(2977321)  
（重要）  
Microsoft SQL Server 2008 Service Pack 3（用于基于 Itanium 的系统）  
(QFE)  
(2977322)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2008 R2**

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
Microsoft SQL Server 2008 R2 Service Pack 2（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 2（用于 32 位系统）  
(GDR)  
2977320)  
（重要）  
Microsoft SQL Server 2008 R2 Service Pack 2（用于 32 位系统）  
(QFE)  
(2977319)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 x64 的系统）  
(GDR)  
(2977320)  
（重要）  
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 x64 的系统）  
(QFE)  
(2977319)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 Itanium 的系统）  
(GDR)  
(2977320)  
（重要）  
Microsoft SQL Server 2008 R2 Service Pack 2（用于基于 Itanium 的系统）  
(QFE)  
(2977319)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2012**

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
Microsoft SQL Server 2012 Service Pack 1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 Service Pack 1（用于 32 位系统）  
(GDR)  
(2977326)  
（重要）  
Microsoft SQL Server 2012 Service Pack 1（用于 32 位系统）  
(QFE)  
(2977325)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 Service Pack 1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2012 Service Pack 1（用于基于 x64 的系统）  
(GDR)  
(2977326)  
（重要）  
Microsoft SQL Server 2012 Service Pack 1（用于基于 x64 的系统）  
(QFE)  
(2977325)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**SQL Server 2014**

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
Microsoft SQL Server 2014（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Microsoft SQL Server 2014（用于基于 x64 的系统）  
(GDR)  
(2977315)  
（重要）  
Microsoft SQL Server 2014（用于基于 x64 的系统）  
(QFE)  
(2977316)  
（重要）

</td>
</tr>
</table>

 

**Microsoft Server 软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-050**](https://go.microsoft.com/fwlink/?linkid=402463)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013  
(2880994)  
（重要）  
Microsoft SharePoint Foundation 2013  
(2880994)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(2880994)  
（重要）  
Microsoft SharePoint Foundation 2013 Service Pack 1  
(2880994)  
（重要）

</td>
</tr>
</table>

 

**其他软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista 的 Windows Media Center TV Pack**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-043**](https://go.microsoft.com/fwlink/?linkid=507337)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 的 Windows Media Center TV Pack（32 位版本）

</td>
<td style="border:1px solid black;">
Windows Vista 的 Windows Media Center TV Pack（32 位版本）  
(2978742)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 的 Windows Media Center TV Pack（64 位版本）

</td>
<td style="border:1px solid black;">
Windows Vista 的 Windows Media Center TV Pack（64 位版本）  
(2978742)  
（严重）

</td>
</tr>
</table>

**MS14-043 注释**

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

**MS14-043**

-   Alisa Esage (@alisaesage) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 CSyncBasePlayer 释放后使用漏洞 (CVE-2014-4060)

**MS14-045**

-   [Qihoo 360](https://www.360.cn/) 的 Wang Yu 报告了字体双重释放漏洞 (CVE-2014-1819)
-   Ilja Van Sprundel 报告了 Windows 内核池分配漏洞 (CVE-2014-4064)

**MS14-047**

-   [Alex Ionescu](https://www.alex-ionescu.com/) 报告了 LRPC ASLR 绕过漏洞 (CVE-2014-0316)

**MS14-048**

-   Eduardo Prado 与 Beyond Security 的 [SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) 计划合作报告了 OneNote 远程执行代码漏洞 (CVE-2014-2815)

**MS14-049**

-   [Entisys](https://www.entisys.com/) 的 Denis Gundarev 报告了 Windows Installer 修复漏洞 (CVE-2012-4784)
-   [Stepfan Kanthak](https://home.arcor.de/skanthak/safer.html) 与我们合作处理了此公告中包括的纵深防御更改。

**MS14-051**

-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2774)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2784)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2796)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2808)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2810)
-   IronRock 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2811)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2014-2817)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2818)
-   [Team509](https://team509.com/) 的 Zeguang Zhao 和 [KeenTeam](https://www.k33nteam.org/) (@K33nTeam) 的 Liang Chen 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 特权提升漏洞 (CVE-2014-2819)
-   Arthur Gerkis 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2820)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2821)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2822)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2823)
-   [Qihoo 360](https://www.360.cn/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2824)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2825)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://github.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2826)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Simon Zuckerbraun 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2827)
-   [Omair](https://krash.in/) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4050)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4051)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4052)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Simon Zuckerbraun 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4055)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4056)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4057)
-   Sky 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4058)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4063)
-   [VulnHunt](https://www.vulnhunt.com/) 的 Wei Wang 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4067)
-   [lokihardt@ASRT](https://technet.microsoft.com/zh-CN/mailto:lokihardt@asrt) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4067)
-   Omair 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4145)
-   Omair 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-6354)

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

-   V1.0（2014 年 8 月 12 日）： 已发布公告摘要。
-   V2.0（2014 年 8 月 27 日）： 对于 MS14-045，重新发布此公告以宣布将 Microsoft Windows 所有受支持版本的 2982791 更新替换为 2993651 更新。有关详细信息，请参阅公告。
-   V2.1（2014 年 10 月 8 日）： 对于 MS14-051，针对 CVE-2014-4145 在“利用指数”中添加了利用评估。这仅仅是一个信息更改。
-   V2.2（2014 年 12 月 19 日）：对于 MS14-051，针对 CVE-2014-6354 在“利用指数”中添加了利用评估。这仅仅是一个信息更改。

*页面生成时间 2014-10-07 17:05Z-07:00。*
