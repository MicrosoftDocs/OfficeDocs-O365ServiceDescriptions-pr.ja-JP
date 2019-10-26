---
title: 計画と展開
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: 6f920cbd0164acc3675bfd31799c2abf25d2b981
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2019
ms.locfileid: "37733868"
---
# <a name="planning-and-deployment"></a><span data-ttu-id="28036-102">計画と展開</span><span class="sxs-lookup"><span data-stu-id="28036-102">Planning and Deployment</span></span>

## <a name="planning-for-service-changes-and-growth"></a><span data-ttu-id="28036-103">サービスの変更と拡大の計画</span><span class="sxs-lookup"><span data-stu-id="28036-103">Planning for service changes and growth</span></span>

<span data-ttu-id="28036-104">組織は、送信元の電子メール システム、希望する最終的な状態 (完全なホスティングか、あるいは部分的なホスティングか)、移行するユーザーの数、またどの程度の期間で最終的な状態を実現しなければならないのかに基づいて、移行オプションを選択する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28036-104">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached.</span></span>
  
## <a name="deployment-options"></a><span data-ttu-id="28036-105">展開オプション</span><span class="sxs-lookup"><span data-stu-id="28036-105">Deployment options</span></span>

- <span data-ttu-id="28036-106">**クラウドのみの展開** お客様の組織では、すべてのユーザー メールボックスを Exchange Online でホストします。</span><span class="sxs-lookup"><span data-stu-id="28036-106">**Cloud-only deployment** Your organization has all user mailboxes hosted in Exchange Online.</span></span> 
    
- <span data-ttu-id="28036-107">**Exchange ハイブリッド展開** お客様の組織では、一部のユーザー メールボックスを社内 Exchange 組織でホストし、他のユーザー メールボックスを Exchange Online でホストします。</span><span class="sxs-lookup"><span data-stu-id="28036-107">**Exchange hybrid deployment** Your organization has some user mailboxes hosted in an on-premises Exchange organization and some user mailboxes hosted in Exchange Online.</span></span> 
    
### <a name="cloud-only"></a><span data-ttu-id="28036-108">クラウド専用</span><span class="sxs-lookup"><span data-stu-id="28036-108">Cloud-only</span></span>

<span data-ttu-id="28036-p101">クラウドのみの展開とは、Exchange Online サービス内の組織が、社内 Exchange 組織とは接続されない展開のことです。すべてのユーザーおよびメールボックスは、Exchange Online と Office 365 でホストおよび管理されます。</span><span class="sxs-lookup"><span data-stu-id="28036-p101">A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.</span></span>
  
### <a name="hybrid"></a><span data-ttu-id="28036-111">ハイブリッド</span><span class="sxs-lookup"><span data-stu-id="28036-111">Hybrid</span></span>

<span data-ttu-id="28036-p102">Microsoft Exchange 2003、Exchange 2007、Exchange 2010 および Exchange 2013 社内組織で利用可能なハイブリッド展開は、社内でホストされる一部のメールボックスと、Exchange Online でホストされる他のメールボックスが長期にわたって共存する構成か、すべてのユーザー メールボックスを Exchange Online でホストするための移行パスを提供します。ハイブリッド展開によって、充実した機能の利用、および既存の社内 Microsoft Exchange 組織に対する管理制御をクラウドにまで拡張することができます。ハイブリッド展開の機能には、安全なメール トランスポート、共有予定表の空き時間情報、および社内組織と Exchange Online 組織間のメッセージ追跡が含まれます。</span><span class="sxs-lookup"><span data-stu-id="28036-p102">Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.</span></span>
  
