---
TOCTitle: 'MS15-MAR'
Title: 'Microsoft 安全公告摘要（2015 年 3 月）'
ms:assetid: 'ms15-mar'
ms:contentKeyID: 64978251
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-mar(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 3 月）
======================================

发布日期：2015-3-10

**版本：** 1.0

本公告摘要列出了 2015 年 3 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><p><strong>重启要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>已知<br />
问题</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的<br />
软件</strong></p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3032359)</strong><br />
此安全更新可解决 Internet Explorer 中的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-019">MS15-019</a></p></td>
<td style="border:1px solid black;"><p><strong>VBScript 脚本引擎中的漏洞可能允许远程执行代码 (3040297)</strong><br />
此安全更新可解决 Microsoft Windows 的 VBScript 脚本引擎中一个漏洞。如果用户访问经特殊设计的网站，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，成功利用此漏洞的攻击者便可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-020">MS15-020</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows 中的漏洞可能允许远程执行代码 (3041836)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者成功诱使用户浏览经特殊设计的网站、打开经特殊设计的文件或在包含经特殊设计的 DLL 文件的工作目录中打开文件，则漏洞可能会允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe 字体驱动程序中的漏洞可能允许远程执行代码 (3032323)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。最严重的漏洞可能在用户查看经特殊设计的文件或网站时允许远程执行代码。成功利用此漏洞的攻击者可以完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3038999)</strong> <br />
此安全更新可修复 Microsoft Office 中的漏洞。最严重的漏洞可能在用户打开经特殊设计的 Microsoft Office 文件时允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/kb/3038999/zh-cn">3038999</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office，<br />
Microsoft Server 软件</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-023">MS15-023</a></p></td>
<td style="border:1px solid black;"><p><strong>内核模式驱动程序中的漏洞可能允许特权提升 (3034344)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者登录系统并运行旨在提升特权的经特殊设计的应用程序，最严重的漏洞可能允许特权提升。攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-024">MS15-024</a></p></td>
<td style="border:1px solid black;"><p><strong>PNG 处理中的漏洞可能允许信息泄漏 (3035132)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者诱使用户访问包含经特殊设计的 PNG 图像的网站，此漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-025">MS15-025</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核中的漏洞可能允许特权提升 (3038680)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者登录受影响的系统并运行经特殊设计的应用程序，最严重的漏洞可能允许特权提升。成功利用该漏洞的攻击者可能在登录到受影响系统的其他用户帐户的安全上下文中运行任意代码。攻击者可随后安装程序；查看、更改或删除数据；或者可能创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/kb/3038680/zh-cn">3038680</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Exchange Server 中的漏洞可能允许特权提升 (3040856)</strong><br />
此安全更新可解决 Microsoft Exchange Server 中的漏洞。如果用户单击定向到目标 Outlook Web App 网站的经特殊设计的 URL，则其中最严重的漏洞可能允许特权提升。攻击者无法强迫用户访问经特殊设计的网站，但攻击者可能会诱使用户访问该网站，方法通常是让用户单击 Instant Messenger 消息或电子邮件中的链接以使用户链接到攻击者的网站，然后诱使用户单击经特殊设计的 URL。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Exchange</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-027">MS15-027</a></p></td>
<td style="border:1px solid black;"><p><strong>NETLOGON 中的漏洞可能允许欺骗 (3002657)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果登录到已加入域的系统的攻击者运行经特殊设计的应用程序，该应用程序可与作为被模拟用户或系统的其他已加入域的系统建立连接，则漏洞可能允许欺骗。攻击者必须登录到已加入域的系统，并能够观察网络流量。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
欺骗</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-028">MS15-028</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 任务计划程序中的漏洞可能允许安全功能绕过 (3030377)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。该漏洞可能允许在受影响系统上权限受限的用户利用任务计划程序来执行其无权运行的文件。成功利用此漏洞的攻击者可以绕过 ACL 检查并运行特权可执行文件。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-029">MS15-029</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 照片解码器组件中的漏洞可能允许信息泄漏 (3035126)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果用户浏览包含经特殊设计的 JPEG XR (.JXR) 图像的网站，该漏洞可能允许信息泄漏。虽然攻击者无法利用此漏洞来执行代码或直接提升他们的用户权限，但此漏洞可用于获取信息，这些信息可用于试图进一步危及受影响系统的安全。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-030">MS15-030</a></p></td>
<td style="border:1px solid black;"><p><strong>远程桌面协议中的漏洞可能允许拒绝服务 (3039976)</strong><br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者创建的多个远程桌面协议 (RDP) 会话无法正确释放内存中的对象，该漏洞可能允许拒绝服务。在任何 Windows 操作系统上，RDP 默认为未启用。未启用 RDP 的系统均不存在这一风险。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-031">MS15-031</a></p></td>
<td style="border:1px solid black;"><p><strong>Schannel 中的漏洞可能允许绕过安全功能 (3046049)<br />
</strong>此安全更新可解决 Microsoft Windows 中利用公开披露的 FREAK 技术的漏洞，这一行业范围问题并不是 Windows 操作系统特有的。此漏洞可以允许中间人 (MiTM) 攻击者在 TLS 连接中强制将 RSA 密钥的密钥长度降级到 EXPORT 级长度。任何使用 Schannel 连接到带有不安全密码套件的远程 TLS 服务器的 Windows 系统均会受到影响。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/kb/3046049/zh-cn">3046049</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。
  
