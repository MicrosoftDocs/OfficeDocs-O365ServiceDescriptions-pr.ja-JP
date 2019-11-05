---
title: Microsoft 365 コンプライアンスを計画する-GCC
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: このガイダンスは、米国連邦、州、地方、エスニック、または territorial government の各エンティティに Office 365 の展開を推進する IT 担当者、または政府の規制と要件に従うデータを処理するその他のエンティティ (Microsoft を使用している場合) を対象としています。365 Government-GCC は、これらの要件を満たすのに適しています。
ms.openlocfilehash: 50649287df37afe20b58f98333a10bc7885b417d
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890507"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a><span data-ttu-id="3d53e-103">Microsoft 365 コンプライアンス (GCC) の計画</span><span class="sxs-lookup"><span data-stu-id="3d53e-103">Plan for Microsoft 365 Compliance – GCC</span></span>

<span data-ttu-id="3d53e-104">このガイダンスは、米国連邦、州、地方、エスニック、または territorial government の各エンティティに Office 365 の展開を推進する IT 担当者、または政府の規制と要件に従うデータを処理するその他のエンティティ (Microsoft を使用している場合) を対象としています。365 Government-GCC は、これらの要件を満たすのに適しています。</span><span class="sxs-lookup"><span data-stu-id="3d53e-104">This guidance is for IT pros who are driving deployments of Office 365 in US federal, state, local, tribal, or territorial government entities or other entities that handle data that is subject to government regulations and requirements, where the use of Microsoft 365 Government - GCC is appropriate to meet these requirements.</span></span>

> [!NOTE]
> <span data-ttu-id="3d53e-105">組織が既に Microsoft 365 Government-GCC の資格要件を満たしており、プログラムに適用されている場合は、手順1と2を省略して手順3に直接進むことができます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-105">If your organization has already met the Microsoft 365 Government - GCC eligibility requirements and applied for and been accepted into the program, you can skip steps 1 and 2 and go directly to step 3.</span></span>

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a><span data-ttu-id="3d53e-106">手順 1. </span><span class="sxs-lookup"><span data-stu-id="3d53e-106">Step 1.</span></span> <span data-ttu-id="3d53e-107">組織に Microsoft 365 Government-GCC が必要かどうかを判断し、資格要件を満たしているかどうかを判断する</span><span class="sxs-lookup"><span data-stu-id="3d53e-107">Determine whether your organization needs Microsoft 365 Government - GCC and meets eligibility requirements</span></span>

<span data-ttu-id="3d53e-108">Microsoft 365 Government-GCC 環境は、FedRAMP を含むクラウドサービスの米国政府の要件と、刑事司法および連邦税務情報システム (CJI および FTI データ型) の要件に準拠しています。</span><span class="sxs-lookup"><span data-stu-id="3d53e-108">The Microsoft 365 Government - GCC environment complies with US government requirements for cloud services, including FedRAMP Moderate, and requirements for criminal justice and federal tax information systems (CJI and FTI data types).</span></span>

<span data-ttu-id="3d53e-109">Office 365 の機能を楽しんだだけでなく、組織は Microsoft 365 Government-GCC 固有の次の機能を活用することができます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-109">In addition to enjoying the features and capabilities of Office 365, organizations benefit from the following features that are unique to Microsoft 365 Government - GCC:</span></span>

- <span data-ttu-id="3d53e-110">組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。</span><span class="sxs-lookup"><span data-stu-id="3d53e-110">Your organization’s customer content is logically segregated from customer content in the commercial Office 365 services from Microsoft.</span></span>

- <span data-ttu-id="3d53e-111">組織の顧客コンテンツは、米国内に格納されます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-111">Your organization’s customer content is stored within the United States.</span></span>

- <span data-ttu-id="3d53e-112">組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-112">Access to your organization’s customer content is restricted to screened Microsoft personnel.</span></span>

- <span data-ttu-id="3d53e-113">Microsoft 365 Government-GCC は、米国の公的機関のお客様に必要な認定および認定に準拠しています。</span><span class="sxs-lookup"><span data-stu-id="3d53e-113">Microsoft 365 Government - GCC complies with certifications and accreditations that are required for US public sector customers.</span></span>