<span data-ttu-id="28036-p103">ハイブリッド展開の詳細については、「[Exchange Server のハイブリッド展開](https://go.microsoft.com/fwlink/p/?LinkId=287035)」を参照してください。21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 を使用して Exchange ハイブリッド展開機能を構成する](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="28036-p103">For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="28036-p104">オンプレミスの Exchange 2003 組織は、Exchange Online でハイブリッド展開を構成する場合、少なくとも 1 台の Exchange 2010 クライアント アクセス/メールボックス サーバーをインストールする必要があります。オンプレミスの Exchange 2007 組織は、Exchange Online でハイブリッド展開を構成する場合、少なくとも 1 台の Exchange 2010 または Exchange 2013 のクライアント アクセス/メールボックス サーバーをインストールする必要があります。オンプレミスの Exchange 2010 および Exchange 2013 組織は、Exchange Online でのハイブリッド展開をネイティブでサポートします。ハイブリッド展開における Exchange サーバーの互換性の詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/p/?LinkId=243541)」を参照してください。 > オンプレミスの Exchange 組織では、組織をハイブリッド展開用に構成する必要があります。管理者が Exchange Server 展開アシスタントおよびハイブリッド構成ウィザードを使用してハイブリッド展開を構成することを強くお勧めします。詳細については、「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-p104">On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)</span></span>
  
## <a name="migration-options"></a><span data-ttu-id="28036-123">移行オプション</span><span class="sxs-lookup"><span data-stu-id="28036-123">Migration options</span></span>

<span data-ttu-id="28036-p105">組織は、送信元の電子メール システム、希望する最終的な状態 (完全なホスティングか、あるいは部分的なホスティングか)、移行するユーザーの数、またどの程度の期間で最終的な状態を実現しなければならないのかに基づいて、移行オプションを選択する必要があります。実行可能な移行オプションは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="28036-p105">Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:</span></span>
  
- <span data-ttu-id="28036-126">**IMAP 移行** メールボックスのデータを IMAP ベースの電子メール システムから Exchange Online に移行します。</span><span class="sxs-lookup"><span data-stu-id="28036-126">**IMAP migration** Migrate mailbox data from IMAP-based email systems to Exchange Online.</span></span> 
    
- <span data-ttu-id="28036-127">**Exchange の一括移行** メールボックスを、Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 およびホストされる Exchange システムから、1 回の一括移行で Exchange Online に移行します。</span><span class="sxs-lookup"><span data-stu-id="28036-127">**Cutover Exchange migration** Migrate mailboxes from Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 and Hosted Exchange systems to Exchange Online in a single cutover migration.</span></span> 
    
- <span data-ttu-id="28036-128">**段階的な Exchange の移行** メールボックスを、Exchange Server 2003 または Exchange Server 2007 から、Web ベースの移行ツールを使用して、最小限の変更で社内インフラストラクチャに段階的に移行します。</span><span class="sxs-lookup"><span data-stu-id="28036-128">**Staged Exchange migration** Perform a staged migration to migrate mailboxes from Exchange Server 2003 or Exchange Server 2007 with web-based migration tools and minimal changes to on-premises infrastructure.</span></span> 
    
- <span data-ttu-id="28036-p106">**リモート移動移行** Exchange のハイブリッド展開で社内の Exchange メールボックスを Exchange Online に移行します。リモート移動移行を使用するには Exchange ハイブリッド展開を実装しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="28036-p106">**Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration.</span></span> 
    
<span data-ttu-id="28036-131">Exchange Online への電子メールおよびメールボックスの移行の詳細については、「[Exchange Online へのメールボックスの移行](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-131">For more information about migrating email and mailboxes to Exchange Online, see [Mailbox Migration to Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).</span></span>
  
### <a name="imap-migration"></a><span data-ttu-id="28036-132">IMAP 移行</span><span class="sxs-lookup"><span data-stu-id="28036-132">IMAP migration</span></span>

<span data-ttu-id="28036-p107">Exchange Online は、IMAP をサポートする電子メールシステムからメールボックスのデータを移行するための Web ベースのツールを提供します。管理者はこのツールにより、次の手順で移行を進めることができます。</span><span class="sxs-lookup"><span data-stu-id="28036-p107">Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps:</span></span> 
  
1. <span data-ttu-id="28036-135">組織内のユーザー用のクラウドに空のメールボックスを作成します (通常は CSV ファイルをアップロードするか、リモート Windows PowerShell を使用することにより実行できます)。</span><span class="sxs-lookup"><span data-stu-id="28036-135">Create empty mailboxes in the cloud for users in the organization (typically this is done by uploading a .csv file or using remote Windows PowerShell).</span></span>
    
2. <span data-ttu-id="28036-136">リモート サーバー接続の設定を入力します。</span><span class="sxs-lookup"><span data-stu-id="28036-136">Enter the remote server connection settings.</span></span>
    
3. <span data-ttu-id="28036-137">CSV ファイルを使用して、Exchange Online のメールボックスにデータを移行するメールボックスを指定します。</span><span class="sxs-lookup"><span data-stu-id="28036-137">Use a CSV file to specify the mailboxes whose data will be migrated to Exchange Online mailboxes.</span></span>
    
4. <span data-ttu-id="28036-138">この情報が入力されると、Exchange Online は、メールボックスのコンテンツを IMAP 経由で移行し始めます (予定表アイテム、連絡先、タスクなど、メール以外のアイテムは移行されません)。</span><span class="sxs-lookup"><span data-stu-id="28036-138">After this information is entered, Exchange Online begins to migrate mailbox content via IMAP (calendar items, contacts, tasks, and other non-mail items are not migrated).</span></span>
    
<span data-ttu-id="28036-139">IMAP 移行の詳細については、「[IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)」と「[他の種類の IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-139">For more information about IMAP migration, see [Migrate Email from an IMAP Server to Exchange Online Mailboxes](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) and [Migrate other types of IMAP mailboxes](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="28036-140">移行時のリモート サーバーのリソースや帯域幅の過剰な使用を避けるため、Exchange Online では、作成する IMAP サーバーへの接続を 10 未満に抑えます。</span><span class="sxs-lookup"><span data-stu-id="28036-140">To avoid overusing the remote server's resources and bandwidth during the migration, Exchange Online creates fewer than 10 connections to the IMAP server.</span></span> 
  
### <a name="cutover-exchange-migration"></a><span data-ttu-id="28036-141">Exchange の一括移行</span><span class="sxs-lookup"><span data-stu-id="28036-141">Cutover Exchange migration</span></span>

<span data-ttu-id="28036-p108">Exchange Online は、社内の Exchange Server 2003、Exchange Server 2007、または Exchange Server 2010 環境からデータを移行するための Web ベースのツールを提供します。管理者はこのツールにより、次の手順で移行を進めることができます。</span><span class="sxs-lookup"><span data-stu-id="28036-p108">Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:</span></span>
  
1. <span data-ttu-id="28036-144">Exchange Online では、電子メール アドレスと社内管理者アカウントのための資格情報を使用して、社内電子メール組織に自動検出サービスで接続します。</span><span class="sxs-lookup"><span data-stu-id="28036-144">Using the email address and credentials for an on-premises administrator account, Exchange Online connects to the on-premises email organization by using the Autodiscover service.</span></span>
    
2. <span data-ttu-id="28036-145">Exchange Online では、RPC/HTTP 接続を使用してリモート サーバーからディレクトリ情報を読み取り、Exchange Online にメールボックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="28036-145">Exchange Online uses an RPC/HTTP connection to read directory information from the remote server and create mailboxes in Exchange Online.</span></span>
    
3. <span data-ttu-id="28036-p109">Exchange Online は、メールボックスのコンテンツとクラウド メールボックスを同期します。データは Exchange Online に移行されますが、ユーザーは引き続き元のメールボックスに接続されます。</span><span class="sxs-lookup"><span data-stu-id="28036-p109">Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.</span></span>
    
4. <span data-ttu-id="28036-148">最初の移行が完了した後、管理者が移行バッチを停止または削除するまで、すべての変更は 24 時間ごとにクラウドに同期されます。</span><span class="sxs-lookup"><span data-stu-id="28036-148">After the initial migration is complete, any changes are synchronized to the cloud every 24 hours until the administrator stops or deletes the migration batch.</span></span>
    
<span data-ttu-id="28036-p110">管理者は、Office 365 をポイントするようにユーザーの MX レコードを構成し、Outlook のユーザー プロファイルを再構成して、ユーザーをクラウド メールボックスに切り替えます。ユーザーがクラウド メールボックスに切り替わると、ローカルのオフライン フォルダー (OST ファイル) が再同期され、移行されたメールがクライアント ワークステーションにダウンロードされます。移行が完了すると、ユーザーはメールボックス内の古いメッセージに返信できます。</span><span class="sxs-lookup"><span data-stu-id="28036-p110">To switch users to their cloud mailboxes, administrators configure their MX record to point to Office 365 and reconfigure the users' profiles in Outlook. When users switch to their cloud mailboxes, their local offline folders (.ost files) will resynchronize, resulting in the download of migrated mail to the client workstation. Users can reply to old messages in their mailboxes after migration.</span></span>
  
<span data-ttu-id="28036-152">Exchange の一括移行の詳細については、「[Office 365 への一括メール移行について知っておくべきこと](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-152">For more information about a cutover Exchange migration, see [What you need to know about a cutover email migration to Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="28036-p111">組織が Exchange の一括移行を使用してクラウドに移行できる Exchange 2003、Exchange 2007、Exchange 2010、または Exchange 2013 のメールボックスの最大数は 2,000 です。 > Exchange Online は社内の Exchange Server に接続しなければならないため、社内サーバーには、信頼できる証明機関の発行する証明書とパブリック IP アドレスが必要です。</span><span class="sxs-lookup"><span data-stu-id="28036-p111">An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address.</span></span> 
  
### <a name="staged-exchange-migration"></a><span data-ttu-id="28036-155">段階的な Exchange の移行</span><span class="sxs-lookup"><span data-stu-id="28036-155">Staged Exchange migration</span></span>

<span data-ttu-id="28036-p112">段階的な移行の場合、Web ベースの Exchange 移行ツールとディレクトリ同期ツールを使用してユーザーをクラウドに移行することができます。このとき、すべてのユーザーを同時に移行するのではなく、Exchange の一括移行のように、管理者は数回に分けてユーザーを移行します。この移行は、CSV ファイルをアップロードし、移行するユーザーの一覧の一部を指定することで実行されます。段階的な移行の場合、組織内のすべてのユーザーは、同じ電子メールのドメイン名を共有することができます。</span><span class="sxs-lookup"><span data-stu-id="28036-p112">With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.</span></span>
  
<span data-ttu-id="28036-p113">段階的な Exchange の移行では、管理者が Online Services のディレクトリ同期ツールを使用する必要があります。このツールは、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧 (GAL) をユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="28036-p113">Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.</span></span>
  
<span data-ttu-id="28036-162">Exchange での段階的な移行の詳細については、「[Office 365 への段階的メール移行について知っておくべきこと](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-162">For more information about staged Exchange migrations, see [What you need to know about a staged email migration](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="28036-p114">Exchange の段階的な移行では、Exchange 2010 および Exchange 2013 のメールボックスは移行できません。組織内の Exchange 2010 または Exchange 2013 メールボックスが 2,000 未満である場合は、Exchange の一括移行を使用できます。Exchange 2010 または Exchange 2013 メールボックスが 2,000 を超える場合は、ハイブリッド展開を実装することができます。 > 移行の際、管理者は、Online Services のディレクトリ同期ツールを使用して、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧 (GAL) をユーザーに提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28036-p114">Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
  
## <a name="migration-tools"></a><span data-ttu-id="28036-167">移行ツール</span><span class="sxs-lookup"><span data-stu-id="28036-167">Migration tools</span></span>

<span data-ttu-id="28036-p115">Microsoft は、既存の電子メール環境を Exchange Online に移行するのに役立ついくつかのツールを提供しています。どのツールが適切かは、組織の現在の環境と展開目標によって異なります。</span><span class="sxs-lookup"><span data-stu-id="28036-p115">Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:</span></span>
  
- <span data-ttu-id="28036-p116">**移行ダッシュボード** 管理者は、Exchange 管理センターで移行ダッシュボードを使用して、Exchange の一括移行または段階的な移行で、メールボックスの Exchange Online への移行を管理できます。管理者は、移行ダッシュボードを使用して、ユーザーのメールボックスのコンテンツを社内 IMAP サーバーから既存の Exchange Online メールボックスに移行することもできます。管理者は移行ダッシュボードにより、次のことが行えます。</span><span class="sxs-lookup"><span data-stu-id="28036-p116">**Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities:</span></span> 
    
  - <span data-ttu-id="28036-p117">**複数の移行バッチを作成し、開始する** 管理者は、最大 100 個の移行バッチを作成して、キューに入れることができます。一度に実行できる移行バッチは 1 つのみですが、管理者は複数のバッチをキューに入れることができるため、1 つの移行バッチの実行が完了すると、キュー内の次のバッチが開始されます。</span><span class="sxs-lookup"><span data-stu-id="28036-p117">**Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts.</span></span> 
    
  - <span data-ttu-id="28036-p118">**エラーを含む移行バッチの再開** 移行バッチに対する最初の同期の後、社内メールボックスから各ユーザーのクラウド メールボックスに移行バッチでアイテムがコピーされますが、一部のメールボックスの同期が失敗する場合があります。このとき管理者は、その移行バッチを再開して、失敗したメールボックスの同期を試行できます。</span><span class="sxs-lookup"><span data-stu-id="28036-p118">**Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes.</span></span> 
    
  - <span data-ttu-id="28036-177">**スキップされたアイテムの詳細情報を取得する** IMAP 移行、一括移行、および段階的な移行の場合、移行ダッシュボードには、スキップされたアイテムの情報が表示されます。この情報には、アイテムがユーザーのメールボックス内に置かれた理由と場所が含まれます。</span><span class="sxs-lookup"><span data-stu-id="28036-177">**Get details about skipped items** For IMAP migrations, cutover migrations, and staged migrations, the Migration dashboard displays information about the specific items that were skipped, including the reason why and where the item is located in the user's mailbox.</span></span> 
    
  - <span data-ttu-id="28036-178">**移行レポートを開く** 管理者は、移行バッチの移行統計情報または移行エラー レポートをダッシュボードから開くことができます。</span><span class="sxs-lookup"><span data-stu-id="28036-178">**Open migration reports** Administrators can open migration statistics or the migration error report for a migration batch right from the dashboard.</span></span> 
    
  - <span data-ttu-id="28036-179">**移行バッチを編集する** 段階的な Exchange の移行または IMAP 移行のための移行バッチが移行キューに含まれているものの現時点で実行されていない場合、管理者は移行バッチを編集することができます。</span><span class="sxs-lookup"><span data-stu-id="28036-179">**Edit a migration batch** If a migration batch for a staged Exchange migration or an IMAP migration is in the migration queue but not currently running, administrators can edit the migration batch.</span></span> 
    
- <span data-ttu-id="28036-p119">**Azure Active Directory 同期ツール** この Azure Active Directory 同期ツール は、移行の際に、Exchange Online と社内 Exchange Server の両方を利用する電子メール シナリオをハイブリッド化する重要な役割を果たします。このツールは、社内 Active Directory から Exchange Online への一方向の同期を実行します。管理者は、移行が完了した後、Exchange Online のみを使用して Active Directory ユーザーおよびグループを管理できます。また、このツールは、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧をユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="28036-p119">**Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment.</span></span> 
    
    <span data-ttu-id="28036-184">Azure Active Directory 同期ツール の詳細については、「[オンプレミス ID と Azure Active Directory の統合](https://go.microsoft.com/fwlink/p/?LinkId=287034)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-184">For more information about the Azure Active Directory Sync tool, see [Directory synchronization: Roadmap](https://go.microsoft.com/fwlink/p/?LinkId=287034).</span></span>
    
- <span data-ttu-id="28036-p120">**ハイブリッド構成ウィザード** ハイブリッド構成ウィザードは、社内および Exchange Online 構成の機能とサービスを簡素化することにより、ハイブリッド展開プロセスを効率化します。Exchange Server 2010 Service Pack 2 の一部として導入されたハイブリッド構成ウィザードは、社内組織でのみ実行され、次のコンポーネントを備えています。</span><span class="sxs-lookup"><span data-stu-id="28036-p120">**Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components:</span></span> 
    
  - <span data-ttu-id="28036-187">管理者によるハイブリッド展開の構成をエンドツーエンドのプロセスでサポートする Exchange 管理センター (EAC) のウィザード。</span><span class="sxs-lookup"><span data-stu-id="28036-187">An Exchange admin center (EAC) wizard that guides administrators through the end-to-end process for configuring a hybrid deployment.</span></span>
    
  - <span data-ttu-id="28036-188">構成プロセスを調整する一連の Exchange 管理シェル (EMS) コマンド。</span><span class="sxs-lookup"><span data-stu-id="28036-188">A set of Exchange Management Shell (EMS) commands that orchestrate the configuration process.</span></span>
    
    <span data-ttu-id="28036-189">ハイブリッド構成ウィザードの詳細については、「[ハイブリッド構成ウィザード](https://go.microsoft.com/fwlink/p/?LinkId=271734)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-189">For more information about the Hybrid Configuration Wizard, see [Hybrid Configuration Wizard](https://go.microsoft.com/fwlink/p/?LinkId=271734).</span></span>
    
- <span data-ttu-id="28036-p121">**リモート Windows PowerShell** リモート Windows PowerShell は、Exchange Online 2011 Service Update の一部として、移行エラーのトラブルシューティングに使用できます。たとえば管理者は、移行バッチの診断情報や、プライマリ SMTP アドレスに基づくユーザーの移行統計情報および診断情報を表示できます。</span><span class="sxs-lookup"><span data-stu-id="28036-p121">**Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses.</span></span> 
    
## <a name="feature-availability"></a><span data-ttu-id="28036-192">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="28036-192">Feature availability</span></span>

<span data-ttu-id="28036-193">Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="28036-193">To view feature availability across Office 365 plans, standalone options, and on-premises solutions see, [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

