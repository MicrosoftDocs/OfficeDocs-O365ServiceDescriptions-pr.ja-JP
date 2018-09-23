---
title: サービスの正常性および継続性
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft Office 365 の管理者では、サービスの状態を表示でき、メンテナンスが予定されていることを検出することができます。サービス稼働状態の情報をいつでも参照するには、Office 365 にサインインします。
ms.openlocfilehash: cc19a26f7bef070837b1dfa53df927373fd35d3e
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036381"
---
# <a name="service-health-and-continuity"></a><span data-ttu-id="a3569-104">サービスの正常性および継続性</span><span class="sxs-lookup"><span data-stu-id="a3569-104">Service Health and Continuity</span></span>

<span data-ttu-id="a3569-p102">Microsoft Office 365 の管理者では、サービスの状態を表示でき、メンテナンスが予定されていることを検出することができます。サービス稼働状態の情報をいつでも参照するには、Office 365 にサインインします。</span><span class="sxs-lookup"><span data-stu-id="a3569-p102">Microsoft Office 365 admins can view the status of services and find out when maintenance is scheduled. Service health information is available at any time by signing in to Office 365.</span></span>
  
> [!NOTE]
> <span data-ttu-id="a3569-p103">21Vianet が運用している Office 365 を使用している場合、以下の情報は適用できない場合があります。代わりに、「[21Vianet のサービス レベル契約](http://www.21vbluecloud.com/office365/O365-SLA/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a3569-p103">If you are using Office 365 operated by 21Vianet, some of the information below might not apply. Instead, see the [21Vianet service level agreement](http://www.21vbluecloud.com/office365/O365-SLA/).</span></span> 
  
## <a name="view-status-of-services"></a><span data-ttu-id="a3569-109">サービスの状態の表示</span><span class="sxs-lookup"><span data-stu-id="a3569-109">View Status of Services</span></span>

<span data-ttu-id="a3569-p104">Office 365 のサービス正常性セクションには、サービスの現在の状態とサービスの中断と停止の詳細が表示されます。計画メンテナンスの情報は、メッセージセンターで確認できます。詳細については、「[Office 365 サービスの正常性をチェックする方法](https://go.microsoft.com/fwlink/p/?LinkID=270178)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a3569-p104">The Service health section of Office 365 shows the current status of the service and details about service disruptions and outages. Planned maintenance information is available on the Message Center. For more information, see [View the status of your services](https://go.microsoft.com/fwlink/p/?LinkID=270178).</span></span> 
  
## <a name="service-incidents"></a><span data-ttu-id="a3569-113">サービス インシデント</span><span class="sxs-lookup"><span data-stu-id="a3569-113">Service incidents</span></span>

<span data-ttu-id="a3569-p105">サービス インシデントとは、サービスの提供に影響を与えるイベントのことです。考えられるサービス インシデントの原因には、Microsoft のデータ センター内のハードウェアやソフトウェアの障害、お客様と Microsoft 間のネットワーク接続の障害、あるいは火災、洪水、その他の地域災害によるデータ センターの重大な被害などがあります。大部分のサービス インシデントは、Microsoft の技術とプロセス ソリューションを利用して短時間で解決されます。ただし、一部のインシデントはより重大で、サービス停止の期間が長くなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a3569-p105">A service incident is an event that affects the delivery of a service. Service incidents may be caused by hardware or software failure in the Microsoft data center, a faulty network connection between the customer and Microsoft, or a major data center challenge such as fire, flood, or regional catastrophe. Most service incidents can be addressed using Microsoft technology and process solutions and are resolved within a short time. However, some service incidents are more serious and can lead to longer term outages.</span></span>
  
<span data-ttu-id="a3569-118">サービスが使用不能になる場合の通知には 2 種類あります。</span><span class="sxs-lookup"><span data-stu-id="a3569-118">There are two types of notifications about times when services may not be available:</span></span>
  
- <span data-ttu-id="a3569-p106">**計画メンテナンス イベント:** 計画メンテナンスは、インフラストラクチャおよびソフトウェア アプリケーションに対して Microsoft が開始する通常のサービス更新です。計画メンテナンス通知は、Office 365 のサービスに影響を与える可能性があるサービス作業についてお客様に通知します。計画メンテナンスについては必ず、遅くとも 5 日前までに Office 365 管理ポータルのメッセージ センターで告知されます。メンテナンスは通常、地域別の時間帯に基づいて、過去の傾向からサービスの利用率が最も低くなる期間に計画されます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p106">**Planned maintenance events:** Planned maintenance is regular Microsoft-initiated service updates to the infrastructure and software applications. Planned maintenance notifications inform customers about service work that might affect the functionality of an Office 365 service. Customers are notified no later than five days in advance of all planned maintenance through Message Center on the Office 365 Admin Portal. Microsoft typically plans maintenance for times when service usage is historically at its lowest based on regional time zones.</span></span> 
    
- <span data-ttu-id="a3569-123">**未計画のダウンタイム:** 未計画のサービス インシデントは、Office 365 スイートのいずれかのサービスが使用できないか応答しない場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="a3569-123">**Unplanned downtime:** Unplanned service incidents occur when one of the services in the Office 365 suite is unavailable or unresponsive.</span></span> 
    
## <a name="notification-policy"></a><span data-ttu-id="a3569-124">通知ポリシー</span><span class="sxs-lookup"><span data-stu-id="a3569-124">Notification policy</span></span>

<span data-ttu-id="a3569-p107">Microsoft は、サービス インシデントが発生した場合、タイムリーで、対象を指定した、正確なコミュニケーションがお客様にとって不可欠であると認識しています。Microsoft は、Office 365 管理ポータルでテナント固有のサービス正常性ダッシュボード (SHD) を更新して Office 365 の管理者に、通知します。サービス インシデントの更新は時間単位で実行されるか、または異なる間隔が必要な場合は、SHD 通信の投稿に記載されます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p107">When a service incident occurs, Microsoft recognizes that timely, targeted, and accurate communications are critical for customers. Microsoft notifies Office 365 administrators by updating the tenant-specific Service Health Dashboard (SHD) on the Office 365 Admin Portal. Service incident updates are provided on an hourly cadence or, if a different cadence is required, it will be stated in the SHD communication posting.</span></span> 
  
## <a name="service-health-communication-channels"></a><span data-ttu-id="a3569-128">サービス正常性の通信チャネル</span><span class="sxs-lookup"><span data-stu-id="a3569-128">Service Health Communication Channels</span></span>

### <a name="office-365-admin-app"></a><span data-ttu-id="a3569-129">Office 365 管理アプリ</span><span class="sxs-lookup"><span data-stu-id="a3569-129">Office 365 Admin App</span></span>

<span data-ttu-id="a3569-p108">Office 365 テナント管理者向けの管理アプリには、外出先で組織の Office 365 サービスの状態に接続する機能が設けられています。Office 365 テナントの管理者は、モバイル デバイスにサービス正常性の情報とメンテナンス状態の更新情報を表示できます。詳細については、「[管理アプリの FAQ](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx)」にアクセスしてください。</span><span class="sxs-lookup"><span data-stu-id="a3569-p108">The Admin App for Office 365 tenant administrators gives you the ability to connect with your organization's Office 365 service status on the go. Office 365 tenant administrators will have the ability to view service health information and maintenance status updates from their mobile devices. For more information, visit the [Admin App FAQ](https://community.office365.com/en-us/w/manage/office-365-admin-app-faq.aspx).</span></span>
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a><span data-ttu-id="a3569-133">Microsoft System Center 2012 R2 用 Office 365 管理パック</span><span class="sxs-lookup"><span data-stu-id="a3569-133">Office 365 Management Pack for Microsoft System Center 2012 R2</span></span>

<span data-ttu-id="a3569-p109">Microsoft System Center は、データ センター、クライアント デバイス、ハイブリッド クラウド IT 環境の管理に役立つ統合された管理プラットフォームです。System Center を使用する Office 365 管理者は、Office 365 管理パックをインポートできるようになりました。それにより、System Center で Operations Manager 内のすべてのサービス通信を表示することが可能になります。このツールを使用すると、サブスクライブ済みサービス、アクティブおよび解決済みサービス インシデント、およびメッセージ センターとの通信の状態にアクセスできます。詳細については、ブログ投稿「[新しい Office 365 管理ツール](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)」にアクセスしてください。</span><span class="sxs-lookup"><span data-stu-id="a3569-p109">Microsoft System Center is an integrated management platform that helps you manage data center, client devices, and hybrid cloud IT environments. Office 365 administrators who use System Center now have the option to import the Office 365 Management Pack, which enables them to view all service communications within Operations Manager in System Center. Using this tool gives you access to the status of your subscribed services, active and resolved service incidents, and your Message Center communications. For more information, visit the [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
### <a name="office-365-service-communications-api"></a><span data-ttu-id="a3569-138">Office 365 サービス通信 API</span><span class="sxs-lookup"><span data-stu-id="a3569-138">Office 365 Service Communications API</span></span>

<span data-ttu-id="a3569-p110">Office 365 サービス通信 API を使用すると、思いどおりに Office 365 サービス通信にアクセスできます。この新しい管理ツールを使用すると、Office 365 サービス通信を作成し、ツールを接続できるようになります。これにより、環境の監視を簡略化する可能性が高まります。サービス通信 API を使用すると、環境内で以下を監視できるようになります。</span><span class="sxs-lookup"><span data-stu-id="a3569-p110">The Office 365 Service Communications API enables you to access Office 365 service communications the way you want. With this new admin tool, you now have the ability to create or connect your tools to Office 365 service communications, potentially simplifying how you monitor your environment. The Service Communications API enables you to monitor the following in your environment:</span></span>
  
- <span data-ttu-id="a3569-142">リアルタイムのサービスの正常性</span><span class="sxs-lookup"><span data-stu-id="a3569-142">Real-time service health</span></span>
    
- <span data-ttu-id="a3569-143">メッセージ センターの通信</span><span class="sxs-lookup"><span data-stu-id="a3569-143">Message Center communications</span></span>
    
- <span data-ttu-id="a3569-144">計画済みメンテナンスの通知</span><span class="sxs-lookup"><span data-stu-id="a3569-144">Planned maintenance notifications</span></span>
    
<span data-ttu-id="a3569-145">詳細については、ブログ投稿「[新しい Office 365 管理ツール](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/)」にアクセスしてください。</span><span class="sxs-lookup"><span data-stu-id="a3569-145">For more information, visit the [New Office 365 admin tools](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
## <a name="post-incident-reviews"></a><span data-ttu-id="a3569-146">インシデントの事後レビュー</span><span class="sxs-lookup"><span data-stu-id="a3569-146">Post-incident reviews</span></span>

<span data-ttu-id="a3569-147">継続的な機能向上に対する Microsoft の取り組みには、お客様に影響を与える計画外のサービス インシデントを分析し、再発生をできる限りなくすことが含まれます。</span><span class="sxs-lookup"><span data-stu-id="a3569-147">Microsoft's commitment to continuous improvement involves analysis of unplanned customer-impacting service incidents to minimize future recurrence.</span></span> 
  
<span data-ttu-id="a3569-148">計画外のサービス インシデントは、SLA サービスで定義されたサービスの使用に影響を与える、マルチ テナント サービスの中断として定義され、サービスの正常性ダッシュボードでそのように宣言されています。</span><span class="sxs-lookup"><span data-stu-id="a3569-148">Unplanned service incidents are defined as multi-tenant service disruptions that impact service usage as defined by our service SLAs, and have been declared as such on the Service Health Dashboard.</span></span>
  
 <span data-ttu-id="a3569-p111"> 大多数の組織全体に広範で大きな影響があった、お客様に影響を与える計画外のサービス インシデントに対して、暫定のインシデントの事後レビュー (PIR) が、インシデントの解決から 48 時間以内にサービスの正常性ダッシュボード経由で配信されます。続いて最終的な PIR が 5 営業日以内に配信されます。この詳細な PIR レポートには以下の項目が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a3569-p111">For unplanned customer-impacting service incidents in which there was broad and noticeable impact across a large number of organizations, a preliminary Post-Incident Review (PIR) will be delivered via your Service Health Dashboard within 48 hours of incident resolution, followed by a final PIR within five business days. The detailed PIR report includes:</span></span> 
  
- <span data-ttu-id="a3569-151">ユーザー エクスペリエンスや顧客への影響</span><span class="sxs-lookup"><span data-stu-id="a3569-151">User experience and customer impact</span></span>
    
- <span data-ttu-id="a3569-152">インシデントの開始と終了の日付と時刻</span><span class="sxs-lookup"><span data-stu-id="a3569-152">Incident start and end date/time</span></span>
    
- <span data-ttu-id="a3569-153">影響と解決策の対策の詳細なタイムライン</span><span class="sxs-lookup"><span data-stu-id="a3569-153">Detailed timeline of impact and resolution measures</span></span>
    
- <span data-ttu-id="a3569-154">継続的な改善のためになされる根本原因分析と対策</span><span class="sxs-lookup"><span data-stu-id="a3569-154">Root cause analysis and actions being taken for continuous improvement</span></span>
    
<span data-ttu-id="a3569-p112">他のすべてのサービス インシデントの場合、サービスの正常性ダッシュボードは、イベントの最終概要、事前の根本原因、開始時刻と終了時刻、および次の手順の詳細情報を含む、インシデント完了の概要を提供します。このカテゴリのサービス インシデントでは、PIR は生成されません。</span><span class="sxs-lookup"><span data-stu-id="a3569-p112">For all other service incidents, the Service Health Dashboard will provide an incident closure summary including a final summary of the event, preliminary root cause, start and end times, and information detailing next steps. For this category of service incident, a PIR will not be generated.</span></span> 
  
## <a name="service-continuity"></a><span data-ttu-id="a3569-157">サービス継続性</span><span class="sxs-lookup"><span data-stu-id="a3569-157">Service Continuity</span></span>

<span data-ttu-id="a3569-p113">Microsoft Office 365 は、ピーク時のサービスのパフォーマンスを維持できる回復力の高いシステムによって提供されます。サービス継続性の提供は、Office 365 システムの設計の一部です。これらの備えにより、Office 365 は、ハードウェアやアプリケーションの障害、データ破損、ユーザーに影響を与えるその他のインシデントといった予期しない事態から迅速に復旧できます。サービス継続性ソリューションは、重大なサービス停止 (たとえば、自然災害やインシデントによって、ある Microsoft のデータ センター全体が使用不能になった場合など) の際にも適用されます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p113">Microsoft Office 365 offerings are delivered by highly resilient systems that help to maintain peak service performance. Service continuity provisions are part of the Office 365 system design. These provisions enable Office 365 to recover quickly from unexpected events such as hardware or application failure, data corruption, or other incidents that affect users. These service continuity solutions also apply during catastrophic outages (for example, natural disasters or an incident within a Microsoft data center that renders the entire data center inoperable).</span></span>
  
<span data-ttu-id="a3569-p114">致命的な障害から復旧した後、データ センターの完全な冗長性がサービスに復元されるまで一定の時間がかかることがあります。たとえば、データ センター 1 に障害が発生すると、サービスがデータ センター 2 のリソースによって復元されます。ただし、データ センター 1 の復元されたリソースまたはデータ センター 3 の新規リソースによって、データ センター 2 のサービスの継続性がサポートされるまで時間がかかります。Office 365 の[サービス レベル契約](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA) は、この期間に適用されます。21Vianet が運用している Office 365 には、別の SLA があります。詳細については、 [21Vianet サイト](http://www.21vbluecloud.com/office365/O365-SLA/)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="a3569-p114">Note that after recovery from catastrophic outages, there may be a period of time before full data center redundancy is restored for the service. For example, if Data Center 1 fails, services are restored by resources in Data Center 2. However, there may be a period of time until services in Data Center 2 have service continuity support either by restored resources in Data Center 1, or new resources in Data Center 3. The Office 365 [Service Level Agreement](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) (SLA) applies during this time. Office 365 operated by 21Vianet has a different SLA. See the [21Vianet site](http://www.21vbluecloud.com/office365/O365-SLA/) for more information.</span></span> 
  
## <a name="ensuring-data-availability"></a><span data-ttu-id="a3569-168">データ可用性の確保</span><span class="sxs-lookup"><span data-stu-id="a3569-168">Ensuring data availability</span></span>

<span data-ttu-id="a3569-169">Microsoft は、以下の機能によって、お客様がいつでも必要なときにデータを利用できるようにしています。</span><span class="sxs-lookup"><span data-stu-id="a3569-169">Microsoft ensures that customer data is available whenever it is needed through the following features:</span></span>
  
- <span data-ttu-id="a3569-p115">**データ ストレージと冗長性:** お客様のデータは、信頼性の高いデータ保護機能を備えた冗長環境に保管されます。これにより可用性とビジネス継続性が確保され、迅速な復旧が可能です。データ冗長性は複数レベルで実装されており、ローカルのディスク障害に対処する冗長ディスク構成から、遠隔地のデータ センターへのデータのフル レプリケーションまでをサポートします。</span><span class="sxs-lookup"><span data-stu-id="a3569-p115">**Data storage and redundancy:** Customer data is stored in a redundant environment with robust data protection capabilities to enable availability, business continuity, and rapid recovery. Multiple levels of data redundancy are implemented, ranging from redundant disks to guard against local disk failure to continuous, full data replication to a geographically diverse data center.</span></span> 
    
- <span data-ttu-id="a3569-172">**データの監視:** Office 365 のサービスは、以下によって高レベルのパフォーマンスを維持します。</span><span class="sxs-lookup"><span data-stu-id="a3569-172">**Data monitoring:** Office 365 services maintain high levels of performance by:</span></span> 
    
  - <span data-ttu-id="a3569-173">**データベースの監視:**</span><span class="sxs-lookup"><span data-stu-id="a3569-173">**Monitoring databases:**</span></span>
    
  - <span data-ttu-id="a3569-174">ブロックされたプロセス</span><span class="sxs-lookup"><span data-stu-id="a3569-174">Blocked processes</span></span>
    
  - <span data-ttu-id="a3569-175">パケット損失</span><span class="sxs-lookup"><span data-stu-id="a3569-175">Packet loss</span></span>
    
  - <span data-ttu-id="a3569-176">キューに登録されたプロセス</span><span class="sxs-lookup"><span data-stu-id="a3569-176">Queued processes</span></span>
    
  - <span data-ttu-id="a3569-177">クエリの待機時間</span><span class="sxs-lookup"><span data-stu-id="a3569-177">Query latency</span></span>
    
- <span data-ttu-id="a3569-178">**予防保守の実行:** 予防保守には、データベースの整合性チェック、定期的なデータ圧縮、およびエラー ログのレビューなどがあります。</span><span class="sxs-lookup"><span data-stu-id="a3569-178">**Completing preventative maintenance:** Preventative maintenance includes database consistency checks, periodic data compression, and error log reviews.</span></span> 
    
## <a name="support"></a><span data-ttu-id="a3569-179">サポート</span><span class="sxs-lookup"><span data-stu-id="a3569-179">Support</span></span>

<span data-ttu-id="a3569-p116">Office 365 の開発および運用チームは、お客様にビジネス継続性を提供するうえで重要な役割を担う専門の Office 365 サポート組織がサポートしています。サポート スタッフはサービスおよびサービスに関連するアプリケーションに精通しており、Microsoft 社内のアーキテクチャ、開発、テストの専門家と直接やり取りします。</span><span class="sxs-lookup"><span data-stu-id="a3569-p116">The Office 365 development and operations teams are complemented by a dedicated Office 365 support organization, which plays an important role in providing customers with business continuity. Support staff has a deep knowledge of the service and its associated applications as well as direct access to Microsoft experts in architecture, development, and testing.</span></span>
  
<span data-ttu-id="a3569-p117">サポート組織は運用および製品開発チームと密接に協力することで、迅速な問題解決を実現し、お客様の声を反映するための窓口になります。お客様からのフィードバックは、計画、開発、運用プロセスに役立てられます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p117">The support organization closely aligns with operations and product development, offers fast resolution times and provides a channel for customers' voices to be heard. Feedback from customers provides input to the planning, development, and operations processes.</span></span>
  
- <span data-ttu-id="a3569-p118">**オンライン問題追跡:** お客様は、問題が対応されていることを把握し、タイムリーに解決されていることを追跡できる必要があります。Office 365 ポータルは、サポート用に単一の Web ベースのインターフェイスを提供します。お客様はこのポータルを使用することで、サービス リクエストを追加および監視するとともに、Microsoft サポート チームからのフィードバックを受信できます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p118">**Online issue tracking:** Customers need to know that their issues are being addressed, and they need to be able to track timely resolution. The Office 365 portal provides a single web-based interface for support. Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams.</span></span> 
    
- <span data-ttu-id="a3569-187">**スタッフによる継続的なサポートでバックアップするセルフヘルプ:** Office 365 は、お客様が Microsoft によるサポートの必要なくサービス関連の問題を解決できるセルフヘルプ リソースおよびツールを幅広く提供しています。</span><span class="sxs-lookup"><span data-stu-id="a3569-187">**Self-help, backed by continuous staff support:** Office 365 offers a wide range of self-help resources and tools that can help customers to resolve service-related issues without requiring Microsoft support.</span></span> 
    
<span data-ttu-id="a3569-p119">お客様は、サービス リクエストを作成する前にサポート技術情報の記事や FAQ を参照することで、よくある問題に関するヘルプを即座に得ることができます。これらのリソースは絶えず最新の情報に更新され、既知の問題に対する解決策をタイムリーに提供します。また、サポート担当者による対応が必要な問題が発生した場合は、電話または管理ポータルを通じて、24 時間 365 日体制のスタッフによる迅速な支援を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="a3569-p119">Before customers enter service requests, they can access knowledge base articles and FAQs that provide immediate help with the most common problems. These resources are continually updated with the latest information, which helps avoid delays by providing solutions to known issues. However, when an issue arises that needs the help of a support professional; staff members are available for immediate assistance by telephone and through the administration portal 24 hours a day, 7 days a week.</span></span>
  
<span data-ttu-id="a3569-191">サポートの詳細については、「[サポート](https://technet.microsoft.com/en-us/library/office-365-support.aspx)」トピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="a3569-191">For more information about support, see the [Support](https://technet.microsoft.com/en-us/library/office-365-support.aspx) topic.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="a3569-192">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="a3569-192">Feature availability</span></span>

<span data-ttu-id="a3569-193">さまざまな Office 365 のプランで利用できる機能を確認するには、「[Office 365 プラットフォーム サービスの説明](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a3569-193">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

