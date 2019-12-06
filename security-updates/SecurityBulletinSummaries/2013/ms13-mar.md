---
TOCTitle: 'MS13-MAR'
Title: 'Microsoft 安全公告摘要（2013 年 3 月）'
ms:assetid: 'ms13-mar'
ms:contentKeyID: 61236983
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-mar(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 3 月）
======================================

发布时间: 2013年3月12日 | 更新时间: 2013年3月15日

**版本:** 1.1

本公告摘要列出了 2013 年 3 月发布的安全公告。

对于 2013 年 3 月发布的安全公告，本公告摘要替代 2013 年 3 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 3 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 3 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us)提供。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279923">MS13-021</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2809289)<br />
<br />
</strong>此安全更新可解决 Internet Explorer 中八个秘密报告的漏洞和一个公开披露的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275737">MS13-022</a></td>
<td style="border:1px solid black;"><strong>Silverlight 中的漏洞可能允许远程执行代码 (2814124)</strong><br />
<br />
此安全更新解决了 Microsoft Silverlight 中一个秘密报告的漏洞。如果攻击者拥有包含可以利用此漏洞的特制 Silverlight 应用程序的网站，然后诱使用户查看该网站，则该漏洞可能允许执行执行代码。攻击者还可能利用受到破坏的网站以及接受或宿主用户提供的内容或广告的网站。此类网站可能包含可以利用此漏洞的特制内容。但是在所有情况下，攻击者无法强制用户访问网站。相反，攻击者必须诱使用户访问该网站，通常是让用户单击电子邮件或 Instant Messenger 消息中的链接使用户链接到攻击者的网站。它还可能使用横幅广告或其他方式显示特制的 Web 内容，以便将 Web 内容传递至受影响的系统。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276801">MS13-023</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio Viewer 2010 中的漏洞可能允许远程执行代码 (2801261)<br />
<br />
</strong>此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果用户打开特制的 Visio 文件，则该漏洞可能允许远程执行代码。成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271610">MS13-024</a></td>
<td style="border:1px solid black;"><strong>SharePoint 中的漏洞可能允许特权提升 (2780176)<br />
<br />
</strong>此安全更新可解决 Microsoft SharePoint 和 Microsoft SharePoint Foundation 中四个秘密报告的漏洞。如果用户单击可将用户定向到目标 SharePoint 网站的特制 URL，则最严重的漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft 服务器软件</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282355">MS13-025</a></td>
<td style="border:1px solid black;"><strong>Microsoft OneNote 中的漏洞可能允许信息泄露 (2816264)<br />
<br />
</strong>此安全更新可解决 Microsoft OneNote 中一个秘密报告的漏洞。如果攻击者诱使用户打开特制 OneNote 文件，则此漏洞可能允许信息泄露。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280673">MS13-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office</strong> <strong>for Mac 中的漏洞可能允许信息泄露 (2813682)<br />
<br />
</strong>此安全更新解决 Microsoft Office for Mac 中一个秘密报告的漏洞。如果用户打开特制的电子邮件，则该漏洞可能允许信息泄露。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282639">MS13-027</a></td>
<td style="border:1px solid black;"><strong>内核模式驱动程序中的漏洞可能允许特权提升 (2807986)</strong> <strong><br />
<br />
</strong>此安全更新解决 Microsoft Windows 中三个秘密报告的漏洞。如果攻击者获得对系统的访问权限，这些漏洞可能允许特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                                                | CVE ID                                                                           | 最新软件版本的利用评估                                                                    | 较旧软件版本的利用评估                                                                    | 拒绝服务利用评估 | 重要注意事项           |  
|-----------------------------------------------------------|---------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|------------------|------------------------|  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer OnResize 释放后使用漏洞               | [CVE-2013-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0087) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer saveHistory 释放后使用漏洞            | [CVE-2013-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0088) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CMarkupBehaviorContext 释放后使用漏洞 | [CVE-2013-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0089) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CCaret 释放后使用漏洞                 | [CVE-2013-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0090) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建   | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CElement 释放后使用漏洞               | [CVE-2013-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0091) | 不受影响                                                                                  | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer GetMarkupPtr 释放后使用漏洞           | [CVE-2013-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0092) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer onBeforeCopy 释放后使用漏洞           | [CVE-2013-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0093) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer removeChild 释放后使用漏洞            | [CVE-2013-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0094) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CTreeNode 释放后使用漏洞              | [CVE-2013-1288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1288) | 不受影响                                                                                  | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | 此漏洞已公开披露。     |  
| [MS13-022](http://go.microsoft.com/fwlink/?linkid=275737) | Silverlight 双重解除引用漏洞                            | [CVE-2013-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0074) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用                                                                                    | 不适用           | （无）                 |  
| [MS13-023](http://go.microsoft.com/fwlink/?linkid=276801) | Visio Viewer 树对象类型混淆漏洞                         | [CVE-2013-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0079) | 不受影响                                                                                  | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建   | 不适用           | （无）                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | 回叫函数漏洞                                            | [CVE-2013-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0080) | 不受影响                                                                                  | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint XSS 漏洞                                     | [CVE-2013-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0083) | 不受影响                                                                                  | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint 目录遍历漏洞                                 | [CVE-2013-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0084) | 不受影响                                                                                  | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 不适用           | （无）                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | 缓冲区溢出漏洞                                          | [CVE-2013-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0085) | 不受影响                                                                                  | [3](http://technet.microsoft.com/security/cc998259) - 不太可能被利用的漏洞检测代码        | 临时             | 这是一个拒绝服务漏洞。 |  
| [MS13-025](http://go.microsoft.com/fwlink/?linkid=282355) | 缓冲区大小验证漏洞                                      | [CVE-2013-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0086) | 不受影响                                                                                  | [3](http://technet.microsoft.com/security/cc998259) - 不太可能被利用的漏洞检测代码        | 不适用           | 这是一个信息泄露漏洞。 |  
| [MS13-026](http://go.microsoft.com/fwlink/?linkid=280673) | 意外内容加载漏洞                                        | [CVE-2013-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0095) | [3](http://technet.microsoft.com/security/cc998259) - 不太可能被利用的漏洞检测代码        | [3](http://technet.microsoft.com/security/cc998259) - 不太可能被利用的漏洞检测代码        | 不适用           | 这是一个信息泄露漏洞。 |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 描述符漏洞                                  | [CVE-2013-1285](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1285) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 永久             | （无）                 |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 描述符漏洞                                  | [CVE-2013-1286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1286) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 永久             | （无）                 |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 描述符漏洞                                  | [CVE-2013-1287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1287) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码 | 永久             | （无）                 |
  
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
<th colspan="3" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ace6994d-7482-40de-84ad-a87853a35860)  
(2809289)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=50c59794-4ec7-404a-b316-dae314521ebb)  
(2809289)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7e5d96a7-d9f5-4832-b4f9-b6e0148c655b)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ba528d03-b0a6-40a5-a6bd-13c062a8a877)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=795cef4e-9c01-447f-916c-e52e69eca4a3)  
(2809289)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=16993a2c-1fe1-4c1e-bcd9-db1a7dd4a058)  
(2809289)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=66a08524-883d-4d67-82cc-2c0f55c56b31)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4f8a48d4-b1bb-465c-a232-d29fe94d1429)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=e3c911b3-7fdd-4105-a20a-eef65b0908e3)  
(2809289)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0f58d63e-0d2c-41d2-9792-edbb2f4a539d)  
(2809289)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e6b63da9-a414-40ee-b877-4fb0d62bacba)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=835651b7-79fb-4d50-b48e-f02173062253)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=eaf2c568-089a-4c2f-bca6-da83f7332de9)  
(2809289)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5a18b139-2773-44c8-85f9-8dce24249e71)  
(2809289)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d6feba92-f014-4521-b6c4-7f5f358a3ce3)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9d5f1ed1-f33b-4c90-9b29-ee8ac587d31b)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=088fd3ec-62e1-4737-8132-6b51219ed37f)  
(2809289)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=799748d8-056d-4139-86e1-9bd0cb0151b4)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=28d441e7-abcf-4cc9-84e0-572e5b79aab7)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0bf77905-1199-4219-a67d-1e9ad3f63757)  
(2809289)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=76e328f8-4f86-4e50-b7e0-22db0385ab01)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c26f74fc-e224-4533-a4e3-b52125dca5cd)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8472bc7-9e20-4238-adcf-a1e1a91687a1)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7b652bb4-7a0a-437b-bcc5-ebbbb820c559)  
(2809289)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=67b09398-ceb6-403c-bba4-261d9d9dea98)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3f1795a5-4376-4929-8748-743840ec2154)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e412c54a-a93d-4c5b-9b13-40b59d1dff35)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0303fcb1-34d5-47da-b6ee-18222fe3235a)  
(2809289)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=337068a5-9281-4db6-9ff1-5282cdfa0763)  
(2809289)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c672c196-5072-468c-8d88-34534fa219fd)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f22b9327-1430-44cb-a609-ea1bb9b7b8f8)  
(2809289)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0496cbfe-77d2-4de6-b78d-937225dc8974)  
(2809289)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=5c40f237-b4c8-41eb-a649-baad46dfa13c)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=09e4832c-b95e-4581-a73b-49cb6a60c1df)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=af2e8e83-fb8f-4ba5-83ec-8bd4347a5fe6)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
（严重）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
（中等）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=7c348fe3-f4f0-4f22-8a7f-8563705c1f64)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=de4ec125-c337-4615-b39b-8456658dae22)  
(2807986)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=0c503b83-5b13-41da-a5ff-7519bc244521)  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 8（用于 64 位系统）](https://www.microsoft.com/download/details.aspx?familyid=c1539e94-0635-4f51-8172-a96a737d81d3)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](https://www.microsoft.com/download/details.aspx?familyid=f9b299f1-8a73-40b2-9942-e6419496bb39)  
(2809289)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752)  
(2807986)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告** **标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer10<sup>[1]</sup>  
(2809289)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-021**](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[**MS13-027**](http://go.microsoft.com/fwlink/?linkid=282639)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e)（服务器核心安装）  
(2807986)  
（重要）
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
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6)（服务器核心安装）  
(2807986)  
（重要）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)（服务器核心安装）  
(2807986)  
（重要）
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
[Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)（服务器核心安装）  
(2807986)  
（重要）
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
[Windows Server 2012](https://www.microsoft.com/download/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752)（服务器核心安装）  
(2807986)  
（重要）
</td>
</tr>
</table>

**MS13-021 的注释**

<sup>[1]</sup> Windows RT 安全更新仅通过 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 提供。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-023**](http://go.microsoft.com/fwlink/?linkid=276801)
</td>
<td style="border:1px solid black;">
[**MS13-025**](http://go.microsoft.com/fwlink/?linkid=282355)
</td>
<td style="border:1px solid black;">
[**MS13-026**](http://go.microsoft.com/fwlink/?linkid=280673)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
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
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 （32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 （32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=b01b4410-1107-472f-bf96-234304e91e77)  
(2687505)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 （64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 （64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=24065dd5-251b-4a3c-bb44-8d552a1f265e)  
(2687505)  
（严重）
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
Microsoft Visio 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=7a1a21e7-3137-4201-a005-cc66379fc1c5)  
(2760762)  
（没有严重等级）<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=7b7d39f0-a341-4d48-8177-329cccb5a7f1)  
(2760762)  
（没有严重等级）<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f10db48f-a980-47bf-83a5-c0da4e615114)  
(2553501)  
（没有严重等级）<sup>[1]</sup>
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Filter Pack Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=70d3372b-74a8-4b68-b6c4-18863835915d)  
(2553501)  
（没有严重等级）<sup>[1]</sup>
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
Microsoft OneNote 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=da4bfd31-65b9-496b-aa98-4fa8b729dcf3)  
(2760600)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft OneNote 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=10fc7350-e1d4-40b6-a5d1-8670263faf05)  
(2760600)  
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=d7aef20a-922b-4495-b473-1afa4a7ac514)  
(2817449)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=4960674b-1cb4-499a-999e-7aa4d4c49e5e)  
(2817452)  
（重要）
</td>
</tr>
</table>

