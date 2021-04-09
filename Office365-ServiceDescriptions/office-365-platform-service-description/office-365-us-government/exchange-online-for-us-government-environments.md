---
title: Exchange Online for US Government 環境
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、Exchange Online サービスの説明に記載されている米国政府機関クラウドと商用クラウドの機能の違いの概要を説明します。
ms.openlocfilehash: cf1b995f8497ff2249504b195ecaf1b2f7c6f62c
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653289"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online for US Government 環境

この記事では、Exchange Online サービスの説明に記載されている米国政府機関クラウドと商用クラウドの機能の違いの概要 [について説明します](../../exchange-online-service-description/exchange-online-service-description.md)。 Exchange Online は、政府機関コミュニティ クラウド (GCC)、GCC High、および国防総省 (DoD) 環境で利用できます。

適格性と購入を含む政府機関クラウドの詳細については [、「Microsoft 365 Government - How to buy 」を参照してください](./microsoft-365-government-how-to-buy.md)。 365 Officeプランと比較するには、「365 Government プラン [Officeを参照してください](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)。

ネットワーク接続を管理する際に必要なエンドポイントについては [、「Office 365 米国政府機関 GCC High](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) エンドポイント」または [「Office 365](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)米国政府機関の DoD エンドポイント」を参照してください。

組織は、365 から 365 の機能Office、米国政府機関のクラウド環境に固有の次の機能を利用できます。

- 組織の顧客コンテンツは、商用サービスおよび 365 サービス内の顧客Office分離されます。

- 組織の顧客コンテンツは米国内で保存されます。

- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。

- 政府機関のクラウド環境は、多くの場合、米国の公的機関のお客様に必要な認定と認定に準拠しています。

すべての Exchange 商用機能を政府機関のクラウド環境に提供する一般的な目的です。 つまり、政府機関のクラウド顧客の要件のために利用できない機能もあります。 その他の機能は政府機関の環境に提供されますが、まだ利用できません。 政府機関のクラウド環境での機能の可用性については、以下のセクションを参照してください。

## <a name="exchange-online-features"></a>Exchange Online の機能

次の表は、指定された Exchange Online 機能が GCC、GCC High、DoD 環境内で使用できるかどうかを示しています。 サポートの声明 (またはその不足) に関するニュアンスがある場合は、追加のコンテキストが提供されます。<br><br>

