---
TOCTitle: 'MS09-OCT'
Title: 'Microsoft 安全公告摘要 (2009 年 10 月)'
ms:assetid: 'ms09-oct'
ms:contentKeyID: 61236937
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms09-oct(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2009 年 10 月)
======================================

发布时间: 2009年10月13日 | 更新时间: 2010年6月22日

**版本:** 4.2

本公告摘要列出了 2009 年 10 月发布的安全公告。

对于 2009 年 10 月发布的安全公告，本公告摘要替代 2009 年 10 月 8 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2009 年 10 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 10 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407488&culture=en-us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;"><strong>SMBv2 中的漏洞可能允许远程执行代码 (975517)</strong><br />
<br />
此安全更新解决服务器消息块版本 2 (SMBv2) 中一个公开披露和两个秘密报告的漏洞。 如果攻击者向运行 Server 的计算机发送特制的 SMB 数据包，则这些漏洞中最严重的漏洞可能允许远程执行代码。 采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。 按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=125438">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Windows Media Runtime 中的漏洞可能允许远程执行代码 (975682)</strong><br />
<br />
此安全更新可解决 Windows Media Runtime 中两个秘密报告的漏洞。 如果用户打开一个特制的媒体文件或从网站或提供 Web 内容的任何应用程序接收特制的流式内容，这些漏洞则可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163913">MS09-052</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player 中的漏洞可能允许远程执行代码 (974112)</strong><br />
<br />
此安全更新可解决 Windows Media Player 中一个秘密报告的漏洞。 如果使用 Windows Media Player 6.4 播放特制的 ASF 文件，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (974455)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中三个秘密报告的漏洞和一个公开披露的漏洞。 如果用户使用 Internet Explorer 查看特制网页，则所有漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 正在运行 Windows Presentation Foundation (WPF) 插件并且没有禁用该插件的 Firefox 用户也应该应用此安全更新。 有关此问题的详细信息，请参阅 HTML 组件处理漏洞 (CVE-2009-2529) 的常见问题部分。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-055">MS09-055</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (973525)</strong><br />
<br />
此安全更新解决了当前正被利用的多个 ActiveX 控件公有的一个秘密报告的漏洞。 如果用户使用实例化 ActiveX 控件的 Internet Explorer 查看特制网页，影响使用 Microsoft 活动模板库 (ATL) 容易受攻击版本编译的 ActiveX 控件的漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 的 Microsoft 活动模板库 (ATL) ActiveX 控件中的漏洞可能允许远程执行代码 (973965)</strong><br />
<br />
此安全更新可解决使用 Microsoft 活动模板库 (ATL) 的容易受攻击版本编译的 Microsoft Office ActiveX 控件中的多个秘密报告的漏洞。 如果用户加载了特制组件或控件，这些漏洞可以允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET 公共语言运行时中的漏洞可能允许远程执行代码 (974378)</strong><br />
<br />
此安全更新解决 Microsoft .NET Framework 和 Microsoft Silverlight 中三个秘密报告的漏洞。 如果用户使用可以运行 XAML 浏览器应用程序 (XBAP) 或 Silverlight 应用程序的 Web 浏览器查看特制网页，或者攻击者成功地说服用户运行特制 Microsoft .NET 应用程序，这些漏洞可能允许在客户端系统上远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。 如果运行 IIS 的服务器系统允许处理 ASP.NET 页面，并且攻击者成功地将特制 ASP.NET 页面上载到该服务器并执行它，这些漏洞也可能允许在该服务器系统上远程执行代码，在 Web 主机情形中也是如此。 非恶意的 Microsoft .NET 应用程序、Silverlight 应用程序、XBAP 和 ASP.NET 页面不受此漏洞的影响。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework，<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;"><strong>GDI+ 中的漏洞可能允许远程执行代码 (957488)</strong><br />
<br />
此安全更新可解决 Microsoft Windows GDI+ 中许多秘密报告的漏洞。 如果用户使用受影响的软件查看特制图像文件或浏览包含特制内容的网站，则这些漏洞可能允许远程执行代码。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer，<br />  
Microsoft .NET Framework，<br />  
Microsoft Office，<br />  
Microsoft SQL Server，<br />  
Microsoft 开发工具，<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=164004">MS09-053</a></td>
<td style="border:1px solid black;"><strong>用于 Internet 信息服务的 FTP 服务中的漏洞可能允许远程执行代码 (975254)</strong><br />
<br />
此安全更新可解决 Microsoft Internet Information Services (IIS) 5.0、Microsoft Internet Information Services (IIS) 5.1、Microsoft Internet Information Services (IIS) 6.0 和 Microsoft Internet Information Services (IIS) 7.0 的 FTP 服务中两个公开披露的漏洞。在 IIS 7.0 中，仅 FTP Service 6.0 受到影响。 这些漏洞可能允许对在 IIS 5.0 上运行 FTP 服务的系统远程执行代码 (RCE)，或对在 IIS 5.0、IIS 5.1、IIS 6.0 或 IIS 7.0 上运行 FTP 服务的系统拒绝服务 (DoS)。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163830">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Windows CryptoAPI 中的漏洞可能允许欺骗 (974571)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中两个公开披露的漏洞。 如果攻击者获得对最终用户用于身份验证的证书的访问，那么这些漏洞可能允许欺骗。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
欺骗</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163832">MS09-057</a></td>
<td style="border:1px solid black;"><strong>索引服务中的漏洞可能允许远程执行代码 (969059)</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。 如果攻击者设置了一个通过调用 ActiveX 组件来调用索引服务的恶意网页，该漏洞可能允许远程执行代码。 此调用可能包括一个恶意的 URL 和利用漏洞，使攻击者凭借用户浏览网页的权限访问客户端系统。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (971486)</strong><br />
<br />
此安全更新可解决 Windows 内核中许多秘密报告的漏洞。 如果攻击者登录系统并运行特制应用程序，最严重的漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=163843">MS09-059</a></td>
<td style="border:1px solid black;"><strong>本地安全机构子系统服务中的漏洞可能允许拒绝服务（975467）</strong><br />
<br />
此安全更新解决了 Microsoft Windows 中一个秘密报告的漏洞。 如果攻击者在 NTLM 身份验证过程中发送一个恶意制造的数据包，则此漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
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
  
