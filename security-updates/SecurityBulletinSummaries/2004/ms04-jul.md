---
TOCTitle: 'MS04-JUL'
Title: 'Microsoft 安全公告摘要 (2004 年 7 月)'
ms:assetid: 'ms04-jul'
ms:contentKeyID: 61236804
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms04-jul(v=Security.10)'
---



Microsoft 安全公告摘要 (2004 年 7 月)
=====================================

发布时间: 2004年7月13日 | 更新时间: 2004年7月30日

**版本:** 2.0

**发布日期：**2004 年 7 月 13 日
**更新日期：**2004 年 7 月 30 日
**版本号：**2.0

可通过访问以下 [Web 站点](http://www.microsoft.com/china/security/default.asp)，获取此信息的最终用户版本。

**保护您的 PC：**Microsoft 在以下位置中提供了关于您如何帮助保护 PC 的信息：

-   最终用户可以访问[保护您的 PC Web 站点](http://www.microsoft.com/china/security/protect/)。
-   IT 专业人士可以访问[安全指南中心](http://www.microsoft.com/china/security/guidance/default.mspx) Web 站点。

**更新管理策略：**[修补程序管理、安全更新和下载](http://www.microsoft.com/china/technet/security/topics/patch/default.mspx) Web 站点提供了 Microsoft 有关应用安全更新的最佳做法建议的详细信息。

**IT 专业人士安全区域社区：**了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人士安全区域 Web 站点](http://go.microsoft.com/fwlink/?linkid=21164)与其他 IT 专业人士一起就安全话题展开讨论。

**Microsoft 安全性通告服务：**要在发布 Microsoft 安全公告时收到自动电子邮件通知，请订阅 [Microsoft 安全性通告服务](http://www.microsoft.com/china/security/bulletins/notify.asp)。

#### 摘要

本通报中包含新发现漏洞的更新。可按严重程度将这些漏洞分为：

严重 (3)
--------

| 公告标识           | Microsoft 安全公告 MS04-025                                                                                |
|--------------------|------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**Internet Explorer 的累积性安全更新 (867801)**](http://technet.microsoft.com/security/bulletin/ms04-025) |
| **摘要**           | 存在于Internet Explorer 中的三个远程执行代码漏洞。                                                         |
| **最高严重等级**   | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                       |
| **安全漏洞的影响** | 远程执行代码                                                                                               |
| **受影响的软件**   | **Windows, Internet Explorer.** 。                                                                         |

| 公告标识           | Microsoft 安全公告 MS04-022                                                                                  |
|--------------------|--------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**任务计划程序中的漏洞可能允许执行代码 (841873)**](http://technet.microsoft.com/security/bulletin/ms04-022) |
| **摘要**           | 任务计划程序由于其进行应用程序名称验证的方式而存在一个远程执行代码漏洞。                                     |
| **最高严重等级**   | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                         |
| **安全漏洞的影响** | 远程执行代码                                                                                                 |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                                              |

| 公告标识           | Microsoft 安全公告 MS04-023                                                                               |
|--------------------|-----------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**HTML 帮助中的漏洞可能允许执行代码 (840315)**](http://technet.microsoft.com/security/bulletin/ms04-023) |
| **摘要**           | 在对特制 showHelp URL 的处理方式中存在一个远程执行代码漏洞。                                              |
| **最高严重等级**   | [严重](http://go.microsoft.com/fwlink/?linkid=21140)                                                      |
| **安全漏洞的影响** | 远程执行代码                                                                                              |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                                           |

重要 (4)
--------

| 公告标识           | Microsoft 安全公告 MS04-019                                                                                  |
|--------------------|--------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**工具管理器中的漏洞可能允许执行代码 (842526)**](http://technet.microsoft.com/security/bulletin/ms04-019)   |
| **摘要**           | 在工具管理器启动应用程序的方式中存在一个权限提升漏洞。已登录的用户可以强制工具管理器以系统权限启动应用程序。 |
| **最高严重等级**   | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                         |
| **安全漏洞的影响** | 本地权限提升                                                                                                 |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                                              |

| 公告标识           | Microsoft 安全公告 MS04-020                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**POSIX 中的漏洞可能允许执行代码 (841872)**](http://technet.microsoft.com/security/bulletin/ms04-020) |
| **摘要**           | POSIX 子系统中存在的权限提升漏洞可能允许登录用户完全控制系统。                                         |
| **最高严重等级**   | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                   |
| **安全漏洞的影响** | 本地权限提升                                                                                           |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                                        |

| 公告标识           | Microsoft 安全公告 MS04-021                                                              |
|--------------------|------------------------------------------------------------------------------------------|
| **公告标题**       | [**IIS 4.0 安全更新 (841373)**](http://technet.microsoft.com/security/bulletin/ms04-021) |
| **摘要**           | Internet Information Server 4.0 中存在一个缓冲区溢出漏洞。                               |
| **最高严重等级**   | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                     |
| **安全漏洞的影响** | 远程执行代码                                                                             |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                          |

| 公告标识           | Microsoft 安全公告 MS04-024                                                                                        |
|--------------------|--------------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**Windows Shell 中的漏洞可能允许远程执行代码 (839645)**](http://technet.microsoft.com/security/bulletin/ms04-024) |
| **摘要**           | 在 Windows Shell 启动应用程序的方式中存在一个远程执行代码漏洞。要利用此漏洞，需要进行用户交互。                    |
| **最高严重等级**   | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                               |
| **安全漏洞的影响** | 远程执行代码                                                                                                       |
| **受影响的软件**   | **Windows**。有关详细信息，请参见“受影响的软件和下载位置”部分。                                                    |

中等 (1)
--------

| 公告标识           | Microsoft 安全公告 MS04-018                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**Outlook Express 的累积性安全更新 (823353)**](http://technet.microsoft.com/security/bulletin/ms04-018) |
| **摘要**           | 存在的拒绝服务漏洞可能允许攻击者发送特制电子邮件，从而导致 Outlook Express 出现故障。                    |
| **最高严重等级**   | [中等](http://go.microsoft.com/fwlink/?linkid=21140)                                                     |
| **安全漏洞的影响** | 拒绝服务                                                                                                 |
| **受影响的软件**   | **Windows、Outlook Express**。有关详细信息，请参见“受影响的软件和下载位置”部分。                         |

受影响的软件和下载位置
----------------------

**我如何使用该表呢？**

可使用该表了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否有必须安装的安全更新。如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件更新。

在该表中，方括号 \[x\] 中的数字表示有一个详细解释该问题的说明。这些说明位于该表的底部。

**注意：**您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

**受影响的软件和下载位置**

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>详细资料</th>
<th>详细资料</th>
<th>详细资料     </th>
<th>详细资料</th>
<th>详细资料</th>
<th>详细资料</th>
<th>详细资料</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-018"><strong>MS04-018</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-019"><strong>MS04-019</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-020"><strong>MS04-020</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-021"><strong>MS04-021</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-022"><strong>MS04-022</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-023"><strong>MS04-023</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms04-024"><strong>MS04-024</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>中等</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>严重</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>受影响的 Windows 软件：</strong></p></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows Server™ 2003</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=8b53c35d-e9ed-46ad-936c-30c8e3a7e606">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=41c7bb26-3500-4492-a447-33440c404e4f">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 64-Bit Edition</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=df0c5c4e-d986-4ad5-95e0-e87106d7c019&amp;displaylang=en">严重 [英文]</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=79cca663-5b72-4345-a3ee-404b466731bc&amp;displaylang=en">重要 [英文]</a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows XP</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=8e8d0a2d-d3b9-4de8-8b6f-fc27715bc0cf">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=8b412c7f-44ad-4e77-8973-fd3e84cc496a">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=c3365b8e-666b-4c82-a9ed-fc0f84f107ba">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 1</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=8e8d0a2d-d3b9-4de8-8b6f-fc27715bc0cf">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=8b412c7f-44ad-4e77-8973-fd3e84cc496a">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=c3365b8e-666b-4c82-a9ed-fc0f84f107ba">重要</a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows XP 64-Bit Edition Service Pack 1</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=7b4ac0fa-7954-4993-85a1-85298f122ce0&amp;displaylang=en">严重 [英语]</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=0042db67-c58b-412c-a24f-9d2aa8071897&amp;displaylang=en">严重 [英语]</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=3fee07f5-9e31-481e-9f89-2549f51147af&amp;displaylang=en">重要 [英语]</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows XP 64-Bit Edition Version 2003</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=df0c5c4e-d986-4ad5-95e0-e87106d7c019&amp;displaylang=en">严重 [英语]</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=79cca663-5b72-4345-a3ee-404b466731bc&amp;displaylang=en">重要 [英语]</a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 2</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=94cd9925-d99b-4cb6-b51e-248d4fd8af07">重要</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=05203a7e-4a11-4f88-aa73-75a6c81466b8">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=bbf3c8a1-7d72-4ce9-a586-7c837b499c08">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=3f2f1a7d-5cf2-4791-a7ee-07f20f75796c">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=397be12b-a026-41a6-8e98-b4027bc6a110">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Service Pack 3</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=94cd9925-d99b-4cb6-b51e-248d4fd8af07">重要</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=05203a7e-4a11-4f88-aa73-75a6c81466b8">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=bbf3c8a1-7d72-4ce9-a586-7c837b499c08">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=3f2f1a7d-5cf2-4791-a7ee-07f20f75796c">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=397be12b-a026-41a6-8e98-b4027bc6a110">重要</a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=94cd9925-d99b-4cb6-b51e-248d4fd8af07">重要</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=05203a7e-4a11-4f88-aa73-75a6c81466b8">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=bbf3c8a1-7d72-4ce9-a586-7c837b499c08">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=3f2f1a7d-5cf2-4791-a7ee-07f20f75796c">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=397be12b-a026-41a6-8e98-b4027bc6a110">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows NT® Workstation 4.0 Service Pack 6a</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=25993f70-191b-4e35-aa1b-0aa1a7027880">重要</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=3a2b38c5-fa73-49ec-9eef-06fe8d6495c0">重要</a></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=18d026d3-3d93-4845-94ad-4f2656500d7a">严重</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=53f0c9c1-d72f-48e8-8f70-b29a70a618e2">重要</a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows NT Server 4.0 Service Pack 6a</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=c2018a81-446c-4930-a6cc-ea5b5960ff05">重要</a></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=3a2b38c5-fa73-49ec-9eef-06fe8d6495c0">重要</a></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=58906e66-064c-4358-9bf9-bc67b1f57bc5">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows NT Workstation 4.0 Service Pack 6a 和 Windows NT Server 4.0 Service Pack 6a with Active Desktop</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=87096271-9716-4a46-93f3-d41fcbdf989a">重要</a><strong>[5]</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows NT Server 4.0 Terminal Server Edition Service Pack 6</td>
<td style="border:1px solid black;"><strong>[3]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=9cfc4af3-b0bc-4798-bc23-f45739e3b802&amp;displaylang=en">重要 [英语]</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=34035ce3-1998-4693-8330-c4515a13407d&amp;displaylang=en">重要 [英语]</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows Millennium Edition (Me)</td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=a71faa02-d34c-47cb-bc99-820013211463">严重</a></td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows 98 Second Edition (SE)</td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=a71faa02-d34c-47cb-bc99-820013211463">严重</a></td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=a71faa02-d34c-47cb-bc99-820013211463">严重</a></td>
<td style="border:1px solid black;"><strong>[2]</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><strong>受影响的 Windows 操作系统组件：</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Outlook Express 5.5 Service Pack 2</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=9a8d1bf2-93c5-41a9-b79a-31d54743ba0e">无</a><strong>[4]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Outlook Express 6</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=d5900df1-10ab-4850-9064-3070ce1f948a">中等</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Outlook Express 6 Service Pack 1</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=ad6a96bc-daf0-4eab-89b8-bd702b3e3e5d">无</a><strong>[4]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Outlook Express 6 Service Pack 1（64 位版本）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=adccf304-6cfc-48d6-9a3f-2a601c3a04a5&amp;displaylang=en">无 [英文]</a><strong>[4]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">安装在 Windows Server 2003 上的 Outlook Express 6</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=c99aafcd-b99b-4b13-a366-5f8edc83633f">无</a><strong>[4]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">安装在 Windows Server 2003 上的 Microsoft Outlook Express 6（64 位版本）</td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?familyid=10d1aad0-0313-4beb-a174-84cf573f31fd&amp;displaylang=en">无 [英文]</a><strong>[4]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Internet Explorer 6 Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://www.microsoft.com/download/details.aspx?displaylang=zh-cn&amp;familyid=d4f57f82-d2ba-411a-8b40-77a3d80e58ac">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>  
</tbody>  
</table>
  
**MS04-025：**请立刻访问 [**Internet Explorer 的累积性安全更新 (867801)**](http://technet.microsoft.com/security/bulletin/ms04-025)查看受影响软件并下载更新。
  
**注意：**
  
**<sup>[1]</sup>** 默认情况下，此操作系统不会受到该问题的影响。但是，如果安装了其他软件程序或组件，此操作系统可能会容易受到攻击。具体来说，在这种情况下，如果安装了 Internet Explorer 6 Service Pack 1，Windows NT4 就容易受到攻击。有关更详细信息，请参见相应的安全公告。
  
**<sup>[2]</sup>** 此操作系统会受到该问题的影响。但是，操作系统不会受到严重影响。通常，在此操作系统上不会提供不严重问题的安全更新。有关针对此操作系统的 Microsoft 技术支持生命周期策略的详细信息，请访问以下 [Web 站点](http://support.microsoft.com/default.aspx?pr=lifean1)。有关更详细信息，请参见相应的安全公告。
  
**<sup>[3]</sup>** 此操作系统有一个安全更新。有关更详细信息，请参见本表中的受影响组件 Microsoft Outlook Express 和相应的安全公告。
  
**<sup>[4]</sup>** 随本公告提供的安全更新并没有消除此版本 Outlook Express 的任何漏洞，但是，它更改了 Outlook Express 5.5 Service Pack 2 的默认安全设置以增加限制，并且消除了用于 Outlook Express 6 SP1 和更高版本的 MS04-013 中出现的一种现象，即在预定位置创建一个 Windows 通讯簿副本，其文件名为“~”。
  
**<sup>[5]</sup>** 有关如何确定是否安装了 Active Desktop 的步骤，请参见公告。
  
部署  
----
  
  
**软件更新服务：**
  
通过使用 Microsoft 软件更新服务 (SUS)，管理员可以在基于 Windows 2000 和 Windows Server 2003 的服务器以及运行 Windows 2000 Professional 或 Windows XP Professional 的台式机系统上快速而可靠地部署最新的重要更新和安全更新。
  
有关如何使用软件更新服务部署此安全更新的详细信息，请访问[软件更新服务 Web 站点](http://go.microsoft.com/fwlink/?linkid=21133)。
  
**Systems Management Server：**
  
Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新且基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而只对最终用户造成最低程度的干扰。SMS 2.0 用户还可以使用[软件更新服务功能包](http://www.microsoft.com/china/smserver/downloads/20/default.asp)帮助部署安全更新。有关 SMS 的信息，请访问 [SMS Web 站点](http://www.microsoft.com/china/smserver/default.asp)。
  
**注意：**SMS 使用 Microsoft 基准安全分析器和 Microsoft Office 检测工具，提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 **SMS 2003 管理功能包**和 SMS 2.0 管理功能包中提供）来安装这些更新。
  
**QChain.exe 和 Update.exe：**
  
Microsoft 已发布了一个名为 QChain.exe 的命令行工具，系统管理员可使用它将安全更新安全地链接在一起。“链接”是指您在安装多个更新时，在两个安装之间不需要重新启动。此通报中描述的更新所使用 Update.exe 内置了链接功能。使用 Windows 2000 Service Pack 2 或更高版本、Windows XP 或 Windows Server 2003 的用户不需要使用 Qchain.exe 来链接这些更新。Qchain.exe 仍支持将这些 Windows 更新链接在一起，以使管理员在所有平台上创建一致的部署脚本。有关 Qchain 的详细信息，请访问此 [Web 站点](http://go.microsoft.com/fwlink/?linkid=21156)。
  
**Microsoft 基准安全分析器：**
  
管理员可使用 Microsoft 基准安全分析器 (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问Microsoft 基准安全分析器 Web 站点。
  
#### 其他信息：
  
**鸣谢**
  
Microsoft 感谢下列人员或组织与我们一起致力于保护用户的利益：
  
-   [Application Security Inc.](http://www.appsecinc.com/) 的 Cesar Cerrudo 报告了 [MS04-019](http://technet.microsoft.com/security/bulletin/ms04-019) 中描述的问题。  
-   与 [Network Associates](http://www.nai.com/) 一起工作的 Rafal Wojtczuk 报告了 [MS04-020](http://technet.microsoft.com/security/bulletin/ms04-020) 中描述的问题。  
-   [Security-Assessment.com](http://www.security-assessment.com/) 的 Brett Moore 报告了 [MS04-022](http://technet.microsoft.com/security/bulletin/ms04-022) 中描述的问题。  
-   [Dustin Schneider](https://technet.microsoft.com/zh-CN/mailto://dschn@verizon.net) 报告了 [MS04-022](http://technet.microsoft.com/security/bulletin/ms04-022) 中描述的问题。  
-   [Next Generation Security Software Ltd.](http://www.ngssoftware.com/) 的 Peter Winter-Smith 报告了 [MS04-022](http://technet.microsoft.com/security/bulletin/ms04-022) 中描述的问题。  
-   Security-Assessment.com 的 Brett Moore 报告了 [MS04-023](http://technet.microsoft.com/security/bulletin/ms04-023) 中描述的问题。  
-   **获取其他安全更新：**
  
    可从以下位置获得针对其他安全问题的更新：
  
    -   [Microsoft 下载中心](http://www.microsoft.com/china/msdownload/default.asp)上提供了安全更新。通过搜索关键字“安全修补程序”，可以非常方便地找到这些更新。  
    -   可从 [Windows Update Web 站点](http://v4.windowsupdate.microsoft.com/zhcn/default.asp)获得有关用户平台的更新。
  
    **支持：**
  
    -   美国和加拿大的用户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。与安全更新有关的电话支持服务是免费的。  
    -   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 取得联系方面的详细信息，请访问[国际支持 Web 站点](http://go.microsoft.com/fwlink/?linkid=21155)。
  
    **安全性资源：**
  
    -   [Microsoft TechNet 安全性](http://www.microsoft.com/china/technet/security/default.asp)Web 站点提供了有关 Microsoft 产品安全性的详细信息。  
    -   [Microsoft 软件更新服务](http://go.microsoft.com/fwlink/?linkid=21133)  
    -   [Microsoft 基准安全分析器](http://www.microsoft.com/china/technet/security/tools/mbsahome.mspx) (MBSA)  
    -   [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)  
    -   Windows Update 目录：有关 Windows Update 目录的详细信息，请参见 Microsoft 知识库文章 [323166](http://support.microsoft.com/default.aspx?scid=kb;zh-cn;323166)。  
    -   [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)
  
    **免责声明：**
  
    Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。
  
    **修订版本：**
  
    -   V1.0（2004 年 7 月 13 日）：已发布公告  
    -   V2.0（2004 年 7 月 30 日）：新增 Microsoft 安全公告 MS04-025
  
*Built at 2014-04-18T01:50:00Z-07:00*
