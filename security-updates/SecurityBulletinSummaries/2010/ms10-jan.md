---
TOCTitle: 'MS10-JAN'
Title: 'Microsoft 安全公告摘要 (2010 年 1 月)'
ms:assetid: 'ms10-jan'
ms:contentKeyID: 61236943
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-jan(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 1 月)
=====================================

发布时间: 2010年1月12日 | 更新时间: 2010年1月21日

**版本:** 2.0

本公告摘要列出了 2010 年 1 月发布的安全公告。

对于 2010 年 1 月发布的安全公告，本公告摘要替代 2010 年 1 月 20 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 1 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 1 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427677&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

对于添加到此公告摘要 (MS10-002) 的版本 2.0 的额外安全公告，Microsoft 在美国和加拿大太平洋时间 2010 年 1 月 21 日下午 1:00 进行网络广播，以解决客户关于这些公告的疑问： [立即注册申请收听 1 月 21 日下午 1:00 的网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032440627&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-001">MS10-001</a></td>
<td style="border:1px solid black;"><strong>Embedded OpenType 字体引擎中的漏洞可能允许远程执行代码 (972270)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。 如果用户在可以呈现 EOT 字体的客户端应用程序（如 Microsoft Internet Explorer、Microsoft Office PowerPoint 或 Microsoft Office Word）中查看以特制的 Embedded OpenType (EOT) 字体呈现的内容，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-002">MS10-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (978207)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中七个秘密报告的漏洞和一个公开披露的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
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
  
| 公告 ID                                                             | 漏洞标题                                                   | CVE ID                                                                           | 利用指数评估                                                                                    | 重要注意事项                                                                                                            |  
|---------------------------------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|  
| [MS10-001](https://technet.microsoft.com/security/bulletin/ms10-001) | LZCOMP 解压缩器中的 Microtype Express 压缩字体整数缺陷漏洞 | [CVE-2010-0018](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0018) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现 | 此利用指数评估适用于运行 Microsoft Windows 2000 的系统。运行 Windows XP 和更高版本的操作系统的操作系统不太可能被利用。  |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | XSS 筛选器脚本处理漏洞                                     | [CVE-2009-4047](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-4047) | 无                                                                                              | 不可能利用此漏洞执行代码。                                                                                              |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | URL 验证漏洞                                               | [CVE-2010-0027](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现   | （无）                                                                                                                  |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0244](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0244) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现   | （无）                                                                                                                  |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0245](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0245) | 无                                                                                              | 应用了 [MS09-072](https://go.microsoft.com/fwlink/?linkid=169404) 的客户受到保护，因为 MS09-072 更新中的更改阻止此漏洞。 |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0246](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0246) | 无                                                                                              | 应用了 [MS09-072](https://go.microsoft.com/fwlink/?linkid=169404) 的客户受到保护，因为 MS09-072 更新中的更改阻止此漏洞。 |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0247](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0247) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现   | （无）                                                                                                                  |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0248](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0248) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现 | （无）                                                                                                                  |  
| [MS10-002](https://technet.microsoft.com/security/bulletin/ms10-002) | 未初始化的内存损坏漏洞                                     | [CVE-2010-0249](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0249) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现   | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                          |
  
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
</tr>  
<tr>  
<th colspan="3" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=47f85cbd-282e-4c92-9809-68bba49e0a12)  
（严重）
</td>
<td style="border:1px solid black;">
[安装在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=51e99e4f-1670-4b12-a9fe-e0ccf50cdabc)  
（严重）  
[安装在 Microsoft Windows 2000 Service Pack 4 上的 Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a38aa9d0-c3fe-4d41-8805-7d5370263c1b)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=793a6b3f-7660-40be-b7d5-7b0eec55e1cd)  
（低）
</td>
<td style="border:1px solid black;">
[用于 Windows XP Service Pack 2 和 Windows XP Service Pack 3 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=207eecad-6e84-48e6-ae18-6794a3618ee0)  
（严重）  
[用于 Windows XP Service Pack 2 和 Windows XP Service Pack 3 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3510c7d8-7e8f-479e-b6f9-5745a845664d)  
（严重）  
[用于 Windows XP Service Pack 2 和 Windows XP Service Pack 3 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7c2948fb-f486-4801-bc21-bbf40d5a78c2)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31609ce9-656a-4f7d-a501-709a31ca34c3)  
（低）
</td>
<td style="border:1px solid black;">
[用于 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=eb2d8055-4d50-4f83-82b8-055c7b8f5422)  
（严重）  
[用于 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=cc5aea0b-e553-4f7f-a2cc-cba41bb87ae7)  
（严重）  
[用于 Windows XP Professional x64 Edition Service Pack 2 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=41b83fad-948b-4a9c-80ed-9c5a60bd35b4)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e1d6e338-dea9-458e-b35d-796e069d74d7)  
（低）
</td>
<td style="border:1px solid black;">
[用于 Windows Server 2003 Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=fea91227-44ad-4549-8732-497a8ceff870)  
（中等）  
[用于 Windows Server 2003 Service Pack 2 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=14726445-3ff4-463c-9fc1-c9b758079aca)  
（严重）  
[用于 Windows Server 2003 Service Pack 2 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7d480c87-2ca9-4505-a59d-a6d73d001fa5)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ddbcf231-9fde-4dc2-ad04-a01b69d1a980)  
（低）
</td>
<td style="border:1px solid black;">
[用于 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=633e63f4-605b-43c4-8a4b-2730312a1c72)  
（中等）  
[用于 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c8742230-16d8-4b2f-bd3e-8834c759856b)  
（严重）  
[用于 Windows Server 2003 x64 Edition Service Pack 2 的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3e2e740b-8417-4758-8468-15221249ec71)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=c71a13cf-7e2f-4b02-8684-1a4e4b46ddda)  
（低）
</td>
<td style="border:1px solid black;">
[用于 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b9308d50-ca66-43ff-9dc5-d05c90baa764)  
（中等）  
[用于 Windows Server 2003 SP2（用于基于 Itanium 的系统）的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5622f223-df9c-4a6a-bdf0-feebaf9920fd)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6387228c-eedc-4511-b3c6-8922606f4c84)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=92495551-dedd-43d4-bb3a-51028bc5c6d6)  
（严重）  
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5e2cbd7d-f64f-49e5-a159-1965ebfe2a92)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b4f5089-13b1-421b-a00b-22632bba4229)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=3cb139b3-59f4-44ef-9911-4dd4e3b83e7d)  
（严重）  
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b7a7e8e7-f4c5-459d-ab6c-05a192e1e3f9)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e175c436-37e0-497f-8b7f-6cacaa25ad7c)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8c4c91ec-1b2b-4176-bd77-45245b590329)\*\*  
（严重）  
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f5ce8582-af63-4870-bee3-0abeeefa1458)\*\*  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1b10a177-fd45-406f-8edc-b8d4b84881b7)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f9975b8-3f91-4116-9200-ef55ece75854)\*\*  
（严重）  
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2 中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=be11981c-d286-4e3c-94bf-d4e67a975d5a)\*\*  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e8bc9a24-a794-4827-a6bb-785c6b2189f4)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2 中的 Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9395547f-b620-4cbd-9ff5-11b76cd73859)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=75491ad0-40a6-4efb-9574-d82210f6d0da)  
（低）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=278443c1-15dc-436b-893b-ffea6d29d16d)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8a53f0e9-0616-440e-90f2-a12524e1bee4)  
（低）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a584cd0f-2e05-4e36-8858-0ffead637162)  
（严重）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-001**](https://technet.microsoft.com/security/bulletin/ms10-001)
</td>
<td style="border:1px solid black;">
[**MS10-002**](https://technet.microsoft.com/security/bulletin/ms10-002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=308166e4-571b-4d6c-bd9f-3ed4afa4eafe)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d3386793-a594-4bc5-8308-28b561d43087)\*\*  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1d0da42b-9755-4fd2-afd1-0d023d187133)  
（低）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）中的 Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9d137bab-8312-4240-af74-c65ba652fde0)  
（严重）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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

-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 报告了 MS10-001 中描述的问题
-   [David Lindsay "thornmaker"](https://p42.us/) 和 [Eduardo A. Vela Nava "sirdarckcat"](https://www.sirdarckcat.net/) 报告了 MS10-002 中描述的问题
-   Lostmon Lords 报告了 MS10-002 中描述的问题
-   Brett Moore 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS10-002 中描述的问题
-   [team509](https://www.team509.com/) 的 Wushi 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS10-002 中描述的问题
-   eshu.co.uk 的 Sam Thomas 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-002 中描述的问题
-   eshu.co.uk 的 Sam Thomas 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-002 中描述的问题
-   [Fortinet FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) 的 Haifei Li 报告了 MS10-002 中描述的问题
-   [Verisign iDefense Labs](https://labs.idefense.com/) 的 Peter Vreugdenhil 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-002 中描述的问题
-   [BugSec](https://www.bugsec.com/) 的 Meron Sellem 报告了 MS10-002 中描述的问题

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)以下公司与我们合作并提供关于 MS10-002 中描述的问题的详细信息：

-   [Google Inc.](https://www.google.com/) 和 [MANDIANT](https://www.mandiant.com/)
-   [Adobe](https://www.adobe.com/)
-   [McAfee](https://www.mcafee.com/)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 1 月 12 日）： 已发布公告摘要。
-   V2.0（2010 年 1 月 21 日）： 添加了 Microsoft 安全公告 **MS10-002，即 Internet Explorer 的累积性更新 (978207)**。 还添加了此额外安全公告的公告网络广播链接。

*Built at 2014-04-18T01:50:00Z-07:00*
