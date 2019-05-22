---
title: レポート作成とメッセージ追跡
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。 一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。
ms.openlocfilehash: 5b836794a430bff7d28814c917e9cfbd14304a2f
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341926"
---
# <a name="reporting-and-message-trace"></a>レポート作成とメッセージ追跡

Microsoft Exchange Online Protection (EOP) には、組織の全体的な状態と正常性を判断するのに役立つさまざまなレポートが用意されています。 一部のレポートは、Microsoft 365 管理センターで利用できますが、Exchange 管理センター (EAC) で使用できます。
  
すべての EOP 機能に関する情報をお探しですか? 「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 管理センターのレポート
<a name="BKMK_office365admincenterreports"> </a>

Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、および Exchange トランスポートルールまたはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報が記載されています。 保護、ルール、DLP に関する拡張レポートは、EOP 管理者が対話形式でレポートを作成できるようにするものです。 これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。
  
これらのレポートについての詳細は、「[Office 365 のメール保護レポートによるマルウェア、スパム、ルールの検出に関するデータ表示](https://go.microsoft.com/fwlink/p/?LinkID=401102)」を参照してください。
  
## <a name="excel-download-application-reports"></a>Excel download application reports
<a name="BKMK_exceldownloadapplicationreports"> </a>

Excel 2013 レポート ブックでは、メール保護のレポートが用意されており、ドリルダウン機能付きの概要レポートが提供されます。 ただし、強化された Microsoft 365 管理センターのレポートを代わりに使用することをお勧めします。 Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。 
  
このワークブックの概要と、ブックのダウンロードおよびインストール (リンク) については、「[Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776)」を参照してください。ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。
  
## <a name="reporting-using-web-services"></a>Reporting using web services
<a name="BKMK_reportingusingwebservices"> </a>

EOP スタンドアロンのお客様は利用できません。REST/OData テナント レポート Web サービスでは、プログラムを使ってメッセージング データに関する概要レポートや詳細レポートを収集し、そのデータをカスタム管理 Web ポータルの Web ページに表示できます。詳細については、「[Office 365 レポート Web サービス](https://go.microsoft.com/fwlink/?LinkId=279926)」を参照してください。
  
## <a name="message-trace"></a>メッセージ追跡
<a name="BKMK_messagetrace"> </a>

管理者は EAC のメッセージ追跡機能を使用して、EOP を経由する電子メール メッセージを追跡できます。これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。メッセージが最終的な状態になる前に、メッセージに行われた処理も表示します。特定メッセージに関する詳細情報を得ることにより、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたり、ポリシーの変更を検証したりすることができるため、テクニカル サポートに支援を求める必要性が減ります。詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkID=282262)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性
<a name="BKMK_messagetrace"> </a>

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  

