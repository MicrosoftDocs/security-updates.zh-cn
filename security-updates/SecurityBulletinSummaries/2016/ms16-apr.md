---
TOCTitle: 'MS16-APR'
Title: 2016 年 4 月的 Microsoft 安全公告摘要
ms:assetid: 'ms16-apr'
ms:contentKeyID: 72785262
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms16-apr(v=Security.10)'
---

MSRC ppDocument 模板

2016 年 4 月的 Microsoft 安全公告摘要
=====================================

发布日期：2016 年 4 月 12 日 | 更新时间：2017 年 4 月 11 日

**版本：**4.0

本公告摘要列出了 2016 年 4 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746891">MS16-037</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 累积安全更新 (3148531)<br />
</strong>此安全更新修复了 Internet Explorer 中的多个漏洞。如果用户使用 Internet Explorer 查看经特殊设计的网页，则其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。如果当前用户使用管理用户权限登录，则攻击者可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746894">MS16-038</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 累积安全更新 (3148532)<br />
</strong>此安全更新修复了 Microsoft Edge 中的多个漏洞。如果用户使用 Microsoft Edge 查看经特殊设计的网页，则其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746883">MS16-039</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft 图形组件安全更新 (3148522)</strong><br />
此安全更新修复了 Microsoft Windows、Microsoft .NET Framework、Microsoft Office、Skype for Business 和 Microsoft Lync 中的多个漏洞。如果用户打开经特殊设计的文档或访问包含经特殊设计的嵌入字体的网页，则其中最严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3148522">3148522</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、Microsoft .NET Framework、<br />
Microsoft Office、Skype for Business、<br />
Microsoft Lync。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746897">MS16-040</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft XML Core Services 安全更新 (3148541)</strong><br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。如果用户单击经特殊设计的链接，该链接可能允许攻击者远程运行恶意代码来控制用户系统，则该漏洞可能允许远程执行代码。但是，在所有情况下，攻击者无法强制用户单击经特殊设计的链接。攻击者必须说服用户单击此链接，通常通过电子邮件或 Instant Messenger 消息的方式。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746929">MS16-041</a></p></td>
<td style="border:1px solid black;"><p><strong>.NET Framework 安全更新 (3148789)</strong><br />
此安全更新修复了 Microsoft .Net Framework 中的一个漏洞。如果具有本地系统访问权限的攻击者执行恶意应用程序，则该漏洞可能允许远程代码执行。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746928">MS16-042</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 安全更新 (3148775)</strong><br />
此安全更新修复了 Microsoft Office 中的多个漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，则其中最严重的漏洞可能允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响较小。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3148775">3148775</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office、<br />
Microsoft Office Services 和 Web 应用</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=747040">MS16-044</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows OLE 安全更新 (3146706)</strong><br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。如果 Windows OLE 无法正确验证用户输入，则漏洞可能允许远程执行代码。攻击者可能利用漏洞执行恶意代码。但是，攻击者必须先说服用户打开经特殊设计的文件或者网页或电子邮件中的程序。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3146706">3146706</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=733440">MS16-045</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Hyper-V 安全更新 (3143118)</strong><br />
此安全更新修复了 Microsoft Windows 中的多个漏洞。如果来宾操作系统上的经身份验证的攻击者运行经特殊设计的应用程序，该应用程序可导致 Hyper-V 主机操作系统执行任意代码，则其中最严重的漏洞可能允许远程执行代码。尚未启用 Hyper-V 角色的客户不会受到影响。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746896">MS16-046</a></p></td>
<td style="border:1px solid black;"><p><strong>辅助登录安全更新 (3148538)</strong><br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。成功利用此漏洞的攻击者可以以管理员身份运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746885">MS16-047</a></p></td>
<td style="border:1px solid black;"><p><strong>SAM 和 LSAD 远程协议安全更新 (3148527)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者启动中间人 (MiTM) 攻击，则该漏洞可能允许特权提升。然后，攻击者可以强制降低 SAM 和 LSAD 通道的身份验证级别，并模拟经身份验证的用户。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746886">MS16-048</a></p></td>
<td style="border:1px solid black;"><p><strong>CSRSS 安全更新 (3148528)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者登录目标系统并运行经特殊设计的应用程序，则此漏洞可能允许绕过安全功能。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
安全功能绕过</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3146723">3146723</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=746932">MS16-049</a></p></td>
<td style="border:1px solid black;"><p><strong>HTTP.sys 安全更新 (3148795)<br />
</strong>此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者向目标系统发送特制 HTTP 数据包，则该漏洞可能允许拒绝服务。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=785154">MS16-050</a></p></td>
<td style="border:1px solid black;"><p><strong>Adobe Flash Player 安全更新 (3154132)</strong><br />
此安全更新修复了 Adobe Flash Player 在 Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1 和 Windows 10 所有支持版本上安装时的漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Adobe Flash Player</p></td>
</tr>
</tbody>
</table>


