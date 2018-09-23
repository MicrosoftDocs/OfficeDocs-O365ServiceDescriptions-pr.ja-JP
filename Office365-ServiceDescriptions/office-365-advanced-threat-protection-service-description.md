---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036314"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="f84ca-104">Office 365 Advanced Threat Protection サービスの説明</span><span class="sxs-lookup"><span data-stu-id="f84ca-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="f84ca-p102">Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p102">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>
  
<span data-ttu-id="f84ca-107">メッセージング保護に ATP を使用できる基本的な方法として、次のようなものがあります。</span><span class="sxs-lookup"><span data-stu-id="f84ca-107">The following are the primary ways you can use ATP for messaging protection:</span></span>
  
- <span data-ttu-id="f84ca-108">Office 365 ATP のフィルタリングのみのシナリオ ATP は、オンプレミスの Exchange Server 2013 環境、従来の Exchange Server バージョン、その他のオンプレミス SMTP メール ソリューションにクラウドベースのメール保護を提供します。</span><span class="sxs-lookup"><span data-stu-id="f84ca-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server 2013 environment, legacy Exchange Server versions, or any other on-premises SMTP email solution.</span></span>
    
- <span data-ttu-id="f84ca-p103">Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。Exchange Online の詳細については、「[Exchange Online サービスの説明](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p103">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes. To learn more about Exchange Online, see the [Exchange Online Service Description](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).</span></span>
    
- <span data-ttu-id="f84ca-111">ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="f84ca-112">Office 365 Advanced Threat Protection (ATP) の可用性</span><span class="sxs-lookup"><span data-stu-id="f84ca-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="f84ca-113">Office 365 エンタープライズ E5、Office 365 の教育 A5、および Microsoft 365 のビジネスでは、分析ツールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="f84ca-114">Microsoft 365 ビジネスでクライアントに依存する分析ツールの機能を利用可能な夏の 2018 となります。</span><span class="sxs-lookup"><span data-stu-id="f84ca-114">Client-dependent ATP features in Microsoft 365 Business will be available Summer 2018.</span></span> 
  
<span data-ttu-id="f84ca-115">ATP は、次の Exchange と Office 365 サブスクリプション プランに追加できます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-115">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span> 
  
- <span data-ttu-id="f84ca-116">Exchange Online プラン 1</span><span class="sxs-lookup"><span data-stu-id="f84ca-116">Exchange Online Plan 1</span></span>
    
- <span data-ttu-id="f84ca-117">Exchange Online プラン 2</span><span class="sxs-lookup"><span data-stu-id="f84ca-117">Exchange Online Plan 2</span></span>
    
- <span data-ttu-id="f84ca-118">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="f84ca-118">Exchange Online Kiosk</span></span>
    
- <span data-ttu-id="f84ca-119">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="f84ca-119">Exchange Online Protection</span></span>
    
- <span data-ttu-id="f84ca-120">Office 365 Business Essentials</span><span class="sxs-lookup"><span data-stu-id="f84ca-120">Office 365 Business Essentials</span></span>
    
- <span data-ttu-id="f84ca-121">Office 365 Business Premium</span><span class="sxs-lookup"><span data-stu-id="f84ca-121">Office 365 Business Premium</span></span>
    
- <span data-ttu-id="f84ca-122">Office 365 Enterprise E1</span><span class="sxs-lookup"><span data-stu-id="f84ca-122">Office 365 Enterprise E1</span></span>
    
- <span data-ttu-id="f84ca-123">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="f84ca-123">Office 365 Enterprise E3</span></span>
    
- <span data-ttu-id="f84ca-124">Office 365 Enterprise F1</span><span class="sxs-lookup"><span data-stu-id="f84ca-124">Office 365 Enterprise F1</span></span>
    
- <span data-ttu-id="f84ca-125">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="f84ca-125">Office 365 A1</span></span>
    
- <span data-ttu-id="f84ca-126">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="f84ca-126">Office 365 A3</span></span>
    
<span data-ttu-id="f84ca-127">Office 365 Advanced Threat Protection を購入するには、「[Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ca-127">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).</span></span>
  
<span data-ttu-id="f84ca-128">各プランの機能を比較するには、「[プランを選ぶ](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f84ca-128">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span></span>
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="f84ca-129">Office 365 Advanced Threat Protection (ATP) の新機能</span><span class="sxs-lookup"><span data-stu-id="f84ca-129">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="f84ca-130">ATP の新機能の詳細については、「[Office 365 の ATP の安全なリンク](https://go.microsoft.com/fwlink/?linkid=846016)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ca-130">For information about new features in ATP, see [ATP safe links in Office 365](https://go.microsoft.com/fwlink/?linkid=846016).</span></span>
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="f84ca-131">Office 365 Advanced Threat Protection (ATP) の要件</span><span class="sxs-lookup"><span data-stu-id="f84ca-131">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="f84ca-p104">ATP は、Microsoft Exchange Server 2013 などのあらゆる SMTP メール転送エージェントと一緒に使用できます。ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p104">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server 2013. For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="f84ca-134">Advanced Threat Protection (ATP) の各プランで利用できる機能</span><span class="sxs-lookup"><span data-stu-id="f84ca-134">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="f84ca-p105">各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>
  
|<span data-ttu-id="f84ca-137">**機能**</span><span class="sxs-lookup"><span data-stu-id="f84ca-137">**Feature**</span></span>|<span data-ttu-id="f84ca-138">**ATP スタンドアロン**</span><span class="sxs-lookup"><span data-stu-id="f84ca-138">**ATP standalone**</span></span>|<span data-ttu-id="f84ca-139">**Exchange Online Protection**</span><span class="sxs-lookup"><span data-stu-id="f84ca-139">**Exchange Online Protection**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="f84ca-140">リンク保護</span><span class="sxs-lookup"><span data-stu-id="f84ca-140">Safe Links</span></span>  <br/> |<span data-ttu-id="f84ca-141">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-141">Yes</span></span>  <br/> |<span data-ttu-id="f84ca-142">いいえ</span><span class="sxs-lookup"><span data-stu-id="f84ca-142">No</span></span>  <br/> |
|<span data-ttu-id="f84ca-143">添付ファイル保護</span><span class="sxs-lookup"><span data-stu-id="f84ca-143">Safe Attachments</span></span>  <br/> |<span data-ttu-id="f84ca-144">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-144">Yes</span></span>  <br/> |<span data-ttu-id="f84ca-145">いいえ</span><span class="sxs-lookup"><span data-stu-id="f84ca-145">No</span></span>  <br/> |
|<span data-ttu-id="f84ca-146">スプーフィング インテリジェンス</span><span class="sxs-lookup"><span data-stu-id="f84ca-146">Spoof intelligence</span></span>  <br/> |<span data-ttu-id="f84ca-147">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-147">Yes</span></span>  <br/> |<span data-ttu-id="f84ca-148">いいえ</span><span class="sxs-lookup"><span data-stu-id="f84ca-148">No</span></span>  <br/> |
|<span data-ttu-id="f84ca-149">検疫</span><span class="sxs-lookup"><span data-stu-id="f84ca-149">Quarantine</span></span>  <br/> |<span data-ttu-id="f84ca-150">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-150">Yes</span></span>  <br/> |<span data-ttu-id="f84ca-151">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-151">Yes</span></span>  <br/> |
|<span data-ttu-id="f84ca-152">高度なフィッシング詐欺対策機能</span><span class="sxs-lookup"><span data-stu-id="f84ca-152">Advanced anti-phishing capabilities</span></span>  <br/> |<span data-ttu-id="f84ca-153">はい</span><span class="sxs-lookup"><span data-stu-id="f84ca-153">Yes</span></span>  <br/> |<span data-ttu-id="f84ca-154">いいえ</span><span class="sxs-lookup"><span data-stu-id="f84ca-154">No</span></span>  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="f84ca-155">Advanced Threat Protection (ATP) の機能</span><span class="sxs-lookup"><span data-stu-id="f84ca-155">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-links"></a><span data-ttu-id="f84ca-156">リンク保護</span><span class="sxs-lookup"><span data-stu-id="f84ca-156">Safe Links</span></span>

<span data-ttu-id="f84ca-p106">ATP リンク保護機能は、メッセージ内の悪質なハイパーリンクから予防的にユーザーを保護します。リンクをクリックした後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p106">The ATP Safe Links feature proactively protects your users from malicious hyperlinks in a message. The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>
  
### <a name="safe-attachments"></a><span data-ttu-id="f84ca-159">添付ファイル保護</span><span class="sxs-lookup"><span data-stu-id="f84ca-159">Safe Attachments</span></span>

<span data-ttu-id="f84ca-p107">添付ファイル保護は、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、ATP がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p107">Safe Attachments protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system. All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent. If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span> 
  
### <a name="spoof-intelligence"></a><span data-ttu-id="f84ca-163">スプーフィング インテリジェンス</span><span class="sxs-lookup"><span data-stu-id="f84ca-163">Spoof intelligence</span></span>

<span data-ttu-id="f84ca-p108">スプーフィングのインテリジェンスは、送信者が組織のドメインのいずれか 1 つまたは複数のユーザー アカウントの代理でメールを送信するときを検出します。自分のドメインのなりすましは、すべての送信者を確認し、続行するか、送信者をブロックする送信者を許可するを選択しすることができます。スプーフィングのインテリジェンスは、セキュリティで利用可能な&amp;、スパム対策の設定] ページ上のコンプライアンス センターです。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p108">Spoof intelligence detects when a sender appears to be sending mail on behalf of one or more user accounts within one of your organization's domains. It enables you to review all senders who are spoofing your domain, and then choose to allow the sender to continue or block the sender. Spoof intelligence is available in the Security &amp; Compliance Center on the Anti-spam settings page.</span></span>
  
### <a name="quarantine"></a><span data-ttu-id="f84ca-167">検疫</span><span class="sxs-lookup"><span data-stu-id="f84ca-167">Quarantine</span></span>

<span data-ttu-id="f84ca-p109">スパム、バルク メール、フィッシング詐欺メール、マルウェアを含んだメールとして Office 365 サービスが識別したメッセージや、メール フロー ルールに一致しているために Office 365 サービスが識別したメッセージは、検疫に送ることができます。既定では、Office 365 は、フィッシング詐欺メッセージとマルウェアを含むメッセージを検疫に直接送信します。許可されているユーザーは、検疫に送信された電子メール メッセージを確認、削除、管理できます。</span><span class="sxs-lookup"><span data-stu-id="f84ca-p109">Messages identified by the Office 365 service as spam, bulk mail, phishing mail, containing malware, or because they matched a mail flow rule can be sent to quarantine. By default, Office 365 sends phishing messages and messages containing malware directly to quarantine. Authorized users can review, delete, or manage email messages sent to quarantine.</span></span>
  
### <a name="advanced-anti-phishing-capabilities"></a><span data-ttu-id="f84ca-171">高度なフィッシング詐欺対策機能</span><span class="sxs-lookup"><span data-stu-id="f84ca-171">Advanced anti-phishing capabilities</span></span>

<span data-ttu-id="f84ca-172">この機能は、フィッシング詐欺メッセージを検出するために、機械学習モデルを使用します。</span><span class="sxs-lookup"><span data-stu-id="f84ca-172">This feature uses machine learning models to detect phishing messages.</span></span> 
  
