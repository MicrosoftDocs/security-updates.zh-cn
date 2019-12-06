---
TOCTitle: 'MS11-OCT'
Title: 'Microsoft 安全公告摘要（2011 年 10 月）'
ms:assetid: 'ms11-oct'
ms:contentKeyID: 61236961
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms11-oct(v=Security.10)'
---



Microsoft 安全公告摘要（2011 年 10 月）
=======================================

发布时间: 2011年10月11日 | 更新时间: 2011年10月26日

**版本:** 1.1

本公告摘要列出了 2011 年 10 月发布的安全公告。

对于 2011 年 10 月发布的安全公告，本公告摘要替代 2011 年 10 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2011 年 10 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 10 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487956)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

摘要
----

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件及其下载位置**”。

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th>公告 ID</th>
<th>公告标题和摘要</th>
<th>最高严重等级和漏洞影响</th>
<th>重新启动要求</th>
<th>受影响的软件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227075">MS11-078</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 和 Microsoft Silverlight 中的漏洞可能允许远程执行代码 (2604930)</strong><br />
<br />
此安全更新解决 Microsoft .NET Framework 和 Microsoft Silverlight 中一个秘密报告的漏洞。如果用户使用可运行 XAML 浏览器应用程序 (XBAP) 或 Silverlight 应用程序的 Web 浏览器查看特制网页，则此漏洞可能允许在客户端系统上远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。如果运行 IIS 的服务器系统允许处理 ASP.NET 页面，并且攻击者成功地将特制 ASP.NET 页面上载到该服务器并执行它，此漏洞也可能允许在该服务器系统上远程执行代码，在 Web 主机情形中也是如此。Windows .NET 应用程序也可能会使用此漏洞绕过代码访问安全性 (CAS) 限制。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft .NET Framework、Microsoft Silverlight</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2586448)</strong><br />
<br />
此安全更新解决 Internet Explorer 中的 11 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221538">MS11-075</a></td>
<td style="border:1px solid black;"><strong>Microsoft Active Accessibility 中的漏洞可能允许远程执行代码 (2623699)</strong><br />
<br />
此安全更新可解决 Microsoft Active Accessibility 组件中一个秘密报告的漏洞。如果攻击者诱使用户打开与特制动态链接库 (DLL) 文件位于同一网络目录下的合法文件，此漏洞可能允许远程执行代码。然后，在打开合法文件时，Microsoft Active Accessibility 组件可能尝试加载 DLL 文件并执行其包含的任何代码。要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227073">MS11-076</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center 中的漏洞可能允许远程执行代码 (2604926)</strong><br />
<br />
此安全更新可解决 Windows Media Center 中一个公开披露的漏洞。如果攻击者诱使用户打开与特制动态链接库 (DLL) 文件位于同一网络目录下的合法文件，此漏洞可能允许远程执行代码。然后，当打开该合法文件时，Windows Media Center 可能尝试加载 DLL 文件并执行其包含的任何代码。要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享并打开合法的文件。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (2567053)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中四个秘密报告的漏洞。如果用户打开网络共享、UNC 或 WebDAV 位置或者电子邮件附件中的特制字体文件（例如 .fon 文件），则这些漏洞中最严重的漏洞可能允许远程执行代码。要成功进行远程攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并打开特制字体文件，或者作为电子邮件附件打开文件。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Forefront Unified Access Gateway 中的漏洞可能导致远程执行代码 (2544641)</strong><br />
<br />
此安全更新可解决 Forefront Unified Access Gateway (UAG) 中五个秘密报告的漏洞。如果用户使用特制的 URL 访问受影响的网站，则其中最严重的漏洞可能允许远程执行代码。但是，攻击者无法强迫用户访问该网站。相反，攻击者必须说服用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227486">MS11-080</a></td>
<td style="border:1px solid black;"><strong>辅助功能驱动程序中的漏洞可能允许特权提升 (2592799)</strong><br />
<br />
此安全更新可解决 Microsoft Windows Ancillary Function Driver (AFD) 中一个秘密报告的漏洞。如果攻击者登录用户的系统，并运行特制应用程序，则此漏洞可能允许提升特权。攻击者必须拥有有效的登录凭据，并能够本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td style="border:1px solid black;"><strong>主机集成服务器中的漏洞可能允许拒绝服务 (2607670)</strong><br />
<br />
此安全更新可解决主机集成服务器中两个公开披露的漏洞。如果远程攻击者将特制网络数据包发送到侦听 UDP 端口 1478 或 TCP 端口 1477 和 1478 的主机集成服务器，则这些漏洞可能允许拒绝服务。采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。在这种情况下，应阻止从 Internet 访问主机集成服务器端口。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Host Integration Server</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>最新软件版本的代码执行利用评估</th>  
<th>较旧软件版本的代码执行利用评估</th>  
<th>拒绝服务利用评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=221538">MS11-075</a></td>
<td style="border:1px solid black;">Active Accessibility 不安全库加载漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1247">CVE-2011-1247</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227073">MS11-076</a></td>
<td style="border:1px solid black;">Media Center 不安全库加载漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2009">CVE-2011-2009</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td style="border:1px solid black;">Win32k 空指针解除引用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1985">CVE-2011-1985</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td style="border:1px solid black;">字体库文件缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2003">CVE-2011-2003</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=225915">MS11-077</a></td>
<td style="border:1px solid black;">Win32k 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2011">CVE-2011-2011</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227075">MS11-078</a></td>
<td style="border:1px solid black;">.NET Framework 类继承漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1253">CVE-2011-1253</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - 不太可能被利用的代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;">ExcelTable 响应拆分 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1895">CVE-2011-1895</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">公告中引用的某些平台上的信息泄露</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;">ExcelTable 反映的 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1896">CVE-2011-1896</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">公告中引用的某些平台上的信息泄露</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;">默认反映的 XSS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1897">CVE-2011-1897</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">公告中引用的某些平台上的信息泄露</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;">中毒代码执行漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1969">CVE-2011-1969</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=217472">MS11-079</a></td>
<td style="border:1px solid black;">空会话 Cookie 崩溃漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2012">CVE-2011-2012</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=227486">MS11-080</a></td>
<td style="border:1px solid black;">辅助功能驱动程序特权提升漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2005">CVE-2011-2005</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">Scroll 事件远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1993">CVE-2011-1993</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">OLEAuto32.dll 远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1995">CVE-2011-1995</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">选项元素远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1996">CVE-2011-1996</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">OnLoad 事件远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1997">CVE-2011-1997</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">Jscript9.dll 远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1998">CVE-2011-1998</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">选择元素远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1999">CVE-2011-1999</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">主体元素远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2000">CVE-2011-2000</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=226382">MS11-081</a></td>
<td style="border:1px solid black;">虚拟功能表损坏远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2001">CVE-2011-2001</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td style="border:1px solid black;">snabase.exe 中的无限循环 DoS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2007">CVE-2011-2007</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。<br />
<br />
此漏洞已公开披露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=228596">MS11-082</a></td>
<td style="border:1px solid black;">未分配内存访问 DoS 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2008">CVE-2011-2008</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。<br />
<br />
此漏洞已公开披露。</td>
</tr>
</tbody>
</table>


