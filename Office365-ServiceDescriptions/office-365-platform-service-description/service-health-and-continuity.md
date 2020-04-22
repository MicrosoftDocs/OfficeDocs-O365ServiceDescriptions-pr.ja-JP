---
title: サービスの正常性および継続性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft 管理者は、サービスの状態を表示し、メンテナンスがスケジュールされているときに確認できます。 サービス正常性情報は、サインインすることでいつでも利用できます。
ms.openlocfilehash: 6ac04087599b2ddbe212a1f292b06b7d5b22a378
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640240"
---
# <a name="service-health-and-continuity"></a><span data-ttu-id="37c4a-104">サービスの正常性および継続性</span><span class="sxs-lookup"><span data-stu-id="37c4a-104">Service health and continuity</span></span>

<span data-ttu-id="37c4a-105">Microsoft 管理者は、サービスの状態を表示し、メンテナンスがスケジュールされているときに確認できます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-105">Microsoft admins can view the status of services and find out when maintenance is scheduled.</span></span> <span data-ttu-id="37c4a-106">サービス正常性情報は、サインインすることでいつでも利用できます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-106">Service health information is available at any time by signing in.</span></span>
  
> [!NOTE]
> <span data-ttu-id="37c4a-107">21Vianet が運用している Office 365 を使用している場合、以下の情報は適用できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="37c4a-107">If you are using Office 365 operated by 21Vianet, some of the information below might not apply.</span></span> <span data-ttu-id="37c4a-108">代わりに、「[21Vianet のサービス レベル契約](https://www.21vbluecloud.com/office365/O365-SLA/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-108">Instead, see the [21Vianet service level agreement](https://www.21vbluecloud.com/office365/O365-SLA/).</span></span> 
  
## <a name="view-status-of-services"></a><span data-ttu-id="37c4a-109">サービスの状態を表示</span><span class="sxs-lookup"><span data-stu-id="37c4a-109">View Status of Services</span></span>

<span data-ttu-id="37c4a-p104">[サービスの正常性] セクションには、サービスの現在の状態と、サービスの中断と停止に関する詳細が表示されます。予定されているメンテナンス情報は、メッセージセンターで利用できます。詳細については、「[サービスの状態を表示する](https://docs.microsoft.com/office365/enterprise/view-service-health)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p104">The Service health section shows the current status of the service and details about service disruptions and outages. Planned maintenance information is available on the Message Center. For more information, see [View the status of your services](https://docs.microsoft.com/office365/enterprise/view-service-health).</span></span> 
  
## <a name="service-incidents"></a><span data-ttu-id="37c4a-113">サービス インシデント</span><span class="sxs-lookup"><span data-stu-id="37c4a-113">Service incidents</span></span>

<span data-ttu-id="37c4a-p105">サービス インシデントとは、サービスの提供に影響を与えるイベントのことです。考えられるサービス インシデントの原因には、Microsoft のデータ センター内のハードウェアやソフトウェアの障害、お客様と Microsoft 間のネットワーク接続の障害、あるいは火災、洪水、その他の地域災害によるデータ センターの重大な被害などがあります。大部分のサービス インシデントは、Microsoft の技術とプロセス ソリューションを利用して短時間で解決されます。ただし、一部のインシデントはより重大で、サービス停止の期間が長くなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p105">A service incident is an event that affects the delivery of a service. Service incidents may be caused by hardware or software failure in the Microsoft data center, a faulty network connection between the customer and Microsoft, or a major data center challenge such as fire, flood, or regional catastrophe. Most service incidents can be addressed using Microsoft technology and process solutions and are resolved within a short time. However, some service incidents are more serious and can lead to longer term outages.</span></span>
  
<span data-ttu-id="37c4a-118">サービスが使用不能になる場合の通知には 2 種類あります。</span><span class="sxs-lookup"><span data-stu-id="37c4a-118">There are two types of notifications about times when services may not be available:</span></span>
  
- <span data-ttu-id="37c4a-p106">計画された**メンテナンスイベント:** 計画されたメンテナンスは、インフラストラクチャおよびソフトウェアアプリケーションに対して、Microsoft が定期的に開始するサービスの更新です。計画されたメンテナンス通知は、Microsoft サービスの機能に影響を与える可能性があるサービス作業についてお客様に通知します。お客様は、Microsoft 365 管理センターのメッセージセンターを使用して、計画されたすべてのメンテナンスの前に、5日後に通知されます。Microsoft は、通常、地域のタイムゾーンに基づいてサービスの利用状況が最も少ない時間帯にメンテナンスを計画します。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p106">**Planned maintenance events:** Planned maintenance is regular Microsoft-initiated service updates to the infrastructure and software applications. Planned maintenance notifications inform customers about service work that might affect the functionality of a Microsoft service. Customers are notified no later than five days in advance of all planned maintenance through Message Center on the Microsoft 365 admin center. Microsoft typically plans maintenance for times when service usage is historically at its lowest based on regional time zones.</span></span> 
    
- <span data-ttu-id="37c4a-123">**予定外のダウンタイム:** 計画外のサービスインシデントは、いずれかのサービスが使用できないか応答しない場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="37c4a-123">**Unplanned downtime:** Unplanned service incidents occur when one of the services is unavailable or unresponsive.</span></span> 

### <a name="recent-worldwide-uptimes"></a><span data-ttu-id="37c4a-124">全世界での最近の稼働時間</span><span class="sxs-lookup"><span data-stu-id="37c4a-124">Recent worldwide uptimes</span></span>

<span data-ttu-id="37c4a-125">クラウドサービスに移行する場合は、何が起こっているのかを知ることができなくなるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="37c4a-125">Moving to a cloud service shouldn't mean losing the ability to know what's going on.</span></span> <span data-ttu-id="37c4a-126">Office 365 では、そうではありません。</span><span class="sxs-lookup"><span data-stu-id="37c4a-126">With Office 365, it doesn't.</span></span> <span data-ttu-id="37c4a-127">Microsoft が目標としているのは運用における透明性なので、お客様はサービスの状態の監視や問題の追跡を行うことができます。また、サービスの利用状況を過去にさかのぼって確認することもできます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-127">We aim to be transparent in our operations so you can monitor the state of your service, track issues, and have a historical view of availability.</span></span> <span data-ttu-id="37c4a-128">下の表は、全世界の稼働時間データを示しています。</span><span class="sxs-lookup"><span data-stu-id="37c4a-128">The following tables show recent worldwide uptime data.</span></span>

<br/>

|<span data-ttu-id="37c4a-129">**2019**</span><span class="sxs-lookup"><span data-stu-id="37c4a-129">**2019**</span></span> <br/> ||||
|:-----|:-----|:-----|:-----|
| <span data-ttu-id="37c4a-130">**Q1**</span><span class="sxs-lookup"><span data-stu-id="37c4a-130">**Q1**</span></span> <br/> | <span data-ttu-id="37c4a-131">**Q2**</span><span class="sxs-lookup"><span data-stu-id="37c4a-131">**Q2**</span></span> <br/> |<span data-ttu-id="37c4a-132">**Q3**</span><span class="sxs-lookup"><span data-stu-id="37c4a-132">**Q3**</span></span> <br/> |<span data-ttu-id="37c4a-133">**Q4**</span><span class="sxs-lookup"><span data-stu-id="37c4a-133">**Q4**</span></span> <br/> |
| <span data-ttu-id="37c4a-134">99.97%</span><span class="sxs-lookup"><span data-stu-id="37c4a-134">99.97%</span></span> <br/> | <span data-ttu-id="37c4a-135">99.97%</span><span class="sxs-lookup"><span data-stu-id="37c4a-135">99.97%</span></span> <br/> | <span data-ttu-id="37c4a-136">99.98%</span><span class="sxs-lookup"><span data-stu-id="37c4a-136">99.98%</span></span> <br/> | <span data-ttu-id="37c4a-137">99.98%</span><span class="sxs-lookup"><span data-stu-id="37c4a-137">99.98%</span></span> <br/> |

<br/>

|<span data-ttu-id="37c4a-138">**2018**</span><span class="sxs-lookup"><span data-stu-id="37c4a-138">**2018**</span></span> <br/>||||
|:-----|:-----|:-----|:-----|
| <span data-ttu-id="37c4a-139">**Q1**</span><span class="sxs-lookup"><span data-stu-id="37c4a-139">**Q1**</span></span> <br/> | <span data-ttu-id="37c4a-140">**Q2**</span><span class="sxs-lookup"><span data-stu-id="37c4a-140">**Q2**</span></span> <br/> |<span data-ttu-id="37c4a-141">**Q3**</span><span class="sxs-lookup"><span data-stu-id="37c4a-141">**Q3**</span></span> <br/> |<span data-ttu-id="37c4a-142">**Q4**</span><span class="sxs-lookup"><span data-stu-id="37c4a-142">**Q4**</span></span> <br/> |
| <span data-ttu-id="37c4a-143">99.99%</span><span class="sxs-lookup"><span data-stu-id="37c4a-143">99.99%</span></span> <br/> | <span data-ttu-id="37c4a-144">99.98%</span><span class="sxs-lookup"><span data-stu-id="37c4a-144">99.98%</span></span> <br/> | <span data-ttu-id="37c4a-145">99.97%</span><span class="sxs-lookup"><span data-stu-id="37c4a-145">99.97%</span></span> <br/> | <span data-ttu-id="37c4a-146">99.98%</span><span class="sxs-lookup"><span data-stu-id="37c4a-146">99.98%</span></span> <br/> |

<br/>

|<span data-ttu-id="37c4a-147">**2017**</span><span class="sxs-lookup"><span data-stu-id="37c4a-147">**2017**</span></span> <br/> ||||
|:-----|:-----|:-----|:-----|
| <span data-ttu-id="37c4a-148">**Q1**</span><span class="sxs-lookup"><span data-stu-id="37c4a-148">**Q1**</span></span> <br/> | <span data-ttu-id="37c4a-149">**Q2**</span><span class="sxs-lookup"><span data-stu-id="37c4a-149">**Q2**</span></span> <br/> |<span data-ttu-id="37c4a-150">**Q3**</span><span class="sxs-lookup"><span data-stu-id="37c4a-150">**Q3**</span></span> <br/> |<span data-ttu-id="37c4a-151">**Q4**</span><span class="sxs-lookup"><span data-stu-id="37c4a-151">**Q4**</span></span> <br/> |
| <span data-ttu-id="37c4a-152">99.99%</span><span class="sxs-lookup"><span data-stu-id="37c4a-152">99.99%</span></span> <br/> | <span data-ttu-id="37c4a-153">99.97%</span><span class="sxs-lookup"><span data-stu-id="37c4a-153">99.97%</span></span> <br/> | <span data-ttu-id="37c4a-154">99.98%</span><span class="sxs-lookup"><span data-stu-id="37c4a-154">99.98%</span></span> <br/> | <span data-ttu-id="37c4a-155">99.99%</span><span class="sxs-lookup"><span data-stu-id="37c4a-155">99.99%</span></span> <br/> |

<br/>

## <a name="notification-policy"></a><span data-ttu-id="37c4a-156">通知ポリシー</span><span class="sxs-lookup"><span data-stu-id="37c4a-156">Notification policy</span></span>

<span data-ttu-id="37c4a-p108">サービスインシデントが発生した場合、Microsoft は、お客様にとって適時かつ正確で正確なコミュニケーションが重要であることを認識しています。Microsoft は、Microsoft 365 管理センターでテナント固有のサービス正常性ダッシュボード (SHD) を更新して管理者に通知します。サービスインシデントの更新は時間単位で提供されるか、別のリズムが必要な場合は、SHD の通信の投稿で示されます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p108">When a service incident occurs, Microsoft recognizes that timely, targeted, and accurate communications are critical for customers. Microsoft notifies administrators by updating the tenant-specific Service Health Dashboard (SHD) on the Microsoft 365 admin center. Service incident updates are provided on an hourly cadence or, if a different cadence is required, it will be stated in the SHD communication posting.</span></span> 
  
## <a name="service-health-communication-channels"></a><span data-ttu-id="37c4a-160">サービス正常性の通信チャネル</span><span class="sxs-lookup"><span data-stu-id="37c4a-160">Service Health Communication Channels</span></span>

### <a name="admin-app"></a><span data-ttu-id="37c4a-161">Admin アプリ</span><span class="sxs-lookup"><span data-stu-id="37c4a-161">Admin App</span></span>

<span data-ttu-id="37c4a-p109">組織管理者用の管理者アプリを使用すると、組織の Microsoft サービスの状態を外出先から接続することができます。Microsoft 管理者は、モバイルデバイスからサービスの正常性情報とメンテナンス状態の更新を表示することができます。詳細については、「[管理者アプリの FAQ](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p109">The Admin App for organization administrators gives you the ability to connect with your organization's Microsoft service status on the go. Microsoft administrators will have the ability to view service health information and maintenance status updates from their mobile devices. For more information, visit the [Admin App FAQ](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).</span></span>
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a><span data-ttu-id="37c4a-165">Microsoft System Center 2012 R2 用 Office 365 管理パック</span><span class="sxs-lookup"><span data-stu-id="37c4a-165">Office 365 Management Pack for Microsoft System Center 2012 R2</span></span>

<span data-ttu-id="37c4a-166">Microsoft System Center は、データ センター、クライアント デバイス、およびハイブリッド型のクラウド IT 環境の管理に役立つ統合された管理プラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="37c4a-166">Microsoft System Center is an integrated management platform that helps you manage data center, client devices, and hybrid cloud IT environments.</span></span> <span data-ttu-id="37c4a-167">System Center を使用している Microsoft 管理者は、Office 365 管理パックをインポートすることができます。これにより、System Center の Operations Manager 内のすべてのサービス通信が表示されます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-167">Microsoft administrators who use System Center now have the option to import the Office 365 Management Pack, which lets them view all service communications within Operations Manager in System Center.</span></span> <span data-ttu-id="37c4a-168">このツールを使用すると、サブスクライブ済みサービス、アクティブおよび解決済みサービス インシデント、およびメッセージ センターとの通信の状態にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-168">Using this tool gives you access to the status of your subscribed services, active and resolved service incidents, and your Message Center communications.</span></span> <span data-ttu-id="37c4a-169">詳細については、「[新しい Office 365 管理ツール](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/) 」のブログ投稿を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-169">For more information, visit the [New Office 365 admin tools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
### <a name="office-365-service-communications-api"></a><span data-ttu-id="37c4a-170">Office 365 サービス通信 API</span><span class="sxs-lookup"><span data-stu-id="37c4a-170">Office 365 Service Communications API</span></span>

<span data-ttu-id="37c4a-171">Office 365 サービス通信 API を使用すると、目的の方法でサービス通信にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-171">The Office 365 Service Communications API lets you access service communications the way you want.</span></span> <span data-ttu-id="37c4a-172">この新しい管理ツールを使用すると、サービス通信用にツールを作成または接続できるようになり、環境の監視が容易になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="37c4a-172">With this new admin tool, you now have the ability to create or connect your tools to service communications, potentially simplifying how you monitor your environment.</span></span> <span data-ttu-id="37c4a-173">サービス通信 API を使用することにより、環境内で以下を監視できます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-173">The Service Communications API lets you monitor the following in your environment:</span></span>
  
- <span data-ttu-id="37c4a-174">リアルタイムのサービスの正常性</span><span class="sxs-lookup"><span data-stu-id="37c4a-174">Real-time service health</span></span>
    
- <span data-ttu-id="37c4a-175">メッセージ センターの通信</span><span class="sxs-lookup"><span data-stu-id="37c4a-175">Message Center communications</span></span>
    
- <span data-ttu-id="37c4a-176">計画済みメンテナンスの通知</span><span class="sxs-lookup"><span data-stu-id="37c4a-176">Planned maintenance notifications</span></span>
    
<span data-ttu-id="37c4a-177">詳細については、「[新しい管理ツール](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/)のブログ投稿」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-177">For more information, visit the [New admin tools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/) blog post.</span></span> 
  
## <a name="post-incident-reviews"></a><span data-ttu-id="37c4a-178">インシデントの事後レビュー</span><span class="sxs-lookup"><span data-stu-id="37c4a-178">Post-incident reviews</span></span>

<span data-ttu-id="37c4a-179">継続的な機能向上に対する Microsoft の取り組みには、お客様に影響を与える計画外のサービス インシデントを分析し、再発生をできる限りなくすことが含まれます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-179">Microsoft's commitment to continuous improvement involves analysis of unplanned customer-impacting service incidents to minimize future recurrence.</span></span> 
  
<span data-ttu-id="37c4a-180">計画外のサービス インシデントは、SLA サービスで定義されたサービスの使用に影響を与える、マルチ テナント サービスの中断として定義され、サービスの正常性ダッシュボードでそのように宣言されています。</span><span class="sxs-lookup"><span data-stu-id="37c4a-180">Unplanned service incidents are defined as multi-tenant service disruptions that impact service usage as defined by our service SLAs, and have been declared as such on the Service Health Dashboard.</span></span>
  
 <span data-ttu-id="37c4a-p112">大多数の組織全体に広範で大きな影響があった、お客様に影響を与える計画外のサービス インシデントに対して、暫定のインシデントの事後レビュー (PIR) が、インシデントの解決から 48 時間以内にサービスの正常性ダッシュボード経由で配信されます。続いて最終的な PIR が 5 営業日以内に配信されます。この詳細な PIR レポートには以下の項目が含まれています。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p112">For unplanned customer-impacting service incidents in which there was broad and noticeable impact across a large number of organizations, a preliminary Post-Incident Review (PIR) will be delivered via your Service Health Dashboard within 48 hours of incident resolution, followed by a final PIR within five business days. The detailed PIR report includes:</span></span> 
  
- <span data-ttu-id="37c4a-183">ユーザー エクスペリエンスや顧客への影響</span><span class="sxs-lookup"><span data-stu-id="37c4a-183">User experience and customer impact</span></span>
    
- <span data-ttu-id="37c4a-184">インシデントの開始と終了の日付と時刻</span><span class="sxs-lookup"><span data-stu-id="37c4a-184">Incident start and end date/time</span></span>
    
- <span data-ttu-id="37c4a-185">影響と解決策の対策の詳細なタイムライン</span><span class="sxs-lookup"><span data-stu-id="37c4a-185">Detailed timeline of impact and resolution measures</span></span>
    
- <span data-ttu-id="37c4a-186">継続的な改善のためになされる根本原因分析と対策</span><span class="sxs-lookup"><span data-stu-id="37c4a-186">Root cause analysis and actions being taken for continuous improvement</span></span>
    
<span data-ttu-id="37c4a-p113">他のすべてのサービス インシデントの場合、サービスの正常性ダッシュボードは、イベントの最終概要、事前の根本原因、開始時刻と終了時刻、および次の手順の詳細情報を含む、インシデント完了の概要を提供します。このカテゴリのサービス インシデントでは、PIR は生成されません。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p113">For all other service incidents, the Service Health Dashboard will provide an incident closure summary including a final summary of the event, preliminary root cause, start and end times, and information detailing next steps. For this category of service incident, a PIR will not be generated.</span></span> 
  
## <a name="service-continuity"></a><span data-ttu-id="37c4a-189">サービス継続性</span><span class="sxs-lookup"><span data-stu-id="37c4a-189">Service Continuity</span></span>

<span data-ttu-id="37c4a-p114">Microsoft オファーリングは、サービスのピーク時のパフォーマンスを維持するために役立つ回復力の高いシステムによって提供されます。サービス継続性の条項は、システム設計の一部です。これらの規定により、Microsoft は、ハードウェアやアプリケーションの障害、データの破損、ユーザーに影響を与えるその他のインシデントなどの予期しないイベントから迅速に復旧できます。これらのサービス継続性ソリューションは、壊滅的な停止 (たとえば、自然災害や、Microsoft データセンター内でデータセンター全体を表示することができないインシデントなど) にも適用されます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p114">Microsoft offerings are delivered by highly resilient systems that help to maintain peak service performance. Service continuity provisions are part of the system design. These provisions enable Microsoft to recover quickly from unexpected events such as hardware or application failure, data corruption, or other incidents that affect users. These service continuity solutions also apply during catastrophic outages (for example, natural disasters or an incident within a Microsoft data center that renders the entire data center inoperable).</span></span>
  
<span data-ttu-id="37c4a-p115">重大な停止から回復した後、サービスの完全なデータセンターの冗長性が復元されるまでの時間があることに注意してください。たとえば、データセンター1に障害が発生すると、サービスはデータセンター2のリソースによって復元されます。ただし、データセンター1でリソースを復元したか、データセンター3で新しいリソースを使用して、データセンター2のサービスがサービス継続性をサポートするまでの期間がある場合があります。Microsoft[サービスレベル契約](service-level-agreement.md)(SLA) は、この期間に適用されます。21Vianet が運用している Office 365 には、異なる SLA があります。詳細については、 [21vianet サイト](https://www.21vbluecloud.com/office365/O365-SLA/)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p115">Note that after recovery from catastrophic outages, there may be a period of time before full data center redundancy is restored for the service. For example, if Data Center 1 fails, services are restored by resources in Data Center 2. However, there may be a period of time until services in Data Center 2 have service continuity support either by restored resources in Data Center 1, or new resources in Data Center 3. The Microsoft [Service Level Agreement](service-level-agreement.md) (SLA) applies during this time. Office 365 operated by 21Vianet has a different SLA. See the [21Vianet site](https://www.21vbluecloud.com/office365/O365-SLA/) for more information.</span></span> 
  
## <a name="ensuring-data-availability"></a><span data-ttu-id="37c4a-200">データ可用性の確保</span><span class="sxs-lookup"><span data-stu-id="37c4a-200">Ensuring data availability</span></span>

<span data-ttu-id="37c4a-201">Microsoft は、以下の機能によって、お客様がいつでも必要なときにデータを利用できるようにしています。</span><span class="sxs-lookup"><span data-stu-id="37c4a-201">Microsoft ensures that customer data is available whenever it is needed through the following features:</span></span>
  
- <span data-ttu-id="37c4a-p116">**データ ストレージと冗長性:** お客様のデータは、信頼性の高いデータ保護機能を備えた冗長環境に保管されます。これにより可用性とビジネス継続性が確保され、迅速な復旧が可能です。データ冗長性は複数レベルで実装されており、ローカルのディスク障害に対処する冗長ディスク構成から、遠隔地のデータ センターへのデータのフル レプリケーションまでをサポートします。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p116">**Data storage and redundancy:** Customer data is stored in a redundant environment with robust data protection capabilities to enable availability, business continuity, and rapid recovery. Multiple levels of data redundancy are implemented, ranging from redundant disks to guard against local disk failure to continuous, full data replication to a geographically diverse data center.</span></span> 
    
- <span data-ttu-id="37c4a-204">**データの監視:** Microsoft サービスは、次のようにして高レベルのパフォーマンスを維持します。</span><span class="sxs-lookup"><span data-stu-id="37c4a-204">**Data monitoring:** Microsoft services maintain high levels of performance by:</span></span> 
    
  - <span data-ttu-id="37c4a-205">**データベースの監視:**</span><span class="sxs-lookup"><span data-stu-id="37c4a-205">**Monitoring databases:**</span></span>
    
  - <span data-ttu-id="37c4a-206">ブロックされたプロセス</span><span class="sxs-lookup"><span data-stu-id="37c4a-206">Blocked processes</span></span>
    
  - <span data-ttu-id="37c4a-207">パケット損失</span><span class="sxs-lookup"><span data-stu-id="37c4a-207">Packet loss</span></span>
    
  - <span data-ttu-id="37c4a-208">キューに登録されたプロセス</span><span class="sxs-lookup"><span data-stu-id="37c4a-208">Queued processes</span></span>
    
  - <span data-ttu-id="37c4a-209">クエリの待機時間</span><span class="sxs-lookup"><span data-stu-id="37c4a-209">Query latency</span></span>
    
- <span data-ttu-id="37c4a-210">**予防保守の実行:** 予防保守には、データベースの整合性チェック、定期的なデータ圧縮、およびエラー ログのレビューなどがあります。</span><span class="sxs-lookup"><span data-stu-id="37c4a-210">**Completing preventative maintenance:** Preventative maintenance includes database consistency checks, periodic data compression, and error log reviews.</span></span> 
    
## <a name="support"></a><span data-ttu-id="37c4a-211">サポート</span><span class="sxs-lookup"><span data-stu-id="37c4a-211">Support</span></span>

<span data-ttu-id="37c4a-p117">Microsoft の開発および運用チームは、お客様にビジネス継続性を提供するうえで重要な役割を果たす、専任のサポート組織によって補われています。サポートスタッフは、サービスとそれに関連付けられたアプリケーションについて深く理解しており、アーキテクチャ、開発、テストにおいて Microsoft の専門家に直接アクセスすることもできます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p117">The Microsoft development and operations teams are complemented by a dedicated support organization, which plays an important role in providing customers with business continuity. Support staff has a deep knowledge of the service and its associated applications as well as direct access to Microsoft experts in architecture, development, and testing.</span></span>
  
<span data-ttu-id="37c4a-p118">サポート組織は運用および製品開発チームと密接に協力することで、迅速な問題解決を実現し、お客様の声を反映するための窓口になります。お客様からのフィードバックは、計画、開発、運用プロセスに役立てられます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p118">The support organization closely aligns with operations and product development, offers fast resolution times and provides a channel for customers' voices to be heard. Feedback from customers provides input to the planning, development, and operations processes.</span></span>
  
- <span data-ttu-id="37c4a-p119">**オンライン問題の追跡:** お客様は、問題が解決されたことを認識し、適切な解決策を追跡できる必要があります。Microsoft 365 padmin center ortal は、サポート用の単一の web ベースのインターフェイスを提供します。顧客は、ポータルを使用してサービス要求を追加および監視し、Microsoft サポートチームからフィードバックを受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p119">**Online issue tracking:** Customers need to know that their issues are being addressed, and they need to be able to track timely resolution. The Microsoft 365 padmin center ortal provides a single web-based interface for support. Customers can use the portal to add and monitor service requests and receive feedback from Microsoft support teams.</span></span> 
    
- <span data-ttu-id="37c4a-219">**スタッフが継続的にサポートするセルフヘルプ:** Microsoft は、お客様が Microsoft サポートを必要とせずにサービス関連の問題を解決するのに役立つ、さまざまなセルフヘルプのリソースとツールを提供しています。</span><span class="sxs-lookup"><span data-stu-id="37c4a-219">**Self-help, backed by continuous staff support:** Microsoft offers a wide range of self-help resources and tools that can help customers to resolve service-related issues without requiring Microsoft support.</span></span> 
    
<span data-ttu-id="37c4a-p120">お客様は、サービス リクエストを作成する前にサポート技術情報の記事や FAQ を参照することで、よくある問題に関するヘルプを即座に得ることができます。これらのリソースは絶えず最新の情報に更新され、既知の問題に対する解決策をタイムリーに提供します。また、サポート担当者による対応が必要な問題が発生した場合は、電話または管理ポータルを通じて、24 時間 365 日体制のスタッフによる迅速な支援を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="37c4a-p120">Before customers enter service requests, they can access knowledge base articles and FAQs that provide immediate help with the most common problems. These resources are continually updated with the latest information, which helps avoid delays by providing solutions to known issues. However, when an issue arises that needs the help of a support professional; staff members are available for immediate assistance by telephone and through the administration portal 24 hours a day, 7 days a week.</span></span>
  
<span data-ttu-id="37c4a-223">サポートの詳細については、「[サポート](support.md)」トピックを参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-223">For more information about support, see the [Support](support.md) topic.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="37c4a-224">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="37c4a-224">Feature availability</span></span>

<span data-ttu-id="37c4a-225">プラン全体の機能の可用性を表示するには、「 [Office 365 プラットフォームサービスの説明](office-365-platform-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="37c4a-225">To view feature availability across plans, see the [Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  