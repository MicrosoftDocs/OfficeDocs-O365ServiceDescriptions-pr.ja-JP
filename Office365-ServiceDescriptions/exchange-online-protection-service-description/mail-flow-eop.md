---
title: メールフロー [EOP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。 これは最も簡単な構成で、Microsoft はすべてのメールボックスとフィルター処理を管理します。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、これを行うことができます。また、クラウドでウイルス対策およびスパム対策のメール処理を提供します。
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132821"
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

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>ハイブリッド メール ルーティング

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
