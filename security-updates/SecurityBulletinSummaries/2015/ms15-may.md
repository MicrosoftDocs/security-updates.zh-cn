---
TOCTitle: 'MS15-MAY'
Title: 'Microsoft 安全公告摘要（2015 年 5 月）'
ms:assetid: 'ms15-may'
ms:contentKeyID: 65633689
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-may(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 5 月）
======================================

发布日期： 2015 年 5 月 12 日

**版本：** 1.0

本公告摘要列出了 2015 年 5 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级<br />
和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积性安全更新 (3049563)</strong> <br />
此安全更新可解决 Internet Explorer 中的漏洞。 最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。 成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-044">MS15-044</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 字体驱动程序中的漏洞可能允许远程执行代码 (3057110)</strong><br />
此安全更新可修复 Microsoft Windows、Microsoft .NET Framework、Microsoft Office、Microsoft Lync 和 Microsoft Silverlight 中的漏洞。 如果用户打开经特殊设计的文档或者访问嵌入了 TrueType 字体的不受信任网页，则这些漏洞中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3057110">3057110</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework，<br />  
Microsoft Office，<br />  
Microsoft Lync，<br />
Microsoft Silverlight</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 日记本中的漏洞可能允许远程执行代码 (3046002)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果用户打开经特殊设计的日记文件，漏洞可能允许远程执行代码。 与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-046">MS15-046</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3057181)<br />
</strong>此安全更新可修复 Microsoft Office 中的漏洞。 最严重的漏洞可能在用户打开经特殊设计的 Microsoft Office 文件时允许远程执行代码。 成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。 与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-047">MS15-047</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft SharePoint Server 中的漏洞可能允许远程执行代码 (3058083)<br />
</strong>此安全更新可修复 Microsoft Office 服务器软件中的漏洞。 如果经过身份验证的攻击者向 SharePoint 服务器发送经特殊设计的页面内容，则这些漏洞可能允许远程执行代码。 成功利用这些漏洞的攻击者可以在目标 SharePoint 站点的 W3WP 服务帐户的安全上下文中运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Server 软件</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-048">MS15-048</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 中的漏洞可能允许特权提升 (3057134)</strong><br />
此安全更新可解决 Microsoft .NET Framework 中的漏洞。 如果用户安装经特殊设计的部分信任应用程序，则最严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-049">MS15-049</a></p></td>
<td style="border:1px solid black;"><p><strong>Silverlight 中的漏洞可能允许特权提升 (3058985)</strong><br />
此安全更新可修复 Microsoft Silverlight 中的漏洞。 如果经特殊设计的 Silverlight 应用程序在受影响的系统上运行，则漏洞可能允许特权提升。 若要利用此漏洞，攻击者必须先登录到系统，或诱使登录用户执行经特殊设计的应用程序。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Silverlight</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-050">MS15-050</a></p></td>
<td style="border:1px solid black;"><p><strong>服务控制管理器中的漏洞可能允许特权提升 (3055642)</strong><br />
此安全更新可解决 Windows 服务控制管理器 (SCM) 中的漏洞，当 SCM 未正确验证模拟级别时会出现此漏洞。 如果攻击者先登录系统，然后运行旨在提升特权的经特殊设计的应用程序，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (3057191)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者在本地登录并可以在内核模式下运行任意代码，最严重的漏洞可能允许特权提升。 攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。 远程或匿名用户无法利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-052">MS15-052</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核中的漏洞可能允许绕过安全功能 (3050514)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果攻击者登录受影响的系统并运行经特殊设计的应用程序，此漏洞可能允许安全功能绕过。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/zh-cn/kb/3050514">3050514</a></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-053">MS15-053</a></p></td>
<td style="border:1px solid black;"><p><strong>JScript 和 VBScript 脚本引擎中的漏洞可能允许安全功能绕过 (3057263)<br />
</strong>此安全更新可解决 Microsoft Windows 中 JScript 和 VBScript 脚本引擎的 ASLR 安全功能绕过漏洞。 攻击者可以将其中一个 ASLR 绕过漏洞与另一个漏洞（如远程执行代码漏洞）组合使用，在目标系统更可靠地运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-054">MS15-054</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 管理控制台文件格式中的漏洞可能允许拒绝服务 (3051768)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。 如果未经身份验证的远程攻击者诱使用户打开包含经特殊设计的 .msc 文件的共享，此漏洞可能允许拒绝服务。 但是，攻击者无法强迫用户访问共享或查看文件。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-055">MS15-055</a></p></td>
<td style="border:1px solid black;"><p><strong>Schannel 中的漏洞可能允许信息泄漏 (3061518)<br />
</strong>此安全更新可修复 Microsoft Windows 中的漏洞。 当安全通道 (Schannel) 允许在加密的 TLS 会话中使用 512 位弱 Diffie-Hellman ephemeral (DHE) 密钥长度时，此漏洞可能允许信息泄漏。 允许 512 位 DHE 密钥会使 DHE 密钥交换变弱并容易受到各种攻击。 服务器需要支持 512 位 DHE 密钥长度，攻击才会得逞；Windows 服务器默认配置情况下允许的密钥长度最短为 1024 位。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3061518">3061518</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
<col width="16%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID              </strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估<br />
</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务<br />
利用评估</strong></p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1658">CVE-2015-1658</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>VBScript ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1685">CVE-2015-1685</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>VBScript 和 JScript ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1688">CVE-2015-1688</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1689">CVE-2015-1689</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1691">CVE-2015-1691</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 剪贴板信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1692">CVE-2015-1692</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1694">CVE-2015-1694</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1703">CVE-2015-1703</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1704">CVE-2015-1704</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1705">CVE-2015-1705</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1706">CVE-2015-1706</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1708">CVE-2015-1708</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1709">CVE-2015-1709</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1710">CVE-2015-1710</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1711">CVE-2015-1711</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1712">CVE-2015-1712</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1713">CVE-2015-1713</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1714">CVE-2015-1714</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1717">CVE-2015-1717</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-043">MS15-043</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1718">CVE-2015-1718</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-044">MS15-044</a></p></td>
<td style="border:1px solid black;"><p>OpenType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1670">CVE-2015-1670</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-044">MS15-044</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1671">CVE-2015-1671</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1675">CVE-2015-1675</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1695">CVE-2015-1695</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1696">CVE-2015-1696</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1697">CVE-2015-1697</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1698">CVE-2015-1698</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-045">MS15-045</a></p></td>
<td style="border:1px solid black;"><p>Windows 日记本远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1699">CVE-2015-1699</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-046">MS15-046</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1682">CVE-2015-1682</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-046">MS15-046</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1683">CVE-2015-1683</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-047">MS15-047</a></p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint 页面内容漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1700">CVE-2015-1700</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-048">MS15-048</a></p></td>
<td style="border:1px solid black;"><p>.NET XML 解密拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1672">CVE-2015-1672</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-048">MS15-048</a></p></td>
<td style="border:1px solid black;"><p>Windows 窗体特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1673">CVE-2015-1673</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-049">MS15-049</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Silverlight 脱离浏览器应用程序漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1715">CVE-2015-1715</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-050">MS15-050</a></p></td>
<td style="border:1px solid black;"><p>服务控制管理器特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1702">CVE-2015-1702</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1676">CVE-2015-1676</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1677">CVE-2015-1677</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1678">CVE-2015-1678</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1679">CVE-2015-1679</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1680">CVE-2015-1680</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-051">MS15-051</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1701">CVE-2015-1701</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-052">MS15-052</a></p></td>
<td style="border:1px solid black;"><p>Windows 内核安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1674">CVE-2015-1674</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-053">MS15-053</a></p></td>
<td style="border:1px solid black;"><p>VBScript ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-053">MS15-053</a></p></td>
<td style="border:1px solid black;"><p>VBScript 和 JScript ASLR 绕过</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-054">MS15-054</a></p></td>
<td style="border:1px solid black;"><p>Microsoft 管理控制台文件格式拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1681">CVE-2015-1681</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>临时</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-055">MS15-055</a></p></td>
<td style="border:1px solid black;"><p>SChannel 信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1716">CVE-2015-1716</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件（表 1-2）

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                             

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                          

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
（中等）  
Internet Explorer 7  
(3049563)  
（中等）  
Internet Explorer 8  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048073)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(3023211)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
（无更新；参阅“注释”）  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
（中等）  
Internet Explorer 7  
(3049563)  
（中等）  
Internet Explorer 8  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048073)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
（无更新；参阅“注释”）  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
（中等）  
Internet Explorer 7  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
（无更新；参阅“注释”）  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
（严重）  
Internet Explorer 8  
(3049563)  
（严重）  
Internet Explorer 9  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
（严重）  
Internet Explorer 8  
(3049563)  
（严重）  
Internet Explorer 9  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
（中等）  
Internet Explorer 8  
(3049563)  
（中等）  
Internet Explorer 9  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
（中等）  
Internet Explorer 8  
(3049563)  
（中等）  
Internet Explorer 9  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
（严重）  
Microsoft .NET Framework 4  
(3048074)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
（严重）  
Internet Explorer 9  
(3049563)  
（严重）  
Internet Explorer 10  
(3049563)  
（严重）  
Internet Explorer 11  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3048070)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3032655)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
（严重）  
Internet Explorer 9  
(3049563)  
（严重）  
Internet Explorer 10  
(3049563)  
（严重）  
Internet Explorer 11  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3048070)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3032655)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
（中等）  
Internet Explorer 9  
(3049563)  
（中等）  
Internet Explorer 10  
(3049563)  
（中等）  
Internet Explorer 11  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3048070)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3032655)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3032655)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
（重要）  
Microsoft .NET Framework 3.5  
(3035486)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
（重要）  
Microsoft .NET Framework 3.5  
(3035486)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048072)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
（重要）  
Microsoft .NET Framework 3.5  
(3035487)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048072)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
（重要）  
Microsoft .NET Framework 3.5  
(3035487)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048071)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
（重要）  
Microsoft .NET Framework 3.5  
(3035486)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048072)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
（重要）  
Microsoft .NET Framework 3.5  
(3035487)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046002)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://technet.microsoft.com/zh-cn/library/security/ms15-043)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://technet.microsoft.com/zh-cn/library/security/ms15-045)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://technet.microsoft.com/zh-cn/library/security/ms15-048)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://technet.microsoft.com/zh-cn/library/security/ms15-050)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3045171)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3048070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
（重要）  
Microsoft .NET Framework 3.5.1  
(3032655)  
（重要）  
Microsoft .NET Framework 4  
(3023221)  
（重要）  
Microsoft .NET Framework 4  
(3032662)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3055642)  
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
Windows Server 2012（服务器核心安装）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048071)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
（重要）  
Microsoft .NET Framework 3.5  
(3035486)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
（重要）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3055642)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3045171)  
（严重）  
Microsoft .NET Framework 3.5  
(3048072)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
（重要）  
Microsoft .NET Framework 3.5  
(3035487)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
（重要）  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3055642)  
（重要）