受影响的软件和下载位置
----------------------

下表按主要软件类别和严重性的排序列出了公告。

**如何使用这些表？**

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重** **等级**
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
无
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a54a7ad5-0504-4cc6-9eca-ba9f31c35a17)  
(KB2572066)  
（仅限 Media Center Edition 2005 和 Tablet PC Edition 2005）  
（严重）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d)  
(KB2572073)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=822f91f5-bf92-42c4-ad33-b971be37d772)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e942554d-6cb6-4e48-a876-3470671a95a2)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a911b5b0-5e46-4a37-83e7-595e20585c56)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=96af60b9-4b8d-4a9b-b125-10775bb48252)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9157e677-ab3f-44b0-9735-192bc7421ba7)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f1b2dceb-5bef-4522-9001-8dff0545d805)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d)  
(KB2572073)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6260318c-e579-4cdf-93e3-4608892bc79e)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f04ad852-1418-4fc4-bd57-f47895bbf3a8)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=67ebf641-1341-4642-96ba-bab5446d7b5d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c8fcf427-17d0-4caa-b406-50703f980862)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0f2444ac-61bd-47cf-9c1e-da86a2b0cfb5)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a37864e-8543-4c52-aa73-e3c190860d76)  
（重要）
</td>
</tr>
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
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b968b0bd-577b-4ea2-a192-a80fe7c20791)  
(KB2572069)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d)  
(KB2572073)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=172c55f3-6249-4ba3-a4a4-677a03262ff3)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ffbdb93-7b92-4197-bb6c-5c305e8072a8)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=14ef20d4-3530-49b2-91b7-d278d9098023)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09e178f8-2bd2-46e1-b975-4938ee1f304d)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3bd62bf6-3400-4c03-95fe-148112b341e8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29228167-b811-43d7-b4a0-91e385b598a5)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d)  
(KB2572073)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f5a0a8db-34d4-4f0a-ab6b-7b2fb420ab91)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7379b3bf-6af0-43cb-bf8b-505e8563fc84)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b35c95f5-30b0-43a9-aa6a-6db63cab0dcb)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9b8030db-1f47-4666-8cb5-1c56577f2340)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b73f4e87-9655-46d5-beb2-ea245dcd280d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0816d729-6769-4ca6-a14e-71750eca8d29)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d)  
(KB2572073)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5825cb4a-47d5-423f-b4c5-2d0fc50856c0)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=11c4878e-df58-4369-b9c0-cb0a230c92dd)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=82653b8c-0e58-440d-9702-8847f599caed)  
(KB2605295)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a618cc19-5ebc-462e-a518-d9bfe41ed98e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=42465652-2664-4fd5-9a22-ae847b08e7c8)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
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
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb)  
(KB2572075)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=630335ac-5a30-46b4-acc1-c4d8bd289668)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=76c8124e-81b9-4a6a-bd53-fbdaf45189aa)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7de276a3-a20d-49de-82b0-51cb22ad73af)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=96b089c0-a2e7-44cb-9fc4-9569b3993afa)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=44f7f10b-86ff-470f-996a-d4aa51c4d18f)  
(KB2579686)  
（重要）  
[Windows Vista 的 Windows Media Center TV Pack（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=60e50f72-4001-423c-831c-8ff1f1b8f090)<sup>[1]</sup>  
(KB2579692)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ff53d01b-97b7-40d2-af88-4978f1099a7c)  
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
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb)  
(KB2572075)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9aabd7a2-0b2f-4c42-a9cf-2ec69ae6b82d)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3454940c-acc2-4e09-8154-075b4be1b697)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3df0c31b-344a-4163-93d2-79df1653b339)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b79a389c-8340-4dd2-9ab1-a0943c5a220f)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cbb66cd7-2688-410f-8a03-fd28e6ef5b01)  
(KB2579686)  
（重要）  
[Windows Vista 的 Windows Media Center TV Pack（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=371c7dab-5aa6-4502-80ee-ae69b736b972)<sup>[1]</sup>  
(KB2579692)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=47322e11-f1cf-4f70-b939-8cac9bbfc2bc)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)\*\*  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb)\*\*  
(KB2572075)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)\*\*<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5660e23c-13a3-4275-ac69-38f03f17491a)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bd144435-1afd-4d6e-a100-fbd613eee409)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=1a7f9855-20ce-4fe0-a903-bd1f145075df)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7cd1ecec-8a3f-4cb2-833c-a177c9602ff5)\*  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c7498ee-eba4-44fd-8846-0b2e96c96705)\*  
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
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)\*\*  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb)\*\*  
(KB2572075)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)\*\*<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=415b1c59-f3dc-4f4f-b2eb-68692d6efc05)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b0c4949f-bce0-4255-a5f2-cf5ecf7416da)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=28a09e42-5865-48b2-af26-ebc8162c3286)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=456e450c-3928-4130-8127-e4d3f482c1ca)\*  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=40386742-f397-402e-8810-63d3d6ba12a6)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507)  
(KB2572067)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb)  
(KB2572075)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=31e68c7f-4db5-463f-a315-92f574af080b)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2e9930d3-ba13-446d-bfa0-60720c48203b)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3633402b-96cb-4f36-b137-d07d1baf28c7)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
</td>
</tr>
<tr class="alternateRow">
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于 32 位系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2)  
(KB2572076)  
（严重）  
仅限 Windows 7（用于 32 位系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618)  
(KB2572077)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4de175be-bbb7-4912-ba4e-d6fe96606c9e)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b49876c7-7c65-4b6d-be9a-9f18be23037b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=02d28e59-b38f-433a-a568-e86f9d43dd42)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=76fcf0ec-9062-4090-acb2-401355341a2b)  
(KB2579686)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9e40bc26-f77f-4b57-9b3d-9d053c19ac56)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2)  
(KB2572076)  
（严重）  
仅限 Windows 7（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618)  
(KB2572077)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=16fd238e-6f65-4d38-88ae-2689817588e1)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=cc0773f2-6099-4d55-9971-ee6546369c7f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=904dec69-e8b9-4b23-a5ea-d3e7e9b9df07)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78c099b7-4bcb-4da7-8967-512c6541c541)  
(KB2579686)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=219554e6-eb5a-42d0-90c0-42b4d0772cfd)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://go.microsoft.com/fwlink/?linkid=226382)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://go.microsoft.com/fwlink/?linkid=221538)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://go.microsoft.com/fwlink/?linkid=227073)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://go.microsoft.com/fwlink/?linkid=225915)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://go.microsoft.com/fwlink/?linkid=227486)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2)\*  
(KB2572076)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618)\*  
(KB2572077)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)\*<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8435781e-0f77-41d0-abb9-9b70f5b02d33)\*\*  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=646a9a56-c343-45cb-a255-303602aa5a64)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c7bd50b7-03f1-4ea4-ad71-d428822c62f8)\*  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=39bd4cfb-fe61-41b8-a5a2-73a9e720fc72)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2)  
(KB2572076)  
（严重）  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618)  
(KB2572077)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a)<sup>[1]</sup>  
(KB2572078)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2676597e-c1d4-4397-8dc4-515ce3d0c5fd)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aa816682-9652-433c-b1b4-5d0bc17b6a87)  
(KB2564958)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0d35c6d0-6d2d-42bf-a97f-4c5e01b1937e)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS11-078 注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS11-076 注释**

