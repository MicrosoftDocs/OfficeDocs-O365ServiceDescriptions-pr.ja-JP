---
title: Microsoft 365 コンプライアンスの計画 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、microsoft 365 Government – GCC High の使用がこれらの要件を満たすのに適した、米国連邦政府機関または政府の規制および要件の対象となるデータを処理する他のエンティティで Office 365 の展開を推進している IT プロ向けです。
ms.openlocfilehash: 14c92229fa5ec147ff995d0cebe991cfdce0de70
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173082"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Microsoft 365 コンプライアンスの計画 – GCC High

このガイダンスは、microsoft 365 Government – GCC High の使用がこれらの要件を満たすのに適した、米国連邦政府機関または政府の規制および要件の対象となるデータを処理する他のエンティティで Office 365 の展開を推進している IT プロ向けです。

> [!NOTE]
>組織が既に Microsoft 365 Government – GCC High eligibility requirements を満たし、プログラムに適用され、受け入れ済みである場合は、手順 1 と 2 をスキップして、手順 3 に直接進みます。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>手順 1. 組織で Microsoft 365 Government – GCC High が必要であり、適格性要件を満たしていることを確認する

Microsoft 365 Government - GCC High 環境は、クラウド サービスに関する米国政府機関の要件に準拠しています。 Office 365 の機能を利用できるだけでなく、組織は Microsoft 365 Government – GCC High 固有の次の機能を利用できます。

- 組織の顧客コンテンツは、Microsoft から 365 サービスを提供する商用サービスの顧客Office論理的に分離されています。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365 Government – GCC High は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

