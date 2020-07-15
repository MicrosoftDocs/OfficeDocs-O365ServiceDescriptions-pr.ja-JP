---
title: レポート機能とトラブルシューティング ツール
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online は、Exchange 管理センター (EAC) の内外で、さまざまなレポート機能を提供します。
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132601"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>レポート機能とトラブルシューティング ツール

Microsoft Exchange Online は、Exchange 管理センター (EAC) の内外で、さまざまなレポート機能を提供します。
  
## <a name="reporting-features"></a>レポート作成機能

Exchange Online のお客様は、Microsoft 365 管理センターで、Excel レポートブックをダウンロードするか、web サービスを使用して、レポートにアクセスできます。
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Microsoft 365 管理センターでのレポート

Microsoft 365 管理センターの [レポート] ページには、メールボックスとグループに関する概要情報を提供するレポートがあります。 たとえば、あるレポートでは、日、週、月、または年単位に作成および削除されたグループの数の一覧があります。 また、新しいメールボックスと削除済みのメールボックス、アクティブおよび非アクティブなメールボックスに関する概要レポートもあります。 
  
さらに、Microsoft 365 管理センターの [レポート] ページには、メッセージトラフィック、スパムおよびマルウェアの検出、および Exchange トランスポートルールまたはデータ損失防止 (DLP) ポリシーによって影響を受けるメッセージに関する情報を提供するメッセージングデータレポートが含まれています。 保護、ルール、および DLP の拡張されたレポートは、Exchange Online 管理者向けの対話型レポートを提供します。 これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。
  
各サブスクリプションで使用可能なレポートの詳細については、「 [reports](../office-365-platform-service-description/reports.md)」を参照してください。 Microsoft 365 管理センターの [レポート] ページの詳細については、「 [Office 365 のサービスの利用状況に関するレポートの表示とダウンロード](https://go.microsoft.com/fwlink/p/?LinkId=401187)」および「[メール保護レポートを使用してマルウェア、スパム、ルールの検出に関するデータを表示する](https://go.microsoft.com/fwlink/p/?LinkID=401102)」を参照してください。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel レポート作成ワークブックを使用したレポート作成

Excel 2013 レポート作成ワークブックを使用して、ドリルダウン機能を備えた概要レポートを表示することもできます。 ただし、強化された Microsoft 365 管理センターのレポートを代わりに使用することをお勧めします。 Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。 詳細情報およびレポート作成ワークブックのダウンロードおよびインストール用のリンクについては、次の[ダウンロード ページ](https://go.microsoft.com/fwlink/p/?LinkId=271776)を参照してください。 レポート作成ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

メールボックス、グループ、およびメッセージングデータに関する概要と詳細なレポートの両方にアクセスするには、REST/OData テナントレポート web サービスを使用します。これは、カスタムレポートを作成できるプログラマティックなインターフェイスです。 詳細については、「 [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041)」を参照してください。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC のレポート作成機能とトラブルシューティング ツール

Exchange 管理センターでは、次のレポート作成機能とトラブルシューティング ツールを使用できます。
  
### <a name="trace-an-email-message"></a>電子メール メッセージの追跡

メッセージ追跡機能を使用すると、管理者は、Exchange Online サービスを通過するときに電子メールメッセージをフォローすることができます。 これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。 したがって、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたりできるため、テクニカル サポートに支援を求める必要性が減ります。
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
メッセージ追跡機能の詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkId=271777)」を参照してください。
  
### <a name="auditing-reports"></a>監査レポート

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
監査ログの詳細については、「[Exchange 監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=271779)」を参照してください。
  
### <a name="unified-messaging-reports"></a>ユニファイド メッセージングのレポート

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

