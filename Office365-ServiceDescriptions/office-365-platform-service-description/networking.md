---
title: ネットワーク
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 は、次のネットワーク機能をサポートしています。
ms.openlocfilehash: f2343872faac2b1b289c37b8dc91240fa030482d
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262900"
---
# <a name="networking"></a><span data-ttu-id="810a1-103">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="810a1-103">Networking</span></span>

<span data-ttu-id="810a1-104">Microsoft Office 365 は、次のネットワーク機能をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="810a1-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="810a1-105">ポート、プロトコル、および IP アドレス</span><span class="sxs-lookup"><span data-stu-id="810a1-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="810a1-p101">Office 365 は IPv4 アドレスおよび IPv6 アドレスを使用します。IPv6 の使用は任意で、Office 365 との接続には必要ありません。Office 365 のすべての機能が IPv6 の使用で完全に有効になるわけではありません。Office 365 での IPv6 サポートの詳細については、「[Office 365 サービスでの IPv6 サポート](https://docs.microsoft.com/office365/enterprise/ipv6-support)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="810a1-p102">Office 365 では、許可されている IP アドレスのリストが Office 365 ヘルプに維持されます。詳細については、「[Office 365 URL および IP アドレス範囲](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)」を参照してください。21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)」を参照してください。Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="810a1-p103">特定の IP アドレス サブネットへのルーティングではなく、上に記載されたルート ドメイン名 (\*.Outlook.com、\*.MicrosoftOnline.com、\*.SharePoint.com など) へのルーティングを有効にすることを強くお勧めします。IP アドレス サブネットを使用すると、変更が行われたときにユーザーに対するサービスが停止する危険があります。</span><span class="sxs-lookup"><span data-stu-id="810a1-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="810a1-116">帯域幅要件</span><span class="sxs-lookup"><span data-stu-id="810a1-116">Bandwidth requirements</span></span>

<span data-ttu-id="810a1-117">帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="810a1-118">Office 365 への接続</span><span class="sxs-lookup"><span data-stu-id="810a1-118">Connecting to Office 365</span></span>

<span data-ttu-id="810a1-119">Office 365 へのすべての接続は、パブリックインターネットまたはプライベートの Azure ExpressRoute 接続を介して行われ、必要に応じて SSL でセキュリティ保護されます。</span><span class="sxs-lookup"><span data-stu-id="810a1-119">All Connections to Office 365 are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="810a1-120">Azure ExpressRoute を使用すると、インターネットを迂回して、グローバルな Microsoft ネットワークに直接接続できます。</span><span class="sxs-lookup"><span data-stu-id="810a1-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="810a1-121">Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。</span><span class="sxs-lookup"><span data-stu-id="810a1-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="810a1-122">Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](https://aka.ms/expressrouteoffice365)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="810a1-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="810a1-123">WAN アクセラレータ</span><span class="sxs-lookup"><span data-stu-id="810a1-123">WAN accelerators</span></span>

<span data-ttu-id="810a1-p105">Microsoft は、Office 365 で顧客が所有する WAN 高速化デバイスやキャッシュ デバイスをサポートしていません。待ち時間が長いまたは帯域幅が狭い条件下で WAN 最適化コントローラーを使用してパフォーマンスを改善する場合は、Microsoft にサービス要求のトラブルシューティングを依頼する際に WAN 最適化コントローラーを無効にする必要があります。また、これらのデバイスのサポートについては、デバイスの提供元に相談してください。詳細については、「[Office 365 での WAN 最適化コントローラーおよびキャッシュ デバイスの使用](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="810a1-127">Microsoft のグローバル ネットワーク</span><span class="sxs-lookup"><span data-stu-id="810a1-127">The global Microsoft network</span></span>

<span data-ttu-id="810a1-128">Office 365 のネットワーク インフラストラクチャは、世界規模でサービスを提供するためのデータセンター、サーバー、コンテンツ配信ネットワーク、エッジ コンピューティング ノード、および光ファイバー ネットワークを大規模に組み合わせて構成されています。</span><span class="sxs-lookup"><span data-stu-id="810a1-128">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="810a1-129">各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="810a1-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="810a1-130">ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。</span><span class="sxs-lookup"><span data-stu-id="810a1-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="810a1-131">詳細については、「 [Microsoft グローバルネットワーク](https://docs.microsoft.com/azure/networking/microsoft-global-network)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="810a1-p107">顧客データの機密性と完全性を維持するため、Microsoft では、コンシューマー サービス用ネットワークと Office 365 用ネットワークを分離しています。情報フローの制御には、以下のような複数の方法を使用しています。</span><span class="sxs-lookup"><span data-stu-id="810a1-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="810a1-p108">物理的な分離。特定の通信パターンを防止するように構成されたルーターで、ネットワーク セグメントを物理的に分離します。</span><span class="sxs-lookup"><span data-stu-id="810a1-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="810a1-p109">論理的な分離。仮想 LAN (VLAN) テクノロジを使用して通信をさらに分離します。</span><span class="sxs-lookup"><span data-stu-id="810a1-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="810a1-138">ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="810a1-138">Firewalls.</span></span> <span data-ttu-id="810a1-139">ファイアウォールおよびその他のネットワークセキュリティ強制ポイントは、インターネットに公開されるシステムとのデータ交換を制限し、Microsoft が管理するバックエンドシステムからシステムを分離するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="810a1-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="810a1-140">プロトコルの制限。</span><span class="sxs-lookup"><span data-stu-id="810a1-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="810a1-141">詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="810a1-142">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="810a1-142">Feature availability</span></span>

<span data-ttu-id="810a1-143">Office 365 プラン全体の機能の可用性を表示するには、「 [office 365 platform service description](office-365-platform-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="810a1-143">To view feature availability across Office 365 plans, see [Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

