---
title: Exchange Online のセットアップと管理
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: このセクションでは、exchange online の設定をカスタマイズし、組織の exchange online 環境を常に最新の状態にして、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
ms.openlocfilehash: 45707cbba47af8076312049686cb01beb6825d9e
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246303"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="494af-104">Exchange Online のセットアップと管理</span><span class="sxs-lookup"><span data-stu-id="494af-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="494af-105">このセクションでは、exchange online の設定をカスタマイズし、組織の exchange online 環境を常に最新の状態にして、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。</span><span class="sxs-lookup"><span data-stu-id="494af-105">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="494af-106">この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="494af-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="494af-107">セルフ サービス管理ツール</span><span class="sxs-lookup"><span data-stu-id="494af-107">Self-service administration tools</span></span>

<span data-ttu-id="494af-p103">Microsoft はすべての Exchange Online データ センターを直接制御し、全体的なシステム パフォーマンスの責任を負います。しかし、Microsoft が管理できる要素は、Office 365 ユーザーの全体的なエクスペリエンスを構成する要素の一部でしかありません。データ センター、カスタマーのワイド エリア ネットワーク (WAN)、およびカスタマーのローカル エリア ネットワーク (LAN) へのネットワーク接続は、組織自体が責任を負います。さらに、ユーザーのデバイスと構成の責任を担います。また、任意の必要な機能 (たとえば、ユーザーが対象機能を利用する場合にはその機能を管理する機能など) に関するユーザーごとに必要なライセンスの保守にも責任があります。</span><span class="sxs-lookup"><span data-stu-id="494af-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="494af-112">このため Exchange Online は、次に説明するツールをカスタマーの管理者に提供し、メッセージングに関するさまざまなタスクを管理できるようにします。</span><span class="sxs-lookup"><span data-stu-id="494af-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="494af-113">Microsoft Office 365 ポータル</span><span class="sxs-lookup"><span data-stu-id="494af-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="494af-114">Microsoft 365 管理センター</span><span class="sxs-lookup"><span data-stu-id="494af-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="494af-115">Exchange 管理センター</span><span class="sxs-lookup"><span data-stu-id="494af-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="494af-116">Exchange Online 用リモート Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="494af-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="494af-117">Microsoft Office 365 ポータル</span><span class="sxs-lookup"><span data-stu-id="494af-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="494af-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="494af-118"></span></span>

