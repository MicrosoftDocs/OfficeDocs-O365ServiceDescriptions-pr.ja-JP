---
title: 受信者
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: このトピックでは、Microsoft Exchange Online に含まれる受信者関連の機能について説明します。 これには、電子メール、連絡先、配布グループ、および予定表とスケジュール機能が含まれています。
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132641"
---
# <a name="recipients"></a>受信者

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>Email

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> キャッチオール アドレスは、Exchange Online ではサポートされていません。 受信者フィルターが潜在的なスパムメッセージから保護するために必要なため、組織内に存在しない電子メールアドレスは拒否されます。 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>メールボックスの種類、ストレージの制限、および容量の警告

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
詳細については、トピック「 [Exchange Online の制限](exchange-online-limits.md)」の「メールボックスの格納域の制限」と「容量のアラート」セクションを参照してください。
  
### <a name="mailtips"></a>メール ヒント

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>代理人アクセス

Exchange Online は、ユーザーが他のユーザーに自身の電子メールや予定表の管理を許可できるようにする代理人アクセスをサポートしています。 代理人アクセスは、一般に、マネージャーとアシスタントの間で、アシスタントがマネージャーの受信した電子メール メッセージを処理し、マネージャーのスケジュールを調整するような場合に使用されます。 代理人アクセスは、Outlook または outlook on the web または Exchange 管理センターの管理者が Exchange Online ユーザーによって有効にすることができます。 
  
代理人は、2 つの方法でアクセスできます。
  
- **代理送信アクセス許可** 代理人は、電子メール メッセージを作成し、送信者フィールドに他のユーザーの名前を入力できます。このフィールドには「個人の名前」の代わりに「代理人の名前」が表示されます。 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
アクセスの委任の詳細については、「[受信者のアクセス許可を管理する](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx)」をご覧ください。
  
### <a name="inbox-rules"></a>受信トレイ ルール

Exchange Online では、ユーザーが、メッセージの到着時に特定の基準をベースにした動作を自動的に実行する受信トレイ ルールを作成できます。 たとえば、メールがある配信グループに送信された場合、すべてのメールを特定のフォルダーに自動的に移動するといったルールを作成できます。 ユーザーは、Outlook または web 上の Outlook から受信トレイルールを管理します。 管理者は、サーバー側転送、サーバー側自動返信、またはその両方を無効化することで、特定の受信トレイ ルールをブロックできます。 たとえば、サーバー側の電子メール転送を無効化すると、電子メールがユーザーの個人アカウントに自動転送されるのを防ぐことができます。 同様に、サーバー側の自動返信を無効化すると、外部の関係者がこれらの返信を利用して、有効な電子メール アドレスを特定するのを防ぐことが可能です。 これらの変更は、リモート Windows PowerShell から行われます。
  
### <a name="clutter"></a>クラッター機能

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>接続されているアカウント

接続されたアカウント機能を使用すると、Exchange Online のユーザーは、外部の電子メールアカウント (個人アカウントなど) を Exchange Online の内部電子メールアカウントに接続し、web 上の Outlook を使用して、1つの場所ですべてのメッセージを操作することができます。 接続されたアカウントは、サインイン時に web 上の Outlook と自動的に同期します。ユーザーは、アカウントを web 上の Outlook から手動で同期することもできます。 管理者は、[Exchange 管理センター](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409) から、この機能を特定のユーザーまたはすべてのユーザーに対して有効および無効にできます。
  
### <a name="inactive-mailboxes"></a>非アクティブなメールボックス

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
非アクティブなメールボックスを有効にするには、メールボックスに Exchange Online (プラン 2) ライセンスを割り当てるか、Exchange Online Archiving をサブスクライブすることによって、インプレース保持または訴訟ホールドを削除前のメールボックスに配置できるようにする必要があります。
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
詳細については、次のトピックを参照してください。
  
