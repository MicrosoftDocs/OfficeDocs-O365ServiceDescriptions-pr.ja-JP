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
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222484"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection サービスの説明

Exchange Online Protection の機能と要件に関する情報を取得します。 含まれるプランの一覧は、Exchange Online Protectionプラン全体の機能の比較と同様に提供されます。

Microsoft Exchange Online保護 (EOP) は、スパムやマルウェアから組織を保護するのに役立つクラウドベースの電子メール フィルター サービスであり、メッセージング ポリシー違反から組織を保護するための機能が含まれています。 EOP はメッセージング環境の管理を簡素化し、オンプレミスのハードウェアおよびソフトウェアの維持に伴う負荷の多くを軽減します。

次の一覧では、メッセージング保護に EOP を使用する主な方法について説明します。

- **スタンドアロン シナリオ:** EOP は、オンプレミスの電子メール環境 (Exchange Serverまたは他のオンプレミス SMTP 電子メール ソリューション) に対してクラウドベースの電子メール保護を提供します。

- **[クラウド ホスト型メールボックスMicrosoft Exchange Online:** 既定では、EOP はクラウドホスト型メールボックスExchange Online保護します。 Exchange Online の詳細については、「[Exchange Online サービスの説明](../exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- **ハイブリッド展開:** EOP を構成して、メッセージング環境を保護し、オンプレミスメールボックスとクラウド メールボックスが混在している場合のメール ルーティングを制御できます。

## <a name="available-plans"></a>使用できるプラン

次の表に、組織のニーズにExchange Online Protection最適なソリューションを選択できるよう、アプリケーションを含むプランを示します。 プランの詳細については、「Exchange Online Protection」 を[参照してください](https://products.office.com/exchange/exchange-email-security-spam-protection)。

ユーザーがサブスクリプションを有効にするサブスクリプションの詳細な計画Exchange Online Protection、完全なサブスクリプション比較表[を参照してください](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)。

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services の機能

Microsoft Exchange Enterprise CAL with Services には、EOP の電子メール保護機能と、次のクラウドベースの追加機能が用意されています。

- [データ損失防止](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Web サービスを使用したレポート作成](reporting-and-message-trace.md#reporting-using-web-services)

サービスライセンスを使用した CAL のExchange Enterprise詳細については、「ライセンスに関するよくあるExchange[を参照してください](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。

CAL をサービス ライセンスExchange Enterpriseし、EOP をプロビジョニングする場合は、「EOP サービスのセットアップ」の手順[に従います](/microsoft-365/security/office-365-security/set-up-your-eop-service)。 セットアップ手順は EOP スタンドアロンのセットアップ手順と同じです。

> [!NOTE]
> Exchange Enterprise CAL with Services の新機能は Exchange Online と同時に展開され、EOP スタンドアロンと同時には展開されません。EOP スタンドアロンと Exchange Online/Exchange Enterprise CAL with Services の展開スケジュールは、多少異なる場合があります。

## <a name="requirements-for-exchange-online-protection-eop"></a>Exchange Online Protection (EOP) の要件

EOP は、SMTP メール転送エージェント (メール転送エージェントなど) とMicrosoft Exchange Server。 EOP でサポートされているオペレーティング システム、Web ブラウザー、および言語の詳細については、Exchange Online Protection の Exchange 管理センターの「サポートされているブラウザー」および「サポートされている言語[」セクションを参照してください](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)。

## <a name="limits"></a>制限

EOP の制限については、「制限[Exchange Online Protection参照してください](exchange-online-protection-limits.md)。

## <a name="feature-availability"></a>機能の可用性

次の表に、複数のプランで利用Exchange Online Protection主な機能を示します。 特定の注意点が適用されます。 詳細については、脚注を参照してください。 この表は、予告なしに変更される場合があります。 最新の完全な機能の一覧については、「エンタープライズをサポートするための強力なツール [」を参照してください](https://products.office.com/business/compare-more-office-365-for-business-plans)。

| 機能 | スタンドアロン EOP | サービスを使用Enterprise Edition CAL の EOP | Exchange Online の EOP 機能 |
|:-----|:-----|:-----|:-----|
|**Protection**||||
|マルウェア対策ポリシー (組み込みおよびカスタム)|はい|はい|はい|
|受信スパム対策ポリシー (組み込みおよびカスタム)|はい|はい|はい|
|送信スパム対策ポリシー (組み込みおよびカスタム)|はい|はい|はい|
|接続フィルター (IP 許可一覧と IP ブロック 一覧)|はい|はい|はい|
|フィッシング対策ポリシー (組み込みおよびカスタム)|はい|はい|はい|
|スプーフィング防止保護 (組み込みおよびカスタム)|はい|はい|はい|
|配信されたマルウェア、スパム、フィッシング メッセージのゼロ時間自動削除 (ZAP)<sup>10</sup>|いいえ|いいえ|はい|
|事前設定されたセキュリティ ポリシー|はい|はい|はい|
|保護ポリシーの構成アナライザー|はい|はい|はい|
|テナント許可/ブロック一覧|はい|はい|はい|
|メッセージ送信者のリストをブロックする|はい|はい|はい|
|メッセージ送信者のリストを許可する|はい|はい|はい|
|エッジブロック|はい|はい|はい|
|存在しない受信者のディレクトリ ベースのエッジ ブロック (DBEB)|はい|はい|はい|
|**検疫と申請**||||
|管理者申請<sup>10</sup>|いいえ|いいえ|はい|
|ユーザー申請 (カスタム メールボックス)<sup>10</sup>|いいえ|いいえ|はい|
|管理者検疫|はい|はい|はい|
|エンド ユーザー検疫|はい|はい|はい|
|レポート メッセージ アドインとレポート フィッシング Outlook|はい|はい|はい|
|**メール フロー**||||
|メール フロー ルール (トランスポート ルール)<sup>4</sup>|はい|はい<sup>6</sup>|はい|
|受け入れドメイン<sup>3</sup> |はい|はい|はい|
|コネクタ|はい|はい|はい|
|コネクタの拡張フィルター (リストをスキップ)|はい|はい|はい|
|**監視**||||
|Message trace|はい|はい|はい|
|電子メールとセキュリティ レポートは、Microsoft 365 管理センター|はい<sup>7</sup>|はい<sup>7、8</sup>|はい<sup>8</sup>|
|セキュリティ センターのMicrosoft 365レポート|はい<sup>7</sup>|はい<sup>7、8</sup>|はい<sup>8</sup>|
|EAC の電子メール レポート|はい<sup>7</sup>|はい<sup>7、8</sup>|はい<sup>8</sup>|
|管理者監査ログ<sup>5</sup>|はい|はい|はい|
|**Users**||||
|メール ユーザーとメール連絡先<sup>1</sup>|はい|はい|はい|
|メールボックス|いいえ|いいえ|は<sup>い 1a</sup>|
|役割ベースのアクセス制御 (RBAC)<sup>2</sup>|はい|はい|はい|
|**コンプライアンス**||||
|電子メールのデータ損失防止|いいえ|はい|はい|
|Office 365 Message Encryption|いいえ<sup>9</sup>|いいえ<sup>9</sup>|はい|
|**管理**||||
|Microsoft 365 管理センター|はい|はい|はい|
|Exchange 管理センター|はい|はい|はい|
|Microsoft 365 セキュリティ センター|はい|はい|はい|
|スタンドアロン Exchange Online Protection PowerShell|はい|いいえ|いいえ|
|Exchange Online PowerShell|いいえ|はい|はい|

<sup>1</sup> EAC でメール ユーザーとメール連絡先を作成、削除、および編集します。 <br/>
<sup>1a</sup>メールボックスを作成して削除するには、Microsoft 365 管理センター。 EAC で既存のメールボックスを編集できます。 <br/>
<sup>2</sup>スタンドアロン EOP およびサービスEnterprise Edition CAL には、エンド ユーザーの役割や役割の割り当てポリシーはありません。<br/>
<sup>3</sup>ドメインを追加および削除するには、Microsoft 365 管理センター。  EAC では、ドメインを権限または非権限として構成します。<br/>
<sup>4</sup>いくつかのルールの条件、例外、およびアクションは、スタンドアロン EOP またはサービス付き CAL Enterprise Edition EOP では使用できません。 これらの違いは、メール フロー ルールのExchange Onlineに明確に示されています。 <br/>
<sup>5</sup>スタンドアロン EOP およびサービスEnterprise Edition CAL の場合:

- メールボックス監査レポートは使用できません。
- 管理者役割グループ レポートと管理者監査ログ レポートは、EAC 内で唯一の管理者監査レポートです。
- PowerShell 経由でのみ使用できる監査ログのエクスポート。 <br/>

<sup>6</sup>つの DLP ポリシー ヒントは、サービスEnterprise Edition CAL では使用できません。 <br/>
<sup>7</sup>スタンドアロン EOP およびサービスEnterprise Edition CAL のレポートは、Exchange Onlineレポート (メールボックスを処理するレポート) のサブセットです。<br/>
<sup>8</sup> DLP レポートが含まれます。 <br/>
<sup>9</sup> Azure Information Protection をアドオン サブスクリプションとして購入し、EOP を介してインターネットに電子メールをルーティングするようにオンプレミスの電子メール環境を構成する場合は、OME を使用できます。 <br/>
<sup>10 この機能</sup>には、メールボックスExchange Online必要があります。 <br/>

## <a name="learn-more"></a>詳細を見る

この機能に関するExchange Online Protection、次のリソースを参照してください。

次[Microsoft 365ロードマップは](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx)、今後の新機能に関する情報を見つけ出す優れたリソースです。

### <a name="licensing-terms"></a>ライセンス条項

Microsoft 商用ボリューム ライセンス プログラムを通じて購入した製品およびサービスのライセンス条件については、「製品条項」 [サイトを参照してください](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>メッセージング

新機能や変更された機能、計画メンテナンス、その他の重要なアナウンスなど、今後の変更を追跡するには、メッセージ センターにアクセスしてください。 詳細については、「メッセージ センター」 [を参照してください](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>アクセシビリティ

Microsoft は、お客様のデータのセキュリティとサービスのアクセシビリティに引き [続きコミット](https://www.microsoft.com/trust-center/compliance/accessibility) しています。 詳細については[、「Microsoft Trust Center」](https://www.microsoft.com/trust-center)および「アクセシビリティ センター Office[参照してください](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
