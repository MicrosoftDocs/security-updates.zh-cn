---
TOCTitle: 'MS13-MAY'
Title: 'Microsoft 安全公告摘要（2013 年 5 月）'
ms:assetid: 'ms13-may'
ms:contentKeyID: 61236984
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-may(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 5 月）
======================================

发布时间: 2013年5月14日 | 更新时间: 2013年5月22日

**版本:** 1.1

本公告摘要列出了 2013 年 5 月发布的安全公告。

对于 2013 年 5 月发布的安全公告，本公告摘要替代 2013 年 5 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 5 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 5 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538728&culture=en-us)提供。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累积性安全更新 (2829530)<br />
<br />
</strong>此安全更新解决 Internet Explorer 中的 11 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 安全更新 (2847204)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中一个公开披露的漏洞。如果用户使用 Internet Explorer 查看特制网页，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;"><strong>HTTP.sys 中的漏洞可能允许拒绝服务 (2829254)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者向受影响的 Windows 服务器或客户端发送特制 HTTP 数据包，该漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的漏洞可能允许欺骗 (2836440)<br />
<br />
</strong>此安全更新可解决 .NET Framework 中<strong></strong>的一个秘密报告的漏洞和一个公开披露的漏洞。如果 .NET 应用程序收到特制 XML 文件，则最严重的漏洞可能允许欺骗。成功利用这些漏洞的攻击者可能会修改 XML 文件的内容，而不会使文件的签名无效，如果他们成为经身份验证的用户，则可以获得对终结点功能的访问权限。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
欺骗</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;"><strong>Lync 中的漏洞可能允许远程执行代码 (2834695)</strong><br />
<br />
此安全更新可解决 Microsoft Lync 中一个秘密报告的漏洞。如果攻击者在 Lync 或 Communicator 中演示时共享特制内容（例如文件或程序），然后诱使用户接受邀请以查看或共享可演示的内容，则该漏洞可能允许远程执行代码。在所有情况下，攻击者无法强迫用户查看或共享由攻击者控制的文件或程序。相反，攻击者必须说服用户执行操作，方法通常是让用户接受 Lync 或 Communicator 中的邀请以查看或共享可演示的内容。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher 中的漏洞可能允许远程执行代码 (2830397)<br />
<br />
</strong>此安全更新可解决 Microsoft Office 中 11 个秘密报告的漏洞。如果用户使用受影响的 Microsoft Publisher 版本打开特制的 Publisher 文件，则这两个漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word 中的漏洞可能允许远程执行代码 (2830399)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft Office 中一个秘密报告的漏洞。如果用户打开特制文件或在受影响的 Microsoft Office 软件版本中预览特制的电子邮件，则该漏洞可能允许执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的漏洞可能允许信息泄露 (2834692)<br />
<br />
</strong>此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果用户打开特制的 Visio 文件，则该漏洞可能允许信息泄露。请注意，虽然攻击者无法利用此漏洞来执行代码或直接提升他们的用户权限，但此漏洞可用于产生信息，这些信息可用于试图进一步危及受影响系统的安全。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;"><strong>Windows 软件包中的漏洞可能导致信息泄露 (2813707)<br />
<br />
</strong>此安全更新可解决 Windows 软件包中一个秘密报告的漏洞。如果用户使用特制 URL 打开 Windows Writer，则该漏洞可能允许信息泄露。成功利用此漏洞的攻击者可能会替代 Windows Writer 代理设置并覆盖目标系统上用户可以访问的文件。在基于 Web 的攻击情形中，网站可能包含用于利用此漏洞的特制链接。攻击者必须说服用户访问该网站，并打开特制链接。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows 软件包</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;"><strong>内核模式驱动程序中的漏洞可能允许特权提升</strong> <strong>(2840221)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中三个秘密报告的漏洞。这些漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>最新软件版本的利用评估</th>  
<th>较旧软件版本的利用评估</th>  
<th>拒绝服务利用评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0811">CVE-2013-0811</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">JSON 阵列信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1297">CVE-2013-1297</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1306">CVE-2013-1306</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1307">CVE-2013-1307</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1308">CVE-2013-1308</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1309">CVE-2013-1309</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1310">CVE-2013-1310</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1311">CVE-2013-1311</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1312">CVE-2013-1312</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2551">CVE-2013-2551</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=294283">MS13-037</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3140">CVE-2013-3140</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299892">MS13-038</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1347">CVE-2013-1347</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试通过 Internet Explorer 8 利用此漏洞的攻击。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293363">MS13-039</a></td>
<td style="border:1px solid black;">HTTP.sys 拒绝服务漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1305">CVE-2013-1305</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">XML 数字签名欺骗漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1336">CVE-2013-1336</a></td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是欺骗漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296485">MS13-040</a></td>
<td style="border:1px solid black;">身份验证绕过漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1337">CVE-2013-1337</a></td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
这是一个安全功能绕过漏洞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293445">MS13-041</a></td>
<td style="border:1px solid black;">Lync RCE 漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1302">CVE-2013-1302</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 负值分配漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1316">CVE-2013-1316</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 整数溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1317">CVE-2013-1317</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 损坏界面指针漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1318">CVE-2013-1318</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 返回值处理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1319">CVE-2013-1319</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1320">CVE-2013-1320</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 返回值验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1321">CVE-2013-1321</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 无效的范围检查漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1322">CVE-2013-1322</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 不正确的空值处理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1323">CVE-2013-1323</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 签名整数漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1327">CVE-2013-1327</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 指针处理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1328">CVE-2013-1328</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287106">MS13-042</a></td>
<td style="border:1px solid black;">Publisher 缓冲区下溢漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1329">CVE-2013-1329</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=287107">MS13-043</a></td>
<td style="border:1px solid black;">Word 形状损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1335">CVE-2013-1335</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293446">MS13-044</a></td>
<td style="border:1px solid black;">XML 外部实体解析漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1301">CVE-2013-1301</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280675">MS13-045</a></td>
<td style="border:1px solid black;">Windows Essentials 不正确 URI 处理漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0096">CVE-2013-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">DirectX 图形内核子系统双重提取漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1332">CVE-2013-1332</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Win32k 缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1333">CVE-2013-1333</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=296427">MS13-046</a></td>
<td style="border:1px solid black;">Win32k 窗口句柄漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1334">CVE-2013-1334</a></td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="6" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
（严重）  
Internet Explorer 7  
(2829530)  
（严重）  
Internet Explorer 8  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2829361)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
（严重）  
Internet Explorer 7  
(2829530)  
（严重）  
Internet Explorer 8  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2829361)  
（重要）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
（中等）  
Internet Explorer 7  
(2829530)  
（中等）  
Internet Explorer 8  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
（中等）  
Internet Explorer 7  
(2829530)  
（中等）  
Internet Explorer 8  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2829530)  
（中等）  
Internet Explorer 7  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804577)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
（严重）  
Internet Explorer 8  
(2829530)  
（严重）  
Internet Explorer 9  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2830290)  
（重要）  
Windows Vista Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
（严重）  
Internet Explorer 8  
(2829530)  
（严重）  
Internet Explorer 9  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2830290)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
（中等）  
Internet Explorer 8  
(2829530)  
（中等）  
Internet Explorer 9  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2830290)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
（中等）  
Internet Explorer 8  
(2829530)  
（中等）  
Internet Explorer 9  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2830290)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2804580)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2830290)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
（严重）  
Internet Explorer 9  
(2829530)  
（严重）  
Internet Explorer 10  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2830290)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(2829361)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
（严重）  
Internet Explorer 9  
(2829530)  
（严重）  
Internet Explorer 10  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（严重）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2830290)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2829361)  
（重要）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
（中等）  
Internet Explorer 9  
(2829530)  
（中等）  
Internet Explorer 10  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）  
Internet Explorer 9  
(2847204)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2830290)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2847204)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2830290)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2829254)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
（重要）  
Microsoft .NET Framework 4.5  
(2804583)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2830290)  
（重要）  
Windows 8（用于 32 位系统）  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2829254)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
（重要）  
Microsoft .NET Framework 4.5  
(2804583)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2830290)  
（重要）  
Windows 8（用于 64 位系统）  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2829254)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
（重要）  
Microsoft .NET Framework 4.5  
(2804583)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2830290)  
（重要）  
Windows Server 2012  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2829530)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows RT  
(2829254)  
（中等）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2804583)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT  
(2830290)  
（重要）  
Windows RT  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-037**](http://go.microsoft.com/fwlink/?linkid=294283)
</td>
<td style="border:1px solid black;">
[**MS13-038**](http://go.microsoft.com/fwlink/?linkid=299892)
</td>
<td style="border:1px solid black;">
[**MS13-039**](http://go.microsoft.com/fwlink/?linkid=293363)
</td>
<td style="border:1px solid black;">
[**MS13-040**](http://go.microsoft.com/fwlink/?linkid=296485)
</td>
<td style="border:1px solid black;">
[**MS13-046**](http://go.microsoft.com/fwlink/?linkid=296427)
</td>
</tr>
<tr class="alternateRow">
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2830290)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2830290)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2829361)  
（没有严重等级）
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
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2804579)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2804576)  
（重要）  
Microsoft .NET Framework 4.5  
(2804582)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2830290)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2829361)  
（没有严重等级）
</td>
</tr>
<tr class="alternateRow">
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
(2829254)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2804584)  
（重要）  
Microsoft .NET Framework 4.5  
(2804583)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2830290)  
（重要）  
Windows Server 2012（服务器核心安装）  
(2829361)  
（没有严重等级）
</td>
</tr>
</table>

