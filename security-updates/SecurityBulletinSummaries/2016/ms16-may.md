---
TOCTitle: 'MS16-MAY'
Title: 'Microsoft 安全公告摘要（2016 年 5 月）'
ms:assetid: 'ms16-may'
ms:contentKeyID: 72963875
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-may(v=Security.10)'
---

MSRC ppDocument 模板

Microsoft 安全公告摘要（2016 年 5 月）
======================================

发布日期：2016 年 5 月 10 日 | 更新时间：2016 年 5 月 25 日

**版本：** 2.1

本公告摘要列出了 2016 年 5 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
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
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-051">MS16-051</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3155533)<br />
</strong>此安全更新程序修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，那么攻击者便可控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-052">MS16-052</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3155538)<br />
</strong>此安全更新程序可修复 Microsoft Edge 中的漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，那么其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-053">MS16-053</a></p></td>
<td style="border:1px solid black;"><p><strong>JScript 和 VBScript 的累积安全更新 (3156764)<br />
</strong>此安全更新程序可修复 Microsoft Windows 的 JScript 和 VBScript 脚本引擎中的多个漏洞。如果用户访问经特殊设计的网站，那么这些漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则成功利用这些漏洞的攻击者可以控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-054">MS16-054</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 的安全更新程序 (3155544)<br />
</strong>此安全更新程序可修复 Microsoft Office 中的多个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞可能会允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web Apps</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-055">MS16-055</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 图形组件的安全更新程序 (3156754)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的多个漏洞。如果用户打开经特殊设计的文档或访问经特殊设计的网站，最严重的漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-056">MS16-056</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 日记本安全更新程序 (3156761)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果用户打开经特殊设计的日记文件，那么此漏洞可能允许远程执行代码。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-057">MS16-057</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Shell 安全更新程序 (3156987)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果攻击者成功诱使用户浏览可接受用户提供的在线内容的经特殊设计的网站，或诱使用户打开经特殊设计的内容，则漏洞可能会允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-058">MS16-058</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows IIS 安全更新程序 (3141083)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果拥有本地系统访问权限的攻击者执行恶意应用程序，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-059">MS16-059</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Media Center 安全更新程序 (3150220)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果 Windows Media Center 打开引用了恶意代码的经特殊设计的 Media Center 链接 (.mcl) 文件，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的用户相比，帐户被配置为拥有较少系统用户权限的用户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-060">MS16-060</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核安全更新程序 (3154846)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果攻击者登录受影响的系统并运行经特殊设计的应用程序，此漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-061">MS16-061</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft RPC 安全更新程序 (3155520)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果未经身份验证的攻击者向受影响的主机发起格式不正确的远程过程调用 (RPC) 请求，此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-062">MS16-062</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序的安全更新程序 (3158222)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的多个漏洞。如果攻击者登录受影响的系统并运行经特殊设计的应用程序，最严重的漏洞可能允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-064">MS16-064</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新程序 (3157993)</strong><br />
此安全更新可修复安装在所有受支持版本的 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 以及 Windows 10 上的 Adobe Flash Player 漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-065">MS16-065</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 的安全更新程序 (3156757)<br />
</strong>此安全更新程序可修复 Microsoft .NET Framework 中的一个漏洞。如果攻击者将未加密的数据插入目标安全通道，然后在目标客户端和合法的服务器之间执行中间人 (MiTM) 攻击，该漏洞可能导致信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3156757">3156757</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-066">MS16-066</a></p></td>
<td style="border:1px solid black;"><p><strong>虚拟安全模式的安全更新程序 (3155451)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果攻击者运行经特殊设计的应用程序以绕过 Windows 中的代码完整性保护，该漏洞可能允许绕过安全功能。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
绕过安全功能</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms16-067">MS16-067</a></p></td>
<td style="border:1px solid black;"><p><strong>卷管理器驱动程序的安全更新程序 (3155784)<br />
</strong>此安全更新程序可修复 Microsoft Windows 中的一个漏洞。如果通过 Microsoft RemoteFX 使用远程桌面协议 (RDP) 装载的 USB 磁盘未正确关联装载用户会话，该漏洞可能允许信息泄漏。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄漏</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>




利用指数
--------

<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

<p> </p>

<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**漏洞标题**

</td>
<td style="border:1px solid black;">
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**较旧软件版本的  
利用评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-051：Internet Explorer 累积安全更新 (3155533)**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0188](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0188)

</td>
<td style="border:1px solid black;">
Internet Explorer 安全功能绕过

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0189](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测到利用情形

</td>
<td style="border:1px solid black;">
0 - 检测到利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0194](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0194)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-052：Microsoft Edge 累积安全更新程序 (3155538)**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0186](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0186)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0191](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0191)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0192](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0193](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0193)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-053：JScript 和 VBScript 的累积安全更新 (3156764)**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0189](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-054：Microsoft Office 的安全更新程序 (3155544)**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0126)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0140)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0183](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0183)

</td>
<td style="border:1px solid black;">
Microsoft Office 图形 RCE 漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0198](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0198)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

