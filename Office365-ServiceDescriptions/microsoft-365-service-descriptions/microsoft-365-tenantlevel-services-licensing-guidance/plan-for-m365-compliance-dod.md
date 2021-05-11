---
title: Microsoft 365 コンプライアンスの計画 - DoD 展開
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、Microsoft 365 Government – DoD の使用がこれらの要件を満たすのに適した、政府の規制および要件の対象となるデータを処理する米国連邦政府機関または他のエンティティで Office 365 の展開を推進している IT プロ向けです。
ms.openlocfilehash: 74907afc24dd468111e3f530dc316346784b2996
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652621"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 コンプライアンスの計画 - DoD 展開

このガイダンスは、Microsoft 365 Government – DoD の使用がこれらの要件を満たすのに適した、政府の規制および要件の対象となるデータを処理する米国連邦政府機関または他のエンティティで Office 365 の展開を推進している IT プロ向けです。

> [!NOTE]
> 組織が Microsoft 365 Government – DoD の適格性要件を既に満たし、プログラムに適用され、受け入れ済みである場合は、手順 1 と 2 をスキップして、手順 3 に直接進みます。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>手順 1. 組織が政府機関 - DoD Microsoft 365要件を満たす必要があるかどうかを判断する

政府機関Microsoft 365 DoD 環境は、クラウド サービスに関する米国政府機関の要件に準拠しています。

組織は、Office 365 の機能を楽しむだけでなく、政府機関 – DoD に固有のMicrosoft 365を利用できます。

- 組織の顧客コンテンツは、商用サービスの顧客コンテンツと Microsoft から論理的にOffice 365分離されます。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365Government - DoD は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

