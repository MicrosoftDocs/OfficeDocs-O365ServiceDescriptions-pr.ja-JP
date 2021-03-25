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
ms.openlocfilehash: fe1d1f5a58012498e5b0f71c9a4299e61a4456ad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173392"
---
# <a name="voice-message-services"></a><span data-ttu-id="2c442-102">音声メッセージ サービス</span><span class="sxs-lookup"><span data-stu-id="2c442-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="2c442-103">ボイス メール</span><span class="sxs-lookup"><span data-stu-id="2c442-103">Voice mail</span></span>

<span data-ttu-id="2c442-104">Microsoft Exchange Online は、以下の機能を提供するホスト型のボイス メール サービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="2c442-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="2c442-105">通話応答 (ボイス メール)</span><span class="sxs-lookup"><span data-stu-id="2c442-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="2c442-106">Exchange へのダイヤルイン ユーザー インターフェイス (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="2c442-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="2c442-107">発信者用ダイヤルイン インターフェイス (自動応答)</span><span class="sxs-lookup"><span data-stu-id="2c442-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="2c442-p101">ホスト型の音声メッセージ サービスにより、会社はオンプレミスの電話システムを Exchange Online が提供するボイス メール サービスに接続できます。ボイス メール メッセージは録音され、Exchange Online インフラストラクチャに格納されます。このため、ユーザーは Outlook、Outlook on the web、または携帯電話から音声メッセージにアクセスできます。Exchange Online に対するすべてのテレフォニー接続には、ボイス オーバー IP (VoIP) プロトコルが必要です。管理者は、VoIP メディア ゲートウェイおよびセッション ボーダー コントローラー (SBC) を使用することにより、オンプレミスの IP PBX または PBX 電話システムを Exchange Online に接続できます。カスタマーが IP PBX を展開済みである場合、または PBX が VoIP を直接サポートし、Exchange 音声メッセージング サービスと相互運用可能である場合、VoIP メディア ゲートウェイは必要ありません。SBC は、オンプレミスのテレフォニー ネットワークに接続するためにカスタマーのネットワークの境界に展開され、盗聴および侵入から通信 (とカスタマーのネットワーク) をセキュリティで保護します。Microsoft Lync Server 2010 および 2013 の音声機能との相互運用性もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="2c442-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="2c442-p102">Exchange Online で使用可能な音声メッセージング サービス機能は、オンプレミスの Exchange Server 2016 で提供される音声メッセージング サービス機能とよく似たものであり、次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2c442-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="2c442-117">Outlook および Outlook on the web から電話で再生する</span><span class="sxs-lookup"><span data-stu-id="2c442-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="2c442-118">不在着信通知</span><span class="sxs-lookup"><span data-stu-id="2c442-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="2c442-119">発信者番号通知 (グローバル アドレス一覧、ユーザーの個人用連絡先、カスタム連絡先フォルダー、および外部ソーシャル ネットワークの連絡先の情報を使用)</span><span class="sxs-lookup"><span data-stu-id="2c442-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="2c442-120">Outlook on the web および Outlook からボイス メール PIN をリセットする (「[ボイス メール PIN のリセット](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="2c442-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span></span>
    
- <span data-ttu-id="2c442-121">メッセージ待機インジケーター (詳細については「[Exchange Online の MWI](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="2c442-121">Message Waiting Indicator (see [MWI in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) for details).</span></span> 
    
- <span data-ttu-id="2c442-122">通話応答ルール (詳細については、「 [ボイス メール ユーザーによる通話の転送を許可する」を](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 参照)。</span><span class="sxs-lookup"><span data-stu-id="2c442-122">Call answering rules (see [Allow voice mail users to forward calls](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) for details).</span></span>
    
- <span data-ttu-id="2c442-123">Exchange Online で保護されたボイス メール (詳細については [、「Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) でボイス メールを保護する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="2c442-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) for details).</span></span>
    
- <span data-ttu-id="2c442-124">ボイス メール プレビュー (サポートされている言語の [一覧については](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) 、「ユーザーにボイス メールトランスクリプトの表示を許可する」を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="2c442-124">Voice mail preview (see [Allow users to see a voice mail transcript](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) for a list of supported languages).</span></span>
    
- <span data-ttu-id="2c442-125">電子メール、ボイス メール、連絡先、個人用連絡先、および個人用連絡先グループへの音声アクセス</span><span class="sxs-lookup"><span data-stu-id="2c442-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="2c442-126">Outlook Voice Access または自動応答からのディレクトリ検索</span><span class="sxs-lookup"><span data-stu-id="2c442-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="2c442-127">管理者は Exchange 管理センター (EAC) を使用して、音声メッセージング サービスの相互運用性を構成して管理できます。</span><span class="sxs-lookup"><span data-stu-id="2c442-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="2c442-128">ボイス メール機能の詳細については [、「Exchange Online のボイス メール」を参照してください](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)。</span><span class="sxs-lookup"><span data-stu-id="2c442-128">For more information about voice mail features, see [Voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2c442-129">自動音声認識 (ASR) 機能は、音声コマンドを使用したメニュー ナビゲーションまたは Outlook Voice Access ユーザーや自動応答の発信者のディレクトリ検索では使用できません。</span><span class="sxs-lookup"><span data-stu-id="2c442-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="2c442-130">顧客は、VoIP ゲートウェイと PBX、IP PBX、または Skype for Business Server 2015 を使用して、公衆交換電話網 (PSTN) からのテレフォニー接続を提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2c442-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="2c442-p103">カスタマーは、社内 SBC ハードウェア デバイスを用意し、オンライン ボイス メール サービスに接続するように SBC を構成する必要があります。これには、証明書とパブリックおよびプライベート IP インターフェイスを使用し、社内ファイアウォール経由による正しい TCP ポートを有効にすることによる、適切なレベルのセキュリティを構成することが含まれます。</span><span class="sxs-lookup"><span data-stu-id="2c442-p103">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="2c442-133">ホストされたボイス メールは、Exchange Online プラン 2 および 365 Enterprise E3 サブスクライバー Officeでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="2c442-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="2c442-134">サードパーティ ボイス メールの相互運用性</span><span class="sxs-lookup"><span data-stu-id="2c442-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="2c442-p104">サードパーティ プロバイダーによる社内ボイス メール ソリューションは、音声メッセージを SMTP 経由で転送可能であるか、Microsoft Exchange Web サービスをサポートすれば、Exchange Online と相互運用できます。ボイス メール システムが SMTP 経由での音声メッセージの転送をネイティブでサポートしない場合、電子メール サーバーを社内に配置したままボイス メール システムからメッセージを受信し、SMTP を使用してクラウドに転送できます。サードパーティ ボイス メール システムの多くが、高度な UM 機能を使用するために MAPI/CDO を使用して Exchange Server と相互運用するため、Exchange Online との相互運用に SMTP を使用する場合には、これらのシステムの全機能は使用できないことがあります。</span><span class="sxs-lookup"><span data-stu-id="2c442-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="2c442-p105">Exchange Online UM では、カスタマーが運用する SBC からの直接接続によるサード パーティの PBX システムのサポートを、2018 年 7 月で終了します。詳細については、「[Exchange Online ユニファイド メッセージングでのセッション ボーダー コントローラーのサポート終了](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2c442-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="2c442-140">Skype for Business 統合</span><span class="sxs-lookup"><span data-stu-id="2c442-140">Skype for Business integration</span></span>

<span data-ttu-id="2c442-141">スタンドアロン サービスとして、または Microsoft Office 365 の一部として、Skype for Business Online を購入することができます。</span><span class="sxs-lookup"><span data-stu-id="2c442-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="2c442-142">オンプレミスの Skype for Business 2015 もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="2c442-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="2c442-143">Skype for Business Online の詳細については、「Skype for Business Online サービスの説明 [」を参照してください](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2c442-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="2c442-144">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="2c442-144">Feature availability</span></span>

<span data-ttu-id="2c442-145">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="2c442-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
