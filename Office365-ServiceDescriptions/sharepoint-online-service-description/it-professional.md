---
title: IT プロフェッショナル
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-it-professional-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b6db338b-522b-44bf-afb7-1de7827691d0
description: SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の SharePoint 機能を使用すると、IT プロフェッショナルは組織の SharePoint 環境のセキュリティを確保し、管理することができます。
ms.openlocfilehash: 70868f9c00c42318013d1fdc8449668a2461f34a
ms.sourcegitcommit: 0f5ad374ff3559c10a1665d894d68665dbd1214b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/21/2019
ms.locfileid: "35131311"
---
# <a name="it-professional"></a>IT プロフェッショナル

SharePoint Online は、組織がデジタル情報を格納、共有、および管理するのに役立つ Web ベースのツールとテクノロジの集合です。 このホスト型サービスは Microsoft SharePoint Server 2013 上に構築されており、プロジェクトの作業、データとドキュメントの一元的な保存、および他のユーザーとの情報の共有を行うのに適しています。 次の SharePoint 機能を使用すると、IT プロフェッショナルは組織の SharePoint 環境のセキュリティを確保し、管理することができます。 
  
## <a name="active-directory-synchronization"></a>Active Directory の同期
<a name="bkmk_ActiveDirectorySynchronization"> </a>