<sup>[1]</sup>Windows Vista 的 Windows Media Center TV Pack 作为可选组件，仅在 Windows Vista 的 Home Premium 和 Ultimate 版本的原始设备制造商 (OEM) 安装中可用。在基于 x64 的系统中安装此可选组件的客户应该安装两个可用更新。为保持最佳做法，Microsoft 建议首先安装操作系统更新 (KB2579686)，然后再安装 Windows Media Center TV Pack 更新 (KB2579692)。在 32 位系统上安装了 Media Center TV Pack 的客户仅需要安装 KB2579692。

#### Microsoft 服务器软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-082**](https://go.microsoft.com/fwlink/?linkid=228596)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b7536139-63ea-482a-8d1c-0faad1fcfaa4)  
(KB2578757)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3bc0c89c-56b2-4463-b671-2a58bed9667b)  
(KB2579597)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2009](https://www.microsoft.com/download/details.aspx?familyid=28716ed4-f215-4c69-b6b8-63fbeecefc5b)  
(KB2579598)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2010](https://www.microsoft.com/download/details.aspx?familyid=dbbd67d8-68aa-424d-8eaf-a273a71624d1)  
(KB2579599)  
（重要）
</td>
</tr>
</table>


#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://go.microsoft.com/fwlink/?linkid=227075)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
安装在 Mac 上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f)  
(KB2617986)  
安装在 Microsoft Windows 客户端的所有受支持版本上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f)  
(KB2617986)  
安装在 Microsoft Windows 服务器的所有受支持版本上的 [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f)\*\*  
(KB2617986)
</td>
</tr>
</table>

