---
title: Microsoft 365 コンプライアンスの計画 - DoD 展開
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、米国連邦政府機関のエンティティに Office 365 の展開を推進する IT 担当者、または政府の規制および要件を満たすデータを処理するその他のエンティティに対して使用されています。これは、Microsoft 365 Government – DoD を使用してこれらの要件を満たすことが適切な場合です。
ms.openlocfilehash: 5518a0332d598a25a434c817ce04eefc6069b62d
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388083"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 コンプライアンスの計画 - DoD 展開

このガイダンスは、米国連邦政府機関のエンティティに Office 365 の展開を推進する IT 担当者、または政府の規制および要件を満たすデータを処理するその他のエンティティに対して使用されています。これは、Microsoft 365 Government – DoD を使用してこれらの要件を満たすことが適切な場合です。

> [!NOTE]
> 組織が既に Microsoft 365 Government DoD の資格要件を満たしており、プログラムに適用されている場合は、手順1と手順2を省略して手順3に直接進むことができます。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>手順 1. お客様の組織で Microsoft 365 Government が必要かどうかを判断し、資格要件を満たすかどうかを判断する

Microsoft 365 Government-DoD 環境は、クラウドサービスの米国政府の要件に準拠しています。

Office 365 の機能を楽しんだだけでなく、組織は Microsoft 365 Government – DoD に固有の次の機能を活用しています。

- 組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365 Government は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

米国政府機関のお客様を対象とした Microsoft 365 Government-DoD オファーリングの詳細については、「特典要件」を含む[Office 365 政府機関プラン](https://products.office.com/government/compare-office-365-government-plans)を参照してください。

「 [Office 365 US Government サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)」では、プラットフォームの利点について説明します。これは、米国内での会議のコンプライアンス要件を中心としています。

> [!TIP]
> サービスの説明の情報の表を Excel ブックに転送して、**組織の y/n に関連**し、**組織のニーズを満たす**2 つの列を追加することをお勧めします。 その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。

**判断ポイント**:<br/>
- *Microsoft 365 Government が組織に適しているかどうかを決定します。*
- *組織が資格要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government は米国でのみご利用いただけます。 米国以外の政府機関のお客様は、多くの[Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>手順 2。 Microsoft 365 Government-DoD の適用

このサービスが組織に適していると判断した場合は、[このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>手順 3. Microsoft 365 Government-DoD 既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。

**判断ポイント**:*既定の Microsoft 365 Government セキュリティ設定を変更するかどうかを決定し、最初に変更が加えられた場合の影響を理解するようにします。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>手順 4. Microsoft 365 Government – DoD<sup>1</sup>で現在利用できない機能、または既定で無効になっている機能について理解する

政府機関のお客様の要件を満たすために、Microsoft 365 Government とエンタープライズのプランにはいくつかの違いがあります。 利用可能な機能を確認するには、次の表を参照してください。


|         |機能  |DoD 状態  |
|---------|---------|---------|
|**情報保護 & ガバナンス** |アーカイブ                                       |  Available             |
|                                        |手動によるラベルとポリシー<sup>2</sup>          |  Available             |
|                                        |ラベルの自動適用                      | エンジニアリングバックログの場合 |
|                                        |機密データ型に基づくラベル            | エンジニアリングバックログの場合 |
|                                        |クエリに基づくラベルと関連付けられたポリシー | エンジニアリングバックログの場合 |
|                                        |ファイル計画                                       | エンジニアリングバックログの場合 |
|                                        |推奨されるポリシー                            | エンジニアリングバックログの場合 |
|                                        |スマートインポートフィルター                            | エンジニアリングバックログの場合 |  
|                                        |イベント ベースの保持                           | エンジニアリングバックログの場合 |
|                                        |処理確認                              | エンジニアリングバックログの場合 |
|                                        |情報バリア                            | Available              |
|                                        |ファイルと電子メールのデータ損失防止 (DLP)  | Available              |
|                                        |Teams チャットおよびチャネル会話の DLP    | エンジニアリングバックログの場合 |
|                                        |DLP の正確なデータ一致                            | エンジニアリングバックログの場合 |
|                                        |ラベル アクティビティ エクスプローラー                         | エンジニアリングバックログの場合 |
|                                        |トレーニング可能な分類子                           | エンジニアリングバックログの場合 |
|                                        |統合されたラベルと機密ラベル         | エンジニアリングバックログの場合 |
|**Insider リスク管理**             |高度なメッセージ暗号化                     | Available              |
|                                        |インサイダー リスクの管理                         | エンジニアリングバックログの場合 |
|                                        |通信コンプライアンス                        | エンジニアリングバックログの場合 |
|                                        |顧客ロックボックス                                | Available              |
|                                        |顧客キー                                    | Available              |
|                                        |特権アクセス管理                    | エンジニアリングバックログの場合 |
|**& 応答の検出**                  |コア電子情報開示: インプレース保持                            | Available              |
|                                        |コア電子情報開示: ケース管理                                 | Available              |
|                                        |コア電子情報開示: 検索                                          | Available              |
|                                        |コア電子情報開示: エクスポート                                          | Available              |
|                                        |コア電子情報開示: RMS 復号化                                  | Available              |
|                                        |コア電子情報開示: ネイティブエクスポート                                   | Available              |
|                                        |高度な電子情報開示: 高度な処理                             | Available |
|                                        |高度な電子情報開示: 電子メールスレッド                                 | Available |
|                                        |高度な電子情報開示: ほぼ重複した識別情報                   | Available |
|                                        |高度な電子情報開示: テーマ                                          | Available |
|                                        |高度な電子情報開示: 予測コーディング                               | Available |
|                                        |高度な電子情報開示: 読み込みファイルを使用したエクスポート処理                 | Available |
|                                        |高度な電子情報開示: タグ付け                                         | Available |
|                                        |高度な電子情報開示: 閲覧者                                         | Available |
|                                        |高度な電子情報開示: Redactions                                      | Available |
|                                        |高度な電子情報開示: フィルター処理                                       | Available |
|                                        |高度な電子情報開示: 保管担当者 to ワークロードマッピング                   | Available |
|                                        |高度な電子情報開示: 保管担当者通信                        | Available |
|                                        |高度な電子情報開示: レビューセット                                     | Available |
|                                        |高度な電子情報開示: レビューと注釈                             | Available |
|                                        |高度な電子情報開示: Office 以外の365の取り込み                        | エンジニアリングバックログの場合 |
|                                        |高度な電子情報開示: 検索用語レポート                              | Available |

<sup>1</sup>特定された状態は、プロジェクト計画と優先度を再評価する際に変更される可能性があります。<br/>
<sup>2</sup>ラベルを手動でアプリケーションに適用するには、 [Azure INFORMATION Protection (AIP) クライアントバージョン 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)が必要です。


**判断ポイント**:*コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
