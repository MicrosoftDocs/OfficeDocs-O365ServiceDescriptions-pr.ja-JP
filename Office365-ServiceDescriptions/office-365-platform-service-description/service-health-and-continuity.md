---
title: サービスの正常性および継続性
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft 管理者は、サービスの状態を表示し、メンテナンスがスケジュールされているときに確認できます。 サービス正常性情報は、サインインすることでいつでも利用できます。
ms.openlocfilehash: 4fa2e8a907eaae36e9185adcd4f99bd841c42ccc
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131801"
---
# <a name="service-health-and-continuity"></a>サービスの正常性および継続性

Microsoft 管理者は、サービスの状態を表示し、メンテナンスがスケジュールされているときに確認できます。 サービス正常性情報は、サインインすることでいつでも利用できます。
  
> [!NOTE]
> 21Vianet が運用している Office 365 を使用している場合、以下の情報は適用できない場合があります。 代わりに、「[21Vianet のサービス レベル契約](https://www.21vbluecloud.com/office365/O365-SLA/)」を参照してください。 
  
## <a name="view-status-of-services"></a>サービスの状態を表示

The Service health section shows the current status of the service and details about service disruptions and outages. Planned maintenance information is available on the Message Center. For more information, see [View the status of your services](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>サービス インシデント

A service incident is an event that affects the delivery of a service. Service incidents may be caused by hardware or software failure in the Microsoft data center, a faulty network connection between the customer and Microsoft, or a major data center challenge such as fire, flood, or regional catastrophe. Most service incidents can be addressed using Microsoft technology and process solutions and are resolved within a short time. However, some service incidents are more serious and can lead to longer term outages.
  
サービスが使用不能になる場合の通知には 2 種類あります。
  
- **Planned maintenance events:** Planned maintenance is regular Microsoft-initiated service updates to the infrastructure and software applications. Planned maintenance notifications inform customers about service work that might affect the functionality of a Microsoft service. Customers are notified no later than five days in advance of all planned maintenance through Message Center on the Microsoft 365 admin center. Microsoft typically plans maintenance for times when service usage is historically at its lowest based on regional time zones. 
    
- **予定外のダウンタイム:** 計画外のサービスインシデントは、いずれかのサービスが使用できないか応答しない場合に発生します。 

### <a name="recent-worldwide-uptimes"></a>全世界での最近の稼働時間

クラウドサービスに移行する場合は、何が起こっているのかを知ることができなくなるわけではありません。 Office 365 では、そうではありません。 Microsoft が目標としているのは運用における透明性なので、お客様はサービスの状態の監視や問題の追跡を行うことができます。また、サービスの利用状況を過去にさかのぼって確認することもできます。 下の表は、全世界の稼働時間データを示しています。

<br/>

|**2020** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.98% <br/> | <br/> | <br/> |<br/> |

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99.99% <br/> | 99.97% <br/> | 99.98% <br/> | 99.99% <br/> |

<br/>

## <a name="notification-policy"></a>通知ポリシー

Microsoft は、サービス インシデントが発生した場合、タイムリーで、対象を指定した、正確なコミュニケーションがお客様にとって不可欠であると認識しています。 Microsoft は、Microsoft 365 管理センターでテナント固有のサービス正常性ダッシュボード (SHD) を更新して管理者に通知します。 サービス インシデントの更新は時間単位で実行されるか、または異なる間隔が必要な場合は、SHD 通信の投稿に記載されます。 
  
## <a name="service-health-communication-channels"></a>サービス正常性の通信チャネル

### <a name="admin-app"></a>Admin アプリ

組織管理者用の管理者アプリを使用すると、組織の Microsoft サービスの状態を外出先から接続することができます。 Microsoft 管理者は、モバイルデバイスからサービスの正常性情報とメンテナンス状態の更新を表示することができます。 詳細については、「[管理アプリ FAQ](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide)」を参照してください。
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Microsoft System Center 2012 R2 用 Office 365 管理パック

Microsoft System Center は、データ センター、クライアント デバイス、およびハイブリッド型のクラウド IT 環境の管理に役立つ統合された管理プラットフォームです。 System Center を使用している Microsoft 管理者は、Office 365 管理パックをインポートすることができます。これにより、System Center の Operations Manager 内のすべてのサービス通信が表示されます。 このツールを使用すると、サブスクライブ済みサービス、アクティブおよび解決済みサービス インシデント、およびメッセージ センターとの通信の状態にアクセスできます。 詳細については、Microsoft ダウンロードセンターで[Office 365 用の Microsoft System Center 管理パック](https://www.microsoft.com/download/details.aspx?id=43708)を入手してください。 
  
### <a name="office-365-service-communications-api"></a>Office 365 サービス通信 API

Office 365 サービス通信 API を使用すると、目的の方法でサービス通信にアクセスできます。 この API を使用すると、通信を行うためのツールを作成または接続することができ、環境の監視が容易になる可能性があります。 サービス通信 API を使用することにより、環境内で以下を監視できます。
  
- リアルタイムのサービスの正常性
    
- メッセージ センターの通信
    
詳細については、「 [Office 365 サービス通信 API リファレンス](https://docs.microsoft.com/office/office-365-management-api/office-365-service-communications-api-reference)」を参照してください。 
  
## <a name="post-incident-reviews"></a>インシデントの事後レビュー

継続的な機能向上に対する Microsoft の取り組みには、お客様に影響を与える計画外のサービス インシデントを分析し、再発生をできる限りなくすことが含まれます。 
  
計画外のサービス インシデントは、SLA サービスで定義されたサービスの使用に影響を与える、マルチ テナント サービスの中断として定義され、サービスの正常性ダッシュボードでそのように宣言されています。
  
 For unplanned customer-impacting service incidents in which there was broad and noticeable impact across a large number of organizations, a preliminary Post-Incident Review (PIR) will be delivered via your Service Health Dashboard within 48 hours of incident resolution, followed by a final PIR within five business days. The detailed PIR report includes: 
  
- ユーザー エクスペリエンスや顧客への影響
    
- インシデントの開始と終了の日付と時刻
    
- 影響と解決策の対策の詳細なタイムライン
    
- 継続的な改善のためになされる根本原因分析と対策
    
For all other service incidents, the Service Health Dashboard will provide an incident closure summary including a final summary of the event, preliminary root cause, start and end times, and information detailing next steps. For this category of service incident, a PIR will not be generated. 
  
## <a name="service-continuity"></a>サービス継続性

Microsoft オファーリングは、サービスのピーク時のパフォーマンスを維持するために役立つ回復力の高いシステムによって提供されます。 サービス継続性の条項は、システム設計の一部です。 これらの規定により、Microsoft は、ハードウェアやアプリケーションの障害、データの破損、ユーザーに影響を与えるその他のインシデントなどの予期しないイベントから迅速に復旧できます。 サービス継続性ソリューションは、重大なサービス停止 (たとえば、自然災害やインシデントによって、ある Microsoft のデータ センター全体が使用不能になった場合など) の際にも適用されます。
  
致命的な障害から復旧した後、データ センターの完全な冗長性がサービスに復元されるまで一定の時間がかかることがあります。 たとえば、データ センター 1 に障害が発生すると、サービスがデータ センター 2 のリソースによって復元されます。 ただし、データ センター 1 の復元されたリソースまたはデータ センター 3 の新規リソースによって、データ センター 2 のサービスの継続性がサポートされるまで時間がかかります。 Microsoft[サービスレベル契約](service-level-agreement.md)(SLA) は、この期間に適用されます。 21Vianet が運用している Office 365 には、別の SLA があります。 詳細については、 [21Vianet サイト](https://www.21vbluecloud.com/office365/O365-SLA/)をご覧ください。 
  
## <a name="ensuring-data-availability"></a>データ可用性の確保

Microsoft は、以下の機能によって、お客様がいつでも必要なときにデータを利用できるようにしています。
  
- **Data storage and redundancy:** Customer data is stored in a redundant environment with robust data protection capabilities to enable availability, business continuity, and rapid recovery. Multiple levels of data redundancy are implemented, ranging from redundant disks to guard against local disk failure to continuous, full data replication to a geographically diverse data center. 
    
- **データの監視:** Microsoft サービスは、次のようにして高レベルのパフォーマンスを維持します。 
    
  - **データベースの監視:**
    
  - ブロックされたプロセス
    
  - パケット損失
    
  - キューに登録されたプロセス
    
  - クエリの待機時間
    
- **予防保守の実行:** 予防保守には、データベースの整合性チェック、定期的なデータ圧縮、およびエラー ログのレビューなどがあります。 
    
## <a name="support"></a>サポート

Microsoft の開発および運用チームは、お客様にビジネス継続性を提供するうえで重要な役割を果たす、専任のサポート組織によって補われています。 サポート スタッフはサービスおよびサービスに関連するアプリケーションに精通しており、Microsoft 社内のアーキテクチャ、開発、テストの専門家と直接やり取りします。
  
The support organization closely aligns with operations and product development, offers fast resolution times and provides a channel for customers' voices to be heard. Feedback from customers provides input to the planning, development, and operations processes.
  
- **オンライン問題追跡:** お客様は、問題が対応されていることを把握し、タイムリーに解決されていることを追跡できる必要があります。 Microsoft 365 padmin center ortal は、サポート用の単一の web ベースのインターフェイスを提供します。 お客様はこのポータルを使用することで、サービス リクエストを追加および監視するとともに、Microsoft サポート チームからのフィードバックを受信できます。 
    
- **スタッフが継続的にサポートするセルフヘルプ:** Microsoft は、お客様が Microsoft サポートを必要とせずにサービス関連の問題を解決するのに役立つ、さまざまなセルフヘルプのリソースとツールを提供しています。 
    
Before customers enter service requests, they can access knowledge base articles and FAQs that provide immediate help with the most common problems. These resources are continually updated with the latest information, which helps avoid delays by providing solutions to known issues. However, when an issue arises that needs the help of a support professional; staff members are available for immediate assistance by telephone and through the administration portal 24 hours a day, 7 days a week.
  
サポートの詳細については、「[サポート](support.md)」トピックを参照してください。 
  
## <a name="feature-availability"></a>機能の可用性

プラン全体の機能の可用性を表示するには、「 [Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)」を参照してください。
  