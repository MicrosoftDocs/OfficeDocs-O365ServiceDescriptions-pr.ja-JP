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
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546004"
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

| 分野 | 機能 | DoD の状態 |
|------|---------|------------|
| **情報保護** | 統合ラベル付けクライアントとスキャナー | Available |
| | 完全なデータ一致 | Available |
| | オンライン、オンライン、およびExchange OnlineのSharePointの自動分類とOneDrive for Business | ロール アウト |
| | Office アプリ (Word、Excel、PowerPoint、Outlook) のプラットフォーム (Web、Windows、および Mac) の自動分類とラベル付け | Available |
| | クライアントの自動分類とラベル付Office - Mobile | エンジニアリング バックログについて |
| | グループ、グループ、およびサイトTeams Microsoft 365の自動分類とSharePoint付け | Available |
| | 必須のラベル付け | Available |
| | アプリでの手動のOfficeラベル付け (iOS、Android、Windows) | Available |
| | メッセージの暗号化専用保護用のOutlook構成 | ロール アウト |
| **分析** | データ分類: 概要とコンテンツ エクスプローラー | ロール アウト |
| | 分析: サービス側での自動ラベル付けによる機械学習分類子 | 開発中 |
| | 分析: アプリ/クライアント側での自動ラベル付Office機械学習分類子 | ロール アウト |
| **暗号化** | 基本Office 365 Message Encryption (E3) | Available |
| | Advanced Office 365 Message Encryption (E5) | Available |
| | 顧客が管理するキー プロビジョニングのライフ サイクル用に独自のキー (BYOK) を持参する | Available |
| | Office 365 の顧客キー | Available |
| | 二重キー暗号化 | Available |
| **データ損失防止** | ファイルと電子メールのデータ損失防止 (DLP) | Available |
| | チャットとチャネルTeamsの DLP | Available |
| | DLP: アラート ダッシュボード | ロール アウト |
| | DLP エンドポイント | 開発中 |
| | DLP On-prem | エンジニアリング バックログについて |
| | DLP の概要ページ | 開発中 |
| **情報ガバナンス** | 情報ガバナンス: 電子メール アーカイブ | Available |
| | 情報ガバナンス: 保持ロック | Available |
| | 情報ガバナンス: PST のインポート | Available |
| | 情報ガバナンス: レコード以外の保持ラベルを手動で適用する | Available |
| | 情報ガバナンス: ライブラリ、フォルダー、およびドキュメント セットSharePoint/OneDrive for Businessの既定の保持ラベルを適用します。Exchange受信トレイ。および Office 365 グループ | Available |
| | 情報ガバナンス: 組織全体に 1 つの既定の保持ラベルを適用します。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に設定されます。 | Available |
| | 情報ガバナンス: 受信トレイに既定のラベルをExchangeする | Available |
| | 情報ガバナンス: 複数段階の廃棄レビュー | エンジニアリング バックログについて |
| | 情報ガバナンス: トレーニング可能な分類子を含む保持ポリシー | 開発中 |
| | 情報ガバナンス: チャットの保持Teamsポリシー | ロール アウト |
| | 情報ガバナンス: 会議の記録に関するTeamsポリシー | Available |
| | 情報ガバナンス: プライベート チャネル メッセージTeams保持ポリシー | エンジニアリング バックログについて |
| | 情報ガバナンス: 保持ポリシーとラベル付けポリシーアダプティブ スコープ | 開発中 |
| | レコード管理: レコード ラベルを手動で適用する | Available |
| | レコード管理: ライブラリ、フォルダー、およびドキュメント セットSharePoint、OneDrive for Business既定のレコード ラベルを適用します。グループOffice 365グループ | Available |
| | レコード管理: 特定の条件 (キーワードや機密情報など) に基づく自動レコード ポリシー。イベントに基づく | Available |
| | レコード管理: 廃棄レビュー | Available |
| | レコード管理: ファイル計画マネージャー | Available |
| | レコード管理: 廃棄の証明 | Available |
| | レコード管理: レコードのバージョン管理 | Available |
| | レコード管理: 規制レコード | Available |
| | レコード管理: Syntex 分類SharePoint使用してレコード ラベルを適用する | エンジニアリング バックログについて |
| **インサイダー リスクの管理** | 顧客ロックボックス | Available |
| | Insider リスク管理: ケース ダッシュボード、コンテンツ エクスプローラー、および通知テンプレート | ロール アウト |
| | Insider リスク管理: リスクの調査をエスカレートAdvanced eDiscovery | ロール アウト |
| | Insider リスク管理: ユーザーを退出してデータを盗む | ロール アウト |
| | Insider リスク管理: 一般的なデータ 漏洩 | ロール アウト |
| | Insider リスク管理: インサイダー リスク管理アラートを調査する | ロール アウト |
| | Insider リスク管理: Office、Teams、SharePointメッセージのインジケーター | ロール アウト |
| | Insider リスク管理アクティビティ エクスプローラー | エンジニアリング バックログについて |
| | Insider リスク管理: ビルド 1809 以上Windows 10アクティビティのデバイス インジケーター | エンジニアリング バックログについて |
| | Insider リスク管理: Microsoft Defender for Endpoint アラートのインジケーター | エンジニアリング バックログについて |
| | Insider リスク管理: セキュリティ ポリシー違反の指標 | エンジニアリング バックログについて |
| | Insider リスク管理: 不満を持つユーザーによるデータ 漏洩のポリシー テンプレート | エンジニアリング バックログについて |
| | Insider リスク管理: 優先ユーザーによるデータ 漏洩のポリシー テンプレート | エンジニアリング バックログについて |
| | Insider リスク管理: 一般的なセキュリティ ポリシー違反のポリシー テンプレート | エンジニアリング バックログについて |
| | Insider リスク管理: 優先ユーザーによるセキュリティ ポリシー違反のポリシー テンプレート、ユーザーの退出、不満を持つユーザー (プレビュー) | エンジニアリング バックログについて |
| | Insider リスク管理: ポリシーのカスタマイズ | エンジニアリング バックログについて |
| | Insider リスク管理: エクスポートアラート | エンジニアリング バックログについて |
| | Insider リスク管理: Microsoft Teams統合 | エンジニアリング バックログについて |
| | Insider リスク管理: 優先度の高いユーザー グループ | エンジニアリング バックログについて |
| | 通信コンプライアンス: 顧客ポリシーの作成、3 つの事前構成済み | Available |
| | 通信コンプライアンス: メッセージのTeams、Exchange、削除のTeamsサポート | Available |
| | 通信コンプライアンス: アクセス通知。通知テンプレート。通信ポリシー ダッシュボード | Available |
| | コミュニケーション コンプライアンス: データの調査をエスカレートAdvanced eDiscovery | Available |
| | 通信コンプライアンス: 時間の間に繰り返し行動規範違反を検出する | Available |
| | 通信コンプライアンス: より詳細なアクセス許可のサポート | Available |
| | 通信コンプライアンス: プレTeamsメールボックスを使用してユーザーのチャット データを分析する | Available |
| | コミュニケーション コンプライアンス: 利益相反テンプレート | Available |
| | 通信コンプライアンス: 電子メールの署名または免責事項を無視する機能 | 開発中 |
| | 通信コンプライアンス: 通信コンプライアンス ポリシーの保持期間を設定する機能 | エンジニアリング バックログについて |
| | コミュニケーション コンプライアンス: 成人向けコンテンツを検出する | エンジニアリング バックログについて |
| | コミュニケーション コンプライアンス: Insider リスク管理ハンドオフ | 開発中 |
| | 通信コンプライアンス: ポリシーの正常性チェックとポリシーを一時停止する機能 | 開発中 |
| | コミュニケーションコンプライアンス: 脅威、標的型ハラスメント、および冒とく分類者に対して 7 つの言語をサポート | 開発中 |
| | コミュニケーション コンプライアンス: 調査中に正常性コンテンツを翻訳する | 開発中 |
| | 情報バリア | ロール アウト |
| | 特権アクセス管理 | エンジニアリング バックログについて |
| **応答&を検出する** | コア電子情報開示: インプレイス保持 | Available |
| | コア電子情報開示: ケース管理 | Available |
| | コア電子情報開示: 検索 | Available |
| | コア電子情報開示: エクスポート | Available |
| | コア電子情報開示: RMS 復号化 | Available |
| | コア電子情報開示: ネイティブ エクスポート | Available |
| | コア電子情報開示: 監査 | Available |
| | コア電子情報開示: コンプライアンスの境界OneDrive for Business | ロール アウト |
| | Advanced eDiscovery: 高度な処理 | Available |
| | Advanced eDiscovery: CJK/Double byte Advanced eDiscovery のサポート | Available |
| | Advanced eDiscovery: 保管担当者からワークロードへのマッピング | Available |
| | Advanced eDiscovery: カストディアン通信 | Available |
| | Advanced eDiscovery: ダッシュボード | Available |
| | Advanced eDiscovery: メール スレッド | Available |
| | Advanced eDiscovery: エクスポート (ダウンロード、エクスポート、別のレビュー セットに追加) | Available |
| | Advanced eDiscovery: フィルター処理 | Available |
| | Advanced eDiscovery: 重複する ID の近く | Available |
| | Advanced eDiscovery: 予測コーディング | Available |
| | Advanced eDiscovery: 読み込みファイルを使用して処理されたエクスポート | Available |
| | Advanced eDiscovery: Redactions | Available |
| | Advanced eDiscovery: レビュー セット | Available |
| | Advanced eDiscovery: レビューと注釈 | Available |
| | Advanced eDiscovery: 検索用語レポート | Available |
| | Advanced eDiscovery: オンラインからリンクされたコンテンツOneDriveサポートSharePoint (モダン添付ファイル) | Available |
| | Advanced eDiscovery: タグ付け | Available |
| | Advanced eDiscovery: Teamsのサポート | Available |
| | Advanced eDiscovery: テナント レポート | Available |
| | Advanced eDiscovery: テーマ | Available |
| | Advanced eDiscovery: 閲覧者 | Available |
| | Advanced eDiscovery: Yammer Advanced eDiscovery コンプライアンス センターの設定 | Available |
| | Advanced eDiscovery: ホールドの最適化 | 開発中 |
| | Advanced eDiscovery: Microsoft コンプライアンス センターでは、コアおよびサーバー内の SharePoint、OneDrive for Business、ごみ箱のアイテムの検索とエクスポートのサポートがAdvanced eDiscovery | 開発中 |
| | Advanced eDiscovery: プライベート チャネル メッセージのTeams保留 | 開発中 |
| | Advanced eDiscovery: 新しい予測コーディング モジュール | 開発中 |
| | Advanced eDiscovery: 非Office 365取り込み | エンジニアリング バックログについて |
| | Advanced eDiscovery: テナント レポート | 開発中 |
| | 基本的な監査 | Available |
| | 高度な監査: 重要なイベントへのアクセス (mailitemsaccessed など) | Available |
| | 高度な監査: 管理アクティビティ API への帯域幅の増加 | Available |
| | 高度な監査: ログ保持 (1 年) | Available |
| | 高度な監査: メール転送イベントとメール送信イベント | Available |
| | 高度な監査: セキュリティとコンプライアンス センターの可用性 | Available |
| | 高度な監査: 監査ログの長期保持 (10 年) | 開発中 |
| | 高度な監査: オンラインとオンラインのExchange Online検索SharePoint検索 | エンジニアリング バックログについて |
| **コンプライアンス管理** | Microsoft 365セキュリティとコンプライアンス センター | Available |
| | Microsoft Cloud App Security | 開発中 |
| | コンプライアンス マネージャー | Available |
| | 2 バイト文字のサポート | Available |
| **エコシステム** | ファースト パーティのデータ コネクタ: HR | Available |
| | ファースト パーティのデータ コネクタ: インスタント ブルームバーグ、ブルームバーグ メール、LinkedIn Business ページ、ICE チャット | エンジニアリング バックログについて |
| | サードパーティのデータ コネクタ | エンジニアリング バックログについて |
| | Graphアプリケーションの API Advanced eDiscovery | 開発中 |
| | GraphデータをエクスポートTeams API | エンジニアリング バックログについて |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度の再評価に応じて変更される可能性があります。<br/>

**意思決定ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*
