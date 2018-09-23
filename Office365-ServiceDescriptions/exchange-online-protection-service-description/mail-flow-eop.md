---
title: メール フロー [EOP]
ms.author: pebaum
author: pebaum
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
description: Office 365 を使用するほとんどの組織は、メールボックスをホストし、メール フローを処理します。それは最も単純な構成であり、Office 365 がすべてのメールボックスを管理することを意味し、フィルタ リングします。ただし、一部の組織では、社内のすべてのメールボックスを保持する必要があるビジネスがあります。Exchange オンライン保護 (EOP) を行うことができますし、クラウドで処理するメールのウイルス対策とスパム対策を提供します。詳細については、EOP を購入するのには、Exchange のオンライン保護に移動します。
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036229"
---
# <a name="mail-floweop"></a>メール フロー [EOP]

Office 365 を使用するほとんどの組織は、メールボックスをホストし、メール フローを処理します。それは最も単純な構成であり、Office 365 がすべてのメールボックスを管理することを意味し、フィルタ リングします。ただし、一部の組織では、社内のすべてのメールボックスを保持する必要があるビジネスがあります。Exchange オンライン保護 (EOP) を行うことができますし、クラウドで処理するメールのウイルス対策とスパム対策を提供します。詳細については、EOP を購入するのには、 [Exchange のオンライン保護](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)に移動します。
  
ドメイン管理や、ディレクトリ ベースのエッジ ブロック (DBEB) に関する詳細情報は、「[受信者、ドメイン、および会社の管理](recipient-domain-and-company-management.md)」を参照してください。EOP のすべての機能についての詳細は、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Office 365 とご使用の電子メール サーバー間で電子メールをルーティングする
<a name="BKMK_outboundmailrouting"> </a>

Office 365 (Exchange Online または EOP を含む) と SMTP ベースの電子メール サーバー (Exchange など) の間でメール フローを有効にするようにコネクタを構成できます。詳細については、「[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)?」および「[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)」をご覧ください。
  
## <a name="secure-messaging-with-a-trusted-partner"></a>信頼できるパートナーとのセキュリティで保護されたメッセージング
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

EOP のお客様は、Office 365 コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメール フローを設定することができます。Office 365 は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートします。コネクタを作成して、TLS による暗号化を適用することができます。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。 
  
詳細については、「[パートナー組織とのセキュリティで保護されたメール フロー用のコネクタを設定する](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)」をご覧ください。
  
## <a name="safe-listing-a-partners-ip-address"></a>パートナーの IP アドレスのセーフ リスト
<a name="BKMK_safelistingapartnersipaddress"> </a>

信頼できるパートナーの IP アドレスをセーフ リストに追加して、そこから自分宛てに送信されるメッセージにスパム フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。詳細については、「[接続フィルター ポリシーを構成する](https://go.microsoft.com/fwlink/p/?LinkID=287108)」を参照してください。
  
## <a name="conditional-mail-routing"></a>条件付きメール ルーティング
<a name="BKMK_conditionalmailrouting"> </a>

条件に基づいてメールを特定のサイトにルーティングするためのトランスポート ルールを使ってコネクタを構成できます。詳しくは、「[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)」をご覧ください。
  
## <a name="hybrid-mail-routing"></a>ハイブリッド メール ルーティング
<a name="BKMK_hybridmailrouting"> </a>

ハイブリッドとは、メールボックスの一部は社内でホストし、一部はクラウド (Exchange Online) でホストすることを意味します。(オンプレミスの) スタンドアロン展開からハイブリッド展開に移行できます。
  
ハイブリッド展開を使用している場合は、EOP を使用してクラウド メールボックスと社内メールボックスを保護できます。社内メールボックスを EOP で保護する場合はスタンドアロン ライセンスが必要です。ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。
  
「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。 
  
## <a name="feature-availability"></a>機能の可用性
<a name="BKMK_hybridmailrouting"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  

