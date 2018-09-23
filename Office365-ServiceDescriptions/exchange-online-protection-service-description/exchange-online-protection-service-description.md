---
title: Exchange Online Protection サービスの説明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection の機能と要件に関する情報を取得します。Exchange Online Protection を提供するプランの一覧、およびこれらのプラン間での機能の比較が含まれています。
ms.openlocfilehash: 6e7ffd6a2248acfc763a71e35ce0daba0f9b0308
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036299"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection サービスの説明

Exchange Online Protection の機能と要件に関する情報を取得します。Exchange Online Protection を提供するプランの一覧、およびこれらのプラン間での機能の比較が含まれています。
  
マイクロソフト Exchange Online Protection (EOP) は、クラウドベースの電子メール フィルタリング サービスであり、スパムやマルウェアから組織を保護するのに役立ち、メッセージング ポリシー違反から組織を保護する機能が含まれています。EOP はメッセージング環境の管理を簡素化し、社内のハードウェアおよびソフトウェアの維持に伴う負荷の多くを軽減します。
  
メッセージング保護に EOP を使用できる基本的な方法として、次のようなものがあります。
  
- **スタンドアロンのシナリオ**EOP は、クラウド ベースの電子メールの保護、オンプレミスの Exchange Server 2013 環境、従来の Exchange Server のバージョンでは、またはその他の設置型の SMTP メール ・ ソリューションを提供します。 
    
