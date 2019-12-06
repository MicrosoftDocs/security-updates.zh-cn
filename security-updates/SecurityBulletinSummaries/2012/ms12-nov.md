---
TOCTitle: 'MS12-NOV'
Title: 'Microsoft 安全公告摘要（2012 年 11 月）'
ms:assetid: 'ms12-nov'
ms:contentKeyID: 61236973
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms12-nov(v=Security.10)'
---



Microsoft 安全公告摘要（2012 年 11 月）
=======================================

发布时间: 2012年11月13日 | 更新时间: 2012年11月14日

**版本:** 2.0

本公告摘要列出了 2012 年 11 月发布的安全公告。

对于 2012 年 11 月发布的安全公告，本公告摘要替代 2012 年 11 月 8 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2012 年 11 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 11 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522560&culture=en-us)提供。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268299">MS12-071</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2761451)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中的三个秘密报告的漏洞。如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=260820">MS12-072</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 中的漏洞可能允许远程执行代码 (2727528)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中两个秘密报告的漏洞。如果用户在 Windows 资源管理器中浏览到特制公文包，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可能以当前用户的身份运行任意代码。如果当前用户使用管理用户权限登录，攻击者便可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=255026">MS12-074</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 中的漏洞可能允许远程执行代码 (2745030)</strong> <strong><br />
<br />
</strong>此安全更新可解决 .NET Framework 中五个秘密报告的漏洞。如果攻击者诱使目标系统的用户使用恶意代理自动配置文件，然后将代码注入到当前运行的应用程序中，则其中较严重的漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=270856">MS12-075</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (2761226)</strong> <strong><br />
<br />
</strong>此安全更新解决 Microsoft Windows 中三个秘密报告的漏洞。如果用户打开特制文档或者访问嵌入了 TrueType 字体文件的恶意网页，则这些漏洞中最严重的漏洞可能允许远程执行代码。攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=260964">MS12-076</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的漏洞可能允许远程执行代码 (2720184)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Microsoft Office 中 4 个秘密报告的漏洞。如果用户使用受影响的 Microsoft Excel 版本打开特制的 Excel 文件，则这两个漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=258247">MS12-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft Internet Information Services (IIS) 中的漏洞可能允许信息泄露 (2733829)<br />
<br />
</strong>此安全更新可解决 Microsoft Internet 信息服务 (IIS) 中一个公开披露和一个秘密报告的漏洞。如果攻击者向服务器发送特制 FTP 命令，则较严重的漏洞可能允许信息泄露。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                           | CVE ID                                                                           | 最新软件版本的利用评估                                                                    | 较旧软件版本的利用评估                                                                        | 拒绝服务利用评估 | 重要注意事项           |  
|-----------------------------------------------------------|------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------|------------------------|  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CFormElement 释放后使用漏洞        | [CVE-2012-1538](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1538) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CTreePos 释放后使用漏洞            | [CVE-2012-1539](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1539) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 临时             | （无）                 |  
| [MS12-071](https://go.microsoft.com/fwlink/?linkid=268299) | CTreeNode 释放后使用漏洞           | [CVE-2012-4775](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4775) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-072](https://go.microsoft.com/fwlink/?linkid=260820) | Windows Briefcase 整数下溢漏洞     | [CVE-2012-1527](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1527) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-072](https://go.microsoft.com/fwlink/?linkid=260820) | Windows 公文包整数溢出漏洞         | [CVE-2012-1528](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1528) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 临时             | （无）                 |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | 反射绕过漏洞                       | [CVE-2012-1895](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1895) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | 代码访问安全性信息泄露漏洞         | [CVE-2012-1896](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1896) | 不受影响                                                                                  | [3](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不适用           | 这是一个信息泄露漏洞。 |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | .NET Framework 不安全库加载漏洞    | [CVE-2012-2519](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2519) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | Web 代理自动发现漏洞               | [CVE-2012-4776](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4776) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | （无）                 |  
| [MS12-074](https://go.microsoft.com/fwlink/?linkid=255026) | WPF 反射优化漏洞                   | [CVE-2012-4777](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4777) | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | Win32k 释放后使用漏洞              | [CVE-2012-2530](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2530) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | （无）                 |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | Win32k 释放后使用漏洞              | [CVE-2012-2553](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2553) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | （无）                 |  
| [MS12-075](https://go.microsoft.com/fwlink/?linkid=270856) | TrueType 字体分析漏洞              | [CVE-2012-2897](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2897) | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建   | [2](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | 永久             | （无）                 |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel SerAuxErrBar 堆溢出漏洞      | [CVE-2012-1885](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1885) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel 内存损坏漏洞                 | [CVE-2012-1886](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1886) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel SST 无效的长度释放后使用漏洞 | [CVE-2012-1887](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1887) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |  
| [MS12-076](https://go.microsoft.com/fwlink/?linkid=260964) | Excel 堆栈溢出漏洞                 | [CVE-2012-2543](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2543) | 不受影响                                                                                  | [1](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                 |
  
受影响的软件和下载位置  
----------------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="6" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fcc633d6-fe18-4220-9b68-ff1479e4dec5)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f5472e86-2b2f-42bd-abca-6adf84973efa)  
(KB2698035)  
（仅限 Media Center Edition 2005 Service Pack 3 和 Tablet PC Edition 2005 Service Pack 3）  
（重要）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=31f2c645-b171-4f11-884b-f5056ef57b4f)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a736c3f0-0326-4a0a-9c12-f61bafa537bb)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=828699ac-eb88-4ff8-9110-69c206f5ef54)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0383bdea-53d1-4799-b380-14da1595882a)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=efe0de22-8ca3-474e-acda-7203bf66d0a3)  
(KB2698032)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=73f5dec6-ccda-426d-8d2c-a2db3e59734a)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=615a96fe-88a5-498b-ae20-bbfc43e3b652)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dc9cd62a-c42d-4c54-bc14-7abd34aeb865)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=36962e96-0eaa-45a9-b2d6-6bec3242c73e)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7e75292-efcf-4c97-960c-958f81931cbf)  
(KB2729450)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e4ec19ea-06f2-4164-8e39-84f1d7a47ae7)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
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
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=205f1cf3-5431-4740-96c2-eaf019edeeeb)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c19585e3-a358-40b0-80a3-8dbb25ba8557)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c4b3fb44-338d-48be-9981-53fa2cf3094a)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=e1785af2-a211-467e-a696-d53840581bca)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=b91091d0-176f-4ff9-98d2-74768b747c3a)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7e7b681c-c580-4671-a515-e5b469002c93)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=31f5ad28-ffe9-4370-b3fc-62eb9fc0c4dd)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7a58e874-f3fc-4db8-8de0-cbfc6ebbf349)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=2db93767-f364-49c6-9a03-39604173771f)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=0c499445-595f-459f-86cf-b821cbb5fa65)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=0161baaa-5d7b-4442-a202-41c64a73c9a8)  
(KB2761451)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=258048b5-d992-4821-8836-72262a7b5bb7)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=52f652bd-edc4-4450-91b4-f19401d2201c)  
(KB2761451)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1c067cb2-71a5-4f8d-9b11-243c9e5318ce)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=17a110d1-ef31-4230-9f2a-0df190c28747)  
(KB2698023)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d742523-5f51-4db7-b05f-a9055b36b090)  
(KB2729453)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fab87b20-398f-4043-9cbe-ffcae8e19ff0)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=279ac887-2420-48d7-bb85-c7cab49f7ff8)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=22ab8987-2506-433f-9f12-0ab60d569949)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c222943e-9888-4fb9-b9a2-7a035311c887)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=77a4ae4e-a75c-490a-a0b1-137816ed5c89)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=fb265aa5-0e09-411a-a0fe-bbb42c409a81)  
(KB2719033)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=eb9babdc-3fac-4ce9-a7ca-85e26a9cb11d)  
(KB2761451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fc70708e-9de9-4618-b0ab-d9aa3e2baea0)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=50d7c25f-a67f-4946-b6db-70d9bd4dc178)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=bda21ea5-f160-4361-8ede-40f6a53a30da)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=52b6ed39-b7c1-4d49-a6a7-e6208fab24fa)  
(KB2719033)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3d0a4455-b788-4ad7-be0c-5824f6103694)  
(KB2761451)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=800cd622-d271-41a4-bd21-a76177d2b272)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=70447115-957d-48a4-bc27-395abaf22149)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=92cd0488-03c2-400d-a506-eb2eb8fce7c7)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=1eea7e7f-83bf-40fc-a978-a4d08af8162a)  
(KB2719033)  
（中等）
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=d7c93ade-f7e3-4b6f-b93d-894ca313282f)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=b120a7a2-0eff-41d6-981e-60e5ecd55869)<sup>[2]</sup>  
(KB2756872)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=24ce3f78-fb25-4f51-8bb0-8cebf19d8843)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=7c4a17b7-bb7f-456c-9cb3-3a355e192734)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c7a417e6-72e5-4087-bb89-fb8e7f57894c)<sup>[2]</sup>  
(KB2756872)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=72c49d94-757c-4da4-a895-96d0830bc667)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
**无**
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=ad6189ae-9341-409b-a53e-486fef094fd0)  
(KB2727528)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>  
(KB2756872)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)****
</td>
<td style="border:1px solid black;">
**无**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>  
(KB2737084)  
（重要）  
Microsoft .NET Framework 4.5<sup>[2]</sup><sup>[3]</sup>  
(KB2756872)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>  
(KB2761226)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-071**](https://go.microsoft.com/fwlink/?linkid=268299)
</td>
<td style="border:1px solid black;">
[**MS12-072**](https://go.microsoft.com/fwlink/?linkid=260820)
</td>
<td style="border:1px solid black;">
[**MS12-074**](https://go.microsoft.com/fwlink/?linkid=255026)
</td>
<td style="border:1px solid black;">
[**MS12-075**](https://go.microsoft.com/fwlink/?linkid=270856)
</td>
<td style="border:1px solid black;">
[**MS12-073**](https://go.microsoft.com/fwlink/?linkid=266541)
</td>
</tr>
<tr class="alternateRow">
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）
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
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=17b987db-0551-45c3-aab1-0cc11ae60dcc)（服务器核心安装）  
(KB2761226)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=cb3598ae-b647-4aaa-90fb-b4d8aa1cf211)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=8b135d6f-0f6c-4bd5-bf64-d79ae16ac6a5)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）
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
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dd9bd994-41e3-46a1-9dfb-c6d89a3ef883)（服务器核心安装）  
(KB2761226)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=74d130a4-f42a-48af-87fc-349a1e107529)<sup>[1]</sup>  
(KB2716513)  
（中等）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=b061a0b0-66e2-49a2-8d20-0c5a6948aecf)<sup>[1]</sup>  
(KB2716513)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=bbdf1e16-67d9-413c-bad2-31d164fea0da)  
(KB2729451)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)（服务器核心安装）  
(KB2761226)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=aa5b1e9c-3068-40e3-b04f-6a71f1a51d45)  
(KB2729452)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=f89c10fb-9f85-47b6-8204-d970d7e84e33)<sup>[1]</sup>  
(KB2729449)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=ca52497c-8023-42de-b707-2bc1bcee4579)  
(KB2729460)  
（严重）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=4c57041f-0ffc-47c9-82d9-8b1d24d27489)<sup>[1]</sup>  
(KB2737019)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=48f57fe1-e180-4b6b-87f5-8dd0c8e821d3)  
(KB2737083)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=114b596c-36e1-45f5-99e2-f5fdd96b1a30)（服务器核心安装）  
(KB2761226)  
（重要）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=87f3aa7a-ee84-4e7e-972c-e83a2a06a0ef)  
(KB2716513)  
（中等）  
[Internet Information Services 7.5](https://www.microsoft.com/download/details.aspx?familyid=e1502884-1149-47b8-93af-7f82c5d83819)  
(KB2719033)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=89faa423-42fa-48ff-be71-8fd58fa523a8)  
(KB2729462)  
（严重）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=c9778a0f-264e-476b-8e40-742e0ab56200)  
(KB2737084)  
（重要）  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/details.aspx?familyid=0a7da3d1-a0ac-42a2-9929-b6d831deb9e3)<sup>[2]</sup>  
(KB2756872)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=2e69d496-25b4-4f24-97e0-47cb59c178aa)（服务器核心安装）  
(KB2761226)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS12-073注释**

