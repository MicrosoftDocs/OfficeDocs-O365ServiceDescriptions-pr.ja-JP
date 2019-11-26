---
title: 開発者
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の機能は、SharePoint の機能を拡張するアプリやソリューションを構築する開発者をサポートしています。
ms.openlocfilehash: 56ea1e5a083c4dd35eab8da537b77e802551ce32
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/26/2019
ms.locfileid: "39263118"
---
# <a name="developer"></a>Developer

SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の機能は、SharePoint の機能を拡張するアプリやソリューションを構築する開発者をサポートしています。
  
## <a name="app-catalog-sharepoint"></a>アプリカタログ (SharePoint)

アプリを SharePoint 配置上にホストされた社内のカタログに公開し、その SharePoint 配置にアクセスできるユーザーが利用できるようにします。[Office と SharePoint 用アプリの公開](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store)について詳細情報を参照してください。
  
## <a name="app-deployment-cloud-hosted-apps"></a>アプリの展開: クラウドでホストされるアプリ

クラウドでホストされる SharePoint アプリには、少なくとも 1 つのリモート コンポーネントが含まれ、SharePoint でホストされるコンポーネントが含まれる場合もあります。[SharePoint アプリのホスティング オプション](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)について詳細情報を参照してください。 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>アプリの展開: SharePoint でホストされるアプリ

SharePoint ホスト型アプリを使用すると、リストや web パーツなどの一般的な SharePoint 成果物を再利用できます。 このアプローチを採用する場合、JavaScript しか使用できず、サーバー側コードは使用できません。 詳細については、「[SharePoint アドインを開発およびホスティングするためのパターンを選択する](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)」を参照してください。
  
## <a name="app-management-service"></a>App Management Service

アプリ管理サービスのデータベースには、SharePoint のすべてのアプリのライセンス情報が保存されます。 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: アプリを対象範囲とする外部コンテンツタイプ (Ect)

SharePoint に新しいアプリモデルを追加することで、Business Connectivity Services (BCS) は、ファームレベルではなく、アプリレベルで外部コンテンツタイプの範囲を変更できるようになりました。 これにより、アプリ開発者は、アプリ内で外部データを使用できるようになります。 [アプリを対象範囲とする外部コンテンツタイプ](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint)の詳細については、こちらを参照してください。
  
## <a name="bcs-business-data-web-parts"></a>BCS: ビジネスデータ Web パーツ

ビジネスデータ Web パーツは、外部データを操作する特別な web パーツです。 これらは SharePoint の標準の Web パーツと同様に使用されますが、外部データとの接続に関する XML 記述である外部コンテンツ タイプに基づいています。 
  
## <a name="bcs-external-list"></a>BCS: 外部リスト

外部リストは外部データソースのデータを表示する特殊な SharePoint リストです。外部リストはデータソースを表す外部コンテンツ タイプを基に作成されます。外部リストにより、ユーザーは使い慣れた SharePoint インターフェイスでデータを使用することができます。[外部コンテンツ タイプ](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution)について詳細情報を参照してください。 
  
## <a name="bcs-odata-connector"></a>BCS:OData コネクタ

OData コネクタは SharePoint の新機能です。 これにより、Business Connectivity Services (BCS) では、外部リスト、ビジネスデータ Web パーツ、およびカスタムユーザーインターフェイスのデータソースとして RESTful OData エンドポイントを使用することができます。
  
## <a name="bcs-rich-client-integration"></a>BCS: リッチクライアントの統合

SharePoint Online のカスタマーは利用できません。Business Connectivity Services (BCS) は、相補的なクライアント側およびサーバー側アーキテクチャを使用するため、Outlook や Excel などの Office クライアントで外部コンテンツ タイプを通じて SharePoint に公開された外部データを直接操作することができます。[Business Connectivity Services Client Runtime](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14))について詳細情報を参照してください。
  
## <a name="client-object-model-om"></a>クライアントオブジェクトモデル (OM)

SharePoint 2013 には, .NET、Silverlight、モバイルというマネージ コード用の 3 つのクライアント オブジェクト モデルがあります。また、SharePoint には JavaScript クライアント オブジェクト モデルも含まれています。[SharePoint 2013 での適切な API セットの選択](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint)について詳細情報を参照してください。
  
## <a name="custom-site-provisioning-page"></a>カスタムサイトプロビジョニングページ

SharePoint Online のカスタマーはこの機能を利用できません。SharePoint Server 2013 のカスタマーは、ユーザーによるサイト要求と早期のサイト利用開始に迅速、容易に対応できます。
  
## <a name="developer-site"></a>開発者向けサイト

Office 365 開発者向けサイトを開発およびテスト環境として使用して、セットアップ時間を短縮し、SharePoint 用アプリの作成、テスト、および展開を開始します。 詳細について[は、「Office 365 開発者向けサイトの](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription)サインアップ」を参照してください。
  
