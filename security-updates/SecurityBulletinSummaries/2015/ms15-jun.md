---
TOCTitle: 'MS15-JUN'
Title: 'Microsoft 安全公告摘要（2015 年 6 月）'
ms:assetid: 'ms15-jun'
ms:contentKeyID: 65883243
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-jun(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 6 月）
======================================

发布日期：2015 年 6 月 9 日

**版本：** 1.0

本公告摘要列出了 2015 年 6 月发布的安全公告。

若要了解如何在 Microsoft 安全公告发布时收到自动通知，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户指定每月安全更新程序以及与每月安全更新程序同日发布的任何与安全无关的更新程序的优先顺序。请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

若要详细了解受影响的软件，请参阅下一部分**受影响的软件**。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新程序 (3058515)</strong> <br />
此安全更新程序可修复 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么这些漏洞的最严重后果可能是允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614954">MS15-057</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Media Player 中的漏洞可能允许远程执行代码 (3033890)</strong> <br />
此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果 Windows Media Player 打开恶意网站上托管的经特殊设计的媒体内容，那么此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以完全远程控制受影响的系统。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3064949)</strong> <br />
此安全更新程序可修复 Microsoft Office 中的多个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞的最严重后果可能是允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614958">MS15-060</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 常见控件中的漏洞可能允许远程执行代码 (3059317)</strong> <br />
此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果用户单击经特殊设计的链接或指向经特殊设计的内容的链接，然后在 Internet Explorer 中调用 F12 开发人员工具，那么此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (3057839)</strong> <br />
此安全更新程序可修复 Microsoft Windows 中的多个漏洞。如果攻击者登录系统并运行特制应用程序，最严重的漏洞可能允许特权提升。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614960">MS15-062</a></p></td>
<td style="border:1px solid black;"><p><strong>Active Directory 联合身份验证服务中的漏洞可能允许特权提升 (3062577)</strong> <br />
此安全更新程序可修复 Microsoft Active Directory 联合身份验证服务 (AD FS) 中的一个漏洞。如果攻击者将经特殊设计的 URL 提交给目标站点，那么此漏洞可能允许特权提升。在特定情况下，此漏洞会导致经特殊设计的脚本没有得到正确清理，进而可能导致在查看恶意内容的用户的安全性上下文中运行攻击者提供的脚本。对于跨站点脚本攻击，此漏洞需要用户访问被侵站点，才能发生恶意行为。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614961">MS15-063</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核中的漏洞可能允许特权提升 (3063858)</strong> <br />
此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果攻击者将恶意 .dll 文件放置在计算机或网络共享上的本地目录中，那么此漏洞可能允许特权提升。攻击者随后需要等待用户运行可以加载恶意 .dll 文件的程序，以便获得特权提升。不过，在任何情况下，攻击者都无法强迫用户访问此类网络共享或网站。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 中的漏洞可能允许特权提升 (3062157)</strong><br />
此安全更新程序可修复 Microsoft Exchange Server 中的多个漏洞。如果已经过身份验证的用户单击指向经特殊设计的网页的链接，那么这些漏洞的最严重后果可能是允许特权提升。攻击者无法强迫用户访问此类网站，而是需要诱使用户单击链接，方法通常是诱使用户单击电子邮件或即时消息中的链接。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange Server</p></td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表评估了本月修复的各个漏洞的利用指数。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新程序，使用该表可以了解在安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，查看下面的每个评估，从而确定部署本月更新程序的优先顺序。若要详细了解这些等级的含义以及如何确定这些等级，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
在下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本，如本公告的“受影响的软件”和“不受影响的软件”表格中所列。
  
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
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID              </strong></p></td>
<td style="border:1px solid black;"><p><strong>最新软件版本的<br />
利用指数评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的<br />
利用指数评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务<br />
利用指数评估</strong></p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1687">CVE-2015-1687</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1730">CVE-2015-1730</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1731">CVE-2015-1731</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1732">CVE-2015-1732</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1735">CVE-2015-1735</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1736">CVE-2015-1736</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1737">CVE-2015-1737</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1739">CVE-2015-1739</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1740">CVE-2015-1740</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1741">CVE-2015-1741</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1742">CVE-2015-1742</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1743">CVE-2015-1743</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1744">CVE-2015-1744</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1745">CVE-2015-1745</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1747">CVE-2015-1747</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1748">CVE-2015-1748</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1750">CVE-2015-1750</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1751">CVE-2015-1751</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1752">CVE-2015-1752</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1753">CVE-2015-1753</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1754">CVE-2015-1754</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1755">CVE-2015-1755</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1765">CVE-2015-1765</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能被利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614953">MS15-056</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1766">CVE-2015-1766</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614954">MS15-057</a></p></td>
<td style="border:1px solid black;"><p>Windows Media Player RCE 通过 DataObject 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1728">CVE-2015-1728</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1759">CVE-2015-1759</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1760">CVE-2015-1760</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614957">MS15-059</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 未初始化内存使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1770">CVE-2015-1770</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614958">MS15-060</a></p></td>
<td style="border:1px solid black;"><p>Microsoft 常见控件释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1756">CVE-2015-1756</a></p></td>
<td style="border:1px solid black;"><p>2 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1719">CVE-2015-1719</a></p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1720">CVE-2015-1720</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Win32k 空指针取消引用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1721">CVE-2015-1721</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核位图处理释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1722">CVE-2015-1722</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 站释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1723">CVE-2015-1723</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核对象释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1724">CVE-2015-1724</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Win32k 缓冲区溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1725">CVE-2015-1725</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核画笔对象释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1726">CVE-2015-1726</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Win32k 池缓冲区溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1727">CVE-2015-1727</a></p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Win32k 内存损坏特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1768">CVE-2015-1768</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 更可能被利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614959">MS15-061</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2360">CVE-2015-2360</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测到利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测到利用情形</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614960">MS15-062</a></p></td>
<td style="border:1px solid black;"><p>ADFS XSS 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1757">CVE-2015-1757</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614961">MS15-063</a></p></td>
<td style="border:1px solid black;"><p>Windows LoadLibrary EoP 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1758">CVE-2015-1758</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></p></td>
<td style="border:1px solid black;"><p>Exchange Server 端请求伪造漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1764">CVE-2015-1764</a></p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></p></td>
<td style="border:1px solid black;"><p>Exchange 跨网站请求伪造漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1771">CVE-2015-1771</a></p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=614962">MS15-064</a></p></td>
<td style="border:1px solid black;"><p>Exchange HTML 注入漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2359">CVE-2015-2359</a></p></td>
<td style="border:1px solid black;"><p>2 - 被利用的可能性比较低</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>暂无</p></td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的顺序列出了公告。
  
