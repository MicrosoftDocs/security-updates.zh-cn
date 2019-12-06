---
TOCTitle: 'MS10-APR'
Title: 'Microsoft 安全公告摘要 (2010 年 4 月)'
ms:assetid: 'ms10-apr'
ms:contentKeyID: 61236939
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms10-apr(v=Security.10)'
---

Security Bulletin Summary

Microsoft 安全公告摘要 (2010 年 4 月)
=====================================

发布时间: 2010年4月13日 | 更新时间: 2010年7月13日

**版本:** 4.0

本公告摘要列出了 2010 年 4 月发布的安全公告。

对于 2010 年 4 月发布的安全公告，本公告摘要替代 2010 年 4 月 8 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2010 年 4 月 14 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 4 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427721&eventcategory=4&culture=en-us&countrycode=us)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](https://technet.microsoft.com/security/bulletin/summary)。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;"><strong>Windows 中的漏洞可能允许远程执行代码 (981210)</strong><br />
<br />
此安全更新解决 Windows Authenticode 验证中可能允许远程执行代码的两个秘密报告的漏洞。 成功利用此漏洞的攻击者可以完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;"><strong>SMB 客户端中的漏洞可能允许远程执行代码 (980232)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露的漏洞和若干个秘密报告的漏洞。 如果攻击者将特制的 SMB 响应发送到客户端发起的 SMB 请求，此漏洞可能允许远程执行代码。 要利用这些漏洞，攻击者必须诱使用户建立与特制的 SMB 服务器的 SMB 连接。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows Media Services 中的漏洞可能允许远程执行代码 (980858)</strong><br />
<br />
此安全更新解决在 Microsoft Windows 2000 Server 上运行的 Windows Media Services 中秘密报告的漏洞。 如果攻击者将特制的传输信息包发送到运行 Windows Media Services 的 Microsoft Windows 2000 Server 系统，此漏洞可能允许远程执行代码。 采用防火墙最佳做法和标准的默认防火墙配置，有助于保护网络免受从企业外部发起的攻击。 按照最佳做法，应使连接到 Internet 的系统所暴露的端口数尽可能少。 在 Microsoft Windows 2000 Server 上，Windows Media Services 是可选组件，在默认情况下并未安装。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft MPEG Layer-3 编码解码器中的漏洞可能允许远程执行代码 (977816)</strong><br />
<br />
此安全更新解决 Microsoft MPEG Layer-3 音频编码解码器中秘密报告的漏洞。 如果用户打开包含 MPEG Layer-3 音频流的特制的 AVI 文件，此漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player 中的漏洞可能允许远程执行代码 (979402)</strong><br />
<br />
此安全更新可解决 Windows Media Player 中一个秘密报告的漏洞。 如果 Windows Media Player 打开恶意网站上特制的媒体内容，此漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (979683)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中许多秘密报告的漏洞。 如果攻击者本地登录并运行特制应用程序，其中最严重的漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;"><strong>VBScript 中的漏洞可能允许远程执行代码 (981169)</strong><br />
<br />  
此安全更新解决 Microsoft Windows 上的 VBScript 中可能允许远程执行代码的公开披露的漏洞。 对于 Microsoft Windows 2000、Windows XP 和 Windows Server 2003，此安全更新的等级为“重要”。在 Windows Server 2008、Windows Vista、Windows 7 和 Windows Server 2008 R2 上，无法利用这个容易受到攻击的代码，但由于存在该代码，所以此更新将作为纵深防御措施提供，并且没有严重等级。<br />  
<br />
如果恶意网站在网页上显示特制的对话框，并且用户按了 F1 键，导致以攻击者提供的 Windows 帮助文件启动 Windows 帮助系统，则此漏洞可能允许远程执行代码。 如果用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher 中的漏洞可能允许远程执行代码 (981160)</strong><br />
<br />
此安全更新解决了 Microsoft Office Publisher 中一个秘密报告的漏洞，如果用户打开特制的 Publisher 文件，则该漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange 和 Windows SMTP 服务中的漏洞可能允许拒绝服务 (981832)</strong><br />
<br />
此安全更新解决 Microsoft Exchange 和 Windows SMTP 服务中一个公开披露的漏洞和一个秘密报告的漏洞。 如果攻击者将特制的 DNS 响应发送到运行 SMTP 服务的计算机，其中最严重的漏洞可能允许拒绝服务。 默认情况下，Windows Server 2003、Windows Server 2003 x64 Edition 或 Windows XP Professional x64 Edition 上未安装 SMTP 组件。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Exchange</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的漏洞可能允许远程执行代码 (980094)</strong><br />
<br />
此安全更新解决 Microsoft Office Visio 中两个秘密报告的漏洞。 如果用户打开特制的 Visio 文件，这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-029">MS10-029</a></td>
<td style="border:1px solid black;"><strong>Windows ISATAP 组件中的漏洞可能允许欺骗 (978338)</strong><br />
<br />  
此安全更新解决 Microsoft Windows 中一个秘密报告的漏洞。 对于 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008，此安全更新的等级为“中等”。由于 Windows 7 和 Windows Server 2008 R2 包含由此安全更新部署的功能，所以这些操作系统不容易受到攻击。<br />  
<br />
此漏洞可能允许攻击者欺骗 IPv4 地址，以便它可绕过依赖源 IPv4 地址的筛选设备。 通过更改 Windows TCP/IP 堆栈检查经过隧道传输的 ISATAP 数据包中的源 IPv6 地址的方式，此安全更新解决了漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">中等</a><br />
欺骗</td>
<td style="border:1px solid black;">需要重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**我如何使用该表呢？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/en-us/security/cc998259.aspx)。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>利用指数评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows 内核内存分配漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0236">CVE-2010-0236</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-021">MS10-021</a></td>
<td style="border:1px solid black;">Windows 内核符号链接创建漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0237">CVE-2010-0237</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio 属性验证内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0254">CVE-2010-0254</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-027">MS10-027</a></td>
<td style="border:1px solid black;">媒体播放器远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0268">CVE-2010-0268</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-025">MS10-025</a></td>
<td style="border:1px solid black;">基于媒体服务堆栈的缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0478">CVE-2010-0478</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-023">MS10-023</a></td>
<td style="border:1px solid black;">Microsoft Office Publisher 文件转换文本框处理缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0479">CVE-2010-0479</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-026">MS10-026</a></td>
<td style="border:1px solid black;">MPEG Layer-3 音频解码器堆栈溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0480">CVE-2010-0480</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-022">MS10-022</a></td>
<td style="border:1px solid black;">VBScript 帮助按键漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-0483</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - 一致漏洞检测代码可能实现<br />
<br />  
对于 Windows Server 2008、Windows 7 和 Windows Server 2008 R2：<br />
<a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 不太可能被利用的代码</td>
<td style="border:1px solid black;">此漏洞已公开披露，如 <a href="https://technet.microsoft.com/security/advisory/981169">Microsoft 安全通报 981169</a> 中所述</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-028">MS10-028</a></td>
<td style="border:1px solid black;">Visio 索引计算内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0256">CVE-2010-0256</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 不一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 客户端事务漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0270">CVE-2010-0270</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 不一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 客户端响应分析漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0476">CVE-2010-0476</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 不一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">WinVerifyTrust 签名验证漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0486">CVE-2010-0486</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 不一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-019">MS10-019</a></td>
<td style="border:1px solid black;">Cabview 损坏验证漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0487">CVE-2010-0487</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - 不一致漏洞检测代码可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 客户端不完整的响应漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3676">CVE-2009-3676</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 功能漏洞检测代码不太可能实现</td>
<td style="border:1px solid black;">此漏洞已公开披露，如 <a href="https://technet.microsoft.com/security/advisory/977544">Microsoft 安全通报 977544</a> 中所述。<br />
<br />
可能的影响是拒绝服务。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-024">MS10-024</a></td>
<td style="border:1px solid black;">SMTP 服务器 MX 记录漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0024">CVE-2010-0024</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 功能漏洞检测代码不太可能实现</td>
<td style="border:1px solid black;">可能的影响是拒绝服务</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 客户端内存分配漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0269">CVE-2010-0269</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 功能漏洞检测代码不太可能实现</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-020">MS10-020</a></td>
<td style="border:1px solid black;">SMB 客户端消息大小漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0477">CVE-2010-0477</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - 功能漏洞检测代码不太可能实现</td>
<td style="border:1px solid black;">可能的影响是拒绝服务</td>
</tr>  
</tbody>  
</table>
  
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
</tr>  
<tr>  
<th colspan="10" style="border:1px solid black;">  
Microsoft Windows 2000  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=d7538166-35ee-4c6b-be8c-e83a1fc6cd77)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 5.1](https://www.microsoft.com/download/details.aspx?familyid=13846177-f25f-4dd4-9fe9-ac43e1d4d73d)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=67ccac04-e5c8-4381-9d1a-9b676dd516a6)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=73b3d681-26bb-49c1-849e-1f72484cb978)  
（严重）
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=f6394fc2-b9d0-46cf-9265-a0d4aeb1448f)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 系列](https://www.microsoft.com/download/details.aspx?familyid=c0b8b362-a321-4ac9-be98-15c71bb7a043)  
（严重）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=c5f4577e-7546-40e9-8bcd-be11c1b260a6)  
（重要）
</td>
<td style="border:1px solid black;">
[VBScript 5.1](https://www.microsoft.com/download/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)<sup>[1]</sup>  
(KB981350)  
（重要）  
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=d5fc47a4-cecb-4817-aafb-45f335061be3)  
(KB981349)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=88a0e872-01de-495b-8eec-d105a970daa7)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 和 Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=2a01ddf0-f3ea-47c8-ada2-e69f6c1b5f96)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=6c3ac102-2107-4726-98be-4fbf6b858bfb)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=dec38c02-3d4a-41c5-8954-e57f56b8fa5b)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=b1582a74-4a7b-4540-beb1-7c89c86eae87)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上的 Windows Media Player 9 系列](https://www.microsoft.com/download/details.aspx?familyid=5c748c6d-84d1-45a9-8a33-9372eb5504d5)  
（严重）  
[Windows XP Service Pack 3 上的 Windows Media Player 9 系列](https://www.microsoft.com/download/details.aspx?familyid=9e4277b4-2dc5-4163-a6aa-7e07dd32b721)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=142710fd-9cd4-4dd0-aaba-2aace03c008f)  
（重要）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上的 [VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=aa8ff157-a7b3-4787-80c9-5bc453f0f1c9)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=cb21d276-65e9-4c8f-96e3-cf6dc36d0133)  
(KB981349)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=ba7ef6e5-80ba-4281-a611-6e5be008c1b4)  
(KB981332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=de447b76-ec89-426b-ac54-3ae3855d1159)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 和 Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9dc3e1c2-2e9d-4d86-9fce-446c409ad613)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=9bbff00c-f8f4-4a44-98f2-18a868986ae1)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=e64e487e-2727-4396-b0c9-6eaf000214d2)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c5a21239-a9a3-4ec5-9de8-7d2fc16fc6b8)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=8afca317-a647-44aa-a771-5d85cd5d62ea)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3c0cb02e-3484-4cdf-8c64-c697ad3e2889)  
（重要）
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=896c738d-4058-440f-8d4f-16c678610cd1)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=d7e8b930-8708-4f0b-b22b-961c2cbc2673)  
(KB981349)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=153fd9c1-0f8e-4492-87d1-f0381e7feb23)  
(KB981332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4f9a696d-2712-4777-a642-e78a38336e8a)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d872bd77-f491-4706-8ff5-081ac0bf3d6f)  
（中等）
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=0e7e3deb-f078-4953-9642-675ec69267f2)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=7ae9b1d0-0dbe-4abd-b315-10cea4ceccd7)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1189304f-d626-426d-960c-a86dc2d2b528)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=9f89746c-181e-4177-a851-ec1826e78b6d)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a7ea2d0-61ce-4b68-ad82-d917b1a56f9d)  
（重要）
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=28b035b8-d56e-4e93-b811-9a82cf1d4ba9)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=a142a553-85fc-40e0-9426-8d58f6a4333c)  
(KB981349)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=72754e1b-3d09-4b9d-8794-689c45a37f66)  
(KB981332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f781e9e4-87d4-4243-9d44-256424d75fec)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cd007a6c-04b3-490c-aff4-d5af3e69d477)  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=99a3f6da-728f-421c-ab41-c4c4751934a4)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=1709fd4e-d7c6-4cbb-8b71-a96b8d6eee58)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=52e4f66b-b76c-46a1-aeff-74efa21fc743)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=b97e7ea1-a163-4ce4-8cbc-5f933773c4b2)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1fc66f54-260a-4219-a0b4-056ba9dd0abe)  
（重要）
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=339ddf48-8949-4857-9ef6-1ddcc7c5f8b8)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=a489b4e3-78d2-411b-b27c-5987b8fc91d1)  
(KB981349)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=72c3013b-f72f-422b-8a89-2246dea4b378)  
(KB981332)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=644ff070-237b-4a73-b2e2-9fffdafa3927)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=19cfddfe-e8da-4564-9730-babfae4a3ebb)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](https://www.microsoft.com/download/details.aspx?familyid=06832599-1e9b-4792-8c7b-7b5b3a3d6277)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=811a2b28-655d-4b5d-821e-5a90d556dba3)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b2b6d8b1-63cc-459c-b5fa-1355386273c8)  
（严重）
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
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=8dcb8be8-fb78-4518-aa7e-f8b17f7dfb86)  
（重要）
</td>
<td style="border:1px solid black;">
[VBScript 5.6](https://www.microsoft.com/download/details.aspx?familyid=9a8bee82-5f7f-490e-a1eb-481f6d4fc4f5)  
(KB981350)  
（重要）  
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=7d542ac6-8a5b-4dd7-8688-2b5feb563636)  
(KB981349)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=56c8238d-8b04-4aa5-8719-40550cd7325c)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=916f1b09-e79e-4347-9fbc-c0cf07de397d)  
（中等）
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
无
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=a52225a7-6005-4f2b-8291-db20558f23f8)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=6145e2b2-36fd-4360-bd5b-2bd11890fc52)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25eeaeb3-c0a3-4a02-9912-acd0342648ba)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=0e7140bb-42d3-48b3-9f4b-d55b17770de8)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista](https://www.microsoft.com/download/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
（重要）  
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=ee5c42c6-16bb-48bf-95c2-c188bb17d04b)  
(KB981349)  
（没有严重等级<sup>[2]</sup>）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f2a37dbf-4a95-4e8d-a474-ecacd9aee690)  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=196055a6-15d1-4da8-b33d-501e69bf5176)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=9ba7468c-23a4-4994-9a5a-22e96ef586f3)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=5b7efa82-0feb-413a-9f8e-212e7432cd99)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=394c1caa-97e4-47a3-9aac-a4a88508bd31)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=b885aef4-3a5d-4c3e-bef6-5efef2965752)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](https://www.microsoft.com/download/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
（重要）  
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=ea5c5e9c-0ecd-47bc-912d-5adc00d1aa21)  
(KB981349)  
（没有严重等级<sup>[2]</sup>）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=79093796-4ea9-4c6c-92cc-3fd63c5db918)  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c1d1622-1b67-438d-aae4-1a3954974a36)  
（中等）
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
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
Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=97ffeec8-8b6d-4a30-97b0-4bff2ba5e91d)\*  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=f111735b-68b0-4bcc-9dd8-818a5eca3400)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=51c9c420-4507-4911-a8f5-82331a696882)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=8e9c04c9-898f-4ed2-949d-f4343cc0d9f6)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25e3ce7f-53a0-4049-a65c-011d2143c4c2)\*  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=dbe89813-0a45-463b-928c-1e58f7bb596a)\*\*  
(KB981349)  
（没有严重等级<sup>[2]</sup>）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=527d6376-efc9-436b-835b-219d38bb28f0)\*\*  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e29ead69-000a-4982-a25c-f3981eda381a)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=61ece7bc-e9fa-4ede-ba7d-9e5a4c64b9be)\*  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=49f9f740-023a-4291-becf-838a1d282321)\*  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=91c08251-0085-44cb-9e9c-9a1a84374caf)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=61c26a1f-c885-4474-9843-204c41628889)\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[MPEG Layer-3 编码解码器](https://www.microsoft.com/download/details.aspx?familyid=d6f2e1ae-48d3-4d2c-b329-32cff00afee5)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8b99e54d-955b-4a06-9a04-b2f4596efd72)\*  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=9db62357-557d-40cd-9826-b7baa6c9de65)\*\*  
(KB981349)  
（没有严重等级<sup>[2]</sup>）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=0c384dbc-21b7-4cbc-b68f-ced971d9b791)\*\*  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8f922e64-e3a6-46fe-9a81-b2813ea6a330)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=72e7c7ea-55ef-457b-a03a-49aa9dea2e84)\*  
（中等）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](https://www.microsoft.com/download/details.aspx?familyid=bd60779a-8bb1-4107-a344-9b09a50e96ff)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.0](https://www.microsoft.com/download/details.aspx?familyid=eb116688-1d6e-4e20-948e-1d347af5d985)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bcf8b919-08a9-487f-8dfd-3ca24328c4f3)  
（严重）
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
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b1f9746d-61a2-406f-b707-60646bd5b5bb)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.7](https://www.microsoft.com/download/details.aspx?familyid=84c5aaae-9417-42a1-834f-22c1ad46a12f)  
(KB981349)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8c48302c-a1d6-41bc-ad24-7ce7332d4842)  
（中等）
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=8d4a6c65-e171-4570-8f3f-118f06910baf)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=f0dbac52-0f0e-40bc-9371-17fa594424d5)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=389184c5-9001-497d-bdf4-81f97ecb617f)  
（严重）
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
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=ff58d80c-33ce-4d9e-aaa5-0b1841458931)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=c3f76835-0053-4e53-a451-14255e7a4fc0)  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
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
Windows 7（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=cf8c6721-05c2-4680-93b4-be36f09c6d15)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=b23efe7d-bca4-4d49-9104-6ae39dc5daa9)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=f3495dae-71f3-421d-a191-d26965f26ad1)  
（严重）
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
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7f1dc055-2ec9-407a-9e69-da12338587e3)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=998164b7-4b8c-468b-8d39-f242633c8838)  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="10" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-019**](https://technet.microsoft.com/security/bulletin/ms10-019)
</td>
<td style="border:1px solid black;">
[**MS10-020**](https://technet.microsoft.com/security/bulletin/ms10-020)
</td>
<td style="border:1px solid black;">
[**MS10-025**](https://technet.microsoft.com/security/bulletin/ms10-025)
</td>
<td style="border:1px solid black;">
[**MS10-026**](https://technet.microsoft.com/security/bulletin/ms10-026)
</td>
<td style="border:1px solid black;">
[**MS10-027**](https://technet.microsoft.com/security/bulletin/ms10-027)
</td>
<td style="border:1px solid black;">
[**MS10-021**](https://technet.microsoft.com/security/bulletin/ms10-021)
</td>
<td style="border:1px solid black;">
[**MS10-022**](https://technet.microsoft.com/security/bulletin/ms10-022)
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
</td>
<td style="border:1px solid black;">
[**MS10-029**](https://technet.microsoft.com/security/bulletin/ms10-029)
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
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=94dfdaae-8464-4de6-a401-7eb70b3bb34f)\*  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=a2979c02-2a80-4b84-bf6c-4798064bdf28)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=cd1a046e-915d-4904-b753-5a24be10c504)\*  
（严重）
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
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=28389c1d-2a12-4bef-a59b-726bb6449c8b)\*  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=c4039d40-a0c7-4183-ab50-04f690d1c5dc)\*\*  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=eb27cd2b-d514-4405-8650-259a42e35155)\*\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](https://www.microsoft.com/download/details.aspx?familyid=40f622d2-48e7-4eb2-9430-bbd218cb5208)  
(KB978601)  
（严重）  
[Cabinet File Viewer Shell Extension 6.1](https://www.microsoft.com/download/details.aspx?familyid=5e416d4b-5de7-4688-80c6-245de159e0ce)  
(KB979309)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=541e9e2f-ec1d-42b2-aae5-481c0d435169)  
（严重）
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
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=d4ea3984-5183-47f1-814e-29cb6c90ae06)  
（中等）
</td>
<td style="border:1px solid black;">
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=8174463c-5c5e-4095-90c8-fd1e898d4ba5)  
(KB981332)  
（没有严重等级<sup>[2]</sup>）
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

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关该安装选项的详细信息，请参阅 MSDN 文章[服务器核心](https://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx)和[Windows Server 2008 R2 的服务器核心](https://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx)。注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](https://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS10-022 注释**

<sup>[1]</sup>此安全更新将您安装的 VBScript 5.1 升级到 VBScript 5.6。

<sup>[2]</sup>严重等级不适用于此更新，因为此公告中讨论的漏洞不影响此软件。 但是，作为针对将来可能发现的任何新媒介的纵深防御措施，Microsoft 建议使用此软件的客户应用此安全更新。

**MS10-024 注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。 此公告涉及多个软件类别。

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
[**MS10-023**](https://technet.microsoft.com/security/bulletin/ms10-023)
</td>
<td style="border:1px solid black;">
[**MS10-028**](https://technet.microsoft.com/security/bulletin/ms10-028)
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
[Microsoft Office Publisher 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=943b3830-70d5-46c5-bffc-1b494434b5f7)  
(KB980466)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2d563cbc-d8f7-486b-8c54-25d168085376)  
(KB979364)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=7c2f4610-77bb-4d72-847b-1a06c523b137)  
(KB980469)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=803a7ea0-a9da-46dd-9548-0177d3774be7)  
(KB979356)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1 和 Microsoft Office Publisher 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=10ca2f71-0ab2-4344-b7fd-bbbd6a783a96)  
(KB980470)  
（重要）
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 Service Pack 1 和 Microsoft Office Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=56fe020f-4444-4a43-aa98-e99a622f6a69)  
(KB979365)  
（重要）
</td>
</tr>
</table>


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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS10-024**](https://technet.microsoft.com/security/bulletin/ms10-024)
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
Microsoft Exchange Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e47c90a0-c9c8-43b7-bec7-34107ddde294)  
(KB976703)  
（中等）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bc8391f8-5335-496b-ad4c-bae38509be4a)  
(KB976702)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 1（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=6a894b4e-12b6-4a91-9555-d813956b6aac)  
(KB981407)  
（没有严重等级<sup>[1]</sup>）  
[Microsoft Exchange Server 2007 Service Pack 2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=b8f7f872-16d5-49d6-9867-adc01351c06f)  
(KB981383)  
（没有严重等级<sup>[1]</sup>）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=7dcf2390-dff7-4e3a-acca-03f4d43fb79a)  
(KB981401)  
（没有严重等级<sup>[1]</sup>）
</td>
</tr>
</table>

