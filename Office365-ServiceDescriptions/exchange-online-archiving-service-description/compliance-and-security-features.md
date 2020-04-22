---
title: Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b977fea67c28a660a7468945c76d19677769cd8f
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638695"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a><span data-ttu-id="6aa9e-102">Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能</span><span class="sxs-lookup"><span data-stu-id="6aa9e-102">Compliance and security features in Exchange Online Archiving</span></span>

## <a name="compliance-features-in-exchange-online-archiving"></a><span data-ttu-id="6aa9e-103">Exchange Online Archiving のコンプライアンス機能</span><span class="sxs-lookup"><span data-stu-id="6aa9e-103">Compliance features in Exchange Online Archiving</span></span>

<span data-ttu-id="6aa9e-104">以下のセクションでは、Microsoft Exchange Online Archiving のコンプライアンス機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-104">The following sections describe the compliance features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="retention-policies"></a><span data-ttu-id="6aa9e-105">アイテム保持ポリシー</span><span class="sxs-lookup"><span data-stu-id="6aa9e-105">Retention policies</span></span>

<span data-ttu-id="6aa9e-106">Exchange Online アーカイブは、組織が電子メールやその他の通信に関連する負債を低減するのに役立つアイテム保持ポリシーを提供します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-106">Exchange Online Archiving offers retention policies to help organizations reduce the liabilities associated with email and other communications.</span></span> <span data-ttu-id="6aa9e-107">これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-107">With these policies, administrators can apply retention settings to specific folders in users' inboxes.</span></span> <span data-ttu-id="6aa9e-108">管理者は、ユーザーにアイテム保持ポリシーのメニューを提供して、Outlook 2010 以降または web 上の Outlook を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-108">Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook on the web.</span></span> <span data-ttu-id="6aa9e-109">Exchange Online のアーカイブでは、管理者がオンプレミスのインフラストラクチャからアイテム保持ポリシーを管理します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-109">In Exchange Online Archiving, administrators manage retention policies from the on-premises infrastructure.</span></span>
  
<span data-ttu-id="6aa9e-p102">Exchange Online Archiving は、アーカイブと削除の 2 種類のポリシーを提供します。両方のポリシーを同じアイテムまたはフォルダーに適用できます。たとえば、ユーザーは、電子メール メッセージにタグを付けて、電子メール メッセージが指定された日数に到達した時点で自動的に個人用アーカイブに移動され、さらに一定の日数が経過すると削除されるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p102">Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="6aa9e-113">Outlook 2010 以降と web 上の Outlook では、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用し、メッセージに適用されているアイテム保持ポリシーと予期される削除日を表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-113">With Outlook 2010 and later and Outlook on the web, users can apply retention policies to folders, conversations, or individual messages and can also view the applied retention policies and expected deletion dates on messages.</span></span> <span data-ttu-id="6aa9e-114">他の電子メール クライアントのユーザーは、管理者が準備したサーバー側のアイテム保持ポリシーに基づいて電子メールを削除またはアーカイブできますが、同じレベルの表示および管理機能は使用できません。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-114">Users of other email clients can have email deleted or archived based on server-side retention policies provisioned by the administrator, but they do not have the same level of visibility and control.</span></span>
  
