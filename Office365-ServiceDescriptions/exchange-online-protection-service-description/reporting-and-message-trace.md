---
title: レポート作成とメッセージ追跡
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。 一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。
ms.openlocfilehash: 9ad043776baf9c9a2e5ea8ca7cead0811ca66d3a
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466824"
---
# <a name="reporting-and-message-trace"></a><span data-ttu-id="47ce4-104">レポート作成とメッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="47ce4-104">Reporting and Message Trace</span></span>

<span data-ttu-id="47ce4-105">Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。</span><span class="sxs-lookup"><span data-stu-id="47ce4-105">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="47ce4-106">一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。</span><span class="sxs-lookup"><span data-stu-id="47ce4-106">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="47ce4-107">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="47ce4-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="47ce4-108">「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="47ce4-109">Microsoft 365 管理センターのレポート</span><span class="sxs-lookup"><span data-stu-id="47ce4-109">Microsoft 365 admin center reports</span></span>
<span data-ttu-id="47ce4-110"><a name="BKMK_office365admincenterreports"> </a></span><span class="sxs-lookup"><span data-stu-id="47ce4-110"></span></span>

<span data-ttu-id="47ce4-111">Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、および Exchange トランスポートルールまたはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="47ce4-111">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="47ce4-112">保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。</span><span class="sxs-lookup"><span data-stu-id="47ce4-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="47ce4-113">これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="47ce4-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="47ce4-114">これらのレポートについての詳細は、「[Office 365 のメール保護レポートによるマルウェア、スパム、ルールの検出に関するデータ表示](https://go.microsoft.com/fwlink/p/?LinkID=401102)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-114">For more detailed information about these reports, see [Use mail protection reports in Office 365 to view data about malware, spam and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
## <a name="excel-download-application-reports"></a><span data-ttu-id="47ce4-115">Excel download application reports</span><span class="sxs-lookup"><span data-stu-id="47ce4-115">Excel download application reports</span></span>
<span data-ttu-id="47ce4-116"><a name="BKMK_exceldownloadapplicationreports"> </a></span><span class="sxs-lookup"><span data-stu-id="47ce4-116"></span></span>

<span data-ttu-id="47ce4-117">Excel 2013 レポート ブックでは、メール保護のレポートが用意されており、ドリルダウン機能付きの概要レポートが提供されます。</span><span class="sxs-lookup"><span data-stu-id="47ce4-117">Email protection reports are also available in the Excel 2013 reporting workbook, which provides summary reports with drill-down capabilities.</span></span> <span data-ttu-id="47ce4-118">ただし、強化された Microsoft 365 管理センターのレポートを代わりに使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="47ce4-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="47ce4-119">Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。</span><span class="sxs-lookup"><span data-stu-id="47ce4-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> 
  
<span data-ttu-id="47ce4-p106">このワークブックの概要と、ブックのダウンロードおよびインストール (リンク) については、「[Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776)」を参照してください。ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-p106">For more overview information and links to download and install the workbook, see [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span>
  
## <a name="reporting-using-web-services"></a><span data-ttu-id="47ce4-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="47ce4-122">Reporting using web services</span></span>
<span data-ttu-id="47ce4-123"><a name="BKMK_reportingusingwebservices"> </a></span><span class="sxs-lookup"><span data-stu-id="47ce4-123"></span></span>

<span data-ttu-id="47ce4-p107">EOP スタンドアロンのお客様は利用できません。REST/OData テナント レポート Web サービスでは、プログラムを使ってメッセージング データに関する概要レポートや詳細レポートを収集し、そのデータをカスタム管理 Web ポータルの Web ページに表示できます。詳細については、「[Office 365 レポート Web サービス](https://go.microsoft.com/fwlink/?LinkId=279926)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-p107">Not available to EOP standalone customers. You can use the REST/OData Tenant Reporting Web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom management Web portal. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/?LinkId=279926).</span></span>
  
## <a name="message-trace"></a><span data-ttu-id="47ce4-127">メッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="47ce4-127">Message trace</span></span>
<span data-ttu-id="47ce4-128"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="47ce4-128"></span></span>

<span data-ttu-id="47ce4-p108">管理者は EAC のメッセージ追跡機能を使用して、EOP を経由する電子メール メッセージを追跡できます。これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkID=282262)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-p108">The message trace feature in the EAC enables you as an administrator to follow email messages as they pass through the EOP. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. It also shows what actions have occurred to the message before reaching its final status. Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance. For more information, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkID=282262).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="47ce4-134">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="47ce4-134">Feature Availability</span></span>
<span data-ttu-id="47ce4-135"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="47ce4-135"></span></span>

<span data-ttu-id="47ce4-136">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="47ce4-136">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

