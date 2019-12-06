---
TOCTitle: 'MS17-MAR'
Title: 'Microsoft 安全公告摘要（2017 年 3 月）'
ms:assetid: 'ms17-mar'
ms:contentKeyID: 74430766
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms17-mar(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2017 年 3 月）
======================================

发布时间：2017 年 3 月 14 日 | 更新时间：2017 年 8 月 8 日

**版本：**4.0

本公告摘要列出了 2017 年 3 月发布的安全公告。

有关每当 Microsoft 安全公告发布时如何接收自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新以及与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

重要提醒：[安全更新程序指南](https://portal.msrc.microsoft.com/zh-cn/security-guidance)将替代安全公告。有关更多详细信息，请参阅我们的博客文章 [Furthering our commitment to security updates](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)（深化我们对安全更新程序的承诺）。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节**受影响的软件**。

<p> </p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级<br />
和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重启要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842208">MS17-006</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (4013073)<br />
</strong>此安全更新修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则成功利用此漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842207">MS17-007</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新 (4013071)<br />
</strong>此安全更新修复了 Microsoft Edge 中的多个漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842215">MS17-008</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Hyper-V 安全更新 (4013082)<br />
</strong>此安全更新修复了 Microsoft Windows 中的多个漏洞。如果来宾操作系统上的经身份验证的攻击者运行经特殊设计的应用程序，该应用程序可导致 Hyper-V 主机操作系统执行任意代码，则其中最严重的漏洞可能允许远程执行代码。尚未启用 Hyper-V 角色的客户不会受到影响。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=839436">MS17-009</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows PDF 库安全更新 (4010319)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果用户在线查看经特殊设计的 PDF 内容或打开经特殊设计的 PDF 文档，则该漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=843149">MS17-010</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows SMB 服务器安全更新 (4013389)<br />
</strong>此安全更新修复了 Microsoft Windows 中的多个漏洞。如果攻击者向 Microsoft 服务器消息块 1.0 (SMBv1) 服务器发送经特殊设计的消息，则其中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842211">MS17-011</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Uniscribe 安全更新 (4013076)<br />
</strong>此安全更新修复了 Windows Uniscribe 中的多个漏洞。如果用户访问经特殊设计的网站或打开经特殊设计的文档，则其中最严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842212">MS17-012</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows 安全更新 (4013078)<br />
</strong>此安全更新修复了 Microsoft Windows 中的多个漏洞。如果攻击者运行连接到 iSNS 服务器的经特殊设计的应用程序，然后向该服务器发出恶意请求，则其中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842210">MS17-013</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 图形组件安全更新 (4013075)<br />
</strong>此安全更新修复了 Microsoft Windows、Microsoft Office、Skype for Business、Microsoft Lync 和 Microsoft Silverlight 中的多个漏洞。如果用户访问经特殊设计的网站或打开经特殊设计的文档，则其中最严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Office、<br />  
Skype for Business、<br />  
Microsoft Lync、<br />
Microsoft Silverlight</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842278">MS17-014</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新 (4013241)</strong><br />
此安全更新修复了 Microsoft Office 中的多个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，则其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web 应用、<br />  
Microsoft Server 软件、<br />
Microsoft 通信平台和软件</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842279">MS17-015</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 安全更新 (4013242)<br />
</strong>此安全更新修复了 Microsoft Exchange Outlook Web Access (OWA) 中的一个漏洞。如果攻击者向易受攻击的 Exchange 服务器发送附带经特殊设计的附件的电子邮件，则该漏洞可能允许在 Exchange Server 中远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842209">MS17-016</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows IIS 安全更新 (4013074)<br />
</strong>此安全更新修复了 Microsoft Internet Information Services (IIS) 中的一个漏洞。如果用户单击由受影响的 Microsoft IIS 服务器托管的经特殊设计的 URL，则此漏洞可能允许特权提升。成功利用此漏洞的攻击者可能会在用户的浏览器中执行脚本以从 Web 会话获取信息。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842216">MS17-017</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Kernel 安全更新程序 (4013081)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果攻击者运行经特殊设计的应用程序，则漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=842217">MS17-018</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序安全更新程序 (4013083)<br />
</strong>此安全更新程序修复了 Microsoft Windows 中的漏洞。如果攻击者登录到受影响的系统并运行一个为利用这些漏洞而经特殊设计的应用程序并控制受影响的系统，漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=839438">MS17-019</a></p></td>
<td style="border:1px solid black;"><p><strong>Active Directory 联合身份验证服务安全更新(4010320)<br />
</strong>此安全更新修复了 Active Directory 联合身份验证服务 (ADFS) 中的一个漏洞。如果攻击者向 ADFS 服务器发送经特殊设计的请求，从而允许攻击者读取有关目标系统的敏感信息，则该漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=836272">MS17-020</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows DVD Maker 安全更新 (3208223)<br />
</strong>此安全更新修复了 Windows DVD Maker 中的一个信息泄漏漏洞。此漏洞可能允许攻击者获取信息，从而进一步入侵目标系统。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=839434">MS17-021</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows DirectShow 安全更新 (4010318)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果 Windows DirectShow 打开恶意网站上托管的经特殊设计的媒体内容，此漏洞可能允许信息泄漏。成功利用此漏洞的攻击者可以获取信息，从而进一步入侵目标系统。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=839435">MS17-022</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft XML Core Services 安全更新 (4010321)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果用户访问恶意网站，此漏洞可能允许信息泄漏。但是，在所有情况下，攻击者无法强制用户单击经特殊设计的链接。攻击者必须说服用户单击此链接，通常通过电子邮件或 Instant Messenger 消息的方式。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=844066">MS17-023</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新</strong>(4014329)<br />
此安全更新修复了安装在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10 和 Windows Server 2016 所有受支持版本上的 Adobe Flash Player 中的多个漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>



利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。按公告 ID（而非 CVE ID）顺序列出了漏洞。公告中仅包含严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

针对你可能需要安装的每个安全更新程序，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据你的特定配置，检查下面的每个评估，从而确定部署本月更新程序的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。

在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**漏洞标题**

</td>
<td style="border:1px solid black;">
**最新软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**旧软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用性评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-006：Internet Explorer 累积安全更新 (4013073)**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0008](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0008)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0018](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0018)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0040](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0040)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0049](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0049)

