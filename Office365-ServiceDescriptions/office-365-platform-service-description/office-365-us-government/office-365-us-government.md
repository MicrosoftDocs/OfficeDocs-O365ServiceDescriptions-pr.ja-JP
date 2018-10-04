---
title: Office 365 US Government
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/6/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 米国公的機関の固有であり、変化し続ける要件に対応して、マイクロソフトが Office 365 の米国政府の計画を作成しました (orOffice 365 米国政府)。このセクションでは、Office 365 の米国政府に特有の機能の概要を提供します。Office 365 サービスの説明の横の補足このセクションを読むことをお勧めします。
ms.openlocfilehash: 672a1548ea1c1e01c085fc0f70c927811f30d84c
ms.sourcegitcommit: 1ab13384025545fa0bb053de8fc20c8956d82119
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/03/2018
ms.locfileid: "25362912"
---
# <a name="office-365-us-government"></a>Office 365 US Government

米国公的機関の固有であり、変化し続ける要件に対応して、マイクロソフトは、Office 365 の米国政府の計画 (または、「Office 365 の米国政府」) を作成しました。 しますこのセクションでは、Office 365 の米国政府に特有の機能の概要を提供します。[Office 365 サービスの説明](../../office-365-service-descriptions-technet-library.md)の横の補足このセクションを読むことをお勧めします。
  
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

Microsoft 管理者による Office 365 US Government 顧客コンテンツへのアクセスは、米国市民である個人に制限されています。これらの個人は、関連する政府規格に従って身元が調査されます。
  
||||
|:-----|:-----|:-----|
|**背景調査** <br/> |**GCC** <br/> |**GCC High および Dod** <br/> |
|アメリカ国籍の確認  <br/> |はい  <br/> |はい  <br/> |
|職歴チェック  <br/> |はい  <br/> |はい  <br/> |
|学歴の確認  <br/> |はい  <br/> |はい  <br/> |
|社会保障番号 (SSN) の検索  <br/> |はい  <br/> |はい  <br/> |
|犯罪歴のチェック (7 年)  <br/> |はい  <br/> |はい  <br/> |
|米国財務省外国資産管理局 (OFAC) のリスト  <br/> |はい  <br/> |はい  <br/> |
|米国産業安全保障局 (BIS) のリスト  <br/> |はい  <br/> |はい  <br/> |
|指紋ベースによる FBI の犯罪データベースのチェック  <br/> |はい  <br/> |はい  <br/> |
|CJIS 犯罪の身元調査  <br/> |はい  <br/> |いいえ  <br/> |
|DOD IT-2 に基づく OPM Tier 3 調査  <br/> |いいえ  <br/> |DOD SRG L5 のテナントのみ  <br/> |
   
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack センターの契約時のアシスタント
<a name="BM5-Restricted"> </a>

Office 365<sup>1</sup>FastTrack センターのメリット、使用するリモートで Office 365 環境内の使用と計画の展開と、組織内で使用できる状態を取得するのには fasttrack というスペシャ リスト。Fasttrack というプロセスでは、契約時とユーザーの導入サービスを提供します。 
  
オンボーディングは、次のもので構成されます。
  
- コアの契約時にこれらは、必要な場合は、テナントの構成と Azure Active Directory (AD の Azure) との統合に必要なタスクです。中核となる契約時もベースライン契約時の他の条件を満たすサービスを提供します。
    