米国政府機関のお客様向け Microsoft 365 DoD サービスの詳細については、Office 365 Government要件を含[](https://products.office.com/government/compare-office-365-government-plans)むプランをご覧ください。

米国[Office 365サービス](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)の説明では、米国内のコンプライアンス要件を満たしていることを中心にプラットフォームの利点について説明します。

> [!TIP]
> サービスの説明の情報テーブルを Excel ブックに転送し、2 つの列を追加できます。組織 **Y/N** に関連し、組織の **Y/N** のニーズを満たします。 次に、この一覧を同僚と確認して、このサービスが組織のニーズを満たしているのを確認できます。

**決定点**:<br/>
- *組織にMicrosoft 365政府 - DoD が適切かどうかを決定します。*
- *組織が適格性要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365Government - DoD は米国でのみ使用できます。 米国以外の政府機関のお客様は、複数のプランから[Office 365 Governmentできます](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>手順 2. 政府機関にMicrosoft 365 - DoD を申請する

このサービスが組織に正しいと決定した後、このサービスに適用 [するプロセスを開始します](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>手順 3. 政府機関Microsoft 365 DoD の既定のセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者とセキュリティ設定を慎重に確認し、コンプライアンスへの影響を考慮してから、既定のセキュリティ設定を変更することをお勧めします。

**決定ポイント**: Microsoft 365 既定の政府機関 - DoD セキュリティ設定を変更するかどうかを決定し、変更の影響を最初 *に理解するために解決します。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>手順 4. 政府機関 – DoD<sup>1</sup>で、現在使用できない機能または既定で無効になっている機能Microsoft 365理解する

政府機関のクラウド顧客の要件を満たすために、政府機関 - DoD とエンタープライズ プランのMicrosoft 365違いがあります。 使用可能な機能については、次の表を参照してください。 ロードマップ[で](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)公開されている最新のコンプライアンス製品更新プログラムについては、Microsoft 365してください。<br><br>

| 分野                                    | 機能                                         | GCC状態             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **情報保護**              | 統合ラベル付けクライアントとスキャナー         | Available              |
|                                         | 完全なデータ一致          | Available               |
|                                         | オンライン、オンライン、およびExchange OnlineのSharePointの自動分類とOneDrive                      | ロール アウト              |
|                                         | Office アプリ (Word、Excel、PowerPoint、Outlook) のプラットフォーム (Web、Android、iOS、Windows、および Mac) の自動分類とラベル付け            | 開発中 |
|                                         | モバイルの自動分類とラベル付け                                       | エンジニアリング バックログについて              |
|                                         | ユーザーの自動分類とラベル付Teams                            | エンジニアリング バックログについて |
|                                         | データ分類: 概要とコンテンツ エクスプローラー                            | 開発中 |
|                                         | 分析: サービス側での自動ラベル付けによる機械学習分類子                           | エンジニアリング バックログについて  |
|                                         | 分析: アプリ/クライアント側での自動ラベル付Office機械学習分類子                           | エンジニアリング バックログについて  |
|                                         | 基本Office 365 Message Encryption (E3)                            | Available              |
|                                         | Advanced Office 365 Message Encryption (E5)  | Available              |
|                                         | Office 365 の顧客キー    | Available |
|                                         | 顧客が管理するキー プロビジョニングのライフ サイクル用に独自のキー (BYOK) を持参する                            | Available |
|                                         | 高度に規制されたシナリオ (プレビュー) の Azure Information Protection と Active Directory (AD) Rights Management にまたがる独自のキー (HYOK) を保持する                         | Available |
|                                         | 二重キー暗号化                           | ロール アウト |
|                                         | ファイルと電子メールのデータ損失防止 (DLP)         | Available |
|                                         | チャットとチャネルTeamsの DLP         | エンジニアリング バックログについて |
|                                         | DLP の完全なデータ一致         | エンジニアリング バックログについて |
|                                         | DLP エンドポイント | エンジニアリング バックログについて |
| **情報ガバナンス** | 情報ガバナンス: 電子メール アーカイブ                                       | Available              |
|                                         | 情報ガバナンス: 保持ロック          | Available              |
|                                         | 情報ガバナンス: PST のインポート                      | Available              |
|                                         | 情報ガバナンス: 手動の非レコード保持ラベル            | Available |
|                                         | 情報ガバナンス: SharePoint/OneDrive for Business、ドキュメント セットの既定の保持ラベル。Exchange受信トレイ。および Office 365 グループ | Available              |
|                                         | 情報ガバナンス: 組織全体に対する保持ポリシー。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に設定されます。                                       | Available              |
|                                         | 情報ガバナンス: トレーニング可能な分類子を含む保持ポリシー                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: 会議の記録に関するTeamsポリシー                            | エンジニアリング バックログについて |
|                                         | 情報ガバナンス: ユーザーとユーザーのYammer保持Teams                           | エンジニアリング バックログについて              |
|                                         | レコード管理: レコード ラベルの手動分類                              | Available              |
|                                         | レコード管理: ライブラリ、フォルダー、SharePoint、OneDrive for Businessセットの既定のレコード ラベル。グループOffice 365グループ                            | Available              |
|                                         | レコード管理: 特定の条件 (キーワードや機密情報など) に基づく自動レコード ポリシー。イベントに基づく  | Available              |
|                                         | レコード管理: 廃棄レビュー    | Available |
|                                         | レコード管理: ファイル計画マネージャー                            | Available |
|                                         | レコード管理: 廃棄の証明                         | Available |
|                                         | レコード管理: 規制レコード | エンジニアリング バックログについて |
|                                         | レコード管理: 複数ステージの廃棄レビュー | エンジニアリング バックログについて |
|                                         | レコード管理: Syntex 分類SharePoint使用してレコード ラベルを適用する         | エンジニアリング バックログについて |
| **インサイダー リスクの管理**             | 顧客ロックボックス                                | Available            |
|                                         | Insider リスク管理: Office、Teams、SharePointメッセージのインジケーター                         | エンジニアリング バックログについて |
|                                         | Insider リスク管理: ユーザーを退出してデータを盗む                        | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 一般的なデータ 漏洩                                | エンジニアリング バックログについて              |
|                                         | Insider リスク管理: インサイダー リスク管理アラートを調査する                                   | エンジニアリング バックログについて              |
|                                         | Insider リスク管理: ケース ダッシュボード、コンテンツ エクスプローラー、通知テンプレート | エンジニアリング バックログについて |
|                                         | Insider リスク管理: リスクの調査をエスカレートAdvanced eDiscovery |エンジニアリング バックログについて|
|                                         | Insider リスク管理: ビルド 1809 以上Windows 10アクティビティのデバイス インジケーター |エンジニアリング バックログについて|
|                                         | Insider リスク管理: セキュリティ ポリシー違反のインジケーター (プレビュー) |エンジニアリング バックログについて|
|                                         | Insider リスク管理: Microsoft Defender for Endpoint アラートのインジケーター (プレビュー) |エンジニアリング バックログについて|
|                                         | Insider リスク管理: 優先ユーザーによるデータ 漏洩のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 不満を持つユーザーによるデータ 漏洩のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 一般的なセキュリティ ポリシー違反のポリシー テンプレート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 優先ユーザーによるセキュリティ ポリシー違反のポリシー テンプレート、ユーザーの退出、不満を持つユーザー (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: ポリシーのカスタマイズ (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: エクスポートアラート (プレビュー) | エンジニアリング バックログについて |
|                                         | Insider リスク管理: 優先度の高いユーザー グループ (プレビュー) | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 顧客ポリシーの作成、3 つの事前構成済み  | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): メッセージのTeams、Exchange、および削除Teamsします。 | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス (監督ポリシーを含む): アクセス通知。通知テンプレート。通信ポリシー ダッシュボード | エンジニアリング バックログについて  |
|                                         | 通信コンプライアンス (監督ポリシーを含む): 監査の調査をエスカレートAdvanced eDiscovery | エンジニアリング バックログについて |
|                                         | コミュニケーション コンプライアンス (監督ポリシーを含む): 成人向けコンテンツを検出する | エンジニアリング バックログについて |
|                                         | 通信コンプライアンス(監督ポリシーを含む): 繰り返しの行動規範違反を検出します。 | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): より詳細なアクセス許可のサポート | ロール アウト |
|                                         | 通信コンプライアンス (監督ポリシーを含む): プレTeamsユーザーのチャット データを分析する | ロール アウト |
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
|                                         | Advanced eDiscovery: 高度な処理                                 | ロール アウト |
|                                         | Advanced eDiscovery: 保管担当者からワークロードへのマッピング                                 | ロール アウト |
|                                         | Advanced eDiscovery: カストディアン通信                                 | ロール アウト |
|                                         | Advanced eDiscovery: ダッシュボード                   | ロール アウト |
|                                         | Advanced eDiscovery: メール スレッド                                          | ロール アウト |
|                                         | Advanced eDiscovery: エクスポート (ダウンロード、エクスポート、別のレビュー セットに追加)                               | ロール アウト |
|                                         | Advanced eDiscovery: フィルター処理                 | ロール アウト |
|                                         | Advanced eDiscovery: プライベート チャネル メッセージのTeams保留                                         | ロール アウト |
|                                         | Advanced eDiscovery: 重複する ID の近く                                         | ロール アウト |
|                                         | Advanced eDiscovery: 非Office 365取り込み                                      | ロール アウト |
|                                         | Advanced eDiscovery: 予測コーディング                                       | ロール アウト |
|                                         | Advanced eDiscovery: 読み込みファイルを使用して処理されたエクスポート                   | ロール アウト |
|                                         | Advanced eDiscovery: Redactions                        | ロール アウト |
|                                         | Advanced eDiscovery: レビュー セット                                     | ロール アウト |
|                                         | Advanced eDiscovery: レビューと注釈                             | ロール アウト |
|                                         | Advanced eDiscovery: 検索用語レポート                        | ロール アウト |
|                                         | Advanced eDiscovery: オンラインからリンクされたコンテンツOneDriveサポートSharePoint (モダン添付ファイル)                        | ロール アウト |
|                                         | Advanced eDiscovery: タグ付け                              | ロール アウト |
|                                         | Advanced eDiscovery: Teamsのサポート                              | ロール アウト |
|                                         | Advanced eDiscovery: テナント レポート                              | ロール アウト |
|                                         | Advanced eDiscovery: テーマ                              | ロール アウト |
|                                         | Advanced eDiscovery: 閲覧者                              | ロール アウト |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery コンプライアンス センターの設定                              | ロール アウト |
|                                         | Advanced eDiscovery: CJK/Double byte Advanced eDiscovery のサポート                              | 開発中 |
|                                         | 基本的な監査                              | Available |
|                                         | 高度な監査: 重要なイベントへのアクセス (mailitemsaccessed など)                              | ロール アウト |
|                                         | 高度な監査: 管理アクティビティ API への帯域幅の増加                              | ロール アウト |
|                                         | 高度な監査: ログ保持 (1 年)                              | ロール アウト |
|                                         | 高度な監査: セキュリティとコンプライアンス センターの可用性                              | Available |
|                                         | 高度な監査: 監査ログの長期保持 (10 年)                              | エンジニアリング バックログについて |
|                                         | 高度な監査: メール転送イベントとメール送信イベント                              | エンジニアリング バックログについて |
|                                         | 高度な監査: 処理された監査の分析情報                              | エンジニアリング バックログについて |
|                                         | 高度な監査: オンラインとオンラインのExchange Online検索SharePoint検索                              | エンジニアリング バックログについて |
|    **コンプライアンス管理**            | Microsoft 365セキュリティとコンプライアンス センター                              | Available |
|                                         | Microsoft Cloud App Security                              | エンジニアリング バックログについて |
|                                         | コンプライアンス マネージャー                              | エンジニアリング バックログについて |
|                                         | 2 バイト文字のサポート                              | エンジニアリング バックログについて |
|    **エコシステム**            | Graphアプリケーションの API Advanced eDiscovery                              | 開発中 |
|                                         | ファースト パーティのデータ コネクタ                              | エンジニアリング バックログについて |
|                                         | サードパーティのデータ コネクタ                              | エンジニアリング バックログについて |
|                                         | GraphデータをエクスポートTeams API                              | エンジニアリング バックログについて |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度の再評価に応じて変更される可能性があります。<br/>

**意思決定ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*