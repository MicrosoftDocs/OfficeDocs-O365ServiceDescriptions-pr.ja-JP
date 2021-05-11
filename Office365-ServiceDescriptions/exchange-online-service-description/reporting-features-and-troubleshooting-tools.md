---
title: レポート機能とトラブルシューティング ツール
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Onlineは、管理センター (EAC) でのレポート機能と管理センター Exchange機能を提供します。
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652691"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>レポート機能とトラブルシューティング ツール

Microsoft Exchange Onlineは、管理センター (EAC) でのレポート機能と管理センター Exchange機能を提供します。
  
## <a name="reporting-features"></a>レポート作成機能

Exchange Onlineユーザーは、Microsoft 365レポート ブックをダウンロードするか、web サービスを使用して、Excel管理センターのレポートにアクセスできます。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>管理センター Microsoft 365レポート

メールボックスとグループに関する概要情報をMicrosoft 365管理センターの [レポート] ページにレポートがあります。 たとえば、あるレポートでは、日、週、月、または年単位に作成および削除されたグループの数の一覧があります。 また、新しいメールボックスと削除済みのメールボックス、アクティブおよび非アクティブなメールボックスに関する概要レポートもあります。 
  
さらに、Microsoft 365 管理センターの [レポート] ページには、メッセージ トラフィック、スパムおよびマルウェア検出、Exchange トランスポート ルールまたはデータ損失防止 (DLP) ポリシーの影響を受けるメッセージに関する情報を提供するメッセージング データ レポートが含まれています。 保護、ルール、および DLP の強化されたレポートは、管理者向け対話型Exchange Online提供します。 これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。
  
各サブスクリプションで使用できるレポートの詳細については、「Reports」を [参照してください](../office-365-platform-service-description/reports.md)。 Microsoft 365 管理センターの [レポート] ページの詳細については[、「Office 365](/microsoft-365/admin/activity-reports/activity-reports)でのサービス使用状況に関するレポートの表示とダウンロード」および「メール[](/exchange/monitoring/use-mail-protection-reports)保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する」を参照してください。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel レポート作成ワークブックを使用したレポート作成

Excel 2013 レポート作成ワークブックを使用して、ドリルダウン機能を備えた概要レポートを表示することもできます。 ただし、代わりに管理センター レポートの拡張Microsoft 365使用することをお勧めします。 Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。 詳細情報およびレポート作成ワークブックのダウンロードおよびインストール用のリンクについては、次の[ダウンロード ページ](https://go.microsoft.com/fwlink/p/?LinkId=271776)を参照してください。 レポート作成ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150))」を参照してください。 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

メールボックス、グループ、およびメッセージング データに関する概要レポートと詳細レポートの両方にアクセスするには、カスタム レポートを作成できるプログラムによるインターフェイスである REST/OData テナント レポート Web サービスを使用します。 詳細については、「レポート[Web サービスOffice 365を参照してください](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15))。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC のレポート作成機能とトラブルシューティング ツール

Exchange 管理センターでは、次のレポート作成機能とトラブルシューティング ツールを使用できます。
  
### <a name="trace-an-email-message"></a>電子メール メッセージの追跡

メッセージ 追跡機能を使用すると、管理者は、ユーザーがサービスを通過する電子メール メッセージExchange Onlineできます。 これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。 したがって、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたりできるため、テクニカル サポートに支援を求める必要性が減ります。
  
> [!IMPORTANT]
> 一般的な問題や傾向をトラブルシューティングする場合は、レポート ツールを使用してこのようなデータを取得できます。単一点でのメッセージに関する詳細が必要な場合は、メッセージ追跡ツールを使用します。 
  
メッセージ追跡機能の詳細については、「[電子メール メッセージの追跡](/exchange/monitoring/trace-an-email-message/trace-an-email-message)」を参照してください。
  
### <a name="auditing-reports"></a>監査レポート

監査ログを使用すると、管理者が行った特定の変更を追跡して構成上の問題をトラブルシューティングしたり、法規制、法令遵守、および訴訟の要件を満たすために利用したりすることができます。Exchange Online には次の 2 種類の監査ログがあります。
  
- 管理者監査ログ は管理者によって実行されたあらゆる処理を記録します。これは、構成上の問題のトラブルシューティングを行ったり、セキュリティ関連または法令遵守に関連する問題の原因を特定したりするのに役立ちます。 
    
- メールボックス監査ログ: メールボックスの所有者以外のユーザーがメールボックスにアクセスするたびに記録されます。これは、メールボックスにアクセスしたユーザーとそのユーザーが実行した操作を確認するのに役立ちます。 
    
監査ログの詳細については、「[Exchange 監査レポート](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)」を参照してください。
  
### <a name="unified-messaging-reports"></a>ユニファイド メッセージングのレポート

これらのレポートを使用すると、Exchange Online 組織内のユニファイド メッセージング (UM) の監視やトラブルシューティングを行うことができます。詳細については、「[ボイス メール通話のレポートを実行する](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online[参照してください](exchange-online-service-description.md)。
