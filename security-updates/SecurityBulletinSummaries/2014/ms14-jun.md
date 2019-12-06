---
TOCTitle: 'MS14-JUN'
Title: 'Microsoft 安全公告摘要（2014 年 6 月）'
ms:assetid: 'ms14-jun'
ms:contentKeyID: 62490174
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms14-jun(v=Security.10)'
---



Microsoft 安全公告摘要（2014 年 6 月）
======================================

发布日期： 2014 年 6 月 10 日 | 更新日期： 2014 年 6 月 17 日

**版本：** 1.1

本公告摘要列出了 2014 年 6 月发布的安全公告。

对于 2014 年 6 月发布的安全公告，本公告摘要替代 2014 年 6 月 5 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2014 年 6 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 6 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572980&culture=en-us)。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (2969262)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中 2 个公开披露的漏洞和 57 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics 组件中的漏洞可能允许远程执行代码 (2967487)</strong><br />
<br />
此安全更新解决了 Microsoft Windows、Microsoft Office 和 Microsoft Lync 中 2 个秘密报告的漏洞。如果用户打开特制文件或网页，则漏洞可能允许远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、Microsoft Office、Microsoft Lync</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Word 中的漏洞可能允许远程执行代码 (2969261)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中一个秘密报告的漏洞。如果特制文件在 Microsoft Word 受影响的版本中打开，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的客户比具有管理用户权限的客户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft XML Core Services 中的漏洞可能允许信息泄露 (2966061)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果登录用户访问设计为通过 Internet Explorer 调用 Microsoft XML Core Services (MSXML) 的特制网站，该漏洞可能允许信息泄露。但是在所有情况下，攻击者无法强制用户访问此类网站。相反，攻击者必须诱使用户访问一个网站，方法通常是让用户单击电子邮件或 Instant Messenger 请求中的链接以使用户链接到攻击者的网站。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄露</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Lync Server 中的漏洞可能允许信息泄露 (2969258)</strong><br />
<br />
此安全更新解决了 Microsoft Lync Server 中一个秘密报告的漏洞。如果用户试图通过单击特制会议 URL 来加入 Lync 会议，则此漏洞可能允许信息泄露。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄露</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Lync Server</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></p></td>
<td style="border:1px solid black;"><p><strong>TCP 协议中的漏洞可能允许拒绝服务 (2962478)<br />
</strong><br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者向目标系统发送一系列特制数据包，则该漏洞可能允许拒绝服务。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></p></td>
<td style="border:1px solid black;"><p><strong>远程桌面中的漏洞可能允许篡改 (2969259)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者在活动远程桌面协议 (RDP) 会话期间获得对目标系统所在的同一网络段的访问权限，然后向目标系统发送特制 RDP 数据包，则该漏洞可能允许篡改。在任何 Windows 操作系统上，RDP 默认为未启用。没有启用 RDP 的系统不受威胁。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
篡改</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></p></td>
<td style="border:1px solid black;"><p>RDP MAC 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0296">CVE-2014-0296</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个篡改漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></p></td>
<td style="border:1px solid black;"><p>TCP 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1811">CVE-2014-1811</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></p></td>
<td style="border:1px solid black;"><p>Lync Server 内容清理漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1823">CVE-2014-1823</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></p></td>
<td style="border:1px solid black;"><p>MSXML 实体 URI 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1816">CVE-2014-1816</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></p></td>
<td style="border:1px solid black;"><p>嵌入字体漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2778">CVE-2014-2778</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0282">CVE-2014-0282</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1762">CVE-2014-1762</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1764">CVE-2014-1764</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1766">CVE-2014-1766</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1769">CVE-2014-1769</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1770">CVE-2014-1770</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>TLS 服务器证书重新协商漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1771">CVE-2014-1771</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。<br />
<br />
此漏洞已公开披露。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1772">CVE-2014-1772</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1773">CVE-2014-1773</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1774">CVE-2014-1774</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1775">CVE-2014-1775</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1777">CVE-2014-1777</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1778">CVE-2014-1778</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1779">CVE-2014-1779</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1780">CVE-2014-1780</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1781">CVE-2014-1781</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1782">CVE-2014-1782</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1783">CVE-2014-1783</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1784">CVE-2014-1784</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1785">CVE-2014-1785</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1786">CVE-2014-1786</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1788">CVE-2014-1788</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1789">CVE-2014-1789</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1790">CVE-2014-1790</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1791">CVE-2014-1791</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1792">CVE-2014-1792</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1794">CVE-2014-1794</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1795">CVE-2014-1795</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1796">CVE-2014-1796</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1797">CVE-2014-1797</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1799">CVE-2014-1799</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1800">CVE-2014-1800</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1802">CVE-2014-1802</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1803">CVE-2014-1803</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1804">CVE-2014-1804</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1805">CVE-2014-1805</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2753">CVE-2014-2753</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2754">CVE-2014-2754</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2755">CVE-2014-2755</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2756">CVE-2014-2756</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2757">CVE-2014-2757</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2758">CVE-2014-2758</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2759">CVE-2014-2759</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2760">CVE-2014-2760</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2761">CVE-2014-2761</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2763">CVE-2014-2763</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2764">CVE-2014-2764</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2765">CVE-2014-2765</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2766">CVE-2014-2766</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2767">CVE-2014-2767</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2768">CVE-2014-2768</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2769">CVE-2014-2769</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2770">CVE-2014-2770</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2771">CVE-2014-2771</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2772">CVE-2014-2772</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2773">CVE-2014-2773</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2775">CVE-2014-2775</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2776">CVE-2014-2776</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2777">CVE-2014-2777</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2782">CVE-2014-2782</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>Unicode 脚本处理器漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Windows 软件。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>Unicode 脚本处理器漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Office 软件。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>Unicode 脚本处理器漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Lync 软件。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>GDI+ 图像分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Windows 软件。<br />
<br />
这是最新软件上的一个拒绝服务漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>GDI+ 图像分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Office 软件。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></p></td>
<td style="border:1px solid black;"><p>GDI+ 图像分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>此利用评估适用于受影响的 Microsoft Lync 软件。</p></td>
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(2957689)  
（重要）  
Internet Explorer 7  
(2957689)  
（重要）  
Internet Explorer 8  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2003 Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）  
安装在 Microsoft Windows 2000 Service Pack 4 上的  
(2957482)  
（低）

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
(2957689)  
（重要）  
Internet Explorer 7  
(2957689)  
（重要）  
Internet Explorer 8  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2003 x64 Edition Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）  
安装在 Microsoft Windows 2000 Service Pack 4 上的  
(2957482)  
（低）

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
(2957689)  
（重要）  
Internet Explorer 7  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）  
安装在 Microsoft Windows 2000 Service Pack 4 上的  
(2957482)  
（低）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
（严重）  
Internet Explorer 8  
(2957689)  
（严重）  
Internet Explorer 9  
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Vista Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2957189)  
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
(2957689)  
（严重）  
Internet Explorer 8  
(2957689)  
（严重）  
Internet Explorer 9  
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(2957689)  
（重要）  
Internet Explorer 8  
(2957689)  
（重要）  
Internet Explorer 9  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2957189)  
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
(2957689)  
（重要）  
Internet Explorer 8  
(2957689)  
（重要）  
Internet Explorer 9  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2957189)  
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
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
（严重）  
Internet Explorer 9  
(2957689)  
（严重）  
Internet Explorer 10  
(2957689)  
（严重）  
Internet Explorer 11  
(2957689)  
（严重）  
Internet Explorer 11  
(2963950)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(Windows GDI+)  
(2957503)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2965788)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
（严重）  
Internet Explorer 9  
(2957689)  
（严重）  
Internet Explorer 10  
(2957689)  
（严重）  
Internet Explorer 11  
(2957689)  
（严重）  
Internet Explorer 11  
(2963950)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(Windows GDI+)  
(2957503)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2965788)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
（重要）  
Internet Explorer 9  
(2957689)  
（重要）  
Internet Explorer 10  
(2957689)  
（重要）  
Internet Explorer 11  
(2957689)  
（重要）  
Internet Explorer 11  
(2963950)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2957189)  
（重要）

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
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(gdi32)  
(2964736)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2965788)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(gdi32)  
(2964736)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2965788)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
（严重）  
Internet Explorer 11  
(2963950)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(gdi32)  
(2964736)  
（严重）  
Windows 8.1（用于 32 位系统）  
(gdi32)  
(2965155)  
（严重）  
Windows 8.1（用于 32 位系统）  
(DirectWrite)  
(2964718)  
（严重）  
Windows 8.1（用于 32 位系统）  
(DirectWrite)  
(2965161)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）  
Microsoft XML Core Services 3.0  
(2966631)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2957189)  
（重要）  
Windows 8.1（用于 32 位系统）  
(2961858)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2965788)  
（重要）  
Windows 8.1（用于 32 位系统）  
(2966034)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
（严重）  
Internet Explorer 11  
(2963950)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(gdi32)  
(2964736)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(gdi32)  
(2965155)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(DirectWrite)  
(2964718)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(DirectWrite)  
(2965161)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）  
Microsoft XML Core Services 3.0  
(2966631)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2957189)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(2961858)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2965788)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(2966034)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(gdi32)  
(2964736)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2965788)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
（重要）  
Internet Explorer 11  
(2963950)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(gdi32)  
(2964736)  
（严重）  
Windows Server 2012 R2  
(gdi32)  
(2965155)  
（严重）  
Windows Server 2012 R2  
(DirectWrite)  
(2964718)  
（严重）  
Windows Server 2012 R2  
(DirectWrite)  
(2965161)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）  
Microsoft XML Core Services 3.0  
(2966631)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2957189)  
（重要）  
Windows Server 2012 R2  
(2961858)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2965788)  
（重要）  
Windows Server 2012 R2  
(2966034)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(gdi32)  
(2964736)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(2957189)  
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
(2957689)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(gdi32)  
(2964736)  
（严重）  
Windows RT 8.1  
(DirectWrite)  
(2964718)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-035**](https://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](https://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](https://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](https://go.microsoft.com/fwlink/?linkid=400970)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2957189)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2957189)  
（重要）

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(Windows GDI+)  
(2957503)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(usp10)  
(2957509)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 和 Microsoft XML Core Services 6.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2957189)  
（重要）

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
Windows Server 2012（服务器核心安装）  
(gdi32)  
(2964736)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2957189)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2965788)  
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
Windows Server 2012 R2（服务器核心安装）  
(gdi32)  
(2964736)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(gdi32)  
(2965155)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(DirectWrite)  
(2964718)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(DirectWrite)  
(2965161)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(2939576)  
（低）  
Microsoft XML Core Services 3.0  
(2966631)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2957189)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(2961858)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(2965788)  
（重要）  
Windows Server 2012 R2（服务器核心安装）  
(2966034)  
（重要）

