---
TOCTitle: 'MS11-FEB'
Title: 'Microsoft 安全公告摘要 (2011 年 2 月)'
ms:assetid: 'ms11-feb'
ms:contentKeyID: 61236954
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms11-feb(v=Security.10)'
---



Microsoft 安全公告摘要 (2011 年 2 月)
=====================================

发布时间: 2011年2月8日 | 更新时间: 2011年3月18日

**版本:** 4.0

本公告摘要列出了 2011 年 2 月发布的安全公告。

对于 2011 年 2 月发布的安全公告，本公告摘要替代 2011 年 2 月 3 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](http://technet.microsoft.com/security/bulletin/advance)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](http://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2011 年 2 月 9 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。 [立即注册申请收听 2 月份安全公告网络广播](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455047&eventcategory=4)。 此日期之后，此网络广播按需提供。 有关详细信息，请参阅 [Microsoft 安全公告摘要和网络广播](http://technet.microsoft.com/security/bulletin/summary)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2482017)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中两个秘密报告的漏洞和两个公开披露的漏洞。 这些漏洞可在用户使用 Internet Explorer 查看特制 Web 页面或者用户打开一个加载特制库文件的合法 HTML 文件时允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与本地用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-006">MS11-006</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 图形处理中的漏洞可能允许远程执行代码 (2483185)</strong><br />
<br />
此安全更新解决了 Windows Shell 图形处理器中一个公开披露的漏洞。 如果用户查看特制缩略图，此漏洞可能允许远程执行代码。 成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-007">MS11-007</a></td>
<td style="border:1px solid black;"><strong>OpenType Compact 字体格式 (CFF) 驱动程序中的漏洞可能允许远程代码执行 (2485376)</strong><br />
<br />
此安全更新解决了 Windows 的 OpenType Compact 字体格式 (CFF) 驱动程序中一个秘密报告的漏洞。 如果用户查看用特制 CFF 字体呈现的内容，则该漏洞可能允许远程代码执行。 在所有情况下，攻击者无法强制用户查看特制内容。 相反，攻击者必须蛊惑用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-004">MS11-004</a></td>
<td style="border:1px solid black;"><strong>Internet Information Services (IIS) FTP 服务中的漏洞可能允许远程执行代码 (2489256)</strong><br />
<br />
此安全更新解决 Microsoft Internet Information Services (IIS) FTP 服务中公开披露的漏洞。 此漏洞允许在 FTP 服务器收到特制 FTP 命令时远程执行代码。 默认情况下不会在 IIS 中安装 FTP 服务。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-005">MS11-005</a></td>
<td style="border:1px solid black;"><strong>Active Directory 中的漏洞可能允许拒绝服务 (2478953)</strong><br />
<br />
此安全更新可解决 Active Directory 中一个公开披露的漏洞。 此漏洞允许在攻击者向受影响的 Active Directory 服务器发送特制数据包时拒绝服务。 攻击者要利用此漏洞，必须在已加入域的计算机上具有有效的本地管理员特权。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visio 中的漏洞可能允许远程执行代码 (2451879)</strong><br />
<br />
此安全更新解决 Microsoft Visio 中两个秘密报告的漏洞。 如果用户打开特制的 Visio 文件，这些漏洞可能允许远程执行代码。 成功利用其中任何一个漏洞的攻击者可以获得与登录用户相同的用户权限。 那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-009">MS11-009</a></td>
<td style="border:1px solid black;"><strong>JScript 和 VBScript 脚本引擎中的漏洞可能允许信息泄露 (2475792)</strong><br />
<br />
此安全更新解决 JScript 和 VBScript 脚本引擎中的一个秘密报告的漏洞。 该漏洞可在用户访问特制网站时导致信息泄露。 攻击者无法强迫用户访问这些网站。 相反，攻击者必须诱使用户访问该网站，方法通常是让用户单击电子邮件或 Instant Messenger 消息中的链接以使用户链接到攻击者的网站。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-010">MS11-010</a></td>
<td style="border:1px solid black;"><strong>Windows 客户端/服务器运行时子系统中的漏洞可能允许特权提升 (2476687)</strong><br />
<br />  
此安全更新可解决 Windows XP 和 Windows Server 2003 中的 Microsoft Windows 客户端/服务器运行时子系统 (CSRSS) 中一个秘密报告的漏洞。<br />  
<br />
该漏洞允许在攻击者登录用户的系统并启动在攻击者注销以获取后续用户的登录凭据后继续运行的特制应用程序时发生特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;"><strong>Windows 内核中的漏洞可能允许特权提升 (2393802)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露和一个秘密报告的漏洞。 如果攻击者本地登录并运行特制应用程序，这些漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;"><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (2479628)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中秘密报告的五个漏洞。 如果攻击者本地登录并运行特制应用程序，这些漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据并能本地登录才能利用这些漏洞。 匿名用户无法利用这些漏洞，也无法以远程方式利用这些漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;"><strong>Kerberos 中的漏洞可能允许特权提升 (2496930)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中的一个秘密报告的漏洞和一个公开披露的漏洞。 如果通过身份验证的本地攻击者在已加入域的计算机上安装恶意服务，则更加严重的这些漏洞可导致特权提升。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-014">MS11-014</a></td>
<td style="border:1px solid black;"><strong>本地安全机构子系统服务中的漏洞可能允许本地特权提升 (2478960)</strong><br />
<br />  
此安全更新可解决 Windows XP 和 Windows Server 2003 中的本地安全授权子系统服务 (LSASS) 中一个秘密报告的漏洞。<br />  
<br />
此漏洞在攻击者登录系统并运行特制应用程序时允许提升特权。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 匿名用户无法利用此漏洞，也无法以远程方式利用此漏洞。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按利用评估级别 和 CVE ID 降序顺序列出。 仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解安全公告发布 30 天内为您可能需要安装的每个安全更新发布有效漏洞检测代码的可能性。 您应该根据您的特定配置，检查下面的每个评估，从而确定部署的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](http://technet.microsoft.com/en-us/security/cc998259.aspx)。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-006">MS11-006</a></td>
<td style="border:1px solid black;">Windows Shell 图形处理溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3970">CVE-2010-3970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><strong>此漏洞已公开披露，可提供漏洞检测代码</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">CSS 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3971">CVE-2010-3971</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><strong>此漏洞已公开披露，正在 Internet 生态系统中被利用</strong></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;">驱动程序与 Windows 内核交互不当漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4398">CVE-2010-4398</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><strong>此漏洞已公开披露</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-010">MS11-010</a></td>
<td style="border:1px solid black;">CSRSS 特权提升漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0030">CVE-2011-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">未初始化的内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0035">CVE-2011-0035</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-003">MS11-003</a></td>
<td style="border:1px solid black;">未初始化的内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0036">CVE-2011-0036</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-014">MS11-014</a></td>
<td style="border:1px solid black;">LSASS 长度验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0039">CVE-2011-0039</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;">Kerberos Unkeyed 校验和漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0043">CVE-2011-0043</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;"><strong>此漏洞已公开披露</strong></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-011">MS11-011</a></td>
<td style="border:1px solid black;">Windows 内核整数截断漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0045">CVE-2011-0045</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 不正确用户输入验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0086">CVE-2011-0086</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 不充分用户输入验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0087">CVE-2011-0087</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 窗口类指针混乱漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0088">CVE-2011-0088</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 窗口类不正确指针验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0089">CVE-2011-0089</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-012">MS11-012</a></td>
<td style="border:1px solid black;">Win32k 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0090">CVE-2011-0090</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;">Visio 对象内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0092">CVE-2011-0092</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-008">MS11-008</a></td>
<td style="border:1px solid black;">Visio 数据类型内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0093">CVE-2011-0093</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - 可能的一致漏洞检测代码</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-004">MS11-004</a></td>
<td style="border:1px solid black;">IIS FTP 服务堆缓冲区溢出漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3972">CVE-2010-3972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;"><strong>此漏洞已公开被披露，可提供 PoC 代码</strong></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-007">MS11-007</a></td>
<td style="border:1px solid black;">OpenType 字体编码字符漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0033">CVE-2011-0033</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - 漏洞检测代码可能不一致</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-009">MS11-009</a></td>
<td style="border:1px solid black;">脚本引擎信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0031">CVE-2011-0031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-005">MS11-005</a></td>
<td style="border:1px solid black;">Active Directory SPN 验证漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0040">CVE-2011-0040</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;"><strong>此漏洞已公开披露</strong><br />
<br />
这是一个拒绝服务漏洞</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-013">MS11-013</a></td>
<td style="border:1px solid black;">Kerberos 欺骗漏洞</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0091">CVE-2011-0091</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – 漏洞检测代码可能不正常</td>
<td style="border:1px solid black;">这只是一个欺骗漏洞</td>
</tr>  
</tbody>  
</table>
  
受影响的软件和下载位置  
----------------------
  
  
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
</tr>  
<tr>  
<th colspan="12" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=ae343de6-ec61-4891-b136-cfc4234d97d9)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=85bf88b7-2dd9-4204-8492-b2c1d8d2264e)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c72fbb97-2313-45f6-842d-99db373822dd)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=bbea7ead-6c5c-4da8-aa03-a40325fd2de3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f86e9e64-801a-431a-b24e-772011dfa66d)  
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=cfa10178-9859-4e03-bedc-e3f5297a0251)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=a511d33a-9ae0-46ee-a225-9d97390de7d1)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=56f4f43e-c313-49dc-a278-e3e8a83a907e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=486d1969-6814-4556-8dc0-5bfbaee528b0)  
(KB2478971)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=541f228f-79b3-402a-8ff9-366c1e595227)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d431100d-a627-4ea0-b75b-2d4157e38df2)  
（严重）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=a795de21-13f4-4035-a4d5-4257ddc92fe7)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=69dfa24b-7c56-4521-850c-1485b062154a)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=bcb7217e-624a-4d61-86a1-f2440a1afd57)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=074396f0-a68c-4190-8dac-0b883d56e3f1)  
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9f0b7b77-5b90-4a4b-97a4-0c1ce6a70126)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e7273a85-ce96-464b-8c4f-2710701213e3)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e80db313-b470-4d71-bc34-70bfbfb6579f)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a210c796-7077-4617-a9a8-9ea99fe11a5e)  
(KB2478971)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=82189bf2-3f34-4949-92da-eea98036d18e)  
（重要）
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
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
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5e0f4bf2-f727-483a-af3a-9a2abf0c36bb)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=45e504d4-c17d-4b73-b08e-d9c0cb3f4918)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=74238e08-fae2-4f17-ac72-681226a53a40)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2aa94528-5063-427b-97f7-2a0a55cbb6bf)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a99c2b13-db81-4f18-9cf7-c20614ba0132)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=651c1f4f-4e69-4d17-8aa2-72681dfc5463)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aed08b96-24cc-4e23-8fd5-c7e52f8ef41a)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6bf2eeec-8225-477f-a606-263d3ee434d6)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=54fe2669-8a63-4d96-8b82-5b10f45b293e)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8a1e2675-0bf0-4d94-b48a-6e846dd6d9f5)  
(KB2478971)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4e31e6b1-577e-468e-9c94-67227d2273c2)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=0592b520-88d1-45bc-8b15-d3f0c8fa2181)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=29adcfb5-540f-4980-b2ca-9a22aa7bba13)  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ebef4869-9812-46ce-9c01-2fb8c866ec90)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6e740922-6ce4-46ec-a35e-e94201a9e398)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aeed45fb-9395-4c2b-a674-e38b04fe0914)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=ec962b0e-e951-4e70-8d97-8c2afd360c28)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ca7879e1-e295-445d-a658-0a31be1928cc)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ec544894-ee98-4a2b-ac4d-33b0c3754213)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4632e1ce-6ae8-431c-9104-9a8840e5ac63)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e79bbbd4-8d5a-4c4c-8427-21c14400f041)  
(KB2478971)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76e3c229-d812-433c-ad05-7cbd1f9c6a6d)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=b2298b32-238a-4970-bc1f-2ede51a6c361)  
（中等）  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c41a0094-204b-4d05-ab39-a32915201af1)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a4f9ec46-35b2-44c9-abf6-647f7a474b99)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=bc09e42b-2eed-41b3-a03f-cb8cc94adfee)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Active Directory](https://www.microsoft.com/download/details.aspx?familyid=4ac66eae-e6d8-4e8b-b4ea-e7a77cc74db0)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=50855101-a15c-4c81-ad81-a7fe3f1d2026)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=fcd48499-1bb4-4304-b9cc-27d9d92e11cd)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a09c3e6e-c55c-492a-b7ad-3e3d35711643)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=856fbcc2-ead9-4ec1-92dd-988e6d22dae9)  
(KB2478971)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=a0cde8d8-7c85-4fcb-bcf7-205064970b41)  
（重要）
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=b176777e-4897-4cf1-9fc0-dd608930bb4c)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=77971c3c-55ec-4a9c-bcb8-8fb8c61431e3)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0c18ecca-afb9-4738-bc7b-76a0e815dfb8)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d60a2098-7351-4fce-83b2-2c1c3a24faa0)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=c09ccc72-8f94-416b-9a7f-ed16e90342a2)<sup>[1]</sup>  
（重要）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=da9b7982-1c6b-45ac-8dd0-d7101bb83949)<sup>[1]</sup>  
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
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=66978514-bb7f-42cc-9360-2fd1c686f4e6)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 和 Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6fb7ebcc-2052-457b-b5bc-1bbcb17696b9)  
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=20ad0136-c6df-4c7b-811f-d6b3dd9e2c56)  
（严重）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d3580784-aada-4118-b7f2-3a23aec2ed04)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=62dc454f-4b1e-4ac0-8ffe-6c73112f8d4d)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=065ad8fe-1caf-488e-a2e1-96db29f2fa57)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=e88d072f-0f5f-4c85-ad2f-91b9b8bf6b3a)<sup>[1]</sup>  
（重要）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=6e4b9878-b5d2-4025-8839-b41515932cf2)<sup>[1]</sup>  
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
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8fdb8c37-1b22-457b-bdc0-21f6a5061dd3)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 和 Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88d68757-1ab0-4585-9578-52a474b10882)  
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
<th colspan="12" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
无
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
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ee61f0dd-9797-4e11-8281-a05b201d0c0b)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ef1ae382-8835-4f60-83bd-e84a3400d55c)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=253c47a0-69ac-437a-ad3e-778c37fa37cb)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=88ba83b9-c14e-499a-8335-04bac1c49c0c)\*  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=3cc55af7-5cd9-4923-8ec5-462ff201d734)<sup>[1]</sup>\*  
（重要）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=4dfa0a25-b7e3-4fb6-a351-58ec3f8a8435)<sup>[1]</sup>\*  
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
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b37418a-e044-415e-b566-4507f157934a)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于 32 位系统）和 Windows Server 2008（用于 32 位系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=80494972-db45-475f-97cd-dac46b9486a1)\*  
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
Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=558bc86a-a49d-4d6c-b5e4-f12956f6b61b)\*\*  
（中等）  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=5607df02-93fa-45fe-a928-e5f6329851f3)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ec7101aa-96c2-4931-a3e4-0c55cbc74d9c)\*\*  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c74d7f4-6372-4809-89b8-c79b05e54cdd)\*  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.0 的 Microsoft FTP Service 7.0](https://www.microsoft.com/download/details.aspx?familyid=f485b30d-dcaf-47c3-ac62-982b14670a1f)<sup>[1]</sup>\*  
（重要）  
[用于 IIS 7.0 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=a98a74c1-0c91-446d-b822-fe57ff06d90b)<sup>[1]</sup>\*  
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
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=163d3aca-3703-452e-b1cb-73932e2bcf8c)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 x64 的系统）和 Windows Server 2008（用于基于 x64 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5597d449-17e3-440f-8b0e-56a902a96569)\*  
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
Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8c2abba5-0597-4565-9b87-a37e574690e0)  
（中等）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e62493cb-8d25-4975-bbe6-a368e039872b)  
（严重）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=91d5d34b-9d7e-4e83-89a4-f1aa388dc4e4)  
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
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=55b07bc0-dff5-4cd7-87c9-c08e5a49197d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008（用于基于 Itanium 的系统）和 Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d10eda21-b3c3-4d8e-8596-bc45e4165f93)  
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
<th colspan="12" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=07aa7ffc-47c7-4611-b32c-ecb3fbcad32f)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=1da57fbc-9ea4-4fc4-911d-d5c7825e012c)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=9dabd1d1-3f1e-46d1-b171-aafd3f08d291)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）](https://www.microsoft.com/download/details.aspx?familyid=e1224c90-b0bc-4e4b-999a-efae327213b4)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=078fe6c0-1b2c-4896-a345-25cc1b1105e2)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于 32 位系统）和 Windows 7（用于 32 位系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=ffed7c76-0b75-4f57-9b63-3961a8b449f6)  
(KB2425227)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2b8ffafe-78bb-4fa7-aea2-01208b6a3dfe)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=587adb89-2f6a-4893-9906-b6d6d9ada2bd)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=66fb4efe-bcd3-4e90-8e35-b013e014a952)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
（重要）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=ddcf352e-742c-485e-9ed5-19cdba673562)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b42642b3-fb78-4700-bfe8-bfa997b90c16)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows 7（用于基于 x64 的系统）和 Windows 7（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c26cebcf-683f-4a51-be75-76535fb979a7)  
(KB2425227)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="12" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-003**](http://technet.microsoft.com/security/bulletin/ms11-003)
</td>
<td style="border:1px solid black;">
[**MS11-006**](http://technet.microsoft.com/security/bulletin/ms11-006)
</td>
<td style="border:1px solid black;">
[**MS11-007**](http://technet.microsoft.com/security/bulletin/ms11-007)
</td>
<td style="border:1px solid black;">
[**MS11-004**](http://technet.microsoft.com/security/bulletin/ms11-004)
</td>
<td style="border:1px solid black;">
[**MS11-005**](http://technet.microsoft.com/security/bulletin/ms11-005)
</td>
<td style="border:1px solid black;">
[**MS11-009**](http://technet.microsoft.com/security/bulletin/ms11-009)
</td>
<td style="border:1px solid black;">
[**MS11-010**](http://technet.microsoft.com/security/bulletin/ms11-010)
</td>
<td style="border:1px solid black;">
[**MS11-011**](http://technet.microsoft.com/security/bulletin/ms11-011)
</td>
<td style="border:1px solid black;">
[**MS11-012**](http://technet.microsoft.com/security/bulletin/ms11-012)
</td>
<td style="border:1px solid black;">
[**MS11-013**](http://technet.microsoft.com/security/bulletin/ms11-013)
</td>
<td style="border:1px solid black;">
[**MS11-014**](http://technet.microsoft.com/security/bulletin/ms11-014)
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
无
</td>
<td style="border:1px solid black;">
[**严重**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
无
</td>
<td style="border:1px solid black;">
[**中等**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
无
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=38b67efb-dd4b-4e8c-8460-0f40f0367441)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=638318ed-4000-4b1a-bb4b-65b795f59784)\*  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=1e075f57-1723-4933-9b8e-7bce4a44a1c1)\*  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
（中等）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285)\*\*  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）](https://www.microsoft.com/download/details.aspx?familyid=70f5056a-72ad-46ff-a43f-ee151639b9a7)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d2c53f44-12eb-4293-9fa5-2a14075b636e)\*  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 x64 的系统）和 Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=46bb3ef1-24c3-41cb-8141-0fdbd85093f7)\*  
(KB2425227)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=0e41cbe5-5e5e-4ece-a71a-71f4b6319f0d)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4688ea0d-a467-4f24-ac52-104d05c8cae8)  
（严重）
</td>
<td style="border:1px solid black;">
[用于 IIS 7.5 的 Microsoft FTP Service 7.5](https://www.microsoft.com/download/details.aspx?familyid=bfddd539-c64f-4467-88ee-6bdfe645b478)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[JScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
（中等）  
[VBScript 5.8](https://www.microsoft.com/download/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）](https://www.microsoft.com/download/details.aspx?familyid=1646b3a5-714f-4ea5-b109-566fa9b933b6)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8c6bf720-f544-4f58-9b1c-2399957ec43d)  
（重要）
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2（用于基于 Itanium 的系统）和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=01737933-e7de-451b-b02f-b7ca24693965)  
(KB2425227)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**Windows Server 2008 和 Windows Server 2008 R2 的注释**

**\*服务器核心安装受到影响。** 此更新适用于 Windows Server 2008 或 Windows Server 2008 R2 的受支持版本，严重等级相同，无论是否使用“服务器核心”安装选项进行了安装。 有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。 注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**\*\*服务器核心安装不受影响。** 如果使用服务器核心安装选项安装如上所述的 Windows Server 2008 或 Windows Server 2008 R2，则此更新所解决的漏洞不会影响其的受支持版本。 有关此安装选项的详细信息，请参阅 TechNet 文章[管理服务器核心安装](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)和[服务服务器核心安装](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx)。 注意，服务器核心安装选项不适用于 Windows Server 2008 和 Windows Server 2008 R2 的某些版本；请参阅[比较服务器核心安装选项](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx)。

**MS11-004 注释**

<sup>[1]</sup>不是此操作系统的默认 FTP 服务

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
Microsoft Office 程序
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS11-008**](http://technet.microsoft.com/security/bulletin/ms11-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=273d8078-0dc7-43d8-bcae-54c811e49e0e)  
(KB2434711)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f1067eaa-d18d-4bff-a02e-1d990c36ca7f)  
(KB2434733)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=097a642b-b786-4724-a907-79f37cded836)  
(KB2434737)  
（重要）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。 有关详细信息，请参阅 [TechNet 更新管理中心](http://go.microsoft.com/fwlink/?linkid=69903)。 [TechNet 安全中心](http://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。 消费者可以访问[家庭安全](http://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“最新的安全更新”访问此信息。

安全更新可从 [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) 获得。 [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。 有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](http://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。 Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。 通过使用安全公告编号（例如“MS07-036”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。 有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](http://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。 该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。 有关详细信息，请参阅 [Microsoft 知识库文章 961747](http://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)。

**System Center Configuration Manager 2007**

Configuration Manager 2007 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。 通过 Configuration Manager 2007，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

Configuration Manager 2007 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。 Configuration Manager 2007 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。 有关管理员如何使用 Configuration Manager 2007 部署更新的详细信息，请参阅[软件更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)。 有关 Configuration Manager 的详细信息，请访问 [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)。 SMS 的下一版本 System Center Configuration Manager 2007 现已可用；请参阅前面的部分 **System Center Configuration Manager 2007**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en)。 有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx)。

**注意** SMS 使用 Microsoft 基准安全分析器提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。 这可触发不兼容并使安全更新的部署占用更多的时间。 通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en)中包含的[更新兼容性评估程序](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Microsoft Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。

#### MU、WU 和 WSUS 上的非安全更新

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

-   [Trend Micro](http://www.trendmicro.com) 的 Yuki Chen 关于 MS11-003 中所述问题的报告
-   [Google Inc.](http://www.google.com/) 的 SkyLined 关于 MS11-003 中所述问题的报告
-   [Fortinet FortiGuard Labs](http://www.fortiguard.com/) 的 Haifei Li 报告了 MS11-003 中描述的问题
-   Kobi Pariente 和 Yaniv Miron 与 [VeriSign iDefense Labs](http://labs.idefense.com/) 关于 MS11-006 中所述问题的联合报告
-   Procyun 与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 关于 MS11-008 中所述问题的联合报告
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Xin Ouyang 关于 MS11-008 中所述两个问题的报告
-   [Palo Alto Networks](http://www.paloaltonetworks.com/) 的 Yamata Li 关于 MS11-009 中所述问题的报告
-   [北京大学信息安全部](http://www.ss.pku.edu.cn/en/)的 Sihan Qing（教授）、Weiping Wen（助理教授）、Liang Yin 和 Husheng Zhou（研究生）关于 MS11-010 中所述问题的报告
-   [360safe](http://www.360.cn) 的 Zhengwenbin 关于 MS11-011 中所述问题的报告
-   Guo Bojun 关于 MS11-011 中所述问题的报告
-   Wei Zhang 关于 MS11-011 中所述问题的报告
-   [Prevx](http://www.prevx.com/) 的 Marco Giuliani 与我们关于 MS11-011 中所述问题的联合报告
-   std\_logic 与 [TippingPoint](http://www.tippingpoint.com/) 的 [Zero Day Initiative](http://www.zerodayinitiative.com/) 关于 MS11-011 中所述问题的联合报告
-   [Norman](http://www.norman.com) 的 Tarjei Mandt 关于 MS11-012 中所述五个问题的报告
-   [The MIT Kerberos Team](http://web.mit.edu/kerberos) 关于 MS11-013 中所述问题的报告
-   [iSEC Partners](http://www.isecpartners.com/) 的 Scott Stender 关于 MS11-013 中所述问题的报告
-   Primavera BSS 的安全测试员 Jorge Moura 关于 MS11-014 中所述问题的报告

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](http://go.microsoft.com/fwlink/?linkid=21742)。
-   美国和加拿大的客户可以通过[安全支持](http://go.microsoft.com/fwlink/?linkid=21131)或 1-866-PCSAFETY 获得技术支持。 与安全更新有关的电话支持服务是免费的。 有关可用支持选项的详细信息，请参阅 [Microsoft 帮助和支持](http://support.microsoft.com/)网站。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 联系方面的详细信息，请访问[国际帮助和支持](http://go.microsoft.com/fwlink/?linkid=21155)。

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2011 年 2 月 8 日）： 已发布公告摘要。
-   V1.1（2011 年 2 月 9 日）： 对于 MS11-013，将 CVE-2011-0091 的利用指数评估更正为“3 – 不太可能被利用的代码”。 这仅仅是一个信息更改。
-   V2.0（2011 年 3 月 8 日）： 对于 MS11-003、MS11-004、MS11-007 和 MS11-009，阐明了受影响的软件包括 Windows 7（用于 32 位系统）Service Pack 1、Windows 7（用于基于 x64 的系统）Service Pack 1、Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1 和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1。有关详细信息，请参阅这些公告的更新常见问题。
-   V3.0（2011 年 3 月 16 日）： 对于 MS11-013，阐明了受影响的软件包括 Windows 7（用于 32 位系统）Service Pack 1、Windows 7（用于基于 x64 的系统）Service Pack 1、Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1 和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1。有关详细信息，请参阅此公告的更新常见问题。
-   V4.0（2011 年 3 月 18 日）： 对于 MS11-012，阐明了受影响的软件包括 Windows 7（用于 32 位系统）Service Pack 1、Windows 7（用于基于 x64 的系统）Service Pack 1、Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1 和 Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1。有关详细信息，请参阅此公告的更新常见问题。

*Built at 2014-04-18T01:50:00Z-07:00*
