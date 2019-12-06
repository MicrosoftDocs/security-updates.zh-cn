---
TOCTitle: 'MS13-FEB'
Title: 'Microsoft 安全公告摘要（2013 年 2 月）'
ms:assetid: 'ms13-feb'
ms:contentKeyID: 61236979
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-feb(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 2 月）
======================================

发布时间: 2013年2月12日 | 更新时间: 2013年2月13日

**版本:** 1.2

本公告摘要列出了 2013 年 2 月发布的安全公告。

对于 2013 年 2 月发布的安全公告，本公告摘要替代 2013 年 2 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 2 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 2 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538626&culture=en-us)提供。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2792100)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中的 13 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;"><strong>矢量标记语言中的漏洞可能允许远程执行代码 (2797052)</strong><br />
<br />
此安全更新可解决矢量标记语言 (VML) 的 Microsoft 实施中一个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则该漏洞可能允许远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;"><strong>媒体解压缩中的漏洞可能允许远程执行代码 (2780091)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果用户打开特制媒体文件（如 .mpg 文件）、打开包含特制嵌入媒体文件的 Microsoft Office 文档（如 .ppt 文件）或收到特制流式内容，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的漏洞可能允许远程执行代码 (2809279)<br />
<br />
</strong>此安全更新可解决 Microsoft Exchange Server 中公开披露的漏洞。最严重的漏洞位于 Microsoft Exchange Server WebReady Document Viewing 中，如果用户使用 Outlook Web App (OWA) 预览特制文件，则这些漏洞可以在 Exchange 服务器上代码转换服务的安全上下文中远程执行代码。Exchange 中用于 WebReady Document Viewing 的代码转换服务在 LocalService 帐户中运行。LocalService 帐户在本地计算机上具有最低特权，在网络上提供匿名凭据。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Server 软件</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;"><strong>OLE 自动化中的漏洞可能允许远程执行代码 (2802968)<br />
<br />
</strong>此安全更新解决 Microsoft Windows 对象链接与嵌入 (OLE) 自动化中一个秘密报告的漏洞。如果用户打开特制文件，则该漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;"><strong>FAST Search Server</strong> <strong>2010 for SharePoint 分析中的漏洞可能允许远程执行代码 (2784242)<br />
<br />
</strong>此安全更新解决了 Microsoft FAST Search Server 2010 for SharePoint 中一个公开披露的漏洞。该漏洞可能允许使用受限制的令牌在用户帐户的安全上下文中远程执行代码。只有当启用高级筛选包时，FAST Search Server for SharePoint 才会受影响。默认情况下，高级筛选包已禁用。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;"><strong>NFS 服务器</strong> <strong>中的漏洞可能允许拒绝服务 (2790978)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者尝试对只读共享执行文件操作，此漏洞可能允许拒绝服务。利用此漏洞的攻击者可能会导致受影响系统停止响应和重新启动。此漏洞仅影响启用了 NFS 角色的 Windows 服务器。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的漏洞可能允许特权提升 (2800277)<br />
<br />
</strong>此安全更新可解决<strong></strong>.NET Framework 中一个秘密报告的漏洞。如果用户使用可运行 XAML 浏览器应用程序 (XBAP) 的 Web 浏览器查看特制网页，则该漏洞可能允许特权提升。Windows .NET 应用程序也可能会使用此漏洞绕过代码访问安全性 (CAS) 限制。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>内核模式驱动程序中的漏洞可能允许特权提升 (2778344)</strong><br />
此安全更新可解决 Microsoft Windows 中秘密报告的 30 个漏洞。这些漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (2799494)</strong><br />
此安全更新可解决 Microsoft Windows 所有受支持版本中的三个秘密报告的漏洞。这些漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;"><strong>TCP/IP 中的漏洞可能允许拒绝服务 (2790655)<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果未经身份验证的攻击者向服务器发送特制的连接终止数据包，此漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统 (CSRSS) 中的漏洞可能允许特权提升 (2790113)<br />
</strong>此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。此漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
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
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。
  
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Shift JIS 字符编码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0015">CVE-2013-0015</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer SetCapture 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0018">CVE-2013-0018</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer COmWindowProxy 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0019">CVE-2013-0019</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CMarkup 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0020">CVE-2013-0020</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer vtable 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0021">CVE-2013-0021</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer LsGetTrailInfo 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0022">CVE-2013-0022</a></td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CDispNode 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0023">CVE-2013-0023</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer pasteHTML 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0024">CVE-2013-0024</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer SLayoutRun 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0025">CVE-2013-0025</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer InsertElement 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0026">CVE-2013-0026</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CPasteCommand 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0027">CVE-2013-0027</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CObjectElement 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0028">CVE-2013-0028</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275670">MS13-009</a></td>
<td style="border:1px solid black;">Internet Explorer CHTML 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0029">CVE-2013-0029</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275837">MS13-010</a></td>
<td style="border:1px solid black;">VML 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0030">CVE-2013-0030</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">Microsoft 获悉此漏洞在有限的目标攻击中被用作信息泄露漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=271307">MS13-011</a></td>
<td style="border:1px solid black;">媒体解压缩漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0077">CVE-2013-0077</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279801">MS13-012</a></td>
<td style="border:1px solid black;">Oracle Outside In 包含多个可利用的漏洞</td>
<td style="border:1px solid black;">多个*</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">* 多个漏洞，详情请参阅 MS13-012 公告。<br />
<br />
这些漏洞已被公开披露。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=272434">MS13-013</a></td>
<td style="border:1px solid black;">Oracle Outside In 包含多个可利用的漏洞</td>
<td style="border:1px solid black;">多个*</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">* 多个漏洞，详情请参阅 MS13-013 公告。<br />
<br />
这些漏洞已被公开披露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276948">MS13-014</a></td>
<td style="border:1px solid black;">空解除引用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1281">CVE-2013-1281</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275736">MS13-015</a></td>
<td style="border:1px solid black;">WinForms 回叫提升漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0073">CVE-2013-0073</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1248">CVE-2013-1248</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是最新软件的纵深防御措施。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1249">CVE-2013-1249</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是最新软件的纵深防御措施。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1250">CVE-2013-1250</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1251">CVE-2013-1251</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1252">CVE-2013-1252</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1253">CVE-2013-1253</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1254">CVE-2013-1254</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1255">CVE-2013-1255</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1256">CVE-2013-1256</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1257">CVE-2013-1257</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1258">CVE-2013-1258</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1259">CVE-2013-1259</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1260">CVE-2013-1260</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1261">CVE-2013-1261</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1262">CVE-2013-1262</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1263">CVE-2013-1263</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1264">CVE-2013-1264</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1265">CVE-2013-1265</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1266">CVE-2013-1266</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1267">CVE-2013-1267</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1268">CVE-2013-1268</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1269">CVE-2013-1269</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1270">CVE-2013-1270</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1271">CVE-2013-1271</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1272">CVE-2013-1272</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1273">CVE-2013-1273</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1274">CVE-2013-1274</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1275">CVE-2013-1275</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1276">CVE-2013-1276</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275718">MS13-016</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1277">CVE-2013-1277</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">内核争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1278">CVE-2013-1278</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">内核争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1279">CVE-2013-1279</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278914">MS13-017</a></td>
<td style="border:1px solid black;">Windows 内核引用计数漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1280">CVE-2013-1280</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278912">MS13-018</a></td>
<td style="border:1px solid black;">TCP FIN WAIT 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0075">CVE-2013-0075</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=278896">MS13-019</a></td>
<td style="border:1px solid black;">引用计数漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0076">CVE-2013-0076</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=279005">MS13-020</a></td>
<td style="border:1px solid black;">OLE 自动化远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1313">CVE-2013-1313</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
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
<tr>  
<th colspan="11" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9bf087e7-4487-48bf-84e9-04b816411a0f)  
(KB2792100)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4501ef62-7d06-49b7-af86-c84e399e6275)  
(KB2792100)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2ab64eac-8ecf-4178-9a01-5f10fc2f049e)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=daed0c2e-bd9a-4685-a5f9-1c01f7fdeccf)  
(KB2797052)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fd693211-bcc8-4267-9aa1-86bac45e25bf)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e8924d23-f6e2-41bf-9542-f8991d084db9)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=95f5acea-32a0-42a5-a14d-837edf313984)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3a8ddbab-5999-48b7-9de8-423954f345b6)  
(KB2802968)
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cdaa7282-c354-4d70-938a-a025631205a2)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9100bf70-8723-4635-9b78-f7c3048a950f)  
(KB2799494)  
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=c42347dd-5ec8-4760-a685-2cd7b6bb7bb2)  
(KB2792100)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6513176c-e9cb-4863-a228-5bc369135996)  
(KB2792100)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=25e15457-ffd2-4466-aff9-1d0830e967d7)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=dd9383b9-a6df-44a7-bea9-8f7d088bc488)  
(KB2797052)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b042e717-bf4e-44a1-a1ba-6359bf551e8e)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c8618c96-25c0-415b-b147-5713ec5ab5b1)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=06ef35a1-f76f-4e99-a8b2-6b086c7e51be)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f72228df-8379-4bd9-b446-cb9505e9d228)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a945336-b037-4ee6-9ea2-dfb885747b97)  
(KB2799494)  
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
<th colspan="11" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
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
无
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=35b58c7a-aae3-4445-957a-42ee708d77a5)  
(KB2792100)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3ee73b80-b8f6-4843-afba-41c7b55faf17)  
(KB2792100)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d67754e2-7ebd-484d-a008-ed8719e0c72d)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9b96ebfc-93e9-41bb-81f9-35c433ca5479)  
(KB2797052)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b902617d-1f35-4b17-9a44-235c0d3c27d2)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=47ca5d22-b957-4ac9-91e9-c440b0614728)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=e3b0b928-0f76-4b51-871a-aeda2ee3b7d5)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8daebdb5-eba2-4685-b781-ead5c2185548)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c005c0a0-4025-4a07-a76d-c57ed5afbd68)  
(KB2799494)  
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=075de724-b996-413f-8ff3-74f435d94b9b)  
(KB2792100)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a90d6861-7ff6-4501-9200-f72b5a9f1817)  
(KB2792100)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=319a7a93-c03e-4c0b-a5c4-6a4f379d781e)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b3ca28b1-9d3c-4df5-b8d7-f31d70f6e714)  
(KB2797052)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e13c9366-9cb6-4e62-bf6c-a09fe7842463)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=80aab9c7-4511-4d44-b570-c77cdb50e542)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=493377a4-4ce2-4dd9-ba84-090466248669)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7d03ef2-517b-4442-a968-5aaa300dd2ba)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dc004424-61f9-49ed-9cb3-b89ed9e98aef)  
(KB2799494)  
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=92ce1fa1-4b12-4fd5-9a02-21fc9b119fb9)  
(KB2792100)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5965ce09-c5d7-4072-bad3-df46f9b76478)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=63791740-00e2-4569-967e-36086efe6ca6)  
(KB2797052)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d1a9b2b2-191c-4ffe-9c8a-8ef641a45eb7)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=8e9a09fd-f360-4471-ac89-481dc2935cec)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb202940-0ece-4631-83d5-8cf52c7dbf36)  
(KB2789643)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=2a3039a4-9b46-4db8-a539-07d52bbf1b92)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3cad66f1-6651-4948-9579-9df050fdaa1b)  
(KB2799494)  
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
<th colspan="11" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
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
无
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=eea43429-2691-4a31-a640-d74035145d2d)  
(KB2792100)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5c195229-8e63-4fff-a304-13c13b2fa132)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7f7ce868-28ce-497e-882f-3abfdd9b89e8)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f946407-cd81-48b5-a279-1ab81388b70b)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e0cfc24f-293c-4817-a69c-f9cfd514e1c1)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4fab0417-5c9a-4e5d-864d-b1b3bee6fc89)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=d730eacf-e30a-45aa-89da-dfec5e87906a)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0ff0475c-cc1b-4886-971e-1a71e6b311c3)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4de1249f-012e-47cb-ad08-4fd5bddb0879)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=80b766e7-3b7f-4d04-9a80-71864a13df8c)  
(KB2790655)  
（中等）
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=308d99ff-7575-4d70-958f-0d57fd6bffab)  
(KB2792100)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d9d4987e-95ad-4246-a52b-7ac859a40e67)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=74b370c0-29f5-4acb-a3cd-bd2c2b708bb7)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ffb3215-1c90-4eb2-9143-0866efc98374)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=649dbf4e-654b-48a2-bd35-2df7f34fbb56)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=44fbe00c-eeb4-4a80-a934-7ce58c02d6ec)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4cd6b10c-b310-4aee-bbca-f23049c14455)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e5043a08-a9e4-422b-8455-80a5091d38b9)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=448ac43a-0a6f-4049-be2b-c853b5dbfab3)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=92bad797-5b66-422c-a096-8070d02bb8b2)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合** **严重等级**
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
无
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
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=71c805ed-a68b-4d3e-97ca-922557cfbf67)  
(KB2792100)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=775ea105-4a71-4b7b-9dc0-50f1eecab96d)  
(KB2792100)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ccdf8abc-9657-4aff-8d73-4824a558c168)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d432acb3-10a0-4f4c-a793-381aedd4bdd1)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b91ce04a-a464-4388-9386-54dd2815b8dd)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=58f0810c-f253-4740-ac9f-75b8a4506b06)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=86cc3b51-818a-49a6-abab-488ac316e021)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c)  
(KB2790655)  
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=de1b96b7-a5ac-4a39-9808-c00c6b1a4325)  
(KB2792100)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e5775802-e529-4894-b1cf-2839948706c2)  
(KB2792100)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=51df1e78-f014-4492-8a3d-83b3c821458b)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=152f90b3-efae-42e6-a845-59052383a8a0)  
(KB2797052)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=304ac41e-b4e5-4bf8-94d2-f2bd9a07bcff)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7b85336a-d3f7-4077-b6eb-55b3042f5335)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=fe239f9b-d986-4828-a01d-8abd494037ec)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c)  
(KB2790655)  
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=61c1964f-9307-4128-9470-bcb20e07856b)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1a2af9dc-e9a7-477e-9943-8132eb7fea81)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](https://www.microsoft.com/download/details.aspx?familyid=4b3e48e3-0dbe-449b-9bca-0ba8bbdcbab0)  
(KB2780091)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b59753f0-b7cb-41c2-9c31-4f2de8356477)  
(KB2789646)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0f84e24c-43f4-4851-932c-8849171b2505)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f3e18038-b8a1-4eba-9542-8396903a3709)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c269c175-f47c-456a-9360-f38bbdfd7ed0)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
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
无
</td>
<td style="border:1px solid black;">
无
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)****
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4df9414b-02da-4254-ab29-5091151e2900)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b21bd7b3-2eb8-433a-b6c2-8243c5128038)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d7d64177-deec-4fd3-9716-b7816fe3c623)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=04a101c6-d553-426f-b3cd-412eefeec580)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=631adede-ba0f-461f-85e1-82b60a7efec1)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=912ac2e1-e737-43fb-acc8-a01a918a8475)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cb4270c4-cec5-49e0-a56b-97539d6352a0)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d4d02ef9-b0a4-46a3-ad92-7508aa26ad3b)  
(KB2790113)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6ef9cbf9-d131-420d-b566-6b0f94f2e1c1)  
(KB2792100)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4b2402ff-035a-47c4-b982-00d428eab379)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d503795a-b1a3-48dc-b1e6-27628aeb150a)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=36eb59be-6703-40c0-b01c-0fffb1456719)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8dab3aca-fde1-4bd9-b82a-e4805a2e8d39)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0d1601cc-fb76-4276-bf0b-a46b7f8055ae)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5d93cb19-7854-4b49-9743-8d6a11be2dd6)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=77277398-c5b4-4ba4-8425-465710b0bef2)  
(KB2790113)  
（重要）
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e7b455a3-6a44-430c-a7d1-30c03ef7f141)  
(KB2792100)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e9d97f2-c006-4e5a-bc80-10450069b8c5)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a36109b-f1e2-4cde-9ede-9f7449c5412c)  
(KB2797052)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=be2fd20a-4c37-47a6-a322-e16acd99db2c)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)  
(KB2790113)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)  
(KB2789644)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c1eb941e-833d-46f0-bf65-d9701d67bc20)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c2e1c1b3-5b75-47cf-91d5-82d413b358e6)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8e37196c-2f43-457d-8d87-336d8775c0bf)  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)  
(KB2789645)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
(KB2789642)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=99320f36-1481-446c-bc3e-d33fcfd1f2c1)  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9f0b132a-8616-49cd-8927-393f35d0cf21)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e1be5dea-dd13-42b5-a37f-4bcd828cc65f)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9fbc37dd-53ec-4de1-b1c1-9761a8f83ab8)  
(KB2790113)  
（重要）
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
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
无
</td>
<td style="border:1px solid black;">
无
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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=7966de38-c6a6-4137-8b7e-8ccd3306521a)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=0389b515-59bf-4733-aab4-ffb822efdbea)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=d5395864-1822-4151-a10c-f6a036f8853f)  
(KB2778344)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=5b74e5b3-7b8d-4669-b403-c776e70bf072)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=e7739ba6-9c62-4180-a095-47fdb6c741e9)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=d6720d21-269b-4605-b95e-573bc327afd9)  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=c1859853-d43f-4497-b212-e6a4daa43485)  
(KB2797052)  
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
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=79aaaa3a-747a-4320-9fd2-5f4a6de3d13c)  
(KB2778344)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=a41a2b38-5e5c-48bc-8727-e19402519f12)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=dd2042b8-c784-4dfc-8fca-61905693cda5)  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
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
无
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
<td style="border:1px solid black;">
无
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=8e3fdcd0-ab75-4500-aac7-7ecb4f39fca7)  
(KB2792100)  
（中等）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=3b39813e-5ee2-412e-b1f1-a16617a70f43)  
(KB2797052)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6)  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)  
(KB2789650)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)  
(KB2789649)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9)  
(KB2778344)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741)  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2)  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer10<sup>[1]</sup>  
(KB2792100)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer10<sup>[1]</sup>  
(KB2797052)  
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
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2778344)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2790655)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="11" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-009**](https://go.microsoft.com/fwlink/?linkid=275670)
</td>
<td style="border:1px solid black;">
[**MS13-010**](https://go.microsoft.com/fwlink/?linkid=275837)
</td>
<td style="border:1px solid black;">
[**MS13-011**](https://go.microsoft.com/fwlink/?linkid=271307)
</td>
<td style="border:1px solid black;">
[**MS13-020**](https://go.microsoft.com/fwlink/?linkid=279005)
</td>
<td style="border:1px solid black;">
[**MS13-014**](https://go.microsoft.com/fwlink/?linkid=276948)
</td>
<td style="border:1px solid black;">
[**MS13-015**](https://go.microsoft.com/fwlink/?linkid=275736)
</td>
<td style="border:1px solid black;">
[**MS13-016**](https://go.microsoft.com/fwlink/?linkid=275718)
</td>
<td style="border:1px solid black;">
[**MS13-017**](https://go.microsoft.com/fwlink/?linkid=278914)
</td>
<td style="border:1px solid black;">
[**MS13-018**](https://go.microsoft.com/fwlink/?linkid=278912)
</td>
<td style="border:1px solid black;">
[**MS13-019**](https://go.microsoft.com/fwlink/?linkid=278896)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=850e319f-dd6e-4480-86c3-a5129f084817)（服务器核心安装）  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d7a74c8-de4b-4bcb-8b3f-581858d0776b)（服务器核心安装）  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c24aa6f3-82a5-4b1f-adc8-4aece948161c)（服务器核心安装）  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8978769b-447b-4b01-848a-cbcdf692f17a)（服务器核心安装）  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c9fbb7cc-c33b-4af9-8416-9d16015e79c1)（服务器核心安装）  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2738fbe4-2163-4e77-82e6-208a7a08a70c)（服务器核心安装）  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）（服务器核心安装）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)（服务器核心安装）  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=3b25dd48-053d-4d9e-9774-905c66c3aca9)（服务器核心安装）  
(KB2789644)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)（服务器核心安装）  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)（服务器核心安装）  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)（服务器核心安装）  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)（服务器核心安装）  
(KB2790113)  
（重要）
</td>
</tr>
<tr class="alternateRow">
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aadb2003-ed7b-46ee-afd0-33cec4ac39b4)（服务器核心安装）  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=0da657e5-161d-46bc-a2b7-7c4696e37062)（服务器核心安装）  
(KB2789645)  
（重要）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=182f4d35-f18b-4485-be22-43becbd3cc05)<sup>[1]</sup>  
（服务器核心安装）(KB2789642)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b5cfc358-e5ff-445c-8d43-3f79fead6139)（服务器核心安装）  
(KB2789648)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ca5a8735-1568-454d-8b4c-b83107eac036)（服务器核心安装）  
(KB2778344)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=201e6d1f-425b-406e-84a1-37cee035dddb)（服务器核心安装）  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=01284b28-043a-4e27-b363-c1e641164a01)（服务器核心安装）  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=97241fdb-991d-4411-8fe1-ea56172360ab)（服务器核心安装）  
(KB2790113)  
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=b284296a-1db5-47dc-af2c-bf55d0ad09e6)（服务器核心安装）  
(KB2790978)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=639674a0-12a3-4185-9858-b2a31ed2f014)（服务器核心安装）  
(KB2789650)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=27d83684-d4f7-4fe0-a54d-25a3d2009be0)（服务器核心安装）  
(KB2789649)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=aac38d33-fad6-4060-bad4-61cf7c059af9)（服务器核心安装）  
(KB2778344)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=4e427f56-436e-43d0-b4f8-eee8427b3741)（服务器核心安装）  
(KB2799494)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=f74a104d-4749-4dd5-b144-2e4ce9c284a2)（服务器核心安装）  
(KB2790655)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS13-009、MS13-010、MS13-017 和 MS13-018 的注释**