**MS13-023 的注释**

<sup>[1]</sup>严重等级不适用于指定软件的此更新，因为该漏洞的的已知攻击媒介已被阻止。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-022**](http://go.microsoft.com/fwlink/?linkid=275737)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安装在 Mac 上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安装在 Mac 上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 客户端的所有受支持版本上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 客户端的所有受支持版本上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 服务器的所有受支持版本上的 [Microsoft Silverlight 5](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
安装在 Microsoft Windows 服务器的所有受支持版本上的 [Microsoft Silverlight 5 Developer Runtime](https://www.microsoft.com/download/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)  
（严重）
</td>
</tr>
</table>


#### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-024**](http://go.microsoft.com/fwlink/?linkid=271610)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=a9e8acbd-90e5-4acd-aa8f-b743a352787b)<sup>[1]</sup>  
(wasrv)  
(2553407)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-024**](http://go.microsoft.com/fwlink/?linkid=271610)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=293666ec-3290-4c6f-a7f6-b44c9b7fa0a6)  
(2687418)  
（重要）
</td>
</tr>
</table>

**MS13-024 的注释**

<sup>[1]</sup>对于 Microsoft SharePoint Server 2010 的受支持版本，除了安全 Microsoft SharePoint 2010 安全更新程序包 (2553407) 外，客户还需要安装 Microsoft SharePoint Foundation 2010 安全更新 (2687418)，以免受本公告中所描述的漏洞影响。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS13-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](http://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](http://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS13-021**

-   [TELUS Security Labs](http://telussecuritylabs.com/) 的 Arseniy Akuney 报告了 Internet Explorer OnResize 释放后使用漏洞 (CVE-2013-0087)
-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer saveHistory 释放后使用漏洞 (CVE-2013-0088)
-   一名匿名研究人员与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer CMarkupBehaviorContext 释放后使用漏洞 (CVE-2013-0089)
-   [Harmony Security](http://www.harmonysecurity.com) 的 Stephen Fewer 与[HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer CCaret 释放后使用漏洞 (CVE-2013-0090)
-   SkyLined 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer CCaret 释放后使用漏洞 (CVE-2013-0090)
-   Yenteasy Security Research 的 Jose A Vazquez 与 [Exodus Intelligence](https://www.exodusintel.com/) 合作报告了 Internet Explorer CElement 释放后使用漏洞 (CVE-2013-0091)
-   [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer GetMarkupPtr 释放后使用漏洞 (CVE-2013-0092)
-   [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer onBeforeCopy 释放后使用漏洞 (CVE-2013-0093)
-   Simon Zuckerbraun 与 [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 Internet Explorer removeChild 释放后使用漏洞 (CVE-2013-0094)
-   [Venustech](http://www.venustech.com.cn/) ADLab 的 Gen Chen 与我们一起努力处理了 Internet Explorer CTreeNode 释放后使用漏洞 (CVE-2013-1288)
-   [Qihoo 360 Security Center](http://www.360.cn/) 与我们一起处理了 Internet Explorer CTreeNode 释放后使用漏洞 (CVE-2013-1288)

**MS13-022**

-   [Context Information Security](http://www.contextis.com/) 的 James Forshaw 报告了 Silverlight 双重解除引用漏洞 (CVE-2013-0074)

**MS13-023**

-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 一起报告了 Visio Viewer 树对象类型混淆漏洞 (CVE-2013-0079)

**MS13-024**

-   [BugSec](http://www.bugsec.com/) 的 Emanuel Bronshtein 报告了回叫函数漏洞 (CVE-2013-0080)
-   INR 实验室 ([Network Intelligence India](http://niiconsulting.com/)) 的 Sunil Yadav 报告了 SharePoint XSS 漏洞 (CVE-2013-0083)
-   [n.runs AG](http://www.nruns.com/) 的 Moritz Jodeit 报告了 SharePoint 目录遍历漏洞 (CVE-2013-0084)

**MS13-025**

-   的 Christopher Gabriel 报告了缓冲区大小验证漏洞 (CVE-2013-0086)

**MS13-026**

-   [Nick Semenkovich](https://technet.microsoft.com/zh-CN/mailto:semenko@alum.mit.edu) 报告了意外内容加载漏洞 (CVE- 2013-0095)

**MS13-027**

-   NCC Group 的 Andy Davis 报告了 Windows USB 描述符漏洞 (CVE-2013-1285)
-   NCC Group 的 Andy Davis 报告了 Windows USB 描述符漏洞 (CVE-2013-1286)
-   NCC Group 的 Andy Davis 报告了 Windows USB 描述符漏洞 (CVE-2013-1287)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](http://technet.microsoft.com/security/bb980617.aspx)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](http://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 3 月 12 日）： 已发布公告摘要。
-   V1.1（2013 年 3 月 15 日） 对于 MS13-026，在“**执行摘要**”部分更正了公告标题。

*Built at 2014-04-18T01:50:00Z-07:00*
