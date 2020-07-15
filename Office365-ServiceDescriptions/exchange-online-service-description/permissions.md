---
title: アクセス許可
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132691"
---
# <a name="permissions"></a>アクセス許可

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Exchange Online で使用される RBAC アクセス許可モデルの詳細については、「[アクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271935)」を参照してください。
  
## <a name="role-based-permissions"></a>役割に基づくアクセス許可

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
役割には、管理役割とエンドユーザー役割の 2 種類があります。
  
- **管理役割** 管理役割には、Exchange Online 組織の一部 (受信者、サーバー、データベースなど) を管理する役割グループを使用することによって管理者または専門家ユーザーに割り当てることができるアクセス許可が含まれます。 
    
- **エンドユーザーの役割**これらの役割は、役割の割り当てポリシーを使用して割り当てられ、ユーザーは自分が所有するメールボックスや配布グループの側面を管理できます。 エンドユーザーの役割は、  `My` というプレフィックスで始まります。
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割は、Exchange Online では使用できません。 
  
Exchange Online でのアクセス許可の詳細については、「[役割に基づくアクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271936)」を参照してください。
  
## <a name="role-groups"></a>役割グループ

管理役割グループ は、管理役割を管理者または専門家ユーザーのグループに関連付けます。 管理者は、広範な Exchange Online 組織または受信者構成を管理します。 専門家ユーザーは、コンプライアンスなどの Exchange Online の特定の機能を管理できますが、ヘルプデスクメンバーなどの管理機能が制限されていても、広範な管理権限を持っているわけではありません。 通常、役割グループは、管理者および専門家ユーザーが組織や受信者の構成を管理できる管理管理役割を関連付けます。 たとえば、管理者が受信者を管理したり、メールボックス検出機能を使用したりするかどうかは、役割グループを使用して制御できます。 
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割グループは、Exchange Online では使用できません。 
  
役割グループの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。
  
## <a name="role-assignment-policies"></a>役割の割り当てポリシー

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割の割り当ては、Exchange Online では使用できません。 
  
役割の割り当てポリシーの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

