---
title: メッセージングのポリシーと準拠
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。
ms.openlocfilehash: 4e4851def9c6eb5675c5302f865f6db369ffbfeb
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341886"
---
# <a name="messaging-policy-and-compliance"></a><span data-ttu-id="a760b-103">メッセージングのポリシーと準拠</span><span class="sxs-lookup"><span data-stu-id="a760b-103">Messaging Policy and Compliance</span></span>

<span data-ttu-id="a760b-104">Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="a760b-104">Microsoft Exchange Online Protection (EOP) provides messaging policy and compliance features that can help you manage your email data.</span></span>
  
<span data-ttu-id="a760b-105">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="a760b-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="a760b-106">「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-106">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="transport-rules"></a><span data-ttu-id="a760b-107">トランスポート ルール</span><span class="sxs-lookup"><span data-stu-id="a760b-107">Transport rules</span></span>
<span data-ttu-id="a760b-108"><a name="BKMK_transportrules"> </a></span><span class="sxs-lookup"><span data-stu-id="a760b-108"></span></span>

<span data-ttu-id="a760b-p102">トランスポート ルールは、電子メールに会社固有のポリシーを適用できる柔軟性をもたらします。トランスポート ルールは条件および例外を定義できる柔軟性のある条件と、その条件に基づいて実行される処理で構成されます。EOP のトランスポート ルールの詳細については、「[トランスポート ルール](https://go.microsoft.com/fwlink/p/?LinkId=320399)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-p102">Transport rules provide you with the flexibility to apply your own company-specific policies to email. Transport rules are made up of flexible criteria, which allow you to define conditions and exceptions, and actions to take based on the criteria. For more information about Transport rules in EOP, see [Transport Rules](https://go.microsoft.com/fwlink/p/?LinkId=320399).</span></span>
  
## <a name="audit-logging"></a><span data-ttu-id="a760b-112">監査ログ</span><span class="sxs-lookup"><span data-stu-id="a760b-112">Audit logging</span></span>
<span data-ttu-id="a760b-113"><a name="BKMK_auditlogging"> </a></span><span class="sxs-lookup"><span data-stu-id="a760b-113"></span></span>

<span data-ttu-id="a760b-p103">監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。詳細については、「[EOP の監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=314258)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-p103">Audit logging lets you track specific changes made by administrators to your organization. These reports help you meet regulatory, compliance, and litigation requirements. For more information, see [Auditing Reports in EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).</span></span>
  
## <a name="data-loss-prevention-dlp"></a><span data-ttu-id="a760b-117">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="a760b-117">Data loss prevention (DLP)</span></span>
<span data-ttu-id="a760b-118"><a name="BKMK_datalossprevention"> </a></span><span class="sxs-lookup"><span data-stu-id="a760b-118"></span></span>

<span data-ttu-id="a760b-p104">EOP スタンドアロンのお客様は利用できません。データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。DLP 機能を使用すると、業務の生産性に影響を及ぼすことなく機密データを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="a760b-p104">Not available to EOP standalone customers. Data loss prevention (DLP) helps you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="a760b-123">EAC で DLP ポリシーを構成することにより、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="a760b-123">You can configure DLP policies in the EAC, which allows you to:</span></span>
  
- <span data-ttu-id="a760b-124">PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。</span><span class="sxs-lookup"><span data-stu-id="a760b-124">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="a760b-125">既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。</span><span class="sxs-lookup"><span data-stu-id="a760b-125">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="a760b-126">DLP ポリシーを完全に実施する前にその効果をテストできます。</span><span class="sxs-lookup"><span data-stu-id="a760b-126">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="a760b-127">独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。</span><span class="sxs-lookup"><span data-stu-id="a760b-127">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="a760b-128">メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。</span><span class="sxs-lookup"><span data-stu-id="a760b-128">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which the service takes action.</span></span>
    
- <span data-ttu-id="a760b-p105">ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。ドキュメントのフィンガープリント機能を使用すると、テキスト ベースのフォームを基に、機密情報のカスタム タイプを手早く作成し、トランスポート ルールと DLP ポリシーを定義できます。</span><span class="sxs-lookup"><span data-stu-id="a760b-p105">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="a760b-131">ポリシー ヒントを追加して、Outlook 2013、Outlook Web App、およびデバイス用 OWA の各ユーザーに通知メッセージを表示し、データの損失を削減できます。また、誤検知の報告を許可することによりポリシーの有効性を改善することもできます。</span><span class="sxs-lookup"><span data-stu-id="a760b-131">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span>
    
- <span data-ttu-id="a760b-132">インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="a760b-132">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
> [!NOTE]
> <span data-ttu-id="a760b-p106">DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。</span><span class="sxs-lookup"><span data-stu-id="a760b-p106">DLP policies are applied only to mail that passes in or out of the organization. Intra-organizational (internal) mail does not have DLP policies applied unless you run Exchange Server 2013 with DLP on-premises. This also applies to DLP policy tips, which inform users about potential policy violations before sensitive data is mistakenly sent to unauthorized recipients.</span></span> 
  
<span data-ttu-id="a760b-136">DLP の詳細については、「[データ損失防止](https://go.microsoft.com/fwlink/p/?LinkId=320398)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-136">To learn more about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=320398).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="a760b-137">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-137">Office 365 Message Encryption</span></span>
<span data-ttu-id="a760b-138"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="a760b-138"></span></span>

<span data-ttu-id="a760b-p107">Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。Exchange Online の Office 365 Message Encryption の詳細については、「Exchange Online サービスの説明」の「[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-p107">Office 365 Message Encryption, a part of Azure Information Protection, is an online service that allows email users to send encrypted email messages to anyone. On-premises customers can access Office 365 Message Encryption by purchasing Azure Information Protection and using Exchange Online Protection to set up mail flow through Exchange Online. To learn more about Office 365 Message Encryption in Exchange Online, see [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in the Exchange Online Service Description.</span></span> 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a><span data-ttu-id="a760b-142">EOP オプション間のメッセージング ポリシーとコンプライアンス機能</span><span class="sxs-lookup"><span data-stu-id="a760b-142">Messaging policy and compliance features across EOP options</span></span>
<span data-ttu-id="a760b-143"><a name="BKMK_OME_in_EOP"> </a></span><span class="sxs-lookup"><span data-stu-id="a760b-143"></span></span>

|<span data-ttu-id="a760b-144">**機能**</span><span class="sxs-lookup"><span data-stu-id="a760b-144">**Feature**</span></span>|<span data-ttu-id="a760b-145">**EOP スタンドアロン**</span><span class="sxs-lookup"><span data-stu-id="a760b-145">**EOP standalone**</span></span>|<span data-ttu-id="a760b-146">**Exchange Online の EOP 機能**</span><span class="sxs-lookup"><span data-stu-id="a760b-146">**EOP features in Exchange Online**</span></span>|<span data-ttu-id="a760b-147">**Exchange Enterprise CAL とサービス**</span><span class="sxs-lookup"><span data-stu-id="a760b-147">**Exchange Enterprise CAL with Services**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="a760b-148">トランスポート ルール</span><span class="sxs-lookup"><span data-stu-id="a760b-148">Transport rules</span></span>  <br/> |<span data-ttu-id="a760b-149">はい<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-149">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="a760b-150">はい<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-150">Yes<sup>1</sup></span></span> <br/> |<span data-ttu-id="a760b-151">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-151">Yes</span></span>  <br/> |
|<span data-ttu-id="a760b-152">監査ログ</span><span class="sxs-lookup"><span data-stu-id="a760b-152">Audit logging</span></span>  <br/> |<span data-ttu-id="a760b-153">はい<sup>2</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-153">Yes<sup>2</sup></span></span> <br/> |<span data-ttu-id="a760b-154">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-154">Yes</span></span>  <br/> |<span data-ttu-id="a760b-155">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-155">Yes</span></span>  <br/> |
|<span data-ttu-id="a760b-156">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="a760b-156">Data Loss Prevention (DLP)</span></span>  <br/> |<span data-ttu-id="a760b-157">いいえ</span><span class="sxs-lookup"><span data-stu-id="a760b-157">No</span></span>  <br/> |<span data-ttu-id="a760b-158">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-158">Yes</span></span>  <br/> |<span data-ttu-id="a760b-159">はい<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-159">Yes<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="a760b-160">Office 365 Message Encryption</span><span class="sxs-lookup"><span data-stu-id="a760b-160">Office 365 Message Encryption</span></span>  <br/> |<span data-ttu-id="a760b-161">はい<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-161">Yes<sup>4</sup></span></span> <br/> |<span data-ttu-id="a760b-162">はい</span><span class="sxs-lookup"><span data-stu-id="a760b-162">Yes</span></span>  <br/> |<span data-ttu-id="a760b-163">はい<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="a760b-163">Yes<sup>4</sup></span></span> <br/> |
   
> [!NOTE]
> <span data-ttu-id="a760b-164"><sup>1</sup> 使用可能な条件とアクションは、EOP と Exchange Online で異なります。</span><span class="sxs-lookup"><span data-stu-id="a760b-164"><sup>1</sup> The available criteria and actions differ between EOP and Exchange Online.</span></span> <span data-ttu-id="a760b-165">EOP で使用可能な条件とアクションのリストについては、「 [トランスポート ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320392)」と「[トランスポート ルールのアクション](https://go.microsoft.com/fwlink/p/?LinkId=320393)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-165">For a list of available criteria and actions in EOP, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320392) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320393).</span></span> <span data-ttu-id="a760b-166">Exchange Online で使用可能な条件とアクションのリストについては、「[メール フロー ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320394)」と「[メール フロー ルールの処理](https://go.microsoft.com/fwlink/p/?LinkId=320395)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a760b-166">For a list of available criteria and actions in Exchange Online, see [Transport Rule Criteria](https://go.microsoft.com/fwlink/p/?LinkId=320394) and [Transport Rule Actions](https://go.microsoft.com/fwlink/p/?LinkId=320395).</span></span> <br/>
> <span data-ttu-id="a760b-167"><sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。</span><span class="sxs-lookup"><span data-stu-id="a760b-167"><sup>2</sup> EOP auditing reports are a subset of Exchange Online auditing reports that exclude information about mailboxes.</span></span> <br/>
> <span data-ttu-id="a760b-168"><sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。</span><span class="sxs-lookup"><span data-stu-id="a760b-168"><sup>3</sup> DLP policy tips are not available for Exchange Enterprise CAL with Services customers.</span></span> <br/>
> <span data-ttu-id="a760b-169"><sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。</span><span class="sxs-lookup"><span data-stu-id="a760b-169"><sup>4</sup> Supported for on-premises customers who purchase the Azure Information Protection add-on and use Exchange Online Protection to route email through Exchange Online.</span></span> <span data-ttu-id="a760b-170">デスクトップ エクスペリエンスのために、Azure Information Protection アドオンに加えて、Office 365 ProPlus を購入する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a760b-170">For the desktop experience, in addition to the Azure Information Protection add-on, Office 365 ProPlus needs to be purchased.</span></span> <br/>
  