- [Exchange Online の非アクティブなメールボックスを管理する](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [インプレース電子情報開示 (eDiscovery) (このページは英語の可能性があります)](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>連絡先と配布グループ

### <a name="offline-address-book"></a>オフライン アドレス帳

オフラインアドレス帳機能は、Outlook グローバルアドレス一覧 (GAL) で利用可能な Active Directory 情報のスナップショットを提供します。 これは、ユーザーがオフラインで作業する際に使用できるよう、Outlook のローカルにキャッシュされます。
  
### <a name="address-book-policies"></a>アドレス帳ポリシー

Exchange Online はアドレス帳ポリシーをサポートしています。 アドレス帳ポリシー (ABP) によって、ユーザーを特定のグループに分割し、組織のグローバル アドレス一覧 (GAL) をカスタマイズ表示することができます。 ABP の作成時には、GAL、オフライン アドレス帳 (OAB)、会議室一覧、1 つ以上のアドレス一覧をポリシーに割り当てます。 その後、ABP をメールボックスユーザーに割り当て、Outlook および web 上の Outlook でカスタマイズされた GAL へのアクセス権を提供できます。 管理者は、リモートの Windows PowerShell を使用して、アドレス帳ポリシーを構成できます。 アドレス帳ポリシーについての詳細は、「[Exchange Online のアドレス帳](https://go.microsoft.com/fwlink/p/?LinkId=394203)」を参照してください。
  
### <a name="address-lists"></a>アドレス一覧

Exchange Online では、アドレス一覧と Gal のカスタマイズがサポートされています。 GAL は、メールが有効なすべてのユーザー、配布グループ、および外部連絡先の組織全体のディレクトリです。 管理者は、ディレクトリ同期ツールまたはリモート Windows PowerShell を使用して、ユーザー、配布グループ、および連絡先を GAL から非表示にすることができます。
  
### <a name="hierarchical-address-books"></a>階層型アドレス帳

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>配布グループ (グローバル)

配布グループ (または配布一覧) は、社内の全ユーザーが利用できるユーザー、連絡先、および他の配布グループのコレクションです。 ユーザーは、配布グループのエイリアスを電子メールの宛先に指定して、そのグループ内の全員にメッセージを送信します。 配布グループは、Outlook で各自が作成する個人の配布グループと似ていますが、メンバー リストが社内でグローバルに利用可能な点のみが異なります。 管理者は Exchange 管理センターで配布グループを作成します。 また、グループは、社内 Active Directory から Exchange Online と同期させることもできます。 これらは、Outlook の GAL に表示されます。 Exchange Online は、以下を含む高度な配布グループ機能をサポートします。
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>外部連絡先 （グローバル）

外部連絡先は、指定した組織の外で作業する個人の情報を含むレコードです。 外部連絡先は、Outlook で各自が作成する個人の連絡先と似ていますが、社内でグローバルに利用可能な点のみが異なります。 管理者は、Exchange 管理センターまたはリモート Windows PowerShell を使用して、外部連絡先を作成します。 また、これらの連絡先は、社内 Active Directory から Exchange Online と同期させることもできます。 これらは、Outlook の GAL に表示されます。
  
外部の連絡先の詳細については、「[Exchange Online で組織の関係を作成する](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx)」をご覧ください。
  
## <a name="calendar-and-scheduling"></a>予定表とスケジューリング

### <a name="resource-mailboxes"></a>リソース メールボックス

リソース メールボックス (会議室や物理的機器など) は、会社の会議室、他の設備、またはリソースを表します。 ユーザーは、Outlook または web 上の Outlook の会議出席依頼にリソースの電子メールエイリアスを追加することによって、会議室またはリソースを予約することができます。 会議室とリソースは、Outlook および web 上の Outlook の GAL に表示されます。
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
リソース メールボックスの詳細については、以下を参照してください。
  
- [会議室メールボックスを作成して管理する](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [備品用メールボックスの管理](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>会議室の管理

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
管理者は、web 上の Outlook で会議室の自動応答をカスタマイズし、予約ポリシーを構成できます。 これらのポリシーには、リソースのスケジュールを設定できるユーザー、スケジュールを設定できる期間、リソースの予定表に表示する会議情報、およびスケジューリングの競合を許可する割合が含まれます。 管理者は、リソース予約アテンダントを無効化して、手動で会議室の会議出席依頼を管理する特定のユーザーを割り当てることができます。
  
管理者は、リモート Windows PowerShell を使用して RBA の設定を定義し、管理する必要があります。
  
### <a name="out-of-office-replies"></a>不在時の返信

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>予定表の共有

ユーザーは、2 つの方法のいずれかで個人の予定表を共有できます。
  
- **フェデレーション予定表の共有**フェデレーションは、フェデレーション共有をサポートする基盤となる信頼インフラストラクチャを指します。これは、Exchange ユーザーが他の外部のフェデレーション組織の受信者と予定表の空き時間情報と連絡先情報を共有する簡単な方法です。 これらには、exchange Online 組織または exchange Server 2010 または Exchange Server 2013 社内で実行されている組織が含まれます。 この信頼は、Microsoft サービスの作成時にすべての Exchange Online のお客様が事前に構成されているため、exchange Online 管理者は Microsoft Federation Gateway との信頼を設定する必要はありません。 既定の共有ポリシーを使用すると、ユーザーは web 上の Outlook または Outlook 2010 から予定表共有への招待を送信することができます。 管理者はリモート Windows PowerShell を使用してこのポリシーを無効にするか、ユーザーが共有できる空き時間情報カレンダーデータのレベルを構成します。 管理者は、別のフェデレーション組織との組織間の関係を作成することもできます。これにより、個々のユーザーが共有への招待を行う必要がなく、すべてのユーザーに対して必要な空き時間情報のレベルを組織間で表示することができます。 管理者が定義した共有ポリシーや組織の組織上の関係の範囲内では、ユーザーは共有の詳細をさらに細かく制限することができます。 
    
- **インターネット予定表共有** Exchange Online では、組織内外のすべてのユーザーが匿名アクセスで利用できるように、iCal 形式で予定表を公開することが可能です。 受信者は、Exchange、別のプラットフォーム、または Web ブラウザーを使用することができます。 Exchange Online ユーザーは、iCal でインターネット上の場所に公開されている予定表を購読することもできます。 この個人予定表の共有は、管理者が構成し、組織間で空き時間情報を共有するフェデレーション予定表の共有とは異なります。 管理者が許可する共有ポリシーを設定して適用するまで、ユーザーは iCal 形式で予定表データを発行することはできません。 管理者は、組織内のユーザーについて、リモート Windows PowerShell で iCal の公開と利用を無効化できます。
    
フェデレーション共有の詳細については、「[Exchange Online での共有](https://go.microsoft.com/fwlink/p/?LinkId=271774)」をご覧ください。
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 の会議室の検索

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- 新しい会議室一覧は、リモート Windows PowerShell を使用して作成できます。 
    
- 会議室のみを含む配布グループはすべて、リモート Windows PowerShell を使用して会議室一覧に変換できます。
    
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  