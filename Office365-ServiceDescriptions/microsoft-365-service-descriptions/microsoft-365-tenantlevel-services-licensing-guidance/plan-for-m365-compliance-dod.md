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
description: このガイダンスは、米国連邦政府機関や、政府の規制や要件に従うデータを処理するその他 Microsoft 365の事業体でOffice 365の展開を推進している IT 担当者向けです。
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546004"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 コンプライアンスの計画 - DoD 展開

このガイダンスは、米国連邦政府機関や、政府の規制や要件に従うデータを処理するその他 Microsoft 365の事業体でOffice 365の展開を推進している IT 担当者向けです。

> [!NOTE]
> 組織が既に Microsoft 365政府 – DoD 資格要件を満たしており、プログラムに適用され、プログラムに受け入れられた場合は、手順 1 と 2 をスキップして、手順 3 に直接進むことができます。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>手順 1. 組織が政府 - DoD Microsoft 365必要とし、適格性要件を満たしているかどうかを判断します

Microsoft 365政府 - DoD 環境は、クラウド サービスに関する米国政府の要件に準拠しています。

Office 365の機能を利用できるだけでなく、組織は、Microsoft 365政府に固有の以下の機能からメリットを得る – DoD:

- 組織の顧客コンテンツは、Microsoft の商用Office 365 サービスの顧客コンテンツから論理的に分離されます。
- 組織の顧客コンテンツは、米国内に格納されます。
- 組織の顧客コンテンツへのアクセスは、審査された Microsoft の担当者にのみ制限されます。
- Microsoft 365政府 - DoDは、米国の公共部門のお客様に必要な認定と認定に準拠しています。

