---
TOCTitle: 'MS15-DEC'
Title: 'Microsoft 安全公告摘要（2015 年 12 月）'
ms:assetid: 'ms15-dec'
ms:contentKeyID: 72045359
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-dec(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 12 月）
=======================================

发布日期：2015 年 12 月 8 日 | 更新时间：2015 年 12 月 16 日

**版本：** 1.2

本公告摘要列出了 2015 年 12 月发布的安全公告。

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
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-124">MS15-124</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的累积安全更新程序 (3116180)</strong> <br />
此安全更新可解决 Internet Explorer 中的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p><a href="https://support.microsoft.com/zh-cn/kb/3104002">3104002</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-125">MS15-125</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Edge 的累积安全更新 (3116184) <br />
</strong>此安全更新可修复 Microsoft Edge 中的漏洞。最严重的漏洞可能在用户使用 Microsoft Edge 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft Edge</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-126">MS15-126</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 JScript 和 VBScript 累积安全更新 (3116178) <br />
</strong>此安全更新可解决 Microsoft Windows 的 VBScript 脚本引擎中的漏洞。如果攻击者拥有一个旨在通过 Internet Explorer 利用这些漏洞的经特殊设计的网站（利用已入侵的网站或接受或托管用户提供的内容或广告的网站），然后诱使用户查看该网站，其中较为严重的漏洞可能允许远程执行代码。攻击者也可能在使用 Internet Explorer 呈现引擎将用户定向到经特殊设计的网站的应用程序或 Microsoft Office 文档中嵌入标有“安全初始化”的 ActiveX 控件。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-127">MS15-127</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Microsoft Windows DNS 安全更新 (3100465)</strong> <br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者向 DNS 服务器发送特殊设计的请求，此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-128">MS15-128</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Microsoft 图形组件安全更新 (3104503)</strong> <br />
此安全更新可修复 Microsoft Windows、.NET Framework、Microsoft Office、Skype for Business、Microsoft Lync 和 Silverlight 中的漏洞。如果用户打开经特殊设计的文档或访问包含嵌入字体的经特殊设计的网页，这些漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows、<br />
Microsoft .NET Framework、<br />  
Microsoft Office、<br />  
Skype for Business、Microsoft Lync 和<br />
Silverlight</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-129">MS15-129</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Silverlight 安全更新 (3106614)</strong> <br />
此安全更新可解决 Microsoft Silverlight 中的漏洞。如果 Microsoft Silverlight 错误地处理某些可能导致读取访问和写入访问冲突的打开和关闭请求，则其中最严重的漏洞可能允许远程执行代码。要利用这一漏洞，攻击者可能拥有一个包含经特殊设计的 Silverlight 应用程序的网站，然后说服用户访问已入侵的网站。攻击者可能还会利用包含经特殊设计的内容的网站，包括接受或托管用户提供的内容或广告的网站。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>无需重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Silverlight</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-130">MS15-130</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Microsoft Uniscribe 安全更新 (3108670)</strong> <br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。如果用户打开经特殊设计的文档或访问包含经特殊设计的字体的不受信任的网页，此漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-131">MS15-131</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Microsoft Office 安全更新 (3116111)</strong> <br />
此安全更新可修复 Microsoft Office 中的漏洞。最严重的漏洞可能在用户打开经特殊设计的 Microsoft Office 文件时允许远程执行代码。成功利用这些漏洞的攻击者可以在当前用户的上下文中运行任意代码。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-132">MS15-132</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Microsoft Windows 安全更新 (3116162)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果攻击者访问本地系统并运行经特殊设计的应用程序，则这些漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-133">MS15-133</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决特权提升的 Windows PGM 安全更新 (3116130)</strong> <br />
此安全更新修复了 Microsoft Windows 中的一个漏洞。如果攻击者登录到目标系统并运行经特殊设计的应用程序，在争用条件下会导致引用已经释放的内存位置，则此漏洞可能允许特权提升。必须安装 Microsoft 消息队列 (MSMQ)，并专门为容易受到攻击的系统启用 Windows 实际通用多播 (PGM) 协议。默认配置中不存在 MSMQ，如果安装了 MSMQ，则 PGM 协议可用，但在默认情况下此协议处于禁用状态。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-134">MS15-134</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决远程执行代码的 Windows Media Center 安全更新 (3108669)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。如果 Windows Media Center 打开引用了恶意代码的经特殊设计的 Media Center 链接 (.mcl) 文件，则其中较为严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能需要重启</p></td>
<td style="border:1px solid black;"><p>---------</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/library/security/ms15-135">MS15-135</a></p></td>
<td style="border:1px solid black;"><p><strong>用于解决特权提升的 Windows 内核模式驱动程序安全更新 (3119075)</strong> <br />
此安全更新可修复 Microsoft Windows 中的漏洞。这些漏洞在攻击者登录目标系统并运行经特殊设计的应用程序时允许特权提升。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重启</p></td>
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
**较旧软件版本的利用评估  
**

</td>
<td style="border:1px solid black;">
**较旧软件版本的利用评估  
**

</td>
<td style="border:1px solid black;">
**拒绝服务  
利用评估**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-124：Internet Explorer 累积安全更新 (3116180)**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6083](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6083)

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
[CVE-2015-6134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6134)

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
[CVE-2015-6135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
脚本引擎信息泄漏漏洞

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
[CVE-2015-6136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

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
[CVE-2015-6138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6138)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS 筛选器绕过漏洞

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
<td style="border:1px solid black;">
[CVE-2015-6139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器特权提升漏洞

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
[CVE-2015-6140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

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
[CVE-2015-6141](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6141)

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
[CVE-2015-6142](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

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
[CVE-2015-6143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6143)

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
<td style="border:1px solid black;">
[CVE-2015-6144](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6144)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器 XSS 筛选器绕过漏洞

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
<td style="border:1px solid black;">
[CVE-2015-6145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6145)

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
[CVE-2015-6146](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6146)

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
[CVE-2015-6147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6147)

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
[CVE-2015-6148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

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
[CVE-2015-6149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6149)

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
[CVE-2015-6150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6150)

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
[CVE-2015-6151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

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
[CVE-2015-6152](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6152)

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
[CVE-2015-6153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

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
[CVE-2015-6154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

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
[CVE-2015-6155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

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
[CVE-2015-6156](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6156)

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
[CVE-2015-6157](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6157)

</td>
<td style="border:1px solid black;">
Internet Explorer 信息泄漏漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2015-6158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

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
[CVE-2015-6159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

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
[CVE-2015-6160](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6160)

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
<td style="border:1px solid black;">
[CVE-2015-6161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Internet Explorer ASLR 绕过

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
[CVE-2015-6162](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6162)

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
[CVE-2015-6164](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6164)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS 筛选器绕过漏洞

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
[**MS15-125：Microsoft Edge 的累积安全更新 (3116184)**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器特权提升漏洞

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
[CVE-2015-6140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6142](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

</td>
<td style="border:1px solid black;">
Microsoft Edge 内存损坏漏洞

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
[CVE-2015-6154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

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
[CVE-2015-6158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

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
[CVE-2015-6159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器内存损坏漏洞

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
[CVE-2015-6161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Microsoft 浏览器 ASLR 绕过

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2015-6168](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6168)

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
[CVE-2015-6169](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6169)

</td>
<td style="border:1px solid black;">
Microsoft Edge 欺骗漏洞

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
[CVE-2015-6170](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6170)

</td>
<td style="border:1px solid black;">
Microsoft Edge 特权提升漏洞

</td>
<td style="border:1px solid black;">
2 - 不太可能利用

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
[CVE-2015-6176](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6176)

</td>
<td style="border:1px solid black;">
Microsoft Edge XSS 筛选器绕过漏洞

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
[**MS15-126：用于解决远程执行代码的 JScript 和 VBScript 累积安全更新 (3116178)**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
脚本引擎信息泄露漏洞

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
[CVE-2015-6136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

</td>
<td style="border:1px solid black;">
脚本引擎内存损坏漏洞

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
[**MS15-127：用于解决远程执行代码的 Microsoft Windows DNS 安全更新 (3100465)**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6125](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6125)

</td>
<td style="border:1px solid black;">
Windows DNS 释放后使用漏洞

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
[**MS15-128：用于解决远程执行代码的 Microsoft 图形组件安全更新 (3104503)**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6106](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6106)

</td>
<td style="border:1px solid black;">
图形内存损坏漏洞

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
[CVE-2015-6107](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6107)

</td>
<td style="border:1px solid black;">
图形内存损坏漏洞

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
[CVE-2015-6108](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6108)

</td>
<td style="border:1px solid black;">
图形内存损坏漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS15-129：用于解决远程执行代码的 Silverlight 安全更新 (3106614)**](https://technet.microsoft.com/zh-cn/library/security/ms15-129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6114](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6114)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 信息泄漏漏洞

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
[CVE-2015-6165](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6165)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 信息泄漏漏洞

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
[CVE-2015-6166](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6166)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight 远程执行代码漏洞

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
<td style="border:1px solid black;" colspan="5">
[**MS15-130：用于解决远程执行代码的 Microsoft Uniscribe 安全更新 (3108670)**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6130](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6130)

</td>
<td style="border:1px solid black;">
Windows 整数下溢漏洞

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
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-131：用于解决远程执行代码的 Microsoft Office 安全更新 (3116111)**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6040](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6040)

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
[CVE-2015-6118](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6118)

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
[CVE-2015-6122](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6122)

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
[CVE-2015-6124](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6124)

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
[CVE-2015-6172](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6172)

</td>
<td style="border:1px solid black;">
Microsoft Office RCE 漏洞

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
[CVE-2015-6177](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6177)

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
[**MS15-132：用于解决远程执行代码的 Microsoft Windows 安全更新 (3116162)**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6128)

</td>
<td style="border:1px solid black;">
Windows 库加载远程执行代码漏洞

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
[CVE-2015-6132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6132)

</td>
<td style="border:1px solid black;">
Windows 库加载远程执行代码漏洞

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
[CVE-2015-6133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6133)

</td>
<td style="border:1px solid black;">
Windows 库加载远程执行代码漏洞

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
[**MS15-133：用于解决特权提升的 Windows PGM 安全更新 (3116130)**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6126)

</td>
<td style="border:1px solid black;">
Windows PGM UAF 特权提升漏洞

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
[**MS15-134：用于解决特权提升的 Windows PGM 安全更新 (3116130)**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6127)

</td>
<td style="border:1px solid black;">
Windows Media Center 信息泄漏漏洞

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
[CVE-2015-6131](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6131)

</td>
<td style="border:1px solid black;">
Media Center 库分析 RCE 漏洞

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
[**MS15-135：用于解决特权提升的 Windows 内核模式驱动程序安全更新 (3119075)**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6171](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6171)

</td>
<td style="border:1px solid black;">
Windows 核心内存特权提升漏洞

</td>
<td style="border:1px solid black;">
3 - 不太可能利用

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
[CVE-2015-6173](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6173)

</td>
<td style="border:1px solid black;">
Windows 核心内存转储特权提升漏洞

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
[CVE-2015-6174](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6174)

</td>
<td style="border:1px solid black;">
Windows 核心内存转储特权提升漏洞

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
[CVE-2015-6175](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6175)

</td>
<td style="border:1px solid black;">
Windows 核心内存转储特权提升漏洞

</td>
<td style="border:1px solid black;">
0 - 检测利用情形

</td>
<td style="border:1px solid black;">
4 - 不受影响

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
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
（严重）  
Internet Explorer 8  
(3104002)  
（严重）  
Internet Explorer 9  
(3104002)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
（严重）  
Microsoft .NET Framework 4  
(3099866)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
（严重）  
Microsoft .NET Framework 4.6  
(3099874)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
（严重）  
Internet Explorer 8  
(3104002)  
（严重）  
Internet Explorer 9  
(3104002)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
（严重）  
Microsoft .NET Framework 4  
(3099866)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
（严重）  
Microsoft .NET Framework 4.6  
(3099874)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
（中等）  
Internet Explorer 8  
(3104002)  
（中等）  
Internet Explorer 9  
(3104002)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3109094)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
（严重）  
Microsoft .NET Framework 4  
(3099866)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
（严重）  
Microsoft .NET Framework 4.6  
(3099874)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
（中等）  
Internet Explorer 8  
(3104002)  
（中等）  
Internet Explorer 9  
(3104002)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3109094)  
（严重）  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
（严重）  
Microsoft .NET Framework 4  
(3099866)  
（严重）  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
（严重）  
Microsoft .NET Framework 4.6  
(3099874)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
（中等）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3109094)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
（严重）  
Internet Explorer 9  
(3104002)  
（严重）  
Internet Explorer 10  
(3104002)  
（严重）  
Internet Explorer 11  
(3104002)  
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
Windows 7（用于 32 位系统）Service Pack 1  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3099862)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
（严重）  
Internet Explorer 9  
(3104002)  
（严重）  
Internet Explorer 10  
(3104002)  
（严重）  
Internet Explorer 11  
(3104002)  
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
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3099862)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
（中等）  
Internet Explorer 9  
(3104002)  
（中等）  
Internet Explorer 10  
(3104002)  
（中等）  
Internet Explorer 11  
(3104002)  
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
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3099862)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
（中等）

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
(3109094)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows 8（用于 32 位系统）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099863)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows 8（用于基于 x64 的系统）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099863)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows 8.1（用于 32 位系统）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099864)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows 8.1（用于基于 x64 的系统）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099864)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099863)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099864)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows RT  
(3109094)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows RT 8.1  
(3109094)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
**无**

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3116869)  
（严重）  
Microsoft .NET Framework 3.5  
(3116869)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3116869)  
（严重）  
Microsoft .NET Framework 3.5  
(3116869)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3116900)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于基于 x64 的系统）  
(3116900)  
（严重）

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
[**MS15-124**](https://technet.microsoft.com/zh-cn/library/security/ms15-124)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/zh-cn/library/security/ms15-125)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/zh-cn/library/security/ms15-126)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/zh-cn/library/security/ms15-127)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3109094)  
（严重）

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
(3105579)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3109094)  
（严重）

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
VBScript 5.8  
(3105578)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5.1  
(3099862)  
（严重）

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
Windows Server 2012  
（服务器核心安装）  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099863)  
（严重）

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
Windows Server 2012 R2  
（服务器核心安装）  
(3100465)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3109094)  
（严重）  
Microsoft .NET Framework 3.5  
(3099864)  
（严重）

</td>
</tr>
</table>

**MS15-128 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Windows 操作系统和组件（表 2-2）

<p> </p>
<table style="border:1px solid black;">
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx) 

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Vista Service Pack 2  
(3108371)  
（重要）  
Windows Vista Service Pack 2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
（重要）

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
Windows Vista x64 Edition Service Pack 2  
(3108371)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
<td style="border:1px solid black;" colspan="3">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3108371)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3109094)  
（重要）

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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3108371)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3109094)  
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
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3108371)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3109103)

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3108670)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3108371)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3108670)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3108371)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3108670)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3108371)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3108670)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3108371)  
（重要）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3108347)  
（重要）  
Windows 8（用于 32 位系统）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3108347)  
（重要）  
Windows 8（用于基于 x64 的系统）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3109094)  
（重要）

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
Windows 8.1（用于 32 位系统）  
(3108347)  
（重要）  
Windows 8.1（用于 32 位系统）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3108347)  
（重要）  
Windows 8.1（用于基于 x64 的系统）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3108347)  
（重要）  
Windows Server 2012  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3108347)  
（重要）  
Windows Server 2012 R2  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3108347)  
（重要）  
Windows RT  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3109094)  
（重要）

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
Windows RT 8.1  
(3108347)  
（重要）  
Windows RT 8.1  
(3108381)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109094)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3116869)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3116869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于 32 位系统）  
(3116869)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3116869)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3116869)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10（用于基于 x64 的系统）  
(3116869)  
（重要）

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
(3116900)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3116900)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（用于 32 位系统）  
(3116900)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 版本 1511（基于 x64 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（基于 x64 的系统）  
(3116900)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（基于 x64 的系统）  
(3116900)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 10 版本 1511（基于 x64 的系统）  
(3116900)  
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
[**MS15-130**](https://technet.microsoft.com/zh-cn/library/security/ms15-130)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/zh-cn/library/security/ms15-132)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/zh-cn/library/security/ms15-133)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/zh-cn/library/security/ms15-134)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/zh-cn/library/security/ms15-135)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**无**

</td>
<td style="border:1px solid black;">
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
（服务器核心安装）  
(3109094)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
（服务器核心安装）  
(3109094)  
（重要）

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
(3108670)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
（服务器核心安装）  
(3109094)  
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
Windows Server 2012  
（服务器核心安装）  
(3108347)  
（重要）  
Windows Server 2012  
（服务器核心安装）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012  
（服务器核心安装）  
(3109094)  
（重要）

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
Windows Server 2012 R2  
（服务器核心安装）  
(3108347)  
（重要）  
Windows Server 2012 R2  
（服务器核心安装）  
(3108381)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3109103)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
（服务器核心安装）  
(3109094)  
（重要）

