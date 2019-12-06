---
TOCTitle: 'MS07-JUL'
Title: 'Microsoft 安全公告摘要 (2007 年 7 月)'
ms:assetid: 'ms07-jul'
ms:contentKeyID: 61236905
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-jul(v=Security.10)'
---



Microsoft 安全公告摘要 (2007 年 7 月)
=====================================

发布时间: 2007年7月10日

**版本:** 1.0

本公告摘要列出了 2007 年 7 月发布的安全公告。

对于 2007 年 7 月发布的安全公告，本公告摘要替代 2007 年 7 月 5 日最初发布的公告预 先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全 通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 7 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播 ，以解答客户关于这些公告的疑问。 [立即注册申请收听 7 月份安全公告网络广 播](https://msevents.microsoft.com/cui/eventdetail.aspx?%20eventid=1032336844&culture=zh-cn)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高 优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (3)
--------

| 公告标识符       | Microsoft 安全公告 MS07-036                                                                                                                                                                                                                          |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Excel 中的漏洞可能允许远程执行代码 (936542)**](https://technet.microsoft.com/security/bulletin/ms07-036)                                                                                                                                 |
| **摘要**         | 除了调查过程中识别的其他安全问题之外，此重要更新还可以消除一个公开披 露的漏洞和两个秘密报告的漏洞。 如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                 |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                         |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新不需要重新启动。                                                                                                                                                               |
| **受影响的软件** | **Office、Excel**。 有关详细信息，请参 阅“受影响的软件和下载位置”部分。                                                                                                                                                                              |

| 公告标识符       | Microsoft 安全公告 MS07-039                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Active Directory 中的漏洞可能允许远程 执行代码 (926122)**](https://technet.microsoft.com/security/bulletin/ms07-039)                                                                                                                                                                                                                                                                                                     |
| **摘要**         | 此严重安全更新解决了 Windows 2000 Server 和 Windows Server 2003 上的 Active Directory 实施中的一个秘密报告的漏洞，该漏洞可能允许远程执行代码或拒绝服务情形。 尝试 利用此漏洞的攻击最有可能导致拒绝服务情况。 但是，很有可能是远程执行代码。 在 Windows Server 2003 上，攻击者必须拥有有效的登录凭据才能利用此漏洞。 成功利用此漏洞的攻击者可以完全控制受影 响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建新帐户。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                               |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新将需要重新启动。                                                                                                                                                                                                                                                                                                                                             |
| **受影响的软件** | **Windows**。 有关详细信息，请参阅“受影 响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                                                                                  |

| 公告标识符       | Microsoft 安全公告 MS07-040                                                                                                                                                                                                                                                           |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**.NET Framework 中的漏洞可能允许远程执行代码 (931212)**](https://technet.microsoft.com/security/bulletin/ms07-040)                                                                                                                                                                   |
| **摘要**         | 此更新解决了三个秘密报告的漏洞。 其中两个漏洞可能允许在安装了 .NET Framework 的客户端系统上远程执行代码，而另一个漏洞可能导致运行 ASP.NET 的 Web 服务器上出现信 息泄露。在所有远程执行代码情形中，那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权 限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                  |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                          |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新将需要重新启动。                                                                                                                                                                                                |
| **受影响的软件** | **.NET Framework**。 有关详细信息，请参 阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                              |

重要 (2)
--------


| 公告标识符       | Microsoft 安全公告 MS07-037                                                                                                                                                                                                                    |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Office Publisher 中的漏洞可能允许远 程执行代码 (936548)**](https://technet.microsoft.com/security/bulletin/ms07-037)                                                                                                               |
| **摘要**         | 此重要安全更新解决了一个公开披露的漏洞。 如果用户查看特制的 Microsoft Office Publisher 文件，此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用 户权限的用户比具有管理用户权限的用户受到的影响要小。 要利用此漏洞，需要进行用户交互。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                           |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                   |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新不需要重新启动。                                                                                                                                                         |
| **受影响的软件** | **Office、Publisher**。 有关详细信息， 请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                    |

| 公告标识符       | Microsoft 安全公告 MS07-041                                                                                                                                                                                                                                                                                                 |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Internet Information Services 中的漏 洞可能允许远程执行代码 (939373)**](https://technet.microsoft.com/security/bulletin/ms07-041)                                                                                                                                                                               |
| **摘要**         | 此重要安全更新可解决一个秘密报告的漏洞。 如果攻击者向 Windows XP Professional Service Pack 2 上 Internet Information Services (IIS) 5.1 宿主的网页发送特制的 URL 请求，则此漏洞可能允许远程执行代码。IIS 5.1 不是 Windows XP Professional Service Pack 2 默认安装的一部分。成功利用此漏洞的攻击者可以完全控制受影响的系统。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                        |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新将需要重新启动。                                                                                                                                                                                                                                      |
| **受影响的软件** | **Windows XP Professional**。 有关详细 信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                           |

中等 (1)
--------

| 公告标识符       | Microsoft 安全公告 MS07-038                                                                                                             |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Vista 防火墙中的漏洞可能允许信息泄露 (935807)**](https://technet.microsoft.com/security/bulletin/ms07-038)                    |
| **摘要**         | 此中等安全更新可消除一个秘密报告的漏洞。 此漏洞可能允许未经请求传入 的网络流量访问网络接口。 攻击者可能潜在地收集有关受影响主机的信息。 |
| **最高严重等级** | [中等](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                    |
| **漏洞的影响**   | 信息泄露                                                                                                                                |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更 新将需要重新启动。                                                  |
| **受影响的软件** | **Windows** **Vista**。 有关详细信息，请参阅“受影响 的软件和下载位置”部分。                                                             |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了 解是否需要安装任何安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用 超链接将其链接到可用的软件更新。

**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

**受影响的软件和下载位置**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
<th>
详细信息        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS07-036**](https://go.microsoft.com/fwlink/?linkid=93347)
</td>
<td style="border:1px solid black;">
[**MS07-037**](https://go.microsoft.com/fwlink/?linkid=93488)
</td>
<td style="border:1px solid black;">
[**MS07-038**](https://technet.microsoft.com/security/bulletin/ms07-038)
</td>
<td style="border:1px solid black;">
[**MS07-039**](https://technet.microsoft.com/security/bulletin/ms07-039)
</td>
<td style="border:1px solid black;">
[**MS07-040**](https://technet.microsoft.com/security/bulletin/ms07-040)
</td>
<td style="border:1px solid black;">
[**MS07-041**](https://technet.microsoft.com/security/bulletin/ms07-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
受影响的 Windows 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=fccbfe90-f838-47df-8310-352e2fb47132)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=28e84603-8159-4429-aaff-a1020531e84f)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20familyid=107902f9-be94-457f-a936-519efbd64779)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=e9b64746-6afa-4a30-833d-e058e000c821)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?%20familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
受影响的 Windows 操作系统组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB928367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=91d7afe4-069b-4ce8-976e-9a01345a8603)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB930494)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB928366)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB933854)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=2495e656-1e0a-4b83-90da-821e68067a71)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB929729)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=7eea368d-7b82-4583-8537-30351718a4e9)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB928365)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB929916)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
受影响的 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=9d93c0ce-5124-4234-ba84-3c27005e010f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Excel 2003 Viewer
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=11f42977-8828-494a-a183-d1aba827b708)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Excel 2007
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=9ab28283-0320-4527-b033-5e80ef32cd34)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Office 兼容包
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Publisher 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?%20displaylang=zh-cn&familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此操作系统有一个可用的安全更新。 有关详细 信息，请参阅本表中的受影响的软件或组件和相应的安全公告。** **

