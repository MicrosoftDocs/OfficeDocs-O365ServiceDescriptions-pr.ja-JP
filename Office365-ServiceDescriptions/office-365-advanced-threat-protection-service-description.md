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
description: Microsoft Defender for Office 365 は、堅牢なゼロデイ保護を提供することで、不明なマルウェアやウイルスから組織を保護するのに役立つクラウドベースの電子メール フィルター サービスであり、組織を有害なリンクからリアルタイムで保護する機能が含まれています。
ms.openlocfilehash: 6116ffdce71686575258c19c7d70159bcefa2134
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460246"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defende for Office 365 サービス説明書

Microsoft Defender for Office 365 は、堅牢なゼロデイ保護を提供することで、不明なマルウェアやウイルスから組織を保護するのに役立つクラウドベースの電子メール フィルター サービスであり、組織を有害なリンクからリアルタイムで保護する機能が含まれています。 Defender for Office 365 には、豊富なレポート機能と URL トレース機能が備え付けられているので、管理者は組織で発生している攻撃の種類を把握できます。

メッセージ保護のために Defender を 365 に使用Office主な方法を次に示します。

- Office 365 フィルター専用の Defender シナリオでは、Defender for Office 365 は、オンプレミスの Exchange Server 環境または他のオンプレミス SMTP 電子メール ソリューションにクラウドベースの電子メール保護を提供します。

- Exchange Online Officeホスト型メールボックスを保護するために、365 の Defender を有効にできます。 Exchange Online の詳細については、「Exchange Online サービスの [説明」を参照してください](exchange-online-service-description/exchange-online-service-description.md)。

- ハイブリッド展開では、受信メール フィルター用の Exchange Online Protection とオンプレミスメールボックスとクラウド メールボックスが混在している場合に、メッセージング環境を保護し、メール ルーティングを制御するように Defender for Office 365 を構成できます。

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 可用性

Office 365 プラン 2 の Microsoft Defender は、Office 365 E5、Office 365 A5、Microsoft 365 E5 Security、および Microsoft 365 E5 に含まれています。ここで指定します。 [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) Microsoft 365 Business Premium には、Office 365 プラン 1 の Defender が含まれています。

次の Exchange および Microsoft 365 サブスクリプション プランOffice 365 用の Defender を追加できます。

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