</td>
</tr>
</table>

 

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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085616)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085549)  
（重要）  
Microsoft Excel 2007 Service Pack 3  
(3114422)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(3114458)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3085612)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3085528)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(3114403)  
（严重）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(3114415)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(3101532)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3085612)  
（严重）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3085528)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(3114403)  
（严重）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(3114415)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(3101532)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1（32 位版本）  
(3114342)  
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
Microsoft Word 2013 Service Pack 1（64 位版本）  
(3114342)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016（32 位版本）  
(3114382)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word 2016（64 位版本）  
(3114382)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(3114342)  
（严重）

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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Microsoft Excel for Mac 2011  
(3119517)  
（重要）

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
Microsoft Excel 2016 for Mac  
(3119518)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/zh-cn/library/security/ms15-131)

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
[**重要说明**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3114457)  
（严重）  
Microsoft Office 兼容包 Service Pack 3  
(3114431)  
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
(3114433)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114478)  
（严重）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS15-128 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
(3115875)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
(3115871)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(3115871)  
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
(3115872)  
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
(3115873)  
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1（32 位）  
(Skype for Business)  
(3114351)  
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
(3114351)  
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
(3114351)  
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
(3114351)  
（严重）

</td>
</tr>
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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

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
Skype for Business 2016（32 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（32 位）  
(3114372)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（32 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（32 位）  
(3114372)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）  
(3114372)  
（严重）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）

