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
ms.openlocfilehash: 318437ce65c5ced55d42e798bf76774cda6708f9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173022"
---
# <a name="networking"></a>ネットワーク

Microsoft は、次のネットワーク機能をサポートしています。
  
## <a name="ports-protocols-and-ip-addresses"></a>ポート、プロトコル、および IP アドレス

Microsoft では、IPv4 アドレスと IPv6 アドレスを使用します。 IPv6 の使用は任意で、Office 365 との接続には必要ありません。 すべての Microsoft 365 機能が IPv6 を使用して完全に有効になっているという場合ではありません。 Ipv6 サポートの詳細については、「Microsoft サービスでの [IPv6 サポート」を参照してください](/office365/enterprise/ipv6-support)。
  
Microsoft は、Microsoft ヘルプで許可されている IP アドレスの一覧を保持しています。 詳細については、「URL と [IP アドレス範囲」を参照してください](/office365/enterprise/urls-and-ip-address-ranges)。 21Vianet が運用している Office 365 については、「[21Vianet が運用している Office 365 の URL と IP アドレス](/office365/enterprise/managing-office-365-endpoints)」を参照してください。 Office 365 Germany については、「[Office 365 Germany エンドポイント](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)」を参照してください。
  
> [!IMPORTANT]
> 特定の IP アドレス サブネットへのルーティングではなく、上に記載されたルート ドメイン名 (\*.Outlook.com、\*.MicrosoftOnline.com、\*.SharePoint.com など) へのルーティングを有効にすることを強くお勧めします。IP アドレス サブネットを使用すると、変更が行われたときにユーザーに対するサービスが停止する危険があります。 
  
## <a name="bandwidth-requirements"></a>帯域幅要件

帯域幅の要件については、「[Office 365 のネットワーク計画とパフォーマンスのチューニング](/office365/enterprise/network-planning-and-performance)」を参照してください。
  
## <a name="connecting-to-microsoft"></a>Microsoft への接続

Microsoft へのすべての接続は、パブリック インターネットまたはプライベート Azure ExpressRoute 接続を使用して行われ、必要に応じて SSL によってセキュリティ保護されます。 Azure ExpressRoute を使用すると、グローバル Microsoft ネットワークに直接接続し、インターネットをバイパスできます。 Microsoft ネットワーク パートナーは、Microsoft のグローバル ネットワークへの接続を提供します。
  
Azure ExpressRoute について詳しくは、「[Office 365 向け Azure ExpressRoute](/microsoft-365/enterprise/azure-expressroute)」をご覧ください。
  
### <a name="wan-accelerators"></a>WAN アクセラレータ

Microsoft は、Office 365 で顧客が所有する WAN 高速化デバイスやキャッシュ デバイスをサポートしていません。待ち時間が長いまたは帯域幅が狭い条件下で WAN 最適化コントローラーを使用してパフォーマンスを改善する場合は、Microsoft にサービス要求のトラブルシューティングを依頼する際に WAN 最適化コントローラーを無効にする必要があります。また、これらのデバイスのサポートについては、デバイスの提供元に相談してください。詳細については、「[Office 365 での WAN 最適化コントローラーおよびキャッシュ デバイスの使用](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)」を参照してください。
  
## <a name="the-global-microsoft-network"></a>Microsoft のグローバル ネットワーク

Microsoft ネットワーク インフラストラクチャは、データ センター、サーバー、コンテンツ配布ネットワーク、エッジ コンピューティング ノード、および光ファイバー ネットワークの大規模なグローバル ポートフォリオで構成され、サービスのグローバル配布を提供します。 各コンポーネントには高度なサービスの計測機能と監視機能が組み込まれているため、データセンター、ネットワーク バックボーン、およびインターネット エクスチェンジなどを詳細に把握して、発生した不具合の原因の特定、診断、管理を行うことができます。 ネットワークは、大規模なネットワーク障害が発生した場合でも、パフォーマンスを低下させることなく、十分な処理能力を維持できるように構成されています。 詳細については [、「Microsoft Global Network」を参照してください](/azure/networking/microsoft-global-network)。 
  
顧客データの機密性と整合性を維持するために、Microsoft はコンシューマー サービス ネットワークを Microsoft ネットワークとは別に保持します。 情報フローの制御には、以下のような複数の方法を使用しています。
  
- 物理的な分離。特定の通信パターンを防止するように構成されたルーターで、ネットワーク セグメントを物理的に分離します。
    
- 論理的な分離。仮想 LAN (VLAN) テクノロジを使用して通信をさらに分離します。
    
- ファイアウォール。 ファイアウォールなどのネットワーク セキュリティ適用ポイントは、インターネットに公開されているシステムとのデータ交換を制限し、Microsoft が管理するバック エンド システムからシステムを分離するために使用されます。 
    
- プロトコルの制限。
    
詳細については、「[Office 365 セキュリティ センター](https://www.microsoft.com/trust-center)」を参照してください。 
  
## <a name="feature-availability"></a>機能の可用性

プラン全体の機能の可用性を表示するには [、「Microsoft 365 および Office 365 プラットフォーム](office-365-platform-service-description.md)サービスの説明」を参照してください。