<sup>[1]</sup>不是此操作系统的默认 FTP 服务。

**MS12-074 注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

<sup>[2]</sup> 在 Windows 8、Windows Server 2012 和 Windows RT 上运行 Microsoft .NET Framework 4.5 的客户不受此问题影响。2012 年 10 月 10 日发布的 Windows 8 客户端和 Windows Server 2012 公开发布累积性更新 KB2756872，包含其他纵深防御更改。作为纵深防御措施，鼓励尚未安装此更新的客户这样做。有关详细信息，请参阅 [Microsoft 知识库文章 2745030](https://support.microsoft.com/kb/2745030)中的“更多信息”部分。有关下载链接和进一步信息,请参阅[Microsoft知识库文章2756872](https://support.microsoft.com/kb/2756872)。 请注意,此更新包含与安全性无关的内容。

<sup>[3]</sup>Windows RT 安全更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

**MS12-07注释**

<sup>[1]</sup>此更新仅通过 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 提供。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=5bb12b2b-a8e2-4324-afee-e4d26dbc658f)  
(KB2687481)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>  
(KB2687307)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e12aafe1-4445-4047-ad05-3db151a6fa4e)<sup>[1]</sup>  
(KB2687307)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=37a1074d-bf4f-4b96-b394-1edc581748d0)  
(KB2597126)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=5db02eae-966e-41a9-8b64-ddda5f8b2e2a)  
(KB2597126)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d3d801a2-d57f-4b4c-970a-c296bc716521)  
(KB2764048)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=0f4e073f-4fec-440d-a9bf-1e01ee9e92ad)  
(KB2764047)  
（重要）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS12-076**](https://go.microsoft.com/fwlink/?linkid=260964)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=a0917aeb-1e94-4142-bc20-5f1998ac249c)<sup>[2]</sup>  
(KB2687313)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 兼容包 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=79686714-9418-4516-81c3-555fe1ea9e84)  
(KB2687311)  
（重要）
</td>
</tr>
</table>

