---
title: Office 365 US Government
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 米国の公的機関の独自性と進化する要件に対応して、Microsoft は Office 365 US Government プラン (または Office 365 Government) を作成しています。 この記事では、Office 365 Government US 環境に固有の機能の概要について説明します。
ms.openlocfilehash: 237a1f39b7c5231475c40750777212a8213a9d2b
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519088"
---
# <a name="office-365-government"></a>Office 365 Government

> [!IMPORTANT]
> Microsoft Teams では、coronavirus (COVID-19) pandemic のために、オンライン通話と音声ビデオ会議で大きなスパイクが発生しています。<br/>
>
>より優れた通話に対応し、継続性と可用性を確保するために、Microsoft では Microsoft Teams GCC audio/video サーバーに対して、商用データセンターの処理能力と政府データセンターの処理能力を活用することを許可しています。<br/>
>
>これらのオーディオ/ビデオサーバーは、米国の Microsoft Azure FedRAMP 高レベルの認定境界サーバー内に存在し、お客様のコンテンツを保存しません。 しかし、これらのサーバーは通話と会議の音声とビデオを処理しており、この中間的な期間中にはコマーシャルスタッフの下で動作しています。<br/>
>
>資格のあるスクリーン化された担当者は、これらのサーバーに対して対話的なログを確認することにより、顧客データにアクセスするためにこれらのサーバーを監視しています。 資格のある担当者は、お客様のコンテンツにアクセスするための GCC 要件を満たしています。 スクリーンの要件の詳細については、「 [GCC サービスの説明](gcc.md)」を参照してください。<br/>
>
>このような特別な時間にサービスが利用可能かつ信頼できることを確認するための手順を実行していただき、サポートを受けていただきありがとうございます。<br/>

米国の公的機関の独自の要件に対応して、Microsoft は Office 365 Government プラン (または Office 365 Government) を作成しました。 このサービスの説明は、Office 365 Government US 環境に固有の機能の概要を示しています。 このサービスの説明は、その他の [Microsoft 365 および Office 365 サービス](../../office-365-service-descriptions-technet-library.md)の説明と共に読むことをお勧めします。

## <a name="how-to-use-this-service-description"></a>このサービスの説明を使用する方法

Office 365 Government サービスの説明は、一般的な Office 365 サービスの説明へのオーバーレイとして機能するように設計されています。 Office 365 Enterprise 製品と比較した独自のコミットメントと相違点を定義します。

## <a name="about-office-365-government-environments"></a>Office 365 Government 環境について

Office 365 Government プランは月単位のサブスクリプションであり、ユーザー数に制限はありません。

- **Office 365 GCC** 環境は、FedRAMP を含むクラウドサービスの連邦要件と、刑事司法および連邦税務情報システム (CJI および FTI データ型) の要件に準拠しています。

- **Office 365 GCC High および DoD** 環境は、米国国防総省のセキュリティ要件のガイドライン、国防総省調達規則 (DFARS)、武器国際取引に関する規制 (ITAR) に準拠します。

Office 365 の機能に加えて、office 365 Government に固有の以下の機能を使用して 365 Office を使用する組織には、次のような機能があります。

- 組織の顧客コンテンツは、Microsoft の商用の Office 365 サービスの顧客コンテンツと論理的に分離されます。

- 組織の顧客コンテンツは、米国内に格納されます。

- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。

- Office 365 Government は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

## <a name="customer-eligibility"></a>お客様の適格性

Office 365 Government は、(1) 米国連邦、州、地方、エスニック、および territorial government エンティティと (2) 政府の規制および要件を満たすデータを処理するその他のエンティティ (2)、およびこれらの要件を満たすために Office 365 Government を使用することが適切であるかどうかを評価する資格を取得します。 Microsoft による適格性の検証には、武器国際取引に関する規制 (ITAR) の対象となるデータ、FBI の米国刑事司法情報サービス (CJIS) ポリシーの対象となる法律施行データ、またはその他の政府が規制または制御するデータの取り扱いに関する検証が含まれます。 検証には、ITAR データに関する米国国務省への登録の証明や、データの取り扱いに関する特定の要件についての政府機関による公的支援が必要な場合があります。 Office 365 DoD 環境は、米国国防総省のみを対象としています。

資格の基準は Office 365 Government の各オファーリング間で一貫していますが、Microsoft は、ITAR 契約言語に対して GCC の高環境用にのみ同意します。

Office 365 Government の特典に関する質問があるエンティティは、アカウントチームにお問い合わせください。

お客様の Office 365 Government の契約の更新時には、適格性の再検証が必要になります。

## <a name="customer-content-located-within-the-united-states"></a>米国内の顧客コンテンツ

Office 365 Government サービスは、米国に物理的にあるデータセンターから提供されます。 次の顧客コンテンツは、米国に配置されたデータ センターにのみ格納されます。

- Exchange Online メールボックスの内容 (メール本文、予定表のエントリ、電子メールの添付ファイルの内容)

