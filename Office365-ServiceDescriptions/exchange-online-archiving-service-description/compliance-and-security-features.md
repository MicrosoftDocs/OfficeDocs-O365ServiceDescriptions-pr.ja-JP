---
title: Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132741"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving のコンプライアンス機能

以下のセクションでは、Microsoft Exchange Online Archiving のコンプライアンス機能について説明します。
  
### <a name="retention-policies"></a>アイテム保持ポリシー

Exchange Online アーカイブは、組織が電子メールやその他の通信に関連する負債を低減するのに役立つアイテム保持ポリシーを提供します。 これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。 管理者は、ユーザーにアイテム保持ポリシーのメニューを提供して、Outlook 2010 以降または web 上の Outlook を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。 Exchange Online のアーカイブでは、管理者がオンプレミスのインフラストラクチャからアイテム保持ポリシーを管理します。
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Outlook 2010 以降と web 上の Outlook では、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用し、メッセージに適用されているアイテム保持ポリシーと予期される削除日を表示することもできます。 他の電子メール クライアントのユーザーは、管理者が準備したサーバー側のアイテム保持ポリシーに基づいて電子メールを削除またはアーカイブできますが、同じレベルの表示および管理機能は使用できません。
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>インプレース保持と訴訟ホールド

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
Exchange Online では、次の目標を達成するためにインプレース保持または訴訟ホールドを使用できます。
  
- ユーザーを保持の状態にしてメールボックス アイテムを変更しないで維持する
    
- ユーザーまたは自動削除プロセス (MRM など) によって削除されたメールボックス アイテムを維持する
    
- 元のアイテムのコピーを保存して、メールボックス アイテムを改ざん、ユーザーによる変更、または自動プロセスから保護する
    
- アイテムを無期限にまたは特定の期間維持する
    
- MRM を中断する必要をなくしユーザーが保持を意識しないで済むようにする
    
- インプレース電子情報開示を使用して、保留中のアイテムを含むメールボックス アイテムを検索する
    
加えて、インプレース保持を以下の目的に使用できます。
  
- 指定した条件と一致するアイテムを検索して保持する
    
- さまざまなケースまたは調査に対応できるようユーザーに複数のインプレース保持を設定する
    
> [!NOTE]
> メールボックスのインプレース保持または訴訟ホールドを有効にすると、プライマリ メールボックスとアーカイブ メールボックスの両方に保持 (ホールド) が適用されます。 
  
詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。
  
> [!NOTE]
> Exchange Online Archiving ユーザーの場合、回復可能なアイテム フォルダーの既定のクォータは 100 GB です。 
  
### <a name="in-place-ediscovery"></a>インプレース電子情報開示 (eDiscovery)

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving のセキュリティ機能

以下のセクションでは、Microsoft Exchange Online Archiving のセキュリティ機能について説明します。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>社内サーバーと Exchange Online Archiving 間の暗号化

TLS は、電子メール サーバー間の接続を暗号化して、スプーフィングの回避を支援したり、伝送中のメッセージの機密性を確保したりするために使用されます。 TLS は、Exchange Online アーカイブ用に Microsoft データセンターへの社内メールサーバートラフィックをセキュリティで保護するためにも使用されます。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>クライアントと Exchange Online Archiving 間の暗号化

Exchange Online Archiving へのクライアント接続は、以下の暗号化方法を使用してセキュリティを強化します。
  
- SSL は、TCP ポート443を使用して Outlook、Outlook on the web、および Exchange Web サービスのトラフィックを保護するために使用されます。
    
- 社内のサーバーへのクライアント接続は、Exchange Online Archiving の導入によって変更されません。
    
### <a name="encryption-smime-and-pgp"></a>暗号化: S/MIME と PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
同様に、Exchange Online Archiving は Pretty Good Privacy (PGP) などのクライアント側のサード パーティ暗号化ソリューションを使用して暗号化されたメッセージを保存します。
  
### <a name="information-rights-management"></a>Information Rights Management

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Outlook on the web での IRM のサポート

ユーザーは、Outlook 上の Outlook で、IRM で保護されたメッセージを Outlook の場合と同じように、読み取りおよび作成を行うことができます。 Web 上の Outlook の IRM で保護されたメッセージには、Internet Explorer、Firefox、Safari、および Chrome を介してアクセスできます (プラグインは必要ありません)。 このメッセージには、フルテキスト検索、スレッド ビュー、プレビュー ウィンドウが含まれています。 Active Directory Rights Management サービス サーバーと社内の Exchange 環境間の相互運用性を有効にするように構成する必要があります。
  
#### <a name="irm-search"></a>IRM 検索

IRM で保護されたメッセージは、ヘッダー、件名、本文、添付ファイルなどのインデックスが作成され、検索可能になります。 ユーザーは、Outlook と web 上の Outlook で IRM で保護されたアイテムを検索でき、管理者はインプレース電子情報開示または**検索-メールボックス**コマンドレットを使用して irm で保護されたアイテムを検索できます。
  
### <a name="auditing"></a>監査

Exchange Online Archiving は、2 種類の組み込み監査機能を提供します。
  
- **管理者監査ログ** 管理者監査ログを使用すると、お客様が、RBAC の役割の変更や Exchange のポリシーと設定の変更などの、Exchange Online Archiving 環境で管理者が行った変更を追跡できます。 
    
- **メールボックス監査ログ** メールボックス監査ログを使用すると、お客様が、メールボックス所有者以外のユーザーによるメールボックスへのアクセスを追跡できます。 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。
  