</td>
<td style="border:1px solid black;">
Skype for Business 2016（64 位）  
(3114372)  
（严重）

</td>
</tr>
</table>

**MS15-128 的注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

 

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
[**MS15-128**](https://technet.microsoft.com/zh-cn/library/security/ms15-128)

</td>
<td style="border:1px solid black;">
[**MS15-129**](https://technet.microsoft.com/zh-cn/library/security/ms15-129)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）

</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5  
(3106614)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(3106614)  
（严重）

</td>
</tr>
</table>

**MS15-128 的注释**

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

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn903755.aspx)部分。

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

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/zh-cn/kb/913086)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://support.microsoft.com/zh-cn/lifecycle)。

IT 专业人员的安全解决方案：[TechNet 安全性疑难解答与支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

根据国家/地区进行本地支持：[国际化支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 12 月 8 日）：已发布公告摘要。
-   V1.1（2015 年 12 月 9 日）：公告摘要经过修订，更正了 CVE-2015-6124 的利用指数。此仅为信息变更
-   V1.2（2015 年 12 月 16 日）：公告摘要经过修订，以向 3104002 的执行摘要表添加一个已知问题。要解决此问题，请安装修补程序 3125446。请参阅 [Microsoft 知识库文章 3104002](https://support.microsoft.com/zh-cn/kb/3104002) 了解详细信息。

*页面生成时间：2015-12-16 17:23-08:00。*
