---
TOCTitle: 'MS13-JUL'
Title: 'Microsoft 安全公告摘要（2013 年 7 月）'
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61236981
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-jul(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 7 月）
======================================

发布时间: 2013年7月9日 | 更新时间: 2013年8月27日

**版本:** 3.0

本公告摘要列出了 2013 年 7 月发布的安全公告。

对于 2013 年 7 月发布的安全公告，本公告摘要替代 2013 年 7 月 4 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 7 月 10 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 7 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=en-us)。此日期之后，此网络广播[按需](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)提供。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

### 公告信息

#### 摘要

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 和 Silverlight 中的漏洞可能允许远程执行代码 (2861561)</strong><br />
<br />
此安全更新可解决 Microsoft .NET Framework 和 Microsoft Silverlight 中五个秘密报告的漏洞和两个公开披露的漏洞。如果受信任的应用程序使用特定代码模式，则这些漏洞中最严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与登录用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft .NET Framework，<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>内核模式驱动程序中的漏洞可能允许远程执行代码 (2761226)<br />
<br />
</strong>此安全更新解决 Microsoft Windows 中两个公开披露的漏洞和六个秘密报告的漏洞。如果用户查看包含特制 TrueType 字体的共享内容，则最严重的漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以完全控制受影响的系统。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;"><strong>GDI+</strong> <strong>中的漏洞可能允许远程执行代码 (2848295)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows、Microsoft Office、Microsoft Lync 和 Microsoft Visual Studio 中一个秘密报告的漏洞。如果用户查看包含特制 TrueType 字体的共享内容，则该漏洞可能允许远程执行代码。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Microsoft Office，<br />  
Microsoft Visual Studio、<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 累积性安全更新 (2846071)</strong> <strong><br />
<br />
</strong>此安全更新可解决 Internet Explorer 中的 17 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow 中的漏洞可能允许远程执行代码 (2845187)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开特制的图像文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;"><strong>Windows Media Format Runtime 中的漏洞可能允许远程执行代码 (2847883)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户打开特制的媒体文件，该漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与本地用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;"><strong>Windows Defender 中的漏洞可能允许特权提升 (2847927)<br />
<br />
</strong>此安全更新可解决适用于 Windows 7 的 Windows Defender 和 Windows Server 2008 R2 上安装的 Windows Defender 中一个秘密报告的漏洞。由于 Windows Defender 所使用的路径名称，该漏洞可能允许特权提升。成功利用此漏洞的攻击者可执行任意代码，并可完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。攻击者必须拥有有效的登录凭据才能利用此漏洞。匿名用户无法利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">无需重新启动</td>
<td style="border:1px solid black;">Microsoft 安全软件</td>
</tr>  
</tbody>  
</table>
  
利用指数  
--------
  
  
下表提供了本月解决的各个漏洞的利用评估。这些漏洞按公告 ID 和 CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/security/cc998259)。
  
在本公告中“受影响的软件”和“不受影响的软件”表的下面几列中，“最新版本的软件发布”是指主题软件，“较旧版本的软件发布”是指主题软件的所有较旧的受支持版本。

<p> </p>
<table style="border:1px solid black;">  
<thead>  
<tr class="header">  
<th>公告 ID</th>  
<th>漏洞标题</th>  
<th>CVE ID</th>  
<th>最新软件版本的利用评估</th>  
<th>较旧软件版本的利用评估</th>  
<th>拒绝服务利用评估</th>  
<th>重要注意事项</th>  
</tr>  
</thead>  
<tbody>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">TrueType 字体分析漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">数组访问冲突漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">委派反射绕过漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">匿名方法注入漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">数组分配漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">此漏洞已公开披露。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">委派序列化漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">空指针漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 内存分配漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 解除引用漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是最新软件版本上的一个拒绝服务漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是最新软件版本上的一个拒绝服务漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">TrueType 字体分析漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">这是一个可能导致特权提升的信息泄露漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 缓冲区覆盖漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k 读取 AV 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">此漏洞已公开披露。<br />
<br />
Microsoft 获悉尝试利用此漏洞进行特权提升的目标攻击。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">TrueType 字体分析漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">Microsoft 获悉尝试通过 Internet Explorer8 利用此漏洞的目标攻击。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Shift JIS 字符编码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">DirectShow 任意内存覆盖漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">WMV 视频解码器远程执行代码漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Microsoft Windows 7 Defender 路径名不正确漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
</tbody>  
</table>
  