- SharePoint Online サイトのコンテンツと、そのサイト内に格納されているファイル

- Skype for Business のアーカイブされた会話、アップロードされたドキュメント、およびホワイトボードセッション

- Microsoft Teams の常設チャットスレッド

> [!NOTE]
> 一般的な使用法では、Skype for Business が顧客コンテンツを保管することはありませんが、保管する場合には、米国内のデータセンターに保管されます。

ユーザーが web 用 Office (旧称 Office Web Apps) を使用している場合、または Active Directory フェデレーションサービス (AD FS) 2.0 の使用を採用している場合、またはユーザーがシングルサインオン経由でサービスに接続できるようにするために、ユーザーが米国内内に配置されている場合は、web 用に一時的に Office にキャッシュされ

## <a name="office-365-government-and-third-party-services"></a>Office 365 Government およびサードパーティのサービス

Office 365 では、サードパーティ製のアプリケーションを SharePoint Online サイト、Skype for Business、Microsoft 365 Apps for enterprise (Word、Excel、PowerPoint、Outlook など)、Outlook Web App に含まれる Office アプリケーションに統合することができます。 さらに、Office 365 はサード パーティ サービス プロバイダーとの統合をサポートしています。 これらのサード パーティ アプリケーションおよびサービスには、組織の顧客データを Office 365 インフラストラクチャ外部のサード パーティ システムで保管、送信、処理する場合があるため、Office 365 のコンプライアンスおよびデータ保護に関するコミットメントは適用されません。 組織でサード パーティのサービスを使用することが適切であるかどうか査定する際には、そのサード パーティのプライバシーおよびコンプライアンスに関する声明を検討することをお勧めします。

## <a name="restricted-data-access-by-administrators"></a>管理者に制限されたデータ アクセス

Microsoft 管理者による Office 365 Government の顧客コンテンツへのアクセスは、スクリーン担当者に制限されます。 審査レベルの詳細については、それぞれの環境 (GCC または GCC High および DoD) のサービスの説明ページを参照してください。

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack センターのオンボードアシスタント

Office 365<sup>1</sup>の Fasttrack センターの特典を使用すると、Fasttrack スペシャリストとリモートで作業して、office 365 環境を使用できる状態にして、組織内での展開と使用を計画できます。 FastTrack プロセスでは、オンボーディングと、ユーザー採用サービスが提供されます。

オンボーディングは、次のもので構成されます。

- コアオンボード-これらは、必要に応じて、テナントの構成と Azure Active Directory (Azure AD) との統合に必要なタスクです。 コア オンボーディングは、他の対象のサービスのオンボーディングのベースラインも提供します。