</td>
<td style="border:1px solid black;">
脚本引擎信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0059](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0130](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0130)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0149)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0154)

</td>
<td style="border:1px solid black;">
Internet Explorer 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-007：Microsoft Edge 累积安全更新 (4013071)**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0010](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0010)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0011](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0011)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0015](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0015)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0017](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0017)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0032](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0032)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器欺骗漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0034](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0034)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0035](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0035)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0065](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0065)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0066](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0066)

</td>
<td style="border:1px solid black;">
Microsoft Office 安全功能绕过漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0067](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0067)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0068](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0068)

</td>
<td style="border:1px solid black;">
Microsoft Edge 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0069](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0069)

</td>
<td style="border:1px solid black;">
Microsoft Edge 欺骗漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0070](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0070)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0071](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0071)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0094](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0094)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0131](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0131)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0132)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0133)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0134)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0135)

</td>
<td style="border:1px solid black;">
Microsoft Edge 安全功能绕过

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0136)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0137](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0137)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0138)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0140)

</td>
<td style="border:1px solid black;">
Microsoft Edge 安全功能绕过

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0141](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0141)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0150)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0151)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-008：Windows Hyper-V 安全更新 (4013082)**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0021](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0021)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0051](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0051)

</td>
<td style="border:1px solid black;">
Microsoft Hyper-V 网络交换机拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0074](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0074)

</td>
<td style="border:1px solid black;">
Hyper-V 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0075](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0075)

</td>
<td style="border:1px solid black;">
Hyper-V 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0076](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0076)

</td>
<td style="border:1px solid black;">
Hyper-V 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0095](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0095)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0096](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0096)

</td>
<td style="border:1px solid black;">
Hyper-V 信息泄露漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0097](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0097)

</td>
<td style="border:1px solid black;">
Hyper-V 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0098](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0098)

</td>
<td style="border:1px solid black;">
Hyper-V 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0099](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0099)

</td>
<td style="border:1px solid black;">
Hyper-V 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0109](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0109)

</td>
<td style="border:1px solid black;">
Hyper-V 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-009：Microsoft Windows PDF 库安全更新程序 (4010319)**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-010：Microsoft Windows SMB 服务器安全更新 (4013389)**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0143)

</td>
<td style="border:1px solid black;">
Windows SMB 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0144](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0144)

</td>
<td style="border:1px solid black;">
Windows SMB 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0145)

</td>
<td style="border:1px solid black;">
Windows SMB 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0146](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0146)

</td>
<td style="border:1px solid black;">
Windows SMB 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0147)

</td>
<td style="border:1px solid black;">
Windows SMB 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0148)

</td>
<td style="border:1px solid black;">
Windows SMB 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-011：Microsoft Uniscribe 安全更新 (4013076)**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0072](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0072)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0083](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0083)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0084](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0084)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0085](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0085)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0086](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0086)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0087](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0087)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0088](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0088)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0089](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0089)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0090)

