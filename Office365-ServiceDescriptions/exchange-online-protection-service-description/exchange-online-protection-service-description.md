---
title: Exchange Online Protection サービスの説明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection の機能と要件に関する情報を取得します。 Exchange Online Protection を提供するプランの一覧と、それらのプラン全体での機能の比較について説明します。
ms.openlocfilehash: c385ef02d7d3c28a37b71162daace04a0cee800c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/26/2019
ms.locfileid: "39260922"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection サービスの説明

Exchange Online Protection の機能と要件に関する情報を取得します。 Exchange Online Protection を提供するプランの一覧と、それらのプラン全体での機能の比較について説明します。

マイクロソフト Exchange Online Protection (EOP) は、クラウドベースの電子メール フィルタリング サービスであり、スパムやマルウェアから組織を保護するのに役立ち、メッセージング ポリシー違反から組織を保護する機能が含まれています。EOP はメッセージング環境の管理を簡素化し、社内のハードウェアおよびソフトウェアの維持に伴う負荷の多くを軽減します。

次の一覧では、メッセージング保護に EOP を使用する主な方法について説明します。

- **スタンドアロンのシナリオで**は、EOP は、オンプレミスの電子メール環境 (Exchange サーバーやその他のオンプレミスの SMTP 電子メールソリューション) に対してクラウドベースの電子メール保護を提供します。

