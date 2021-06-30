---
title: Microsoft Defender for Office 365 機能 サービスの説明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Microsoft Defender で使用できる機能について説明Office 365。
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204867"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Microsoft Defender for Office 365 機能 サービスの説明

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の新機能

Microsoft は、Defender for Office 365 に新機能を追加し続けています。 Defender for Office 365 (または一般的に Microsoft 365) の新機能に関する詳細については、次のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap)

- [Microsoft Defender for Office 365 - Office 365 |Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365 機能

### <a name="safe-attachments"></a>安全な添付ファイル

[添付ファイル保護](/microsoft-365/security/office-365-security/atp-safe-attachments)は、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。 既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、Defender for Office 365 がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> 安全な添付ライフのスキャンは、Office 365 データが存在する安全な領域で実行されます。 データ センター保護の詳細については、「[データの移動先](/microsoft-365/enterprise/o365-data-locations)」を参照してください。

### <a name="safe-links"></a>安全なリンク

[安全なリンク](/microsoft-365/security/office-365-security/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪質な URL から予防的にユーザーを保護します。 リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

セーフリンクは、次のアプリのURLで使用できます。

- Windows または Mac 上のエンタープライズ向け Microsoft 365 アプリ

- Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）

- Windows の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> Defender for Office 365<sup>\*</sup> がライセンスされたユーザーは、[安全なリンク] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。
>
> <sup>\*</sup> 組織全体のDefender for Office 365 ライセンス (ATP_ENTERPRISE_FACULTY など) には、個々のユーザーに Defender for Office 365 ライセンスを割り当てる必要はありません。
>
> 安全なリンク保護の詳細については、「[Microsoft Defender for Office 365 の安全なリンク](/microsoft-365/security/office-365-security/atp-safe-links)」を参照してください。

### <a name="safe-documents"></a>安全なドキュメント

[安全なドキュメント](/microsoft-365/security/office-365-security/safe-docs) 機能では、[Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) を使用して、[保護ビュー](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)で開かれたドキュメントやファイルをスキャンします。

はじめに把握しておくべき情報

- 安全なドキュメントは、現在 Office バージョン 2004 (12730.x) 以降を使用するユーザーに一般公開されています。 この機能は既定ではオフになっており、セキュリティ管理者が有効にする必要があります。

- この機能は、Microsoft 365 E5 または Microsoft 365 E5 セキュリティ ライセンス (Defender for Office 365 プランには含まれません) を持つユーザーのみが利用できます。

- Windows の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> Microsoft 365 E5 または Microsoft 365 E5 Security<sup>\*</sup> がライセンスされたユーザーは、[安全なドキュメント] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。
>
> 安全なドキュメント保護の詳細については、「[Microsoft 365 E5 の安全なドキュメント](/microsoft-365/security/office-365-security/safe-docs)」を参照してください。

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>ユーザー、SharePoint、OneDrive、およびMicrosoft Teams

[チーム サイトSharePoint OneDriveドキュメント](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)ライブラリSharePoint、Microsoft Teamsファイルとして識別されるファイルの検出とブロックに役立ちます。 さらに、[安全なリンク] 保護は、現在Microsoft Teams チャネルおよびチャットで使用可能です。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[フィッシング詐欺対策](/microsoft-365/security/office-365-security/atp-anti-phishing)は、受信メッセージをチェックして、メッセージがフィッシング詐欺になる可能性がある指標がないか確認します。 ユーザーが Defender for Office 365 ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング詐欺対策) に含まれる場合、受信メッセージは、構成されたポリシーに基づいてメッセージを分析し、適切なアクションを実行する複数の機械学習モデルによって評価されます。

### <a name="real-time-reports"></a>リアルタイム レポート

[セキュリティ & コンプライアンス](https://protection.office.com)センターで使用できる監視機能には、[](/microsoft-365/security/office-365-security/view-reports-for-atp)セキュリティとコンプライアンスの管理者がセキュリティ攻撃や疑わしいアクティビティの増加など、優先度の高い問題に集中できるリアルタイム のレポートと分析情報が含まれます。 問題の領域の強調表示に加えて、スマート リポートおよび分析情報にはおすすめ候補が含まれ、データの表示および検索にリンクしてクイック アクションも実行します。

### <a name="threat-explorer"></a>脅威エクスプローラー

Threat Explorer (エクスプローラーとも呼ばれます) は、承認されたユーザーが最近の脅威を特定して分析できるリアルタイム レポートです。 既定では、このレポートには、過去 7 日間のデータが表示されますが、過去 30 日間のデータを表示するようにビューを変更できます。

エクスプローラーには、(メールおよびコンテンツに対する) マルウェア、送信、フィッシング、すべてのメールなどの表示が含まれます。 エクスプローラーとリアルタイムの検出との比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="real-time-detections"></a>リアルタイムの検出

リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。 既定では、このレポートには、エクスプローラーと同様に過去 7 日間のデータが表示されます。

リアルタイムの検出には、(メールおよびコンテンツに対する) マルウェア、送信、フィッシングなどの表示が含まれます。 リアルタイム検出とエクスプローラーとの比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威トラッカー](/microsoft-365/security/office-365-security/threat-trackers)は、組織に影響を与える可能性があるサイバーセキュリティの問題に関するインテリジェンスを許可されたユーザーに提供する、有益なウィジェットとビューです。

### <a name="automated-investigation--response"></a>自動調査&応答

[](/microsoft-365/security/office-365-security/office-365-air) Office 365 プラン 2 の Defender で利用可能な自動調査&応答 (AIR) 機能を使用すると、現在存在する既知の脅威に対応して自動調査プロセスを実行できます。 特定の調査タスクを自動化することで、セキュリティ運用チームは、より効率的かつ効果的に運用できます。 悪意のあるメール、メッセージなどの修復アクションは、セキュリティ運用チームの承認を得て実行されます。 詳細については、「[Office 365 での AIR のしくみ](/microsoft-365/security/office-365-security/automated-investigation-response-office)」を参照してください。

### <a name="attack-simulation-training"></a>攻撃シミュレーション トレーニング

[攻撃シミュレーション トレーニングは](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 、フィッシング シミュレーションの作成と管理を自動化するインテリジェントなソーシャル リスク管理ツールです。 シミュレーションは、実際のフィッシングルアーとハイパーターゲットトレーニングを使用して従業員の行動を変更することで、フィッシングリスクを検出、優先順位付け、修復するのに役立ちます。

- 攻撃シミュレーション のトレーニングは、WW および GCCで利用できます (6 月 21 日GCC予定)。
- 開始方法の詳細については、「攻撃シミュレーション トレーニングの使用 [を開始する」を参照してください](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。
- 実際の攻撃者の動作を再現してフィッシング シミュレーションを関連性のあるものにする、武器化された実際のフィッシング ペイロードを適用するさまざまな攻撃手法が利用できます。
- このサービスは、プラン[2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)ライセンスのMicrosoft 365 E5、Office 365 E5、Microsoft Defender のいずれかを持つOffice 365利用できます。 機能のサブセットは、試用版として E3 のお客様に提供されます。
- 詳しくは、「フィッシング攻撃のシミュレーション」 [をご覧ください](/microsoft-365/security/office-365-security/attack-simulation-training)。