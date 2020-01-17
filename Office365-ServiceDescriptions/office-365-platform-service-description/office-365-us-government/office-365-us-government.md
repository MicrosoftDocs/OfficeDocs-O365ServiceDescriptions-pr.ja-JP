---
title: Office 365 US Government
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 米国の公的機関の独自性と進化する要件に対応して、Microsoft は Office 365 US Government プラン (または Office 365 Government) を作成しています。 このセクションでは、Office 365 Government US 環境に固有の機能の概要について説明します。 この補足セクションは、「Office 365 のサービスの説明」を参照することをお勧めします。
ms.openlocfilehash: be73b616012d37c2bd58df63587201675962ae11
ms.sourcegitcommit: d6b4bac54d41be873dcd2dbfd44463c8f3d49101
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2020
ms.locfileid: "41216742"
---
# <a name="office-365-us-government"></a>Office 365 US Government

米国の公的機関の独自性と進化する要件に対応して、Microsoft は Office 365 US Government プラン (または Office 365 Government) を作成しています。 このセクションでは、Office 365 Government US 環境に固有の機能の概要について説明します。 この補足セクションは、「 [Office 365 のサービスの説明](../../office-365-service-descriptions-technet-library.md)」を参照することをお勧めします。
  
## <a name="how-to-use-this-service-description-section"></a>このサービスの説明セクションの使用方法

Office 365 US Government のサービスの説明は、全般的な Office 365 のサービスの説明へのオーバーレイとして機能するよう設計されています。Office 365 Enterprise 製品と比較した独自のコミットメントと相違点を定義します。
  
## <a name="about-office-365-us-government-environments"></a>Office 365 US Government 環境について

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

Office 365 US Government を使用できるのは、(1) 米国連邦、州、地方、部族、地域関連の行政機関と、(2) 政府の規制や要件の対象となるデータを取り扱い、Office 365 US Government を使用することがこれらの要件を満たす上で適切な、適格性の検証の対象となるその他の機関です。Microsoft による適格性の検証には、武器国際取引に関する規制 (ITAR) の対象となるデータ、FBI の米国刑事司法情報サービス (CJIS) ポリシーの対象となる法律施行データ、またはその他の政府が規制または制御するデータの取り扱いに関する検証が含まれます。検証には、ITAR データに関する米国国務省への登録の証明や、データの取り扱いに関する特定の要件についての政府機関による公的支援が必要な場合があります。Office 365 DoD 環境は、米国国防総省専用です。
  
資格の基準は Office 365 Government の各オファーリング間で一貫していますが、Microsoft は、ITAR 契約言語に対して GCC の高環境用にのみ同意します。
  
Office 365 US Government の適格性に関してご質問がある機関は、アカウント チームにお問い合わせください。
  
お客様の Office 365 US Government の契約の更新時には、適格性の再検証が必要になります。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="customer-content-located-within-the-united-states"></a>米国内の顧客コンテンツ

Office 365 US Government サービスは、米国内に物理的に配置されたデータ センターから提供されます。次の顧客コンテンツは、米国に配置されたデータ センターにのみ格納されます。 
  
- Exchange Online メールボックスの内容 (メール本文、予定表のエントリ、電子メールの添付ファイルの内容)
    
- SharePoint Online サイトのコンテンツと、そのサイト内に格納されているファイル
    
- Skype for Business のアーカイブされた会話、アップロードされたドキュメント、およびホワイトボードセッション

- Microsoft Teams の常設チャットスレッド
    
> [!NOTE]
> 一般的な使用法では、Skype for Business が顧客コンテンツを保管することはありませんが、保管する場合には、米国内のデータセンターに保管されます。 
  
ユーザーが web 用 Office (旧称 Office Web Apps) を使用しているとき、または Active Directory フェデレーションサービス (AD FS) 2.0 の使用を採用している場合に、ユーザーが米国内内に配置されている場合、またはユーザーが単一の si を通じてサービスに接続できるようにするためのポリシーを設定する場合gn は、web 用に Office に一時的にキャッシュされるお客様のコンテンツが米国内に配置されます。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-third-party-services"></a>Office 365 US Government およびサード パーティ サービス