**MS10-024 注释**

<sup>[1]</sup>严重等级不适用于此更新，因为此公告中讨论的漏洞不影响此软件。 但是，由于此安全更新包含将其他源端口平均信息量添加到 SMTP 服务启动的 DNS 事务的纵深防御措施，所以 Microsoft 建议此软件的客户应用此更新。

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

-   [Visuality Systems Ltd.](https://www.visualitynq.com/) 的 Mark Rabinovich 报告了 MS10-020 中描述的问题
-   [stratsec](https://www.stratsec.net/) 的 Laurent Gaffié 报告了 MS10-020 中描述的三个问题
-   [Hispasec](https://www.hispasec.com/)[Virustotal](https://www.virustotal.com/) 的 Matthew 'j00ru' Jurczyk 和 Gynvael Coldwind 报告了 MS10-021 中描述的五个问题
-   [Google Inc.](https://www.google.com/) 的 Tavis Ormandy 报告了 MS10-021 中描述的两个问题
-   [Obsidium Software](https://www.obsidium.de/) 的 Martin Tofall 报告了 MS10-021 中描述的问题
-   Lionel d'Hauenens 与 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 MS10-023 中描述的问题
-   [CERT-LEXSI](https://cert.lexsi.com/) 的 Fabien Perigaud 报告了 MS10-025 中描述的问题
-   [CERT-LEXSI](https://cert.lexsi.com/) 的 Fabien Perigaud、[VUPEN 漏洞调查小组](https://www.vupen.com/)、[TELUS Security Labs](https://telussecuritylabs.com/)、[Core Security Technologies](https://www.coresecurity.com/) 以及 [NSFOCUS 安全小组](https://www.nsfocus.com/)与我们合作，提供关于 MS10-025 的最初安全更新中质量问题的详细信息。
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Yamata Li 报告了 MS10-026 中描述的问题
-   一位匿名研究人员与 [TippingPoint](https://www.tippingpoint.com/) 的 [Zero Day Initiative](https://www.zerodayinitiative.com/) 合作，报告了 MS10-027 中描述的问题
-   Fortinet's [FortiGuard Labs](https://www.fortiguard.com/) 的 Bing Liu 报告了 MS10-028 中描述的两个问题
-   National EW Research & Simulation Center（隶属于 Rafael 公司）的 Gabi Nakibly 报告了 MS10-029 中描述的问题

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](https://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](https://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](https://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2010 年 4 月 13 日）： 已发布公告摘要。
-   V1.1（2010 年 4 月 14 日）： 纠正了“**摘要**”部分 MS10-025 的重新启动要求。 还纠正了 Windows Server 2008 和 Windows Server 2008 R2 的服务器核心表示，仅适用于 MS10-019 的 KB978601 更新。
-   V2.0（2010 年 4 月 21 日）： 已修订以通知客户 MS10-025 的原始安全更新不能防止此公告中描述的漏洞。 Microsoft 建议客户应用 MS10-025 中描述的变通办法之一，在修订的安全更新推出之前减轻对受影响系统的影响。
-   V3.0（2010 年 4 月 27 日）： 已修订以提供 MS10-025 的重新发布安全更新。
-   V4.0（2010 年 7 月 13 日）： 已修订以提供针对 MS10-024 重新发布的 Windows Server 2008 和 Windows Server 2008 R2 安全更新。

*Built at 2014-04-18T01:50:00Z-07:00*
