---
title: Microsoft 365 コンプライアンスの計画 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、米国連邦政府機関のエンティティに Office 365 の展開を推進する IT 担当者、または政府の規制および要件を満たすデータを処理するその他のエンティティに対して使用されています。これは、Microsoft 365 Government – GCC 高を使用してこれらの要件を満たすことが適切な場合です。
ms.openlocfilehash: 3fecae08a3cdc53e71a68d5181b9d8c2fa8c8008
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962106"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Microsoft 365 コンプライアンスの計画-GCC 高

このガイダンスは、米国連邦政府機関のエンティティに Office 365 の展開を推進する IT 担当者、または政府の規制および要件を満たすデータを処理するその他のエンティティに対して使用されています。これは、Microsoft 365 Government – GCC 高を使用してこれらの要件を満たすことが適切な場合です。

> [!NOTE]
>組織が既に Microsoft 365 Government を使用していて、プログラムに適用されていて、かつに対して適用されている場合は、手順1と手順2を省略して手順3に直接進むことができます。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>手順 1. 組織に Microsoft 365 Government が必要かどうかを判断します。 GCC 高で、資格の要件を満たしているかどうかを判断する

Microsoft 365 Government-GCC 高環境は、クラウドサービスの米国政府の要件に準拠しています。 Office 365 の機能を楽しんでいることに加えて、組織は、Microsoft 365 Government – GCC High に固有の次の機能を活用しています。

- 組織の顧客コンテンツは、Microsoft の商用 Office 365 サービスの顧客コンテンツと論理的に分離されています。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365 Government –米国公的機関のお客様に必要な証明書と認定に準拠した GCC。

