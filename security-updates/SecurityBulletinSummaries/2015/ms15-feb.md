---
TOCTitle: 'MS15-FEB'
Title: 'Microsoft 安全公告摘要（2015 年 2 月）'
ms:assetid: 'ms15-feb'
ms:contentKeyID: 64119038
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms15-feb(v=Security.10)'
---



Microsoft 安全公告摘要（2015 年 2 月）
======================================

发布日期：2015 年 2 月 10 日

**版本：** 1.0

本公告摘要列出了 2015 年 2 月发布的安全公告。

有关在 Microsoft 安全公告发布时如何收到自动通知的信息，请访问 [Microsoft 技术安全通知](https://technet.microsoft.com/zh-cn/security/dd252948.aspx)。

Microsoft 还会提供相关信息，帮助客户对每月安全更新和与每月安全更新同日发布的任何非安全更新进行优先排序。请参阅**其他信息**部分。

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
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p><strong>Internet Explorer 的安全更新 (3034682)<br />
</strong><br />
此安全更新可解决 Internet Explorer 中一个公开披露的漏洞和四十个秘密报告的漏洞。最严重的漏洞可能在用户使用 Internet Explorer 查看经特殊设计的网页时允许远程执行代码。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows，<br />
Internet Explorer</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p><strong>Windows 内核模式驱动程序中的漏洞可能允许远程执行代码 (3036220)</strong><br />
<br />
此安全更新解决 Microsoft Windows 中一个公开披露的漏洞和五个秘密报告的漏洞。如果攻击者诱使用户打开特制文档或访问包含嵌入 TrueType 字体的不受信任的网站，则其中最为严重的漏洞可能允许远程执行代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525536">MS15-011</a></p></td>
<td style="border:1px solid black;"><p><strong>组策略中的漏洞可能允许远程执行代码 (3000483)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。如果攻击者诱使用户将配置域的系统连接到受攻击者控制的网络，此漏洞可能允许远程执行代码。成功利用此漏洞的攻击者可以完全控制受影响的系统。攻击者可随后安装程序；查看、更改或删除数据；或者创建拥有完全用户权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">严重</a><br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许远程执行代码 (3032328)<br />
</strong><br />
此安全更新可修复 Microsoft Office 中的三个秘密报告的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么这些漏洞可能会允许远程代码执行。成功利用这些漏洞的攻击者可以获得与当前用户相同的用户权限。与拥有管理用户权限的客户相比，帐户被配置为拥有较少系统用户权限的客户受到的影响更小。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
远程代码执行</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525533">MS15-013</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Office 中的漏洞可能允许安全功能规避 (3033857)<br />
</strong><br />
此安全更新可修复 Microsoft Office 中的一个公开披露的漏洞。如果用户打开经特殊设计的 Microsoft Office 文件，那么此漏洞可能会允许安全功能规避。该安全功能规避本身不允许执行任意代码。但是，攻击者可以将此安全功能规避漏洞与另一个漏洞（如远程代码执行漏洞）组合使用，从而运行任意代码。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Office</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522532">MS15-014</a></p></td>
<td style="border:1px solid black;"><p><strong>组策略中的漏洞可能允许安全功能规避 (3004361)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。如果攻击者通过中间人攻击的方式导致目标系统上的组策略安全配置引擎策略文件已损坏或不可读，该漏洞可能允许安全功能规避。这将导致系统上的组策略设置恢复到他们默认的可能较不安全的状态。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a> <br />
安全功能规避</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525538">MS15-015</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Windows 云中的漏洞可能允许特权提升 (3031432)</strong><br />
<br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。漏洞可能允许攻击者利用模拟级别安全检查的缺失，在进程创建过程中提升特权。成功利用此漏洞的经过身份验证的攻击者可能会获取管理员凭据，并可能使用它们来提升特权。攻击者随后可安装程序；查看、更改或删除数据；或者创建拥有完全管理权限的新帐户。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525539">MS15-016</a></p></td>
<td style="border:1px solid black;"><p><strong>Microsoft Graphics 组件中的漏洞可能允许信息泄露 (3029944)<br />
</strong><br />
此安全更新可解决 Microsoft Windows 中一个私下报告的漏洞。如果用户浏览包含经特殊设计的 TIFF 图像的网站，该漏洞可能允许信息泄露。虽然攻击者无法利用此漏洞来执行代码或直接提升他们的用户权限，但此漏洞可用于获取信息，这些信息可用于试图进一步危及受影响系统的安全。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
信息泄露</p></td>
<td style="border:1px solid black;"><p>可能要求重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Windows</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525540">MS15-017</a></p></td>
<td style="border:1px solid black;"><p><strong>Virtual Machine Manager 中的漏洞可能允许特权提升 (3035898)</strong><br />
<br />
此安全更新可解决 Virtual Machine Manager (VMM) 中一个秘密报告的漏洞。如果攻击者登录受影响的系统，该漏洞可能允许特权提升。攻击者必须拥有有效的 Active Directory 登录凭据，并能够使用那些凭据登录以利用此漏洞。</p></td>
<td style="border:1px solid black;"><p><a href="https://technet.microsoft.com/zh-cn/security/gg309177.aspx">重要</a><br />
特权提升</p></td>
<td style="border:1px solid black;"><p>需要重新启动</p></td>
<td style="border:1px solid black;"><p>Microsoft Server 软件</p></td>
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
<td style="border:1px solid black;"><p><strong>最新软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>较旧软件版本的利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>拒绝服务利用评估</strong></p></td>
<td style="border:1px solid black;"><p><strong>重要注意事项</strong></p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8967">CVE-2014-8967</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0017">CVE-2015-0017</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0018">CVE-2015-0018</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0019">CVE-2015-0019</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0020">CVE-2015-0020</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0021">CVE-2015-0021</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0022">CVE-2015-0022</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0023">CVE-2015-0023</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0025">CVE-2015-0025</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0026">CVE-2015-0026</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0027">CVE-2015-0027</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0028">CVE-2015-0028</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0029">CVE-2015-0029</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0030">CVE-2015-0030</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0031">CVE-2015-0031</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0035">CVE-2015-0035</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0036">CVE-2015-0036</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0037">CVE-2015-0037</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0038">CVE-2015-0038</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0039">CVE-2015-0039</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0040">CVE-2015-0040</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0041">CVE-2015-0041</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0042">CVE-2015-0042</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0043">CVE-2015-0043</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0044">CVE-2015-0044</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0045">CVE-2015-0045</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0046">CVE-2015-0046</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0048">CVE-2015-0048</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0049">CVE-2015-0049</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0050">CVE-2015-0050</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0051">CVE-2015-0051</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能规避漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0052">CVE-2015-0052</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0053">CVE-2015-0053</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0054">CVE-2015-0054</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0055">CVE-2015-0055</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0066">CVE-2015-0066</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0067">CVE-2015-0067</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 内存损坏漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0068">CVE-2015-0068</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0069">CVE-2015-0069</a></p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>3 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能规避漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer 跨域信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0070">CVE-2015-0070</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></p></td>
<td style="border:1px solid black;"><p>Internet Explorer ASLR 规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0071">CVE-2015-0071</a></p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>0 - 检测利用情形</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>Microsoft 获悉尝试使用此漏洞的有限攻击。<br />
<br />
这是一个安全功能规避漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0003">CVE-2015-0003</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p>CNG 安全功能规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0010">CVE-2015-0010</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个安全功能规避漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p>Win32k 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0057">CVE-2015-0057</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p>Windows 光标对象双重释放漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0058">CVE-2015-0058</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></p></td>
<td style="border:1px solid black;"><p>TrueType 字体分析远程执行代码漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0059">CVE-2015-0059</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>永久</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525536">MS15-011</a></p></td>
<td style="border:1px solid black;"><p>组策略远程代码执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0008">CVE-2015-0008</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></p></td>
<td style="border:1px solid black;"><p>Excel 远程代码执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0063">CVE-2015-0063</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></p></td>
<td style="border:1px solid black;"><p>Office 远程代码执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0064">CVE-2015-0064</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></p></td>
<td style="border:1px solid black;"><p>OneTableDocumentStream 远程代码执行漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0065">CVE-2015-0065</a></p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>（无）</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525533">MS15-013</a></p></td>
<td style="border:1px solid black;"><p>Microsoft Office 组件释放后使用漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6362">CVE-2014-6362</a></p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>1 - 可能被利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>此漏洞已公开披露。<br />
<br />
这是一个安全功能规避漏洞。</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=522532">MS15-014</a></p></td>
<td style="border:1px solid black;"><p>组策略安全功能规避漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0009">CVE-2015-0009</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个安全功能规避漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525538">MS15-015</a></p></td>
<td style="border:1px solid black;"><p>Windows 创建进程特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0062">CVE-2015-0062</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525539">MS15-016</a></p></td>
<td style="border:1px solid black;"><p>TIFF 处理信息泄露漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0061">CVE-2015-0061</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个信息泄露漏洞。</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p><a href="https://go.microsoft.com/fwlink/?linkid=525540">MS15-017</a></p></td>
<td style="border:1px solid black;"><p>Virtual Machine Manager 特权提升漏洞</p></td>
<td style="border:1px solid black;"><p><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0012">CVE-2015-0012</a></p></td>
<td style="border:1px solid black;"><p>2 - 不太可能利用</p></td>
<td style="border:1px solid black;"><p>不受影响</p></td>
<td style="border:1px solid black;"><p>不适用</p></td>
<td style="border:1px solid black;"><p>这是一个特权提升漏洞。</p></td>
</tr>  
</tbody>  
</table>
  
 
  
受影响的软件  
------------
  
<span id="sectionToggle2"></span>  
下表按主要软件类别和严重性的排序列出了公告。
  
通过这些表可了解可能需要安装的安全更新。您应该查看列出的每个软件程序或组件，了解是否需要安装任何安全更新。如果列出了软件程序或组件，则也会列出软件更新的严重等级。
  
**注意** 您可能必须为单个漏洞安装几个安全更新。查看列出的每个公告标识符的整列，核实必须安装的更新（基于系统上已安装的程序或组件）。
  
### Windows 操作系统和组件

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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
（中等）  
Internet Explorer 7  
(3021952)  
（中等）  
Internet Explorer 8  
(3021952)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013455)  
（重要）  
Windows Server 2003 Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
（中等）  
Internet Explorer 7  
(3021952)  
（中等）  
Internet Explorer 8  
(3021952)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013455)  
（重要）  
Windows Server 2003 x64 Edition Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
（中等）  
Internet Explorer 7  
(3021952)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3013455)  
（重要）  
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2（用于基于 Itanium 的系统）<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2003 SP2（用于基于 Itanium 的系统）  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
（严重）  
Internet Explorer 8  
(3021952)  
（严重）  
Internet Explorer 9  
(3021952)  
（严重）  
Internet Explorer 9  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013455)  
（重要）  
Windows Vista Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
（严重）  
Internet Explorer 8  
(3021952)  
（严重）  
Internet Explorer 9  
(3021952)  
（严重）  
Internet Explorer 9  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013455)  
（重要）  
Windows Vista x64 Edition Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
[**重要**](https://technet.microsoft.com/zh-cn/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
（中等）  
Internet Explorer 8  
(3021952)  
（中等）  
Internet Explorer 9  
(3021952)  
（中等）  
Internet Explorer 9  
(3034196)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3013455)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
（中等）  
Internet Explorer 8  
(3021952)  
（中等）  
Internet Explorer 9  
(3021952)  
（中等）  
Internet Explorer 9  
(3034196)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3013455)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3013455)  
（重要）  
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 Itanium 的系统）Service Pack 2  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
(3021952)  
（严重）  
Internet Explorer 9  
(3021952)  
（严重）  
Internet Explorer 9  
(3034196)  
（重要）  
Internet Explorer 10  
(3021952)  
（严重）  
Internet Explorer 10  
(3034196)  
（重要）  
Internet Explorer 11  
(3021952)  
（严重）  
Internet Explorer 11  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3013455)  
（严重）  
Windows 7（用于 32 位系统）Service Pack 1  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于 32 位系统）Service Pack 1  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
（严重）  
Internet Explorer 9  
(3021952)  
（严重）  
Internet Explorer 9  
(3034196)  
（重要）  
Internet Explorer 10  
(3021952)  
（严重）  
Internet Explorer 10  
(3034196)  
（重要）  
Internet Explorer 11  
(3021952)  
（严重）  
Internet Explorer 11  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3013455)  
（严重）  
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 7（用于基于 x64 的系统）Service Pack 1  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
（中等）  
Internet Explorer 9  
(3021952)  
（中等）  
Internet Explorer 9  
(3034196)  
（低）  
Internet Explorer 10  
(3021952)  
（中等）  
Internet Explorer 10  
(3034196)  
（低）  
Internet Explorer 11  
(3021952)  
（中等）  
Internet Explorer 11  
(3034196)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3013455)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
（中等）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3013455)  
（严重）  
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 Itanium 的系统）Service Pack 1  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
(3021952)  
（严重）  
Internet Explorer 10  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3013455)  
（严重）  
Windows 8（用于 32 位系统）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于 32 位系统）  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3021952)  
（严重）  
Internet Explorer 10  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3013455)  
（严重）  
Windows 8（用于基于 x64 的系统）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8（用于基于 x64 的系统）  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
（严重）  
Internet Explorer 11  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3013455)  
（严重）  
Windows 8.1（用于 32 位系统）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于 32 位系统）  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
（严重）  
Internet Explorer 11  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3013455)  
（严重）  
Windows 8.1（用于基于 x64 的系统）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows 8.1（用于基于 x64 的系统）  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3021952)  
（中等）  
Internet Explorer 10  
(3034196)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013455)  
（严重）  
Windows Server 2012  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
（中等）  
Internet Explorer 11  
(3034196)  
（低）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013455)  
（严重）  
Windows Server 2012 R2  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
(3021952)  
（严重）  
Internet Explorer 10  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3013455)  
（严重）  
Windows RT  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT  
(3029944)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
（严重）  
Internet Explorer 11  
(3034196)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013455)  
（严重）  
Windows RT 8.1  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3029944)  
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
[**MS15-009**](https://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](https://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](https://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](https://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](https://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](https://go.microsoft.com/fwlink/?linkid=525539)

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
(3013455)  
（重要）  
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于 32 位系统）Service Pack 2（服务器核心安装）  
(3029944)  
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
(3013455)  
（重要）  
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
<td style="border:1px solid black;">
Windows Server 2008（用于基于 x64 的系统）Service Pack 2（服务器核心安装）  
(3029944)  
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
(3013455)  
（严重）  
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2（用于基于 x64 的系统）Service Pack 1（服务器核心安装）  
(3029944)  
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
(3013455)  
（严重）  
Windows Server 2012（服务器核心安装）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012（服务器核心安装）  
(3029944)  
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
(3013455)  
（严重）  
Windows Server 2012 R2（服务器核心安装）  
(3023562)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3000483)  
（严重）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3004361)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3031432)  
（重要）

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2（服务器核心安装）  
(3029944)  
（重要）

