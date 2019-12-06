---
TOCTitle: 'MS09-AUG'
Title: 'Microsoft 安全公告摘要 (2009 年 8 月)'
ms:assetid: 'ms09-aug'
ms:contentKeyID: 61236928
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 8 月)
=====================================

发布时间: 2009年8月11日

**版本:** 1.0

本公告摘要列出了 2009 年 8 月发布的安全公告。

对于 2009 年 8 月发布的安全公告，本公告摘要替代 2009 年 8 月 6 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 8 月 12 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 8 月份安全公告网络广播](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-043">MS09-043</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (957638)</strong><br />
<br />
此安全更新解决了 Microsoft Office Web 组件中几个秘密报告的漏洞，如果用户查看特制的网页，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft Visual Studio、Microsoft ISA Server、Microsoft BizTalk Server</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-044">MS09-044</a></td>
<td style="border:1px solid black;"><strong>远程桌面连接中的漏洞可能允许远程执行代码 (970927)</strong><br />
<br />
此安全更新可解决 Microsoft 远程桌面连接中两个秘密报告的漏洞。 如果攻击者成功说服一位终端服务用户连接到恶意 RDP 服务器，或者用户访问利用此漏洞的特制网站，该漏洞可以允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、用于 Mac 的远程桌面连接客户端</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-039">MS09-039</a></td>
<td style="border:1px solid black;"><strong>WINS 中的漏洞可能允许远程执行代码 (969883)</strong><br />
<br />
此安全更新可解决 Windows Internet 名称服务 (WINS) 中两个秘密报告的漏洞。 如果用户在运行 WINS 服务的受影响系统上收到特制的 WINS 复制数据包，则这些漏洞可能允许远程执行代码。 默认情况下，WINS 不会安装在任何受影响的操作系统版本上。 仅手动安装此组件的客户可能受到此问题的影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-038">MS09-038</a></td>
<td style="border:1px solid black;"><strong>Windows Media 文件处理中的漏洞可能允许远程执行代码 (971557)</strong><br />
<br />
此安全更新可解决 Windows Media 文件处理中两个秘密报告的漏洞。 如果用户打开特制 AVI 文件，这两个漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-037">MS09-037</a></td>
<td style="border:1px solid black;"><strong>Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)</strong><br />
<br />
此安全更新可解决 Microsoft 活动模板库 (ATL) 中许多秘密报告的漏洞。 如果用户加载了恶意网站上的特制组件或控件，这些漏洞可以允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-041">MS09-041</a></td>
<td style="border:1px solid black;"><strong>工作站服务中的漏洞可能允许特权提升 (971657)</strong><br />
<br />
此安全更新解决工作站服务中一个秘密报告的漏洞。 如果攻击者创建特制的 RPC 消息并向受影响的系统发送此消息，此漏洞可能允许特权提升。 成功利用此漏洞的攻击者可执行任意代码，并可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 攻击者必须拥有对易受攻击的系统的有效登录凭据才能利用此漏洞。 匿名用户无法利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-040">MS09-040</a></td>
<td style="border:1px solid black;"><strong>服务器队列中的漏洞可能允许特权提升 (971032)</strong><br />
<br />
此安全更新解决了 Windows 消息队列服务 (MSMQ) 中一个秘密报告的漏洞。 如果用户收到对受影响的 MSMQ 服务的特制请求，则该漏洞可能允许特权提升。 默认情况下，消息队列组件不安装在任何受影响的操作系统版本上，而仅由具有管理特权的用户启用。 只有手动安装“消息队列服务”组件的客户才可能受此问题的影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-036">MS09-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的 ASP.NET 中的漏洞可能允许拒绝服务 (970957)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 的 Microsoft .NET Framework 组件中的一个秘密报告的拒绝服务漏洞。 只有在受影响的 Microsoft Windows 版本上安装了 Internet Information Services (IIS) 7.0，且 ASP.NET 配置为使用集成模式时，此漏洞才会被利用。 攻击者可以创建特制的匿名 HTTP 请求，可能导致受影响的 Web 服务器无响应，直到相关的应用程序池重新启动。 在经典模式中运行 IIS 7.0 应用程序池的客户不受此漏洞的影响。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-042">MS09-042</a></td>
<td style="border:1px solid black;"><strong>Telnet 中的漏洞可能允许远程执行代码 (960859)</strong><br />
<br />
此安全更新解决了 Microsoft Telnet 服务中一个公开披露的漏洞。 漏洞可能使攻击者获得凭据，然后用来登录回受影响的系统。 然后攻击者就获得了与登录用户的权限相同的系统用户权限。 这种情形最终可能导致在受影响的系统上远程执行代码。 成功利用此漏洞的攻击者可以安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
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
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 公告标题                                                              | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                                                                                                                                                                                              |  
|---------------------------------------------------------------------|-----------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-036](http://technet.microsoft.com/security/bulletin/ms09-036) | Microsoft Windows 中的 ASP.NET 中的漏洞可能允许拒绝服务 (970957)      | [CVE-2009-1536](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 拒绝服务工具有可能实现。 但是，远程执行代码的功能漏洞检测代码不太可能实现。                                                                                                                               |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)      | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | **此漏洞当前正在 Internet 生态系统中被利用。**                                                                                                                                                            |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)      | [CVE-2008-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)      | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | 无                                                                                                | （[7 月安全公告摘要](http://technet.microsoft.com/security/bulletin/ms09-jul)中已经为此漏洞提供了利用指数评估。 这是因为此漏洞在 [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) 中最先解决。） |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)      | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 无                                                                                                | （[7 月安全公告摘要](http://technet.microsoft.com/security/bulletin/ms09-jul)中已经为此漏洞提供了利用指数评估。 这是因为此漏洞在 [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) 中最先解决。） |  
| [MS09-037](http://technet.microsoft.com/security/bulletin/ms09-037) | Microsoft 活动模板库 (ATL) 中的漏洞可能允许远程执行代码 (973908)      | [CVE-2009-2494](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-038](http://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 文件处理中的漏洞可能允许远程执行代码 (971557)           | [CVE-2009-1545](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                    |  
| [MS09-038](http://technet.microsoft.com/security/bulletin/ms09-038) | Windows Media 文件处理中的漏洞可能允许远程执行代码 (971557)           | [CVE-2009-1546](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                    |  
| [MS09-039](http://technet.microsoft.com/security/bulletin/ms09-039) | WINS 中的漏洞可能允许远程执行代码 (969883)                            | [CVE-2009-1923](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-039](http://technet.microsoft.com/security/bulletin/ms09-039) | WINS 中的漏洞可能允许远程执行代码 (969883)                            | [CVE-2009-1924](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 针对 Windows 2000 目标的攻击很有可能成功。                                                                                                                                                                |  
| [MS09-040](http://technet.microsoft.com/security/bulletin/ms09-040) | 服务器队列中的漏洞可能允许特权提升 (971032)                           | [CVE-2009-1922](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 对此漏洞的远程攻击不是可能实现。                                                                                                                                                                          |  
| [MS09-041](http://technet.microsoft.com/security/bulletin/ms09-041) | Workstation 服务中的漏洞可能允许特权提升 (971657)                     | [CVE-2009-1544](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 攻击者需要身份验证才能利用此漏洞。                                                                                                                                                                        |  
| [MS09-042](http://technet.microsoft.com/security/bulletin/ms09-042) | Telnet 中的漏洞可能允许远程执行代码 (960859)                          | [CVE-2009-1930](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 此漏洞类似于以前漏洞检测代码已存在的 NTLM 凭据反射漏洞。                                                                                                                                                  |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (957638) | [CVE-2009-0562](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (957638) | [CVE-2009-1136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 此漏洞的漏洞检测代码公开发布。                                                                                                                                                                            |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (957638) | [CVE-2009-1534](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-043](http://technet.microsoft.com/security/bulletin/ms09-043) | Microsoft Office Web Components 中的漏洞可能允许远程执行代码 (957638) | [CVE-2009-2496](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |  
| [MS09-044](http://technet.microsoft.com/security/bulletin/ms09-044) | 远程桌面连接中的漏洞可能允许远程执行代码 (970927)                     | [CVE-2009-1133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                    |  
| [MS09-044](http://technet.microsoft.com/security/bulletin/ms09-044) | 远程桌面连接中的漏洞可能允许远程执行代码 (970927)                     | [CVE-2009-1929](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                    |
  
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
<th colspan="9" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[RDP 版本 5.0](https://www.microsoft.com/download/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864)\*\*\*  
(KB958471) 和 [RDP 版本 5.0](https://www.microsoft.com/download/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864) (KB958470)  
（严重）  
[RDP 版本 5.1](https://www.microsoft.com/download/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
（严重）  
[RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2)\*\*\*\*  
(KB958470)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2)  
(KB973354)  
（严重）  
[Microsoft Outlook Express 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f340af34-b9a0-44fb-b595-dbb346c727bf)  
(KB973354)  
（严重）  
[Windows Media Player 9](https://www.microsoft.com/download/details.aspx?familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c)  
(KB973354)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0)  
(KB973869)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=240977d6-3581-4058-b9f1-7847e4edcf8a)  
（重要）
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上的 RDP 版本 5.1](https://www.microsoft.com/download/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)  
(KB958470)  
（严重）  
[Windows XP Service Pack 2 上的 RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f)\*\*\*\*  
(KB958470)  
（严重）  
[Windows XP Service Pack 2 上的 RDP 版本 6.0](https://www.microsoft.com/download/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
（重要）  
[Windows XP Service Pack 2 上的 RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719)\*\*\*\*  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=c67b5506-00ea-47cc-a0e8-897057b7380c)  
(KB973354)  
（严重）  
[Windows Media Player 9、Windows Media Player 10 和 Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=34b2b14d-5811-4635-ba83-f837dcb03d04)  
(KB973540)  
（严重）  
（仅限 Windows XP Service Pack 2）  
[Windows Media Player 9、Windows Media Player 10 和 Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f)  
(KB973540)  
（严重）  
（仅限 Windows XP Service Pack 3）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592)  
(KB973869  
（严重）  
[Microsoft MSWebDVD ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36)  
(KB973769)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b3331388-1e52-4924-b512-23275a8fde84)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2 上的 RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda)  
(KB958469)  
（重要）  
[Windows XP Professional x64 Edition Service Pack 2 上的 RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b)\*\*\*\*  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da)  
(KB973354)  
（严重）  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6)  
(KB973540)  
（严重）  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467)  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99)  
(KB973869  
（严重）  
[Microsoft MSWebDVD ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade)  
(KB973769)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4)  
（重要）
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
（严重）  
[RDP 版本 6.0](https://www.microsoft.com/download/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=3119ab1e-6729-40a1-b28f-0dab50502be6)  
(KB973354)  
（严重）  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=ab054890-983b-4414-ad0a-da1b2d2a4895)  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561)  
(KB973869  
（严重）  
[Microsoft MSWebDVD ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=301ad191-8d3f-41d3-b41c-e2e863893f73)  
(KB973769)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b)  
(KB958469)  
（严重）  
[RDP 版本 6.0](https://www.microsoft.com/download/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59)\*\*\*\*  
(KB956744)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e)  
(KB973354)  
（严重）  
[Windows Media Player 10](https://www.microsoft.com/download/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991)  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa)  
(KB973869  
（严重）  
[Microsoft MSWebDVD ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc)  
(KB973769)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[RDP 版本 5.2](https://www.microsoft.com/download/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028)  
(KB958469)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](https://www.microsoft.com/download/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9)  
(KB973354)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be)  
(KB973507)  
（严重）  
[DHTML 编辑组件 ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac)  
(KB973869  
（严重）  
[Microsoft MSWebDVD ActiveX 控件](https://www.microsoft.com/download/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218)  
(KB973769)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d)  
（重要）
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista 上的 RDP 版本 6.0](https://www.microsoft.com/download/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea)  
(KB956744)  
（重要）  
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2 上的 RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088)  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3)  
(KB973507)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Vista](https://www.microsoft.com/download/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Vista： [Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
（重要）  
仅限 Windows Vista Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f)\*\*\*\*\* (KB972594)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d77f406d-11cb-4d19-94ec-938b356c3427)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 上的 RDP 版本 6.0](https://www.microsoft.com/download/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
（重要）  
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2 上的 RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad)  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd)  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294)  
(KB973507)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86)  
（重要）
</td>
<td style="border:1px solid black;">
仅限 Windows Vista x64 Edition： [Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff) (KB972591) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e)\*\*\*\*\* (KB972592)  
（重要）  
仅限 Windows Vista x64 Edition Service Pack 1：  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7a41b8c1-f955-474e-a08e-5e73964327d1)  
（中等）
</td>
</tr>
<tr>
<th colspan="9" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
</td>
<td style="border:1px solid black;">
[**MS09-039**](http://technet.microsoft.com/security/bulletin/ms09-039)
</td>
<td style="border:1px solid black;">
[**MS09-038**](http://technet.microsoft.com/security/bulletin/ms09-038)
</td>
<td style="border:1px solid black;">
[**MS09-037**](http://technet.microsoft.com/security/bulletin/ms09-037)
</td>
<td style="border:1px solid black;">
[**MS09-041**](http://technet.microsoft.com/security/bulletin/ms09-041)
</td>
<td style="border:1px solid black;">
[**MS09-040**](http://technet.microsoft.com/security/bulletin/ms09-040)
</td>
<td style="border:1px solid black;">
[**MS09-036**](http://technet.microsoft.com/security/bulletin/ms09-036)
</td>
<td style="border:1px solid black;">
[**MS09-042**](http://technet.microsoft.com/security/bulletin/ms09-042)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a)\*\*  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4)\*\*  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc)\*  
(KB973507)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913)\*  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于 32 位系统）： [Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e)\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261)\*\*  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0)\*\*  
(KB973540)  
（严重）  
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd)\*  
(KB973507)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93)\*  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于基于 x64 的系统）： [Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e5d1db9-efef-4112-8138-62f14670cf0d)\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[RDP 版本 6.1](https://www.microsoft.com/download/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8)  
(KB956744)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows ATL 组件](https://www.microsoft.com/download/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c)  
(KB973507)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
仅限 Windows Server 2008（用于基于 Itanium 的系统）： [Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd) (KB972593) 以及 [Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f) (KB972594)  
（重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d)  
（中等）
</td>
</tr>
</table>

**Windows Server 2008 的注释**

**\*Windows Server 2008 服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 的受支持版本，严重等级相同，无论安装 Windows Server 2008 时是否使用“服务器核心”安装选项。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*Windows Server 2008 服务器核心安装不受影响。** 如果安装 Windows Server 2008 时使用“服务器核心”安装选项，则此更新所解决的漏洞不会影响 Windows Server 2008 的受支持版本。 有关该安装选项的详细信息，请参阅[服务器核心](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)。 注意，“服务器核心”安装选项不适用于某些 Windows Server 2008 版本；请参阅[比较“服务器核心”安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS09-044 注释**

\*\*\*Microsoft Windows 2000 Service Pack 4 的客户在安装 KB958470 之前必须安装 KB958471。

\*\*\*\*管理员可能已经手动安装了此额外更新。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的“Mac 客户端软件”小节。 此公告涉及多个软件类别。

**MS09-036 注释**

\*\*\*\*\*由于 IIS 7.0 不在 Windows Vista Starter 和 Windows Vista Home Basic 上运行，因此以下版本不受影响： Windows Vista Starter（32 位）、Windows Vista Home Basic（32 位）和 Windows Vista Home Basic（64 位）。

#### Mac 客户端软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
远程桌面
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-044**](http://technet.microsoft.com/security/bulletin/ms09-044)
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
Mac 远程桌面连接客户端
</td>
<td style="border:1px solid black;">
[用于 Mac 2.0.1 的远程桌面连接客户端](https://www.microsoft.com/download/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871)\*  
（重要）
</td>
</tr>
</table>

**MS09-044 注释**

\*管理员可能已经手动安装了此额外更新。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的“Windows 操作系统和组件”小节。 此公告涉及多个软件类别。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 套件、系统和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Office Web 组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
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
Microsoft Office 2000 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2000 Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580)  
(KB947320)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Web Components
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web Components Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7)  
(KB947319)  
（严重）  
[Microsoft Office 2003 Web Components Service Pack 1 for the 2007 Microsoft Office System](https://www.microsoft.com/download/details.aspx?familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be)\*  
(KB947318)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Small Business Accounting 2006
</td>
<td style="border:1px solid black;">
[Microsoft Office Small Business Accounting 2006](https://www.microsoft.com/download/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82)  
(KB968377)  
（严重）
</td>
</tr>
</table>

**MS09-043 注释**

\*SQL Server 2008 和 Microsoft Forefront Threat Management Gateway Medium Business Edition 重新发布受影响的组件 Office 2003 Web Components for the 2007 Microsoft Office System。 Office 2003 Web Components for the 2007 Microsoft Office System 组件的更新检测 SQL Server 2008 和 Microsoft Forefront Threat Management Gateway Medium Business Edition 并将向客户提供更新。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他小节。 此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
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
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585)  
(KB969172)  
（严重）
</td>
</tr>
</table>

**MS09-043 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他小节。 此公告涉及多个软件类别。

#### Microsoft 服务器和安全软件

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th>
</th>
<th>
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
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
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)\*  
(KB947826)  
（严重）  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006 Standard Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
（严重）  
[Microsoft Internet Security and Acceleration Server 2006 Enterprise Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326)  
(KB947826)  
（严重）
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft BizTalk Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-043**](http://technet.microsoft.com/security/bulletin/ms09-043)
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
Microsoft BizTalk Server 2002
</td>
<td style="border:1px solid black;">
[Microsoft BizTalk Server 2002](https://www.microsoft.com/download/details.aspx?familyid=495839b6-0322-4755-997d-4a7762c53333)  
(KB971388)  
（严重）
</td>
</tr>
</table>

**MS09-043 注释**

\*Microsoft ISA Server 2004 Standard Edition 作为独立产品交付。 Microsoft ISA Server 2004 Standard Edition 还作为 Windows Small Business Server 2003 Premium Edition Service Pack 1 和 Windows Small Business Server 2003 R2 Premium Edition 的组件交付。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他小节。 此公告涉及多个软件类别。

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

通过使用 Windows Server Update Services (WSUS)，管理员可以快速而可靠地将 Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**Systems Management Server**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；另请参阅 [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)。有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用安全更新清单工具 (SUIT) 来帮助部署安全更新。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://go.microsoft.com/fwlink/?linkid=33387)和 [SMS 2.0 管理功能包](http://go.microsoft.com/fwlink/?linkid=21161)中提供）来安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全、高优先级更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](http://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [Microsoft Windows 之外的其他 Microsoft 产品的新更新、经过修订的更新以及已发布的更新](http://technet.microsoft.com/en-us/wsus/dd573344.aspx)。

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

-   [IBM ISS X-Force](http://www.iss.net/) 的 Ryan Smith 和 Alex Wheeler 最初报告了 MS09-037 中描述的问题
-   [IBM ISS X-Force](http://www.iss.net/) 的 Robert Freeman 报告了 MS09-037 中描述的问题
-   [IBM ISS X-Force](http://www.iss.net/) 的 David Dewey 报告了 MS09-037 中描述的问题
-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Ryan Smith 报告了 MS09-037 中描述的两个问题
-   [Adobe Systems, Inc.](http://www.adobe.com/) 的 Vinay Anantharaman 报告了 MS09-038 中描述的两个问题
-   [TippingPoint](http://www.tippingpoint.com/) 和 [Zero Day Initiative](http://www.zerodayinitiative.com/) 报告了 MS09-039 中描述的问题
-   [National University of Defense Technology](http://english.nudt.edu.cn/) 的 LiGen 报告了 MS09-039 中描述的问题
-   [Positive Technologies Research Team](http://en.securitylab.ru/lab/) 的 Nikita Tarakanov 报告了 MS09-040 中描述的问题
-   [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) 的 Cody Pierce 报告了 MS09-041 中描述的问题
-   [@stake](http://www.xxxx.xxx/) 的 DilDog 报告了 MS09-042 中描述的问题
-   Beau Butler 报告了 MS09-042 中描述的问题
-   [Zero Day Initiative](http://www.zerodayinitiative.com/)的 Peter Vreugdenhil 报告了 MS09-043 中描述的两个问题
-   [Zero Day Initiative](http://www.zerodayinitiative.com/) 的 Peter Vreugdenhil 和 Fortinet 的 [FortiGuard 全球安全研究小组](http://www.fortiguardcenter.com/)的 Haifei Li 报告了 MS09-043 中描述的问题
-   [VeriSign iDefense Labs](http://labs.idefense.com/) 的 Sean Larsson 报告了 MS09-043 中描述的问题
-   [Team509](http://www.team509.com/) 的 Wushi 与 Zero Day Initiative 合作，报告了 MS09-044 中描述的问题
-   Yamata Li 报告了 MS09-044 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/default.aspx?ln=zh-cn)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 8 月 11 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
