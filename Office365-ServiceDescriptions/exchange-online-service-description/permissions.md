---
title: アクセス許可
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online は、役割ベースのアクセス制御 (RBAC) モデルを使用して、ユーザーおよび IT 従業員がサービスで実施できることを組織の管理者が細かく制御できるようにします。たとえば、コンプライアンス責任者がメールボックス検索の要求を担当する場合、管理者はこの管理機能を RBAC により責任者に委任できます。Exchange Online では、Microsoft Exchange Server 2013 と同じ RBAC フレームワークが使用されます。
ms.openlocfilehash: 03153cfaeaa280eedbb4ab0e16a5cabe3fb1aa9f
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342826"
---
# <a name="permissions"></a>アクセス許可

Microsoft Exchange Online は、役割ベースのアクセス制御 (RBAC) モデルを使用して、ユーザーおよび IT 従業員がサービスで実施できることを組織の管理者が細かく制御できるようにします。たとえば、コンプライアンス責任者がメールボックス検索の要求を担当する場合、管理者はこの管理機能を RBAC により責任者に委任できます。Exchange Online では、Microsoft Exchange Server 2013 と同じ RBAC フレームワークが使用されます。 
  
その最上位では、RBAC は管理役割、管理役割グループ、および管理役割の割り当てポリシーで構成されます。次に、各 RBAC コンポーネントに関する詳細情報を説明します。
  
Exchange Online で使用される RBAC アクセス許可モデルの詳細については、「[アクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271935)」を参照してください。
  
## <a name="role-based-permissions"></a>役割に基づくアクセス許可

Exchange Online では、管理者とユーザーに与えるアクセス許可は管理役割に基づきます。役割は管理者やユーザーが実行できるタスクのセットを定義します。たとえば  `Mail Recipients` と呼ばれる管理役割は、メールボックス、連絡先、および配布グループのセットに対して実行できるタスクを定義します。ある役割が管理者やユーザーに割り当てられる場合、その管理者やユーザーに対して、その役割が提供するアクセス許可が与えられます。 
  
役割には、管理役割とエンドユーザー役割の 2 種類があります。
  
- **管理役割** 管理役割には、Exchange Online 組織の一部 (受信者、サーバー、データベースなど) を管理する役割グループを使用することによって管理者または専門家ユーザーに割り当てることができるアクセス許可が含まれます。 
    
- **エンドユーザーの役割** エンドユーザーの役割は、役割の割り当てポリシーを使用することによって割り当てられ、ユーザーが自分の所有するメールボックスおよび配布グループを部分的に管理できます。エンドユーザーの役割は、  `My` というプレフィックスで始まります。
    
役割は、役割が割り当てられている管理者とユーザーがコマンドレットを使用できるようにすることで、管理者とユーザーにタスクを実行するアクセス許可を付与します。Exchange 管理センター (EAC) および Exchange 管理シェルではコマンドレットを使用して Exchange Online を管理するため、コマンドレットへのアクセスを許可することは、管理者やユーザーに対して Exchange Online の各管理インターフェイスでのタスク実行に必要なアクセス許可を与えることになります。
  
Microsoft Online Services の役割に基づくアクセス許可は、Exchange Online RBAC のアクセス許可と 2 つの点で重複します。まず、Microsoft Online の全体管理者またはサービス管理者であるユーザーは、自動的に Exchange Online で "Organization Management/組織管理" 役割グループに割り当てられます。続いて、Microsoft Online のヘルプ デスク管理者であるユーザーは、自動的に Exchange Online で "Help Desk/ヘルプ デスク" 役割グループに割り当てられます。それ以外の場合は、2 つのセキュリティ モデルが個別に管理されます。
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割は、Exchange Online では使用できません。 
  
Exchange Online でのアクセス許可の詳細については、「[役割に基づくアクセス許可](https://go.microsoft.com/fwlink/p/?LinkId=271936)」を参照してください。
  
## <a name="role-groups"></a>役割グループ

管理役割グループ は、管理役割を管理者または専門家ユーザーのグループに関連付けます。管理者は、広範な Exchange Online 組織または受信者の構成を管理します。専門家ユーザーは、コンプライアンスなど Exchange Online の特定機能を管理します。あるいは、ヘルプ デスク メンバーなど制限された管理機能を持つ場合がありますが、広範な管理権限は付与されません。役割グループは、通常、管理者の管理役割を関連付けて管理者および専門家ユーザーが組織や受信者の構成を管理できるようにします。たとえば、管理者が受信者を管理できるかどうか、またはメールボックス検出機能を使用できるかどうかは、役割グループを使用して制御します。 
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割グループは、Exchange Online では使用できません。 
  
役割グループの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。
  
## <a name="role-assignment-policies"></a>役割の割り当てポリシー

管理役割の割り当てポリシーは、エンドユーザーの管理役割をユーザーに関連付けます。役割の割り当てポリシーは、ユーザーが自分のメールボックスまたは配布グループでできることを制御する役割で構成されます。これらの役割は、ユーザーと直接関連付けられた機能を管理することを許可しません。役割の割り当てポリシーを作成するときに、ユーザーが自分のメールボックスに対して行える操作をすべて定義できます。たとえば、役割の割り当てポリシーを使用すれば、ユーザーに表示名の設定、ボイス メールの設定、および受信トレイ ルールの構成を許可することができます。別の役割の割り当てポリシーでは、ユーザーにアドレスの変更、テキスト メッセージングの使用、および配布グループの設定を許可することができます。管理者を含む Exchange Online メールボックスを持つすべてのユーザーには、既定で役割の割り当てポリシーが与えられています。既定で割り当てるべき役割の割り当てポリシーを決定したり、既定の役割の割り当てポリシーに含むべきものを選択したり、特定のメールボックスに既定値を上書きしたり、既定でいかなる役割の割り当てポリシーも割り当てないようにしたりすることができます。
  
> [!IMPORTANT]
> 内部設置型の Microsoft Exchange Server 2013 で使用できる一部の役割の割り当ては、Exchange Online では使用できません。 
  
役割の割り当てポリシーの詳細については、「[役割グループと役割割り当てポリシー](https://go.microsoft.com/fwlink/p/?LinkId=271937)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

