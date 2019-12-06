---
TOCTitle: 'MS10-FEB'
Title: 'Microsoft 安全公告摘要 (2010 年 2 月)'
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61236942
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-feb(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 2 月)
=====================================

发布时间: 2010年2月9日

**版本:** 1.0

本公告摘要列出了 2010 年 2 月发布的安全公告。

对于 2010 年 2 月发布的安全公告，本公告摘要替代 2010 年 2 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 2 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 2 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-006">MS10-006</a></td>
<td style="border:1px solid black;"><strong>SMB 客户端中的漏洞可能允许远程执行代码 (978251)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。 如果攻击者将特制的 SMB 响应发送到客户端发起的 SMB 请求，此漏洞可能允许远程执行代码。 要利用这些漏洞，攻击者必须诱使用户建立与恶意 SMB 服务器的 SMB 连接。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-007">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Windows Shell Handler 中的漏洞可能允许远程执行代码 (975713)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 2000、Windows XP 和 Windows Server 2003 中的一个秘密报告的漏洞。Windows 的其他版本不受此安全更新的影响。 如果应用程序（如 Web 浏览器）通过 Windows Shell Handler 将特制的数据传送给 ShellExecute API 函数，此漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-008">MS10-008</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (978262)</strong><br />
<br />
此安全更新解决 Microsoft 软件的一个秘密报告的漏洞。 对于 Microsoft Windows 2000 和 Windows XP 的所有受支持版本，此安全更新的等级为“严重”；对于 Windows Vista 和 Windows 7 的所有受支持版本，此安全更新的等级为“重要”；对于 Windows Server 2003 的所有受支持版本，此安全更新的等级为“中等”；对于 Windows Server 2008 和 Windows Server 2008 R2 的所有受支持版本，此安全更新的等级为“低”。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-009">ms10-009</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP 中的漏洞可能允许远程执行代码 (974145)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中四个秘密报告的漏洞。 如果特制数据包发送至启用了 IPv6 的计算机，则最严重的漏洞可能允许远程执行代码。 攻击者可能通过创建特制的 ICMPv6 数据包并将其发送到启用了 IPv6 的系统来试图利用此漏洞。 只有攻击者处于连接中时才会利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-013">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的漏洞可能允许远程执行代码 (977935)</strong><br />
<br />
此安全更新解决 Microsoft DirectShow 中一个秘密报告的漏洞。 如果用户打开特制 AVI 文件，这两个漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-003">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office (MSO) 中的漏洞可能允许远程执行代码 (978214)</strong><br />
<br />
此安全更新解决 Microsoft Office 中秘密报告的漏洞，如果用户打开特制的 Office 文件，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-004">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office PowerPoint 中的漏洞可能允许远程执行代码 (975416)</strong><br />
<br />
此安全更新解决 Microsoft Office PowerPoint 中六个秘密报告的漏洞。 如果用户打开特制的 PowerPoint 文件，这些漏洞可能允许远程执行代码。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-010">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Windows Server 2008 Hyper-V 中的漏洞可能允许拒绝服务 (977894)</strong><br />
<br />
此安全更新解决 Windows Server 2008 Hyper-V 和 Windows Server 2008 R2 Hyper-V 中一个秘密报告的漏洞。 如果经身份验证的用户在由 Hyper-V 服务器托管的客户虚拟机上运行错误的计算机指令顺序，则该漏洞可能允许拒绝服务。 攻击者必须拥有有效的登录凭据并能本地登录客户虚拟机才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-011">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统中的漏洞可能允许特权提升 (978037)</strong><br />
<br />
此安全更新解决 Microsoft Windows 2000、Windows XP 和 Windows Server 2003 中的 Microsoft Windows 客户端/服务器运行时子系统 (CSRSS) 中的一个秘密报告的漏洞。Windows 的其他版本不受影响。 如果攻击者登录到系统，并启动设计为在攻击者注销后仍可继续运行的特制应用程序，则该漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-012">MS10-012</a></td>
<td style="border:1px solid black;"><strong>SMB 服务器中的漏洞可能允许远程执行代码 (971468)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中多个秘密报告的漏洞。 如果攻击者创建了特制的 SMB 数据包并将其发送到受影响的系统，这些漏洞中最严重的漏洞可能允许远程执行代码。 采用防火墙最佳做法和标准默认防火墙配置，有助于保护网络免受来自试图利用这些漏洞的企业防线外部的攻击。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-014">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Kerberos 中的漏洞可能允许拒绝服务 (977290)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。 如果特制票证续订请求通过受信任的非 Windows Kerberos 领域上的经身份验证的用户发送到 Windows Kerberos 域，该漏洞可能允许拒绝服务。 拒绝服务可能会一直持续到域控制器重新启动为止。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (977165)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露和一个秘密报告的漏洞。 如果攻击者登录系统并运行特制应用程序，这些漏洞可能允许特权提升。 要利用任一漏洞，攻击者必须拥有有效的登录凭据并且能够本地登录。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-005">MS10-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Paint 中的漏洞可能允许远程执行代码 (978706)</strong><br />
<br />
此安全更新解决 Microsoft Paint 中一个秘密报告的漏洞。 如果用户使用 Microsoft Paint 查看特制 JPEG 图像文件，此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                             | 漏洞标题 | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项 |  
|-----------------------------------------------------|----------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|--------------|  
| [MS10-0xx](https://go.microsoft.com/fwlink/?linkid=) | 示例     | [CVE-2010-xxxx](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-xxxx) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 示例         |  
| [MS10-0xx](https://go.microsoft.com/fwlink/?linkid=) | 示例     | [CVE-2010-xxxx](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-xxxx) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 示例         |  
| [MS10-0xx](https://go.microsoft.com/fwlink/?linkid=) | 示例     | [CVE-2010-xxxx](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-xxxx) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 示例         |
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
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
<th colspan="12" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3)  
(KB977914)  
（严重）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146)  
(KB975560)  
（严重）  
[DirectX 9.0 中的 Quartz](https://www.microsoft.com/download/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b)<sup>[1]</sup>  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=e5861705-8f49-45cb-8a92-cf052ccf4134)  
（中等）
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f6c4472e-385c-4412-bda9-c2e615e50713)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb)  
(KB977914)  
（严重）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
（严重）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
（中等）
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204)  
(KB977914)  
（严重）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=90360537-9311-45e2-8047-9a971f90c3c3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f)  
(KB977914)  
（严重）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[AVI 筛选器](https://www.microsoft.com/download/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764)  
(KB977914)  
（重要）  
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f)  
(KB975560)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
（中等）
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09e19263-18ba-495e-bcf7-719e957204a7)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47)\*\*  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fde218c3-90ab-4664-852d-25ca55835054)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10)\*\*  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7)  
（严重）
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717)  
(KB975560)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=122fc003-0651-4ad2-a5c8-a21536defad8)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b3265576-04c1-48b1-8ce9-128843c58cf5)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb)  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5)  
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
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-006**](https://technet.microsoft.com/security/bulletin/ms10-006)
</td>
<td style="border:1px solid black;">
[**MS10-007**](https://technet.microsoft.com/security/bulletin/ms10-007)
</td>
<td style="border:1px solid black;">
[**MS10-008**](https://technet.microsoft.com/security/bulletin/ms10-008)
</td>
<td style="border:1px solid black;">
[**ms10-009**](https://technet.microsoft.com/security/bulletin/ms10-009)
</td>
<td style="border:1px solid black;">
[**MS10-013**](https://technet.microsoft.com/security/bulletin/ms10-013)
</td>
<td style="border:1px solid black;">
[**MS10-010**](https://technet.microsoft.com/security/bulletin/ms10-010)
</td>
<td style="border:1px solid black;">
[**MS10-011**](https://technet.microsoft.com/security/bulletin/ms10-011)
</td>
<td style="border:1px solid black;">
[**MS10-012**](https://technet.microsoft.com/security/bulletin/ms10-012)
</td>
<td style="border:1px solid black;">
[**MS10-014**](https://technet.microsoft.com/security/bulletin/ms10-014)
</td>
<td style="border:1px solid black;">
[**MS10-015**](https://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](https://technet.microsoft.com/security/bulletin/ms10-005)
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
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cda31c54-8b81-4185-a623-64480ad4b73c)\*\*  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891)\*\*  
(KB975560)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3214b347-d901-4aac-85ce-676e4602de87)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9)\*  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=badd6cab-7738-4401-a68c-c15414388601)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
（低）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Quartz](https://www.microsoft.com/download/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68)  
(KB975560)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e)  
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
</tr>
</table>

**MS10-013 注释**

<sup>[1]</sup>DirectX 9.0 的更新也适用于 Microsoft Windows 2000 上的 DirectX 9.0a、DirectX 9.0b 和 DirectX 9.0c。

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-003**](https://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](https://technet.microsoft.com/security/bulletin/ms10-004)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-003**](https://technet.microsoft.com/security/bulletin/ms10-003)
</td>
<td style="border:1px solid black;">
[**MS10-004**](https://technet.microsoft.com/security/bulletin/ms10-004)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>  
(KB979674)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>  
(KB979674)  
（重要）
</td>
</tr>
</table>

**Microsoft Office for Mac 注释**

<sup>[1]</sup>由于 Microsoft Office 2004 for Mac 累积性服务模型，这些更新是相同的。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [Core Security Technologies](https://www.coresecurity.com/) 的 Damian Frizza 报告了 MS10-003 中描述的问题
-   [Secunia](https://secunia.com/) 的 Carsten Eiram 报告了 MS10-004 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 报告了 MS10-004 中描述的三个问题
-   SkD 与 [TippingPoint 的](https://www.tippingpoint.com/) [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，报告了 MS10-004 中描述的问题
-   [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Cody Pierce 报告了 MS10-004 中描述的问题
-   ICST-ERCIS 的 Tielei Wang（中国北京大学计算机科学技术研究所信息安全工程研究中心）与 [Secunia](https://secunia.com/) 一起报告了 MS10-005 中描述的问题
-   [stratsec](https://www.stratsec.net/) 的 Laurent Gaffié 报告了 MS10-006 中描述的两个问题
-   Brett Moore 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS10-007 中描述的问题
-   [Lostmon Lords](https://lostmon.blogspot.com/) 报告了 MS10-007 中描述的问题
-   [NGS Software](https://www.ngssoftware.com/) 的 Shaun Colley 报告了 MS10-008 中描述的问题
-   [Google 安全团队成员](https://www.google.com/) Sumit Gwalani、Drew Hintz 和 Neel Mehta 报告了 ms10-009 中描述的三个问题
-   Jan Bottorff 报告了 MS10-010 中描述的问题
-   [Hispasec](https://www.hispasec.com/) 的 Matthew 'j00ru' Jurczyk 和 Gynvael Coldwind 报告了 MS10-011 中描述的问题
-   [Codenomicon](https://www.codenomicon.com/) 的 Joshua Morin 报告了 MS10-012 中描述的问题
-   [BSI](https://www.bsi.bund.de/) 的 Florian Rienhardt 报告了 MS10-012 中描述的问题
-   Hernan Ochoa 报告了 MS10-012 中描述的问题
-   [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS10-013 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 报告了 MS10-015 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 2 月 9 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
