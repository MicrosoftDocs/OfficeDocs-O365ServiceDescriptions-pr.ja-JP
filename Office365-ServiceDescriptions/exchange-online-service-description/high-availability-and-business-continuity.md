---
title: 高可用性とビジネス継続性
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。これには、データセンターのメールボックスレプリケーションと、削除済みメールボックスおよび削除済みアイテムを復元する機能が含まれます。
ms.openlocfilehash: ec9d598fe2c0af2cc9af9a879c91a99a78baf883
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210230"
---
# <a name="high-availability-and-business-continuity"></a>高可用性とビジネス継続性

Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。これには、データセンターのメールボックスレプリケーションと、削除済みメールボックスおよび削除済みアイテムを復元する機能が含まれます。
  
## <a name="mailbox-replication-at-data-centers"></a>データ センターでのメールボックス レプリケーション

Exchange Online メールボックスは、地理的に分散した Microsoft データ センター内で、複数のデータベース コピーに継続的にレプリケートされ、ローカルのメッセージング インフラストラクチャに障害が発生した場合にデータ復元機能を提供します。大規模な障害の場合、サービス継続性管理手順が開始されます。
  
Microsoft がデータを保護する方法の詳細については、「[Office 365 セキュリティ センター](https://go.microsoft.com/fwlink/p/?LinkId=299135)」をご覧ください。21Vianet が運用している Office 365 をご使用の方は、「[21Vianet セキュリティ センター](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)」をご覧ください。
  
## <a name="deleted-mailbox-recovery"></a>削除済みメールボックスの回復

管理者は、Microsoft 365 管理センターを使用して、対応するユーザーアカウントを削除したり、exchange online ライセンスを削除したり、リモート Windows PowerShell で**メールボックスの削除**コマンドレットを使用して、exchange online メールボックスを削除したりできます。メールボックスが削除されると、Exchange Online は既定でメールボックスとそのコンテンツを30日間保持します。30日後、メールボックスは復元できません。回復されたメールボックスには、削除時に格納されたすべてのデータが含まれています。管理者は、Microsoft 365 管理センターを使用して、保存期間内に削除されたメールボックスを回復できます。削除されたメールボックスを回復するには、管理者は、対応する Office 365 ユーザーアカウントを復元するか、Exchange Online ライセンスをユーザーアカウントに再割り当てする必要があります。詳細については、「 [Exchange Online でユーザーメールボックスを削除または復元](https://go.microsoft.com/fwlink/p/?LinkId=286992)する」を参照してください。
  
## <a name="deleted-item-recovery"></a>削除済みアイテムの回復

Exchange Online では、削除済みアイテム フォルダーを含む電子メール フォルダーから削除したアイテムを回復できます。削除されたアイテムは、ユーザーの削除済みアイテム フォルダーに保持されます。削除済みアイテム フォルダー内のアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、フォルダーに保持されたままになります。管理者は、EAC またはリモート Windows PowerShell を使用して、保持ポリシーをカスタマイズできます。
  
削除済みアイテム フォルダーからアイテムが削除された後、さらに 14 日間は回復可能なアイテム フォルダーに保持され、その後に完全に削除されますが、管理者がリモート Windows PowerShell を使用してこの期間を延長した場合は、最大で 30 日間保持できます。ユーザーはこの期間中に、Outlook Web App または Outlook の削除済みアイテムの復元機能を使用してアイテムを復元できます。詳細については、「[Exchange Online メールボックスの完全に削除したアイテムの保持期間を変更する](https://go.microsoft.com/fwlink/p/?LinkId=286940)」を参照してください。
  
ユーザーが手動で回復可能なアイテム フォルダーからアイテムを削除した場合、管理者は同じ期間内であれば単一アイテムの回復機能とリモート Windows PowerShell を使用してアイテムを復元できます。既定では、メールボックスの作成時に単一アイテムの回復機能は有効になっています。詳細については、「[メールボックスの単一アイテムの回復を有効または無効にする](https://go.microsoft.com/fwlink/p/?LinkID=286941)」を参照してください。
  
30 日より長い間メッセージを回復可能なアイテム フォルダーに保持するには、組織で、電子メールの保存期間を延長するか、時間ベースのインプレース保持を実装します。詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

