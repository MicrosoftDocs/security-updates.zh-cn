---
TOCTitle: 'MS07-OCT'
Title: 'Microsoft 安全公告摘要 (2007 年 10 月)'
ms:assetid: 'ms07-oct'
ms:contentKeyID: 61236910
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms07-oct(v=Security.10)'
---



Microsoft 安全公告摘要 (2007 年 10 月)
======================================

发布时间: 2007年10月9日

**版本:** 1.0

本公告摘要列出了 2007 年 10 月发布的安全公告。

对于 2007 年 10 月发布的安全公告，本公告摘要替代 2007 年 10 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2007 年 10 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 10 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344692&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何高优先级非安全更新进行优先排序。 请参阅**其他信息**部分。

### 公告信息

#### 摘要

本月的安全公告如下所示（按严重性排序）：

严重 (4)
--------

| 公告标识符       | Microsoft 安全公告 MS07-055                                                                                                                                                                                                                                                   |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Kodak 图像查看器中的漏洞可能允许远程执行代码 (923810)**](http://technet.microsoft.com/security/bulletin/ms07-055)                                                                                                                                                          |
| **摘要**         | 此严重安全更新可消除一个秘密报告的漏洞。 Kodak 图像查看器（以前称为 Wang 图像查看器）处理特制图像文件的方式中存在一个远程执行代码漏洞。 该漏洞可能允许攻击者在受影响的系统上远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                          |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                                                                  |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                                                                         |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                              |

| 公告标识符       | Microsoft 安全公告 MS07-056                                                                                                                            |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Outlook Express 和 Windows Mail 的安全更新 (941202)**](http://technet.microsoft.com/security/bulletin/ms07-056)                                     |
| **摘要**         | 此严重安全更新可解决一个秘密报告的漏洞。 该漏洞由于不正确地处理格式错误的 NNTP 响应而可能允许远程执行代码。 攻击者可以通过构建特制的网页来利用该漏洞。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                   |
| **漏洞的影响**   | 远程执行代码                                                                                                                                           |
| **检测**         | Microsoft 基准安全分析器和企业更新扫描工具可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动，在某些情况下对于 Windows Vista 除外。           |
| **受影响的软件** | **Windows、Outlook Express 和 Windows Mail。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                      |

| 公告标识符       | Microsoft 安全公告 MS07-057                                                                                                                                                                                                               |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Internet Explorer 的累积性安全更新 (939653)**](http://technet.microsoft.com/security/bulletin/ms07-057)                                                                                                                                |
| **摘要**         | 此关键安全更新可消除三个秘密报告的漏洞以及一个公开披露的漏洞。 安全影响最为严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                      |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                                              |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                                                                                                                     |
| **受影响的软件** | **Windows、Internet Explorer。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                       |

| 公告标识符       | Microsoft 安全公告 MS07-060                                                                                                                                                                                             |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Microsoft Word 中的漏洞可能允许远程执行代码 (942695)**](http://technet.microsoft.com/security/bulletin/ms07-060)                                                                                                     |
| **摘要**         | 此安全更新解决了 Microsoft Word 中一个秘密报告的漏洞，如果用户打开带有格式错误的字符串的特制 Word 文件，该漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 |
| **最高严重等级** | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                    |
| **漏洞的影响**   | 远程执行代码                                                                                                                                                                                                            |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动。                                                                                                                                   |
| **受影响的软件** | **Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                         |

重要 (2)
--------

| 公告标识符       | Microsoft 安全公告 MS07-058                                                                                                                         |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**RPC 中的漏洞可能允许拒绝服务 (933729)**](http://technet.microsoft.com/security/bulletin/ms07-058)                                                |
| **摘要**         | 此重要更新可解决一个秘密报告的漏洞。 在执行 RPC 请求身份验证时，由于与 NTLM 安全提供程序通讯失败，远程过程调用 ( RPC ) 设备里存在一个拒绝服务漏洞。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                |
| **漏洞的影响**   | 拒绝服务                                                                                                                                            |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新将需要重新启动。                                                               |
| **受影响的软件** | **Windows。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                    |

| 公告标识符       | Microsoft 安全公告 MS07-059                                                                                                                                                                                                                                                                                                 |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**     | [**Windows SharePoint Services 3.0 和 Office SharePoint Server 2007 中的漏洞可能导致 SharePoint 站点中的特权提升 (942017)**](http://technet.microsoft.com/security/bulletin/ms07-059)                                                                                                                                       |
| **摘要**         | 此安全更新解决 Microsoft Windows SharePoint Services 3.0 和 Microsoft Office SharePoint Server 2007 中的一个公开报告的漏洞。与工作站或者服务器环境中的特权提升相反，该漏洞可能允许攻击者运行可导致 SharePoint 站点中的特权提升的任意脚本。 该漏洞还可能允许攻击者运行任意脚本以修改用户的缓存，从而导致工作站上的信息泄露。 |
| **最高严重等级** | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                        |
| **漏洞的影响**   | 特权提升                                                                                                                                                                                                                                                                                                                    |
| **检测**         | Microsoft 基准安全分析器可以检测您的计算机系统是否需要此更新。 此更新不需要重新启动，在某些情况下除外。                                                                                                                                                                                                                     |
| **受影响的软件** | **Windows、Office。** 有关详细信息，请参阅“受影响的软件和下载位置”部分。                                                                                                                                                                                                                                                    |

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
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS07-055**](http://technet.microsoft.com/security/bulletin/ms07-055)
</td>
<td style="border:1px solid black;">
[**MS07-056**](http://technet.microsoft.com/security/bulletin/ms07-056)
</td>
<td style="border:1px solid black;">
[**MS07-057**](http://technet.microsoft.com/security/bulletin/ms07-057)
</td>
<td style="border:1px solid black;">
[**MS07-060**](http://technet.microsoft.com/security/bulletin/ms07-060)
</td>
<td style="border:1px solid black;">
[**MS07-058**](http://technet.microsoft.com/security/bulletin/ms07-058)
</td>
<td style="border:1px solid black;">
[**MS07-059**](http://technet.microsoft.com/security/bulletin/ms07-059)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最高严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 操作系统
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=29763117-c2dc-4746-b31e-0b27350118e6)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[低](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=6c7fb9a8-1d8d-4307-b5c6-bc6c28ee09de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=be52f740-e9c9-4228-95c0-00995213bbd0)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=1fee539c-ab86-4298-b6f4-22ce31ee7b8b)
</td>
<td style="border:1px solid black;">
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=011593a0-f37e-4578-bee1-a985639b521b)
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
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=011593a0-f37e-4578-bee1-a985639b521b)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=ceca7f8c-7b56-48fc-8c17-87ffadf25629)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=7625f5a4-2921-41ce-986d-4cc0c264135c)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 操作系统组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 上的 Outlook Express 5.5 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=5aa009c9-4edc-4f34-989b-0493549649e8)
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
Microsoft Windows 2000 Service Pack 4 上的 Outlook Express 6 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=b537115d-611c-4486-960c-08d2df450579)
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
Windows XP Service Pack 2 上的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=3ed7f466-78c7-4251-ba24-8ae71ad54e18)
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
Windows XP Professional x64 Edition Service Pack 2 上的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=6468a552-2194-4866-97d5-ff77ae205eea)
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
Windows Server 2003 Service Pack 1 或 Windows Server 2003 Service Pack 2 上的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=708926e4-f8af-4533-8747-22d6536ebd66)
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
Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 上的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=26720f5a-d7e9-44b9-9330-2e9faa4af0d9)
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
Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）上的 Outlook Express 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=a8844fbb-5b2c-41f3-80f1-dce563aa7cb7)
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
Windows Vista 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=b6ac8d93-adc3-4ec3-bad1-4990bd7d52b4)
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
Windows Vista x64 Edition 中的 Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?familyid=34aaf9dd-4d63-43e2-b631-bbf492d56a26)
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
Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 5.01 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=95827f3f-a984-4e34-a949-d16a0614121a)
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
安装在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=df3ba596-7c5b-4151-9884-6957aa884aab)
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
Windows XP Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=513a8320-6d36-4fc9-a38a-867192b55b53)
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
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=ae8a26d8-1910-4b8c-8a73-6e2fa6b5b29f)
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
用于 Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=4aefaa38-8757-4e6e-8924-57cabd1c2fc3)
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
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=88aba9dd-653b-4cdf-a513-cca32a7d7e41)
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
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 6
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=309a8f10-c7ea-4961-a969-092b0c4d7bbc)
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
用于 Windows XP Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=4ca0ac93-bf51-40fe-a1ba-cb3e0a36d8b5)
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
用于 Windows XP Professional x64 Edition 和 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=dbd284d0-2664-42a4-ad16-a0535244c81c)
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
Windows Server 2003 Service Pack 1 和 Windows Server 2003 Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=0a31c451-32f4-4551-ae45-d600f8b3b11b)
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
用于 Windows Server 2003 x64 Edition 和 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=c1915633-d181-4ca1-a4f0-7ca0f865aa72)
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
用于 Windows Server 2003 SP1（用于基于 Itanium 的系统）和 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[中等](https://www.microsoft.com/download/details.aspx?familyid=093a2250-3be3-494f-80e0-89ca7217030f)
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
Windows Vista 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=86392e8d-098c-427f-a233-699cdb9375ae)
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
Windows Vista x64 Edition 中的 Internet Explorer 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?familyid=62490e6d-0a21-4a15-90bd-63ca8f8886b6)
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
Windows Server 2003 Service Pack 1 上的 Windows SharePoint Services 3.0 (KB934525)
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
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=76fc2225-2802-46e5-a294-a842e3841877)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2 上的 Windows SharePoint Services 3.0 (KB934525)
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
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=76fc2225-2802-46e5-a294-a842e3841877)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition 上的 MWindows SharePoint Services 3.0 (KB934525)
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
[重要](https://www.microsoft.com/download/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2 上的 Windows SharePoint Services 3.0 (KB934525)
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
[重要](https://www.microsoft.com/download/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055)
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[严重](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=8b3072fb-5933-47f7-a498-13a93e268e57)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=d6b787bb-03ff-4f67-8b69-6011fb18ba75)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 (KB937832)
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
[重要](https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&familyid=aaea9695-f541-4c4c-9107-81ead5cfc8c9)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 x64 Edition (KB937832)
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
[重要](https://www.microsoft.com/download/details.aspx?familyid=1d319164-d133-4493-be27-1aeda62362c4)
</td>
</tr>
</table>

**备注**

**<sup>[1]</sup>** 此操作系统有一个可用的安全更新。 有关详细信息，请参阅本表中的受影响的软件或组件和相应的安全公告。** **

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)和 [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 已为本月的安全更新提供了检测和部署指南。 此指南还将帮助 IT 专业人士了解如何可以使用各种工具帮助部署安全更新，例如 Windows Update、Microsoft Update、Office Update、Microsoft 基准安全分析器 (MBSA)、Office 检测工具、Microsoft Systems Management Server (SMS)、扩展安全更新清单工具以及企业更新扫描工具 (EST)。 有关详细信息，请参阅 [Microsoft 知识库文章 910723](http://support.microsoft.com/kb/910723)。

**Microsoft 基准安全分析器和企业** **更新扫描工具**

管理员可使用 Microsoft 基准安全分析器 (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft 基准安全分析器](http://go.microsoft.com/fwlink/?linkid=21134)。

当 MBSA 1.2.1 不支持对某特定安全更新的检测时，Microsoft 将为此特定安全更新发行一个企业更新扫描工具 (EST) 版本。 有关 EST 的详细信息，请访问[企业更新扫描工具](http://support.microsoft.com/default.aspx?id=894193)。

**注意** 2007 年 10 月 9 日以后，MBSA 1.2.1 使用的 MSSecure.XML 文件将不再更新。 在此日期后，MBSA 1.2.1 使用的 MSSecure.XML 文件中不会再添加新的安全更新，也不会再发行新版本的“企业扫描工具”。 有关详细信息，请访问 [Microsoft 基准安全分析器](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service 功能包](http://go.microsoft.com/fwlink/?linkid=33340)帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

在本月：

-   Microsoft 已在 Microsoft Update (MU) 和 Windows Server 更新服务 (WSUS) 上发布三个**非安全**、高优先级更新。
-   Microsoft 已在 Windows Update (WU) 上发布一个**非安全**、高优先级 Windows 更新。

注意，此信息**仅**适用于 Microsoft Update、Windows Update 和 Windows Server Update Services 上在发布安全公告摘要当天发布的**非安全**、高优先级更新。 并**不**提供关于其他日期发布的**非安全**更新的信息。

#### 安全策略和社区

**更新管理策略**

[安全修补程序管理指南](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳实践建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   Cu Fang 报告了 MS07-055 中描述的问题
-   [Global 360](http://www.global360.com/products/g360_imaging/default.asp) 的 Rita Schappler 与我们合作处理 MS07-055 中描述的问题
-   [VeriSign iDefense Labs](http://www.idefense.com/) 的 Greg MacManus 报告了 MS07-056 中描述的问题
-   next.motion OHG 的 Pierre Geyer 报告了 MS07-057 中描述的问题
-   [Secunia Research](http://secunia.com/) 的 Carsten H. Eiram 报告了 MS07-057 中描述的问题
-   [Secunia Research](http://secunia.com/) 的 Jakob Balle 最初报告了 MS07-057 中描述的问题
-   [Zero Day Initiative](http://www.zerodayinitiative.com/) 报告了 MS07-058 中描述的问题
-   Information & Communication Security Technology Center 的 Liu Kun-Hao 报告了 MS07-060 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2007 年 10 月 9 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
