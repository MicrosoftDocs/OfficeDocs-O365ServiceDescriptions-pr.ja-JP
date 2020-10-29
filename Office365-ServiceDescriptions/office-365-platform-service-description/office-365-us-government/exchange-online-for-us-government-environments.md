---
title: 米国政府機関向けの Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、「Exchange Online サービスの説明」に記載されている米国政府機関クラウドと商用クラウドの機能の違いの概要について説明します。
ms.openlocfilehash: 2277f7d74cb893dd172bc13efcbd01d964b81736
ms.sourcegitcommit: 9794350861e41d80980ecf6b9000a730b5564988
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2020
ms.locfileid: "48793654"
---
# <a name="exchange-online-for-us-government-environments"></a>米国政府機関向けの Exchange Online

この記事では、「 [Exchange Online サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description)」に記載されている米国政府機関クラウドと商用クラウドの機能の違いの概要について説明します。 Exchange Online は、Government Community Cloud (GCC)、GCC High、および国防総省 (DoD) 環境で利用できます。

資格および購入を含む、政府機関のクラウドの詳細については、「 [Microsoft 365 government-購入方法](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)」を参照してください。 Office 365 Government プランを比較するには、「 [office 365 government プラン](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)」を参照してください。

ネットワーク接続を管理するときに必要なエンドポイントの詳細については、「 [office 365 米国政府用 GCC、高エンドポイント](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) または [Office 365 米国政府の DoD エンドポイント](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)」を参照してください。

Office 365 の機能を楽しんだだけでなく、米国政府機関のクラウド環境特有の次の機能を活用することができます。

- 組織の顧客コンテンツは、商用の Office 365 サービスの顧客コンテンツと論理的に分離されています。

- 組織の顧客コンテンツは、米国内の rest に保存されます。

- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。

- 政府機関のクラウド環境は、多くの場合、公的機関のお客様に必要とされる証明書と認定に準拠しています。

すべての Exchange 商用機能を政府機関のクラウド環境に提供することが一般的な目的です。 これは、政府機関のお客様の要件により、一部の機能は利用できません。 その他の機能は政府機関の環境に送られますが、まだ利用できません。 政府機関のクラウド環境で利用できる機能については、以下のセクションを参照してください。

## <a name="exchange-online-features"></a>Exchange Online の機能

次の表は、指定された Exchange Online 機能が GCC、GCC High、および DoD 環境で使用できるかどうかを示しています。 サポートのステートメントに関してニュアンスがある場合 (またはその欠如) は、追加のコンテキストが提供されます。<br><br>