米国政府機関のお客様向け Microsoft 365 Government – GCC High オファリングの詳細については [、Office 365 Government](https://products.office.com/government/compare-office-365-government-plans)プラン (適格性要件を含む) をご覧ください。

この [Office 365 米国](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 政府機関サービスの説明では、米国内のコンプライアンス要件を満たしていることを中心にプラットフォームの利点について説明します。

> [!TIP]
> サービス説明の情報テーブルを Excel ブックに転送し、自分の組織 **Y/N** に関連する列と組織の **Y/N** のニーズを満たすという 2 つの列を追加できます。 次に、この一覧を同僚と確認して、このサービスが組織のニーズを満たしているのを確認できます。

**決定点**:<br/>
- *組織に適した Microsoft 365 Government – GCC-Highを決定します。*
- *組織が適格性要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365 Government - GCC High は米国でのみ利用可能です。 米国以外の政府機関のお客様は [、365 の政府機関Officeから選択できます](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>手順 2. Microsoft 365 Government に申請する – GCC-High

このサービスが組織に正しいと決定した後、このサービスに適用 [するプロセスを開始します](https://products.office.com/government/eligibility-validation)。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>手順 3. Microsoft 365 Government について – GCC-Highのセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者とセキュリティ設定を慎重に確認し、コンプライアンスへの影響を考慮してから、既定のセキュリティ設定を変更することをお勧めします。

**決定ポイント**: 既定の *Microsoft 365 Government - GCC-High* セキュリティ設定を変更するかどうかを決定し、変更の影響を最初に理解します。

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>手順 4. Microsoft 365 Government – GCC-High 1 で既定で現在使用できない機能または無効になっている機能を<sup>理解する</sup>

政府機関向けクラウドのお客様の要件を満たすために、Microsoft 365 Government とエンタープライズ プランのGCC-High違いがあります。 使用可能な機能については、次の表を参照してください。 Microsoft [](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 365 ロードマップで公開されている最新のコンプライアンス製品更新プログラムについては、こちらを参照してください。<br><br>

| 分野                                    | 機能                                         | GCC の状態             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | 統合ラベル付けクライアントとスキャナー         | Available              |
|                                         | 完全なデータ一致          | Available              |
|                                         | Exchange Online、SharePoint Online、OneDrive の自動分類とラベル付け                      | ロール アウト              |
|                                         | Web、Android、iOS、Windows、および Mac Officeアプリ (Word、Excel、PowerPoint、Outlook) の自動分類とラベル付け            | 開発中 |
|                                         | クライアントの自動分類とOffice (Mobile)                                       | エンジニアリング バックログについて              |
|                                         | Teams の自動分類とラベル付け                            | エンジニアリング バックログについて |
|                                         | データ分類分析: 概要とコンテンツ エクスプローラー                            | エンジニアリング バックログについて |
|                                         | 分析: サービス側での自動ラベル付けによる機械学習分類子                           | エンジニアリング バックログについて  |
|                                         | 分析: アプリ/クライアント側での自動ラベル付Office機械学習分類子                           | エンジニアリング バックログについて  |
|                                         | 基本Office 365 メッセージ暗号化 (E3)                            | Available              |
|                                         | Advanced Office 365 メッセージ暗号化 (E5)  | Available              |
|                                         | Office 365 の顧客キー    | Available |
|                                         | 顧客が管理するキー プロビジョニングのライフ サイクル用に独自のキー (BYOK) を持参する                            | Available |
|                                         | 高度に規制されたシナリオ (プレビュー) の Azure Information Protection と Active Directory (AD) Rights Management にまたがる独自のキー (HYOK) を保持する                         | Available |
|                                         | 二重キー暗号化                           | Available |
|                                         | 暗号化: WXP Web アプリを使用した暗号化されたドキュメントの共同編集         | エンジニアリング バックログについて |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
|                                         | Teams チャットとチャネルの会話用 DLP | エンジニアリング バックログについて |
|                                         | DLP エンドポイント | エンジニアリング バックログについて |
| **情報ガバナンス** | 情報ガバナンス: 電子メール アーカイブ                                       | Available              |
|                                         | 情報ガバナンス: 保持ロック          | Available              |
|                                         | 情報ガバナンス: PST のインポート                      | Available              |
|                                         | 情報ガバナンス: 手動の非レコード保持ラベル            | Available |
|                                         | 情報ガバナンス: SharePoint/OneDrive for Business ライブラリ、フォルダー、およびドキュメント セットの既定の保持ラベル。Exchange の受信トレイ。および Office 365 グループ | Available              |
|                                         | 情報ガバナンス: 組織全体に対する保持ポリシー。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に実行されます。イベントに基づく                                       | Available              |
|                                         | 情報ガバナンス: Teams の保持ポリシー                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: SharePoint Syntex 分類を使用した保持ラベル                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: トレーニング可能な分類子を含む保持ポリシー                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: Teams 会議記録の保持ポリシー                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: ユーザーの保持ポリシー Yammer                            | エンジニアリング バックログについて |
|                                         | レコード管理: レコード ラベルの手動分類                           | Available              |
|                                         | レコード管理: SharePoint、OneDrive for Business ライブラリ、フォルダー、およびドキュメント セットの既定のレコード ラベル。および Office 365 グループ                              | Available              |
|                                         | レコード管理: 特定の条件 (キーワードや機密情報など) に基づく自動レコード ポリシー。イベントに基づく                            | Available              |
|                                         | レコード管理: 廃棄レビュー  | Available              |
|                                         | レコード管理: ファイル計画マネージャー    | Available |
|                                         | レコード管理: 廃棄の証明                            | Available |
|                                         | レコード管理: レコードのバージョン管理                         | Available |
|                                         | レコード管理: 規制レコード                         | エンジニアリング バックログについて |
|                                         | レコード管理: 複数ステージの廃棄レビュー | エンジニアリング バックログについて |
|                                         | レコード管理: SharePoint Syntex 分類を使用してレコード ラベルを適用する | エンジニアリング バックログについて |
| **インサイダー リスクの管理**             | カスタマー ロックボックス                                | Available            |
|                                         | Insider リスク管理: Teams Office SharePoint サイト、電子メール メッセージングのインジケーター                         | 開発中 |
|                                         | Insider リスク管理: ユーザーを退出してデータを盗む                        | 開発中 |
|                                         | Insider リスク管理: 一般的なデータ 漏洩                                | 開発中              |
|                                         | Insider リスク管理: インサイダー リスク管理アラートを調査する                                   | 開発中              |
|                                         | Insider リスク管理: ケース ダッシュボード、コンテンツ エクスプローラー、通知テンプレート | 開発中 |
|                                         | Insider リスク管理: 高度な電子情報開示の調査のためのエスカレート | 開発中|
|                                         | Insider リスク管理: Windows 10 ビルド 1809 以上のアクティビティのデバイス インジケーター | エンジニアリング バックログについて|
|                                         | Insider リスク管理: セキュリティ ポリシー違反のインジケーター (プレビュー) | エンジニアリング バックログについて|
|                                         | Insider リスク管理: Microsoft Defender for Endpoint アラートのインジケーター (プレビュー) | エンジニアリング バックログについて|
|                                         | Insider リスク管理: 優先ユーザーによるデータ 漏洩のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 不満を持つユーザーによるデータ 漏洩のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 一般的なセキュリティ ポリシー違反のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 優先ユーザーによるセキュリティ ポリシー違反のポリシー テンプレート、ユーザーの退出、不満を持つユーザー (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: ポリシーのカスタマイズ (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: エクスポートアラート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 優先度の高いユーザー グループ (プレビュー) | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 顧客ポリシーの作成、3 つの事前構成済み  | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): Teams、Exchange、および Teams メッセージの削除のサポート | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): アクセス通知。通知テンプレート。通信ポリシー ダッシュボード | 開発中  |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 高度な電子情報開示の調査をエスカレートする | 開発中 |
|                                         | コミュニケーション コンプライアンス (監督ポリシーを含む): 成人向けコンテンツを検出する | 開発中 |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 繰り返しの行動規範違反を検出します。 | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): より詳細なアクセス許可のサポート | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): プレムメールボックスを使用してユーザーの Teams チャット データを分析する | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 利益相反テンプレート | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 電子メールの署名または免責事項を無視する機能 | エンジニアリング バックログについて |
|                                         | コミュニケーション コンプライアンス (監督ポリシーを含む): Insider リスク管理ハンドオフ | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): ポリシーの正常性チェックとポリシーを一時停止する機能 | エンジニアリング バックログについて |
|                                         | コミュニケーション コンプライアンス (監督ポリシーを含む): 調査中に正常性コンテンツを翻訳する | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): バーンアウトと自殺の検出 | エンジニアリング バックログについて |
|                                         | 情報バリア | エンジニアリング バックログについて |
|                                         | 特権アクセス管理                    | エンジニアリング バックログについて |
| **応答&を検出する**                  | コア電子情報開示: インプレイス保持                            | Available              |
|                                         | コア電子情報開示: ケース管理                                 | Available              |
|                                         | コア電子情報開示: 検索                                          | Available              |
|                                         | コア電子情報開示: エクスポート                                          | Available              |
|                                         | コア電子情報開示: RMS 復号化                                  | Available              |
|                                         | コア電子情報開示: ネイティブ エクスポート                                   | Available              |
|                                         | コア電子情報開示: 監査                                        | Available              |
|                                         | コア電子情報開示: Microsoft コンプライアンス センターでは、SharePoint および OneDrive for Business ごみ箱のアイテムを検索およびエクスポートするサポートが拡張されました                                        | 開発中              |
|                                         | 高度な電子情報開示: 高度な処理                             | Available |
|                                         | 高度な電子情報開示: 保管担当者からワークロードへのマッピング                             | Available |
|                                         | 高度な電子情報開示: カストディアン通信                             | Available |
|                                         | 高度な電子情報開示: ダッシュボード                             | Available |
|                                         | 高度な電子情報開示: 電子メール スレッド                                 | Available |
|                                         | 高度な電子情報開示: エクスポート (ダウンロード、エクスポート、別のレビュー セットへの追加)                   | Available |
|                                         | 高度な電子情報開示: フィルター処理                                          | Available |
|                                         | 高度な電子情報開示: Teams プライベート チャネル メッセージの法的保持                               | Available |
|                                         | 高度な電子情報開示: 重複した ID に近い                 | Available |
|                                         | 高度な電子情報開示: 非保管データ ソース                                         | Available |
|                                         | 高度な電子情報開示: 非Office 365 インジェスト                                         | Available |
|                                         | 高度な電子情報開示: 予測コーディング                                      | Available |
|                                         | 高度な電子情報開示: 読み込みファイルを使用して処理されたエクスポート                                       | Available |
|                                         | 高度な電子情報開示: Redactions                   | Available |
|                                         | 高度な電子情報開示: レビュー セット                        | Available |
|                                         | 高度な電子情報開示: データの確認 (クエリ データ、スマート タグ、ダッシュボード) と注釈 (やり直し)                                     | Available |
|                                         | 高度な電子情報開示: 検索用語レポート                             | Available |
|                                         | 高度な電子情報開示: 単一アイテムのエラー修復                        | Available |
|                                         | 高度な電子情報開示: PST エクスポートのサポート                              | ロール アウト |
|                                         | 高度な電子情報開示: OneDrive と SharePoint Online からのリンクされたコンテンツのサポート (最新の添付ファイル)                              | Available |
|                                         | 高度な電子情報開示: タグ付け                              | Available |
|                                         | 高度な電子情報開示: テナント レポート                              | Available |
|                                         | 高度な電子情報開示: テーマ                               | Available |
|                                         | 高度な電子情報開示: 閲覧者                              | Available |
|                                         | 高度な電子情報開示: Yammer コンプライアンス センターで高度な電子情報開示を作成する                              | Available |
|                                         | 高度な電子情報開示: 高度な電子情報開示の CJK/Double byte サポート                              | 開発中 |
|                                         | 高度な電子情報開示: サポート チームの反応                             | 開発中 |
|                                         | 高度な電子情報開示: Microsoft コンプライアンス センターでは、SharePoint および OneDrive for Business ごみ箱のアイテムを検索およびエクスポートするサポートが拡張されました                               | エンジニアリング バックログについて |
|                                         | 基本的な監査                              | Available |
|                                         | 高度な監査: 重要なイベントへのアクセス (mailitemsaccessed など)                              | Available |
|                                         | 高度な監査: 管理アクティビティ API への帯域幅の増加                              | Available |
|                                         | 高度な監査: Teams プライベート チャネル メッセージの法的保持                              | Available |
|                                         | 高度な監査: ログ保持 (1 年)                              | ロール アウト |
|                                         | 高度な監査: セキュリティとコンプライアンス センターの可用性                              | Available |
|                                         | 高度な監査: 監査ログの長期保持 (10 年)                              | エンジニアリング バックログについて |
|                                         | 高度な監査: メール転送イベントとメール送信イベント                              | エンジニアリング バックログについて |
|                                         | 高度な監査: 処理された監査の分析情報                              | エンジニアリング バックログについて |
|                                         | 高度な監査: Exchange Online および SharePoint Online の検索用語イベント                              | エンジニアリング バックログについて |
|    **コンプライアンス管理**            | Microsoft 365 セキュリティとコンプライアンス センター                              | Available |
|                                         | コンプライアンス マネージャー                                 | Available              |
|                                         | Microsoft Cloud App Security                                 | Available              |
|                                         | 2 バイト文字のサポート                                 | エンジニアリング バックログについて              |
|    **エコシステム**            | 高度な電子情報開示のグラフ API                              | 開発中 |
|                                         | ファースト パーティのデータ コネクタ                                 | エンジニアリング バックログについて              |
|                                         | サードパーティのデータ コネクタ                                 | エンジニアリング バックログについて              |
|                                         | Teams エクスポート データのグラフ API                                 | エンジニアリング バックログについて              |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度の再評価に応じて変更される可能性があります。<br/>

**意思決定ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*