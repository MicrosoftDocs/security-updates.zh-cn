---
TOCTitle: 'MS11-DEC'
Title: 'Microsoft 安全公告摘要 (2011 年 12 月)'
ms:assetid: 'ms11-dec'
ms:contentKeyID: 61236953
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms11-dec(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2011 年 12 月)
======================================

发布时间: 2011年12月13日 | 更新时间: 2012年2月22日

**版本:** 2.1

本公告摘要列出了 2011 年 12 月发布的安全公告。

对于 2011 年 12 月发布的安全公告，本公告摘要替代 2011 年 12 月 28 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2011 年 12 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 12 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487961)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 将在 2011 年 12 月 29 日下午 1 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于额外安全公告的疑问。[立即注册申请收听 12 月 29 日下午 1:00 的安全公告网络传播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032502798&culture=en-us)。此日期之后，此网络广播按需提供。有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://go.microsoft.com/fwlink/?linkid=217214)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=233008">MS11-087</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (2639417)</strong> <br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。如果用户打开特制文档或者访问嵌入了 TrueType 字体文件的恶意网页，此漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232507">MS11-090</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (2618451)</strong> <br />
<br />
此安全更新可解决 Microsoft 软件中一个秘密报告的漏洞。如果用户在 Internet Explorer 中查看使用特定二进制行为的特制网页，则此漏洞可能允许远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。此更新也包括用于四个第三方 ActiveX 控件的 kill bit。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232517">MS11-092</a></td>
<td style="border:1px solid black;"><strong>Windows Media 中的漏洞</strong> <strong>可能允许远程执行代码 (2648048)</strong> <br />
<br />
此安全更新可解决 Windows Media Player 和 Windows Media Center 中一个秘密报告的漏洞。如果用户打开特制的 Microsoft Digital Video Recording (.dvr-ms) 文件，此漏洞可能允许远程执行代码。不管怎样，不能强制用户打开文件；攻击要想成功，必须诱使用户这样做。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227070">MS11-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office IME（中文）中的漏洞</strong> <strong>可能允许特权提升 (2652016)</strong> <br />
<br />
此安全更新解决了 Microsoft Office IME（中文）中一个秘密报告的漏洞。如果登录用户在安装了微软拼音 (MSPY) 简体中文输入法编辑器 (IME) 受影响版本的系统上执行特定操作，则该漏洞可能会允许特权提升。成功利用此漏洞的攻击者可以运行内核模式中的任意代码。攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。仅 Microsoft Pinyin IME 2010 的实施受此漏洞影响。简体中文 IME 的其他版本和其他 IME 实施不受影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225739">MS11-089</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的漏洞</strong> <strong>可能允许远程执行代码 (2590602)</strong> <br />
<br />
此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果用户打开特制的 Word 文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235287">MS11-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher 中的漏洞</strong> <strong>可能允许远程执行代码 (2607702)</strong> <br />
<br />
此安全更新可解决 Microsoft Office 中一个公开披露的漏洞和三个秘密报告的漏洞。如果用户打开特制的 Publisher 文件，最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232516">MS11-093</a></td>
<td style="border:1px solid black;"><strong>OLE 中的漏洞可能允许远程执行代码 (2624667)</strong> <br />
<br />  
此安全更新解决了 Windows XP 和 Windows Server 2003 所有受支持的版本中一个秘密报告的漏洞。对于 Windows XP 和 Windows Server 2003 的所有受支持版本，此安全更新的等级为“重要”。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 不受此漏洞影响。<br />  
<br />
如果用户打开包含特制 OLE 对象的文件，则该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232493">MS11-094</a></td>
<td style="border:1px solid black;"><strong>Microsoft PowerPoint 中的漏洞可能允许远程执行代码 (2639142)</strong> <br />
<br />
此安全更新解决 Microsoft Office中两个秘密报告的漏洞。如果用户打开特制的 PowerPoint 文件，这些漏洞可能允许远程执行代码。成功利用其中任何一个漏洞的攻击者可以完全控制受影响的系统。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232666">MS11-095</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的漏洞可能允许远程执行代码 (2640045)</strong> <br />
<br />
此安全更新解决 Active Directory、Active Directory 应用程序模式 (ADAM) 和 Active Directory 轻型目录服务 (AD LDS) 中一个秘密报告的漏洞。如果攻击者登录到 Active Directory 域并运行特制应用程序，此漏洞可能允许远程执行代码。要利用此漏洞，攻击者首先需要获得凭据以登录到 Active Directory 域。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232696">MS11-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel 中的漏洞可能允许远程执行代码 (2640241)</strong> <br />
<br />
此安全更新解决了 Microsoft Office 中一个秘密报告的漏洞。如果用户打开特制的 Excel 文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。安装和配置 Office 文件验证 (OFV) 可防止打开可疑的文件，从而阻止利用 CVE-2011-3403 中所述的漏洞的攻击媒介。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232663">MS11-097</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统中的漏洞</strong> <strong>可能允许特权提升 (2620712)</strong> <br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者登录受影响的系统，并运行设计为将设备事件消息发送到较高完整性进程的特制应用程序，该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232424">MS11-098</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (2633171)</strong> <br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者登录受影响的系统并运行旨在利用该漏洞的特制应用程序，该漏洞可能允许特权提升。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232505">MS11-099</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2618444</strong> <strong>)</strong> <br />
<br />
此安全更新可解决 Internet Explorer 中的三个秘密报告的漏洞。如果用户打开与特制动态链接库 (DLL) 文件位于同一目录下的合法超文本标记语言 (HTML) 文件，最严重的漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows， <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232432">MS11-100</a></td>
<td style="border:1px solid black;"><strong>.NET Framework</strong> <strong>中的</strong> <strong>漏洞</strong> <strong>可能</strong> <strong>允许特权提升</strong> <strong>(2638420)</strong> <br />
<br />
此安全更新可解决 Microsoft .NET Framework 中一个公开披露的漏洞和三个秘密报告的漏洞。如果未通过身份验证的攻击者传送特制 Web 请求至目标站点，最严重的漏洞可能允许特权提升。成功利用此漏洞的攻击者可以在 ASP.NET 站点上在一个现有帐户的上下文内容中执行任何操作，包括执行任意命令。要利用此漏洞，攻击者必须能在 ASP.NET 站点上注册一个帐户，且必须知道一个现有用户名。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/security/cc998259.aspx)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
| 公告 ID                                                   | 漏洞标题                                 | CVE ID                                                                           | 最新软件版本的利用评估                                                                        | 较旧软件版本的利用评估                                                                        | 拒绝服务利用评估 | 重要注意事项                                                                                                                               |  
|-----------------------------------------------------------|------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS11-087](http://go.microsoft.com/fwlink/?linkid=233008) | TrueType 字体分析漏洞                    | [CVE-2011-3402](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | 此漏洞已公开披露。                                                                                                                         |  
| [MS11-088](http://go.microsoft.com/fwlink/?linkid=227070) | 拼音 IME 提升漏洞                        | [CVE-2011-2010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2010) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | （无）                                                                                                                                     |  
| [MS11-089](http://go.microsoft.com/fwlink/?linkid=225739) | Word 释放后使用漏洞                      | [CVE-2011-1983](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1983) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-090](http://go.microsoft.com/fwlink/?linkid=232507) | Microsoft Time 远程执行代码漏洞          | [CVE-2011-3397](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3397) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher 超出界限数组索引漏洞           | [CVE-2011-3410](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3410) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher 无效指针漏洞                   | [CVE-2011-3411](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3411) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-091](http://go.microsoft.com/fwlink/?linkid=235287) | Publisher 内存损坏漏洞                   | [CVE-2011-3412](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3412) | 不受影响                                                                                      | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | 不适用           | （无）                                                                                                                                     |  
| [MS11-092](http://go.microsoft.com/fwlink/?linkid=232517) | Windows Media Player DVR-MS 内存损坏漏洞 | [CVE-2011-3401](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3401) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-093](http://go.microsoft.com/fwlink/?linkid=232516) | OLE 属性漏洞                             | [CVE-2011-3400](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3400) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-094](http://go.microsoft.com/fwlink/?linkid=232493) | PowerPoint 不安全库加载漏洞              | [CVE-2011-3396](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3396) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 只有未安装最新的服务包时，Microsoft PowerPoint 2010 才会受到影响。                                                                         |  
| [MS11-094](http://go.microsoft.com/fwlink/?linkid=232493) | 艺术字形状 RCE 漏洞                      | [CVE-2011-3413](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3413) | 不受影响                                                                                      | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | 不适用           | （无）                                                                                                                                     |  
| [MS11-095](http://go.microsoft.com/fwlink/?linkid=232666) | Active Directory 缓冲区溢出漏洞          | [CVE-2011-3406](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3406) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | 只有运行 Active Directory、AD LDS 或 ADAM 的系统会受到影响。                                                                               |  
| [MS11-096](http://go.microsoft.com/fwlink/?linkid=232696) | 记录内存损坏漏洞                         | [CVE-2011-3403](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3403) | 不受影响                                                                                      | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-097](http://go.microsoft.com/fwlink/?linkid=232663) | CSRSS 本地特权提升漏洞                   | [CVE-2011-3408](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3408) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | （无）                                                                                                                                     |  
| [MS11-098](http://go.microsoft.com/fwlink/?linkid=232424) | Windows 内核异常处理程序漏洞             | [CVE-2011-2018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2018) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 永久             | （无）                                                                                                                                     |  
| [MS11-099](http://go.microsoft.com/fwlink/?linkid=232505) | XSS 筛选器信息泄露漏洞                   | [CVE-2011-1992](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1992) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 不适用           | 这是一个信息泄露漏洞。                                                                                                                     |  
| [MS11-099](http://go.microsoft.com/fwlink/?linkid=232505) | Internet Explorer 不安全库加载漏洞       | [CVE-2011-2019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2019) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不受影响                                                                                      | 不适用           | （无）                                                                                                                                     |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | HashTable 中的冲突可能导致 DoS 漏洞      | [CVE-2011-3414](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3414) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不太可能被利用的漏洞检测代码 | 临时             | 此漏洞只是一个拒绝服务漏洞，并且已公开披露。[拒绝服务漏洞的利用指数评级为“3”。](http://technet.microsoft.com/en-us/security/cc998259.aspx) |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | ASP.Net 表单身份验证绕过漏洞             | [CVE-2011-3416](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3416) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能被利用的漏洞检测代码     | 不适用           | 特权提升 - 帐户接管                                                                                                                        |  
| [MS11-100](http://go.microsoft.com/fwlink/?linkid=232432) | ASP.NET 表单身份验证票证缓存漏洞         | [CVE-2011-3417](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3417) | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | [2](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 漏洞检测代码会很难创建       | 不适用           | 特权提升 - 帐户接管                                                                                                                        |
  
受影响的软件和下载位置  
----------------------
  
<span></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果某个软件程序或者组件被列出，则可用的软件更新会被加上超链接，软件更新的严重等级也会被列出。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件
  
**表 1**

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="7" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b01bb041-005c-48c4-a606-66aa264ba0fa)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=21b4b999-2dbf-4921-80bd-cc7ab2cd1190)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d85091b5-69bb-4d0f-839a-a65cd94e2887)  
(KB2619339)  
（严重）  
[Windows XP Media Center Edition 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=03bc6446-7cf3-47c4-8ed1-a53a4d53a429)  
(KB2619340)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=73531165-f299-4b62-b738-52fca410eaae)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=3b816964-d3c3-4f05-94c3-f54a6f54ca73)  
(KB2626416)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=edb594a4-14d2-4ffe-8d1c-2c283689fe8c)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a872cd2-5f4d-400c-a1c4-a2d194746fb6)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=126e8092-980d-471a-867d-d5939671b7df)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7d1d1e9a-603c-4895-a69f-b61186a75ad5)  
(KB2619339)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a98bb7cf-9939-4927-8d21-ccb3845e7cb7)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=986f0087-c674-4060-8710-af3496adbfdd)  
(KB2626416)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9e1273e2-7775-40b4-b939-ab530677cd4a)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e84e6964-1580-41ef-9d3e-4d0c3ad4cb69)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dfb948c5-8aee-4bcd-babf-3564b78712dd)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6b555040-1117-4b06-a48c-02f0e1b686d8)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=01caf06f-777d-4ea8-95ca-e11d60a973ad)  
(KB2621146)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=6f7c7ccd-22a3-4fbc-bf21-bd0e42ab1da5)  
(KB2626416)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a14057e5-e2c2-4dde-8d26-542a9f162e98)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9d9f3667-3fd6-4948-83db-282783599f41)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2d37a8cb-2316-4db4-980c-11b6dcbdc696)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb17782c-f754-42ab-905b-6f141df008c3)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=e1ba50cf-fc6b-4668-b71c-e9f75a8ac638)  
(KB2621146)  
（重要）  
[Active Directory 应用程序模式 (ADAM)](https://www.microsoft.com/download/details.aspx?familyid=1b610eb3-456c-4125-94b7-1ead4face8e3)  
(KB2626416)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f595fd6-bdfd-4075-97e5-70efb7d49dff)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1ecf72cd-6732-4cf3-aa22-8caf15ea633e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7726ddbe-0578-44fb-a40f-49b804a45989)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4cdde8a9-6d44-41fa-82c0-a25404cdfbb5)  
（重要）
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=74099261-60ad-4c68-906c-60e131818955)  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=147ec6d3-3401-4aa3-a409-55346bcc7bd7)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7f69ec9d-43ad-4106-90ef-c191e7ec43af)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1dd069a2-fb1a-4f31-88cc-bc031c3e2c80)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e9130fad-de8c-4be0-aea1-62cbaa310b76)  
(KB2619339)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=470da512-2c8b-4ba9-b7bb-b9e6c45cd33f)  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fa6e6d91-4aca-49a6-a6e8-c33ec413097e)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ae1f1f86-6f13-4e1e-9f93-4f70b6c9927e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=60fd5bf6-e820-44f6-8081-b98c0103acc1)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b7c4bf05-eb2d-48ac-a6df-8afd88e811d8)  
(KB2619339)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=8daf9a49-60cb-4813-ac7a-e9a4bf296889)  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c9794756-803d-48ba-86db-350fb577f01b)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c4ba344d-dd0d-4cfb-81d9-d364d7f37e25)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f485d4c3-a4af-4ae6-9404-e79afcbb4f6e)\*\*  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=6f9ddcdb-a471-4e00-a697-92a24e4ea8d4)\*  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6f934885-b134-400c-a452-50fd4eeedd5e)\*  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=058963f6-9654-41d0-86d2-f25a0c2ad416)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=28598ef6-13fb-44fd-8c76-599af7b0a01d)\*\*  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=5253477b-422f-404a-941e-8b69da5a2670)\*  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7ade3832-bc20-4fce-8eac-8a3d072d2f1c)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42cd1c33-11a7-4a29-ae85-f7272a626f91)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5915e19c-b576-453b-b621-5737774f5955)  
（没有严重等级<sup>[1]</sup>）
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
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4bd7a02b-c6d8-4eb5-a46d-e494a1233dc8)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0526727a-f2fb-4846-9b04-f1899f52f1f6)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d112623c-86ce-434a-8fe1-ec3e3e632763)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b6e44069-dec5-48f6-8fc4-8ab375a10b4e)  
(KB2619339)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=d2e87199-6469-4bc0-a721-f43e817e4344)  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0666bdf5-9eed-44c9-84ee-b45f9b3e14b3)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=cfd42c42-1595-419a-bf04-b23b64663629)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=81114ecd-0c73-4ca6-8a66-09c6c636a5db)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f7997ab8-27e0-4714-845a-d237f4326587)  
(KB2619339)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=ba8d7aa9-8299-49a3-b0c0-b8b5eab48434)  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=620f94f9-1f61-45a0-a22e-e7510b56b9b8)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-087**](http://go.microsoft.com/fwlink/?linkid=233008)
</td>
<td style="border:1px solid black;">
[**MS11-090**](http://go.microsoft.com/fwlink/?linkid=232507)
</td>
<td style="border:1px solid black;">
[**MS11-092**](http://go.microsoft.com/fwlink/?linkid=232517)
</td>
<td style="border:1px solid black;">
[**MS11-093**](http://go.microsoft.com/fwlink/?linkid=232516)
</td>
<td style="border:1px solid black;">
[**MS11-095**](http://go.microsoft.com/fwlink/?linkid=232666)
</td>
<td style="border:1px solid black;">
[**MS11-097**](http://go.microsoft.com/fwlink/?linkid=232663)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d64a31ca-cccd-488a-98fd-c059b9e9e1ea)\*\*\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=bc018647-08cb-431a-8e7c-5dc04980eaa9)\*\*  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory 和 Active Directory 轻型目录服务 (AD LDS)](https://www.microsoft.com/download/details.aspx?familyid=a3e0d27c-8b29-4981-bdef-bcd037fd3408)\*  
(KB2621146)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=04878e9a-539a-4549-a5af-11d45add91da)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b46f6da7-6d24-4262-8e55-3b657db39813)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9323b9b9-e9b0-4941-afe0-196d22df9ab4)  
（没有严重等级<sup>[1]</sup>）
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
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=5b2ebec4-cebb-47b6-864a-12d59a9a3e18)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*\*\*服务器核心安装受到影响。**当使用服务器核心安装选项进行安装时，此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级较低。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS11-090 的注释**

<sup>[1]</sup>此特定操作系统不受本公告中介绍的漏洞影响。可用更新为第三方控件设置 kill bit。

**表 2**

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7a6fcf8d-8c7b-4882-90d3-02db79a75238)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=caa9360b-2fd8-4f46-99e6-2decf1b60ca7)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dc6dcd8c-c39f-4c4b-b5b2-b4c18c36973b)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f3906245-b6f6-464a-84b6-e1b6b195df95)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2fa77733-70f5-46ff-9cfe-2262d292b870)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a0c55d9b-8529-4d3d-910d-1a822a825be2)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3e60e996-8850-4d25-b994-39646e2cc25e)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重** **等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=281e5bd4-4582-4aa9-af88-518ad3152132)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=759041cf-fd8b-4e04-b289-d74112bf978b)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b1b4af92-3ff1-4727-9ba3-52764a7b81bb)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1cbe9469-05f4-4305-bbfd-76b4a04cd598)  
（低）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid%20=%207538762a-50e9-4f13-a60e-ff99aa8fbbf8)  
（KB2656358）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5587eca8-86e9-4a63-81cb-81f68178a6c0)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7a87f890-f106-41ab-bc53-4ca44dc99cb1)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a42fa727-482c-4578-9a30-61fdf14ed4da)  
（低）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=02d5c057-d551-411b-917b-43d7795111bc)  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2fccb214-6c79-4ef6-9d6e-df4f16ef792e)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eff633f7-abd9-45cc-acbd-4885123dbed2)  
(KB2656352)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6c7c960-768d-40d4-8fe5-7d59f48ead1d)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0adc422f-73f2-46ee-973f-9b7603a76d1e)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4327147b-0481-4172-a835-8786abc50596)  
（重要）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=a0b19b35-1d48-4419-ba3d-66063cc472a7)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid%20=%2049050cf2-949a-40e5-b2ee-6257a3837294)  
（KB2656362）  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8a3f2351-380b-4566-b186-906dca426d39)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=987f0966-01de-4edf-a0d6-4032d1d72966)  
（重要）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c951044b-4596-462f-bc8f-bdd9d6734297)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid%20=%2049050cf2-949a-40e5-b2ee-6257a3837294)  
（KB2656362）  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
[**低**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5a4443f8-fec8-42be-ad67-8475920f1460)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=eaf587f0-9951-4480-a08b-377e61aaf72b)\*\*  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8f5af52f-dece-4f0c-9fc0-d4973e4f7b1a)\*\*  
（低）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=c03e65d6-4f92-4bc1-94b5-2f0183d0133e)\*\*  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid%20=%2049050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
（KB2656362）  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2f18fc98-984a-4c02-951f-b8438a9e4f6b)\*\*  
（没有严重等级<sup>[1]</sup>）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=808d26f7-c8fa-446d-9d2f-e8c0babb0c4a)\*\*  
（低）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b7a582f3-0a18-4fbf-9b99-21c664bfd979)\*\*  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)\*\*  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid%20=%2049050cf2-949a-40e5-b2ee-6257a3837294)\*\*  
（KB2656362）  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)\*\*  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*\*<sup>[1]</sup>  
(KB2656351)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fc62df39-7185-448b-b356-25a5a07886ec)  
（没有严重等级<sup>[1]</sup>）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=471e1f51-c79c-4285-9f1e-aee1e4c4f189)  
(KB2656353)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid%20=%2049050cf2-949a-40e5-b2ee-6257a3837294)  
（KB2656362）  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=306acd0a-bea2-40dd-a639-f381587c9eb7)  
(KB2657424)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=eb2bd108-5ef1-45be-9157-e7cbfc8afd2a)  
（重要）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=018610bb-e80a-432a-8f32-f50451f71ad9)  
（重要）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=ec2046a6-f069-4f02-9600-7640e57be0a3)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于 32 位系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%202de28d32-1efd-4177-82e6-19a08266096c)  
（KB2656355）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)  
仅限 Windows 7（用于 32 位系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%2026e0b56d-9228-49cf-9276-0741257567a9)  
（KB2656356）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=dbe85b05-e252-4029-8e25-f2452db1c017)  
（重要）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=4c773b3d-0ca3-4b9b-af9a-9d6edcd261f7)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows 7（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%202de28d32-1efd-4177-82e6-19a08266096c)  
（KB2656355）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)  
仅限 Windows 7（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%2026e0b56d-9228-49cf-9276-0741257567a9)  
（KB2656356）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-098**](http://go.microsoft.com/fwlink/?linkid=232424)
</td>
<td style="border:1px solid black;">
[**MS11-099**](http://go.microsoft.com/fwlink/?linkid=232505)
</td>
<td style="border:1px solid black;">
[**MS11-100**](http://go.microsoft.com/fwlink/?linkid=232432)
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
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2108b4ef-942f-4727-a1fc-ee7d0abb427c)\*\*  
（低）  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=72c1654e-526f-4ece-b7ad-767a0710e076)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 x64 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%202de28d32-1efd-4177-82e6-19a08266096c)\*  
（KB2656355）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)  
仅限 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%2026e0b56d-9228-49cf-9276-0741257567a9)\*  
（KB2656356）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)\*<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=74614510-e13c-43e8-90e7-d81e63895cf2)  
（低）
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%202de28d32-1efd-4177-82e6-19a08266096c)  
（KB2656355）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)  
仅限 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1：  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid%20=%2026e0b56d-9228-49cf-9276-0741257567a9)  
（KB2656356）  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=37a8fb34-e3ad-4605-980b-28361889ce72)<sup>[1]</sup>  
(KB2656351)
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。**此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。**如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS11-099 的注释**

