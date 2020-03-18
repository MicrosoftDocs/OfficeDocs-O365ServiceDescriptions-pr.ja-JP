---
title: 受信者、ドメイン、および会社の管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) は、受信者、ドメイン、および会社の情報を管理するためのいくつかの手段を提供します。 管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365 管理センターで実行されたその他の管理タスクを確認できます。
ms.openlocfilehash: 1183a90754edc2bab698fb4d8d8b97acff90370c
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2020
ms.locfileid: "42688073"
---
# <a name="recipient-domain-and-company-management"></a>受信者、ドメイン、および会社の管理

Microsoft Exchange Online Protection (EOP) は、受信者、ドメイン、および会社の情報を管理するためのいくつかの手段を提供します。 管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365 管理センターで実行されたその他の管理タスクを確認できます。
  
すべての EOP 機能に関する情報をお探しですか? 「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="mail-recipients"></a>Mail recipients

メールの受信者は、メール ユーザーまたはメール グループに分類され、ディレクトリ同期によって管理することも、EAC またはリモート Windows PowerShell で直接管理することもできます。 社内で受信者を管理している場合は、ディレクトリ同期を実行してメール受信者を EAC に反映させる必要があります。 Microsoft 365 管理センターだけで管理されているユーザーは、EAC では表示できませんが、EAC の管理者の役割グループのメンバーシップに追加または削除することができます。 EOP の受信者の詳細については、「[EOP で受信者を管理する](https://go.microsoft.com/fwlink/p/?LinkId=280011)」を参照してください。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

EOP では、管理役割の構成のみが可能です。EAC では、既定の管理役割グループに対してユーザーを直接、追加または削除できます。RBAC のカスタマイズはできません。詳細については、「[EOP で管理役割グループのアクセス許可を管理する](https://go.microsoft.com/fwlink/p/?LinkId=282238)」を参照してください。
  
## <a name="domain-management"></a>Domain management

管理対象ドメインは、EOP によって保護されているドメインです。 EAC では、管理対象ドメインの表示とドメインの種類の編集ができます。 ドメインのプロビジョニングと管理は、Microsoft 365 管理センターで行われ、変更が EAC に反映されます。 詳細については、「[EOP で承認済みドメインを管理する](https://go.microsoft.com/fwlink/p/?LinkId=282239)」を参照してください。
  
## <a name="match-subdomains"></a>一致サブドメイン

EOP では、管理対象ドメインのサブドメインへのメール フローを有効にできます。詳細については、「[EOP でサブドメインの電子メール フローを有効にする](https://go.microsoft.com/fwlink/p/?LinkId=397213)」を参照してください。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)

ディレクトリ ベースのエッジ ブロック機能では、サービス ネットワーク境界で無効な受信者宛てのメッセージを拒否することができます。管理者は DBEB を使用することにより、メールが有効な受信者を Office 365 に追加したり、Office 365 内に存在しない電子メール アドレスに送信されたすべてのメッセージをブロックしたりすることができます。メッセージの送信先が Office 365 内に存在する有効なメール アドレスの場合、そのメッセージはサービスの残りのフィルター層 (マルウェア対策、スパム対策、トランスポート ルールなど) を通ります。宛先のアドレスが存在しない場合、メッセージはフィルターを適用する前にブロックされ、送信者には、メッセージが配信されなかったことを通知する配信不能レポート (NDR) が送信されます。 
  
DBEB を有効にするには、ユーザーおよびドメインの構成が必要です。詳細については、「[ディレクトリ ベースのエッジ ブロックを使用して無効な受信者に送信されたメッセージを拒否する](https://go.microsoft.com/fwlink/p/?LinkId=390676)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
