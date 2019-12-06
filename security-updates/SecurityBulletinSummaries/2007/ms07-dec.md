---
TOCTitle: 'MS07-DEC'
Title: 'Microsoft 安全公告摘要 (2007 年 12 月)'
ms:assetid: 'ms07-dec'
ms:contentKeyID: 61236902
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-dec(v=Security.10)'
---



Microsoft 安全公告摘要 (2007 年 12 月)
======================================

发布时间: 2007年12月11日

**版本:** 1.0

本公告摘要列出了 2007 年 12 月发布的安全公告。

对于 2007 年 12 月发布的安全公告，本公告摘要替代 2007 年 12 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 12 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 12 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344696&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (3)
--------


| 公告标识符       | Microsoft 安全公告 MS07-064                                                                                                                                                                                                                                                                                                                                                                |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**DirectX 中的漏洞可能允许远程执行代码 (941568)**](https://technet.microsoft.com/security/bulletin/ms07-064)                                                                                                                                                                                                                                                                               |
| **摘要**         | 此严重安全更新可解决 Microsoft DirectX 中两个秘密报告的漏洞。 如果用户在 DirectX 中打开用于流式媒体的特制文件，这些漏洞可能允许执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                       |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                                                                                                                               |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动，在某些情况下除外。                                                                                                                                                                                                                                                                       |
| **受影响的软件** | **Windows、DirectX、DirectShow。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                                                                      |

| 公告标识符       | Microsoft 安全公告 MS07-068                                                                                                                                                                                                          |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows Media Format 中的漏洞可能允许远程执行代码（941569 和 944275）**](https://technet.microsoft.com/security/bulletin/ms07-068)                                                                                                 |
| **摘要**         | 此关键安全更新解决了 Windows Media Format 中秘密报告的漏洞。 如果用户在 Windows Media Format Runtime 中查看特制文件，此漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                 |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                         |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动，在某些情况下除外。                                                                                                                 |
| **受影响的软件** | **Windows、Windows Media Format Runtime。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                       |

| 公告标识符       | Microsoft 安全公告 MS07-069                                                                                                                                                                                   |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (942615)**](https://technet.microsoft.com/security/bulletin/ms07-069)                                                                                                    |
| **摘要**         | 此严重安全更新可消除四个秘密报告的漏洞。 最严重的安全影响可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                          |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                  |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                            |
| **受影响的软件** | **Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                           |

重要 (4)
--------


| 公告标识符       | Microsoft 安全公告 MS07-063                                                                                                                                          |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**SMBv2 中的漏洞可能允许远程执行代码 (942624)**](https://technet.microsoft.com/security/bulletin/ms07-063)                                                           |
| **摘要**         | 此重要安全更新解决了服务器消息块版本 2 (SMBv2) 中一个秘密报告的漏洞。 该漏洞可能允许攻击者篡改通过 SMBv2 传输的数据，从而允许在与 SMBv2 通信的域配置中远程执行代码。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                 |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                         |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                   |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                     |

| 公告标识符       | Microsoft 安全公告 MS07-065                                                                                                                                                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**消息队列中的漏洞可能允许远程执行代码 (937894)**](https://technet.microsoft.com/security/bulletin/ms07-065)                                                                                                                                                   |
| **摘要**         | 此重要安全更新可解决消息队列服务 (MSMQ) 中秘密报告的漏洞，该漏洞可能允许在 Microsoft Windows 2000 中实施远程执行代码或在 Windows XP 上实施特权提升。 攻击者必须拥有有效的登录凭据才能利用此漏洞。 攻击者可随后安装程序；查看、更改或删除数据；或者创建新帐户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                           |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                   |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                                             |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                               |

| 公告标识符       | Microsoft 安全公告 MS07-066                                                                                                                                                           |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows 内核中的漏洞可能允许特权提升 (943078)**](https://technet.microsoft.com/security/bulletin/ms07-066)                                                                          |
| **摘要**         | 此重要安全更新解决 Windows 内核中一个秘密报告的漏洞。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                  |
| **漏洞的影响**   | 特权提升                                                                                                                                                                              |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                    |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                      |

| 公告标识符       | Microsoft 安全公告 MS07-067                                                                                                                                                                                                                 |
|------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Macrovision 驱动程序中的漏洞可能允许本地特权提升 (944653)**](https://technet.microsoft.com/security/bulletin/ms07-067)                                                                                                                    |
| **摘要**         | 此重要安全更新解决了一个公开披露的漏洞。 Macrovision 驱动程序不正确地处理配置参数的方式中存在一个本地特权提升漏洞。 成功利用此漏洞的攻击者可以完全控制系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 |
| **最高严重等级** | [重要](https://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                        |
| **漏洞的影响**   | 本地特权提升                                                                                                                                                                                                                                |
| **检测**         | Microsoft Baseline Security Analyzer 可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                          |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                            |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件更新。

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
<th>
详细信息        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS07-063**](https://technet.microsoft.com/security/bulletin/ms07-063)
</td>
<td style="border:1px solid black;">
[**MS07-064**](https://technet.microsoft.com/security/bulletin/ms07-064)
</td>
<td style="border:1px solid black;">
[**MS07-065**](https://technet.microsoft.com/security/bulletin/ms07-065)
</td>
<td style="border:1px solid black;">
[**MS07-066**](https://technet.microsoft.com/security/bulletin/ms07-066)
</td>
<td style="border:1px solid black;">
[**MS07-067**](https://technet.microsoft.com/security/bulletin/ms07-067)
</td>
<td style="border:1px solid black;">
[**MS07-068**](https://technet.microsoft.com/security/bulletin/ms07-068)
</td>
<td style="border:1px solid black;">
[**MS07-069**](https://technet.microsoft.com/security/bulletin/ms07-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 操作系统
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=bda9d0b4-f7cb-4d9d-b030-043d7437734b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=09d4e6ae-5d19-4f11-bb7e-60cee8263bc8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=c7d368d0-f7bf-4946-a4a6-3e88315e5317)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=9d22a9ee-cc08-4b2d-af4e-55d326f82761)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=9787619f-1297-411e-8b9c-3ad3e6a99797)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=05a9501c-4da3-4fa1-901e-99cb262e5e36)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=5f382050-8df6-43aa-82e9-8fad5ff8ecec)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 操作系统组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 DirectX 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=06196774-5a11-4525-b53c-8cb000738949)
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
Microsoft Windows 2000 Service Pack 4 上的 DirectX 8.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=ccb872bd-fc06-4a3f-ac70-3c9a42d57b37)
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
Microsoft Windows 2000 Service Pack 4 上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=03b14ce0-5189-4803-8151-6ac5cb6a9179)
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
Windows XP Service Pack 2 上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=04a8f8d3-69f9-4445-baab-f45616a6b9b7)
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
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=f096c500-e765-4e75-8443-7ffec4ddf149)
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
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=d80a295a-baf9-4981-8a28-1b4207ecc5f7)
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
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=378086ea-60b8-409f-970a-fcfd62025150)
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
Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）上的 DirectX 9.0c
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=2e6ea4bb-9f4f-46fb-9d51-e20b15e61a89)
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
Windows Vista 上的 DirectX 10.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=bfa571bc-e43f-45e3-bc98-4086985c99aa)
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
Windows Vista x64 Edition 上的 DirectX 10.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=3d8803da-108b-4b9d-a039-84932dce8e42)
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
Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 5.01 Service Pack 4
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=b3bd16ea-5d69-4ae3-84b3-ab773052ceeb)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=bc8edf05-262a-4d1d-b196-4fc1a844970c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 的 Internet Explorer 6
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=6e4ebafc-34c3-4dc7-b712-152c611d3f0a)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=f5a5af23-30fb-4e47-94bd-3b05b55c92f2)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 6
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=bf466060-a585-4c2e-a48d-70e080c3bbe7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=074697f2-18c8-4521-bbf7-1d0e7395d27d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 6
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=b3f390a6-0361-4553-b627-5e7ad6bf5055)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows XP Service Pack 2 的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=b15a6506-02dd-43c2-aef4-e10c1c76ee97)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=c092a6bb-8e62-4d90-bdb1-5f3a15968f75)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=34759c10-16a5-42a2-974d-9d532fb5a0a7)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=7dccce5a-7562-448b-a345-cf1cc758e35c)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=8414f3fb-216a-4d46-b590-4c1f304dff91)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista 中的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=26d303da-bb2e-4555-96f1-becb0e277341)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition 中的 Internet Explorer 7
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
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=c5e88e0b-a4c2-4690-91d9-326800030a16)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Windows Media Format Runtime 7.1 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Windows Media Format Runtime 9 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=https://www.microsoft.com/download/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 9 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=81f20b45-dfc7-4ddf-a4b4-6c0e9476ed51)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=8fea7da8-a7f3-4786-97c2-fb5ea7018159)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 x64 Edition (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 9.5 x64 Edition (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=72d2ca0e-da81-45ee-9321-4970b80f4a5a)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 Windows Media Format Runtime 11 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 上的 Windows Media Format Runtime 11 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=1037b224-ac89-4efd-b189-6f3da77a88e6)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista 上的 Windows Media Format Runtime 11 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=9a98ef96-bc2e-42b7-9a24-c82c8fb379db)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition 上的 Windows Media Format Runtime 11 (KB941569)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=3ce02c95-d695-4f14-9fb3-30c83a9cfb9c)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 上的 Windows Media Services 9.1 (KB944275)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=096711d4-ce01-45d0-9c2d-ebfa5c671b9f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Windows Media Services 9.1 x64 Edition (KB944275)
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
[严重](https://www.microsoft.com/download/details.aspx?familyid=23c23800-5aaa-455b-96bf-4ead4dfdd95d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此操作系统有一个可用的安全更新。 有关详细信息，请参阅本表中的受影响的软件或组件和相应的安全公告。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS) 和扩展安全更新清单工具 (ESUIT)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](https://support.microsoft.com/kb/910723)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加新的安全更新，也不会再发行新版本的“企业扫描工具”。 这不影响 SMS 2.0 和 SMS 2003 的安全更新清单工具 (SUIT) 或扩展安全更新清单工具 (ESUIT)。有关详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](https://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

在本月：

-   Microsoft 在 Microsoft Update (MU) 和 Windows Server Update Services (WSUS) 上发布了四个**非安全**、高优先级更新和 2007 Microsoft Office Service Pack 1。
-   Microsoft 在 Windows Update (WU) 和 WSUS 上针对 Windows 和 Windows SharePoint Services 3.0 Service Pack 1 发布了四个**非安全**高优先级更新。

注意，此信息**仅**适用于 Microsoft Update、Windows Update 和 Windows Server Update Services 上在发布安全公告摘要当天发布的**非安全**、高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安全修补程序管理指南](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Jun Mao 与我们合作处理了 MS07-064 中描述的问题
-   [NGSSoftware](https://www.ngssoftware.com/) 的 Peter Winter Smith 与我们合作处理了 MS07-064 中描述的问题
-   [AhnLab](https://global.ahnlab.com/) 的 Jung-hyung Lee 与我们合作处理了 MS07-064 中描述的对 DirectX 的纵深防御更改
-   [Zero Day Initiative](https://www.zerodayinitiative.com/) 与我们合作处理了 MS07-065 中描述的问题
-   [ADLABS](https://www.venustech.com.cn/) 与我们合作处理了 MS07-065 中描述的问题
-   [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 报告了 MS07-066 中描述的问题。
-   [ISS X-Force](https://xforce.iss.net/) 的 Ryan Smith 与我们合作处理了 MS07-068 中描述的问题
-   Peter Vreugdenhil 与 [iDefense VCP](https://idefense.com/) 合作报告了 MS07-069 中描述的问题
-   一名匿名研究员与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS07-069 中描述的问题
-   Sam Thomas 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS07-069 中描述的问题
-   Peter Vreugdenhil 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS07-069 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](https://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 12 月 11 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
