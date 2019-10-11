---
title: メール フロー
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: Office 365 を使用しているほとんどの組織では、メールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。 以下に、こうしたオプションについて記します。
ms.openlocfilehash: bf16ff4034333a2bd85ba798e9c02c621b4d7cfc
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442602"
---
# <a name="mail-flow"></a>メール フロー

Office 365 を使用しているほとんどの組織では、メールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。 以下に、こうしたオプションについて記します。 
  
## <a name="custom-routing-of-outbound-email"></a>送信電子メールのカスタム ルーティング

Microsoft Exchange Online は、社内サーバーまたはホステッド サービス (「スマート ホスティング」と呼ぶ) を通じて、組織からのメール フローをルーティングできます。この機能により組織は、データ損失防止 (DLP) アプライアンスを使用したり、送信電子メールのカスタムの事後処理を実行したり、プライベート ネットワーク経由でビジネス パートナーに電子メールを送信できます。Exchange Online はアドレス書き換えもサポートします。アドレス書き換え機能により、送信電子メールはアドレスを変更するオンプレミス ゲートウェイを通るようにルーティングされます。この機能により組織は、サブドメインを非公開にしたり、マルチドメイン組織からの電子メールを単一ドメインのように見せかけたり、パートナーからの中継電子メールを組織内部から送信されたように見せかけられます。管理者は、Exchange 管理センター (EAC) でカスタム電子メール ルーティングを構成します。
  
詳細については、「[Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)」を参照してください。
  
> [!IMPORTANT]
> Exchange Online は、組織との間を流れるメールを配信できます。 受信者のドメインが、Exchange Online Protection をポイントする DNS MX レコードと共に Exchange Online でホストされている場合、テナントから受信者へのメールフローはインターネット経由で転送されません。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Exchange Online のお客様は、Office 365 コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメール フローを設定することができます。 Office 365 は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートします。 [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections)は、インターネット上での通信のセキュリティを提供する暗号化プロトコルです。 コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。 パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)」を参照してください。
  
> [!IMPORTANT]
> CA 検証の証明書が必要な場合があります。 
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング

コネクタとトランスポート ルールを使用して特定のサイトにメールをルーティングできます。条件に基づいたルーティングでは、特定の条件に基づいてコネクタを選択できます。
  
詳しくは、「[Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)」を参照してください。
  
## <a name="incoming-mail-safe-list"></a>受信メールのセーフ リスト

信頼できるパートナーの IP アドレスをセーフ リストに追加して、自分宛てにパートナーから送信されるメッセージにスパム対策フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。
  
詳細については、「[Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)」を参照してください。
  
## <a name="hybrid-email-routing"></a>ハイブリッド電子メール ルーティング

ハイブリッド展開によって、充実した機能の利用、および既存の社内 Microsoft Exchange 組織に対する管理制御をクラウドにまで展開することができます。ハイブリッド トランスポートでは、いずれかの組織の受信者間で送信されたメッセージは、認証、暗号化され、トランスポート層セキュリティ (TLS) を使用して転送され、トランスポート ルール、ジャーナリング、およびスパム対策ポリシーといった Exchange コンポーネントに対して「内部」として表示されます。ハイブリッド トランスポートは、Exchange Server のハイブリッド構成ウィザードを使用して構成します。
  
ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>社内ルーティング制御を使った共有アドレス スペース (MX が社内を指定)

オンプレミスルーティングコントロール (オンプレミスへの MX ポイント) を使用した共有アドレススペースは、Exchange Online と部分的にオンプレミスの両方にホストされ、受信および送信インターネットメールフローが一部である、ハイブリッド展開のメールルーティングシナリオです。は、オンプレミスの Exchange 組織を経由してルーティングされます。 このシナリオは、メールトランスポートの集中管理とも呼ばれます。 このシナリオでは、Exchange Online は EOP を使用してプロビジョニングされ、受信インターネットメールは、EOP にルーティングされる前にオンプレミスのメールサーバーにルーティングされ、最終的に Exchange Online でホストされるメールボックスにルーティングされます。 さらに、Exchange Online メールボックスからの送信メールは、外部の受信者に送信されたメッセージの社内 Exchange 組織を経由してルーティングされます。 この構成では、オンプレミスの Exchange 組織と Exchange Online 組織の両方のすべてのメールボックスに対して、単一の SMTP ドメイン名前空間を使用できます。 
  
ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](https://go.microsoft.com/fwlink/p/?LinkID=271758)」を参照してください。
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>社内ルーティング制御を使わない共有アドレス スペース (MX が EOP を指定)

社内ルーティング制御を使わない共有アドレス スペース (MX が EOP を指定) はハイブリッド展開メールルーティング シナリオで、メールボックスの一部が Exchange Online を使用したクラウド、残りが社内でホストされます。MX レコードは EOP をポイントします。Office 365 サービスを使用して組織の一部のメールボックスをホストし、EOP を使用して社内メールボックスとクラウド メールボックスの両方を保護する場合、このシナリオが適しています。このシナリオでは、組織内の受信者に送信されたメールは最初に EOP を経由してルーティングされます。EOP でスパムおよびポリシーのフィルタリングが行われ、その後、社内メールボックスおよびクラウド メールボックスに転送されます。 
  
ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](https://go.microsoft.com/fwlink/p/?LinkID=271758)」を参照してください。
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>ハイブリッド構成ウィザードでの展開のトラブルシューティング

ハイブリッド構成ウィザードを使用して Microsoft Exchange Server でハイブリッド展開を構成すると、ハイブリッド展開で問題が発生する可能性が大幅に低下します。ただし構成を誤った場合、ハイブリッド構成ウィザードの範囲外に、ハイブリッド展開で問題が発生する可能性がある一般的な領域がいくつかあります。このような領域には、クライアント アクセス サーバーの適切な構成、および証明書の適切なインストールと構成があります。
  
ハイブリッド構成ウィザードによる展開のトラブルシューティングの詳細については、「[ハイブリッド展開のトラブルシューティング](https://go.microsoft.com/fwlink/p/?LinkId=271040)」を参照してください。
  
### <a name="managing-a-hybrid-configuration"></a>ハイブリッド構成の管理

ハイブリッド構成ウィザードで設定を変更することにより、既存のハイブリッド構成を変更できます。シナリオには、集中型トランスポートを無効にするシナリオ、またはセキュリティで保護されたメール トランスポートを無効にするシナリオがあります。
  
ハイブリッド展開の構成の管理の詳細については、「[ハイブリッド展開の管理](https://go.microsoft.com/fwlink/p/?LinkId=271044)」を参照してください。
  
### <a name="hybrid-deployment-requirements"></a>ハイブリッド展開の要件

ハイブリッド展開の前提条件の詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/p/?LinkId=271759)」を参照してください。
  
> [!IMPORTANT]
> 一部のハイブリッド構成では、社内メールボックス用に Exchange Online Protection ライセンスの購入が必要となる場合があります。 
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  