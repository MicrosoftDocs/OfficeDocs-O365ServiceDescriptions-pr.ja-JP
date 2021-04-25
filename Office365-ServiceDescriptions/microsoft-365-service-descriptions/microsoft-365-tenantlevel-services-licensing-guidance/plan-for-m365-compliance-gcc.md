---
title: Microsoft 365 コンプライアンスの計画 - GCC
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、microsoft 365 Government - GCC の使用がこれらの要件を満たすのに適した、政府の規制および要件の対象となるデータを処理する米国連邦、州、地方、部族、または地域の政府機関または他のエンティティで Office 365 の展開を推進している IT のプロ向けです。
ms.openlocfilehash: d3be49d3171e07cfc11e6d6924a8b5ec2395d920
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001903"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Microsoft 365 コンプライアンスの計画 – GCC

このガイダンスは、microsoft 365 Government - GCC の使用がこれらの要件を満たすのに適した、政府の規制および要件の対象となるデータを処理する米国連邦、州、地方、部族、または地域の政府機関または他のエンティティで Office 365 の展開を推進している IT のプロ向けです。

> [!NOTE]
> 組織が Microsoft 365 Government - GCC の適格性要件を既に満たし、プログラムに適用され、受け入れ済みである場合は、手順 1 と 2 をスキップして、手順 3 に直接進みます。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>手順 1. 組織で Microsoft 365 Government - GCC が必要であり、適格性要件を満たしているか確認する

Microsoft 365 Government - GCC 環境は、FedRAMP Moderate などのクラウド サービスに関する米国政府の要件、および刑事司法および連邦税情報システム (CJI および FTI データ型) の要件に準拠しています。

Office 365 の機能を利用できるだけでなく、組織は Microsoft 365 Government - GCC 固有の次の機能を利用できます。

- 組織の顧客コンテンツは、Microsoft から 365 サービスを提供する商用サービスの顧客Office論理的に分離されています。

- 組織の顧客コンテンツは、米国内に格納されます。

- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。

- Microsoft 365 Government - GCC は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

