---
title: Exchange Online Protection でのレポート作成とメッセージ追跡
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: この記事では、Microsoft Exchange Online Protection (EOP) のレポート作成とメッセージ追跡について説明します。
ms.openlocfilehash: 6690c246620d4324610213b4968367cff0d30cf9
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293663"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a><span data-ttu-id="24449-103">Exchange Online Protection でのレポート作成とメッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="24449-103">Reporting and message trace in Exchange Online Protection</span></span>

<span data-ttu-id="24449-104">Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。</span><span class="sxs-lookup"><span data-stu-id="24449-104">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="24449-105">一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。</span><span class="sxs-lookup"><span data-stu-id="24449-105">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>

<span data-ttu-id="24449-106">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="24449-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="24449-107">「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="24449-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>

## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="24449-108">Microsoft 365 管理センターのレポート</span><span class="sxs-lookup"><span data-stu-id="24449-108">Microsoft 365 admin center reports</span></span>

<span data-ttu-id="24449-109">Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、およびメールフロールール (トランスポートルールとも呼ばれます) またはデータ損失防止 (DLP) ポリシーによって影響を受けるメッセージに関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="24449-109">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by mail flow rules (also known as transport rules) or data loss prevention (DLP) policies.</span></span> <span data-ttu-id="24449-110">保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。</span><span class="sxs-lookup"><span data-stu-id="24449-110">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="24449-111">これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="24449-111">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>

<span data-ttu-id="24449-112">これらのレポートの詳細については、「 [メール保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="24449-112">For more detailed information about these reports, see [Use mail protection reports to view data about malware, spam, and rule detections](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).</span></span>

## <a name="reporting-using-web-services"></a><span data-ttu-id="24449-113">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="24449-113">Reporting using web services</span></span>

> [!NOTE]
> <span data-ttu-id="24449-114">REST ベースのレポート機能および関連するコマンドレットの多くは、2018年1月に廃止されました。</span><span class="sxs-lookup"><span data-stu-id="24449-114">Many of the REST-based reporting features and related cmdlets were deprecated in January, 2018.</span></span> <span data-ttu-id="24449-115">Office 365 で利用可能な代替の Microsoft Graph レポートの詳細については、「 [Microsoft graph で利用状況レポートを](https://go.microsoft.com/fwlink/p/?LinkID=865135)使用する」のトピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="24449-115">For information about the available replacement Microsoft Graph reports in Office 365, see the subtopics of [Working with usage reports in Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).</span></span>

<span data-ttu-id="24449-116">EOP スタンドアロンのお客様は利用できません。</span><span class="sxs-lookup"><span data-stu-id="24449-116">Not available to EOP standalone customers.</span></span> <span data-ttu-id="24449-117">REST/OData テナントレポート web サービスを使用すると、プログラムによってメッセージングデータに関する概要と詳細レポートを収集できます。また、カスタム web 管理ポータルの web ページにデータを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="24449-117">You can use the REST/OData Tenant Reporting web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom web management portal.</span></span>

## <a name="message-trace"></a><span data-ttu-id="24449-118">メッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="24449-118">Message trace</span></span>

<span data-ttu-id="24449-119">EAC のメッセージ追跡機能を使用すると、管理者は EOP を通過する電子メールメッセージを追跡できます。</span><span class="sxs-lookup"><span data-stu-id="24449-119">The message trace feature in the EAC lets you, as an administrator, follow email messages as they pass through the EOP.</span></span> <span data-ttu-id="24449-120">これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="24449-120">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="24449-121">メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。</span><span class="sxs-lookup"><span data-stu-id="24449-121">It also shows what actions have occurred to the message before reaching its final status.</span></span> <span data-ttu-id="24449-122">特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。</span><span class="sxs-lookup"><span data-stu-id="24449-122">Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance.</span></span> <span data-ttu-id="24449-123">詳細については、「 [メッセージ追跡を実行し、Exchange 管理センターで結果を表示](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="24449-123">For more information, see [Run a message trace and view the results in the Exchange admin center](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).</span></span>

## <a name="feature-availability"></a><span data-ttu-id="24449-124">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="24449-124">Feature availability</span></span>

<span data-ttu-id="24449-125">プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="24449-125">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
