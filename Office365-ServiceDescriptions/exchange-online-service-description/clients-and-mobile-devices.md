---
title: クライアントとモバイル デバイス
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Onlineは、デスクトップおよびモバイル バージョンの Outlook、および web Outlookで動作します。
ms.openlocfilehash: 3aa0c2bbdf9b55b6a3544919143fd9d5e5cfed24
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653119"
---
# <a name="clients-and-mobile-devices"></a>クライアントとモバイル デバイス

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表、連絡先、タスク、および以下の主な機能をサポートする電子メール プログラムです。
  
- **MAPI over HTTP** - HTTP を使用したメッセージング アプリケーション プログラム インターフェイス (MAPI) を使用すると、Outlook ユーザーは組織のファイアウォールの外部からインターネット上の Exchange Online メールボックスに接続できます。 MAPI over HTTP は、Outlook Anywhere の長期的な置き換えとしてサポートされています。 この接続方法は、接続回復力の向上、より安全なサインイン、拡張性、および IT とサポートの拡張機能を提供します。 詳細については、「 [Office 365 における RPC over HTTP のサポート終了 (2017 年 10 月 31 日) に関する情報](/exchange/troubleshoot/administration/rpc-over-http-end-of-support)」および「[MAPI over HTTP](/exchange/mapi-over-http-exchange-2013-help)」を参照してください。

- **自動検出**- 自動検出サービス機能は、自動検出サービスOutlookを自動的に構成Exchange Online。 Outlook ユーザーは、電子メール アドレスとパスワードを使って初めて Exchange Online にサインインしたときに、必要なプロファイル設定を受信します。 これらの設定は、ユーザーのプロファイルの作成と管理に必要な情報で Outlook クライアントを自動的に更新します。 自動検出サービスを使用するには SSL 証明書が必要です。 この SSL 証明書は、単一のプライマリ SSL ドメインに限定されます。 

- **キャッシュ** Exchange モード - キャッシュされた Exchange モード機能を使用すると、Outlook ユーザーがインターネットに接続されていないときに、Exchange Online メールボックスのローカル コピーにアクセスできます。 キャッシュ Exchange モードは、ユーザーの Exchange メールボックスのクライアント側のコピーを Outlook に保持し、このコピーを電子メール サーバーと自動的に同期します。 クライアントとサーバー間のネットワーク状態が理想的ではない場合でも、オフライン アクセスを提供し、応答性の高いユーザー エクスペリエンスを提供するのに役立つため、キャッシュ Exchange モードで Outlook を使用することをお勧めします。 

既定では、すべてのユーザーが Outlook からアクセスできます。管理者は Windows PowerShell を使って特定のユーザーまたはグループのアクセスを無効にできます。Exchange Online へのアクセスには、最新の Service Pack をインストールした最新バージョンの Outlook を使用してください。 
  
