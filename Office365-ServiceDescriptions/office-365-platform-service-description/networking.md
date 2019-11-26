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
# <a name="networking"></a>ネットワーク

Microsoft Office 365 は、次のネットワーク機能をサポートしています。
  
## <a name="ports-protocols-and-ip-addresses"></a>ポート、プロトコル、および IP アドレス

Office 365 は IPv4 アドレスおよび IPv6 アドレスを使用します。IPv6 の使用は任意で、Office 365 との接続には必要ありません。Office 365 のすべての機能が IPv6 の使用で完全に有効になるわけではありません。Office 365 での IPv6 サポートの詳細については、「[Office 365 サービスでの IPv6 サポート](https://docs.microsoft.com/office365/enterprise/ipv6-support)」を参照してください。
  
Office 365 では、許可されている IP アドレスのリストが Office 365 ヘルプに維持されます。詳細については、「[Office 365 URL および IP アドレス範囲](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)」を参照してください。21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)」を参照してください。Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。
  
> [!IMPORTANT]
> 特定の IP アドレス サブネットへのルーティングではなく、上に記載されたルート ドメイン名 (\*.Outlook.com、\*.MicrosoftOnline.com、\*.SharePoint.com など) へのルーティングを有効にすることを強くお勧めします。IP アドレス サブネットを使用すると、変更が行われたときにユーザーに対するサービスが停止する危険があります。 
  
## <a name="bandwidth-requirements"></a>帯域幅要件

帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)」を参照してください。
  
## <a name="connecting-to-office-365"></a>Office 365 への接続

Office 365 へのすべての接続は、パブリックインターネットまたはプライベートの Azure ExpressRoute 接続を介して行われ、必要に応じて SSL でセキュリティ保護されます。 Azure ExpressRoute を使用すると、インターネットを迂回して、グローバルな Microsoft ネットワークに直接接続できます。 Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。
  
Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](https://aka.ms/expressrouteoffice365)」をご覧ください。
  
### <a name="wan-accelerators"></a>WAN アクセラレータ

Microsoft は、Office 365 で顧客が所有する WAN 高速化デバイスやキャッシュ デバイスをサポートしていません。待ち時間が長いまたは帯域幅が狭い条件下で WAN 最適化コントローラーを使用してパフォーマンスを改善する場合は、Microsoft にサービス要求のトラブルシューティングを依頼する際に WAN 最適化コントローラーを無効にする必要があります。また、これらのデバイスのサポートについては、デバイスの提供元に相談してください。詳細については、「[Office 365 での WAN 最適化コントローラーおよびキャッシュ デバイスの使用](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)」を参照してください。
  
## <a name="the-global-microsoft-network"></a>Microsoft のグローバル ネットワーク

Office 365 のネットワーク インフラストラクチャは、世界規模でサービスを提供するためのデータセンター、サーバー、コンテンツ配信ネットワーク、エッジ コンピューティング ノード、および光ファイバー ネットワークを大規模に組み合わせて構成されています。 各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。 ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。 詳細については、「 [Microsoft グローバルネットワーク](https://docs.microsoft.com/azure/networking/microsoft-global-network)」を参照してください。 
  
顧客データの機密性と完全性を維持するため、Microsoft では、コンシューマー サービス用ネットワークと Office 365 用ネットワークを分離しています。情報フローの制御には、以下のような複数の方法を使用しています。
  
- 物理的な分離。特定の通信パターンを防止するように構成されたルーターで、ネットワーク セグメントを物理的に分離します。
    
- 論理的な分離。仮想 LAN (VLAN) テクノロジを使用して通信をさらに分離します。
    
- ファイアウォール。 ファイアウォールおよびその他のネットワークセキュリティ強制ポイントは、インターネットに公開されるシステムとのデータ交換を制限し、Microsoft が管理するバックエンドシステムからシステムを分離するために使用されます。 
    
- プロトコルの制限。
    
詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。 
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン全体の機能の可用性を表示するには、「 [office 365 platform service description](office-365-platform-service-description.md)」を参照してください。
  

