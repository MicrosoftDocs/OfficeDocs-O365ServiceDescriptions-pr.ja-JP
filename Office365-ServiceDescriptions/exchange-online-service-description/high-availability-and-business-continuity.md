---
title: 高可用性とビジネス継続性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。 これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131971"
---
# <a name="high-availability-and-business-continuity"></a>高可用性とビジネス継続性

Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。 これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。
  
## <a name="mailbox-replication-at-data-centers"></a>データ センターでのメールボックス レプリケーション

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>削除済みメールボックスの回復

管理者は、Microsoft 365 管理センターを使用して、対応するユーザーアカウントを削除したり、Exchange Online ライセンスを削除したり、リモート Windows PowerShell で**メールボックスの削除**コマンドレットを使用して、exchange online メールボックスを削除したりできます。 メールボックスが削除されると、Exchange Online がメールボックスとその内容を既定で 30 日間保持します。 30 日後、メールボックスは回復不可能になります。 回復したメールボックスには、削除された時点でメールボックスに格納されていたすべてのデータが含まれます。 管理者は、Microsoft 365 管理センターを使用して、保存期間内に削除されたメールボックスを回復できます。 削除されたメールボックスを回復するには、管理者は対応するユーザーアカウントを復元するか、Exchange Online ライセンスをユーザーアカウントに再割り当てする必要があります。 詳細については、「 [Exchange Online でユーザー メールボックスを削除または復元する](https://go.microsoft.com/fwlink/p/?LinkId=286992)」を参照してください。
  
## <a name="deleted-item-recovery"></a>削除済みアイテムの回復

Exchange Online では、ユーザーは削除済みアイテムフォルダーを含むすべての電子メールフォルダーから削除されたアイテムを復元できます。 削除されたアイテムは、ユーザーの削除済みアイテム フォルダーに保持されます。 削除済みアイテム フォルダー内のアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、フォルダーに保持されたままになります。 管理者は、EAC またはリモート Windows PowerShell を使用して、保持ポリシーをカスタマイズできます。
  
削除済みアイテム フォルダーからアイテムが削除された後、さらに 14 日間は回復可能なアイテム フォルダーに保持され、その後に完全に削除されますが、管理者がリモート Windows PowerShell を使用してこの期間を延長した場合は、最大で 30 日間保持できます。 ユーザーは、web 上または Outlook 上の Outlook の削除済みアイテムの回復機能を使用して、この期間にアイテムを復元できます。 詳細については、「[Exchange Online メールボックスの完全に削除したアイテムの保持期間を変更する](https://go.microsoft.com/fwlink/p/?LinkId=286940)」を参照してください。
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  