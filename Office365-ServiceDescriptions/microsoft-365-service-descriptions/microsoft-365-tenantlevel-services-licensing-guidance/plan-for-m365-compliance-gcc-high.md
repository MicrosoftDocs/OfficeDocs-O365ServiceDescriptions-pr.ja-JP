---
title: Microsoft 365 コンプライアンスの計画 - GCC High
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: このガイダンスは、Microsoft 365 Government – GCC High の使用がこれらの要件を満たすのに適している、政府の規制および要件の対象となるデータを処理する米国連邦政府機関または他のエンティティで Office 365 の展開を推進している IT プロ向けです。
ms.openlocfilehash: 357cf30350ff2a3b21d7d9326e91c2c01d119b21
ms.sourcegitcommit: f7874215059c1e5a9d383da0539f87b6f85a57e6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2021
ms.locfileid: "52001913"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>コンプライアンスの計画Microsoft 365 – GCC高

このガイダンスは、Microsoft 365 Government – GCC High の使用がこれらの要件を満たすのに適している、政府の規制および要件の対象となるデータを処理する米国連邦政府機関または他のエンティティで Office 365 の展開を推進している IT プロ向けです。

> [!NOTE]
>組織が既に Microsoft 365 Government – GCC High eligibility requirements を満たし、プログラムに適用され、プログラムに受け入れ済みである場合は、手順 1 と 2 をスキップして、手順 3 に直接進みます。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>手順 1. 組織が政府機関を必要とMicrosoft 365 - GCC要件を満たしていることを確認する

政府機関 - Microsoft 365高GCCは、クラウド サービスに関する米国政府機関の要件に準拠しています。 組織は、Office 365 の機能を楽しむだけでなく、Microsoft 365 - GCC High に固有のGCC利用できます。

- 組織の顧客コンテンツは、商用サービスの顧客コンテンツと Microsoft から論理的にOffice 365分離されます。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365Government – GCC High は、米国の公的機関のお客様に必要な認定および認定に準拠しています。

