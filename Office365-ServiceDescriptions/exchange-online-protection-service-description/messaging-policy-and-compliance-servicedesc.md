---
title: メッセージングのポリシーと準拠 [ServiceDesc]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online ・保護 (EOP) には、メッセージングのポリシーが用意されていて、電子メール データを管理することができますコンプライアンス機能します。
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036230"
---
# <a name="messaging-policy-and-complianceservicedesc"></a><span data-ttu-id="fb646-103">メッセージングのポリシーと準拠 [ServiceDesc]</span><span class="sxs-lookup"><span data-stu-id="fb646-103">Messaging Policy and Compliance[ServiceDesc]</span></span>

<span data-ttu-id="fb646-104">Microsoft Exchange Online ・保護 (EOP) には、メッセージングのポリシーが用意されていて、電子メール データを管理することができますコンプライアンス機能します。</span><span class="sxs-lookup"><span data-stu-id="fb646-104">Microsoft Exchange Online Protection (EOP) provides messaging policy and compliance features that can help you manage your email data.</span></span>
  
<span data-ttu-id="fb646-p101">EOP のすべての機能についての説明をご覧になりますか?「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb646-p101">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="transport-rules"></a><span data-ttu-id="fb646-107">トランスポート ルール</span><span class="sxs-lookup"><span data-stu-id="fb646-107">Transport rules</span></span>
<span data-ttu-id="fb646-108"><a name="BKMK_transportrules"> </a></span><span class="sxs-lookup"><span data-stu-id="fb646-108"></span></span>