Microsoft Defender for Office 365 を購入するには [、「Microsoft Defender for Office 365」を参照してください](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。

プラン間で機能を比較するには、「エンタープライズをサポート [するための強力](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) なツール」および [「Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)を使用してエンタープライズを変換する」を参照してください。

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の新機能

365 用の Defender に新機能を追加Officeしています。 Defender for Office 365 (または Microsoft 365 全般) の新機能の詳細については、次のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365 の新機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

365 Officeの Defender は、SMTP メール転送エージェント (メール転送エージェントなど) とMicrosoft Exchange Server。 defender for Office 365 でサポートされているオペレーティング システム、Web ブラウザー、および言語については [、Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381)の Exchange 管理センターの「サポートされているブラウザー」および「サポートされている言語」セクションを参照してください。

## <a name="feature-availability-across-defender-for-office-365-plans"></a>365 プランの Defender Office機能の可用性

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。<br><br>

| 機能 | Defender for Office 365 Plan 1 | Defender for Office 365 Plan 2 | Microsoft 365 E5 / A5 Security|
|:-----|:-----|:-----|:-----|
|*構成、保護、および検出*|
|[添付ファイル保護](#safe-attachments)|はい|はい|はい|
|Teams の安全な添付ファイル|はい|はい|はい|
|[リンク保護](#safe-links)|はい|はい|はい|
|[安全なドキュメント](#safe-documents)|いいえ|いいえ|はい|
|Teams の安全なリンク|はい|はい|はい|
|[SharePoint、OneDrive、Microsoft Teams 用の ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|はい|はい|はい|
|[フィッシング詐欺対策ポリシー](#anti-phishing-policies)|はい|はい|はい|
|[リアルタイム レポート](#real-time-reports)|はい|はい|はい|
|*自動化、調査、修復、および教育*|
|[脅威トラッカー](#threat-trackers)|いいえ|はい|はい|
|脅威の調査 (高度な脅威調査)|[リアルタイムの検出](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[インシデント対応の自動化](#automated-incident-response)|いいえ|はい|はい|
|[攻撃シミュレータ](#attack-simulator)|いいえ|はい|はい|
|*Microsoft [365 Defender との統合](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|いいえ|はい|はい|

> [!NOTE]
> テナントが microsoft Defender for Office Plan P2 試用版ライセンスまたは Office 365 E5 試用版ライセンスのみを持ち、Microsoft 365 Defender の他の適格なライセンスがない場合は、Microsoft 365 Defender にアクセスできません。 MTP ライセンスの詳細については [、「Microsoft 365 Defender の要件」を参照してください](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)。

## <a name="defender-for-office-365-capabilities"></a>365 Officeの Defender

### <a name="safe-attachments"></a>安全な添付ファイル

[安全な添付](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) ファイルは、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するためのゼロデイ保護を提供します。 既知のウイルス/マルウェア署名を持っていないすべてのメッセージと添付ファイルは、Defender for Office 365 がさまざまな機械学習および分析手法を使用して悪意のある意図を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> 安全な添付ファイルのスキャンは、365 データが存在するOffice領域で行います。 データ センターの地域の詳細については、「データの場所 [」を参照してください。](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全なリンク

安全 [なリンク機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) は、メッセージまたはドキュメント内の悪意のある URL からユーザーをプロアクティブにOfficeします。 リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

セーフリンクは、次のアプリのURLで使用できます。

- Windows または Mac の Microsoft 365 Apps for enterprise

- Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）

- Windows 上の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーは、Office 365 の Defender のライセンスを取得する必要があります。セーフ リンク ポリシーに含める必要があります。保護を行うには、デバイスでサインインする <sup>\*</sup> 必要があります。
>
> <sup>\*</sup> Office 365 ライセンス (ATP_ENTERPRISE_FACULTY など) の組織全体の Defender の場合、Office 365 ライセンスの Defender を個々のユーザーに割り当てる必要はありません。
>
> セーフ リンク保護の詳細については、「Safe Links [in Microsoft Defender for Office 365」を参照してください](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)。

### <a name="safe-documents"></a>安全なドキュメント

安全[なドキュメント機能では](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)[、Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)を使用して、保護ビューで開いているドキュメントとファイル[をスキャンします](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。

はじめに把握しておくべき情報

- 安全なドキュメントは、バージョン 2004 (12730.x) 以上Officeユーザーが一般に利用できます。 この機能は既定でオフになっているので、セキュリティ管理者が有効にする必要があります。

- この機能は、Microsoft 365 E5 または Microsoft 365 E5 セキュリティ ライセンスを持つユーザーにのみ使用できます (365 プランの Defender にはOfficeではありません)。

- Windows 上の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーは、Microsoft 365 E5 または Microsoft 365 E5 セキュリティのライセンスを取得する必要があります。安全なドキュメント ポリシーに含める必要があります。保護を行うには、デバイスでサインインする必要があります。 <sup>\*</sup>
>
> 安全なドキュメント保護の詳細については [、「Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)の安全なドキュメント」を参照してください。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、および Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  の ATP は、チーム サイトやドキュメント ライブラリで悪意のあるファイルとして識別されるファイルを検出およびブロックするのに役立ちます。 さらに、安全なリンク保護は、Microsoft Teams チャネルとチャットで利用できます。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[フィッシング対策は、](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) メッセージがフィッシング詐欺の試みである可能性があるインジケーターについて受信メッセージをチェックします。 ユーザーが Office 365 ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング対策) の Defender で対象となる場合、受信メッセージは、構成されたポリシーに基づいて、メッセージを分析する複数の機械学習モデルによって評価され、適切なアクションが実行されます。

### <a name="real-time-reports"></a>リアルタイム レポート

セキュリティ & コンプライアンス センター ( ) で使用できる監視機能には、セキュリティとコンプライアンスの管理者がセキュリティ攻撃や疑わしいアクティビティの増加など、優先度の高い問題に集中できるリアルタイムのレポートと分析情報が含まれます。 [https://protection.office.com](https://protection.office.com) [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 問題領域の強調表示に加えて、スマート レポートと分析情報には、データを表示および探索するための推奨事項やリンクが含まれており、迅速なアクションも実行できます。

### <a name="explorer"></a>Explorer

エクスプローラー (脅威エクスプローラーとも呼ばれます) は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイムのレポートです。 既定では、このレポートには過去 7 日間のデータが表示されます。ただし、過去 30 日間のデータを表示するためにビューを変更できます。

エクスプローラーには、マルウェア (電子メールとコンテンツ用)、申請、フィッシング、すべてのメールなどのビューが含まれる。 エクスプローラーとリアルタイム検出の比較方法を確認するには、この [PDF をダウンロードしてください](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

Explorer (microsoft Defender for Office 365 Plan 2) とリアルタイム検出 (Microsoft Defender for Office 365 Plan 1) の詳細については、「Threat [Explorer](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)とリアルタイム検出」を参照してください。

### <a name="real-time-detections"></a>リアルタイムの検出

リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。 エクスプローラーと同様、既定では、このレポートには過去 7 日間のデータが表示されます。

リアルタイム検出には、マルウェア (メールとコンテンツの場合)、申請、フィッシングなどのビューが含まれる。 リアルタイム検出とエクスプローラーの比較方法を確認するには、この [PDF をダウンロードしてください](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

Explorer (microsoft Defender for Office 365 Plan 2) とリアルタイム検出 (Microsoft Defender for Office 365 Plan 1) の詳細については、「Threat [Explorer (](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)およびリアルタイム検出)」を参照してください。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威トラッカーは](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 、組織に影響を与える可能性のあるサイバーセキュリティの問題に関するインテリジェンスを承認されたユーザーに提供する有益なウィジェットとビューです。

### <a name="automated-incident-response"></a>インシデント対応の自動化

[](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) Office 365 プラン 2 の Defender で利用できる自動インシデント対応 (AIR) 機能を使用すると、現在存在する既知の脅威に対応して自動化された調査プロセスを実行できます。 特定の調査タスクを自動化することで、セキュリティ運用チームは、より効率的かつ効果的に運用できます。 悪意のある電子メール メッセージの削除などの修復アクションは、セキュリティ運用チームの承認を受け取られます。 詳細については [、「365 の AIR のしくみ」を参照Officeしてください](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻撃シミュレータ

[攻撃シミュレーターを](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 使用すると、承認されたユーザーは組織内で現実的な攻撃シナリオを実行できます。 表示名のスピア フィッシング攻撃、パスワード スプレー攻撃、ブルートフォース パスワード攻撃など、さまざまな種類の攻撃を利用できます。
