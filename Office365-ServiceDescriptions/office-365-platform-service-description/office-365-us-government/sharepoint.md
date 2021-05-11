---
title: SharePoint環境向け
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 米国政府機関向けクラウドSharePointの利用可能性に関する詳細をご覧ください。
ms.openlocfilehash: cec996804ab0d402d2bcccd89b8bbfb5e7f70905
ms.sourcegitcommit: c34f7acea5e172eb2b29ae42f71e69932def6ac0
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/20/2021
ms.locfileid: "51900777"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint環境向け

この記事では、米国政府機関向けクラウドと商用クラウドの機能の違いの概要を説明します(「サービスの説明」にSharePoint[示します](../../sharepoint-online-service-description/sharepoint-online-service-description.md)。 SharePoint (Government Community Cloud)、GCC、DoD GCCで使用できます。 

適格性や購入を含む政府機関のクラウドの詳細については、「Microsoft 365 [- 購入方法」を参照してください](./microsoft-365-government-how-to-buy.md)。 プランとプランOffice 365 Government比較するには、「Office 365 Government[プラン」を参照してください](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

ネットワーク接続を管理する際に必要なエンドポイントの詳細については[、「Office 365](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)米国政府機関 GCC 高エンドポイント」または「Office 365 米国政府機関の[DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)エンドポイント」を参照してください。

組織は、Office 365の機能を楽しむだけでなく、米国政府のクラウド環境に固有の次の機能を利用できます。

-   組織の顧客コンテンツは、商用サービスの顧客コンテンツと Microsoft から論理的にOffice 365分離されます。
-   組織の顧客コンテンツは、米国内に格納されます。
-   組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
-   政府機関のクラウド環境は、米国の公的機関のお客様に必要な認定と認定に準拠しています。

政府機関のクラウド環境に商用SharePoint機能を提供する目的です。 政府機関のクラウド顧客の要件のために利用できない機能もあります。 その他の機能は政府機関の環境に提供されますが、まだ利用できません。 政府機関のクラウド環境での機能の可用性については、以下のセクションを参照してください。

## <a name="developer-features"></a>開発者向けの機能

商用顧客向けの開発者向け機能と政府機関向けクラウド顧客向けの開発者向け機能には、既知の違いはありません。

- アドインのデータ ソースなどの外部アプリケーションへの接続は、政府機関環境でサポートされているシステム セキュリティ境界内にあるソースに限定されます。
- Business Connectivity Services (BCS) 機能は、クラウド サービスのセキュリティ境界内でデータ ソースが到達可能なままの接続シナリオでサポートされます。

サイトでサードパーティ アプリケーションを使用する場合は、組織に対するこれらのサービスの適切な使用を評価する際に、第三者が提供するプライバシーとコンプライアンスに関する声明を確認してください。 サード パーティのアプリケーションとサービスには、政府機関のクラウドの外部にあるサードパーティ システム上の組織の顧客データの保存、送信、および処理が含まれる場合があります。したがって、コンプライアンスとデータ保護のコミットメントの対象となされない場合があります。 

## <a name="it-admin-features"></a>IT 管理者の機能

商用顧客の IT 管理者機能と政府機関のクラウド顧客向け IT 管理者機能の違いを次に示します。

- サイト アドレスの変更は、高いユーザー GCC使用できません
- ハイブリッド SharePoint サーバーは、すべての政府機関クラウドのお客様に利用できるとは言え
- 移行SharePoint移行マネージャーでは、構成の変更が必要です。 詳細については [、「SPMT Government cloud support」を参照してください](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.io はまだサポートされていません
- 複数地域は、すべての政府機関向けクラウドのお客様が利用できるとは言え

FastTrack 移行の詳細については、「米国政府機関[サービスOffice 365を参照してください](./office-365-us-government.md#data-migrations-performed-by-fasttrack)。

## <a name="security-and-compliance-features"></a>セキュリティとコンプライアンスの機能

商用顧客のセキュリティ機能とコンプライアンス機能と、政府機関向けクラウド顧客のセキュリティ機能とコンプライアンス機能の間には、既知の違いはありません。

セキュリティおよびコンプライアンス機能の詳細については [、「Security &コンプライアンス センター」を参照してください](../office-365-securitycompliance-center.md)。

政府機関向けAzure Active Directoryの詳細については[、「Azure Government Security + Identity」のドキュメントを参照してください](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

政府機関向け Azure Information Protection 機能の詳細については[、「Azure Information Protection プレミアム」を参照してください](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

## <a name="sites-and-content"></a>サイトおよびコンテンツ

商用顧客向けサイトとコンテンツ機能と、政府機関向けクラウド顧客のサイトとコンテンツ機能の違いを次に示します。

- Amazon Kindle、Bing地図、Twitter、YouTube Web パーツなど、インターネット サービスへの接続に依存する Web パーツは期待通りに動作しません。
- 組織アセット ライブラリは使用できません
- リストとページをユーザーにTeams、高値ユーザーおよび DoD ユーザー GCC使用できません
- Graph High のオンラインSharePoint機能GCC現在無効になっています。 Microsoft サービスに依存しているサービスGraph現在利用できない場合があります
- [ストック イメージ] タブなど、インターネット サービスへの接続に依存する機能が期待通りに動作しない
- ファイルとサイトのアクティビティに関する通知は使用できません
- ニュース Web パーツは、現在のサイトからのみニュースを取得します。 関連付けられたサイトからの選択したサイトまたはハブニュースのロールアップからのニュースは、高値および DoD GCC利用できません

## <a name="search-features"></a>検索機能

商用顧客の検索機能と政府機関向けクラウド顧客の検索機能の違いを次に示します。

- Microsoft Search は、GCC で使用できません。

## <a name="sharing-and-sync"></a>共有と同期

商用クラウドと政府機関のクラウド環境の機能の違いについては、「ファイル共有」 [を参照してください](./gcc-high-and-dod.md#file-sharing)。

## <a name="plan-for-governance"></a>ガバナンスの計画

クラウドに移行すると、組み込みの管理コントロールで変革的なエクスペリエンスが提供されます。 ガバナンスの要件と要件を満たす方法を決定します。 詳細については、「[ガバナンスを計画する」](https://resources.techcommunity.microsoft.com/teamwork-governance/)を参照して、Microsoft 365チームワークを変革します。 グループ、グループ、Office 365、SharePointなどTeamsがあります。

## <a name="deploy-sharepoint-for-collaboration"></a>コラボレーションSharePoint展開する

Microsoft US Government cloud で組織をセットアップした後、導入リソース センターで説明されている推奨される展開パスSharePoint[従います](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)。 導入および変更管理のチャンピオンと必ず参加してください。
FastTrack または選択した [パートナーと](https://www.microsoft.com/fasttrack) 一緒に作業して、サービスをユーザーにロールアウトできます。
Microsoft がセキュリティ、プライバシー、コンプライアンスに取り組む方法、組織が顧客にサービスを提供する方法に関するコア テネトの詳細については [、Microsoft](https://www.microsoft.com/trust-center) Trust Center をご覧ください。