- **Microsoft Exchange Online の一部として** 既定で、EOP は Exchange Online クラウド ホスト型メールボックスを保護します。Exchange Online の詳細については、「 [Exchange Online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」をご覧ください。
    
- **ハイブリッド展開で** EOP はメッセージング環境を保護し、社内メールボックスとクラウド メールボックスが混在している場合のメール ルーティングを制御するように構成できます。 
    
各プランの機能を比較するには、「[プランを選ぶ](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」をご覧ください。
  
Exchange Online Protection を購入するには、「[Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)」をご覧ください。
  
Office 365 サービスの説明のページは、エクスポート、保存、印刷が可能です。[複数のページをエクスポート](https://go.microsoft.com/fwlink/?LinkId=403349)する方法について説明します。
  
> [!IMPORTANT]
> EOP は Forefront Online Protection for Exchange (FOPE) に取って代わります。すべての FOPE のお客様が EOP に移行することになります。EOP には、FOPE で提供されていた保護と制御に加え、追加の機能も含まれています。FOPE から EOP への移行の詳細については、「[Forefront Online Protection for Exchange (FOPE) 移行センター](http://www.movetoeop.com)」をご覧ください。 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の新機能

EOP の新機能の詳細については、「[Exchange Online Protection の概要](https://go.microsoft.com/fwlink/p/?LinkId=320390)」をご覧ください。FOPE と EOP の機能比較については、「[FOPE と EOP の機能比較](https://go.microsoft.com/fwlink/p/?LinkId=320391)」をご覧ください。
  
## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) のプラン

EOP は以下のサブスクリプション プランで提供されています。
  
|**プラン**|**説明**|
|:-----|:-----|
|[Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |EOP が社内のメールボックスを保護します。  <br/> |
|[Exchange Online プランの比較](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |EOP が Exchange Online クラウド ホスト型メールボックスを保護します。  <br/> |
|[Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |EOP スタンドアロンと同様に EOP が社内のメールボックスを保護します。さらに、データ損失防止 (DLP) と Web サービスを使用したレポート機能を備えています。  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services の機能

Microsoft Exchange Enterprise CAL with Services は、社内メッセージング環境用の EOP の電子メール保護機能に加えて、以下の機能を提供します。
  
- [データ損失防止 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)
    
Exchange Enterprise CAL with Services のライセンスの詳細については、「[Exchange Server 2013 のライセンス](https://go.microsoft.com/fwlink/p/?LinkId=293699)」をご覧ください。
  
Exchange Enterprise CAL with Services のライセンスを所有しており、サービスをプロビジョニングする場合は、「[EOP サービスを設定する](https://go.microsoft.com/fwlink/p/?LinkId=320397)」内の手順に従ってください。セットアップ手順は EOP スタンドアロンのセットアップ手順と同じです。
  
> [!NOTE]
> Exchange Enterprise CAL with Services の新機能は Exchange Online と同時に展開され、EOP スタンドアロンと同時には展開されません。EOP スタンドアロンと Exchange Online/Exchange Enterprise CAL with Services の展開スケジュールは、多少異なる場合があります。 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の要件

EOP は、Microsoft Exchange Server 2013 などの SMTP メール転送エージェントと一緒に使用できます。EOP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。
  
## <a name="limits"></a>制限

EOP の制限については、「[Exchange Online Protection の制限](exchange-online-protection-limits.md)」を参照してください。
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) の各プランで利用できる機能

各機能を以下に列挙します。EOP 機能の詳細については、表内のリンクをクリックしてください。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。
  
|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**EOP スタンドアロン** <br/> |**Exchange Online の EOP 機能** <br/> |**Exchange Enterprise CAL (サービス付き)** <br/> |
|[メールの受信者](recipient-domain-and-company-management.md#mail-recipients) <br/> |<sup>1</sup>を [はい] します。 <br/> |<sup>1</sup>を [はい] します。 <br/> |はい  <br/> |
|[管理役割グループのアクセス許可](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |<sup>2</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |
|[ドメインの管理](recipient-domain-and-company-management.md#domain-management) <br/> |<sup>3</sup>を [はい] します。 <br/> |<sup>3</sup>を [はい] します。 <br/> |<sup>3</sup>を [はい] します。 <br/> |
|[一致サブドメイン](recipient-domain-and-company-management.md#match-subdomains) <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[ディレクトリ ベースのエッジ ブロック (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[トランスポート ルール](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |はい<sup>3、4、14</sup> <br/> |はい<sup>3、4、14</sup> <br/> |はい  <br/> |
|[監査ログ](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |<sup>5</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |
|[データ損失防止 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |いいえ  <br/> |はい  <br/> |<sup>6</sup>を [はい] します。 <br/> |
|[Office 365 Message Encryption](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |<sup>12</sup>を [はい] します。 <br/> |はい  <br/> |<sup>12</sup>を [はい] します。 <br/> |
|[スパム対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (組み込み)  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[スパム対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |<sup>7</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |
|[マルウェア対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (組み込み)  <br/> |<sup>13</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |
|[マルウェア対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): 管理者による管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): エンドユーザーによる自己管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[Microsoft Office Outlook 用迷惑メール報告アドイン](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[Outlook Web App での迷惑メール報告](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |<sup>8</sup>を [はい] します。 <br/> |なし<sup>8</sup> <br/> |なし<sup>8</sup> <br/> |
|[Office 365 とご使用の電子メール サーバー間で電子メールをルーティングする](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[信頼できるパートナーとのセキュリティで保護されたメッセージング](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[パートナーの IP アドレスのセーフ リスト](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[条件付きメール ルーティング](mail-flow-eop.md#conditional-mail-routing) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[ハイブリッド メール ルーティング](mail-flow-eop.md#hybrid-mail-routing) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[Office 365 管理センターのレポート](reporting-and-message-trace.md#office-365-admin-center-reports) <br/> |<sup>9</sup>を [はい] します。 <br/> |<sup>10</sup>を [はい] します。 <br/> |はい <sup>9、10</sup> <br/> |
|[Excel 形式でダウンロードするアプリケーション レポート](reporting-and-message-trace.md#excel-download-application-reports) <br/> |はい  <br/> |はい  <br/> |<sup>11</sup>を [はい] します。 <br/> |
|[Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |
|[メッセージの追跡](reporting-and-message-trace.md#message-trace) <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |はい  <br/> |
|[Office 365 管理センターへのアクセス](administration-and-management-eop.md#access-to-the-office-365-admin-center) <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[Exchange 管理センターへのアクセス](administration-and-management-eop.md#access-to-the-exchange-admin-center) (EAC)  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|[リモート Windows PowerShell へのアクセス](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |<sup>2</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |
   
> [!NOTE]
> <sup>1</sup>メール ユーザーは、「メールボックス」として定義されてと、外部メール連絡先および追加、削除され、それ以外の場合、Exchange 管理センター (EAC) で直接管理できます。 <br/><sup>2</sup>いいえ RBAC のカスタマイズ。管理者ロールの場合のみです。 <br/> <sup>3</sup>マネージ ドメインを参照できるため、ドメインの種類は、EAC で編集できます。Office 365 の管理センターでは、他のすべてのドメインの管理を行う必要があります。 <br/><sup>4</sup>使用可能な柔軟な条件とアクションは、EOP と Exchange のオンラインの間で異なります。使用可能な基準と EOP 内のアクションのリストは、[トランスポート ルールの条件](https://go.microsoft.com/fwlink/p/?LinkId=320392)および[トランスポート ルールのアクション](https://go.microsoft.com/fwlink/p/?LinkId=320393)を参照してください。使用可能な基準と Exchange のオンラインでのアクションのリストは、[トランスポート ルールの条件](https://go.microsoft.com/fwlink/p/?LinkId=320394)および[トランスポート ルールのアクション](https://go.microsoft.com/fwlink/p/?LinkId=320395)を参照してください。 <br/><sup>5</sup> EOP の監査レポートは、メールボックスに関する情報を除外する Exchange Online の監査レポートのサブセットです。 <br/> <sup>6</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。<br/><sup>7</sup>コンテンツ フィルターの既定の動作は、迷惑メール メッセージを受信者の迷惑メール フォルダーに移動するのには。そのためには、オンプレミスのメールボックスを持つ、EOP によって追加された迷惑メールのヘッダーを検出するために、オンプレミスのサーバーに 2 つの Exchange トランスポート ルールを構成することもする必要があります。詳細については、[迷惑メールを各ユーザーの [迷惑メール] フォルダーにルーティングされるようにする](https://go.microsoft.com/fwlink/p/?LinkId=320396)を参照してください。 <br/><sup>8</sup>この機能は、メールボックスの EOP、フィルター処理があり、直ちに Exchange オンラインのお客様に利用可能な Exchange Server 2013 の Service Pack 1 (SP1) のお客様に利用可能です。 <br/><sup>9</sup> EOP のレポートは、メールボックスに関する情報を除外する Exchange Online のレポートのサブセットです。 <br/><sup>10</sup>は、DLP を報告します。 <br/><sup>11</sup>お客様のサービスと Exchange のエンタープライズ CAL は、 **Exchange のオンライン保護**サービスではなく、 **Exchange のオンライン**サービスを選択することによって、ブックをインストールする必要があります。 <br/><sup>12</sup> Azure 情報の保護を購入し、Exchange のオンライン保護を使用して、Exchange のオンラインを介して電子メールをルーティングするオンプレミス ユーザーのサポートがされています。 <br/> <sup>13</sup>が、受信および送信メッセージをスキャンしますが、組織内の受信者に、組織内の送信者から送信された内部のメッセージをスキャンしません。 <br/><sup>14</sup>使用可能な述語とアクションは、EOP と Exchange のオンラインの間で異なります。 <br/> <sup>15</sup>ハイブリッド設定ハイブリッド ウィザードを通じて利用できるがないこと手動で設定する Exchange SP1 がある場合。 