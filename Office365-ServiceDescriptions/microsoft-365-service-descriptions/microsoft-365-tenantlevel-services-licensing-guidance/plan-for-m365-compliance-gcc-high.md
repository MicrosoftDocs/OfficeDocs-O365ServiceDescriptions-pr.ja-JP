---
title: Microsoft 365 コンプライアンスを計画する-GCC 高
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: このガイダンスは、米国連邦政府機関のエンティティで Office 365 の展開を推進する IT 担当者、または Microsoft 365 Government – GCC 高を使用することが適切な政府の規制と要件に従うデータを処理する IT 担当者を対象としています。これらの要件を満たすため。
ms.openlocfilehash: 4ddc98b4784741e62d0cdabefb9d36d7b11ac560
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890506"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Microsoft 365 コンプライアンスの計画-GCC 高

このガイダンスは、米国連邦政府機関のエンティティで Office 365 の展開を推進する IT 担当者、または Microsoft 365 Government – GCC 高を使用することが適切な政府の規制と要件に従うデータを処理する IT 担当者を対象としています。これらの要件を満たすため。

> [!NOTE]
>組織が既に Microsoft 365 Government を使用していて、プログラムに適用されていて、かつに対して適用されている場合は、手順1と手順2を省略して手順3に直接進むことができます。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>手順 1.  組織に Microsoft 365 Government が必要かどうかを判断します。 GCC 高で、資格の要件を満たしているかどうかを判断する

Microsoft 365 Government-GCC 高環境は、クラウドサービスの米国政府の要件に準拠しています。 Office 365 の機能を楽しんでいることに加えて、組織は、Microsoft 365 Government – GCC High に固有の次の機能を活用しています。

- 組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365 Government –米国公的機関のお客様に必要な証明書と認定に準拠した GCC。

Microsoft 365 Government の詳細については、「特典の要件を含む[Office 365 政府](https://products.office.com/government/compare-office-365-government-plans)機関向けの米国政府のお客様向けの英語 (米国)」を参照してください。

「 [Office 365 US Government サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)」では、プラットフォームの利点について説明します。これは、米国内での会議のコンプライアンス要件を中心としています。

> [!TIP]
> サービスの説明の情報の表を Excel ブックに転送して、組織の  **y/n に関連**し、 **組織のニーズを満たす**2 つの列を追加することをお勧めします。 その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。

**判断ポイント**:<br/>
- *Microsoft 365 Government – GCC-高が組織に適しているかどうかを決定します。*
- *組織が資格要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government-GCC High は米国でのみ利用可能です。 米国以外の政府機関のお客様は、多くの[Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>手順 2.  Microsoft 365 Government に適用-GCC-高

このサービスが組織に適していると判断した場合は、[このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>手順 3.  Microsoft 365 Government – GCC-高既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。

**判断ポイント**:*既定の Microsoft 365 Government-GCC-高セキュリティ設定を変更するかどうかを決定します。解決するには、変更による影響を最初に理解する必要があります。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-high"></a>手順 4.  Microsoft 365 Government-GCC-高 * * で、現在どの機能が使用できないか、または無効になっているかを理解する

政府機関のお客様の要件を満たすために、Microsoft 365 Government と、GCC-高およびエンタープライズプランにはいくつかの違いがあります。 利用可能な機能を確認するには、次の表を参照してください。

|                                         | 機能                                         | GCC High 状態        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護 & ガバナンス** | アーカイブ                                       | Available              |
|                                         | 手動によるラベルとポリシー                      | Available              |
|                                         | ラベルの自動適用                      | エンジニアリングバックログの場合 |
|                                         | 機密データ型に基づくラベル            | エンジニアリングバックログの場合 |
|                                         | クエリに基づくラベルと関連付けられたポリシー | エンジニアリングバックログの場合 |
|                                         | ファイル計画                                       | エンジニアリングバックログの場合 |
|                                         | 推奨されるポリシー                            | エンジニアリングバックログの場合 |
|                                         | スマートインポートフィルター                            | エンジニアリングバックログの場合 |
|                                         | イベント ベースの保持                           | エンジニアリングバックログの場合 |
|                                         | 廃棄のレビュー                              | エンジニアリングバックログの場合 |
|                                         | 情報障壁                            | Available              |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)  | Available              |
|                                         | Teams チャットおよびチャネル会話の DLP    | エンジニアリングバックログの場合 |
| **Insider リスク管理**             | 高度なメッセージ暗号化                     | Available              |
|                                         | 通信のコンプライアンス                        | エンジニアリングバックログの場合 |
|                                         | 顧客ロックボックス                                | Available              |
|                                         | カスタマー キー                                    | Available              |
|                                         | 特権アクセスの管理                    | エンジニアリングバックログの場合 |
| **& 応答の検出**                  | インプレースの予約                            | Available              |
|                                         | ケース管理                                 | Available              |
|                                         | 検索                                          | Available              |
|                                         | エクスポート                                          | Available              |
|                                         | RMS 復号化                                  | Available              |
|                                         | ネイティブエクスポート                                   | Available              |
|                                         | 高度な処理                             | Available              |
|                                         | 電子メールスレッド                                 | エンジニアリングバックログの場合 |
|                                         | ほぼ重複した識別                   | エンジニアリングバックログの場合 |
|                                         | テーマ                                          | エンジニアリングバックログの場合 |
|                                         | 予測コーディング                               | エンジニアリングバックログの場合 |
|                                         | 読み込みファイルを使用したエクスポートの処理                 | エンジニアリングバックログの場合 |
|                                         | タグ                                         | エンジニアリングバックログの場合 |
|                                         | 表示者                                         | エンジニアリングバックログの場合 |
|                                         | Redactions                                      | エンジニアリングバックログの場合 |
|                                         | フィルター                                       | エンジニアリングバックログの場合 |
|                                         | 保管担当者からワークロードへのマッピング                   | エンジニアリングバックログの場合 |
|                                         | 保管担当者通信                        | エンジニアリングバックログの場合 |
|                                         | チェックセット                                     | エンジニアリングバックログの場合 |
|                                         | レビューと注釈                             | エンジニアリングバックログの場合 |
|                                         | Office 以外の365の取り込み                        | エンジニアリングバックログの場合 |
|                                         | 検索用語レポート                              | エンジニアリングバックログの場合 |

**判断ポイント**:*コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
