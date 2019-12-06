---
TOCTitle: 'MS13-APR'
Title: 'Microsoft 安全公告摘要（2013 年 4 月）'
ms:assetid: 'ms13-apr'
ms:contentKeyID: 61236976
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-apr(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 4 月）
======================================

发布时间: 2013年4月9日 | 更新时间: 2013年6月25日

**版本:** 4.0

本公告摘要列出了 2013 年 4 月发布的安全公告。

对于 2013 年 4 月发布的安全公告，本公告摘要替代 2013 年 4 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 4 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 4 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538640&culture=en-us)提供。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2817183)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中两个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;"><strong>远程桌面客户端中的漏洞可能允许远程执行代码</strong> <strong>(2828223)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Windows 远程桌面客户端中一个秘密报告的漏洞。如果用户查看特制网页，此漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;"><strong>SharePoint 中的漏洞可能允许信息泄露 (2827663)</strong> <strong><br />
<br />
</strong>此安全更新解决了 Microsoft SharePoint Server 中一个公开披露的漏洞。如果攻击者确定特定 SharePoint 列表的地址或位置，并且获得对维护该列表的 SharePoint 网站的访问权限，则此漏洞可能允许信息泄露。攻击者需要能够满足 SharePoint 网站的身份验证请求才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (2813170)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。这些漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的漏洞可能导致拒绝服务 (2830914)<br />
<br />
</strong>此安全更新可解决 Active Directory 中一个秘密报告的漏洞。如果攻击者向轻型目录访问协议 (LDAP) 服务发送特制查询，则此漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统 (CSRSS) 中的漏洞可能允许特权提升 (2820917)<br />
<br />
</strong>在 Windows XP、Windows Vista、Windows Server 2003 和 Windows Server 2008 的所有受支持版本中，此安全更新可解决一个秘密报告的漏洞。如果攻击者登录系统并运行特制应用程序，则该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;"><strong>Microsoft 反恶意软件客户端中的漏洞可能允许特权提升 (2823482)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft 反恶意软件客户端中一个秘密报告的漏洞。由于 Microsoft 反恶意软件客户端使用的路径名称，此漏洞可能允许特权提升。成功利用此漏洞的攻击者可执行任意代码，并可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。攻击者必须拥有有效的登录凭据才能利用此漏洞。匿名用户无法利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft 安全软件</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;"><strong>HTML 清理组件中的漏洞可能允许特权提升 (2821818)</strong> <strong><br />
<br />
</strong>此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果攻击者将特制内容发送给用户，则该漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office，<br />
Microsoft Server 软件</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;"><strong>内核模式驱动程序中的漏洞可能允许特权提升 (2829996)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中的三个秘密报告的漏洞和一个公开披露的漏洞。如果攻击者登录系统并运行特制应用程序，最严重的漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用最严重的漏洞。</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1303">CVE-2013-1303</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1304">CVE-2013-1304</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285215">MS13-028</a></td>
<td style="border:1px solid black;">Internet Explorer 释放后使用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1338">CVE-2013-1338</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286679">MS13-029</a></td>
<td style="border:1px solid black;">RDP ActiveX 控件远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1296">CVE-2013-1296</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286577">MS13-030</a></td>
<td style="border:1px solid black;">不正确的访问权限信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1290">CVE-2013-1290</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。<br />
<br />
此漏洞已公开披露。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">内核争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1284">CVE-2013-1284</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=282388">MS13-031</a></td>
<td style="border:1px solid black;">内核争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1294">CVE-2013-1294</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=280660">MS13-032</a></td>
<td style="border:1px solid black;">内存消耗漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1282">CVE-2013-1282</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=286700">MS13-033</a></td>
<td style="border:1px solid black;">CSRSS 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1295">CVE-2013-1295</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">在 Windows Server 2003 和 Windows XP Professional x64 Edition 上，这是一个特权提升漏洞。<br />
<br />
在 Windows XP、Windows Vista 和 Windows Server 2008 上，这是一个特权提升漏洞。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=276805">MS13-034</a></td>
<td style="border:1px solid black;">Microsoft 反恶意软件不正确路径名称漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0078">CVE-2013-0078</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=285672">MS13-035</a></td>
<td style="border:1px solid black;">HTML 清理漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1289">CVE-2013-1289</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">Microsoft 获悉尝试使用此漏洞的有限目标攻击。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1283">CVE-2013-1283</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=281927">MS13-036</a></td>
<td style="border:1px solid black;">Win32k 争用条件漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1292">CVE-2013-1292</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
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
<th colspan="7" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f7b699b1-7655-4c8f-bd1a-535ff210b338)  
(2817183)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e9f9848e-b926-4487-9dc2-b2a6b6f5f98e)  
(2817183)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4cf0de09-2e8d-4be0-bbbf-d040164f22e0)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=353812de-b1eb-4245-82e3-7829cb72bba3)  
(2813345)  
（严重）  
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=1754fdde-4744-4783-b6d3-e38eb2874b58)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=69de7e3c-d99b-432a-b286-f45841edc4a7)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=8adb6ced-6065-454b-ba67-b0acd621df76)  
(2801109)  
（低）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f47a73d3-05f6-4c7d-b063-c83dd0070c2d)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=75914c2a-37bb-4541-81ed-a602acb27a14)  
(2808735)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=4496bce8-809e-458c-b199-49b32eef7b21)  
(2817183)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9d792ad9-c2d7-4972-9f27-4580af04571c)  
(2817183)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c3bdbbb8-57a2-4474-9b86-239f7a77e658)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=f413845a-84e0-48d9-b5bc-56a37109ab33)  
(2813345)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=74855fb1-cad1-463f-a02d-1c27a39667c9)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=9fb780b9-bbca-45ec-98db-da413f0ccddf)  
(2801109)  
（低）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c143a028-2c38-469f-a563-be8030ec76e3)  
(2820917)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=20a1f311-5cdc-4675-a228-32993d8be3f9)  
(2808735)  
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
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=8d834fd2-eaa0-4742-a8a2-93277ca41f91)  
(2817183)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b0cbbaaf-be40-4088-b3d3-ca85410807b7)  
(2817183)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cd2731b3-406e-4b73-bd70-4f2bb16dfb08)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=75b00750-80c3-4ffa-adbf-5f40a41309b9)  
(2813345)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c242d48-8dbe-4474-ba39-f7e3ebe9a604)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=c27666a5-67ff-4e2d-b9d7-2cef19da1edd)  
(2772930)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=13eb9459-0a39-4652-b577-6d8509801f62)  
(2801109)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=63ffbd1a-79a9-47c8-a904-b6e9a0fb626f)  
(2820917)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0722d681-eda8-48af-b079-36d45eb20f98)  
(2808735)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7149ecda-78d3-4289-81b2-5133cd9b4564)  
(2817183)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f22de9fa-96e0-4a09-8923-8731e0de38c9)  
(2817183)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=08c55acd-4c5e-4d5e-b524-19fd449e5c50)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=7efb8816-ca23-4a75-a0cc-53a663eac3a9)  
(2813345)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b7af0c30-0d09-434a-85d6-69e7e9ee9e29)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=1b009894-8503-42b6-85d1-1285ed14bef9)  
(2772930)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=30c0c8d8-df70-4637-bea4-96e2e4d2cb28)  
(2801109)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bf96696e-13a4-4b01-a8d9-60654d7d1ac5)  
(2820917)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fc5f39a7-e89b-4ef0-887c-873ad546fb65)  
(2808735)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b10b94db-b281-46b6-b301-58f14de327d2)  
(2817183)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9d799925-5f8e-43c8-8674-19437a7a6c99)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=54e286a0-22f5-4b34-a246-c98c0647f093)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=0b65be9e-724d-469d-ba3b-93d8b174aecb)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c56d776a-4293-4d3c-bcac-cd5f50eeb328)  
(2820917)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=dd159949-e0f0-4515-876d-837758a3fd51)  
(2808735)  
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
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5591feef-5bc6-4e3e-9bbb-cd2205757340)  
(2817183)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e244c3f1-3c4e-4648-b1f9-e216b0009f1e)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=190a78a5-e557-44f3-b214-7d3c904f7bd8)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=20500712-2c0f-41e2-95a8-db1a5dcf717a)  
(2813345)  
（严重）  
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=1bf2935a-2fa4-4a26-bccf-fe0b63a16b37)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f1aa4bd-a14e-4797-b542-4220e3d9d0d7)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=e1b1a3b4-7aae-4934-96cc-990cd1ce962d)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=10664eeb-f759-4a0e-b1df-c463aae43902)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3881a7f9-a5f1-4a28-b652-7b7f20c05259)  
(2808735)  
（重要）  
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=55d753f3-b912-401c-bca6-61c212ffa0df)  
(2840149)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1bcd238f-2758-49f7-a347-7ec998637d5c)  
(2817183)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c35f53d6-eceb-4966-9487-2dfc2652c775)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=6cfdb0d5-9c47-405f-bc60-0e4dd3eaff12)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=4c6f006c-fcb8-499f-bd91-9c8acb3ec3c3)  
(2813345)  
（严重）  
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=201eb194-e7c9-479c-bb03-646b22f2bbd1)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d6b3ef0e-16e3-42cb-bffe-4b046f995771)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=ca2182ae-cd47-48d7-9bb0-4aeda4ee26cc)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c12ce8b7-e8e2-47ac-bdaa-874dff5a6115)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e5ba88a4-e0ec-45d7-8c0a-611521351890)  
(2808735)  
（重要）  
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=89f1556f-442f-4888-b21a-ffbedaa8792e)  
(2840149)  
（中等）
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
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=09bd431a-e94f-4fc5-bea9-569ebc17b0f3)  
(2817183)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=76f96697-0f07-49ad-9169-47cfe2f6a362)  
(2817183)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=2d8c4080-ff7a-42ef-95f4-36b642c0a089)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=92bd1819-46f9-4a9b-bf2b-ea6aaaee9890)  
(2813345)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71)  
(2808735)  
（重要）  
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081)  
(2840149)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e46e002e-40b2-4bb3-89ad-63d320273ffa)  
(2817183)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b93153dc-f83a-4891-8230-765e3472614d)  
(2817183)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=08abb2ce-0a07-4f25-b9ad-5ec87c07f0bf)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=6518cdc6-10a6-46ed-a2f6-6f58216fe319)  
(2813345)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0)  
(2808735)  
（重要）  
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2)  
(2840149)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b0d20b3f-f6cb-4cbc-9af1-1d33b4a6dfb2)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 6.1 Client](https://www.microsoft.com/download/details.aspx?familyid=4807c3fe-bc54-4db6-a9b0-ee21bdd9820f)  
(2813345)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6133c84a-b2ce-4a2e-8afc-7386caf80cc8)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=94971d7b-df42-4566-97eb-0a7572b0e2da)  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3e9ccb95-284a-478e-b521-f3a0acbae8da)  
(2808735)  
（重要）  
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=738b2263-e1eb-4ada-a7f0-5165f42bc5c9)  
(2840149)  
（中等）
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
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
（重要）  
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ec9c221a-065b-4f5c-95b6-9b650c24cffa)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=041fd330-0998-44b5-bedd-d3e47965370d)  
(2817183)  
（严重）  
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=cf49622e-8494-4082-a9aa-a6699711d827)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](https://www.microsoft.com/download/details.aspx?familyid=d7623f17-783d-431a-8274-17d71df72202)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=90d2c454-c31c-4ac4-ab94-b341d1244ee6)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=37b3e861-35fb-471b-b81a-a8b58bd26647)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1abeaf49-c458-4046-a001-8aee0ba35b3a)  
(2808735)  
（重要）  
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=808ac8c6-394d-406b-b34e-07d03c760c27)  
(2840149)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
（重要）  
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=01f4b588-38e3-43a7-ae5c-674b9c03fc42)  
(2817183)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ac93c656-2c9c-4378-9ae3-a60636b8ce6f)  
(2817183)  
（严重）  
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=775536fa-a8a2-4733-a0f0-08e742be1122)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](https://www.microsoft.com/download/details.aspx?familyid=5595efaa-3d57-4c9a-8b53-7cfa06093f1e)  
(2813347)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ebc1ea79-158f-4c81-ab49-3d3fca870363)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=94d19c2a-2457-4fa7-ade6-ad37d0e7f56a)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84275cfd-f5a3-4830-895d-beaf162cdc27)  
(2808735)  
（重要）  
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=737a0cd0-eee6-4095-b9b1-2822024dd825)  
(2840149)  
（中等）
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
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d8ffa592-6336-494d-bcd0-535ea2821525)  
(2817183)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7f68500e-6699-4341-b129-2dbd5bc508ac)  
(2817183)  
（中等）  
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=752ffe45-b251-4cdf-9848-4d15f75d4452)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](https://www.microsoft.com/download/details.aspx?familyid=79c870b9-b800-4f59-a5ea-19a5c890af52)  
(2813347)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)  
(2840149)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.0 Client](https://www.microsoft.com/download/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2dec754b-4d51-4792-bee6-67e94a1a8157)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
[Remote Desktop Connection 7.1 Client](https://www.microsoft.com/download/details.aspx?familyid=c7047403-8c2a-42de-bea5-d7354847730a)  
(2813347)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5cfc2f18-4cde-4e21-8604-f694d69da535)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6c577423-cd17-4317-98a3-5f6e767513c0)  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3f1abf13-14c3-4a92-b4c1-4caa40e29e7b)  
(2840149)  
（中等）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
**无**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=159c43ec-beaf-4ac3-8c3a-06a9716ac9ae)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=02d6d10e-3708-4424-8618-88414694c973)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=c7a7ba4d-1fe1-40ed-81f2-6fbb6dde2cf6)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=882f2d67-b8e0-4859-871b-6a7cef27e3e5)  
(2808735)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=3309f621-4087-4688-b991-c2ef54532cb6)  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=18992e76-70f3-43a2-b47f-199c9728c7ca)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=bafaac33-2bef-4a5e-9451-23ca69c0a132)  
(2772930)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=852dac0f-75fe-443f-9b3d-1dbcac166b3d)  
(2808735)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=5015e763-6fb8-4737-9305-2e5850ef853d)  
(2817183)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a)  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务](https://www.microsoft.com/download/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9)  
(2808735)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
**无**
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer10<sup>[1]</sup>  
(2817183)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(2808735)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-028**](https://go.microsoft.com/fwlink/?linkid=285215)
</td>
<td style="border:1px solid black;">
[**MS13-029**](https://go.microsoft.com/fwlink/?linkid=286679)
</td>
<td style="border:1px solid black;">
[**MS13-031**](https://go.microsoft.com/fwlink/?linkid=282388)
</td>
<td style="border:1px solid black;">
[**MS13-032**](https://go.microsoft.com/fwlink/?linkid=280660)
</td>
<td style="border:1px solid black;">
[**MS13-033**](https://go.microsoft.com/fwlink/?linkid=286700)
</td>
<td style="border:1px solid black;">
[**MS13-036**](https://go.microsoft.com/fwlink/?linkid=281927)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=527ea8cd-88db-448a-b8e4-0fdf87fa369c)（服务器核心安装）  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=dd955bf1-e51f-4738-82bf-759e9dea0895)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31561241-07c8-4396-ad80-9c62a2394658)（服务器核心安装）  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e598863e-7ca1-42a6-9cb4-3f3a10f0ce71)（服务器核心安装）  
(2808735)  
（重要）  
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a4bdfe68-4de2-41fa-a593-2e07de105081)（服务器核心安装）  
(2840149)  
（中等）
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
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=604709f7-8712-4162-ab86-5988b19084f9)（服务器核心安装）  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=38d1cd8c-977b-47be-b703-a326a1b4f445)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=46ef3ace-30b2-4099-aa9d-142de82b0257)（服务器核心安装）  
(2820917)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a9dd92b5-4137-47d1-85a3-506f1eaacee0)（服务器核心安装）  
(2808735)  
（重要）  
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1c36a50c-023d-420d-830a-d4cb2eda6ef2)（服务器核心安装）  
(2840149)  
（中等）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)（服务器核心安装）  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)（服务器核心安装）  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)（服务器核心安装）  
(2840149)  
（中等）
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
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=dbbd2e3d-1b37-4173-9955-e6fceb7bcd45)（服务器核心安装）  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=78d11246-06b0-4a22-a2b0-c772aa60e726)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cbaac7fb-b673-4cf5-8c6f-57bedcb5285d)（服务器核心安装）  
(2808735)  
（重要）  
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3e96483f-ec2d-4335-8c50-8686eed06018)（服务器核心安装）  
(2840149)  
（中等）
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
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=ef106525-c42b-4b25-83bf-e290e2bcad5a)（服务器核心安装）  
(2813170)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 服务](https://www.microsoft.com/download/details.aspx?familyid=209e3d5f-9333-469e-8b2c-212dc4ec764a)  
(2772930)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=fbf53f06-1ee2-49c4-a5a8-3b1e9823b1b9)（服务器核心安装）  
(2808735)  
（重要）
</td>
</tr>
</table>