</td>
<td style="border:1px solid black;">
1 - 不太可能利用

</td>
<td style="border:1px solid black;">
1 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-055：Microsoft 图形组件的安全更新程序 (3156754)**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0168](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0168)

</td>
<td style="border:1px solid black;">
Windows Graphics 组件信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
临时

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0169](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0169)

</td>
<td style="border:1px solid black;">
Windows Graphics 组件信息泄漏漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
临时

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0170](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0170)

</td>
<td style="border:1px solid black;">
Windows 图形组件 RCE 漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0184](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0184)

</td>
<td style="border:1px solid black;">
Direct3D 释放后使用漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0195](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0195)

</td>
<td style="border:1px solid black;">
Windows 图像处理组件内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-056：Windows 日记本安全更新程序 (3156761)**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0182](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0182)

</td>
<td style="border:1px solid black;">
日记本内存损坏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-057：Windows Shell 安全更新程序 (3156987)**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0179](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0179)

</td>
<td style="border:1px solid black;">
Windows Shell 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-058：Windows IIS 安全更新程序 (3141083)**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0152](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0152)

</td>
<td style="border:1px solid black;">
Windows DLL 加载远程执行代码漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-059：Windows Media Center 安全更新程序 (3150220)**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0185](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0185)

</td>
<td style="border:1px solid black;">
Windows Media Center 远程执行代码漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-060：Windows 内核安全更新程序 (3154846)**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0180](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0180)

</td>
<td style="border:1px solid black;">
Windows 内核特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-061：Microsoft RPC 安全更新程序 (3155520)**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0178](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0178)

</td>
<td style="border:1px solid black;">
RPC 网络数据表示引擎远程执行代码漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-062：Windows 内核模式驱动程序的安全更新程序 (3158222)**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0171](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0171)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0173](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0173)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0174](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0174)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0175](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0175)

</td>
<td style="border:1px solid black;">
Win32k 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0176](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0176)

</td>
<td style="border:1px solid black;">
Microsoft DirectX 图形内核子系统特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0196](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0196)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
1 - 可能被利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0197](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0197)

</td>
<td style="border:1px solid black;">
Microsoft DirectX 图形内核子系统特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-064：Adobe Flash Player 安全更新程序 (3157993)**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-15](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-15.html)

</td>
<td style="border:1px solid black;">
请参阅 [Adobe 安全公告 APSB16-15](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-15.html)，了解漏洞严重性级别和更新优先级级别。

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
<td style="border:1px solid black;" colspan="5">
[**MS16-065：.NET Framework 的安全更新程序 (3156757)**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0149)

</td>
<td style="border:1px solid black;">
TLS/SSL 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-066：虚拟安全模式的安全更新程序 (3155451)**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0181](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0181)

</td>
<td style="border:1px solid black;">
虚拟机监控程序代码完整性安全功能绕过

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-067：卷管理器驱动程序的安全更新程序 (3155784)**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0190](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0190)

</td>
<td style="border:1px solid black;">
远程桌面协议驱动器重定向信息泄漏漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 1-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3156013)  
（严重）  
Windows Vista Service Pack 2  
(3156016)  
（严重）  
Windows Vista Service Pack 2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3156013)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(3156016)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3156013)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3156016)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3156013)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3156016)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3156013)  
（严重）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3156013)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3156016)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3156013)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3156016)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3156013)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3156016)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3156013)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3156016)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3156013)  
（严重）  
Windows 8.1（用于 32 位系统）  
(3156016)  
（严重）  
Windows 8.1（用于 32 位系统）  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3156059)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3156013)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(3156016)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3156059)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3150220)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3154070)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3156013)  
（严重）  
Windows Server 2012  
(3156016)  
（严重）  
Windows Server 2012  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156013)  
（严重）  
Windows Server 2012 R2  
(3156016)  
（严重）  
Windows Server 2012 R2  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156059)  
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
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156013)  
（严重）  
Windows RT 8.1  
(3156016)  
（严重）  
Windows RT 8.1  
(3156019)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3155178)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156059)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
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
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
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
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
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
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
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
<td style="border:1px solid black;" colspan="9">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-051**](https://technet.microsoft.com/zh-cn/library/security/ms16-051)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://technet.microsoft.com/zh-cn/library/security/ms16-052)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://technet.microsoft.com/zh-cn/library/security/ms16-053)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://technet.microsoft.com/zh-cn/library/security/ms16-055)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://technet.microsoft.com/zh-cn/library/security/ms16-056)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://technet.microsoft.com/zh-cn/library/security/ms16-057)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://technet.microsoft.com/zh-cn/library/security/ms16-058)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://technet.microsoft.com/zh-cn/library/security/ms16-059)

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
**无**

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
**无**

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3156013)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3156016)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3156019)  
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
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3158991)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3156013)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3156016)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3156019)  
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
(3141083)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
JScript 5.8 和 VBScript 5.8  
(3155413)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3156013)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3156016)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

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
Windows Server 2012（服务器核心安装）  
(3156013)  
（严重）  
Windows Server 2012（服务器核心安装）  
(3156016)  
（严重）  
Windows Server 2012（服务器核心安装）  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

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
Windows Server 2012 R2（服务器核心安装）  
(3156013)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(3156016)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(3156019)  
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
</tr>
</table>

 

