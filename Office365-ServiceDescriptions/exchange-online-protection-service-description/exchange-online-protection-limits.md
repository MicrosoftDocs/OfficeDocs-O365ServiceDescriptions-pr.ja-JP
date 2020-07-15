---
title: Exchange Online Protection の制限
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: 現在、Exchange Online Protection には次の制限があります。 これらの制限は、特に指定がない限り構成できません。
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133011"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection の制限

現在、Exchange Online Protection には次の制限があります。 これらの制限は、特に指定がない限り構成できません。 
  
> [!TIP]
> Exchange Online の制限の詳細については、「 [Exchange online の制限](../exchange-online-service-description/exchange-online-limits.md)」を参照してください。 トランスポート ルールの制限は、EOP スタンドアロンのお客様にも適用されます。 Exchange Online の受信者レートやメッセージ レートの制限は、EOP スタンドアロンのお客様には適用されません。 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **メッセージ サイズの制限** EOP スタンドアロンのお客様の最大メッセージ サイズは、添付ファイルを含めて 150 MB です。 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **IP 許可一覧または IP 禁止一覧の制限** 接続フィルターの IP 許可一覧または IP 禁止一覧を構成するとき、最大で 1,273 個のエントリを指定できます (エントリは、単一の IP アドレス、または /24 ～ /32 までの CIDR レンジの IP アドレスです)。 
    
- **メッセージ遅延の制限**延期されたメッセージは、24時間キューに残ります。 メッセージの再送信は、受信者のメールシステムから返されたエラーの種類に基づいて行われます。 15 分ごとにメッセージの送信が再試行されます。 
    
- **スパム検疫の保存期間**既定では、検疫に送信されたスパムメッセージは30日間保持されます。 管理者は、コンテンツ フィルター ポリシーによってこの値を下げることができます。 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **レポート作成とメッセージ追跡の制限**レポート作成とメッセージ追跡の制限については、「Reporting and message trace [In Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248)」の「レポート作成およびメッセージ追跡データの可用性と遅延」セクションを参照してください。
    
### <a name="limits-across-eop-options"></a>各 EOP オプションでの制限

|**機能**|****EOP スタンドアロン****|****EOP 機能Exchange Online****|****Exchange Enterprise CAL (サービス付き)****|
|:-----|:-----|:-----|:-----|
|ドメインの制限  <br/> |900  <br/> |900  <br/> |900  <br/> |
|メッセージ サイズの制限 (添付ファイルを含む)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|受信者の制限  <br/> |上記の "受信者の制限" を参照  <br/> |ホストされているメールボックスから送信する場合は、500 人の受信者。その他のシナリオについては、上記の "受信者の制限" を参照  <br/> |上記の "受信者の制限" を参照  <br/> |
|差出人セーフ リストの制限  <br/> |1024 エントリ  <br/> |1024 エントリ  <br/> ||
|ポリシーあたりの受信拒否リストの制限  <br/> |1024 エントリ  <br/> |1024 エントリ  <br/> ||
|IP 許可一覧または IP 禁止一覧の制限  <br/> |1,273 エントリ  <br/> |1,273 エントリ  <br/> |1,273 エントリ  <br/> |
|保留状態のメッセージの制限  <br/> |1日、15分ごとに再試行  <br/> |1日、15分ごとに再試行  <br/> |1日、15分ごとに再試行  <br/> |
|スパム検疫の保存期間  <br/> |既定では30日間ですが、下げることができます  <br/> |既定では30日間ですが、下げることができます  <br/> |既定では30日間ですが、下げることができます  <br/> |
|エンドユーザー スパム検疫通知  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |
   

