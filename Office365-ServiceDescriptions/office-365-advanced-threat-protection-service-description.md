---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。
ms.openlocfilehash: 2c08cb74b826602ec9e123cae3e6e29390b37895
ms.sourcegitcommit: faa19e491c43f33c0a07077b7dcb74daa11d4842
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "40824991"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="7b83b-103">Office 365 Advanced Threat Protection サービスの説明</span><span class="sxs-lookup"><span data-stu-id="7b83b-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="7b83b-p101">Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-p101">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="7b83b-106">メッセージ保護に対して ATP を使用する主な方法は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="7b83b-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="7b83b-107">Office 365 ATP のフィルター処理のみのシナリオでは、オンプレミスの Exchange Server 環境またはその他の社内 SMTP 電子メールソリューションに対して、クラウドベースの電子メール保護を ATP が提供します。</span><span class="sxs-lookup"><span data-stu-id="7b83b-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="7b83b-108">Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="7b83b-109">Exchange Online の詳細については、「 [Exchange online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="7b83b-110">ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="7b83b-111">Office 365 Advanced Threat Protection (ATP) の可用性</span><span class="sxs-lookup"><span data-stu-id="7b83b-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="7b83b-112">ATP は、Office 365 Enterprise E5、Office 365 エデュケーション A5、および Microsoft 365 Business に含まれています。</span><span class="sxs-lookup"><span data-stu-id="7b83b-112">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span>

<span data-ttu-id="7b83b-113">ATP は、次の Exchange と Office 365 サブスクリプション プランに追加できます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-113">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span>

- <span data-ttu-id="7b83b-114">Exchange Online プラン 1</span><span class="sxs-lookup"><span data-stu-id="7b83b-114">Exchange Online Plan 1</span></span>

- <span data-ttu-id="7b83b-115">Exchange Online プラン 2</span><span class="sxs-lookup"><span data-stu-id="7b83b-115">Exchange Online Plan 2</span></span>

- <span data-ttu-id="7b83b-116">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="7b83b-116">Exchange Online Kiosk</span></span>

- <span data-ttu-id="7b83b-117">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="7b83b-117">Exchange Online Protection</span></span>

- <span data-ttu-id="7b83b-118">Office 365 Business Essentials</span><span class="sxs-lookup"><span data-stu-id="7b83b-118">Office 365 Business Essentials</span></span>

- <span data-ttu-id="7b83b-119">Office 365 Business Premium</span><span class="sxs-lookup"><span data-stu-id="7b83b-119">Office 365 Business Premium</span></span>

- <span data-ttu-id="7b83b-120">Office 365 Enterprise E1</span><span class="sxs-lookup"><span data-stu-id="7b83b-120">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="7b83b-121">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="7b83b-121">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="7b83b-122">Office 365 Enterprise F1</span><span class="sxs-lookup"><span data-stu-id="7b83b-122">Office 365 Enterprise F1</span></span>

- <span data-ttu-id="7b83b-123">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="7b83b-123">Office 365 A1</span></span>

- <span data-ttu-id="7b83b-124">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="7b83b-124">Office 365 A3</span></span>

<span data-ttu-id="7b83b-125">Office 365 Advanced Threat Protection を購入するには、「[Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-125">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="7b83b-126">プランの機能を比較するには、「 [Office 365 For Business プランの比較](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」を参照して、[適切な Microsoft 365 Enterprise ソリューションを見つけ](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)てください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-126">To compare features across plans, see [Compare Office 365 for Business plans](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Discover the Microsoft 365 Enterprise solution that's right for you](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="7b83b-127">Office 365 Advanced Threat Protection (ATP) の新機能</span><span class="sxs-lookup"><span data-stu-id="7b83b-127">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="7b83b-128">引き続き Office 365 ATP に新機能を追加しています。</span><span class="sxs-lookup"><span data-stu-id="7b83b-128">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="7b83b-129">ATP (または Microsoft 365 全般) に出てくる新機能の詳細については、以下のリソースを参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-129">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="7b83b-130">Microsoft 365 ロードマップ</span><span class="sxs-lookup"><span data-stu-id="7b83b-130">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="7b83b-131">Office 365 ATP の新機能</span><span class="sxs-lookup"><span data-stu-id="7b83b-131">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="7b83b-132">Office 365 Advanced Threat Protection (ATP) の要件</span><span class="sxs-lookup"><span data-stu-id="7b83b-132">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="7b83b-133">ATP は、Microsoft Exchange Server などの任意の SMTP メール転送エージェントで使用できます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-133">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="7b83b-134">ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-134">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="7b83b-135">Advanced Threat Protection (ATP) の各プランで利用できる機能</span><span class="sxs-lookup"><span data-stu-id="7b83b-135">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="7b83b-p105">各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。</span><span class="sxs-lookup"><span data-stu-id="7b83b-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="7b83b-138">**機能**</span><span class="sxs-lookup"><span data-stu-id="7b83b-138">**Feature**</span></span>|<span data-ttu-id="7b83b-139">**ATP プラン1**</span><span class="sxs-lookup"><span data-stu-id="7b83b-139">**ATP Plan 1**</span></span><br><span data-ttu-id="7b83b-140">(旧称 ATP スタンドアロン)</span><span class="sxs-lookup"><span data-stu-id="7b83b-140">(formerly ATP standalone)</span></span>|<span data-ttu-id="7b83b-141">**ATP プラン2**</span><span class="sxs-lookup"><span data-stu-id="7b83b-141">**ATP Plan 2**</span></span><br><span data-ttu-id="7b83b-142">(以前の脅威インテリジェンス</span><span class="sxs-lookup"><span data-stu-id="7b83b-142">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="7b83b-143">スタンドアロン</span><span class="sxs-lookup"><span data-stu-id="7b83b-143">standalone)</span></span>| <span data-ttu-id="7b83b-144">Office 365 Enterprise E5</span><span class="sxs-lookup"><span data-stu-id="7b83b-144">Office 365 Enterprise E5</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="7b83b-145">*構成、保護、および検出*</span><span class="sxs-lookup"><span data-stu-id="7b83b-145">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="7b83b-146">安全な添付ファイル</span><span class="sxs-lookup"><span data-stu-id="7b83b-146">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="7b83b-147">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-147">Yes</span></span>|<span data-ttu-id="7b83b-148">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-148">Yes</span></span>|<span data-ttu-id="7b83b-149">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-149">Yes</span></span>|
|<span data-ttu-id="7b83b-150">Teams での安全な添付ファイル</span><span class="sxs-lookup"><span data-stu-id="7b83b-150">Safe Attachments in Teams</span></span>|<span data-ttu-id="7b83b-151">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-151">Yes</span></span>|<span data-ttu-id="7b83b-152">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-152">Yes</span></span>|<span data-ttu-id="7b83b-153">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-153">Yes</span></span>|
|[<span data-ttu-id="7b83b-154">安全なリンク</span><span class="sxs-lookup"><span data-stu-id="7b83b-154">Safe Links</span></span>](#safe-links)|<span data-ttu-id="7b83b-155">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-155">Yes</span></span>|<span data-ttu-id="7b83b-156">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-156">Yes</span></span>|<span data-ttu-id="7b83b-157">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-157">Yes</span></span>|
|<span data-ttu-id="7b83b-158">Teams での安全なリンク</span><span class="sxs-lookup"><span data-stu-id="7b83b-158">Safe Links in Teams</span></span>|<span data-ttu-id="7b83b-159">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-159">No</span></span>|<span data-ttu-id="7b83b-160">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-160">No</span></span>|<span data-ttu-id="7b83b-161">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-161">No</span></span>|
|[<span data-ttu-id="7b83b-162">SharePoint、OneDrive、Microsoft Teams 用の ATP</span><span class="sxs-lookup"><span data-stu-id="7b83b-162">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="7b83b-163">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-163">Yes</span></span>|<span data-ttu-id="7b83b-164">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-164">Yes</span></span>|<span data-ttu-id="7b83b-165">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-165">Yes</span></span>|
|[<span data-ttu-id="7b83b-166">フィッシング対策ポリシー</span><span class="sxs-lookup"><span data-stu-id="7b83b-166">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="7b83b-167">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-167">Yes</span></span>|<span data-ttu-id="7b83b-168">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-168">Yes</span></span>|<span data-ttu-id="7b83b-169">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-169">Yes</span></span>|
|[<span data-ttu-id="7b83b-170">リアルタイムレポート</span><span class="sxs-lookup"><span data-stu-id="7b83b-170">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="7b83b-171">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-171">Yes</span></span>|<span data-ttu-id="7b83b-172">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-172">Yes</span></span>|<span data-ttu-id="7b83b-173">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-173">Yes</span></span>|
|<span data-ttu-id="7b83b-174">*自動化、調査、修復、教育*</span><span class="sxs-lookup"><span data-stu-id="7b83b-174">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="7b83b-175">脅威トラッカー</span><span class="sxs-lookup"><span data-stu-id="7b83b-175">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="7b83b-176">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-176">No</span></span>|<span data-ttu-id="7b83b-177">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-177">Yes</span></span>|<span data-ttu-id="7b83b-178">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-178">Yes</span></span>|
|<span data-ttu-id="7b83b-179">[エクスプローラー](#explorer) (高度な脅威調査)</span><span class="sxs-lookup"><span data-stu-id="7b83b-179">[Explorer](#explorer) (advanced threat investigation)</span></span>|<span data-ttu-id="7b83b-180">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-180">No</span></span>|<span data-ttu-id="7b83b-181">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-181">Yes</span></span>|<span data-ttu-id="7b83b-182">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-182">Yes</span></span>|
|[<span data-ttu-id="7b83b-183">インシデント対応の自動化</span><span class="sxs-lookup"><span data-stu-id="7b83b-183">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="7b83b-184">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-184">No</span></span>|<span data-ttu-id="7b83b-185">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-185">Yes</span></span>|<span data-ttu-id="7b83b-186">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-186">Yes</span></span>|
|[<span data-ttu-id="7b83b-187">攻撃シミュレータ</span><span class="sxs-lookup"><span data-stu-id="7b83b-187">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="7b83b-188">いいえ</span><span class="sxs-lookup"><span data-stu-id="7b83b-188">No</span></span>|<span data-ttu-id="7b83b-189">あり</span><span class="sxs-lookup"><span data-stu-id="7b83b-189">Yes</span></span>|<span data-ttu-id="7b83b-190">はい</span><span class="sxs-lookup"><span data-stu-id="7b83b-190">Yes</span></span>|

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="7b83b-191">Advanced Threat Protection (ATP) の機能</span><span class="sxs-lookup"><span data-stu-id="7b83b-191">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="7b83b-192">添付ファイル保護</span><span class="sxs-lookup"><span data-stu-id="7b83b-192">Safe Attachments</span></span>

<span data-ttu-id="7b83b-193">[ATP の安全な添付ファイル](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)は、不明なマルウェアやウイルスから保護され、メッセージングシステムを保護するためのゼロ日の保護を提供します。</span><span class="sxs-lookup"><span data-stu-id="7b83b-193">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="7b83b-194">既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、ATP がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-194">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="7b83b-195">不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-195">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="7b83b-196">ATP の安全な添付ファイルのスキャンは、Office 365 データが存在する地域と同じ地域で行われます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-196">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="7b83b-197">データセンター地理の詳細については、「[データの保存場所](https://products.office.com/where-is-your-data-located?geo=All)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-197">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="7b83b-198">安全なリンク</span><span class="sxs-lookup"><span data-stu-id="7b83b-198">Safe Links</span></span>

<span data-ttu-id="7b83b-199">[ATP の安全なリンク](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪意のある url からユーザーを予防的に保護します。</span><span class="sxs-lookup"><span data-stu-id="7b83b-199">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="7b83b-200">リンクを選択するたびに保護は保持されます。悪意のあるリンクは、適切なリンクにアクセスできるように、動的にブロックされます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-200">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="7b83b-201">安全なリンクは、次のアプリの Url に対して使用できます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-201">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="7b83b-202">Office 365 ProPlus on Windows または Mac</span><span class="sxs-lookup"><span data-stu-id="7b83b-202">Office 365 ProPlus on Windows or Mac</span></span>

- <span data-ttu-id="7b83b-203">Web 用 Office (web 用の Word、web 用の Excel、web 用の PowerPoint、web 用の OneNote)</span><span class="sxs-lookup"><span data-stu-id="7b83b-203">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="7b83b-204">Windows 上の Word、Excel、PowerPoint、および Visio と、iOS および Android デバイス上の Office アプリ</span><span class="sxs-lookup"><span data-stu-id="7b83b-204">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

> [!NOTE]
> <span data-ttu-id="7b83b-205">ユーザーが ATP<sup>\*</sup>のライセンスを持っている必要があり、Atp の安全なリンクポリシーに含まれている必要があります。また、保護のためにデバイス上でサインインする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7b83b-205">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="7b83b-206"><sup>\*</sup>組織全体にわたる ATP のライセンス (ATP_ENTERPRISE_FACULTY など) については、個々のユーザーに ATP ライセンスを割り当てる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7b83b-206"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="7b83b-207">ATP の安全なリンク保護の詳細については、「 [Office ドキュメントの url で atp の安全なリンクが機能する方法](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-207">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="7b83b-208">SharePoint、OneDrive、Microsoft Teams 用の ATP</span><span class="sxs-lookup"><span data-stu-id="7b83b-208">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="7b83b-209">[SharePoint、OneDrive、Microsoft Teams 用の ATP は、](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)チームサイトやドキュメントライブラリで悪意のあるものとして識別されたファイルを検出してブロックするのに便利です。</span><span class="sxs-lookup"><span data-stu-id="7b83b-209">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="7b83b-210">フィッシング対策ポリシー</span><span class="sxs-lookup"><span data-stu-id="7b83b-210">Anti-phishing policies</span></span>

<span data-ttu-id="7b83b-211">[ATP のフィッシング対策](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)は、メッセージがフィッシングである可能性があることを示すインジケーターの受信メッセージをチェックします。</span><span class="sxs-lookup"><span data-stu-id="7b83b-211">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="7b83b-212">ユーザーが ATP ポリシー (「安全な添付ファイル」、「安全なリンク」、または「フィッシング対策」) でカバーされている場合、受信メッセージは、メッセージを分析し、構成されたポリシーに基づいて適切なアクションを実行する複数の machine learning モデルによって評価されます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-212">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="7b83b-213">リアルタイムレポート</span><span class="sxs-lookup"><span data-stu-id="7b83b-213">Real-time reports</span></span>

<span data-ttu-id="7b83b-214">Office 365 セキュリティ & コンプライアンスセンターで利用可能な監視機能には[リアルタイムのレポートと洞察](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)が含まれており、セキュリティおよびコンプライアンスの管理者は、セキュリティ攻撃や不審な活動の増加など、優先度の高い問題に焦点を当てることができます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-214">Monitoring capabilities available in the Office 365 Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="7b83b-215">スマートレポートと分析には、問題の領域を強調するだけでなく、データを表示して探索したり、簡単なアクションを実行したりするための推奨事項やリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="7b83b-215">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="7b83b-216">脅威トラッカー</span><span class="sxs-lookup"><span data-stu-id="7b83b-216">Threat Trackers</span></span>

<span data-ttu-id="7b83b-217">[脅威のトラッカー](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)は、組織に影響を与える可能性がある cybersecurity の問題に関するインテリジェンスを承認されたユーザーに提供する情報ウィジェットとビューです。</span><span class="sxs-lookup"><span data-stu-id="7b83b-217">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="explorer"></a><span data-ttu-id="7b83b-218">Explorer</span><span class="sxs-lookup"><span data-stu-id="7b83b-218">Explorer</span></span>

<span data-ttu-id="7b83b-219">エクスプローラー (脅威エクスプローラーとも呼ばれます) はリアルタイムレポートで、承認されたユーザーが最近の脅威を識別して分析できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7b83b-219">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="7b83b-220">既定では、このレポートには過去7日間のデータが表示されます。ただし、過去30日間のデータを表示するようにビューを変更することはできます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-220">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="7b83b-221">エクスプローラー (Office 365 Advanced Threat Protection プラン 2) およびリアルタイム検出 (Office 365 Advanced Threat Protection プラン 1) の詳細については、「[脅威エクスプローラー (およびリアルタイム検出)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-221">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="7b83b-222">インシデント対応の自動化</span><span class="sxs-lookup"><span data-stu-id="7b83b-222">Automated incident response</span></span>

<span data-ttu-id="7b83b-223">Office 365 ATP Plan 2 で利用できる[自動インシデント対応](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)(エア) 機能により、現在存在している既知の脅威への対応として、自動化された調査プロセスを実行することができます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-223">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="7b83b-224">自動化された特定の調査タスクによって、セキュリティ運用チームはより効率的かつ効果的に操作できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7b83b-224">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="7b83b-225">ウイルス対策アクション (悪意のある電子メールメッセージの削除など) は、セキュリティ運用チームによる承認に基づいて行われます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-225">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="7b83b-226">詳細については、「 [Office 365 での空気の仕組み](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7b83b-226">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="7b83b-227">攻撃シミュレータ</span><span class="sxs-lookup"><span data-stu-id="7b83b-227">Attack Simulator</span></span>

<span data-ttu-id="7b83b-228">[アタックシミュレータ](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)を使用すると、承認されたユーザーが組織内で現実的な攻撃シナリオを実行できます。</span><span class="sxs-lookup"><span data-stu-id="7b83b-228">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="7b83b-229">表示名のスピアーフィッシング攻撃、パスワードスプレー攻撃、ブルートフォースパスワード攻撃など、さまざまな種類の攻撃が利用可能です。</span><span class="sxs-lookup"><span data-stu-id="7b83b-229">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
