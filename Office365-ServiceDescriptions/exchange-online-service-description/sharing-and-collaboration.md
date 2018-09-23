---
title: 共有とコラボレーション
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 13ab2163b76b5ccc4732659a64be5fcead01dc9d
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036254"
---
# <a name="sharing-and-collaboration"></a><span data-ttu-id="d2ce6-102">共有とコラボレーション</span><span class="sxs-lookup"><span data-stu-id="d2ce6-102">Sharing and Collaboration</span></span>

## <a name="federated-sharing"></a><span data-ttu-id="d2ce6-103">フェデレーションの共有</span><span class="sxs-lookup"><span data-stu-id="d2ce6-103">Federated sharing</span></span>

<span data-ttu-id="d2ce6-p101">フェデレーションとは、フェデレーション共有をサポートする、基盤となる信頼インフラストラクチャを指します。フェデレーションは、Microsoft Exchange Online ユーザーが外部のフェデレーションされた組織の受信者、またはインターネット アクセスがあるユーザーと空き時間予定表データと連絡先情報を共有する方法です。これらには、Exchange Online によりホストされる組織、外部の Microsoft Exchange Server 2010 または Exchange Server 2013 組織が含まれます。組織の関係と共有ポリシーを使用することにより、Exchange Online 管理者は、Microsoft Outlook Web App または Microsoft Outlook 2010 以降からユーザーが予定表共有のお知らせを送信できるように設定できます。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p101">Federation refers to the underlying trust infrastructure that supports federated sharing, a method for Microsoft Exchange Online users to share free/busy calendar data and contact information with recipients in other external federated organizations or with users that have Internet access. These include organizations that are also hosted by Exchange Online, or external Microsoft Exchange Server 2010 or Exchange Server 2013 organizations. Using organization relationships and sharing policies, Exchange Online administrators can enable users to send calendar-sharing invitations from Microsoft Outlook Web App or Microsoft Outlook 2010 or later.</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="d2ce6-p102">外部の Exchange 2010 および Exchange 2013 組織は、フェデレーション共有の構成の一環として、Microsoft Federation Gateway でフェデレーションの信頼を構成する必要があります。Exchange Online 組織はフェデレーションの信頼を構成する必要はありません。Office 365 テナントの作成時に、Microsoft Federation Gateway でフェデレーションの信頼が作成されるためです。 >  Exchange Online 組織は、フェデレーション共有を有効にするため、組織の関係、または共有ポリシーのいずれかを構成する必要があります。 >  フェデレーション共有では、異なる Office 365 テナントの Exchange Online 組織間でグローバル アドレス一覧 (GAL) を共有したり、ユーザー メールボックスを移動することはサポートされません。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p102">External Exchange 2010 and Exchange 2013 organizations must configure a federation trust with the Microsoft Federation Gateway as part of configuring federated sharing. Exchange Online organizations don't have to configure a federation trust—the federation trust with the Microsoft Federation Gateway is automatically created when the Office 365 tenant is created. >  Exchange Online organizations must configure either an organization relationship or a sharing policy to enable federated sharing. >  Sharing of the global access list (GAL) or moving user mailboxes between Exchange Online organizations in different Office 365 tenants is not supported in federated sharing.</span></span> 
  