</td>
</tr>
</table>

**MS14-036 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2878233)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(2881069)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2880515)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

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
Microsoft Office 2010 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2863942)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2767915)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2863942)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2767915)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2863942)  
（重要）  
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2767915)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2863942)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2767915)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 兼容包**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](https://go.microsoft.com/fwlink/?linkid=400971)

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
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2880513)  
（重要）

</td>
</tr>
</table>

**MS14-036 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console\[

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(2968966)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(2963285)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(2963285)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
(2963282)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(2963284)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
（Web 组件服务器）  
(2963286)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS14-036**](https://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](https://go.microsoft.com/fwlink/?linkid=400969)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013（64 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(2881013)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
（Web 组件服务器）  
(2963288)  
（重要）

</td>
</tr>
</table>

**MS14-036 注释**

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

**MS14-030**

-   [Tripwire](https://www.tripwire.com/) 的 Andrew Swoboda 和 Tyler Reguly 报告了 RDP MAC 漏洞 (CVE-2014-0296)

     

**MS14-033**

-   Christian Kulenkampff 报告了 MSXML 实体 URI 漏洞 (CVE-2014-1816)

     

**MS14-034**

-   s3tm3m 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了嵌入字体漏洞 (CVE-2014-2778)

     

**MS14-035**

-   Simon Zuckerbraun 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0282)
-   [Qihoo 360](https://www.360.cn/) 的 Renguang Yuan 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-0282)
-   [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 AbdulAziz Hariri、Matt Molinyawe 和 Jasiel Spelman 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1762)
-   [VUPEN](https://www.vupen.com/) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 特权提升漏洞 (CVE-2014-1764)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1766)
-   Andreas Schmidt 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1766)
-   IronRock 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1766)
-   一位匿名研究人员与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1766)
-   [OUSPG](https://www.ee.oulu.fi/research/ouspg/) 的 Atte Kettunen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1769)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1769)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1769)
-   [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Abdul-Aziz Hariri 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1769)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://weibo.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1769)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1770)
-   Institut National de Recherche en Informatique et en Automatique (INRIA) 的 Prosecco 小组报告了 TLS 服务器证书重新协商漏洞 (CVE-2014-1771)
-   [Omair](https://krash.in/) 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1772)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1772)
-   [Trend Micro](https://www.trendmicro.com/) 的 Jack Tang 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1772)
-   [Venustech Active-Defense Laboratory](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1772)
-   John Villamil 和 Sean Larsson 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1773)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://weibo.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1773)
-   AMol NAik 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1774)
-   [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 与[HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1775)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Hui Gao 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1775)
-   TELUS Security Labs 漏洞研究小組的 Arezou Hosseinzad-Amirkhizi 报告了Internet Explorer内存损坏漏洞 (CVE-2014-1775)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 Internet Explorer 信息泄露漏洞 (CVE-2014-1777)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了 Internet Explorer 特权提升漏洞 (CVE-2014-1778)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1779)
-   [Soroush Dalili](https://www.secproject.com/) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1780)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1781)
-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   [knownsec](https://www.knownsec.com/) 的 ZhaoWei 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   35c27308b34d55904da10770e5303503 与 [iSIGHT Partners GVP Program](https://gvp.isightpartners.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   IronRock 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1782)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1783)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1784)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1784)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1784)
-   SkyLined 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1785)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1785)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1785)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1786)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1788)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1789)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1789)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1790)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1791)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1792)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1792)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1794)
-   [FireEye](https://www.fireeye.com/) 的 Xiaobo Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1795)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Hui Gao 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1796)
-   Gareth Heyes 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1797)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1799)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1799)
-   0016EECD9D7159A949DAD3BC17E0A939 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1799)
-   Sweetchip 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1799)
-   SkyLined 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1800)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1802)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1803)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Royce Lu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1804)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1804)
-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-1805)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2753)
-   [Qihoo 360](https://www.360.cn/) 的 Liu Long 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2754)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Xin Ouyang 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2755)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2755)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2756)
-   0016EECD9D7159A949DAD3BC17E0A939 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2756)
-   Simon Zuckerbraun 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2757)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2758)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2759)
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sabre 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2759)
-   [Qihoo 360](https://www.360.cn/) 的 Zhibin Hu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2760)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2761)
-   0016EECD9D7159A949DAD3BC17E0A939 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2761)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2763)
-   [Qihoo 360](https://www.360.cn/) 的 Yujie Wen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2764)
-   [NSFOCUS Security Team](https://www.nsfocus.com/) 的 [Chen Zhang (demi6od)](https://weibo.com/demi6od) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2764)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2764)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2765)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2766)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2767)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2768)
-   [Trend Micro](https://www.trendmicro.com/) 的 Yuki Chen 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2768)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2769)
-   [Venustech Active-Defense Laboratory](https://www.venustech.com.cn/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2769)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Xin Ouyang 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2770)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Royce Lu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2771)
-   [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 与[HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2772)
-   [Keen Team](https://www.k33nteam.org/) 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2773)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2773)
-   [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 AbdulAziz Hariri、Matt Molinyawe 和 Jasiel Spelman 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2775)
-   [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 AbdulAziz Hariri、Matt Molinyawe 和 Jasiel Spelman 报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2776)
-   [VUPEN](https://www.vupen.com/) 与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 特权提升漏洞 (CVE-2014-2777)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2014-2782)
-   [Cyber Defense Institute, Inc.](https://www.cyberdefense.jp/) 的 Noriaki Iwasaki 与我们一起努力处理了此公告中包括的纵深防御更改

     

**MS14-036**

-   [Security-Assessment.com](https://www.security-assessment.com/) 的 Scott Bell 报告了 Unicode 脚本处理器漏洞 (CVE-2014-1817)
-   [Google Security Team](https://www.google.com/) 的 Mateusz Jurczyk、Ivan Fratric 和 Ben Hawkes 报告了 GDI+ 图像分析漏洞 (CVE-2014-1818)

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

-   V1.0（2014 年 6 月 10 日）： 已发布公告摘要。
-   V1.1（2014 年 6 月 17 日）： 对于 MS14-035，针对 CVE-2014-2782 在“利用指数”中添加了利用评估。这仅仅是一个信息更改。

*页面生成时间：2014-09-18 16:14Z-07:00。*