- **Microsoft Exchange online の一部として**: 既定では、EOP は Exchange Online クラウドホスト型メールボックスを保護します。 Exchange Online の詳細については、「 [Exchange online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- **ハイブリッド展開で**は、社内メールボックスとクラウドメールボックスが混在している場合にメッセージング環境を保護し、メールルーティングを制御するように EOP を構成できます。

各プランの機能を比較するには、「[プランを選ぶ](https://products.office.com/business/compare-more-office-365-for-business-plans)」をご覧ください。

Exchange Online Protection を購入するには、「[Office 365 Advanced Threat Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)」をご覧ください。

> [!NOTE]
> EOP は Forefront Online Protection for Exchange (FOPE) に置き換えました。 すべての FOPE お客様は、EOP に移行しています。

## <a name="whats-new-in-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の新機能

「[ビジネス向けの Office 365 ロードマップ](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)」は新機能を調べるためのお勧めの情報源です。

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) のプラン

EOP は以下のサブスクリプション プランで提供されています。

|**プラン**|**説明**|
|:-----|:-----|
|[Office 365 Advanced Threat Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)|オンプレミスの電子メール組織を保護する別のクラウドベースのサービス。|
|[Exchange Online の EOP 機能](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Exchange Online クラウドホスト型メールボックスの組み込み保護。|
|[Exchange Enterprise CAL (サービス付き)](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|EOP およびその他のクラウドベースの機能を含むオンプレミスの Exchange 組織用に購入するアドオンライセンス (詳細については、次のセクションを参照してください)。|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services の機能

Microsoft Exchange Enterprise CAL with Services には、EOP の電子メール保護機能と、次のクラウドベースの追加機能が用意されています。

- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)

Exchange Enterprise CAL with Services のライセンスの詳細については、「 [Exchange Server licensing](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)」を参照してください。

Exchange Enterprise CAL とサービスライセンスがあり、EOP をプロビジョニングする場合は、「 [Set up THE EOP service](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service)」の手順に従ってください。 セットアップ手順は EOP スタンドアロンのセットアップ手順と同じです。

> [!NOTE]
> Exchange Enterprise CAL with Services の新機能は Exchange Online と同時に展開され、EOP スタンドアロンと同時には展開されません。EOP スタンドアロンと Exchange Online/Exchange Enterprise CAL with Services の展開スケジュールは、多少異なる場合があります。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の要件

EOP は、Microsoft Exchange Server などの任意の SMTP メール転送エージェントで使用できます。 EOP でサポートされているオペレーティングシステム、web ブラウザー、および言語の詳細については、「exchange [Online Protection の exchange 管理センター](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)」の「サポートされるブラウザー」と「サポートされる言語」のセクションを参照してください。

## <a name="limits"></a>制限

EOP の制限については、「 [Exchange Online Protection の制限](exchange-online-protection-limits.md)」を参照してください。

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Exchange Online Protection (EOP) の各プランで利用できる機能

各機能を以下に列挙します。EOP 機能の詳細については、表内のリンクをクリックしてください。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。

|||||
|:-----|:-----|:-----|:-----|
|**機能**|**EOP スタンドアロン**|**Exchange Online の<br/> EOP 機能**|**Exchange Enterprise <br/> CAL とサービス**|
|[メールの受信者](recipient-domain-and-company-management.md#mail-recipients)|はい<sup>1</sup>|はい<sup>1</sup>|はい|
|[管理役割グループのアクセス許可](recipient-domain-and-company-management.md#admin-role-group-permissions)|はい<sup>2</sup>|はい|はい|
|[ドメインの管理](recipient-domain-and-company-management.md#domain-management)|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|
|[一致サブドメイン](recipient-domain-and-company-management.md#match-subdomains)|はい|はい|いいえ|
|[ディレクトリ ベースのエッジ ブロック (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|はい|はい|はい|
|[メール フロー ルール](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|はい<sup>4</sup>|はい<sup>4、6</sup>|はい|
|[監査ログ](messaging-policy-and-compliance-servicedesc.md#audit-logging)|はい (<sup>5</sup> )|はい|はい|
|[データ損失防止 (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|いいえ|はい|はい<sup>6</sup>|
|[Office 365 Message Encryption](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|[はい]<sup>12</sup>|はい|[はい]<sup>12</sup>|
|[スパム対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (組み込み)|はい|はい|はい|
|[スパム対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Yes<sup>7</sup>|はい|はい|
|[マルウェア対策保護](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (組み込み)|はい (<sup>13</sup> )|はい|はい|
|[マルウェア対策ポリシーのカスタマイズ](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|はい|はい|はい|
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): 管理者による管理|はい|はい|はい|
|[検疫](anti-spam-and-anti-malware-protection-eop.md#quarantine): エンドユーザーによる自己管理|はい|はい|はい|
|[Outlook 用のレポートメッセージアドイン](anti-spam-and-anti-malware-protection-eop.md#report-message-add-in-for-outlook)|はい|はい|はい|
|[Outlook on the web での迷惑メール報告](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-on-the-web)|はい|はい|はい|
|[Office 365 とご使用の電子メール サーバー間で電子メールをルーティングする](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers)|はい|はい|はい|
|[信頼できるパートナーとのセキュリティで保護されたメッセージング](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|はい|はい|はい|
|[パートナーの IP アドレスのセーフ リスト](mail-flow-eop.md#safe-listing-a-partners-ip-address)|はい|はい|はい|
|[条件付きメール ルーティング](mail-flow-eop.md#conditional-mail-routing)|はい|はい|はい|
|[ハイブリッド メール ルーティング](mail-flow-eop.md#hybrid-mail-routing)|はい|はい|はい|
|[Microsoft 365 管理センターのレポート](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |はい (<sup>9</sup> )|はい (<sup>10</sup> )|はい <sup>9、10</sup>|
|[Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)|いいえ|はい|はい|
|[メッセージの追跡](reporting-and-message-trace.md#message-trace)|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい|
|[Microsoft 365 管理センターへのアクセス](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|はい|はい|はい|
|[Exchange 管理センターへのアクセス](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|はい|はい|はい|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|はい|はい|はい|

<sup>1</sup>メールユーザーは "メールボックス" として定義され、外部メール連絡先と一緒に Exchange 管理センター (EAC) で直接追加、削除、その他の管理を行うことができます。 <br/>
<sup>2</sup> RBAC はカスタマイズしません。 管理者の役割のみ。 <br/>
<sup>3</sup>管理対象ドメインを表示し、ドメインの種類を EAC で編集できます。 他のすべてのドメイン管理は、Microsoft 365 管理センターで行う必要があります。<br/>
EOP の<sup>4 つ</sup>のメールフロールール (トランスポートルールとも呼ばれます) については、「 [Exchange Online Protection のメールフロールール (トランスポートルール)](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)」で説明します。 使用可能なメールフロールールの条件、例外、およびアクションは、EOP と Exchange Online で少し異なります。 これらの相違点については、「exchange [online のメールフロールールの条件と例外 (述語)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) 」および「 [exchange Online でのメールフロールールの処理](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)」で説明されています。<br/>
<sup>5</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。 <br/>
<sup>6</sup> DLP ポリシーヒントは、EXCHANGE Enterprise CAL with Services のお客様には使用できません。  <br/>
<sup>7</sup>既定のコンテンツフィルター操作は、スパムメッセージを受信者の迷惑メールフォルダーに移動することです。 このことをオンプレミスの Exchange メールボックスでも使用できるようにするには、EOP によって追加されたスパムヘッダーを検出するために、オンプレミスの Exchange 組織で2つのトランスポートルールを構成する必要があります。 詳細については、「[スパムが各ユーザーの迷惑メールフォルダーにルーティングされるようにする](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder)」を参照してください。 <br/>
<sup>9</sup> EOP レポートは、メールボックスに関する情報を除いた Exchange Online レポートの一部です。<br/>
<sup>10</sup> DLP レポートを含みます。 <br/>
<sup>12</sup> Azure Information protection を購入して Exchange online Protection を使用して exchange online 経由で電子メールをルーティングするオンプレミスのお客様に対してサポートされています。 <br/>
<sup>13</sup>受信メッセージと送信メッセージをスキャンしますが、組織内の送信者が組織内の受信者に送信する内部メッセージはスキャンしません。 <br/>
<sup>15</sup>ハイブリッドセットアップはハイブリッドウィザードでは使用できませんが、Exchange SP1 がある場合は手動でセットアップできます。