### Windows 操作系统和组件（表 2-2）

<p> </p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153199)  
（重要）  
Windows Vista Service Pack 2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153199)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3153199)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3153199)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3153199)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3153199)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3153199)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
**无**

</td>
<td style="border:1px solid black;">
**无**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3153199)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3153199)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3153199)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142030)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3153199)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142030)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 和 Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
[**中等**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153199)  
（重要）  
Windows Server 2012  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142032)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3155784)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153199)  
（重要）  
Windows Server 2012 R2  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（中等）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142030)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3155784)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153199)  
（重要）  
Windows RT 8.1  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3142030)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
（重要）  
Microsoft .NET Framework 4.6  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
（重要）  
Microsoft .NET Framework 4.6  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3156387)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3163207)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
（重要）  
Microsoft .NET Framework 4.6.1  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3156421)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://technet.microsoft.com/zh-cn/library/security/ms16-060)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://technet.microsoft.com/zh-cn/library/security/ms16-061)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://technet.microsoft.com/zh-cn/library/security/ms16-062)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://technet.microsoft.com/zh-cn/library/security/ms16-064)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://technet.microsoft.com/zh-cn/library/security/ms16-065)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://technet.microsoft.com/zh-cn/library/security/ms16-066)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://technet.microsoft.com/zh-cn/library/security/ms16-067)

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
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3153199)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3156017)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3153199)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3156017)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3153199)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142033)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3153199)  
（重要）  
Windows Server 2012  
（服务器核心安装）  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142032)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3155784)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3153171)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3153704)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3153199)  
（重要）  
Windows Server 2012 R2  
（服务器核心安装）  
(3156017)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
（重要）  
Microsoft .NET Framework 4.5.2  
(3142030)  
（重要）  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3155784)  
（重要）

</td>
</tr>
</table>

 

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
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
(2984938)  
（重要）  
Microsoft Office 2007 Service Pack 3  
(2984943)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3115116)  
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
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
(3115121)  
（严重）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3054984)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3101520)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3115123)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3115121)  
（严重）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3054984)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3101520)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3115123)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(3115016)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3115025)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(3115016)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3115025)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3115016)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3115025)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）  
(3115103)  
（重要）  
Microsoft Word 2016（32 位版本）  
(3115094)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）  
(3115103)  
（重要）  
Microsoft Word 2016（64 位版本）  
(3115094)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3155776)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3155777)  
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
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3115115)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115132)  
（严重）

</td>
</tr>
</table>

**MS16-054 的注释**

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
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Word Automation Services  
(3115117)  
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
[**MS16-054**](https://technet.microsoft.com/zh-cn/library/security/ms16-054)

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
Microsoft Office Web Apps 2010 Service Pack 2  
(3115124)  
（严重）

</td>
</tr>
</table>

**MS16-054 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/mt674627.aspx)部分。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/zh-cn/kb/894199)：Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新程序**

可从以下位置获得针对其他安全问题的更新程序：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新程序。通过输入关键字“安全更新”可以非常方便地找到这些更新程序。
-   [Microsoft 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新程序。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

面向 IT 专业人员的安全解决方案：[TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

基于国家/地区的本地支持：[国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 5 月 10 日）：已发布公告摘要。
-   V1.1（2016 年 5 月 11 日）：公告摘要经过修订，将 MS16-061 的漏洞影响从特权提升更改为远程执行代码，并将 CVE 2016-0178 的标题更改为 RPC 网络数据表示引擎远程执行代码漏洞。此仅为信息变更。
-   V1.2（2016 年 5 月 13 日）：公告摘要已针对 MS16-067 进行修订，将 Windows 8.1 和 Windows RT 8.1 的漏洞严重等级更改为“不适用”，因为这些操作系统不受公告中描述的漏洞的影响。已经应用了安全更新程序 3155784 的客户不需要执行任何进一步操作。此仅为信息变更。
-   V2.0（2016 年 5 月 13 日）：公告摘要已针对 MS16-064 进行修订，以宣布将发布可修复 Adobe 安全公告 APSB16-15 中漏洞的更新 3163207。请注意，更新 3163207 将替代 MS16-064 公告中以前发布的更新（更新 3157993）。Microsoft 强烈建议客户安装更新 3163207，以帮助避免 Adobe 安全公告 APSB16-15 中描述的漏洞。
-   V2.1（2016 年 5 月 25 日）：对于 MS16-065，向“执行摘要”表添加了已知问题。在适用于 Lync Server 2010、Lync Server 2013 或 Skype for Business Server 2015 的前端服务器或 Standard Edition 服务器上安装包括在 MS16-065 中的任意安全更新程序之后，几种会议方式不再适用于内部用户。有关此已知问题的解决方案的信息，请参阅 [Microsoft 知识库文章 3165438](https://support.microsoft.com/zh-cn/kb/3165438)。

*页面生成时间：2016-05-25 12:52-07:00。*
