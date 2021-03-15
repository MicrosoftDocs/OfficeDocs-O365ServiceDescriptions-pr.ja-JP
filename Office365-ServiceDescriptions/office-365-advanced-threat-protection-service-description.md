---
title: Microsoft Defende for Office 365 サービス説明書
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。
ms.openlocfilehash: cc8d16f4a0a1058799ee3f5b0873ed6e9bf7f182
ms.sourcegitcommit: 34fd77f26c3fde723680c82af1004dffc143c823
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2021
ms.locfileid: "50726742"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defende for Office 365 サービス説明書

Microsoft Defender for Office 365 は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。 Defender for Office 365 には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。

メッセージ保護に Defender for Office 365 を使用できる基本的な方法として、次のようなものがあります。

- Defender for Office 365 のフィルタリングのみのシナリオでは、Defender for Office 365 はオンプレミスの Exchange Server 環境、その他のオンプレミス SMTP メール ソリューションにクラウドベースのメール保護を提供します。

- Defender for Office 365 は、Exchange Online クラウドにホストされているメールボックスを保護することができます。 Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信メール フィルタリングに Exchange Online Protection を併用するように Defender for Office 365 を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 の状態

Microsoft Defender for Office 365 プラン 2 は、こちらに指定された Office 365 E5、Office 365 A5、および Microsoft 365 E5 Security と Microsoft 365 E5 に含まれています: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)。 Defender for Office 365 プラン 1 は、Microsoft 365 Business Premium に含まれています。

Defender for Office 365 は、以下の Exchange と Microsoft 365 サブスクリプション プランに追加できます。

- Exchange Online プラン 1

- Exchange Online プラン 2

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Microsoft Defender for Office 365 を購入するには、「[Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)」を参照してください。

