---
title: Exchange Online環境向け
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、米国政府機関のクラウドと商用クラウドの機能の違いの概要について説明します(「サービスの説明」にExchange Online示します。
ms.openlocfilehash: cf1b995f8497ff2249504b195ecaf1b2f7c6f62c
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653289"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online環境向け

この記事では、米国政府機関向けクラウドと商用クラウドの機能の違いの概要について説明します(「サービスの説明」にExchange Online[示します](../../exchange-online-service-description/exchange-online-service-description.md)。 Exchange Online (Government Community Cloud)、GCC、GCC (DoD) 環境で使用できます。

適格性や購入を含む政府機関のクラウドの詳細については、「Microsoft 365 [- 購入方法」を参照してください](./microsoft-365-government-how-to-buy.md)。 プランとプランOffice 365 Government比較するには、「Office 365 Government[プラン」を参照してください](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

ネットワーク接続を管理する際に必要なエンドポイントの詳細については[、「Office 365](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)米国政府機関 GCC 高エンドポイント」または「Office 365 米国政府機関の[DoD](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)エンドポイント」を参照してください。

組織は、Office 365の機能を楽しむだけでなく、米国政府のクラウド環境に固有の次の機能を利用できます。

- 組織の顧客コンテンツは、商用サービスの顧客コンテンツと論理的にOffice 365されます。

- 組織の顧客コンテンツは米国内で保存されます。

- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。

- 政府機関のクラウド環境は、多くの場合、米国の公的機関のお客様に必要な認定と認定に準拠しています。

すべての商用機能と機能を政府機関Exchangeに提供する一般的な目的です。 つまり、政府機関のクラウド顧客の要件のために利用できない機能もあります。 その他の機能は政府機関の環境に提供されますが、まだ利用できません。 政府機関のクラウド環境での機能の可用性については、以下のセクションを参照してください。

## <a name="exchange-online-features"></a>Exchange Online の機能

次の表では、指定したExchange Online機能を、GCC、GCC DoD 環境内で使用できるかどうかを示します。 サポートの声明 (またはその不足) に関するニュアンスがある場合は、追加のコンテキストが提供されます。<br><br>

| 機能 | GCC | GCC High | DoD | 主な考慮事項 |
|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|サポートされているハイブリッド展開|はい|はい|はい|オンプレミスの Exchange Serverと共存するには、少なくとも 1 つの Exchange Server 2013 クライアント アクセス サーバー (または 2016 Exchange Serverが必要です。 Exchange Server 2010 以前はサポートされていません。|
|サポートされている IMAP 移行|はい|はい|はい||
|カット オーバー移行のサポート|はい|はい|はい||
|サポートされている段階的な移行|はい|はい|はい|GSuite の移行は、High および DoD のGCCサポートされていません。 詳細については <a href="/exchange/mailbox-migration/perform-g-suite-migration">、「GSuite 移行の実行」を参照してください</a>。|
|**[アクセス許可](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|役割に基づくアクセス許可|はい|はい|はい||
|役割グループ|はい|はい|はい||
|役割の割り当てポリシー|はい|はい|はい||
|**[メッセージ ポリシーとコンプライアンス](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Exchange Online ベースのメールボックスのアーカイブ|はい|はい|はい||
|社内メールボックスのクラウドベースのアーカイブ|はい|はい|はい||
|Messaging Records Management(MRM) |はい|はい|はい||
|手動保持ポリシー、ラベル、およびタグ |はい|はい|はい||
|保存中のデータの暗号化 (BitLocker)|はい|はい|はい||
|Azure Information Protection を使用した IRM|はい|はい|はい|High および DoD の A GCC IP の制限の詳細については<a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">、「Azure Information Protection</a>プレミアム」を参照してください。<br><br>Azure Information Protection は G1/F3 には含まれていませんが、個別のアドオンとして購入できます。サポートされている Information Rights Management (IRM) 機能を有効にできます。 Azure Information Protection の一部の機能では、Office 365 ProPlus F3 に含まれていないサブスクリプションOffice 365 Government G1必要Office 365 Governmentがあります。|
|Windows Server AD RMS を使用した IRM|はい|はい|はい| Windows Server AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。|
|Office 365 Message Encryption|はい|はい|はい|GCC High/DoD ユーザーと非 GCC High/DoD ユーザーの<a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment"></a>間でメッセージを送信する場合の Office 365 Message Encryption の動作のニュアンスを文書化する GCC High 展開では、GCC [High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)境界全体の Office 365 Message Encryption の動作と Office 365 Message Encryption の固有の特性を参照してください。|
|顧客キー|はい|はい|はい|G5 サービスプランが必要です。|
|S/MIME|はい|はい|はい||
|インプレース保持と訴訟ホールド|はい|はい|はい|G3 または G5 のサービス プランが必要です。|
|インプレース電子情報開示 (eDiscovery)|はい|はい|はい||
|メール フロー ルール|はい|はい|はい||
|Data loss prevention|はい|はい|はい|G3 または G5 のサービス プランが必要です。|
|ジャーナル|はい|はい|はい||
|**[スパム対策とマルウェア対策の保護](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|組み込みのスパム対策保護|はい|はい|はい||
|Customize anti-spam policies|はい|はい|はい||
|組み込みのマルウェア対策保護|はい|はい|はい||
|Customize anti-malware policies|はい|はい|はい||
|検疫 - 管理者による管理|はい|はい|はい||
|検疫 - エンドユーザーによる自己管理|はい|はい|はい||
|Microsoft Defender for Office 365|はい|はい|はい|G5 Service プラン (またはアドオンの購入) が必要です。<br><br>ユーザーとドメインの偽装およびスプーフィング インテリジェンスに対するフィッシング対策は、GCC DoD では使用できません。|
|**[メール フロー](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|送信メールのカスタム ルーティング|はい|はい|はい||
|Secure messaging with a trusted partner|はい|はい|はい||
|Conditional mail routing|はい|はい|はい||
|受信セーフ リストへのパートナーの追加|はい|はい|はい||
|ハイブリッド 電子メール ルーティング|はい|はい|はい||
|**[受信者](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|容量のアラート|はい|はい|はい||
|クラッター機能|はい|はい|はい||
|メール ヒント|はい|はい|はい||
|代理人アクセス|はい|はい|はい||
|受信トレイのルール|はい|はい|はい||
|接続されているアカウント|はい|いいえ|いいえ|この機能は、サードパーティ サービスへのGCC制限のため、High または DoD ではサポートされていません。 影響を受け取る機能の詳細については、この記事の [「サードパーティ サービス](#connectivity-with-third-party-services) との接続」を参照してください。|
|非アクティブなメールボックス|はい|はい|はい|G3 または G5 のサービス プランが必要です。|
|オフライン アドレス帳|はい|はい|はい||
|アドレス帳ポリシー|はい|はい|はい||
|階層型アドレス帳|はい|はい|はい||
|アドレス一覧とグローバル アドレス一覧|はい|はい|はい||
|Office 365 グループ|はい|はい|はい|ユーザー グループへのOffice 365は、High 環境と DoD 環境GCCサポートされていません。 詳細については <a href="/azure/azure-government/documentation-government-services-securityandidentity">、「Azure Government Security + Identity」を参照してください</a>。|
|配布グループ|はい|はい|はい||
|外部連絡先 （グローバル）|はい|はい|はい|高レベル環境と DoD 環境では、組織GCC制限が適用されます。 |
|ソーシャル ネットワークとの連絡先のリンク|はい|いいえ|いいえ|この機能は、High または DoD GCCサポートされていません。|
|リソース メールボックス|はい|はい|はい||
|会議室の管理|はい|はい|はい||
|不在時の返信|はい|はい|はい||
|インターネット カレンダーの共有|はい|いいえ|いいえ|GCC High では、インターネット カレンダーの発行/共有は、GCC High ユーザーが共有する予定表への受信接続には機能しますが、GCC High 以外の共有予定表に送信を接続する GCC 高ユーザーには機能します。<br><br>DoD-Internet Calendar の共有は、その環境での受信/送信接続許可リストの要件のためにサポートされていません。|
|**[レポート機能とトラブルシューティング ツール](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Microsoft 365管理センター レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|Web サービス レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|Message trace|はい|はい|はい||
|監査レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|ユニファイド メッセージングのレポート|はい|いいえ|いいえ||
|**[共有とコラボレーション](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|フェデレーション共有 (予定表の発行を含む)|はい|はい|はい|制限は、High と DoD の両方GCC存在します。 この記事 [の「空き時間情報フェデレーション](#freebusy-federation) 」を参照してください。|
|サイト メールボックス|はい|はい|はい||
|パブリック フォルダー|はい|はい|はい||
|**[クライアントとモバイル デバイス](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|To Do Web 上の情報|はい|いいえ|いいえ||
|Outlook for Windows|はい|はい|はい|高および doD GCC要件を満たすには、少なくともバージョン 1803 のコンプライアンス要件を満たす必要Office 365 ProPlus。 Office 365 ProPlus G1 または F3 には含まれません。|
|Outlook on the web|はい|はい|はい||
|Outlook for Mac|はい|はい|はい|高および doD GCC要件を満たすには、少なくともバージョン 1803 のコンプライアンス要件を満たす必要Office 365 ProPlus。 Office 365 ProPlus G1 または F3 には含まれません。|
|iOS および Android 用の Outlook|はい|はい|はい||
|Exchange ActiveSync|はい|はい|はい||
|ユーザーの基本的なモビリティとセキュリティMicrosoft 365|はい|いいえ|いいえ||
|POP と IMAP|はい|はい|はい||
|SMTP|はい|はい|はい||
|EWS アプリケーションのサポート|はい|はい|はい||
|**[音声メッセージ サービス](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|ボイス メール|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムとユニファイド メッセージングExchange Online統合はサポートされていません。|
|ボイス メールとサード パーティ FAX の統合|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムとユニファイド メッセージングExchange Online統合はサポートされていません。|
|サードパーティ ボイス メールの相互運用性|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムとユニファイド メッセージングExchange Online統合はサポートされていません。|
|Skype for Business統合|はい|はい|はい||
|**[高可用性とビジネス継続性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|データセンターでのメールボックスレプリケーション|はい|はい|はい||
|削除済みメールボックスの回復|はい|はい|はい||
|削除済みアイテムの回復|はい|はい|はい||
|単一アイテムの回復|はい|はい|はい||
|**[相互運用性、接続、および互換性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|OWA と OWA でのプレゼンスOutlook|はい|はい|はい||
|SharePoint相互運用性|はい|はい|はい||
|EWS 接続のサポート|はい|はい|はい||
|SMTP リレーのサポート|はい|はい|はい||
|**[Exchange Online のセットアップと管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Microsoft Office 365 ポータルへのアクセス|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|Microsoft 365管理センターへのアクセス|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|Exchange 管理センターへのアクセス|はい|はい|はい||
|リモート Windows PowerShell へのアクセス|はい|はい|はい||
|モバイル デバイスの ActiveSync ポリシー|はい|はい|はい||
|利用状況レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在<a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a>、米国政府機関Office 365のプラットフォーム機能セクションを参照してください。|
|**[サービスの拡張 - カスタマイズ、アドイン、およびリソース](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Outlookアドインと MAPI のOutlookする|はい|はい|はい|一部の OWA および Outlookは、High および DoD GCC使用できます。 詳細[については、この記事の「OutlookおよびOutlook Web Appアドイン](#add-insin-outlook-and-outlook-web-app)」を参照してください。|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>High 環境と DoD 環境GCC機能のニュアンス

### <a name="connectivity-with-third-party-services"></a>サードパーティ サービスとの接続  

高GCC DoD 環境はどちらも、明示的な承認と送信接続の構成を必要とする制限された環境です。 さらに、Microsoft は、これらの環境から商用クラウド サービス (商用 Office 365、Google GSuite、Amazon Web Services など) への送信アクセスを許可する要求に対応できません。

これらの制限により、GCC High/DoD 環境からのこの送信接続に依存する機能は、次のような一般にサポートされていません。

- 接続されたアカウント - ユーザーはアカウントを追加/同期できません (Google、POP/IMAP など)。

- サードパーティのファイル ストレージ プロバイダーのサポート - ファイルの添付/共有を目的として *、GCC High/DoD* 内のユーザーの OneDrive for Business アカウントのみ、さまざまな Outlook クライアント内からアクセスできます。 サードパーティのストレージ アカウント (Dropbox Box、Google ドライブ) は追加できません。

- Facebook や LinkedIn などのソーシャル ネットワークとの接続。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active DirectoryB2B コラボレーション

Azure Active DirectoryB2B コラボレーションは現在、Azure US Government クラウド内の組織と、両方が B2B コラボレーションをサポートしている組織間でのみサポートされています。

さらに、B2B ユーザーは、Office 365グループのゲストとして、GCC DoD 環境ではサポートされません。 

詳細と最新の更新プログラムについては [、「Azure Government Security + Identity」を参照してください](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 Message Encryption/DoD 境界GCC動作

高レベル環境で Office 365 Message EncryptionをGCCする場合は、受信者エクスペリエンスに関する次の固有の特性に注意してください。  

- 暗号化された電子メールを同じ環境GCC高または DoD から受信者に送信する場合は、次の手順を実行します。
    
    - 送信者は、Outlook for PC と Mac、および web 上の Outlook で電子メールを手動で暗号化するか、組織が Exchange メール フロー ルールを使用して電子メールを暗号化するポリシーを設定できます。
    
    - GCC High/DoD 内の受信者は、pc と Mac の Outlook でインライン読み取りエクスペリエンスを受け取り、Outlook は他のすべてのユーザーと同Office 365します。

<!-- end list -->

- 暗号化された電子メールを GCC High または DoD からその環境外の受信者 (GCC および商用を含む) に送信する場合:
    
    - High/DoD GCC内の送信者は、High/DoD 境界の外部でGCCメールを送信できます。
    
    - GCC High/DoD 以外のすべての受信者 (商用 Office 365 ユーザー、Outlook.com ユーザー、その他のメール プロバイダーのユーザーを含む) は、ラッパー メールを受信します。 このラッパー メールは受信者を OME ポータルにリダイレクトし、受信者はメッセージの読み取りおよび返信を行います。

詳細と最新の更新プログラムについては [、「OME のバージョンを比較する」を参照してください](/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>空き時間情報フェデレーション

フェデレーション共有 (空き時間情報を含む) は、現在、GCCおよび DoD 環境でいくつかの重要な制限の対象になります。

[高GCC環境:

- フェデレーション信頼 (双方向の空き時間情報共有を含む) は、GCC High 内のテナントとハイブリッド共存 (Exchange 2013 以降) でサポートされます。

- フェデレーション共有は、High および GCCまたは商用のテナントGCC Office 365されません。 現時点では、GCC High 環境から商用クラウド (GCCおよび商用Office 365を含む) への送信接続は許可されません。 その結果、GCC高いユーザーは、共有予定表情報にアクセスするために、GCC/商用に対して必要な送信要求を行う必要があります。

DoD 環境では、次の操作を行います。

  - 現在、フェデレーション信頼 (空き時間情報の共有を含む) は、DoD 環境内のテナント間でのみサポートされています。 DoD テナントとビジネス テナントまたは商用テナントGCCサポートされていません。

### <a name="client-configuration"></a>クライアント構成

ProPlus の展開と構成には、追加の手順 (Officeを含む) がOutlook。 これらの手順の詳細については、「High 環境または DoD 環境でのMicrosoft 365 Apps for enterprise展開GCC[ガイダンス」を参照してください](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)。

Outlook Android の場合は、High 環境と DoD 環境GCC使用することもできます。 これらの環境での機能の制限と管理の詳細については、「Outlook で iOS と Android を使用する[」を参照Government Community Cloud。](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>アドインとOutlookアドインOutlook Web App  

一部の OWA および Outlookは、High および DoD GCC使用できます。 My Templates と Suggested Meetings は使用可能で、機能する予定です。 サポートされている既定の OWA アドインは 5 つのみです。 ただし、サード パーティ製アプリケーションとの統合は可能ですが、これらの統合は、高値または DoD の Microsoft コンプライアンスGCC対象とされません。 お客様は、組織のアドオンを構成する前に、サードパーティのデータ処理のプラクティスとコンプライアンスの約束を理解する必要があります。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>環境内の機能のニュアンスGCCに対応Microsoft To Do

| 機能 | 説明 | WW | GCC |
|:-----|:-----|:-----|:-----|
|サポートされているプラットフォーム|Web、Android、iOS、Mac、Windows|すべて|Web のみ|
|M365 ハブのサポート|Planner、Outlook、Teamsとの統合|すべて|Outlook Planner (Teamsタスク アプリでTeams利用可能)|
|Wunderlist移行|wunderlist ユーザーが Web 上のユーザーにデータTo Do移行を許可する|はい|いいえ|
|プッシュ通知|リマインダーなどのプッシュ通知をエンド ユーザーに送信する|はい|いいえ|
|ヘルプシフトのサポート|ヘルプシフト インターフェイスを使用してサポート要求を作成する|はい|いいえ|
|My Day|1 日の計画|はい|はい|
|計画リスト|期日を持つすべてのタスクを表示する|はい|はい|
|[自分に割り当て済み] リスト|共有リスト、Planner または WXP で割り当てられているすべてのタスク (将来)|はい|はい|
|フラグ付きメール|Outlook でタスクとしてフラグが設定されたメールを表示する|はい|はい|
|マルチ アカウントのサポート|1 つのウィンドウでホーム アカウントと Office アカウントを使用する|はい|はい|
|リスト共有|同じ組織内の同僚とリストを共有する|はい|はい|
|テナント間の共有|組織外でタスク リストを共有する|はい|いいえ|
|アラームと繰り返し|タスクのリマインダーを設定する |はい|はい|

*記載されていないその他の機能は、両方の環境で使用できます。