通过这些表，您可以了解可能需要安装的安全更新程序。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新程序。如果列出了软件程序或组件，则也会列出软件更新程序的严重等级。
  
**注意** 您可能需要为一个漏洞安装多个安全更新程序。请查看列出的每个公告标识符所对应的一整列，根据系统上已安装的程序或组件确认必须安装的更新程序。
  
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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                 

</td>
<td style="border:1px solid black;">
**无**                                 

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                 

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
Windows Server 2003 Service Pack 2                

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
（中等）  
Internet Explorer 7  
(3058515)  
（中等）  
Internet Explorer 8  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3057839)  
（重要）  
Windows Server 2003 R2 Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
（中等）  
Internet Explorer 7  
(3058515)  
（中等）  
Internet Explorer 8  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Media Player 10  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3057839)  
（重要）  
Windows Server 2003 R2 x64 Edition Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3058515)  
（中等）  
Internet Explorer 7  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
（严重）  
Internet Explorer 8  
(3058515)  
（严重）  
Internet Explorer 9  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
（严重）  
Internet Explorer 8  
(3058515)  
（严重）  
Internet Explorer 9  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3063858)  
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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
（中等）  
Internet Explorer 8  
(3058515)  
（中等）  
Internet Explorer 9  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 2.0  
(3062577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
（中等）  
Internet Explorer 8  
(3058515)  
（中等）  
Internet Explorer 9  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 2.0  
(3062577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3063858)  
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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
（严重）  
Internet Explorer 9  
(3058515)  
（严重）  
Internet Explorer 10  
(3058515)  
（严重）  
Internet Explorer 11  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
（严重）  
Internet Explorer 9  
(3058515)  
（严重）  
Internet Explorer 10  
(3058515)  
（严重）  
Internet Explorer 11  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3063858)  
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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
（中等）  
Internet Explorer 9  
(3058515)  
（中等）  
Internet Explorer 10  
(3058515)  
（中等）  
Internet Explorer 11  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(3033890)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 2.0  
(3062577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3063858)  
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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
Active Directory 联合身份验证服务 2.1  
(3062577)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
（中等）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows RT  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows RT  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3058515)  
（严重）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

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
[**MS15-056**](https://go.microsoft.com/fwlink/?linkid=614953)

</td>
<td style="border:1px solid black;">
[**MS15-057**](https://go.microsoft.com/fwlink/?linkid=614954)

</td>
<td style="border:1px solid black;">
[**MS15-060**](https://go.microsoft.com/fwlink/?linkid=614958)

</td>
<td style="border:1px solid black;">
[**MS15-061**](https://go.microsoft.com/fwlink/?linkid=614959)

</td>
<td style="border:1px solid black;">
[**MS15-062**](https://go.microsoft.com/fwlink/?linkid=614960)

</td>
<td style="border:1px solid black;">
[**MS15-063**](https://go.microsoft.com/fwlink/?linkid=614961)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3063858)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3059317)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3057839)  
（重要）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
暂无

</td>
</tr>
</table>

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-064**](https://go.microsoft.com/fwlink/?linkid=614962)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3062157)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 8

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 8  
(3062157)  
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
[**MS15-059**](https://go.microsoft.com/fwlink/?linkid=614957)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2863812)  
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
[**MS15-059**](https://go.microsoft.com/fwlink/?linkid=614957)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2863817)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2863817)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-059**](https://go.microsoft.com/fwlink/?linkid=614957)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039749)  
（重要）  
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3039782)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3039749)  
（重要）  
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3039782)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-059**](https://go.microsoft.com/fwlink/?linkid=614957)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3039749)  
（重要）  
Microsoft Office 2013 RT Service Pack 1  
(3039782)  
（重要）

</td>
</tr>
</table>


检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新程序。

借助 Microsoft Baseline Security Analyzer (MBSA)，管理员可以扫描本地和远程系统，确认是否缺少安全更新程序和存在常见安全错误配置。

通过 Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager，管理员可以分发安全更新程序。

应用程序兼容性工具包随附的更新兼容性评估程序组件有助于简化 Windows 更新程序的测试和验证（针对已安装的应用程序）。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 认可在安全社区中通过可靠的漏洞披露渠道帮助我们保护客户的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

对于每个月的第二个星期二发布的公告，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外发布的安全公告中不提供 Microsoft Windows 恶意软件删除工具的更新版本。

### MU、WU 和 WSUS 上的与安全无关的更新程序

若要了解 Windows 更新和 Microsoft 更新上的与安全无关的更新程序，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新程序](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。显示除 Microsoft Windows 之外的其他 Microsoft 产品的所有新的、修订过的和重新发布的更新程序。

### Microsoft Active Protections Program (MAPP)

为了加强对客户的安全保护，Microsoft 在发布每月安全更新程序之前向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用此类漏洞信息通过其安全软件或设备向客户提供更新后的保护措施，例如防病毒、基于网络的入侵检测系统或基于主机的防止入侵系统。若要确定能否从安全软件供应商处获得主动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的主动保护网站。

### 安全策略和社区

**更新程序管理策略**

[管理更新程序的安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)额外介绍了 Microsoft 关于应用安全更新程序的最佳做法建议。

**获取其他安全更新程序**

可从以下位置获取修复其他安全问题的更新程序：

-   可从 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)下载安全更新程序。找到这些更新程序的最简便方法是输入关键字“安全更新程序”进行搜索。
-   可从 [Microsoft 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)下载消费者平台的更新程序。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新程序。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。若要确定软件版本的支持生命周期，请参阅 [Microsoft 支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 专业人员安全解决方案：[TechNet 安全性疑难解答与支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持：[国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。由于有些州不允许免除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 6 月 9 日）：已发布公告摘要。

*页面生成时间：2015-06-08 11:03Z-07:00。*
