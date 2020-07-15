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
# <a name="voice-message-services"></a>音声メッセージ サービス

## <a name="voice-mail"></a>ボイス メール

Microsoft Exchange Online は、以下の機能を提供するホスト型のボイス メール サービスを提供します。
  
- 通話応答 (ボイス メール)
    
- Exchange へのダイヤルイン ユーザー インターフェイス (Outlook Voice Access)
    
- 発信者用ダイヤルイン インターフェイス (自動応答)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
- Outlook および Outlook on the web から電話で再生する
    
- 不在着信通知
    
- 発信者番号通知 (グローバル アドレス一覧、ユーザーの個人用連絡先、カスタム連絡先フォルダー、および外部ソーシャル ネットワークの連絡先の情報を使用)
    
- Outlook on the web および Outlook からボイス メール PIN をリセットする (「[ボイス メール PIN のリセット](https://go.microsoft.com/fwlink/p/?LinkId=286328)」を参照してください)。
    
- メッセージ待機インジケーター (詳細については「[Exchange Online の MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794)」を参照してください)。 
    
- 通話応答ルール (詳細については、「[ボイスメールユーザーが通話を転送できるように](https://go.microsoft.com/fwlink/p/?LinkId=271795)する」を参照してください)。
    
- Exchange Online の保護されたボイスメール (詳細については、「 [Exchange online のボイスメールを保護](https://go.microsoft.com/fwlink/p/?LinkId=271796)する」を参照してください)。
    
- ボイスメールプレビュー (サポートされている言語の一覧については、「[ユーザーがボイスメールのトランスクリプトを表示できる」を](https://go.microsoft.com/fwlink/p/?LinkId=271797)参照してください)。
    
- 電子メール、ボイス メール、連絡先、個人用連絡先、および個人用連絡先グループへの音声アクセス
    
- Outlook Voice Access または自動応答からのディレクトリ検索
    
- 管理者は Exchange 管理センター (EAC) を使用して、音声メッセージング サービスの相互運用性を構成して管理できます。
    
ボイスメール機能の詳細については、「 [Exchange Online のボイスメール](https://go.microsoft.com/fwlink/p/?LinkId=271798)」を参照してください。
  
> [!IMPORTANT]
> 自動音声認識 (ASR) 機能は、音声コマンドを使用したメニュー ナビゲーションまたは Outlook Voice Access ユーザーや自動応答の発信者のディレクトリ検索では使用できません。 
>
> お客様は、VoIP ゲートウェイと PBX、IP PBX、または Skype for Business Server 2015 を使用して、公衆交換電話網 (PSTN) からテレフォニー接続を提供する必要があります。 
>
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> ホストボイスメールは、Exchange Online プラン2および Office 365 Enterprise E3 サブスクライバーに対してのみ使用できます。 
  
## <a name="third-party-voice-mail-interoperability"></a>サードパーティ ボイス メールの相互運用性

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Skype for Business 統合

スタンドアロン サービスとして、または Microsoft Office 365 の一部として、Skype for Business Online を購入することができます。 オンプレミスの Skype for Business 2015 もサポートされます。 Skype for business Online の詳細については、「 [skype For Business online サービスの説明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