**MS13-028、MS13-031,** **和 MS13-036 的注释**

<sup>[1]</sup> Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-035**](https://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=63f6a338-a195-4923-908e-8c21713c7373)  
(2687422)  
（没有严重等级）<sup>[1]</sup>  
[Microsoft InfoPath 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f1cd73d2-411b-4a58-b8c0-04fd58922dae)  
(2760406)  
（没有严重等级）<sup>[1]</sup>
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=ae2069d0-55b5-4dfe-9131-41888d6bbec3)  
(2687422)  
（没有严重等级）<sup>[1]</sup>  
[Microsoft InfoPath 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f206071a-4502-432a-9e5b-50bb4e3f1757)  
(2760406)  
（没有严重等级）<sup>[1]</sup>
</td>
</tr>
</table>

**MS13-035 的注释**

<sup>[1]</sup>严重等级不适用于指定软件的此更新，因为该漏洞的的已知攻击媒介已被阻止。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

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
[**MS13-030**](https://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](https://go.microsoft.com/fwlink/?linkid=285672)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)](https://www.microsoft.com/download/details.aspx?familyid=6c7d007f-5c8d-464c-af04-4e7800a2e2a6)<sup>[1]</sup>  
(2687421)  
（重要）  
[Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)](https://www.microsoft.com/download/details.aspx?familyid=c59c0d25-8d6c-4dda-a06b-e42891a9ddae)<sup>[1]</sup>  
(2760408)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2013 (coreserverloc)](https://www.microsoft.com/download/details.aspx?familyid=2e5b1e49-0355-4111-a464-224bb2192029)<sup>[1]</sup>  
(2737969)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-030**](https://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](https://go.microsoft.com/fwlink/?linkid=285672)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d63ee461-b823-4eb1-9e6d-82f380627fb5)  
(2687424)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-030**](https://go.microsoft.com/fwlink/?linkid=286577)
</td>
<td style="border:1px solid black;">
[**MS13-035**](https://go.microsoft.com/fwlink/?linkid=285672)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ac805c46-8661-4e99-84da-c395dc05beb0)  
(2810059)  
（重要）
</td>
</tr>
</table>

**MS13-030 的注释**

<sup>[1]</sup>此更新要求预先安装 Project Server 2013 累积性更新 (2768001)。有关该更新的详细信息，包括下载链接，请参阅 [Microsoft 知识库文章 2768001](https://support.microsoft.com/kb/2768001)。

**MS13-035 的注释**

<sup>[1]</sup>对于 Microsoft SharePoint Server 2010 的受支持版本，除了安全 Microsoft SharePoint 2010 安全更新程序包（2687421 和 2760408）外，客户还需要安装 Microsoft SharePoint Foundation 2010 安全更新 (2687418)，以免受本公告中所描述的漏洞影响。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Office Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-035**](https://go.microsoft.com/fwlink/?linkid=285672)
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
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1d35b235-305a-45c8-a395-7658792d177e)  
(2760777)  
（重要）
</td>
</tr>
</table>

**MS13-035 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 安全软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
反恶意软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-034**](https://go.microsoft.com/fwlink/?linkid=276805)
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
用于 Windows 8 和 Windows RT 的 Windows Defender
</td>
<td style="border:1px solid black;">
用于 Windows 8 和 Windows RT 的 Windows Defender<sup>[1]</sup>  
(2781197)  
（重要）
</td>
</tr>
</table>

**MS13-034 的注释**

<sup>[1]</sup>此更新通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

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

**MS13-028**

-   [Google Security Team](https://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1303)
-   [Google Security Team](https://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1304)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 释放后使用漏洞 (CVE-2013-1338)
-   一名匿名研究员与我们合作处理了此公告中包括的纵深防御更改

**MS13-029**

-   c1d2d9acc746ae45eeb477b97fa74688 与 [HP 的](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 RDP ActiveX 控件远程执行代码漏洞 (CVE-2013-1296)

**MS13-031**

-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了内核争用条件漏洞 (CVE-2013-1284)
-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了内核争用条件漏洞 (CVE-2013-1294)

**MS13-033**

-   George Georgiev Valkov 报告了 CSRSS 内存损坏漏洞 (CVE-2013-1295)

**MS13-034**

-   [Intel](https://www.intel.com/) 的 Bruce Monroe 报告了 Microsoft 反恶意软件不正确路径名称漏洞 (CVE-2013-0078)
-   Shai Sarfaty 报告了 Microsoft 反恶意软件不正确路径名称漏洞 (CVE-2013-0078)
-   Centrica 的 Tony Robotham 报告了 Microsoft 反恶意软件不正确路径名称漏洞 (CVE-2013-0078)

**MS13-035**

-   [Google Security Team](https://www.google.com/) 的 Drew Hintz 和 Andrew Lyons 报告了 HTML 清理漏洞 (CVE-2013-1289)

**MS13-036**

-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 Win32k 争用条件漏洞 (CVE-2013-1283)
-   [Qihoo 360 Security Center](https://www.360.cn/) 的 Wang Yu 报告了 Win32k 字体分析漏洞 (CVE-2013-1291)
-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 Win32k 争用条件漏洞 (CVE-2013-1292)
-   [Gynvael Coldwind](https://gynvael.coldwind.pl/) 和 [Google Inc](https://www.google.com/) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 与我们一起努力处理了 NTFS 空指针解除引用漏洞 (CVE-2013-1293)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 4 月 9 日）： 已发布公告摘要。
-   V1.1 （2013 年 4 月 10 日）： 对于 MS13-029，将 Windows 7 Service Pack 1 和 Windows Server 2008 R2 Service Pack 1 上的远程桌面连接客户端的版本号从 7.0 更改至 7.1。这仅仅是一个信息更改。没有更改安全更新文件。
-   V2.0 （2013 年 4 月 11 日）： 对于 MS13-036，由于已知安装问题而删除了安全更新 2823324 的链接。有关详细信息，请参阅公告。
-   V3.0 （2013 年 4 月 23 日）： 对于 MS13-036，已将安装在 Windows Vista、Windows Server2008、Windows 7 和 Windows Server2008 R2 的受支持版本上的 NTFS.sys 的 2823324 更新替换为 2840149 更新。有关详细信息，请参阅更新常见问题。
-   V3.1（2013 年 4 月 24 日）： 对于 MS13-028，针对 CVE-2013-1338 在“**利用指数**”中添加了利用评估。这仅仅是一个信息更改。
-   V4.0（2013 年 6 月 25 日）： 对于 MS13-029，已修订公告以重新发布在 Windows XP Service Pack3 上运行的 Remote Desktop Connection7.0 客户端的 2813347 更新。有关详细信息，请参阅公告。

*Built at 2014-04-18T01:50:00Z-07:00*
