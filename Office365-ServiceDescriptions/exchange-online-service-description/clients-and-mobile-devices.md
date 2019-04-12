---
title: クライアントとモバイル デバイス
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: b5755b76445ddc186d02e5b8a499d905636bd311
ms.sourcegitcommit: 7248888900104d79c5f53cafb1000140eefac7eb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/12/2019
ms.locfileid: "31825205"
---
# <a name="clients-and-mobile-devices"></a>クライアントとモバイル デバイス

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表、連絡先、タスク、および以下の主な機能をサポートする電子メール プログラムです。
  
- **MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP を使用すると、組織のファイアウォールの外からインターネット経由で Exchange Online のメールボックスに接続できます。MAPI over HTTP は、Outlook Anywhere の長期的な置き換えとしてサポートされています。この接続方法は、接続回復力の向上、より安全なサインイン、拡張性、および IT とサポートの拡張機能を提供します。詳細については、「 [Office 365 における RPC over HTTP のサポート終了 (2017 年 10 月 31 日) に関する情報](https://go.microsoft.com/fwlink/?linkid=863890)」および「[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)」を参照してください。
    
- **自動検出** 自動検出サービスは、Exchange Online と連携するように Outlook を自動的に構成します。Outlook ユーザーは、電子メール アドレスとパスワードを使って初めて Exchange Online にサインインしたときに、必要なプロファイル設定を受信します。これらの設定は、ユーザーのプロファイルの作成と管理に必要な情報で Outlook クライアントを自動的に更新します。自動検出サービスを使用するには SSL 証明書が必要です。この SSL 証明書は、単一のプライマリ SSL ドメインに限定されます。 
    
- **Exchange キャッシュ モード** Exchange キャッシュ モードを使うと、インターネットに接続していないときに、Outlook から Exchange Online メールボックスのローカル コピーにアクセスできます。Exchange キャッシュ モードは、ユーザーの Exchange メールボックスのクライアント側のコピーを Outlook 内に保持し、コピーと電子メール サーバーを自動的に同期します。Outlook は Exchange キャッシュ モードで使用してください。オフライン アクセスが可能になり、クライアントとサーバー間のネットワーク状態が理想的でない場合にもユーザーの操作に素早く反応するからです。 
    
既定では、すべてのユーザーが Outlook からアクセスできます。管理者は Windows PowerShell を使って特定のユーザーまたはグループのアクセスを無効にできます。Exchange Online へのアクセスには、最新の Service Pack をインストールした最新バージョンの Outlook を使用してください。 
  
Exchange 2016 と Exchange Online でサポートされている Outlook クライアントの詳細については、「[Exchange 2016 のシステム要件](https://go.microsoft.com/fwlink/?LinkID=828972)」の「サポートされるクライアント」を参照してください。
  
> [!IMPORTANT]
>  Outlook は、Exchange Online サブスクリプションの価格には含まれません。Microsoft Office Pro Plus (Microsoft Outlook を含みます) は、一部の Office 365 プランに含まれている他、個別のサブスクリプションとしても購入できます。 >  POP を使用して Exchange Online の電子メール アカウントに接続する場合、次の制限事項が表示されます。 >  予定表情報がない >  空き時間情報がない >  グローバル アドレス一覧がない >  プッシュ メールがない >  POP 経由で接続した場合、すべてのメッセージはクライアントにダウンロードされ、複数のコンピューターまたはデバイス間 (ノート PC と携帯電話の間など) で同期されることはありません。 
  
## <a name="outlook-on-the-web"></a>Outlook on the web

Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。インターネットに接続していれば、どこからでも電子メール、予定表、連絡先に Web ブラウザーでアクセスできます。サポートされているブラウザーについては、「[Office のシステム要件](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)」を参照してください。
  
Outlook on the web のクライアントには 2 つのバージョンがあり、どちらも Exchange Online とともに利用できます。
  
- **Outlook on the web** Outlook on the web の標準バージョンでは、Exchange Online ユーザーに、Outlook ユーザーに一番近いメッセージング エクスペリエンスを提供します。ほとんどの新しいブラウザーをサポートしており、タブレットやスマートフォンだけでなく、デスクトップやノート PC での利用にも最適化されています。メッセージの送受信、連絡先の整理、予定と会議のスケジュールを実行できます。アクティビティ ベースのタイムアウトの既定値は 6 時間ですが、5 分から 8 時間までの範囲で [管理者が Windows PowerShell で構成できます](https://go.microsoft.com/fwlink/p/?LinkId=399155)。このタイムアウトは、ボタンのクリックやメッセージの選択など、Web アプリ内でのユーザーの操作に依存します。さらに、別個のセキュリティに基づくタイムアウトがあります。これは構成はできず、ユーザー アクティビティとは関係なく発生します。ユーザーのログインから 8 時間が経過すると、OWA が自動的にユーザーをログアウトし、再認証を要求します。 
    
- **Outlook on the web の Light バージョン** Outlook on the web の Light バージョンによって、Exchange Online ユーザーはほぼすべての Web ブラウザーからメールボックスにアクセスできます。メッセージの送受信、連絡先の整理、予定と会議のスケジュールを実行できます。アクティビティ ベースのタイムアウトの既定値は 6 時間ですが、5 分から 8 時間までの範囲で [管理者が Windows PowerShell で構成できます](https://go.microsoft.com/fwlink/p/?LinkId=399155)。このタイムアウトは、ボタンのクリックやメッセージの選択など、Web アプリ内でのユーザーの操作に依存します。さらに、別個のセキュリティに基づくタイムアウトがあります。これは構成はできず、ユーザー アクティビティとは関係なく発生します。ユーザーのログインから 8 時間が経過すると、OWA の Light バージョンは自動的にユーザーをログアウトし、再認証を要求します。 
    
Outlook on the web は、モバイル バージョンでも利用可能です。詳細については、「[このページ](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)」をご覧ください。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online は Microsoft Outlook for Mac をサポートしています。Microsoft Outlook for Mac では電子メール、予定表、アドレス帳、タスク リスト、ノートの一覧を使用できます。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook for iOS、Android、および Windows Phone

Exchange Online は、iOS、Android、および Windows Phone で使用可能な Outlook アプリで動作します。これらのデバイスのいずれかで、アプリ ストアを使用して Outlook アプリを検索します。モバイル OS での概要を次に示します。
  
|||||
|:-----|:-----|:-----|:-----|
|デバイス  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook モバイル アプリ利用の可否  <br/> |はい  <br/> [Outlook for Android の入手](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |可  <br/> [Outlook for iOS の入手](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |組み込み  <br/> |
|Exchange Online と互換性のある組み込みの電子メール アプリ  <br/> |Gmail アプリ/Samsung 電子メール アプリ  <br/> |iOS メール アプリ  <br/> |Outlook メール、予定表、連絡先  <br/> |
|詳細情報  <br/> |[Android モバイルのセットアップ](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone または iPad のセットアップ](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone のセットアップ](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
また、Blackberry などのデバイスで Exchange Online を使用するためのオプションもあります。
  
### <a name="feature-availability"></a>機能の可用性

Outlook は、ユーザーが最新のモバイル アプリに期待する高速で直感的な電子メールと予定表のエクスペリエンスを提供し、Office 365 の最高の機能をサポートする唯一のアプリです。これは、特に完全な Office 365 エクスペリエンスをサポートするように設計された唯一の電子メール アプリであり、ユーザーにデスクトップからモバイルまでの一貫したエクスペリエンスを提供します。Outlook は Intune、エンタープライズ モビリティとセキュリティ、および Exchange コントロールと統合され、データとユーザーの安全を確保します。
  
Outlook を使用すると、次のことが可能になります。
  
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
  
Exchange ActiveSync の詳細については、「[Exchange Online のクライアントとモバイル](https://go.microsoft.com/fwlink/p/?LinkId=271792)」を参照してください。
  
> [!IMPORTANT]
> 各メールボックスの Exchange ActiveSync デバイスの最大数は 100 です。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Exchange Web サービス (EWS) で開発されたアプリケーション

 管理者は、Exchange Web サービス (EWS) または EWS Managed API を使用して開発されたアプリケーションを利用することで、社内で、Azure 内で、または他のホステッド サービス内で実行しているアプリケーションから Exchange Online で保存されたデータにアクセスできます。 
  
Exchange Web サービスで開発されたアプリケーションの詳細については、「[Exchange の Web サービス](https://go.microsoft.com/fwlink/?LinkId=325346)」をご覧ください。
  
## <a name="pop-and-imap"></a>POP と IMAP

Exchange Online は、POP3 および IMAP4 プロトコルによるメールボックスへのアクセスをサポートします。POP および IMAP でのアクセスには、SSL による暗号化が必要です。既定では、POP がすべてのユーザーに対して有効になっています。POP および IMAP の接続設定は Outlook on the web で確認できます。管理者はユーザーごとに POP および IMAP によるアクセスを無効にできます。
  
POP3 および IMAP4 接続の詳細については、「[Exchange Server 2013 での POP3 と IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)」を参照してください。
  
## <a name="smtp"></a>SMTP

簡易メール転送プロトコル (SMTP) は、IMAP または POP で Exchange Online に接続しているクライアントからのメール送信に使用されます。SMTP は、Exchange サーバーを経由したルーティングおよび配信を行うためのプライマリ プロトコルです。Exchange Online は、SMTP によるメール送信を必要とするお客様社内の承認済みアプリケーションに対して、2 種類の SMTP リレー サービスをサポートしています。
  
- 管理環境内のユーザーに対する SMTP メッセージの送信。
    
- 管理環境外のアドレスに対する認証済み SMTP メッセージ リレー。
    
> [!IMPORTANT]
> SMTP リレーを行うには、承認済み送信元サーバーの IP アドレスが必要です。SMTP で電子メールを送信するには、トランスポート層セキュリティ (TLS) による暗号化と認証が必要です。 
  
## <a name="blackberry-devices"></a>BlackBerry® デバイス

Office 365 の電子メールは BlackBerry® デバイスで利用できます (Exchange ActiveSync 経由)。オプションの詳細については、次のトピックを参照してください。
  
- [BlackBerry で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [BlackBerry デバイス 7.1 OS 以前で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863403)
    
詳細については、「[BlackBerry](../office-365-platform-service-description/blackberry.md)」を参照してください。
  
> [!NOTE]
> 中国の 21Vianet が運用している Office 365 を使用している場合は、BlackBerry Business Cloud Services が使用できません。ただし、Exchange ActiveSync デバイスまたは Research in Motion (RIM: BlackBerry ワイヤレス電子メール ソリューション) からの製品を使用して、Blackberry Enterprise Server (BES) を実行することはできます。 
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

