---
title: ネットワーク
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft は、次のネットワーク機能をサポートしています。
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132331"
---
# <a name="networking"></a><span data-ttu-id="0806f-103">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="0806f-103">Networking</span></span>

<span data-ttu-id="0806f-104">Microsoft は、次のネットワーク機能をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0806f-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="0806f-105">ポート、プロトコル、および IP アドレス</span><span class="sxs-lookup"><span data-stu-id="0806f-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="0806f-106">Microsoft では、IPv4 アドレスと IPv6 アドレスを使用しています。</span><span class="sxs-lookup"><span data-stu-id="0806f-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="0806f-107">IPv6 の使用は任意で、Office 365 との接続には必要ありません。</span><span class="sxs-lookup"><span data-stu-id="0806f-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="0806f-108">IPv6 を使用してすべての Microsoft 365 機能が完全に有効になっているわけではありません。</span><span class="sxs-lookup"><span data-stu-id="0806f-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="0806f-109">Ipv6 のサポートの詳細については、「 [Microsoft サービスでの ipv6 サポート](https://docs.microsoft.com/office365/enterprise/ipv6-support)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="0806f-110">Microsoft は、Microsoft ヘルプで許可されている IP アドレスの一覧を保持しています。</span><span class="sxs-lookup"><span data-stu-id="0806f-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="0806f-111">詳細については、「 [url と IP アドレスの範囲](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-111">For more information, see [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="0806f-112">21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="0806f-113">Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="0806f-114">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets.</span><span class="sxs-lookup"><span data-stu-id="0806f-114">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets.</span></span> <span data-ttu-id="0806f-115">Relying on IP address subnets runs the risk of outages for your users as changes are made.</span><span class="sxs-lookup"><span data-stu-id="0806f-115">Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="0806f-116">帯域幅要件</span><span class="sxs-lookup"><span data-stu-id="0806f-116">Bandwidth requirements</span></span>

<span data-ttu-id="0806f-117">帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="0806f-118">Microsoft に接続する</span><span class="sxs-lookup"><span data-stu-id="0806f-118">Connecting to Microsoft</span></span>

<span data-ttu-id="0806f-119">Microsoft へのすべての接続は、パブリックインターネットまたはプライベートの Azure ExpressRoute 接続を介して行われ、必要に応じて SSL で保護されています。</span><span class="sxs-lookup"><span data-stu-id="0806f-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="0806f-120">Azure ExpressRoute を使用すると、インターネットを迂回して、グローバルな Microsoft ネットワークに直接接続できます。</span><span class="sxs-lookup"><span data-stu-id="0806f-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="0806f-121">Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。</span><span class="sxs-lookup"><span data-stu-id="0806f-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="0806f-122">Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](https://aka.ms/expressrouteoffice365)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="0806f-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="0806f-123">WAN アクセラレータ</span><span class="sxs-lookup"><span data-stu-id="0806f-123">WAN accelerators</span></span>

<span data-ttu-id="0806f-124">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365.</span><span class="sxs-lookup"><span data-stu-id="0806f-124">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365.</span></span> <span data-ttu-id="0806f-125">If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support.</span><span class="sxs-lookup"><span data-stu-id="0806f-125">If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support.</span></span> <span data-ttu-id="0806f-126">For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="0806f-126">For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="0806f-127">Microsoft のグローバル ネットワーク</span><span class="sxs-lookup"><span data-stu-id="0806f-127">The global Microsoft network</span></span>

<span data-ttu-id="0806f-128">Microsoft ネットワークインフラストラクチャは、サービスのグローバルな分散を実現するために、データセンター、サーバー、コンテンツ配布ネットワーク、エッジコンピューティングノード、および光ファイバーネットワークの大規模なグローバルポートフォリオで構成されています。</span><span class="sxs-lookup"><span data-stu-id="0806f-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="0806f-129">各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="0806f-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="0806f-130">ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。</span><span class="sxs-lookup"><span data-stu-id="0806f-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="0806f-131">詳細については、「 [Microsoft グローバルネットワーク](https://docs.microsoft.com/azure/networking/microsoft-global-network)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="0806f-132">顧客データの機密性と整合性を維持するために、Microsoft は、コンシューマーサービスネットワークを Microsoft ネットワークとは分離して保持します。</span><span class="sxs-lookup"><span data-stu-id="0806f-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="0806f-133">情報フローの制御には、以下のような複数の方法を使用しています。</span><span class="sxs-lookup"><span data-stu-id="0806f-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="0806f-134">Physical separation.</span><span class="sxs-lookup"><span data-stu-id="0806f-134">Physical separation.</span></span> <span data-ttu-id="0806f-135">Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span><span class="sxs-lookup"><span data-stu-id="0806f-135">Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="0806f-136">Logical separation.</span><span class="sxs-lookup"><span data-stu-id="0806f-136">Logical separation.</span></span> <span data-ttu-id="0806f-137">Virtual LAN (VLAN) technology is used to further separate communications.</span><span class="sxs-lookup"><span data-stu-id="0806f-137">Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="0806f-138">ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="0806f-138">Firewalls.</span></span> <span data-ttu-id="0806f-139">ファイアウォールおよびその他のネットワークセキュリティ強制ポイントは、インターネットに公開されるシステムとのデータ交換を制限し、Microsoft が管理するバックエンドシステムからシステムを分離するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="0806f-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="0806f-140">プロトコルの制限。</span><span class="sxs-lookup"><span data-stu-id="0806f-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="0806f-141">詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="0806f-142">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="0806f-142">Feature availability</span></span>

<span data-ttu-id="0806f-143">プラン全体の機能の可用性を表示するには、「 [Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0806f-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

