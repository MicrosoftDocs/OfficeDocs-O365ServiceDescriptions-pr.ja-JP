---
title: メッセージ ポリシーと準拠
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036429"
---
# <a name="message-policy-and-compliance"></a><span data-ttu-id="f84ee-102">メッセージ ポリシーと準拠</span><span class="sxs-lookup"><span data-stu-id="f84ee-102">Message Policy and Compliance</span></span>

## <a name="archiving-exchange-online-based-mailboxes"></a><span data-ttu-id="f84ee-103">Exchange Online ベースのメールボックスのアーカイブ</span><span class="sxs-lookup"><span data-stu-id="f84ee-103">Archiving Exchange Online-based mailboxes</span></span>

<span data-ttu-id="f84ee-p101">Exchange Online のメールボックスはクラウド内に存在するため、これらのメールボックスをアーカイブするには固有のホスティング環境が必要になります。いくつかのケースでは、Exchange Online を使用して社内メールボックスをクラウドでアーカイブすることもできます。このセクションでは、Exchange Online でのアーカイブ オプションについて説明します。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p101">Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.</span></span>
  
<span data-ttu-id="f84ee-p102">Exchange Online は、クラウドベースのメールボックスのアーカイブ機能を標準で備えています。これには、古い電子メール メッセージを保管するのに便利なインプレース アーカイブも含まれます。インプレース アーカイブは、Outlook や Outlook Web App でユーザーのプライマリ メールボックス フォルダーと並んで表示される特殊なメールボックスです。ユーザーはプライマリ メールボックスと同様の手順でアーカイブへのアクセスや検索を行うことができます。利用できる機能は、次のように使用しているクライアントによって異なります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p102">Exchange Online provides built-in archiving capabilities for cloud-based mailboxes, including an In-Place Archive that gives users a convenient place to store older email messages. An In-Place Archive is a special type of mailbox that appears alongside a user's primary mailbox folders in Outlook and Outlook Web App. Users can access and search the archive in the same way they access and search their primary mailboxes. Available functionality depends on the client in use:</span></span>
  
- <span data-ttu-id="f84ee-111">**Outlook 2016、Outlook 2013、Outlook 2010、および Outlook Web App** ユーザーはアーカイブのすべての機能に加え、保持およびアーカイブ ポリシーの制御といった関連するコンプライアンス機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-111">**Outlook 2016, Outlook 2013, Outlook 2010, and Outlook Web App** Users have access to the full features of the archive, as well as related compliance features like control over retention and archive policies.</span></span> 
    
- <span data-ttu-id="f84ee-p103">**Outlook 2007** ユーザーはインプレース アーカイブの基本的な機能を利用できますが、すべてのアーカイブ機能とコンプライアンス機能を利用できるわけではありません。たとえば、ユーザーはメールボックス アイテムに対して保持またはアーカイブ ポリシーを適用できないため、管理者がプロビジョニングするポリシーを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p103">**Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead.</span></span> 
    
<span data-ttu-id="f84ee-114">管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用し、特定のユーザーに対する個人用アーカイブ機能を有効にします。</span><span class="sxs-lookup"><span data-stu-id="f84ee-114">Administrators use the Exchange admin center or remote Windows PowerShell to enable the personal archive feature for specific users.</span></span>
  
<span data-ttu-id="f84ee-115">詳細については、次のトピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-115">For more information, see:</span></span>
  