利用指数
--------

下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。

**如何使用该表？**

对于您可能需要安装的每个安全更新，使用该表了解安全公告发布 30 天内发生代码执行和拒绝服务漏洞的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。

在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新软件版本”是指主题软件，“较旧软件版本”是指主题软件的所有较旧的受支持版本。

<p> </p>
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID**                    

</td>
<td style="border:1px solid black;">
**漏洞标题**

</td>
<td style="border:1px solid black;">
**最新软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**旧软件版本的  
利用性评估**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用性评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-037：Internet Explorer 累积安全更新 (3148531)**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2016-0159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0159)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-0160](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0160)

</td>
<td style="border:1px solid black;">
DLL 加载远程执行代码漏洞

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
[CVE-2016-0162](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0162)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

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
[CVE-2016-0164](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0164)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[CVE-2016-0166](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0166)

</td>
<td style="border:1px solid black;">
Internet Explorer 内存损坏漏洞

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
[**MS16-038：Microsoft Edge 累积安全更新 (3148532)**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)

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
[CVE-2016-0155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0155)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

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
[CVE-2016-0156](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0156)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

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
[CVE-2016-0157](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0157)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

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
[CVE-2016-0158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0158)

</td>
<td style="border:1px solid black;">
Microsoft Edge 特权提升漏洞

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
[CVE-2016-0161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0161)

</td>
<td style="border:1px solid black;">
Microsoft Edge 特权提升漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS16-039：Microsoft Graphics 组件的安全更新 (3148522)**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0143)

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
[CVE-2016-0145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0145)

</td>
<td style="border:1px solid black;">
图形内存损坏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2016-0165](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0165)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0167](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0167)

</td>
<td style="border:1px solid black;">
Win32k 特权提升漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-040：Microsoft XML Core Services 的安全更新 (3148541)**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0147)

</td>
<td style="border:1px solid black;">
MSXML 3.0 远程执行代码漏洞

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
[**MS16-041：.NET Framework 的安全更新 (3148789)**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0148)

</td>
<td style="border:1px solid black;">
.NET Framework 远程执行代码漏洞

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
[**MS16-042：Microsoft Office 的安全更新 (3148775)**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0122](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0122)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
[CVE-2016-0127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0127)

</td>
<td style="border:1px solid black;">
Microsoft Office 内存损坏漏洞

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
[CVE-2016-0136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0136)

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
[CVE-2016-0139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0139)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-044：Windows OLE 的安全更新 (3146706)**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0153)

</td>
<td style="border:1px solid black;">
Windows OLE 远程执行代码漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS16-045：Windows Hyper-V 的安全更新 (3143118)**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0088](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0088)

</td>
<td style="border:1px solid black;">
Hyper-V 远程代码执行漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0089](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0089)

</td>
<td style="border:1px solid black;">
Hyper-V 信息泄露漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0090)

</td>
<td style="border:1px solid black;">
Hyper-V 信息泄露漏洞

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-046：辅助登录的安全更新 (3148538)**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0135)

</td>
<td style="border:1px solid black;">
辅助登录特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-047：SAM 和 LSAD 远程协议的安全更新 (3148527)**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0128)

