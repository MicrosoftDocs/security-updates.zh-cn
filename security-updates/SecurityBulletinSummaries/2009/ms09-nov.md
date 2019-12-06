---
TOCTitle: 'MS09-NOV'
Title: 'Microsoft 安全公告摘要 (2009 年 11 月)'
ms:assetid: 'ms09-nov'
ms:contentKeyID: 61236936
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-nov(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 11 月)
======================================

发布时间: 2009年11月10日

**版本:** 1.0

本公告摘要列出了 2009 年 11 月发布的安全公告。

对于 2009 年 11 月发布的安全公告，本公告摘要替代 2009 年 11 月 5 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 11 月 11 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 11 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407490&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-063">MS09-063</a></td>
<td style="border:1px solid black;"><strong>Web Services on Devices API 中的漏洞可能允许远程执行代码 (973565)</strong><br />
<br />
此安全更新解决 Windows 操作系统上的 Web Services on Devices 应用程序编程接口 (WSDAPI) 中的一个秘密报告的漏洞。 如果受影响的 Windows 系统接收特制数据包，此漏洞可能允许远程执行代码。 只有本地子网上的攻击者才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-064">MS09-064</a></td>
<td style="border:1px solid black;"><strong>License Logging Server 中的漏洞可能允许远程执行代码 (974783)</strong><br />
<br />
此安全更新解决 Microsoft Windows 2000 中的一个秘密报告的漏洞。如果攻击者向运行 License Logging Server 的计算机发送特制的网络消息，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制系统。 采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-065">MS09-065</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (969947)</strong><br />
<br />
此安全更新可解决 Windows 内核中许多秘密报告的漏洞。 如果用户查看了以特制 Embedded OpenType (EOT) 字体呈现的内容，这些漏洞最严重时可以允许远程执行代码。 在基于 Web 的攻击情形中，攻击者必须拥有一个网站，其中包含用来试图利用此漏洞的特制嵌入字体。 另外，接受或宿主用户提供的内容的网站以及受到破坏的网站可能包含可能利用此漏洞的特制内容。 攻击者无法强迫用户访问特制的网站。 攻击者必须说服用户访问网站，通常的方式是让用户单击电子邮件或 Instant Messenger 消息中的链接而转到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-066">MS09-066</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的漏洞可能允许拒绝服务 (973309)</strong><br />
<br />
此安全更新解决 Active Directory 目录服务、Active Directory 应用程序模式 (ADAM) 和 Active Directory 轻型目录服务 (AD LDS) 中的一个秘密报告的漏洞。 如果执行某些类型的 LDAP 或 LDAPS 请求期间耗尽堆栈空间，该漏洞可以允许拒绝服务。 此漏洞仅影响配置为运行 ADAM 或 AD LDS 的域控制器和系统。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-067">MS09-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel 中的漏洞可能允许远程执行代码 (972652)</strong><br />
<br />
此安全更新可解决 Microsoft Office Excel 中许多秘密报告的漏洞。 如果用户打开特制的 Excel 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-068">MS09-068</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word 中的漏洞可能允许远程执行代码 (976307)</strong><br />
<br />
此安全更新解决了一个秘密报告的漏洞，如果用户打开特制 Word 文件，该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID 和 CVE ID 的排序列出。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                                   | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                       |  
|---------------------------------------------------------------------|--------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|------------------------------------|  
| [MS09-063](https://technet.microsoft.com/security/bulletin/ms09-063) | 设备 API 上的 Web 服务内存损坏漏洞         | [CVE-2009-2512](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 此方案可能允许服务攻击的限制拒绝。 |  
| [MS09-064](https://technet.microsoft.com/security/bulletin/ms09-064) | License Logging Server 堆溢出漏洞          | [CVE-2009-2523](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k 空指针解除引用漏洞                  | [CVE-2009-1127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k 数据验证不足漏洞                    | [CVE-2009-2513](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     |                                    |  
| [MS09-065](https://technet.microsoft.com/security/bulletin/ms09-065) | Win32k EOT 分析漏洞                        | [CVE-2009-2514](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     |                                    |  
| [MS09-066](https://technet.microsoft.com/security/bulletin/ms09-066) | LSASS 递归堆栈溢出漏洞                     | [CVE-2009-1928](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 该情况对于拒绝服务存在。           |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 高速缓存损坏漏洞                     | [CVE-2009-3127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel SxView 内存损坏漏洞                  | [CVE-2009-3128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel Featheader 记录内存损坏漏洞          | [CVE-2009-3129](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 文档分析堆溢出漏洞                   | [CVE-2009-3130](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3130) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 公式分析内存损坏漏洞                 | [CVE-2009-3131](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3131) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 索引分析漏洞                         | [CVE-2009-3132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3132) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 文档分析内存损坏漏洞                 | [CVE-2009-3133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3133) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-067](https://technet.microsoft.com/security/bulletin/ms09-067) | Excel 字段清理漏洞                         | [CVE-2009-3134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                    |  
| [MS09-068](https://technet.microsoft.com/security/bulletin/ms09-068) | Microsoft Office Word 文件信息内存损坏漏洞 | [CVE-2009-3135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     |                                    |
  
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
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=365a8dff-2383-42f6-b567-e545461fd135)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上的 Active Directory](https://www.microsoft.com/download/details.aspx?familyid=297158cf-374c-45d9-b213-978e1f54d244)  
(KB973037)  
（重要）
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
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
无
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
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06)  
（严重）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=cbe09780-f288-457a-b254-58c9c8744055)  
(KB973039)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236)  
（严重）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a)  
(KB973039)  
（重要）
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
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
无
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a)  
（严重）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9)  
(KB973037)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e)  
(KB973039)  
（重要）
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=04a7f817-f330-4003-8b25-d3e744905b12)  
（严重）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=509aeec0-112b-44ab-8686-43f381b61940)  
(KB973037)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=87f2109e-5129-467c-930f-70af31ebf5de)  
(KB973039)  
（重要）
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9)  
（严重）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca)  
(KB973037)  
（重要）
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
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ebf0c294-cd99-445a-a741-78253e47189f)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
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
[**MS09-063**](https://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](https://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](https://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](https://technet.microsoft.com/security/bulletin/ms09-066)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d6a60883-b103-459a-a91b-cd6ed946cefe)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=701abf15-7f93-41de-8d09-13404fd79a7e)\*  
(KB973037)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3dde1587-42d3-438f-8344-696a5657b9b1)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0e2b8607-10fa-406a-96a5-18290f479c48)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0)\*  
(KB973037)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=28eba3f3-99a5-424c-bc8d-a718c716699e)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

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
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=5672c8fc-8509-4962-ad86-ebc0f2575043)  
(KB973471)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273)  
(KB973444)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5)  
(KB973475)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54)  
(KB973443)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693)<sup>[1]</sup>  
(KB973593)  
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
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
（重要）
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-067**](https://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](https://technet.microsoft.com/security/bulletin/ms09-068)
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
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=19151e22-5642-456c-bd39-298574369cdb)  
(KB973484)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 和 Microsoft Office Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3)  
(KB973707)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 1 的 Microsoft Office 兼容包以及用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa)  
(KB973704)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS09-067 注释**

<sup>[1]</sup>对于 Microsoft Office Excel 2007 Service Pack 1 和 Microsoft Office Excel 2007 Service Pack 2，除了安全更新程序包 KB969682 之外，客户还需要安装[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 和用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=?...?) 的安全更新 (KB973704)，以免受本公告中所描述的漏洞影响。

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

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](https://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](https://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

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

-   [Google Inc.](https://www.google.com/) 的 Neel Mehta 报告了 MS09-063 中描述的问题
-   [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) 的 Cody Pierce 报告了 MS09-064 中描述的问题
-   Agin Sun 报告了 MS09-065 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 报告了 MS09-065 中描述的问题
-   [Fortinet's FortiGuard Labs](https://www.fortiguard.com/) 的 Bing Liu 报告了 MS09-067 中描述的三个问题
-   [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS09-067 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Sean Larsson 报告了 MS09-067 中描述的问题
-   [VUPEN Security](https://www.vupen.com/) 的 Nicolas Joly 报告了 MS09-067 中描述的四个问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Jun Mao 报告了 MS09-068 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 11 月 10 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
