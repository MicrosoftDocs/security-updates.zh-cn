---
TOCTitle: 'MS10-DEC'
Title: 'Microsoft 安全公告摘要 (2010 年 12 月)'
ms:assetid: 'ms10-dec'
ms:contentKeyID: 61236941
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-dec(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 12 月)
======================================

发布时间: 2010年12月14日 | 更新时间: 2010年12月15日

**版本:** 1.1

本公告摘要列出了 2010 年 12 月发布的安全公告。

对于 2010 年 12 月发布的安全公告，本公告摘要替代 2010 年 12 月 9 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 12 月 15 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 12 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-090">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2416400)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中四个秘密报告的漏洞和三个公开披露的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-091">MS10-091</a></td>
<td style="border:1px solid black;"><strong>OpenType 字体 (OTF) 驱动程序中的漏洞可能允许远程执行代码 (2296199)</strong><br />
<br />
此安全更新可解决 Windows OpenType 字体 (OTF) 驱动程序中许多秘密报告的漏洞，此漏洞可能允许远程执行代码。 攻击者可能会将特制 OpenType 字体放在网络共享上。 当用户导航到 Windows 资源管理器中的共享时，受影响的控制路径将会触发，从而允许特制字体完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td style="border:1px solid black;"><strong>任务计划程序中的漏洞可能允许特权提升 (2305420)</strong><br />
<br />
此安全更新可解决 Windows 任务计划程序中一个公开披露的漏洞。 如果攻击者登录受影响的系统并运行特制应用程序，此漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-093">MS10-093</a></td>
<td style="border:1px solid black;"><strong>Windows Movie Maker 中的漏洞可能允许远程执行代码 (2424434)</strong><br />
<br />
此安全更新可解决 Windows Movie Maker 中一个公开披露的漏洞。 如果攻击者诱使用户打开与特制库文件位于同一网络目录下的合法 Windows Movie Maker 文件，此漏洞可能允许远程执行代码。 要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-094">MS10-094</a></td>
<td style="border:1px solid black;"><strong>Windows Media Encoder 中的漏洞可能允许远程执行代码 (2447961)</strong><br />
<br />
此安全更新可解决 Windows Media Encoder 中一个公开披露的漏洞。 如果攻击者诱使用户打开与特制库文件位于同一网络目录下的合法 Windows 媒体配置文件 (.prx) 文件，此漏洞可能允许远程执行代码。 要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-095">MS10-095</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 中的漏洞可能允许远程执行代码 (2385678)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。 如果用户打开与特制库文件位于同一网络文件夹下的文件类型（例如 .eml 和 .rss (Windows Live Mail) 或 .wpost (Microsoft Live Writer)），此漏洞可能允许远程执行代码。 要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-096">MS10-096</a></td>
<td style="border:1px solid black;"><strong>Windows 通讯簿中的漏洞可能允许远程执行代码 (2423089)</strong><br />
<br />
此安全更新可解决 Windows 通讯簿中一个公开披露的漏洞。 如果用户打开与特制库文件位于同一网络文件夹下的 Windows 通讯簿文件，此漏洞可能允许远程执行代码。 要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-097">MS10-097</a></td>
<td style="border:1px solid black;"><strong>Internet 连接注册向导中的库加载不安全可能允许远程执行代码 (2443105)</strong><br />
<br />  
此安全更新可解决 Microsoft Windows 的 Internet 连接注册向导中一个公开披露的漏洞。 对于 Windows XP 和 Windows Server 2003 的所有受支持版本，此安全更新等级为“重要”。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 的所有受支持版本不受此漏洞影响。<br />  
<br />
如果用户打开与特制库文件位于同一网络文件夹下的 .ins 或 .isp 文件，此漏洞可能允许远程执行代码。 要成功进行攻击，用户必须访问不受信任的远程文件系统位置或 WebDAV 共享，并从该位置打开文档，然后由容易受攻击的应用程序加载此文档。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-098">MS10-098</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (2436673)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞和若干个秘密报告的漏洞。 如果攻击者本地登录并运行特制应用程序，这些漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-099">MS10-099</a></td>
<td style="border:1px solid black;"><strong>路由和远程访问中的漏洞可能允许特权提升 (2440591)</strong><br />
<br />  
此安全更新可解决 Microsoft Windows 的路由和远程访问 NDProxy 组件中一个秘密报告的漏洞。 对于 Windows XP 和 Windows Server 2003 的所有受支持版本，此安全更新等级为“重要”。Windows Vista、Windows Server 2008、Windows 7 和 Windows Server 2008 R2 的所有受支持版本不受此漏洞影响。<br />  
<br />
如果攻击者登录受影响的系统并运行特制应用程序，此漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-100">MS10-100</a></td>
<td style="border:1px solid black;"><strong>Consent 用户界面中的漏洞可能允许特权提升 (2442962)</strong><br />
<br />
此安全更新可解决 Consent 用户界面 (UI) 中一个秘密报告的漏洞。 如果攻击者在受影响的系统上运行特制的应用程序，此漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据和 SeImpersonatePrivilege 并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-101">MS10-101</a></td>
<td style="border:1px solid black;"><strong>Windows Netlogon 服务中的漏洞可能允许拒绝服务 (2207559)</strong><br />
<br />
此安全更新可解决受影响的 Windows Server 版本（它们被配置为用作域控制器）上的 Netlogon RPC 服务中一个秘密报告的漏洞。 如果攻击者向受影响系统上的 Netlogon RPC 服务接口发送特制的 RPC 数据包，此漏洞可能允许拒绝服务。 攻击者需要加入到与受影响域控制器相同的域中的计算机的管理员权限才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-102">MS10-102</a></td>
<td style="border:1px solid black;"><strong>Hyper-V 中的漏洞可能允许拒绝服务 (2345316)</strong><br />
<br />
此安全更新可解决 Windows Server 2008 Hyper-V 和 Windows Server 2008 R2 Hyper-V 中一个秘密报告的漏洞。 如果经身份验证的用户在由 Hyper-V 服务器托管的客户虚拟机上将特制数据包发送给 VMBus，则该漏洞可能允许拒绝服务。 攻击者必须拥有有效的登录凭据并能从客户虚拟机发送特制的内容才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-103">MS10-103</a></td>
<td style="border:1px solid black;"><strong>Microsoft Publisher 中的漏洞可能允许远程执行代码 (2292970)</strong><br />
<br />
此安全更新可解决 Microsoft Publisher 中五个秘密报告的漏洞，如果用户打开特制的 Publisher 文件，该漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-104">MS10-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint 中的漏洞可能允许远程执行代码 (2455005)</strong><br />
<br />
此安全更新可解决 Microsoft SharePoint 中一个秘密报告的漏洞。 如果攻击者向使用文档转换负载平衡器服务的 SharePoint 服务器环境中的文档转换启动器服务发送特制 SOAP 请求，则此漏洞可能允许在来宾用户的安全上下文中远程执行代码。 默认情况下，Microsoft Office SharePoint Server 2007 中不启用文档转换负载平衡器服务和文档转换启动器服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-105">MS10-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 图形筛选器中的漏洞可能允许远程执行代码 (968095)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中 7 个秘密报告的漏洞。 如果用户使用 Microsoft Office 查看特制图像文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-106">MS10-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 中的漏洞可能允许拒绝服务 (2407132)</strong><br />
<br />
此安全更新可解决 Microsoft Exchange Server 中一个秘密报告的漏洞。 如果经过验证的攻击者向运行 Exchange 服务的计算机发送特制网络消息，则此漏洞可能允许拒绝服务。 采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。 按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
拒绝服务</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。
  
