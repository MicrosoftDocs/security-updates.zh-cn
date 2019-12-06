---
TOCTitle: 'MS09-JUL'
Title: 'Microsoft 安全公告摘要 (2009 年 7 月)'
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61236932
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-jul(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 7 月)
=====================================

发布时间: 2009年7月14日 | 更新时间: 2010年1月12日

**版本:** 7.0

本公告摘要列出了 2009 年 7 月发布的安全公告。

对于 2009 年 7 月发布的安全公告，本公告摘要替代 2009 年 7 月 9 日最初发布的公告预先通知以及 2009 年 7 月 24 日最初发布的额外公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 在 2009 年 7 月 15 日上午 11 点（美国和加拿大太平洋时间）进行了网络广播，解答了客户关于这些定期公告的疑问。 此网络广播现在按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

对于添加到此公告摘要 (MS09-034 和 MS09-035) 的版本 2.0 的额外安全公告，Microsoft 将于 2009 年 7 月 28 日下午 1 点和下午 4 点（美国和加拿大太平洋时间）主持两次网络广播，以解决客户关于这些公告的疑问。 立即注册申请收听 [7 月 28 日下午 1 点网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us)和 [7 月 28 日下午 4 点网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us)。 然后，这些网络广播以点播方式提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Embedded OpenType 字体引擎中的漏洞可能允许远程执行代码 (961371)</strong><br />
<br />
此安全更新解决 Microsoft Windows 组件 Embedded OpenType (EOT) 字体引擎中的两个秘密报告的漏洞。 这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以远程完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的漏洞可能允许远程执行代码 (971633)</strong><br />
<br />
此安全更新可解决 Microsoft DirectShow 中一个公开披露和两个秘密报告的漏洞。 如果用户打开特制的 QuickTime 媒体文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (973346)</strong><br />
<br />
此安全更新解决了当前正被利用的一个秘密报告的漏洞。 如果用户使用实例化控件的 Internet Explorer 查看特制网页，则 Microsoft Video ActiveX 控件中的漏洞可能允许远程执行代码。 此 ActiveX 控件从不在 Internet Explorer 中实例化。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (972260)</strong><br />
<br />  
此安全更新与 Microsoft 安全公告 MS09-035 一起特别发布，描述了使用 Microsoft 活动模板库 (ATL) 的易受攻击版本开发的组件和控件中的漏洞。 作为一种纵深防御措施，对于使用 Microsoft 安全通报 (973882) 和 Microsoft 安全公告 MS09-035 中所述的 ATL 的易受攻击版本开发的组件和控件，此 Internet Explorer 安全更新帮助减轻 Internet Explorer 中的已知攻击媒介的影响。<br />  
<br />
此安全更新还解决 Internet Explorer 中的三个秘密报告的漏洞。 如果用户使用 Internet Explorer 查看特制网页，这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Virtual PC 和 Virtual Server 中的漏洞可能允许特权提升 (969856)</strong><br />
<br />
此安全更新可解决 Microsoft Virtual PC 和 Microsoft Virtual Server 中一个秘密报告的漏洞。 成功利用此漏洞的攻击者可执行任意代码，并可完全控制受影响的来宾操作系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Virtual PC 和 Virtual Server</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 2006 中的漏洞可能导致特权提升 (970953)</strong><br />
<br />
此安全更新可解决 Microsoft Internet Security and Acceleration (ISA) Server 2006 中的一个秘密报告的漏洞。如果攻击者成功模拟专为 Radius 一次性密码 (OTP) 身份验证和委派 Kerberos 受约束的委派的身份验证配置的 ISA 服务器的管理用户帐户，此漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher 中的漏洞可能允许远程执行代码 (969516)</strong><br />
<br />
此安全更新解决了 Microsoft Office Publisher 中一个秘密报告的漏洞，如果用户打开特制的 Publisher 文件，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Visual Studio 活动模板库中的漏洞可能允许远程执行代码 (969706)</strong><br />
<br />  
此安全更新解决了 Visual Studio 中包括的 Microsoft 活动模板库 (ATL) 的公共版本中多个秘密报告的漏洞。 此安全更新特别适用于组件和控件的开发人员。 使用 ATL 创建并重新分配组件和控件的开发人员应安装此公告中提供的更新，然后按照提供的指导创建不易受此安全更新中所述漏洞影响的组件和控件，并将它们分配给客户。<br />  
<br />
如果用户加载了使用 ATL 的易受攻击版本构建的组件或控件，此安全公告将讨论可能允许远程执行代码的漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                   | 公告标题                                                         | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                                   |  
|-----------------------------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|------------------------------------------------|  
| [MS09-028](https://go.microsoft.com/fwlink/?linkid=152887) | Microsoft DirectShow 中的漏洞可能允许远程执行代码 (971633)       | [CVE-2009-1537](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | **此漏洞当前正在 Internet 生态系统中被利用。** |  
| [MS09-028](https://go.microsoft.com/fwlink/?linkid=152887) | Microsoft DirectShow 中的漏洞可能允许远程执行代码 (971633)       | [CVE-2009-1538](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-028](https://go.microsoft.com/fwlink/?linkid=152887) | Microsoft DirectShow 中的漏洞可能允许远程执行代码 (971633)       | [CVE-2009-1539](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-029](https://go.microsoft.com/fwlink/?linkid=139788) | Embedded OpenType 字体引擎中的漏洞可能允许远程执行代码 (961371)  | [CVE-2009-0231](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-029](https://go.microsoft.com/fwlink/?linkid=139788) | Embedded OpenType 字体引擎中的漏洞可能允许远程执行代码 (961371)  | [CVE-2009-0232](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-030](https://go.microsoft.com/fwlink/?linkid=147424) | Microsoft Office Publisher 中的漏洞可能允许远程执行代码 (969516) | [CVE-2009-0566](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-031](https://go.microsoft.com/fwlink/?linkid=154993) | Microsoft ISA Server 2006 中的漏洞可能导致特权提升 (970953)      | [CVE-2009-1135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                         |  
| [MS09-032](https://go.microsoft.com/fwlink/?linkid=157386) | ActiveX Kill Bit 的累积性安全更新 (973346)                       | [CVE-2008-0015](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | **此漏洞当前正在 Internet 生态系统中被利用。** |  
| [MS09-033](https://go.microsoft.com/fwlink/?linkid=153891) | Virtual PC 和 Virtual Server 中的漏洞可能允许特权提升 (969856)   | [CVE-2009-1542](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 功能代码执行可能伴随不一致的漏洞利用结果。     |  
| [MS09-034](https://go.microsoft.com/fwlink/?linkid=158199) | Internet Explorer 的累积性安全更新 (972260)                      | [CVE-2009-1917](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 功能代码执行轻松可靠。                         |  
| [MS09-034](https://go.microsoft.com/fwlink/?linkid=158199) | Internet Explorer 的累积性安全更新 (972260)                      | [CVE-2009-1918](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 功能代码执行可能伴随不一致的漏洞利用结果。     |  
| [MS09-034](https://go.microsoft.com/fwlink/?linkid=158199) | Internet Explorer 的累积性安全更新 (972260)                      | [CVE-2009-1919](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 功能代码执行可能伴随不一致的漏洞利用结果。     |  
| [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) | Visual Studio 活动模板库中的漏洞可能允许远程执行代码 (969706)    | [CVE-2009-0901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 功能代码执行轻松可靠。                         |  
| [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) | Visual Studio 活动模板库中的漏洞可能允许远程执行代码 (969706)    | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 功能代码执行轻松可靠。                         |  
| [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) | Visual Studio 活动模板库中的漏洞可能允许远程执行代码 (969706)    | [CVE-2009-2495](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 不威胁代码执行的信息泄露错误。                 |
  
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
</tr>  
<tr>  
<th colspan="5" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://go.microsoft.com/fwlink/?linkid=158199)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 7.0](https://www.microsoft.com/download/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3)  
（严重）  
[DirectX 8.1](https://www.microsoft.com/download/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d)\*\*\*  
（严重）  
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72)  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://go.microsoft.com/fwlink/?linkid=158199)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://go.microsoft.com/fwlink/?linkid=158199)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af)  
（中等）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d)  
（中等）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
（严重）
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
（中等）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
（中等）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://go.microsoft.com/fwlink/?linkid=158199)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45)  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7)  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb)  
（严重）
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-029**](https://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](https://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](https://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](https://go.microsoft.com/fwlink/?linkid=158199)
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
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995)\*  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead)\*  
（中等）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae)\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0)\*  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516)\*  
（中等）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93)\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
（没有严重等级\*\*）
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 备注**

**\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS09-032 注释**

\*\*严重等级不适用于此更新，因为此公告中讨论的漏洞不影响此软件。 但是，作为针对将来可能发现的任何新媒介的纵深防御措施，Microsoft 建议使用此软件的客户应用此安全更新。

**MS09-028 注释**

\*\*\*DirectX 8.1 的更新同样适用于 DirectX 8.1b。

\*\*\*\*DirectX 9.0 的更新也适用于 DirectX 9.0a、DirectX 9.0b 和 DirectX 9.0c。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-030**](https://go.microsoft.com/fwlink/?linkid=147424)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8)  
(KB969693)  
（重要）
</td>
</tr>
</table>


#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-035**](https://go.microsoft.com/fwlink/?linkid=158131)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e)  
(KB971089)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197)  
(KB971090)  
（中等）  
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42)\*  
(KB973673)  
（中等）  
[Microsoft Visual Studio 2005 Service Pack 1 64-bit Hosted Visual C++ Tools](https://www.microsoft.com/download/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2)  
(KB973830)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](https://www.microsoft.com/download/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c)  
(KB971091)  
（中等）  
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd)\*  
(KB973674)  
（中等）  
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb)  
(KB971092)  
（中等）  
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f)\*  
(KB973675)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2)  
(KB973544)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93)  
(KB973551)  
（中等）  
[Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c)  
(KB973552)  
（中等）
</td>
</tr>
</table>