- サービスオンボードおよび移行サービスのオンボードタスクは、テナント内のシナリオを有効にします。 データ移行 (電子メールやファイルを含む) については、「 [データ移行](https://aka.ms/whatcanmigrate)」で説明します。<sup>2</sup>

ユーザー導入サービスは、ユーザーが対象となるサービスを認識し、それらを使用してビジネス価値を促進できるようにするためのガイダンスを提供するタスクで構成されています。 この支援は、オンボーディング アクティビティと並行して行われます。

FastTrack センタープロセスの詳細については、 [こちら](https://aka.ms/whatistheprocess)を参照してください。 契約の役割と責任の内訳については、 [Fasttrack の責任](https://aka.ms/whatdoesftcdo) だけでなく、 [責任](https://aka.ms/whatdowedo)についても確認してください。

> <sup>1</sup> fasttrack サービスを受けるには、対象となる [プラン](https://aka.ms/whocanbenefit) のリストから少なくとも50のライセンスを購入する必要があります。
<br/><sup>2</sup> データ移行サービスは、500またはそれ以上のライセンスを持つ Office 365 テナントで使用できます。

## <a name="data-migrations-performed-by-fasttrack"></a>FastTrack によって実行されたデータ移行

[Fasttrack](https://fasttrack.microsoft.com/)移行特典を選択する場合は、データ移行を管理するチームへのアクセス権を付与する必要があります。 これらの人員は米国市民で、Office 365 US Government サービスのお客様に移行を実行する前に、次のバックグラウンドチェックが行われています。<br><br>

|背景調査|GCC|GCC High および DoD|
|---|---|---|
|米市民権の確認|はい|はい|
|雇用履歴チェック|はい|はい|
|教育機関の確認|はい|はい|
|社会保障番号 (SSN) の検索|はい|はい|
|犯罪履歴チェック (7 年)|はい|はい|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 US Government および Azure Government ExpressRoute

Office 365 米国政府機関のお客様は、Azure Government ExpressRoute サービスを使用して、パブリックインターネット経由で接続するのではなく、サポートされている Office 365 サービスにプライベートに接続できます。

サポートされているプロバイダーや価格モデルなどの詳細については、「 [Azure ExpressRoute の情報](https://go.microsoft.com/fwlink/?LinkID=798220&amp;clcid=0x409)」を参照してください。

Azure ExpressRoute の Office 365 サポートの詳細については、「 [Azure expressroute For office 365](https://go.microsoft.com/fwlink/?LinkID=798216&amp;clcid=0x409) 」を参照してください。

## <a name="system-requirements"></a>システム要件

Office 365 US Government プランのシステム要件については、[office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 製品サイトの「 [Office のシステム要件](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)」を参照してください。

## <a name="security-amp-compliance-center"></a>セキュリティ/コンプライアンス センター

セキュリティ &amp; コンプライアンスセンターおよび追加情報と可用性へのリンクについては、「 [セキュリティ &amp; コンプライアンスセンター](../../office-365-platform-service-description/office-365-securitycompliance-center.md)」を参照してください。

## <a name="service-availability-for-each-plan"></a>各プランのサービスの可用性

各 Office 365 プランには、Exchange Online や SharePoint Online などの個別のサービスが複数含まれています。次の表に、各 Office 365 US Government プランで使用できるサービスを示します。<br><br>

|Office 365 サービス|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|Webアプリ上の Office|はい|はい|はい|はい|
|Microsoft 365 Apps for enterprise|いいえ|はい|はい|いいえ|
|Exchange Online|はい|はい|はい|はい|
|Exchange Online Protection|はい|はい|はい|はい|
|SharePoint Online|はい|はい|はい|はい|
|OneDrive for Business|はい|はい|はい|はい|
|Skype for Business (Instant Messaging &amp; Presence)|はい<sup>1</sup>|はい|はい|はい<sup>1</sup>|
|音声ビデオシステム、電話会議|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい<sup>5</sup>|いいえ|
|Power BI Pro|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい|いいえ<sup>2</sup>|
|Project Online|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|
|Web 用 Visio|<sup>6</sup>なし|<sup>6</sup>なし|<sup>6</sup>なし|<sup>6</sup>なし|
|Yammer Enterprise|いいえ<sup>4</sup>|いいえ<sup>4</sup>|いいえ<sup>4</sup>|いいえ<sup>4</sup>|

> <sup>1</sup> Skype For business Basic は、すべてのお客様が利用できます。 Skype for Business デスクトップ クライアントは、Skype for Business Online を含む Office 365 プランのプレゼンス機能、インスタント メッセージング機能、会議機能を提供するローカルにインストールされるアプリケーションです。 Enterprise、G3、および G5 用の Microsoft 365 Apps には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能を含む完全な Skype アプリケーションが含まれています。 Skype for Business Online のライセンスは、ユーザーごとに割り当てる必要があります。
<br/><sup>2</sup> 含まれていませんが、個別のアドオンとして購入できます。 Project Online には、サブスクリプションの一部として Project Online デスクトップクライアントが含まれています。
<br/> <sup>3</sup> 現時点では GCC High または DoD プランでは利用できませんが、近日中に提供されます。
<br/><sup>4</sup> Yammer エンタープライズは OFFICE 365 US Government のコンポーネントではありませんが、GCC で office 365 のライセンスを供与された各ユーザーに対してスタンドアロンの提案として無償で購入することができます。 この提供は現在、エンタープライズ契約およびエンタープライズ サブスクリプション契約に基づいて Office 365 GCC を購入するお客様に限定されています。 Yammer は、GCC High または DoD では利用可能ではありません。
<br/><sup>5</sup> 通話プランはアドオンです。
<br/><sup>6</sup> 含まれていませんが、個別のアドオンとして購入できます。 Visio for the web には、サブスクリプションの一部として Visio デスクトップアプリが含まれています。

## <a name="platform-features"></a>プラットフォーム機能 

以下の表は、Office 365 US Government プラン全体で利用可能なプラットフォームの機能やサービスの一覧です。<br><br>

|機能|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Office 365 管理**|||||
|Microsoft 365 管理センターを使用して Office 365 を管理する|Yes<sup>16</sup>|Yes<sup>16</sup>|はい|Yes<sup>16</sup>|
|Office 365 からのコア サービスの設定の管理|はい|はい|はい|はい|
|Windows PowerShell を使用して Office 365 を管理する|はい|はい|はい|はい|
|Azure Information Protection を使用してコンテンツを保護する|いいえ<sup>1</sup>|はい (<sup>15</sup> )|はい (<sup>15</sup> )|いいえ<sup>1</sup>|
|**[Office 365 スイート機能](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|Microsoft の予約|いいえ|はい (<sup>21</sup> )|はい (<sup>21</sup> )|いいえ|
|Microsoft ブリーフィング電子メール|いいえ|いいえ|いいえ|いいえ|
|Microsoft Power Automate|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|Microsoft Forms|はい|はい|はい<br/>|はい</sup>|
|Microsoft Graph API|はい|はい|はい|はい|
|Microsoft MyAnalytics|いいえ|いいえ|Yes<sup>17</sup>|いいえ|
|Microsoft Planner|はい|はい|はい|はい|
|Microsoft PowerApps|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|Microsoft StaffHub|いいえ|いいえ|いいえ|いいえ<br/>|
|Microsoft Stream|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|はい<sup>9、15、20</sup>|
|Microsoft Sway|いいえ|いいえ|いいえ|いいえ|
|Microsoft Teams|はい|はい|はい|はい|
|Office Delve|Yes<sup>17</sup>|Yes<sup>17</sup>|はい|Yes<sup>17</sup>|
|Office 365 グループ|はい|はい|はい|はい|
|**[ユーザー アカウント管理](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|クラウド ID|はい|はい|はい|はい|
|フェデレーション ID (シングル サインオン)|はい|はい|はい|はい|
|多要素認証|はい|はい|はい|はい|
|電話要素の認証|はい (<sup>9</sup> )|はい (<sup>9</sup> )|はい|はい (<sup>9</sup> )|
|Office 365 デスクトップ セットアップ|はい|はい|はい|はい|
|Office 365 によるユーザーの管理|はい|はい|はい|はい|
|CSV ファイルを使用する一括アップロード|はい (<sup>9</sup> )|はい (<sup>9</sup> )|はい|はい (<sup>9</sup> )|
|ディレクトリ同期ツール|はい|はい|はい|はい|
|Exchange のシンプルな (一括) 移行|はい|はい|はい|はい|
|Office 365 を使用したアカウントの削除|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|
|管理者は Office 365 から、または Windows PowerShell を使用してユーザー パスワードをリセットできる|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|
|ユーザーが自分のパスワードを変更できる|はい<sup>5</sup>|はい<sup>5</sup>|はい<sup>5</sup>|はい<sup>5</sup>|
|ライセンスの管理|はい<sup>7、8</sup>|はい<sup>7、8</sup>|はい<sup>7、8</sup>|はい<sup>7、8</sup>|
|Office 365 からのセキュリティ グループの管理|はい|はい|はい|はい|
|複数の管理者役割を使用できる|はい|はい|はい|はい|
|パートナーに Office 365 の管理を許可する|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|
|Azure Active Directory サービス|はい|はい|はい|はい|
|**[ドメイン](../../office-365-platform-service-description/domains.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|fourthcoffee.com などのカスタム第 2 レベル ドメインの追加|はい|はい|はい|はい|
|marketing.fourthcoffee.com などのカスタム第 3 レベル ドメインの追加|はい|はい|はい|はい|
|最大 900 のカスタム ドメインの追加|はい|はい|はい|はい|
|カスタム ドメインに必要なドメイン所有権の検証|はい|はい|はい|はい|
|**[サービスの正常性および継続性](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|[ **サービス正常性**] または [ **サービスの状態**] ページで利用可能な状態に関する情報|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|
|Microsoft 365 管理センターダッシュボードで利用可能な個々のアラートの状態|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|
|[ **サービスの正常性**] RSS フィード|はい|はい|はい|はい|
|**[レポート](../../office-365-platform-service-description/reports.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|アクティブおよび非アクティブ メールボックス|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|新規メールボックスおよび削除済みメールボックス|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|新規および削除済みグループ|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールボックスの使用状況|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールボックスの接続の種類|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|送信メールと受信メール|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|上位送信者および受信者|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|スパム検出|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|マルウェア検出|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールの上位マルウェア|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールのルール一致|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールの上位ルール一致|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|メールの上位 DLP ポリシー一致|いいえ|はい (<sup>15</sup> )|はい (<sup>15</sup> )|いいえ|
|メールの重大度別 DLP ポリシー一致|いいえ|はい (<sup>15</sup> )|はい (<sup>15</sup> )|いいえ|
|メールの DLP ポリシーの一致、上書き、および誤検知の数|いいえ|はい (<sup>15</sup> )|はい (<sup>15</sup> )|いいえ|
|メールの上位 DLP ルール一致|いいえ|はい (<sup>15</sup> )|はい (<sup>15</sup> )|いいえ|
|IM とオーディオ セッション|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|アプリケーション共有、Web、およびダイヤルイン会議|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|ビデオ、アプリケーション共有、およびファイル転送セッション|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|IM と電話/ビデオ会議|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|ダウンロード可能なメールの保護レポート|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|使用されるブラウザー|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|使用されるオペレーティング システム|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|Microsoft 365 reporting web サービスを使用して独自のレポートを作成する|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|**[サービスの更新情報](../../office-365-platform-service-description/service-updates.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|すべてのカスタマーに提供される定期的な更新プログラム|はい|はい|はい|はい|
|アクションが必要な場合にメッセージ センターに通知を送信|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい (<sup>15</sup> )|
|一部のサービス更新のための Roadmap.office.com|いいえ<sup>10、13</sup>|いいえ<sup>10、13</sup>|いいえ<sup>10、13</sup>|いいえ<sup>10、13</sup>|
|対象のリリースを有効にするオプション|はい (<sup>10</sup> )|はい (<sup>10</sup> )|はい (<sup>10</sup> )|はい (<sup>10</sup> )|
|**[ヘルプとトレーニング](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|オンライン ヘルプ|はい|はい|はい|はい|
|コミュニティ|はい|はい|はい|はい|
|その他のセルフヘルプ リソース|はい|はい|はい|はい|
|自己学習トレーニング|はい|はい|はい|はい|
|**[ネットワーク](../../office-365-platform-service-description/networking.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|IPv4 および IPv6 プロトコル|はい|はい|はい|はい|
|**信頼**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|**[プライバシー、セキュリティ、および透明性](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|高度なデータ ガバナンス|<sup>12</sup>|<sup>12</sup>|はい|<sup>12</sup>|
|Cloud App Security|<sup>12、15、19</sup>|<sup>12、15、19</sup>|はい<sup>(15, 19)</sup>|<sup>12、15、19</sup>|
|Microsoft Defender for Office 365|<sup>12、18</sup>|<sup>12、18</sup>|はい<sup>18</sup>|<sup>12、18</sup>|
|顧客ロックボックス|<sup>12</sup>|<sup>12</sup>|はい|<sup>12</sup>|
|Advanced eDiscovery|<sup>12</sup>|<sup>12</sup>|はい|<sup>12</sup>|
|セキュリティ スコア<sup>14</sup>|Yes<sup>9、15</sup>|はい (<sup>9</sup> )|Yes<sup>9、15</sup>|Yes<sup>9、15</sup>|
|Office メッセージの暗号化|いいえ|はい|はい|いいえ|
|脅威インテリジェンス|<sup>12</sup>|<sup>12</sup>|はい|<sup>12</sup>|
|**[コンプライアンス](https://docs.microsoft.com/microsoft-365/compliance/offering-home)**|||||
|SAS 70/SSAE16 の評価|はい|はい|はい|はい|
|ISO 27001 認定|はい|はい|はい|はい|
|EU モデル条項|はい|はい|はい|はい|
|EU セーフ ハーバー|はい|はい|はい|はい|
|HIPAA ビジネス アソシエイト契約|はい|はい|はい|はい|
|FISMA 運用認可|はい|はい|はい|はい|
|Microsoft データ処理契約|はい|はい|はい|はい|
|PCI DSS レベル 1|はい|はい|はい|はい|
|PCI 準拠 PAN データ|いいえ|いいえ|いいえ|いいえ|
|**[サービスの継続性](../../office-365-platform-service-description/service-health-and-continuity.md)**|はい|はい|はい|はい|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|BlackBerry Internet Service (BIS) の使用|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|
|**[パートナー](../../office-365-platform-service-description/partners.md)**|||||
|指定されたプランを使用しているカスタマーに対する試用版への招待および発注書の作成|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|
|代理管理の提供|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|
|**[サービス レベル契約](../../office-365-platform-service-description/service-level-agreement.md)**|はい|はい|はい|はい|
|**[製品使用権](../../office-365-platform-service-description/product-use-rights.md)**|はい|はい|はい|はい|

> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、Microsoft 365 Apps for enterprise のサブスクリプションが必要です。これは、Office 365 Government G1 または Office 365 Government F3 には含まれていません。 >
<br/><sup>2</sup> 既存の bbcs および BIS お客様は、サービスを引き続き使用できます。 新規のお客様の受け付けはしていません。
<br/><sup>3</sup> ディレクトリ同期を使用する場合は、Office 365 ポータルではなく Active directory を使用するか、Windows PowerShell の Azure Active directory モジュールを使用して、アカウントを削除するか、パスワードを変更する必要があります。
<br/><sup>4</sup> パスワード同期を使用する場合、ユーザーはローカルの Active Directory でパスワードを変更する必要があります。
<br/><sup>5</sup> ユーザーのセルフサービスのパスワード管理ポリシーを設定する方法については、「 [Azure AD でパスワードを管理](https://azure.microsoft.com/documentation/articles/active-directory-manage-passwords/)する」を参照してください。
<br/><sup>6</sup> 以前のバージョンの office 365 からアップグレードしていない場合は、office 365 でパブリック web サイトを1つしか使用できません。 この場合、パブリック Web サイトが 2 つあっても、どちらか一方のサイトしかカスタム ドメイン名でホストすることができません。 ビジネスサブスクリプションで2つの web サイトを操作する方法の詳細については、「 [2 つの Office 365 パブリック web サイトの操作](https://go.microsoft.com/fwlink/p/?LinkID=271589)」を参照してください。 別のサブスクリプションをお持ちの場合は、「 [365 Office web サイトホスティングとパブリック web サイトについて」](https://go.microsoft.com/fwlink/p/?LinkID=325009)を参照してください。
<br/><sup>7</sup> 年割引を使用して購入された座席は、早期の解雇料金の対象となる場合があります。 これは月単位で支払われるサブスクリプションには適用されません。
<br/><sup>8</sup> 以下のプランでは、Microsoft 365 管理センターからのライセンスシートの変更をサポートしていません。 Office 365 government G1、Office 365 government G3、Office 365 government F3。
<br/><sup>9</sup> 現時点では GCC では使用できませんが、近日中に公開されています。
<br/><sup>10</sup> for Office 365 Government G1、G3、および F3、対象指定リリース、および office 365 for business ロードマップが適用されます。ただし、 [コンプライアンス要件](https://www.microsoft.com/trust-center)により、特定のサービス更新に関して何らかの相違や遅延が発生する場合があります。
<br/><sup>11</sup> まだ Office 365 Government では利用できませんが、近日中に提供されています。
<br/><sup>12</sup> 含まれていませんが、GCC で個別のアドオンとして購入できます。
<br/><sup>13</sup> Office 365 Government 製品ではサポートされていません。
<br/><sup>14</sup> 使用可能 [https://securescore.office.com](https://securescore.office.com) です。 管理者のアクセス許可が必要です。 詳細については、「 [Office 365 Secure Score の概要](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-secure-score)」を参照してください。
).
<br/><sup>15</sup> 現時点では DoD 環境では使用できませんが、近日中に提供されます。
<br/><sup>16</sup> 管理センターには、DoD または GCC の高度な環境での利用状況分析は含まれていません。
<br/><sup>17</sup> GCC High または DoD 環境ではサポートされていません。
<br/><sup>18</sup> マルウェア対策は、ユーザーおよびドメインの偽装およびスプーフィングインテリジェンスについては、GCC High および DoD ではまだ利用できません。
<br/><sup>19</sup> 現時点では GCC 環境では使用できませんが、近日中に提供されます。
<br/><sup>20 個</sup> の Microsoft Stream のみ: 公開または共有を行いません。
<br/><sup>21</sup> MICROSOFT Graph API または microsoft Teams では使用できません。

## <a name="office-application-availability-and-enterprise-value"></a>Office アプリケーションの可用性とエンタープライズ価値

次の表には、Office 365 US Government プラン全体にわたって利用可能な Office アプリケーション機能が示されています。<br><br>

|アプリケーション/機能|Office 365 Government G1|Office 365 Government G3|Office 365 Government G5|Office 365 Government F3|
|---|---|---|---|---|
|**Office アプリケーション**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|いいえ|はい|はい|いいえ|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|いいえ|はい|はい|いいえ|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|いいえ|はい|はい|いいえ|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|いいえ|はい|はい|いいえ|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|いいえ|はい|はい|いいえ|
|Microsoft Forms<sup>7</sup>|はい|はい <br/>|はい|いいえ|
|Microsoft ホワイトボード<sup>7</sup>|いいえ|はい|はい|いいえ|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|いいえ|はい|はい|いいえ|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|いいえ|はい|はい|いいえ|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|はい<sup>3</sup>|はい|はい|はい<sup>3</sup>|
|[Office for Mac for Office 365](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|いいえ|はい|はい|いいえ|
|[IPad/iPhone 用 Office Mobile](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|はい|はい<sup></sup>|はい<sup></sup>|はい|
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|はい|はい<sup></sup>|はい<sup></sup>|はい|
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|はい|はい<sup>4</sup>|はい<sup>4</sup>|はい|
|Office Mobile for Windows 10 tablets|はい|はい<sup></sup>|はい<sup></sup>|はい|
|IOS および Android 用の Outlook<sup>5、4</sup>|はい|はい|はい|はい|
|**企業にとっての利点**|**Office 365 Government G1**|**Office 365 Government G3**|**Office 365 Government G5**|**Office 365 Government F3**|
|PC または Mac 上のユーザーごとに 5 個のインストール|いいえ|はい|はい|いいえ|
|自動化されたユーザー アカウント プロビジョニング|はい|はい|はい|はい|
|多言語ユーザー インターフェイス|いいえ|はい|はい|いいえ|
|クライアント プッシュ展開|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|社内 Exchange のクライアント サポート|いいえ|はい|はい|いいえ|
|社内 SharePoint のクライアント サポート|いいえ|はい|はい|いいえ|
|ソフトウェア更新の制御|いいえ|はい|はい|いいえ|
|データベース比較|いいえ|はい|はい|いいえ|
|デスクトップの仮想化|いいえ|はい|はい|いいえ|
|Excel スプレッドシート比較|いいえ|はい|はい|いいえ|
|Excel スプレッドシート検査|いいえ|はい|はい|いいえ|
|Exchange Online と SharePoint Online のアーカイブとコンプライアンス|いいえ|はい|はい|いいえ|
|グループ ポリシーのサポート|いいえ|はい|はい|いいえ|
|Azure Information Protection を使用した Information Rights Management|いいえ<sup>1</sup>|はい<sup>6</sup>|はい<sup>6</sup>|いいえ<sup>1</sup>|
|Windows Server AD RMS を使用した Information Rights Management|はい<sup>2</sup>|はい<sup>2</sup>|はい<sup>2</sup>|はい<sup>2</sup>|
|Office アドイン、ActiveX、および BHO のサポート|いいえ|はい|はい|いいえ|
|OneNote クライアントから SharePoint Server、SharePoint Online、OneDrive for Business、Office 365 上のノートブックへのアクセス|いいえ|はい|はい|いいえ|
|Office Lens|いいえ|いいえ|いいえ|いいえ|
|Office テレメトリ|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|クライアント アプリケーションのオフライン サポート|いいえ|はい|はい|いいえ|
|最適化されたサイド バイ サイド クライアント インストール|いいえ|はい|はい|いいえ|
|Power Map for Excel|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|Power Pivot for Excel|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|Power Query for Excel|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|Power View for Excel|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|ローミング設定|いいえ|はい<sup></sup>|はい<sup></sup>|いいえ|
|共有コンピューターのライセンス認証|いいえ|はい|はい|いいえ|
|クラウドベース ファイル ストレージのブロックのサポート|いいえ|はい|はい|いいえ|
|バージョン アップグレード|いいえ|はい<sup>4</sup>|はい<sup>4</sup>|いいえ|
|Volume activation (KMS/MAK)|いいえ|いいえ|いいえ|いいえ|

> <sup>1</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、Microsoft 365 Apps for enterprise のサブスクリプションが必要です。これは、Office 365 Government G1 または Office 365 Government F3 には含まれていません。
<br/><sup>2</sup> WINDOWS SERVER AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。
<br/><sup>3</sup> Skype For business Basic は、すべてのお客様が利用できます。 Skype for Business デスクトップ クライアントは、Skype for Business Online を含む Office 365 プランのプレゼンス機能、インスタント メッセージング機能、会議機能を提供するローカルにインストールされるアプリケーションです。 Microsoft 365 Apps for enterprise、および Office 365 Enterprise E3 には、高度なテレフォニーサポート、アーカイブ、コンプライアンス機能などの追加機能が含まれる、完全な Skype アプリケーションが含まれています。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](https://docs.microsoft.com/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup> 現時点では GCC High または DoD 環境では使用できませんが、近日中に提供されます。
<br/><sup>5</sup> 詳細について [は、「Government Community Cloud で Outlook For iOS と Outlook For Android を使用する](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 」を参照してください。
<br/><sup>6</sup> Office 365 DoD 環境ではまだ使用できませんが、近日中に提供されます。
<br/><sup>7</sup> アプリケーションは、現時点では利用できない特定の機能を除き、政府機関のクラウドで完全に使用できます。 詳細については、「 [Office アプリケーション機能の可用性](#office-application-and-feature-availability-in-government-plans) 」を参照してください。

## <a name="office-application-and-feature-availability-in-government-plans"></a>政府機関向けプランで利用できる Office アプリケーションと機能

政府機関向けクラウドで利用できる Office アプリケーションは次のとおりです。ただし、表で、表に示されるとおり、一部のクラウドベース機能は現在利用できない可能性があります。<br><br>

|アプリケーション/機能|GCC|GCC High|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用でき **ません** 。||||
|3D 埋め込みアニメーションと 3D モデル|いいえ|いいえ|いいえ|
|データ型|いいえ|いいえ|いいえ|
|フラッシュ フィル|いいえ|いいえ|いいえ|
|Ideas (Insight サービス)|いいえ|いいえ|いいえ|
|Power BI との統合の強化 (カスタムビジュアル、Excel からの直接 PBI グラフの作成)|いいえ|いいえ|いいえ|
|Intelligent Digital Ink|いいえ|いいえ|いいえ|
|Office 365 グループ|いいえ|いいえ|いいえ|
|ピボットテーブルに接続されたピボットグラフ データ|いいえ|いいえ|いいえ|
|PowerPivot|いいえ|いいえ|いいえ|
|Power BI への公開|いいえ|いいえ|いいえ|
|リアルタイムの共同作業 (プレゼンス, 通常の共同編集, ドキュメント内チャット)|いいえ|いいえ|いいえ|
|[私と共有]|いいえ|いいえ|いいえ|
|スマート検索|いいえ|いいえ|いいえ|
|グラフ: サンバーストツリー、ウォーターフォール、ヒストグラム、地図、タイムライン、じょうご|いいえ|いいえ|いいえ|
|バージョン履歴|いいえ|いいえ|いいえ|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用でき **ません** 。|**GCC**|**GCC High**|**DOD**|
|メール通知|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ|
|画像の挿入|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ|
|ビデオの挿入|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ|
|数学|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ|
|Office との統合|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ|
|最近使用したグループ フォーム|いいえ<sup>4</sup>|はい|はい|
|外部共有<sup>3</sup>|はい|いいえ|いいえ|
|フォーム Pro|いいえ|いいえ|いいえ|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、この時点では利用でき **ません** 。|**GCC**|**GCC High**|**DOD**|
|リサーチ ツール|いいえ|いいえ|いいえ|
|Intelligent Digital Ink|いいえ|いいえ|いいえ|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用でき **ません** 。|**GCC**|**GCC High**|**DOD**|
|Office サウンド (一部)|いいえ|いいえ|いいえ|
|動的データ交換 (DDE) が既定で無効になっている|いいえ|いいえ|いいえ|
|ディクテーション|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用でき **ません** 。|**GCC**|**GCC High**|**DOD**|
|スマート検索|いいえ|いいえ|いいえ|
|Office サウンド (一部)|いいえ|いいえ|いいえ|
|3D モデルと 3D 埋め込みアニメーションと|いいえ|いいえ|いいえ|
|グラフ: マップ|いいえ|いいえ|いいえ|
|Intelligent Digital Ink|いいえ|いいえ|いいえ|
|PowerPoint のライブキャプションと字幕|いいえ|いいえ|いいえ|
|プレゼンター コーチ|いいえ|いいえ|いいえ|
|[私と共有]|いいえ|いいえ|いいえ|
|共有 との Skype for Business の統合|いいえ|いいえ|いいえ|
|バージョン履歴|いいえ|いいえ|いいえ|
|Office 365 グループ|いいえ|いいえ|いいえ|
|リアルタイムの共同作業 (プレゼンス, 通常の共同編集, ドキュメント内チャット)|いいえ|いいえ|いいえ|
|ディクテーション|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ<sup>1</sup>|
|スライドの再利用|いいえ|いいえ|いいえ|
|政府機関向けクラウドでの **Microsoft Whiteboard** は、現在 Hub クライアントでのみ利用可能で、デスクトップでは利用できません。|**GCC**<sup>2</sup>|**GCC High**<sup>2</sup>|**DOD**<sup>2</sup>|
|付箋、テキスト、画像の挿入|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|
|インクを図形に変換とインクを表に変換|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|
|インクをきれいにする|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|
|画像をインクに変換|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|
|アクセシビリティ チェック|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|はい<sup>2</sup> <br/>|
|動的テンプレート (かんばん、SWOT など)|いいえ|いいえ|いいえ|
|リアルタイム コラボレーション|いいえ|いいえ|いいえ|
|リアルタイムのプレゼンス|いいえ|いいえ|いいえ|
|コンテンツへのリアクション|いいえ|いいえ|いいえ|
|ホワイトボードのボード ギャラリー (自分と共有されたものを含む)|いいえ|いいえ|いいえ|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word) は、次の機能を除き、政府機関のクラウドで完全に利用できます。ただし、現時点では利用でき **ません** 。|**GCC**|**GCC High**|**DOD**|
|スマート検索|いいえ|いいえ|いいえ|
|リサーチ ツール|いいえ|いいえ|いいえ|
|Office サウンド|いいえ|いいえ|いいえ|
|3D モデル|いいえ|いいえ|いいえ|
|3D 埋め込みアニメーション|いいえ|いいえ|いいえ|
|タップ|いいえ|いいえ|いいえ|
|履歴書アシスタント|いいえ|いいえ|いいえ|
|マップ グラフ|いいえ|いいえ|いいえ|
|Intelligent Digital Ink|いいえ|いいえ|いいえ|
|[私と共有]|いいえ|いいえ|いいえ|
|翻訳|いいえ|いいえ|いいえ|
|共有 との Skype for Business の統合|いいえ|いいえ|いいえ|
|バージョン履歴|いいえ|いいえ|いいえ|
|Office 365 グループ|いいえ|いいえ|いいえ|
|共同編集者とのコンテキストに応じたチャット: ドキュメント内の共同編集者とのチャット|いいえ|いいえ|いいえ|
|ディクテーション|いいえ<sup>1</sup>|いいえ<sup>1</sup>|いいえ<sup>1</sup>|

GCC/GCC High/DoD 内の Microsoft Teams で利用できる機能については、「 [Microsoft teams サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/teams-service-description)」を参照してください。
> <sup>1 つ</sup> の利用可能時間。
<br/><sup>2</sup> ローカル Surface Hub での可用性 (サインインしていない場合)。
<br/><sup>3 つ</sup> の外部共有が GCC 環境で使用できます。 組織で [Microsoft Forms をオンまたは](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) オフにする方法について説明します。 GCC High および DOD 環境では、外部共有は無効になっています。組織内のユーザーは、フォームを完成させ、応答を送信したり、フォーム [をテンプレートとして複製および共有](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)したり、 [フォームで共同編集または共同作業](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)を行ったり、 [フォームの結果にアクセス](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)したりすることがあります。
<br/><sup>4</sup> 最近のグループフォーム機能は、GCC 環境では無効になっています。 ただし、ユーザーはグループフォームタブで特定のグループを選択することで、グループフォームにアクセスできます。
