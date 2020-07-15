---
title: クライアントとモバイル デバイス
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: a09609e81d9d179dcd156db886913d3124b2e16f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132971"
---
# <a name="clients-and-mobile-devices"></a>クライアントとモバイル デバイス

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook は、予定表、連絡先、タスク、および以下の主な機能をサポートする電子メール プログラムです。
  
- **MAPI OVER HTTP**HTTP 経由のメッセージングアプリケーションプログラムインターフェイス (MAPI) により、Outlook ユーザーは組織のファイアウォールの外側からインターネット経由で Exchange Online メールボックスに接続することができます。 MAPI over HTTP は、Outlook Anywhere の長期的な置き換えとしてサポートされています。 この接続方法は、接続回復力の向上、より安全なサインイン、拡張性、および IT とサポートの拡張機能を提供します。 詳細については、「 [Office 365 における RPC over HTTP のサポート終了 (2017 年 10 月 31 日) に関する情報](https://go.microsoft.com/fwlink/?linkid=863890)」および「[MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041)」を参照してください。

- **Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain. 

- **Exchange キャッシュモード**Exchange キャッシュモード機能を使用すると、Outlook ユーザーは、インターネットに接続されていない場合に Exchange Online メールボックスのローカルコピーにアクセスすることができます。 Exchange キャッシュモードでは、ユーザーの Exchange メールボックスのクライアント側コピーが Outlook に保持され、このコピーが電子メールサーバーと自動的に同期されます。 Exchange キャッシュモードで Outlook を使用することをお勧めします。これは、オフラインアクセスを提供し、クライアントとサーバーの間のネットワーク条件が理想的でない場合でも、応答性の高いユーザー環境を提供するために使用することをお勧めします。 

By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online. 
  
Exchange 2016 と Exchange Online でサポートされている Outlook クライアントの詳細については、「 [Office のシステム要件](https://products.office.com/office-system-requirements)」を参照してください。 

Microsoft 365 は、Office の最新のブラウザーおよびバージョンと共に動作するように設計されています。 旧バージョンのブラウザーと、メインストリームサポートされていないバージョンの Office を使用している場合:

- Microsoft は、サービスへの接続を意図的に妨げるものではありませんが、ユーザーの利便性は徐々に低下する可能性があります。
- マイクロソフトは、セキュリティに関連しない問題を解決するためのソフトウェア更新プログラムを提供していません。

> [!IMPORTANT]
>  Outlook は、Exchange Online サブスクリプションの価格には含まれません。 Microsoft 365 for enterprise (Microsoft Outlook を含む) は、一部のプランに含まれており、個別のサブスクリプションとして購入できます。 POP を使用して Exchange Online の電子メールアカウントに接続する場合は、次の制限があります。予定表情報がない > > 空き時間情報はありません > > >] POP を使用して接続すると、すべてのメッセージがクライアントにダウンロードされ、複数のコンピューターまたはデバイス (ノート pc と電話など) 間の同期はありません 
  
## <a name="outlook-on-the-web"></a>Web 上の Outlook

Outlook on the web は、Exchange Online と連携する Web ベースの Outlook 電子メール プログラムです。 これにより、ユーザーは、インターネットに接続されている場所から、web ブラウザーを使用して電子メール、予定表、連絡先にアクセスできるようになります。 サポートされているブラウザーについては、「[Office のシステム要件](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)」を参照してください。
  
Outlook on the web のクライアントには 2 つのバージョンがあり、どちらも Exchange Online とともに利用できます。
  
- **Outlook on the web**Web 上の Outlook の標準バージョンでは、Exchange Online ユーザーが Outlook ユーザーの場合とほとんど同じようなメッセージングの使用環境を備えています。 最新の web ブラウザーをサポートしており、デスクトップやラップトップだけでなく、タブレットやスマートフォンでも使用できるように最適化されています。 ユーザーは、メッセージの読み取りと送信、連絡先の整理、予定および会議のスケジュールを行うことができます。 既定の動作ベースのタイムアウトは6時間に設定されていますが、 [Windows PowerShell の管理者が](https://go.microsoft.com/fwlink/p/?LinkId=399155)5 ~ 8 時間に構成することができます。 このタイムアウトは、web アプリ内でのユーザー操作に依存します。たとえば、ボタンを選択したり、メッセージを選択したりできます。 また、個別にセキュリティで保護されたタイムアウトもあります。これは構成できず、ユーザーのアクティビティに関係なく実行されます。 ユーザーが8時間でログインしている場合、OWA は自動的にユーザーをログアウトし、再認証を要求します。 

- **Outlook on the web の light バージョン**ライトバージョンの Outlook on the web では、ほとんどすべての web ブラウザーを使用して Exchange Online ユーザーがメールボックスにアクセスできます。 ユーザーは、メッセージの読み取りと送信、連絡先の整理、予定および会議のスケジュールを行うことができます。 既定の動作ベースのタイムアウトは6時間に設定されていますが、 [Windows PowerShell の管理者が](https://go.microsoft.com/fwlink/p/?LinkId=399155)5 ~ 8 時間に構成することができます。 このタイムアウトは、web アプリ内でのユーザー操作に依存します。たとえば、ボタンを選択したり、メッセージを選択したりできます。 また、個別にセキュリティで保護されたタイムアウトもあります。これは構成できず、ユーザーのアクティビティに関係なく実行されます。 ユーザーが8時間でログインしている場合、light バージョンの OWA は自動的にユーザーをログアウトし、再認証を要求します。 

Outlook on the web は、モバイル バージョンでも利用可能です。 詳細については、「[このページ](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)」をご覧ください。
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online は Microsoft Outlook for Mac をサポートしています。Microsoft Outlook for Mac では電子メール、予定表、アドレス帳、タスク リスト、ノートの一覧を使用できます。
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook for iOS、Android、および Windows Phone

Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.
  
|||||
|:-----|:-----|:-----|:-----|
|デバイス  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook モバイル アプリ利用の可否  <br/> |はい  <br/> [Outlook for Android の入手](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |可  <br/> [Outlook for iOS の入手](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |組み込み  <br/> |
|Exchange Online と互換性のある組み込みの電子メール アプリ  <br/> |Gmail アプリ/Samsung 電子メール アプリ  <br/> |iOS メール アプリ  <br/> |Outlook メール、予定表、連絡先  <br/> |
|詳細情報  <br/> |[Android モバイルのセットアップ](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone または iPad のセットアップ](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone のセットアップ](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

また、Blackberry などのデバイスで Exchange Online を使用するためのオプションもあります。
  
### <a name="feature-availability"></a>機能の可用性

Outlook では、優れた機能のサポートを提供する唯一のアプリであるのに対して、ユーザーには、最新のモバイルアプリからの迅速で直感的な電子メールや予定表の操作性が提供されます。 これは、Microsoft のすべての環境をサポートするために特別に設計された唯一の電子メールアプリであり、ユーザーはデスクトップからモバイルへの一貫性のある環境を提供しています。 Outlook は Intune、エンタープライズ モビリティとセキュリティ、および Exchange コントロールと統合され、データとユーザーの安全を確保します。
  
Outlook では、ユーザーは次のことができます。
  
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
  
A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.
  
Exchange ActiveSync の詳細については、「[Exchange Online のクライアントとモバイル](https://go.microsoft.com/fwlink/p/?LinkId=271792)」を参照してください。
  
> [!IMPORTANT]
> 各メールボックスの Exchange ActiveSync デバイスの最大数は 100 です。 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Exchange Web サービス (EWS) で開発されたアプリケーション

 管理者は、Exchange Web サービス (EWS) または EWS Managed API を使用して開発されたアプリケーションを利用することで、社内で、Azure 内で、または他のホステッド サービス内で実行しているアプリケーションから Exchange Online で保存されたデータにアクセスできます。 
  
Exchange Web サービスで開発されたアプリケーションの詳細については、「[Exchange の Web サービス](https://go.microsoft.com/fwlink/?LinkId=325346)」をご覧ください。
  
## <a name="pop-and-imap"></a>POP と IMAP

Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.
  
POP3 および IMAP4 接続の詳細については、「[Exchange Server 2013 での POP3 と IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)」を参照してください。
  
## <a name="smtp"></a>SMTP

Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:
  
- 管理環境内のユーザーに対する SMTP メッセージの送信。

- 管理環境外のアドレスに対する認証済み SMTP メッセージ リレー。

> [!IMPORTANT]
> IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email. 
  
## <a name="blackberryreg-devices"></a>BlackBerry &reg; デバイス

電子メールは、BlackBerry &reg; デバイスの Exchange ActiveSync から入手できます。 オプションの詳細については、次のトピックを参照してください。
  
- [BlackBerry で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863394)

- [BlackBerry デバイス 7.1 OS 以前で電子メールをセットアップする](https://go.microsoft.com/fwlink/?linkid=863403)

詳細については、「[BlackBerry](../office-365-platform-service-description/blackberry.md)」を参照してください。
  
> [!NOTE]
> If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES). 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  