---
title: メール フロー [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、そのニーズを満たすことができ、クラウドでウィルス対策とスパム対策のメール処理を行えます。 詳細について、および EOP を購入するには、Exchange Online Protection にアクセスしてください。
ms.openlocfilehash: 0e9e5fffaa88b2ec654cb90dc5d432875336328e
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244913"
---
# <a name="mail-floweop"></a>メール フロー [EOP]

Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、そのニーズを満たすことができ、クラウドでウィルス対策とスパム対策のメール処理を行えます。 詳細について、および EOP を購入するには、[Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection) にアクセスしてください。
  
ドメイン管理や、ディレクトリ ベースのエッジ ブロック (DBEB) に関する詳細情報は、「[受信者、ドメイン、および会社の管理](recipient-domain-and-company-management.md)」を参照してください。EOP のすべての機能についての詳細は、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Office 365 とご使用の電子メール サーバー間で電子メールをルーティングする
<a name="BKMK_outboundmailrouting"> </a>

Office 365 (Exchange Online または EOP を含む) と SMTP ベースの電子メール サーバー (Exchange など) の間でメール フローを有効にするようにコネクタを構成できます。詳細については、「[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)?」および「[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)」をご覧ください。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

EOP のお客様は、Office 365 コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメール フローを設定することができます。Office 365 は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートします。コネクタを作成して、TLS による暗号化を適用することができます。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[パートナー組織とのセキュリティで保護されたメール フロー用のコネクタを設定する](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)」をご覧ください。
  
## <a name="safe-listing-a-partners-ip-address"></a>パートナーの IP アドレスのセーフ リスト
<a name="BKMK_safelistingapartnersipaddress"> </a>

信頼できるパートナーの IP アドレスをセーフ リストに追加して、そこから自分宛てに送信されるメッセージにスパム フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。詳細については、「[接続フィルター ポリシーを構成する](https://go.microsoft.com/fwlink/p/?LinkID=287108)」を参照してください。
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング
<a name="BKMK_conditionalmailrouting"> </a>

条件に基づいてメールを特定のサイトにルーティングするためのトランスポート ルールを使ってコネクタを構成できます。詳しくは、「[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)」をご覧ください。
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

ハイブリッドとは、メールボックスの一部は社内でホストし、一部はクラウド (Exchange Online) でホストすることを意味します。(オンプレミスの) スタンドアロン展開からハイブリッド展開に移行できます。
  
ハイブリッド展開を使用している場合は、EOP を使用してクラウド メールボックスと社内メールボックスを保護できます。社内メールボックスを EOP で保護する場合はスタンドアロン ライセンスが必要です。ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
## <a name="feature-availability"></a>機能の可用性
<a name="BKMK_hybridmailrouting"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  

