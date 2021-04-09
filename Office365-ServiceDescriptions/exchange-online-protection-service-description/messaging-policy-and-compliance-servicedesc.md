---
title: Exchange Online Protection のメッセージング ポリシーとコンプライアンス
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: この記事では、メッセージ保護 (EOP) のメッセージング ポリシーとコンプライアンスMicrosoft Exchange Online説明します。
ms.openlocfilehash: 81228b13036e831df630cca6f27b4ad285705f29
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653349"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Exchange Online Protection のメッセージング ポリシーとコンプライアンス

Microsoft Exchange Online保護 (EOP) には、メール データの管理に役立つメッセージング ポリシーとコンプライアンス機能が提供されます。

すべての EOP 機能に関する情報をお探しですか? Exchange [Online Protection サービスの説明を参照してください](exchange-online-protection-service-description.md)。

## <a name="mail-flow-rules"></a>メール フロー ルール

メール フロー ルール (トランスポート ルールとも呼ばれる) を使用すると、独自の会社固有のポリシーを電子メールに柔軟に適用できます。 メール フロー ルールは柔軟な条件で構成され、条件、例外、および条件に基づいて実行するアクションを定義できます。 詳細については [、「Exchange Online Protection のメール フロー ルール (トランスポート ルール)」を参照してください](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)。

## <a name="audit-logging"></a>監査ログ

監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。 これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。 詳細については、「[EOP の監査レポート](/microsoft-365/security/office-365-security/auditing-reports-in-eop)」を参照してください。

## <a name="data-loss-prevention-dlp"></a>データ損失防止 (DLP)

EOP スタンドアロンのお客様は利用できません。 データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。 ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。 DLP 機能を使用すると、作業者の生産性に影響を与えることなく、機密データを保護できます。

EAC で DLP ポリシーを構成することにより、次のことが可能になります。

- PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。

- 既存のメール フロー ルールの条件とアクションのフル パワーを使用し、新しいメール フロー ルールを追加します。

- DLP ポリシーを完全に実施する前にその効果をテストできます。

- 独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。

- メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。

- ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。 ドキュメント フィンガープリントは、メール フロー ルールと DLP ポリシーの定義に使用できるテキスト ベースのフォームに基づいて、カスタムの機密情報の種類を簡単に作成するのに役立ちます。

- ポリシー ヒントを追加すると、Outlook 2013、Outlook on the Web、および OWA for Devices ユーザーに通知を表示してデータ損失を減らすのに役立ちます。また、誤検知レポートを許可することでポリシーの有効性を改善することもできます。

- インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。

> [!NOTE]
> DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。

DLP の詳細については [、「Exchange Online でのデータ損失防止」を参照してください](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。 社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。 Exchange Online での 365 Office暗号化の詳細については、「Exchange Online サービスの説明Office [365 Message](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) Encryption」を参照してください。

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP オプション間のメッセージング ポリシーとコンプライアンス機能

| 機能 | EOP スタンドアロン | EOP の機能 <br/> Exchange Online | Exchange Enterprise <br/> CAL with Services |
|:-----|:-----|:-----|:-----|
|メール フロー ルール|はい<sup>1</sup>|はい<sup>1</sup>|は<sup>い 1、3</sup>|
|監査ログ|はい<sup>2</sup>|はい|はい|
|データ損失防止 (DLP)|いいえ|はい|はい<sup>3</sup>|
|Office 365 Message Encryption|はい<sup>4</sup>|はい|はい<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> 使用可能なメール フロー ルールの条件、例外、およびアクションは、EOP と Exchange Online の間で若干異なります。 これらの違いは [、Exchange Online](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) のメール フロー ルールの条件と例外 (述語) および Exchange Online のメール フロー [ルール アクションで説明されています](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)。 <br/>
> <sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。 <br/>
> <sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。 <br/>
> <sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。 デスクトップ エクスペリエンスでは、Azure Information Protection アドオンに加えて、Microsoft 365 Apps for enterprise を購入する必要があります。 <br/>