** **

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信 息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也 可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?%20linkid=21130)和 [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过搜索关键字“安全修补程序”，可 以非常方便地找到这些更新。 最后，安全更新可从 Windows Update 目录下载。 有关 Windows Update 目录的详细信息，请参阅 [Microsoft 知识库文章 323166](https://support.microsoft.com/kb/323166)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士 了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft 基准安全分析器 (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS)、扩展安全更新清单工具以及企业更新扫描工具 (EST)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](https://support.microsoft.com/kb/910723)。

**Microsoft 基准安全分析器和企业** **更新扫描工具**

管理员可使用 Microsoft 基准安全分析器 (MBSA)，在本地和远程系统中扫描缺少的安全 更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft 基准安全 分析器](https://go.microsoft.com/fwlink/?linkid=21134)。

当 MBSA 1.2.1 不支持对某特定安全更新的检测时，Microsoft 将为此特定安全更新发行 一个企业更新扫描工具 (EST) 版本。 有关 EST 的详细信息，请访问[企业更新扫描 工具](https://support.microsoft.com/default.aspx?id=894193)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用 的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加 新的安全更新，也不会再发行新版本的“企业扫描工具”。 有关详细信息，请访问 [Microsoft 基准安全 分析器](https://go.microsoft.com/fwlink/?linkid=21134)。

**Software Update Services**

通过使用 Microsoft Software Update Services (SUS)，管理员可以在基于 Windows 2000 和 Windows Server 2003 的服务器以及运行 Windows 2000 Professional 或 Windows XP Professional 的台式机系统上快速而可靠地部署最新的关键更新和安全更新。

有关如何使用 Software Update Services 部署此安全更新的详细信息，请访问 [Software Update Services](https://go.microsoft.com/fwlink/?linkid=21133)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的 企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中 以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?%20linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](https://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些 软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的 详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能 需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

注意，此工具**不**使用 Software Update Services (SUS) 分发。

#### MU、WU、WSUS 和 SUS 上的非安全、高优先级更新

在本月：

-   Microsoft 在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上发布了四个**非安全**高优先级更新。
-   Microsoft 在 Windows Update (WU) 和 Software Update Services (SUS) 上发布 了一个**非安全**高优先级 Windows 更新。

注意，此信息**仅**适用于发布安全公告摘要当天 Microsoft Update、Windows Update、Windows Server Update Services 和 Software Update Services 上发布的**非安全**高优先级更新。 并 **不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安 全修补程序管理指南](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“安全修补程序”，可以 非常方便地找到这些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [OWASP](https://www.owasp.org/) 的 Dinis Cruz 报告了 [MS07-040](https://technet.microsoft.com/security/bulletin/ms07-040) 中描述的问题。
-   [Security Assessment](https://www.smsiinc.com/) 的 Paul Craig 报告了 [MS07-040](https://go.microsoft.com/fwlink/?%20linkid=91233) 中描述的问题。
-   [Sumatra](https://www.sumatra.nl/) 的 Jeroen Frijters 报告了 [MS07-040](https://technet.microsoft.com/security/bulletin/ms07-040) 中描述的问题。
-   [Portcullis Computer Security Ltd.](https://www.portcullis-security.com/) 的 Ferruh T. Mavituna 最初报告了 [MS07- 040](https://technet.microsoft.com/security/bulletin/ms07-040) 中描述的问题。
-   [NGSSoftware](https://www.nextgenss.com/) 的 Peter Winter-Smith 报告了 [MS07-039](https://www.microsoft.com/china/technet/security/bulletin/ms07-%20039.mspx) 中描述的问题。
-   [IBM Internet Security Systems x-Force](https://xforce.iss.net/) 的 Neel Mehta 报告了 [MS07-039](https://technet.microsoft.com/security/bulletin/ms07-039) 中描述的问题。
-   [eEye](https://www.eeye.com/) 报告了 [MS07- 037](https://go.microsoft.com/fwlink/?linkid=93488) 中描述的问题。
-   [Symantec](https://www.symantec.com/) 的 Jim Hoagland 和 Ollie Whitehouse 报告了 [MS07-038](https://technet.microsoft.com/security/bulletin/ms07-038) 中描述的问题。
-   [Watchfire](https://www.watchfire.com/) 的 Jonathan Afek 和 Adi Sharabani 与 Microsoft 合作提供了有关 [MS07-041](https://technet.microsoft.com/security/bulletin/ms07-041) 中描述的问题的附加信息。

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命 周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持 生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持 服务](https://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有 关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何 明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商 不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任 ，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限 制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 7 月 10 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
