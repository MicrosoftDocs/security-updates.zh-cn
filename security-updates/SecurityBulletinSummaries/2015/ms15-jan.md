---
TOCTitle: 'MS15-JAN'
Title: 'Microsoft 安全公告摘要（2015 年 1 月）'
ms:assetid: 'ms15-jan'
ms:contentKeyID: 63898332
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-jan(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 1 月）
======================================

发布日期： 2015 年 1 月 13 日

**版本：** 1.0

本公告摘要列出了 2015 年 1 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。 请参阅**其他信息**部分。

执行摘要
--------

下表概述了本月的安全公告（按严重性排序）。

有关受影响软件的详细信息，请参阅下一节“**受影响的软件**”。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p><strong>公告 ID</strong></p></td>
<td style="border:1px solid black;"><p><strong>公告标题和执行摘要</strong></p></td>
<td style="border:1px solid black;"><p><strong>最高严重等级和漏洞影响</strong></p></td>
<td style="border:1px solid black;"><p><strong>重新启动要求</strong></p></td>
<td style="border:1px solid black;"><p><strong>受影响的软件</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 应用程序兼容性缓存中的漏洞可能允许特权提升 (3023266)<br />
<br />
</strong>此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。 此漏洞在攻击者登录系统并运行经特殊设计的应用程序时允许提升特权。 成功利用此漏洞后，经过身份验证的攻击者能够绕过在 Microsoft Windows 应用程序兼容性组件的缓存修改期间执行的现有的权限检查，并使用提升的特权执行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows Telnet 服务中的漏洞可能允许远程执行代码 (3020393)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。 如果攻击者向受影响的 Windows Server 发送特殊设计的数据包，此漏洞可能允许远程执行代码。 默认情况下，Telnet 不会安装在任何受影响的操作系统版本上。 仅手动安装此服务的客户可能容易受到攻击。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程执行代码</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows User Profile Service 中的漏洞可能允许特权提升 (3021674)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个公开披露的漏洞。 如果攻击者登录系统并运行经特殊设计的应用程序，则该漏洞可能允许提升特权。 成功利用此漏洞的本地攻击者能够使用提升的特权在目标系统上运行任意代码。 攻击者必须拥有有效的登录凭据，并能够本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 组件中的漏洞可能允许特权提升 (3025421)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。 如果攻击者诱使用户运行经特殊设计的应用程序，则该漏洞可能允许特权提升。 成功利用该漏洞的攻击者可以获得与当前用户相同的用户权限。 如果当前用户使用管理用户权限登录，则攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。 那些帐户被配置为拥有较少用户权限的用户比具有管理用户权限的用户受到的影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></p></td>
<td style="border:1px solid black;"><p><strong>网络位置感知服务中的漏洞可能允许安全功能规避 (3022777)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。 当与受害者位于同一网络中的攻击者欺骗由受害者发起的对 DNS 和 LDAP 流量的响应时，该漏洞可能通过无意中放松的防火墙策略和/或某些服务的配置允许安全功能规避。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 错误报告中的漏洞可能允许安全功能规避 (3004365)</strong><br />
<br />
此安全更新可解决 Windows 错误报告 (WER) 中一个私下报告的漏洞。 如果被攻击者成功利用，该漏洞可能允许安全功能规避。 成功利用此漏洞的攻击者可能会获取对运行中进程内存的访问权限。 在系统上配置为具有较少用户权限的用户帐户比具有管理员权限的用户帐户所受影响要小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></p></td>
<td style="border:1px solid black;"><p><strong>在网络策略服务器 RADIUS 实施中的漏洞可能导致拒绝服务 (3014029)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。 如果攻击者将经特殊设计的用户名字符串发送到 IAS 或 NPS，则该漏洞可能允许拒绝 Internet 验证服务 (IAS) 或网络策略服务器 (NPS) 上的服务。 请注意，虽然攻击者无法通过拒绝服务漏洞来执行代码或提升用户权限；但此漏洞可以阻止对 IAS 或 NPS 的 RADIUS 认证。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
拒绝服务</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许特权提升 (3019215)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。 如果攻击者在受影响的系统上运行经特殊设计的应用程序，此漏洞可能允许特权提升。 攻击者必须拥有有效的登录凭据，并能够本地登录才能利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
</tbody>  
</table>
  
 
  
利用指数  
--------
  
<span id="sectionToggle1"></span>  
下表提供了本月解决的各个漏洞的利用评估。 这些漏洞按公告 ID、CVE ID 的顺序列出。仅包括公告中严重等级为“严重”或“重要”的漏洞。
  
**如何使用该表？**
  
使用该表了解对于您可能需要安装的每个安全更新，安全公告发布 30 天内发生代码执行和拒绝服务利用的可能性。 根据您的特定配置，检查下面的每个评估，从而确定部署本月更新的优先次序。 有关这些等级的含义以及如何确定这些等级的详细信息，请参阅 [Microsoft 利用指数](https://technet.microsoft.com/zh-cn/security/cc998259)。
  
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
<td style="border:1px solid black;"><p><strong>最新软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></p></td>
<td style="border:1px solid black;"><p>Microsoft 应用程序兼容性基础结构的特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0002">CVE-2015-0002</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个特权提升漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></p></td>
<td style="border:1px solid black;"><p>Windows Telnet 服务缓冲区溢出漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0014">CVE-2015-0014</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个远程执行代码漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></p></td>
<td style="border:1px solid black;"><p>Microsoft User Profile Service 的特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0004">CVE-2015-0004</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个特权提升漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></p></td>
<td style="border:1px solid black;"><p>目录遍历的特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0016">CVE-2015-0016</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。<br />
<br />
在受限的针对性攻击中，此漏洞被用作沙箱绕过。</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></p></td>
<td style="border:1px solid black;"><p>NLA 安全功能规避漏洞 - CVE-2015-0006</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0006">CVE-2015-0006</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个绕过安全功能漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></p></td>
<td style="border:1px solid black;"><p>Windows 错误报告安全功能规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0001">CVE-2015-0001</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个绕过安全功能漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></p></td>
<td style="border:1px solid black;"><p>网络策略服务器 RADIUS 实施拒绝服务漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0015">CVE-2015-0015</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>此漏洞导致拒绝服务。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></p></td>
<td style="border:1px solid black;"><p>WebDAV 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0011">CVE-2015-0011</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
</tbody>  
</table>
  
 
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。 如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。 查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件

<p> </p>
<table style="border:1px solid black;">  
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3019215)  
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
Windows Server 2003 x64 Edition Service Pack 2  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）  
(3019215)  
（重要）

</td>
</tr>
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
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2（远程桌面客户端 7.0 已安装）  
(3023299)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3022777)  
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
(3019215)  
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
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2（远程桌面客户端 7.0 已安装）  
(3023299)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3022777)  
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
(3019215)  
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
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3019215)  
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
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3019215)  
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
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows 7（用于 32 位系统）Service Pack 1  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3019978)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1（远程桌面客户端 8.0 已安装）  
(3020387)  
（重要）  
Windows 7（用于 32 位系统）Service Pack 1（远程桌面客户端 8.1 已安装）  
(3020388)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3022777)  
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
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3019978)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1（远程桌面客户端 8.0 已安装）  
(3020387)  
（重要）  
Windows 7（用于基于 x64 的系统）Service Pack 1（远程桌面客户端 8.1 已安装）  
(3020388)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3022777)  
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
(3019215)  
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
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3019978)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（远程桌面客户端 8.0 已安装）  
(3020387)  
（重要）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（远程桌面客户端 8.1 已安装）  
(3020388)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3022777)  
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
<td style="border:1px solid black;" colspan="9">
**Windows 8 和 Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
Windows 8（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3022777) )  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3022777) )  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3022777) )  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3019215)  
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
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3014029)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 和 Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT  
(3019215)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004365)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019215)  
（重要）

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
[**MS15-001**](https://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](https://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](https://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](https://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](https://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](https://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](https://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](https://go.microsoft.com/fwlink/?linkid=522533)

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
[**严重**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

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
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3022777)  
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
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3022777)  
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
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3022777)  
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
Windows Server 2012（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3004365)  
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
Windows Server 2012 R2（服务器核心安装）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3023266)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3020393)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3021674)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3019978)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3022777)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3004365)  
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