Microsoft 365 Government の詳細については、「特典の要件を含む [Office 365 政府](https://products.office.com/government/compare-office-365-government-plans)機関向けの米国政府のお客様向けの英語 (米国)」を参照してください。

「 [Office 365 US Government サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) 」では、プラットフォームの利点について説明します。これは、米国内での会議のコンプライアンス要件を中心としています。

> [!TIP]
> サービスの説明の情報の表を Excel ブックに転送して、 **組織の y/n に関連**   し、 **組織のニーズを満たす**2 つの列を追加することをお勧めします。 その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。

**判断ポイント**:<br/>
- *Microsoft 365 Government – GCC-高が組織に適しているかどうかを決定します。*
- *組織が資格要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government-GCC High は米国でのみ利用可能です。 米国以外の政府機関のお客様は、多くの [Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>手順 2.  Microsoft 365 Government に適用-GCC-高

このサービスが組織に適していると判断した場合は、 [このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>手順 3. Microsoft 365 Government – GCC-高既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。

**判断ポイント**: *既定の Microsoft 365 Government-GCC-高セキュリティ設定を変更するかどうかを決定します。解決するには、変更による影響を最初に理解する必要があります。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>手順 4. Microsoft 365 Government – GCC-High<sup>1</sup>で現在使用できない機能と無効になっている機能を理解する

政府機関のお客様の要件を満たすために、Microsoft 365 Government と、GCC-高およびエンタープライズプランにはいくつかの違いがあります。 利用可能な機能を確認するには、次の表を参照してください。


|                                         | 機能                                         | GCC の状態             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | 統合されたラベルと機密ラベル         | Available              |
|                                         | Sharepoint Online、Office グループのコンテナーラベル          | ロール アウト              |
|                                         | Excel Online、SharePoint Online、OneDrive for Business の機密データ型に基づく自動ラベル付け                      | ロール アウト              |
|                                         | Win32 および Mac Office クライアントの機密データ型に基づくラベル            | エンジニアリングバックログの場合 |
|                                         | Win 32、Mac の機密データ型に基づく自動ラベル付け |  エンジニアリングバックログの場合              |
|                                         | Teams の機密データ型に基づく自動ラベル付け                                       |エンジニアリングバックログの場合              |
|                                         | モバイルの機密データ型に基づく自動ラベル付け                            |エンジニアリングバックログの場合 |
|                                         | クエリに基づくラベルと関連付けられたポリシー                            | Available |
|                                         | ラベル アクティビティ エクスプローラー                           | エンジニアリングバックログの場合  |
|                                         | トレーニング可能な分類子                              | エンジニアリングバックログの場合              |
|                                         | 基本的な Office 365 メッセージの暗号化 (E3)                            | Available              |
|                                         | Advanced Office 365 Message Encryption (E5)  | Available              |
|                                         | Office 365 の顧客キー    | Available |
|                                         | お客様が管理するキープロビジョニングライフサイクルに独自のキー (BYOK) をもたらす                            | Available |
|                                         | 厳しい規制シナリオ (プレビュー) に対して Azure Information Protection と Active Directory (AD) Rights Management にまたがる独自のキー (HYOK) を保持する                         | Available |
|                                         | 二重キー暗号化                           | エンジニアリングバックログの場合 |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
|                                         | Teams チャットおよびチャネル会話の DLP         | ロール アウト |
|                                         | DLP の正確なデータ一致 | エンジニアリングバックログの場合 |
|                                         | DLP エンドポイント | エンジニアリングバックログの場合 |
| **情報ガバナンス** | メールのアーカイブ                                       | Available              |
|                                         | 保持ロック          | Available              |
|                                         | PST のインポート                      | Available              |
|                                         | 手動による非レコード保持ラベル            | Available |
|                                         | SharePoint/OneDrive for Business のライブラリ、フォルダー、ドキュメントセットの既定の保持ラベル。Exchange の受信トレイ。および Office 365 グループ | Available              |
|                                         | 組織全体に対するアイテム保持ポリシー。特定の場所またはユーザー。特定の条件に基づいて自動的に (キーワードや機密情報など)                                       | Available              |
|                                         | Trainable クラシファイアを使用したアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | Yammer および Teams のアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | 手動によるレコードラベル                           | Available              |
|                                         | SharePoint、OneDrive for Business のライブラリ、フォルダー、およびドキュメントセットの既定のレコードラベル。および Office 365 グループ                              | Available              |
|                                         | 特定の条件に基づく自動レコードポリシー (キーワードや機密情報など)。イベントに基づく                            | Available              |
|                                         | 処理確認  | Available              |
|                                         | ファイル計画マネージャー    | Available |
|                                         | 廃棄の証明                            | Available |
|                                         | 規定の記録                         | エンジニアリングバックログの場合 |
|                                         | レコード管理ライセンスの適用                           | エンジニアリングバックログの場合 |
|                                         | レコード管理の複数段階の廃棄レビュー | エンジニアリングバックログの場合 |
|                                         | ラベル アクティビティ エクスプローラー | エンジニアリングバックログの場合 |
|                                         | トレーニング可能な分類子 | エンジニアリングバックログの場合 |
|                                         | 統合されたラベルと機密ラベル         | エンジニアリングバックログの場合 |
| **インサイダー リスクの管理**             | 顧客ロックボックス                                | Available            |
|                                         | Teams、SharePoint サイト、電子メールメッセージングの Office インジケーター                         | ロール アウト |
|                                         | ユーザーが出発したデータの盗難                        | ロール アウト |
|                                         | 一般的なデータリーク                                | ロール アウト              |
|                                         | Insider リスク管理の通知を調査する                                   | ロール アウト              
|                                         | Insider リスク管理ケースダッシュボード、コンテンツエクスプローラー、およびメモテンプレート | ロール アウト |
|                                         | 上級電子情報開示の調査のためのエスカレーション | ロール アウト|
|                                         | 優先度の高いユーザーによるデータリーク (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 不満のあるユーザーがデータをリークする (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 一般的なセキュリティポリシー違反 (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 優先度の高いユーザーによるセキュリティポリシー違反、ユーザーの離脱、不満を抱くユーザー (プレビュー) | エンジニアリングバックログの場合 |
|                                         | ポリシーのカスタマイズ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 通知のエクスポート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 優先ユーザーグループ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | コミュニケーションコンプライアンス (監督ポリシーを含む) に対して事前構成された顧客ポリシーの作成  | ロール アウト |
|                                         | Teams、Exchange、および remove Teams メッセージの通信コンプライアンス (監督ポリシーを含む) のサポート | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む) のアクセス通知。メモテンプレートコミュニケーションポリシーダッシュボード | ロール アウト  |
|                                         | 高度な電子情報開示のための通信コンプライアンス (監督ポリシーを含む) のエスカレーション | ロール アウト |
|                                         | コミュニケーションコンプライアンス (監督ポリシーを含む) による成人向けコンテンツの検出 | ロール アウト |
|                                         | 情報バリア | エンジニアリングバックログの場合 |
|                                         | 特権アクセス管理                    | エンジニアリングバックログの場合 |
| **& 応答の検出**                  | コア電子情報開示: インプレース保持                            | Available              |
|                                         | コア電子情報開示: ケース管理                                 | Available              |
|                                         | コア電子情報開示: 検索                                          | Available              |
|                                         | コア電子情報開示: エクスポート                                          | Available              |
|                                         | コア電子情報開示: RMS 復号化                                  | Available              |
|                                         | コア電子情報開示: ネイティブエクスポート                                   | Available              |
|                                         | コア電子情報開示: 監査                                        | Available              |
|                                         | 高度な電子情報開示: 高度な処理                             | ロール アウト |
|                                         | 高度な電子情報開示: 電子メールスレッド                                 | ロール アウト |
|                                         | 高度な電子情報開示: ほぼ重複した識別情報                   | ロール アウト |
|                                         | 高度な電子情報開示: テーマ                                          | ロール アウト |
|                                         | 高度な電子情報開示: 予測コーディング                               | ロール アウト |
|                                         | 高度な電子情報開示: 読み込みファイルを使用したエクスポート処理                 | ロール アウト |
|                                         | 高度な電子情報開示: タグ付け                                         | ロール アウト |
|                                         | 高度な電子情報開示: 閲覧者                                         | ロール アウト |
|                                         | 高度な電子情報開示: Redactions                                      | ロール アウト |
|                                         | 高度な電子情報開示: フィルター処理                                       | ロール アウト |
|                                         | 高度な電子情報開示: 保管担当者 to ワークロードマッピング                   | ロール アウト |
|                                         | 高度な電子情報開示: 保管担当者通信                        | ロール アウト |
|                                         | 高度な電子情報開示: レビューセット                                     | ロール アウト |
|                                         | 高度な電子情報開示: レビューと注釈                             | ロール アウト |
|                                         | 高度な電子情報開示: Office 以外の365の取り込み                        | ロール アウト |
|                                         | 高度な電子情報開示: 検索用語レポート                              | ロール アウト |
|                                         | 基本的な監査                              | Available |
|                                         | 高度な監査: 重要なイベントへのアクセス (たとえば、mailitemsaccessed アクセス)                              | ロール アウト |
|                                         | 高度な監査ログの保存期間 (1 年)                               | ロール アウト |
|                                         | 高度な監査による管理アクティビティ API への帯域幅の増加                              | ロール アウト |
|    **コンプライアンス管理**            | コンプライアンスマネージャーとスコア                              | エンジニアリングバックログの場合 |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度を再評価する際に変更される可能性があります。<br/>
<sup>2</sup> ラベルを手動でアプリケーションに適用するには、 [Azure INFORMATION Protection (AIP) クライアントバージョン 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)が必要です。 


**判断ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
