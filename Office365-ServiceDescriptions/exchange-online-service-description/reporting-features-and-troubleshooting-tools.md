---
title: レポート機能とトラブルシューティング ツール
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft exchange Online は、exchange 管理センター (EAC) の内外で、さまざまなレポート機能を提供します。
ms.openlocfilehash: 1fb9a0fe62fb94c0ace7388613ca26f65fc4698f
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246373"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="83897-103">レポート機能とトラブルシューティング ツール</span><span class="sxs-lookup"><span data-stu-id="83897-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="83897-104">Microsoft exchange Online は、exchange 管理センター (EAC) の内外で、さまざまなレポート機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="83897-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="83897-105">レポート作成機能</span><span class="sxs-lookup"><span data-stu-id="83897-105">Reporting features</span></span>

<span data-ttu-id="83897-106">Exchange Online のお客様は、Microsoft 365 管理センターで、excel レポートブックをダウンロードするか、Web サービスを使用して、レポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="83897-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="83897-107">Microsoft 365 管理センターでのレポート</span><span class="sxs-lookup"><span data-stu-id="83897-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="83897-108">Microsoft 365 管理センターの [レポート] ページには、メールボックスとグループに関する概要情報を提供するレポートがあります。</span><span class="sxs-lookup"><span data-stu-id="83897-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="83897-109">たとえば、あるレポートでは、日、週、月、または年単位に作成および削除されたグループの数の一覧があります。</span><span class="sxs-lookup"><span data-stu-id="83897-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="83897-110">また、新しいメールボックスと削除済みのメールボックス、アクティブおよび非アクティブなメールボックスに関する概要レポートもあります。</span><span class="sxs-lookup"><span data-stu-id="83897-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="83897-111">さらに、Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、および Exchange トランスポートルールまたはデータ損失防止 (DLP) の影響を受けるメッセージに関する情報を提供するメッセージングデータレポートが含まれています。規定.</span><span class="sxs-lookup"><span data-stu-id="83897-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="83897-112">保護、ルール、および DLP の拡張されたレポートは、Exchange Online 管理者向けの対話型レポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="83897-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="83897-113">これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="83897-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="83897-114">各 Office 365 サブスクリプションで利用可能なレポートの詳細については、[レポート](../office-365-platform-service-description/reports.md)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-114">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="83897-115">Microsoft 365 管理センターの [レポート] ページの詳細については、「 [office 365 のサービス利用状況に関するレポートの表示とダウンロード](https://go.microsoft.com/fwlink/p/?LinkId=401187)」および「 [office 365 でメール保護レポートを使用する」を参照し、マルウェア、スパム、ルールの検出に関するデータを表示してください。](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="83897-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="83897-116">Excel レポート作成ワークブックを使用したレポート作成</span><span class="sxs-lookup"><span data-stu-id="83897-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="83897-117">Excel 2013 レポート作成ワークブックを使用して、ドリルダウン機能を備えた概要レポートを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="83897-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="83897-118">ただし、強化された Microsoft 365 管理センターのレポートを代わりに使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="83897-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="83897-119">Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。</span><span class="sxs-lookup"><span data-stu-id="83897-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="83897-120">詳細情報およびレポート作成ワークブックのダウンロードおよびインストール用のリンクについては、次の[ダウンロード ページ](https://go.microsoft.com/fwlink/p/?LinkId=271776)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="83897-121">レポート作成ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="83897-122">Web サービスを使用したレポート作成</span><span class="sxs-lookup"><span data-stu-id="83897-122">Reporting using Web services</span></span>

<span data-ttu-id="83897-p105">メールボックス、グループ、およびメッセージング データに関する概要レポートと詳細レポートには、REST/OData テナント レポート Web サービスを使用してアクセスできます。この Web サービスは、カスタム レポートを作成できるプログラマティック インターフェイスです。詳細については、「[Office 365 レポート Web サービス](https://go.microsoft.com/fwlink/p/?LinkId=287041)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="83897-125">EAC のレポート作成機能とトラブルシューティング ツール</span><span class="sxs-lookup"><span data-stu-id="83897-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="83897-126">Exchange 管理センターでは、次のレポート作成機能とトラブルシューティング ツールを使用できます。</span><span class="sxs-lookup"><span data-stu-id="83897-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="83897-127">電子メール メッセージの追跡</span><span class="sxs-lookup"><span data-stu-id="83897-127">Trace an email message</span></span>

<span data-ttu-id="83897-p106">メッセージ追跡機能を使用すると、管理者は Exchange Online サービスを経由する電子メール メッセージを追跡できます。これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。したがって、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたりできるため、テクニカル サポートに支援を求める必要性が減ります。</span><span class="sxs-lookup"><span data-stu-id="83897-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="83897-p107">一般的な問題や傾向をトラブルシューティングする場合は、レポート ツールを使用してこのようなデータを取得できます。単一点でのメッセージに関する詳細が必要な場合は、メッセージ追跡ツールを使用します。</span><span class="sxs-lookup"><span data-stu-id="83897-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="83897-133">メッセージ追跡機能の詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkId=271777)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="83897-134">監査レポート</span><span class="sxs-lookup"><span data-stu-id="83897-134">Auditing reports</span></span>

<span data-ttu-id="83897-p108">監査ログを使用すると、管理者が行った特定の変更を追跡して構成上の問題をトラブルシューティングしたり、法規制、法令遵守、および訴訟の要件を満たすために利用したりすることができます。Exchange Online には次の 2 種類の監査ログがあります。</span><span class="sxs-lookup"><span data-stu-id="83897-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="83897-p109">管理者監査ログ は管理者によって実行されたあらゆる処理を記録します。これは、構成上の問題のトラブルシューティングを行ったり、セキュリティ関連または法令遵守に関連する問題の原因を特定したりするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="83897-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="83897-p110">メールボックス監査ログ: メールボックスの所有者以外のユーザーがメールボックスにアクセスするたびに記録されます。これは、メールボックスにアクセスしたユーザーとそのユーザーが実行した操作を確認するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="83897-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="83897-141">監査ログの詳細については、「[Exchange 監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=271779)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="83897-142">ユニファイド メッセージングのレポート</span><span class="sxs-lookup"><span data-stu-id="83897-142">Unified Messaging reports</span></span>

<span data-ttu-id="83897-p111">これらのレポートを使用すると、Exchange Online 組織内のユニファイド メッセージング (UM) の監視やトラブルシューティングを行うことができます。詳細については、「[ボイス メール通話のレポートを実行する](https://go.microsoft.com/fwlink/p/?LinkId=287042)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="83897-145">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="83897-145">Feature Availability</span></span>

<span data-ttu-id="83897-146">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="83897-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