Office 365 は、サード パーティ アプリケーションを SharePoint Online サイト、Skype for Business、Office 365 ProPlus に含まれる Office アプリケーション (Word、Excel、PowerPoint、Outlook など)、Outlook Web App に統合する機能を提供します。さらに、Office 365 はサード パーティ サービス プロバイダーとの統合をサポートしています。これらのサード パーティ アプリケーションおよびサービスには、組織の顧客データを Office 365 インフラストラクチャ外部のサード パーティ システムで保管、送信、処理する場合があるため、Office 365 のコンプライアンスおよびデータ保護に関するコミットメントは適用されません。組織でサード パーティのサービスを使用することが適切であるかどうか査定する際には、そのサード パーティのプライバシーおよびコンプライアンスに関する声明を検討することをお勧めします。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="restricted-data-access-by-administrators"></a>管理者に制限されたデータ アクセス

Microsoft 管理者による Office 365 US Government のお客様のコンテンツへのアクセスは、スクリーン担当者に制限されています。 審査レベルの詳細については、それぞれの環境 (GCC または GCC High および DoD) について、「サービスの説明」ページを参照してください。 

  
## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack センターのオンボードアシスタント

Office 365<sup>1</sup>の Fasttrack センターの特典を使用すると、Fasttrack スペシャリストとリモートで作業して、office 365 環境を使用できる状態にして、組織内での展開と使用を計画できます。 FastTrack プロセスでは、オンボーディングと、ユーザー採用サービスが提供されます。 
  
オンボーディングは、次のもので構成されます。
  
- コアオンボード-これらは、必要に応じて、テナントの構成と Azure Active Directory (Azure AD) との統合に必要なタスクです。 コア オンボーディングは、他の対象のサービスのオンボーディングのベースラインも提供します。
    
