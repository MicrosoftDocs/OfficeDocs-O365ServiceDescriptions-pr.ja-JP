---
title: 相互運用性、接続、および互換性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776798"
---
# <a name="interoperability-connectivity-and-compatibility"></a>相互運用性、接続、および互換性

## <a name="interoperability-with-other-microsoft-products"></a>他のマイクロソフト製品との相互運用性

### <a name="skype-for-business-online"></a>Skype for Business Online

内部設置型の Microsoft Lync Server 2010、Lync Server 2013、または Microsoft Office Communications Server 2007 R2 を導入されているお客様の場合は、不在時の自動応答メッセージや予定表のデータにアクセスするために、Exchange Web Service を使用することで、Microsoft Office Communicator と Microsoft Exchange Online を接続できます。
  
内部設置型の Lync Server 2010 と Lync Server 2013 は、次の 2 つの方法でも Exchange Online と相互運用できます。
  
- Outlook Web App での IM とプレゼンスの相互運用性
    
- ボイス メールの相互運用性
    
Exchange Online を使用するように Skype for Business Server 2015 を設定する方法の詳細については、「[オンプレミスの Skype for Business Server 2015 と Exchange Online の間での統合の構成](https://go.microsoft.com/fwlink/p/?LinkId=271804)」を参照してください。ハイブリッド構成については、「[Skype for Business Server 2015 でサポートされるハイブリッド構成](https://go.microsoft.com/fwlink/?LinkID=513084)」を参照してください。
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Microsoft SharePoint Server または SharePoint Online を Office 365 加入プランの一部として展開されているお客様は、SharePoint を Exchange Online に接続して統合サービスを実現できます。
  
SharePoint を Exchange Online に接続する方法の詳細については、「[他の Office 365 サービスを設定している場合に、カスタム ドメイン名を使用して Office 365 の一般向け Web サイトの名前を変更する](https://go.microsoft.com/fwlink/?LinkId=271805)」を参照してください。
  
## <a name="features-for-external-connectivity"></a>外部接続のための機能

Exchange Online は、外部のアプリケーションおよびデバイスと接続するために次の機能を提供しています。
  
- **MAPI over HTTP、SMTP、POP3、IMAP4、Exchange Web サービスなどのメッセージング プロトコルを使用** 社内、Azure、または他のホステッド サービスで動作している外部アプリケーションは、MAPI over HTTP、SMTP、POP3、IMAPv4 などのメッセージング プロトコルを使用して、Exchange Online によって保存されたデータにアクセスすることができます。アプリケーション開発には、Exchange Web Service または Exchange Web Service マネージ API を使用することをお勧めします。 
    
- **SMTP リレーとして** Exchange Online は、ファックス ゲートウェイ、ネットワーク アプライアンス、およびカスタム アプリケーションから送信された電子メール メッセージを中継する SMTP 配信サービスとして設定できます。 
    
### <a name="exchange-web-services"></a>Exchange Web サービス

Exchange Web Service (EWS) は、Exchange Server および Exchange Online 用に推奨される開発 API です。管理者は EWS または EWS マネージ API を使用して、社内、Azure、またはその他のホステッド サービスで実行されているアプリケーションから Exchange Online によって格納されたデータにアクセスできます。EWS によって、管理者は、メールボックスのコンテンツのクエリ、カレンダー イベントの登録、タスクの作成、電子メール メッセージの内容に基づく特定のアクションのトリガーなど特化したアクションを実行できます。Exchange Online では、顧客アカウントにアプリケーションのアクセス許可を付与することで EWS 機能を有効にできます。これらのアクセス許可によって、顧客のアプリケーションは、アプリケーション メールボックスにアクセスし、コンテンツを追加できます。Exchange の偽装は、アプリケーションのアクセス許可を付与するために使用する方法の 1 つです。Exchange Web Service と Exchange Online を併用する方法の詳細については、Exchange Online デベロッパー センターの技術情報を参照してください。
  
### <a name="smtp-relay"></a>SMTP リレー

Exchange Online は、ファックス ゲートウェイ、ネットワーク アプライアンス、およびカスタム アプリケーションから送信された電子メール メッセージを中継する SMTP 配信サービスとして設定できます。たとえば、基幹業務アプリケーションが電子メール アラートをユーザーに送信する場合に、Exchange Online をメール配信システムとして使用するように設定できます。アプリケーションまたはサービスは、有効なライセンスが付与された Exchange Online メールボックスのユーザー名とパスワードで認証を行い、トランスポート層セキュリティ (TLS) を使用して接続する必要があります。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