</td>
</tr>
</table>

**MS15-009 和 MS15-010 注释**

Windows Technical Preview 和 Windows Server Technical Preview 均受到影响。建议运行这些操作系统的客户通过 [Windows 更新](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn)应用此更新。

**MS15-011 注释**

<sup>[1]</sup>Windows Server 2003 会受到影响，但是未对其发布更新。请参阅公告以了解详细信息。

 

### Microsoft Server 软件

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft System Center Virtual Machine Manager 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-017**](https://go.microsoft.com/fwlink/?linkid=525540)

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
Microsoft System Center Virtual Machine Manager 2012 R2 更新汇总 4

</td>
<td style="border:1px solid black;">
Microsoft System Center Virtual Machine Manager 2012 R2 更新汇总 4  
（VMM 服务器更新 2992024）<sup>[1]</sup>  
（重要）

</td>
</tr>
</table>

**MS15-017 注释**

<sup>[1]</sup>运行此软件的客户应下载并安装 Microsoft System Center 2012 R2 - Virtual Machine Manager 2012 R2 UR5 安全更新 (KB3023195)，以解决 MS15-017 中所述的漏洞。请参阅公告以了解详细信息。

 

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
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](https://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2920788)  
（重要）  
Microsoft Word 2007 Service Pack 3  
(2956099)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2920795)  
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
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](https://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2010 Service Pack 2（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）（校对工具）  
(2956073)  
（重要）  
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2956058)  
（重要）  
Microsoft Excel 2010 Service Pack 2（32 位版本）  
(2956081)  
（重要）  
Microsoft Word 2010 Service Pack 2（32 位版本）  
(2956066)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（32 位版本）  
(2920748)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）（校对工具）  
(2956073)  
（重要）  
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2956058)  
（重要）  
Microsoft Excel 2010 Service Pack 2（64 位版本）  
(2956081)  
（重要）  
Microsoft Word 2010 Service Pack 2（64 位版本）  
(2956066)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2（64 位版本）  
(2920748)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 和 Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**公告标识符**