**MS12-076注释**

<sup>[1]</sup>对于 Microsoft Excel 2007，除安全更新程序包 KB2687307 之外，客户还需要安装 Microsoft Office 兼容包的安全更新 (KB2687311)，以免受本公告中所描述的漏洞影响。

<sup>[2]</sup>在安装此更新之前，必须将 Microsoft Excel Viewer 更新到受支持的 Service Pack 级别（Excel Viewer 2007 Service Pack 2 或 Excel Viewer 2007 Service Pack 3）。有关受支持的 Office 查看器的信息，请参阅 [Microsoft 知识库文章 979860](https://support.microsoft.com/kb/979860)。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS12-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](https://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](https://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   spa-s3c.blogspot.com 的 Jose A. Vazquez 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 合作报告了 MS12-071 中描述的两个问题
-   [Omair](https://krash.in/) 报告了 MS12-071 中描述的问题
-   [Trend Micro](https://www.trendmicro.com/) 的 Cheng-da Tsai (Orange)、Sung-ting Tsai 和 Ming-chieh Pan (Nanika) 报告了 MS12-071 中描述的一个问题
-   Tal Zeltzer 与 [VeriSign iDefense Labs](https://labs.idefense.com/) 报告了 MS12-072 中描述的一个问题
-   ProDX 的 Justin Royce 报告了 MS12-073 中描述的一个问题
-   Context Information Security 的 James Forshaw 报告了 MS12-074 中描述的四个问题
-   [Google Inc](https://www.google.com) 的 [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 报告了 MS12-075 中描述的一个问题
-   [Documill](https://www.documill.com) 的 Eetu Luodemaa 和 Joni Vähämäkifor 报告了 MS12-075 中描述的一个问题
-   Sean Larsson 与 [iDefense VCP](https://labs.idefense.com) 报告了 MS12-076 中描述的一个问题
-   一名匿名研究员与 [iDefense VCP](https://labs.idefense.com) 一起报告了 MS12-076 中描述的问题
-   一名匿名研究员与 [iDefense VCP](https://labs.idefense.com) 一起报告了 MS12-076 中描述的问题
-   一位匿名研究员与 [HP TippingPoint's](https://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 一起报告了 MS12-076 中描述的一个问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2012 年 11 月 13 日）： 已发布公告摘要。
-   V1.1（2012 年 11 月 13 日）： 对于 MS12-075，已纠正 CVE-2012-2897 在**利用指数**中的 CVE 标题及拒绝服务利用评估。
-   V2.0（2012 年 11 月 14 日）： 对于 MS12-073，修订了公告摘要以反映 Windows Vista 和 Windows Server 2008 上的 KB2716513 更新已可以通过所有分发渠道提供，包括 Windows Update 和 Microsoft Update。有关详细信息，请参阅 MS12-073 公告。

*Built at 2014-04-18T01:50:00Z-07:00*
