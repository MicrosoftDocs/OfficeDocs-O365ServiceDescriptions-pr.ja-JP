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
description: 現在、Exchange Online Protection には次の制限があります。 これらの制限は、特に指定しない限り構成できません。
ms.openlocfilehash: 6c399c359d39f50a4bd359833fdf595415872bff
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173802"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection の制限

現在、Exchange Online Protection には次の制限があります。 これらの制限は、特に指定しない限り構成できません。 
  
> [!TIP]
> Exchange Online の制限の詳細については、「Exchange Online の制限 [」を参照してください](../exchange-online-service-description/exchange-online-limits.md)。 トランスポート ルールの制限は、EOP スタンドアロンのお客様にも適用されます。 Exchange Online の受信者レートやメッセージ レートの制限は、EOP スタンドアロンのお客様には適用されません。 
  
- **ドメイン制限** - テナントごとに最大 900 のドメインを追加できます。 この 900 の制限には、サブドメイン、または必要に応じて、キャッチオール オプションの一部として一致サブドメインを含めることができます。 詳しくは、「 [EOP で承認済みドメインを管理する](/microsoft-365/security/office-365-security/exchange-online-protection-overview)」を参照してください。

- **リモート ドメインの制限** - テナントごとに最大 200 のリモート ドメインを追加できます。
    
- **メッセージ サイズの制限** - 添付ファイルを含む EOP スタンドアロンユーザーの最大メッセージ サイズは 150 MB です。 
    
- **送信される送信メッセージ** の数 - EOP を介して送信される送信メッセージの数の制限は、通常の電子メール通信がスパムとして扱われるのに十分な高値です。 商業用の電子メール メッセージを送信したい場合は、EOP 経由で送信メッセージを送信するよりも、サード パーティ電子メール サービス プロバイダー (ESP) を使用するか、社内の電子メール サーバー経由で送信することをお勧めします。 
    
- **受信者の** 制限 - 送信ホストがメッセージを 500 未満の受信者の "チャンク" に分割できる限り、明示的な制限は定義されません。 ただし、各 "チャンク" は、事実上新しいメッセージとして扱われます。 短い期間中の多すぎるメッセージ、低い評価のホストからのメッセージ、または信頼できないコンテンツを含むメッセージは、制限またはブロックされる可能性があります。 
    
- **IP 許可** または IP ブロック リストの制限 - 接続フィルターで IP 許可リストまたは IP ブロック リストを構成する場合、エントリが 1 つの IP アドレスまたは /24 ~ /32 の IP アドレスの CIDR 範囲である最大 1273 エントリを指定できます。 
    
- **メッセージの遅延制限** - 保留メッセージは 24 時間キューに残ります。 メッセージの再送信は、受信者のメールシステムから返されたエラーの種類に基づいて行われます。 15 分ごとにメッセージの送信が再試行されます。 
    
- **スパム検疫の保持期間** - 既定では、検疫に送信されたスパム メッセージは 30 日間保持されます。 管理者は、コンテンツ フィルター ポリシーによってこの値を下げることができます。 
    
- **エンド ユーザーのスパム検疫通知** - 既定では、有効にした場合、エンド ユーザーのスパム検疫通知は 3 日ごとに送信されます。 それらは 1 ～ 15 日ごとに送信されるように構成できます。 
    
- **レポートとメッセージのトレース** の制限 - レポートとメッセージのトレースの制限については、「レポートとメッセージのトレース データの可用性と待機時間」セクションを参照してください [。Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)のレポートとメッセージ トレース。
    
### <a name="limits-across-eop-options"></a>各 EOP オプションでの制限

| 機能 | EOP スタンドアロン | Exchange Online の EOP 機能 | Exchange Enterprise CAL (サービス付き) |
|:-----|:-----|:-----|:-----|
|ドメインの制限  <br/> |900  <br/> |900  <br/> |900  <br/> |
|リモート ドメインの制限  <br/> |200  <br/> |200  <br/> |200  <br/> |
|メッセージ サイズの制限 (添付ファイルを含む)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|受信者の制限  <br/> |上記の "受信者の制限" を参照  <br/> |ホストされているメールボックスから送信する場合は、500 人の受信者。その他のシナリオについては、上記の "受信者の制限" を参照  <br/> |上記の "受信者の制限" を参照  <br/> |
|差出人セーフ リストの制限  <br/> |1024 エントリ  <br/> |1024 エントリ  <br/> ||
|ポリシーごとの送信者の制限のブロック  <br/> |1024 エントリ  <br/> |1024 エントリ  <br/> ||
|IP 許可一覧または IP 禁止一覧の制限  <br/> |1,273 エントリ  <br/> |1,273 エントリ  <br/> |1,273 エントリ  <br/> |
|保留状態のメッセージの制限  <br/> |1 日、15 分ごとに再試行  <br/> |1 日、15 分ごとに再試行  <br/> |1 日、15 分ごとに再試行  <br/> |
|スパム検疫の保存期間  <br/> |既定では 30 日間ですが、下げ可能  <br/> |既定では 30 日間ですが、下げ可能  <br/> |既定では 30 日間ですが、下げ可能  <br/> |
|エンドユーザー スパム検疫通知  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |既定では 3 日、1 ～ 15 日に構成可能です  <br/> |