</td>
<td style="border:1px solid black;">
Windows SAM 和 LSAD 降级漏洞

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
[**MS16-048：CSRSS 的安全更新 (3148528)**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0151)

</td>
<td style="border:1px solid black;">
Windows CSRSS 绕过安全功能漏洞

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
[**MS16-049：HTTP.sys 的安全更新 (3148795)**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0150)

</td>
<td style="border:1px solid black;">
HTTP.sys 拒绝服务漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

</td>
<td style="border:1px solid black;">
4 - 不受影响

</td>
<td style="border:1px solid black;">
永久

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-050：Adobe Flash Player 的安全更新 3154132**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-10](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-10.html)

</td>
<td style="border:1px solid black;">
请参阅 [Adobe 安全公告 APSB16-10](https://helpx.adobe.com/cn/security/products/flash-player/apsb16-10.html)，了解漏洞严重性级别和更新优先级级别。

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


受影响的软件
------------

下表按主要软件类别和严重性的排序列出了公告。

通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。

**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。

 

### Windows 操作系统和组件（表 1-2）

<p> </p>
<p> </p>
<table style="border:1px solid black;">
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3145739)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3145739)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3145739)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3145739)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3146706)  
（重要）

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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3145739)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3142042)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3142042)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3142042)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3146706)  
（重要）

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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3145739)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142045)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142045)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3146706)  
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
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4014661)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142043)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142045)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3145739)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3147461)  
（严重）  
Microsoft .NET Framework 3.5  
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
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
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（严重）  
Microsoft .NET Framework 3.5  
(3147461)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
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
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3147458)  
（严重）  
Microsoft .NET Framework 3.5  
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
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
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3147458)  
（严重）  
Microsoft .NET Framework 3.5  
(3147458)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
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
<td style="border:1px solid black;" colspan="7">
**服务器核心安装选项**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-037**](https://go.microsoft.com/fwlink/?linkid=746891)

</td>
<td style="border:1px solid black;">
[**MS16-038**](https://go.microsoft.com/fwlink/?linkid=746894)

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-040**](https://go.microsoft.com/fwlink/?linkid=746897)

</td>
<td style="border:1px solid black;">
[**MS16-041**](https://go.microsoft.com/fwlink/?linkid=746929)

</td>
<td style="border:1px solid black;">
[**MS16-044**](https://go.microsoft.com/fwlink/?linkid=747040)

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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3145739)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3146706)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3145739)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3146706)  
（重要）

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3142042)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3146706)  
（重要）

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
Windows Server 2012（服务器核心安装）  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142043)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3146706)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
暂无

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3145739)  
（严重）  
Microsoft .NET Framework 3.5  
(3142045)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3146706)  
（重要）

</td>
</tr>
</table>

**MS16-039 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Windows 操作系统和组件（表 2-2）

<p> </p>
<p> </p>
<table style="border:1px solid black;">
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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3149090)  
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
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3149090)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3149090)  
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
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3149090)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3149090)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3149090)  
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
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3149090)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3149090)  
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
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3149090)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3146723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3135456)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3146723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3135456)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3135456)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（中等）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146723)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要提示**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3147461)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3147458)  
（重要）

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
（严重）

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
[**MS16-045**](https://go.microsoft.com/fwlink/?linkid=733440)

</td>
<td style="border:1px solid black;">
[**MS16-046**](https://go.microsoft.com/fwlink/?linkid=746896)

</td>
<td style="border:1px solid black;">
[**MS16-047**](https://go.microsoft.com/fwlink/?linkid=746885)

</td>
<td style="border:1px solid black;">
[**MS16-048**](https://go.microsoft.com/fwlink/?linkid=746886)

</td>
<td style="border:1px solid black;">
[**MS16-049**](https://go.microsoft.com/fwlink/?linkid=746932)

</td>
<td style="border:1px solid black;">
[**MS16-050**](https://go.microsoft.com/fwlink/?linkid=785154)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3149090)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3149090)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3149090)  
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
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3135456)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3146723)  
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
Windows Server 2012 R2  
（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3135456)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3149090)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3146723)  
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

 

### Microsoft Office 套件和软件

<p> </p>
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3114542)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3114892)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3114983)  
（严重）

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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114566)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114990)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3114888)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3114993)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114566)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114990)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3114888)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3114993)  
（严重）

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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(3114947)  
（重要）  
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3114937)  
（严重）

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
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(3114947)  
（重要）  
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3114937)  
（严重）

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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Excel 2013 RT Service Pack 1  
(3114947)  
（重要）  
Microsoft Word 2013 RT Service Pack 1  
(3114937)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（32 位版本）  
(3114964)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016（64 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016（64 位版本）  
(3114964)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Word for Mac 2011  
(3154208)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3142577)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(3114982)  
（严重）  
Microsoft Office 兼容包 Service Pack 3  
(3114895)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114898)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114985)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114987)  
（严重）

