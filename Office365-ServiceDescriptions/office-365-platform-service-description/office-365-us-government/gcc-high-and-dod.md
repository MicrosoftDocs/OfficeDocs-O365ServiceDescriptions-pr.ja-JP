---
title: Office 365 GCC High および DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Office 365 コマーシャル環境と比較した Office 365 GCC High および DoD 環境の固有のコミットメントと相違点について説明します。
ms.openlocfilehash: 388e7c3a37e88233982cf12a73e22622a61d1cb8
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131981"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High および DoD

To meet the unique and evolving requirements of the United States Department of Defense, as well as contractors holding or processing DoD controlled unclassified information (CUI) or subject to International Traffic in Arms Regulations (ITAR), Microsoft offers GCC High and DoD environments. Available through Volume Licensing, interested organizations go through a validation process to ensure eligibility before an environment is established. Trials are not available at this time. 
  
詳細情報を確認したり、検証プロセスを開始したりするよう、アカウント チームや優先パートナーに働きかけてください。 購入方法の詳細については、「 [Microsoft 365 Government-購入方法](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)」を参照してください。
  
## <a name="how-to-use-this-service-description-section"></a>このサービスの説明セクションの使用方法

Office 365 US Government サービスの説明は、一般的な Office 365 サービスの説明へのオーバーレイとして機能するように設計されています。 Office 365 Enterprise 製品と比較した独自のコミットメントと相違点を定義します。
  
## <a name="compliance"></a>コンプライアンス

GCC High および DoD は以下の認定資格に関する法令遵守の要件を満たします。 
  
- FedRAMP の連邦リスクおよび承認管理プログラム。これらのセキュリティ制御や、米国標準技術局 (NIST) の特別な文書800-53 に記載されている機能拡張を含みます。
    
- 影響レベル 5 (L5) までの情報に関する米国国防総省クラウド コンピューティング セキュリティ要件ガイド (SRG) に対するセキュリティ コントロールとコントロールの強化。
    
Department of Defense subscribers to Office 365 will receive services provided from the DOD exclusive environment that meets DOD SRG L5. Non-Department of Defense subscribers will receive services from the US Government Defense environment which is assessed at L5, but uses L4 segmentation.
  
## <a name="background-screening"></a>背景調査

Office 365 staff do not have standing access to GCC High and DoD production. Any staff who request temporary permission elevation which would grant access to customer content must first have passed the following background checks.
  
|||
|:-----|:-----|
|**Microsoft の人事審査と背景のチェック**<sup>1</sup> <br/> |**説明** <br/> |
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

<sup>1</sup>は、OFFICE 365 US GCC-高または DOD クラウドでホストされている顧客のコンテンツに一時的なアクセス権または永続的にアクセスできる人員にのみ適用されます。
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>対応しているクラウド アーキテクチャに基づく機能のわずかな違い

GCC High および DoD 環境のサブスクリプションには、Exchange Online、SharePoint、Skype for business のコア機能が含まれています。 インフラストラクチャの認定資格は増加しており、市販の Office 365 オファリングと GCC High および DoD で提供されるものでも、機能に違いがあります。
  
### <a name="exchange-online"></a>Exchange Online

 **オンプレミス IP-PBX のための Exchange Online ユニファイド メッセージング サポート**: Exchange Online ユニファイド メッセージングでのオンプレミスの IP-PBX システムの統合サポートは、GCC High および DoD ではサポートされていません。 
  
### <a name="file-sharing"></a>ファイル共有

ユーザーには、SharePoint と OneDrive でファイルやフォルダーを共有するための複数のオプションがあります。 すべてのオプションは、GCC High および DoD 環境で利用できます。 これらのオプションを管理する方法については、「[共有設定を管理](/sharepoint/turn-external-sharing-on-or-off)する」を参照してください。 ユーザーが [特定の人] オプションを使用して共有し、組織外のユーザーを選択すると、通常、SharePoint は電子メールで検証コードを送信します。 受信者は、共有アイテムにアクセスするためのコードを入力する必要があります。 これは、GCC 高の組織のユーザーが GCC 以外の組織のユーザーと共有している場合や、その逆の場合に当てはまります。 (外部共有機能の詳細については、「[ユーザーが共有する](/sharepoint/external-sharing-overview#what-happens-when-users-share)」を参照してください)。ただし、ある GCC レベルの組織のユーザーが別の GCC の組織のユーザーと共有している場合、Azure AD の受信者に対してゲストアカウントが作成され、ユーザー名とパスワードでサインインします。 

[ファイル要求](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af)は、Office 365 Government では使用できません。

また、ユーザープロファイルに添付された非 GCC の電子メールアドレスはサポートされていないため、通知の電子メールを送信することはできません。 たとえば、オンプレミスユーザー A には Gmail 電子メールアドレスが割り当てられ、Azure GCC 高組織と同期されます。 ユーザー A がライブラリに移動し、変更について通知を作成します。 通知は Gmail アドレスに送信されません。
  

### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN Calling &amp; PSTN Conferencing** - Due to the requirement to use the Public Switched Telephone Network (PSTN) for telephony-oriented services, PSTN Calling &amp; PSTN Conferencing services are currently not available in GCC High and DoD.

### <a name="microsoft-teams"></a>Microsoft Teams

**電話システムと電話会議 (直接ルーティング経由)**: スマートフォンシステムと電話会議 (GCC High および DoD 環境) は直接ルーティングによって配信されています。 詳細については、以下のサービスレベルのドキュメントを参照してください。

- [直接ルーティング経由の電話システム](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [GCC High および DoD のダイレクト ルーティングを使用する電話会議](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>ID

フェデレーション認証モデルを使用した多要素認証では、PIV カードおよび CAC カードを使用できます。
  
### <a name="yammer"></a>Yammer

Yammer Enterprise は、GCC High および DoD 環境では使用できません。
  
## <a name="customer-support"></a>顧客サポート

Office 365 GCC 高/DOD を使用している場合は、サポートインシデントの一部として、制御された機密情報や機密情報をサポートインシデントの一部として共有しないようにしてください。少なくとも、そのようなデータを表示またはアクセスするためのサポートエージェントの承認を確認するまで。

Microsoft は、お客様の[プライバシー](https://privacy.microsoft.com/privacystatement)の保護に努めています。 ただし、Office 365 GCC High/DoD サポートは、サービスの認定境界には含まれておらず、FedRAMP、DOD SRG、ITAR、IRS 1075、または CJIS データ処理コンプライアンスの保証は提供されません。
