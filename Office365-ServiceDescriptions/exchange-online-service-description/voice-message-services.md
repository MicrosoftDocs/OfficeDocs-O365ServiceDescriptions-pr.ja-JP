---
title: 音声メッセージ サービス
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 23cc82d51d1afcbd2662e86dd6bc2aeebfb22346
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652681"
---
# <a name="voice-message-services"></a>音声メッセージ サービス

## <a name="voice-mail"></a>ボイス メール

Microsoft Exchange Online は、以下の機能を提供するホスト型のボイス メール サービスを提供します。
  
- 通話応答 (ボイス メール)
    
- Exchange へのダイヤルイン ユーザー インターフェイス (Outlook Voice Access)
    
- 発信者用ダイヤルイン インターフェイス (自動応答)
    
ホスト型の音声メッセージ サービスにより、会社はオンプレミスの電話システムを Exchange Online が提供するボイス メール サービスに接続できます。ボイス メール メッセージは録音され、Exchange Online インフラストラクチャに格納されます。このため、ユーザーは Outlook、Outlook on the web、または携帯電話から音声メッセージにアクセスできます。Exchange Online に対するすべてのテレフォニー接続には、ボイス オーバー IP (VoIP) プロトコルが必要です。管理者は、VoIP メディア ゲートウェイおよびセッション ボーダー コントローラー (SBC) を使用することにより、オンプレミスの IP PBX または PBX 電話システムを Exchange Online に接続できます。カスタマーが IP PBX を展開済みである場合、または PBX が VoIP を直接サポートし、Exchange 音声メッセージング サービスと相互運用可能である場合、VoIP メディア ゲートウェイは必要ありません。SBC は、オンプレミスのテレフォニー ネットワークに接続するためにカスタマーのネットワークの境界に展開され、盗聴および侵入から通信 (とカスタマーのネットワーク) をセキュリティで保護します。Microsoft Lync Server 2010 および 2013 の音声機能との相互運用性もサポートされます。
  
Exchange Online で使用可能な音声メッセージング サービス機能は、オンプレミスの Exchange Server 2016 で提供される音声メッセージング サービス機能とよく似たものであり、次の機能が含まれます。
  
- Outlook および Outlook on the web から電話で再生する
    
- 不在着信通知
    
- 発信者番号通知 (グローバル アドレス一覧、ユーザーの個人用連絡先、カスタム連絡先フォルダー、および外部ソーシャル ネットワークの連絡先の情報を使用)
    
- Outlook on the web および Outlook からボイス メール PIN をリセットする (「[ボイス メール PIN のリセット](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)」を参照してください)。
    
- メッセージ待機インジケーター (詳細については「[Exchange Online の MWI](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)」を参照してください)。 
    
- 通話応答ルール (詳細については、「 [ボイス メール ユーザーによる通話の転送を許可する」を](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 参照)。
    
- Exchange Online で保護されたボイス メール (詳細については [、「Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) でボイス メールを保護する」を参照してください)。
    
- ボイス メール プレビュー (サポートされている言語の [一覧については](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) 、「ユーザーにボイス メールトランスクリプトの表示を許可する」を参照してください)。
    
- 電子メール、ボイス メール、連絡先、個人用連絡先、および個人用連絡先グループへの音声アクセス
    
- Outlook Voice Access または自動応答からのディレクトリ検索
    
- 管理者は Exchange 管理センター (EAC) を使用して、音声メッセージング サービスの相互運用性を構成して管理できます。
    
ボイス メール機能の詳細については [、「Exchange Online のボイス メール」を参照してください](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)。
  
> [!IMPORTANT]
> 自動音声認識 (ASR) 機能は、音声コマンドを使用したメニュー ナビゲーションまたは Outlook Voice Access ユーザーや自動応答の発信者のディレクトリ検索では使用できません。 
>
> 顧客は、VoIP ゲートウェイと PBX、IP PBX、または Skype for Business Server 2015 を使用して、公衆交換電話網 (PSTN) からのテレフォニー接続を提供する必要があります。 
>
> カスタマーは、社内 SBC ハードウェア デバイスを用意し、オンライン ボイス メール サービスに接続するように SBC を構成する必要があります。これには、証明書とパブリックおよびプライベート IP インターフェイスを使用し、社内ファイアウォール経由による正しい TCP ポートを有効にすることによる、適切なレベルのセキュリティを構成することが含まれます。 
>
> ホストされたボイス メールは、Exchange Online プラン 2 および 365 Enterprise E3 サブスクライバー Officeでのみ使用できます。 
  
## <a name="third-party-voice-mail-interoperability"></a>サードパーティ ボイス メールの相互運用性

サードパーティ プロバイダーによる社内ボイス メール ソリューションは、音声メッセージを SMTP 経由で転送可能であるか、Microsoft Exchange Web サービスをサポートすれば、Exchange Online と相互運用できます。ボイス メール システムが SMTP 経由での音声メッセージの転送をネイティブでサポートしない場合、電子メール サーバーを社内に配置したままボイス メール システムからメッセージを受信し、SMTP を使用してクラウドに転送できます。サードパーティ ボイス メール システムの多くが、高度な UM 機能を使用するために MAPI/CDO を使用して Exchange Server と相互運用するため、Exchange Online との相互運用に SMTP を使用する場合には、これらのシステムの全機能は使用できないことがあります。
  
> [!NOTE]
> Exchange Online UM では、カスタマーが運用する SBC からの直接接続によるサード パーティの PBX システムのサポートを、2018 年 7 月で終了します。詳細については、「[Exchange Online ユニファイド メッセージングでのセッション ボーダー コントローラーのサポート終了](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117)」を参照してください。 
  
## <a name="skype-for-business-integration"></a>Skype for Business 統合

スタンドアロン サービスとして、または Microsoft Office 365 の一部として、Skype for Business Online を購入することができます。 オンプレミスの Skype for Business 2015 もサポートされます。 Skype for Business Online の詳細については、「Skype for Business Online サービスの説明 [」を参照してください](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。
