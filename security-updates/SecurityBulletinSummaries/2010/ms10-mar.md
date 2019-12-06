---
TOCTitle: 'MS10-MAR'
Title: 'Microsoft 安全公告摘要 (2010 年 3 月)'
ms:assetid: 'ms10-mar'
ms:contentKeyID: 61236946
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-mar(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 3 月)
=====================================

发布时间: 2010年3月9日 | 更新时间: 2010年8月11日

**版本:** 3.1

本公告摘要列出了 2010 年 3 月发布的安全公告。

对于 2010 年 3 月发布的安全公告，本公告摘要替代 2010 年 3 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 3 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 3 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427711&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

对于添加到此公告摘要 (MS10-018) 的版本 2.0 的额外安全公告，Microsoft 在美国和加拿大太平洋时间 2010 年 3 月 30 日下午 1:00 进行网络广播，以解决客户关于这些公告的疑问： [立即注册申请收听 3 月 30 日下午 1:00 的网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032448112&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-018">MS10-018</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (980182)</strong> <br />
<br />
此安全更新可解决 Internet Explorer 中九个秘密报告的漏洞和一个公开披露的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-016">MS10-016</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker 中的漏洞可能允许远程执行代码 (975561)</strong><br />
<br />
此安全更新解决了 Windows Movie Maker 和 Microsoft Producer 2003 中一个秘密报告的漏洞。Windows Live Movie Maker（适用于 Windows Vista 和 Windows 7）不受此漏洞的影响。 如果攻击者发送了特制的 Movie Maker 或 Microsoft Producer 项目文件并诱使用户打开该特制的文件，则该漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-017">MS10-017</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的漏洞可能允许远程执行代码 (980150)</strong><br />
<br />
此安全更新可解决 Microsoft Office Excel 中七个秘密报告的漏洞。 如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。
  
**如何使用该表？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                                                  | CVE ID                                                                           | 利用指数评估                                                                                  | 重要注意事项                                 |  
|---------------------------------------------------------------------|-----------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------|  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel 记录内存损坏漏洞                   | [CVE-2010-0257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0257) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel MDXTUPLE 记录堆溢出漏洞            | [CVE-2010-0260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0260) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel MDXSET 记录堆溢出漏洞              | [CVE-2010-0261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0261) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel XLSX 文件分析代码执行漏洞          | [CVE-2010-0263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel DbOrParamQry 记录分析漏洞          | [CVE-2010-0264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0264) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-016](http://technet.microsoft.com/security/bulletin/ms10-016) | Movie Maker 和 Producer 缓冲区溢出漏洞                    | [CVE-2010-0265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0265) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 对象内存损坏漏洞                                     | [CVE-2010-0491](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0491) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 对象内存损坏漏洞                                     | [CVE-2010-0492](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0492) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 元素跨域漏洞                                         | [CVE-2010-0494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0494) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | 代码执行仅在 Windows 2000 上可能实现         |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 未初始化的内存损坏漏洞                                    | [CVE-2010-0806](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0806) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞当前正在 Internet 生态系统中被利用** |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | HTML 呈现内存损坏漏洞                                     | [CVE-2010-0807](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0807) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel 工作表对象类型混淆漏洞             | [CVE-2010-0258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0258) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-017](http://technet.microsoft.com/security/bulletin/ms10-017) | Microsoft Office Excel FNGROUPNAME 记录未初始化的内存漏洞 | [CVE-2010-0262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0262) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 竞争状态内存损坏漏洞                                      | [CVE-2010-0489](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0489) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 内存损坏漏洞                                              | [CVE-2010-0805](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0805) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 未初始化的内存损坏漏洞                                    | [CVE-2010-0267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0267) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的代码     | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | Post 编码信息泄露漏洞                                     | [CVE-2010-0488](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0488) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的代码     | （无）                                       |  
| [MS10-018](http://technet.microsoft.com/security/bulletin/ms10-018) | 未初始化的内存损坏漏洞                                    | [CVE-2010-0490](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0490) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的代码     | （无）                                       |
  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=389da7a9-e0a3-4b5d-801e-0a38fc55dcec)  
（严重）  
[Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=daf199c4-da56-4a7f-80e6-3936ce5c267b)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](https://www.microsoft.com/download/details.aspx?familyid=6301e462-02be-4b9a-bae9-7c4821b42d2d)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2f2caa01-5cd1-45cb-9995-e34d933920d4)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=167ed896-d383-4dc0-9183-cd4cb73e17e7)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=46172617-293a-44c7-95b6-18202ab06a41)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Movie Maker 2.1](https://www.microsoft.com/download/details.aspx?familyid=cae81585-d0df-41b8-9277-ca02f1265056)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6c711387-6853-477c-917e-820a97613cf9)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=aadb1d97-5cec-45ed-9967-aaf41a0bcdac)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=284d70ea-24a3-4e67-a2a8-e9f272f728db)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=dc77f1c9-8240-42d9-aee9-30ac4f33bde7)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e957a7cf-e5ca-454d-b199-ec8fe6a6a2bf)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=53fc3285-63c4-487f-ad9a-7e1673aeffc7)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2be85462-28ec-4184-a326-0459554b7213)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=cb0e39f8-9730-4454-a0e3-479b610b1591)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5201a0c5-8162-4809-b9d1-0e972b0f0066)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=04abea55-ea2f-423f-b410-5536ea184ea3)  
（重要）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7ebd99b4-da6b-4dff-9f89-6a86d275a3da)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](https://www.microsoft.com/download/details.aspx?familyid=ae2e9b75-1616-4fe3-91bb-e2e28252ff1c)<sup>[1]</sup>  
（重要）  
[Movie Maker 2.6](https://www.microsoft.com/download/details.aspx?familyid=ca2d1118-ca64-419d-86af-9396e61b90b0)<sup>[2]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=511aba0e-6f15-42cf-9c5d-b2f3e215b5a8)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c9584689-5196-4840-927c-23c8038f3382)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Movie Maker 6.0](https://www.microsoft.com/download/details.aspx?familyid=e27f353e-deb6-4d61-8808-c751d20a42a1)<sup>[1]</sup>  
（重要）  
[Movie Maker 2.6](https://www.microsoft.com/download/details.aspx?familyid=6a1f4126-97f2-4aee-bfe1-05bd13a0667b)<sup>[2]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c8933a45-62a7-4c19-be30-02e3a461f081)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=50809cc3-6baa-41b4-ba0a-596a1dd846ed)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=42f8c1f2-ee55-47af-b113-8d9f4bd40c8f)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c69a6dfe-66b1-4426-96a5-d64000296e76)\*\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=769043b5-df52-4446-9bd8-dc37d9fa00df)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e16c10d2-896d-48f3-bc76-5fa70881396a)\*\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c1c2309d-22db-4dbf-ad95-3219847cd42d)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c0145563-428e-47b6-b245-b59dce88ac0e)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6172dbec-6bfc-40bd-a0d4-67c39fb41b87)  
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
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
<td style="border:1px solid black;">
[**MS10-018**](http://technet.microsoft.com/security/bulletin/ms10-018)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8b7c664b-8612-458f-bd0a-cf28b67f8374)\*\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=82fa6f47-002f-4943-888c-2e852675e76e)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS10-016 注释**

<sup>[1]</sup> 这些版本的 Windows Movie Maker 随指定的操作系统附带提供。

<sup>[2]</sup> Windows Movie Maker 2.6 是一种可选下载程序，可以安装在指定的操作系统上。

有关相同公告标识符下的更多更新文件，另请参阅本部分“受影响的软件和下载位置”下的其他软件类别。 此公告涉及多个软件类别。

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
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e0136f62-60ce-4ebd-8660-be81eba29ae8)  
(KB978471)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7e42793e-747b-48da-968a-1ec29ea37151)  
(KB978474)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=03429f8a-8aab-4a59-97e4-7ce047f100a5)<sup>[1]</sup>  
(KB978382)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ae5936f8-fe3f-4d23-a37c-d80f228e475e)  
(KB980837)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=e0ed1569-ab2f-407c-b728-4eddc463c385)  
(KB980839)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=4c5487d5-c912-4087-8c83-769e3fb78ea9)  
(KB980840)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-017**](http://technet.microsoft.com/security/bulletin/ms10-017)
</td>
<td style="border:1px solid black;">
[**MS10-016**](http://technet.microsoft.com/security/bulletin/ms10-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=010d0a4d-02a4-4142-963b-a38cd06cc897)  
(KB978383)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15)  
(KB978380)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 和 Microsoft Office SharePoint Server 2007 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=94ddf6ef-3392-4d77-a02b-3bc0470721cd)<sup>[2]</sup>  
(KB979439)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 和 Microsoft Office SharePoint Server 2007 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=06f6bffb-3fad-4fb5-878b-39550812e9b5)<sup>[2]</sup>  
(KB979439)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Producer 2003
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Producer 2003](https://www.microsoft.com/download/details.aspx?familyid=1b3c76d5-fc75-4f99-94bc-784919468e73)<sup>[3]</sup>  
（重要）
</td>
</tr>
</table>

**MS10-017 注释**

<sup>[1]</sup>对于 Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2，除了安全更新程序包 KB978382 之外，客户还需要安装[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 和用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=314f076e-8f9d-46c2-b666-86599a02bf15) 的安全更新 (KB978380)，以免受本公告中所描述的漏洞影响。

<sup>[2]</sup>此更新适用于安装了 Excel Services 的服务器，例如 Microsoft Office SharePoint Server 2007 Enterprise 和 Microsoft Office SharePoint Server 2007 For Internet Sites 的默认配置。 Microsoft Office SharePoint Server 2007 Standard 不包含 Excel Services。

**MS10-016 注释**

<sup>[3]</sup>此下载将安装的 Microsoft Producer 2003 升级到新版本 Microsoft Producer。 Microsoft Producer 仅有英语版。

有关相同公告标识符下的更多更新文件，另请参阅本部分“受影响的软件和下载位置”下的其他软件类别。 此公告涉及多个软件类别。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**注意** 从 2009 年 8 月 1 日起，Microsoft 将不再对 Office Update 和 Office Update 清单工具提供支持。 要继续获得 Microsoft Office 产品的最新更新，请使用 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)。 有关详细信息，请参阅[关于 Microsoft Office Update： 常见问题](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意** SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://www.microsoft.com/security/msrc/mapp/partners.mspx)中列出）提供的活动保护网站。

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

-   [Core Security Technologies](http://www.coresecurity.com/) 的 Damián Frizza 报告了 MS10-016 中描述的问题
-   [VUPEN Vulnerability Research Team](http://www.vupen.com/) 的 Nicolas Joly 报告了 MS10-017 中描述的问题
-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 报告了 MS10-017 中描述的四个问题
-   一名匿名研究人员与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 一起报告了 MS10-017 中描述的问题
-   [Core Security Technologies](http://www.coresecurity.com/) 的 Damián Frizza 报告了 MS10-017 中描述的问题
-   [Secunia](http://secunia.com) 与我们一起努力处理了 MS10-018 中描述的问题。
-   [Cyber Defense Institute Inc.](http://www.cyberdefense.jp/) 的 Daiki Fukumori 报告了 MS10-018 中描述的问题
-   [Red Database Security](http://www.red-database-security.com/) 的 Alexander Kornbrust 报告了 MS10-018 中描述的问题
-   [iSIGHT Partners](http://www.isightpartners.com/) Global Vulnerability Partnership 的 Ivan Fratric 报告了 MS10-018 中描述的问题
-   [team509](http://www.team509.com/) 的 Wushi 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 MS10-018 中描述的问题
-   Simon Zuckerbraun 与 [TippingPoint 的](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS10-018 中描述的问题
-   [Context Information Security](http://www.contextis.co.uk/) 的 Paul Stone 报告了 MS10-018 中描述的问题
-   一名匿名研究人员与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS10-018 中描述的问题
-   [VenusTech](http://www.venustech.com.cn/) 的 ADLab 报告了 MS10-018 中描述的两个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 3 月 9 日）： 已发布公告摘要。
-   V2.0（2010 年 3 月 30 日）： 添加了 Microsoft 安全公告 MS10-018，即 Internet Explorer 的累积性更新 (980182)。 还添加了此额外安全公告的公告网络广播链接。
-   V3.0（2010 年 5 月 3 日）： 宣布与 MS10-016 相关的 Microsoft Producer 下载的可用性。
-   V3.1（2010 年 8 月 11 日）： 针对 MS10-016 删除了 Windows Movie Maker 2.6，它不是 Windows 7 上的受影响组件。

*Built at 2014-04-18T01:50:00Z-07:00*
