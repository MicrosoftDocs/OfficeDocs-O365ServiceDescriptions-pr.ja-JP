---
title: メールフロー [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。 これは最も簡単な構成で、Microsoft はすべてのメールボックスとフィルター処理を管理します。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、これを行うことができます。また、クラウドでウイルス対策およびスパム対策のメール処理を提供します。
ms.openlocfilehash: d85ae7b22be1405679ceac8d853b345d251166b6
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638926"
---
# <a name="mail-floweop"></a>メールフロー [EOP]

Microsoft を使用するほとんどの組織では、メールボックスをホストし、メールフローを処理します。 これは最も簡単な構成で、Microsoft はすべてのメールボックスとフィルター処理を管理します。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、これを行うことができます。また、クラウドでウイルス対策およびスパム対策のメール処理を提供します。 詳細について、および EOP を購入するには、[Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection) にアクセスしてください。
  
ドメイン管理またはディレクトリベースのエッジブロック (DBEB) に関する情報をお探しですか? 「[受信者、ドメイン、および会社の管理](recipient-domain-and-company-management.md)」を参照してください。 すべての EOP 機能の詳細については、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Microsoft と独自の電子メールサーバーとの間で電子メールをルーティングする

Microsoft (Exchange Online または EOP を含む) と、Exchange などの SMTP ベースの電子メールサーバーとの間でメールフローを有効にするようにコネクタを構成することができます。 詳細については、「[コネクタが必要](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)ですか?」を参照してください。 を使用して、 [Microsoft と独自の電子メールサーバー間でメールをルーティングするようにコネクタを設定](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)します。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

EOP のお客様は、Microsoft コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメールフローを設定することができます。 Microsoft は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートしており、TLS 経由の暗号化を強制するコネクタを作成することができます。 [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections)は、インターネット上での通信のセキュリティを提供する暗号化プロトコルです。 コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。 パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[パートナー組織とのセキュリティで保護されたメール フロー用のコネクタを設定する](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)」をご覧ください。
  
## <a name="safe-listing-a-partners-ip-address"></a>パートナーの IP アドレスのセーフ リスト

信頼できるパートナーの IP アドレスをセーフ リストに追加して、そこから自分宛てに送信されるメッセージにスパム フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。詳細については、「[接続フィルター ポリシーを構成する](https://go.microsoft.com/fwlink/p/?LinkID=287108)」を参照してください。
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング

条件に基づいてメールを特定のサイトにルーティングするためのトランスポート ルールを使ってコネクタを構成できます。詳しくは、「[Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)」をご覧ください。
  
## <a name="hybrid-mail-routing"></a>ハイブリッド メール ルーティング

ハイブリッドとは、メールボックスの一部は社内でホストし、一部はクラウド (Exchange Online) でホストすることを意味します。(オンプレミスの) スタンドアロン展開からハイブリッド展開に移行できます。
  
ハイブリッド展開を使用している場合は、EOP を使用してクラウド メールボックスと社内メールボックスを保護できます。社内メールボックスを EOP で保護する場合はスタンドアロン ライセンスが必要です。ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
