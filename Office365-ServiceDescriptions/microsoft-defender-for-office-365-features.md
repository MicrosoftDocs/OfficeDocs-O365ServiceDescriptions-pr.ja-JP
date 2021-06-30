---
title: Microsoft Defender for Office 365 機能 サービスの説明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Microsoft Defender で使用できる機能について説明Office 365。
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204867"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a><span data-ttu-id="a58eb-103">Microsoft Defender for Office 365 機能 サービスの説明</span><span class="sxs-lookup"><span data-stu-id="a58eb-103">Microsoft Defender for Office 365 Features service description</span></span>

## <a name="whats-new-in-microsoft-defender-for-office-365"></a><span data-ttu-id="a58eb-104">Microsoft Defender for Office 365 の新機能</span><span class="sxs-lookup"><span data-stu-id="a58eb-104">What's new in Microsoft Defender for Office 365</span></span>

<span data-ttu-id="a58eb-105">Microsoft は、Defender for Office 365 に新機能を追加し続けています。</span><span class="sxs-lookup"><span data-stu-id="a58eb-105">We are continuing to add new features to Defender for Office 365.</span></span> <span data-ttu-id="a58eb-106">Defender for Office 365 (または一般的に Microsoft 365) の新機能に関する詳細については、次のリソースを参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-106">To learn more about new features coming to Defender for Office 365 (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="a58eb-107">Microsoft 365 ロードマップ</span><span class="sxs-lookup"><span data-stu-id="a58eb-107">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap)

