---
title: アクセス許可
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online は、役割ベースのアクセス制御 (RBAC) モデルを使用して、ユーザーおよび IT 従業員がサービスで実施できることを組織の管理者が細かく制御できるようにします。たとえば、コンプライアンス責任者がメールボックス検索の要求を担当する場合、管理者はこの管理機能を RBAC により責任者に委任できます。Exchange Online では、Microsoft Exchange Server 2013 と同じ RBAC フレームワークが使用されます。
ms.openlocfilehash: 037a92123c67e313f4db93835be6355bbd829efc
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036300"
---
# <a name="permissions"></a><span data-ttu-id="f78a3-105">アクセス許可</span><span class="sxs-lookup"><span data-stu-id="f78a3-105">Permissions</span></span>

<span data-ttu-id="f78a3-p102">Microsoft Exchange Online は、役割ベースのアクセス制御 (RBAC) モデルを使用して、ユーザーおよび IT 従業員がサービスで実施できることを組織の管理者が細かく制御できるようにします。たとえば、コンプライアンス責任者がメールボックス検索の要求を担当する場合、管理者はこの管理機能を RBAC により責任者に委任できます。Exchange Online では、Microsoft Exchange Server 2013 と同じ RBAC フレームワークが使用されます。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p102">Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.</span></span> 
  
<span data-ttu-id="f78a3-p103">その最上位では、RBAC は管理役割、管理役割グループ、および管理役割の割り当てポリシーで構成されます。次に、各 RBAC コンポーネントに関する詳細情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p103">At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.</span></span>
  
<span data-ttu-id="f78a3-111">Exchange Online で使用される RBAC アクセス許可モデルの詳細については、「[アクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271935)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f78a3-111">For more information about the RBAC permissions model that's used in Exchange Online, see [Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271935).</span></span>
  
## <a name="role-based-permissions"></a><span data-ttu-id="f78a3-112">役割に基づくアクセス許可</span><span class="sxs-lookup"><span data-stu-id="f78a3-112">Role-Based permissions</span></span>

<span data-ttu-id="f78a3-p104">Exchange Online では、管理者とユーザーに与えるアクセス許可は管理役割に基づきます。役割は管理者やユーザーが実行できるタスクのセットを定義します。たとえば  `Mail Recipients` と呼ばれる管理役割は、メールボックス、連絡先、および配布グループのセットに対して実行できるタスクを定義します。ある役割が管理者やユーザーに割り当てられる場合、その管理者やユーザーに対して、その役割が提供するアクセス許可が与えられます。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p104">In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role.</span></span> 
  
<span data-ttu-id="f78a3-117">役割には、管理役割とエンドユーザー役割の 2 種類があります。</span><span class="sxs-lookup"><span data-stu-id="f78a3-117">There are two types of roles, administrative roles and end-user roles:</span></span>
  
- <span data-ttu-id="f78a3-118">**管理役割** 管理役割には、Exchange Online 組織の一部 (受信者、サーバー、データベースなど) を管理する役割グループを使用することによって管理者または専門家ユーザーに割り当てることができるアクセス許可が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f78a3-118">**Administrative roles** These roles contain permissions that can be assigned to administrators or specialist users by using role groups that manage a part of the Exchange Online organization, such as recipients, servers, or databases.</span></span> 
    
- <span data-ttu-id="f78a3-p105">**エンドユーザーの役割** エンドユーザーの役割は、役割の割り当てポリシーを使用することによって割り当てられ、ユーザーが自分の所有するメールボックスおよび配布グループを部分的に管理できます。エンドユーザーの役割は、  `My` というプレフィックスで始まります。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p105">**End-user roles** These roles, assigned by using role assignment policies, enable users to manage aspects of their own mailboxes and distribution groups that they own. End-user roles begin with the prefix  `My`.</span></span>
    
<span data-ttu-id="f78a3-p106">役割は、役割が割り当てられている管理者とユーザーがコマンドレットを使用できるようにすることで、管理者とユーザーにタスクを実行するアクセス許可を付与します。Exchange 管理センター (EAC) および Exchange 管理シェルではコマンドレットを使用して Exchange Online を管理するため、コマンドレットへのアクセスを許可することは、管理者やユーザーに対して Exchange Online の各管理インターフェイスでのタスク実行に必要なアクセス許可を与えることになります。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p106">Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.</span></span>
  
