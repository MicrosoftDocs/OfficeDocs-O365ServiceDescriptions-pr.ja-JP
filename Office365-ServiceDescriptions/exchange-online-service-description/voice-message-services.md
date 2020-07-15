---
title: 音声メッセージ サービス
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132551"
---
# <a name="voice-message-services"></a><span data-ttu-id="4a027-102">音声メッセージ サービス</span><span class="sxs-lookup"><span data-stu-id="4a027-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="4a027-103">ボイス メール</span><span class="sxs-lookup"><span data-stu-id="4a027-103">Voice mail</span></span>

<span data-ttu-id="4a027-104">Microsoft Exchange Online は、以下の機能を提供するホスト型のボイス メール サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4a027-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="4a027-105">通話応答 (ボイス メール)</span><span class="sxs-lookup"><span data-stu-id="4a027-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="4a027-106">Exchange へのダイヤルイン ユーザー インターフェイス (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="4a027-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="4a027-107">発信者用ダイヤルイン インターフェイス (自動応答)</span><span class="sxs-lookup"><span data-stu-id="4a027-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="4a027-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4a027-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span></span> <span data-ttu-id="4a027-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span><span class="sxs-lookup"><span data-stu-id="4a027-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span></span> <span data-ttu-id="4a027-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span><span class="sxs-lookup"><span data-stu-id="4a027-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span></span> <span data-ttu-id="4a027-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4a027-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span></span> <span data-ttu-id="4a027-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span><span class="sxs-lookup"><span data-stu-id="4a027-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span></span> <span data-ttu-id="4a027-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span><span class="sxs-lookup"><span data-stu-id="4a027-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span></span> <span data-ttu-id="4a027-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span><span class="sxs-lookup"><span data-stu-id="4a027-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="4a027-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span><span class="sxs-lookup"><span data-stu-id="4a027-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span></span> <span data-ttu-id="4a027-116">These include:</span><span class="sxs-lookup"><span data-stu-id="4a027-116">These include:</span></span>
  
- <span data-ttu-id="4a027-117">Outlook および Outlook on the web から電話で再生する</span><span class="sxs-lookup"><span data-stu-id="4a027-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="4a027-118">不在着信通知</span><span class="sxs-lookup"><span data-stu-id="4a027-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="4a027-119">発信者番号通知 (グローバル アドレス一覧、ユーザーの個人用連絡先、カスタム連絡先フォルダー、および外部ソーシャル ネットワークの連絡先の情報を使用)</span><span class="sxs-lookup"><span data-stu-id="4a027-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="4a027-120">Outlook on the web および Outlook からボイス メール PIN をリセットする (「[ボイス メール PIN のリセット](https://go.microsoft.com/fwlink/p/?LinkId=286328)」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4a027-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="4a027-121">メッセージ待機インジケーター (詳細については「[Exchange Online の MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794)」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4a027-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="4a027-122">通話応答ルール (詳細については、「[ボイスメールユーザーが通話を転送できるように](https://go.microsoft.com/fwlink/p/?LinkId=271795)する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4a027-122">Call answering rules (see [Allow voice mail users to forward calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span>
    
- <span data-ttu-id="4a027-123">Exchange Online の保護されたボイスメール (詳細については、「 [Exchange online のボイスメールを保護](https://go.microsoft.com/fwlink/p/?LinkId=271796)する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4a027-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span>
    
- <span data-ttu-id="4a027-124">ボイスメールプレビュー (サポートされている言語の一覧については、「[ユーザーがボイスメールのトランスクリプトを表示できる」を](https://go.microsoft.com/fwlink/p/?LinkId=271797)参照してください)。</span><span class="sxs-lookup"><span data-stu-id="4a027-124">Voice mail preview (see [Allow users to see a voice mail transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span>
    
- <span data-ttu-id="4a027-125">電子メール、ボイス メール、連絡先、個人用連絡先、および個人用連絡先グループへの音声アクセス</span><span class="sxs-lookup"><span data-stu-id="4a027-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="4a027-126">Outlook Voice Access または自動応答からのディレクトリ検索</span><span class="sxs-lookup"><span data-stu-id="4a027-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="4a027-127">管理者は Exchange 管理センター (EAC) を使用して、音声メッセージング サービスの相互運用性を構成して管理できます。</span><span class="sxs-lookup"><span data-stu-id="4a027-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="4a027-128">ボイスメール機能の詳細については、「 [Exchange Online のボイスメール](https://go.microsoft.com/fwlink/p/?LinkId=271798)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4a027-128">For more information about voice mail features, see [Voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="4a027-129">自動音声認識 (ASR) 機能は、音声コマンドを使用したメニュー ナビゲーションまたは Outlook Voice Access ユーザーや自動応答の発信者のディレクトリ検索では使用できません。</span><span class="sxs-lookup"><span data-stu-id="4a027-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="4a027-130">お客様は、VoIP ゲートウェイと PBX、IP PBX、または Skype for Business Server 2015 を使用して、公衆交換電話網 (PSTN) からテレフォニー接続を提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4a027-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="4a027-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span><span class="sxs-lookup"><span data-stu-id="4a027-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span></span> <span data-ttu-id="4a027-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span><span class="sxs-lookup"><span data-stu-id="4a027-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="4a027-133">ホストボイスメールは、Exchange Online プラン2および Office 365 Enterprise E3 サブスクライバーに対してのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a027-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="4a027-134">サードパーティ ボイス メールの相互運用性</span><span class="sxs-lookup"><span data-stu-id="4a027-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="4a027-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span><span class="sxs-lookup"><span data-stu-id="4a027-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span></span> <span data-ttu-id="4a027-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span><span class="sxs-lookup"><span data-stu-id="4a027-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span></span> <span data-ttu-id="4a027-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4a027-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="4a027-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span><span class="sxs-lookup"><span data-stu-id="4a027-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span></span> <span data-ttu-id="4a027-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span><span class="sxs-lookup"><span data-stu-id="4a027-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="4a027-140">Skype for Business 統合</span><span class="sxs-lookup"><span data-stu-id="4a027-140">Skype for Business integration</span></span>

<span data-ttu-id="4a027-141">スタンドアロン サービスとして、または Microsoft Office 365 の一部として、Skype for Business Online を購入することができます。</span><span class="sxs-lookup"><span data-stu-id="4a027-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="4a027-142">オンプレミスの Skype for Business 2015 もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="4a027-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="4a027-143">Skype for business Online の詳細については、「 [skype For Business online サービスの説明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4a027-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4a027-144">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="4a027-144">Feature availability</span></span>

<span data-ttu-id="4a027-145">プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4a027-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