| 公告 ID                                                             | 公告标题                                                                                          | CVE ID                                                                           | 利用指数评估                                                                                      | 重要注意事项                                                                                                                                                                                                                                                                                          |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-050](https://go.microsoft.com/fwlink/?linkid=163970)           | SMBv2 中的漏洞可能允许远程执行代码 (975517)                                                       | [CVE-2009-2526](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是一个受限的拒绝服务漏洞。                                                                                                                                                                                                                                                                          |  
| [MS09-050](https://go.microsoft.com/fwlink/?linkid=163970)           | SMBv2 中的漏洞可能允许远程执行代码 (975517)                                                       | [CVE-2009-2532](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-050](https://go.microsoft.com/fwlink/?linkid=163970)           | SMBv2 中的漏洞可能允许远程执行代码 (975517)                                                       | [CVE-2009-3103](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 漏洞检测代码已公开发布。                                                                                                                                                                                                                                                                              |  
| [MS09-051](https://go.microsoft.com/fwlink/?linkid=125438)           | Windows Media Runtime 中的漏洞可能允许远程执行代码 (975682)                                       | [CVE-2009-0555](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-051](https://go.microsoft.com/fwlink/?linkid=125438)           | Windows Media Runtime 中的漏洞可能允许远程执行代码 (975682)                                       | [CVE-2009-2525](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-052](https://go.microsoft.com/fwlink/?linkid=163913)           | Windows Media Player 中的漏洞可能允许远程执行代码 (974112)                                        | [CVE-2009-2527](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-053](https://go.microsoft.com/fwlink/?linkid=164004)           | 用于 Internet 信息服务的 FTP 服务中的漏洞可能允许远程执行代码 (975254)                            | [CVE-2009-2521](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是一个拒绝服务漏洞。 漏洞检测代码已公开发布。                                                                                                                                                                                                                                                       |  
| [MS09-053](https://go.microsoft.com/fwlink/?linkid=164004)           | 用于 Internet 信息服务的 FTP 服务中的漏洞可能允许远程执行代码 (975254)                            | [CVE-2009-3023](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 漏洞检测代码已公开发布。                                                                                                                                                                                                                                                                              |  
| [MS09-054](https://go.microsoft.com/fwlink/?linkid=163979)           | Internet Explorer 的累积性安全更新 (974455)                                                       | [CVE-2009-1547](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-054](https://go.microsoft.com/fwlink/?linkid=163979)           | Internet Explorer 的累积性安全更新 (974455)                                                       | [CVE-2009-2529](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-054](https://go.microsoft.com/fwlink/?linkid=163979)           | Internet Explorer 的累积性安全更新 (974455)                                                       | [CVE-2009-2530](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | 在 Microsoft Windows 2000 系统上，缺少堆保护会使利用指数评估增大到 [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 可能的一致漏洞检测代码。                                                                                                                                      |  
| [MS09-054](https://go.microsoft.com/fwlink/?linkid=163979)           | Internet Explorer 的累积性安全更新 (974455)                                                       | [CVE-2009-2531](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   |                                                                                                                                                                                                                                                                                                       |  
| [MS09-055](https://technet.microsoft.com/security/bulletin/ms09-055) | ActiveX Kill Bit 的累积性安全更新 (973525)                                                        | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 无                                                                                                | （[7 月安全公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中已经为此漏洞提供了利用指数评估。 这是因为此漏洞在 [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) MS09-035。另请参阅 [MS09-060](https://go.microsoft.com/fwlink/?linkid=160633) 中的相同 CVE 编号。           |  
| [MS09-056](https://go.microsoft.com/fwlink/?linkid=163830)           | Windows CryptoAPI 中的漏洞可能允许欺骗 (974571)                                                   | [CVE-2009-2510](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是欺骗漏洞。                                                                                                                                                                                                                                                                                        |  
| [MS09-056](https://go.microsoft.com/fwlink/?linkid=163830)           | Windows CryptoAPI 中的漏洞可能允许欺骗 (974571)                                                   | [CVE-2009-2511](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是欺骗漏洞。                                                                                                                                                                                                                                                                                        |  
| [MS09-057](https://go.microsoft.com/fwlink/?linkid=163832)           | 索引服务中的漏洞可能允许远程执行代码 (969059)                                                     | [CVE-2009-2507](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-058](https://go.microsoft.com/fwlink/?linkid=162442)           | Windows 内核中的漏洞可能允许特权提升 (971486)                                                     | [CVE-2009-2515](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-058](https://go.microsoft.com/fwlink/?linkid=162442)           | Windows 内核中的漏洞可能允许特权提升 (971486)                                                     | [CVE-2009-2516](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 当使用网络共享作为目标时，此漏洞导致拒绝服务情形，当本地使用以本地系统为目标时，此漏洞导致特权提升情形。                                                                                                                                                                                              |  
| [MS09-058](https://go.microsoft.com/fwlink/?linkid=162442)           | Windows 内核中的漏洞可能允许特权提升 (971486)                                                     | [CVE-2009-2517](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是一个拒绝服务漏洞。                                                                                                                                                                                                                                                                                |  
| [MS09-059](https://go.microsoft.com/fwlink/?linkid=163843)           | 本地安全机构子系统服务中的漏洞可能允许拒绝服务 (975467)                                           | [CVE-2009-2524](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是一个受限的拒绝服务漏洞。                                                                                                                                                                                                                                                                          |  
| [MS09-060](https://go.microsoft.com/fwlink/?linkid=160633)           | Microsoft Office 的 Microsoft 活动模板库 (ATL) ActiveX 控件中的漏洞可能允许远程执行代码（973965） | [CVE-2009-0901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | 无                                                                                                | （[7 月安全公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中已经为此漏洞提供了利用指数评估。 这是因为此漏洞在 [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) 中最先解决。）                                                                                             |  
| [MS09-060](https://go.microsoft.com/fwlink/?linkid=160633)           | Microsoft Office 的 Microsoft 活动模板库 (ATL) ActiveX 控件中的漏洞可能允许远程执行代码（973965） | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | 无                                                                                                | （[7 月安全公告摘要](https://technet.microsoft.com/security/bulletin/ms09-jul)中已经为此漏洞提供了利用指数评估。 这是因为此漏洞在 [MS09-035](https://go.microsoft.com/fwlink/?linkid=158131) MS09-035。另请参阅 [MS09-055](https://technet.microsoft.com/security/bulletin/ms09-055) 中的相同 CVE 编号。 |  
| [MS09-060](https://go.microsoft.com/fwlink/?linkid=160633)           | Microsoft Office 的 Microsoft 活动模板库 (ATL) ActiveX 控件中的漏洞可能允许远程执行代码（973965） | [CVE-2009-2495](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 功能漏洞检测代码不太可能实现 | 这是一个信息泄露漏洞。                                                                                                                                                                                                                                                                                |  
| [MS09-061](https://go.microsoft.com/fwlink/?linkid=160527)           | Microsoft .NET 公共语言运行时中的漏洞可能允许远程执行代码 (974378)                                | [CVE-2009-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-061](https://go.microsoft.com/fwlink/?linkid=160527)           | Microsoft .NET 公共语言运行时中的漏洞可能允许远程执行代码 (974378)                                | [CVE-2009-0091](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-061](https://go.microsoft.com/fwlink/?linkid=160527)           | Microsoft .NET 公共语言运行时中的漏洞可能允许远程执行代码 (974378)                                | [CVE-2009-2497](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | 可能存在影响 Internet 的攻击。                                                                                                                                                                                                                                                                        |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2500](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2501](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2502](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2503](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2504](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2518](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-2528](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528) | [**1**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 一致漏洞检测代码可能实现     | （无）                                                                                                                                                                                                                                                                                                |  
| [MS09-062](https://go.microsoft.com/fwlink/?linkid=161342)           | GDI+ 中的漏洞可能允许远程执行代码 (957488)                                                        | [CVE-2009-3126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126) | [**2**](https://technet.microsoft.com/en-us/security/cc998259.aspx) - 不一致漏洞检测代码可能实现   | （无）                                                                                                                                                                                                                                                                                                |
  
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
</tr>  
<tr>  
<th colspan="13" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**无**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[DirectShow WMA Voice Codec](https://www.microsoft.com/download/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
（严重）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e)  
(KB954155)  
（严重）  
[Audio Compression Manager](https://www.microsoft.com/download/details.aspx?familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194)  
(KB975025)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38)  
（严重）  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=edfea805-9544-4dc0-a52c-d7594205657b)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c)  
(KB958869)  
（严重）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2)  
(KB971108)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3e534aa8-29c2-4379-9f57-931a6ff47418)  
(KB971110)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc)  
(KB971111)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=7fecd367-aaff-458b-91bc-8925c8e57528)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=52b9198d-b65f-467a-a5ab-141e23d64a86)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=b34d94b5-b828-4e16-a636-04344c60d945)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[DirectShow WMA Voice Codec](https://www.microsoft.com/download/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
（严重）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=4516c219-e357-485e-a52b-23dcb8ee49d8)  
(KB954155)  
（严重）  
（仅限 Windows XP Service Pack 2）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=746d3440-5a6a-421e-9286-7b534a1dfe54)  
(KB954155)  
（严重）  
（仅限 Windows XP Service Pack 3）  
[Audio Compression Manager](https://www.microsoft.com/download/details.aspx?familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3)  
(KB975025)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dc166dc6-577f-4d8d-94df-dd963233dd85)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8799159d-df69-49f6-9db5-49147690ce0c)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=171d43d3-669c-4923-b266-e47591833c05)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c)  
(KB953295)  
（严重）  
（仅限 Tablet PC Edition 2005 和 Media Center Edition 2005）  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e2acde20-a6d3-4135-b6eb-1214f743d474)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9c5ab624-e37b-418a-a919-d8f652b15679)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=768fd74e-0a2f-4353-ac22-65d0d6321739)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cece4c55-0756-4357-9d2d-6709e8426068)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e997ea40-668e-40df-bd50-0ca53437b375)<sup>[1]</sup>  
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
[DirectShow WMA Voice Codec](https://www.microsoft.com/download/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
（严重）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684)  
(KB954155)  
（严重）  
Windows Media Format SDK 9.5 x64 版本中的 [Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2)  
(KB954155)  
（严重）  
Windows Media Format SDK 11 中的 [Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6)  
(KB954155)  
（严重）  
[Audio Compression Manager](https://www.microsoft.com/download/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=bd54e595-25f2-4839-a838-2a0f809bde2b)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=77b18fc2-e769-47c6-8e72-916716a49e58)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c08623bf-94bc-4c50-8c10-f50fb8448a0b)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ad92503a-8c91-4d73-98b0-942d7961637d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ad29696d-4611-4a12-9dfa-74fa6866b759)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=17008892-7950-44c4-850d-002c8d73495f)<sup>[1]</sup>  
（重要）
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
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
[DirectShow WMA Voice Codec](https://www.microsoft.com/download/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
（严重）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87)  
(KB954155)  
（严重）  
[Audio Compression Manager](https://www.microsoft.com/download/details.aspx?familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e)  
(KB975025)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=5f82d01c-573e-425e-b9f2-86a54f377b19)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f3249c99-82e4-45dc-a254-28e647e822c8)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1) (KB953298)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=48256ea3-b433-4e84-9019-22300069cfc1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=78072164-84d1-44da-8ede-2a9d212d47a9)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55)<sup>[1]</sup>  
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
[DirectShow WMA Voice Codec](https://www.microsoft.com/download/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
（严重）  
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20)  
(KB954155)  
（严重）  
Windows Media Format SDK 9.5 x64 版本中的 [Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2)  
(KB954155)  
（严重）  
[Audio Compression Manager](https://www.microsoft.com/download/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=2f966053-01eb-4a23-a9d5-71deac2498ea)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=708a549d-11fd-43bf-a6e1-309e3205d59d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=61bded07-201e-4815-ac1e-468bf907e063)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09)<sup>[1]</sup>  
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
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59)  
（严重）  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e)  
（中等）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=faef714b-5f46-47f2-bea7-881df05a1bc0)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8)<sup>[1]</sup>  
（重要）
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
Windows Vista
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29842c0c-8930-4b5f-83c6-1a718974b63f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe)  
(KB954155)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f6995616-2a84-4c26-9599-26f1314873ed)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=e8f6014f-950b-4e11-a105-51d298069f1a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=19aa01f3-026d-4264-85f8-216d0597969b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b5a9a95-9439-40c8-acef-000b919daa04)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista 和 Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
（严重）
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
（中等）
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=26905f12-92c7-4d45-99e7-227f03d2cb82)  
(KB954155)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b3de5236-afdd-436e-8648-5382d564cc99)  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=85978f28-5fc0-481b-9b03-2021c785889b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1 和 Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bce096c8-833b-45c8-99cd-1280f0744f2f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition 和 Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=58c995ca-f308-4e07-8e60-2e542384d95d)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
（严重）
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
（严重）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
（中等）
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3)\*\*  
(KB954155)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc)\*\*  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=fd1694af-8873-43aa-9243-91f7cde452b7)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f9b487af-fe73-42a8-b240-d59c4321f95b)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
（中等）
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa)\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Audio Voice Decoder](https://www.microsoft.com/download/details.aspx?familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd)\*\*  
(KB954155)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0111d741-bda4-4a50-a12b-d3337ff4441d)\*\*  
（严重）  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea)\*\*  
（低）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=db969ddc-708e-42b7-9956-6c27bf346bbb)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
（中等）
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b70108b-7f59-4898-ab4e-76be990de878)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e81f30b7-ef05-4488-b62a-d330e17129cf)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae)  
（低）
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)  
(KB974291)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2 和 Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)  
(KB974469)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a221451a-cb4e-4a43-a225-4b1e86e87525)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
（重要）  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)  
(KB974470)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
（中等）
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
Windows 7（用于 32 位系统）
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=b64bcc14-38a7-45b9-8f85-acc573777506)  
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
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=35b85783-90df-4f67-a3cb-02351432133e)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=809e29f3-ec68-4a2b-b04e-11759dd16001)  
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
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=70cd0270-77e9-492a-82d9-798364640c10)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=97010f2c-6c10-4fda-84fd-6c8749968db5)  
（重要）
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://go.microsoft.com/fwlink/?linkid=163843)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**低**](https://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2（用于基于 x64 的系统）
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=f50307d6-7869-4996-9ff7-23f87d08994b)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=bcd2b944-6852-48f2-820b-cce7d195e391)\*\*  
（低）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea)\*  
（重要）
</td>
</tr>
<tr class="alternateRow">
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=85e76e55-3766-4ffe-9a18-8655de935b7c)  
（低）
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
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e)  
（重要）
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS09-061 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

