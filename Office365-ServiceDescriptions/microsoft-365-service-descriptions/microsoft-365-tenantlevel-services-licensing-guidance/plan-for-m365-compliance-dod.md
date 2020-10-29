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
ms.openlocfilehash: aca09e0e7768228f39e942fbeffba1bae84cb77f
ms.sourcegitcommit: 9794350861e41d80980ecf6b9000a730b5564988
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2020
ms.locfileid: "48793656"
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

米国政府機関のお客様を対象とした Microsoft 365 Government-DoD オファーリングの詳細については、「特典要件」を含む [Office 365 政府機関プラン](https://products.office.com/government/compare-office-365-government-plans)を参照してください。

「 [Office 365 US Government サービスの説明](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) 」では、プラットフォームの利点について説明します。これは、米国内での会議のコンプライアンス要件を中心としています。

> [!TIP]
> サービスの説明の情報の表を Excel ブックに転送して、 **組織の y/n に関連** し、 **組織のニーズを満たす** 2 つの列を追加することをお勧めします。 その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。

**判断ポイント** :<br/>
- *Microsoft 365 Government が組織に適しているかどうかを決定します。*
- *組織が資格要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government は米国でのみご利用いただけます。 米国以外の政府機関のお客様は、多くの [Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>手順 2.  Microsoft 365 Government-DoD の適用

このサービスが組織に適していると判断した場合は、 [このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>手順 3. Microsoft 365 Government-DoD 既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。

**判断ポイント** : *既定の Microsoft 365 Government セキュリティ設定を変更するかどうかを決定し、最初に変更が加えられた場合の影響を理解するようにします。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>手順 4. Microsoft 365 Government – DoD<sup>1</sup>で現在利用できない機能、または既定で無効になっている機能について理解する

政府機関のお客様の要件を満たすために、Microsoft 365 Government とエンタープライズのプランにはいくつかの違いがあります。 利用可能な機能を確認するには、次の表を参照してください。<br><br>

| 分野                                    | 機能                                         | GCC の状態             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | クライアントとスキャナーの統一されたラベル付け         | Available              |
|                                         | 正確なデータ一致          | Available               |
|                                         | Exchange Online、SharePoint Online、OneDrive の自動分類とラベル付け                      | ロール アウト              |
|                                         | Web、Android、iOS、Windows、および Mac での Office アプリ (Word、Excel、PowerPoint、Outlook) の自動分類とラベル付け            | 開発中 |
|                                         | Office 365 グループでの分類に基づくポリシー |  ロール アウト              |
|                                         | モバイルの自動分類とラベル付け                                       | エンジニアリングバックログの場合              |
|                                         | Teams の自動分類とラベル付け                            | エンジニアリングバックログの場合 |
|                                         | データ分類: 概要とコンテンツアクティビティエクスプローラー                            | エンジニアリングバックログの場合 |
|                                         | 自動ラベル付きの Machine learning 分類子                           | エンジニアリングバックログの場合  |
|                                         | 基本的な Office 365 メッセージの暗号化 (E3)                            | Available              |
|                                         | Advanced Office 365 Message Encryption (E5)  | Available              |
|                                         | Office 365 の顧客キー    | Available |
|                                         | お客様が管理するキープロビジョニングライフサイクルに独自のキー (BYOK) をもたらす                            | Available |
|                                         | 厳しい規制シナリオ (プレビュー) に対して Azure Information Protection と Active Directory (AD) Rights Management にまたがる独自のキー (HYOK) を保持する                         | Available |
|                                         | 二重キー暗号化                           | 開発中 |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
|                                         | Teams チャットおよびチャネル会話のデータ損失防止         | エンジニアリングバックログの場合 |
|                                         | データ損失防止エンドポイント | エンジニアリングバックログの場合 |
| **情報ガバナンス** | 情報ガバナンス: メールのアーカイブ                                       | Available              |
|                                         | 情報ガバナンス: 保持ロック          | Available              |
|                                         | 情報ガバナンス: PST のインポート                      | Available              |
|                                         | 情報ガバナンス: 手動による非レコード保持ラベル            | Available |
|                                         | 情報ガバナンス: SharePoint/OneDrive for Business のライブラリ、フォルダー、ドキュメントセットの既定の保持ラベル。Exchange の受信トレイ。および Office 365 グループ | Available              |
|                                         | 情報ガバナンス: 組織全体へのアイテム保持ポリシーの保持。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動で行います。イベントに基づく                                       | Available              |
|                                         | 情報ガバナンス: SharePoint の同期 Tex 分類を使用したアイテム保持ラベル                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: trainable クラシファイアを使用したアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: Yammer および Teams のアイテム保持ポリシー                           | エンジニアリングバックログの場合              |
|                                         | レコード管理: レコードラベルの手動分類                              | Available              |
|                                         | レコード管理: SharePoint、OneDrive for Business のライブラリ、フォルダー、およびドキュメントセットの既定のレコードラベル。および Office 365 グループ                            | Available              |
|                                         | レコード管理: 特定の条件に基づいた自動レコードポリシー (キーワードや機密情報など)。イベントに基づく  | Available              |
|                                         | レコード管理: 廃棄レビュー    | Available |
|                                         | レコード管理: ファイル計画マネージャー                            | Available |
|                                         | レコード管理: 廃棄の証明                         | Available |
|                                         | レコード管理: レコードのバージョン管理                           | Available |
|                                         | レコード管理: 規制に関するレコード | エンジニアリングバックログの場合 |
|                                         | レコード管理: ライセンス執行 | エンジニアリングバックログの場合 |
|                                         | レコード管理: 複数段階の廃棄レビュー | エンジニアリングバックログの場合 |
|                                         | レコード管理: ラベルアクティビティエクスプローラー         | エンジニアリングバックログの場合 |
|                                         | レコード管理: Trainable 分類子         | エンジニアリングバックログの場合 |
| **インサイダー リスクの管理**             | 顧客ロックボックス                                | Available            |
|                                         | Insider リスク管理: Teams、SharePoint サイト、電子メールメッセージングの Office インジケーター                         | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: ユーザーが出発したデータの盗難                        | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 一般的なデータリーク                                | エンジニアリングバックログの場合              |
|                                         | Insider リスク管理: insider リスク管理警告の調査                                   | エンジニアリングバックログの場合              |
|                                         | Insider リスク管理: ケースダッシュボード、コンテンツエクスプローラー、およびメモテンプレート | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 高度な電子情報開示の調査のためのエスカレーション |エンジニアリングバックログの場合|
|                                         | Insider リスク管理: 優先度の高いユーザーによるデータ漏洩のポリシーテンプレート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 不満を持つユーザーがデータをリークするポリシーテンプレート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 一般的なセキュリティポリシー違反 (プレビュー) のポリシーテンプレート | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 優先度の高いユーザーによるセキュリティポリシー違反のポリシーテンプレート、ユーザーの離脱、不満を抱くユーザー (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: ポリシーのカスタマイズ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: アラートのエクスポート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 優先ユーザーグループ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 顧客ポリシーの作成、3つの事前構成  | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): Teams、Exchange、および remove Teams メッセージのサポート | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): アクセスアラート。メモテンプレートコミュニケーションポリシーダッシュボード | エンジニアリングバックログの場合  |
|                                         | コミュニケーションコンプライアンス (監督ポリシーを含む): 上級電子情報開示の調査のためのエスカレーション | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 成人向けコンテンツの検出 | エンジニアリングバックログの場合 |
|                                         | 情報バリア | エンジニアリングバックログの場合 |
|                                         | 特権アクセス管理                    | エンジニアリングバックログの場合 |
| **& 応答の検出**                  | コア電子情報開示: インプレース保持                            | Available              |
|                                         | コア電子情報開示: ケース管理                                 | Available              |
|                                         | コア電子情報開示: 検索                                          | Available              |
|                                         | コア電子情報開示: エクスポート                                          | Available              |
|                                         | コア電子情報開示: RMS 復号化                                  | Available              |
|                                         | コア電子情報開示: ネイティブエクスポート                                   | Available              |
|                                         | コア電子情報開示: 監査                                        | Available              |
|                                         | コア電子情報開示: SharePoint および OneDrive for Business のごみ箱内のアイテムを検索してエクスポートするためのサポートが拡張された Microsoft コンプライアンスセンター                             | 開発中 |
|                                         | 高度な電子情報開示: 高度な処理                                 | ロール アウト |
|                                         | 高度な電子情報開示: ダッシュボード                   | ロール アウト |
|                                         | 高度な電子情報開示: 電子メールスレッド                                          | ロール アウト |
|                                         | 高度な電子情報開示: エクスポート (ダウンロード、エクスポート、別のレビューセットへの追加)                               | ロール アウト |
|                                         | 高度な電子情報開示: フィルター処理                 | ロール アウト |
|                                         | 高度な電子情報開示: Teams のプライベートチャネルメッセージのリーガルホールド                                         | ロール アウト |
|                                         | 高度な電子情報開示: ほぼ重複した識別情報                                         | ロール アウト |
|                                         | 高度な電子情報開示: 非 custodial データソース                                      | ロール アウト |
|                                         | 高度な電子情報開示: 予測コーディング                                       | ロール アウト |
|                                         | 高度な電子情報開示: 読み込みファイルを使用したエクスポート処理                   | ロール アウト |
|                                         | 高度な電子情報開示: Redactions                        | ロール アウト |
|                                         | 高度な電子情報開示: レビューセット                                     | ロール アウト |
|                                         | 高度な電子情報開示: データの確認 (クエリデータ、スマートタグ、ダッシュボード、および注釈 (墨消し)                             | ロール アウト |
|                                         | 高度な電子情報開示: 検索用語レポート                        | ロール アウト |
|                                         | 高度な電子情報開示: タグ付け                              | ロール アウト |
|                                         | 高度な電子情報開示: テナントレポート                              | ロール アウト |
|                                         | 高度な電子情報開示: 閲覧者                              | ロール アウト |
|                                         | 高度な電子情報開示: Microsoft コンプライアンスセンターの Yammer Advanced eDiscovery                              | ロール アウト |
|                                         | 高度な電子情報開示: CJK/ダブルバイトの文字のサポート                              | エンジニアリングバックログの場合 |
|                                         | 高度な電子情報開示: Graph Api                              | エンジニアリングバックログの場合 |
|                                         | 高度な電子情報開示: SharePoint および OneDrive for Business のごみ箱のアイテムを検索してエクスポートするためのサポートが拡張された Microsoft コンプライアンスセンター                              | エンジニアリングバックログの場合 |
|                                         | 高度な電子情報開示: Office 以外の365の取り込みと処理 (たとえば、OCR)                              | エンジニアリングバックログの場合 |
|                                         | 高度な電子情報開示: Teams の反応のサポート                              | エンジニアリングバックログの場合 |
|                                         | 基本的な監査                              | Available |
|                                         | 高度な監査: セキュリティとコンプライアンスセンターの可用性                              | Available |
|                                         | 高度な監査: 重要なイベントへのアクセス (たとえば、mailitemsaccessed アクセス)                              | ロール アウト |
|                                         | 高度な監査: 管理アクティビティ API に対する帯域幅の増加                               | ロール アウト |
|                                         | 高度な監査: ログの保存期間 (1 年)                              | ロール アウト |
|                                         | 高度な監査: 監査ログに長期間保存                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: メールの転送とメールの送信イベント                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: audit insights の処理                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: Exchange Online および SharePoint Online の検索用語イベント                              | エンジニアリングバックログの場合 |
|    **コンプライアンス管理**            | Microsoft 365 セキュリティ/コンプライアンスセンター                              | Available |
|                                         | Microsoft Cloud App Security                              | エンジニアリングバックログの場合 |
|                                         | コンプライアンス マネージャー (プレビュー)                              | エンジニアリングバックログの場合 |
|                                         | 2バイト文字のサポート                              | エンジニアリングバックログの場合 |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度を再評価する際に変更される可能性があります。<br/>
<sup>2</sup> ラベルを手動でアプリケーションに適用するには、 [Azure INFORMATION Protection (AIP) クライアントバージョン 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)が必要です。


**判断ポイント** : *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