米国政府機関のお客様向け Microsoft 365 – GCCハイ オファリングの詳細については、Office 365 Government要件[](https://products.office.com/government/compare-office-365-government-plans)を含む)をご覧ください。

米国[Office 365サービス](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)の説明では、米国内のコンプライアンス要件を満たしていることを中心にプラットフォームの利点について説明します。

> [!TIP]
> サービスの説明の情報テーブルを Excel ブックに転送し、2 つの列を追加できます。組織 **Y/N** に関連し、組織の **Y/N** のニーズを満たします。 次に、この一覧を同僚と確認して、このサービスが組織のニーズを満たしているのを確認できます。

**決定点**:<br/>
- *組織に適Microsoft 365政府 – GCC-Highを決定します。*
- *組織が適格性要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365Government - GCC High は米国でのみ使用できます。 米国以外の政府機関のお客様は、複数のプランから[Office 365 Governmentできます](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>手順 2. 政府機関に申請Microsoft 365 – GCC-High

このサービスが組織に正しいと決定した後、このサービスに適用 [するプロセスを開始します](https://products.office.com/government/eligibility-validation)。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>手順 3. 政府機関Microsoft 365 – 既定GCC-Highのセキュリティ設定について

既定のセキュリティ設定を変更する前に、管理者とセキュリティ設定を慎重に確認し、コンプライアンスへの影響を考慮してから、既定のセキュリティ設定を変更することをお勧めします。

**決定ポイント**: 既定の Microsoft 365 Government - GCC-High セキュリティ設定を変更するかどうかを決定し、変更の影響を最初に理解 *します。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>手順 4. 現在使用できない機能または無効になっている機能を、Microsoft 365 - GCC-High<sup>1 で理解する</sup>

政府機関向けクラウドのお客様の要件を満たすために、政府機関と企業Microsoft 365プランGCC-High違いがあります。 使用可能な機能については、次の表を参照してください。 この[ロードマップで](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)公開されている最新のコンプライアンス製品更新プログラムについては、Microsoft 365してください。<br><br>

| 分野 | 機能 | GCC高い状態 |
|------|---------|-----------------|
| **情報保護** | 統合ラベル付けクライアントとスキャナー | Available |
| | 完全なデータ一致 | Available |
| 感度ラベル付け | オンライン、オンライン、およびExchange OnlineのSharePointの自動分類とOneDrive | Available |
| 感度ラベル付け | Web、Android、iOS、Office、Mac の Office アプリ (Word、Excel、PowerPoint、Outlook) の自動分類と Windowsラベル付け | Available |
| 感度ラベル付け | クライアントの自動分類とラベル付Office (Mobile) | エンジニアリング バックログについて |
| 感度ラベル付け | グループ、グループ、およびサイトTeams Microsoft 365の自動分類とSharePoint付け | Available |
| 分析 | データ分類分析: 概要とコンテンツ エクスプローラー | Available |
| 分析 | 分析: サービス側での自動ラベル付けによる機械学習分類子 | エンジニアリング バックログについて |
| 分析 | 分析: アプリ/クライアント側での自動ラベル付Office機械学習分類子 | ロール アウト |
| 暗号化 | 基本Office 365 Message Encryption (E3) | Available |
| 暗号化 | Advanced Office 365 Message Encryption (E5) | Available |
| 暗号化 | Office 365 の顧客キー | Available |
| 暗号化 | 顧客キー: データ保存時の暗号化 (Microsoft 365 | ロール アウト |
| 暗号化 | 顧客が管理するキー プロビジョニングのライフ サイクル用に独自のキー (BYOK) を持参する | Available |
| 暗号化 | 二重キー暗号化 | Available |
| 暗号化 | Exchange Onlineキーを使用したサービス暗号化の管理 | Available |
| データ損失防止 | ファイルと電子メールのデータ損失防止 (DLP) | Available |
| データ損失防止 | チャットとチャネルTeamsの DLP | Available |
| データ損失防止 | DLP エンドポイント | 開発中 |
| データ損失防止 | アラート ダッシュボード | 開発中 |
| データ損失防止 | 概要ページ | 開発中 |
| **情報ガバナンス** | 保持ポリシーとラベル付けポリシーのアダプティブ スコープ | エンジニアリング バックログについて |
| | 情報ガバナンス: 電子メール アーカイブ | Available |
| | 情報ガバナンス: SharePoint/OneDrive for Business、ドキュメント セットの既定の保持ラベル。Exchange受信トレイ。および Office 365 グループ | Available |
| | 情報ガバナンス: PST のインポート | Available |
| | 情報ガバナンス: 手動の非レコード保持ラベル | Available |
| | 情報ガバナンス: 保持ロック | Available |
| | 情報ガバナンス: 組織全体に対する保持ポリシー。特定の場所またはユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に実行されます。イベントに基づく | Available |
| | 情報ガバナンス: ユーザーの保持ポリシー Teams | ロール アウト |
| | 情報ガバナンス: 会議の記録に関するTeamsポリシー | 開発中 |
| | 情報ガバナンス: プライベート チャネルTeams保持ポリシー | エンジニアリング バックログについて |
| | 情報ガバナンス: 共有チャネルTeams保持ポリシー | エンジニアリング バックログについて |
| | 情報ガバナンス: トレーニング可能な分類子を含む保持ポリシー | 開発中 |
| | 情報ガバナンス: ユーザーの保持ポリシー Yammer | エンジニアリング バックログについて |
| レコード管理 | レコード ラベルを削除する機能 | 開発中 |
| レコード管理 | レコード ラベルを手動で適用する | Available |
| レコード管理 | ライブラリ、フォルダー、ドキュメント セットSharePoint、OneDrive for Businessの既定のレコード ラベルを適用します。グループOffice 365グループ | Available |
| レコード管理 | 特定の条件 (キーワードや機密情報など) に基づいてレコード ポリシーを自動的に適用する。イベントに基づく | Available |
| レコード管理 | トレーニング可能な分類子を使用してレコード ポリシーを自動的に適用する | 開発中 |
| レコード管理 | 処理確認 | Available |
| レコード管理 | ファイル計画マネージャー | Available |
| レコード管理 | 複数ステージの廃棄レビュー | エンジニアリング バックログについて |
| レコード管理 | 廃棄の証明 | Available |
| レコード管理 | Power Automate Flow期間の終わりに表示される | エンジニアリング バックログについて |
| レコード管理 | クラウド添付ファイルの保存と自動ラベル付け | エンジニアリング バックログについて |
| レコード管理 | レコードのバージョン管理 | Available |
| レコード管理 | 規制レコード | Available |
| レコード管理 | Syntex SharePointを使用してレコード ラベルを適用する | エンジニアリング バックログについて |
| **インサイダー リスクの管理** | 顧客ロックボックス | Available |
| 通信コンプライアンス | 電子メールの署名または免責事項を無視する機能 | 開発中 |
| 通信コンプライアンス | 通信コンプライアンス ポリシーの保持期間を設定する機能 | 開発中 |
| 通信コンプライアンス | アクセスアラート。通知テンプレート。通信ポリシー ダッシュボード | Available |
| 通信コンプライアンス | プレTeamsメールボックスを使用してユーザーのチャット データを分析する | Available |
| 通信コンプライアンス | 利益相反テンプレート | Available |
| 通信コンプライアンス | 顧客ポリシーの作成、3 つの事前構成済み | Available |
| 通信コンプライアンス | 成人向けコンテンツを検出する | エンジニアリング バックログについて |
| 通信コンプライアンス | 時間の間に繰り返し行動規範違反を検出する | Available |
| 通信コンプライアンス | エスカレートして調査を行Advanced eDiscovery | Available |
| 通信コンプライアンス | Insider リスク管理のハンドオフ | エンジニアリング バックログについて |
| 通信コンプライアンス | 光学式文字認識を活用してメッセージを抽出および評価する | 開発中 |
| 通信コンプライアンス | 非常に小規模な企業向け新しい簡略化されたビュー | 開発中 |
| 通信コンプライアンス | ポリシーの正常性チェックとポリシーを一時停止する機能 | エンジニアリング バックログについて |
| 通信コンプライアンス | Power Automate の統合 | エンジニアリング バックログについて |
| 通信コンプライアンス | 脅威、ターゲットを絞った嫌がらせ、冒とく分類子の 7 つの言語をサポート | エンジニアリング バックログについて |
| 通信コンプライアンス | より詳細なアクセス許可のサポート | Available |
| 通信コンプライアンス | メッセージのTeams、Exchange、および削除機能Teamsサポート | Available |
| 通信コンプライアンス | Microsoft Teams の統合 | エンジニアリング バックログについて |
| 通信コンプライアンス | Teams会話コンテキスト | エンジニアリング バックログについて |
| 通信コンプライアンス | 調査中にコンテンツを翻訳する | エンジニアリング バックログについて |
| 顧客ロックボックス | 顧客ロックボックス | Available |
| 情報バリア | 情報バリア | 開発中 |
| インサイダー リスク管理 | ケースダッシュボード | Available |
| インサイダー リスク管理 | ユーザーを退出してデータを盗む | Available |
| インサイダー リスク管理 | ビルド 1809 以上Windows 10アクティビティのデバイス インジケーター | エンジニアリング バックログについて |
| インサイダー リスク管理 | エスカレートして調査を行Advanced eDiscovery | Available |
| インサイダー リスク管理 | アラートのエクスポート | エンジニアリング バックログについて |
| インサイダー リスク管理 | 一般的なデータ リーク | Available |
| インサイダー リスク管理 | セキュリティ ポリシー違反のインジケーター | エンジニアリング バックログについて |
| インサイダー リスク管理 | Microsoft Defender for Endpoint アラートのインジケーター | エンジニアリング バックログについて |
| インサイダー リスク管理 | Insider リスク管理 アクティビティ エクスプローラー | 開発中 |
| インサイダー リスク管理 | Insider リスク管理コンテンツ エクスプローラー | 開発中 |
| インサイダー リスク管理 | インサイダーリスク管理アラートの調査 | Available |
| インサイダー リスク管理 | 通知テンプレート | Available |
| インサイダー リスク管理 | Office、Teams、SharePointメッセージのインジケーター | Available |
| インサイダー リスク管理 | 優先ユーザーによるデータ リークのポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理 | 不満を持つユーザーによるデータ リークのポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理 | 一般的なセキュリティ ポリシー違反のポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理 | 優先ユーザーによるセキュリティ ポリシー違反、ユーザーの退出、不満を持つユーザーのポリシー テンプレート | エンジニアリング バックログについて |
| インサイダー リスク管理 | ポリシーのカスタマイズ | エンジニアリング バックログについて |
| インサイダー リスク管理 | 優先度の高いユーザー グループ | エンジニアリング バックログについて |
| インサイダー リスク管理 | Power Automate の統合 | 開発中 |
| インサイダー リスク管理 | Microsoft Teams の統合 | エンジニアリング バックログについて |
| 特権アクセス管理 | 特権アクセス管理 | エンジニアリング バックログについて |
| **応答の &amp; 検出** | コア電子情報開示: 監査 | Available |
| 電子情報開示 | コア電子情報開示: ケース管理 | Available |
| 電子情報開示 | コア電子情報開示: エクスポート | Available |
| 電子情報開示 | コア電子情報開示: インプレイス保持 | Available |
| 電子情報開示 | コア電子情報開示: ネイティブ エクスポート | Available |
| 電子情報開示 | コア電子情報開示: RMS 復号化 | Available |
| 電子情報開示 | コア電子情報開示: 検索 | Available |
| 電子情報開示 | Advanced eDiscovery: 高度な処理 | Available |
| 電子情報開示 | Advanced eDiscovery: 保管担当者からワークロードへのマッピング | Available |
| 電子情報開示 | Advanced eDiscovery: カストディアン通信 | Available |
| 電子情報開示 | Advanced eDiscovery: ダッシュボード | Available |
| 電子情報開示 | Advanced eDiscovery: 中国語、日本語、韓国語の 2 バイトサポート | Available |
| 電子情報開示 | Advanced eDiscovery: メール スレッド | Available |
| 電子情報開示 | Advanced eDiscovery: エクスポート (ダウンロード、エクスポート、別のレビュー セットに追加) | Available |
| 電子情報開示 | Advanced eDiscovery: フィルター処理 | Available |
| 電子情報開示 | Advanced eDiscovery: ホールドの最適化 | 開発中 |
| 電子情報開示 | Advanced eDiscovery: プライベート チャネル メッセージのTeams保留 | Available |
| 電子情報開示 | Advanced eDiscovery: Microsoft コンプライアンス センターでは、ごみ箱内のアイテムを検索およびエクスポートするサポートSharePoint展開OneDrive for Businessしました | 開発中 |
| 電子情報開示 | Advanced eDiscovery: 重複する ID の近く | Available |
| 電子情報開示 | Advanced eDiscovery: 新しい予測コーディング モジュール | エンジニアリング バックログについて |
| 電子情報開示 | Advanced eDiscovery: 非保管データ ソース | Available |
| 電子情報開示 | Advanced eDiscovery: 非Office 365取り込み | Available |
| 電子情報開示 | Advanced eDiscovery: 予測コーディング | Available |
| 電子情報開示 | Advanced eDiscovery: 読み込みファイルを使用して処理されたエクスポート | Available |
| 電子情報開示 | Advanced eDiscovery: Redactions | Available |
| 電子情報開示 | Advanced eDiscovery: レビュー セット | Available |
| 電子情報開示 | Advanced eDiscovery: データの確認 (クエリ データ、スマート タグ、ダッシュボード) と注釈 (redact) | Available |
| 電子情報開示 | Advanced eDiscovery: 検索用語レポート | Available |
| 電子情報開示 | Advanced eDiscovery: 単一アイテムのエラー修復 | Available |
| 電子情報開示 | Advanced eDiscovery: PST エクスポートのサポート | Available |
| 電子情報開示 | Advanced eDiscovery: オンラインからリンクされたコンテンツOneDriveサポートSharePoint (モダン添付ファイル) | Available |
| 電子情報開示 | Advanced eDiscovery: サポート Teams反応 | エンジニアリング バックログについて |
| 電子情報開示 | Advanced eDiscovery: タグ付け | Available |
| 電子情報開示 | Advanced eDiscovery: テナント レポート | Available |
| 電子情報開示 | Advanced eDiscovery: テーマ | Available |
| 電子情報開示 | Advanced eDiscovery: 閲覧者 | Available |
| 電子情報開示 | Advanced eDiscovery: Yammer Advanced eDiscovery コンプライアンス センターの設定 | Available |
| 監査 | 基本的な監査 | Available |
| 監査 | 高度な監査: 重要なイベントへのアクセス *(MailItemsAccessed* など) | Available |
| 監査 | 高度な監査: 管理アクティビティ API への帯域幅の増加 | Available |
| 監査 | 高度な監査: プライベート チャネル メッセージTeamsホールド | Available |
| 監査 | 高度な監査: ログ保持 (1 年) | Available |
| 監査 | 高度な監査: 監査ログの長期保持 (10 年) | 開発中 |
| 監査 | 高度な監査: メール転送イベントとメール送信イベント | Available |
| 監査 | 高度な監査: Microsoft 365コンプライアンス センターの可用性 | Available |
| 監査 | 高度な監査: オンラインとオンラインのExchange Online検索SharePoint検索 | エンジニアリング バックログについて |
| **コンプライアンス管理** | Microsoft 365セキュリティとコンプライアンス センター | Available |
| | コンプライアンス マネージャー | Available |
| | 2 バイト文字のサポート | Available |
| | Microsoft Cloud App Security | Available |
| **エコシステム** | Graphアプリケーションの API Advanced eDiscovery | 開発中 |
| | GraphデータをエクスポートTeams API | エンジニアリング バックログについて |
| | ファースト パーティのデータ コネクタ | エンジニアリング バックログについて |
| | サードパーティのデータ コネクタ | 開発中 |

<sup>1</sup> 特定された状態は、プロジェクト計画と優先度の再評価に応じて変更される可能性があります。<br/>

**意思決定ポイント**: *コンプライアンス機能が組織のニーズを満たすかどうかを決定します。*