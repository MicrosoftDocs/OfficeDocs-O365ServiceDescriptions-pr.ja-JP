---
title: 受信者、ドメイン、および会社の管理 (Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: この記事では、受信者、ドメイン、および企業の管理について、Microsoft Exchange Onlineを参照してください。
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652999"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>受信者、ドメイン、および会社の管理 (Exchange Online Protection

Microsoft Exchange Online保護 (EOP) は、受信者、ドメイン、および会社情報を管理するためのいくつかの手段を提供します。 管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365管理センターで実行されるその他の管理タスクを確認できます。
  
すべての EOP 機能に関する情報をお探しですか? サービスのExchange Online Protection[を参照してください](exchange-online-protection-service-description.md)。
  
## <a name="mail-recipients"></a>Mail recipients

メールの受信者は、メール ユーザーまたはメール グループに分類され、ディレクトリ同期によって管理することも、EAC またはリモート Windows PowerShell で直接管理することもできます。 社内で受信者を管理している場合は、ディレクトリ同期を実行してメール受信者を EAC に反映させる必要があります。 Microsoft 365 管理センターでのみ管理されているユーザーは、EAC では表示できませんが、EAC の管理者役割グループのメンバーシップに追加または削除できます。 EOP の受信者の詳細については、「[EOP で受信者を管理する](/microsoft-365/security/office-365-security/manage-recipients-in-eop)」を参照してください。
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

EOP では、管理役割の構成のみが可能です。EAC では、既定の管理役割グループに対してユーザーを直接、追加または削除できます。RBAC のカスタマイズはできません。詳細については、「[EOP で管理役割グループのアクセス許可を管理する](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)」を参照してください。
  
## <a name="domain-management"></a>Domain management

管理対象ドメインは、EOP によって保護されているドメインです。 EAC では、管理対象ドメインの表示とドメインの種類の編集ができます。 ドメインのプロビジョニングと管理は、管理センター Microsoft 365で行われます。変更は EAC に反映されます。 詳細については、「[EOP で承認済みドメインを管理する](/microsoft-365/security/office-365-security/exchange-online-protection-overview)」を参照してください。
  
## <a name="match-subdomains"></a>一致サブドメイン

EOP では、管理対象ドメインのサブドメインへのメール フローを有効にできます。詳細については、「[EOP でサブドメインの電子メール フローを有効にする](/microsoft-365/security/office-365-security/mail-flow-in-eop)」を参照してください。 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)

ディレクトリ ベースのエッジ ブロック機能では、サービス ネットワーク境界で無効な受信者宛てのメッセージを拒否することができます。 DBEB を使用すると、管理者はメールが有効な受信者を Microsoft に追加し、Microsoft に存在しない電子メール アドレスに送信されるメッセージをブロックできます。 メッセージが Microsoft に存在する有効な電子メール アドレスに送信された場合、メッセージはサービス フィルターレイヤーの残りの部分 (マルウェア対策、スパム対策、トランスポート ルール) を通じて続行されます。 宛先のアドレスが存在しない場合、メッセージはフィルターを適用する前にブロックされ、送信者には、メッセージが配信されなかったことを通知する配信不能レポート (NDR) が送信されます。 
  
DBEB を有効にするには、ユーザーおよびドメインの構成が必要です。詳細については、「[ディレクトリ ベースのエッジ ブロックを使用して無効な受信者に送信されたメッセージを拒否する](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、およびオンプレミス ソリューション全体で機能の可用性を表示するには、「サービスの説明Exchange Online Protection[参照してください](exchange-online-protection-service-description.md)。