<table style="width:100%;">  
<colgroup>  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
<col width="14%" />  
</colgroup>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>漏洞标题</strong></p></td>
<td style="border:1px solid black;"><p><strong>CVE ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>最新版本软件的<br />
利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较低版本软件的<br />
利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务<br />
利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>VBScript 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0056">CVE-2015-0056</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0072">CVE-2015-0072</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个特权提升漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0099">CVE-2015-0099</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0100">CVE-2015-0100</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1622">CVE-2015-1622</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1623">CVE-2015-1623</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1624">CVE-2015-1624</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1625">CVE-2015-1625</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1626">CVE-2015-1626</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1627">CVE-2015-1627</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-018">MS15-018</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1634">CVE-2015-1634</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-019">MS15-019</a></p></td>
<td style="border:1px solid black;"><p>VBScript 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-020">MS15-020</a></p></td>
<td style="border:1px solid black;"><p>WTS 远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0081">CVE-2015-0081</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-020">MS15-020</a></p></td>
<td style="border:1px solid black;"><p>DLL 种植远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0096">CVE-2015-0096</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0074">CVE-2015-0074</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0087">CVE-2015-0087</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0088">CVE-2015-0088</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0089">CVE-2015-0089</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0090">CVE-2015-0090</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0091">CVE-2015-0091</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0092">CVE-2015-0092</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-021">MS15-021</a></p></td>
<td style="border:1px solid black;"><p>Adobe 字体驱动程序远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0093">CVE-2015-0093</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 组件释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0085">CVE-2015-0085</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0086">CVE-2015-0086</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Word 本地区域远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0097">CVE-2015-0097</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1633">CVE-2015-1633</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-022">MS15-022</a></p></td>
<td style="border:1px solid black;"><p>Microsoft SharePoint XSS 漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1636">CVE-2015-1636</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-023">MS15-023</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0077">CVE-2015-0077</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-023">MS15-023</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0078">CVE-2015-0078</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-023">MS15-023</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0094">CVE-2015-0094</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-023">MS15-023</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows 内核内存泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0095">CVE-2015-0095</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄漏漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-024">MS15-024</a></p></td>
<td style="border:1px solid black;"><p>恶意 PNG 分析信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0080">CVE-2015-0080</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-025">MS15-025</a></p></td>
<td style="border:1px solid black;"><p>注册表虚拟化特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0073">CVE-2015-0073</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-025">MS15-025</a></p></td>
<td style="border:1px solid black;"><p>模拟级别检查特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0075">CVE-2015-0075</a></p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p>OWA 已修改 Canary 参数跨站点脚本执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1628">CVE-2015-1628</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p>ExchangeDLP 跨站点脚本执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1629">CVE-2015-1629</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p>审核报告跨站点脚本执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1630">CVE-2015-1630</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p>Exchange 伪造会议请求欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1631">CVE-2015-1631</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个欺骗漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-026">MS15-026</a></p></td>
<td style="border:1px solid black;"><p>Exchange 错误消息跨站点脚本执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1632">CVE-2015-1632</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>4 - 不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-027">MS15-027</a></p></td>
<td style="border:1px solid black;"><p>NETLOGON 欺骗漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0005">CVE-2015-0005</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个欺骗漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-028">MS15-028</a></p></td>
<td style="border:1px solid black;"><p>任务计划程序安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0084">CVE-2015-0084</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能规避漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-029">MS15-029</a></p></td>
<td style="border:1px solid black;"><p>JPEG XR 分析器信息泄漏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0076">CVE-2015-0076</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄漏漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-030">MS15-030</a></p></td>
<td style="border:1px solid black;"><p>远程桌面协议 (RDP) 拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0079">CVE-2015-0079</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个拒绝服务漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-031">MS15-031</a></p></td>
<td style="border:1px solid black;"><p>Schannel 安全功能绕过漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1637">CVE-2015-1637</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个安全功能规避漏洞。</p></td>
</tr>
</tbody>
</table>


