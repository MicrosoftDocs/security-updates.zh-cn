---
TOCTitle: 'MS08-JUL'
Title: 'Microsoft 安全公告摘要 (2008 年 7 月)'
ms:assetid: 'ms08-jul'
ms:contentKeyID: 61236917
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms08-jul(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2008 年 7 月)
=====================================

发布时间: 2008年7月8日

**版本:** 1.0

本公告摘要列出了 2008 年 7 月发布的安全公告。

对于 2008 年 7 月发布的安全公告，本公告摘要替代 2008 年 7 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2008 年 7 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 7 月份安全公告网络广播](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374629&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

重要 (4)
--------


| 公告标识符       | Microsoft 安全公告 MS08-040                                                                                                                                                                    |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft SQL Server 中的漏洞可能允许特权提升 (941203)**](http://technet.microsoft.com/security/bulletin/ms08-040)                                                                          |
| **摘要**         | 此安全更新可消除四个秘密披露的漏洞。 更加严重的漏洞可能允许攻击者执行代码并完全控制受影响的系统。 经过身份验证的攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                           |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                       |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                           |
| **受影响的软件** | **Microsoft Windows、Microsoft SQL Server.** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                |

| 公告标识符       | Microsoft 安全公告 MS08-038                                                                                                                                                                                                                                                                                                                                              |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows 资源管理器中的漏洞可能允许远程执行代码 (950582)**](http://technet.microsoft.com/security/bulletin/ms08-038)                                                                                                                                                                                                                                                   |
| **摘要**         | 此安全更新解决了 Windows 资源管理器中公开报告的漏洞，如果用户打开并保存特制的保存搜索文件，该漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                     |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                             |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                                                                                                                                                                         |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS08-037                                                                                                                                                                                        |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**DNS 中的漏洞可能允许欺骗 (953230)**](http://technet.microsoft.com/security/bulletin/ms08-037)                                                                                                                   |
| **摘要**         | 此安全更新可解决 Windows 域名系统 (DNS) 中两个秘密报告的漏洞，这些漏洞可允许欺骗。 DNS 客户端和 DNS 服务器中均存在这些漏洞，这些漏洞可能会允许远程攻击者将 Internet 上针对系统的网络通信重定向至攻击者自己的系统。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                               |
| **漏洞的影响**   | 欺骗                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新需要重新启动。                                                                                                                   |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                         |

| 公告标识符       | Microsoft 安全公告 MS08-039                                                                                                                                                                                                                    |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Outlook Web Access for Exchange Server 中的漏洞可能允许特权提升 (953747)**](http://technet.microsoft.com/security/bulletin/ms08-039)                                                                                                        |
| **摘要**         | 此安全更新可解决 Outlook Web Access (OWA) for Microsoft Exchange Server 中两个秘密报告的漏洞。 成功利用这些漏洞的攻击者可以访问单个 OWA 客户端的会话数据，允许特权提升。 在单个客户端的 OWA 会话中，攻击者随后可以执行用户能够执行的任何操作。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                           |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                                                                       |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 该更新可能要求重新启动。                                                                                                                                           |
| **受影响的软件** | **Microsoft Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                     |

受影响的软件和下载位置
----------------------

**如何使用该表？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

#### Windows 操作系统

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
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](https://www.microsoft.com/download/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7)  
(KB948110)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=269c219c-9d6b-4b12-b621-c70cd07cdd22)  
（重要）  
DNS 服务器更新：  
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=332aa92f-a1ad-42a0-87d0-485d2d41335b)  
（重要）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最高严重等级**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ed989a33-7a9e-4423-93a8-b38907467cdf)  
（重要）  
没有适用的 DNS 服务器更新
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a2b016fa-b108-4e8e-b41b-4ca89002907b)  
（重要）  
没有适用的 DNS 服务器更新
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告最高严重等级**
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](https://www.microsoft.com/download/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7)  
(KB948110)  
（重要）  
[Windows Internal Database (WYukon) Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)  
(KB948109)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4ef5033c-9843-4e0b-bfad-fcaf05d7dab9)  
（重要）  
DNS 服务器更新：  
[Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d1fcb794-e6a5-4c28-b3b3-9cd88f468a42)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](https://www.microsoft.com/download/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7)  
(KB948110)  
（重要）  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)  
(KB948109)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=66624a1f-38bf-4af7-936d-3131474ffe1f)  
（重要）  
DNS 服务器更新：  
[Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=040a1ba8-21b0-439e-bf21-1acd1c43b162)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
DNS 客户端更新：  
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=facc80da-61d6-49c5-872d-a1980b66ae3e)  
（重要）  
DNS 服务器更新：  
[Windows Server 2003 SP1（用于基于 Itanium 的系统）以及 Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c63e3ee6-6055-4313-b0f1-fec7408886bb)  
（重要）
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
Windows Vista 和 Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=06739ca6-7368-4acb-bb67-7e8146071a29)  
（重要）
</td>
<td style="border:1px solid black;">
没有适用的 DNS 客户端更新  
没有适用的 DNS 服务器更新
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=74ea0893-7c2f-4fad-ad27-588ad953b046)  
（重要）
</td>
<td style="border:1px solid black;">
没有适用的 DNS 客户端更新  
没有适用的 DNS 服务器更新
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告最高严重等级**
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
Windows Server 2008（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)\*  
(KB948109)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 32 位系统的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=189a4170-b495-4904-9cbd-209e7494d303)\*  
（重要）
</td>
<td style="border:1px solid black;">
没有适用的 DNS 客户端更新  
DNS 服务器更新：  
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=1fcea8f4-b233-42e1-b913-c4fcae276c7b)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf)\*  
(KB948109)  
（重要）
</td>
<td style="border:1px solid black;">
[用于基于 x64 的系统的 Windows Server 2008](https://www.microsoft.com/download/details.aspx?familyid=85d8701d-f8c7-4079-8a21-a3a9d5ba71ce)\*  
（重要）
</td>
<td style="border:1px solid black;">
没有适用的 DNS 客户端更新  
DNS 服务器更新：  
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=afac5bbc-71fa-457b-8b0a-f5902d37bfd0)\*  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b30ee4f0-850f-4ff3-86a4-663603a0a802)  
（重要）
</td>
<td style="border:1px solid black;">
没有适用的 DNS 客户端更新  
没有适用的 DNS 服务器更新
</td>
</tr>
</table>

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