- サービスオンボードおよび移行サービスのオンボードタスクは、テナント内のシナリオを有効にします。 データ移行 (電子メールやファイルを含む) については、「[データ移行](https://aka.ms/whatcanmigrate)」で説明します。<sup>2</sup>
    
ユーザー採用サービスは、ユーザーが使用できるサービスを認識し、そのサービスを使用してビジネス価値を高めることができるようにするガイダンスを提供するタスクで構成されています。この支援は、オンボーディング アクティビティと並行して行われます。
  
FastTrack センタープロセスの詳細については、[こちら](https://aka.ms/whatistheprocess)を参照してください。 契約の役割と責任の内訳については、 [Fasttrack の責任](https://aka.ms/whatdoesftcdo)だけでなく、[責任](https://aka.ms/whatdowedo)についても確認してください。
  
<sup>1</sup> fasttrack サービスを受けるには、対象となる[プラン](https://aka.ms/whocanbenefit)のリストから少なくとも50のライセンスを購入する必要があります。 
  
<sup>2</sup>データ移行サービスは、500またはそれ以上のライセンスを持つ Office 365 テナントで使用できます。 
  
## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack によって実行されたデータ移行

[Fasttrack](https://fasttrack.microsoft.com/)移行特典を選択する場合は、データ移行を管理するチームへのアクセス権を付与する必要があります。 これらの人員は米国市民で、Office 365 US Government サービスのお客様に移行を実行する前に、次のバックグラウンドチェックが行われています。 
  
||||
|:-----|:-----|:-----|
|**背景調査** <br/> |**GCC** <br/> |**GCC High および DoD** <br/> |
|アメリカ国籍の確認  <br/> |あり  <br/> |はい  <br/> |
|職歴チェック  <br/> |あり  <br/> |はい  <br/> |
|学歴の確認  <br/> |あり  <br/> |はい  <br/> |
|社会保障番号 (SSN) の検索  <br/> |あり  <br/> |はい  <br/> |
|犯罪歴のチェック (7 年)  <br/> |あり  <br/> |はい  <br/> |
   
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government および Azure Government ExpressRoute

Office 365 米国政府機関のお客様は、Azure Government ExpressRoute サービスを使用して、パブリックインターネット経由で接続するのではなく、サポートされている Office 365 サービスにプライベートに接続できます。
  
サポートされているプロバイダーや価格モデルなどの詳細については、「[ExpressRoute のドキュメント](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)」をご確認ください。
  
Azure ExpressRoute の Office 365 サポートの詳細については、「[Azure ExpressRoute for Office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409)」をご覧ください。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="system-requirements"></a>システム要件

Office 365 US Government プランのシステム要件については、[office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 製品サイトの「 [Office のシステム要件](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)」を参照してください。 
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="security-amp-compliance-center"></a>セキュリティ/コンプライアンス センター

セキュリティ&amp;コンプライアンスセンターおよび追加情報と可用性へのリンクの詳細については、「 [Office 365 &amp;セキュリティコンプライアンスセンター](../../office-365-platform-service-description/office-365-securitycompliance-center.md)」を参照してください。
  
## <a name="service-availability-for-each-plan"></a>各プランのサービスの可用性

各 Office 365 プランには、Exchange Online や SharePoint Online などの個別のサービスが複数含まれています。次の表に、各 Office 365 US Government プランで使用できるサービスを示します。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**Office 365 サービス** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|Web 用 Office  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 ProPlus  <br/> |いいえ <br/> |あり <br/> |はい <br/> |いいえ  <br/> |
|Exchange Online  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange Online Protection  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|SharePoint Online  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|OneDrive for Business  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Skype for Business (Instant Messaging &amp; Presence)  <br/> |はい<sup>1</sup> <br/> |あり  <br/> |はい  <br/> |はい<sup>1</sup> <br/> |
| 音声ビデオシステム、電話会議  <br/> |いいえ <sup>2、3</sup> <br/> |いいえ <sup>2、3</sup> <br/> |はい <sup>3、5</sup> <br/> |いいえ  <br/> |
|Power BI Pro  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |はい  <br/> |<sup>2</sup>なし <br/> |
|Project Online  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |
|Web 用 Visio  <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |<sup>6</sup>なし <br/> |
|Yammer Enterprise  <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |<sup>4</sup>なし <br/> |
   
> <sup>1</sup> Skype For business Basic は、すべてのお客様が利用できます。 Skype for Business デスクトップクライアントは、ローカルにインストールされたアプリケーションで、Skype for Business Online を含む Office 365 プランのプレゼンス、インスタントメッセージング、および会議機能を提供します。 Office 365 ProPlus、G3、および G5 には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能を含む完全な Skype アプリケーションが含まれています。 A Skype for Business Online license must be assigned for each user.
<br/><sup>2</sup>含まれていませんが、個別のアドオンとして購入できます。 Project Online には、サブスクリプションの一部として Project Online デスクトップクライアントが含まれています。
<br/> <sup>3</sup>現時点では GCC High または DoD プランでは利用できませんが、近日中に提供されます。 
<br/><sup>4</sup> Yammer エンタープライズは OFFICE 365 US Government のコンポーネントではありませんが、GCC で office 365 のライセンスを供与された各ユーザーに対してスタンドアロンの提案として無償で購入することができます。 この提供は現在、エンタープライズ契約およびエンタープライズ サブスクリプション契約に基づいて Office 365 GCC を購入するお客様に限定されています。 Yammer は、GCC High または DoD では利用可能ではありません。
<br/><sup>5</sup>通話プランはアドオンです。 
<br/><sup>6</sup>含まれていませんが、個別のアドオンとして購入できます。 Visio for the web には、サブスクリプションの一部として Visio デスクトップアプリが含まれています。

## <a name="platform-features"></a>プラットフォーム機能 

以下の表は、Office 365 US Government プラン全体で利用可能なプラットフォームの機能やサービスの一覧です。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|**Office 365 管理** <br/> |||||
|Microsoft 365 管理センターを使用して Office 365 を管理する  <br/> |Yes<sup>16</sup> <br/> |Yes<sup>16</sup> <br/> |はい  <br/> |Yes<sup>16</sup> <br/> |
|Office 365 からのコア サービスの設定の管理  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Windows PowerShell を使用して Office 365 を管理する  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Azure Information Protection を使用してコンテンツを保護する  <br/> |なし<sup></sup> <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> )  <br/> |なし<sup></sup> <br/> |
|**[Office 365 スイート機能](../../office-365-platform-service-description/office-365-suite-features.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|Microsoft の予約  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|Microsoft ブリーフィング電子メール  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|Microsoft Power の自動化  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|Microsoft Forms  <br/> |あり <br/> |はい <br/> |はい<br/> |はい</sup> <br/> |
|Microsoft Graph API  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft MyAnalytics  <br/> |いいえ <br/> |いいえ <br/> |Yes<sup>17</sup> <br/> |いいえ <br/> |
|Microsoft Planner  <br/> |あり <br/> |はい <br/> |はい <br/> |はい <br/> |
|Microsoft PowerApps  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|Microsoft StaffHub  <br/> |いいえ <br/> |いいえ <br/> |いいえ <br/> |いいえ<br/> |
|Microsoft Stream  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |いいえ  <br/> |
|Microsoft Sway  <br/> |いいえ <br/> |いいえ <br/> |いいえ <br/> |いいえ <br/> |
|Microsoft Teams  <br/> |あり <br/> |はい <br/> |はい <br/> |はい <br/> |
|Office Delve  <br/> |Yes<sup>17</sup> <br/> |Yes<sup>17</sup> <br/> |はい  <br/> |Yes<sup>17</sup> <br/> |
|Office 365 グループ  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ユーザー アカウント管理](../../office-365-platform-service-description/user-account-management.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|クラウド ID  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|フェデレーション ID (シングル サインオン)  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多要素認証  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|電話要素の認証  <br/> |はい (<sup>9</sup> ) <br/> |はい (<sup>9</sup> ) <br/> |はい  <br/> |はい (<sup>9</sup> ) <br/> |
|Office 365 デスクトップ セットアップ  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 によるユーザーの管理  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|CSV ファイルを使用する一括アップロード  <br/> |はい (<sup>9</sup> ) <br/> |はい (<sup>9</sup> ) <br/> |はい  <br/> |はい (<sup>9</sup> ) <br/> |
|ディレクトリ同期ツール  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Exchange のシンプルな (一括) 移行  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Office 365 を使用したアカウントの削除  <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |はい <sup>3</sup> <br/> |
|管理者は Office 365 から、または Windows PowerShell を使用してユーザー パスワードをリセットできる  <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |はい <sup>4</sup> <br/> |
|ユーザーが自分のパスワードを変更できる  <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |はい <sup>5</sup> <br/> |
|ライセンスの管理  <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |はい<sup>7、8</sup> <br/> |
|Office 365 からのセキュリティ グループの管理  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|複数の管理者役割を使用できる  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|パートナーに Office 365 の管理を許可する  <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |はい<sup>11</sup> <br/> |
|Azure Active Directory サービス  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ドメイン](../../office-365-platform-service-description/domains.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|fourthcoffee.com などのカスタム第 2 レベル ドメインの追加  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|marketing.fourthcoffee.com などのカスタム第 3 レベル ドメインの追加  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|最大 900 のカスタム ドメインの追加  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|カスタム ドメインに必要なドメイン所有権の検証  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[サービスの正常性および継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|[ **サービス正常性**] または [ **サービスの状態**] ページで利用可能な状態に関する情報  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|Microsoft 365 管理センターダッシュボードで利用可能な個々のアラートの状態  <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|[ **サービスの正常性**] RSS フィード  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[レポート](../../office-365-platform-service-description/reports.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
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
|**[サービス更新](../../office-365-platform-service-description/service-updates.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|すべてのカスタマーに提供される定期的な更新プログラム  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|アクションが必要な場合にメッセージ センターに通知を送信  <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |はい (<sup>15</sup> ) <br/> |
|一部のサービス更新のための Roadmap.office.com  <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |いいえ<sup>10、13</sup> <br/> |
|対象のリリースを有効にするオプション  <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |はい (<sup>10</sup> ) <br/> |
|**[ヘルプとトレーニング](../../office-365-platform-service-description/help-and-training.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|オンライン ヘルプ  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|コミュニティ  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|その他のセルフヘルプ リソース  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|自己学習トレーニング  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[ネットワーク](../../office-365-platform-service-description/networking.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|IPv4 および IPv6 プロトコル  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**信頼** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|**[プライバシー、セキュリティ、および透明性](../../office-365-platform-service-description/privacy-security-and-transparency.md)** <br/> |||||
|高度なデータ ガバナンス  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |あり <br/> |<sup>12</sup> <br/> |
|Cloud App Security  <br/> |<sup>12、15、19</sup> <br/> |<sup>12、15、19</sup> <br/> |はい<sup>(15, 19)</sup> <br/> |<sup>12、15、19</sup> <br/> |
|Advanced Threat Protection  <br/> |<sup>12、18</sup> <br/> |<sup>12、18</sup> <br/> |はい<sup>18</sup>  <br/> |<sup>12、18</sup> <br/> |
|顧客ロックボックス  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |あり <br/> |<sup>12</sup> <br/> |
|Office 365 Advanced eDiscovery  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |あり  <br/> |<sup>12</sup> <br/> |
|セキュリティ スコア<sup>14</sup> <br/> |Yes<sup>9、15</sup> <br/> |はい (<sup>9</sup> ) <br/> |Yes<sup>9、15</sup> <br/> |Yes<sup>9、15</sup> <br/> |
|Office メッセージの暗号化  <br/> |いいえ  <br/> |あり <br/> |はい <br/> |いいえ  <br/> |
|脅威インテリジェンス  <br/> |<sup>12</sup> <br/> |<sup>12</sup> <br/> |あり <br/> |<sup>12</sup> <br/> |
|**[コンプライアンス](../../office-365-platform-service-description/compliance-servicedesc.md)** <br/> |||||
|SAS 70/SSAE16 の評価  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|ISO 27001 認定  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU モデル条項  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|EU セーフ ハーバー  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|HIPAA ビジネス アソシエイト契約  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|FISMA 運用認可  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|Microsoft データ処理契約  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI DSS レベル 1  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|PCI 準拠 PAN データ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|**[サービスの継続性](../../office-365-platform-service-description/service-health-and-continuity.md)** <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|BlackBerry Internet Service (BIS) の使用  <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |<sup>2</sup>なし <br/> |
|**[パートナー](../../office-365-platform-service-description/partners.md)** <br/> |||||
|指定されたプランを使用しているカスタマーに対する試用版への招待および発注書の作成  <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |
|代理管理の提供  <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |<sup>11</sup>なし <br/> |
|**[サービス レベル契約](../../office-365-platform-service-description/service-level-agreement.md)** <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|**[製品使用権](../../office-365-platform-service-description/product-use-rights.md)** <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
   
> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、office 365 ProPlus へのサブスクリプションが必要です。これは、Office 365 Government の G1 または Office 365 Government F1 には含まれていません。 > 
<br/><sup>2</sup>既存の bbcs および BIS お客様は、サービスを引き続き使用できます。 新規のお客様の受け付けはしていません。 
<br/><sup>3</sup>ディレクトリ同期を使用する場合は、Office 365 ポータルではなく Active directory を使用するか、Windows PowerShell の Azure Active directory モジュールを使用して、アカウントを削除するか、パスワードを変更する必要があります。 
<br/><sup>4</sup>パスワード同期を使用する場合、ユーザーはローカルの Active Directory でパスワードを変更する必要があります。 
<br/><sup>5</sup>ユーザーのセルフサービスのパスワード管理ポリシーを設定する方法については、「 [Azure AD でパスワードを管理](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)する」を参照してください。 
<br/><sup>6</sup>以前のバージョンの office 365 からアップグレードしていない場合は、office 365 でパブリック web サイトを1つしか使用できません。 この場合、パブリック Web サイトが 2 つあっても、どちらか一方のサイトしかカスタム ドメイン名でホストすることができません。 ビジネスサブスクリプションで2つの web サイトを操作する方法の詳細については、「 [2 つの Office 365 パブリック web サイトの操作](https://go.microsoft.com/fwlink/p/?LinkID=271589)」を参照してください。 別のサブスクリプションをお持ちの場合は、「 [365 Office web サイトホスティングとパブリック web サイトについて」](https://go.microsoft.com/fwlink/p/?LinkID=325009)を参照してください。 
<br/><sup>7</sup>年割引を使用して購入された座席は、早期の解雇料金の対象となる場合があります。 これは月単位で支払われるサブスクリプションには適用されません。 
<br/><sup>8</sup>以下のプランでは、Microsoft 365 管理センターからのライセンスシートの変更をサポートしていません。 Office 365 Government G1、Office 365 government G3、Office 365 government F1。 
<br/><sup>9</sup>現時点では GCC では使用できませんが、近日中に公開されています。
<br/><sup>10</sup> for Office 365 Government G1、G3、および F1、対象指定リリース、および office 365 for business ロードマップが適用されます。ただし、[コンプライアンス要件](https://www.microsoft.com/trust-center)により、特定のサービス更新に関して何らかの相違や遅延が発生する場合があります。
<br/><sup>11</sup>まだ Office 365 Government では利用できませんが、近日中に提供されています。 
<br/><sup>12</sup>含まれていませんが、GCC で個別のアドオンとして購入できます。 
<br/><sup>13</sup> Office 365 Government 製品ではサポートされていません。 
<br/><sup>14</sup>使用可能[https://securescore.office.com](https://securescore.office.com)です。 管理者のアクセス許可が必要です。 詳細については、「 [Office 365 Secure Score の概要](https://go.microsoft.com/fwlink/?linkid=836894)」を参照してください。 
<br/><sup>15</sup>現時点では DoD 環境では使用できませんが、近日中に提供されます。 
<br/><sup>16</sup>管理センターには、DoD または GCC の高度な環境での利用状況分析は含まれていません。
<br/><sup>17</sup> GCC High または DoD 環境ではサポートされていません。
<br/><sup>18</sup>マルウェア対策は、ユーザーおよびドメインの偽装およびスプーフィングインテリジェンスについては、GCC High および DoD ではまだ利用できません。
<br/><sup>19</sup>現時点では GCC 環境では使用できませんが、近日中に提供されます。
  
[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)
  
## <a name="office-application-availability-and-enterprise-value"></a>Office アプリケーションの可用性とエンタープライズ価値

次の表には、Office 365 US Government プラン全体にわたって利用可能な Office アプリケーション機能が示されています。
  
||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|**Office アプリケーション** <br/> |||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup> <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup> <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup> <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup> <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup> <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Microsoft Forms<sup>7</sup>| あり <br/> | はい <br/>| はい <br/> | いいえ <br/> |
|Microsoft ホワイトボード<sup>7</sup>| いいえ <br/> | あり <br/> | はい <br/> | いいえ <br/> |
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business) <br/> |はい<sup>3</sup> <br/> |あり  <br/> |はい  <br/> |はい<sup>3</sup> <br/> |
|[Office for Mac for Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57) <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|[IPad/iPhone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone) <br/> |はい  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |あり  <br/> |
|[Android 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-android) <br/> |あり  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |あり  <br/> |
|[Windows Phone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone) <br/> |はい  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |はい  <br/> |
|Office Mobile for Windows 10 tablets <br/> |あり  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |あり  <br/> |
|IOS および Android 用の Outlook<sup>5、4</sup>  <br/> |あり <br/> |はい <br/> |はい <br/> |はい <br/> |
|**企業価値** <br/> |**Office 365 Government G1** <br/> |**Office 365 Government G3** <br/> |**Office 365 Government G5** <br/> |**Office 365 Government F1** <br/> |
|PC または Mac 上のユーザーごとに 5 個のインストール  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|自動化されたユーザー アカウント プロビジョニング  <br/> |あり  <br/> |はい  <br/> |はい  <br/> |はい  <br/> |
|多言語ユーザー インターフェイス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|クライアント プッシュ展開  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|社内 Exchange のクライアント サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|社内 SharePoint のクライアント サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|ソフトウェア更新の制御  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|データベース比較  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|デスクトップの仮想化  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Excel スプレッドシート比較  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Excel スプレッドシート検査  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Exchange Online と SharePoint Online のアーカイブとコンプライアンス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|グループ ポリシーのサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Azure Information Protection を使用した Information Rights Management  <br/> |なし<sup></sup> <br/> |はい<sup>6</sup> <br/> |はい<sup>6</sup> <br/> |なし<sup></sup> <br/> |
|Windows Server AD RMS を使用した Information Rights Management  <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |はい<sup>2</sup> <br/> |
|Office アドイン、ActiveX、および BHO のサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|OneNote クライアントから SharePoint Server、SharePoint Online、OneDrive for Business、Office 365 上のノートブックへのアクセス  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Office Lens  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
|Office テレメトリ  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|クライアント アプリケーションのオフライン サポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|最適化されたサイド バイ サイド クライアント インストール  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|Power Map for Excel  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|Power Pivot for Excel  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|Power Query for Excel  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|Power View for Excel  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|ローミング設定  <br/> |いいえ  <br/> |はい<sup></sup> <br/> |はい<sup></sup> <br/> |いいえ  <br/> |
|共有コンピューターのライセンス認証  <br/> |いいえ  <br/> |あり <br/> |はい <br/> |いいえ  <br/> |
|クラウドベース ファイル ストレージのブロックのサポート  <br/> |いいえ  <br/> |あり  <br/> |はい  <br/> |いいえ  <br/> |
|バージョン アップグレード  <br/> |いいえ  <br/> |はい<sup>4</sup> <br/> |はい<sup>4</sup> <br/> |いいえ  <br/> |
|Volume activation (KMS/MAK)  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |いいえ  <br/> |
   
> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、office 365 ProPlus へのサブスクリプションが必要です。これは、Office 365 Government の G1 または Office 365 Government F1 には含まれていません。 
<br/><sup>2</sup> WINDOWS SERVER AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。 
<br/><sup>3</sup> Skype For business Basic は、すべてのお客様が利用できます。 Skype for Business デスクトップクライアントは、ローカルにインストールされたアプリケーションで、Skype for Business Online を含む Office 365 プランのプレゼンス、インスタントメッセージング、および会議機能を提供します。 Office 365 ProPlus、および Office 365 Enterprise E3 には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能が含まれる、完全な Skype アプリケーションが含まれています。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables). 
<br/><sup>4</sup>現時点では GCC High または DoD 環境では使用できませんが、近日中に提供されます。
<br/><sup>5</sup>詳細について[は、「Government Community Cloud で Outlook For iOS と Outlook For Android を使用する](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)」を参照してください。
<br/><sup>6</sup> Office 365 DoD 環境ではまだ使用できませんが、近日中に提供されます。
<br/><sup>7</sup>アプリケーションは、現時点では利用できない特定の機能を除き、政府機関のクラウドで完全に使用できます。 詳細については、「 [Office アプリケーション機能の可用性](#office-application-and-feature-availability-in-government-plans)」を参照してください。
<br/><br/>[このサービスの説明セクションの使用方法](office-365-us-government.md#how-to-use-this-service-description-section)

## <a name="office-application-and-feature-availability-in-government-plans"></a>政府機関向けプランにおける Office アプリケーションと機能の可用性

次の Office アプリケーションは、官公庁クラウドで利用できます。ただし、この表に示されているように、一部のクラウドベースの機能は現在使用できない場合があります。

|||||
|-----|-----|-----|-----|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|3D の埋め込みアニメーションと3D モデル | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|データ型 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|フラッシュフィル | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|アイデア (洞察サービス) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|PowerBI との統合の強化 (カスタムビジュアル、Excel からの直接 PBI グラフの作成) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|インテリジェントなデジタルインク | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Office 365 グループ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|ピボットテーブルに接続されたピボットグラフデータ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|PowerPivot | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|PowerBI への発行 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|リアルタイムコラボレーション (プレゼンス、通常の共同編集、ドキュメント内チャット) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Shared with Me | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|スマート検索 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|グラフ: サンバーストツリー、ウォーターフォール、ヒストグラム、地図、タイムライン、じょうご | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|バージョン履歴 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD**<sup>3</sup> <br/> |
|電子メール通知 | なし<sup></sup> <br/> | なし<sup></sup> <br/> | いいえ <br/> | 
|画像を挿入する | なし<sup></sup> <br/> | なし<sup></sup> <br/> | いいえ <br/> |
|ビデオを挿入する | なし<sup></sup> <br/> | なし<sup></sup> <br/> | いいえ <br/> |
|数学 | なし<sup></sup> <br/> | なし<sup></sup> <br/> | いいえ <br/> |
|Office 統合 | なし<sup></sup> <br/> | なし<sup></sup> <br/> | いいえ <br/> |
|最新のグループフォーム | あり <br/> | はい <br/> | いいえ <br/> |
|外部共有<sup>4</sup> | はい <br/> | いいえ <br/> | いいえ <br/> |
|フォーム Pro | いいえ | いいえ | いいえ |
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、この時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|リサーチ ツール | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|インテリジェントなデジタルインク | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|Office サウンド (一部) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|動的データ交換 (DDE) が既定で無効になっている | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|ディクテーション | なし<sup></sup> <br/> | なし<sup></sup> <br/> | なし<sup></sup> <br/> |
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|スマート検索 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Office サウンド (一部) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|3D モデルと3D の埋め込みアニメーション | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|グラフ: マップ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|インテリジェントなデジタルインク | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|PowerPoint のライブキャプションと字幕 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|プレゼンターコーチ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Shared with Me | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Skype for Business と共有の統合 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|バージョン履歴 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Office 365 グループ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|リアルタイムコラボレーション (プレゼンス、通常の共同編集、ドキュメント内チャット) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|ディクテーション | なし<sup></sup> <br/> | なし<sup></sup> <br/> | なし<sup></sup> <br/> |
|スライドの再利用 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|米国政府機関の**Microsoft ホワイトボード**は、現在、デスクトップではなくハブクライアントでのみ使用できます。 | **GCC**<sup>2</sup> <br/> | **GCC High**<sup>2</sup> <br/> | **DOD**<sup>2</sup> <br/> |
|付箋、テキスト、画像を挿入する | はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>|
|インクを図形に、インクからテーブルへ | はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>|
|インク beautification | はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>|
|画像をインクに変換する | はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>|
|アクセシビリティ チェック | はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>| はい<sup>2</sup> <br/>|
|動的テンプレート (かんばん、SWOT など) | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|リアルタイムコラボレーション | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|リアルタイムプレゼンス | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|コンテンツに対する反応 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|お客様との共有を含む、ホワイトボードギャラリー | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word)は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用できません。 | **GCC** <br/> | **GCC 高** <br/> | **DOD** <br/> |
|スマート検索 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|リサーチ ツール | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Office サウンド  | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|3D モデル | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|3D の埋め込みアニメーション  | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|タップ  | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|履歴書アシスタント | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|マップグラフ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|インテリジェントなデジタルインク | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Shared with Me | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Translation | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Skype for Business と共有の統合 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|バージョン履歴 | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|Office 365 グループ | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|共同編集者とのコンテキストチャット: ドキュメント内の共同編集者とチャット | いいえ <br/> | いいえ <br/> | いいえ <br/> |
|ディクテーション | なし<sup></sup> <br/> | なし<sup></sup> <br/> | なし<sup></sup> <br/> |

<sup>1 つ</sup>の利用可能時間。<br/>
<sup>2</sup>ローカル Surface Hub での可用性 (サインインしていない場合)。<br/>
<sup>3</sup>アプリケーションは、現在 DOD クラウドでは利用できません。<br/>
GCC 環境では、 <sup>4 つ</sup>の外部共有を使用できます。 組織で[Microsoft Forms をオンまたは](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure)オフにする方法について説明します。 GCC High および DOD 環境では、外部共有は無効になっています。組織内のユーザーは、フォームを完成させ、応答を送信したり、フォーム[をテンプレートとして複製および共有](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)したり、[フォームで共同編集または共同作業](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)を行ったり、[フォームの結果にアクセス](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)したりすることがあります。<br/>
