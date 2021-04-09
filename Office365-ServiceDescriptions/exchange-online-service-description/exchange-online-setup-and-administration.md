---
title: Exchange Online のセットアップと管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を稼働、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
ms.openlocfilehash: 56d7dbc7e5e6300172d120bbf1464fd2bbf0daf0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652731"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="75287-104">Exchange Online のセットアップと管理</span><span class="sxs-lookup"><span data-stu-id="75287-104">Exchange Online setup and administration</span></span>

<span data-ttu-id="75287-105">この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を稼働、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。</span><span class="sxs-lookup"><span data-stu-id="75287-105">This article describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="75287-106">この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="75287-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="75287-107">セルフ サービス管理ツール</span><span class="sxs-lookup"><span data-stu-id="75287-107">Self-service administration tools</span></span>

<span data-ttu-id="75287-108">Microsoft は、すべての Exchange Online データ センターを直接制御し、システム全体のパフォーマンスを担当しますが、ユーザーに全体的なエクスペリエンスを提供するために組み合わせる要素の一部のみを制御できます。</span><span class="sxs-lookup"><span data-stu-id="75287-108">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for users.</span></span> <span data-ttu-id="75287-109">組織自体は、データ センターへのネットワーク接続、顧客のワイド エリア ネットワーク (WAN)、および顧客のローカル エリア ネットワーク (LAN) を担当します。</span><span class="sxs-lookup"><span data-stu-id="75287-109">Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs).</span></span> <span data-ttu-id="75287-110">さらに、ユーザー デバイスとその構成を担当します。</span><span class="sxs-lookup"><span data-stu-id="75287-110">Additionally, they are in charge of user devices and their configuration.</span></span><span data-ttu-id="75287-111">また、ユーザーが機能にアクセスする必要がある限り、これらの機能を管理する機能を含むが、これらに限定されない任意の機能に対して、ユーザーごとに必要なライセンスを維持する責任があります。</span><span class="sxs-lookup"><span data-stu-id="75287-111">  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="75287-112">このため Exchange Online は、次に説明するツールをカスタマーの管理者に提供し、メッセージングに関するさまざまなタスクを管理できるようにします。</span><span class="sxs-lookup"><span data-stu-id="75287-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="75287-113">Microsoft Office 365 ポータル</span><span class="sxs-lookup"><span data-stu-id="75287-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="75287-114">Microsoft 365 管理センター</span><span class="sxs-lookup"><span data-stu-id="75287-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="75287-115">Exchange 管理センター</span><span class="sxs-lookup"><span data-stu-id="75287-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="75287-116">Exchange Online 用リモート Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="75287-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="75287-117">Microsoft Office 365 ポータル</span><span class="sxs-lookup"><span data-stu-id="75287-117">Microsoft Office 365 portal</span></span>