**MS09-035 注释**

\*适用于使用智能设备 ATL 的移动应用程序

\*\*安装 Windows Embedded CE 6.0 每月更新（2010 年 1 月）。 此更新程序包只能从 Microsoft 下载中心下载。

#### Microsoft 服务器和安全软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-031**](https://go.microsoft.com/fwlink/?linkid=154993)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](https://www.microsoft.com/download/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19)  
(KB970811)  
（重要）  
[Microsoft Internet Security and Acceleration Server 2006 可支持性更新](https://www.microsoft.com/download/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476)  
(KB970811)  
（重要）  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5)  
(KB971143)  
（重要）
</td>
</tr>
</table>


#### Microsoft 虚拟化软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-033**](https://go.microsoft.com/fwlink/?linkid=153891)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
（重要）  
[Microsoft Virtual PC 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
（重要）  
[Microsoft Virtual PC 2007 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft 虚拟服务器
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-033**](https://go.microsoft.com/fwlink/?linkid=153891)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
（重要）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](https://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) 中包含的[更新兼容性评估程序](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](https://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

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

-   [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 以及 [Qihoo 360 Security Center](https://www.360.cn/) 的 Zheng Wenbin、Liu Qi 和 Song Shenlei 报告了 MS09-028 中描述的一个问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS09-028 中描述的问题
-   [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Aaron Portnoy 以及与 TippingPoint 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作的一个匿名研究人员、[SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier、[Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS09-028 中描述的一个问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 报告了 MS09-029 中描述的问题
-   Thomas Garnier 报告了 MS09-029 中描述的问题
-   [Labo Skopia](https://www.laboskopia.com/) 的 Lionel d'Hauenens 与 [VeriSign iDefense Labs](https://www.idefense.com/) 合作，报告了 MS09-030 中描述的问题
-   [IBM IIS X-Force](https://www.iss.net/) 的 Ryan Smith 和 Alex Wheeler 最初报告了 MS09-032 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Julien Tinnes 和 Tavis Ormandy 报告了 MS09-033 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Peter Vreugdenhil 报告了 MS09-034 中描述的问题
-   Wushi 和 [team509](https://www.team509.com/) 的 Ling与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS09-034 中描述的问题
-   Peter Vreugdenhil 与 [Tippingpoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS09-034 中描述的问题
-   [IBM ISS X-Force](https://www.iss.net/) 的 David Dewey 报告了 MS09-035 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Ryan Smith 报告了 MS09-035 中描述的两个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 7 月 14 日）： 已发布公告摘要。
-   V1.1（2009 年 7 月 15 日）： 更新了 MS09-032 的摘要；纠正了 MS09-029 的重新启动要求；并执行了其他编辑。
-   V2.0（2009 年 7 月 28 日）： 添加了 Microsoft 安全公告 MS09-034、Internet Explorer 的累积性安全更新 (972260) 和 MS09-035 - Visual Studio 活动模板库中的漏洞可能允许远程执行代码 (969706)。 还添加了这些额外安全公告的公告网络广播链接。
-   V3.0（2009 年 8 月 4 日）： 已修订以宣布重新发布 Microsoft Windows 2000 Service Pack 4 上的 Microsoft Internet Explorer 6 Service Pack 1 的更新。已经安装 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1 的最初更新的所有客户均已受到保护。 然而，具有 Internet Explorer 6 Service Pack 1 的朝鲜语语言版本的客户可在他们的 Windows 2000 系统上重新安装 Internet Explorer 6 Service Pack 1 的更新，以获得相同保护并解决一个打印问题。 请参阅 Microsoft 安全公告 MS09-034。
-   V4.0（2009 年 8 月 11 日）： 经过修订以宣布 MS09-035 的发布。发布 MS09-035 是为了提供 Microsoft Visual Studio 2005 Service Pack 1 (KB973673)、Microsoft Visual Studio 2008 (KB973674) 和 Microsoft Visual Studio 2008 Service Pack 1 (KB973675) 的新更新，适用于使用 Visual Studio 为使用智能设备 ATL 的移动应用程序创建组件和控件的开发人员。
-   V4.1（2009 年 8 月 13 日）： 纠正了 MS09-035 的重新启动要求。
-   V5.0（2009 年 8 月 19 日）： 添加了对公告 MS09-028 的脚注以阐明 DirectX 8.1 的受影响软件。
-   V6.0（2009 年 8 月 25 日）： 经过修订以宣布重新发布 Windows XP Service Pack 2、Windows XP Service Pack 3 和 Windows XP Professional x64 Edition Service Pack 2 的日语更新。已经安装最初更新的所有客户均已受到保护。 但是，安装了 Windows XP Service Pack 2、Windows XP Service Pack 3 或 Windows XP Professional x64 Edition Service Pack 2 的客户应重新安装更新以获得相同的保护并解决打印问题。 请参阅 Microsoft 安全公告 MS09-029。
-   7.0（2010 年 1 月 12 日）： 重新发布是为了将 Windows Embedded CE 6.0 添加到 MS09-035 的受影响的软件。Windows Embedded CE 6.0 更新 (KB974616) 是一个累积性更新，只能从 Microsoft 下载中心下载。 使用 Windows Embedded CE 6.0 平台的客户应考虑应用累积性更新。

*Built at 2014-04-18T01:50:00Z-07:00*