<sup>[1]</sup>严重等级不适用于指定软件的此更新，因为本公告中讨论的漏洞的已知攻击媒介已在默认配置中阻止。然而，作为一种纵深防御措施，Microsoft 建议这款软件的客户应用此安全更新。

**MS11-100 注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx)”。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="6" style="border:1px solid black;">
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=13f3e884-37bf-4ed2-b3ed-a0e7fb48e44f)  
(KB2553084)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/4downloads/details.aspx?familyid%20=%205859014f-afc5-4958-82ea-6ba45a5ad4b3)  
(KB2596954)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2 和 Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2 和 Microsoft Office 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e924cd85-5764-4056-bd32-b0e57dc25146)  
(KB2596785)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 Service Pack 2 和 Microsoft Publisher 2007 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2856821e-f1fd-424b-b03c-e443685eea6d)  
(KB2596705)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d0c3156c-c87c-4d3e-aca2-3fab9ff78711)  
(KB2596764)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=d812621e-c35a-4cb0-ba26-928363f3422d)  
(KB2596511)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=e47c0694-a9a5-4dd7-bfba-e470d9855c28)  
(KB2589320)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=fd32d083-46e7-4835-ba83-c33332b920bd)  
(KB2553185)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Pinyin IME 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=c8d3ac17-5aca-4da3-961f-b753be4a3634)  
(KB2596511)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 和 Microsoft Office 2010 Service Pack 1（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=6c2d5273-eef9-4ff6-be6f-8d86f417f004)  
(KB2589320)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=f28b8cf6-8946-448a-ae4e-d11f8a76a679)  
(KB2553185)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Microsoft Office 2004 for Mac
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=ef3b559c-0bd2-45dd-8049-6946f6431a2a)  
(KB2644358)  
（重要）
</td>
</tr>
<tr class="alternateRow">
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=2c4d0381-f7ab-49ed-a0c0-b381387d1e68)  
(KB2644354)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/details.aspx?familyid=3c8017d6-232c-42a6-a133-96efe3ad3385)  
(KB2644347)  
（重要）
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
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-088**](http://go.microsoft.com/fwlink/?linkid=227070)
</td>
<td style="border:1px solid black;">
[**MS11-089**](http://go.microsoft.com/fwlink/?linkid=225739)
</td>
<td style="border:1px solid black;">
[**MS11-091**](http://go.microsoft.com/fwlink/?linkid=235287)
</td>
<td style="border:1px solid black;">
[**MS11-094**](http://go.microsoft.com/fwlink/?linkid=232493)
</td>
<td style="border:1px solid black;">
[**MS11-096**](http://go.microsoft.com/fwlink/?linkid=232696)
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
<td style="border:1px solid black;">
无
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
Microsoft PowerPoint Viewer 2007 Service Pack 2
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
[Microsoft PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4417592a-8db0-4e35-9895-d589bc341077)  
(KB2596912)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包
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
[用于 Word、Excel 和 PowerPoint 2007 文件格式 Service Pack 2 的 Microsoft Office 兼容包](https://www.microsoft.com/download/details.aspx?familyid=e799f654-7e2d-40c7-a3b8-32e44d1aa6ee)  
(KB2596843)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010（32 位版本）<sup>[1]</sup>  
（重要）
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
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010（64 位版本）<sup>[1]</sup>  
（重要）
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
不适用
</td>
</tr>
</table>

**MS11-088 的注释**

<sup>[1]</sup>不再支持此版本的 Microsoft Office Pinyin。

检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)
-   ： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](http://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](http://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)
-   提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)
-   提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](http://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](http://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](http://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   Symantec 和 Laboratory of Cryptography and System Security (CrySyS) 与我们一起努力处理了 MS11-087 中描述的一个问题
-   Yang Yanbei 报告了 MS11-088 中描述的一个问题
-   Nikita Tarakanov (CISS Research Team) 和 Alexey Sintsov (Digital Security Research Group) 与 [TippingPoint's](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS11-089 中描述的一个问题
-   一位匿名研究员与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 MS11-090 中描述的一个问题
-   [CERT/CC](http://www.cert.org/)
-   的 Will Dormann 报告了 MS11-091 中描述的三个问题
-   一位匿名研究员与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 MS11-092 中描述的一个问题
-   一位匿名研究员与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 MS11-093 中描述的一个问题
-   [iSIGHT Partners Labs](http://www.isightpartners.com/)
-   的 Greg MacManus 报告了 MS11-094 中描述的一个问题
-   一位匿名研究员与 [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) 合作报告了 MS11-094 中描述的一个问题
-   一位匿名研究员与 [VeriSign iDefense Labs](http://labs.idefense.com) 合作报告了 MS11-096 中描述的一个问题
-   Winsider Seminars & Solutions Inc. 的 Alex Ionescu 报告了 MS11-097 中描述的一个问题
-   Matthew Jurczyk 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 合作报告了 MS11-098 中描述的一个问题
-   Thomas Stehle 报告了 MS11-099 中描述的一个问题
-   [Citrix Security Team](http://www.citrix.com)
-   的 Andy Cooper 报告了 MS11-099 中描述的一个问题
-   [Google Inc.](http://www.google.com/)
-   的
-   [Robert Swiecki](http://www.swiecki.net/)
-   报告了 MS11-099 中描述的一个问题
-   [Yosuke Hasegawa](http://utf-8.jp/)
-   与我合作处理了 MS11-099 中描述的一个问题
-   [Jan Schejbal](http://janschejbal.wordpress.com/)
-   与我们合作处理了 MS11-099 中包括的纵深防御更改。
-   [Seeker](http://www.seekersec.com)
-   的 Irene Abezgauz 报告了 MS11-100 中描述的问题
-   [SEC Consult](https://www.sec-consult.com/)
-   的 Kestutis Gudinavicius 报告了 MS11-100 中描述的问题。
-   [LBi](http://www.lbi.com/)
-   的 Oliver Dewdney 报告了 MS11-100 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY (1-866-727-2338) 获得技术支持。与安全更新有关的电话支持服务是免费的。有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。与安全更新有关的支持服务不收取任何费用。有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2011 年 12 月 13 日）： 已发布公告摘要。
-   V1.1（2011 年 12 月 13 日）： 对于 MS11-099，更正了“受影响的软件”表中的严重等级。对于 MS11-088，更正了“利用指数”中的重要注释。这些只是信息更改。没有更改安全更新文件或检测逻辑。
-   V2.0（2011 年 12 月 29 日）： 添加了 Microsoft 安全公告 MS11-100：.NET Framework 中的漏洞可能允许特权提升 (2638420).还添加了此额外安全公告的公告网络广播链接。
-   V2.1（2012 年 2 月 22 日）： 对于 MS11-088，阐明了 Microsoft Office Pinyin SimpleFast Style 2010 和 Microsoft Office Pinyin New Experience Style 2010 的产品支持状态。不再支持 Microsoft Office Pinyin 的这些版本。有关详细信息，请参阅公告。

*Built at 2014-04-18T01:50:00Z-07:00*
