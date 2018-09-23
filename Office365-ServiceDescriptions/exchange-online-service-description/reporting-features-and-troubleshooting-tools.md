---
title: レポート機能とトラブルシューティング ツール
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online には、さまざまな Exchange 管理センター (EAC) および機能両方のレポートが用意されています。
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036247"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>レポート機能とトラブルシューティング ツール

Microsoft Exchange Online には、さまざまな Exchange 管理センター (EAC) および機能両方のレポートが用意されています。
  
## <a name="reporting-features"></a>レポート作成機能

Exchange Online のユーザーは、Office 365 管理センターで、Excel レポート作成ワークブックをダウンロードするか、Web サービスを使用してレポートにアクセスできます。
  
### <a name="reporting-in-the-office-365-admin-center"></a>Office 365 管理センターでのレポート作成

Microsoft Office 365 管理センターの [レポート] ページに、メールボックスおよびグループに関する概要情報を提供するレポートがあります。たとえば、あるレポートでは、日、週、月、または年単位に作成および削除されたグループの数の一覧があります。また、新しいメールボックスと削除済みのメールボックス、アクティブおよび非アクティブなメールボックスに関する概要レポートもあります。 
  
さらに、Microsoft Office 365 管理センターの [レポート] ページにはメッセージング データ レポートもあります。このレポートは、メッセージ トラフィック、スパムとマルウェアの検知、および Exchange トランスポート ルールまたはデータ損失防止 (DLP) ポリシーによって影響されたメッセージに関する情報を提供します。保護、ルール、DLP に関する拡張レポートは、Exchange Online 管理者が対話形式でレポートを作成できるようにするものです。これらのレポートでは、概要データと、個別のメッセージに関する詳細へのドリルダウン機能が提供されます。
  
各 Office 365 サブスクリプションで利用可能なレポートの詳細については、[レポート](../office-365-platform-service-description/reports.md)を参照してください。Office 365 管理センターのレポート ページの詳細については、「[Office 365 管理センターのアクティビティ レポート](https://go.microsoft.com/fwlink/p/?LinkId=401187)」および「[Office 365 のメール保護レポートによるマルウェア、スパム、ルールの検出に関するデータ表示](https://go.microsoft.com/fwlink/p/?LinkID=401102)」を参照してください。
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel レポート作成ワークブックを使用したレポート作成

Excel 2013 レポート作成ワークブックを使用して、ドリルダウン機能を備えた概要レポートを表示することもできます。しかし、拡張 Office 365 管理センターのレポートの利用をお勧めします。Excel 2013 レポート ワークブックは、今後は提供されなくなる予定です。詳細情報およびレポート作成ワークブックのダウンロードおよびインストール用のリンクについては、次の[ダウンロード ページ](https://go.microsoft.com/fwlink/p/?LinkId=271776)を参照してください。レポート作成ワークブックの使用方法については、「[Excel レポート ワークブックを使用したメール保護レポート](https://go.microsoft.com/fwlink/p/?LinkId=285211)」を参照してください。 
  
### <a name="reporting-using-web-services"></a>Web サービスを使用したレポート作成

メールボックス、グループ、およびメッセージング データに関する概要レポートと詳細レポートには、REST/OData テナント レポート Web サービスを使用してアクセスできます。この Web サービスは、カスタム レポートを作成できるプログラマティック インターフェイスです。詳細については、「[Office 365 レポート Web サービス](https://go.microsoft.com/fwlink/p/?LinkId=287041)」を参照してください。
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC のレポート作成機能とトラブルシューティング ツール

Exchange 管理センターでは、次のレポート作成機能とトラブルシューティング ツールを使用できます。
  
### <a name="trace-an-email-message"></a>電子メール メッセージの追跡

メッセージ追跡機能を使用すると、管理者は Exchange Online サービスを経由する電子メール メッセージを追跡できます。これは、対象の電子メール メッセージがサービスによって受信、拒否、延期、または配信されたかどうかを判断する上で役立ちます。したがって、効率良くユーザーの質問に回答したり、メール フローの問題をトラブルシューティングしたりできるため、テクニカル サポートに支援を求める必要性が減ります。
  
> [!IMPORTANT]
> 一般的な問題や傾向をトラブルシューティングする場合は、レポート ツールを使用してこのようなデータを取得できます。単一点でのメッセージに関する詳細が必要な場合は、メッセージ追跡ツールを使用します。 
  
メッセージ追跡機能の詳細については、「[電子メール メッセージの追跡](https://go.microsoft.com/fwlink/p/?LinkId=271777)」を参照してください。
  
### <a name="auditing-reports"></a>監査レポート

監査ログを使用すると、管理者が行った特定の変更を追跡して構成上の問題をトラブルシューティングしたり、法規制、法令遵守、および訴訟の要件を満たすために利用したりすることができます。Exchange Online には次の 2 種類の監査ログがあります。
  
- 管理者監査ログ は管理者によって実行されたあらゆる処理を記録します。これは、構成上の問題のトラブルシューティングを行ったり、セキュリティ関連または法令遵守に関連する問題の原因を特定したりするのに役立ちます。 
    
- メールボックス監査ログ: メールボックスの所有者以外のユーザーがメールボックスにアクセスするたびに記録されます。これは、メールボックスにアクセスしたユーザーとそのユーザーが実行した操作を確認するのに役立ちます。 
    
監査ログの詳細については、「[Exchange 監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=271779)」を参照してください。
  
### <a name="unified-messaging-reports"></a>ユニファイド メッセージングのレポート

これらのレポートを使用すると、Exchange Online 組織内のユニファイド メッセージング (UM) の監視やトラブルシューティングを行うことができます。詳細については、「[ボイス メール通話のレポートを実行する](https://go.microsoft.com/fwlink/p/?LinkId=287042)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