</td>
<td style="border:1px solid black;">
Uniscribe 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0091](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0091)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0092](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0092)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0111](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0111)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0112](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0112)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0113](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0113)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0114](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0114)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0115](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0115)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0116](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0116)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0117](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0117)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0118](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0118)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0119](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0119)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0120](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0120)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0121](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0121)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0122](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0122)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0123](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0123)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0124](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0124)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0125](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0127)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0128)

</td>
<td style="border:1px solid black;">
Uniscribe 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-012：Microsoft Windows 安全更新程序 (4013078)**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0007](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0007)

</td>
<td style="border:1px solid black;">
Device Guard 安全功能绕过漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0016](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0016)

</td>
<td style="border:1px solid black;">
SMBv2/SMBv3 空取消引用拒绝服务漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0039](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0039)

</td>
<td style="border:1px solid black;">
Windows DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0057](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0057)

</td>
<td style="border:1px solid black;">
Windows DNS 查询信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0100](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0100)

</td>
<td style="border:1px solid black;">
Windows HelpPane 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0104](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0104)

</td>
<td style="border:1px solid black;">
iSNS 服务器内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-013：Microsoft 图形组件安全更新 (4013075)**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0001](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0001)

</td>
<td style="border:1px solid black;">
Windows GDI 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0005](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0005)

</td>
<td style="border:1px solid black;">
Windows GDI 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0014](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0014)

</td>
<td style="border:1px solid black;">
GDI+ 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0025](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0025)

</td>
<td style="border:1px solid black;">
Windows GDI 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0038](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0038)

</td>
<td style="border:1px solid black;">
Windows 图形组件信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0047](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0047)

</td>
<td style="border:1px solid black;">
Windows GDI 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0060](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0060)

</td>
<td style="border:1px solid black;">
GDI+ 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0061](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0061)

</td>
<td style="border:1px solid black;">
Microsoft 颜色管理信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0062](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0062)

</td>
<td style="border:1px solid black;">
GDI+ 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0063](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0063)

</td>
<td style="border:1px solid black;">
Microsoft 颜色管理信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0073](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0073)

</td>
<td style="border:1px solid black;">
Windows GDI+ 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0108](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0108)

</td>
<td style="border:1px solid black;">
Windows 图形组件远程执行代码漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-014：Microsoft Office 安全更新 (4013241)**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0006](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0006)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0019](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0019)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0020](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0020)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0027](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0027)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0029](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0029)

</td>
<td style="border:1px solid black;">
Microsoft Office 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0030](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0030)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0031](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0031)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0052](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0053](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0105](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0105)

</td>
<td style="border:1px solid black;">
Microsoft Office 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0107](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0107)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS 漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0129](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0129)

</td>
<td style="border:1px solid black;">
Microsoft Lync for Mac 证书验证漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-015：Microsoft Exchange Server 安全更新 (4013242)**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0110](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0110)

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-016：Windows IIS 安全更新 (4013074)**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0055](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0055)

</td>
<td style="border:1px solid black;">
Microsoft IIS Server XSS 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-017：Windows 内核安全更新程序 (4013081)**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0050](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0050)

</td>
<td style="border:1px solid black;">
Windows 内核特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0101](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0101)

</td>
<td style="border:1px solid black;">
Windows 特权提升漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0102](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0102)

</td>
<td style="border:1px solid black;">
Windows 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0103](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0103)

</td>
<td style="border:1px solid black;">
Windows 注册表特权提升漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-018：Windows 内核模式驱动程序的安全更新程序 (4013083)**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0024](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0024)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0026](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0026)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0056](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0056)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0078](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0078)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0079](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0079)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0080](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0080)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0081](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0081)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0082](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0082)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-019：Active Directory 联合身份验证服务安全更新 (4010320)**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0043](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0043)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory 联合身份验证服务信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
临时

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-020：Windows DVD Maker 安全更新程序 (3208223)**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0045](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0045)

</td>
<td style="border:1px solid black;">
Windows DVD Maker 跨网站请求伪造漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-021：Windows DirectShow 安全更新程序 (4010318)**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0042](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0042)

