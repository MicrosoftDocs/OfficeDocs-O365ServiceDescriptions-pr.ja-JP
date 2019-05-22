---
title: 開発者
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 05/20/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-developer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 415c9536-ae70-4d4b-b481-5255cb03cc32
description: SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の機能は、SharePoint の機能を拡張するアプリやソリューションを構築する開発者をサポートしています。
ms.openlocfilehash: c1b9bd6e86b14d8328edabc0ebf1d81fb592fb21
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342516"
---
# <a name="developer"></a>開発者

SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の機能は、SharePoint の機能を拡張するアプリやソリューションを構築する開発者をサポートしています。
  
## <a name="app-catalog-sharepoint"></a>アプリ カタログ (SharePoint)
<a name="bkmk_AppCatalogSharePoint"> </a>

アプリを SharePoint 配置上にホストされた社内のカタログに公開し、その SharePoint 配置にアクセスできるユーザーが利用できるようにします。[Office と SharePoint 用アプリの公開](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store)について詳細情報を参照してください。
  
## <a name="app-deployment-cloud-hosted-apps"></a>アプリの展開:クラウドでホストされるアプリ
<a name="bkmk_AppDeploymentCloudHostedApps"> </a>

クラウドでホストされる SharePoint アプリには、少なくとも 1 つのリモート コンポーネントが含まれ、SharePoint でホストされるコンポーネントが含まれる場合もあります。[SharePoint アプリのホスティング オプション](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)について詳細情報を参照してください。 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>アプリの展開:SharePoint でホストされるアプリ
<a name="bkmk_AppDeploymentSharePointHostedApps"> </a>

SharePoint でホストされるアプリでは、リストや Web パーツなどの共通の SharePoint アーティファクトを再利用できます。このアプローチを採用する場合、JavaScript しか使用できず、サーバー側コードは使用できません。[SharePoint アプリのホスティング オプション](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)について詳細情報を参照してください。
  
## <a name="app-management-services"></a>アプリ管理サービス
<a name="bkmk_AppManagementServices"> </a>

アプリ管理サービスのデータベースには、SharePoint のすべてのアプリのライセンス情報が保存されます。 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS:アプリケーション スコープの外部コンテンツ タイプ (ECT)
<a name="bkmk_AppScopedExternalContentTypes"> </a>

SharePoint に新しいアプリモデルを追加することで、Business Connectivity Services (BCS) は、ファームレベルではなく、アプリレベルで外部コンテンツタイプの範囲を変更できるようになりました。 これにより、アプリ開発者は、アプリ内で外部データを使用できるようになります。 アプリを対象[範囲とする外部コンテンツタイプ](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint)の詳細について説明します。
  
## <a name="bcs-business-data-web-parts"></a>BCS: ビジネスデータ Web パーツ
<a name="bkmk_BCSBusinessDataWebparts"> </a>

ビジネスデータ Web パーツは、外部データを操作する特別な web パーツです。 これらは標準の SharePoint Web パーツと同様に使用されますが、外部データへの接続の XML 記述である外部コンテンツタイプに基づいています。 
  
## <a name="bcs-external-list"></a>BCS:外部リスト
<a name="bkmk_BCSExternalList"> </a>

外部リストは外部データソースのデータを表示する特殊な SharePoint リストです。外部リストはデータソースを表す外部コンテンツ タイプを基に作成されます。外部リストにより、ユーザーは使い慣れた SharePoint インターフェイスでデータを使用することができます。[外部コンテンツ タイプ](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution)について詳細情報を参照してください。 
  
## <a name="bcs-odata-connector"></a>BCS:OData コネクタ
<a name="bkmk_OdataConnector"> </a>

OData コネクタは SharePoint の新機能です。OData コネクタにより、Business Connectivity Services (BCS) で外部リスト、ビジネス データ Web パーツ、およびカスタム ユーザー インターフェイスのデータソースとして RESTful な OData エンドポイントを使用することができます。
  
## <a name="bcs-rich-client-integration"></a>BCS:リッチ クライアントの統合
<a name="bkmk_BCSRichClientIntegration"> </a>

SharePoint Online のカスタマーは利用できません。Business Connectivity Services (BCS) は、相補的なクライアント側およびサーバー側アーキテクチャを使用するため、Outlook や Excel などの Office クライアントで外部コンテンツ タイプを通じて SharePoint に公開された外部データを直接操作することができます。[Business Connectivity Services Client Runtime](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14))について詳細情報を参照してください。
  
## <a name="client-object-model-om"></a>クライアント オブジェクト モデル (OM)
<a name="bkmk_ClientObjectModel"> </a>

SharePoint 2013 には, .NET、Silverlight、モバイルというマネージ コード用の 3 つのクライアント オブジェクト モデルがあります。また、SharePoint には JavaScript クライアント オブジェクト モデルも含まれています。[SharePoint 2013 での適切な API セットの選択](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint)について詳細情報を参照してください。
  
## <a name="custom-site-provisioning-page"></a>カスタム サイト プロビジョニング ページ
<a name="bkmk_CustomSiteProvisioning"> </a>

SharePoint Online のカスタマーはこの機能を利用できません。SharePoint Server 2013 のカスタマーは、ユーザーによるサイト要求と早期のサイト利用開始に迅速、容易に対応できます。
  
## <a name="developer-site"></a>開発者向けサイト
<a name="bkmk_DeveloperSite"> </a>

Office 365 の開発者向けサイトを開発およびテスト環境として使用すると、セットアップに要する時間を短縮して、SharePoint 用のアプリの作成、テスト、展開を始めることができます。[Office 365 開発者向けサイトへのサインアップ](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription)について詳細情報を参照してください。
  
