---
title: ネットワーク
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft は、次のネットワーク機能をサポートしています。
ms.openlocfilehash: df2fb9343529a7722fc434a79bf74621b78b787e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652541"
---
# <a name="networking"></a><span data-ttu-id="9e71d-103">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="9e71d-103">Networking</span></span>

<span data-ttu-id="9e71d-104">Microsoft は、次のネットワーク機能をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="9e71d-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="9e71d-105">ポート、プロトコル、および IP アドレス</span><span class="sxs-lookup"><span data-stu-id="9e71d-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="9e71d-106">Microsoft では、IPv4 アドレスと IPv6 アドレスを使用します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="9e71d-107">IPv6 の使用は任意で、Office 365 との接続には必要ありません。</span><span class="sxs-lookup"><span data-stu-id="9e71d-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="9e71d-108">すべての Microsoft 365 機能が IPv6 を使用して完全に有効になっているという場合ではありません。</span><span class="sxs-lookup"><span data-stu-id="9e71d-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="9e71d-109">Ipv6 サポートの詳細については、「Microsoft サービスでの [IPv6 サポート」を参照してください](/office365/enterprise/ipv6-support)。</span><span class="sxs-lookup"><span data-stu-id="9e71d-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="9e71d-110">Microsoft は、Microsoft ヘルプで許可されている IP アドレスの一覧を保持しています。</span><span class="sxs-lookup"><span data-stu-id="9e71d-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="9e71d-111">詳細については、「URL と [IP アドレス範囲」を参照してください](/office365/enterprise/urls-and-ip-address-ranges)。</span><span class="sxs-lookup"><span data-stu-id="9e71d-111">For more information, see [URLs and IP address ranges](/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="9e71d-112">21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](/office365/enterprise/managing-office-365-endpoints)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="9e71d-113">Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="9e71d-p103">特定の IP アドレス サブネットへのルーティングではなく、上に記載されたルート ドメイン名 (\*.Outlook.com、\*.MicrosoftOnline.com、\*.SharePoint.com など) へのルーティングを有効にすることを強くお勧めします。IP アドレス サブネットを使用すると、変更が行われたときにユーザーに対するサービスが停止する危険があります。</span><span class="sxs-lookup"><span data-stu-id="9e71d-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="9e71d-116">帯域幅要件</span><span class="sxs-lookup"><span data-stu-id="9e71d-116">Bandwidth requirements</span></span>

<span data-ttu-id="9e71d-117">帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](/office365/enterprise/network-planning-and-performance)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-117">For information on bandwidth requirements, see [Internet bandwidth planning](/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="9e71d-118">Microsoft への接続</span><span class="sxs-lookup"><span data-stu-id="9e71d-118">Connecting to Microsoft</span></span>

<span data-ttu-id="9e71d-119">Microsoft へのすべての接続は、パブリック インターネットまたはプライベート Azure ExpressRoute 接続を使用して行われ、必要に応じて SSL によってセキュリティ保護されます。</span><span class="sxs-lookup"><span data-stu-id="9e71d-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="9e71d-120">Azure ExpressRoute を使用すると、グローバル Microsoft ネットワークに直接接続し、インターネットをバイパスできます。</span><span class="sxs-lookup"><span data-stu-id="9e71d-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="9e71d-121">Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="9e71d-122">Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](/microsoft-365/enterprise/azure-expressroute)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](/microsoft-365/enterprise/azure-expressroute)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="9e71d-123">WAN アクセラレータ</span><span class="sxs-lookup"><span data-stu-id="9e71d-123">WAN accelerators</span></span>

<span data-ttu-id="9e71d-p105">Microsoft は、Office 365 で顧客が所有する WAN 高速化デバイスやキャッシュ デバイスをサポートしていません。待ち時間が長いまたは帯域幅が狭い条件下で WAN 最適化コントローラーを使用してパフォーマンスを改善する場合は、Microsoft にサービス要求のトラブルシューティングを依頼する際に WAN 最適化コントローラーを無効にする必要があります。また、これらのデバイスのサポートについては、デバイスの提供元に相談してください。詳細については、「[Office 365 での WAN 最適化コントローラーおよびキャッシュ デバイスの使用](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="9e71d-127">Microsoft のグローバル ネットワーク</span><span class="sxs-lookup"><span data-stu-id="9e71d-127">The global Microsoft network</span></span>

<span data-ttu-id="9e71d-128">Microsoft ネットワーク インフラストラクチャは、データ センター、サーバー、コンテンツ配布ネットワーク、エッジ コンピューティング ノード、および光ファイバー ネットワークの大規模なグローバル ポートフォリオで構成され、サービスのグローバル配布を提供します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="9e71d-129">各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="9e71d-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="9e71d-130">ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。</span><span class="sxs-lookup"><span data-stu-id="9e71d-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="9e71d-131">詳細については [、「Microsoft Global Network」を参照してください](/azure/networking/microsoft-global-network)。</span><span class="sxs-lookup"><span data-stu-id="9e71d-131">For more information, see [Microsoft Global Network](/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="9e71d-132">顧客データの機密性と整合性を維持するために、Microsoft はコンシューマー サービス ネットワークを Microsoft ネットワークとは別に保持します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="9e71d-133">情報フローの制御には、以下のような複数の方法を使用しています。</span><span class="sxs-lookup"><span data-stu-id="9e71d-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="9e71d-p108">物理的な分離。特定の通信パターンを防止するように構成されたルーターで、ネットワーク セグメントを物理的に分離します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="9e71d-p109">論理的な分離。仮想 LAN (VLAN) テクノロジを使用して通信をさらに分離します。</span><span class="sxs-lookup"><span data-stu-id="9e71d-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="9e71d-138">ファイアウォール。</span><span class="sxs-lookup"><span data-stu-id="9e71d-138">Firewalls.</span></span> <span data-ttu-id="9e71d-139">ファイアウォールなどのネットワーク セキュリティ適用ポイントは、インターネットに公開されているシステムとのデータ交換を制限し、Microsoft が管理するバック エンド システムからシステムを分離するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="9e71d-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="9e71d-140">プロトコルの制限。</span><span class="sxs-lookup"><span data-stu-id="9e71d-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="9e71d-141">詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="9e71d-142">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="9e71d-142">Feature availability</span></span>

<span data-ttu-id="9e71d-143">プラン全体の機能の可用性を表示するには [、「Microsoft 365 および Office 365 プラットフォーム](office-365-platform-service-description.md)サービスの説明」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9e71d-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
