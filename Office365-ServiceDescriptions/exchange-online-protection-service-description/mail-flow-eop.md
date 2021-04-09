---
title: Exchange Online Protection のメール フロー
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: この記事では、EOP (電子メール保護) のメール フロー Microsoft Exchange Onlineを参照してください。
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653139"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Exchange Online Protection のメール フロー

Microsoft を使用するほとんどの組織では、メールボックスをホストし、メール フローの処理を行います。 これは最も簡単な構成であり、Microsoft がすべてのメールボックスとフィルター処理を管理します。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、クラウドでウイルス対策およびスパム対策メール処理を実行できます。 詳細について、および EOP を購入するには、[Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection) にアクセスしてください。
  
ドメイン管理またはディレクトリ ベースのエッジ ブロック (DBEB) に関する情報をお探しですか? 「 [受信者、ドメイン、および会社の管理」を参照してください](recipient-domain-and-company-management.md)。 すべての EOP 機能の詳細については [、「Exchange Online Protection サービスの説明」を参照してください](exchange-online-protection-service-description.md)。
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Microsoft と独自の電子メール サーバー間の電子メールのルーティング

コネクタを構成して、Microsoft (Exchange Online または EOP を含む) と Exchange などの SMTP ベースの電子メール サーバーとの間のメール フローを有効にできます。 この詳細については、「コネクタ [が必要か」を参照してください](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)。 Microsoft [と独自のメール サーバー間でメールをルーティングするコネクタを設定します](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

EOP のお客様として、Microsoft コネクタを使用して、信頼できるパートナーとセキュリティで保護されたメール フローを設定できます。 Microsoft はトランスポート層セキュリティ (TLS) によるセキュリティで保護された通信をサポートし、TLS 経由で暗号化を適用するためのコネクタを作成できます。 [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。 コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。 パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[パートナー組織とのセキュリティで保護されたメール フロー用のコネクタを設定する](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)」をご覧ください。
  
## <a name="safe-listing-a-partners-ip-address"></a>パートナーの IP アドレスのセーフ リスト

信頼できるパートナーの IP アドレスをセーフ リストに追加して、そこから自分宛てに送信されるメッセージにスパム フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。詳細については、「[接続フィルター ポリシーを構成する](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy)」を参照してください。
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング

条件に基づいてメールを特定のサイトにルーティングするためのトランスポート ルールを使ってコネクタを構成できます。詳しくは、「[Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)」をご覧ください。
  
## <a name="hybrid-mail-routing"></a>ハイブリッド メール ルーティング

ハイブリッドとは、メールボックスの一部は社内でホストし、一部はクラウド (Exchange Online) でホストすることを意味します。(オンプレミスの) スタンドアロン展開からハイブリッド展開に移行できます。
  
ハイブリッド展開を使用している場合は、EOP を使用してクラウド メールボックスと社内メールボックスを保護できます。社内メールボックスを EOP で保護する場合はスタンドアロン ライセンスが必要です。ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](/exchange/transport-routing)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](/exchange/exchange-deployment-assistant)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online Protection サービスの説明」 [を参照してください](exchange-online-protection-service-description.md)。