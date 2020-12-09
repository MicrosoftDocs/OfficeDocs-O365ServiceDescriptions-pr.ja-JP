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
ms.openlocfilehash: 9b4e4deec0ef79a124cc73679709970f01e73e4d
ms.sourcegitcommit: d0ca41de5b242d2d5688d92d55064d9eecbb89a9
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601768"
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
> サービスの説明の情報の表を Excel ブックに転送して、 **組織の y/n に関連** し、 **組織のニーズを満たす** 2 つの列を追加することをお勧めします。 その後、このリストを同僚と共に確認して、このサービスが組織のニーズに適合していることを確認できます。

**判断ポイント**:<br/>
- *Microsoft 365 Government – GCC-High が組織に適しているかどうかを決定します。*
- *組織が資格要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government-GCC High は米国でのみ利用可能です。 米国以外の政府機関のお客様は、多くの [Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>手順 2。 Microsoft 365 Government への適用-GCC-High

このサービスが組織に適していると判断した場合は、 [このサービスの適用](https://products.office.com/government/eligibility-validation)プロセスを開始します。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>手順 3. Microsoft 365 Government について-GCC-High 既定のセキュリティ設定を理解する

既定のセキュリティ設定を変更する前に、管理者およびセキュリティ設定を慎重に確認して、コンプライアンスへの影響を考慮することをお勧めします。

**判断ポイント**: *Microsoft 365 Government の既定の GCC-High セキュリティ設定を変更するかどうかを決定し、最初に変更が行われた場合の影響について理解します。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>手順 4. Microsoft 365 Government – GCC-High<sup>1</sup>で現在使用できない機能と無効になっている機能を理解する

政府機関のお客様の要件を満たすために、Microsoft 365 Government とエンタープライズプランにはいくつかの相違点があります。 GCC-High とエンタープライズプランにはいくつかの違いがあります。 利用可能な機能を確認するには、次の表を参照してください。 Microsoft 365 ロードマップに公開されている最新のコンプライアンス製品更新プログラムについて [は、ここ](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) を参照してください。<br><br>

| 分野                                    | 機能                                         | GCC の状態             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | クライアントとスキャナーの統一されたラベル付け         | Available              |
|                                         | 正確なデータ一致          | Available              |
|                                         | Exchange Online、SharePoint Online、OneDrive の自動分類とラベル付け                      | ロール アウト              |
|                                         | Web、Android、iOS、Windows、および Mac での Office アプリ (Word、Excel、PowerPoint、Outlook) の自動分類とラベル付け            | 開発中 |
|                                         | Office クライアントの自動分類とラベル付け (モバイル)                                       | エンジニアリングバックログの場合              |
|                                         | Teams の自動分類とラベル付け                            | エンジニアリングバックログの場合 |
|                                         | データ分類分析: 概要とコンテンツエクスプローラー                            | エンジニアリングバックログの場合 |
|                                         | 分析: サービス側の自動ラベル付きコンピューター学習分類子                           | エンジニアリングバックログの場合  |
|                                         | 分析: Office アプリ/クライアント側の自動ラベル付きコンピューター学習分類子                           | エンジニアリングバックログの場合  |
|                                         | 基本的な Office 365 メッセージの暗号化 (E3)                            | Available              |
|                                         | Advanced Office 365 Message Encryption (E5)  | Available              |
|                                         | Office 365 の顧客キー    | Available |
|                                         | お客様が管理するキープロビジョニングライフサイクルに独自のキー (BYOK) をもたらす                            | Available |
|                                         | 厳しい規制シナリオ (プレビュー) に対して Azure Information Protection と Active Directory (AD) Rights Management にまたがる独自のキー (HYOK) を保持する                         | Available |
|                                         | 二重キー暗号化                           | Available |
|                                         | 暗号化: WXP web アプリを使用した暗号化されたドキュメントの共同編集         | エンジニアリングバックログの場合 |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
|                                         | Teams チャットおよびチャネル会話の DLP | エンジニアリングバックログの場合 |
|                                         | DLP エンドポイント | エンジニアリングバックログの場合 |
| **情報ガバナンス** | 情報ガバナンス: メールのアーカイブ                                       | Available              |
|                                         | 情報ガバナンス: 保持ロック          | Available              |
|                                         | 情報ガバナンス: PST のインポート                      | Available              |
|                                         | 情報ガバナンス: 手動による非レコード保持ラベル            | Available |
|                                         | 情報ガバナンス: SharePoint/OneDrive for Business のライブラリ、フォルダー、およびドキュメントセットの既定の保持ラベル。Exchange の受信トレイ。および Office 365 グループ | Available              |
|                                         | 情報ガバナンス: 組織全体へのアイテム保持ポリシーの保持。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動で行います。イベントに基づく                                       | Available              |
|                                         | 情報ガバナンス: Teams のアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: SharePoint の同期 Tex 分類を使用したアイテム保持ラベル                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: trainable 分類子を使用したアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: Teams 会議レコーディングのアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | 情報ガバナンス: Yammer のアイテム保持ポリシー                            | エンジニアリングバックログの場合 |
|                                         | レコード管理: レコードラベルの手動分類                           | Available              |
|                                         | レコード管理: SharePoint、OneDrive for Business のライブラリ、フォルダー、およびドキュメントセットの既定のレコードラベル。および Office 365 グループ                              | Available              |
|                                         | レコード管理: 特定の条件に基づいた自動レコードポリシー (キーワードや機密情報など)。イベントに基づく                            | Available              |
|                                         | レコード管理: 廃棄レビュー  | Available              |
|                                         | レコード管理: ファイル計画マネージャー    | Available |
|                                         | レコード管理: 廃棄の証明                            | Available |
|                                         | レコード管理: レコードのバージョン管理                         | Available |
|                                         | レコード管理: 規制に関するレコード                         | エンジニアリングバックログの場合 |
|                                         | レコード管理: 複数段階の廃棄レビュー | エンジニアリングバックログの場合 |
|                                         | レコード管理: SharePoint の Syntex 分類を使用してレコードラベルを適用する | エンジニアリングバックログの場合 |
| **インサイダー リスクの管理**             | 顧客ロックボックス                                | Available            |
|                                         | Insider リスク管理: Teams、SharePoint サイト、電子メールメッセージングの Office インジケーター                         | 開発中 |
|                                         | Insider リスク管理: ユーザーが出発したデータの盗難                        | 開発中 |
|                                         | Insider リスク管理: 一般的なデータリーク                                | 開発中              |
|                                         | Insider リスク管理: insider リスク管理警告の調査                                   | 開発中              |
|                                         | Insider リスク管理: ケースダッシュボード、コンテンツエクスプローラー、およびメモテンプレート | 開発中 |
|                                         | Insider リスク管理: 高度な電子情報開示の調査のためのエスカレーション | 開発中|
|                                         | Insider リスク管理: Windows 10 ビルド1809以降のアクティビティのデバイスインジケーター | エンジニアリングバックログの場合|
|                                         | Insider リスク管理: セキュリティポリシー違反のインジケーター (プレビュー) | エンジニアリングバックログの場合|
|                                         | Insider リスク管理: エンドポイント通知に関する Microsoft Defender のインジケーター (プレビュー) | エンジニアリングバックログの場合|
|                                         | Insider リスク管理: 優先度の高いユーザーによるデータ漏洩のポリシーテンプレート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 不満を持つユーザーがデータをリークするポリシーテンプレート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 一般的なセキュリティポリシー違反 (プレビュー) のポリシーテンプレート | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 優先度の高いユーザーによるセキュリティポリシー違反のポリシーテンプレート、ユーザーの離脱、不満を抱くユーザー (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: ポリシーのカスタマイズ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: アラートのエクスポート (プレビュー) | エンジニアリングバックログの場合 |
|                                         | Insider リスク管理: 優先ユーザーグループ (プレビュー) | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 顧客ポリシーの作成、3つの事前構成  | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): Teams、Exchange、および remove Teams メッセージのサポート | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): アクセスアラート。メモテンプレートコミュニケーションポリシーダッシュボード | 開発中  |
|                                         | コミュニケーションコンプライアンス (監督ポリシーを含む): 上級電子情報開示の調査のためのエスカレーション | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 成人向けコンテンツの検出 | 開発中 |
|                                         | コミュニケーションコンプライアンス (監督ポリシーを含む): 時間の経過とともに行動違反のリピートコードを検出します。 | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): より詳細なアクセス許可のサポート | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): オンプレミスメールボックスを使用したユーザーのチャットデータの分析 | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 利息の競合テンプレート | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 電子メール署名または免責事項を無視する機能 | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): Insider リスク管理の手動 | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): ポリシーの正常性チェックとポリシーの一時停止機能 | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 調査中に正常性コンテンツを翻訳する | エンジニアリングバックログの場合 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 極度および suicide の検出 | エンジニアリングバックログの場合 |
|                                         | 情報バリア | エンジニアリングバックログの場合 |
|                                         | 特権アクセス管理                    | エンジニアリングバックログの場合 |
| **& 応答の検出**                  | コア電子情報開示: インプレース保持                            | Available              |
|                                         | コア電子情報開示: ケース管理                                 | Available              |
|                                         | コア電子情報開示: 検索                                          | Available              |
|                                         | コア電子情報開示: エクスポート                                          | Available              |
|                                         | コア電子情報開示: RMS 復号化                                  | Available              |
|                                         | コア電子情報開示: ネイティブエクスポート                                   | Available              |
|                                         | コア電子情報開示: 監査                                        | Available              |
|                                         | コア電子情報開示: SharePoint および OneDrive for Business のごみ箱内のアイテムを検索してエクスポートするためのサポートが拡張された Microsoft コンプライアンスセンター                                        | 開発中              |
|                                         | 高度な電子情報開示: 高度な処理                             | Available |
|                                         | 高度な電子情報開示: 保管担当者 to ワークロードマッピング                             | Available |
|                                         | 高度な電子情報開示: 保管担当者通信                             | Available |
|                                         | 高度な電子情報開示: ダッシュボード                             | Available |
|                                         | 高度な電子情報開示: 電子メールスレッド                                 | Available |
|                                         | 高度な電子情報開示: エクスポート (ダウンロード、エクスポート、別のレビューセットへの追加)                   | Available |
|                                         | 高度な電子情報開示: フィルター処理                                          | Available |
|                                         | 高度な電子情報開示: Teams のプライベートチャネルメッセージのリーガルホールド                               | Available |
|                                         | 高度な電子情報開示: ほぼ重複した識別情報                 | Available |
|                                         | 高度な電子情報開示: 非 custodial データソース                                         | Available |
|                                         | 高度な電子情報開示: Office 以外の365の取り込み                                         | Available |
|                                         | 高度な電子情報開示: 予測コーディング                                      | Available |
|                                         | 高度な電子情報開示: 読み込みファイルを使用したエクスポート処理                                       | Available |
|                                         | 高度な電子情報開示: Redactions                   | Available |
|                                         | 高度な電子情報開示: レビューセット                        | Available |
|                                         | 高度な電子情報開示: データの確認 (クエリデータ、スマートタグ、ダッシュボード) および注釈 (墨消し)                                     | Available |
|                                         | 高度な電子情報開示: 検索用語レポート                             | Available |
|                                         | 高度な電子情報開示: 単一アイテムエラーの修復                        | Available |
|                                         | 高度な電子情報開示: PST エクスポートをサポートする                              | ロール アウト |
|                                         | 高度な電子情報開示: OneDrive および SharePoint Online からのリンクされたコンテンツのサポート (モダン添付ファイル)                              | Available |
|                                         | 高度な電子情報開示: タグ付け                              | Available |
|                                         | 高度な電子情報開示: テナントレポート                              | Available |
|                                         | 高度な電子情報開示: テーマ                               | Available |
|                                         | 高度な電子情報開示: 閲覧者                              | Available |
|                                         | 高度な電子情報開示: Microsoft コンプライアンスセンターの Yammer Advanced eDiscovery                              | Available |
|                                         | 高度な電子情報開示: 高度な電子情報開示のための CJK/ダブルバイトのサポート                              | 開発中 |
|                                         | 高度な電子情報開示: Teams の反応のサポート                             | 開発中 |
|                                         | 高度な電子情報開示: SharePoint および OneDrive for Business のごみ箱のアイテムを検索してエクスポートするためのサポートが拡張された Microsoft コンプライアンスセンター                               | エンジニアリングバックログの場合 |
|                                         | 基本的な監査                              | Available |
|                                         | 高度な監査: 重要なイベントへのアクセス (たとえば、mailitemsaccessed アクセス)                              | Available |
|                                         | 高度な監査: 管理アクティビティ API に対する帯域幅の増加                              | Available |
|                                         | 高度な監査: Teams の法務ホールドメッセージの公開チャネル                              | Available |
|                                         | 高度な監査: ログの保存期間 (1 年)                              | ロール アウト |
|                                         | 高度な監査: セキュリティとコンプライアンスセンターの可用性                              | Available |
|                                         | 高度な監査: 監査ログに長期間保存する (10 年)                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: メールの転送とメールの送信イベント                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: audit insights の処理                              | エンジニアリングバックログの場合 |
|                                         | 高度な監査: Exchange Online および SharePoint Online の検索用語イベント                              | エンジニアリングバックログの場合 |
|    **コンプライアンス管理**            | Microsoft 365 セキュリティ/コンプライアンスセンター                              | Available |
|                                         | コンプライアンス マネージャー                                 | Available              |
|                                         | Microsoft Cloud App Security                                 | Available              |
|                                         | 2バイト文字のサポート                                 | エンジニアリングバックログの場合              |
|    **システム**            | 高度な電子情報開示用のグラフ Api                              | 開発中 |
|                                         | ファーストパーティデータコネクタ                                 | エンジニアリングバックログの場合              |
|                                         | サードパーティのデータ コネクタ                                 | エンジニアリングバックログの場合              |
|                                         | Teams のグラフ Api データをエクスポートする                                 | エンジニアリングバックログの場合              |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度を再評価する際に変更される可能性があります。<br/>

**判断ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
