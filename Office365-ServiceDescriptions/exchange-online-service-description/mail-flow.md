---
title: メール フロー
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: ほとんどの組織では、メールボックスをホストし、メール フローの処理を行います。 これは最も簡単な構成であり、Microsoft がすべてのメールボックスとフィルター処理を管理します。 ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。 以下に、こうしたオプションについて記します。
ms.openlocfilehash: 0fe7cf2f0e8619bce911457ba634bee41ee4e113
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653329"
---
# <a name="mail-flow"></a>メール フロー

ほとんどの組織では、メールボックスをホストし、メール フローの処理を行います。 これは最も簡単な構成であり、Microsoft がすべてのメールボックスとフィルター処理を管理します。 ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。 以下に、こうしたオプションについて記します。 
  
## <a name="custom-routing-of-outbound-email"></a>送信電子メールのカスタム ルーティング

Microsoft Exchange Onlineは、組織からオンプレミス サーバーまたはホストされたサービス ("スマート ホスティング" とも呼ばれる) を経由してメールをルーティングできます。 これにより、組織はデータ損失防止 (DLP) アプライアンスを使用し、送信メールのカスタム後処理を実行し、プライベート ネットワークを通じてビジネス パートナーに電子メールを配信できます。 Exchange Online では、アドレスの変更を行うオンプレミス ゲートウェイを介して送信メールをルーティングするアドレス書き換えもサポートしています。 この機能を使用すると、サブドメインを非表示にしたり、複数ドメイン組織からのメールを単一のドメインとして表示したり、パートナー中継メールを組織内から送信した場合と同様に表示できます。 管理者は、Exchange 管理センター (EAC) 内でカスタム メール ルーティングを構成します。
  
詳細については、「Microsoft と独自の電子メール サーバー間でメールをルーティングするコネクタをセットアップ [する」を参照してください](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)。
  
> [!IMPORTANT]
> Exchange Online は、組織との間を流れるメールを配信できます。 受信者ドメインが Exchange Online Protection を指す DNS MX レコードを使用して Exchange Online でホストされている場合、テナントから受信者へのメール フローはインターネット上を移動されません。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Exchange Online のお客様は、Microsoft コネクタを使用して、信頼できるパートナーとセキュリティで保護されたメール フローを設定できます。 Microsoft はトランスポート層セキュリティ (TLS) によるセキュリティで保護された通信をサポートし、TLS 経由で暗号化を適用するためのコネクタを作成できます。 [TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。 コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。 パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)」を参照してください。
  
> [!IMPORTANT]
> CA 検証の証明書が必要な場合があります。 
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング

コネクタとトランスポート ルールを使用して特定のサイトにメールをルーティングできます。条件に基づいたルーティングでは、特定の条件に基づいてコネクタを選択できます。
  
詳しくは、「[Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)」を参照してください。
  
## <a name="incoming-mail-safe-list"></a>受信メールのセーフ リスト

信頼できるパートナーの IP アドレスをセーフ リストに追加して、自分宛てにパートナーから送信されるメッセージにスパム対策フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。
  
詳細については、「[Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy)」を参照してください。
  
## <a name="hybrid-email-routing"></a>ハイブリッド電子メール ルーティング

ハイブリッド展開によって、充実した機能の利用、および既存の社内 Microsoft Exchange 組織に対する管理制御をクラウドにまで展開することができます。ハイブリッド トランスポートでは、いずれかの組織の受信者間で送信されたメッセージは、認証、暗号化され、トランスポート層セキュリティ (TLS) を使用して転送され、トランスポート ルール、ジャーナリング、およびスパム対策ポリシーといった Exchange コンポーネントに対して「内部」として表示されます。ハイブリッド トランスポートは、Exchange Server のハイブリッド構成ウィザードを使用して構成します。
  
ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](/exchange/transport-routing)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](/exchange/exchange-deployment-assistant)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>社内ルーティング制御を使った共有アドレス スペース (MX が社内を指定)

オンプレミスルーティング制御を使用した共有アドレス空間 (MX Points to On-Premises) は、メールボックスが部分的に Exchange Online でホストされ、部分的にオンプレミスでホストされ、受信および送信インターネット メール フローがオンプレミスの Exchange 組織を介してルーティングされるハイブリッド展開メール ルーティング シナリオです。 このシナリオは、集中メール トランスポートとも呼ばれる。 このシナリオでは、Exchange Online は EOP でプロビジョニングされ、受信インターネット メールは EOP にルーティングされる前にオンプレミスのメール サーバーにルーティングされ、最後に Exchange Online でホストされるメールボックスにルーティングされます。 さらに、Exchange Online メールボックスからの送信メールは、外部受信者に送信されるメッセージに対して、オンプレミスの Exchange 組織を介してルーティングされます。 この構成では、オンプレミスの Exchange 組織と Exchange Online 組織の両方のすべてのメールボックスに対して 1 つの SMTP ドメイン名前空間を使用できます。 
  
ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](/exchange/transport-options)」を参照してください。
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>社内ルーティング制御を使わない共有アドレス スペース (MX が EOP を指定)

オンプレミス ルーティング制御のない共有アドレス空間 (MX Points to EOP) は、Exchange Online と部分的にオンプレミスを使用して、メールボックスがクラウド内で部分的にホストされ、MX レコードが EOP をポイントするハイブリッド メール ルーティング シナリオです。 このシナリオは、Microsoft を使用して組織のメールボックスの一部をホストし、EOP でオンプレミスメールボックスとクラウド メールボックスの両方を保護する場合に適しています。 このシナリオでは、組織内の受信者に送信されるメールは、最初は EOP 経由でルーティングされ、スパムとポリシー のフィルター処理が行われます。その後、オンプレミスのメールボックスとクラウド メールボックスに到達します。 
  
ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](/exchange/transport-options)」を参照してください。
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>ハイブリッド構成ウィザードでの展開のトラブルシューティング

ハイブリッド構成ウィザードを使用して Microsoft Exchange Server でハイブリッド展開を構成すると、ハイブリッド展開で問題が発生する可能性が大幅に低下します。ただし構成を誤った場合、ハイブリッド構成ウィザードの範囲外に、ハイブリッド展開で問題が発生する可能性がある一般的な領域がいくつかあります。このような領域には、クライアント アクセス サーバーの適切な構成、および証明書の適切なインストールと構成があります。
  
ハイブリッド構成ウィザードによる展開のトラブルシューティングの詳細については、「[ハイブリッド展開のトラブルシューティング](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment)」を参照してください。
  
### <a name="managing-a-hybrid-configuration"></a>ハイブリッド構成の管理

ハイブリッド構成ウィザードで設定を変更することにより、既存のハイブリッド構成を変更できます。シナリオには、集中型トランスポートを無効にするシナリオ、またはセキュリティで保護されたメール トランスポートを無効にするシナリオがあります。
  
ハイブリッド展開の構成の管理の詳細については、「[ハイブリッド展開の管理](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150))」を参照してください。
  
### <a name="hybrid-deployment-requirements"></a>ハイブリッド展開の要件

ハイブリッド展開の前提条件の詳細については、「[ハイブリッド展開の前提条件](/exchange/hybrid-deployment-prerequisites)」を参照してください。
  
> [!IMPORTANT]
> 一部のハイブリッド構成では、社内メールボックス用に Exchange Online Protection ライセンスの購入が必要となる場合があります。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。