受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

### Windows 操作系统和组件（表 1，共 2 个表）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)                                             

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
（中等）  
Internet Explorer 7  
(3032359)  
（中等）  
Internet Explorer 8  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
（中等）  
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033889)  
（严重）  
Windows Server 2003 Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
（中等）  
Internet Explorer 7  
(3032359)  
（中等）  
Internet Explorer 8  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
（中等）  
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033889)  
（严重）  
Windows Server 2003 x64 Edition Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
（中等）  
Internet Explorer 7  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
（中等）  
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3033889)  
（严重）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
(3032359)  
（严重）  
Internet Explorer 8  
(3032359)  
（严重）  
Internet Explorer 9  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3033889)  
（严重）  
Windows Vista Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
（严重）  
Internet Explorer 8  
(3032359)  
（严重）  
Internet Explorer 9  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3033889)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3032359)  
（中等）  
Internet Explorer 8  
(3032359)  
（中等）  
Internet Explorer 9  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3033889)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
（中等）  
Internet Explorer 8  
(3032359)  
（中等）  
Internet Explorer 9  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3033889)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3033889)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
**无**

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
(3032359)  
（严重）  
Internet Explorer 9  
(3032359)  
（严重）  
Internet Explorer 10  
(3032359)  
（严重）  
Internet Explorer 11  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3033889)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
（严重）  
Internet Explorer 9  
(3032359)  
（严重）  
Internet Explorer 10  
(3032359)  
（严重）  
Internet Explorer 11  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3033889)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
**无**

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
(3032359)  
（中等）  
Internet Explorer 9  
(3032359)  
（中等）  
Internet Explorer 10  
(3032359)  
（中等）  
Internet Explorer 11  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3033889)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3033889)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
**无**

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
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3033889)  
（严重）  
Windows 8（用于 32 位系统）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3033889)  
（严重）  
Windows 8（用于基于 x64 的系统）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3033889)  
（严重）  
Windows 8.1（用于 32 位系统）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3033889)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
**无**

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
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3033889)  
（严重）  
Windows Server 2012  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3033889)  
（严重）  
Windows Server 2012 R2  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
**无**

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
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3033889)  
（严重）  
Windows RT  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3033889)  
（严重）  
Windows RT 8.1  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035132)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-018**](https://technet.microsoft.com/zh-cn/library/security/ms15-018)

</td>
<td style="border:1px solid black;">
[**MS15-019**](https://technet.microsoft.com/zh-cn/library/security/ms15-019)

</td>
<td style="border:1px solid black;">
[**MS15-020**](https://technet.microsoft.com/zh-cn/library/security/ms15-020)

</td>
<td style="border:1px solid black;">
[**MS15-021**](https://technet.microsoft.com/zh-cn/library/security/ms15-021)

</td>
<td style="border:1px solid black;">
[**MS15-023**](https://technet.microsoft.com/zh-cn/library/security/ms15-023)

</td>
<td style="border:1px solid black;">
[**MS15-024**](https://technet.microsoft.com/zh-cn/library/security/ms15-024)

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
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3033889)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3035132)  
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
VBScript 5.7   
(3030398)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3033889)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3035132)  
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
VBScript 5.8   
(3030630)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3033889)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3035132)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3033889)  
（严重）  
Windows Server 2012（服务器核心安装）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3035132)  
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
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3033889)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(3039066)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3032323)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3034344)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3035132)  
（重要）

</td>
</tr>
</table>

**MS15-018、MS15-019、MS15-020、MS15-021 和 MS15-023 注释**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。建议运行这些操作系统的客户通过 [Windows 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)应用这些更新。** **

** **

### Windows 操作系统和组件（表 2，共 2 个表）

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
**无**                                        

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033395)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002657)  
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
Windows Server 2003 Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033395)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002657)  
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
Windows Server 2003 x64 Edition Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3033395)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3002657)  
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
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
**无**

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
**无**

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3035017)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3036493)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3035017)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3036493)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
**无**

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
**无**

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
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035126)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-025**](https://technet.microsoft.com/zh-cn/library/security/ms15-025)

</td>
<td style="border:1px solid black;">
[**MS15-027**](https://technet.microsoft.com/zh-cn/library/security/ms15-027)

</td>
<td style="border:1px solid black;">
[**MS15-028**](https://technet.microsoft.com/zh-cn/library/security/ms15-028)

</td>
<td style="border:1px solid black;">
[**MS15-029**](https://technet.microsoft.com/zh-cn/library/security/ms15-029)

</td>
<td style="border:1px solid black;">
[**MS15-030**](https://technet.microsoft.com/zh-cn/library/security/ms15-030)

</td>
<td style="border:1px solid black;">
[**MS15-031**](https://technet.microsoft.com/zh-cn/library/security/ms15-031)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3002657)  
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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3002657)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3046049)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3035131)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3002657)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3030377)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3035017)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3046049)  
（重要）