<span data-ttu-id="f78a3-p107">Microsoft Online Services の役割に基づくアクセス許可は、Exchange Online RBAC のアクセス許可と 2 つの点で重複します。まず、Microsoft Online の全体管理者またはサービス管理者であるユーザーは、自動的に Exchange Online で "Organization Management/組織管理" 役割グループに割り当てられます。続いて、Microsoft Online のヘルプ デスク管理者であるユーザーは、自動的に Exchange Online で "Help Desk/ヘルプ デスク" 役割グループに割り当てられます。それ以外の場合は、2 つのセキュリティ モデルが個別に管理されます。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p107">The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f78a3-127">内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割は、Exchange Online では使用できません。</span><span class="sxs-lookup"><span data-stu-id="f78a3-127">Some roles available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="f78a3-128">Exchange Online でのアクセス許可の詳細については、「[役割に基づくアクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271936)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f78a3-128">For more information about permissions in Exchange Online, see [Role-Based Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271936).</span></span>
  
## <a name="role-groups"></a><span data-ttu-id="f78a3-129">役割グループ</span><span class="sxs-lookup"><span data-stu-id="f78a3-129">Role groups</span></span>

<span data-ttu-id="f78a3-p108">管理役割グループ は、管理役割を管理者または専門家ユーザーのグループに関連付けます。管理者は、広範な Exchange Online 組織または受信者の構成を管理します。専門家ユーザーは、コンプライアンスなど Exchange Online の特定機能を管理します。あるいは、ヘルプ デスク メンバーなど制限された管理機能を持つ場合がありますが、広範な管理権限は付与されません。役割グループは、通常、管理者の管理役割を関連付けて管理者および専門家ユーザーが組織や受信者の構成を管理できるようにします。たとえば、管理者が受信者を管理できるかどうか、またはメールボックス検出機能を使用できるかどうかは、役割グループを使用して制御します。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p108">Management role groups associate management roles to a group of administrators or specialist users. Administrators manage a broad Exchange Online organization or recipient configuration. Specialist users manage the specific features of Exchange Online, such as compliance, or they may have limited management abilities, such as Help desk members, but aren't given broad administrative rights. Role groups typically associate administrative management roles that enable administrators and specialist users to manage the configuration of their organization and recipients. For example, whether administrators can manage recipients or use mailbox discovery features is controlled by using role groups.</span></span> 
  
> [!IMPORTANT]
> <span data-ttu-id="f78a3-135">内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割グループは、Exchange Online では使用できません。</span><span class="sxs-lookup"><span data-stu-id="f78a3-135">Some role groups available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="f78a3-136">役割グループの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f78a3-136">For more information about role groups, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="role-assignment-policies"></a><span data-ttu-id="f78a3-137">役割の割り当てポリシー</span><span class="sxs-lookup"><span data-stu-id="f78a3-137">Role assignment policies</span></span>

<span data-ttu-id="f78a3-p109">管理役割の割り当てポリシーは、エンドユーザーの管理役割をユーザーに関連付けます。役割の割り当てポリシーは、ユーザーが自分のメールボックスまたは配布グループでできることを制御する役割で構成されます。これらの役割は、ユーザーと直接関連付けられた機能を管理することを許可しません。役割の割り当てポリシーを作成するときに、ユーザーが自分のメールボックスに対して行える操作をすべて定義できます。たとえば、役割の割り当てポリシーを使用すれば、ユーザーに表示名の設定、ボイス メールの設定、および受信トレイ ルールの構成を許可することができます。別の役割の割り当てポリシーでは、ユーザーにアドレスの変更、テキスト メッセージングの使用、および配布グループの設定を許可することができます。管理者を含む Exchange Online メールボックスを持つすべてのユーザーには、既定で役割の割り当てポリシーが与えられています。既定で割り当てるべき役割の割り当てポリシーを決定したり、既定の役割の割り当てポリシーに含むべきものを選択したり、特定のメールボックスに既定値を上書きしたり、既定でいかなる役割の割り当てポリシーも割り当てないようにしたりすることができます。</span><span class="sxs-lookup"><span data-stu-id="f78a3-p109">Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f78a3-146">内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割の割り当ては、Exchange Online では使用できません。</span><span class="sxs-lookup"><span data-stu-id="f78a3-146">Some role assignments available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="f78a3-147">役割の割り当てポリシーの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f78a3-147">For more information about role assignment policies, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f78a3-148">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="f78a3-148">Feature Availability</span></span>

<span data-ttu-id="f78a3-149">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f78a3-149">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
