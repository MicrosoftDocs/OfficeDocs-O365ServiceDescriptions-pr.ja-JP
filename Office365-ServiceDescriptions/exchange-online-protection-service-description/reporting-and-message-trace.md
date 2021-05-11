---
title: Exchange Online Protection でのレポート作成とメッセージ追跡
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: この記事では、EOP (EOP) のレポートとメッセージMicrosoft Exchange Onlineを参照してください。
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653129"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a><span data-ttu-id="83d84-103">Exchange Online Protection でのレポート作成とメッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="83d84-103">Reporting and message trace in Exchange Online Protection</span></span>

<span data-ttu-id="83d84-104">Microsoft Exchange Online保護 (EOP) は、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="83d84-104">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="83d84-105">一部のレポートは、Microsoft 365管理センターで使用できる一方で、他のレポートは、Exchangeセンター (EAC) で利用できます。</span><span class="sxs-lookup"><span data-stu-id="83d84-105">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="83d84-106">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="83d84-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="83d84-107">サービスのExchange Online Protection[を参照してください](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="83d84-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="83d84-108">Microsoft 365管理センター レポート</span><span class="sxs-lookup"><span data-stu-id="83d84-108">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="83d84-109">Microsoft 365 管理センターの [レポート] ページには、メッセージ トラフィック、スパムとマルウェアの検出、メール フロー ルール (トランスポート ルールとも呼ばれる) またはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="83d84-109">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="83d84-110">保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。</span><span class="sxs-lookup"><span data-stu-id="83d84-110">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="83d84-111">これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="83d84-111">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="83d84-112">これらのレポートの詳細については、「メール保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する」 [を参照してください](/exchange/monitoring/use-mail-protection-reports)。</span><span class="sxs-lookup"><span data-stu-id="83d84-112">For more detailed information about these reports, see [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="83d84-113">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="83d84-113">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="83d84-114">REST ベースのレポート機能と関連するコマンドレットの多くは、2018 年 1 月に廃止されました。</span><span class="sxs-lookup"><span data-stu-id="83d84-114">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="83d84-115">使用できる代替の Microsoft Graph レポートOffice 365については、「Microsoft Graph での使用状況レポートの操作」[のサブトピックを参照してください](/graph/api/resources/report)。</span><span class="sxs-lookup"><span data-stu-id="83d84-115">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with usage reports in Microsoft Graph](/graph/api/resources/report).</span></span>

<span data-ttu-id="83d84-116">EOP スタンドアロンのお客様は利用できません。</span><span class="sxs-lookup"><span data-stu-id="83d84-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="83d84-117">REST/OData テナント レポート Web サービスを使用して、メッセージング データに関する概要と詳細なレポートをプログラムで収集し、カスタム Web 管理ポータルの Web ページにデータを表示できます。</span><span class="sxs-lookup"><span data-stu-id="83d84-117">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="83d84-118">メッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="83d84-118">Message trace</span></span>

<span data-ttu-id="83d84-119">EAC のメッセージ トレース機能を使用すると、管理者として EOP を通過する電子メール メッセージをフォローできます。</span><span class="sxs-lookup"><span data-stu-id="83d84-119">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="83d84-120">これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="83d84-120">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="83d84-121">メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。</span><span class="sxs-lookup"><span data-stu-id="83d84-121">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="83d84-122">特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。</span><span class="sxs-lookup"><span data-stu-id="83d84-122">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="83d84-123">詳細については、「メッセージ トレース[を実行し、](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)管理センターで結果を表示する」をExchangeしてください。</span><span class="sxs-lookup"><span data-stu-id="83d84-123">For more information, see [Run a message trace and view the results in the Exchange admin center](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="83d84-124">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="83d84-124">Feature availability</span></span>

<span data-ttu-id="83d84-125">プラン、スタンドアロン オプション、およびオンプレミス ソリューション全体で機能の可用性を表示するには、「サービスの説明Exchange Online Protection[参照してください](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="83d84-125">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>