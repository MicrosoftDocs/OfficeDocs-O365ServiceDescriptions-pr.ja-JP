---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
ms.date: 3/4/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 米国の公的機関の固有の要件および進化する要件に対応して、Microsoft は office 365 us government プラン (oroffice 365 us government) を作成しています。 このセクションでは、Office 365 US Government 固有の機能の概要について説明します。 この補足セクションは、「Office 365 サービスの説明」に記載することをお勧めします。
ms.openlocfilehash: 6d10de59be0f2f8e187933d47d24a4108c69478a
ms.sourcegitcommit: 7248888900104d79c5f53cafb1000140eefac7eb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/12/2019
ms.locfileid: "31825225"
---
# <a name="office-365-us-government"></a>Office 365 US Government

米国の公的機関の固有かつ進化する要件への対応として、Microsoft は office 365 us government プラン (または「office 365 US government」) を作成しています。 このセクションでは、Office 365 US Government 固有の機能の概要について説明します。 この補足セクションは、「 [Office 365 サービスの説明](../../office-365-service-descriptions-technet-library.md)」に記載することをお勧めします。
  
## <a name="how-to-use-this-service-description-section"></a>このサービスの説明セクションの使用方法
<a name="TopOfPage"> </a>

Office 365 US Government のサービスの説明は、全般的な Office 365 のサービスの説明へのオーバーレイとして機能するよう設計されています。Office 365 Enterprise 製品と比較した独自のコミットメントと相違点を定義します。
  
## <a name="about-office-365-us-government-environments"></a>Office 365 US Government 環境について
<a name="BM1_About"> </a>

Office 365 US Government プランは、月単位のサブスクリプションであり、ユーザーへのライセンス数は無制限です。 
  
- **Office 365 GCC** 環境は、FedRAMP Moderate を含むクラウド サービスへの連邦政府の要件と、刑事司法および連邦税務情報システム (CJI データ型および FTI データ型) の要件に準拠します。 
    
- **Office 365 GCC High および DoD** 環境は、米国国防総省のセキュリティ要件のガイドライン、国防総省調達規則 (DFARS)、武器国際取引に関する規制 (ITAR) に準拠します。 
    
Office 365 US Government には、Office 365 の特長と機能に加え、次のように、Office 365 US Government を使用する組織に向けた独特の特長が備わっています。
  
- 組織の顧客コンテンツは、Microsoft の商用の Office 365 サービスの顧客コンテンツと論理的に分離されます。
    
- 組織の顧客コンテンツは、米国内に格納されます。
    
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
    
- Office 365 US Government は、米国公的機関のお客様に必要な資格および認定に準拠しています。
    
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-eligibility"></a>お客様の適格性
<a name="BM2-customer"> </a>

Office 365 US Government を使用できるのは、(1) 米国連邦、州、地方、部族、地域関連の行政機関と、(2) 政府の規制や要件の対象となるデータを取り扱い、Office 365 US Government を使用することがこれらの要件を満たす上で適切な、適格性の検証の対象となるその他の機関です。Microsoft による適格性の検証には、武器国際取引に関する規制 (ITAR) の対象となるデータ、FBI の米国刑事司法情報サービス (CJIS) ポリシーの対象となる法律施行データ、またはその他の政府が規制または制御するデータの取り扱いに関する検証が含まれます。検証には、ITAR データに関する米国国務省への登録の証明や、データの取り扱いに関する特定の要件についての政府機関による公的支援が必要な場合があります。Office 365 DoD 環境は、米国国防総省専用です。
  
利用資格が、Office 365 US Government 製品間で一貫している限り、Microsoft は GCC High 環境に対して DFARS および ITAR の契約の言語にのみ同意します。
  
Office 365 US Government の適格性に関してご質問がある機関は、アカウント チームにお問い合わせください。
  
お客様の Office 365 US Government の契約の更新時には、適格性の再検証が必要になります。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>米国内の顧客コンテンツ
<a name="BM3-withinUSA"> </a>

Office 365 US Government サービスは、米国内に物理的に配置されたデータ センターから提供されます。次の顧客コンテンツは、米国に配置されたデータ センターにのみ格納されます。 
  
- Exchange Online メールボックスの内容 (メール本文、予定表のエントリ、メールの添付ファイルの内容)。
    
- SharePoint Online サイトのコンテンツと、そのサイト内に格納されているファイル。
    
- Skype for Business で保存された会話、アップロードされたドキュメント、ホワイトボード セッション。
    
