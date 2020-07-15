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
# <a name="networking"></a>ネットワーク

Microsoft は、次のネットワーク機能をサポートしています。
  
## <a name="ports-protocols-and-ip-addresses"></a>ポート、プロトコル、および IP アドレス

Microsoft では、IPv4 アドレスと IPv6 アドレスを使用しています。 IPv6 の使用は任意で、Office 365 との接続には必要ありません。 IPv6 を使用してすべての Microsoft 365 機能が完全に有効になっているわけではありません。 Ipv6 のサポートの詳細については、「 [Microsoft サービスでの ipv6 サポート](https://docs.microsoft.com/office365/enterprise/ipv6-support)」を参照してください。
  
Microsoft は、Microsoft ヘルプで許可されている IP アドレスの一覧を保持しています。 詳細については、「 [url と IP アドレスの範囲](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)」を参照してください。 21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)」を参照してください。 Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>帯域幅要件

帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)」を参照してください。
  
## <a name="connecting-to-microsoft"></a>Microsoft に接続する

Microsoft へのすべての接続は、パブリックインターネットまたはプライベートの Azure ExpressRoute 接続を介して行われ、必要に応じて SSL で保護されています。 Azure ExpressRoute を使用すると、インターネットを迂回して、グローバルな Microsoft ネットワークに直接接続できます。 Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。
  
Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](https://aka.ms/expressrouteoffice365)」をご覧ください。
  
### <a name="wan-accelerators"></a>WAN アクセラレータ

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Microsoft のグローバル ネットワーク

Microsoft ネットワークインフラストラクチャは、サービスのグローバルな分散を実現するために、データセンター、サーバー、コンテンツ配布ネットワーク、エッジコンピューティングノード、および光ファイバーネットワークの大規模なグローバルポートフォリオで構成されています。 各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。 ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。 詳細については、「 [Microsoft グローバルネットワーク](https://docs.microsoft.com/azure/networking/microsoft-global-network)」を参照してください。 
  
顧客データの機密性と整合性を維持するために、Microsoft は、コンシューマーサービスネットワークを Microsoft ネットワークとは分離して保持します。 情報フローの制御には、以下のような複数の方法を使用しています。
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- ファイアウォール。 ファイアウォールおよびその他のネットワークセキュリティ強制ポイントは、インターネットに公開されるシステムとのデータ交換を制限し、Microsoft が管理するバックエンドシステムからシステムを分離するために使用されます。 
    
- プロトコルの制限。
    
詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。 
  
## <a name="feature-availability"></a>機能の可用性

プラン全体の機能の可用性を表示するには、「 [Microsoft 365 And Office 365 platform service description](office-365-platform-service-description.md)」を参照してください。
  

