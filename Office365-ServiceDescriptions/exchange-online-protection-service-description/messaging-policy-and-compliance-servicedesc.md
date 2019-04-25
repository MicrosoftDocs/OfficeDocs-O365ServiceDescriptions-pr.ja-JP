---
title: メッセージングのポリシーと準拠
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。
ms.openlocfilehash: a37ad3c1bcecb73f7c903b553bdcb43935dc9ed7
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246123"
---
# <a name="messaging-policy-and-compliance"></a>メッセージングのポリシーと準拠

Microsoft Exchange Online Protection (EOP) は、電子メールデータの管理に役立つメッセージングポリシーとコンプライアンス機能を提供します。
  
すべての EOP 機能に関する情報をお探しですか? 「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。
  
## <a name="transport-rules"></a>トランスポート ルール
<a name="BKMK_transportrules"> </a>

トランスポート ルールは、電子メールに会社固有のポリシーを適用できる柔軟性をもたらします。トランスポート ルールは条件および例外を定義できる柔軟性のある条件と、その条件に基づいて実行される処理で構成されます。EOP のトランスポート ルールの詳細については、「[トランスポート ルール](https://go.microsoft.com/fwlink/p/?LinkId=320399)」を参照してください。
  
## <a name="audit-logging"></a>監査ログ
<a name="BKMK_auditlogging"> </a>

監査ログを使用すると、組織に対して管理者が行った変更を追跡できます。これらのレポートは、法規制、法令遵守、訴訟の要件を満たすために役立ちます。詳細については、「[EOP の監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=314258)」を参照してください。
  
## <a name="data-loss-prevention-dlp"></a>データ損失防止 (DLP)
<a name="BKMK_datalossprevention"> </a>

EOP スタンドアロンのお客様は利用できません。データ損失防止 (DLP) では、詳細なコンテンツ分析によって、組織内の機密情報を特定、監視、保護できます。ビジネスクリティカルな電子メールには保護が必要な機密データが含まれているため、企業のメッセージ システムでの DLP の重要性がますます高まっています。DLP 機能を使用すると、業務の生産性に影響を及ぼすことなく機密データを保護することができます。
  
EAC で DLP ポリシーを構成することにより、次のことが可能になります。
  
- PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。
    
- 既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。
    
- DLP ポリシーを完全に実施する前にその効果をテストできます。
    
- 独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。
    
- メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、サービスで処理を実行する信頼レベルを調整できます。
    
- ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。ドキュメントのフィンガープリント機能を使用すると、テキスト ベースのフォームを基に、機密情報のカスタム タイプを手早く作成し、トランスポート ルールと DLP ポリシーを定義できます。
    
- ポリシー ヒントを追加して、Outlook 2013、Outlook Web App、およびデバイス用 OWA の各ユーザーに通知メッセージを表示し、データの損失を削減できます。また、誤検知の報告を許可することによりポリシーの有効性を改善することもできます。
    
- インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。
    
> [!NOTE]
> DLP ポリシーは、組織と外部との間で送受信されるメールにのみ適用されます。社内で Exchange Server 2013 と DLP を実行していない場合、組織内 (内部) メールに DLP ポリシーは適用されません。このことは、許可されていない受信者に機密データを誤って送信する前に、潜在的なポリシー違反をユーザーに通知する DLP ポリシー ヒントにも当てはまります。 
  
DLP の詳細については、「[データ損失防止](https://go.microsoft.com/fwlink/p/?LinkId=320398)」を参照してください。
  
## <a name="office-365-message-encryption"></a>はい
<a name="BKMK_OME_in_EOP"> </a>

Office 365 Message Encryption は、Azure Information Protection の一部で、電子メールのユーザーが暗号化された電子メール メッセージを任意のユーザーに送信できるようにするオンライン サービスです。社内展開の Exchange カスタマーが Office 365 Message Encryption を利用する場合は、Azure Information Protection を購入し、Exchange Online Protection を使って Exchange Online を介したメール フローをセットアップする必要があります。Exchange Online の Office 365 Message Encryption の詳細については、「Exchange Online サービスの説明」の「[Office 365 Message Encryption](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption)」を参照してください。 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP オプション間のメッセージング ポリシーとコンプライアンス機能
<a name="BKMK_OME_in_EOP"> </a>

|**機能**|**EOP スタンドアロン**|**Exchange Online の EOP 機能**|**Exchange Enterprise CAL とサービス**|
|:-----|:-----|:-----|:-----|
|トランスポート ルール  <br/> |はい<sup>1</sup> <br/> |はい<sup>1</sup> <br/> |はい  <br/> |
|監査ログ  <br/> |はい<sup>2</sup> <br/> |はい  <br/> |はい  <br/> |
|データ損失防止 (DLP)  <br/> |いいえ  <br/> |はい  <br/> |はい<sup>3</sup> <br/> |
|Office 365 Message Encryption  <br/> |はい<sup>4</sup> <br/> |はい  <br/> |はい<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 使用可能な条件とアクションは、EOP と Exchange Online で異なります。 EOP で使用可能な条件とアクションのリストについては、「 [トランスポート ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320392)」と「[トランスポート ルールのアクション](https://go.microsoft.com/fwlink/p/?LinkId=320393)」を参照してください。 Exchange Online で使用可能な条件とアクションのリストについては、「[メール フロー ルールの条件 (述語)](https://go.microsoft.com/fwlink/p/?LinkId=320394)」と「[メール フロー ルールの処理](https://go.microsoft.com/fwlink/p/?LinkId=320395)」を参照してください。 <br/>
> <sup>2</sup> EOP 監査レポートは、メールボックスに関する情報を除いた Exchange Online 監査レポートの一部です。 <br/>
> <sup>3</sup> サービス付き Exchange Enterprise CAL のお客様は、DLP ポリシー ヒントを利用できません。 <br/>
> <sup>4</sup>Azure Information Protection アドオンを購入し、Exchange Online Protection を使用して Exchange Online 経由で電子メールをルーティングしているオンプレミスのお客様のためにサポートされています。 デスクトップ エクスペリエンスのために、Azure Information Protection アドオンに加えて、Office 365 ProPlus を購入する必要があります。 <br/>
  

