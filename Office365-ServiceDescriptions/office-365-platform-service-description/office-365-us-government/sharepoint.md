---
title: 米国政府機関向け SharePoint 環境
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 米国政府機関向けクラウドのお客様向け SharePoint 機能の可用性について説明します。
ms.openlocfilehash: 505be0509dbef718e64983377c8dc75a23adfd26
ms.sourcegitcommit: bf25a64ef2b5c1a1c1e5b94babbebf8d2eb7a1a1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/08/2021
ms.locfileid: "50145984"
---
# <a name="sharepoint-for-us-government-environments"></a>米国政府機関向け SharePoint 環境

この記事では、SharePoint サービスの説明に記載されている米国政府機関向けクラウドと商用クラウドの機能の違いの概要 [を説明します](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)。 SharePoint は、Government Community Cloud (GCC)、GCC High、DoD 環境で使用できます。 

適格性や購入など、政府機関向けクラウドについて詳しくは [、Microsoft 365 Government の購入方法に関するページをご覧ください](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)。 365 Officeプランと比較するには [、365 政府機関向Officeプランを参照してください](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

ネットワーク接続を管理する際に必要なエンドポイントについては [、Office 365 U.S. Government GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) エンドポイントまたは [Office 365 U.S. Government DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)エンドポイントを参照してください。

Office 365 の機能を活用できるだけでなく、組織は米国政府機関のクラウド環境に固有の次の機能を活用できます。

-   組織の顧客コンテンツは、Microsoft の商用サービスまたは 365 サービスOfficeコンテンツから論理的に分離されています。
-   組織の顧客コンテンツは、米国内に格納されます。
-   組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
-   政府機関向けクラウド環境は、米国公的機関のお客様に必要な認定と認定に準拠しています。

すべての SharePoint の商用機能を政府機関向けクラウド環境に提供する目標です。 政府機関向けクラウドのお客様の要件のため、一部の機能は利用できません。 他の機能は政府機関の環境に提供されますが、まだ利用できません。 政府機関のクラウド環境での機能の可用性については、以下のセクションを参照してください。

## <a name="developer-features"></a>開発者向けの機能

商用顧客向けの開発者向け機能と政府機関向けクラウドのお客様向けの機能には、既知の違いはありません。

- アドインのデータ ソースなどの外部アプリケーションへの接続は、政府機関の環境でサポートされているシステム セキュリティの境界内にあるソースに限定されます。
- Business Connectivity Services (BCS) 機能は、クラウド サービスのセキュリティ境界内でデータ ソースに到達可能なままである接続シナリオでサポートされています。

サイトでサードパーティアプリケーションを使用する場合は、組織に対するこれらのサービスの適切な使用を評価する際に、サード パーティが提供するプライバシーおよびコンプライアンスに関する声明を確認してください。 サードパーティのアプリケーションおよびサービスには、政府機関向けクラウドの外部にあるため、コンプライアンスとデータ保護のコミットメントの対象となされていないサードパーティ システム上で、組織の顧客データを保存、送信、処理する必要があります。 

## <a name="it-admin-features"></a>IT 管理者向け機能

以下に、商用顧客向け IT 管理者機能と政府機関向けクラウドのお客様向け機能の違いを示します。

- GCC High のお客様はサイト アドレスを変更できません
- ハイブリッド SharePoint Server は、すべての政府機関向けクラウドのお客様が利用できるとは言え
- SharePoint 移行ツールと移行マネージャーでは、構成を変更する必要があります。 詳しくは [、SPMT 政府機関向けクラウド サポートに関するページをご覧ください](/sharepointmigration/spmt-install-issues#government-cloud-support)。
- Mover.ioはまだサポートされていません
- 複数地域は、すべての政府機関向けクラウドのお客様が利用できるとは言え

FastTrack の移行について詳しくは、米国政府機関向け Office [365 のサービス](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)の説明をご覧ください。

## <a name="security-and-compliance-features"></a>セキュリティとコンプライアンスの機能

商用顧客と政府機関向けクラウドのお客様のセキュリティとコンプライアンスの機能には、既知の違いはありません。

セキュリティおよびコンプライアンス機能の詳細については、セキュリティ/コンプライアンス センター [&参照してください](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)。

政府機関向け Azure Active Directory 機能の詳細については、Azure Government のセキュリティと ID に関する [ドキュメントを参照してください](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)。 

政府機関向け Azure Information Protection 機能の詳細については [、Azure Information Protection Premium Government サービスの説明を参照してください](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)。 

## <a name="sites-and-content"></a>サイトおよびコンテンツ

以下に、商用顧客向けと政府機関向けクラウドのお客様向けサイトとコンテンツ機能の違いを示します。

- Amazon Kindle、Bing Maps、Twitter、YouTube の各 Web パーツなど、インターネット サービスへの接続に依存する Web パーツは期待通りに動作しません。
- 組織のアセット ライブラリは使用できません
- Teams へのリストとページの追加は、GCC High および DoD のお客様は利用できません。
- 現在、SharePoint Online for GCC High 内のグラフ機能は無効になっています。 Microsoft Graph に依存しているサービスは、現在利用できない場合があります。
- [画像] タブなど、インターネット サービスへの接続に依存する機能は期待通りに機能しません。

## <a name="search-features"></a>検索機能

以下に、商用顧客向け検索機能と政府機関向けクラウドのお客様向け検索機能の違いを示します。

- Microsoft Search 統合は使用できません。

## <a name="sharing-and-sync"></a>共有と同期

商用クラウドと政府機関向けクラウド環境の機能の違いについては、「ファイル共有」を [参照してください](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)。

## <a name="plan-for-governance"></a>ガバナンスを計画する

クラウドへの移行では、組み込みの管理コントロールを使用して、変換的なエクスペリエンスを提供できます。 ガバナンスの要件とそれらを満たす方法を決定します。 詳細については [、「Microsoft 365 でチームワークを](https://resources.techcommunity.microsoft.com/teamwork-governance/) 変革するガバナンスを計画する」を参照してください。 365 グループ、SharePoint、Teams Officeに関するガイダンスが表示されます。

## <a name="deploy-sharepoint-for-collaboration"></a>共同作業用に SharePoint を展開する

Microsoft US Government Cloud で組織をセットアップした後、SharePoint 導入リソース センターに示されている推奨される展開パス [に従います](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)。 必ず導入および変更管理のチャンピオンと一緒に取り組む必要があります。
FastTrack または選択した [パートナーと](https://www.microsoft.com/fasttrack) 一緒に作業して、ユーザーにサービスをロールアウトできます。
Microsoft がセキュリティ、プライバシー、コンプライアンスに取り組む方法、組織が顧客にサービスを提供する方法に関する主要なテネトについて詳しくは [、Microsoft](https://www.microsoft.com/trust-center) セキュリティ センターをご覧ください。