<span data-ttu-id="494af-119">Microsoft Office 365 ポータル ([https://portal.office.com](https://portal.office.com)) は、管理者やパートナーが Office 365 サービスを購入および管理する Web サイトです。ユーザーは、このサイトで Office 365 コラボレーション ツールにアクセスして使用することができます。</span><span class="sxs-lookup"><span data-stu-id="494af-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="494af-120">Microsoft 365 管理センター</span><span class="sxs-lookup"><span data-stu-id="494af-120">Microsoft 365 admin center</span></span>
<span data-ttu-id="494af-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="494af-121"></span></span>

<span data-ttu-id="494af-122">Microsoft 365 管理センターは、各企業のサービス管理者が、購読している各 Office 365 サービスのユーザーアカウントと設定を管理できる web ポータルです。</span><span class="sxs-lookup"><span data-stu-id="494af-122">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="494af-123">Microsoft 365 管理センターでは、管理者は exchange 管理センター (EAC) へのリンクをたどって、exchange Online に固有の設定を管理できます。</span><span class="sxs-lookup"><span data-stu-id="494af-123">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="494af-124">Microsoft 365 管理センターを使用した取得と実行の詳細については、「 [Office 365 Enterprise の概要](https://go.microsoft.com/fwlink/p/?LinkId=271806)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-124">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="494af-125">Exchange 管理センター</span><span class="sxs-lookup"><span data-stu-id="494af-125">Exchange admin center</span></span>
<span data-ttu-id="494af-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="494af-126"></span></span>

<span data-ttu-id="494af-p105">Exchange Online には、使いやすく、社内、オンライン、またはハイブリッド展開の管理用に最適化された、統合管理コンソールがあります。Exchange 管理センター (EAC) では、管理者が Exchange に固有の設定を管理することができます。</span><span class="sxs-lookup"><span data-stu-id="494af-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="494af-129">EAC を使用して Exchange Online を管理する方法の詳細については、「[Exchange Online の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=271807)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="494af-130">Exchange Online 用リモート Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="494af-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="494af-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="494af-131"></span></span>

<span data-ttu-id="494af-p106">リモート Windows PowerShell を使用することにより、管理者は Exchange Online にアクセスして、EAC では使用不可であったり実用的ではない管理タスクを実行できます。これらは、繰り返しタスクの自動化、カスタム レポートからのデータ抽出、ポリシーのカスタマイズ、既存インフラストラクチャおよびプロセスへの Exchange Online の接続などの機能です。詳細については、「[リモート PowerShell による Exchange への接続](https://go.microsoft.com/fwlink/p/?LinkId=308994)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="494af-p107">Exchange Online は Exchange Server 2013 と同じ Windows PowerShell コマンドレットを使用しますが、一部のコマンドとパラメーターは Exchange Online には該当しない機能となるため、使用できません。Exchange Online で使用するコマンドレットの一覧については、「[Exchange Online コマンドレット](https://go.microsoft.com/fwlink/p/?LinkId=271808)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="494af-p108">管理者はリモート Windows PowerShell を使用するのに、Exchange Server 管理ツールまたは移行ツールをインストールする必要はありません。ただし、管理者のコンピューターは Windows PowerShell v3 と WinRM 3.0 を含む Windows Management Framework 3.0 と Windows .NET Framework 4.5 を実行している必要があります。これらのコンポーネントは、Windows 8 または Windows Server 2012 を実行しているコンピューターにはすでにインストールされています。管理者は Windows 7 または Windows Server 2008 R2 を実行しているコンピューター用にこれらのコンポーネントを手動でダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="494af-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="494af-141">サービス拒否 (DoS) 攻撃を防止するため、Exchange Online 組織に対して開かれる Windows PowerShell 接続は 3 つに制限されています。</span><span class="sxs-lookup"><span data-stu-id="494af-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="494af-142">Exchange Online のセルフ サービス機能</span><span class="sxs-lookup"><span data-stu-id="494af-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="494af-p109">EAC、リモート Windows PowerShell、およびその他のツールを使用して、Exchange Online を管理する場合に使用可能な重要な機能を以下に挙げます。これらのツールにより、その他の多くの設定も制御可能です (本稿で説明します)。</span><span class="sxs-lookup"><span data-stu-id="494af-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="494af-145">Exchange Online でのモバイル デバイスのセキュリティ ポリシー</span><span class="sxs-lookup"><span data-stu-id="494af-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="494af-p110">Exchange Online では、モバイル デバイス用に Exchange Server 2013 と同じ ActiveSync ポリシーがサポートされます。管理者は、EAC またはリモート Windows PowerShell を使用して、特定のユーザーおよびグループ用にこれらのセキュリティ ポリシーを適用またはカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="494af-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="494af-148">Exchange Online でのメッセージ追跡</span><span class="sxs-lookup"><span data-stu-id="494af-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="494af-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="494af-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="494af-150">Exchange Online の利用状況レポート</span><span class="sxs-lookup"><span data-stu-id="494af-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="494af-p111">管理者はリモート Windows PowerShell を使用して、組織内のユーザーが Exchange Online サービスをどのように使用するのかに関する情報を取得できます。取得可能な情報を以下に挙げます。</span><span class="sxs-lookup"><span data-stu-id="494af-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="494af-153">組織内の各ユーザーのメールボックス サイズを表示する。</span><span class="sxs-lookup"><span data-stu-id="494af-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="494af-154">メールボックスに設定されたカスタム アクセス許可 (代理人アクセス等) を表示する。</span><span class="sxs-lookup"><span data-stu-id="494af-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="494af-155">モバイル データ アクセスに関するデータを抽出する (どのユーザーが Exchange ActiveSync 経由で接続しているか、ユーザーはどのデバイスを使用しているか、ユーザーの最終接続日時等)。</span><span class="sxs-lookup"><span data-stu-id="494af-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="494af-p112">"get-" で始まるリモート Windows PowerShell コマンドレットは、Exchange Online システムからデータを取得できます。管理者はさらに、分析したりレポートを作成するため、Windows PowerShell から .csv 形式でこの情報をエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="494af-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="494af-158">Exchange Online で使用する Windows PowerShell コマンドレットの詳細については、「[Exchange Online コマンドレット](https://go.microsoft.com/fwlink/p/?LinkId=271808)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="494af-159">Exchange Online での監査</span><span class="sxs-lookup"><span data-stu-id="494af-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="494af-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="494af-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="494af-161">Exchange Online でのサービスおよび製品のアップグレード</span><span class="sxs-lookup"><span data-stu-id="494af-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="494af-p113">Exchange Server の新しいリリースを含め、最新の Exchange テクノロジへの定期的なアップグレードは、Exchange Online のカスタマーにとって有益です。これらのアップグレードは追加料金なしで利用することができ、カスタマーは常に最新の Exchange ソフトウェアを使用できます。</span><span class="sxs-lookup"><span data-stu-id="494af-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="494af-164">Exchange の主要なバージョンが Microsoft からリリースされた後、カスタマーは最長 12 ヶ月までサービスを最新リリースにアップグレードすることができます。</span><span class="sxs-lookup"><span data-stu-id="494af-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="494af-165">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="494af-165">Feature Availability</span></span>

<span data-ttu-id="494af-166">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="494af-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

