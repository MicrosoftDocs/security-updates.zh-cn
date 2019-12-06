---
TOCTitle: 'MS13-NOV'
Title: 'Microsoft 安全公告摘要（2013 年 11 月）'
ms:assetid: 'ms13-nov'
ms:contentKeyID: 61236985
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms13-nov(v=Security.10)'
---



Microsoft 安全公告摘要（2013 年 11 月）
=======================================

发布时间: 2013年11月12日

**版本:** 1.0

本公告摘要列出了 2013 年 11 月发布的安全公告。

对于 2013 年 11 月发布的安全公告，本公告摘要替代 2013 年 11 月 7 日最初发布的公告预先通知。有关公告预先通知服务的详细信息，请参阅 [Microsoft 安全公告预先通知](https://go.microsoft.com/fwlink/?linkid=217213)。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://go.microsoft.com/fwlink/?linkid=21163)。

Microsoft 将在 2013 年 11 月 13 日上午 11 点（美国和加拿大太平洋时间）进行网络广播，以解答客户关于这些公告的疑问。[立即注册申请收听 11 月份安全公告网络广播](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557383&culture=en-us)。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 的累积性安全更新 (2888505)</strong><br />
<br />
此安全更新可解决 Internet Explorer 中的 10 个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看特制网页时允许远程执行代码。成功利用这些最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows，<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;"><strong>Windows 图形设备接口中的漏洞可能允许远程执行代码 (2876331)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果用户在写字板中查看或打开特制 Windows Write 文件，则此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;"><strong>ActiveX Kill Bit 的累积性安全更新 (2618451)</strong><br />
<br />
此安全更新解决了当前正被利用的一个秘密报告的漏洞。InformationCardSigninHelper 类 ActiveX 控件中存在该漏洞。如果用户使用实例化 ActiveX 控件的 Internet Explorer 查看特制网页，此漏洞可能允许远程执行代码。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">严重</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (2885093)</strong><br />
<br />
此安全更新可解决 Microsoft Office 中<strong></strong>3 个秘密报告的漏洞。如果特制 WordPerfect 文档文件在 Microsoft Office 软件受影响的版本中打开，则这些漏洞可能允许远程执行代码。成功利用最严重的漏洞的攻击者可以获得与当前用户相同的用户权限。那些帐户被配置为拥有较少系统用户权限的用户比具有管理用户权限的用户受到的影响要小。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
远程执行代码</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;"><strong>Hyper-V 中的漏洞可能允许特权提升 (2893986)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者将虚拟化调用中的特制函数参数从当前运行的虚拟机传递到虚拟机监控程序，则该漏洞可能允许特权提升。如果攻击者将虚拟化调用中的特制函数参数从当前运行的虚拟机传递到虚拟机监控程序，则对于 Hyper-V 主机，此漏洞也可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特权提升</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;"><strong>Windows 辅助功能驱动程序中的漏洞可能允许信息泄露 (2875783)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。如果攻击者以本地用户身份登录受影响的系统，并且在系统上运行旨在使攻击者从特权较高的帐户中获取信息的应用程序，则此漏洞可能允许信息泄露。攻击者必须拥有有效的登录凭据并能本地登录才能利用此漏洞。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;"><strong>Microsoft Outlook 中的漏洞可能允许信息泄露 (2894514)</strong><br />
<br />
此安全更新可解决 Microsoft Outlook 中一个公开披露的漏洞。如果用户使用受影响的 Microsoft Outlook 版本打开或预览特制的电子邮件，则此漏洞可能允许信息泄露。成功利用此漏洞的攻击者可能会从目标系统和与目标系统共享网络的其他系统确定系统信息（例如，IP 地址和开放的 TCP 端口）。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
信息泄露</td>
<td style="border:1px solid black;">可能要求重新启动</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;"><strong>数字签名中的漏洞可能允许拒绝服务</strong> <strong>(2868626)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个秘密报告的漏洞。当受影响的 Web 服务处理特制 X.509 证书时，此漏洞可能允许拒绝服务。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
拒绝服务</td>
<td style="border:1px solid black;">需要重启动</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3871">CVE-2013-3871</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3908">CVE-2013-3908</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3909">CVE-2013-3909</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3910">CVE-2013-3910</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3911">CVE-2013-3911</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3912">CVE-2013-3912</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3914">CVE-2013-3914</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3915">CVE-2013-3915</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3916">CVE-2013-3916</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325357">MS13-088</a></td>
<td style="border:1px solid black;">Internet Explorer 内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3917">CVE-2013-3917</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">2</a> - 漏洞检测代码会很难创建</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325390">MS13-089</a></td>
<td style="border:1px solid black;">图形设备接口整数溢出漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3940">CVE-2013-3940</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329834">MS13-090</a></td>
<td style="border:1px solid black;">InformationCardSigninHelper 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3918">CVE-2013-3918</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">Microsoft 获悉尝试使用此漏洞的有限目标攻击。</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">WPD 文件格式内存损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0082">CVE-2013-0082</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 堆栈缓冲区覆盖漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1324">CVE-2013-1324</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325392">MS13-091</a></td>
<td style="border:1px solid black;">Word 堆覆盖漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1325">CVE-2013-1325</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324692">MS13-092</a></td>
<td style="border:1px solid black;">地址损坏漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3898">CVE-2013-3898</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">1</a> - 可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">永久</td>
<td style="border:1px solid black;">（无）</td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325391">MS13-093</a></td>
<td style="border:1px solid black;">辅助功能驱动程序信息泄露漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3887">CVE-2013-3887</a></td>
<td style="border:1px solid black;">不受影响</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。</td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=324873">MS13-094</a></td>
<td style="border:1px solid black;">S/MIME AIA 漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3905">CVE-2013-3905</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">不适用</td>
<td style="border:1px solid black;">这是一个信息泄露漏洞。<br />
<br />
此漏洞已公开披露。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=320632">MS13-095</a></td>
<td style="border:1px solid black;">数字签名漏洞</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3869">CVE-2013-3869</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/cc998259">3</a> - 不太可能被利用的漏洞检测代码</td>
<td style="border:1px solid black;">临时</td>
<td style="border:1px solid black;">这是一个拒绝服务漏洞。</td>
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
<th colspan="7" style="border:1px solid black;">  
Windows XP  
</th>  
</tr>  
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
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
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
（严重）  
Internet Explorer 7  
(2888505)  
（严重）  
Internet Explorer 8  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
（严重）  
Internet Explorer 7  
(2888505)  
（严重）  
Internet Explorer 8  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
（重要）  
Internet Explorer 7  
(2888505)  
（重要）  
Internet Explorer 8  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
（重要）  
Internet Explorer 7  
(2888505)  
（重要）  
Internet Explorer 8  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2888505)  
（重要）  
Internet Explorer 7  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
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
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
（严重）  
Internet Explorer 8  
(2888505)  
（严重）  
Internet Explorer 9  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
（严重）  
Internet Explorer 8  
(2888505)  
（严重）  
Internet Explorer 9  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
（重要）  
Internet Explorer 8  
(2888505)  
（重要）  
Internet Explorer 9  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
（重要）  
Internet Explorer 8  
(2888505)  
（重要）  
Internet Explorer 9  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
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
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
（严重）  
Internet Explorer 9  
(2888505)  
（严重）  
Internet Explorer 10  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(2900986)  
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
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
（严重）  
Internet Explorer 9  
(2888505)  
（严重）  
Internet Explorer 10  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
（重要）  
Internet Explorer 9  
(2888505)  
（重要）  
Internet Explorer 10  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows 8 和 Windows 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
（仅限专业版和企业版）  
(2893986)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(2868626)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(2900986)  
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
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(2900986)  
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
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows Server 2012 和 Windows Server 2012 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合严重等级**
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**中等**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2900986)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
（仅限标准版和数据中心版和 Hyper-V Server 2012）  
(2893986)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
（中等）
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2900986)  
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
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
Windows RT 和 Windows RT 8.1
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
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
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT  
(2900986)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows RT  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2888505)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2900986)  
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
(2868626)  
（重要）
</td>
</tr>
<tr>
<th colspan="7" style="border:1px solid black;">
服务器核心安装选项
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-088**](https://go.microsoft.com/fwlink/?linkid=325357)
</td>
<td style="border:1px solid black;">
[**MS13-089**](https://go.microsoft.com/fwlink/?linkid=325390)
</td>
<td style="border:1px solid black;">
[**MS13-090**](https://go.microsoft.com/fwlink/?linkid=329834)
</td>
<td style="border:1px solid black;">
[**MS13-092**](https://go.microsoft.com/fwlink/?linkid=324692)
</td>
<td style="border:1px solid black;">
[**MS13-093**](https://go.microsoft.com/fwlink/?linkid=325391)
</td>
<td style="border:1px solid black;">
[**MS13-095**](https://go.microsoft.com/fwlink/?linkid=320632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**综合** **严重等级**
</td>
<td style="border:1px solid black;">
**无**
</td>
<td style="border:1px solid black;">
[**严重**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**无**[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)[](https://go.microsoft.com/fwlink/?linkid=21140)
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
(2876331)  
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
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(2868626)  
（重要）
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
(2876331)  
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
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(2868626)  
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
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(2868626)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2876331)  
（严重）
</td>
<td style="border:1px solid black;">
不适用
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2893986)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2875783)  
（重要）
</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(2868626)  
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
(2876331)  
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
Windows Server 2012 R2（服务器核心安装）  
(2868626)  
（重要）
</td>
</tr>
</table>


#### Microsoft Office 套件和软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-091**](https://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](https://go.microsoft.com/fwlink/?linkid=324873)
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
**无**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
（文件格式转换器）  
(2760494)  
（重要）
</td>
<td style="border:1px solid black;">
不适用
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-091**](https://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](https://go.microsoft.com/fwlink/?linkid=324873)
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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
（文件格式转换器）  
(2760415)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 Service Pack 3  
(2825644)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-091**](https://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](https://go.microsoft.com/fwlink/?linkid=324873)
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
Microsoft Office 2010 Service Pack 1（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（32 位版本）  
（文件格式转换器）  
(2553284)  
（重要）  
Microsoft Office 2010 Service Pack 1（32 位版本）  
（校对工具）  
(2760781)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1（32 位版本）  
(2837597)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
（文件格式转换器）  
(2553284)  
（没有严重等级）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
（校对工具）  
(2760781)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2（32 位版本）  
(2837597)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1（64 位版本）  
（文件格式转换器）  
(2553284)  
（重要）  
Microsoft Office 2010 Service Pack 1（64 位版本）  
（校对工具）  
(2760781)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1（64 位版本）  
(2837597)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
（文件格式转换器）  
(2553284)  
（没有严重等级）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
（校对工具）  
(2760781)  
（没有严重等级）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2（64 位版本）  
(2837597)  
（重要）
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**
</td>
<td style="border:1px solid black;">
[**MS13-091**](https://go.microsoft.com/fwlink/?linkid=325392)
</td>
<td style="border:1px solid black;">
[**MS13-094**](https://go.microsoft.com/fwlink/?linkid=324873)
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
Microsoft Office 2013（32 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
（文件格式转换器）  
(2768005)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013（32 位版本）  
(2837618)  
（重要）
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）
</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
（文件格式转换器）  
(2768005)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013（64 位版本）  
(2837618)  
（重要）
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
（文件格式转换器）  
(2768005)  
（重要）
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2013 RT  
(2837618)  
（重要）
</td>
</tr>
</table>


检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

-   管理员可使用 Microsoft Baseline Security Analyzer (MBSA) 在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。
-   Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关的这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/security/cc297183)。

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

**MS13-088**

-   Simon Zuckerbraun 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3871)
-   Masato Kinugawa 报告了 Internet Explorer 信息泄露漏洞 (CVE-2013-3908)
-   Sergey Markov 报告了 Internet Explorer 信息泄露漏洞 (CVE-2013-3909)
-   [Corelan](https://www.corelangcv.com/) 的 Peter 'corelanc0d3r' Van Eeckhoutte 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3910)
-   [Harmony Security](https://www.harmonysecurity.com/) 的 Stephen Fewer 与[HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3911)
-   lokihardt@ASRT 与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3912)
-   一位匿名研究人员与 [VeriSign iDefense Labs](https://labs.idefense.com) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3914)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3915)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3916)
-   一名匿名研究人员与 [HP's](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) 合作报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3917)
-   [Palo Alto Networks](https://www.paloaltonetworks.com/) 的 Bo Qu 报告了 Internet Explorer 内存损坏漏洞 (CVE-2013-3917)

**MS13-089**

-   [Secunia Research](https://secunia.com/) 的 Hossein Lotfi 报告了图形设备接口整数溢出漏洞 (CVE-2013-3940)

**MS13-090**

-   [Cyber Defense Institute, Inc.](https://www.cyberdefense.jp/) 的 ucq 和 Daiki Fukumori 报告了 InformationCardSigninHelper 漏洞 (CVE-2013-3918)
-   [iSIGHT Partners](https://www.isightpartners.com/) 与我们一起处理了 InformationCardSigninHelper 漏洞 (CVE-2013-3918)
-   [FireEye](https://www.fireeye.com/) 的 Dan Caselden 和 Xiaobo Chen 与我们一起处理了 InformationCardSigninHelper 漏洞 (CVE-2013-3918)

**MS13-091**

-   Merliton 报告了 WPD 文件格式内存损坏漏洞 (CVE-2013-0082)
-   [CERT/CC](https://www.cert.org/) 的 Will Dormann 报告了 Word 堆栈缓冲区覆盖漏洞 (CVE-2013-1324)
-   [CERT/CC](https://www.cert.org/) 的 Will Dormann 报告了 Word 堆覆盖漏洞 (CVE-2013-1325)

**MS13-092**

-   thinktecture ([www.thinktecture.com](https://www.thinktecture.com)) & ERNW ([www.ernw.de](https://www.ernw.de); Felix Wilhelm) 代表 Bundesamt für Sicherheit in der Informationstechnik （BSI，德国联邦信息安全办公室）报告了地址损坏漏洞 (CVE-2013-3898)

**MS13-094**

-   [n.runs professionals GmbH](https://www.nruns.com/) 的 Alexander Klink 报告了 S/MIME AIA 漏洞 (CVE-2013-3905)

**MS13-095**

-   [Context Information Security](https://www.contextis.com/) 的 James Forshaw 报告了数字签名漏洞 (CVE-2013-3869)

#### 支持

-   已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。
-   面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/security/bb980617)
-   帮助保护运行 Windows 的计算机免遭病毒和恶意软件攻击： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx)

#### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

#### 修订版本

-   V1.0（2013 年 11 月 12 日）： 已发布公告摘要。

*Built at 2014-04-18T01:50:00Z-07:00*