企業のローカル Active Directory 環境に既存のユーザーが存在する場合、これらのユーザーをエンタープライズ ディレクトリ用に Office 365 と同期するためのツールがあります。同期後に、Office 365 ディレクトリから SharePoint Online ユーザー プロファイルが提供されます。「[オンプレミス ID と Azure Active Directory の統合](https://go.microsoft.com/fwlink/p/?linkid=270051)」の詳細情報を参照してください。
  
## <a name="alternate-access-mapping-aam"></a>Alternate Access Mapping (AAM)
<a name="bkmk_AlternateAccessMapping"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 のカスタマーは、代替アクセス マッピングを構成して、インターネット インフォメーション サービス (IIS) が受信した Web 要求の URL がユーザーが入力した URL と異なる要求をマップできます。
  
## <a name="anti-malware-protection"></a>マルウェア対策保護
<a name="bkmk_AntiMalware"> </a>

ドキュメント ライブラリにアップロードされ、保存されたファイルのためのマルウェア対策保護を提供します。この保護は Microsoft マルウェア対策エンジンによって提供されており、Exchange にも統合されています。このマルウェア対策サービスは、すべての SharePoint Online のコンテンツ フロント エンド (CFES) 上で実行されます。
  
## <a name="claims-based-authentication-support"></a>Claims-Based Authentication Support
<a name="bkmk_ClaimsBasedAuthenticationSupport"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 のカスタマーは、SharePoint Server 2013 のサーバー間認証およびアプリ認証をサポートしている Web アプリケーションに対してクレームベース認証を構成します。「[SharePoint 2013 でクレーム ベースの Web アプリケーションを作成する](https://go.microsoft.com/fwlink/p/?LinkId=270982)」の詳細情報を参照してください。
  
## <a name="data-loss-prevention"></a>データ損失防止
<a name="bkmk_DLP"> </a> 

データ損失防止 (DLP) は SharePoint Online に格納された機密データを識別します。機密データを識別することにより、組織へのリスクを軽減できます。電子情報開示センターを使用して、組織内の機密情報の種類を検索できます。機密性の高いコンテンツが検出されると、記載および格納され、電子情報開示センターで承認されているユーザーのみが使用できます。また、分類結果を簡単にエクスポートすることもできます。機密データの種類の詳細については、「[Exchange での機密情報の種類の検索基準](https://technet.microsoft.com/library/jj150541%28v=exchg.150%29.aspx)」を参照してください。「[サイトに保存された機密データを確認するために SharePoint Online で DLP を使用する](https://docs.microsoft.com/office365/securitycompliance/protect-sharepoint-online-files-with-office-365-labels-and-dlp)」方法の詳細を参照してください。
  
## <a name="encryption-at-rest"></a>暗号化
<a name="bkmk_EncryptionAtRest"> </a>

SharePoint Online 用の暗号化には 2 つのレベルがあります。 SharePoint Online の暗号化は、すべての顧客のドキュメント ライブラリ、ユーザーの OneDrive for Business のデータ、および Office 365 データ センター内に存在するサイトのデータに対して既定で BitLocker 暗号化を提供します。ファイルごとの暗号化の場合、SharePoint Online と OneDrive for Business に格納されている個々のファイルはすべて、独自の一意のキーを使用して暗号化されます。 SharePoint Online と OneDrive for Business では、送信中の暗号化を常に提供します。静止時の暗号化の詳細については、「[Office 365  セキュリティおよびコンプライアンスにおける最新のイノベーション](https://blogs.office.com/2014/10/28/office-365-latest-innovations-security-compliance/)」を参照してください。
  
## <a name="host-header-site-collections"></a>Host Header Site Collections
<a name="bkmk_HostHeaderSiteCollections"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 サイト コレクションには、固有のホスト ヘッダーを設定できます。ホスト名付きのサイト コレクションを作成すると、組織では複数のサイト コレクションの URL を修飾して、ユーザーが覚えやすくできます。
  
## <a name="mobile-device-management-for-office-365"></a>Office 365 のモバイル デバイス管理
<a name="bkmk_MDM"> </a>

Mobile Device Management (MDM) for Office 365 を使用して、デバイスのセキュリティ ポリシーやアクセス ルールを設定したり、紛失や盗難があったときにモバイル デバイスのデータをワイプしたりできます。MDM for Office 365 を使用すると、WindowsPhone、Android、iPhone、iPad など、多くの種類のモバイル デバイスを管理できます。組織内のユーザーによって使用されるモバイル デバイスを管理するには、各ユーザーが該当する Office 365 ライセンスを持っていることと、ユーザーのデバイスを MDM for Office 365 に登録することが必要です。 
  
## <a name="oauth"></a>OAuth
<a name="bkmk_OAuth"> </a>

Oauth は、アプリ ID を作成および管理するためのインターネット プロトコルです。Oauth を使用すると、アプリ ID をユーザー ID と切り離して認識できるようになります。このクロスプラットフォーム メカニズムでは、現在のユーザーが持つアクセス許可より多くのアクセス許可をアプリに付与できます。「[SharePoint 2013 の認証の新機能](https://go.microsoft.com/fwlink/p/?LinkId=270988)」の詳細情報を参照してください。
  
## <a name="patch-management"></a>Patch Management
<a name="bkmk_PatchManagement"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 の更新プログラムは、次の 2 段階フェーズのプロセスを使用してリリースされます。パッチおよびアップグレード。パッチ段階では、新しいバイナリ ファイルが全体管理サーバーにコピーされます。置き換える必要があるファイルを使用しているすべてのサービスは、一時的に停止されます。サーバーを再起動する必要がある場合もいくつかあります。
  
## <a name="quota-templates"></a>Quota Templates
<a name="bkmk_QuotaTemplates"> </a>

SharePoint Online のカスタマーは利用できません。クォータ テンプレートは、サイト コレクションに格納できるデータの最大量を指定する記憶域の制限値から構成されています。記憶域の制限に達すると、クォータ テンプレートは、サイト コレクション管理者に警告の電子メールをトリガーすることもできます。SharePoint Online 管理者と SharePoint Server 2013 ファーム管理者は、すべてのサイト コレクションに適用可能なクォータ テンプレートを作成できます。
  
## <a name="read-only-database-support"></a>Read-Only Database Support
<a name="bkmk_ReadOnlyDatabaseSupport"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 管理者は、コンテンツ データベースを読み取り専用に設定できます。
  
## <a name="remote-blob-storage"></a>Remote BLOB Storage
<a name="bkmk_RemoteBLOBStorage"> </a>

SharePoint Online のカスタマーは利用できません。リモート BLOB ストレージ (RBS) は、Microsoft SQL Server 用のアドオン機能パックです。RBS は、バイナリ ラージ オブジェクト (BLOB) のストレージをデータベース サーバーからコモディティ ストレージ ソリューションに移動するように設計されています。Microsoft SharePoint Server 2013 のコンテンツ データベースが 4 GB 以上の場合、データ ストレージ ソリューションの一部として RBS を使用することを検討してください。
  
## <a name="request-management"></a>依頼管理
<a name="bkmk_RequestManagement"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 管理者は Request Manager を使用することによって、要求のルーティングと調整を行いパフォーマンスを向上させるルールを定義できます。
  
## <a name="resource-throttling"></a>リソースの調整
<a name="bkmk_Resourcethrottling"> </a>

SharePoint Online のカスタマーは利用できません。リソースの調整を使用すると、SharePoint Server 2013 管理者には、サーバー リソースおよび Web アプリケーション用の大きいリストを監視および調整するオプションが与えられます。リソースの調整では、CPU、メモリ、待機時間などのリソースを監視し、5 秒ごとにリソースを確認できます。 
  
## <a name="service-application-platform"></a>Service Application Platform
<a name="bkmk_ServiceApplicationPlatform"> </a>

SharePoint サービスは、任意の Web アプリケーションから個別に使用できます。 このプラットフォームでは、アプリケーションのニーズに応じてサービスを柔軟に使用できます。 Web Analytics は、もはやサービス アプリケーションではありません。 分析とレポート作成プロセスは、Search service アプリケーションに組み込まれました。 Web 用の Office はサービスアプリケーションではなくなりました。 Office Web Apps サーバーは別のサーバー製品になりました。 組織が加入している Office 365 プランによっては、web 用の Office を SharePoint Online のお客様が利用できる場合があります。 「[SharePoint サービス アプリケーション](https://go.microsoft.com/fwlink/p/?LinkId=270989)」の詳細情報を参照してください。
  
## <a name="sharepoint-health-analyzer"></a>SharePoint Health Analyzer
<a name="bkmk_SharePointHealthAnalyzer"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 の新機能であるサイト コレクションのアップグレード前正常性チェックは、サイト コレクションを調べ、潜在的なアップグレードの問題や問題の対処方法を記載したレポートを生成します。たとえば、ファイルがカスタマイズされている場合、そのフラグが付けられます。こうすることで、組織では、カスタム ファイルを特定し、必要に応じてサイト定義でデフォルトのテンプレートにリセットできます。
  
## <a name="sharepoint-admin-center-office-365"></a>SharePoint 管理センター (Office 365)
<a name="bkmk_SharePointOnlineAdminCenter"> </a>

SharePoint Online の特定のカスタマーにのみ利用可能な SharePoint 管理センターを使用すると、管理者は次のような機能を管理できます。
  
- サイト コレクション
    
- InfoPath フォーム
    
- ユーザー プロファイル
    
- Business Connectivity Services (BCS)
    
- 管理されたメタデータおよび用語ストア
    
- レコードの管理
    
- 検索
    
- Secure Store
    
- SharePoint 用アプリ
    
- 外部共有
    
- Information Rights Management
    
- セルフサービス サイト作成
    
「[一般法人向け Office 365 の SharePoint サイト - 管理者向けヘルプ](https://go.microsoft.com/fwlink/p/?LinkId=270990)」の詳細情報を参照してください。
  
## <a name="site-collection-compliance-policies"></a>Site Collection Compliance Policies
<a name="bkmk_SiteCollectionCompliancePolicies"> </a>

サイト コレクション ポリシーは、サイト コレクションの最上位サイトのサイト コレクション ポリシー一覧で作成できます。サイト コレクション ポリシーを作成したら、他のサイト コレクションの管理者がサイト コレクション ポリシー一覧にインポートできるようにエクスポートできます。エクスポート可能なサイト コレクション ポリシーを作成すると、SharePoint 管理者は組織内のサイト全体にわたって情報管理ポリシーを標準化できます。
  
## <a name="usage-reporting-and-logging"></a>Usage Reporting and Logging
<a name="bkmk_UsageReportingandLogging"> </a>

SharePoint Online のカスタマーは利用できません。SharePoint Server 2013 管理者は監査ログ レポートを使用して、サイト コレクションの監査ログのデータを表示できます。「[監査ログ レポートを表示する](https://go.microsoft.com/fwlink/p/?LinkId=270992)」の詳細情報を参照してください。
  
## <a name="windows-powershell-support"></a>Windows PowerShell Support
<a name="bkmk_WindowsPowerShellSupport"> </a>

SharePoint Online 管理者は、SharePoint Online Windows PowerShell コマンドレットを使用して、次のようなスクリプトを作成して、サブスクリプション用の管理タスクを自動化することができます。
  
- サイトの作成
    
- サイトのアップグレードの評価
    
- サイトのアップグレード
    
- SharePoint ユーザーおよびグループの追加と削除
    
- サイトの修復
    
- ごみ箱の管理
    
「[SharePoint Online 管理シェルの概要](https://go.microsoft.com/fwlink/p/?LinkId=270993)」の使用方法を参照してください。 
  
## <a name="feature-availability"></a>機能の可用性
<a name="bkmk_WindowsPowerShellSupport"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[SharePoint Online サービスの説明](sharepoint-online-service-description.md)」を参照してください。
  