</td>
</tr>
</table>

**MS15-044 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

更新还适用于 Microsoft .NET Framework 4.6 RC，仅通过 [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供。

**MS15-043、MS15-044 和 MS15-045 注释**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。 建议运行这些操作系统的客户通过 [Windows 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)应用这些更新。

**MS15-050 注释**

Windows Server 2003 会受到影响，但是未对其发布更新。 请参阅公告以了解详细信息。

** **

### Windows 操作系统和组件（表 2-2）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                      

</td>
<td style="border:1px solid black;">
**无**                                             

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                      

</td>
<td style="border:1px solid black;">
**无**                                             

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                      

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6  
(3050946)  
（重要）  
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6  
(3050946)  
（重要）  
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.6 和 VBScript 5.6  
(3050946)  
（重要）  
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://technet.microsoft.com/zh-cn/library/security/ms15-051)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://technet.microsoft.com/zh-cn/library/security/ms15-052)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://technet.microsoft.com/zh-cn/library/security/ms15-053)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://technet.microsoft.com/zh-cn/library/security/ms15-054)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://technet.microsoft.com/zh-cn/library/security/ms15-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.7 和 VBScript 5.7  
(3050945)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.8 和 VBScript 5.8  
(3050941)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3061518)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3045171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3050514)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3051768)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3061518)  
（重要）