- サービス契約時と移行のサービス契約時の作業には、テナントのシナリオが有効にします。電子メールとファイルを含む) のデータ移行については、[データ移行](https://aka.ms/whatcanmigrate)してください。<sup>2</sup>
    
ユーザー採用サービスは、ユーザーが使用できるサービスを認識し、そのサービスを使用してビジネス価値を高めることができるようにするガイダンスを提供するタスクで構成されています。この支援は、オンボーディング アクティビティと並行して行われます。
  
FastTrack センター プロセスに固有の情報を参照して[ここで](https://aka.ms/whatistheprocess)。活動の役割と責任の内訳、 [fasttrack という責任](https://aka.ms/whatdoesftcdo)と[、責任の範囲](https://aka.ms/whatdowedo)を確認してください。
  
<sup>1</sup> FastTrack のサービスを受信する[対象となるプラン](https://aka.ms/whocanbenefit)の一覧から、少なくとも 50 のライセンスを購入する必要があります。 
  
<sup>2</sup>データ移行サービスは、500 以上のライセンスで Office 365 テナントに使用します。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack によって実行されるデータの移行
<a name="BM5-Restricted"> </a>

[FastTrack](https://fasttrack.microsoft.com/)移行のメリットを選択したお客様は、データの移行を管理するチームへのアクセス権を付与する必要があります。これらのスタッフは米国人であり、Office 365 の米国政府のサービスの顧客の移行を実行する前に次のバック グラウンド チェックが行われます。 
  
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
  
## <a name="security-amp-compliance-center"></a>セキュリティ&amp;コンプライアンス センター
<a name="BM9-Requirements"> </a>

セキュリティについての情報の&amp;コンプライアンス センターおよびその他の情報と可用性へのリンクを参照してください[Office 365 のセキュリティ&amp;コンプライアンス センター](../../office-365-platform-service-description/office-365-securitycompliance-center.md)です。
  
## <a name="service-availability-for-each-plan"></a>各プランのサービスの可用性
<a name="BM9-Requirements"> </a>

各 Office 365 プランには、Exchange Online や SharePoint Online などの個別のサービスが複数含まれています。次の表に、各 Office 365 US Government プランで使用できるサービスを示します。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 サービス** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|Office Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 ProPlus  <br/> |いいえ <br/> |はい <br/> |はい <br/> |いいえ  <br/> |
|Exchange Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange Online Protection  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|SharePoint Online  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|OneDrive for Business  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|ビジネス用の Skype (インスタント メッセージング&amp;プレゼンス)  <br/> |<sup>1</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |<sup>1</sup>を [はい] します。 <br/> |
| 音声の電話システムでは、オーディオ会議  <br/> |いいえ <sup>2、3</sup> <br/> |いいえ <sup>2、3</sup> <br/> |はい <sup>3、5</sup> <br/> |いいえ  <br/> |
|Power BI Pro  <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |はい  <br/> |なし<sup>2</sup> <br/> |
|Project Online  <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |
|Yammer エンタープライズ  <br/> |ない<sup>4</sup> <br/> |ない<sup>4</sup> <br/> |ない<sup>4</sup> <br/> |ない<sup>4</sup> <br/> |
   
> <sup>1</sup> Skype のビジネスの基本はすべての顧客です。ビジネス デスクトップ クライアントの Skype は、Skype を含むオンライン ビジネスの計画を Office 365 のプレゼンス、インスタント メッセージング、および会議機能を提供するローカルにインストールされたアプリケーションです。Office 365 ProPlus、G3、g5 の数値には、フルの Skype のアプリケーションには、高度な電話サポート、アーカイブ、およびコンプライアンス機能などの追加機能が含まれていますが含まれます。Skype のオンライン ビジネスのライセンスは、ユーザーごとに割り当てる必要があります。<br/><sup>2</sup>されませんが、別のアドオンとして購入することができます。 
<br/> <sup>3</sup> 現時点では GCC High または DoD プランでは使用できませんが、まもなく公開されます。 
<br/><sup>4</sup> Yammer の企業は Office 365 の米国政府のコンポーネントではありませんが、Office 365 の GCC のライセンス付与、スタンドアロンの案内各ユーザーに無料で取得できます。このサービスは、エンタープライズ アグリーメント、およびエンタープライズ サブスクリプション契約の下で Office 365 の GCC を購入する顧客に限定されています。Yammer は、GCC 高または DoD では使用できません。<br/><sup>5</sup> 通話プランはアドオンです。 
  
## <a name="platform-features"></a>プラットフォーム機能
<a name="BM7-Platform"> </a>

以下の表は、Office 365 US Government プラン全体で利用可能なプラットフォームの機能やサービスの一覧です。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|**Office 365 管理** <br/> |||||
|Office 365 管理センターを使用して Ofiice 365 を管理する  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |はい  <br/> |<sup>15</sup>を [はい] します。 <br/> |
|Office 365 からのコア サービスの設定の管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Windows PowerShell を使用して Office 365 を管理する  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Azure Information Protection を使用してコンテンツを保護する  <br/> |なし<sup>1</sup> <br/> |<sup>9</sup>を [はい] します。 <br/> |はい  <br/> |なし<sup>1</sup> <br/> |
|**[Office 365 スイート機能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|Microsoft の予約  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|Microsoft Flow  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft Forms  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft Graph API  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft MyAnalytics  <br/> |なし<sup>9、12、15</sup> <br/> |なし<sup>9、12、15</sup> <br/> |<sup>9、15</sup>を [はい] します。 <br/> |なし<sup>9、12、15</sup> <br/> |
|Microsoft Planner  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft PowerApps  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft StaffHub  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft Stream  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Microsoft Sway  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Microsoft Teams  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Office Delve  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |はい  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |
|Office 365 グループ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 ビデオ  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |いいえ  <br/> |
|**[ユーザー アカウント管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|クラウド ID  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|フェデレーション ID (シングル サインオン)  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多要素認証  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|電話要素による認証  <br/> |<sup>9</sup>を [はい] します。 <br/> |<sup>9</sup>を [はい] します。 <br/> |はい  <br/> |<sup>9</sup>を [はい] します。 <br/> |
|Office 365 デスクトップ セットアップ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 によるユーザーの管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|CSV ファイルを使用する一括アップロード  <br/> |<sup>9</sup>を [はい] します。 <br/> |<sup>9</sup>を [はい] します。 <br/> |はい  <br/> |<sup>9</sup>を [はい] します。 <br/> |
|ディレクトリ同期ツール  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange のシンプルな (一括) 移行  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 を使用したアカウントの削除  <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |
|管理者は Office 365 から、または Windows PowerShell を使用してユーザー パスワードをリセットできる  <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |
|ユーザーが自分のパスワードを変更できる  <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |
|ライセンスの管理  <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |
|Office 365 からのセキュリティ グループの管理  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|複数の管理者役割を使用できる  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|パートナーに Office 365 の管理を許可する  <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |<sup>11</sup>を [はい] します。 <br/> |
|Azure Active Directory サービス  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ドメイン](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|fourthcoffee.com などのカスタム第 2 レベル ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|marketing.fourthcoffee.com などのカスタム第 3 レベル ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|最大 900 のカスタム ドメインの追加  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|カスタム ドメインに必要なドメイン所有権の検証  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[サービスの正常性および継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|[ **サービス正常性**] または [ **サービスの状態**] ページで利用可能な状態に関する情報  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |
|Office 365 管理センター ダッシュボードで利用可能な個々のアラートの状態  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |
|[ **サービスの正常性**] RSS フィード  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[レポート](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|アクティブおよび非アクティブ メールボックス  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|新規メールボックスおよび削除済みメールボックス  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|新規および削除済みグループ  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールボックスの使用状況  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールボックスの接続の種類  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|送信メールと受信メール  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|上位送信者および受信者  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|スパム検出  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|マルウェア検出  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの上位マルウェア  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールのルール一致  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの上位ルール一致  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの上位 DLP ポリシー一致  <br/> |いいえ  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの重大度別 DLP ポリシー一致  <br/> |いいえ  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの DLP ポリシーの一致、上書き、および誤検知の数  <br/> |いいえ  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|メールの上位 DLP ルール一致  <br/> |いいえ  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|IM とオーディオ セッション  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|アプリケーション共有、Web、およびダイヤルイン会議  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|ビデオ、アプリケーション共有、およびファイル転送セッション  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|IM と電話/ビデオ会議  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|ダウンロード可能なメールの保護レポート  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|使用されるブラウザー  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|使用されるオペレーティング システム  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|Office 365 レポート Web サービスを使用した、独自のレポートの作成  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|**[サービス更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|すべてのカスタマーに提供される定期的な更新プログラム  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|アクションが 必要な場合に メッセージ センターに 通知が送信される  <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |<sup>15</sup>を [はい] します。 <br/> |
|一部のサービス更新のための Roadmap.office.com  <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |
|対象のリリースを有効にするオプション  <br/> |<sup>10</sup>を [はい] します。 <br/> |<sup>10</sup>を [はい] します。 <br/> |<sup>10</sup>を [はい] します。 <br/> |<sup>10</sup>を [はい] します。 <br/> |
|**[ヘルプとトレーニング](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|オンライン ヘルプ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|コミュニティ  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|その他のセルフヘルプ リソース  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|自己学習トレーニング  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ネットワーク](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|IPv4 および IPv6 プロトコル  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**信頼** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|**[プライバシー、セキュリティ、および透過性](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|高度なデータ ガバナンス  <br/> |ない<sup>12、15</sup> <br/> |ない<sup>12、15</sup> <br/> |<sup>15</sup>を [はい] します。 <br/> |ない<sup>12、15</sup> <br/> |
|Cloud App Security  <br/> |いいえ<sup>11、12</sup> <br/> |いいえ<sup>11、12</sup> <br/> |<sup>11</sup>を [はい] します。 <br/> |いいえ<sup>11、12</sup> <br/> |
|Advanced Threat Protection  <br/> |なし<sup>12</sup> <br/> |なし<sup>12</sup> <br/> |はい  <br/> |なし<sup>12</sup> <br/> |
|顧客ロックボックス  <br/> |なし<sup>9、12、15</sup> <br/> |なし<sup>9、12、15</sup> <br/> |<sup>9、15</sup>を [はい] します。 <br/> |なし<sup>9、12、15</sup> <br/> |
|Office 365 の詳細な電子情報開示  <br/> |ない<sup>12、15</sup> <br/> |ない<sup>12、15</sup> <br/> |はい  <br/> |なし<sup>9, 15</sup> <br/> |
|セキュリティ スコア<sup>14</sup> <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |
|Office のメッセージの暗号化  <br/> |いいえ  <br/> |<sup>9、15</sup>を [はい] します。 <br/> |<sup>9、15</sup>を [はい] します。 <br/> |いいえ  <br/> |
|脅威インテリジェンス  <br/> |ない<sup>12、15</sup> <br/> |ない<sup>12、15</sup> <br/> |<sup>15</sup>を [はい] します。 <br/> |ない<sup>12、15</sup> <br/> |
|**[準拠[ServiceDesc]](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|SAS 70/SSAE16 の評価  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|ISO 27001 認定  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU モデル条項  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU セーフ ハーバー  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|HIPAA ビジネス アソシエイト契約  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|FISMA 運用認可  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft データ処理契約  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI DSS レベル 1  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI 準拠 PAN データ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|**[サービス継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|BlackBerry Internet Service (BIS) の使用  <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |なし<sup>2</sup> <br/> |
|**[パートナー](../../office-365-platform-service-description/partners.md)** <br/> |||||
|指定されたプランを使用しているカスタマーに対する試用版への招待および発注書の作成  <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |
|代理管理の提供  <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |なし<sup>11</sup> <br/> |
|**[サービス レベル契約](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[製品使用権](../../office-365-platform-service-description/product-use-rights.md)** <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
   
> <sup>1</sup> azure 情報の保護が含まれていませんが、別のアドオンとして購入することができ、サポートされている情報権利管理 (IRM) 機能を有効にするには。Azure の情報保護の一部の機能は Office 365 の米国政府の G1 または Office 365 の米国政府の f1 キーに含まれていない Office 365 用リソース、サブスクリプションが必要です。><br/><sup>2</sup> 既存の BBCS および BIS のお客様は、引き続きサービスをご利用いただけます。新規のお客様の受け付けはしていません。<br/><sup>3</sup>場合は、ディレクトリ同期を使用すると、アカウントを削除するかしてください Office 365 ポータルではなく、または Windows PowerShell の Azure Active Directory のモジュールを使用して、Active Directory を使用してパスワードを変更します。 
<br/><sup>4</sup> パスワード同期を使用する場合は、ユーザーは、ローカルの Active Directory でパスワードを変更する必要があります。 
<br/><sup>5</sup>ユーザーのセルフ サービス パスワード管理ポリシーを設定する方法についてには、 [Azure AD でのパスワードの管理](https://azure.microsoft.com/en-us/documentation/articles/active-directory-manage-passwords/)を参照してください。 <br/><sup>6</sup>には、Office 365 の以前のバージョンからアップグレードしていない限り、Office 365 でパブリック web サイトを 1 つだけことができます。その場合は、2 つのパブリック web サイトがあるが、カスタム ドメイン名のうち一方のみをホストできます。ビジネスのサブスクリプションの 2 つの web サイトの操作に関する詳細については、 [2 つの Office 365 の公開サイトでの作業](https://go.microsoft.com/fwlink/p/?LinkID=271589)を参照してください。別のサブスクリプションがあれば、[パートナーの web サイトをホストし、Office 365 のパブリック web サイトについて](https://go.microsoft.com/fwlink/p/?LinkID=325009)パブリック web サイトの詳細を説明します。<br/><sup>7</sup> 長期割引で購入したシートを減らすと、早期解約手数料を徴収される場合があります。これは月単位で支払われるサブスクリプションには適用されません。<br/><sup>8</sup>以下の計画は Office 365 の管理センターからライセンスの座席の変更をサポートして: > Office 365 の米国政府の G1 > Office 365 の米国政府の G3 > Office 365 の米国政府の K1 <br/><sup>9</sup>まだ利用できません、GCC 高が準備中です。
<br/><sup>10</sup> Office 365 米国政府 G1 は、G3、および対象のリリースで、ビジネスのロードマップの Office 365、f1 キーを適用します。ただし、可能性がありますいくつかの相違点や[コンプライアンスの要件](https://products.office.com/en-us/business/office-365-trust-center-cloud-computing-security?legRedir=true&amp;CorrelationId=eeaccba9-85ea-4fa8-9c84-3fb4c9e1547b&amp;tab=7a3a6365-14c0-81ac-34ff-f4a416599263)のための特定のサービスの更新プログラムで遅延が発生。
<br/><sup>11</sup> 現時点では Office 365 US Government 製品では使用できませんが、まもなく公開されます。 ><br/><sup>12</sup> 含まれていませんが、GCC の個別のアドオンとして購入できます。 
<br/><sup>13</sup> Office 365 US Government 製品ではサポートされていません。 
<br/><sup>14</sup>で利用可能な[https://securescore.office.com](https://securescore.office.com)。管理者アクセス許可が必要です。詳細については、 [Office 365 のセキュリティで保護されたスコアを導入すること](https://go.microsoft.com/fwlink/?linkid=836894)を参照してください。<br/><sup>15</sup> DoD の環境が準備中でまだ利用できません。 
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-features"></a>Office アプリケーション機能
<a name="BM11-Applications"> </a>

次の表には、Office 365 US Government プラン全体にわたって利用可能な Office アプリケーション機能が示されています。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|**Office アプリケーション** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |<sup>3</sup>を [はい] します。 <br/> |はい  <br/> |はい  <br/> |<sup>3</sup>を [はい] します。 <br/> |
|[Office for Mac for Office 365](https://support.office.com/en-us/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57?ui=en-US&amp;rs=en-US&amp;ad=US) <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|[IPad/iPhone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|[Android 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|[Windows Phone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|[Windows Phone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Outlook を iOS および Android<sup>5</sup>  <br/> |はい <br/> |はい <br/> |はい <br/> |はい <br/> |
|**企業価値** <br/> |**Office 365 米国政府の G1** <br/> |**Office 365 米国政府の第 3 世代** <br/> |**Office 365 米国政府の G5** <br/> |**Office 365 米国政府の F1** <br/> |
|PC または Mac 上のユーザーごとに 5 個のインストール  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|自動化されたユーザー アカウント プロビジョニング  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多言語ユーザー インターフェイス  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|クライアント プッシュ展開  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|社内 Exchange のクライアント サポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|社内 SharePoint のクライアント サポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|ソフトウェア更新の制御  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|データベース比較  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|デスクトップの仮想化  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Excel スプレッドシート比較  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Excel スプレッドシート検査  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Exchange Online と SharePoint Online のアーカイブとコンプライアンス  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|グループ ポリシーのサポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Azure Information Protection を使用した Information Rights Management  <br/> |なし<sup>1</sup> <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |なし<sup>1</sup> <br/> |
|Windows Server AD RMS を使用した Information Rights Management  <br/> |<sup>2</sup>を [はい] します。 <br/> |<sup>2</sup>を [はい] します。 <br/> |<sup>2</sup>を [はい] します。 <br/> |<sup>2</sup>を [はい] します。 <br/> |
|Office アドイン、ActiveX、および BHO のサポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|OneNote クライアントから SharePoint Server、SharePoint Online、OneDrive for Business、Office 365 上のノートブックへのアクセス  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Office Lens  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|Office テレメトリ  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|クライアント アプリケーションのオフライン サポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|最適化されたサイド バイ サイド クライアント インストール  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|Power Map for Excel  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Power Pivot for Excel  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Power Query for Excel  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Power View for Excel  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|ローミング設定  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|共有コンピューターのライセンス認証  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|クラウドベース ファイル ストレージのブロックのサポート  <br/> |いいえ  <br/> |はい  <br/> |はい  <br/> |いいえ  <br/> |
|バージョン アップグレード  <br/> |いいえ  <br/> |<sup>4</sup>を [はい] します。 <br/> |<sup>4</sup>を [はい] します。 <br/> |いいえ  <br/> |
|Volume activation (KMS/MAK)  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
   
> <sup>1</sup> azure 情報の保護が含まれていませんが、別のアドオンとして購入することができ、サポートされている情報権利管理 (IRM) 機能を有効にするには。Azure の情報保護の一部の機能は Office 365 の米国政府の G1 または Office 365 の米国政府の f1 キーに含まれていない Office 365 用リソース、サブスクリプションが必要です。<br/><sup>2</sup> Windows Server AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。 
<br/><sup>3</sup> Skype のビジネスの基本がすべての顧客です。ビジネス デスクトップ クライアントの Skype は、Skype を含むオンライン ビジネスの計画を Office 365 のプレゼンス、インスタント メッセージング、および会議機能を提供するローカルにインストールされたアプリケーションです。Office 365 ProPlus、および Office 365 エンタープライズ E3 には、フルの Skype のアプリケーションには、高度な電話サポート、アーカイブ、およびコンプライアンス機能などの追加機能が含まれていますが含まれます。Skype のオンライン ビジネスのライセンスは、ユーザーごとに割り当てる必要があります。Lync Basic の機能の詳細については、 [Skype](https://technet.microsoft.com/en-us/library/gg425836%28v=ocs.15%29.aspx)を参照してください。<br/><sup>4</sup> 現時点では GCC High または DoD 環境では使用できませんが、まもなく公開されます。
<br/><sup>5</sup>では、詳細については[iOS および Android 政府コミュニティ クラウドで Outlook を使用する](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)を参照してください。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)