---
title: GCC High および DoD
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/23/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: 米国国防総省、米国国防総省の管理下における非機密扱いの情報 (CUI) を保持または処理する請負業者、または国際武器取引規則 (ITAR) の対象となる、独自の進化し続ける要件に応じるため、Microsoft は GCC High および DoD 環境を提供いたします。これはボリューム ライセンスから利用でき、関心のある組織は環境を確立する前に適格性を確認する検証プロセスを完了します。試用版は、この時点では提供されません。
ms.openlocfilehash: 4fd893157eb12f470c78f8d8c88fa1ab6e5c1772
ms.sourcegitcommit: de65f864b9c82d5e163a2c59beb2aaec7bb3f5d5
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2018
ms.locfileid: "25719071"
---
# <a name="gcc-high-and-dod"></a>GCC High および DoD

米国国防総省、米国国防総省の管理下における非機密扱いの情報 (CUI) を保持または処理する請負業者、または国際武器取引規則 (ITAR) の対象となる、独自の進化し続ける要件に応じるため、Microsoft は GCC High および DoD 環境を提供いたします。これはボリューム ライセンスから利用でき、関心のある組織は環境を確立する前に適格性を確認する検証プロセスを完了します。試用版は、この時点では提供されません。 
  
詳細情報を確認したり、検証プロセスを開始したりするよう、アカウント チームや優先パートナーに働きかけてください。
  
## <a name="how-to-use-this-service-description-section"></a>このサービスの説明セクションの使用方法

Office 365 US Government のサービスの説明は、全般的な Office 365 のサービスの説明へのオーバーレイとして機能するよう設計されています。Office 365 Enterprise 製品と比較した独自のコミットメントと相違点を定義します。
  
## <a name="compliance"></a>準拠

GCC High および DoD は以下の認定資格に関する法令遵守の要件を満たします。 
  
- 米国国立標準技術研究所 (NIST) 臨時発行 800-53 に記載されるセキュリティ コントロールとコントロールの機能拡張を含む、Federal Risk and Authorization Management Program at a Moderate (FedRAMP Moderate) ベースライン。
    
- 影響レベル 5 (L5) までの情報に関する米国国防総省クラウド コンピューティング セキュリティ要件ガイド (SRG) に対するセキュリティ コントロールとコントロールの強化。
    
Office 365 の国防総省サブスクライバーは、DOD SRG L5 に適合する DOD の排他的な環境から提供されるサービスを受けられます。国防総省以外のサブスクライバーは、米国国防総省環境からの L5 と評価されたサービスを受けられますが、セグメンテーションは L4 を使用します。
  
## <a name="background-screening"></a>背景調査

Office 365 のスタッフには、GCC High および DoD 製品への永続的なアクセス権がありません。お客様のコンテンツへのアクセス権を付与する一時的なアクセス許可の昇格を要求するすべてのスタッフは、まず次の身元調査に合格する必要があります。
  
|||
|:-----|:-----|
|**Microsoft の担当者の選別と身元調査** <br/> |**説明** <br/> |
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
   
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>対応しているクラウド アーキテクチャに基づく機能のわずかな違い

GCC High および DoD 環境内の Office 365 サブスクリプションには、コアの Exchange Online、SharePoint Online、および Skype for Business 機能が含まれます。インフラストラクチャの認定資格は増加しており、市販の Office 365 オファリングと GCC High および DoD で提供されるものでも、機能に違いがあります。
  
### <a name="exchange-online"></a>Exchange Online

 **オンプレミス IP-PBX のための Exchange Online ユニファイド メッセージング サポート**: Exchange Online ユニファイド メッセージングでのオンプレミスの IP-PBX システムの統合サポートは、GCC High および DoD ではサポートされていません。 
  
### <a name="sharepoint-online"></a>SharePoint Online

 **ドキュメントの共有**: SharePoint Online と OneDrive for Business は、ユーザーとチームの間のシームレスな情報共有とコラボレーションを可能にします。ドキュメントの所有者は、Web インターフェイスや Outlook のモダンな添付ファイルを介して、他のユーザーにドキュメントへのアクセスを提供します。ドキュメントを共有するときには、アクセス許可を管理するための複数のオプションがあります。 
  
1. 自分のみ
    
2. 社内のユーザー全員
    
3. このリンクを持つユーザー全員
    
4. 特定のユーザー
    
GCC 高または DoD の環境でのビジネスがプライベートにしておくドキュメントを SharePoint Online と OneDrive を使用しているユーザー (最初にオプションで)、組織内のユーザーと共有 (2 番目のオプション)、ドキュメントへのリンクを持つ任意のユーザーと共有する (3 番目のオプション) とGCC 高および DoD の環境内のみで特定の人と共有 (オプション 4)。もちろん、これらのオプションを制限できますテナント レベルのアクセス コントロールも同様にします。
  
GCC 高テナントは、GCC の高い他のテナントとのみ共有できます。例えば：
  
- GCC 高テナント B. GCC 高テナント A と共有できます。
    
- GCC 高テナント A または B 以外の GCC テナント C と共有できます。
    
- 非 GCC 高テナント C. A または B の GCC の高いテナントが共有できません。
    
ユーザー プロファイルに接続されている GCC 高以外の電子メール アドレスはサポートされていませんまた、警告の電子メールを送信することはできません。などの社内ユーザー A は Gmail の電子メール アドレスを割り当てられている、Azure GCC 高テナントを同期し、ユーザー A は、ライブラリに移動し、変更の通知を作成します。Gmail アドレスには、警告は送信されません。
  
 **外部アプリケーションへのアクセス**: アドインのデータ ソースなど、外部アプリケーションへの接続は、GCC High および DoD でサポートされているシステムのセキュリティ境界内にあるソースに限定されます。 
  
 **Business Connectivity Services**の BCS の機能は、データ ソースは、クラウド サービスのセキュリティ境界内で到達可能な接続の場合、サポートされています。 
  
 **サンド ボックス ソリューション**: この機能は非推奨であり、利用できません。サンドボックス ソリューションはすべて、 [ SharePoint アドイン拡張モデル ]( https://msdn.microsoft.com/en-us/library/office/fp179930.aspx)に移行する必要があります。
  
### <a name="skype-for-business-online"></a>Skype for Business Online

 **PSTN の呼び出し&amp;PSTN 会議**- テレフォニー指向サービスは、PSTN の呼び出し、公衆交換電話網 (PSTN) を使用する必要性のため&amp;PSTN 会議サービスが現在利用できない GCC 高、DoD にします。 
  
### <a name="identity"></a>ID

フェデレーション認証モデルを使用した多要素認証では、PIV カードおよび CAC カードを使用できます。
  
### <a name="yammer"></a>Yammer

Yammer は GCC High および DoD 環境では利用できません。
  

