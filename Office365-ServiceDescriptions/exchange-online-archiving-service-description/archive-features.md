---
title: Exchange Online アーカイブのアーカイブ機能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 次のセクションでは、Microsoft Exchange Online アーカイブのアーカイブ機能について説明します。
ms.openlocfilehash: 8e27ce238fa0aa7e2b670f6d991178c5f595908a
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581403"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online アーカイブのアーカイブ機能

次のセクションでは、Microsoft Exchange Online アーカイブのアーカイブ機能について説明します。
  
## <a name="archive-mailbox"></a>アーカイブ メールボックス

Exchange Online Archiving は、アーカイブ メールボックス機能を使用した高度なアーカイブ機能をユーザーに提供します。 アーカイブメールボックスは、Outlook または web 上の Outlook のユーザーのプライマリメールボックスフォルダーと共に表示される専用のメールボックスです。 ユーザーは、プライマリ メールボックスと同じ方法でアーカイブにアクセスできます。 加えて、アーカイブとプライマリ メールボックスの両方を検索することができます。
  
管理者は、Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用して特定のユーザーのアーカイブ機能を有効にすることができます。詳細については、「[Exchange Online のアーカイブ メールボックスを有効または無効にする](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)」を参照してください。
  
> [!IMPORTANT]
>  アーカイブの目的で、ジャーナリング、トランスポート ルール、または自動転送ルールを使用して Exchange Online Archiving にメッセージをコピーすることは許可されていません。 <br/>
>  ユーザーのアーカイブ メールボックスは、そのユーザー専用です。 Microsoft は、ユーザーのアーカイブ メールボックスを使用して他のユーザーのアーカイブ データを格納する、インスタンスでの無制限アーカイブを拒否する権利を有します。 
  
### <a name="move-messages-to-exchange-online-archiving"></a>Exchange Online Archiving へのメッセージの移動

ユーザーは、メッセージを .pst ファイルからアーカイブにドラッグ アンド ドロップするだけで簡単にオンラインでアクセスできます。 また、アーカイブ ポリシーを使用して電子メール アイテムをプライマリ メールボックスからアーカイブ メールボックスに自動的に移動することによって、プライマリ メールボックスのサイズを削減し、パフォーマンスを向上させることができます。 
  
### <a name="import-data-to-the-archive"></a>アーカイブへのデータのインポート

ユーザーは、以下の方法でアーカイブにデータをインポートできます。
  
- Outlook のインポート/エクスポート ウィザードを使用して .pst ファイルからデータをインポートします。
    
- 電子メール メッセージを .pst ファイルからアーカイブにドラッグします。
    
- 電子メールメッセージをプライマリ メールボックスからアーカイブにドラッグします。
    
- アーカイブ ポリシーを利用して、電子メール メッセージをその保存期間に基づいてプライマリ メールボックスから自動的に移動します。詳細については、「[保持タグおよびアイテム保持ポリシー](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)」を参照してください。
    
> [!NOTE]
> 管理者は、ユーザーのクラウドベースのアーカイブ メールボックスに .pst ファイルをインポートするため Office 365 インポート サービスを使用することもできます。詳細については、「[ネットワーク アップロードを使用して PST ファイルを Office 365 にインストールする](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)」を参照してください。 
  
## <a name="deleted-item-recovery"></a>削除済みアイテムの回復

ユーザーは、アーカイブ内の任意の電子メール フォルダーから削除されたアイテムを復元できます。削除されたアイテムは、アーカイブの [削除済みアイテム] フォルダーに移動されます。このアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、[削除済みアイテム] フォルダーに残ります。
  
アーカイブの [削除済みアイテム] フォルダーからアイテムが削除されると、さらに 14 日間アーカイブの回復可能なアイテム フォルダー内に保存されてから、完全に削除されます。 ユーザーは、Microsoft Outlook または web 上の Outlook の [**削除済みアイテムを復元**する機能を使用してこれらのアイテムを回復できます。 
  
ユーザーが回復可能なアイテム フォルダーからアイテムを手動で削除した場合、管理者は単一アイテムの回復と呼ばれる機能を使って同じ 14 日間の期間内にアイテムを回復できます。管理者は、この機能を使用して、複数のメールボックスを検索して削除されたアイテムを検索してから、 `Search-Mailbox` Windows PowerShell コマンドレットを使用してそれらのアイテムを探索メールボックスからユーザーのメールボックスに移動できます。詳細については、「 [メールボックスの単一アイテムの回復を有効または無効にする](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)」を参照してください。
  
> [!NOTE]
>  既定で、単一アイテムの回復期間は 14 日間ですが、一部の環境ではカスタマイズができます。 <br/>
>  管理者がユーザーのメールボックスをインプレース保持または訴訟ホールドの対象にしている場合、削除されたアイテムは無期限に保持されるため、14日間の期間は適用されません。 
  
## <a name="deleted-mailbox-recovery"></a>削除済みメールボックスの回復

管理者が社内の Exchange Server からユーザーを削除すると、そのユーザーのアーカイブも削除されます。削除されたアーカイブ メールボックスを回復する必要がある場合は、Office 365 サポート チームがこの回復を実行できます。回復されたアーカイブには、削除時点で保存されていたすべてのメールが含まれています。
  
> [!IMPORTANT]
> 管理者は、ユーザーのメールボックスが削除された時点から 30 日間、アーカイブ メールボックスの回復を要求できます。30 日後、アーカイブ メールボックスは回復できなくなります。 
  
## <a name="mailbox-service-redundancy"></a>メールボックス サービスの冗長性

Exchange Online アーカイブのアーカイブメールボックスは、地理的に分散した Microsoft データセンターの複数のデータベースコピーにレプリケートされ、メッセージングインフラストラクチャに障害が発生した場合にデータ復元機能を提供します。 大規模な障害については、ビジネス継続性管理が開始されます。 
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。
  