<span data-ttu-id="6aa9e-p104">Exchange Online Archiving で提供されるアイテム保持ポリシー機能は、Exchange Server 2010 Service Pack 2 (SP2) 以降で提供される機能と同じです。管理者は、社内の Exchange Server 2010 以降の環境からアイテム保持ポリシーを管理できます。管理対象フォルダー (Exchange 2007 で導入されたメッセージング レコード管理に対する従来のアプローチ) は Exchange Online Archiving と互換性がないため、利用できません。詳細については、「[Exchange 2016 での保持タグおよびアイテム保持ポリシー](https://go.microsoft.com/fwlink/p/?LinkID=314153)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p104">The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span></span>
  
### <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="6aa9e-119">インプレース保持と訴訟ホールド</span><span class="sxs-lookup"><span data-stu-id="6aa9e-119">In-Place Hold and Litigation Hold</span></span>

<span data-ttu-id="6aa9e-p105">訴訟となる可能性がある程度見込まれる場合、組織では、訴訟に関連する電子メールを含めた電子的に格納された情報 (ESI) を保持する必要があります。訴訟の詳細が明らかになる前に訴訟の可能性を予測する場合もあるため、保持の対象が広範囲にわたることもあります。組織では、特定の問題に関するすべての電子メールを保存したり、特定の個人に関するすべての電子メールを保存したりします。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p105">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="6aa9e-123">Exchange Online では、次の目標を達成するためにインプレース保持または訴訟ホールドを使用できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-123">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="6aa9e-124">ユーザーを保持の状態にしてメールボックス アイテムを変更しないで維持する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-124">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="6aa9e-125">ユーザーまたは自動削除プロセス (MRM など) によって削除されたメールボックス アイテムを維持する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-125">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="6aa9e-126">元のアイテムのコピーを保存して、メールボックス アイテムを改ざん、ユーザーによる変更、または自動プロセスから保護する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-126">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="6aa9e-127">アイテムを無期限にまたは特定の期間維持する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-127">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="6aa9e-128">MRM を中断する必要をなくしユーザーが保持を意識しないで済むようにする</span><span class="sxs-lookup"><span data-stu-id="6aa9e-128">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="6aa9e-129">インプレース電子情報開示を使用して、保留中のアイテムを含むメールボックス アイテムを検索する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-129">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="6aa9e-130">加えて、インプレース保持を以下の目的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-130">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="6aa9e-131">指定した条件と一致するアイテムを検索して保持する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-131">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="6aa9e-132">さまざまなケースまたは調査に対応できるようユーザーに複数のインプレース保持を設定する</span><span class="sxs-lookup"><span data-stu-id="6aa9e-132">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="6aa9e-133">メールボックスのインプレース保持または訴訟ホールドを有効にすると、プライマリ メールボックスとアーカイブ メールボックスの両方に保持 (ホールド) が適用されます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-133">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="6aa9e-134">詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-134">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
> [!NOTE]
> <span data-ttu-id="6aa9e-135">Exchange Online Archiving ユーザーの場合、回復可能なアイテム フォルダーの既定のクォータは 100 GB です。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-135">The default quota for the Recoverable Items Folder is 100 GB for Exchange Online Archiving users.</span></span> 
  
### <a name="in-place-ediscovery"></a><span data-ttu-id="6aa9e-136">インプレース電子情報開示 (eDiscovery)</span><span class="sxs-lookup"><span data-stu-id="6aa9e-136">In-Place eDiscovery</span></span>

<span data-ttu-id="6aa9e-p106">Exchange Online Archiving は、組織内のメールボックスの内容を検索するためのインフレース電子情報開示をサポートしています。社内の Exchange 2013 サーバーから Exchange 管理センターまたはリモート Windows PowerShell を使用している管理者または認定証拠開示管理者は、電子メール メッセージ、添付ファイル、予定、タスク、連絡先などのさまざまなメールボックス アイテムを検索できます。インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。Keyword Query Language (KQL) 構文に加えて、送信者、受信者、メッセージの種類、送信日、受信日、カーボン コピー、ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。詳細については、「[インプレース電子情報開示 (eDiscovery)](https://go.microsoft.com/fwlink/p/?LinkId=314169)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p106">Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span></span>
  
<span data-ttu-id="6aa9e-p107">Exchange 管理センターとリモート Windows PowerShell を使用すると、インプレース電子情報開示検索で最大 5,000 個のメールボックスを同時に検索できます。リモート Windows PowerShell を使用してインプレース電子情報開示検索を実行する方法については、「[New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p107">The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span></span> 
  
> [!NOTE]
> <span data-ttu-id="6aa9e-p108">リモート Windows PowerShell では、 `Search-Mailbox` コマンドレットを使用して 5,000 個を超えるメールボックスを検索できます。リモート Windows PowerShell を使用して大量のメールボックスを検索する場合の詳細については、「 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p108">In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span></span> 
  
<span data-ttu-id="6aa9e-p109">インプレース電子情報開示検索の結果は、Exchange 管理センターでプレビューしたり, .pst ファイルにエクスポートしたり、探索メールボックスという特殊なメールボックスにコピーしたりできます。管理者またはコンプライアンス担当役員は、探索メールボックスに接続してメッセージを確認できます。詳細については、「[インプレース電子情報開示検索を作成する](https://go.microsoft.com/fwlink/p/?LinkId=314172)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p109">Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span></span>
  
> [!NOTE]
> <span data-ttu-id="6aa9e-p110">社内およびクラウド ベースのメールボックスまたはアーカイブに対して実行されたインプレース電子情報開示検索の結果をコピーする場合は、社内探索メールボックスを選択する必要があります。社内のプライマリ メールボックスとクラウド ベースのアーカイブからのメッセージは、社内の探索メールボックスにコピーされます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p110">When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox.</span></span> 
  
<span data-ttu-id="6aa9e-p111">管理者は、組織全体の複数のメールボックスに送信された不適切な電子メール メッセージを検索して削除することもできます。たとえば、機密扱いの給与情報が誤ってすべての従業員に電子メールで送信された場合は、管理者がユーザーのメールボックスからその電子メールを削除できます。この種の検索は、Exchange 管理センターでは使用できません。リモート PowerShell を使用して実行する必要があります。ユーザーのメールボックスからメッセージを削除する方法については、「[Exchange 2016 でメッセージを検索して削除する](https://go.microsoft.com/fwlink/p/?LinkId=314173)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p111">Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span></span>
  
## <a name="security-features-in-exchange-online-archiving"></a><span data-ttu-id="6aa9e-156">Exchange Online Archiving のセキュリティ機能</span><span class="sxs-lookup"><span data-stu-id="6aa9e-156">Security features in Exchange Online Archiving</span></span>

<span data-ttu-id="6aa9e-157">以下のセクションでは、Microsoft Exchange Online Archiving のセキュリティ機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-157">The following sections describe the security features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a><span data-ttu-id="6aa9e-158">社内サーバーと Exchange Online Archiving 間の暗号化</span><span class="sxs-lookup"><span data-stu-id="6aa9e-158">Encryption between on-premises servers and Exchange Online Archiving</span></span>

<span data-ttu-id="6aa9e-159">TLS は、電子メール サーバー間の接続を暗号化して、スプーフィングの回避を支援したり、伝送中のメッセージの機密性を確保したりするために使用されます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-159">TLS is used to encrypt the connection between email servers to help prevent spoofing and provide confidentiality for messages in transit.</span></span> <span data-ttu-id="6aa9e-160">TLS は、Exchange Online アーカイブ用に Microsoft データセンターへの社内メールサーバートラフィックをセキュリティで保護するためにも使用されます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-160">TLS is also used for securing on-premises mail server traffic to Microsoft datacenters for Exchange Online Archiving.</span></span>
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a><span data-ttu-id="6aa9e-161">クライアントと Exchange Online Archiving 間の暗号化</span><span class="sxs-lookup"><span data-stu-id="6aa9e-161">Encrypting between clients and Exchange Online Archiving</span></span>

<span data-ttu-id="6aa9e-162">Exchange Online Archiving へのクライアント接続は、以下の暗号化方法を使用してセキュリティを強化します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-162">Client connections to Exchange Online Archiving use the following encryption methods to enhance security:</span></span>
  
- <span data-ttu-id="6aa9e-163">SSL は、TCP ポート443を使用して Outlook、Outlook on the web、および Exchange Web サービスのトラフィックを保護するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-163">SSL is used for securing Outlook, Outlook on the web, and Exchange Web Services traffic, using TCP port 443.</span></span>
    
- <span data-ttu-id="6aa9e-164">社内のサーバーへのクライアント接続は、Exchange Online Archiving の導入によって変更されません。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-164">Client connections to on-premises servers do not change with the introduction of Exchange Online Archiving.</span></span>
    
### <a name="encryption-smime-and-pgp"></a><span data-ttu-id="6aa9e-165">暗号化: S/MIME と PGP</span><span class="sxs-lookup"><span data-stu-id="6aa9e-165">Encryption: S/MIME and PGP</span></span>

<span data-ttu-id="6aa9e-p113">Exchange Online Archiving は、Secure/Multipurpose Internet Mail Extension (S/MIME) メッセージを保存します。ただし、Exchange Online Archiving が S/MIME 機能または公開キーをホストしたり、キー リポジトリ、キー管理、キー ディレクトリ サービスを提供したりすることはありません。これは、これらのサービスのすべてが社内の Exchange インフラストラクチャに附属しているためです。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p113">Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.</span></span>
  
<span data-ttu-id="6aa9e-168">同様に、Exchange Online Archiving は Pretty Good Privacy (PGP) などのクライアント側のサード パーティ暗号化ソリューションを使用して暗号化されたメッセージを保存します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-168">Similarly, Exchange Online Archiving will store messages that are encrypted using client-side, third-party encryption solutions such as Pretty Good Privacy (PGP).</span></span>
  
### <a name="information-rights-management"></a><span data-ttu-id="6aa9e-169">Information Rights Management</span><span class="sxs-lookup"><span data-stu-id="6aa9e-169">Information Rights Management</span></span>

<span data-ttu-id="6aa9e-p114">Exchange Online Archiving はホスト型 Information Rights Management (IRM) サービスを提供しませんが、管理者は社内の Active Directory Rights Management Services (AD RMS) を使用できます。AD RMS サーバーが展開されている場合、Outlook はそのサーバーと直接通信できるため、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。AD RMS サーバーと社内の Exchange 環境間の相互運用性が構成されていれば、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p114">Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.</span></span>
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a><span data-ttu-id="6aa9e-173">Outlook on the web での IRM のサポート</span><span class="sxs-lookup"><span data-stu-id="6aa9e-173">Support for IRM in Outlook on the web</span></span>

<span data-ttu-id="6aa9e-174">ユーザーは、Outlook 上の Outlook で、IRM で保護されたメッセージを Outlook の場合と同じように、読み取りおよび作成を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-174">Users can read and create IRM-protected messages natively in Outlook on the web, just as they can in Outlook.</span></span> <span data-ttu-id="6aa9e-175">Web 上の Outlook の IRM で保護されたメッセージには、Internet Explorer、Firefox、Safari、および Chrome を介してアクセスできます (プラグインは必要ありません)。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-175">IRM-protected messages in Outlook on the web can be accessed through Internet Explorer, Firefox, Safari, and Chrome (with no plug-in required).</span></span> <span data-ttu-id="6aa9e-176">このメッセージには、フルテキスト検索、スレッド ビュー、プレビュー ウィンドウが含まれています。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-176">The messages include full-text search, conversation view, and the preview pane.</span></span> <span data-ttu-id="6aa9e-177">Active Directory Rights Management サービス サーバーと社内の Exchange 環境間の相互運用性を有効にするように構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-177">Interoperability between the Active Directory Rights Management Services server and the on-premises Exchange environment must be configured to enable this.</span></span>
  
#### <a name="irm-search"></a><span data-ttu-id="6aa9e-178">IRM 検索</span><span class="sxs-lookup"><span data-stu-id="6aa9e-178">IRM search</span></span>

<span data-ttu-id="6aa9e-179">IRM で保護されたメッセージは、ヘッダー、件名、本文、添付ファイルなどのインデックスが作成され、検索可能になります。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-179">IRM-protected messages are indexed and searchable, including headers, subject, body, and attachments.</span></span> <span data-ttu-id="6aa9e-180">ユーザーは、Outlook と web 上の Outlook で IRM で保護されたアイテムを検索でき、管理者はインプレース電子情報開示または**検索-メールボックス**コマンドレットを使用して irm で保護されたアイテムを検索できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-180">Users can search IRM-protected items in Outlook and Outlook on the web, and administrators can search IRM-protected items by using In-Place eDiscovery or the **Search-Mailbox** cmdlet.</span></span>
  
### <a name="auditing"></a><span data-ttu-id="6aa9e-181">監査</span><span class="sxs-lookup"><span data-stu-id="6aa9e-181">Auditing</span></span>

<span data-ttu-id="6aa9e-182">Exchange Online Archiving は、2 種類の組み込み監査機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-182">Exchange Online Archiving provides two types of built-in auditing capabilities:</span></span>
  
- <span data-ttu-id="6aa9e-183">**管理者監査ログ** 管理者監査ログを使用すると、お客様が、RBAC の役割の変更や Exchange のポリシーと設定の変更などの、Exchange Online Archiving 環境で管理者が行った変更を追跡できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-183">**Administrator audit logging** Administrator audit logging allows customers to track changes made by their administrators in the Exchange Online Archiving environment, including changes to RBAC roles or Exchange policies and settings.</span></span> 
    
- <span data-ttu-id="6aa9e-184">**メールボックス監査ログ** メールボックス監査ログを使用すると、お客様が、メールボックス所有者以外のユーザーによるメールボックスへのアクセスを追跡できます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-184">**Mailbox audit logging** Mailbox audit logging allows customers to track access to mailboxes by users other than the mailbox owner.</span></span> 
    
<span data-ttu-id="6aa9e-p117">Exchange 管理センターで、管理者の役割の変更、訴訟ホールド、所有者以外のメールボックス アクセスなどのいくつかの定義済みの監査レポートを利用できます。管理者は、日付や役割でレポートをフィルター処理したり、特定のメールボックスに対するすべての監査イベントを XML 形式でエクスポートして長期保存やカスタム レポート作成に利用したりできます。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p117">Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.</span></span>
  
<span data-ttu-id="6aa9e-p118">管理者監査ログは既定でオンになっており、メールボックス監査ログは既定でオフになっています。管理者は、リモート Windows PowerShell を使用して、組織内の一部またはすべてのメールボックスに対してメールボックス監査ログを有効にすることができます。詳細については、「[Exchange 監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=314175)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-p118">Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="6aa9e-190">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="6aa9e-190">Feature availability</span></span>

<span data-ttu-id="6aa9e-191">プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6aa9e-191">To view feature availability across plans, standalone options, and on-premise solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  

