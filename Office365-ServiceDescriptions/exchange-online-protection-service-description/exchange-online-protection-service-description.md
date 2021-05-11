---
title: Exchange Online Protection サービスの説明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection の機能と要件に関する情報を取得します。 含まれるプランの一覧は、Exchange Online Protectionプラン全体の機能の比較と同様に提供されます。
ms.openlocfilehash: 172e07db12590e51720c2446974418244f3234e4
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653039"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection サービスの説明

Exchange Online Protection の機能と要件に関する情報を取得します。 含まれるプランの一覧は、Exchange Online Protectionプラン全体の機能の比較と同様に提供されます。

マイクロソフト Exchange Online Protection (EOP) は、クラウドベースの電子メール フィルタリング サービスであり、スパムやマルウェアから組織を保護するのに役立ち、メッセージング ポリシー違反から組織を保護する機能が含まれています。EOP はメッセージング環境の管理を簡素化し、社内のハードウェアおよびソフトウェアの維持に伴う負荷の多くを軽減します。

次の一覧では、メッセージング保護に EOP を使用する主な方法について説明します。

- **スタンドアロン シナリオ:** EOP は、オンプレミスの電子メール環境 (Exchange Serverまたは他のオンプレミス SMTP 電子メール ソリューション) に対してクラウドベースの電子メール保護を提供します。