| 機能 | GCC | GCC High | DoD | 主な考慮事項 |
|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|サポートされているハイブリッド展開|はい|はい|はい|オンプレミスの Exchange Serverと共存するには、少なくとも 1 つの Exchange Server 2013 クライアント アクセス サーバー (または 2016 年Exchange Serverインストールする必要があります。 Exchange Server 2010 以前はサポートされていません。|
|サポートされている IMAP 移行|はい|はい|はい||
|カット オーバー移行のサポート|はい|はい|はい||
|サポートされている段階的な移行|はい|はい|はい|GSUITE の移行は、GCC High および DoD ではサポートされていません。 詳細については <a href="/exchange/mailbox-migration/perform-g-suite-migration">、「GSuite 移行の実行」を参照してください</a>。|
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
|Azure Information Protection を使用した IRM|はい|はい|はい|GCC High および DoD での AIP の制限の詳細については、「Azure Information Protection Premium Government Service Description」 <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">を参照してください</a>。<br><br>Azure Information Protection は G1/F3 には含まれていませんが、個別のアドオンとして購入できます。サポートされている Information Rights Management (IRM) 機能を有効にできます。 Azure Information Protection の一部の機能では、Office 365 ProPlus へのサブスクリプションが必要ですが、Office 365 Government G1 または Office 365 Government F3 には含まれません。|
|Windows Server AD RMS を使用した IRM|はい|はい|はい| Windows Server AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。|
|Office 365 Message Encryption|はい|はい|はい|GCC High/DoD 境界全体での Office 365 メッセージ暗号化の動作と、GCC High 展開での<a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">Office 365</a>メッセージ暗号化の固有の特性を参照してください。これは、GCC High/DoD ユーザーと非[GCC High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary)ユーザー間でメッセージを送信する場合の Office 365 メッセージ暗号化の動作のニュアンスを文書化します。|
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
|Microsoft Defender for Office 365|はい|はい|はい|G5 Service プラン (またはアドオンの購入) が必要です。<br><br>GCC High および DoD では、ユーザーとドメインの偽装およびスプーフィング インテリジェンスに対するフィッシング対策はまだ利用できません。|
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
|接続されているアカウント|はい|いいえ|いいえ|この機能は、サードパーティ サービスへの送信接続の制限により、GCC High または DoD ではサポートされていません。 影響を受け取る機能の詳細については、この記事の [「サードパーティ サービス](#connectivity-with-third-party-services) との接続」を参照してください。|
|非アクティブなメールボックス|はい|はい|はい|G3 または G5 のサービス プランが必要です。|
|オフライン アドレス帳|はい|はい|はい||
|アドレス帳ポリシー|はい|はい|はい||
|階層型アドレス帳|はい|はい|はい||
|アドレス一覧とグローバル アドレス一覧|はい|はい|はい||
|Office 365 グループ|はい|はい|はい|GCC High Office DoD 環境では、365 グループへのゲスト アクセスはサポートされていません。 詳細については <a href="/azure/azure-government/documentation-government-services-securityandidentity">、「Azure Government Security + Identity」を参照してください</a>。|
|配布グループ|はい|はい|はい||
|外部連絡先 （グローバル）|はい|はい|はい|GCC High 環境と DoD 環境では、組織間のコラボレーションの制限が適用されます。 |
|ソーシャル ネットワークとの連絡先のリンク|はい|いいえ|いいえ|この機能は、GCC High または DoD ではサポートされていません。|
|リソース メールボックス|はい|はい|はい||
|会議室の管理|はい|はい|はい||
|不在時の返信|はい|はい|はい||
|インターネット カレンダーの共有|はい|いいえ|いいえ|GCC High では、インターネット カレンダー発行/共有は、GCC High ユーザーが共有する予定表への受信接続には機能しますが、GCC High 以外の共有予定表に送信を接続する GCC High ユーザーには機能します。<br><br>DoD-Internet Calendar の共有は、その環境での受信/送信接続許可リストの要件のためにサポートされていません。|
|**[レポート機能とトラブルシューティング ツール](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Microsoft 365 管理センターレポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|Web サービス レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|Message trace|はい|はい|はい||
|監査レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|ユニファイド メッセージングのレポート|はい|いいえ|いいえ||
|**[共有とコラボレーション](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|フェデレーション共有 (予定表の発行を含む)|はい|はい|はい|制限は、GCC High と DoD の両方に存在します。 この記事 [の「空き時間情報フェデレーション](#freebusy-federation) 」を参照してください。|
|サイト メールボックス|はい|はい|はい||
|パブリック フォルダー|はい|はい|はい||
|**[クライアントとモバイル デバイス](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Web 上で実行するには|はい|いいえ|いいえ||
|Outlook for Windows|はい|はい|はい|GCC High および DoD コンプライアンス要件を満たすには、365 ProPlus のバージョン 1803 以上Office必要があります。 Office 365 ProPlus は G1 または F3 には含まれません。|
|Outlook on the web|はい|はい|はい||
|Outlook for Mac|はい|はい|はい|GCC High および DoD コンプライアンス要件を満たすには、365 ProPlus のバージョン 1803 以上Office必要があります。 Office 365 ProPlus は G1 または F3 には含まれません。|
|iOS 版および Android 版 Outlook|はい|はい|はい||
|Exchange ActiveSync|はい|はい|はい||
|Microsoft 365 の基本的なモビリティとセキュリティ|はい|いいえ|いいえ||
|POP と IMAP|はい|はい|はい||
|SMTP|はい|はい|はい||
|EWS アプリケーションのサポート|はい|はい|はい||
|**[音声メッセージ サービス](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|ボイス メール|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムと Exchange Online ユニファイド メッセージングの統合はサポートされていません。|
|ボイス メールとサード パーティ FAX の統合|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムと Exchange Online ユニファイド メッセージングの統合はサポートされていません。|
|サードパーティ ボイス メールの相互運用性|いいえ|いいえ|いいえ|オンプレミスの IP-PBX システムと Exchange Online ユニファイド メッセージングの統合はサポートされていません。|
|Skype for Business の統合|はい|はい|はい||
|**[高可用性とビジネス継続性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|データセンターでのメールボックスレプリケーション|はい|はい|はい||
|削除済みメールボックスの回復|はい|はい|はい||
|削除済みアイテムの回復|はい|はい|はい||
|単一アイテムの回復|はい|はい|はい||
|**[相互運用性、接続、および互換性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|OWA と Outlook でのプレゼンス|はい|はい|はい||
|SharePoint の相互運用性|はい|はい|はい||
|EWS 接続のサポート|はい|はい|はい||
|SMTP リレーのサポート|はい|はい|はい||
|**[Exchange Online のセットアップと管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Microsoft Office 365 ポータルへのアクセス|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|Microsoft 365 管理センターへのアクセス|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|Exchange 管理センターへのアクセス|はい|はい|はい||
|リモート Windows PowerShell へのアクセス|はい|はい|はい||
|モバイル デバイスの ActiveSync ポリシー|はい|はい|はい||
|利用状況レポート|はい|はい|いいえ|レポートは DoD で使用できません。 更新プログラム/現在 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">の可用性については</a> 、Office 365 US Government サービスの説明のプラットフォーム機能セクションを参照してください。|
|**[サービスの拡張 - カスタマイズ、アドイン、およびリソース](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**主な考慮事項**|
|Outlook アドインと Outlook MAPI|はい|はい|はい|一部の OWA アドインと Outlook アドインだけが GCC High および DoD で使用できます。 この [記事の「Outlook および Outlook Web Appアドイン」](#add-insin-outlook-and-outlook-web-app) を参照してください。|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC High 環境と DoD 環境内の機能のニュアンス

### <a name="connectivity-with-third-party-services"></a>サードパーティ サービスとの接続  

GCC High と DoD の両方の環境は、明示的な承認と送信接続の構成を必要とする制限された環境です。 さらに、Microsoft は、これらの環境から商用クラウド サービス (商用 Office 365、Google GSuite、Amazon Web Services など) への送信アクセスを許可する要求に対応できません。

これらの制限により、GCC High/DoD 環境からのこの送信接続に依存する機能は、次のような一般にサポートされていません。

- 接続されたアカウント - ユーザーはアカウントを追加/同期できません (Google、POP/IMAP など)。

- サードパーティのファイル ストレージ プロバイダーのサポート - ファイルの添付および共有を目的として *、GCC High/DoD* 内のユーザーの OneDrive for Business アカウントにのみ、さまざまな Outlook クライアント内からアクセスできます。 サードパーティのストレージ アカウント (Dropbox、Box、Google ドライブ) は追加できません。

- Facebook や LinkedIn などのソーシャル ネットワークとの接続。

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B コラボレーション

現在、Azure Active Directory B2B コラボレーションは、Azure US Government クラウド内の組織と、両方が B2B コラボレーションをサポートしている組織間でのみサポートされています。

さらに、365 グループのゲストOffice B2B ユーザーは、GCC High および DoD 環境ではサポートされていません。 

詳細と最新の更新プログラムについては [、「Azure Government Security + Identity」を参照してください](/azure/azure-government/documentation-government-services-securityandidentity)。

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 メッセージ暗号化の動作を GCC High/DoD 境界全体で実行する

GCC High 環境で Office 365 Message Encryption を使用する場合は、受信者エクスペリエンスに関する次の固有の特性に注意してください。  

- GCC High または DoD から同じ環境の受信者に暗号化されたメールを送信する場合:
    
    - 送信者は、Outlook for PC および Mac および Outlook on the web の電子メールを手動で暗号化したり、Exchange メール フロー ルールを使用して電子メールを暗号化するポリシーを組織で設定できます。
    
    - GCC High/DoD 内の受信者は、他のすべてのユーザー 365 ユーザーと同じインライン読み取りエクスペリエンスを Outlook for PC および Mac および Outlook on the web で受け取Officeします。

<!-- end list -->

- GCC High または DoD からその環境外の受信者 (GCC および商用を含む) に暗号化された電子メールを送信する場合:
    
    - GCC High/DoD 内の送信者は、GCC High/DoD 境界外で暗号化された電子メールを送信できます。
    
    - GCC High/DoD 以外のすべての受信者 (商用 Office 365 ユーザー、Outlook.com ユーザー、その他の電子メール プロバイダーのユーザーを含む) は、ラッパー メールを受信します。 このラッパー メールは受信者を OME ポータルにリダイレクトし、受信者はメッセージの読み取りおよび返信を行います。

詳細と最新の更新プログラムについては [、「OME のバージョンを比較する」を参照してください](/microsoft-365/compliance/ome-version-comparison)。

### <a name="freebusy-federation"></a>空き時間情報フェデレーション

フェデレーション共有 (空き時間情報を含む) は、現在、GCC High 環境と DoD 環境でいくつかの重要な制限の対象になります。

GCC High 環境では、次の条件を実行します。

- フェデレーション信頼 (双方向の空き時間情報共有を含む) は、GCC High 内のテナント間およびハイブリッド共存 (Exchange 2013 以降) でサポートされます。

- フェデレーション共有は、GCC High と GCC のテナント間または 365 商用Officeサポートされていません。 現時点では、GCC High 環境から商用クラウド (GCC および Office 365 商用を含む) への送信接続は許可されません。 その結果、GCC High ユーザーは、共有予定表情報にアクセスするために必要な送信要求を GCC/商用に行う事ができないのです。

DoD 環境では、次の操作を行います。

  - 現在、フェデレーション信頼 (空き時間情報の共有を含む) は、DoD 環境内のテナント間でのみサポートされています。 DoD テナントと GCC テナントまたは商用テナントの間ではサポートされません。

### <a name="client-configuration"></a>クライアント構成

ProPlus (Outlook を含む) の展開と構成にはOffice手順が含まれます。 これらの手順の詳細については [、「Microsoft 365 Apps for enterprise](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)を GCC High または DoD 環境に展開するためのガイダンス」を参照してください。

Outlook for iOS と Android は、GCC High 環境と DoD 環境でも利用できます。 これらの環境での機能の制限と管理の詳細については、「Using [Outlook for iOS and Android in the Government Community Cloud」を参照してください](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook と Outlook のアドインOutlook Web App  

一部の OWA アドインと Outlook アドインだけが GCC High および DoD で使用できます。 My Templates と Suggested Meetings は使用可能で、機能する予定です。 サポートされている既定の OWA アドインは 5 つのみです。 ただし、サード パーティ製アプリケーションとの統合は可能ですが、これらの統合は、GCC High または DoD の Microsoft コンプライアンスの約束ではカバーされません。 お客様は、組織のアドオンを構成する前に、サードパーティのデータ処理のプラクティスとコンプライアンスの約束を理解する必要があります。

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Microsoft To Do の GCC 環境内の機能のニュアンス

| 機能 | 説明 | WW | GCC での可用性 |
|:-----|:-----|:-----|:-----|
|サポートされているプラットフォーム|Web、Android、iOS、Mac、Windows|すべて|Web のみ|
|M365 ハブのサポート|Outlook、Teams、Planner との統合|すべて|Outlook、Planner (Teams タスク アプリで利用できる Teams)|
|Wunderlist 移行|wunderlist ユーザーが Web 上の To Do にデータを移行するを許可する|はい|いいえ|
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