米国政府の顧客向けのMicrosoft 365 - DoD サービスの詳細については、資格要件を含む[Office 365 Government プラン](https://products.office.com/government/compare-office-365-government-plans)をご覧ください。

[Office 365米国政府サービスの説明](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)は、米国内のコンプライアンス要件を満たすことを中心とするプラットフォームの利点を説明します。

> [!TIP]
> サービスの説明の情報のテーブルをExcelブックに転送し、組織の **Y/N に関連する** 列と組織 **のニーズを満たす** 2 つの列を追加する場合があります。 次に、この一覧を同僚と確認して、このサービスが組織のニーズを満たしていることを確認します。

**決定ポイント**:<br/>
- *政府 - DoD Microsoft 365組織に適しているかどうかを決定します。*
- *組織が適格性要件を満たしていることを確認します。*

> [!NOTE]
> Microsoft 365政府 - DoD は米国でのみ利用可能です。 米国政府以外の顧客は、さまざまな[Office 365 Governmentプラン](https://products.office.com/government/compare-office-365-government-plans)から選択できます。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>手順 2. 政府Microsoft 365申請 - DoD

このサービスが組織に適していると判断したら、 [このサービスに対する申請](https://products.office.com/government/eligibility-validation)のプロセスを開始します。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>手順 3. 政府Microsoft 365理解 - DoD の既定のセキュリティ設定

管理者とセキュリティ設定を変更する前に、管理者とセキュリティ設定を慎重に確認し、コンプライアンスへの影響を考慮してから、既定のセキュリティ設定を変更することをお勧めします。

**決定ポイント**:*政府 - DoD セキュリティ設定のデフォルトMicrosoft 365変更するかどうかを決定し、変更の影響を最初に理解します。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>手順 4. 政府のMicrosoft 365で、現在利用できない機能または無効になっている機能Microsoft 365<sup>理解する</sup>

政府のクラウド顧客の要件を満たすために、政府 - DoDと企業計画Microsoft 365の間にいくつかの違いがあります。 使用可能な機能については、次の表を参照してください。 Microsoft 365ロードマップに掲載されている最新のコンプライアンス対応製品の更新については[、こちら](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)を参照してください。<br><br>

| 分野 | 機能 | DoD ステータス |
|------|---------|------------|
| **情報保護** | 統一されたラベリング クライアントとスキャナー | Available |
| | 完全なデータ一致 | Available |
| | Exchange Online、オンライン、OneDrive for BusinessのSharePointの自動分類とラベリング | ロール アウト |
| | プラットフォーム (Web、Windows、Mac) 間でOfficeアプリ (Word、Excel、PowerPoint、Outlook) の自動分類とラベリング | Available |
| | Officeクライアントの自動分類とラベリング - モバイル | エンジニアリングバックログについて |
| | Teams、Microsoft 365グループ、SharePointサイトの自動分類とラベル付け | Available |
| | 必須のラベリング | Available |
| | Officeアプリでの手動感度ラベル付け(iOS、アンドロイド、Windows) | Available |
| | Outlook メッセージに対する暗号化のみの保護のための機密ラベル構成 | ロール アウト |
| **分析** | データ分類: 概要とコンテンツ エクスプローラー | ロール アウト |
| | 分析: サービス側で自動ラベリングを使用した機械学習分類子 | 開発中 |
| | 分析: Officeアプリ/クライアント側で自動ラベリングを使用した機械学習分類子 | ロール アウト |
| **暗号化** | 基本Office 365 Message Encryption (E3) | Available |
| | 高度なOffice 365 Message Encryption (E5) | Available |
| | 顧客管理のキー プロビジョニング ライフサイクルに独自のキー (BYOK) を用意する | Available |
| | Office 365 の顧客キー | Available |
| | 二重キー暗号化 | Available |
| **データ損失防止** | ファイルおよび電子メールのデータ損失防止 (DLP) | Available |
| | チャットとチャネルの会話Teams DLP | Available |
| | DLP: アラート ダッシュボード | ロール アウト |
| | DLP エンドポイント | 開発中 |
| | DLP オンプレム | エンジニアリングバックログについて |
| | DLP の概要ページ | 開発中 |
| **情報ガバナンス** | 情報ガバナンス: メール・アーカイブ | Available |
| | 情報ガバナンス: 保存ロック | Available |
| | 情報ガバナンス: PST のインポート | Available |
| | 情報ガバナンス: 非レコード保持ラベルを手動で適用する | Available |
| | 情報ガバナンス: SharePoint/OneDrive for Businessライブラリ、フォルダ、およびドキュメント セットに既定の保持ラベルを適用します。受信トレイExchange。Office 365 グループ | Available |
| | 情報ガバナンス: 組織全体に単一のデフォルト保持ラベルを適用します。特定の場所やユーザー。特定の条件 (キーワードや機密情報など) に基づいて自動的に実行されます。 | Available |
| | 情報ガバナンス: Exchange受信トレイにデフォルトのラベルを適用する | Available |
| | 情報ガバナンス: 多段階の廃棄レビュー | エンジニアリングバックログについて |
| | 情報ガバナンス: トレーニング可能分類子を使用した保存ポリシー | 開発中 |
| | 情報ガバナンス: Teamsチャットの保持ポリシー | ロール アウト |
| | 情報ガバナンス: 会議の記録Teams保存ポリシー | Available |
| | 情報ガバナンス: プライベート チャネル メッセージTeamsの保存ポリシー | エンジニアリングバックログについて |
| | 情報ガバナンス: 保存ポリシーとラベル付けポリシーの適応範囲 | 開発中 |
| | レコード管理: レコード ラベルを手動で適用する | Available |
| | レコード管理: SharePoint、OneDrive for Businessライブラリ、フォルダ、およびドキュメント セットに既定のレコード ラベルを適用します。Office 365 グループ | Available |
| | レコード管理: 特定の条件 (キーワードや機密情報など) に基づく自動レコード ポリシー。イベントに基づいて | Available |
| | レコード管理: 廃棄の確認 | Available |
| | レコード管理: ファイル計画マネージャー | Available |
| | 記録管理:処分の証明 | Available |
| | レコード管理: レコードのバージョン管理 | Available |
| | 記録管理:規制記録 | Available |
| | レコード管理: SharePoint Syntex 分類を使用してレコード ラベルを適用する | エンジニアリングバックログについて |
| **インサイダー リスクの管理** | 顧客ロックボックス | Available |
| | インサイダーリスク管理: ケースダッシュボード、コンテンツエクスプローラ、および通知テンプレート | ロール アウト |
| | インサイダーリスク管理:Advanced eDiscoveryの調査に向けてエスカレート | ロール アウト |
| | インサイダーリスク管理:ユーザーの離脱によるデータ盗難 | ロール アウト |
| | インサイダーリスク管理:一般的なデータ漏洩 | ロール アウト |
| | インサイダーリスク管理:インサイダーリスク管理アラートの調査 | ロール アウト |
| | インサイダーリスク管理:Teams、SharePointサイト、電子メールメッセージングのOffice指標 | ロール アウト |
| | インサイダーリスク管理活動エクスプローラ | エンジニアリングバックログについて |
| | インサイダーリスク管理:Windows 10ビルド1809以上での活動のデバイス指標 | エンジニアリングバックログについて |
| | インサイダー リスク管理: エンドポイント アラートの Microsoft Defender のインジケーター | エンジニアリングバックログについて |
| | インサイダーリスク管理:セキュリティポリシー違反の指標 | エンジニアリングバックログについて |
| | インサイダーリスク管理:不満を持つユーザーによるデータ漏洩のポリシーテンプレート | エンジニアリングバックログについて |
| | インサイダーリスク管理: 優先ユーザーによるデータ漏洩のポリシーテンプレート | エンジニアリングバックログについて |
| | 内部リスク管理: 一般的なセキュリティ ポリシー違反に対するポリシー テンプレート | エンジニアリングバックログについて |
| | 内部リスク管理: 優先度の高いユーザー、ユーザーの離脱、不満を持つユーザーによるセキュリティ ポリシー違反のポリシー テンプレート (プレビュー) | エンジニアリングバックログについて |
| | インサイダーリスク管理:ポリシーのカスタマイズ | エンジニアリングバックログについて |
| | インサイダーリスク管理: 輸出アラート | エンジニアリングバックログについて |
| | インサイダーリスク管理:Microsoft Teams統合 | エンジニアリングバックログについて |
| | インサイダーリスク管理: 優先度の高いユーザーグループ | エンジニアリングバックログについて |
| | 通信コンプライアンス:顧客ポリシーの作成、3つの事前設定 | Available |
| | 通信コンプライアンス: Teams、Exchange、およびTeamsメッセージの削除をサポート | Available |
| | 通信コンプライアンス: アクセスアラートテンプレートに注意してください。通信ポリシー ダッシュボード | Available |
| | 通信コンプライアンス: Advanced eDiscoveryの調査に対するエスカレーション | Available |
| | 通信コンプライアンス:時間の経過に応じて繰り返し行動規範違反を検出 | Available |
| | 通信コンプライアンス: より細かい権限のサポート | Available |
| | 通信コンプライアンス: オンプレミスメールボックスを使用Teamsユーザーのチャットデータを分析する | Available |
| | 通信コンプライアンス: 利益相反テンプレート | Available |
| | 通信コンプライアンス:電子メールの署名または免責事項を無視する機能 | 開発中 |
| | 通信コンプライアンス:通信コンプライアンスポリシーの保存期間を設定する機能 | エンジニアリングバックログについて |
| | コミュニケーションコンプライアンス:アダルトコンテンツの検出 | エンジニアリングバックログについて |
| | 通信コンプライアンス:インサイダーリスク管理ハンドオフ | 開発中 |
| | 通信コンプライアンス:ポリシーの正常性チェックとポリシーを一時停止する機能 | 開発中 |
| | コミュニケーションコンプライアンス:脅威、標的型ハラスメント、および不適切な分類者に対する7つの言語をサポート | 開発中 |
| | 通信コンプライアンス: 調査中に正常性コンテンツを翻訳する | 開発中 |
| | 情報バリア | ロール アウト |
| | 特権アクセス管理 | エンジニアリングバックログについて |
| **応答&検出** | コア電子情報開示: インプレース保存 | Available |
| | コア電子情報開示: ケース管理 | Available |
| | コア電子情報開示: 検索 | Available |
| | コア電子情報開示: エクスポート | Available |
| | コア電子情報開示: RMS 暗号化解除 | Available |
| | コア電子情報開示: ネイティブ エクスポート | Available |
| | コア電子情報開示: 監査 | Available |
| | コア電子情報開示: OneDrive for Businessのコンプライアンス境界 | ロール アウト |
| | Advanced eDiscovery: 高度な処理 | Available |
| | Advanced eDiscovery: Advanced eDiscoveryの CJK/ダブル・バイト・サポート | Available |
| | Advanced eDiscovery: ワークロードマッピングへの管理 | Available |
| | Advanced eDiscovery:カストディアン通信 | Available |
| | Advanced eDiscovery: ダッシュボード | Available |
| | Advanced eDiscovery: 電子メールスレッド | Available |
| | Advanced eDiscovery: エクスポート (ダウンロード、エクスポート、別のレビューセットへの追加) | Available |
| | Advanced eDiscovery: フィルタリング | Available |
| | Advanced eDiscovery: ほぼ重複した識別 | Available |
| | Advanced eDiscovery: 予測コーディング | Available |
| | Advanced eDiscovery: ロードファイルを使用したエクスポート処理 | Available |
| | Advanced eDiscovery: やり直し | Available |
| | Advanced eDiscovery: レビューセット | Available |
| | Advanced eDiscovery: レビューとアセート | Available |
| | Advanced eDiscovery: 検索用語レポート | Available |
| | Advanced eDiscovery: OneDriveおよびオンラインSharePointからのリンクされたコンテンツをサポート (最新の添付ファイル) | Available |
| | Advanced eDiscovery: タグ付け | Available |
| | Advanced eDiscovery:Teams反応サポート | Available |
| | Advanced eDiscovery: テナント レポート | Available |
| | Advanced eDiscovery: テーマ | Available |
| | Advanced eDiscovery: 視聴者 | Available |
| | Advanced eDiscovery: マイクロソフト コンプライアンス センターのYammer Advanced eDiscovery | Available |
| | Advanced eDiscovery: ホールドの最適化 | 開発中 |
| | Advanced eDiscovery: Microsoft コンプライアンス センターでは、SharePoint、OneDrive for Business、ごみ箱、およびAdvanced eDiscovery内のアイテムを検索およびエクスポートするためのサポートが拡張されました。 | 開発中 |
| | Advanced eDiscovery: プライベート チャネル メッセージTeams法的保留 | 開発中 |
| | Advanced eDiscovery: 新しい予測コーディング モジュール | 開発中 |
| | Advanced eDiscovery: 非Office 365摂取 | エンジニアリングバックログについて |
| | Advanced eDiscovery: テナント レポート | 開発中 |
| | 基本的な監査 | Available |
| | 高度な監査: 重要なイベントへのアクセス (たとえば、メールアイテムアクセス) | Available |
| | 高度な監査: 管理アクティビティ API の帯域幅の増加 | Available |
| | 高度な監査: ログ保持 (1 年) | Available |
| | 高度な監査: メール転送イベントとメール送信イベント | Available |
| | 高度な監査: セキュリティ/コンプライアンス センターの可用性 | Available |
| | 高度な監査: 監査ログの長期保存期間の長期 (10 年) | 開発中 |
| | 高度な監査: Exchange Onlineおよびオンラインでの検索用語イベントSharePoint | エンジニアリングバックログについて |
| **コンプライアンス管理** | Microsoft 365セキュリティ/コンプライアンス センター | Available |
| | Microsoft Cloud App Security | 開発中 |
| | コンプライアンス マネージャー | Available |
| | 2 バイト文字のサポート | Available |
| **生態系** | ファーストパーティデータコネクタ: HR | Available |
| | ファーストパーティデータコネクタ:インスタントブルームバーグ、ブルームバーグメール、LinkedInビジネスページ、ICEチャット | エンジニアリングバックログについて |
| | サードパーティのデータ コネクタ | エンジニアリングバックログについて |
| | GraphAdvanced eDiscovery用の API | 開発中 |
| | GraphデータをエクスポートTeams API | エンジニアリングバックログについて |

<sup>1</sup> 特定されたステータスは、プロジェクト計画と優先度が再評価されるため、変更される可能性があります。<br/>

**決定ポイント**: *コンプライアンス機能が組織のニーズを満たしているかどうかを判断します。*
