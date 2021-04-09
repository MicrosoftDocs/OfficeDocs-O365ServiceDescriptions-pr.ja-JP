---
title: 米国政府機関環境向け SharePoint
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 米国政府機関向けクラウドのお客様向け SharePoint 機能の可用性について説明します。
ms.openlocfilehash: 8688c80ee2214ad77f4c27fa79dd38dca3c6cbb9
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653149"
---
# <a name="sharepoint-for-us-government-environments"></a>米国政府機関環境向け SharePoint

この記事では、SharePoint サービスの説明に記載されている米国政府機関クラウドと商用クラウドの機能の違いの概要 [について説明します](../../sharepoint-online-service-description/sharepoint-online-service-description.md)。 SharePoint は、Government Community Cloud (GCC)、GCC High、DoD 環境で使用できます。 

適格性や購入を含む政府機関のクラウドの詳細については [、「Microsoft 365 Government - How to buy」を参照してください](./microsoft-365-government-how-to-buy.md)。 365 Officeプランと比較するには、「365 Government プラン [Officeを参照してください](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

ネットワーク接続を管理する際に必要なエンドポイントについては [、「Office 365 米国政府機関 GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) エンドポイント」または [「Office 365](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)米国政府機関の DoD エンドポイント」を参照してください。

組織は、Office 365 の機能を利用できるだけでなく、米国政府機関のクラウド環境に固有の次の機能を利用できます。

-   組織の顧客コンテンツは、Microsoft から 365 サービスを提供する商用サービスの顧客Office論理的に分離されています。
-   組織の顧客コンテンツは、米国内に格納されます。
-   組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
-   政府機関のクラウド環境は、米国の公的機関のお客様に必要な認定と認定に準拠しています。

すべての SharePoint 商用機能を政府機関のクラウド環境に提供する目標です。 政府機関のクラウド顧客の要件のために利用できない機能もあります。 その他の機能は政府機関の環境に提供されますが、まだ利用できません。 政府機関のクラウド環境での機能の可用性については、以下のセクションを参照してください。

## <a name="developer-features"></a>開発者向けの機能

商用顧客向けの開発者向け機能と政府機関向けクラウド顧客向けの開発者向け機能には、既知の違いはありません。

- アドインのデータ ソースなどの外部アプリケーションへの接続は、政府機関環境でサポートされているシステム セキュリティ境界内にあるソースに限定されます。
- Business Connectivity Services (BCS) 機能は、クラウド サービスのセキュリティ境界内でデータ ソースが到達可能なままの接続シナリオでサポートされます。

サイトでサードパーティ アプリケーションを使用する場合は、組織に対するこれらのサービスの適切な使用を評価する際に、第三者が提供するプライバシーとコンプライアンスに関する声明を確認してください。 サード パーティのアプリケーションとサービスには、政府機関のクラウドの外部にあるサードパーティ システム上の組織の顧客データの保存、送信、および処理が含まれる場合があります。したがって、コンプライアンスとデータ保護のコミットメントの対象となされない場合があります。 

## <a name="it-admin-features"></a>IT 管理者の機能

商用顧客の IT 管理者機能と政府機関のクラウド顧客向け IT 管理者機能の違いを次に示します。

- サイト アドレスの変更は、GCC High のお客様には利用できません
- ハイブリッド SharePoint Server は、すべての政府機関向けクラウドのお客様が利用できるとは言え
- SharePoint 移行ツールと移行マネージャーでは、構成の変更が必要です。 詳細については [、「SPMT Government cloud support」を参照してください](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.io はまだサポートされていません
- 複数地域は、すべての政府機関向けクラウドのお客様が利用できるとは言え

FastTrack 移行の詳細については [、「365 US Government service description Office 365」を参照してください](./office-365-us-government.md#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>セキュリティとコンプライアンスの機能

商用顧客のセキュリティ機能とコンプライアンス機能と、政府機関向けクラウド顧客のセキュリティ機能とコンプライアンス機能の間には、既知の違いはありません。

セキュリティおよびコンプライアンス機能の詳細については [、「Security &コンプライアンス センター」を参照してください](../office-365-securitycompliance-center.md)。

政府機関向け Azure Active Directory 機能の詳細については [、「Azure Government Security + Identity」のドキュメントを参照してください](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

政府機関向け Azure Information Protection 機能の詳細については [、「Azure Information Protection Premium Government Service Description」を参照してください](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

## <a name="sites-and-content"></a>サイトおよびコンテンツ

商用顧客向けサイトとコンテンツ機能と、政府機関向けクラウド顧客のサイトとコンテンツ機能の違いを次に示します。

- インターネット サービスへの接続に依存する Web パーツ (Amazon Kindle、Bing Maps、Twitter、YouTube Web パーツなど) は期待通りに動作しません。
- 組織アセット ライブラリは使用できません
- Teams へのリストとページの追加は、GCC High および DoD のお客様には使用できません
- SharePoint Online for GCC High 内のグラフ機能は現在無効になっています。 Microsoft Graph に依存しているサービスは、現在利用できない場合があります。
- [ストック イメージ] タブなど、インターネット サービスへの接続に依存する機能が期待通りに動作しない
- ファイルとサイトのアクティビティに関する通知は使用できません

## <a name="search-features"></a>検索機能

商用顧客の検索機能と政府機関向けクラウド顧客の検索機能の違いを次に示します。

- Microsoft Search は GCC では使用できません。

## <a name="sharing-and-sync"></a>共有と同期

商用クラウドと政府機関のクラウド環境の機能の違いについては、「ファイル共有」 [を参照してください](./gcc-high-and-dod.md#file-sharing)。

## <a name="plan-for-governance"></a>ガバナンスの計画

クラウドに移行すると、組み込みの管理コントロールで変革的なエクスペリエンスが提供されます。 ガバナンスの要件と要件を満たす方法を決定します。 詳細については [、「ガバナンスの計画」を参照して、Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) とのチームワークを変革します。 365 グループ、SharePoint、Teams Officeに関するガイダンスが表示されます。

## <a name="deploy-sharepoint-for-collaboration"></a>コラボレーション用に SharePoint を展開する

Microsoft 米国政府機関クラウドで組織をセットアップした後、SharePoint 導入リソース センターで説明されている推奨される展開パス [に従います](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)。 導入および変更管理のチャンピオンと必ず参加してください。
FastTrack または選択した [パートナーと](https://www.microsoft.com/fasttrack) 一緒に作業して、サービスをユーザーにロールアウトできます。
Microsoft がセキュリティ、プライバシー、コンプライアンスに取り組む方法、組織が顧客にサービスを提供する方法に関するコア テネトの詳細については [、Microsoft](https://www.microsoft.com/trust-center) Trust Center をご覧ください。