Microsoft Defender for Office 365 のユーザーを有効にするサブスクリプションの詳細なプラン情報については、[完全なサブスクリプション比較表](https://go.microsoft.com/fwlink/?linkid=2139145)を参照してください。

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の新機能

Microsoft は、Defender for Office 365 に新機能を追加し続けています。 Defender for Office 365 (または一般的に Microsoft 365) の新機能に関する詳細については、次のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365 の新機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の要件

Defender for Office 365 は、Microsoft Exchange Server などの SMTP メール転送エージェントと一緒に使用できます。 Defender for Office 365 でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Defender for Office 365 の各プランで利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。<br><br>

| 特徴 | Microsoft Defender for Office 365 プラン 1 | Defender for Office 365 プラン 2 | Microsoft 365 E5 Security または A5 Security|
|:-----|:-----|:-----|:-----|
|*構成、保護、検出*|
|[安全な添付ファイル](#safe-attachments)|はい|はい|はい|
|Teams の安全なリンク|はい|はい|はい|
|[安全なリンク](#safe-links)|はい|はい|はい|
|[安全なドキュメント](#safe-documents)|いいえ|いいえ|はい|
|Teams の安全なリンク|はい|はい|はい|
|[SharePoint、OneDrive、Microsoft Teams 用の ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|はい|はい|はい|
|[フィッシング詐欺対策ポリシー](#anti-phishing-policies)|はい|はい|はい|
|[リアルタイム レポート](#real-time-reports)|はい|はい|はい|
|*自動化、調査、修復、教育*|
|[脅威トラッカー](#threat-trackers)|いいえ|はい|はい|
|脅威調査 (高度な脅威調査)|[リアルタイムの検出](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[自動化したインシデント応答](#automated-incident-response)|いいえ|はい|はい|
|[攻撃シミュレータ](#attack-simulator)|いいえ|はい|はい|
|*[Microsoft 365 Defender](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection) との統合*|いいえ|はい|はい|

> [!NOTE]
> テナントに Microsoft Defender for Office プラン P2 試用版ライセンスまたは Office 365 E5  試用版ライセンス以外に Microsoft 365 Defender 向けの対象ライセンスがない場合は、Microsoft 365 Defender にアクセスできなくなります。 MTP ライセンスの詳細については、「[Microsoft 365 Defender の要件](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)」を参照してください。

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365 機能

### <a name="safe-attachments"></a>安全な添付ファイル

[添付ファイル保護](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)は、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。 既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、Defender for Office 365 がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> 安全な添付ライフのスキャンは、Office 365 データが存在する安全な領域で実行されます。 データ センター保護の詳細については、「[データの移動先](https://products.office.com/where-is-your-data-located?geo=All)」を参照してください。

### <a name="safe-links"></a>安全なリンク

[安全なリンク](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪質な URL から予防的にユーザーを保護します。 リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

 安全なリンクは、次のアプリのURLで使用できます。

- Windows または Mac 上のエンタープライズ向け Microsoft 365 アプリ

- Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）

- Windows の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> Defender for Office 365<sup>\*</sup> がライセンスされたユーザーは、[安全なリンク] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。
>
> <sup>\*</sup> 組織全体のDefender for Office 365 ライセンス (ATP_ENTERPRISE_FACULTY など) には、個々のユーザーに Defender for Office 365 ライセンスを割り当てる必要はありません。
>
> 安全なリンク保護の詳細については、「[Microsoft Defender for Office 365 の安全なリンク](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)」を参照してください。

### <a name="safe-documents"></a>安全なドキュメント

[安全なドキュメント](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) 機能では、[Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) を使用して、[保護ビュー](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)で開かれたドキュメントやファイルをスキャンします。

はじめに把握しておくべき情報

- 安全なドキュメントは、現在 Office バージョン 2004 (12730.x) 以降を使用するユーザーに一般公開されています。 この機能は既定ではオフになっており、セキュリティ管理者が有効にする必要があります。

- この機能は、Microsoft 365 E5 または Microsoft 365 E5 セキュリティ ライセンス (Defender for Office 365 プランには含まれません) を持つユーザーのみが利用できます。

- Windows の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> Microsoft 365 E5 または Microsoft 365 E5 Security<sup>\*</sup> がライセンスされたユーザーは、[安全なドキュメント] ポリシーに含まれる必要があり、保護が実行されるためにデバイスにサインインされている必要があります。
>
> 安全なドキュメント保護の詳細については、「[Microsoft 365 E5 の安全なドキュメント](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)」を参照してください。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、および Microsoft Teams を対象とした ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) は、チーム サイトとドキュメント ライブラリに悪意があると特定されたファイルを検出してブロックします。 さらに、[安全なリンク] 保護は、現在Microsoft Teams チャネルおよびチャットで使用可能です。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[フィッシング詐欺対策](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)は、受信メッセージをチェックして、メッセージがフィッシング詐欺になる可能性がある指標がないか確認します。 ユーザーが Defender for Office 365 ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング詐欺対策) に含まれる場合、受信メッセージは、構成されたポリシーに基づいてメッセージを分析し、適切なアクションを実行する複数の機械学習モデルによって評価されます。

### <a name="real-time-reports"></a>リアルタイム レポート

セキュリティとコンプライアンスの管理者がセキュリティの攻撃や不審な活動の増加など、優先度の高い問題に専念できるようにする[リアルタイムのレポートおよびインサイト機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)を使用して、セキュリティ/コンプライアンスセンター ([https://protection.office.com](https://protection.office.com)) に表示されます。 問題の領域の強調表示に加えて、スマート リポートおよび分析情報にはおすすめ候補が含まれ、データの表示および検索にリンクしてクイック アクションも実行します。

### <a name="explorer"></a>エクスプローラー

エクスプローラー (脅威エクスプローラーとも呼ばれます) は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイムのレポートです。 既定では、このレポートには、過去 7 日間のデータが表示されますが、過去 30 日間のデータを表示するようにビューを変更できます。

エクスプローラーには、(メールおよびコンテンツに対する) マルウェア、送信、フィッシング、すべてのメールなどの表示が含まれます。 エクスプローラーとリアルタイムの検出との比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="real-time-detections"></a>リアルタイムの検出

リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。 既定では、このレポートには、エクスプローラーと同様に過去 7 日間のデータが表示されます。

リアルタイムの検出には、(メールおよびコンテンツに対する) マルウェア、送信、フィッシングなどの表示が含まれます。 リアルタイム検出とエクスプローラーとの比較の詳細については、「[この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)」を参照してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「[脅威エクスプローラーとリアルタイムの検出](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威トラッカー](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)は、組織に影響を与える可能性があるサイバーセキュリティの問題に関するインテリジェンスを許可されたユーザーに提供する、有益なウィジェットとビューです。

### <a name="automated-incident-response"></a>自動インシデント応答 (AIR) イベント

[自動調査および対応](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (ARI) 機能を使用すると、既存のよく知られている脅威に対処するために、自動調査プロセスを実行できます。 自動化された特定の調査タスクを使用すると、セキュリティ運用チームはより効率化され、より効果的に使うことができるようになります。 悪意のあるメール、メッセージなどの修復アクションは、セキュリティ運用チームの承認を得て実行されます。 詳細については、「[Office 365 での AIR のしくみ](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)」を参照してください。

### <a name="attack-simulator"></a>攻撃シミュレーター

[攻撃シミュレーター](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)では、組織内で許可されているユーザーが現実的な攻撃シナリオを実行できるようにします。 表示名のスピア フィッシング攻撃、パスワード スプレー攻撃、ブルート フォース パスワード攻撃など、さまざまな種類の攻撃を利用できます。