**MS15-005 的注释**
<sup>[1]</sup>Windows Server 2003 会受到影响，但是未对其发布更新。 请参阅公告以了解详细信息。

 

检测和部署工具及指导
--------------------

许多资源可帮助管理员部署安全更新。

Microsoft Baseline Security Analyzer (MBSA) 支持管理员扫描本地和远程系统中缺少的安全更新和常见的安全错误配置。

Windows Server Update Services (WSUS)、Systems Management Server (SMS) 和 System Center Configuration Manager 帮助管理员分发安全更新。

Application Compatibility Toolkit 随附的更新兼容性评估程序组件针对安装的应用程序协助简化 Windows 更新的测试和验证。

有关这些和其他可用工具的信息，请参阅 [IT 专业人员安全工具](https://technet.microsoft.com/zh-cn/security/cc297183)。

鸣谢
----

Microsoft 通过可靠的漏洞披露渠道认可在安全社区中帮助我们对客户进行保护的人们所做出的努力。 有关详细信息，请参阅[鸣谢](https://technet.microsoft.com/zh-cn/library/security/dn820091.aspx)。

其他信息
--------

### Microsoft Windows 恶意软件删除工具

在每个月的第二个星期二发布的公告中，Microsoft 已在 Windows 更新、Microsoft 更新、Windows Server Update Services 和下载中心上发布了 Microsoft Windows 恶意软件删除工具的更新版本。 带外安全公告发布中未提供 Microsoft Windows 恶意软件删除工具的更新。

### MU、WU 和 WSUS 上的非安全更新

有关 Windows 更新和 Microsoft 更新上非安全发布的信息，请参阅：

-   [Microsoft 知识库文章 894199](https://support.microsoft.com/kb/894199/zh-cn)： Software Update Services 和 Windows Server Update Services 的内容更改说明。 包括所有 Windows 内容。
-   [过去几个月关于 Windows Server Update Services 的更新](https://technet.microsoft.com/zh-cn/windowsserver/bb332157.aspx)。 显示除 Microsoft Windows 之外的 Microsoft 产品的所有新的、修订的和重新发布的更新。

### Microsoft Active Protections Program (MAPP)

为改进客户的安全保护，Microsoft 在发布每月安全更新之前将向主要的安全软件供应商提供漏洞信息。 然后，安全软件供应商可以使用该漏洞信息通过其安全软件或者设备向客户提供更新的保护，例如防病毒、基于网络的入侵检测系统或者基于主机的入侵防止系统。 要确定是否可从安全软件供应商处得到活动保护，请访问计划合作伙伴（在 [Microsoft Active Protections Program (MAPP) 合作伙伴](https://technet.microsoft.com/zh-cn/security/dn467918)中列出）提供的活动保护网站。

### 安全策略和社区

**更新管理策略**

[更新管理安全指导](https://technet.microsoft.com/zh-cn/library/bb466251.aspx)提供 Microsoft 关于应用安全更新的最佳方案建议的其他信息。

**获取其他安全更新**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://www.microsoft.com/downloads/results.aspx?displaylang=zh-cn&freetext=security%20update)提供了安全更新。 通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。 有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086/zh-cn)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。 其他版本的支持生命周期已结束。 要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案： [TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害： [病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

本地支持（根据您的国家/地区）： [国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 1 月 13 日）： 已发布公告摘要。

*页面生成时间：2015-01-08 14:01Z-08:00。*