</td>
<td style="border:1px solid black;">
Windows DirectShow 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-022：Microsoft XML Core Services 安全更新程序 (4010321)**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0022](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0022)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-023：Adobe Flash Player 安全更新程序 (4014329)**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-07](https://helpx.adobe.com/cn/security/products/flash-player/apsb17-07.html)

</td>
<td style="border:1px solid black;">
有关漏洞安全性和更新优先级等级的信息，请参阅 Adobe 安全公告 [APSB17-07](https://helpx.adobe.com/cn/security/products/flash-player/apsb17-07.html)。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。

**注意** 你可能必须为单个漏洞安装多个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新程序（基于系统上已安装的程序或组件）。

### Windows 操作系统和组件（表 2-1）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
（严重）  
Microsoft Internet Messaging API  
(3218362)  
（重要）

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
Windows Vista Service Pack 2  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3217587)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4017018)  
（严重）  
Windows Vista Service Pack 2  
(4012584)  
（重要）  
Windows Vista Service Pack 2  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
（严重）  
Microsoft Internet Messaging API  
(3218362)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3211306)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3217587)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4017018)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(4012584)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
（中等）  
Microsoft Internet Messaging API  
(3218362)  
（重要）

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3217587)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012021)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4017018)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012584)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
（中等）  
Microsoft Internet Messaging API  
(3218362)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3211306)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3217587)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012021)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4017018)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012584)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3217587)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4017018)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012584)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
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
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
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
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
仅安全

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
每月汇总补丁

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
仅安全相关

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012204)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012217)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
纯安全补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
**无**

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
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4013429)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

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
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3217587)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4017018)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4012584)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3211306)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012598)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012583)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3217587)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4017018)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012584)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012497)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
纯安全补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
纯安全补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
纯安全补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（严重）

</td>
</tr>
</table>

**MS17-013 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Windows 操作系统和组件（表 2-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012497)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3205715)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3214051)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
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
Windows Vista x64 Edition Service Pack 2  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012497)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3205715)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3214051)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(4012497)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3217882)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3214051)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(4012497)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3217882)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3214051)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(4012497)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3217882)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3214051)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3216916)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
月度汇总

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
仅安全

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
每月汇总

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
仅安全相关

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
月度汇总

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015548)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015551)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
仅安全

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012606)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013198)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于 32 位系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1607（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于 32 位系统）

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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1703（用于基于 x64 的系统）

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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

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
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(4012497)  
（重要）

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
Microsoft XML Core Services 3.0  
(3216916)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012373)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4011981)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(4012497)  
（重要）

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
Microsoft XML Core Services 3.0  
(3216916)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012212)  
（重要）

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
Microsoft XML Core Services 3.0  
(4012212)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(4012215)  
（重要）

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
Microsoft XML Core Services 3.0  
(4012215)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
仅安全

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012214)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012217)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
纯安全补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012213)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
每月汇总补丁

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4012216)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2016（用于基于 x64 的系统）  
（服务器核心安装）  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(4013429)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

 

### Microsoft Office 套件和软件

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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3127945)  
（严重）  
Microsoft Office 2007 Service Pack 3  
(3141535)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3178676)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3178683)  
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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3127958)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3178688)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3178686)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3178690)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3178687)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3127958)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3178688)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3178686)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3178690)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3178687)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3172542)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3172464)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3172542)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3172464)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3172542)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3172464)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（32 位版本）  
(3178673)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3178674)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（64 位版本）  
(3178673)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3178674)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3198809)  
（重要）  
Microsoft Excel for Mac 2011  
(3212218)  
（重要）  
Microsoft Word for Mac 2011  
(3198809)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac  
（重要）  
Microsoft Excel 2016 for Mac  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3178677)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(3178682)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3178680)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178693)  
（严重）  
Microsoft Word Viewer  
(3178653)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178694)  
（重要）

</td>
</tr>
</table>

**MS17-013 和 MS17-014 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Microsoft Office Services 和 Web Apps

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services（32 位版本）  
(3178678)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services（64 位版本）  
(3178678)  
（重要）

</td>
</tr>
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3178685)  
（重要）  
Word Automation Services  
(3178684)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3172431)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3178689)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3172457)  
（重要）

</td>
</tr>
</table>

**MS17-014 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Microsoft Server 软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

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
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3172540)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(4012178)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 14

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 14  
(4012178)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

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
Microsoft Exchange Server 2016 累积更新 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 累积更新 3  
(4012178)  
（重要）

</td>
</tr>
</table>

**MS17-014 和 MS17-015 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Microsoft 通信平台和软件

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Skype for Business 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（32 位版本）  
(3178656)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016（32 位版本）  
(3178656)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（64 位版本）  
(3178656)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016（64 位版本）  
(3178656)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3172539)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)  
(3172539)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)  
(3172539)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)  
(3172539)  
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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010（32 位）  
(4010299)  
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
Microsoft Lync 2010（64 位）  
(4010299)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级安装）  
(4010300)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理级安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理级安装）  
(4010301)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(4010303)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 外接程序**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Live Meeting 2007 外接程序

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 外接程序  
(4010304)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
Microsoft Lync for Mac 2011

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Lync for Mac 2011  
(4012487)  
（重要）