> [!NOTE]
> 一般的な使用法では、Skype for Business が顧客コンテンツを保管することはありませんが、保管する場合には、米国内のデータセンターに保管されます。 
  
米国内にいるユーザーが Office Online (旧称 Office Web Apps) を使用している場合、あるいはActive Directory フェデレーション サービス (AD FS) 2.0 を使用していてユーザーがシングル サインオンでサービスに接続するようにポリシーをセットアップしている場合は、一時的に Office Online にキャッシュされる顧客コンテンツは、米国内にあることになります。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government およびサード パーティ サービス
<a name="BM4-3rdParty"> </a>

Office 365 は、サード パーティ アプリケーションを SharePoint Online サイト、Skype for Business、Office 365 ProPlus に含まれる Office アプリケーション (Word、Excel、PowerPoint、Outlook など)、Outlook Web App に統合する機能を提供します。さらに、Office 365 はサード パーティ サービス プロバイダーとの統合をサポートしています。これらのサード パーティ アプリケーションおよびサービスには、組織の顧客データを Office 365 インフラストラクチャ外部のサード パーティ システムで保管、送信、処理する場合があるため、Office 365 のコンプライアンスおよびデータ保護に関するコミットメントは適用されません。組織でサード パーティのサービスを使用することが適切であるかどうか査定する際には、そのサード パーティのプライバシーおよびコンプライアンスに関する声明を検討することをお勧めします。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>管理者に制限されたデータ アクセス
<a name="BM5-Restricted"> </a>

Microsoft 管理者による Office 365 US Government のお客様のコンテンツへのアクセスは、スクリーン担当者に制限されています。 審査レベルの詳細については、それぞれの環境 (gcc または gcc High および DoD) について、「サービスの説明」ページを参照してください。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>fasttrack センターのオンボードアシスタント
<a name="BM5-Restricted"> </a>

office 365<sup>1</sup>の fasttrack センターの特典を使用すると、fasttrack スペシャリストとリモートで作業して、office 365 環境を使用できる状態にして、組織内での展開と使用を計画できます。 FastTrack プロセスでは、オンボーディングと、ユーザー採用サービスが提供されます。 
  
オンボーディングは、次のもので構成されます。
  
- コアオンボード-これらは、必要に応じて、テナントの構成と azure Active Directory (azure AD) との統合に必要なタスクです。 コア オンボーディングは、他の対象のサービスのオンボーディングのベースラインも提供します。
    