2016 および Outlook 2016 および Exchange でサポートされているクライアントのExchange Onlineについては、「System [Requirements for Office」を参照してください](https://products.office.com/office-system-requirements)。 

Microsoft 365は、最新のブラウザーとバージョンのブラウザーで動作するように設計Office。 以前のブラウザーとバージョンのブラウザーを使用している場合Officeメインストリーム サポートに含めなかった場合は、次のコマンドを実行します。

- Microsoft は意図的にサービスへの接続を妨げるのではなく、時間の流れによってエクスペリエンスの品質が低下する可能性があります。
- Microsoft は、セキュリティ以外の問題を解決するためのソフトウェア更新プログラムを提供しない。

> [!IMPORTANT]
> Outlook は、Exchange Online サブスクリプションの価格には含まれません。 Microsoft 365 Apps for enterprise (Microsoft Outlook を含む) は一部のプランに含まれており、個別のサブスクリプションとして購入できます。 POP を使用して Exchange Online の電子メール アカウントに接続する場合、次の制限事項が表示されます。
> - 予定表情報がない
>- 空き時間情報がない
>- グローバル アドレス一覧がない
>- プッシュ メールがない
>- POP 経由で接続した場合、すべてのメッセージはクライアントにダウンロードされ、複数のコンピューターまたはデバイス間 (ノート PC と携帯電話の間など) で同期されることはありません。 
  
## <a name="outlook-on-the-web"></a>Web 上の Outlook

Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。 これにより、ユーザーはインターネットに接続する場所から Web ブラウザーを介して電子メール、予定表、連絡先にアクセスできます。 サポートされているブラウザーについては、「[Office のシステム要件](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)」を参照してください。
  
Outlook on the web のクライアントには 2 つのバージョンがあり、どちらも Exchange Online とともに利用できます。
  
- **Outlook -** web 上の Outlook の標準バージョンは、Exchange Online ユーザーに、Outlook ユーザーのメッセージング エクスペリエンスを提供します。 これは、ほとんどの新しい Web ブラウザーをサポートし、タブレットやスマートフォン、デスクトップ、ラップトップでの使用に最適化されています。 ユーザーは、メッセージの読み取りおよび送信、連絡先の整理、予定と会議のスケジュールを設定できます。 既定のアクティビティ ベースのタイム アウトは 6 時間に設定されますが、管理者は 5 分[から](/powershell/module/exchange/set-organizationconfig)8 時間Windows PowerShellで構成できます。 このタイム アウトは、ボタンの選択やメッセージの選択など、Web アプリ内でのユーザー操作によって異なります。 セキュリティ駆動型の個別のタイム アウトも用意されています。これは構成可能ではなく、ユーザーのアクティビティに関係なく発生します。 ユーザーが 8 時間ログインしている場合、OWA は自動的にユーザーをログアウトし、再認証を要求します。 

- **web 上の** Outlook のライト バージョン - web 上の Outlook のライト バージョンは、Exchange Online ユーザーがほとんどすべての Web ブラウザーを使用してメールボックスにアクセスできます。 ユーザーは、メッセージの読み取りおよび送信、連絡先の整理、予定と会議のスケジュールを設定できます。 既定のアクティビティ ベースのタイム アウトは 6 時間に設定されますが、管理者は 5 分[から](/powershell/module/exchange/set-organizationconfig)8 時間Windows PowerShellで構成できます。 このタイム アウトは、ボタンの選択やメッセージの選択など、Web アプリ内でのユーザー操作によって異なります。 セキュリティ駆動型の個別のタイム アウトも用意されています。これは構成可能ではなく、ユーザーのアクティビティに関係なく発生します。 ユーザーが 8 時間ログインしている場合、ライト バージョンの OWA は自動的にユーザーをログアウトし、再認証を求めるメッセージを表示します。 

Outlook on the web は、モバイル バージョンでも利用可能です。詳細については、「[このページ](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)」をご覧ください。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online は Microsoft Outlook for Mac をサポートしています。Microsoft Outlook for Mac では電子メール、予定表、アドレス帳、タスク リスト、ノートの一覧を使用できます。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook for iOS、Android、および Windows Phone

Exchange Online は、iOS、Android、および Windows Phone で使用可能な Outlook アプリで動作します。これらのデバイスのいずれかで、アプリ ストアを使用して Outlook アプリを検索します。モバイル OS での概要を次に示します。<br><br>
  
| デバイス | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook モバイル アプリ利用の可否  <br/> |可  <br/> [Outlook for Android の入手](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |可  <br/> [Outlook for iOS の入手](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |組み込み  <br/> |
|Exchange Online と互換性のある組み込みの電子メール アプリ  <br/> |Gmail アプリ/Samsung 電子メール アプリ  <br/> |iOS メール アプリ  <br/> |Outlook メール、予定表、連絡先  <br/> |
|詳細情報  <br/> |[Android モバイルのセットアップ](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone または iPad のセットアップ](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone のセットアップ](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

また、Blackberry などのデバイスで Exchange Online を使用するためのオプションもあります。
  
### <a name="feature-availability"></a>機能の可用性

Outlookユーザーは、最新のモバイル アプリに期待される、迅速で直感的なメールと予定表のエクスペリエンスを提供し、最高の機能のサポートを提供する唯一のアプリです。 これは、Microsoft の完全なエクスペリエンスをサポートするように特別に設計された唯一の電子メール アプリで、デスクトップからモバイルまで一貫したエクスペリエンスをユーザーに提供します。 Outlook は Intune、エンタープライズ モビリティとセキュリティ、および Exchange コントロールと統合され、データとユーザーの安全を確保します。
  
このOutlook、ユーザーは次の機能を使用できます。
  
- 全日をモバイル デバイスから管理できます。

- 仕事と個人情報を分離して安全に保ちながら、生産性を高めるために必要なアプリやサービスに接続します。

Outlook for iOS、Outlook for Android、または Outlook for Windows Phone を使用すると、次のことが可能になります。 
  
- 優先受信トレイから優先的に重要なメールを受信するメリットを得る

- 一意の電子メールの習慣に合わせてスワイプのジェスチャーをカスタマイズする

- 予定表に直接追加できる旅行日程を作成する (一目で確認できる重要な情報を付加できる)

- 受信トレイから会議の出欠確認を行う

- 電子メールと予定表の予定に、情報の迅速な処理に役立つ直感的なアイコンを使用する

- すべてのデバイスで一貫性のある使い慣れた Outlook エクスペリエンスを使用する

- 簡単に予定表から Skype 会議を起動して参加する

- IRM の暗号化され保護された電子メールを読み、返信する

- OneDrive for Business に保存されているファイルを共有する

- タップで自動応答を設定する

- 共有された予定表や委任された予定表を表示および管理する

- 数回のタップで会社のグローバル アドレス一覧を検索する

- 他のユーザーの空き時間情報を表示して、全員が参加できる会議時間をスケジュールする

- 招待状の承諾、仮承諾、辞退のステータスを参照する

- 電話から予定表を直接共有する

- 予定表から直接 Skype 会議を起動し、参加する

- 1 か所で仕事と個人の予定表にアクセスする (アプリの切り替え不要)
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online は、モバイル デバイスと Exchange Online の間でメールボックス データを同期する Microsoft Exchange ActiveSync プロトコルをサポートしているため、電子メール、予定表、連絡先、タスクに外出先からアクセスできます。
  
Microsoft の Windows Phone、Apple の iPhone および iPad、Android の携帯電話およびタブレットなど、さまざまなモバイル デバイスが Exchange ActiveSync に対応しています。携帯電話やモバイル デバイスだけでなく、Windows Phone の電子メール アプリケーションも Exchange Online への接続に Exchange ActiveSync を使用しています。最新の Exchange ActiveSync ライセンシーの完全な一覧は、Exchange ActiveSync ライセンス サイトで提供しています。
  
Exchange ActiveSync の詳細については、「[Exchange Online のクライアントとモバイル](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)」を参照してください。
  
> [!IMPORTANT]
> 各メールボックスの Exchange ActiveSync デバイスの最大数は 100 です。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Exchange Web サービス (EWS) で開発されたアプリケーション

 管理者は、Exchange Web サービス (EWS) または EWS Managed API を使用して開発されたアプリケーションを利用することで、社内で、Azure 内で、または他のホステッド サービス内で実行しているアプリケーションから Exchange Online で保存されたデータにアクセスできます。 
  
Exchange Web サービスで開発されたアプリケーションの詳細については、「[Exchange の Web サービス](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)」をご覧ください。
  
## <a name="pop-and-imap"></a>POP と IMAP

Exchange Online は、POP3 および IMAP4 プロトコルによるメールボックスへのアクセスをサポートします。POP および IMAP でのアクセスには、SSL による暗号化が必要です。既定では、POP がすべてのユーザーに対して有効になっています。POP および IMAP の接続設定は Outlook on the web で確認できます。管理者はユーザーごとに POP および IMAP によるアクセスを無効にできます。
  
POP3 および IMAP4 接続の詳細については、「[Exchange Server 2013 での POP3 と IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)」を参照してください。
  
## <a name="smtp"></a>SMTP

簡易メール転送プロトコル (SMTP) は、IMAP または POP で Exchange Online に接続しているクライアントからのメール送信に使用されます。SMTP は、Exchange サーバーを経由したルーティングおよび配信を行うためのプライマリ プロトコルです。Exchange Online は、SMTP によるメール送信を必要とするお客様社内の承認済みアプリケーションに対して、2 種類の SMTP リレー サービスをサポートしています。
  
- 管理環境内のユーザーに対する SMTP メッセージの送信。

- 管理環境外のアドレスに対する認証済み SMTP メッセージ リレー。

> [!IMPORTANT]
> SMTP リレーを行うには、承認済み送信元サーバーの IP アドレスが必要です。SMTP で電子メールを送信するには、トランスポート層セキュリティ (TLS) による暗号化と認証が必要です。 
  
## <a name="blackberry-devices"></a>BlackBerry デバイス

電子メールは、BlackBerry デバイス &reg; 上で、Exchange ActiveSync。 オプションの詳細については、次のトピックを参照してください。
  
- [BlackBerry で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863394)

- [BlackBerry デバイス 7.1 OS 以前で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863403)

詳細については、「[BlackBerry](../office-365-platform-service-description/blackberry.md)」を参照してください。
  
> [!NOTE]
> 中国の 21Vianet が運用している Office 365 を使用している場合は、BlackBerry Business Cloud Services が使用できません。ただし、Exchange ActiveSync デバイスまたは Research in Motion (RIM: BlackBerry ワイヤレス電子メール ソリューション) からの製品を使用して、Blackberry Enterprise Server (BES) を実行することはできます。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online[参照してください](exchange-online-service-description.md)。