<sup>[1]</sup> Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS13-015 的注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

**MS13-016 的注释**

<sup>[1]</sup>Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

<sup>[2]</sup>对于指定软件，严重等级不适用于此更新。然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新。

#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-012**](https://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](https://go.microsoft.com/fwlink/?linkid=272434)
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
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=316a1aff-b72d-4d96-8ee5-bd86b0e29e6f)  
(KB2788321)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=498e7612-73b5-4e28-99a4-b3157ac69932)  
(KB2746164)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft FAST Search Server 2010 for SharePoint
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-012**](https://go.microsoft.com/fwlink/?linkid=279801)
</td>
<td style="border:1px solid black;">
[**MS13-013**](https://go.microsoft.com/fwlink/?linkid=272434)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft FAST Search Server 2010 for SharePoint Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[高级筛选包](https://www.microsoft.com/download/details.aspx?familyid=0ae86754-69a8-4c82-855c-2ee2b7887fa5)<sup>[1]</sup>  
(KB2553234)  
（重要）
</td>
</tr>
</table>

**MS13-013 的注释**

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS13-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](https://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](https://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

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

-   Masato Kinugawa 报告了 MS13-009 中描述的问题
-   [Omair](https://krash.in/) 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的两个问题
-   SkyLined 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的问题
-   Arthur Gerkis 与 Exodus Intelligence 合作报告了 MS13-009 中描述的问题
-   [Harmony Security](https://www.harmonysecurity.com) 的 Stephen Fewer 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的两个问题
-   [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的问题
-   Tencent PC 经理报告了 MS13-009 中描述的问题
-   Arthur Gerkis 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的问题
-   一位匿名研究员与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的问题
-   [Security-Assessment.com](https://www.security-assessment.com) 的 Scott Bell 报告了 MS13-009 中描述的问题
-   Yenteasy Security Research 的 Jose A Vazquez 与 Exodus Intelligence 合作报告了 MS13-009 中描述的问题
-   Yenteasy Security Research 的 Jose A Vazquez 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-009 中描述的问题
-   IBM X-Force 的 Mark Yason 报告了 MS13-009 中描述的问题
-   [NCC Group](https://www.nccgroup.com/) 的 Ollie Whitehouse 与我们一起努力处理了 MS13-009 中包括的其他纵深防御更改
-   [Tencent Security Team](https://security.tencent.com/) 报告了 MS13-011 中描述的问题
-   [Context Information Security](https://www.contextis.com/) 的 James Forshawor 报告了 MS13-015 中描述的一个问题
-   [Google Inc](https://www.google.com) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 和 [Tencent Security Team](https://security.tencent.com/) 报告了 MS13-016 中描述的两个问题
-   [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 MS13-016 中描述的 25 个问题
-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 MS13-016 中描述的 3 个问题
-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 MS13-017 中描述的 2 个问题
-   Max DeLiso 与我们一起努力处理了 MS13-019 中描述的问题
-   一位匿名研究员与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS13-020 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 2 月 12 日）： 已发布公告摘要。
-   V1.1（2013 年 2 月 12 日）： 对于 MS13-009，在 CVE-2013-0022 的“**利用指数**”中更正了最新软件版本的利用评估。
-   V1.2（2013 年 2 月 13 日）： 对于 MS13-014，在 CVE-2013-1281 的“**利用指数**”中更正了最新软件版本的利用评估。

*Built at 2014-04-18T01:50:00Z-07:00*
