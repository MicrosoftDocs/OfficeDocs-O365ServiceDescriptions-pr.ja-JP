---
title: レポート機能とトラブルシューティング ツール
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Onlineは、管理センター (EAC) でのレポート機能と管理センター Exchange機能を提供します。
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652691"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="bebde-103">レポート機能とトラブルシューティング ツール</span><span class="sxs-lookup"><span data-stu-id="bebde-103">Reporting features and troubleshooting tools</span></span>

<span data-ttu-id="bebde-104">Microsoft Exchange Onlineは、管理センター (EAC) でのレポート機能と管理センター Exchange機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="bebde-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="bebde-105">レポート作成機能</span><span class="sxs-lookup"><span data-stu-id="bebde-105">Reporting features</span></span>

<span data-ttu-id="bebde-106">Exchange Onlineユーザーは、Microsoft 365レポート ブックをダウンロードするか、web サービスを使用して、Excel管理センターのレポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="bebde-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="bebde-107">管理センター Microsoft 365レポート</span><span class="sxs-lookup"><span data-stu-id="bebde-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="bebde-108">メールボックスとグループに関する概要情報をMicrosoft 365管理センターの [レポート] ページにレポートがあります。</span><span class="sxs-lookup"><span data-stu-id="bebde-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="bebde-109">たとえば、あるレポートでは、日、週、月、または年単位に作成および削除されたグループの数の一覧があります。</span><span class="sxs-lookup"><span data-stu-id="bebde-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="bebde-110">また、新しいメールボックスと削除済みのメールボックス、アクティブおよび非アクティブなメールボックスに関する概要レポートもあります。</span><span class="sxs-lookup"><span data-stu-id="bebde-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="bebde-111">さらに、Microsoft 365 管理センターの [レポート] ページには、メッセージ トラフィック、スパムおよびマルウェア検出、Exchange トランスポート ルールまたはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報を提供するメッセージング データ レポートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="bebde-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="bebde-112">保護、ルール、および DLP の強化されたレポートは、管理者向け対話型Exchange Online提供します。</span><span class="sxs-lookup"><span data-stu-id="bebde-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="bebde-113">これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="bebde-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="bebde-114">各サブスクリプションで使用できるレポートの詳細については、「Reports」を [参照してください](../office-365-platform-service-description/reports.md)。</span><span class="sxs-lookup"><span data-stu-id="bebde-114">For more information about which reports are available with each subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="bebde-115">Microsoft 365 管理センターの [レポート] ページの詳細については[、「Office 365](/microsoft-365/admin/activity-reports/activity-reports)でのサービス使用状況に関するレポートの表示とダウンロード」および「メール[](/exchange/monitoring/use-mail-protection-reports)保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](/microsoft-365/admin/activity-reports/activity-reports) and [Use mail protection reports to view data about malware, spam, and rule detections](/exchange/monitoring/use-mail-protection-reports).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="bebde-116">Excel レポート作成ワークブックを使用したレポート作成</span><span class="sxs-lookup"><span data-stu-id="bebde-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="bebde-117">Excel 2013 レポート作成ワークブックを使用して、ドリルダウン機能を備えた概要レポートを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="bebde-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="bebde-118">ただし、代わりに管理センター レポートの拡張Microsoft 365使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="bebde-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="bebde-119">Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。</span><span class="sxs-lookup"><span data-stu-id="bebde-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="bebde-120">詳細情報およびレポート作成ワークブックのダウンロードおよびインストール用のリンクについては、次の[ダウンロード ページ](https://go.microsoft.com/fwlink/p/?LinkId=271776)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="bebde-121">レポート作成ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150))」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="bebde-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="bebde-122">Reporting using web services</span></span>

<span data-ttu-id="bebde-123">メールボックス、グループ、およびメッセージング データに関する概要レポートと詳細レポートの両方にアクセスするには、カスタム レポートを作成できるプログラムによるインターフェイスである REST/OData テナント レポート Web サービスを使用します。</span><span class="sxs-lookup"><span data-stu-id="bebde-123">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting web service, which is a programmatic interface that lets you create custom reports.</span></span> <span data-ttu-id="bebde-124">詳細については、「レポート[Web サービスOffice 365を参照してください](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15))。</span><span class="sxs-lookup"><span data-stu-id="bebde-124">For more information, see [Office 365 Reporting web services](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15)).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="bebde-125">EAC のレポート作成機能とトラブルシューティング ツール</span><span class="sxs-lookup"><span data-stu-id="bebde-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="bebde-126">Exchange 管理センターでは、次のレポート作成機能とトラブルシューティング ツールを使用できます。</span><span class="sxs-lookup"><span data-stu-id="bebde-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="bebde-127">電子メール メッセージの追跡</span><span class="sxs-lookup"><span data-stu-id="bebde-127">Trace an email message</span></span>

<span data-ttu-id="bebde-128">メッセージ 追跡機能を使用すると、管理者は、ユーザーがサービスを通過する電子メール メッセージExchange Onlineできます。</span><span class="sxs-lookup"><span data-stu-id="bebde-128">The message trace feature lets you, as an administrator, follow email messages as they pass through your Exchange Online service.</span></span> <span data-ttu-id="bebde-129">これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bebde-129">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="bebde-130">したがって、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたりできるため、テクニカル サポートに支援を求める必要性が減ります。</span><span class="sxs-lookup"><span data-stu-id="bebde-130">This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="bebde-p107">一般的な問題や傾向をトラブルシューティングする場合は、レポート ツールを使用してこのようなデータを取得できます。単一点でのメッセージに関する詳細が必要な場合は、メッセージ追跡ツールを使用します。</span><span class="sxs-lookup"><span data-stu-id="bebde-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="bebde-133">メッセージ追跡機能の詳細については、「[電子メール メッセージの追跡](/exchange/monitoring/trace-an-email-message/trace-an-email-message)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-133">For more information about the message trace feature, see [Trace an Email Message](/exchange/monitoring/trace-an-email-message/trace-an-email-message).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="bebde-134">監査レポート</span><span class="sxs-lookup"><span data-stu-id="bebde-134">Auditing reports</span></span>

<span data-ttu-id="bebde-p108">監査ログを使用すると、管理者が行った特定の変更を追跡して構成上の問題をトラブルシューティングしたり、法規制、法令遵守、および訴訟の要件を満たすために利用したりすることができます。Exchange Online には次の 2 種類の監査ログがあります。</span><span class="sxs-lookup"><span data-stu-id="bebde-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="bebde-p109">管理者監査ログ は管理者によって実行されたあらゆる処理を記録します。これは、構成上の問題のトラブルシューティングを行ったり、セキュリティ関連または法令遵守に関連する問題の原因を特定したりするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bebde-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="bebde-p110">メールボックス監査ログ: メールボックスの所有者以外のユーザーがメールボックスにアクセスするたびに記録されます。これは、メールボックスにアクセスしたユーザーとそのユーザーが実行した操作を確認するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bebde-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="bebde-141">監査ログの詳細については、「[Exchange 監査レポート](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-141">For more information about audit logging, see [Auditing Reports](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="bebde-142">ユニファイド メッセージングのレポート</span><span class="sxs-lookup"><span data-stu-id="bebde-142">Unified Messaging reports</span></span>

<span data-ttu-id="bebde-p111">これらのレポートを使用すると、Exchange Online 組織内のユニファイド メッセージング (UM) の監視やトラブルシューティングを行うことができます。詳細については、「[ボイス メール通話のレポートを実行する](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="bebde-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="bebde-145">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="bebde-145">Feature availability</span></span>

<span data-ttu-id="bebde-146">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online[参照してください](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="bebde-146">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
