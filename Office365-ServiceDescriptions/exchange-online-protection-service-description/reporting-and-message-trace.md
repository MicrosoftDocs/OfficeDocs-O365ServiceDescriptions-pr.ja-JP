---
title: Exchange Online Protection でのレポート作成とメッセージ追跡
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: この記事では、EOP (セキュリティ保護) のレポートとメッセージMicrosoft Exchange Onlineを参照してください。
ms.openlocfilehash: e07b7b9f6f7bee2715314021d9a7e96a29af8b21
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173332"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Exchange Online Protection でのレポート作成とメッセージ追跡

Microsoft Exchange Online保護 (EOP) は、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートを提供します。 一部のレポートは Microsoft 365 管理センターで利用できます。他のレポートは Exchange 管理センター (EAC) で利用できます。

すべての EOP 機能に関する情報をお探しですか? Exchange [Online Protection サービスの説明を参照してください](exchange-online-protection-service-description.md)。

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理センターレポート

Microsoft 365 管理センターの [レポート] ページには、メッセージ トラフィック、スパム、マルウェアの検出、メール フロー ルール (トランスポート ルールとも呼ばれる) またはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報が表示されます。 保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。 これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。

これらのレポートの詳細については、「メール保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する」 [を参照してください](/exchange/monitoring/use-mail-protection-reports)。

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> REST ベースのレポート機能と関連するコマンドレットの多くは、2018 年 1 月に廃止されました。 Office 365 で使用可能な置換 Microsoft Graph レポートの詳細については、「Microsoft Graph での使用状況レポートの操作」のサブトピック [を参照してください](/graph/api/resources/report)。

EOP スタンドアロンのお客様は利用できません。 REST/OData テナント レポート Web サービスを使用して、メッセージング データに関する概要と詳細なレポートをプログラムで収集し、カスタム Web 管理ポータルの Web ページにデータを表示できます。

## <a name="message-trace"></a>メッセージ追跡

EAC のメッセージ トレース機能を使用すると、管理者として EOP を通過する電子メール メッセージをフォローできます。 これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。 メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。 特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。 詳細については、「メッセージ トレース [を実行し、Exchange 管理センターで結果を表示する」を参照してください](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)。

## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online Protection サービスの説明」 [を参照してください](exchange-online-protection-service-description.md)。