## <a name="forms-based-applications"></a>フォームベースのアプリケーション

フォーム ビューは基本的にコントロールを含むビューです。 フォームベースのアプリケーションでは、アプリケーション内で1つまたは複数のフォームを作成して使用できます。 [フォームベースアプリケーション](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60))の詳細については、こちらを参照してください。
  
## <a name="full-trust-solutions"></a>完全信頼ソリューション

SharePoint Online のカスタマーは利用できません。 SharePoint Server 2013 のお客様は、完全信頼ソリューション (ファームソリューションとも呼ばれます) を作成できます。 SharePoint 用アプリとは異なり、ファームソリューションには、SharePoint サーバーに展開され、SharePoint のサーバーオブジェクトモデルを呼び出すためのコードが含まれています。 これらのアセンブリは常に完全信頼で実行されます。 ファーム ソリューションは、カスタム タイマー ジョブ、Windows PowerShell のカスタム コマンドレット、およびサーバーの全体管理の拡張機能など、SharePoint 管理機能をカスタマイズするのに使用します。 詳細について[は、「SharePoint 2013 でのファームソリューションの構築](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint)について」をご覧ください。
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services

Forms Service は、InfoPath でデザインされたフォームテンプレートに基づいて、SharePoint での web ブラウザーフォーム入力を提供します。 詳細については[、「InfoPath Forms Services」を参照してください。](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))
  
## <a name="javascript-object-model"></a>JavaScript オブジェクト モデル

SharePoint では、インライン スクリプトまたは個別の .js ファイルで使用するための JavaScript オブジェクト モデルが利用できます。 JavaScript オブジェクト モデルは、.NET Framework や Silverlight クライアント オブジェクト モデルと同じ機能を備えています。 JavaScript オブジェクト モデルは、アプリに SharePoint のカスタム コードを含めるのに便利です。 また、web 開発者は、既存の JavaScript スキルを使用して、最小限の学習曲線で SharePoint アプリケーションを作成することもできます。 詳細について[は、「JAVASCRIPT API reference For SharePoint 2013」を参照](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15))してください。
  
## <a name="remote-event-receiver"></a>リモート イベント レシーバー

SharePoint 用アプリのイベントを処理するため、開発者はリモート イベント レシーバーとアプリ イベント レシーバーを作成します。リモート イベント レシーバーは、アプリ内のアイテム (リスト、リスト項目、Web など) に対して発生したイベントを処理します。[SharePoint アプリのイベントの処理](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins)について詳細情報を参照してください。 
  
## <a name="rest-apis"></a>REST API

SharePoint 2013 では、OData プロトコルを使用して SharePoint リスト データで CRUD 処理を行う REST (Representational State Transfer) Web サービスの実装が利用できます。これは、JavaScript を使用せず, .NET Framework または Microsoft Silverlight プラットフォーム上で構築されたものではないクライアント テクノロジから SharePoint データにアクセスする場合に使用します。[SharePoint 2013 REST サービスを使用したプログラミング](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests)について詳細情報を参照してください。
  
## <a name="sharepoint-design-manager"></a>SharePoint デザイン マネージャー

デザイン マネージャーを使用すると、サイトのブランディングに使用するデザイン アセットをステップバイステップで作成できます。デザイン アセット (画像、HTML、CSS など) をアップロードした後に、マスター ページとページ レイアウトを作成します。[SharePoint 2013 サイト開発](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development)について詳細情報を参照してください。
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013

SharePoint Designer を使用すると、高度なユーザーおよび開発者は、ビジネスニーズに応じて SharePoint ソリューションをすばやく作成できます。 [開発者向けの SharePoint Designer の](https://go.microsoft.com/fwlink/?LinkId=271294)詳細について説明します。
  
## <a name="sharepoint-framework"></a>SharePoint Framework

SharePoint Framework (SPFx) は、クライアント側の SharePoint の開発、SharePoint データとの容易な統合、オープンソース ツーリングのサポートをすべてサポートするページと Web パーツ モデルです。 詳細については、「 [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)」を参照してください。
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>SharePoint 2010 ワークフロー (標準)

SharePoint に含まれる標準ワークフローを使用して、一般的なビジネス プロセスをモデル化します。
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>SharePoint 2013 および SharePoint 2016 のワークフロー

SharePoint 2013 と SharePoint 2016 のワークフローは、以前のバージョンから大幅に再設計された Windows Workflow Foundation 4 (WF) によって稼働しています。 新しいワークフローインフラストラクチャの最も顕著な機能は、ワークフロー実行ホストとして Azure を導入したことです。 [SharePoint のワークフローの新機能](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint)について説明します。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [SharePoint Online サービスの説明](sharepoint-online-service-description.md)」を参照してください。
  