## <a name="forms-based-applications"></a>フォーム ベースのアプリケーション
<a name="bkmk_FormsBasedApplications"> </a>

フォーム ビューは基本的にコントロールを含むビューです。フォーム ベース アプリケーションでは、ユーザーはアプリケーション内で 1 つまたは複数のフォームを作成して使用することができます。[フォーム ベースのアプリケーション](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60))について詳細情報を参照してください。
  
## <a name="full-trust-solutions"></a>完全信頼ソリューション
<a name="bkmk_FullTrustSolutions"> </a>

SharePoint Online のカスタマーはこの機能を利用できません。SharePoint Server 2013 のカスタマーは、完全信頼ソリューションを作成できます。これはファーム ソリューションとも呼ばれます。SharePoint 用のアプリと異なり、ファーム ソリューションには、SharePoint サーバーに展開され、SharePoint のサーバー オブジェクト モデルを呼び出すコードが含まれます。これらのアセンブリは常に完全信頼で実行されます。ファーム ソリューションは、カスタム タイマー ジョブ、Windows PowerShell のカスタム コマンドレット、およびサーバーの全体管理の拡張機能など、SharePoint 管理機能をカスタマイズするのに使用します。[SharePoint 2013 でのファーム ソリューションの作成](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint)について詳細情報を参照してください。
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services
<a name="bkmk_InfoPathFormsServices"> </a>

フォーム サービスは、InfoPath でデザインされたフォーム テンプレートに基づいて、SharePoint に Web ブラウザーから使用するフォーム入力機能を提供します。[InfoPath Forms Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))について詳細情報を参照してください。
  
## <a name="javascript-object-model"></a>JavaScript オブジェクト モデル
<a name="bkmk_JavaScriptObjectModel"> </a>

SharePoint では、インライン スクリプトまたは個別の .js ファイルで使用するための JavaScript オブジェクト モデルが利用できます。JavaScript オブジェクト モデルは, .NET Framework や Silverlight クライアント オブジェクト モデルと同じ機能を備えています。JavaScript オブジェクト モデルは、アプリに SharePoint のカスタム コードを含めるのに便利です。また、Web 開発者は JavaScript のスキルを活用することで、最小限の習得期間で SharePoint アプリケーションを作成することができます。[SharePoint 2013 の JavaScript API リファレンス](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15))について詳細情報を参照してください。
  
## <a name="remote-event-receiver"></a>リモート イベント レシーバー
<a name="bkmk_RemoteEventReceiver"> </a>

SharePoint 用アプリのイベントを処理するため、開発者はリモート イベント レシーバーとアプリ イベント レシーバーを作成します。リモート イベント レシーバーは、アプリ内のアイテム (リスト、リスト項目、Web など) に対して発生したイベントを処理します。[SharePoint アプリのイベントの処理](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins)について詳細情報を参照してください。 
  
## <a name="rest-apis"></a>REST API
<a name="bkmk_RESTAPI"> </a>

SharePoint 2013 では、OData プロトコルを使用して SharePoint リスト データで CRUD 処理を行う REST (Representational State Transfer) Web サービスの実装が利用できます。これは、JavaScript を使用せず, .NET Framework または Microsoft Silverlight プラットフォーム上で構築されたものではないクライアント テクノロジから SharePoint データにアクセスする場合に使用します。[SharePoint 2013 REST サービスを使用したプログラミング](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests)について詳細情報を参照してください。
  
## <a name="sharepoint-design-manager"></a>SharePoint デザイン マネージャー
<a name="bkmk_SharePointDesignerManager"> </a>

デザイン マネージャーを使用すると、サイトのブランディングに使用するデザイン アセットをステップバイステップで作成できます。デザイン アセット (画像、HTML、CSS など) をアップロードした後に、マスター ページとページ レイアウトを作成します。[SharePoint 2013 サイト開発](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development)について詳細情報を参照してください。
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013
<a name="bkmk_SharePointDesigner"> </a>

SharePoint Designer を使用すると、上級ユーザーおよび開発者はビジネス ニーズに対応して SharePoint ソリューションをすばやく作成できます。[開発者向け SharePoint Designer](https://go.microsoft.com/fwlink/?LinkId=271294) について詳細情報を参照してください。
  
## <a name="sharepoint-framework"></a>SharePoint Framework
<a name="bkmk_SharePointFramework"> </a>

SharePoint Framework (SPFx) は、クライアント側の SharePoint の開発、SharePoint データとの容易な統合、オープンソース ツーリングのサポートをすべてサポートするページと Web パーツ モデルです。 詳細については、「 [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)」を参照してください。
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>SharePoint 2010 ワークフロー (標準)
<a name="bkmk_Worflow2010outofthebox"> </a>

SharePoint に含まれる標準ワークフローを使用して、一般的なビジネス プロセスをモデル化します。
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>SharePoint 2013 および SharePoint 2016 のワークフロー
<a name="bkmk_Workflow2013"> </a>

SharePoint 2013 と SharePoint 2016 のワークフローは、以前のバージョンから大幅に再設計された Windows Workflow Foundation 4 (WF) によって稼働しています。 新しいワークフローインフラストラクチャの最も顕著な機能は、ワークフロー実行ホストとして Azure を導入したことです。 [SharePoint のワークフローの新機能](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint)について説明します。
  
## <a name="feature-availability"></a>機能の可用性
<a name="bkmk_Workflow2013"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[SharePoint Online サービスの説明](sharepoint-online-service-description.md)」を参照してください。
  