</td>
</tr>
</table>

**MS15-053 和 MS15-054 注释：**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。 建议运行这些操作系统的客户通过 [Windows 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)应用这些更新。

 

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-cn/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）  
(2760412)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）  
(2760412)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-cn/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
（重要）  
Microsoft SharePoint Server 2010 Service Pack 2  
(2956192)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://technet.microsoft.com/zh-cn/library/security/ms15-047)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3039736)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3054792)  
（重要）

</td>
</tr>
</table>

**MS15-046 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2883029)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2965282)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2881073)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2965311)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2999412)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2965242)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(2965240)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(2999420)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2965237)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2881073)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2965311)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2999412)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2965242)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(2965240)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(2999420)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2965237)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(2975808)  
（重要）  
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(2986216)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（32 位版本）  
(2975816)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(2965307)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(2975808)  
（重要）  
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(2986216)  
（重要）  
Microsoft PowerPoint 2013 Service Pack 1（64 位版本）  
(2975816)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(2965307)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2975808)  
（重要）  
Microsoft Excel 2013 RT Service Pack 1  
(2986216)  
（重要）  
Microsoft PowerPoint 2013 RT Service Pack 1  
(2975816)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(2965307)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft Office for Mac 2011  
(3048688)  
（重要）  
Microsoft Excel for Mac 2011  
(3048688)  
（重要）  
Microsoft PowerPoint for Mac 2011  
(3048688)  
（重要）  
Microsoft Word for Mac 2011  
(3048688)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(2956195)  
（重要）

</td>
</tr>
</table>

**MS15-044 和 MS15-046 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office Services 和 Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2965233)  
（重要）  
Excel Services  
(2956194)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3023055)  
（重要）  
Excel Services  
(3039725)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(2956140)  
（重要）  
Microsoft Excel Web Apps 2010 Service Pack 2  
(2956193)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://technet.microsoft.com/zh-cn/library/security/ms15-046)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3039748)  
（重要）

</td>
</tr>
</table>

**MS15-046 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3051467)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(3051464)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(3051464)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级别安装）  
(3051465)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(3051466)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3039779)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)  
(3039779)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)  
(3039779)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)  
(3039779)  
（严重）

</td>
</tr>
</table>

**MS15-044 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://technet.microsoft.com/zh-cn/library/security/ms15-044)

</td>
<td style="border:1px solid black;">
[**MS15-049**](https://technet.microsoft.com/zh-cn/library/security/ms15-049)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3056819)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3056819)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3056819)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3056819)  
（重要）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3056819)  
（重要）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3056819)  
（重要）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3056819)  
（重要）

</td>
</tr>
</table>

**MS15-044 注释**

此公告涉及多个软件类别。 请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 专业人员安全解决方案： [TechNet 安全性疑难解答与支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持： [国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 5 月 12 日）： 已发布公告摘要。

*页面生成时间：2015-05-19 13:28Z-07:00。*
