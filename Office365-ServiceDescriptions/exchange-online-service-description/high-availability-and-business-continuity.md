---
title: 高可用性とビジネス継続性
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Onlineの電子メール インフラストラクチャに対する広範な保持と回復のサポートを提供します。 これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。
ms.openlocfilehash: 5415499e85d0e6fb0334e2e23abc435d0df9d2ab
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653339"
---
# <a name="high-availability-and-business-continuity"></a>高可用性とビジネス継続性

Microsoft Exchange Onlineの電子メール インフラストラクチャに対する広範な保持と回復のサポートを提供します。 これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。
  
## <a name="mailbox-replication-at-data-centers"></a>データ センターでのメールボックス レプリケーション

Exchange Online メールボックスは、地理的に分散した Microsoft データ センター内で、複数のデータベース コピーに継続的にレプリケートされ、ローカルのメッセージング インフラストラクチャに障害が発生した場合にデータ復元機能を提供します。大規模な障害の場合、サービス継続性管理手順が開始されます。
  
Microsoft がデータを保護する方法の詳細については、「[Office 365 セキュリティ センター](https://go.microsoft.com/fwlink/p/?LinkId=299135)」をご覧ください。21Vianet が運用している Office 365 をご使用の方は、「[21Vianet セキュリティ センター](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)」をご覧ください。
  
## <a name="deleted-mailbox-recovery"></a>削除済みメールボックスの回復

管理者は、Microsoft 365 管理センターを使用して、対応するユーザー アカウントを削除するか、Exchange Online ライセンスを削除するか、リモート Windows PowerShell で **Remove-Mailbox** コマンドレットを使用して Exchange Online メールボックスを削除できます。 メールボックスが削除されると、Exchange Online がメールボックスとその内容を既定で 30 日間保持します。 30 日後、メールボックスは回復不可能になります。 回復したメールボックスには、削除された時点でメールボックスに格納されていたすべてのデータが含まれます。 管理者は、Microsoft 365 管理センターを使用して、保持期間中に削除されたメールボックスを回復できます。 削除されたメールボックスを回復するには、管理者が対応するユーザー アカウントを復元するか、Exchange Online ライセンスをユーザー アカウントに再割り当てする必要があります。 詳細については、「 [Exchange Online でユーザー メールボックスを削除または復元する](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes)」を参照してください。
  
## <a name="deleted-item-recovery"></a>削除済みアイテムの回復

Exchange Online を使用すると、削除済みアイテム フォルダーを含む任意のメール フォルダーから削除したアイテムを復元できます。 削除されたアイテムは、ユーザーの削除済みアイテム フォルダーに保持されます。 削除済みアイテム フォルダー内のアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、フォルダーに保持されたままになります。 管理者は、EAC またはリモート Windows PowerShell を使用して、保持ポリシーをカスタマイズできます。
  
削除済みアイテム フォルダーからアイテムが削除された後、さらに 14 日間は回復可能なアイテム フォルダーに保持され、その後に完全に削除されますが、管理者がリモート Windows PowerShell を使用してこの期間を延長した場合は、最大で 30 日間保持できます。 ユーザーは、Outlook on the web または Outlook の [削除済みアイテムの回復] 機能を使用して、この期間中にアイテムを回復できます。 詳細については、「[Exchange Online メールボックスの完全に削除したアイテムの保持期間を変更する](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention)」を参照してください。
  
ユーザーが手動で回復可能なアイテム フォルダーからアイテムを削除した場合、管理者は同じ期間内であれば単一アイテムの回復機能とリモート Windows PowerShell を使用してアイテムを復元できます。既定では、メールボックスの作成時に単一アイテムの回復機能は有効になっています。詳細については、「[メールボックスの単一アイテムの回復を有効または無効にする](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery)」を参照してください。
  
30 日より長い間メッセージを回復可能なアイテム フォルダーに保持するには、組織で、電子メールの保存期間を延長するか、時間ベースのインプレース保持を実装します。詳細については、「[インプレース保持と訴訟ホールド](/exchange/security-and-compliance/in-place-and-litigation-holds)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。