**MS09-062 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

**MS09-059 注释**

<sup>[1]</sup>该操作系统仅在安装了 KB968389“对身份验证的扩展保护”（请参阅 [Microsoft 安全通报 973811](https://technet.microsoft.com/security/advisory/973811)）时才受影响。 有关详细信息，请参阅 [MS09-059](https://go.microsoft.com/fwlink/?linkid=163843) 中“与此安全更新相关的常见问题 (FAQ)”中的该条目。

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
[**MS09-060**](https://go.microsoft.com/fwlink/?linkid=160633)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
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
[Microsoft Outlook 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=04878c2c-eb97-426f-be08-89036a6799db)  
(KB973702)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>  
(KB974811)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d)  
(KB973705)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>  
(KB972580)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 Service Pack 1 和 Microsoft Office Outlook 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d39234a3-c62c-44ba-a626-3179a183ca09)  
(KB972363)  
（严重）
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 和 2007 Microsoft Office System Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
其他 Microsoft Office 软件
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-060**](https://go.microsoft.com/fwlink/?linkid=160633)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
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
Microsoft Visio
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4)  
(KB975365)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio Viewer
</td>
<td style="border:1px solid black;">
Microsoft Visio 2002 Viewer<sup>[1]</sup>  
（严重）  
Microsoft Office Visio 2003 Viewer<sup>[1]</sup>  
（严重）  
[Microsoft Office Visio Viewer 2007 Service Pack 1 和 Microsoft Office Visio Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d20004c5-dd01-459e-8120-5f127e20c085)  
(KB973709)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio Viewer 2007 Service Pack 1 和 Microsoft Office Visio Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>  
(KB974811)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer、Microsoft Office Excel Viewer 和 Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer 2003 Service Pack 3 和 Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>  
(KB972580)  
（重要）  
[Microsoft Office Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
（重要）  
[PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[用于 Word、Excel 和 PowerPoint 2007 文件格式的 Microsoft Office 兼容包 Service Pack 1 以及用于 Word、Excel 和 PowerPoint 2007 文件格式 的 Microsoft Office 兼容包 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?familyid=6f96de9a-62d8-428f-9567-51d55c129be6)  
(KB973636)  
（重要）
</td>
</tr>
</table>

**MS09-060 注释**

<sup>[1]</sup>Microsoft 建议 Microsoft Visio Viewer 2002 和 Microsoft Visio Viewer 2003 用户升级到 Microsoft Office Visio Viewer 2007 Service Pack 2。

**MS09-062 注释**

<sup>[2]</sup>这些更新是相同的。

<sup>[3]</sup>这些更新是相同的。

<sup>[4]</sup>这些更新是相同的。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

#### Microsoft 服务器软件

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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新  
不适用  
QFE 更新：  
[SQL Server 2000 Reporting Services Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=33554f96-5af7-4683-a537-9db293b67b8d)  
(KB970899)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>  
(KB970895)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>  
(KB970896)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>  
(KB970895)  
（严重）  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>  
(KB970896)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>  
(KB970895)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>  
(KB970896)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 更新  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>  
(KB970892)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>  
(KB970894)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>  
(KB970892)  
（严重）  
QFE 更新：  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>  
(KB970894)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
GDR 更新：  
[SQL Server 2005 Service Pack 3（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>  
(KB970892)  
（严重）  
QFE 更新：  
[SQL Server 2005 Service Pack 3（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>  
(KB970894)  
（严重）
</td>
</tr>
</table>

**MS09-062 注释**

<sup>[1]</sup>依赖 Reporting Services SharePoint 的 SQL Server 2005 Service Pack 2 客户需要从 Microsoft 下载中心安装 [Service Pack 2 的 Microsoft SQL Server 2005 Reporting Services 加载项](https://www.microsoft.com/download/details.aspx?familyid=%20f4d4d0ae-e5d4-4ed1-8d78-7137578161ce&displaylang=en)。

<sup>[2]</sup>依赖 Reporting Services SharePoint 的 SQL Server 2005 Service Pack 3 客户需要从 Microsoft 下载中心安装 [Service Pack 3 的 Microsoft SQL Server 2005 Reporting Services 加载项](https://www.microsoft.com/download/details.aspx?familyid=%20648766ac-2a35-4238-a3f4-c26d7077f2a9&displaylang=en)。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

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
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](https://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> 安装在 Mac 上时  
(KB970363)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](https://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> 安装在 Microsoft Windows 客户端的所有版本上时  
(KB970363)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](https://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> 安装在 Microsoft Windows 服务器的所有版本上时\*\*  
(KB970363)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c)  
(KB971022)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060)  
(KB971023)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?familyid=4fa10c93-ce20-43df-a725-ef4c77353747)  
(KB972221)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52)  
(KB972222)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 Microsoft Visual FoxPro 8.0 Service Pack 1  
(KB971104)
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af)  
Microsoft XML Core Services 6.0  
(KB971104)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安装在 Microsoft Windows 2000 Service Pack 4 上的 Microsoft Visual FoxPro 9.0 Service Pack 2  
(KB971105)
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7)  
Microsoft XML Core Services 6.0  
(KB971105)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=0dfaf300-2b53-4678-a779-0d805ddfe538)  
(KB971117)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package](https://www.microsoft.com/download/details.aspx?familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22)  
(KB971118)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42)  
(KB971119)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable： GDI+
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable： GDI+](https://www.microsoft.com/download/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(KB975337)  
（没有严重等级<sup>[2]</sup>）
</td>
</tr>
</table>

**MS09-061 注释**

<sup>[1]</sup>此下载将 Microsoft Silverlight 2 升级到 Microsoft Silverlight 3，从而解决本公告中描述的漏洞。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

**MS09-062 注释**

<sup>[2]</sup>严重等级不适用于此更新，因为对于此公告中讨论的特定于这些软件的漏洞， Microsoft 尚未识别任何攻击媒介。 但此安全更新提供给使用这些软件的开发人员，以便他们可能发布其应用程序的更新版本。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

#### Microsoft 安全软件

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
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](https://www.microsoft.com/download/details.aspx?familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8)  
Microsoft XML Core Services 6.0  
(KB975962)  
（重要）
</td>
</tr>
</table>

**MS09-062 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

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

-   [Netherlands Forensics Institute](https://www.nederlandsforensischinstituut.nl/) 的 [Matthieu Suiche](https://www.msuiche.net/) 报告了 MS09-050 中描述的问题
-   [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Ivan Fratric 和 [McAfee Avert Labs](https://www.avertlabs.com/) 的 Jun Xie 报告了 MS09-051 中描述的问题
-   [Adobe Systems, Inc.](https://www.adobe.com/) 的 Vinay Anantharaman 报告了 MS09-051 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS09-052 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 SkyLined 报告了 MS09-054 中描述的问题
-   [IBM ISS X-Force](https://www.iss.net/) 的 Mark Dowd 报告了 MS09-054 中描述的问题
-   [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 报告了 MS09-054 中描述的问题
-   eshu.co.uk 的 Sam Thomas 与 [TippingPoint](https://www.tippingpoint.com/) 和 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS09-054 中描述的一个问题
-   [Citrix](https://www.citrix.com/) 的 Ian Wright 和 Jean-Luc Giraud 与我们合作解决 MS09-056 中描述的问题
-   [IOActive](https://www.ioactive.com/) 的 Dan Kaminsky 报告了 MS09-056 中描述的两个问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS09-057 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 和 Neel Mehta 报告了 MS09-058 中描述的两个问题
-   [NSFocus Security Team](https://www.nsfocus.com/) 报告了 MS09-058 中描述的问题。
-   [IBM ISS X-Force](https://www.iss.net/) 的 David Dewey 报告了 MS09-060 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Ryan Smith 报告了 MS09-060 中描述的两个问题
-   [Pavel Minaev](https://int19h.org/) 报告了 MS09-061 中描述的问题
-   [Sumatra](https://www.sumatra.nl/) 的 Jeroen Frijters 报告了 MS09-061 中描述的问题
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS09-062 中描述的问题
-   [SkyRecon](https://www.skyrecon.com/) 的 Thomas Garnier 报告了 MS09-062 中描述的问题
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Wushi 报告了 MS09-062 中描述的问题
-   [Zero Day Initiative](https://www.zerodayinitiative.com/) 的 Ivan Fratric 报告了 MS09-062 中描述的问题
-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 报告了 MS09-062 中描述的两个问题
-   Carlo Di Dato (aka shinnai) 报告了 MS09-062 中描述的问题。
-   [VeriSign iDefense Labs](https://labs.idefense.com/) 的 Marsu Pilami 报告了 MS09-062 中描述的问题
-   [Secunia](https://secunia.com/) 的 Carsten H. Eiram 报告了 MS09-062 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2009 年 10 月 13 日）： 已发布公告摘要。
-   V1.1（2009 年 10 月 14 日）： 针对 MS09-055 更正了 Windows XP x64 Edition Service Pack 2 的下载链接。
-   V1.2（2009 年 10 月 18 日）： 修订了 MS09-054 的摘要以便为 Firefox 用户提供指示。
-   V2.0（2009 年 10 月 28 日）： 将 Microsoft Office Visio Viewer 2007、Microsoft Office Visio Viewer 2007 Service Pack 1 和 Microsoft Office Visio Viewer 2007 Service Pack 2 添加为 MS09-062 的受影响软件，并为依赖 Reporting Services SharePoint 的 SQL Server 2005 客户添加了 MS09-062 注释。
-   V3.0（2009 年 11 月 2 日）： 已经过修订以宣布用于解决应用程序兼容性问题的 MS09-054 修补程序的可用性。 已应用此更新的客户可从 Microsoft 知识库文章 976749 安装该修补程序。
-   V3.1（2009 年 11 月 4 日）： 删除了 MS09-060 和 MS09-062 中关于将 Microsoft Office Visio Viewer 2007 原始发行版本作为受影响的软件的错误引用。
-   V4.0（2009 年 11 月 10 日）： 公告经过修订，传达重新发布 MS09-051 中针对 Microsoft Windows 2000 Service Pack 4 上的 Audio Compression Manager 的更新，以解决检测问题。 这仅仅是一个检测更改；不更改二进制。 成功地更新了其系统的客户不需要重新安装此更新。
-   V4.1（2010 年 6 月 12 日）： 删除 MS09-062 的作为受影响软件的 Microsoft Expression Web、Microsoft Expression Web 2、Microsoft Office Groove 2007 和 Microsoft Office Groove 2007 Service Pack 1。
-   V4.2（2010 年 6 月 22 日）： 针对 MS09-061 删除了 .NET Framework 1.1 Service Pack，其不再是 Windows 7 和 Windows Server 2008 R2 上的受影响组件。

*Built at 2014-04-18T01:50:00Z-07:00*