</td>
</tr>
</table>

**MS16-039 和 MS16-042 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft Office Services 和 Web Apps

<p> </p>
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（32 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3（64 位版本）

</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
（重要）

</td>
</tr>
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3114871)  
（重要）  
Word Automation Services  
(3114988)  
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3114927)  
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114994)  
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
[**MS16-042**](https://go.microsoft.com/fwlink/?linkid=746928)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114934)  
（严重）

</td>
</tr>
</table>

**MS16-042 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

### Microsoft 通信平台和软件

<p> </p>
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（32 位版本）  
(3114960)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016（32 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016（32 位版本）  
(3114960)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（64 位版本）  
(3114960)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016（64 位版本）

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016（64 位版本）  
(3114960)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3114944)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（32 位）  
(Skype for Business Basic)  
(3114944)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（64 位）  
(Skype for Business)  
(3114944)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1（64 位）  
(Skype for Business Basic)  
(3114944)  
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
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010（32 位）  
(3144427)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010（64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010（64 位）  
(3144427)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（用户级安装）  
(3144428)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理级安装）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理级安装）  
(3144429)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS16-039**](https://go.microsoft.com/fwlink/?linkid=746883)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**

</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3144432)  
（严重）

</td>
</tr>
</table>

**MS16-039 注释**

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
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/zh-cn/contactus/cu_sc_virsec_master)

基于国家/地区的本地支持：[国际支持](https://support.microsoft.com/zh-cn/common/international.aspx)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定用途的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害、商业利润损失或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2016 年 4 月 12 日）：已发布公告摘要。
-   V1.1（2016 年 4 月 13 日）：向 MS16-039 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3148522](https://support.microsoft.com/zh-cn/kb/3148522)。向 MS16-042 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3148775](https://support.microsoft.com/zh-cn/kb/3148775)。
-   V1.2（2016 年 5 月 11 日）：向 MS16-044 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3146706](https://support.microsoft.com/zh-cn/kb/3146706)。向 MS16-042 的“执行摘要”表添加了已知问题的引用。有关详细信息，请参阅 [Microsoft 知识库文章 3146723](https://support.microsoft.com/zh-cn/kb/3146723)。
-   V2.0（2016 年 6 月 14 日）：对于 MS16-039，修订的公告总结声明 Microsoft 已重新发布 Microsoft Lync 2010 和 Microsoft Lync 2010 Attendee 受影响版本的安全更新 3144427。此重新发布解决了客户下载更新 3144427 时可能遇到的问题。运行 Microsoft Lync 2010 的客户应安装此更新以充分防护漏洞攻击。有关详细信息，请参阅 [Microsoft 知识库文章 3144427](https://support.microsoft.com/zh-cn/kb/3144427)。
-   V3.0（2017 年 4 月 11 日）：对于 Ms16-037，公告摘要经过修订以宣布 CVE-2016-0162 的新的 Internet Explorer 累积更新 (4014661) 的发布。该更新添加至原版本以全面修复 CVE-2016-0162。Microsoft 建议运行此受影响软件的客户安装此安全更新以完全防止此公告中描述的漏洞。有关更多信息，请参阅 [Microsoft 知识库文章 4014661](https://support.microsoft.com/zh-cn/kb/4014661)。

*页面生成时间：2017-04-10 16:29-07:00。*