| 公告 ID                                                             | 漏洞标题                                             | CVE ID                                                                           | 利用指数评估                                                                                  | 重要注意事项                                 |  
|---------------------------------------------------------------------|------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|----------------------------------------------|  
| [MS10-103](https://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll 中的大小值堆损坏漏洞                     | [CVE-2010-2569](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-103](https://technet.microsoft.com/security/bulletin/ms10-103) | pubconv.dll 中的堆溢出漏洞                           | [CVE-2010-2570](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-097](https://technet.microsoft.com/security/bulletin/ms10-097) | Internet 连接注册向导库加载不安全漏洞                | [CVE-2010-3144](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                         |  
| [MS10-096](https://technet.microsoft.com/security/bulletin/ms10-096) | 库加载不安全漏洞                                     | [CVE-2010-3147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                         |  
| [MS10-092](https://go.microsoft.com/fwlink/?linkid=203463)           | 任务计划程序漏洞                                     | [CVE-2010-3338](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞正在 Internet 生态系统中被利用**     |  
| [MS10-090](https://technet.microsoft.com/security/bulletin/ms10-090) | HTML 对象内存损坏漏洞                                | [CVE-2010-3340](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-090](https://technet.microsoft.com/security/bulletin/ms10-090) | HTML 对象内存损坏漏洞                                | [CVE-2010-3343](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-090](https://technet.microsoft.com/security/bulletin/ms10-090) | HTML 元素内存损坏漏洞                                | [CVE-2010-3345](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-090](https://technet.microsoft.com/security/bulletin/ms10-090) | HTML 元素内存损坏漏洞                                | [CVE-2010-3346](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 缓冲区溢出漏洞                                | [CVE-2010-3939](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                         |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k PFE 指针双重释放漏洞                          | [CVE-2010-3940](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 光标链接漏洞                                  | [CVE-2010-3943](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 内存损坏漏洞                                  | [CVE-2010-3944](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 图像转换器缓冲区溢出漏洞                    | [CVE-2010-3951](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-091](https://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 字体双重释放漏洞                            | [CVE-2010-3957](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-091](https://technet.microsoft.com/security/bulletin/ms10-091) | OpenType CMAP 表漏洞                                 | [CVE-2010-3959](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-100](https://technet.microsoft.com/security/bulletin/ms10-100) | Consent UI 模拟漏洞                                  | [CVE-2010-3961](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-090](https://technet.microsoft.com/security/bulletin/ms10-090) | 未初始化的内存损坏漏洞                               | [CVE-2010-3962](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞当前正在 Internet 生态系统中被利用** |  
| [MS10-099](https://technet.microsoft.com/security/bulletin/ms10-099) | 内核 NDProxy 缓冲区溢出漏洞                          | [CVE-2010-3963](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-104](https://technet.microsoft.com/security/bulletin/ms10-104) | 格式错误的请求执行代码漏洞                           | [CVE-2010-3964](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-094](https://technet.microsoft.com/security/bulletin/ms10-094) | 库加载不安全漏洞                                     | [CVE-2010-3965](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                         |  
| [MS10-095](https://technet.microsoft.com/security/bulletin/ms10-095) | BranchCache 库加载不安全漏洞                         | [CVE-2010-3966](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | （无）                                       |  
| [MS10-093](https://technet.microsoft.com/security/bulletin/ms10-093) | 库加载不安全漏洞                                     | [CVE-2010-3967](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码   | **此漏洞已公开披露**                         |  
| [MS10-103](https://technet.microsoft.com/security/bulletin/ms10-103) | Pubconv.dll 中由于索引到数组无效而导致的内存损坏漏洞 | [CVE-2010-2571](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k 双重释放漏洞                                  | [CVE-2010-3941](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-098](https://technet.microsoft.com/security/bulletin/ms10-098) | Win32k WriteAV 漏洞                                  | [CVE-2010-3942](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | CGM 图像转换器缓冲区溢出漏洞                         | [CVE-2010-3945](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | PICT 图像转换器整数溢出漏洞                          | [CVE-2010-3946](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 图像转换器堆溢出漏洞                            | [CVE-2010-3947](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 图像转换器缓冲区溢出漏洞                        | [CVE-2010-3949](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | TIFF 图像转换器内存损坏漏洞                          | [CVE-2010-3950](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-105](https://technet.microsoft.com/security/bulletin/ms10-105) | FlashPix 图像转换器堆损坏漏洞                        | [CVE-2010-3952](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-103](https://technet.microsoft.com/security/bulletin/ms10-103) | 数组索引内存损坏漏洞                                 | [CVE-2010-3955](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-091](https://technet.microsoft.com/security/bulletin/ms10-091) | OpenType 字体索引漏洞                                | [CVE-2010-3956](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的不一致漏洞检测代码 | （无）                                       |  
| [MS10-101](https://technet.microsoft.com/security/bulletin/ms10-101) | Netlogon RPC 空解除引用 DOS 漏洞                     | [CVE-2010-2742](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能被利用的代码     | 这只是一个拒绝服务漏洞                       |  
| [MS10-106](https://technet.microsoft.com/security/bulletin/ms10-106) | Exchange Server 无限循环漏洞                         | [CVE-2010-3937](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能被利用的代码     | 这只是一个拒绝服务漏洞                       |  
| [MS10-103](https://technet.microsoft.com/security/bulletin/ms10-103) | Microsoft Publisher 内存损坏漏洞                     | [CVE-2010-3954](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能被利用的代码     | （无）                                       |  
| [MS10-102](https://technet.microsoft.com/security/bulletin/ms10-102) | Hyper-V VMBus 漏洞                                   | [CVE-2010-3960](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) – 不太可能被利用的代码     | 这只是一个拒绝服务漏洞                       |
  
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
<th colspan="14" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50)  
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
<th colspan="14" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926)  
（重要）
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa)  
（重要）
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de)  
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
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="14" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846)  
（重要）
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](https://www.microsoft.com/download/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664)  
（重要）
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
Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613)  
（重要）
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](https://www.microsoft.com/download/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82)<sup>[1]</sup>  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408)  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="14" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284)\*\*  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](https://www.microsoft.com/download/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126)\*\*  
（重要）  
[Windows Media Encoder 9 x64](https://www.microsoft.com/download/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee)  
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
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="14" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401)  
（重要）
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
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="14" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-090**](https://technet.microsoft.com/security/bulletin/ms10-090)
</td>
<td style="border:1px solid black;">
[**MS10-091**](https://technet.microsoft.com/security/bulletin/ms10-091)
</td>
<td style="border:1px solid black;">
[**MS10-092**](https://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](https://technet.microsoft.com/security/bulletin/ms10-093)
</td>
<td style="border:1px solid black;">
[**MS10-094**](https://technet.microsoft.com/security/bulletin/ms10-094)
</td>
<td style="border:1px solid black;">
[**MS10-095**](https://technet.microsoft.com/security/bulletin/ms10-095)
</td>
<td style="border:1px solid black;">
[**MS10-096**](https://technet.microsoft.com/security/bulletin/ms10-096)
</td>
<td style="border:1px solid black;">
[**MS10-097**](https://technet.microsoft.com/security/bulletin/ms10-097)
</td>
<td style="border:1px solid black;">
[**MS10-098**](https://technet.microsoft.com/security/bulletin/ms10-098)
</td>
<td style="border:1px solid black;">
[**MS10-099**](https://technet.microsoft.com/security/bulletin/ms10-099)
</td>
<td style="border:1px solid black;">
[**MS10-100**](https://technet.microsoft.com/security/bulletin/ms10-100)
</td>
<td style="border:1px solid black;">
[**MS10-101**](https://technet.microsoft.com/security/bulletin/ms10-101)
</td>
<td style="border:1px solid black;">
[**MS10-102**](https://technet.microsoft.com/security/bulletin/ms10-102)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。 注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](https://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](https://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。 注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS10-093 注释**

<sup>[1]</sup>Windows Movie Maker 2.6 是一种可选下载程序，可以安装在指定的操作系统上。

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
Microsoft Office 套件和组件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-103**](https://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](https://technet.microsoft.com/security/bulletin/ms10-105)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5)  
(KB2284692)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b)<sup>[1]</sup>  
(KB2289162)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e)  
(KB2284695)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd)<sup>[1]</sup>  
(KB2289163)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35)  
(KB2284697)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290)  
(KB2288931)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2)  
(KB2409055)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53)  
(KB2289078)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966)  
(KB2409055)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082)  
(KB2289078)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-103**](https://technet.microsoft.com/security/bulletin/ms10-103)
</td>
<td style="border:1px solid black;">
[**MS10-105**](https://technet.microsoft.com/security/bulletin/ms10-105)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](https://www.microsoft.com/download/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306)  
(KB2456849)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](https://www.microsoft.com/download/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f)  
(KB2431831)  
（重要）
</td>
</tr>
</table>

**MS10-105 注释**

<sup>[1]</sup>使用所述软件的客户也需要安装 MS10-087 中提供的 Microsoft Office 更新以免受 MS10-105 中所述的漏洞影响。

<sup>[2]</sup>严重等级不适用于此更新，因为此公告中讨论的漏洞不影响此软件。 但是，作为针对将来可能发现的任何新媒介的纵深防御措施，Microsoft 建议使用此软件的客户应用此安全更新。

#### Microsoft 服务器软件

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
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-104**](https://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](https://technet.microsoft.com/security/bulletin/ms10-106)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2（32 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60)  
(KB2433089)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2（64 位版本）](https://www.microsoft.com/download/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3)  
(KB2433089)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-104**](https://technet.microsoft.com/security/bulletin/ms10-104)
</td>
<td style="border:1px solid black;">
[**MS10-106**](https://technet.microsoft.com/security/bulletin/ms10-106)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62)  
(KB2407132)  
（中等）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。 有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://go.microsoft.com/fwlink/?linkid=50120)。

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。 通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。 Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。 有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](https://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。 有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](https://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 。SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面章节“**SystemCenter Configuration Manager 2007**”。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意** SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

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

-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Aniway 报告了 MS10-090 中描述的问题
-   [VUPEN 漏洞调查小组](https://www.vupen.com/) 的 Nicolas Joly 报告了 MS10-090 中描述的问题
-   Stephen Fewer 与 [Tipping Point](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-090 中描述的问题
-   [Peter Vreugdenhil](https://vreugdenhilresearch.nl/) 与 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-090 中描述的问题
-   [Yosuke Hasegawa](https://utf-8.jp/) 与我们合作解决了 MS10-090 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Jose Antonio Vazquez Gonzalez 报告了 MS10-090 中描述的问题
-   [Red Hat Security Response Team](https://www.redhat.com/security/team/) 的 Marc Schoenefeld 与 [Opera Security Team](https://www.opera.com/security/) 合作报告了 MS10-091 中描述的问题
-   [Red Hat Security Response Team](https://www.redhat.com/security/team/) 的 Marc Schoenefeld 报告了 MS10-091 中描述的问题
-   Paul-Kenji Cahier Furuya 报告了 MS10-091 中描述的问题
-   [Kaspersky Lab](https://usa.kaspersky.com/) 的 Sergey Golovanov、Alexander Gostev、Maxim Golovkin 和 Alexey Monastyrsky 以及 [Design and Test Lab](https://www.dnt-lab.com/) 的 Vitaly Kiktenko 和 Alexander Saprykin 报告了 MS10-092 中描述的问题
-   [Symantec](https://www.symantec.com/index.jsp) 的 Liam O Murchu 报告了 MS10-092 中描述的问题
-   [ESET](https://www.eset.com/) 的 Alexandr Matrosov、Eugene Rodionov、Juraj Malcho 和 David Harley 报告了 MS10-092 中描述的问题
-   [Fortinet's FortiGuard Labs](https://www.fortiguard.com/) 的 Haifei Li 报告了 MS10-095 中描述的问题
-   [ACROS Security](https://www.acrossecurity.com/) 的 Simon Raner 报告了 MS10-096 中描述的问题
-   [Rapid7](https://www.rapid7.com/)的 HD Moore 报告了 MS10-096 中描述的问题
-   [NGS Software](https://www.ngssoftware.com/) 的 Muhaimin Dzulfakar 报告了 MS10-096 中描述的问题
-   [NGS Software](https://www.ngssoftware.com/) 的 Muhaimin Dzulfakar 报告了 MS10-097 中描述的问题
-   [Norman](https://www.norman.com/) 的 Tarjei Mandt 报告了 MS10-098 中描述的四个问题
-   [Sysdream](https://www.sysdream.com/) 的 Stéfan Le Berre 报告了 MS10-098 中描述的问题
-   [Fortinet's FortiGuard Labs](https://www.fortiguard.com/) 的 Honggang Ren 报告了 MS10-099 中描述的问题
-   [Argeniss](https://www.argeniss.com/) 的 Cesar Cerrudo 报告了 MS10-100 中描述的问题
-   The Samba Team 的 Matthias Dieter Wallnöfer 和 Andrew Bartlett 报告了 MS10-101 中描述的问题
-   [HP](https://www.hp.com/) 和 [techit](https://www.techit.de/) 报告了 MS10-102 中描述的问题
-   [VUPEN 漏洞调查小组](https://www.vupen.com/) 的 Chaouki Bekrar 报告了 MS10-103 中描述的五个问题
-   Oleksandr Mirosh 与 [TippingPoint 的](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-104 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS10-105 中描述的两个问题
-   [Secunia Research](https://secunia.com/) 的 Alin Rad Pop 报告了 MS10-105 中描述的一个问题
-   [Secunia Research](https://secunia.com/) 的 Carsten Eiram 报告了 MS10-105 中描述的三个问题
-   [Secunia Research](https://secunia.com/) 的 Dyon Balding 报告了 MS10-105 中描述的两个问题
-   Oleksandr Mirosh 与 [TippingPoint 的](https://www.tippingpoint.com/)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-106 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 12 月 14 日）： 已发布公告摘要。
-   V1.1（2010 年 12 月 15 日）： 阐明了 Microsoft Office XP 和 Microsoft Office 2003 的客户需要应用 MS10-087 中的更新以免受 MS10-105 中所述的漏洞影响。

*Built at 2014-04-18T01:50:00Z-07:00*
