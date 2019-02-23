---
title: レポート作成とメッセージ追跡
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。
ms.openlocfilehash: b52e1e33a8eec0694143c3dc277481fff79bf918
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210210"
---
# <a name="reporting-and-message-trace"></a>レポート作成とメッセージ追跡

Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。
  
EOP のすべての機能についての説明をご覧になりますか?「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理センターのレポート
<a name="BKMK_office365admincenterreports"> </a>

Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、および Exchange トランスポートルールまたはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報が記載されています。保護、ルール、および DLP の強化されたレポートは、EOP 管理者向けの対話型レポート機能を提供します。これらのレポートは、概要データと個々のメッセージに関する詳細をドリルダウンする機能を提供します。
  
これらのレポートについての詳細は、「[Office 365 のメール保護レポートによるマルウェア、スパム、ルールの検出に関するデータ表示](https://go.microsoft.com/fwlink/p/?LinkID=401102)」を参照してください。
  
## <a name="excel-download-application-reports"></a>Excel 形式でダウンロードするアプリケーション レポート
<a name="BKMK_exceldownloadapplicationreports"> </a>

電子メール保護レポートは、Excel 2013 レポートブックでも使用できます。これにより、ドリルダウン機能を備えた概要レポートが提供されます。ただし、強化された Microsoft 365 管理センターのレポートを代わりに使用することをお勧めします。Excel 2013 レポートブックは、今後使用されなくなる予定です。 
  
このワークブックの概要と、ブックのダウンロードおよびインストール (リンク) については、「[Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776)」を参照してください。ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。
  
## <a name="reporting-using-web-services"></a>Web サービスを使用したレポート作成
<a name="BKMK_reportingusingwebservices"> </a>

EOP スタンドアロンのお客様は利用できません。REST/OData テナント レポート Web サービスでは、プログラムを使ってメッセージング データに関する概要レポートや詳細レポートを収集し、そのデータをカスタム管理 Web ポータルの Web ページに表示できます。詳細については、「[Office 365 レポート Web サービス](https://go.microsoft.com/fwlink/?LinkId=279926)」を参照してください。
  
## <a name="message-trace"></a>メッセージの追跡
<a name="BKMK_messagetrace"> </a>

管理者は EAC のメッセージ追跡機能を使用して、EOP を経由する電子メール メッセージを追跡できます。これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkID=282262)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性
<a name="BKMK_messagetrace"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  