#### Microsoft 服务器软件

<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft SQL Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-040"><strong>MS08-040</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">SQL Server 7.0 Service Pack 4</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">SQL Server 7.0 Service Pack 4</a><br />  
(KB948113)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">SQL Server 7.0 Service Pack 4</a><br />  
(KB948113)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2000 Service Pack 4</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">SQL Server 2000 Service Pack 4</a><br />  
(KB948110)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">SQL Server 2000 Service Pack 4</a><br />  
(KB948111)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2000 Itanium-based Edition Service Pack 4</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />  
(KB948110)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />  
(KB948111)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2005 Service Pack 2</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">SQL Server 2005 Service Pack 2</a><br />  
(KB948109)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">SQL Server 2005 Service Pack 2</a><br />  
(KB948108)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">SQL Server 2005 x64 Edition Service Pack</a>2<br />  
(KB948109)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">SQL Server 2005 x64 Edition Service Pack</a>2<br />  
(KB948108)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">用于基于 Itanium 的系统的 SQL Server 2005 SP2</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">用于基于 Itanium 的系统的 SQL Server 2005 SP2</a><br />  
(KB948109)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">用于基于 Itanium 的系统的 SQL Server 2005 SP2</a><br />  
(KB948108)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</a><br />  
(KB948113)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</a><br />  
(KB948113)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />  
(KB948110)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />  
(KB948111)<br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft SQL Server 2005 Express Edition Service Pack 2</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">Microsoft SQL Server 2005 Express Edition Service Pack 2</a><br />  
(KB948109)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">Microsoft SQL Server 2005 Express Edition Service Pack 2</a><br />  
(KB948108)<br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">带 Advanced Services Service Pack 2 的 Microsoft SQL Server 2005 Express Edition</td>
<td style="border:1px solid black;">GDR 更新：<br />
<a href="https://www.microsoft.com/download/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7">带 Advanced Services Service Pack 2 的 Microsoft SQL Server 2005 Express Edition</a><br />  
(KB948109)<br />  
（重要）<br />  
<br />  
QFE 更新：<br />  
<a href="https://www.microsoft.com/download/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3">带 Advanced Services Service Pack 2 的 Microsoft SQL Server 2005 Express Edition</a><br />  
(KB948108)<br />
（重要）</td>
</tr>
</tbody>
</table>


<p> </p>
<table style="border:1px solid black;">
<caption>Microsoft Exchange Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识符</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-039"><strong>MS08-039</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>公告最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=e099c1d1-5af6-4d6c-b735-9599412b3131">Microsoft Exchange Server 2003 Service Pack 2</a><br />
（重要）</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Server 2007</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=086a2a13-a1de-4b1d-bd12-b148bfd2dafa">Microsoft Exchange Server 2007</a><br />
（重要）</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2007 Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=63e7f26c-92a8-4264-882d-f96b348c96ab">Microsoft Exchange Server 2007 Service Pack 1</a><br />
（重要）</td>
</tr>
</tbody>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](http://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： 2008 年 Software Update Services 和 Windows Server Update Services 内容的更改说明。包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新。](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [IOActive](http://www.ioactive.com/) 的 Dan Kaminsky 报告了 MS08-037 中描述的问题
-   [Context Information Security](http://www.contextis.co.uk/) 的 Michael Jordan 报告了 MS08-039 中描述的两个问题。
-   一位匿名发现者报告了 MS08-040 中描述的问题。
-   一位匿名发现者报告了 MS08-040 中描述的问题。
-   [Insomnia Security](http://www.insomniasec.com/) 的 Brett Moore 与 [iDefense VCP](http://labs.idefense.com/) 合作，报告了 MS08-040 中描述的问题。
-   一位匿名发现者报告了 MS08-040 中描述的问题。

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2008 年 7 月 8 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