</td>
</tr>
</table>

**MS17-013 和 MS17-014 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

### Microsoft 开发工具和软件

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
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
Microsoft Silverlight 5（安装在所有受支持的 Microsoft Windows 客户端版本上）

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5（安装在所有受支持的 Microsoft Windows 客户端版本上）  
(4013867)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime（安装在所有受支持的 Microsoft Windows 客户端版本上）

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime（安装在所有受支持的 Microsoft Windows 客户端版本上）  
(4013867)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5（安装在所有受支持的 Microsoft Windows 服务器版本上）

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5（安装在所有受支持的 Microsoft Windows 服务器版本上）  
(4013867)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime（安装在所有受支持的 Microsoft Windows 服务器版本上）

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 Developer Runtime（安装在所有受支持的 Microsoft Windows 服务器版本上）  
(4013867)  
（严重）

</td>
</tr>
</table>

**MS17-013 注释**

本公告涉及多个软件类别。如需了解其他受影响软件，请参阅本节中的其他表格。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新程序。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。 

鸣谢
----

Microsoft 认可在安全社区中通过可靠的漏洞披露渠道帮助我们保护客户的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt745121.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新程序之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件提供商可以使用此类漏洞信息通过其安全软件或设备（如防病毒、基于网络的入侵检测系统或基于主机的入侵防护系统）更新对客户提供的保护。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新：

-   可从 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)获取安全更新。通过对“安全更新”进行关键词搜索可以非常方便地找到这些更新。
-   [Microsoft 更新](https://go.microsoft.com/fwlink/?linkid=40747)提供了适用于消费者平台的更新程序。
-   你可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关更多信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全疑难解答和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](https://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2017 年 3 月 14 日）：公告摘要已发布。
-   V2.0（2017 年 4 月 11 日）：公告摘要经过修订以宣布以下更新：
    -   对于 MS17-013，Windows Vista 和 Windows Server 2008 更新 4017018 的发布。该更新仅替代 CVE-2017-0038 的更新 4012583，以全面修复此漏洞。Microsoft 建议运行此受影响软件的客户安装此安全更新以完全防止此公告中描述的漏洞。有关更多信息，请参阅 [Microsoft 知识库文章 4017018](https://support.microsoft.com/zh-cn/kb/4017018)。
    -   对于 MS17-014，为了仅全面修复 Office for Mac 2011 的 CVE-2017-0027，Microsoft 将发布安全更新 3212218。Microsoft 建议运行 Office for Mac 2011 的客户安装更新 3212218，以完全防止此漏洞。有关更多信息，请参阅 [Microsoft 知识库文章 3212218](https://support.microsoft.com/zh-cn/kb/3212218)。
    -   对于 MS17-021，适用于 Windows Server 2012 的 CVE-2017-0042 的安全更新现已可用。运行 Windows Server 2012 的客户应安装更新 4015548（纯安全补丁）或 4015551（每月汇总补丁），以完全防止此漏洞。运行其他 Microsoft Windows 版本的客户无需采取任何进一步操作。
-   已修订 V2.1（2017 年 4 月 14 日）CVE-2017-0022，以将利用指数更新为 0 - 检测利用情形。此仅为信息性变更。
-   V3.0（2017 年 5 月 9 日）：对于 MS17-013，Microsoft 已重新发布 Windows Server 2008 受影响版本的安全更新 4017018。此重新发布已被重新归类为安全更新。Microsoft 建议客户应安装更新 4017018 以受到 CVE-2017-0038 的充分保护。已安装此更新的客户无需采取任何进一步操作。
-   V4.0（2017 年 8 月 8 日）：对于 MS17-007，为了全面修复 CVE-2017-0071，Microsoft 已于 6 月发布了面向 Windows 10 所有版本的安全更新。现在，由于 Windows 10（用于 32 位系统）、Windows 10（用于基于 x64 的系统）、Windows 10 版本 1703（用于 32 位系统）和 Windows 10 版本 1703（用于基于 x64 的系统）也受到了此漏洞的影响，已将其添加到了“受影响的产品”表中。Microsoft 建议尚未安装 2017 年 7 月安全更新的客户安装这些安全更新，以完全防止此漏洞。

*页面生成时间：2017-08-02 12:34-07:00。*