- [<span data-ttu-id="f84ee-116">Exchange Online のアーカイブ メールボックス</span><span class="sxs-lookup"><span data-stu-id="f84ee-116">Archive mailboxes in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [<span data-ttu-id="f84ee-117"> Exchange Online のアーカイブ メールボックスを有効または無効にする </span><span class="sxs-lookup"><span data-stu-id="f84ee-117">Enable or disable an archive mailbox in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a><span data-ttu-id="f84ee-118">アーカイブのサイズ</span><span class="sxs-lookup"><span data-stu-id="f84ee-118">Archive sizes</span></span>

<span data-ttu-id="f84ee-p104">個々の個人用アーカイブには、1 人のユーザーのメッセージ データを保存できます。ストレージの割り当ては、次のようにサブスクリプション プランによって異なります。アーカイブ メールボックスのサイズの詳細について、「[Exchange Online の制限](exchange-online-limits.md)」の「メールボックス格納域の制限」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p104">Only one user's messaging data can be stored in each personal archive. The allocation of storage depends on the subscription plan. For more information about archive mailbox sizes, see the "Mailbox storage limits" section in [Exchange Online Limits](exchange-online-limits.md).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f84ee-p105">ジャーナリング、トランスポート ルール、または自動転送ルールを使用してアーカイブの目的のため、Exchange Online メールボックスにメッセージをコピーすることは許可されていません。Microsoft は、メールボックス アーカイブが個人用途以外で使用されている場合に、無制限のアーカイブを拒否する権利を留保します。 > インプレース アーカイブには、Outlook ユーザーに対する特定のライセンス要件があります。Outlook 2007 ユーザーが個人用アーカイブにアクセスするためには、Office 2007 の 2011 年 2 月の累積的な更新プログラムが必要です。 > Exchange Online では、管理者駆動で .pst ファイルを個人用アーカイブにインポートするための、Exchange Server 2010 Service Pack 1 以降の  _New-MailboxImportRequest_ Windows PowerShell コマンドレットをサポートしていません。ユーザーのプライマリ メールボックスとアーカイブの両方が Exchange Online にある場合、管理者は PST Capture (無料ツール) を使用してユーザーのプライマリ メールボックスまたはアーカイブに .pst ファイルのデータをインポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p105">Using journaling, transport rules, or auto-forwarding rules to copy messages to an Exchange Online mailbox for the purposes of archiving is not permitted. Microsoft reserves the right to deny unlimited archiving in instances where a mailbox archive is not being used in a personal scenario. > In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. > Exchange Online does not support the  _New-MailboxImportRequest_ Windows PowerShell cmdlet of Exchange Server 2010 Service Pack 1 or later for administrator-driven import of .pst files into a personal archive. If a user has both the primary mailbox and the archive in Exchange Online, an administrator can use PST Capture, a free tool, to import .pst file data to the user's primary mailbox or archive.</span></span> 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a><span data-ttu-id="f84ee-128">社内メールボックスのクラウドベースのアーカイブ</span><span class="sxs-lookup"><span data-stu-id="f84ee-128">Cloud-based archiving of on-premises mailboxes</span></span>

<span data-ttu-id="f84ee-p106">Microsoft のホスト型のアーカイブ ソリューションである Microsoft Exchange Online Archiving では、Exchange Online を使用して Exchange Server 2010 以降の社内メールボックスをクラウドベースでアーカイブすることができます。これを行うには、社内組織がハイブリッド モードになっているか、Exchange Online Archiving 用にセットアップされている必要があります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p106">Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f84ee-131">管理フォルダー ポリシーが適用された Exchange 2010 メールボックス サーバー上の社内メールボックスを使用するユーザーでは、社内またはクラウドベースのインプレース アーカイブを有効にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="f84ee-131">Users with an on-premises mailbox on an Exchange 2010 Mailbox server who have a Managed Folder policy applied cannot have an on-premises or cloud-based In-Place Archive enabled.</span></span> 
  
## <a name="retention-tags-and-retention-policies"></a><span data-ttu-id="f84ee-132">保持タグおよびアイテム保持ポリシー</span><span class="sxs-lookup"><span data-stu-id="f84ee-132">Retention tags and retention policies</span></span>

<span data-ttu-id="f84ee-p107">Exchange Online ではアイテム保持ポリシーが利用できます。これは、組織が電子メールやその他の通信に関連する負担を軽減するのに役立ちます。これらのポリシーを使用すると、管理者はユーザーの受信トレイの特定のフォルダーに保持設定を適用できます。また、管理者はユーザーにアイテム保持ポリシーのメニューを提供し、ユーザーが Outlook 2010 以降または Outlook Web App を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p107">Exchange Online offers retention policies to help organizations reduce the liabilities associated with email and other communications. With these policies, administrators can apply retention settings to specific folders in users' inboxes. Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook Web App.</span></span>
  
<span data-ttu-id="f84ee-136">Exchange Online では、管理者は Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用してアイテム保持ポリシーを管理します。</span><span class="sxs-lookup"><span data-stu-id="f84ee-136">In Exchange Online, administrators manage retention policies by using the Exchange admin center (EAC) or remote Windows PowerShell.</span></span>
  
<span data-ttu-id="f84ee-p108">Exchange Online では、アーカイブ ポリシーと削除ポリシーの 2 つのタイプのポリシーが利用できます。同じアイテムまたはフォルダーに対して両方のタイプを組み合わせて使用することができます。たとえば、ユーザーは指定した日数後に電子メール メッセージをインプレース アーカイブに自動的に移動し、さらに一定の期間が経過した後に削除するように電子メール メッセージにタグ付けできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p108">Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="f84ee-p109">ユーザーは Outlook 2010 以降または Outlook Web App を使用して、フォルダー、会話、または個別のメッセージに対してアイテム保持ポリシーを適用できます。また、メッセージに適用済みのアイテム保持ポリシーや削除日を表示することもできます。他の電子メール クライアントのユーザーは、管理者が設定したサーバー側のアイテム保持ポリシーに基づいて電子メール メッセージの削除またはアーカイブを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p109">With Outlook 2010 or later and Outlook Web App, users can apply retention policies to folders, conversations, or individual messages. They can also view the applied retention policies and expected deletion dates on messages. Users of other email clients can only have email messages deleted or archived based on server-side retention policies set by the administrator.</span></span>
  
<span data-ttu-id="f84ee-p110">Exchange Online で利用できるアイテム保持ポリシーの機能は、Exchange Server 2010 Service Pack 2 RU4 で利用できる機能と同じです。管理者はリモート Windows PowerShell を使用して、アイテム保持ポリシーを Exchange Server 2010 以降の社内環境から Exchange Online に移行できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p110">The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f84ee-145">管理フォルダー (Exchange Server 2007 で導入された古いメッセージング レコード管理方式) は Exchange Online では利用できません。</span><span class="sxs-lookup"><span data-stu-id="f84ee-145">Managed Folders, an older approach to messaging records management that was introduced in Exchange Server 2007, are not available in Exchange Online.</span></span> 
  
<span data-ttu-id="f84ee-146">詳細については、「[保持タグおよびアイテム保持ポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271745)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-146">For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=271745).</span></span>
  
## <a name="encryption-of-data-at-rest"></a><span data-ttu-id="f84ee-147">保存データの暗号化</span><span class="sxs-lookup"><span data-stu-id="f84ee-147">Encryption of data at rest</span></span>

<span data-ttu-id="f84ee-p111">Office 365 の顧客保存データの暗号化は、Exchange Online、Skype for Business、OneDrive for Business、SharePoint Online での複数のサービス側テクノロジ (BitLocker、DKM、Azure Storage Service Encryption、およびサービス暗号化を含む) によって提供されます。Office 365 Service Encryption には、Azure Key Vault に格納され、顧客によって管理される暗号化キーを使用するオプションがあります。この顧客管理キー オプションは [Office 365 顧客キー](https://go.microsoft.com/fwlink/?linkid=863349)と呼ばれ、Exchange Online、SharePoint Online、OneDrive for Business で使用できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p111">Encryption of Office 365 customer data at rest is provided by multiple service-side technologies, including BitLocker, DKM, Azure Storage Service Encryption, and service encryption in Exchange Online, Skype for Business, OneDrive for Business, and SharePoint Online. Office 365 Service Encryption include an option to use customer-managed encryption keys that are stored in Azure Key Vault. This customer-managed key option, called [Office 365 Customer Key](https://go.microsoft.com/fwlink/?linkid=863349), is available for Exchange Online, SharePoint Online, and OneDrive for Business.</span></span> 
  
### <a name="bitlocker"></a><span data-ttu-id="f84ee-151">BitLocker</span><span class="sxs-lookup"><span data-stu-id="f84ee-151">BitLocker</span></span>

<span data-ttu-id="f84ee-p112">Office 365 サーバーは BitLocker を使用して、顧客保存データが含まれるディスク ドライブをボリューム レベルで暗号化します。BitLocker 暗号化は、Windows に組み込まれているデータ保護機能です。BitLocker は、顧客データが含まれるディスクに何者かが物理的にアクセスできるようになりかねない過失がプロセスや制御 (アクセス制御またはハードウェアのリサイクルなど) で生じた場合に、脅威から安全に保護するために使用されるテクノロジの 1 つです。その場合、BitLocker は、コンピューターやディスクの紛失、盗難、または不適切な廃棄によるデータの盗難や漏洩などの脅威の可能性を低減します。 </span><span class="sxs-lookup"><span data-stu-id="f84ee-p112">Office 365 servers use BitLocker to encrypt the disk drives containing customer data at rest at the volume-level. BitLocker encryption is a data protection feature that is built into Windows. BitLocker is one of the technologies used to safeguard against threats in case there are lapses in other processes or controls (e.g., access control or recycling of hardware) that could lead to someone gaining physical access to disks containing customer data. In this case, BitLocker eliminates the potential for data theft or exposure because of lost, stolen, or inappropriately decommissioned computers and disks.</span></span> 
  
### <a name="distributed-key-manager"></a><span data-ttu-id="f84ee-156">Distributed Key Manager</span><span class="sxs-lookup"><span data-stu-id="f84ee-156">Distributed Key Manager</span></span>

<span data-ttu-id="f84ee-p113">BitLocker に加え、Distributed Key Manager (DKM) と呼ばれるテクノロジも使用しています。DKM は、一連の秘密キーを使用して情報を暗号化および復号化するクライアント側の機能です。Active Directory ドメイン サービス内の特定のセキュリティ グループのメンバーのみが、DKM によって暗号化されたデータを解読するためにこれらのキーにアクセスできます。Exchange Online では Exchange プロセスの実行に使用する特定のサービス アカウントだけが、そのセキュリティ グループに属します。データセンター内の標準運用手順の一環として、このセキュリティ グループに属する資格情報は人間には付与されないため、人間はだれもこれらの機密情報を解読できるキーにアクセスできません。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p113">In addition to BitLocker, we use a technology called Distributed Key Manager (DKM). DKM is a client-side functionality that uses a set of secret keys to encrypt and decrypt information. Only members of a specific security group in Active Directory Domain Services can access those keys to decrypt the data that is encrypted by DKM. In Exchange Online, only certain service accounts under which the Exchange processes run are part of that security group. As part of standard operating procedure in the datacenter, no human is given credentials that are part of this security group and therefore no human has access to the keys that can decrypt these secrets.</span></span>
  
## <a name="customer-key"></a><span data-ttu-id="f84ee-162">顧客キー</span><span class="sxs-lookup"><span data-stu-id="f84ee-162">Customer Key</span></span>

<span data-ttu-id="f84ee-p114">顧客キーによって、組織の暗号化キーを制御し、Microsoft のデータ センターにある保存データの暗号化にそれを使用するよう Office 365 を構成できます。保存データには、メールボックスに保存されている Exchange Online および Skype for Business からのデータと、SharePoint Online および OneDrive for Business に保存されているファイルが含まれます。詳しくは、「[顧客キーを使用して Office 365 のデータを制御する](https://go.microsoft.com/fwlink/?linkid=863349)」および「[Office 365 の顧客キーによるサービスの暗号化に関してよく寄せられる質問](https://go.microsoft.com/fwlink/?linkid=869438)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p114">With Customer Key, you control your organization's encryption keys and then configure Office 365 to use them to encrypt your data at rest in Microsoft's data centers. Data at rest includes data from Exchange Online and Skype for Business that is stored in mailboxes and files that are stored in SharePoint Online and OneDrive for Business. For more information, see [Controlling your data in Office 365 using Customer Key](https://go.microsoft.com/fwlink/?linkid=863349) and [Service Encryption with Customer Key for Office 365 FAQ](https://go.microsoft.com/fwlink/?linkid=869438).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="f84ee-166">Office 365 Message Encryption</span><span class="sxs-lookup"><span data-stu-id="f84ee-166">Office 365 Message Encryption</span></span>
<span data-ttu-id="f84ee-167"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-167"></span></span>

<span data-ttu-id="f84ee-p115">Office 365 Message Encryption によって、電子メール ユーザーは暗号化された電子メールを任意の宛先に送信できます。Azure Information Encryption の保護機能を活用する Office Message Encryption の新機能を発表しました。これらの新機能ではエンド ユーザー エクスペリエンスが拡張されており、それによって組織内外のだれとでも保護されたメッセージを簡単に共有し、共同作業をすることが可能になります。新しい Office Message Encryption 機能のセットアップにはいくつかの要件があります。Azure Information Protection をベースにビルドされている新しい Office 365 Message Encryption 機能のセットアップ情報を参照してください。従来の Office 365 Message Encryption を使用しているお客様は、上記のガイダンスに基づいてセットアップを行わない限り、新機能をご利用になれません。Office 365 Message Encryption の新旧それぞれの機能の詳細については、[FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p115">Office 365 Message Encryption allows email users to send encrypted email messages to anyone. We announced new capabilities in Office Message Encryption that leverage the protection features in Azure Information Encryption. These new capabilities provided enhanced end user experiences that make it easier to share and collaborate on protected messages with anyone inside or outside the organization. The new Office Message Encryption capabilities have some setup requirements. See Set up new Office 365 Message Encryption capabilities built on top of Azure Information Protection. Customers on legacy Office 365 Message Encryption do not get the new capabilities without following the set up guidance provided above. Please read the [FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) for more details on what's included in the new vs. legacy Office 365 Message Encryption capabilities.</span></span> 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a><span data-ttu-id="f84ee-175">Secure/Multipurpose Internet Mail Extensions (S/MIME)</span><span class="sxs-lookup"><span data-stu-id="f84ee-175">Secure/Multipurpose Internet Mail Extensions (S/MIME)</span></span>
<span data-ttu-id="f84ee-176"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-176"></span></span>

<span data-ttu-id="f84ee-p116">S/MIME を使用すれば、組織内で署名して暗号化した電子メールを送信することにより、機密情報を保護することができます。管理者は、PKI 証明書を設定してユーザーに発行した後で、リモート Windows PowerShell を使用して S/MIME をセットアップすることができます。この証明書は、社内の Active Directory 証明書サービスから同期する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p116">S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.</span></span>
  
<span data-ttu-id="f84ee-p117">S/MIME は Internet Explorer 9 以降でサポートされています。現在、S/MIME は Firefox、Opera、および Chrome でサポートされていません。詳細については、「[S/MIME によるメッセージの署名と暗号化](https://go.microsoft.com/fwlink/p/?LinkID=393973)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p117">S/MIME is supported on Internet Explorer 9 or later. Currently, S/MIME is unsupported on Firefox, Opera, and Chrome. For more information, see [S/MIME for Message Signing and Encryption](https://go.microsoft.com/fwlink/p/?LinkID=393973).</span></span>
  
## <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="f84ee-183">インプレース保持と訴訟ホールド</span><span class="sxs-lookup"><span data-stu-id="f84ee-183">In-Place Hold and Litigation Hold</span></span>
<span data-ttu-id="f84ee-184"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-184"></span></span>

<span data-ttu-id="f84ee-p118">訴訟となる可能性がある程度見込まれる場合、組織では、訴訟に関連する電子メールを含めた電子的に格納された情報 (ESI) を保持する必要があります。訴訟の詳細が明らかになる前に訴訟の可能性を予測する場合もあるため、保持の対象が広範囲にわたることもあります。組織では、特定の問題に関するすべての電子メールを保存したり、特定の個人に関するすべての電子メールを保存したりします。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p118">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="f84ee-188">Exchange Online では、次の目標を達成するためにインプレース保持または訴訟ホールドを使用できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-188">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="f84ee-189">ユーザーを保持の状態にしてメールボックス アイテムを変更しないで維持する</span><span class="sxs-lookup"><span data-stu-id="f84ee-189">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="f84ee-190">ユーザーまたは自動削除プロセス (MRM など) によって削除されたメールボックス アイテムを維持する</span><span class="sxs-lookup"><span data-stu-id="f84ee-190">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="f84ee-191">元のアイテムのコピーを保存して、メールボックス アイテムを改ざん、ユーザーによる変更、または自動プロセスから保護する</span><span class="sxs-lookup"><span data-stu-id="f84ee-191">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="f84ee-192">アイテムを無期限にまたは特定の期間維持する</span><span class="sxs-lookup"><span data-stu-id="f84ee-192">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="f84ee-193">MRM を中断する必要をなくしユーザーが保持を意識しないで済むようにする</span><span class="sxs-lookup"><span data-stu-id="f84ee-193">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="f84ee-194">インプレース電子情報開示を使用して、保留中のアイテムを含むメールボックス アイテムを検索する</span><span class="sxs-lookup"><span data-stu-id="f84ee-194">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="f84ee-195">加えて、インプレース保持を以下の目的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-195">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="f84ee-196">指定した条件と一致するアイテムを検索して保持する</span><span class="sxs-lookup"><span data-stu-id="f84ee-196">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="f84ee-197">さまざまなケースまたは調査に対応できるようユーザーに複数のインプレース保持を設定する</span><span class="sxs-lookup"><span data-stu-id="f84ee-197">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="f84ee-198">メールボックスのインプレース保持または訴訟ホールドを有効にすると、プライマリ メールボックスとアーカイブ メールボックスの両方に保持 (ホールド) が適用されます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-198">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="f84ee-199">詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-199">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="in-place-ediscovery"></a><span data-ttu-id="f84ee-200">インプレース電子情報開示 (eDiscovery)</span><span class="sxs-lookup"><span data-stu-id="f84ee-200">In-Place eDiscovery</span></span>
<span data-ttu-id="f84ee-201"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-201"></span></span>

<span data-ttu-id="f84ee-p119">Exchange Online では、カスタマーは Web ベースのインターフェイスを使用して組織全体のメールボックスの内容を検索することができます。インプレースの電子情報開示検索の実行を許可された管理者やコンプライアンス担当者およびセキュリティ担当者は、(割り当てにより) 電子メール メッセージ、添付ファイル、予定表の予定、タスク、連絡先、およびその他のアイテムを検索できます。インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。KQL 構文に加えて、送信者、受信者、メッセージの種類、送信/受信日付、およびカーボン コピー/ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。検索結果には、検索クエリに一致した削除済みアイテム フォルダー内のアイテムも含まれます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p119">Exchange Online enables customers to search the contents of mailboxes across an organization using a web-based interface. Administrators or compliance and security officials who are authorized to perform In-Place eDiscovery search (by assigning) can search email messages, attachments, calendar appointments, tasks, contacts, and other items. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message type, sent/receive date, and carbon copy/blind carbon copy, along with KQL Syntax. Search results will also include items in the Deleted Items folder if they match the search query.</span></span>
  
<span data-ttu-id="f84ee-p120">インプレース電子情報開示検索の結果は、Web ベースのインターフェイスでプレビューし、PST ファイルにエクスポートし、探索メールボックスと呼ばれる特殊なメールボックスにコピーすることができます。探索メールボックスには、検索結果を格納するための 50 GB のクォータが割り当てられています。また、管理者は Outlook を探索メールボックスに接続して検索結果にアクセスし、検索結果を .pst ファイルにエクスポートすることもできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p120">Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.</span></span>
  
<span data-ttu-id="f84ee-p121">管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用して、複数メールボックス検索を実行できます。Exchange 管理センターでは、検索結果の読み取り専用のプレビューを利用できます。これにより、管理者は検索をすばやく確認し、必要に応じて、別のパラメーターで検索を実行し直すことができます。検索を最適化した後に、管理者は検索結果を探索メールボックスにコピーできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p121">Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.</span></span>
  
<span data-ttu-id="f84ee-p122">既定では各組織に 1 つの探索メールボックスが作成されますが、管理者はリモート Windows PowerShell を使用して追加の探索メールボックスを作成することができます。インプレース電子情報開示検索の結果を格納する以外の目的に探索メールボックスを使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p122">By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.</span></span>
  
<span data-ttu-id="f84ee-p123">管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用して、インプレース電子情報開示検索を実行できます。Exchange 管理センターでは、検索結果の読み取り専用のプレビューを利用できます。これにより、管理者は検索をすばやく確認し、必要に応じて、別のパラメーターで検索を実行し直すことができます。検索を最適化した後に、管理者は検索結果を探索メールボックスにコピーしたり、検索結果を PST ファイルにエクスポートしたりできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p123">Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.</span></span>
  
<span data-ttu-id="f84ee-218">管理者は、Exchange 管理センターまたはリモート Windows PowerShell を使用して、インプレース電子情報開示検索で一度に最大 10,000 のメールボックスを検索できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-218">Administrators can use either the Exchange admin center or remote Windows PowerShell to search up to 10,000 mailboxes at a time in an In-Place eDiscovery search.</span></span> 
  
<span data-ttu-id="f84ee-219">Exchange Online では、権限のあるユーザーがインプレース電子情報開示を実行して次の操作のいずれかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-219">In Exchange Online, authorized users can perform In-Place eDiscovery and choose one of the following actions:</span></span>
  
- <span data-ttu-id="f84ee-220">**検索結果の推定** 検索によって返されるメッセージ数の見積もりを返します。これには、検索で使用されたキーワードの有効性を判断するキーワードの統計および必要に応じて検索パラメーターの微調整が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-220">**Estimate search results** Get an estimate of the number of messages the search will return, including keywords statistics to determine the effectiveness of keywords used in the search and tweak search parameters if required.</span></span> 
    
- <span data-ttu-id="f84ee-221">**検索結果のプレビュー**</span><span class="sxs-lookup"><span data-stu-id="f84ee-221">**Preview search results**</span></span>
    
- <span data-ttu-id="f84ee-222">検索結果に返されたメッセージを検出メールボックスにコピーします。</span><span class="sxs-lookup"><span data-stu-id="f84ee-222">Copy messages returned in search results to a Discovery mailbox.</span></span>
    
<span data-ttu-id="f84ee-223">詳細については、「[インプレース電子情報開示 (eDiscovery) (このページは英語の可能性があります)](http://go.microsoft.com/fwlink/p/?LinkId=271747)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-223">For more information, see [In-Place eDiscovery](http://go.microsoft.com/fwlink/p/?LinkId=271747).</span></span>
  
## <a name="mail-flow-rules"></a><span data-ttu-id="f84ee-224">メール フロー ルール</span><span class="sxs-lookup"><span data-stu-id="f84ee-224">Mail flow rules</span></span>
<span data-ttu-id="f84ee-225"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-225"></span></span>

<span data-ttu-id="f84ee-p124">メール フロー ルールを使用すると、組織を通過するメッセージを、特定の条件に基づいて確認し、処理することができます。メール フロー ルールによって、電子メール メッセージにメッセージング ポリシーを適用し、メッセージおよびメッセージング システムを保護し、情報漏洩を防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p124">You can use mail flow rules to look for specific conditions on messages that pass through your organization and act on them. Mail flow rules let you apply messaging policies to email messages, secure messages, protect messaging systems, and prevent information leakage.</span></span>
  
<span data-ttu-id="f84ee-p125">今日、多くの組織では、組織の内部および外部にいる受信者と送信者の間の通信を制限するメッセージング ポリシーを適用することが、法律、規制要件、または企業ポリシーによって要求されています。一部の組織では、個人間、組織内の各部門のグループ間、および組織外のエンティティ間の通信を制限するだけでなく、以下のようなメッセージング ポリシーの要件も満たす必要があります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p125">Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:</span></span>
  
- <span data-ttu-id="f84ee-230">不適切なコンテンツが組織に侵入したり組織から発信されたりしないようにする</span><span class="sxs-lookup"><span data-stu-id="f84ee-230">Preventing inappropriate content from entering or leaving the organization</span></span>
    
- <span data-ttu-id="f84ee-231">組織の機密情報をフィルター処理する</span><span class="sxs-lookup"><span data-stu-id="f84ee-231">Filtering confidential organization information</span></span>
    
- <span data-ttu-id="f84ee-232">特定の個人によって送受信されるメッセージを追跡またはコピーする</span><span class="sxs-lookup"><span data-stu-id="f84ee-232">Tracking or copying messages that are sent to or received from specific individuals</span></span>
    
- <span data-ttu-id="f84ee-233">配信する前に、検査のために受信メッセージと送信メッセージをリダイレクトする</span><span class="sxs-lookup"><span data-stu-id="f84ee-233">Redirecting inbound and outbound messages for inspection before delivery</span></span>
    
- <span data-ttu-id="f84ee-234">メッセージが組織を通過するときに免責事項を適用する</span><span class="sxs-lookup"><span data-stu-id="f84ee-234">Applying disclaimers to messages as they pass through the organization</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="f84ee-p126">電子メール サーバー上にサードパーティの iFilter をインストールする必要のある添付ファイルの種類 (Adobe .pdf など) では、適切な iFilter をインストールしない限りメール フロー ルールを使用して検査できません。メール フロー ルールでサポートされているファイルの種類の詳細については、「[Office 365 で、メール フロー ルールを使用してメッセージの添付ファイルを検査する](https://go.microsoft.com/fwlink/p/?LinkId=271748)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p126">Attachment file types that require installation of third-party iFilters on the email server (such as Adobe .pdf) cannot be inspected using mail flow rules until after an appropriate iFilter is installed. For more information about file types that are supported by mail flow rules, see [Use mail flow rules to inspect message attachments in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748).</span></span> 
  
<span data-ttu-id="f84ee-237">メール フロー ルールの詳細については、「[Exchange 2016 でのメール フロー ルール](https://go.microsoft.com/fwlink/p/?LinkId=296488)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-237">For more information about mail flow rules, see [Mail flow rules in Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).</span></span>
  
## <a name="data-loss-prevention"></a><span data-ttu-id="f84ee-238">データ損失防止</span><span class="sxs-lookup"><span data-stu-id="f84ee-238">Data loss prevention</span></span>
<span data-ttu-id="f84ee-239"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-239"></span></span>

<span data-ttu-id="f84ee-p127">データ損失防止 (DLP) 機能では、詳細なコンテンツ分析を通じて組織内の機密情報の識別、監視、および保護を行うことができます。DLP はプレミアム機能です。ビジネスクリティカルな電子メールには保護が必要な機密データが含まれるため、企業のメッセージ システムでの DLP の重要性はますます高まっています。Exchange Online で DLP 機能を使用すると、業務の生産性に影響を及ぼすことなく機密データを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p127">The data loss prevention (DLP) feature will help you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is a premium feature that is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature in Exchange Online enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="f84ee-243">DLP ポリシーは Exchange 管理センター (EAC) の管理インターフェイスで構成できます。この管理インターフェイスでは、次の操作を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-243">You can configure DLP policies in the Exchange admin center (EAC) management interface, which allows you to:</span></span> 
  
- <span data-ttu-id="f84ee-244">PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-244">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="f84ee-245">既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-245">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="f84ee-246">DLP ポリシーを完全に実施する前にその効果をテストできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-246">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="f84ee-247">独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-247">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="f84ee-248">メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、Exchange Online で処理を実行する信頼レベルを調整できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-248">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which Exchange Online acts.</span></span>
    
- <span data-ttu-id="f84ee-p128">ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。ドキュメントのフィンガープリント機能を使用すると、テキスト ベースのフォームを基に、機密情報のカスタム タイプを手早く作成し、トランスポート ルールと DLP ポリシーを定義できます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p128">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="f84ee-251">ポリシー ヒントを追加して、Outlook 2016、Outlook 2013、Outlook Web App、およびデバイス用 OWA の各ユーザーに通知メッセージを表示し、データの損失を削減できます。また、誤検知の報告を許可することによりポリシーの有効性を改善することもできます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-251">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2016, Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span> 
    
- <span data-ttu-id="f84ee-252">インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-252">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
<span data-ttu-id="f84ee-253">DLP の詳細については、「[データ損失防止](https://go.microsoft.com/fwlink/p/?LinkId=271749)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-253">For more information about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=271749).</span></span>
  
## <a name="journaling"></a><span data-ttu-id="f84ee-254">ジャーナル</span><span class="sxs-lookup"><span data-stu-id="f84ee-254">Journaling</span></span>
<span data-ttu-id="f84ee-255"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-255"></span></span>

<span data-ttu-id="f84ee-p129">Exchange Online は、SMTP を介してメッセージを受信できる任意の外部メールボックスに電子メールのコピーをジャーナリングするように構成することができます。ジャーナリングは、受信および送信電子メールを記録することで、組織が法律、規則、および組織の準拠要件に応答するのに役立ちます。メッセージのアイテム保持および準拠の計画をする場合、ジャーナリングについて、どのように組織の準拠ポリシーに適合するかを理解することは重要です。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p129">You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.</span></span>
  
<span data-ttu-id="f84ee-p130">ジャーナル ルールは、Exchange 管理センターまたはリモート Windows PowerShell を使用して管理できます。ユーザー単位および配布リスト単位でジャーナリングを構成し、内部メッセージのみ、外部メッセージのみ、または内部メッセージと外部メッセージの両方をジャーナリングするように選択できます。ジャーナリングされたメッセージには、元のメッセージだけでなく、送信者、受信者、コピー、およびブラインド コピーについての情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="f84ee-p130">You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.</span></span>
  
<span data-ttu-id="f84ee-262">信頼性の高いジャーナリングを実現するには、次のタスクをすべて実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f84ee-262">To ensure a successful and reliable journaling solution, you need to complete the following tasks:</span></span>
  
- <span data-ttu-id="f84ee-263">ジャーナリングの送信先が Exchange Online のメールボックスになっていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="f84ee-263">Make sure that the journaling destination is not be an Exchange Online mailbox.</span></span>
    
- <span data-ttu-id="f84ee-264">カスタマーのディレクトリにジャーナリングで使用する SMTP ターゲット メール アドレスの連絡先オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="f84ee-264">Create in the customer directory a contact object for the SMTP target email address to be used for journaling.</span></span>
    
- <span data-ttu-id="f84ee-265">もう 1 つ別の連絡先オブジェクトを作成します。これは、プライマリのジャーナル メールボックスが使用できないときにジャーナル レポートを受け取る代替用のジャーナル メールボックスです。</span><span class="sxs-lookup"><span data-stu-id="f84ee-265">Create a second contact object as an alternative journal mailbox to capture any journal reports when the primary journal mailbox is unavailable.</span></span>
    
- <span data-ttu-id="f84ee-266">SMTP ターゲットの適切な管理、冗長性、可用性、パフォーマンス、および機能レベルを維持して、いつでもメッセージを正常に受信できるようにします。</span><span class="sxs-lookup"><span data-stu-id="f84ee-266">Maintain proper management, redundancy, availability, performance, and functionality levels of the SMTP target to ensure successful mail acceptance always.</span></span>
    
- <span data-ttu-id="f84ee-267">メッセージ形式、送信者/受信者情報の統合、および適切なコンテンツ変換など、Exchange Server および Exchange トランスポートでの相互運用性を実現します。</span><span class="sxs-lookup"><span data-stu-id="f84ee-267">Provide respective interoperability with Exchange Server and Exchange transport including message formats, sender/recipient information integration, and appropriate content conversion.</span></span>
    
<span data-ttu-id="f84ee-268">ジャーナルの詳細については、「[Exchange Online でのジャーナリング](https://go.microsoft.com/fwlink/p/?LinkId=271750)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-268">For more information about journaling, see [Journaling](https://go.microsoft.com/fwlink/p/?LinkId=271750).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f84ee-269">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="f84ee-269">Feature Availability</span></span>
<span data-ttu-id="f84ee-270"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="f84ee-270"></span></span>

<span data-ttu-id="f84ee-271">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f84ee-271">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