<span data-ttu-id="75287-118">Microsoft Office 365 ポータル ([https://portal.office.com](https://portal.office.com)) は、管理者やパートナーが Office 365 サービスを購入および管理する Web サイトです。ユーザーは、このサイトで Office 365 コラボレーション ツールにアクセスして使用することができます。</span><span class="sxs-lookup"><span data-stu-id="75287-118">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="75287-119">Microsoft 365 管理センター</span><span class="sxs-lookup"><span data-stu-id="75287-119">Microsoft 365 admin center</span></span>

<span data-ttu-id="75287-120">Microsoft 365 管理センターは、各会社のサービス管理者が購読する各 Microsoft サービスのユーザー アカウントと設定を管理できる Web ポータルです。</span><span class="sxs-lookup"><span data-stu-id="75287-120">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="75287-121">Microsoft 365 管理センター内から、管理者は Exchange 管理センター (EAC) へのリンクに従って、Exchange Online 固有の設定を管理できます。</span><span class="sxs-lookup"><span data-stu-id="75287-121">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="75287-122">Microsoft 365 管理センターを使用した立ち上げと実行の詳細については、次のビデオ「 [365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806)の概要」を参照Officeしてください。</span><span class="sxs-lookup"><span data-stu-id="75287-122">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="75287-123">Exchange 管理センター</span><span class="sxs-lookup"><span data-stu-id="75287-123">Exchange admin center</span></span>

<span data-ttu-id="75287-p105">Exchange Online には、使いやすく、社内、オンライン、またはハイブリッド展開の管理用に最適化された、統合管理コンソールがあります。Exchange 管理センター (EAC) では、管理者が Exchange に固有の設定を管理することができます。</span><span class="sxs-lookup"><span data-stu-id="75287-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="75287-126">EAC を使用して Exchange Online を管理する方法の詳細については、「[Exchange Online の Exchange 管理センター](/exchange/exchange-admin-center)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="75287-126">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](/exchange/exchange-admin-center).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="75287-127">Exchange Online 用リモート Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="75287-127">Remote Windows PowerShell for Exchange Online</span></span>

<span data-ttu-id="75287-p106">リモート Windows PowerShell を使用することにより、管理者は Exchange Online にアクセスして、EAC では使用不可であったり実用的ではない管理タスクを実行できます。これらは、繰り返しタスクの自動化、カスタム レポートからのデータ抽出、ポリシーのカスタマイズ、既存インフラストラクチャおよびプロセスへの Exchange Online の接続などの機能です。詳細については、「[リモート PowerShell による Exchange への接続](/powershell/exchange/connect-to-exchange-online-powershell)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="75287-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](/powershell/exchange/connect-to-exchange-online-powershell).</span></span>
  
<span data-ttu-id="75287-p107">Exchange Online は Exchange Server 2013 と同じ Windows PowerShell コマンドレットを使用しますが、一部のコマンドとパラメーターは Exchange Online には該当しない機能となるため、使用できません。Exchange Online で使用するコマンドレットの一覧については、「[Exchange Online コマンドレット](/powershell/exchange/exchange-online-powershell)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="75287-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](/powershell/exchange/exchange-online-powershell).</span></span>
  
<span data-ttu-id="75287-p108">管理者はリモート Windows PowerShell を使用するのに、Exchange Server 管理ツールまたは移行ツールをインストールする必要はありません。ただし、管理者のコンピューターは Windows PowerShell v3 と WinRM 3.0 を含む Windows Management Framework 3.0 と Windows .NET Framework 4.5 を実行している必要があります。これらのコンポーネントは、Windows 8 または Windows Server 2012 を実行しているコンピューターにはすでにインストールされています。管理者は Windows 7 または Windows Server 2008 R2 を実行しているコンピューター用にこれらのコンポーネントを手動でダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="75287-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="75287-137">サービス拒否 (DoS) 攻撃を防止するため、Exchange Online 組織に対して開かれる Windows PowerShell 接続は 3 つに制限されています。</span><span class="sxs-lookup"><span data-stu-id="75287-137">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="75287-138">Exchange Online のセルフ サービス機能</span><span class="sxs-lookup"><span data-stu-id="75287-138">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="75287-p109">EAC、リモート Windows PowerShell、およびその他のツールを使用して、Exchange Online を管理する場合に使用可能な重要な機能を以下に挙げます。これらのツールにより、その他の多くの設定も制御可能です (本稿で説明します)。</span><span class="sxs-lookup"><span data-stu-id="75287-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="75287-141">Exchange Online でのモバイル デバイスのセキュリティ ポリシー</span><span class="sxs-lookup"><span data-stu-id="75287-141">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="75287-p110">Exchange Online では、モバイル デバイス用に Exchange Server 2013 と同じ ActiveSync ポリシーがサポートされます。管理者は、EAC またはリモート Windows PowerShell を使用して、特定のユーザーおよびグループ用にこれらのセキュリティ ポリシーを適用またはカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="75287-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="75287-144">Exchange Online でのメッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="75287-144">Message tracking for Exchange Online</span></span>

<span data-ttu-id="75287-145">配信レポート機能によるメッセージ追跡については、次のトピック「レポート機能とトラブルシューティング [ツール」で説明します](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="75287-145">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="75287-146">Exchange Online の利用状況レポート</span><span class="sxs-lookup"><span data-stu-id="75287-146">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="75287-p111">管理者はリモート Windows PowerShell を使用して、組織内のユーザーが Exchange Online サービスをどのように使用するのかに関する情報を取得できます。取得可能な情報を以下に挙げます。</span><span class="sxs-lookup"><span data-stu-id="75287-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="75287-149">組織内の各ユーザーのメールボックス サイズを表示する。</span><span class="sxs-lookup"><span data-stu-id="75287-149">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="75287-150">メールボックスに設定されたカスタム アクセス許可 (代理人アクセス等) を表示する。</span><span class="sxs-lookup"><span data-stu-id="75287-150">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="75287-151">モバイル データ アクセスに関するデータを抽出する (どのユーザーが Exchange ActiveSync 経由で接続しているか、ユーザーはどのデバイスを使用しているか、ユーザーの最終接続日時等)。</span><span class="sxs-lookup"><span data-stu-id="75287-151">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="75287-p112">"get-" で始まるリモート Windows PowerShell コマンドレットは、Exchange Online システムからデータを取得できます。管理者はさらに、分析したりレポートを作成するため、Windows PowerShell から .csv 形式でこの情報をエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="75287-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="75287-154">Exchange Online で使用する Windows PowerShell コマンドレットの詳細については、「[Exchange Online コマンドレット](/powershell/exchange/exchange-online-powershell)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="75287-154">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](/powershell/exchange/exchange-online-powershell).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="75287-155">Exchange Online での監査</span><span class="sxs-lookup"><span data-stu-id="75287-155">Auditing for Exchange Online</span></span>

<span data-ttu-id="75287-156">監査ログ機能については、次のトピック「レポート機能と [トラブルシューティング ツール」で説明します](reporting-features-and-troubleshooting-tools.md)。</span><span class="sxs-lookup"><span data-stu-id="75287-156">The audit logging feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="75287-157">Exchange Online でのサービスおよび製品のアップグレード</span><span class="sxs-lookup"><span data-stu-id="75287-157">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="75287-p113">Exchange Server の新しいリリースを含め、最新の Exchange テクノロジへの定期的なアップグレードは、Exchange Online のカスタマーにとって有益です。これらのアップグレードは追加料金なしで利用することができ、カスタマーは常に最新の Exchange ソフトウェアを使用できます。</span><span class="sxs-lookup"><span data-stu-id="75287-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="75287-160">Exchange の主要なバージョンが Microsoft からリリースされた後、カスタマーは最長 12 ヶ月までサービスを最新リリースにアップグレードすることができます。</span><span class="sxs-lookup"><span data-stu-id="75287-160">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="75287-161">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="75287-161">Feature availability</span></span>

<span data-ttu-id="75287-162">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="75287-162">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