米国政府機関のお客様向け Microsoft 365 Government - GCC 製品の詳細については [、Office 365 Government](https://products.office.com/government/compare-office-365-government-plans)プラン (資格要件を含む) をご覧ください。

この [Office 365 米国](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 政府機関サービスの説明では、米国内のコンプライアンス要件を満たしていることを中心にプラットフォームの利点について説明します。

> [!TIP]
> サービス説明の情報テーブルを Excel ブックに転送し、自分の組織 **Y/N** に関連する列と組織の **Y/N** のニーズを満たすという 2 つの列を追加できます。 次に、この一覧を同僚と確認して、このサービスが組織のニーズを満たしているのを確認できます。

> [!NOTE]
> Microsoft 365 Government - GCC は米国でのみ使用できます。 米国以外の政府機関のお客様は [、365 の政府機関Officeから選択できます](https://products.office.com/government/compare-office-365-government-plans)。

**決定点**: <br/>
- *組織に適した Microsoft 365 Government - GCC かどうかを決定します。*
- *組織が適格性要件を満たしていることを確認します。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>手順 2. Microsoft 365 Government - GCC に申し込む

このサービスが組織に正しいと決定した後、このサービスに適用 [するプロセスを開始します](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>手順 3. Microsoft 365 Government - GCC の既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者とセキュリティ設定を慎重に確認し、コンプライアンスへの影響を考慮してから、既定のセキュリティ設定を変更することをお勧めします。

**決定ポイント**: 既定の *Microsoft 365 Government - GCC* のセキュリティ設定を変更するかどうかを決定し、変更の影響を最初に理解します。

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>手順 4. Microsoft 365 Government – GCC 1 で既定で現在使用できない機能または無効になっている機能を<sup>理解する</sup>

政府機関のクラウド顧客の要件に対応するために、Microsoft 365 Government - GCC とエンタープライズ プランにはいくつかの違いがあります。 使用可能な機能については、次の表を参照してください。 Microsoft [](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 365 ロードマップで公開されている最新のコンプライアンス製品更新プログラムについては、こちらを参照してください。<br><br>

| 分野 | 機能 | GCC の状態 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | 統合ラベル付けクライアントとスキャナー         | Available              |
|                                         | 完全なデータ一致          | Available              |
| 感度ラベル付け                    | Exchange Online、SharePoint Online、OneDrive の自動分類とラベル付け                      | Available         |
| 感度ラベル付け                    | プラットフォーム間 (web、Android、iOS、Windows、および Mac) Office アプリ (Word、Excel、PowerPoint、Outlook) の自動分類とラベル付け |  Available              |
| 感度ラベル付け                    | クライアントの自動分類とOffice (Mobile)                                       | エンジニアリング バックログについて              |
| 感度ラベル付け                    | Teams、Microsoft 365 グループ、SharePoint サイトの自動分類とラベル付け                            | Available |
| 分析                               | データ分類分析: 概要とコンテンツ エクスプローラー                            | Available |
| 分析                               | 分析: サービス側での自動ラベル付けによる機械学習分類子                           | エンジニアリング バックログについて  |
| 分析                               | 分析: アプリ/クライアント側での自動ラベル付Office機械学習分類子                           | ロール アウト |
| 暗号化                              | 基本Office 365 メッセージ暗号化 (E3)                            | Available              |
| 暗号化                              | Advanced Office 365 メッセージ暗号化 (E5)  | Available              |
| 暗号化                              | Office 365 の顧客キー    | Available |
| 暗号化                              | 顧客キー: Microsoft 365 の保存時のデータ暗号化    | ロール アウト |
| 暗号化                              | 顧客が管理するキー プロビジョニングのライフ サイクル用に独自のキー (BYOK) を持参する                            | Available |
| 暗号化                              | 二重キー暗号化                           | Available |
| 暗号化                              | Microsoft Managed キーを使用した Exchange Online サービスの暗号化         | Available |
| データ損失防止                    | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
| データ損失防止                    | Teams チャットとチャネルの会話用 DLP         | Available |
| データ損失防止                    | DLP エンドポイント | ロール アウト |
| データ損失防止                    | アラート ダッシュボード | 開発中 |
| データ損失防止                    | 概要ページ | 開発中 |
| **情報ガバナンス** | 保持ポリシーとラベル付けポリシーのアダプティブ スコープ                 | エンジニアリング バックログについて              |
| 情報ガバナンス                 | メール のアーカイブ          | Available              |
| 情報ガバナンス                 | SharePoint、OneDrive for Business ライブラリ、フォルダー、およびドキュメント セットの既定の保持ラベル。Exchange の受信トレイ。および Office 365 グループ          | Available              |
| 情報ガバナンス                 | PST のインポート                      | Available              |
| 情報ガバナンス                 | 手動の非レコード保持ラベル            | Available |
| 情報ガバナンス                 | 保持ロック            | Available |
| 情報ガバナンス                 | 組織全体に対するアイテム保持ポリシー。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に実行されます。イベントに基づく                                       | Available              |
| 情報ガバナンス                 | Teams のアイテム保持ポリシー                            | Available |
| 情報ガバナンス                 | Teams 会議記録の保持ポリシー                            | 開発中 |
| 情報ガバナンス                 | Teams プライベート チャネルのアイテム保持ポリシー                            | エンジニアリング バックログについて |
| 情報ガバナンス                 | Teams 共有チャネルのアイテム保持ポリシー                            | エンジニアリング バックログについて |
| 情報ガバナンス                 | トレーニング可能な分類子を持つアイテム保持ポリシー                            | エンジニアリング バックログについて |
| 情報ガバナンス                 | アイテム保持ポリシー Yammer                            | エンジニアリング バックログについて |
| レコード管理                     | レコード ラベルを削除する機能                           | 開発中              |
| レコード管理                     | レコード ラベルを手動で適用する                            | Available              |
| レコード管理                     | SharePoint、OneDrive for Business ライブラリ、フォルダー、およびドキュメント セットの既定のレコード ラベルを適用します。および Office 365 グループ                              | Available              |
| レコード管理                     | 特定の条件 (キーワードや機密情報など) に基づいてレコード ポリシーを自動的に適用する。イベントに基づく                            | Available              |
| レコード管理                     | トレーニング可能な分類子を使用してレコード ポリシーを自動的に適用する  | 開発中              |
| レコード管理                     | 処理確認  | Available              |
| レコード管理                     | ファイル計画マネージャー    | Available |
| レコード管理                     | 複数ステージの廃棄レビュー    | エンジニアリング バックログについて |
| レコード管理                     | レコード管理の Outlook クライアント サポート    | エンジニアリング バックログについて |
| レコード管理                     | 保持期間の終了時点での Power Automate Flow    | エンジニアリング バックログについて |
| レコード管理                     | クラウド添付ファイルの保存と自動ラベル付け    | エンジニアリング バックログについて |
| レコード管理                     | 廃棄の証明                            | Available |
| レコード管理                     | レコードのバージョン管理                            | Available |
| レコード管理                     | 規制レコード                         | Available |
| レコード管理                     | SharePoint Syntex 分類を使用してレコード ラベルを適用する | エンジニアリング バックログについて |
| **インサイダー リスクの管理**             | 顧客ロックボックス                                | Available            |
| 通信コンプライアンス                | 電子メールの署名または免責事項を無視する機能                         | 開発中 |
| 通信コンプライアンス                | 通信コンプライアンス ポリシーの保持期間を設定する機能                         | 開発中 |
| 通信コンプライアンス                | アクセスアラート。通知テンプレート。通信ポリシー ダッシュボード                         | Available |
| 通信コンプライアンス                | プレムメールボックスを使用してユーザーの Teams チャット データを分析する                         | Available |
| 通信コンプライアンス                | ユーザーがメンバーであるすべての Teams を自動的に監視する                         | Available |
| 通信コンプライアンス                | 利益相反テンプレート                         | Available |
| 通信コンプライアンス                | 顧客ポリシーの作成、3 つの事前構成済み                         | Available |
| 通信コンプライアンス                | 成人向けコンテンツを検出する                         | Available |
| 通信コンプライアンス                | 時間の間に繰り返し行動規範違反を検出する                         | Available |
| 通信コンプライアンス                | 高度な電子情報開示の調査をエスカレートする                         | Available |
| 通信コンプライアンス                | Insider リスク管理のハンドオフ                         | エンジニアリング バックログについて |
| 通信コンプライアンス                | 光学式文字認識を活用してメッセージを抽出および評価する                         | 開発中 |
| 通信コンプライアンス                | 非常に小規模な企業向け新しい簡略化されたビュー                         | 開発中 |
| 通信コンプライアンス                | ポリシーの正常性チェックとポリシーを一時停止する機能                         | 開発中 |
| 通信コンプライアンス                | Power Automate の統合                         | 開発中 |
| 通信コンプライアンス                | より詳細なアクセス許可のサポート                         | Available |
| 通信コンプライアンス                | 脅威、標的型ハラスメント、冒とく分類者に対して 7 つの言語をサポート                         | 開発中 |
| 通信コンプライアンス                | Microsoft Teams の統合                         | エンジニアリング バックログについて |
| 通信コンプライアンス                | Teams の会話コンテキスト                         | 開発中 |
| 通信コンプライアンス                | 調査中にコンテンツを翻訳する                         | エンジニアリング バックログについて |
| 顧客ロックボックス                | 顧客ロックボックス                         | Available |
| 情報バリア                | 情報バリア                         | Available |
| インサイダー リスク管理             | ケースダッシュボード                         | Available |
| インサイダー リスク管理             | ユーザーを退出してデータを盗む                        | Available |
| インサイダー リスク管理             | Windows 10 ビルド 1809 以上のアクティビティのデバイス インジケーター                        | エンジニアリング バックログについて |
| インサイダー リスク管理             | 高度な電子情報開示の調査をエスカレートする                        | Available |
| インサイダー リスク管理             | アラートのエクスポート                        | エンジニアリング バックログについて |
| インサイダー リスク管理             | 一般的なデータ リーク                                | Available              |
| インサイダー リスク管理             | セキュリティ ポリシー違反のインジケーター                   | エンジニアリング バックログについて              |
| インサイダー リスク管理             | Microsoft Defender for Endpoint アラートのインジケーター      | エンジニアリング バックログについて              |
| インサイダー リスク管理             | Insider リスク管理 アクティビティ エクスプローラー      | 開発中              |
| インサイダー リスク管理             | Insider risk Management Content Explorer      | 開発中              |
| インサイダー リスク管理             | インサイダーリスク管理アラートの調査      | Available              |
| インサイダー リスク管理             | 通知テンプレート      | Available              |
| インサイダー リスク管理             | Office Teams、SharePoint サイト、電子メール メッセージングのインジケーター      | Available              |
| インサイダー リスク管理             | ポリシーのカスタマイズ      | エンジニアリング バックログについて              |
| インサイダー リスク管理             | 不満を持つユーザーによるデータ リークのポリシー テンプレート      | エンジニアリング バックログについて              |
| インサイダー リスク管理             | 優先ユーザーによるデータ リークのポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理             | 一般的なセキュリティ ポリシー違反のポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理             | 優先ユーザーによるセキュリティ ポリシー違反、ユーザーの退出、不満を持つユーザーのポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理             | 優先度の高いユーザー グループ | エンジニアリング バックログについて |
| インサイダー リスク管理             | Power Automate の統合 | 開発中 |
| インサイダー リスク管理             | Microsoft Teams の統合 | エンジニアリング バックログについて |
| 特権アクセス管理        | 特権アクセス管理 | エンジニアリング バックログについて |
| **応答&を検出する**                  | コア電子情報開示: 監査                            | Available              |
| 電子情報開示                              | コア電子情報開示: ケース管理                                 | Available              |
| 電子情報開示                              | コア電子情報開示: エクスポート                                          | Available              |
| 電子情報開示                              | コア電子情報開示: インプレイス保持                           | Available              |
| 電子情報開示                              | コア電子情報開示: ネイティブ エクスポート                                  | Available              |
| 電子情報開示                              | コア電子情報開示: RMS 復号化                                   | Available              |
| 電子情報開示                              | コア電子情報開示: 検索                                   | Available              |
| 電子情報開示                              | コア電子情報開示: Microsoft コンプライアンス センターは、SharePoint および OneDrive for Business ごみ箱のアイテムの検索とエクスポートのサポートを拡張しました                                        | Available              |
| 電子情報開示                              | 高度な電子情報開示: 高度な処理                             | Available |
| 電子情報開示                              | 高度な電子情報開示: ワークロードマッピングへの保管                             | Available |
| 電子情報開示                              | 高度な電子情報開示: カストディアン通信                             | Available |
| 電子情報開示                              | 高度な電子情報開示: ダッシュボード                                 | Available |
| 電子情報開示                              | 高度な電子情報開示: 2 バイト文字のサポート (中国語、日本語、韓国語)                                 | Available |
| 電子情報開示                              | 高度な電子情報開示: 電子メール スレッド                   | Available |
| 電子情報開示                              | 高度な電子情報開示: エクスポート (ダウンロード、エクスポート、別のビュー セットへの追加)                                          | Available |
| 電子情報開示                              | 高度な電子情報開示: フィルター処理                               | Available |
| 電子情報開示                              | 高度な電子情報開示: ホールドの最適化                      | 開発中 |
| 電子情報開示                              | 高度な電子情報開示: Teams プライベート チャネル メッセージの法的保持            | Available |
| 電子情報開示                              | 高度な電子情報開示: Microsoft コンプライアンス センターでは、SharePoint および OneDrive for Business ごみ箱のアイテムを検索およびエクスポートするサポートが拡張されました            | 開発中 |
| 電子情報開示                              | 高度な電子情報開示: 重複した ID に近い                               | Available |
| 電子情報開示                              | 高度な電子情報開示: 新しい予測コーディング モジュール                   | エンジニアリング バックログについて |
| 電子情報開示                              | 高度な電子情報開示: 非保管データ ソース                                  | Available |
| 電子情報開示                              | 高度な電子情報開示: 非Office 365 インジェスト                                    | Available |
| 電子情報開示                              | 高度な電子情報開示: 予測コーディング                                       | Available |
| 電子情報開示                              | 高度な電子情報開示: 読み込みファイルを使用して処理されたエクスポート                   | Available |
| 電子情報開示                              | 高度な電子情報開示: Redactions                        | Available |
| 電子情報開示                              | 高度な電子情報開示: レビュー セット                                     | Available |
| 電子情報開示                              | 高度な電子情報開示: データの確認 (クエリ データ、スマート タグ、ダッシュボード) と注釈 (やり直し)                             | Available |
| 電子情報開示                              | 高度な電子情報開示: 検索用語レポート                        | Available |
| 電子情報開示                              | 高度な電子情報開示: 単一アイテムのエラー修復                              | Available |
| 電子情報開示                              | 高度な電子情報開示: PST エクスポートのサポート                              | Available |
| 電子情報開示                              | 高度な電子情報開示: OneDrive と SharePoint Online からのリンクされたコンテンツのサポート (最新の添付ファイル)                              | Available |
| 電子情報開示                              | 高度な電子情報開示: サポート チームの反応                      | エンジニアリング バックログについて |
| 電子情報開示                              | 高度な電子情報開示: タグ付け                              | Available |
| 電子情報開示                              | 高度な電子情報開示: テナント レポート                              | Available |
| 電子情報開示                              | 高度な電子情報開示: テーマ                              | Available |
| 電子情報開示                              | 高度な電子情報開示: 閲覧者                              | Available |
| 電子情報開示                              | 高度な電子情報開示: Yammer コンプライアンス センターで高度な電子情報開示を作成する                              | Available |
| 監査                                   | 基本的な監査                              | Available |
| 監査                                   | 高度な監査: 重要なイベントへのアクセス *(MailItemsAccessed* など)                              | Available |
| 監査                                   | 高度な監査: 管理アクティビティ API への帯域幅の増加                   | Available |
| 監査                                   | 高度な監査: Teams プライベート チャネル メッセージの法的保持                   | Available |
| 監査                                   | 高度な監査: ログ保持 (1 年)                               | Available |
| 監査                                   | 高度な監査: 監査ログの長期保持 (10 年)              | 開発中 |
| 監査                                   | 高度な監査: メール転送イベントとメール送信イベント                               | Available |
| 監査                                   | 高度な監査: Microsoft 365 セキュリティ とコンプライアンス センター                    | Available |
| 監査                                   | 高度な監査: Exchange Online および SharePoint Online の検索用語イベント                              | エンジニアリング バックログについて |
|    **コンプライアンス管理**            | Microsoft 365 セキュリティとコンプライアンス センター                              | Available |
|                                         | コンプライアンス マネージャー                              | Available |
|                                         | 2 バイト文字のサポート                              | Available |
|                                         | Microsoft Cloud App Security                              | エンジニアリング バックログについて |
|    **エコシステム**            | 高度な電子情報開示のグラフ API                              | 開発中 |
|                                         | Teams エクスポート データのグラフ API                              | エンジニアリング バックログについて |
|                                         | ファースト パーティのデータ コネクタ                              | エンジニアリング バックログについて |
|                                         | サードパーティのデータ コネクタ                              | 開発中 |




<sup>1</sup> 特定された状態は、プロジェクト計画と優先度の再評価に応じて変更される可能性があります。<br/>

**意思決定ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
