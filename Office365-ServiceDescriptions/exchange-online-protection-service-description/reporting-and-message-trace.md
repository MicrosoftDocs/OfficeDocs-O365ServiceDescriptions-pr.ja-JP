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
description: この記事では、Microsoft Exchange Online Protection (EOP) のレポート作成とメッセージ追跡について説明します。
ms.openlocfilehash: 6690c246620d4324610213b4968367cff0d30cf9
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293663"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Exchange Online Protection でのレポート作成とメッセージ追跡

Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。 一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。

すべての EOP 機能に関する情報をお探しですか? 「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理センターのレポート

Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、およびメールフロールール (トランスポートルールとも呼ばれます) またはデータ損失防止 (DLP) ポリシーによって影響を受けるメッセージに関する情報が記載されています。 保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。 これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。

これらのレポートの詳細については、「 [メール保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)」を参照してください。

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> REST ベースのレポート機能および関連するコマンドレットの多くは、2018年1月に廃止されました。 Office 365 で利用可能な代替の Microsoft Graph レポートの詳細については、「 [Microsoft graph で利用状況レポートを](https://go.microsoft.com/fwlink/p/?LinkID=865135)使用する」のトピックを参照してください。

EOP スタンドアロンのお客様は利用できません。 REST/OData テナントレポート web サービスを使用すると、プログラムによってメッセージングデータに関する概要と詳細レポートを収集できます。また、カスタム web 管理ポータルの web ページにデータを表示することもできます。

## <a name="message-trace"></a>メッセージ追跡

EAC のメッセージ追跡機能を使用すると、管理者は EOP を通過する電子メールメッセージを追跡できます。 これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。 メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。 特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。 詳細については、「 [メッセージ追跡を実行し、Exchange 管理センターで結果を表示](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)する」を参照してください。

## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