- **[クラウド ホスト型メールボックスMicrosoft Exchange Online:** 既定では、EOP はクラウドホスト型メールボックスExchange Online保護します。 Exchange Online の詳細については、「[Exchange Online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- **ハイブリッド展開:** EOP を構成して、メッセージング環境を保護し、オンプレミスメールボックスとクラウド メールボックスが混在している場合のメール ルーティングを制御できます。

## <a name="available-plans"></a>使用できるプラン

ユーザーがサブスクリプションを有効にするサブスクリプションの詳細な計画Exchange Online Protection、完全なサブスクリプション比較表[を参照してください](https://go.microsoft.com/fwlink/?linkid=2139145)。

Exchange Online Protection を購入するには、「[Office 365 Advanced Threat Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)」をご覧ください。

> [!NOTE]
> EOP は Forefront Online Protection for Exchange (FOPE) に置き換えました。 すべての FOPE のお客様が EOP に移行されました。

## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の新機能

次[Microsoft 365ロードマップは](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)、今後の新機能に関する情報を見つけ出す優れたリソースです。

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) のプラン

EOP は以下のサブスクリプション プランで提供されています。<br><br>

| プラン | 説明 |
|:-----|:-----|
|[EOP スタンドアロン](https://products.office.com/exchange/exchange-email-security-spam-protection)|オンプレミスの電子メール組織を保護する独立したクラウドベースのサービス。|
|[Exchange Online の EOP 機能](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|クラウドホスト型メールボックスExchange Online組み込みの保護。|
|[Exchange Enterprise CAL (サービス付き)](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|EOP などのクラウドベースの機能を含むオンプレミス Exchange組織用に購入したアドオン ライセンス (詳細については、次のセクションを参照してください)。|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services の機能

Microsoft Exchange Enterprise CAL with Services には、EOP の電子メール保護機能と、次のクラウドベースの追加機能が用意されています。

- [データ損失防止 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)

サービスライセンスを使用した CAL のExchange Enterprise詳細については、「ライセンスに関するよくあるExchange[を参照してください](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

CAL をサービス ライセンスExchange Enterpriseし、EOP をプロビジョニングする場合は、「EOP サービスのセットアップ」の手順[に従います](/microsoft-365/security/office-365-security/set-up-your-eop-service)。 セットアップ手順は EOP スタンドアロンのセットアップ手順と同じです。

> [!NOTE]
> Exchange Enterprise CAL with Services の新機能は Exchange Online と同時に展開され、EOP スタンドアロンと同時には展開されません。EOP スタンドアロンと Exchange Online/Exchange Enterprise CAL with Services の展開スケジュールは、多少異なる場合があります。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の要件

EOP は、SMTP メール転送エージェント (メール転送エージェントなど) とMicrosoft Exchange Server。 EOP でサポートされているオペレーティング システム、Web ブラウザー、および言語の詳細については、Exchange Online Protection の Exchange 管理センターの「サポートされているブラウザー」および「サポートされている言語[」セクションを参照してください](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)。

## <a name="limits"></a>制限

EOP の制限については、「制限[Exchange Online Protection参照してください](exchange-online-protection-limits.md)。

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) の各プランで利用できる機能

各機能を以下に列挙します。EOP 機能の詳細については、表内のリンクをクリックしてください。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。<br><br>

| 機能 | EOP スタンドアロン | Exchange Online の EOP 機能 | Exchange Enterprise CAL (サービス付き)|
|:-----|:-----|:-----|:-----|
|[メールの受信者](recipient-domain-and-company-management.md#mail-recipients)|はい<sup>1</sup>|はい<sup>1</sup>|はい|
|[管理役割グループのアクセス許可](recipient-domain-and-company-management.md#admin-role-group-permissions)|はい<sup>2</sup>|はい|はい|
|[ドメインの管理](recipient-domain-and-company-management.md#domain-management)|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|
|[一致サブドメイン](recipient-domain-and-company-management.md#match-subdomains)|はい|はい|いいえ|
|[ディレクトリ ベースのエッジ ブロック (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|はい|はい|はい|
|[メール フロー ルール](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|はい<sup>4</sup>|は<sup>い 4、6</sup>|はい|
|[監査ログ](messaging-policy-and-compliance-servicedesc.md#audit-logging)|はい<sup>5</sup>|はい|はい|
|[データ損失防止 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|いいえ|はい|はい<sup>6</sup>|
|[Office 365 Message Encryption](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|はい<sup>12</sup>|はい|はい<sup>12</sup>|
|[スパム対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (組み込み)|はい|はい|はい|
|[スパム対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|はい<sup>7</sup>|はい|はい|
|[マルウェア対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (組み込み)|はい<sup>13</sup>|はい|はい|
|[マルウェア対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|はい|はい|はい|
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): 管理者による管理|はい|はい|はい|
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): エンドユーザーによる自己管理|はい|はい|はい|
|[申請](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|いいえ|はい|いいえ|
|[レポート メッセージ アドインのOutlook](/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|はい|はい|はい|
|[Web 上の迷惑Outlookレポート](/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|はい|はい|はい|
|[Microsoft と独自の電子メール サーバー間の電子メールのルーティング](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|はい|はい|はい|
|[信頼できるパートナーとのセキュリティで保護されたメッセージング](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|はい|はい|はい|
|[パートナーの IP アドレスのセーフ リスト](mail-flow-eop.md#safe-listing-a-partners-ip-address)|はい|はい|はい|
|[条件付きメール ルーティング](mail-flow-eop.md#conditional-mail-routing)|はい|はい|はい|
|[ハイブリッド メール ルーティング](mail-flow-eop.md#hybrid-mail-routing)|はい|はい|はい|
|[Microsoft 365管理センター レポート](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |はい<sup>9</sup>|はい<sup>10</sup>|はい <sup>9、10</sup>|
|[Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)|いいえ|はい|はい|
|[メッセージの追跡](reporting-and-message-trace.md#message-trace)|は<sup>い 15</sup>|は<sup>い 15</sup>|はい|
|[管理センターへのMicrosoft 365アクセス](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|はい|はい|はい|
|[管理センターへのExchangeアクセス](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|はい|はい|はい|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|はい|はい|はい|

<sup>1</sup>メール ユーザーは "メールボックス" として定義され、外部メール連絡先と共に、Exchange 管理センター (EAC) で直接追加、削除、および管理できます。 <br/>
<sup>2</sup> RBAC のカスタマイズはありません。 管理者の役割のみ。 <br/>
<sup>3</sup> つの管理対象ドメインを表示し、EAC でドメインの種類を編集できます。 その他のすべてのドメイン管理は、管理センター Microsoft 365する必要があります。<br/>
<sup>EOP の 4</sup>つのメール フロー ルール (トランスポート ルールとも呼ばれる) については、EOP のメール フロー ルール (トランスポート ルール[) で](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)説明Exchange Online Protection。 使用可能なメール フロー ルールの条件、例外、およびアクションは、EOP とサーバー間で少し異Exchange Online。 これらの違いは、メール フロー ルールの条件と例外 (述語[)](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions)の Exchange Online および メール フロー ルール アクションで[Exchange Online。](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)<br/>
<sup>5</sup> EOP 監査レポートは、メールボックスに関する情報をExchange Onlineする監査レポートのサブセットです。 <br/>
<sup>6</sup>つの DLP ポリシー ヒントは、サービスExchange Enterprise CAL では使用できません。  <br/>
<sup>7</sup> 既定のコンテンツ フィルターアクションは、スパム メッセージを受信者の迷惑メール フォルダーに移動します。 これをオンプレミスの Exchange メールボックスで使用するには、EOP によって追加されたスパム ヘッダーを検出するために、オンプレミス Exchange 組織で 2 つのトランスポート ルールを構成する必要もあります。 詳細については、「スタンドアロン EOP を構成してハイブリッド環境の迷惑メール フォルダーにスパムを配信 [する」を参照してください](/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)。 <br/>
<sup>9</sup> EOP レポートは、メールボックスに関するExchange Online含むレポートのサブセットです。<br/>
<sup>10</sup> DLP レポートが含まれます。 <br/>
<sup>12</sup> Azure Information Protection を購入し、Azure Information Protection を使用してメールExchange Online Protectionをルーティングするオンプレミスのお客様Exchange Online。 <br/>
<sup>13</sup> 受信メッセージと送信メッセージをスキャンしますが、組織内の送信者から組織内の受信者に送信された内部メッセージはスキャンしません。 <br/>
<sup>15</sup>ハイブリッド セットアップはハイブリッド ウィザードでは使用できませんが、SP1 を使用している場合は手動Exchangeできます。