**MS11-078 注释**

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Remote Access 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-079**](https://go.microsoft.com/fwlink/?linkid=217472)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Unified Access Gateway 2010](https://www.microsoft.com/download/details.aspx?familyid=770ad8ba-4d9a-404e-9515-6ed1e41682df)<sup>[1]</sup>  
(KB2522482)  
（重要）  
[Microsoft Forefront Unified Access Gateway 2010 Update 1](https://www.microsoft.com/download/details.aspx?familyid=b0de8d20-9c25-41c0-9c02-d263b9ed22fa)<sup>[1]</sup>  
(KB2522483)  
（重要）  
[Microsoft Forefront Unified Access Gateway 2010 Update 2](https://www.microsoft.com/download/details.aspx?familyid=166bdfcb-5088-4471-9d51-a3071ac13b73)<sup>[1]</sup>  
(KB2522484)  
（重要）  
[Microsoft Forefront Unified Access Gateway 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8b6ad2ae-e168-45d9-bd3f-5590e0cbd2b5)<sup>[1]</sup>  
(KB2522485)  
（重要）
</td>
</tr>
</table>

**MS11-079** **注释**

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/default.aspx)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [Mila Parkour](https://contagiodump.com) 与 [Adobe Systems, Inc.](https://www.adobe.com) 的 Anshul Kothari 和 Nishant Kaushik 合作报告了 MS11-075 中描述的一个问题
-   [BitDefender](https://www.bitdefender.com/) 的 Andrei Lutas 报告了 MS11-077 中描述的一个问题
-   [Norman](https://www.norman.com/) 的 Tarjei Mandt 报告了 MS11-077 中描述的一个问题
-   Maik Wellmann 报告了 MS11-077 中描述的一个问题
-   [CERT/CC](https://www.cert.org/) 的 Will Dorman 报告了 MS11-077 中描述的一个问题
-   一位匿名人员与 [Beyond Security's SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) 计划团队合作报告了 MS11-078 中描述的一个问题
-   [Tenable Network Security](https://www.tenable.com/) 报告了 MS11-079 中描述的三个问题
-   [SEC Consult Unternehmensberatung GmbH](https://www.sec-consult.com/) 的 Elisabeth Demeter 报告了 MS11-079 中描述的一个问题
-   [National University of Defense Technology](https://www.nudt.edu.cn/) 的 Bo Zhou 报告了 MS11-080 中描述的一个问题
-   McAfee Labs 的 Vishwas Sharma 报告了 MS11-081 中描述的一个问题
-   [Greplin](https://www.greplin.com) 的 David Bloom 报告了 MS11-081 中描述的两个问题
-   Ivan Fratric 与 [TippingPoint's](https://www.tippingpoint.com)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS11-081 中描述的两个问题
-   [GWSlabs](https://www.gwslabs.com)与 [VeriSign iDefense Labs](https://labs.idefense.com) 合作报告了 MS11-081 中描述的一个问题
-   Sebastian Apelt 与 [TippingPoint's](https://www.tippingpoint.com)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS11-081 中描述的一个问题
-   一位匿名研究员与 [TippingPoint's](https://www.tippingpoint.com)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS11-081 中描述的一个问题
-   [Google Inc.](https://www.google.com) 的 Eduardo Vela Nava 和 [Greplin](https://www.greplin.com) 的 David Bloom 与我们一起努力处理了 MS11-081 中包括的纵深防御更改
-   [Soroush Dalili](https://www.secproject.com) 与我们一起努力处理了 MS11-081 中包括的纵深防御更改
-   [Google Inc.](https://www.google.com) 的 Billy Rios 与我们一起努力处理了 MS11-081 中包括的纵深防御更改

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2011 年 10 月 11 日）： 已发布公告摘要。
-   V1.1（2011 年 10 月 26 日）： 对于 MS11-078，更正了 Windows Server 2008 R2（用于基于 x64 的系统）上 .NET Framework 4 的服务器核心安装适用性。

*Built at 2014-04-18T01:50:00Z-07:00*