- [<span data-ttu-id="a58eb-108">Microsoft Defender for Office 365 - Office 365 |Microsoft Docs</span><span class="sxs-lookup"><span data-stu-id="a58eb-108">What's new in Microsoft Defender for Office 365 - Office 365 | Microsoft Docs</span></span>](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a><span data-ttu-id="a58eb-109">Defender for Office 365 機能</span><span class="sxs-lookup"><span data-stu-id="a58eb-109">Defender for Office 365 capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="a58eb-110">安全な添付ファイル</span><span class="sxs-lookup"><span data-stu-id="a58eb-110">Safe Attachments</span></span>

<span data-ttu-id="a58eb-111">[添付ファイル保護](/microsoft-365/security/office-365-security/atp-safe-attachments)は、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。</span><span class="sxs-lookup"><span data-stu-id="a58eb-111">[Safe Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="a58eb-112">既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、Defender for Office 365 がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-112">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where Defender for Office 365 uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="a58eb-113">不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-113">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="a58eb-114">安全な添付ライフのスキャンは、Office 365 データが存在する安全な領域で実行されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-114">Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="a58eb-115">データ センター保護の詳細については、「[データの移動先](/microsoft-365/enterprise/o365-data-locations)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-115">For more information about data center geography, see [Where is your data located?](/microsoft-365/enterprise/o365-data-locations)</span></span>

### <a name="safe-links"></a><span data-ttu-id="a58eb-116">安全なリンク</span><span class="sxs-lookup"><span data-stu-id="a58eb-116">Safe Links</span></span>

<span data-ttu-id="a58eb-117">[安全なリンク](/microsoft-365/security/office-365-security/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪質な URL から予防的にユーザーを保護します。</span><span class="sxs-lookup"><span data-stu-id="a58eb-117">The [Safe Links](/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="a58eb-118">リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-118">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="a58eb-119">セーフリンクは、次のアプリのURLで使用できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-119">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="a58eb-120">Windows または Mac 上のエンタープライズ向け Microsoft 365 アプリ</span><span class="sxs-lookup"><span data-stu-id="a58eb-120">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="a58eb-121">Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）</span><span class="sxs-lookup"><span data-stu-id="a58eb-121">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="a58eb-122">Windows の Word、Excel、および PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a58eb-122">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="a58eb-123">Microsoft Teams チャンネルおよびチャット</span><span class="sxs-lookup"><span data-stu-id="a58eb-123">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="a58eb-124">Defender for Office 365<sup>\*</sup> がライセンスされたユーザーは、[安全なリンク] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="a58eb-124">Users must be licensed for Defender for Office 365<sup>\*</sup>, must be included in Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="a58eb-125"><sup>\*</sup> 組織全体のDefender for Office 365 ライセンス (ATP_ENTERPRISE_FACULTY など) には、個々のユーザーに Defender for Office 365 ライセンスを割り当てる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="a58eb-125"><sup>\*</sup> For organization-wide Defender for Office 365 licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign Defender for Office 365 licenses to individual users.</span></span>
>
> <span data-ttu-id="a58eb-126">安全なリンク保護の詳細については、「[Microsoft Defender for Office 365 の安全なリンク](/microsoft-365/security/office-365-security/atp-safe-links)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-126">For more information about Safe Links protection, see [Safe Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="a58eb-127">安全なドキュメント</span><span class="sxs-lookup"><span data-stu-id="a58eb-127">Safe Documents</span></span>

<span data-ttu-id="a58eb-128">[安全なドキュメント](/microsoft-365/security/office-365-security/safe-docs) 機能では、[Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) を使用して、[保護ビュー](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)で開かれたドキュメントやファイルをスキャンします。</span><span class="sxs-lookup"><span data-stu-id="a58eb-128">The [Safe Documents](/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="a58eb-129">はじめに把握しておくべき情報</span><span class="sxs-lookup"><span data-stu-id="a58eb-129">What do you need to know before you begin?</span></span>

- <span data-ttu-id="a58eb-130">安全なドキュメントは、現在 Office バージョン 2004 (12730.x) 以降を使用するユーザーに一般公開されています。</span><span class="sxs-lookup"><span data-stu-id="a58eb-130">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="a58eb-131">この機能は既定ではオフになっており、セキュリティ管理者が有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a58eb-131">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="a58eb-132">この機能は、Microsoft 365 E5 または Microsoft 365 E5 セキュリティ ライセンス (Defender for Office 365 プランには含まれません) を持つユーザーのみが利用できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-132">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Defender for Office 365 plans).</span></span>

- <span data-ttu-id="a58eb-133">Windows の Word、Excel、および PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a58eb-133">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="a58eb-134">Microsoft Teams チャンネルおよびチャット</span><span class="sxs-lookup"><span data-stu-id="a58eb-134">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="a58eb-135">Microsoft 365 E5 または Microsoft 365 E5 Security<sup>\*</sup> がライセンスされたユーザーは、[安全なドキュメント] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="a58eb-135">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="a58eb-136">安全なドキュメント保護の詳細については、「[Microsoft 365 E5 の安全なドキュメント](/microsoft-365/security/office-365-security/safe-docs)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-136">For more information about Safe Documents protection, see [Safe Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="a58eb-137">ユーザー、SharePoint、OneDrive、およびMicrosoft Teams</span><span class="sxs-lookup"><span data-stu-id="a58eb-137">Protection for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="a58eb-138">[チーム サイトSharePoint OneDriveドキュメント](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)ライブラリSharePoint、Microsoft Teamsファイルとして識別されるファイルの検出とブロックに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-138">[Protection for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="a58eb-139">さらに、[安全なリンク] 保護は、現在Microsoft Teams チャネルおよびチャットで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="a58eb-139">In addition, Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="a58eb-140">フィッシング対策ポリシー</span><span class="sxs-lookup"><span data-stu-id="a58eb-140">Anti-phishing policies</span></span>

<span data-ttu-id="a58eb-141">[フィッシング詐欺対策](/microsoft-365/security/office-365-security/atp-anti-phishing)は、受信メッセージをチェックして、メッセージがフィッシング詐欺になる可能性がある指標がないか確認します。</span><span class="sxs-lookup"><span data-stu-id="a58eb-141">[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="a58eb-142">ユーザーが Defender for Office 365 ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング詐欺対策) に含まれる場合、受信メッセージは、構成されたポリシーに基づいてメッセージを分析し、適切なアクションを実行する複数の機械学習モデルによって評価されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-142">When users are covered by Defender for Office 365 policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="a58eb-143">リアルタイム レポート</span><span class="sxs-lookup"><span data-stu-id="a58eb-143">Real-time reports</span></span>

<span data-ttu-id="a58eb-144">[セキュリティ & コンプライアンス](https://protection.office.com)センターで使用できる監視機能には、[](/microsoft-365/security/office-365-security/view-reports-for-atp)セキュリティとコンプライアンスの管理者がセキュリティ攻撃や疑わしいアクティビティの増加など、優先度の高い問題に集中できるリアルタイム のレポートと分析情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-144">Monitoring capabilities available in the [Security & Compliance Center](https://protection.office.com) include [real-time reports and insights](/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="a58eb-145">問題の領域の強調表示に加えて、スマート リポートおよび分析情報にはおすすめ候補が含まれ、データの表示および検索にリンクしてクイック アクションも実行します。</span><span class="sxs-lookup"><span data-stu-id="a58eb-145">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-explorer"></a><span data-ttu-id="a58eb-146">脅威エクスプローラー</span><span class="sxs-lookup"><span data-stu-id="a58eb-146">Threat Explorer</span></span>

<span data-ttu-id="a58eb-147">Threat Explorer (エクスプローラーとも呼ばれます) は、承認されたユーザーが最近の脅威を特定して分析できるリアルタイム レポートです。</span><span class="sxs-lookup"><span data-stu-id="a58eb-147">Threat Explorer (also referred to as Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="a58eb-148">既定では、このレポートには、過去 7 日間のデータが表示されますが、過去 30 日間のデータを表示するようにビューを変更できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-148">By default, this report shows data for the past seven days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="a58eb-149">エクスプローラーには、(メールおよびコンテンツに対する) マルウェア、送信、フィッシング、すべてのメールなどの表示が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-149">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="a58eb-150">エクスプローラーとリアルタイムの検出との比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-150">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="a58eb-151">エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-151">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="a58eb-152">リアルタイムの検出</span><span class="sxs-lookup"><span data-stu-id="a58eb-152">Real-time detections</span></span>

<span data-ttu-id="a58eb-153">リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。</span><span class="sxs-lookup"><span data-stu-id="a58eb-153">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="a58eb-154">既定では、このレポートには、エクスプローラーと同様に過去 7 日間のデータが表示されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-154">Similar to Explorer, by default, this report shows data for the past seven days.</span></span>

<span data-ttu-id="a58eb-155">リアルタイムの検出には、(メールおよびコンテンツに対する) マルウェア、送信、フィッシングなどの表示が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-155">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="a58eb-156">リアルタイム検出とエクスプローラーとの比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-156">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="a58eb-157">エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-157">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="a58eb-158">脅威トラッカー</span><span class="sxs-lookup"><span data-stu-id="a58eb-158">Threat Trackers</span></span>

<span data-ttu-id="a58eb-159">[脅威トラッカー](/microsoft-365/security/office-365-security/threat-trackers)は、組織に影響を与える可能性があるサイバーセキュリティの問題に関するインテリジェンスを許可されたユーザーに提供する、有益なウィジェットとビューです。</span><span class="sxs-lookup"><span data-stu-id="a58eb-159">[Threat Trackers](/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-investigation--response"></a><span data-ttu-id="a58eb-160">自動調査&応答</span><span class="sxs-lookup"><span data-stu-id="a58eb-160">Automated investigation & response</span></span>

<span data-ttu-id="a58eb-161">[](/microsoft-365/security/office-365-security/office-365-air) Office 365 プラン 2 の Defender で利用可能な自動調査&応答 (AIR) 機能を使用すると、現在存在する既知の脅威に対応して自動調査プロセスを実行できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-161">[Automated investigation & response](/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Defender for Office 365 Plan 2 let you run automated investigation processes in response to well-known threats that exist today.</span></span> <span data-ttu-id="a58eb-162">特定の調査タスクを自動化することで、セキュリティ運用チームは、より効率的かつ効果的に運用できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-162">By automating certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="a58eb-163">悪意のあるメール、メッセージなどの修復アクションは、セキュリティ運用チームの承認を得て実行されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-163">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="a58eb-164">詳細については、「[Office 365 での AIR のしくみ](/microsoft-365/security/office-365-security/automated-investigation-response-office)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a58eb-164">To learn more, see [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulation-training"></a><span data-ttu-id="a58eb-165">攻撃シミュレーション トレーニング</span><span class="sxs-lookup"><span data-stu-id="a58eb-165">Attack simulation training</span></span>

<span data-ttu-id="a58eb-166">[攻撃シミュレーション トレーニングは](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 、フィッシング シミュレーションの作成と管理を自動化するインテリジェントなソーシャル リスク管理ツールです。</span><span class="sxs-lookup"><span data-stu-id="a58eb-166">[Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) is an intelligent social risk management tool that automates the creation and management of phishing simulations.</span></span> <span data-ttu-id="a58eb-167">シミュレーションは、実際のフィッシングルアーとハイパーターゲットトレーニングを使用して従業員の行動を変更することで、フィッシングリスクを検出、優先順位付け、修復するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-167">Simulations help customers detect, prioritize, and remediate phishing risks by using real world phish lures and hyper-targeted training to change employee behaviors.</span></span>

- <span data-ttu-id="a58eb-168">攻撃シミュレーション のトレーニングは、WW および GCCで利用できます (6 月 21 日GCC予定)。</span><span class="sxs-lookup"><span data-stu-id="a58eb-168">Attack simulation training is now available in WW and GCC (will be in GCC from June 21).</span></span>
- <span data-ttu-id="a58eb-169">開始方法の詳細については、「攻撃シミュレーション トレーニングの使用 [を開始する」を参照してください](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。</span><span class="sxs-lookup"><span data-stu-id="a58eb-169">For more information on how to get started, see [Get started using Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).</span></span>
- <span data-ttu-id="a58eb-170">実際の攻撃者の動作を再現してフィッシング シミュレーションを関連性のあるものにする、武器化された実際のフィッシング ペイロードを適用するさまざまな攻撃手法が利用できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-170">Various attack techniques that apply de-weaponized, real-world phish payloads are available that replicate real world attacker behavior to make phishing simulations relevant.</span></span>
- <span data-ttu-id="a58eb-171">このサービスは、プラン[2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)ライセンスのMicrosoft 365 E5、Office 365 E5、Microsoft Defender のいずれかを持つOffice 365利用できます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-171">This service is available to organizations that have either Microsoft 365 E5, Office 365 E5, or [Microsoft Defender for Office 365 Plan 2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) licenses.</span></span> <span data-ttu-id="a58eb-172">機能のサブセットは、試用版として E3 のお客様に提供されます。</span><span class="sxs-lookup"><span data-stu-id="a58eb-172">A subset of capabilities is offered to E3 customers as a trial.</span></span>
- <span data-ttu-id="a58eb-173">詳しくは、「フィッシング攻撃のシミュレーション」 [をご覧ください](/microsoft-365/security/office-365-security/attack-simulation-training)。</span><span class="sxs-lookup"><span data-stu-id="a58eb-173">To learn more and try out a simulation, see [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).</span></span>