<span data-ttu-id="d2ce6-111">フェデレーション共有の詳細については、「[Exchange Online での共有](https://go.microsoft.com/fwlink/p/?LinkId=271774)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-111">For more information about federated sharing, see [Sharing in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).</span></span>
  
## <a name="site-mailboxes"></a><span data-ttu-id="d2ce6-112">サイト メールボックス</span><span class="sxs-lookup"><span data-stu-id="d2ce6-112">Site mailboxes</span></span>

<span data-ttu-id="d2ce6-p103">電子メールとドキュメントは、従来から 2 つの固有で別個のデータ リポジトリに保持されています。チームの多くは、電子メールとドキュメントの両方を使用して共同作業します。課題は、電子メールとドキュメントが異なるクライアントでアクセスされることです。そのため、通常は、ユーザーの生産性が低下し、ユーザー エクスペリエンスの質が低下します。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p103">Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.</span></span>
  
<span data-ttu-id="d2ce6-p104">サイト メールボックスは、この問題を解消しようとする Exchange 2013 の新しいコンセプトです。サイト メールボックスでは、同じクライアント インターフェイスを使用して Microsoft SharePoint 2013 ドキュメントと Exchange 電子メールの両方にアクセスできるようにすることで、コラボレーションとユーザーの生産性を向上します。サイト メールボックスの機能は、SharePoint 2013 サイト メンバーシップ (所有者とメンバー)、共有ストレージ (電子メール メッセージのための Exchange 2013 メールボックスとドキュメントのための SharePoint 2013 サイト)、およびプロビジョニングとライフサイクル ニーズに対応する管理インターフェイスから構成されます。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p104">The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d2ce6-p105">Office 365 のプランは SharePoint を含む必要があります。サイト メールボックスでは、ユーザーは SharePoint と Exchange の両方のライセンスを必要とします。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p105">Your Office 365 plan must include SharePoint. Site mailboxes require that users have both SharePoint and Exchange licenses.</span></span> 
  
<span data-ttu-id="d2ce6-122">サイト メールボックスの詳細については、「[Exchange Online でのコラボレーション](https://go.microsoft.com/fwlink/p/?LinkId=271789)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-122">For more information about site mailboxes, see [Site Mailboxes](https://go.microsoft.com/fwlink/p/?LinkId=271789).</span></span>
  
## <a name="public-folders"></a><span data-ttu-id="d2ce6-123">パブリック フォルダー</span><span class="sxs-lookup"><span data-stu-id="d2ce6-123">Public folders</span></span>

<span data-ttu-id="d2ce6-p106">オンライン Exchange 内のパブリック フォルダーは、メールボックス データベースの既存高可用性とストレージ ・ テクノロジーを活用するのには modernized されています。パブリック フォルダーのアーキテクチャでは、階層とパブリック フォルダーのコンテンツの両方を格納するのに特別に設計されたメールボックスを使用します。これは、別のパブリック フォルダー データベースが既にあることを意味します。パブリック フォルダーのレプリケーションを今すぐには、継続的なレプリケーション モデルが使用されます。階層とコンテンツのメールボックスの高可用性は、データ ・ センター内のデータベース可用性グループ (DAG) によって提供されます。Exchange online では、1000 個のパブリック フォルダーのメールボックスに制限しています。各パブリック フォルダーのメールボックスには、最大記憶域サイズもあります。詳細については、 [Exchange オンラインの制限](exchange-online-limits.md)で「メールボックス フォルダーの制限」セクションを参照してください。パブリック フォルダーのメールボックス メールボックスが通常と同じメッセージ、受信者、および警告の処理能力の限界であります。詳細については、[受信者](recipients.md)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p106">Public folders in Exchange Online have been modernized to take advantage of the existing high availability and storage technologies of the mailbox database. The public folder architecture uses specially designed mailboxes to store both the hierarchy and the public folder content. This means that there's no longer a separate public folder database. Public folder replication now uses the continuous replication model. High availability for the hierarchy and content mailboxes is provided by a database availability group (DAG) in the data center. In Exchange Online, you are limited to 1000 public folder mailboxes. Each public folder mailbox also has a maximum storage size. For more information, see the "Mailbox folder limits" section in [Exchange Online Limits](exchange-online-limits.md). Public folder mailboxes have the same message, recipient, and capacity alert limits as regular mailboxes. For more information, see [Recipients](recipients.md).</span></span> 
  
<span data-ttu-id="d2ce6-134">パブリック フォルダーの詳細については、「[Office 365 と Exchange Online のパブリック フォルダー](https://go.microsoft.com/fwlink/p/?LinkId=271790)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-134">For more information about public folders, see [Public Folders](https://go.microsoft.com/fwlink/p/?LinkId=271790).</span></span>
  
## <a name="group-and-shared-mailboxes"></a><span data-ttu-id="d2ce6-135">グループ メールボックスと共有メールボックス</span><span class="sxs-lookup"><span data-stu-id="d2ce6-135">Group and Shared mailboxes</span></span>

<span data-ttu-id="d2ce6-p107">グループ メールボックスと共有メールボックスを使用すると、特定のグループのユーザーによるパブリック電子メール アドレスのような共通のアカウント (info@contoso.com、contact@contoso.com など) からの電子メールの送信、およびこれらの電子メールの監視が容易になります。グループ内のユーザーが共有メールボックスに送信されたメッセージに返信すると、その電子メールは個人ユーザーからではなく、共有メールボックスから送信された電子メールとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p107">Group and Shared mailboxes make it easy for a specific group of people to monitor and send email from a common account, like public email addresses (for example, info@contoso.com or contact@contoso.com). When a person in the group replies to a message sent to the Shared mailbox, the email appears to be from the Shared mailbox, not from the individual user.</span></span>
  
<span data-ttu-id="d2ce6-p108">通常、グループ メールボックスまたは共有メールボックスの使用には、特別なユーザー ライセンスは必要ありません。ただし、グループ メールボックスまたは共有メールボックスでインプレース アーカイブを有効にするには、Exchange Online プラン 1 または Exchange Online プラン 2 ライセンスを割り当てる必要があります。ライセンスが割り当てられると、メールボックスのサイズは、ライセンスで許可されたサイズまで増加します。共有メールボックスをインプレース ホールドに入れるには、Exchange Online プラン 2 ライセンスを割り当てる必要があります。現時点で、グループ メールボックスは割り当てることができませんが、総ライセンス数にはカウントされる点にご注意ください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p108">Typically, Group or Shared mailboxes don't require a separate user license. However, To enable In-Place Archive for a Group or Shared mailbox, you must assign an Exchange Online Plan 1 or Exchange Online Plan 2 license to it. After the license is assigned, the mailbox size increases to that of the licensed plan. To put a Shared mailbox on In-Place Hold, you must assign an Exchange Online Plan 2 license to it. Please note that Group mailboxes cannot be assigned at this time but should be accounted for in your total licenses.</span></span>
  
<span data-ttu-id="d2ce6-p109">インプレース アーカイブは、ライセンスが適用された単一のユーザーまたはエンティティ (共有メールボックスなど) のメールをアーカイブする場合にのみ使用できます。複数のユーザーまたはエンティティからのメールを格納する方法として、インプレース アーカイブを使用することは禁止されています。たとえば、IT 管理者が共有メールボックスを作成して、アーカイブという明確な目的のために、ユーザーに (CC フィールドまたは BCC フィールドを通して、あるいは、トランスポート ルールを介して) それをコピーさせることはできません。複数のユーザーが使用する共有メールボックスは、実際には個々のユーザーの電子メールを保存しないことに注意してください。複数のユーザーがアクセスでき、共有メールボックスとしてメールを送信します。このため、共有メールボックスに保存されているメールだけが、共有メールボックスとして送受信されるメールです。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-p109">In-Place Archive can only be used to archive mail for a single user or entity (such as a Shared mailbox) for which a license has been applied. Using an In-Place Archive as a means of storing mail from multiple users or entities is prohibited. For example, an IT administrator can't create a Shared mailbox and have users copy it (through the Cc or Bcc field, or through a transport rule) for the explicit purpose of archiving. Note that a Shared mailbox that multiple people use does not actually store email for those individual users. Multiple users have access, and they send email as the Shared mailbox. Therefore, the only emails stored in the Shared mailbox are those sent to or from it, as the Shared mailbox.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d2ce6-149">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="d2ce6-149">Feature Availability</span></span>

<span data-ttu-id="d2ce6-150">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d2ce6-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