<span data-ttu-id="fb646-p102">トランスポート ルールは、電子メールに会社固有のポリシーを適用できる柔軟性をもたらします。トランスポート ルールは条件および例外を定義できる柔軟性のある条件と、その条件に基づいて実行される処理で構成されます。EOP のトランスポート ルールの詳細については、「[トランスポート ルール](https://go.microsoft.com/fwlink/p/?LinkId=320399)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb646-p102">Transport rules provide you with the flexibility to apply your own company-specific policies to email. Transport rules are made up of flexible criteria, which allow you to define conditions and exceptions, and actions to take based on the criteria. For more information about Transport rules in EOP, see [Transport Rules](https://go.microsoft.com/fwlink/p/?LinkId=320399).</span></span>
  
## <a name="audit-logging"></a><span data-ttu-id="fb646-112">監査ログ</span><span class="sxs-lookup"><span data-stu-id="fb646-112">Audit logging</span></span>
<span data-ttu-id="fb646-113"><a name="BKMK_auditlogging"> </a></span><span class="sxs-lookup"><span data-stu-id="fb646-113"></span></span>

<span data-ttu-id="fb646-p103">監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。詳細については、「[EOP の監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=314258)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb646-p103">Audit logging lets you track specific changes made by administrators to your organization. These reports help you meet regulatory, compliance, and litigation requirements. For more information, see [Auditing Reports in EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).</span></span>
  
## <a name="data-loss-prevention-dlp"></a><span data-ttu-id="fb646-117">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="fb646-117">Data loss prevention (DLP)</span></span>
<span data-ttu-id="fb646-118"><a name="BKMK_datalossprevention"> </a></span><span class="sxs-lookup"><span data-stu-id="fb646-118"></span></span>

<span data-ttu-id="fb646-p104">EOP スタンドアロンのお客様は利用できません。データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。DLP 機能を使用すると、業務の生産性に影響を及ぼすことなく機密データを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="fb646-p104">Not available to EOP standalone customers. Data loss prevention (DLP) helps you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="fb646-123">EAC で DLP ポリシーを構成することにより、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="fb646-123">You can configure DLP policies in the EAC, which allows you to:</span></span>
  
- <span data-ttu-id="fb646-124">PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。</span><span class="sxs-lookup"><span data-stu-id="fb646-124">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="fb646-125">既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。</span><span class="sxs-lookup"><span data-stu-id="fb646-125">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="fb646-126">DLP ポリシーを完全に実施する前にその効果をテストできます。</span><span class="sxs-lookup"><span data-stu-id="fb646-126">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="fb646-127">独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。</span><span class="sxs-lookup"><span data-stu-id="fb646-127">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="fb646-128">メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。</span><span class="sxs-lookup"><span data-stu-id="fb646-128">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which the service takes action.</span></span>
    
- <span data-ttu-id="fb646-p105">ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。ドキュメントのフィンガープリント機能を使用すると、テキスト ベースのフォームを基に、機密情報のカスタム タイプを手早く作成し、トランスポート ルールと DLP ポリシーを定義できます。</span><span class="sxs-lookup"><span data-stu-id="fb646-p105">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="fb646-131">ポリシー ヒントを追加して、Outlook 2013、Outlook Web App、およびデバイス用 OWA の各ユーザーに通知メッセージを表示し、データの損失を削減できます。また、誤検知の報告を許可することによりポリシーの有効性を改善することもできます。</span><span class="sxs-lookup"><span data-stu-id="fb646-131">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span>
    
- <span data-ttu-id="fb646-132">インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="fb646-132">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
> [!NOTE]
> <span data-ttu-id="fb646-p106">DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。</span><span class="sxs-lookup"><span data-stu-id="fb646-p106">DLP policies are applied only to mail that passes in or out of the organization. Intra-organizational (internal) mail does not have DLP policies applied unless you run Exchange Server 2013 with DLP on-premises. This also applies to DLP policy tips, which inform users about potential policy violations before sensitive data is mistakenly sent to unauthorized recipients.</span></span> 
  
<span data-ttu-id="fb646-136">DLP の詳細については、「[データ損失防止](https://go.microsoft.com/fwlink/p/?LinkId=320398)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb646-136">To learn more about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=320398).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="fb646-137">Office 365 Message Encryption</span><span class="sxs-lookup"><span data-stu-id="fb646-137">Office 365 Message Encryption</span></span>
<span data-ttu-id="fb646-138"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="fb646-138"></span></span>

<span data-ttu-id="fb646-p107">Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。Exchange Online の Office 365 Message Encryption の詳細については、「Exchange Online サービスの説明」の「[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fb646-p107">Office 365 Message Encryption, a part of Azure Information Protection, is an online service that allows email users to send encrypted email messages to anyone. On-premises customers can access Office 365 Message Encryption by purchasing Azure Information Protection and using Exchange Online Protection to set up mail flow through Exchange Online. To learn more about Office 365 Message Encryption in Exchange Online, see [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in the Exchange Online Service Description.</span></span> 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a><span data-ttu-id="fb646-142">EOP オプション間のメッセージング ポリシーとコンプライアンス機能</span><span class="sxs-lookup"><span data-stu-id="fb646-142">Messaging policy and compliance features across EOP options</span></span>
<span data-ttu-id="fb646-143"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="fb646-143"></span></span>

|<span data-ttu-id="fb646-144">**機能**</span><span class="sxs-lookup"><span data-stu-id="fb646-144">**Feature**</span></span>|<span data-ttu-id="fb646-145">**EOP スタンドアロン**</span><span class="sxs-lookup"><span data-stu-id="fb646-145">**EOP standalone**</span></span>|<span data-ttu-id="fb646-146">**Exchange Online の EOP 機能**</span><span class="sxs-lookup"><span data-stu-id="fb646-146">**EOP features in Exchange Online**</span></span>|<span data-ttu-id="fb646-147">**Exchange Enterprise CAL とサービス**</span><span class="sxs-lookup"><span data-stu-id="fb646-147">**Exchange Enterprise CAL with Services**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="fb646-148">トランスポート ルール</span><span class="sxs-lookup"><span data-stu-id="fb646-148">Transport rules</span></span>  <br/> |<span data-ttu-id="fb646-149">はい<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="fb646-149">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="fb646-150"><sup>1</sup>を [はい] します。</span><span class="sxs-lookup"><span data-stu-id="fb646-150">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="fb646-151">はい</span><span class="sxs-lookup"><span data-stu-id="fb646-151">Yes</span></span>  <br/> |
|<span data-ttu-id="fb646-152">監査ログ</span><span class="sxs-lookup"><span data-stu-id="fb646-152">Audit logging</span></span>  <br/> |<span data-ttu-id="fb646-153"><sup>2</sup>を [はい] します。</span><span class="sxs-lookup"><span data-stu-id="fb646-153">Yes<sup>2</sup></span></span> <br/> |<span data-ttu-id="fb646-154">○</span><span class="sxs-lookup"><span data-stu-id="fb646-154">Yes</span></span>  <br/> |<span data-ttu-id="fb646-155">はい</span><span class="sxs-lookup"><span data-stu-id="fb646-155">Yes</span></span>  <br/> |
|<span data-ttu-id="fb646-156">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="fb646-156">Data Loss Prevention (DLP)</span></span>  <br/> |<span data-ttu-id="fb646-157">いいえ</span><span class="sxs-lookup"><span data-stu-id="fb646-157">No</span></span>  <br/> |<span data-ttu-id="fb646-158">はい</span><span class="sxs-lookup"><span data-stu-id="fb646-158">Yes</span></span>  <br/> |<span data-ttu-id="fb646-159"><sup>3</sup>を [はい] します。</span><span class="sxs-lookup"><span data-stu-id="fb646-159">Yes<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="fb646-160">Office 365 Message Encryption</span><span class="sxs-lookup"><span data-stu-id="fb646-160">Office 365 Message Encryption</span></span>  <br/> |<span data-ttu-id="fb646-161"><sup>4</sup>を [はい] します。</span><span class="sxs-lookup"><span data-stu-id="fb646-161">Yes<sup>4</sup></span></span> <br/> |<span data-ttu-id="fb646-162">はい</span><span class="sxs-lookup"><span data-stu-id="fb646-162">Yes</span></span>  <br/> |<span data-ttu-id="fb646-163"><sup>4</sup>を [はい] します。</span><span class="sxs-lookup"><span data-stu-id="fb646-163">Yes<sup>4</sup></span></span> <br/> |
   
> [!NOTE]
> <span data-ttu-id="fb646-p108"><sup>1</sup> 使用可能な条件とアクションは、EOP と Exchange Online で異なります。EOP で使用可能な条件とアクションのリストについては、「 [トランスポート ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320392)」と「[トランスポート ルールのアクション](https://go.microsoft.com/fwlink/p/?LinkId=320393)」を参照してください。Exchange Online で使用可能な条件とアクションのリストについては、「[メール フロー ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320394)」と「[メール フロー ルールの処理](https://go.microsoft.com/fwlink/p/?LinkId=320395)」を参照してください。 > <sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。 > <sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。 > <sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。デスクトップ エクスペリエンスのために、Azure Information Protection アドオンに加えて、Office 365 ProPlus を購入する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fb646-p108"><sup>1</sup> The available criteria and actions differ between EOP and Exchange Online. For a list of available criteria and actions in EOP, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320392) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393). For a list of available criteria and actions in Exchange Online, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320394) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395). > <sup>2</sup> EOP auditing reports are a subset of Exchange Online auditing reports that exclude information about mailboxes. > <sup>3</sup> DLP policy tips are not available for Exchange Enterprise CAL with Services customers. > <sup>4</sup> Supported for on-premises customers who purchase the Azure Information Protection add-on and use Exchange Online Protection to route email through Exchange Online. For the desktop experience, in addition to the Azure Information Protection add-on, Office 365 ProPlus needs to be purchased.</span></span> 
  

