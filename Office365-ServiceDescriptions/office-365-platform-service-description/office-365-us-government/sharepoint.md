---
title: 米国政府機関向けの SharePoint
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 米国政府機関のクラウドのお客様が利用できる SharePoint の機能について説明します。
ms.openlocfilehash: c360bc7ebda3c1a4041e0dcd8c2d5cb9699b8820
ms.sourcegitcommit: 6b7918dd0f125b49d81b11672617c95ebd676b01
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2020
ms.locfileid: "42175010"
---
# <a name="sharepoint-for-us-government-environments"></a>米国政府機関向けの SharePoint

この記事では、 [SharePoint サービスの説明](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)に記載されているように、米国政府機関クラウドと商用クラウドの機能の相違点の概要について説明します。 SharePoint は、Government Community Cloud (GCC)、GCC High、DoD 環境で利用できます。 

資格および購入に関する政府機関のクラウドに関する詳細については、「 [Microsoft 365 government-購入方法](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)」を参照してください。 Office 365 Government プランを比較するには、「 [office 365 government プラン](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)」を参照してください。

ネットワーク接続を管理するときに必要なエンドポイントの詳細については、「 [office 365 米国政府用 GCC、高エンドポイント](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)または[Office 365 米国政府の DoD エンドポイント](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)」を参照してください。

Office 365 の機能を楽しんだだけでなく、米国政府機関のクラウド環境に固有の次の機能を活用することができます。

-   組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。
-   組織の顧客コンテンツは、米国内に格納されます。
-   組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
-   政府機関のクラウド環境は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

この記事では、すべての SharePoint の商用機能を政府機関のクラウド環境に提供することを目標としています。 政府機関のクラウドのお客様の要件により、一部の機能は使用できません。 その他の機能は政府機関の環境に送られますが、まだ利用できません。 政府機関のクラウド環境で利用できる機能については、以下のセクションを参照してください。

## <a name="developer-features"></a>開発者向けの機能

市販のお客様向けの開発者向け機能と、政府機関のお客様にとっては、既知の違いはありません。

- アドインのデータソースなどの外部アプリケーションへの接続は、政府機関の環境でサポートされているシステムセキュリティ境界内にあるソースに制限されます。
- クラウドサービスのセキュリティ境界内でデータソースにアクセスできる接続シナリオでは、Business Connectivity Services (BCS) 機能がサポートされています。

サイトでサードパーティ製アプリケーションを使用する場合は、組織でのこれらのサービスの適切な使用法を評価する際に、サードパーティによって提供されるプライバシーとコンプライアンスのステートメントを確認してください。 サードパーティ製のアプリケーションおよびサービスには、政府機関の外部のシステムで組織の顧客データを保存、送信、および処理することが含まれるため、コンプライアンスとデータ保護の対象にならない場合があります。対する. 

## <a name="it-admin-features"></a>IT 管理者向けの機能

ここでは、商用のお客様向けの IT 管理者向けの機能と、行政機関のお客様向けの相違点を示します。

- GCC High お客様はサイトアドレスを変更できない
- ハイブリッド SharePoint サーバーは、すべての政府機関のお客様が利用できるわけではありません
- SharePoint 移行ツールおよび移行マネージャーは、構成の変更を必要とします。 詳細については、「 [Spmt government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support)」を参照してください。
- Mover.io はまだサポートされていません
- 複数地域は、すべての政府機関のお客様が利用できるわけではありません。

FastTrack の移行の詳細については、「 [Office 365 US Government サービスの説明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)」を参照してください。

## <a name="security-and-compliance-features"></a>セキュリティとコンプライアンスの機能

商用のお客様や政府機関のお客様のためのセキュリティとコンプライアンスの機能には、既知の違いはありません。

次の機能の詳細については、 [Office 365 US Government サービスの説明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features)を参照してください。
- 顧客ロックボックス
- データ損失防止 (DLP)
- 電子情報開示 (コンテンツ検索、保留、エクスポート)
- Office 365 Advanced Threat Protection (ATP)
- 機密ラベル

Government の Azure Active Directory 機能の詳細については、「 [Azure Government Security + Identity ドキュメント](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)」を参照してください。 

Government の Azure Information Protection 機能の詳細については、「 [Azure Information Protection Premium Government サービスの説明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)」を参照してください。 

## <a name="sites-and-content"></a>サイトおよびコンテンツ

以下は、商用のお客様向けのサイトとコンテンツ機能の相違点と、政府機関のお客様のためのものです。

- Amazon Kindle、Bing Maps、Twitter、YouTube web パーツなどのインターネットサービスへの接続に依存する web パーツは、期待どおりに機能しません。
- 組織のアセットライブラリは使用できません
- リストとページを Teams に追加することは、GCC High および DoD のお客様には使用できません。

## <a name="search-features"></a>検索機能

以下に、商用のお客様向けの検索機能と、政府機関のお客様のための相違点を示します。

- Microsoft 検索統合は使用できません。

## <a name="sharing-and-sync"></a>共有と同期

商用クラウド環境と官公庁クラウド環境の機能の違いについては、「[ファイル共有](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)」を参照してください。

## <a name="plan-for-governance"></a>ガバナンスを計画する

クラウドへの移行では、組み込みの管理コントロールを使用したプロジェクトエクスペリエンスが提供されます。 ガバナンスの要件と、それに対応する方法を決定します。 詳細については、「[ワークチームを Microsoft 365 に変換するためのガバナンスを計画](https://resources.techcommunity.microsoft.com/teamwork-governance/)する」を参照してください。 Office 365 グループ、SharePoint、Teams などに関するガイダンスが記載されています。

## <a name="deploy-sharepoint-for-collaboration"></a>コラボレーションのために SharePoint を展開する

Microsoft US government cloud で組織を設定した後、 [SharePoint 導入リソースセンター](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)で説明されている推奨される展開パスに従います。 導入の際には、管理エキスパートに協力してください。
また、 [Fasttrack](https://www.microsoft.com/fasttrack)または選択したパートナーと連携して、ユーザーにサービスをロールアウトすることもできます。
Microsoft のセキュリティ[センター](https://www.microsoft.com/en-us/trust-center)にアクセスすることにより、お客様にサービスを提供するように組織を支援する方法についての基本理念として、microsoft のセキュリティ、プライバシー、法令遵守の方法について知ることができます。
