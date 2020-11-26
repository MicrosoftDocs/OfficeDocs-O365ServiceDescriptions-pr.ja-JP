---
title: 米国政府機関向けの SharePoint
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 米国政府機関のクラウドのお客様が利用できる SharePoint の機能について説明します。
ms.openlocfilehash: 310aa1589aed1156de223bed229ce99ef2f5b69a
ms.sourcegitcommit: ace6cd97a0d3823959e1629929be77489f79b520
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/25/2020
ms.locfileid: "49411606"
---
# <a name="sharepoint-for-us-government-environments"></a><span data-ttu-id="25323-103">米国政府機関向けの SharePoint</span><span class="sxs-lookup"><span data-stu-id="25323-103">SharePoint for US government environments</span></span>

<span data-ttu-id="25323-104">この記事では、 [SharePoint サービスの説明](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)に記載されているように、米国政府機関クラウドと商用クラウドの機能の相違点の概要について説明します。</span><span class="sxs-lookup"><span data-stu-id="25323-104">This article provides an overview of feature differences between the US government cloud and the commercial cloud as listed in the [SharePoint service description](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description).</span></span> <span data-ttu-id="25323-105">SharePoint は、Government Community Cloud (GCC)、GCC High、DoD 環境で利用できます。</span><span class="sxs-lookup"><span data-stu-id="25323-105">SharePoint is available for the Government Community Cloud (GCC), GCC High, and DoD environments.</span></span> 

