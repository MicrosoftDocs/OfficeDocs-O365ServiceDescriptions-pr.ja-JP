---
title: メッセージングのポリシーと準拠
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。
ms.openlocfilehash: 9ff12288f0b0432878d920ce4fb4ceccc6075ab2
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581873"
---
# <a name="messaging-policy-and-compliance"></a>メッセージング ポリシーとコンプライアンス

Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。

すべての EOP 機能に関する情報をお探しですか? 「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。

## <a name="mail-flow-rules"></a>メール フロー ルール

メールフロールール (トランスポートルールとも呼ばれます) は、独自の会社固有のポリシーを電子メールに適用する柔軟性を提供します。 メールフロールールは柔軟な条件で構成されているため、条件、例外、および実行する操作を条件に基づいて定義できます。 詳細については、「 [Mail flow rules (transport rules) In Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)」を参照してください。

## <a name="audit-logging"></a>監査ログ

監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。 これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。 詳細については、「[EOP の監査レポート](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop)」を参照してください。

## <a name="data-loss-prevention-dlp"></a>データ損失防止 (DLP)

EOP スタンドアロンのお客様は利用できません。 データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。 ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。 DLP 機能を使用すると、ワーカーの生産性に影響を与えることなく機密データを保護できます。

EAC で DLP ポリシーを構成することにより、次のことが可能になります。

- PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。

- 既存のメールフロールールの条件とアクションの全機能を使用して、新しいメールフロールールを追加します。

- DLP ポリシーを完全に実施する前にその効果をテストできます。

- 独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。

- メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。

- ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。 ドキュメントフィンガープリンティングを使用すると、メールフロールールと DLP ポリシーを定義するために使用できるテキストベースのフォームに基づいて、カスタムの機密情報の種類を簡単に作成できます。

- ポリシーヒントを追加します。これにより、Outlook 2013、Outlook on the web、およびデバイス用 OWA のユーザーに通知が表示されるので、データの損失を減らすことができます。また、誤報告を許可することで、ポリシーの有効性を向上させることもできます。

- インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。

> [!NOTE]
> DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。

DLP の詳細については、「 [Exchange Online でのデータ損失防止](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)」を参照してください。

## <a name="office-365-message-encryption"></a>はい

Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。Exchange Online の Office 365 Message Encryption の詳細については、「Exchange Online サービスの説明」の「[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)」を参照してください。

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP オプション間のメッセージング ポリシーとコンプライアンス機能

|**機能**|**EOP スタンドアロン**|**Exchange Online の<br/> EOP 機能**|**Exchange Enterprise <br/> CAL とサービス**|
|:-----|:-----|:-----|:-----|
|メール フロー ルール|はい<sup>1</sup>|はい<sup>1</sup>|はい<sup>1、3</sup>|
|監査ログ|はい<sup>2</sup>|はい|はい|
|データ損失防止 (DLP)|いいえ|はい|はい<sup>3</sup>|
|Office 365 Message Encryption|はい<sup>4</sup>|はい|はい<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> EOP と Exchange Online では、使用可能なメールフロールールの条件、例外、およびアクションが若干異なります。 これらの相違点については、「exchange [online のメールフロールールの条件と例外 (述語)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) 」および「 [exchange Online でのメールフロールールの処理](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)」で説明されています。 <br/>
> <sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。 <br/>
> <sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。 <br/>
> <sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。 デスクトップ エクスペリエンスのために、Azure Information Protection アドオンに加えて、Office 365 ProPlus を購入する必要があります。 <br/>