</td>
</tr>
</table>

**MS15-031 注释：**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。建议运行这些操作系统的客户通过 [Windows 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)应用这些更新。

 

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-cn/library/security/ms15-026)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3040856)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 7

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 累积更新 7  
(3040856)  
（重要）

</td>
</tr>
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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-cn/library/security/ms15-026)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）  
(2881068)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）  
(2881068)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（32 位版本）  
(2881068)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3（64 位版本）  
(2881068)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-cn/library/security/ms15-026)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2956208)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2 (wssloc)  
(2956208)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

</td>
<td style="border:1px solid black;">
[**MS15-026**](https://technet.microsoft.com/zh-cn/library/security/ms15-026)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 (sts)  
(2956175)  
（重要）  
Microsoft SharePoint Foundation 2013 (wssloc)  
(2956183)  
（重要）  
Microsoft SharePoint Foundation 2013 (smsloc)  
(2760508)  
（重要）  
Microsoft SharePoint Server 2013 (acsrvloc)  
(2956180)  
（重要）  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2956153)  
（重要）  
Microsoft SharePoint Server 2013 (eduloc)  
(2760554)  
（重要）  
Microsoft SharePoint Server 2013 (ifsloc)  
(2880473)  
（重要）  
Microsoft SharePoint Server 2013 (lpsrvloc)  
(2737989)  
（重要）  
Microsoft SharePoint Server 2013 (ppsmaloc)  
(2881078)  
（重要）  
Microsoft SharePoint Server 2013 (vsrvloc)  
(2956181)  
（重要）  
Microsoft SharePoint Server 2013 (wasrvloc)  
(2760361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1 (sts)  
(2956175)  
（重要）  
Microsoft SharePoint Foundation 2013 Service Pack 1 (wssloc)  
(2956183)  
（重要）  
Microsoft SharePoint Foundation 2013 Service Pack 1 (smsloc)  
(2760508)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (acsrvloc)  
(2956180)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (coreserverloc)  
(2956153)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (eduloc)  
(2760554)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (ifsloc)  
(2880473)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (lpsrvloc)  
(2737989)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (ppsmaloc)  
(2881078)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (vsrvloc)  
(2956181)  
（重要）  
Microsoft SharePoint Server 2013 Service Pack 1 (wasrvloc)  
(2760361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS15-022 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2984939)  
（重要）  
Microsoft Excel 2007 Service Pack 3  
(2956103)  
（重要）  
Microsoft PowerPoint 2007 Service Pack 3  
(2899580)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(2956109)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2956076)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2956138)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）(oart)  
(2883100)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）(oartconv)  
(2889839)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(2956142)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（32 位版本）  
(2920812)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2956139)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2956076)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2956138)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）(oart)  
(2883100)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）(oartconv)  
(2889839)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(2956142)  
（重要）  
Microsoft PowerPoint 2010 Service Pack 2（64 位版本）  
(2920812)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2956139)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
(2956151)  
（重要）  
Microsoft Word 2013（32 位版本）  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
(2956151)  
（重要）  
Microsoft Word 2013（64 位版本）  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(2956151)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(2956151)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2956151)  
（重要）  
Microsoft Word 2013 RT  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2956151)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(2956163)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**其他 Office 软件**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956188)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2956189)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Pack Service Pack 3 (wordconv)  
(2956107)  
（严重）  
Microsoft Office 兼容包 Pack Service Pack 3 (xlconv)  
(2956106)  
（重要）

</td>
</tr>
</table>

**MS15-022 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services (wdsrv)  
(2956136)  
（严重）

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
（重要）  
Word Automation Services (wdsrvloc)  
(2920731)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
（重要）  
Word Automation Services (wdsrvloc)  
(2920731)  
（严重）

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2 (wacloc2010)  
(2956069)  
（严重）  
Microsoft Office Web Apps Server 2010 Service Pack 2 (wacloc2010)  
(2956069)  
（严重）

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
[**MS15-022**](https://technet.microsoft.com/zh-cn/library/security/ms15-022)

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
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(wacserver2013)  
(2956158)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(wacserver2013)  
(2956158)  
（严重）

</td>
</tr>
</table>

**MS15-022 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199/zh-cn)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086/zh-cn)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

IT 专业人员安全解决方案：[TechNet 安全性疑难解答与支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持：[国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 3 月 10 日）：已发布公告摘要。

*页面生成时间 2015-03-10 9:05Z-07:00。*