| 機能 | GCC | GCC High | DoD | 重要な考慮事項 |
|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|サポートされているハイブリッド展開|はい|はい|必要|オンプレミスの Exchange Server との共存の場合、Microsoft は少なくとも1つの Exchange Server 2013 クライアントアクセスサーバー (または Exchange Server 2016) をインストールする必要があります。 Exchange Server 2010 以前はサポートされていません。|
|サポートされている IMAP 移行|はい|はい|必要||
|カット オーバー移行のサポート|はい|はい|必要||
|サポートされている段階的な移行|はい|はい|必要|GSuite 移行は、GCC High および DoD ではサポートされていません。 詳細については、「 <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">suite 移行を実行する</a>」を参照してください。|
|**[アクセス許可](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|役割に基づくアクセス許可|はい|はい|必要||
|役割グループ|はい|はい|必要||
|役割の割り当てポリシー|はい|はい|必要||
|**[メッセージ ポリシーとコンプライアンス](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|Exchange Online ベースのメールボックスのアーカイブ|はい|はい|必要||
|社内メールボックスのクラウドベースのアーカイブ|はい|はい|必要||
|Messaging Records Management(MRM) |はい|はい|必要||
|手動のアイテム保持ポリシー、ラベル、タグ |はい|はい|必要||
|保存中のデータの暗号化 (BitLocker)|はい|はい|必要||
|Azure Information Protection を使用した IRM|はい|はい|必要|GCC High および DoD での AIP の制限に関する詳細については、「 <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government サービスの説明</a>」を参照してください。<br><br>Azure Information Protection は、G1/F3 には含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights Management (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、office 365 ProPlus へのサブスクリプションが必要です。これは、Office 365 Government G1 または Office 365 Government F3 には含まれていません。|
|Windows Server AD RMS を使用した IRM|はい|はい|必要| Windows Server AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。|
|Office 365 Message Encryption|はい|はい|必要|この記事の「office [365 Message encryption behavior IN Gcc high/dod](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) 」および「 <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">365 office 2010 メッセージ暗号化の特徴</a>」を参照してください。 gcc 高展開では、gcc high/dod および非 gcc 高/dod ユーザーの間でメッセージを送信する場合の office 365 メッセージ暗号化の微妙な違いが文書化されています。|
|顧客キー|はい|はい|必要|G5 サービスプランが必要です。|
|S/MIME|はい|はい|必要||
|インプレース保持と訴訟ホールド|はい|はい|必要|G3 または G5 サービスプランが必要です。|
|インプレース電子情報開示 (eDiscovery)|はい|はい|必要||
|メール フロー ルール|はい|はい|必要||
|Data loss prevention|はい|はい|必要|G3 または G5 サービスプランが必要です。|
|ジャーナル|はい|はい|必要||
|**[スパム対策とマルウェア対策の保護](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|組み込みのスパム対策保護|はい|はい|必要||
|Customize anti-spam policies|はい|はい|必要||
|組み込みのマルウェア対策保護|はい|はい|必要||
|Customize anti-malware policies|はい|はい|必要||
|検疫 - 管理者による管理|はい|はい|必要||
|検疫 - エンドユーザーによる自己管理|はい|はい|必要||
|Advanced Threat Protection|はい|はい|必要|G5 Service プラン (またはアドオンの購入) が必要です。<br><br>ユーザーおよびドメインの偽装およびスプーフィングインテリジェンスのフィッシング対策は、GCC High および DoD ではまだ利用できません。|
|**[メール フロー](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|送信メールのカスタムルーティング|はい|はい|必要||
|Secure messaging with a trusted partner|はい|はい|必要||
|Conditional mail routing|はい|はい|必要||
|着信セーフリストへのパートナーの追加|はい|はい|必要||
|ハイブリッド電子メールルーティング|はい|はい|必要||
|**[受信者](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|容量のアラート|はい|はい|必要||
|クラッター機能|はい|はい|必要||
|メール ヒント|はい|はい|必要||
|代理人アクセス|はい|はい|必要||
|受信トレイのルール|はい|はい|必要||
|接続されているアカウント|必要|いいえ|いいえ|この機能は、サードパーティのサービスへの送信接続に関する制限のため、GCC High または DoD ではサポートされていません。 影響を受ける機能の詳細については、この記事の「 [サードパーティ製サービスとの接続](#connectivity-with-third-party-services) 」を参照してください。|
|非アクティブなメールボックス|はい|はい|必要|G3 または G5 サービスプランが必要です。|
|オフライン アドレス帳|はい|はい|必要||
|アドレス帳ポリシー|はい|はい|必要||
|階層型アドレス帳|はい|はい|必要||
|アドレス一覧とグローバルアドレス一覧|はい|はい|必要||
|Office 365 グループ|はい|はい|必要|Office 365 グループへのゲストアクセスは、GCC High および DoD 環境ではサポートされていません。 詳細については、「 <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>」を参照してください。|
|配布グループ|はい|はい|必要||
|外部連絡先 （グローバル）|はい|はい|必要|GCC High および DoD 環境での組織の関係のコラボレーションの制限に従います。 |
|ソーシャルネットワークを使用した連絡先リンク|必要|いいえ|いいえ|この機能は、GCC High または DoD ではサポートされていません。|
|リソース メールボックス|はい|はい|必要||
|会議室の管理|はい|はい|必要||
|不在時の返信|はい|はい|必要||
|インターネット予定表の共有|必要|いいえ|いいえ|GCC High では、インターネット予定表の公開と共有は、GCC のユーザーが共有している予定表への受信接続に対しては機能しますが、gcc 高のユーザーは GCC の外部の共有の予定表への送信に接続します。<br><br>DoD では、インターネット予定表の共有は、その環境での受信/送信接続の許可リストの要件により、サポートされていません。|
|**[レポート機能とトラブルシューティング ツール](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|Microsoft 365 管理センターのレポート|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|Web サービスレポート|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|Message trace|はい|はい|必要||
|監査レポート|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|ユニファイド メッセージングのレポート|必要|いいえ|いいえ||
|**[共有とコラボレーション](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|フェデレーションの共有 (予定表の公開を含む)|はい|はい|必要|GCC High と DoD の両方に制限があります。 この記事の「 [空き時間情報フェデレーション](#freebusy-federation) 」を参照してください。|
|サイト メールボックス|はい|はい|必要||
|パブリック フォルダー|はい|はい|必要||
|**[クライアントとモバイル デバイス](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|Outlook for Windows|はい|はい|必要|GCC の高および米国のコンプライアンス要件を満たすには、少なくともバージョン1803の Office 365 ProPlus を実行している必要があります。 Office 365 ProPlus は、G1 または F3 に含まれていません。|
|Outlook on the web|はい|はい|必要||
|Outlook for Mac|はい|はい|必要|GCC の高および米国のコンプライアンス要件を満たすには、少なくともバージョン1803の Office 365 ProPlus を実行している必要があります。 Office 365 ProPlus は、G1 または F3 に含まれていません。|
|iOS および Android 用の Outlook|はい|はい|必要||
|Exchange ActiveSync|はい|はい|必要||
|Microsoft 365 の基本的なモビリティとセキュリティ|必要|いいえ|いいえ||
|POP と IMAP|はい|はい|必要||
|SMTP|はい|はい|必要||
|EWS アプリケーションのサポート|はい|はい|必要||
|**[音声メッセージ サービス](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|ボイス メール|いいえ|いいえ|いいえ|Exchange Online ユニファイドメッセージングでのオンプレミスの ip-pbx システムの統合はサポートされていません。|
|ボイスメールとサードパーティ製 FAX 間の統合|いいえ|いいえ|いいえ|Exchange Online ユニファイドメッセージングでのオンプレミスの ip-pbx システムの統合はサポートされていません。|
|サードパーティ ボイス メールの相互運用性|いいえ|いいえ|いいえ|Exchange Online ユニファイドメッセージングでのオンプレミスの ip-pbx システムの統合はサポートされていません。|
|Skype for Business の統合|はい|はい|必要||
|**[高可用性とビジネス継続性](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|データセンターでのメールボックスレプリケーション|はい|はい|必要||
|削除済みメールボックスの回復|はい|はい|必要||
|削除済みアイテムの回復|はい|はい|必要||
|単一アイテムの回復|はい|はい|必要||
|**[相互運用性、接続、および互換性](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|OWA および Outlook でのプレゼンス|はい|はい|必要||
|SharePoint の相互運用性|はい|はい|必要||
|EWS 接続のサポート|はい|はい|必要||
|SMTP リレーのサポート|はい|はい|必要||
|**[Exchange Online のセットアップと管理](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|Microsoft Office 365 ポータルへのアクセス|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|Microsoft 365 管理センターへのアクセス|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|Exchange 管理センターへのアクセス|はい|はい|必要||
|リモート Windows PowerShell へのアクセス|はい|はい|必要||
|モバイルデバイスの ActiveSync ポリシー|はい|はい|必要||
|利用状況レポート|はい|必要|いいえ|レポートは DoD では利用できません。 更新プログラム/現在の可用性については、「Office 365 US Government サービスの説明」の「 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">プラットフォーム機能</a> 」セクションを参照してください。|
|**[サービスのカスタマイズ、アドイン、およびリソースの拡張](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**重要な考慮事項**|
|Outlook アドインと Outlook MAPI|はい|はい|必要|一部の OWA および Outlook アドインは、GCC High および DoD で利用できます。 この記事の「 [outlook および Outlook Web App で](#add-insin-outlook-and-outlook-web-app) のアドイン」を参照してください。|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC High および DoD 環境内の微妙なニュアンス

### <a name="connectivity-with-third-party-services"></a>サードパーティ製のサービスとの接続  

GCC High および DoD 環境の両方とも、送信接続の明示的な承認と構成を必要とする制限された環境です。 また、Microsoft は、これらの環境からコマーシャルクラウドサービス (市販の Office 365、Google GSuite、Amazon Web サービスなど) への送信アクセスを許可する要求を満たすことはできません。     

これらの制限により、次のような場合には、GCC High/DoD 環境からのこの送信接続に依存する機能はサポートされません。 

- 接続されたアカウント-ユーザーは、アカウント (Google、POP、IMAP など) を追加または同期できません。 

- サードパーティ製のファイルストレージプロバイダーのサポート- *GCC High/DoD 内* のユーザーの OneDrive for Business アカウントのみが、さまざまな Outlook クライアントからアクセスできます。ファイルの添付/共有を目的としています。 サードパーティ製のストレージアカウント (Dropbox、ボックス、Google Drive) を追加することはできません。 

- Facebook や LinkedIn などのソーシャルネットワークとの接続。 

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B コラボレーション 

Azure Active Directory B2B コラボレーションは現在、Azure US Government クラウドに含まれる組織間でのみサポートされており、両方が B2B コラボレーションをサポートしています。

さらに、Office 365 グループのゲストとしての B2B ユーザーは、GCC High および DoD 環境ではサポートされていません。 

詳細および最新の更新プログラムについては、「 [Azure Government Security + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity)」を参照してください。 

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 GCC High/DoD 境界にまたがる、メッセージの暗号化の動作 

GCC の高環境で Office 365 メッセージの暗号化を使用する場合は、受信者の動作に関する次のような固有の特徴に注意してください。  

- GCC High または DoD から同じ環境内の受信者に暗号化された電子メールを送信する場合:
    
    - 送信者は、Outlook for PC および Mac および web 上の Outlook でメールを手動で暗号化できます。また、Exchange メールフロールールを使用して電子メールを暗号化するポリシーを設定することもできます。 
    
    - GCC High/DoD の内側の受信者は、PC と Mac 用の Outlook と web 上の Outlook の同じインライン読み取り操作を、他のすべての Office 365 ユーザーとして受け取ります。 

<!-- end list -->

- GCC High または DoD からその環境外の受信者に暗号化された電子メールを送信する場合 (GCC と商用を含む):
    
    - GCC High/DoD 内部の送信者は、暗号化された電子メールを GCC High/DoD 境界の外側に送信できます。 
    
    - 市販の Office 365 ユーザー、Outlook.com ユーザー、その他の電子メールプロバイダーのその他のユーザーなど、GCC High/DoD の外部のすべての受信者は、ラッパーメールを受信します。 このラッパーメールは、受信者がメッセージに対して読み取りおよび返信できる OME ポータルにリダイレクトします。 

詳細および最新の更新プログラムについては、「 [OME のバージョンの比較](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison)」を参照してください。

### <a name="freebusy-federation"></a>空き時間情報フェデレーション

現在、空き時間情報を含むフェデレーション共有には、GCC High および DoD 環境におけるいくつかの重要な制限が適用されています。

GCC の高環境では、次のようになります。

- フェデレーションの信頼 (双方向空き時間情報共有を含む) は、複数のテナント間で、ハイブリッド共存 (Exchange 2013 以降) を介してサポートされます。

- GCC High および GCC または Office 365 コマーシャルでは、フェデレーション共有はサポートされていません。 現時点では、GCC の高環境からコマーシャルクラウド (GCC および Office 365 コマーシャルを含む) への送信接続は許可されていません。 その結果、GCC のユーザーは、共有された予定表の情報にアクセスするために、GCC/商用に必要な送信要求を行うことができません。

DoD 環境で、次のようになります。

  - 現在、フェデレーションの信頼 (空き時間情報の共有を含む) は、DoD 環境内のテナント間でのみサポートされています。 DoD テナントと GCC または商用テナント間ではサポートされていません。

### <a name="client-configuration"></a>クライアント構成 

Office ProPlus (Outlook を含む) の展開と構成には、追加の手順が含まれています。 これらの手順の詳細については、「 [Microsoft 365 app for enterprise を GCC High または DoD 環境に展開するためのガイダンス ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)」を参照してください。

IOS および Android 用の Outlook は、GCC High および DoD 環境でも使用できます。 これらの環境における機能の制限と管理の詳細については、「 [Government Community Cloud で Outlook For iOS と Outlook For Android を使用](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)する」を参照してください。

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook および Outlook Web App でのアドイン  

一部の OWA および Outlook アドインは、GCC High および DoD で利用できます。 マイテンプレートと提案された会議が利用可能で、機能する必要があります。 既定の5つの OWA アドインのみがサポートされます。 サードパーティ製のアプリケーションとの統合は可能ですが、これらの統合は、GCC High または DoD の Microsoft コンプライアンスの約束によって対象となるものではありません。 お客様は、組織のためにアドオンを構成する前に、サードパーティのデータ処理方法とコンプライアンスの約束を熟知している必要があります。