<span data-ttu-id="25323-106">資格および購入に関する政府機関のクラウドに関する詳細については、「 [Microsoft 365 government-購入方法](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-106">For more info about the government cloud, including eligibility and purchasing, see [Microsoft 365 Government - how to buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).</span></span> <span data-ttu-id="25323-107">Office 365 Government プランを比較するには、「 [office 365 government プラン](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-107">To compare Office 365 Government plans, see [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).</span></span>

<span data-ttu-id="25323-108">ネットワーク接続を管理するときに必要なエンドポイントの詳細については、「 [office 365 米国政府用 GCC、高エンドポイント](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) または [Office 365 米国政府の DoD エンドポイント](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-108">To learn about required endpoints when managing network connectivity, see the [Office 365 U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).</span></span>

<span data-ttu-id="25323-109">Office 365 の機能を楽しんだだけでなく、米国政府機関のクラウド環境に固有の次の機能を活用することができます。</span><span class="sxs-lookup"><span data-stu-id="25323-109">In addition to enjoying the features and capabilities of Office 365, organizations benefit from the following features that are unique to the US government cloud environments:</span></span>

-   <span data-ttu-id="25323-110">組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。</span><span class="sxs-lookup"><span data-stu-id="25323-110">Your organization’s customer content is logically segregated from customer content in the commercial Office 365 services from Microsoft.</span></span>
-   <span data-ttu-id="25323-111">組織の顧客コンテンツは、米国内に格納されます。</span><span class="sxs-lookup"><span data-stu-id="25323-111">Your organization’s customer content is stored within the United States.</span></span>
-   <span data-ttu-id="25323-112">組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。</span><span class="sxs-lookup"><span data-stu-id="25323-112">Access to your organization’s customer content is restricted to screened Microsoft personnel.</span></span>
-   <span data-ttu-id="25323-113">政府機関のクラウド環境は、米国の公的機関のお客様に必要な認定および認定に準拠しています。</span><span class="sxs-lookup"><span data-stu-id="25323-113">The government cloud environments comply with certifications and accreditations that are required for US Public Sector customers.</span></span>

<span data-ttu-id="25323-114">この記事では、すべての SharePoint の商用機能を政府機関のクラウド環境に提供することを目標としています。</span><span class="sxs-lookup"><span data-stu-id="25323-114">It's our goal to deliver all SharePoint commercial features and functionality to the government cloud environments.</span></span> <span data-ttu-id="25323-115">政府機関のクラウドのお客様の要件により、一部の機能は使用できません。</span><span class="sxs-lookup"><span data-stu-id="25323-115">Some features aren't available because of the requirements of government cloud customers.</span></span> <span data-ttu-id="25323-116">その他の機能は政府機関の環境に送られますが、まだ利用できません。</span><span class="sxs-lookup"><span data-stu-id="25323-116">Other features are coming to the government environments, but not yet available.</span></span> <span data-ttu-id="25323-117">政府機関のクラウド環境で利用できる機能については、以下のセクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-117">Refer to the following sections to learn about feature availability in the government cloud environments.</span></span>

## <a name="developer-features"></a><span data-ttu-id="25323-118">開発者向けの機能</span><span class="sxs-lookup"><span data-stu-id="25323-118">Developer features</span></span>

<span data-ttu-id="25323-119">市販のお客様向けの開発者向け機能と、政府機関のお客様にとっては、既知の違いはありません。</span><span class="sxs-lookup"><span data-stu-id="25323-119">There are no known differences between the developer features for commercial customers and those for government cloud customers.</span></span>

- <span data-ttu-id="25323-120">アドインのデータソースなどの外部アプリケーションへの接続は、政府機関の環境でサポートされているシステムセキュリティ境界内にあるソースに制限されます。</span><span class="sxs-lookup"><span data-stu-id="25323-120">Connections to external applications such as data sources for add-ins are limited to sources that are located within the system security boundaries supported by your government environment.</span></span>
- <span data-ttu-id="25323-121">クラウドサービスのセキュリティ境界内でデータソースにアクセスできる接続シナリオでは、Business Connectivity Services (BCS) 機能がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="25323-121">Business Connectivity Services (BCS) functionality is supported for connectivity scenarios in which the data sources remain reachable within the security boundary for your cloud service.</span></span>

<span data-ttu-id="25323-122">サイトでサードパーティ製アプリケーションを使用する場合は、組織でのこれらのサービスの適切な使用法を評価する際に、サードパーティによって提供されるプライバシーとコンプライアンスのステートメントを確認してください。</span><span class="sxs-lookup"><span data-stu-id="25323-122">If you use third-party applications on sites, review the privacy and compliance statements provided by the third parties when assessing the appropriate use of these services for your organization.</span></span> <span data-ttu-id="25323-123">サードパーティ製のアプリケーションおよびサービスでは、政府機関の外部のシステムで組織の顧客データを保存、送信、および処理することによって、コンプライアンスやデータ保護のコミットメントの対象にならない場合があります。</span><span class="sxs-lookup"><span data-stu-id="25323-123">Third-party applications and services might involve storing, transmitting, and processing your organization's customer data on third-party systems that are outside of the government cloud and therefore not covered by its compliance and data protection commitments.</span></span> 

## <a name="it-admin-features"></a><span data-ttu-id="25323-124">IT 管理者向けの機能</span><span class="sxs-lookup"><span data-stu-id="25323-124">IT admin features</span></span>

<span data-ttu-id="25323-125">ここでは、商用のお客様向けの IT 管理者向けの機能と、行政機関のお客様向けの相違点を示します。</span><span class="sxs-lookup"><span data-stu-id="25323-125">Here are the differences between the IT admin features for commercial customers and those for government cloud customers.</span></span>

- <span data-ttu-id="25323-126">GCC High お客様はサイトアドレスを変更できない</span><span class="sxs-lookup"><span data-stu-id="25323-126">Changing a site address is not available for GCC High customers</span></span>
- <span data-ttu-id="25323-127">ハイブリッド SharePoint サーバーは、すべての政府機関のお客様が利用できるわけではありません</span><span class="sxs-lookup"><span data-stu-id="25323-127">Hybrid SharePoint Server is not available for all government cloud customers</span></span>
- <span data-ttu-id="25323-128">SharePoint 移行ツールおよび移行マネージャーは、構成の変更を必要とします。</span><span class="sxs-lookup"><span data-stu-id="25323-128">The SharePoint Migration Tool and Migration Manager require a configuration change.</span></span> <span data-ttu-id="25323-129">詳細については、「 [Spmt government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-129">For info, see [SPMT government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).</span></span>
- <span data-ttu-id="25323-130">Mover.io はまだサポートされていません</span><span class="sxs-lookup"><span data-stu-id="25323-130">Mover.io is not yet supported</span></span>
- <span data-ttu-id="25323-131">複数地域は、すべての政府機関のお客様が利用できるわけではありません。</span><span class="sxs-lookup"><span data-stu-id="25323-131">Multi-geo is not available for all government cloud customers</span></span>

<span data-ttu-id="25323-132">FastTrack の移行の詳細については、「 [Office 365 US Government サービスの説明](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-132">For info about FastTrack migration, see the [Office 365 US Government service description](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).</span></span>

## <a name="security-and-compliance-features"></a><span data-ttu-id="25323-133">セキュリティとコンプライアンスの機能</span><span class="sxs-lookup"><span data-stu-id="25323-133">Security and compliance features</span></span>

<span data-ttu-id="25323-134">商用のお客様や政府機関のお客様のためのセキュリティとコンプライアンスの機能には、既知の違いはありません。</span><span class="sxs-lookup"><span data-stu-id="25323-134">There are no known differences between the security and compliance features for commercial customers and those for government cloud customers.</span></span>

<span data-ttu-id="25323-135">セキュリティとコンプライアンスの機能の詳細については、「 [セキュリティ & コンプライアンスセンター](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-135">For information about security and compliance features, see the [Security & Compliance Center](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center).</span></span>

<span data-ttu-id="25323-136">Government の Azure Active Directory 機能の詳細については、「 [Azure Government Security + Identity ドキュメント](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-136">For information about Azure Active Directory features for government, see [Azure Government Security + Identity documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory).</span></span> 

<span data-ttu-id="25323-137">Government の Azure Information Protection 機能の詳細については、「 [Azure Information Protection Premium Government サービスの説明](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-137">For information about Azure Information Protection features for government, see the [Azure Information Protection Premium Government Service Description](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description).</span></span> 

## <a name="sites-and-content"></a><span data-ttu-id="25323-138">サイトおよびコンテンツ</span><span class="sxs-lookup"><span data-stu-id="25323-138">Sites and content</span></span>

<span data-ttu-id="25323-139">以下は、商用のお客様向けのサイトとコンテンツ機能の相違点と、政府機関のお客様のためのものです。</span><span class="sxs-lookup"><span data-stu-id="25323-139">Here are the differences between the sites and content features for commercial customers and those for government cloud customers:</span></span>

- <span data-ttu-id="25323-140">Amazon Kindle、Bing Maps、Twitter、YouTube web パーツなどのインターネットサービスへの接続に依存する web パーツは、期待どおりに機能しません。</span><span class="sxs-lookup"><span data-stu-id="25323-140">Web parts that rely on connections to Internet services, such as the Amazon Kindle, Bing Maps, Twitter, and YouTube web parts, won't work as expected</span></span>
- <span data-ttu-id="25323-141">組織のアセットライブラリは使用できません</span><span class="sxs-lookup"><span data-stu-id="25323-141">Organization assets library is not available</span></span>
- <span data-ttu-id="25323-142">リストとページを Teams に追加することは、GCC High および DoD のお客様には使用できません。</span><span class="sxs-lookup"><span data-stu-id="25323-142">Adding lists and pages to Teams isn't available for GCC High and DoD customers</span></span>

## <a name="search-features"></a><span data-ttu-id="25323-143">検索機能</span><span class="sxs-lookup"><span data-stu-id="25323-143">Search features</span></span>

<span data-ttu-id="25323-144">以下に、商用のお客様向けの検索機能と、政府機関のお客様のための相違点を示します。</span><span class="sxs-lookup"><span data-stu-id="25323-144">Here are the differences between the search features for commercial customers and those for government cloud customers:</span></span>

- <span data-ttu-id="25323-145">Microsoft 検索統合は使用できません。</span><span class="sxs-lookup"><span data-stu-id="25323-145">Microsoft Search integration is not available.</span></span>

## <a name="sharing-and-sync"></a><span data-ttu-id="25323-146">共有と同期</span><span class="sxs-lookup"><span data-stu-id="25323-146">Sharing and sync</span></span>

<span data-ttu-id="25323-147">商用クラウド環境と官公庁クラウド環境の機能の違いについては、「 [ファイル共有](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-147">For feature differences between the commercial cloud and the government cloud environments, see [File sharing](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).</span></span>

## <a name="plan-for-governance"></a><span data-ttu-id="25323-148">ガバナンスを計画する</span><span class="sxs-lookup"><span data-stu-id="25323-148">Plan for governance</span></span>

<span data-ttu-id="25323-149">クラウドへの移行では、組み込みの管理コントロールを使用したプロジェクトエクスペリエンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="25323-149">Your move to the cloud offers transformative experiences with built-in admin controls.</span></span> <span data-ttu-id="25323-150">ガバナンスの要件と、それに対応する方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="25323-150">Determine your requirements for governance and how you can meet them.</span></span> <span data-ttu-id="25323-151">詳細については、「 [ワークチームを Microsoft 365 に変換するためのガバナンスを計画](https://resources.techcommunity.microsoft.com/teamwork-governance/) する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="25323-151">Go to [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) for more information.</span></span> <span data-ttu-id="25323-152">Office 365 グループ、SharePoint、Teams などに関するガイダンスが記載されています。</span><span class="sxs-lookup"><span data-stu-id="25323-152">You will find guidance about Office 365 Groups, SharePoint, Teams and more.</span></span>

## <a name="deploy-sharepoint-for-collaboration"></a><span data-ttu-id="25323-153">コラボレーションのために SharePoint を展開する</span><span class="sxs-lookup"><span data-stu-id="25323-153">Deploy SharePoint for collaboration</span></span>

<span data-ttu-id="25323-154">Microsoft US government cloud で組織を設定した後、 [SharePoint 導入リソースセンター](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)で説明されている推奨される展開パスに従います。</span><span class="sxs-lookup"><span data-stu-id="25323-154">After you set up your organization in the Microsoft US government cloud, follow the recommended deployment path outlined in the [SharePoint adoption resource center](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/).</span></span> <span data-ttu-id="25323-155">導入の際には、管理エキスパートに協力してください。</span><span class="sxs-lookup"><span data-stu-id="25323-155">Be sure to engage with your Adoption and Change Management champions.</span></span>
<span data-ttu-id="25323-156">また、 [Fasttrack](https://www.microsoft.com/fasttrack) または選択したパートナーと連携して、ユーザーにサービスをロールアウトすることもできます。</span><span class="sxs-lookup"><span data-stu-id="25323-156">You can also work with [FastTrack](https://www.microsoft.com/fasttrack) or your chosen partner to roll out the service to your users.</span></span>
<span data-ttu-id="25323-157">Microsoft のセキュリティ [センター](https://www.microsoft.com/trust-center) にアクセスすることにより、お客様にサービスを提供するように組織を支援する方法についての基本理念として、microsoft のセキュリティ、プライバシー、法令遵守の方法について知ることができます。</span><span class="sxs-lookup"><span data-stu-id="25323-157">Visit the [Microsoft Trust Center](https://www.microsoft.com/trust-center) to learn more about how Microsoft approaches security, privacy, and compliance, core tenets for how we empower organizations to serve their customers.</span></span>