**MS13-040 注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-042**](http://go.microsoft.com/fwlink/?linkid=287106)
</td>
<td style="border:1px solid black;">
[**MS13-043**](http://go.microsoft.com/fwlink/?linkid=287107)
</td>
<td style="border:1px solid black;">
[**MS13-044**](http://go.microsoft.com/fwlink/?linkid=293446)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2003 Service Pack 3  
(2810047)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Word 2003 Service Pack 3  
(2810046)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2007 Service Pack 3  
(2597971)  
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
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 Service Pack 1（32 位版本）  
(2553147)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Publisher 2010 Service Pack 1（64 位版本）  
(2553147)  
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2817361)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3  
(2810062)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 3  
(2596595)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1（32 位版本）  
(2810068)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1（64 位版本）  
(2810068)  
（重要）
</td>
</tr>
</table>


#### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-041**](http://go.microsoft.com/fwlink/?linkid=293445)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
Microsoft Communicator 2007 R2  
(2827753)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010（32 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010（32 位）  
(2827750)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010（64 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010（64 位）  
(2827750)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(2827752)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）  
(2827751)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（Web 组件服务器）
</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（Web 组件服务器）  
(2827754)  
（重要）
</td>
</tr>
</table>


#### Microsoft 客户工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Windows Essentials
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-045**](http://go.microsoft.com/fwlink/?linkid=280675)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 软件包 2011
</td>
<td style="border:1px solid black;">
Windows 软件包 2011  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 软件包 2012
</td>
<td style="border:1px solid black;">
Windows 软件包 2012  
(2813707)  
（重要）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS13-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](http://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](http://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS13-037**

-   Jose Antonio Vazquez Gonzalez 与 [VeriSign iDefense Labs](http://labs.idefense.com) 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-0811)
-   Yosuke Hasegawa 和 Masahiro Yamada 报告了 JSON 数组信息泄露漏洞 (CVE-2013-1297)
-   SkyLined 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1306)
-   [Security-Assessment.com](http://www.security-assessment.com/) 的 Scott Bell 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1306)
-   [Google Security Team](http://www.google.com/) 的 Ivan Fratric 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1307)
-   [Aniway.Aniway@gmail.com](mailto:aniway.anyway@gmail.com) 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1308)
-   SkyLined 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1309)
-   Yuhong Bao 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1310)
-   [Security-Assessment.com](http://www.security-assessment.com/) 的 Scott Bell 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1311)
-   [Harmony Security](http://www.harmonysecurity.com) 的 Stephen Fewer 与[HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1312)
-   [VUPEN Security](http://www.vupen.com) (Pwn2Own 2013) 与[HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative 合作](http://www.zerodayinitiative.com/)报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-2551)
-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-3140)
-   Masato Kinugawa 与我们合作处理了此公告中包括的纵深防御更改。
-   [VUPEN Security](http://www.vupen.com) (Pwn2Own 2013) 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/)合作处理了此公告中的纵深防御更改。

**MS13-038**

-   [FireEye](http://www.fireeye.com/) 的 Daniel Caseldenfor 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1347)
-   [iSIGHT Partners](http://www.isightpartners.com/) 与我们合作处理了 Internet Explorer 释放后使用漏洞 (CVE-2013-1347)

**MS13-039**

-   Marek Kroemeke、22733db72ab3ed94b5f8a1ffcde850251fe6f466、AKAT-1与 [HP 的](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 HTTP.sys 拒绝服务漏洞 (CVE-2013-1305)

**MS13-040**

-   [Context Information Security](http://www.contextis.com/) 的 James Forshaw 报告了 XML 数字签名欺骗漏洞 (CVE-2013-1336)

**MS13-042**

-   [CERT/CC](http://www.cert.org/) 的 Will Dormann 与我们一起努力处理了多个 Microsoft Publisher 远程执行代码漏洞（CVE-2013-1316、CVE-2013-1317、CVE-2013-1318、CVE-2013-1319、CVE-2013-1320、CVE-2013-1321、CVE-2013-1322、CVE-2013-1323、CVE-2013-1327、CVE-2013-1328 和 CVE-2013-1329）

**MS13-043**

-   [CERT/CC](http://www.cert.org/) 的 Will Dormann 报告了 Word 形状损坏漏洞 (CVE-2013-1335)

**MS13-044**

-   [Positive Technologies](http://www.ptsecurity.com/) 的 Timur Yunusov 报告了 XML 外部实体解析漏洞 (CVE-2013-1301)

**MS13-045**

-   Andrea Micalizzi 与 Beyond Security 的 [SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) 团队一起报告了 Windows 软件包不正确 URI 处理漏洞 (CVE-2013-0096)

**MS13-046**

-   [Gynvael Coldwind](http://gynvael.coldwind.pl/) 和 [Google Inc](http://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 报告了 DirectX 图形内核子系统双重提取漏洞 (CVE-2013-1332)
-   [Qihoo 360 Security Center](http://www.360.cn/) 报告了 Win32k 缓冲区溢出漏洞 (CVE-2013-1333)
-   一名匿名研究员与 [iDefense VCP](http://labs.idefense.com/) 合作报告了 Win32k 窗口句柄漏洞 (CVE-2013-1334)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 5 月 14 日）： 已发布公告摘要。
-   V1.1 （2013 年 5 月 22 日）： 对于 MS13-037，更正了常见问题和披露号码 CVE-2013-3140。这仅仅是信息更改。

*Built at 2014-04-18T01:50:00Z-07:00*
