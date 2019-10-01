---
title: メッセージングのポリシーと準拠
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。
ms.openlocfilehash: af611b7124c85866bad5bec74f853d70f721e5ae
ms.sourcegitcommit: d6f315a056e0e356a9e37275d361e4195b97bff0
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/01/2019
ms.locfileid: "37334127"
---
# <a name="messaging-policy-and-compliance"></a><span data-ttu-id="b504a-103">メッセージングのポリシーと準拠</span><span class="sxs-lookup"><span data-stu-id="b504a-103">Messaging Policy and Compliance</span></span>

<span data-ttu-id="b504a-104">Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="b504a-104">Microsoft Exchange Online Protection (EOP) provides messaging policy and compliance features that can help you manage your email data.</span></span>

<span data-ttu-id="b504a-105">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="b504a-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="b504a-106">「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b504a-106">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>

## <a name="mail-flow-rules"></a><span data-ttu-id="b504a-107">メール フロー ルール</span><span class="sxs-lookup"><span data-stu-id="b504a-107">Mail flow rules</span></span>

<span data-ttu-id="b504a-108">メールフロールール (トランスポートルールとも呼ばれます) は、独自の会社固有のポリシーを電子メールに適用する柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="b504a-108">Mail flow rules (also known as transport rules) provide you with the flexibility to apply your own company-specific policies to email.</span></span> <span data-ttu-id="b504a-109">メールフロールールは柔軟な条件で構成されているため、条件、例外、および実行する操作を条件に基づいて定義できます。</span><span class="sxs-lookup"><span data-stu-id="b504a-109">Mail flow rules are made up of flexible criteria, which allow you to define conditions, exceptions, and actions to take based on the criteria.</span></span> <span data-ttu-id="b504a-110">詳細については、「 [Mail flow rules (transport rules) In Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b504a-110">For more information, see [Mail flow rules (transport rules) in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).</span></span>

## <a name="audit-logging"></a><span data-ttu-id="b504a-111">監査ログ</span><span class="sxs-lookup"><span data-stu-id="b504a-111">Audit logging</span></span>

<span data-ttu-id="b504a-112">監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。</span><span class="sxs-lookup"><span data-stu-id="b504a-112">Audit logging lets you track specific changes made by administrators to your organization.</span></span> <span data-ttu-id="b504a-113">これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="b504a-113">These reports help you meet regulatory, compliance, and litigation requirements.</span></span> <span data-ttu-id="b504a-114">詳細については、「[EOP の監査レポート](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b504a-114">For more information, see [Auditing reports in EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).</span></span>

## <a name="data-loss-prevention-dlp"></a><span data-ttu-id="b504a-115">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="b504a-115">Data loss prevention (DLP)</span></span>

<span data-ttu-id="b504a-p104">EOP スタンドアロンのお客様は利用できません。データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。DLP 機能を使用すると、業務の生産性に影響を及ぼすことなく機密データを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="b504a-p104">Not available to EOP standalone customers. Data loss prevention (DLP) helps you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature enables you to protect sensitive data without affecting worker productivity.</span></span>

<span data-ttu-id="b504a-120">EAC で DLP ポリシーを構成することにより、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="b504a-120">You can configure DLP policies in the EAC, which allows you to:</span></span>

- <span data-ttu-id="b504a-121">PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。</span><span class="sxs-lookup"><span data-stu-id="b504a-121">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>

- <span data-ttu-id="b504a-122">既存のメールフロールールの条件とアクションの全機能を使用して、新しいメールフロールールを追加します。</span><span class="sxs-lookup"><span data-stu-id="b504a-122">Use the full power of existing mail flow rule criteria and actions and add new mail flow rules.</span></span>

- <span data-ttu-id="b504a-123">DLP ポリシーを完全に実施する前にその効果をテストできます。</span><span class="sxs-lookup"><span data-stu-id="b504a-123">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>

- <span data-ttu-id="b504a-124">独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。</span><span class="sxs-lookup"><span data-stu-id="b504a-124">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>

- <span data-ttu-id="b504a-125">メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。</span><span class="sxs-lookup"><span data-stu-id="b504a-125">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which the service takes action.</span></span>

- <span data-ttu-id="b504a-126">ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。</span><span class="sxs-lookup"><span data-stu-id="b504a-126">Detect sensitive form data by using Document Fingerprinting.</span></span> <span data-ttu-id="b504a-127">ドキュメントフィンガープリンティングを使用すると、メールフロールールと DLP ポリシーを定義するために使用できるテキストベースのフォームに基づいて、カスタムの機密情報の種類を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="b504a-127">Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define mail flow rules and DLP policies.</span></span>

- <span data-ttu-id="b504a-128">ポリシー ヒントを追加して、Outlook 2013、Outlook Web App、およびデバイス用 OWA の各ユーザーに通知メッセージを表示し、データの損失を削減できます。また、誤検知の報告を許可することによりポリシーの有効性を改善することもできます。</span><span class="sxs-lookup"><span data-stu-id="b504a-128">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span>

- <span data-ttu-id="b504a-129">インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="b504a-129">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>

> [!NOTE]
> <span data-ttu-id="b504a-p106">DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。</span><span class="sxs-lookup"><span data-stu-id="b504a-p106">DLP policies are applied only to mail that passes in or out of the organization. Intra-organizational (internal) mail does not have DLP policies applied unless you run Exchange Server 2013 with DLP on-premises. This also applies to DLP policy tips, which inform users about potential policy violations before sensitive data is mistakenly sent to unauthorized recipients.</span></span>

<span data-ttu-id="b504a-133">DLP の詳細については、「 [Exchange Online でのデータ損失防止](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b504a-133">To learn more about DLP, see [Data loss prevention in Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).</span></span>

## <a name="office-365-message-encryption"></a><span data-ttu-id="b504a-134">はい</span><span class="sxs-lookup"><span data-stu-id="b504a-134">Office 365 Message Encryption</span></span>

<span data-ttu-id="b504a-p107">Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。Exchange Online の Office 365 Message Encryption の詳細については、「Exchange Online サービスの説明」の「[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b504a-p107">Office 365 Message Encryption, a part of Azure Information Protection, is an online service that allows email users to send encrypted email messages to anyone. On-premises customers can access Office 365 Message Encryption by purchasing Azure Information Protection and using Exchange Online Protection to set up mail flow through Exchange Online. To learn more about Office 365 Message Encryption in Exchange Online, see [Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in the Exchange Online Service Description.</span></span>

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a><span data-ttu-id="b504a-138">EOP オプション間のメッセージング ポリシーとコンプライアンス機能</span><span class="sxs-lookup"><span data-stu-id="b504a-138">Messaging policy and compliance features across EOP options</span></span>

|<span data-ttu-id="b504a-139">**機能**</span><span class="sxs-lookup"><span data-stu-id="b504a-139">**Feature**</span></span>|<span data-ttu-id="b504a-140">**EOP スタンドアロン**</span><span class="sxs-lookup"><span data-stu-id="b504a-140">**EOP standalone**</span></span>|<span data-ttu-id="b504a-141">**Exchange Online の<br/> EOP 機能**</span><span class="sxs-lookup"><span data-stu-id="b504a-141">**EOP features in <br/> Exchange Online**</span></span>|<span data-ttu-id="b504a-142">**Exchange Enterprise <br/> CAL とサービス**</span><span class="sxs-lookup"><span data-stu-id="b504a-142">**Exchange Enterprise <br/> CAL with Services**</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="b504a-143">メール フロー ルール</span><span class="sxs-lookup"><span data-stu-id="b504a-143">Mail flow rules</span></span>|<span data-ttu-id="b504a-144">はい<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-144">Yes<sup>1</sup></span></span>|<span data-ttu-id="b504a-145">はい<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-145">Yes<sup>1</sup></span></span>|<span data-ttu-id="b504a-146">はい<sup>1、3</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-146">Yes<sup>1, 3</sup></span></span>|
|<span data-ttu-id="b504a-147">監査ログ</span><span class="sxs-lookup"><span data-stu-id="b504a-147">Audit logging</span></span>|<span data-ttu-id="b504a-148">はい<sup>2</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-148">Yes<sup>2</sup></span></span>|<span data-ttu-id="b504a-149">はい</span><span class="sxs-lookup"><span data-stu-id="b504a-149">Yes</span></span>|<span data-ttu-id="b504a-150">はい</span><span class="sxs-lookup"><span data-stu-id="b504a-150">Yes</span></span>|
|<span data-ttu-id="b504a-151">データ損失防止 (DLP)</span><span class="sxs-lookup"><span data-stu-id="b504a-151">Data Loss Prevention (DLP)</span></span>|<span data-ttu-id="b504a-152">いいえ</span><span class="sxs-lookup"><span data-stu-id="b504a-152">No</span></span>|<span data-ttu-id="b504a-153">はい</span><span class="sxs-lookup"><span data-stu-id="b504a-153">Yes</span></span>|<span data-ttu-id="b504a-154">はい<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-154">Yes<sup>3</sup></span></span>|
|<span data-ttu-id="b504a-155">Office 365 Message Encryption</span><span class="sxs-lookup"><span data-stu-id="b504a-155">Office 365 Message Encryption</span></span>|<span data-ttu-id="b504a-156">はい<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-156">Yes<sup>4</sup></span></span>|<span data-ttu-id="b504a-157">はい</span><span class="sxs-lookup"><span data-stu-id="b504a-157">Yes</span></span>|<span data-ttu-id="b504a-158">はい<sup>4</sup></span><span class="sxs-lookup"><span data-stu-id="b504a-158">Yes<sup>4</sup></span></span>|

> [!NOTE]
> <span data-ttu-id="b504a-159"><sup>1</sup> EOP と Exchange Online では、使用可能なメールフロールールの条件、例外、およびアクションが若干異なります。</span><span class="sxs-lookup"><span data-stu-id="b504a-159"><sup>1</sup> The available mail flow rule conditions, exceptions, and actions differ slightly between EOP and Exchange Online.</span></span> <span data-ttu-id="b504a-160">これらの相違点については、「exchange [online のメールフロールールの条件と例外 (述語)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) 」および「 [exchange Online でのメールフロールールの処理](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)」で説明されています。</span><span class="sxs-lookup"><span data-stu-id="b504a-160">These differences are noted in [Mail flow rule conditions and exceptions (predicates) in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) and [Mail flow rule actions in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions).</span></span> <br/>
> <span data-ttu-id="b504a-161"><sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。</span><span class="sxs-lookup"><span data-stu-id="b504a-161"><sup>2</sup> EOP auditing reports are a subset of Exchange Online auditing reports that exclude information about mailboxes.</span></span> <br/>
> <span data-ttu-id="b504a-162"><sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。</span><span class="sxs-lookup"><span data-stu-id="b504a-162"><sup>3</sup> DLP policy tips are not available for Exchange Enterprise CAL with Services customers.</span></span> <br/>
> <span data-ttu-id="b504a-163"><sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。</span><span class="sxs-lookup"><span data-stu-id="b504a-163"><sup>4</sup> Supported for on-premises customers who purchase the Azure Information Protection add-on and use Exchange Online Protection to route email through Exchange Online.</span></span> <span data-ttu-id="b504a-164">デスクトップ エクスペリエンスのために、Azure Information Protection アドオンに加えて、Office 365 ProPlus を購入する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b504a-164">For the desktop experience, in addition to the Azure Information Protection add-on, Office 365 ProPlus needs to be purchased.</span></span> <br/>