</td>
<td style="border:1px solid black;">
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](https://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2013（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（32 位版本）  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（32 位版本）  
(2910941)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（32 位版本）  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（32 位版本）  
(2910941)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013（64 位版本）  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013（64 位版本）  
(2910941)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1（64 位版本）  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1（64 位版本）  
(2910941)  
（重要）

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2920753)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

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
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](https://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956092)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2920791)<sup>[1]</sup>  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 兼容包 Service Pack 3  
(2956097)  
（重要）  
Microsoft Office 兼容包 Service Pack 3  
(2956098)  
（重要）

</td>
<td style="border:1px solid black;">
不适用

</td>
</tr>
</table>

**MS15-012 注释**

此公告涉及多个软件类别。请参阅本节中的其他表，了解其他受影响的软件。

<sup>[1]</sup>更新 2920791 还解决了 [MS14-083](https://technet.microsoft.com/zh-cn/library/security/ms14-083) 中讨论的漏洞，它会同时重新发布。

 

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
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

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
(2920810)  
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
[**MS15-012**](https://go.microsoft.com/fwlink/?linkid=525537)

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
Microsoft Web Applications 2010 Service Pack 2  
(2956070)  
（重要）

</td>
</tr>
</table>

**MS15-012 注释**

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

-   [Microsoft 下载中心](https://www.microsoft.com/downloads/results.aspx?displaylang=zh-cn&freetext=security%20update)提供了安全更新。通过输入关键字“安全更新”可以非常方便地找到些更新。
-   [Microsoft Update](https://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=zh-cn) 提供了消费者平台的更新。
-   您可以从下载中心的“安全和关键发布 ISO CD 映像文件”获得本月 Windows 更新上提供的安全更新。有关详细信息，请参阅 [Microsoft 知识库文章 913086](https://support.microsoft.com/kb/913086/zh-cn)。

**IT 专业人员安全社区**

了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人员安全社区](https://technet.microsoft.com/zh-cn/security/cc136632.aspx)中就安全主题与其他 IT 专业人员展开讨论。

### 支持

已对列出的受影响的软件进行测试，以确定受到影响的版本。其他版本的支持生命周期已结束。要确定软件版本的技术支持生命周期，请访问 [Microsoft 技术支持生命周期](https://go.microsoft.com/fwlink/?linkid=21742)。

面向 IT 专业人员的安全解决方案：[TechNet 安全故障排除和支持](https://technet.microsoft.com/zh-cn/security/bb980617)

帮助保护您运行 Windows 的计算机不受病毒和恶意软件危害：[病毒解决方案和安全中心](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=zh-cn)

本地支持（根据您的国家/地区）：[国际支持](https://support.microsoft.com/common/international.aspx?ln=zh-cn)

### 免责声明

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。

### 修订版本

-   V1.0（2015 年 2 月 10 日）：已发布公告摘要。

*页面生成时间：2015-02-06 12:47Z-08:00。*