- サービスオンボードおよび移行サービスのオンボードタスクは、テナント内のシナリオを有効にします。 データ移行 (電子メールやファイルを含む) については、「[データ移行](https://aka.ms/whatcanmigrate)」で説明します。<sup>2</sup>
    
ユーザー採用サービスは、ユーザーが使用できるサービスを認識し、そのサービスを使用してビジネス価値を高めることができるようにするガイダンスを提供するタスクで構成されています。この支援は、オンボーディング アクティビティと並行して行われます。
  
fasttrack センタープロセスの詳細については、[こちら](https://aka.ms/whatistheprocess)を参照してください。 契約の役割と責任の内訳については、 [fasttrack の責任](https://aka.ms/whatdoesftcdo)だけでなく、[責任](https://aka.ms/whatdowedo)についても確認してください。
  
<sup>1</sup> fasttrack サービスを受けるには、対象となる[プラン](https://aka.ms/whocanbenefit)のリストから少なくとも50のライセンスを購入する必要があります。 
  
<sup>2</sup>データ移行サービスは、500またはそれ以上のライセンスを持つ Office 365 テナントで使用できます。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>fasttrack によって実行されたデータ移行
<a name="BM5-Restricted"> </a>

[fasttrack](https://fasttrack.microsoft.com/)移行特典を選択する場合は、データ移行を管理するチームへのアクセス権を付与する必要があります。 これらの人員は米国市民で、Office 365 US Government サービスのお客様に移行を実行する前に、次のバックグラウンドチェックが行われています。 
  
||||
|:-----|:-----|:-----|
|**背景調査** <br/> |**GCC** <br/> |**GCC High および DoD** <br/> |
|アメリカ国籍の確認  <br/> |はい  <br/> |はい  <br/> |
|職歴チェック  <br/> |はい  <br/> |はい  <br/> |
|学歴の確認  <br/> |はい  <br/> |はい  <br/> |
|社会保障番号 (SSN) の検索  <br/> |はい  <br/> |はい  <br/> |
|犯罪歴のチェック (7 年)  <br/> |はい  <br/> |はい  <br/> |
   
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government および Azure Government ExpressRoute
<a name="BM6-Express"> </a>

Office 365 US Government のお客様は Azure Government ExpressRoute サービスを使用して、サポートされている Office 365 サービスにパブリック インターネット経由で接続するのではなく、プライベートで接続できます。
  
サポートされているプロバイダーや価格モデルなどの詳細については、「[ExpressRoute のドキュメント](http://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)」をご確認ください。
  
Azure ExpressRoute の Office 365 サポートの詳細については、「[Azure ExpressRoute for Office 365](http://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)」をご覧ください。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>システム要件
<a name="BM9-Requirements"> </a>

Office 365 US Government プランのシステム要件については、[office.com](http://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 製品サイトの「 [Office のシステム要件](http://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)」を参照してください。 
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>セキュリティ/コンプライアンス センター
<a name="BM9-Requirements"> </a>

セキュリティ&amp;コンプライアンスセンターおよび追加情報と可用性へのリンクの詳細については、「 [Office 365 &amp;セキュリティコンプライアンスセンター](../../office-365-platform-service-description/office-365-securitycompliance-center.md)」を参照してください。
  
## <a name="service-availability-for-each-plan"></a>各プランのサービスの可用性
<a name="BM9-Requirements"> </a>

各 Office 365 プランには、Exchange Online や SharePoint Online などの個別のサービスが複数含まれています。次の表に、各 Office 365 US Government プランで使用できるサービスを示します。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 サービス** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|Office Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 ProPlus  <br/> |いいえ <br/> |あり <br/> |はい <br/> |なし  <br/> |
|Exchange Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange Online Protection  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|SharePoint Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|OneDrive for Business  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |はい<sup>1</sup> <br/> |はい  <br/> |はい  <br/> |はい<sup>1</sup> <br/> |
| 音声ビデオシステム、電話会議  <br/> |いいえ <sup>2、3</sup> <br/> |いいえ <sup>2、3</sup> <br/> |はい <sup>3、5</sup> <br/> |いいえ  <br/> |
|Power BI Pro  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |はい  <br/> |<sup>2</sup>なし <br/> |
|Project Online  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |
|Visio Online  <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |
|Yammer Enterprise  <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |
   
> <sup>1</sup> Skype for business Basic は、すべてのお客様が利用できます。 skype for business デスクトップクライアントは、ローカルにインストールされたアプリケーションで、skype for business Online を含む Office 365 プランのプレゼンス、インスタントメッセージング、および会議機能を提供します。 Office 365 ProPlus、G3、および G5 には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能を含む完全な Skype アプリケーションが含まれています。 A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup>含まれていませんが、個別のアドオンとして購入できます。 project online には、サブスクリプションの一部として project online デスクトップクライアントが含まれています。
<br/> <sup>3</sup>現時点では GCC High または DoD プランでは利用できませんが、近日中に提供されます。 
<br/><sup>4</sup> Yammer エンタープライズは office 365 US Government のコンポーネントではありませんが、GCC で office 365 のライセンスを供与された各ユーザーに対してスタンドアロンの提案として無償で購入することができます。 この提供は現在、エンタープライズ契約およびエンタープライズ サブスクリプション契約に基づいて Office 365 GCC を購入するお客様に限定されています。 Yammer は、GCC High または DoD では利用可能ではありません。
<br/><sup>5</sup>通話プランはアドオンです。 
<br/><sup>6</sup>含まれていませんが、個別のアドオンとして購入できます。 visio online には、サブスクリプションの一部として visio online デスクトップクライアントが含まれています。  
## <a name="platform-features"></a>プラットフォーム機能 
<a name="BM7-Platform"> </a>

以下の表は、Office 365 US Government プラン全体で利用可能なプラットフォームの機能やサービスの一覧です。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|**Office 365 管理** <br/> |||||
|Microsoft 365 管理センターを使用して Office 365 を管理する  <br/> |Yes<sup>16</sup> <br/> |Yes<sup>16</sup> <br/> |はい  <br/> |Yes<sup>16</sup> <br/> |
|Office 365 からのコア サービスの設定の管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Windows PowerShell を使用して Office 365 を管理する  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Azure Information Protection を使用してコンテンツを保護する  <br/> |なし<sup></sup> <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> )  <br/> |なし<sup></sup> <br/> |
|**[Office 365 スイート機能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|Microsoft の予約  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |なし  <br/> |
|Microsoft Flow  <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |
|Microsoft Forms  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|Microsoft Graph API  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft MyAnalytics  <br/> |<sup>9、12、15</sup> <br/> |<sup>9、12、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |<sup>9、12、15</sup> <br/> |
|Microsoft Planner  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|Microsoft PowerApps  <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |
|Microsoft StaffHub  <br/> |いいえ <br/> |いいえ <br/> |いいえ <br/> |なし<br/> |
|Microsoft Stream  <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |いいえ  <br/> |
|Microsoft Sway  <br/> |いいえ <br/> |いいえ <br/> |いいえ <br/> |なし <br/> |
|Microsoft Teams  <br/> |はい <br/> |はい <br/> |はい <br/> |はい <br/> |
|Office Delve  <br/> |Yes<sup>17</sup> <br/> |Yes<sup>17</sup> <br/> |はい  <br/> |Yes<sup>17</sup> <br/> |
|Office 365 グループ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft Stream  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |いいえ  <br/> |
|**[ユーザー アカウント管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|クラウド ID  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|フェデレーション ID (シングル サインオン)  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多要素認証  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|電話要素の認証  <br/> |はい (<sup>9</sup> ) <br/> |はい (<sup>9</sup> ) <br/> |はい  <br/> |はい (<sup>9</sup> ) <br/> |
|Office 365 デスクトップ セットアップ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 によるユーザーの管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|CSV ファイルを使用する一括アップロード  <br/> |はい (<sup>9</sup> ) <br/> |はい (<sup>9</sup> ) <br/> |はい  <br/> |はい (<sup>9</sup> ) <br/> |
|ディレクトリ同期ツール  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange のシンプルな (一括) 移行  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 を使用したアカウントの削除  <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |
|管理者は Office 365 から、または Windows PowerShell を使用してユーザー パスワードをリセットできる  <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |
|ユーザーが自分のパスワードを変更できる  <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |
|ライセンスの管理  <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |
|Office 365 からのセキュリティ グループの管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|複数の管理者役割を使用できる  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|パートナーに Office 365 の管理を許可する  <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |
|Azure Active Directory サービス  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ドメイン](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|fourthcoffee.com などのカスタム第 2 レベル ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|marketing.fourthcoffee.com などのカスタム第 3 レベル ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|最大 900 のカスタム ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|カスタム ドメインに必要なドメイン所有権の検証  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[サービスの正常性および継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|[ **サービス正常性**] または [ **サービスの状態**] ページで利用可能な状態に関する情報  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|Microsoft 365 管理センターダッシュボードで利用可能な個々のアラートの状態  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|[ **サービスの正常性**] RSS フィード  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[レポート](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|アクティブおよび非アクティブ メールボックス  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|新規メールボックスおよび削除済みメールボックス  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|新規および削除済みグループ  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールボックスの使用状況  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールボックスの接続の種類  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|送信メールと受信メール  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|上位送信者および受信者  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|スパム検出  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|マルウェア検出  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの上位マルウェア  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールのルール一致  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの上位ルール一致  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの上位 DLP ポリシー一致  <br/> |いいえ  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの重大度別 DLP ポリシー一致  <br/> |いいえ  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの DLP ポリシーの一致、上書き、および誤検知の数  <br/> |いいえ  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|メールの上位 DLP ルール一致  <br/> |いいえ  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|IM とオーディオ セッション  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|アプリケーション共有、Web、およびダイヤルイン会議  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|ビデオ、アプリケーション共有、およびファイル転送セッション  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|IM と電話/ビデオ会議  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|ダウンロード可能なメールの保護レポート  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|使用されるブラウザー  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|使用されるオペレーティング システム  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|Office 365 レポート Web サービスを使用した、独自のレポートの作成  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|**[サービス更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|すべてのカスタマーに提供される定期的な更新プログラム  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|アクションが必要な場合にメッセージ センターに通知を送信  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|一部のサービス更新のための Roadmap.office.com  <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |
|対象のリリースを有効にするオプション  <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |
|**[ヘルプとトレーニング](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|オンライン ヘルプ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|コミュニティ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|その他のセルフヘルプ リソース  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|自己学習トレーニング  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ネットワーク](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|IPv4 および IPv6 プロトコル  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**信頼** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|**[プライバシー、セキュリティ、および透過性](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|高度なデータ ガバナンス  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |はい <br/> |<sup>12</sup> <br/> |
|Cloud App Security  <br/> |いいえ<sup>11、12</sup> <br/> |いいえ<sup>11、12</sup> <br/> |はい<sup>11</sup> <br/> |いいえ<sup>11、12</sup> <br/> |
|Advanced Threat Protection  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |はい  <br/> |<sup>12</sup> <br/> |
|カスタマー ロックボックス  <br/> |<sup>9、12、15</sup> <br/> |<sup>9、12、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |<sup>9、12、15</sup> <br/> |
|Office 365 Advanced eDiscovery  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |はい  <br/> |<sup>12</sup> <br/> |
|セキュリティ スコア<sup>14</sup> <br/> |Yes<sup>9、15</sup> <br/> |はい (<sup>9</sup> ) <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|Office メッセージの暗号化  <br/> |いいえ  <br/> |あり <br/> |はい <br/> |いいえ  <br/> |
|脅威インテリジェンス  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |はい <br/> |<sup>12</sup> <br/> |
|**[準拠[ServiceDesc]](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|SAS 70/SSAE16 の評価  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|ISO 27001 認定  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU モデル条項  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU セーフ ハーバー  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|HIPAA ビジネス アソシエイト契約  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|FISMA 運用認可  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft データ処理契約  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI DSS レベル 1  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI 準拠 PAN データ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |なし  <br/> |
|**[サービス継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|BlackBerry Internet Service (BIS) の使用  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |
|**[パートナー](../../office-365-platform-service-description/partners.md)** <br/> |||||
|指定されたプランを使用しているカスタマーに対する試用版への招待および発注書の作成  <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |
|代理管理の提供  <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |
|**[サービス レベル契約](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[製品使用権](../../office-365-platform-service-description/product-use-rights.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
   
> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights Management (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、office 365 ProPlus へのサブスクリプションが必要です。これは、office 365 US government G1 または office 365 US government F1 には含まれていません。 > 
<br/><sup>2</sup>既存の bbcs および BIS お客様は、サービスを引き続き使用できます。 新規のお客様の受け付けはしていません。 
<br/><sup>3</sup>ディレクトリ同期を使用する場合は、Office 365 ポータルではなく Active directory を使用するか、Windows PowerShell の Azure Active directory モジュールを使用して、アカウントを削除するか、パスワードを変更する必要があります。 
<br/><sup>4</sup>パスワード同期を使用する場合、ユーザーはローカルの Active Directory でパスワードを変更する必要があります。 
<br/><sup>5</sup>ユーザーのセルフサービスのパスワード管理ポリシーを設定する方法については、「 [Azure AD でパスワードを管理](https://azure.microsoft.com/en-us/documentation/articles/active-directory-manage-passwords/)する」を参照してください。 <br/><sup>6</sup>以前のバージョンの office 365 からアップグレードしていない場合は、office 365 でパブリック web サイトを1つしか使用できません。 この場合、パブリック Web サイトが 2 つあっても、どちらか一方のサイトしかカスタム ドメイン名でホストすることができません。 ビジネスサブスクリプションで2つの web サイトを操作する方法の詳細については、「 [2 つの Office 365 パブリック web サイトの操作](https://go.microsoft.com/fwlink/p/?LinkID=271589)」を参照してください。 別のサブスクリプションをお持ちの場合は、「 [Office web サイトホスティングとパブリック web サイトについて」](https://go.microsoft.com/fwlink/p/?LinkID=325009)を参照してください。 
<br/><sup>7</sup>年割引を使用して購入された座席は、早期の解雇料金の対象となる場合があります。 これは月単位で支払われるサブスクリプションには適用されません。 
<br/><sup>8</sup>以下のプランでは、Microsoft 365 管理センターからのライセンスシートの変更をサポートしていません。 > Office 365 US government G1 > office 365 us government G3 > office 365 us government K1 <br/><sup>9</sup>現時点では GCC では使用できませんが、近日中に公開されています。
<br/><sup>10</sup> office 365 US Government G1、G3、および F1、対象指定リリース、および office 365 for business ロードマップが適用されます。ただし、[コンプライアンス要件](https://products.office.com/en-us/business/office-365-trust-center-cloud-computing-security?legRedir=true&amp;CorrelationId=eeaccba9-85ea-4fa8-9c84-3fb4c9e1547b&amp;tab=7a3a6365-14c0-81ac-34ff-f4a416599263)により、特定のサービス更新に関して何らかの相違や遅延が発生する場合があります。
<br/><sup>11</sup>まだ Office 365 US Government 製品では利用できませんが、近日中に公開されています。 ><br/><sup>12</sup>含まれていませんが、GCC で個別のアドオンとして購入できます。 
<br/><sup>13</sup> Office 365 US Government 製品ではサポートされていません。 
<br/><sup>14</sup>使用可能[https://securescore.office.com](https://securescore.office.com)です。 管理者のアクセス許可が必要です。 詳細については、「 [Office 365 Secure Score の概要](https://go.microsoft.com/fwlink/?linkid=836894)」を参照してください。 
<br/><sup>15</sup>現時点では DoD 環境では使用できませんが、近日中に提供されます。 
<br><sup>16</sup>管理センターには、DoD または GCC の高環境での利用状況分析は含まれていません。
<br><sup>17</sup> GCC High または DoD 環境ではサポートされていません
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office アプリケーション機能  
<a name="BM11-Applications"> </a>

次の表には、Office 365 US Government プラン全体にわたって利用可能な Office アプリケーション機能が示されています。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|**Office アプリケーション** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |はい<sup>3</sup> <br/> |はい  <br/> |はい  <br/> |はい<sup>3</sup> <br/> |
|[Office for Mac for Office 365](https://support.office.com/en-us/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57?ui=en-US&amp;rs=en-US&amp;ad=US) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|[IPad/iPhone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |なし  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |いいえ  <br/> |
|[Android 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |なし  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |なし  <br/> |
|[Windows Phone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|Office Mobile for Windows 10 tablets <br/> |なし  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |なし  <br/> |
|iOS および Android 用の Outlook<sup>5、4</sup>  <br/> |はい <br/> |はい <br/> |はい <br/> |はい <br/> |
|**企業価値** <br/> |**Office 365 US Government G1** <br/> |**Office 365 US Government G3** <br/> |**Office 365 US Government G5** <br/> |**Office 365 US Government F1** <br/> |
|PC または Mac 上のユーザーごとに 5 個のインストール  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|自動化されたユーザー アカウント プロビジョニング  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多言語ユーザー インターフェイス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|クライアント プッシュ展開  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|社内 Exchange のクライアント サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|社内 SharePoint のクライアント サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|ソフトウェア更新の制御  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|データベース比較  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|デスクトップの仮想化  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|Excel スプレッドシート比較  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|Excel スプレッドシート検査  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|Exchange Online と SharePoint Online のアーカイブとコンプライアンス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|グループ ポリシーのサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|Azure Information Protection を使用した Information Rights Management  <br/> |なし<sup></sup> <br/> |はい<sup>6</sup> <br/> |はい<sup>6</sup> <br/> |なし<sup></sup> <br/> |
|Windows Server AD RMS を使用した Information Rights Management  <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |
|Office アドイン、ActiveX、および BHO のサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |なし  <br/> |
|OneNote クライアントから SharePoint Server、SharePoint Online、OneDrive for Business、Office 365 上のノートブックへのアクセス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Office Lens  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |なし  <br/> |
|Office テレメトリ  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|クライアント アプリケーションのオフライン サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|最適化されたサイド バイ サイド クライアント インストール  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Power Map for Excel  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|Power Pivot for Excel  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|Power Query for Excel  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|Power View for Excel  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|ローミング設定  <br/> |なし  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |いいえ  <br/> |
|共有コンピューターのライセンス認証  <br/> |なし  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |なし  <br/> |
|クラウドベース ファイル ストレージのブロックのサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|バージョン アップグレード  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|Volume activation (KMS/MAK)  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |なし  <br/> |
   
> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights Management (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、office 365 ProPlus へのサブスクリプションが必要です。これは、office 365 US government G1 または office 365 US government F1 には含まれていません。 
<br/><sup>2</sup> Windows Server AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。 
<br/><sup>3</sup> Skype for business Basic は、すべてのお客様が利用できます。 skype for business デスクトップクライアントは、ローカルにインストールされたアプリケーションで、skype for business Online を含む Office 365 プランのプレゼンス、インスタントメッセージング、および会議機能を提供します。 office 365 ProPlus、および office 365 Enterprise E3 には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能が含まれる、完全な Skype アプリケーションが含まれています。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://technet.microsoft.com/en-us/library/gg425836%28v=ocs.15%29.aspx). 
<br/><sup>4</sup>現時点では GCC High または DoD 環境では使用できませんが、近日中に提供されます。
<br/><sup>5</sup>詳細について[は、「Government Community Cloud で Outlook for iOS と Outlook for Android を使用する](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)」を参照してください。
  <br/><sup>6</sup> Office 365 DoD 環境ではまだ使用できませんが、近日中に提供されます。
<br/><br/>[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
