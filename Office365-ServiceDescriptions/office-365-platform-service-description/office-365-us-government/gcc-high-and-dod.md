---
title: Office 365 GCCと DoD
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 高環境と DoD 環境の固有のコミットメントと相違点について、Office 365 GCC商用環境と比較Office 365説明します。
ms.openlocfilehash: 5446d5d1e6e10649a75f001c92f0d970e2fae842
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653459"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCCと DoD

米国国防総省、米国国防総省の管理下における非機密扱いの情報 (CUI) を保持または処理する請負業者、または国際武器取引規則 (ITAR) の対象となる、独自の進化し続ける要件に応じるため、Microsoft は GCC High および DoD 環境を提供いたします。これはボリューム ライセンスから利用でき、関心のある組織は環境を確立する前に適格性を確認する検証プロセスを完了します。試用版は、この時点では提供されません。 
  
アカウント チームまたは優先パートナーに参加して、詳細を確認したり、検証プロセスを開始したりします。 購入方法の詳細については、「Microsoft 365 [- 購入方法」を参照してください](./microsoft-365-government-how-to-buy.md)。
  
## <a name="how-to-use-this-service-description"></a>このサービスの説明を使用する方法

米国Office 365サービスの説明は、サービスの一般的な説明へのオーバーレイOffice 365設計されています。 企業向けサービスに対する固有のコミットメントと相違点Office 365定義します。
  
## <a name="compliance"></a>コンプライアンス

GCC High および DoD は以下の認定資格に関する法令遵守の要件を満たします。 
  
- FedRAMP High の連邦リスクと承認管理プログラム(米国国立標準技術研究所(NIST) Special Publication 800-53 に記載されているセキュリティ制御と制御の強化を含む。
    
- 影響レベル 5 (L5) までの情報に関する米国国防総省クラウド コンピューティング セキュリティ要件ガイド (SRG) に対するセキュリティ コントロールとコントロールの強化。
    
Office 365 の国防総省サブスクライバーは、DOD SRG L5 に適合する DOD の排他的な環境から提供されるサービスを受けられます。 国防省以外のサブスクライバーは、L5 で評価されるが、L4 セグメンテーションを使用する米国政府防衛環境からサービスを受け取ります。
  
## <a name="background-screening"></a>背景調査

Office 365 のスタッフには、GCC High および DoD 製品への永続的なアクセス権がありません。 顧客コンテンツへのアクセスを許可する一時的なアクセス許可の昇格を要求するスタッフは、まず次のバックグラウンド チェックに合格している必要があります。<br><br>
  
| Microsoft の担当者によるスクリーニングとバックグラウンド チェック<sup>1</sup> | 説明 |
|:-----|:-----|
|アメリカ国籍  <br/> |アメリカ国籍の確認  <br/> |
|職歴チェック  <br/> |過去 7 年間の職歴の確認  <br/> |
|学歴の確認  <br/> |最終学歴の検証  <br/> |
|社会保障番号 (SSN) の検索  <br/> |提供された SSN が有効であるかどうかの確認  <br/> |
|犯罪歴のチェック  <br/> |州、郡、地域レベル、さらに連邦レベルにおける、過去 7 年間の重犯罪および軽犯罪の記録のチェック  <br/> |
|米国財務省外国資産管理局 (OFAC) のリスト  <br/> |米国人が貿易や金融取引の相手とすることを禁じられているグループが記載された財務省のリストの照合  <br/> |
|米国産業安全保障局 (BIS) のリスト  <br/> |輸出活動が禁じられた個人または事業体が記載された米国商務省のリストの照合  <br/> |
|国防貿易管理局 (DDTC) の禁止対象者リスト  <br/> |軍需産業に関連する輸出活動が禁じられた個人または事業体が記載された米国国務省のリストの照合  <br/> |
|指紋チェック  <br/> |FBI データベースに照らして行う指紋の身元調査  <br/> |
|米国国防総省 IT-2  <br/> |お客様データへの管理者特権のアクセス許可、または国防総省 SRG L5 サービス機能への管理者特権アクセスを要求しているスタッフは、OPM Tier 3 調査に基づく国防総省 IT-2 の判定に合格する必要があります  <br/> |

<sup>1</sup>米国または DOD クラウドでホストされている顧客コンテンツに一時的または永続的にアクセスできるOffice 365担当者GCC-High適用されます。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>対応しているクラウド アーキテクチャに基づく機能のわずかな違い

GCCおよび DoD 環境のサブスクリプションには、コア Exchange Online、SharePoint、Skype for Businessがあります。 インフラストラクチャの認定資格は増加しており、市販の Office 365 オファリングと GCC High および DoD で提供されるものでも、機能に違いがあります。
  
### <a name="exchange-online"></a>Exchange Online

 **オンプレミス IP-PBX のための Exchange Online ユニファイド メッセージング サポート**: Exchange Online ユニファイド メッセージングでのオンプレミスの IP-PBX システムの統合サポートは、GCC High および DoD ではサポートされていません。 
  
### <a name="file-sharing"></a>ファイル共有

ユーザーには、ファイルとフォルダーを共有するための複数のSharePointおよびOneDrive。 すべてのオプションは、GCC DoD 環境で使用できます。 これらのオプションの管理の詳細については、「共有設定の管理 [」を参照してください](/sharepoint/turn-external-sharing-on-or-off)。 ユーザーは GCC-High-High の他の組織GCC共有できます。 さらに、NON-GCCユーザー プロファイルに添付された高電子メール アドレスはサポートされていません。また、警告メールの送信は許可されません。 たとえば、オンプレミスのユーザー A には Gmail のメール アドレスが割り当てられた後、Azure GCC High 組織に同期されます。 ユーザー A はライブラリに移動し、変更に関するアラートを作成します。 アラートは Gmail アドレスに送信されません。

> [!NOTE]
> 現在、GCC-Highユーザーは、高レベル以外の組織のユーザーとGCCできません。

[ファイル要求は](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af)、ユーザーが使用Office 365 Government。

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN Calling &amp; PSTN Conferencing** - Due to the requirement to use the Public Switched Telephone Network (PSTN) for telephony-oriented services, PSTN Calling &amp; PSTN Conferencing services are currently not available in GCC High and DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**電話システム電話会議 (** ダイレクト ルーティング経由) - 電話システム High 環境および DoD 環境の GCC および電話会議は、直接ルーティングを介して配信されています。 詳細については、次のサービス レベルのドキュメントを参照してください。

- [電話システムルーティングを介して行う](/microsoftteams/here-s-what-you-get-with-phone-system)
- [GCC High および DoD のダイレクト ルーティングを使用する電話会議](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>ID

フェデレーション認証モデルを使用した多要素認証では、PIV カードおよび CAC カードを使用できます。
  
### <a name="yammer"></a>Yammer

Yammerは、High 環境と DoD 環境GCC使用できません。
  
## <a name="customer-support"></a>顧客サポート

Microsoft は、Office 365 GCC High/DOD を使用する場合、少なくともサポート エージェントがそのようなデータを表示またはアクセスするための承認を確認するまで、サポート インシデントの一環として、管理、機密情報、または機密情報をカスタマー サポート担当者と共有してはならないことを通知します。

Microsoft は、お客様のプライバシーの保護に取り組[む。](https://privacy.microsoft.com/privacystatement) ただし、Office 365 GCC High/DoD サポートはサービス認定の境界には含まれていないので、FedRAMP、DOD SRG、ITAR、IRS 1075、または CJIS データ処理コンプライアンス保証は提供しません。