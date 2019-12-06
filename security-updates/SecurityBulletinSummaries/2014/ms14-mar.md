---
TOCTitle: 'MS14-MAR'
Title: 'Microsoft 安全公告摘要（2014 年 3 月）'
ms:assetid: 'ms14-mar'
ms:contentKeyID: 61598072
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-mar(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 3 月）
======================================

发布日期： 发布日期：2014 年 3 月 11 日 | 更新时间： 2014 年 9 月 18 日

**版本：** 1.1

本公告摘要列出了 2014 年 3 月发布的安全公告。

对于 2014 年 3 月发布的安全公告，本公告摘要替代 2014 年 3 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 3 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 3 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572977&culture=en-us)。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2925418)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中 1 个公开披露的漏洞和 17 个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392071">MS14-013</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft DirectShow 中的漏洞可能允许远程执行代码 (2929961)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开特制的图像文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (2930275)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露和一个秘密报告的漏洞。如果攻击者登录系统并运行特制应用程序，较严重的漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392066">MS14-016</a></p></td>
<td style="border:1px solid black;"><p><strong>安全帐户管理器远程 (SAMR) 协议中的漏洞可能允许安全功能绕过 (2934418)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者多次尝试对一个用户名匹配密码，此漏洞可能允许安全功能绕过。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392070">MS14-014</a></p></td>
<td style="border:1px solid black;"><p><strong>Silverlight 中的漏洞可能允许安全功能绕过 (2932677)</strong><br />
<br />
此安全更新解决了 Microsoft Silverlight 中一个秘密报告的漏洞。如果攻击者拥有包含旨在利用此漏洞的特制 Silverlight 内容的网站，然后诱使用户查看该网站，则该漏洞可能允许安全功能绕过。但是在所有情况下，攻击者无法强制用户访问网站。相反，攻击者必须诱使用户访问该网站，通常是让用户单击电子邮件或 Instant Messenger 消息中的链接使用户链接到攻击者的网站。它还可能使用横幅广告或其他方式显示特制的 Web 内容，以便将 Web 内容传递至受影响的系统。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>无需重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Silverlight</p></td>
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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0297">CVE-2014-0297</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0298">CVE-2014-0298</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0299">CVE-2014-0299</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0302">CVE-2014-0302</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0303">CVE-2014-0303</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0304">CVE-2014-0304</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0305">CVE-2014-0305</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0306">CVE-2014-0306</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0307">CVE-2014-0307</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0308">CVE-2014-0308</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0309">CVE-2014-0309</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0311">CVE-2014-0311</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0312">CVE-2014-0312</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0313">CVE-2014-0313</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0314">CVE-2014-0314</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0321">CVE-2014-0321</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0322">CVE-2014-0322</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试在 Internet Explorer 10 中利用此漏洞的有限目标攻击。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0324">CVE-2014-0324</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试在 Internet Explorer 8 中利用此漏洞的有限目标攻击。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392064">MS14-012</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4112">CVE-2014-4112</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392071">MS14-013</a></p></td>
<td style="border:1px solid black;"><p>DirectShow 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0301">CVE-2014-0301</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392070">MS14-014</a></p></td>
<td style="border:1px solid black;"><p>Silverlight DEP/ASLR 绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0319">CVE-2014-0319</a></p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0300">CVE-2014-0300</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392067">MS14-015</a></p></td>
<td style="border:1px solid black;"><p>Win32k 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0323">CVE-2014-0323</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />  
这是较旧软件版本上一个信息泄露漏洞。<br />  
<br />
这是最新软件版本上的一个拒绝服务漏洞。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=392066">MS14-016</a></p></td>
<td style="border:1px solid black;"><p>SAMR 安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0317">CVE-2014-0317</a></p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能绕过漏洞。</p></td>
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
<td style="border:1px solid black;" colspan="5">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
（严重）  
Internet Explorer 7   
(2925418)  
（严重）  
Internet Explorer 8   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
（安装了 Active Directory 应用程序模式）  
(2933528)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
（严重）  
Internet Explorer 7   
(2925418)  
（严重）  
Internet Explorer 8   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
（安装了 Active Directory 应用程序模式）  
(2933528)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
(2925418)  
（中等）  
Internet Explorer 7  
(2925418)  
（中等）  
Internet Explorer 8  
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
（安装了 Active Directory）  
(2923392)  
（重要）  
Windows Server 2003 Service Pack 2  
（安装了 Active Directory 应用程序模式）  
(2933528)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
（中等）  
Internet Explorer 7  
(2925418)  
（中等）  
Internet Explorer 8  
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
（安装了 Active Directory）  
(2923392)  
（重要）  
Windows Server 2003 x64 Edition Service Pack 2  
（安装了 Active Directory 应用程序模式）  
(2933528)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2925418)  
（中等）  
Internet Explorer 7  
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
（安装了 Active Directory）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
（严重）  
Internet Explorer 8  
(2925418)  
（严重）  
Internet Explorer 9   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
（安装了 Active Directory 轻型目录服务 (AD LDS)）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
（严重）  
Internet Explorer 8  
(2925418)  
（严重）  
Internet Explorer 9   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
（安装了 Active Directory 轻型目录服务 (AD LDS)）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(2925418)  
（中等）  
Internet Explorer 8  
(2925418)  
（中等）  
Internet Explorer 9   
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
（中等）  
Internet Explorer 8  
(2925418)  
（中等）  
Internet Explorer 9   
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
无

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
（严重）  
Internet Explorer 9   
(2925418)  
（严重）  
Internet Explorer 10   
(2925418)  
（严重）  
Internet Explorer 11   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2930275)  
（重要）

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
(2925418)  
（严重）  
Internet Explorer 9   
(2925418)  
（严重）  
Internet Explorer 10   
(2925418)  
（严重）  
Internet Explorer 11   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
(2925418)  
（中等）  
Internet Explorer 9   
(2925418)  
（中等）  
Internet Explorer 10   
(2925418)  
（中等）  
Internet Explorer 11   
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
无

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2930275)  
（重要）

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
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2930275)  
（重要）

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
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2930275)  
（重要）

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
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（安装了 Active Directory）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2925418)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2929961)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（安装了 Active Directory）  
(2923392)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(2930275)  
（重要）

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
(2925418)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-012**](https://go.microsoft.com/fwlink/?linkid=392064)

</td>
<td style="border:1px solid black;">
[**MS14-013**](https://go.microsoft.com/fwlink/?linkid=392071)

</td>
<td style="border:1px solid black;">
[**MS14-015**](https://go.microsoft.com/fwlink/?linkid=392067)

</td>
<td style="border:1px solid black;">
[**MS14-016**](https://go.microsoft.com/fwlink/?linkid=392066)

</td>
</tr>
<tr>
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
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
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
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
（安装了 Active Directory 或 Active Directory 轻型目录服务(AD LDS)）  
(2923392)  
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
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
（安装了 Active Directory）  
(2923392)  
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
(2930275)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
（安装了 Active Directory）  
(2923392)  
（重要）

</td>
</tr>
</table>

 

**Microsoft 开发工具和软件**

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-014**](https://go.microsoft.com/fwlink/?linkid=392070)

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
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(2932677)  
（重要）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(2932677)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(2932677)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2932677)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(2932677)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2932677)  
（重要）

</td>
</tr>
</table>

 

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

**MS14-012**

-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0297)
-   Amol Naik 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0297)
-   [NCC Group](https://www.nccgroup.com/) 的 Edward Torkington 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0297)
-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0298)
-   Yenteasy - Security Research 的 Jose A. Vazquez 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0299)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0302)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0303)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Hui Gao 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0304)
-   [Qihoo](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0304)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Tianfang Guo 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0305)
-   Jason Kratzer 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0306)
-   Jason Kratzer 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0307)
-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0308)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0308)
-   Jason Kratzer 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0308)
-   Amol Naik 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0309)
-   [Security-Assessment.com](https://www.security-assessment.com/) 的 Scott Bell 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0311)
-   [Qihoo](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0311)
-   Simon Zuckerbraun 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0312)
-   [Omair](https://krash.in/) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0313)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0314)
-   [Qihoo](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0314)
-   [Qihoo](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0314)
-   Anil Aphale 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0314)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [Qihoo](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [Qihoo](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [Qihoo](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0321)
-   [FireEye, Inc.](https://www2.fireeye.com/) 与我们合作处理了 Internet Explorer 内存损坏漏洞 (CVE-2014-0322)
-   [Qihoo](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0322)
-   Yenteasy - Security Research 的 Jose A. Vazquez 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-4112)

**MS14-013**

-   一位匿名研究人员与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 DirectShow 内存损坏漏洞 (CVE-2014-0301)

**MS14-014**

-   [NSFOCUS Information Technology Co., Ltd.](https://en.nsfocus.com/) 报告了 Silverlight DEP/ASLR 绕过漏洞 (CVE-2014-0319)

**MS14-015**

-   Alexander Chizhov 与我们一起处理了 Win32k 信息泄露漏洞 (CVE-2014-0323)

**MS14-016**

-   Samba Team 的 Andrew Bartlett 和 Catalyst IT 报告 SAMR 安全功能绕过漏洞 (CVE-2014-0317)
-   巴基斯坦的 [Muhammad Faisal Naqvi](https://ae.linkedin.com/in/mfaisalnaqvi) 报告了 SAMR 安全功能绕过漏洞 (CVE-2014-0317)

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

-   V1.0（2014 年 3 月 11 日）： 已发布公告摘要。
-   V1.1（2014 年 9 月 18 日）： 对于 MS14-012，针对 CVE-2014-4066 在“利用指数”中添加了利用评估。这仅仅是一个信息更改。

*页面生成时间：2014-09-18 10:01Z-07:00。*
