---
TOCTitle: 'MS04-NOV'
Title: 'Microsoft 安全公告摘要 (2004 年 11 月)'
ms:assetid: 'ms04-nov'
ms:contentKeyID: 61236830
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms04-nov(v=Security.10)'
---



Microsoft 安全公告摘要 (2004 年 11 月)
======================================

发布时间: 2004年11月9日

**版本:** 1.0

**发布时间：**2004 年 11 月 9 日
**版本号：**1.0

可通过访问以下[网站](https://www.microsoft.com/china/security/)，获取此信息的最终用户版本。

**保护您的 PC：**Microsoft 在以下位置提供了关于如何帮助保护 PC 的信息：

-   最终用户可以访问[保护您的 PC 网 站](https://www.microsoft.com/china/security/protect/)。
-   IT 专业人士可以访问[安全指南中心网站](https://www.microsoft.com/china/technet/security/guidance/default.mspx)。

**更新管理策略：**[修补程序管理、安全更新和下载](https://go.microsoft.com/fwlink/?linkid=21168)网站提供有关 Microsoft 对应用安全更新的最佳做法建议的详细信息。

**IT 专业人士安全区域社区：**了解如何提高安全性和优化 IT 基础结 构，并在 [IT 专业人士安全 区域网站](https://go.microsoft.com/fwlink/?linkid=21164)与其他 IT 专业人士一起就安全话题展开讨论。

**Microsoft 安全性通告服务：**要在 Microsoft 安全公告发布时收到 自动电子邮件通知，请订阅 [Microsoft 安全性通知服务](https://go.microsoft.com/fwlink/?linkid=21163)。

#### 摘要

本通报中包含新发现漏洞的更新。 可按严重程度将这些漏洞分为：

重要 (1)
--------

| 公告标识           | Microsoft 安全公告 MS04-039                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [ISA Server 2000 和 Proxy Server 2.0 中的安全漏洞可能给 Internet 内容欺骗以可乘之机 (888258)](https://technet.microsoft.com/security/bulletin/ms04-039) |
| **摘要：**         | 此漏洞使攻击者可以进行受信任 Internet 内容欺骗。                                                                                                       |
| **最高严重等级**   | 重要                                                                                                                                                   |
| **安全漏洞的影响** | 欺骗                                                                                                                                                   |
| **受影响的软件**   | **Windows。** 有关详细信息，请参阅“受影响的软件和 下载位置”部分。                                                                                      |

受影响的软件和下载位置
----------------------

**如何使用该表？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否有必须安 装的安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件 更新。

**受影响的软件和下载位置**

|                                                                                                                                                    | 详细信息                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| **公告标识**                                                                                                                                       | **MS04-039**                                                                                                         |
| **最高严重等级**                                                                                                                                   | [**重要**](https://go.microsoft.com/fwlink/?linkid=21140)                                                             |
| **受影响的 Windows 软件：**                                                                                                                        |                                                                                                                      |
| Microsoft Internet Security and Acceleration Server 2000 Service Pack 1 和 Microsoft Internet Security and Acceleration Server 2000 Service Pack 2 | [重要](https://www.microsoft.com/download/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7&displaylang=en) |
| Microsoft Small Business Server 2000（包括 Microsoft Internet Security and Acceleration Server 2000）                                              | [重要](https://www.microsoft.com/download/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7&displaylang=en) |
| Microsoft Small Business Server 2003 Premium Edition（包括 Microsoft Internet Security and Acceleration Server 2000）                              | [重要](https://www.microsoft.com/download/details.aspx?familyid=7a4c318f-5ac9-4cf2-8792-a4a62076ebe7&displaylang=en) |
| Microsoft Proxy Server 2.0 Service Pack 1                                                                                                          | [重要](https://www.microsoft.com/download/details.aspx?familyid=55643141-91e3-4474-8134-72887bc6fc18&displaylang=en) |

部署
----

**Systems Management Server：**

Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案 。 通过使用 SMS，管理员可以确定需要安全更新且基于 Windows 的系统，并在整个企业中以可控制的方式执行这些 更新的部署，而只对最终用户造成最低程度的干扰。 有关管理员如何使用 SMS 2003 来部署安全更新的详细信息，请 参阅 [SMS 2003 安全修补程 序管理网站](https://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service Feature Pack](https://go.microsoft.com/fwlink/?%20linkid=33340) 帮助部署安全更新。 有关 SMS 的信息，请访问 [SMS 网站](https://go.microsoft.com/fwlink/?linkid=21158)。

**注意：**SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office Detection Tool 提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更 新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请访问以 下[网站](https://go.microsoft.com/fwlink/?linkid=33341)。 某些安全 更新在重新启动系统后可能需要管理权限。 管理员可以使用 Elevated Rights Deployment Tool（在 [SMS 2003 Administration Feature Pack](https://go.microsoft.com/fwlink/?linkid=33387) 和 [SMS 2.0 Administration Feature Pack](https://go.microsoft.com/fwlink/?linkid=21161) 中提供）安装这些更新。

#### 其他信息：

**鸣谢**

Microsoft [感 谢](https://go.microsoft.com/fwlink/?linkid=21127)下列人员或组织与我们一起致力于保护客户的利益：

-   Martijn de Vries 和 Thomas de Klerk，二位均来自 Info Support，分别发现和报告该欺骗漏洞 (CAN-2004-0892)。

**获取其他安全更新：**

可从以下位置获得针对其他安全问题的更新：

-   [Microsoft 下载中心](https://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“security\_patch”，可以非常方 便地找到这些更新。
-   可从 [Windows Update 网站](https://go.microsoft.com/fwlink/?linkid=21130)获得适用于客户平台的更新。

**支持：**

-   美国和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](https://go.microsoft.com/fwlink/?linkid=21131) 获得技术支持。 与安全更新有关的电话支持服务是免费的。
-   其他国家（或地区）的用户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务 不收取任何费用。 有关如何就支持问题与 Microsoft 取得联系方面的详细信息，请访问[国际支持网站](https://go.microsoft.com/fwlink/?linkid=21155)。

**安全资源：**

-   [Microsoft TechNet 安全](https://go.microsoft.com/fwlink/?linkid=21132)网站提供了有关 Microsoft 产品安全的详细信息。
-   [Microsoft 软件更新服务](https://go.microsoft.com/fwlink/?linkid=21133)
-   [Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) (MBSA)
-   [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130)
-   Windows Update 目录：有关 Windows Update 目录的详细信息，请参阅 [Microsoft 知 识库文章 323166](https://support.microsoft.com/default.aspx?scid=kb;en-us;323166)。
-   [Office Update](https://go.microsoft.com/fwlink/?linkid=21135)

**免责声明：**

Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保 证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的 、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供 应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不 适用。

**修订：**

-   V1.0（2004 年 11 月 9 日）：公告发布

*Built at 2014-04-18T01:50:00Z-07:00*