受影响的软件  
------------
  
  
下表按主要软件类别和严重性的排序列出了公告。
  
**如何使用这些表？**
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
#### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>  
<th colspan="8" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 Service Pack 3  
（仅限 Media Center Edition 2005 Service Pack 3 和 Tablet PC Edition 2005 Service Pack 3）  
(2833951)  
（重要）  
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(Windows GDI+)  
(2834886)  
（严重）  
Windows XP Service Pack 3  
（仅限 Windows XP Tablet PC Edition 2005）  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
（严重）  
Internet Explorer 7  
(2846071)  
（严重）  
Internet Explorer 8  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 11<sup>[1]</sup>  
(wmvdecod.dll)  
（仅限 Media Center Edition）  
(2834904)  
（严重）  
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
（仅限 Media Center Edition）  
(2834905)  
（严重）  
Windows Media Format Runtime 9  
(wmvdmod.dll)  
(2803821)  
（严重）  
Windows Media Format Runtime 9.5<sup>[2]</sup>  
(wmvdmod.dll)  
(2834902)  
（严重）  
Windows Media Format Runtime 9.5<sup>[3]</sup>  
(wmvdmod.dll)  
(2834903)  
（严重）  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>
  
(2840628)  
（重要）

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
（严重）  
Internet Explorer 7  
(2846071)  
（严重）  
Internet Explorer 8  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
（严重）  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
（严重）  
Windows Media Format Runtime 11  
(wmvdecod.dll)  
(2834904)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833949)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
（中等）  
Internet Explorer 7  
(2846071)  
（中等）  
Internet Explorer 8  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
（中等）  
Internet Explorer 7  
(2846071)  
（中等）  
Internet Explorer 8  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Format Runtime 9.5  
(wmvdmod.dll)  
(2803821)  
（严重）  
Windows Media Format Runtime 9.5 x64  
(wmvdmod.dll)  
(2834902)  
（严重）  
Windows Media Format Runtime 11  
(wmvdmod.dll)  
(2834904)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
（重要）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2846071)  
（中等）  
Internet Explorer 7  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2835622)  
（严重）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(DirectWrite)  
(2835361)  
（严重）  
Windows Vista Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）  
Windows Vista Service Pack 2  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
（严重）  
Internet Explorer 8  
(2846071)  
（严重）  
Internet Explorer 9  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2835622)  
（严重）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(DirectWrite)  
(2835361)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）  
Windows Vista x64 Edition Service Pack 2  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
（严重）  
Internet Explorer 8  
(2846071)  
（严重）  
Internet Explorer 9  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
（严重）  
wmv9vcm.dll（编码解码器）  
(2845142)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2835622)  
（严重）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(DirectWrite)  
(2835361)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
（中等）  
Internet Explorer 8  
(2846071)  
（中等）  
Internet Explorer 9  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
（严重）  
WMV9vcm.dll （编码解码器）\[5\]  
(2845142)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
（重要）  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
（严重）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2832407)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2835622)  
（严重）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(DirectWrite)  
(2835361)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
（中等）  
Internet Explorer 8  
(2846071)  
（中等）  
Internet Explorer 9  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
（严重）  
WMV9vcm.dll （编码解码器）\[5\]  
(2845142)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
（重要）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
（严重）  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
（重要）  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2833946)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2840631)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2844286)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(DirectWrite)  
(2835361)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(Windows GDI+)  
(2834886)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
（严重）  
Internet Explorer 9  
(2846071)  
（严重）  
Internet Explorer 10  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2833946)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2840631)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2844286)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(DirectWrite)  
(2835361)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(Windows GDI+)  
(2834886)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
（严重）  
Internet Explorer 9  
(2846071)  
（严重）  
Internet Explorer 10  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2833946)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2840631)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2844286)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(DirectWrite)  
(2835361)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(Windows GDI+)  
(2834886)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
（中等）  
Internet Explorer 9  
(2846071)  
（中等）  
Internet Explorer 10  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2840631)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2844286)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(DirectWrite)  
(2835361)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
（严重）  
Microsoft .NET Framework 3.5  
(2833959)  
（严重）  
Microsoft .NET Framework 3.5  
(2840633)  
（重要）  
Microsoft .NET Framework 3.5  
(2844289)  
（重要）  
Microsoft .NET Framework 4.5  
(2833958)  
（严重）  
Microsoft .NET Framework 4.5  
(2840632)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(DirectWrite)  
(2835361)  
（严重）  
Windows 8（用于 32 位系统）  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
（严重）  
Microsoft .NET Framework 3.5  
(2833959)  
（严重）  
Microsoft .NET Framework 3.5  
(2840633)  
（重要）  
Microsoft .NET Framework 3.5  
(2844289)  
（重要）  
Microsoft .NET Framework 4.5  
(2833958)  
（严重）  
Microsoft .NET Framework 4.5  
(2840632)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(DirectWrite)  
(2835361)  
（严重）  
Windows 8（用于 64 位系统）  
(Journal)  
(2835364)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 64 位系统）  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
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
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
（严重）  
Microsoft .NET Framework 3.5  
(2833959)  
（严重）  
Microsoft .NET Framework 3.5  
(2840633)  
（重要）  
Microsoft .NET Framework 3.5  
(2844289)  
（重要）  
Microsoft .NET Framework 4.5  
(2833958)  
（严重）  
Microsoft .NET Framework 4.5  
(2840632)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
（严重）  
Windows Server 2012  
(Journal)  
(2835364)  
（严重）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
（严重）
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
<td style="border:1px solid black;" colspan="2">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
（严重）  
Microsoft .NET Framework 4.5  
(2840632)  
（重要）
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
（严重）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2846071)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
（严重）
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-053**](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[**MS13-055**](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[**MS13-056**](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;" colspan="2">
[**MS13-057**](https://go.microsoft.com/fwlink/?linkid=301528)
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
**无**
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;" colspan="2">
**无**
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
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
（严重）  
Microsoft .NET Framework 3.5.1  
(2840631)  
（重要）  
Microsoft .NET Framework 3.5.1  
(2844286)  
（重要）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2835393)  
（严重）  
Microsoft .NET Framework 4<sup>[1]</sup>  
(2840628)  
（重要）  
Microsoft .NET Framework 4.5  
(2833957)  
（严重）  
Microsoft .NET Framework 4.5  
(2840642)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(Windows GDI+)  
(2834886)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
（严重）  
Microsoft .NET Framework 3.5  
(2833959)  
（严重）  
Microsoft .NET Framework 3.5  
(2840633)  
（重要）  
Microsoft .NET Framework 3.5  
(2844289)  
（重要）  
Microsoft .NET Framework 4.5  
(2833958)  
（严重）  
Microsoft .NET Framework 4.5  
(2840632)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2850851)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(DirectWrite)  
(2835361)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;" colspan="2">
不适用
</td>
</tr>
</table>

**MS13-052 的注释**

<sup>[1]</sup>**.NET Framework 4 和 .NET Framework 4 客户端配置文件受到影响。**两种配置文件中提供 .NET Framework 版本 4 可再次分发程序包： .NET Framework 4 和 .NET Framework 4 客户端配置文件。.NET Framework 4 Client Profile 是 .NET Framework 4 的子集。此更新中解决的漏洞同时影响 .NET Framework 4 和 .NET Framework 4 Client Profile。有关详细信息，请参阅 MSDN 文章“[安装 .NET Framework](https://msdn.microsoft.com/library/5a4x27ek)”。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS13-053** **和** **MS13-055 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS13-054 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS13-057 的注释**

<sup>[1]</sup>此更新仅提供给已升级到 Windows Media Format Runtime 11 或 Windows Media Player 11 的系统。
<sup>[2]</sup>此更新仅提供给运行 Windows Media Format Runtime 9.5 NL 的系统。
<sup>[2]</sup>此更新仅提供给运行 Windows Media Format Runtime 9.5 L 的系统。
\[4\]仅当可选桌面体验功能启用时，才提供此更新。
\[5\]仅当可选桌面体验功能启用并且存在 wmv9vcm.dll 编码解码器时，才提供此更新。请参阅公告以了解详细信息。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Office 软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817480)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687309)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
(2687276)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
(2687276)  
（重要）
</td>
</tr>
</table>

**MS13-054 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 开发工具和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
</tr>
<tr class="alternateRow">
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
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1<sup>[1]</sup>  
(2856545)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[**MS13-052**](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
安装在 Mac 上的 Microsoft Silverlight 5  
(2847559)  
（严重）  
安装在 Mac 上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
（严重）  
安装在 Microsoft Windows 客户端的 32 位版本上的 Microsoft Silverlight 5  
(2847559)  
（严重）  
安装在 Microsoft Windows 客户端的基于 x64 版本上的 Microsoft Silverlight 5  
(2847559)  
（严重）  
安装在 Microsoft Windows 客户端的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
（严重）  
安装在 Microsoft Windows 服务器的 32 位版本上的 Microsoft Silverlight 5  
(2847559)  
（严重）  
安装在 Microsoft Windows 服务器的基于 x64 版本上的 Microsoft Silverlight 5  
(2847559)  
（严重）  
安装在 Microsoft Windows 服务器的所有受支持版本上的 Microsoft Silverlight 5 Developer Runtime  
(2847559)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
</table>

**MS13-052 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

**MS13-054 的注释**

<sup>[1]</sup>此更新只能从 Microsoft 下载中心下载。

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别。

#### Microsoft 通信平台和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-054**](https://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Lync 2010 （32 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （32 位）  
(2843160)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 （64 位）  
(2843160)  
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
(2843162)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
（管理员级别安装）  
(2843163)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （32 位）  
(2817465)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 （32 位）  
(2817465)  
（严重）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 （64 位）  
(2817465)  
（严重）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013（64 位）
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013（64 位）  
(2817465)  
（严重）
</td>
</tr>
</table>

**MS13-054 的注释**

有关相同公告标识符下的更多更新文件，另请参阅本部分“**受影响的软件和下载位置**”下的其他软件类别。此公告涉及多个软件类别

#### Microsoft 安全软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2" style="border:1px solid black;">
反间谍软件
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-058**](https://go.microsoft.com/fwlink/?linkid=308992)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
适用于 Windows 7 的 Windows Defender (x86)
</td>
<td style="border:1px solid black;">
适用于 Windows 7 的 Windows Defender (x86)  
(2847927)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
适用于 Windows 7 的 Windows Defender (x64)
</td>
<td style="border:1px solid black;">
适用于 Windows 7 的 Windows Defender (x64)  
(2847927)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
安装在 Windows Server 2008 R2 上的 Windows Defender (x64)
</td>
<td style="border:1px solid black;">
安装在 Windows Server 2008 R2 上的 Windows Defender (x64)  
(2847927)  
（重要）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

**安全中心**

管理需要部署到组织中的服务器、台式机和移动计算机的软件和安全更新。有关详细信息，请参阅 [TechNet 更新管理中心](https://go.microsoft.com/fwlink/?linkid=69903)。[TechNet 安全技术中心](https://go.microsoft.com/fwlink/?linkid=21171)提供了有关 Microsoft 产品安全性的其他信息。消费者可以访问 [Microsoft 安全中心](https://go.microsoft.com/fwlink/?linkid=85102)，也可以通过单击“安全更新”访问此信息。

安全更新可从 [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 和 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) 获得。[Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)也提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到这些更新。

对于 Microsoft Office for Mac 的客户，Microsoft AutoUpdate for Mac 有助于使 Microsoft 软件保持最新。有关使用 Microsoft AutoUpdate for Mac 的详细信息，请参阅[自动检查软件更新](https://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)。

最后，可以从 [Microsoft Update 目录](https://go.microsoft.com/fwlink/?linkid=96155)下载安全更新。Microsoft Update 目录提供通过 Windows Update 和 Microsoft Update 提供的内容的可搜索目录，包括安全更新、驱动程序和 Service Pack。通过使用安全公告编号（例如“MS13-001”）进行搜索，您可以将所有适用的更新添加到您的篮（包括某个更新的不同语言），然后将其下载到您选择的文件夹。有关 Microsoft Update 目录的详细信息，请参阅 [Microsoft Update 目录常见问题](https://go.microsoft.com/fwlink/?linkid=97900)。

**检测和部署指南**

Microsoft 提供安全更新的检测和部署指南。该指南包含可帮助 IT 专业人员了解如何使用各种工具检测和部署安全更新的建议和信息。有关详细信息，请参阅 [Microsoft 知识库文章 961747](https://support.microsoft.com/kb/961747)。

**Microsoft Baseline Security Analyzer**

管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。有关 MBSA 的详细信息，请参阅 [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134)。

**Windows Server Update Services**

通过使用 Windows Server Update Services (WSUS)，管理员可以快速可靠地将 Microsoft Windows 2000 操作系统和更高版本、Office XP 和更高版本、Exchange Server 2003 以及 SQL Server 2000 的最新关键更新和安全更新部署到 Microsoft Windows 2000 和更高版本的操作系统。

有关如何使用 Windows Server Update Services 部署此安全更新的详细信息，请访问 [Windows Server Update Services](https://technet.microsoft.com/wsus/default)。

**SystemCenter Configuration Manager**

System Center Configuration Manager 软件更新管理简化了在整个企业中提供和管理 IT 系统更新的复杂任务。通过 System Center Configuration Manager，IT 管理员可以为包括台式机、便携式计算机、服务器和移动设备在内的各种设备提供 Microsoft 产品更新。

System Center Configuration Manager 中的自动漏洞评估发现需要根据建议的操作进行更新和报告。System Center Configuration Manager 中的软件更新管理基于 Microsoft Windows Software Update Services (WSUS) 构建，它是全球 IT 管理员所熟悉的经过时间检验的更新基础结构。有关 System Center Configuration Manager 的详细信息，请参阅 [System Center 技术资源](https://technet.microsoft.com/systemcenter/bb980621)。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。

**注意** System Management Server 2003 自 2010 年 1 月 12 日起不再受主流支持。有关产品生命周期的详细信息，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。SMS 的下一版本 System Center Configuration Manager 现已可用；请参阅前面的部分 **System Center Configuration Manager**。

有关管理员如何使用 SMS 2003 部署安全更新的详细信息，请参阅 [Microsoft Systems Management Server 2003 的方案和过程： 软件分发和修补程序管理](https://www.microsoft.com/download/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f)。有关 SMS 的信息，请访问 [Microsoft Systems Management Server TechCenter](https://technet.microsoft.com/systemcenter/bb545936)。

**注意：** SMS 使用 Microsoft Baseline Security Analyzer 提供对安全公告更新检测和部署的广泛支持。这些工具可能检测不到某些软件更新。在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。有关此过程的详细信息，请参阅[使用 SMS 软件分发功能部署软件更新](https://go.microsoft.com/fwlink/?linkid=33341)。某些安全更新在重新启动系统后可能需要管理权限。管理员可以使用提升权限部署工具（在 [SMS 2003 管理功能包](https://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d)中提供）安装这些更新。

**更新兼容性评估程序和应用程序兼容性工具箱**

此更新通常写入运行应用程序所必需的相同文件和注册表设置。这可触发不兼容并使安全更新的部署占用更多的时间。通过使用[应用程序兼容性工具包](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971)中包含的[更新兼容性评估程序](https://technet.microsoft.com/library/cc749197)组件，您可以简化测试和验证对已安装程序进行的 Windows 更新。

应用程序兼容性工具包 (ACT) 包含必要的工具和文档，以便在您的环境中部署 Windows Vista、Windows Update、Microsoft Security Update 或新版本的 Windows Internet Explorer 之前评估和缓减应用程序的兼容性问题。

### 其他信息

#### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows Update、Microsoft Update、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

#### MU、WU 和 WSUS 上的非安全更新

有关 Windows Update 和 Microsoft Update 上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199)： Software Update Services 和 Windows Server Update Services 的内容更改说明。包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/wsus/bb456965)。显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

#### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://go.microsoft.com/fwlink/?linkid=215201)中列出）提供的活动保护网站。

#### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://go.microsoft.com/fwlink/?linkid=21168)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) 提供了消费者平台的更新。
-   您可以从 Microsoft 下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows Update 上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086)。

**IT 专业人员安全区域社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://go.microsoft.com/fwlink/?linkid=21164)中就安全主题与其他 IT 专业人员展开讨论。

#### 鸣谢

Microsoft [感谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

**MS13-052**

-   [F-13 Laboratory](https://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 报告了 TrueType 字体分析漏洞 (CVE-2013-3129)
-   Alon Fliess 报告了数组访问违反漏洞 (CVE-2013-3131)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了委派反射绕过漏洞 (CVE-2013-3132)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了匿名方法注入漏洞 (CVE-2013-3133)
-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了委派序列化漏洞 (CVE-2013-3171)
-   Vitaliy Toropov 报告了空指针漏洞 (CVE-2013-3178)

**MS13-053**

-   MWR Labs 的 Jon Butler 和 Nils 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/)　一起报告了　Win32k 内存分配漏洞 (CVE-2013-1300)
-   [Dr.Web](https://drweb.com/) 的 Alexander Chizhov 报告了 Win32k 解除引用漏洞 (CVE-2013-1340)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Win32k 窗口句柄漏洞 (CVE-2013-1345)
-   [F13 Laboratory](https://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 报告了 TrueType 字体分析漏洞 (CVE-2013-3129)
-   [腾讯电脑管家](https://guanjia.qq.com)的 Yinliang 报告了 Win32k 信息泄露漏洞 (CVE-2013-3167)
-   [Google Inc](https://www.google.com/) 的[Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/)报告了 Win32k 缓冲区溢出漏洞 (CVE-2013-3172)
-   Wen Yujie 和 [Qihoo 360 Security Center](https://www.360.cn/) 的 Guo Pengfei 报告了 Win32k 缓冲区覆盖漏洞 (CVE-2013-3173)

**MS13-054**

-   [F13 Laboratory](https://www.f13-labs.net/) 的 Ling Chuan Lee 和 Lee Yee Chan 报告了 TrueType 字体分析漏洞 (CVE-2013-3129)

**MS13-055**

-   [Google Security Team](https://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3115)
-   SkyLined 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3143)
-   Simon Zuckerbraun 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3144)
-   Toan Pham Van 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3145)
-   Toan Pham Van 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3146)
-   [Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3147)
-   Bluesea 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3148)
-   Bluesea 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3149)
-   [Omair](https://krash.in/) 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3150)
-   Toan Pham Van 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3151)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3152)
-   e6af8de8b1d4b2b6d5ba2610cbf9cd38 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3153)
-   [Google Security Team](https://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3161)
-   [Google Security Team](https://www.google.com/) 的 Ivan Fratric 和 Ben Hawkes 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3162)
-   Jose Antonio Vazquez Gonzalez 与 [VeriSign iDefense Labs](https://labs.idefense.com) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3163)
-   [Security-Assessment.com](https://www.security-assessment.com/) 的 Scott Bell 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3164)
-   Masato Kinugawa 报告了 Shift JIS 字符编码漏洞 (CVE-2013-3166)
-   IBM X-Force 的 Mark Yason 与我们一起努力处理了此公告中包括的纵深防御更改 (CVE-2013-4015)

**MS13-056**

-   Andrés Gómez Ramírez 报告了 DirectShow 任意内存覆盖漏洞 (CVE-2013-3174)

**MS13-057**

-   一位匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/)，合作报告了 WMV 视频解码器远程执行代码漏洞 (CVE-2013-3127)

**MS13-058**

-   [Reserve Bank of Australia](https://www.rba.gov.au/) 的 Alton Blom 报告了 Microsoft Windows 7 Defender 不正确的路径名称漏洞 (CVE-2013-3154)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 7 月 9 日）： 已发布公告摘要。
-   V1.1（2013 年 7 月 9 日）： 对于 MS13-055，在“**利用指数**”中修改了对 CVE-2013-3163 的利用评估。Microsoft 获悉尝试通过 Internet Explorer8 利用此漏洞的目标攻击。这仅仅是信息更改。
-   V2.0（2013 年 8 月 13 日）： 对于 MS13-052，已修订公告以重新发布 2840628、2840632、2840642、2844285、2844286、2844287 和 2844289 更新。对于 MS13-057，已修订公告以针对 Windows 7 和 Windows 2008 R2 重新发布 2803821 更新。客户应该安装适用于其系统的重新发布的更新。有关详细信息，请参阅各自的公告。
-   V3.0 （2013 年 8 月 27 日）： 对于 MS13-057，已修订公告以重新发布适用于 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的更全更新 2803821；适用于 Windows XP 和 Windows Server 2003 的安全更新 2834902；适用于 Windows XP 的安全更新 2834903；适用于 Windows XP 和 Windows Server 2003 的安全更新 2834904 以及适用于 Windows XP 的安全更新 2834905。使用 Windows XP、Windows Server 2003、Windows Vista 和 Windows Server 2008 的客户应安装重新发布的适用其系统的更新。有关详细信息，请参阅公告。

*Built at 2014-04-18T01:50:00Z-07:00*