<span data-ttu-id="3d53e-114">米国政府機関のお客様向けの Microsoft 365 Government-GCC 製品の詳細については、「特典要件」を含む「 [Office 365 政府](https://products.office.com/government/compare-office-365-government-plans)機関向けのプラン」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d53e-114">You can find more information about the Microsoft 365 Government - GCC offering for US Government customers at [Office 365 Government plans](https://products.office.com/government/compare-office-365-government-plans), including eligibility requirements.</span></span>

<span data-ttu-id="3d53e-115">「 [Office 365 US Government サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)」では、プラットフォームの利点について説明します。これは、米国内での会議のコンプライアンス要件を中心としています。</span><span class="sxs-lookup"><span data-stu-id="3d53e-115">The [Office 365 US Government service description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) describes the platform’s benefits, which are centered on meeting compliance requirements within the United States.</span></span>

> [!TIP]
> <span data-ttu-id="3d53e-116">サービスの説明の情報の表を Excel ブックに転送して、組織の  **y/n に関連**し、 **組織のニーズを満たす**2 つの列を追加することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3d53e-116">You might want to transfer the tables of information in the service description into an Excel workbook and add two columns: **Relevant for my organization Y/N** and **Meets the needs of my organization Y/N**.</span></span> <span data-ttu-id="3d53e-117">その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-117">Then you can review this list with your colleagues to confirm that this service meets your organization’s needs.</span></span>

> [!NOTE]
> <span data-ttu-id="3d53e-118">Microsoft 365 Government-GCC は米国でのみ利用可能です。</span><span class="sxs-lookup"><span data-stu-id="3d53e-118">Microsoft 365 Government - GCC is only available in the United States.</span></span> <span data-ttu-id="3d53e-119">米国以外の政府機関のお客様は、多くの[Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。</span><span class="sxs-lookup"><span data-stu-id="3d53e-119">Non–US Government customers can choose from a number of [Office 365 Government plans](https://products.office.com/government/compare-office-365-government-plans).</span></span>

<span data-ttu-id="3d53e-120">**判断ポイント**:</span><span class="sxs-lookup"><span data-stu-id="3d53e-120">**Decision points**:</span></span> <br/>
- <span data-ttu-id="3d53e-121">*Microsoft 365 Government-GCC が組織に適しているかどうかを決定します。*</span><span class="sxs-lookup"><span data-stu-id="3d53e-121">*Decide whether Microsoft 365 Government - GCC is appropriate for your organization.*</span></span>
- <span data-ttu-id="3d53e-122">*組織が資格要件を満たしていることを確認します。*</span><span class="sxs-lookup"><span data-stu-id="3d53e-122">*Confirm that your organization meets eligibility requirements.*</span></span>

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a><span data-ttu-id="3d53e-123">手順 2. </span><span class="sxs-lookup"><span data-stu-id="3d53e-123">Step 2.</span></span> <span data-ttu-id="3d53e-124">Microsoft 365 Government-GCC への適用</span><span class="sxs-lookup"><span data-stu-id="3d53e-124">Apply for Microsoft 365 Government - GCC</span></span>

<span data-ttu-id="3d53e-125">このサービスが組織に適していると判断した場合は、[このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。</span><span class="sxs-lookup"><span data-stu-id="3d53e-125">Having decided that this service is right for your organization, start the process of [applying for this service](https://products.office.com/government/eligibility-validation).</span></span>

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a><span data-ttu-id="3d53e-126">手順 3. </span><span class="sxs-lookup"><span data-stu-id="3d53e-126">Step 3.</span></span> <span data-ttu-id="3d53e-127">Microsoft 365 Government-GCC の既定のセキュリティ設定について</span><span class="sxs-lookup"><span data-stu-id="3d53e-127">Understand Microsoft 365 Government - GCC default security settings</span></span>

<span data-ttu-id="3d53e-128">既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3d53e-128">We recommend that you take time to carefully review your admin and security settings before you modify them and consider the impact on compliance before you make any changes to the default security settings.</span></span>

<span data-ttu-id="3d53e-129">**判断ポイント**:*既定の Microsoft 365 Government-GCC セキュリティ設定を変更するかどうかを決定します。解決するには、変更による影響を最初に理解する必要があります。*</span><span class="sxs-lookup"><span data-stu-id="3d53e-129">**Decision point**: *Decide whether you’ll modify any of the default Microsoft 365 Government - GCC security settings, resolving to first understand the impact of any changes you might make.*</span></span>

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc"></a><span data-ttu-id="3d53e-130">手順 4. </span><span class="sxs-lookup"><span data-stu-id="3d53e-130">Step 4.</span></span> <span data-ttu-id="3d53e-131">Microsoft 365 Government – GCC で、現在どの機能が使用できなくなっているか、または既定で無効になっているかを理解する</span><span class="sxs-lookup"><span data-stu-id="3d53e-131">Understand which capabilities are currently unavailable or disabled by default in Microsoft 365 Government – GCC</span></span>

<span data-ttu-id="3d53e-132">政府機関のお客様の要件を満たすために、Microsoft 365 Government とエンタープライズプランにはいくつかの違いがあります。</span><span class="sxs-lookup"><span data-stu-id="3d53e-132">To accommodate the requirements of our government cloud customers, there are some differences between Microsoft 365 Government - GCC and enterprise plans.</span></span> <span data-ttu-id="3d53e-133">利用可能な機能を確認するには、次の表を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d53e-133">Refer to the following table to see which features are available.</span></span>

|                                         | <span data-ttu-id="3d53e-134">**機能**</span><span class="sxs-lookup"><span data-stu-id="3d53e-134">**Feature**</span></span>                                     | <span data-ttu-id="3d53e-135">**GCC の状態**</span><span class="sxs-lookup"><span data-stu-id="3d53e-135">**GCC Status**</span></span>         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| <span data-ttu-id="3d53e-136">**情報保護 & ガバナンス**</span><span class="sxs-lookup"><span data-stu-id="3d53e-136">**Information protection & governance**</span></span> | <span data-ttu-id="3d53e-137">アーカイブ</span><span class="sxs-lookup"><span data-stu-id="3d53e-137">Archiving</span></span>                                       | <span data-ttu-id="3d53e-138">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-138">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-139">手動によるラベルとポリシー</span><span class="sxs-lookup"><span data-stu-id="3d53e-139">Manual labels and policies</span></span>                      | <span data-ttu-id="3d53e-140">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-140">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-141">ラベルの自動適用</span><span class="sxs-lookup"><span data-stu-id="3d53e-141">Auto application of labels</span></span>                      | <span data-ttu-id="3d53e-142">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-142">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-143">機密データ型に基づくラベル</span><span class="sxs-lookup"><span data-stu-id="3d53e-143">Labels based on sensitive data types</span></span>            | <span data-ttu-id="3d53e-144">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-144">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-145">クエリに基づくラベルと関連付けられたポリシー</span><span class="sxs-lookup"><span data-stu-id="3d53e-145">Labels and associated policies based on queries</span></span> | <span data-ttu-id="3d53e-146">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-146">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-147">ファイル計画</span><span class="sxs-lookup"><span data-stu-id="3d53e-147">File plan</span></span>                                       | <span data-ttu-id="3d53e-148">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-148">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-149">推奨されるポリシー</span><span class="sxs-lookup"><span data-stu-id="3d53e-149">Recommended policies</span></span>                            | <span data-ttu-id="3d53e-150">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-150">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-151">スマートインポートフィルター</span><span class="sxs-lookup"><span data-stu-id="3d53e-151">Smart import filters</span></span>                            | <span data-ttu-id="3d53e-152">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-152">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-153">イベント ベースの保持</span><span class="sxs-lookup"><span data-stu-id="3d53e-153">Event-based retention</span></span>                           | <span data-ttu-id="3d53e-154">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-154">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-155">廃棄のレビュー</span><span class="sxs-lookup"><span data-stu-id="3d53e-155">Disposition review</span></span>                              | <span data-ttu-id="3d53e-156">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-156">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-157">情報障壁</span><span class="sxs-lookup"><span data-stu-id="3d53e-157">Information barriers</span></span>                            | <span data-ttu-id="3d53e-158">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-158">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-159">ファイルと電子メールのデータ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="3d53e-159">Data loss prevention (DLP) for files and email</span></span>  | <span data-ttu-id="3d53e-160">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-160">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-161">Teams チャットおよびチャネル会話の DLP</span><span class="sxs-lookup"><span data-stu-id="3d53e-161">DLP for Teams chat and channel conversations</span></span>    | <span data-ttu-id="3d53e-162">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-162">Available</span></span>              |
| <span data-ttu-id="3d53e-163">**Insider リスク管理**</span><span class="sxs-lookup"><span data-stu-id="3d53e-163">**Insider risk management**</span></span>             | <span data-ttu-id="3d53e-164">高度なメッセージ暗号化</span><span class="sxs-lookup"><span data-stu-id="3d53e-164">Advanced Message Encryption</span></span>                     | <span data-ttu-id="3d53e-165">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-165">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-166">通信のコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="3d53e-166">Communication compliance</span></span>                        | <span data-ttu-id="3d53e-167">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-167">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-168">顧客ロックボックス</span><span class="sxs-lookup"><span data-stu-id="3d53e-168">Customer Lockbox</span></span>                                | <span data-ttu-id="3d53e-169">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-169">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-170">カスタマー キー</span><span class="sxs-lookup"><span data-stu-id="3d53e-170">Customer Key</span></span>                                    | <span data-ttu-id="3d53e-171">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-171">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-172">特権アクセスの管理</span><span class="sxs-lookup"><span data-stu-id="3d53e-172">Privileged access management</span></span>                    | <span data-ttu-id="3d53e-173">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-173">On engineering backlog</span></span> |
| <span data-ttu-id="3d53e-174">**& 応答の検出**</span><span class="sxs-lookup"><span data-stu-id="3d53e-174">**Discover & respond**</span></span>                  | <span data-ttu-id="3d53e-175">インプレースの予約</span><span class="sxs-lookup"><span data-stu-id="3d53e-175">In-place reservation</span></span>                            | <span data-ttu-id="3d53e-176">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-176">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-177">ケース管理</span><span class="sxs-lookup"><span data-stu-id="3d53e-177">Case management</span></span>                                 | <span data-ttu-id="3d53e-178">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-178">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-179">検索</span><span class="sxs-lookup"><span data-stu-id="3d53e-179">Search</span></span>                                          | <span data-ttu-id="3d53e-180">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-180">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-181">エクスポート</span><span class="sxs-lookup"><span data-stu-id="3d53e-181">Export</span></span>                                          | <span data-ttu-id="3d53e-182">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-182">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-183">RMS 復号化</span><span class="sxs-lookup"><span data-stu-id="3d53e-183">RMS decryption</span></span>                                  | <span data-ttu-id="3d53e-184">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-184">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-185">ネイティブエクスポート</span><span class="sxs-lookup"><span data-stu-id="3d53e-185">Native export</span></span>                                   | <span data-ttu-id="3d53e-186">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-186">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-187">監査</span><span class="sxs-lookup"><span data-stu-id="3d53e-187">Auditing</span></span>                                        | <span data-ttu-id="3d53e-188">Available</span><span class="sxs-lookup"><span data-stu-id="3d53e-188">Available</span></span>              |
|                                         | <span data-ttu-id="3d53e-189">高度な処理</span><span class="sxs-lookup"><span data-stu-id="3d53e-189">Advanced processing</span></span>                             | <span data-ttu-id="3d53e-190">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-190">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-191">電子メールスレッド</span><span class="sxs-lookup"><span data-stu-id="3d53e-191">Email threading</span></span>                                 | <span data-ttu-id="3d53e-192">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-192">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-193">ほぼ重複した識別</span><span class="sxs-lookup"><span data-stu-id="3d53e-193">Near duplicate identification</span></span>                   | <span data-ttu-id="3d53e-194">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-194">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-195">テーマ</span><span class="sxs-lookup"><span data-stu-id="3d53e-195">Themes</span></span>                                          | <span data-ttu-id="3d53e-196">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-196">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-197">予測コーディング</span><span class="sxs-lookup"><span data-stu-id="3d53e-197">Predictive coding</span></span>                               | <span data-ttu-id="3d53e-198">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-198">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-199">読み込みファイルを使用したエクスポートの処理</span><span class="sxs-lookup"><span data-stu-id="3d53e-199">Processed export with load file</span></span>                 | <span data-ttu-id="3d53e-200">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-200">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-201">タグ</span><span class="sxs-lookup"><span data-stu-id="3d53e-201">Tagging</span></span>                                         | <span data-ttu-id="3d53e-202">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-202">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-203">表示者</span><span class="sxs-lookup"><span data-stu-id="3d53e-203">Viewers</span></span>                                         | <span data-ttu-id="3d53e-204">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-204">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-205">Redactions</span><span class="sxs-lookup"><span data-stu-id="3d53e-205">Redactions</span></span>                                      | <span data-ttu-id="3d53e-206">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-206">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-207">フィルター</span><span class="sxs-lookup"><span data-stu-id="3d53e-207">Filtering</span></span>                                       | <span data-ttu-id="3d53e-208">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-208">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-209">保管担当者からワークロードへのマッピング</span><span class="sxs-lookup"><span data-stu-id="3d53e-209">Custodian to workload mapping</span></span>                   | <span data-ttu-id="3d53e-210">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-210">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-211">保管担当者通信</span><span class="sxs-lookup"><span data-stu-id="3d53e-211">Custodian communications</span></span>                        | <span data-ttu-id="3d53e-212">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-212">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-213">チェックセット</span><span class="sxs-lookup"><span data-stu-id="3d53e-213">Review sets</span></span>                                     | <span data-ttu-id="3d53e-214">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-214">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-215">レビューと注釈</span><span class="sxs-lookup"><span data-stu-id="3d53e-215">Review and annotate</span></span>                             | <span data-ttu-id="3d53e-216">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-216">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-217">Office 以外の365の取り込み</span><span class="sxs-lookup"><span data-stu-id="3d53e-217">Non-Office 365 ingestion</span></span>                        | <span data-ttu-id="3d53e-218">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-218">On engineering backlog</span></span> |
|                                         | <span data-ttu-id="3d53e-219">検索用語レポート</span><span class="sxs-lookup"><span data-stu-id="3d53e-219">Search Term report</span></span>                              | <span data-ttu-id="3d53e-220">エンジニアリングバックログの場合</span><span class="sxs-lookup"><span data-stu-id="3d53e-220">On engineering backlog</span></span> |

<span data-ttu-id="3d53e-221">**判断ポイント**:*コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*</span><span class="sxs-lookup"><span data-stu-id="3d53e-221">**Decision point**: *Decide whether the compliance features meet your organization’s needs.*</span></span>