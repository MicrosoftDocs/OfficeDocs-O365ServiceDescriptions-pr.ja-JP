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
description: microsoft Defender for Office 365 は、堅牢なゼロデイ保護を提供することで未知のマルウェアやウイルスから組織を保護するクラウドベースの電子メール フィルタリング サービスであり、リアルタイムで有害なリンクから組織を保護する機能が含まれています。
ms.openlocfilehash: b3eb9d94fdd96899a0d08e591715a07354104c25
ms.sourcegitcommit: 29db3ccfdd875fc8968e11c040c6db46c2720134
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/12/2021
ms.locfileid: "49799406"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defende for Office 365 サービス説明書

microsoft Defender for Office 365 は、堅牢なゼロデイ保護を提供することで未知のマルウェアやウイルスから組織を保護するクラウドベースの電子メール フィルタリング サービスであり、リアルタイムで有害なリンクから組織を保護する機能が含まれています。 defender for Office 365 には、豊富なレポート機能と URL トレース機能が備え付けられているので、管理者は組織で発生する攻撃の種類を把握できます。

メッセージ保護のために Defender を Office 365 に使用する主な方法を次に示します。

- Office 365 フィルタリング専用の Defender では、Defender for Office 365 は、オンプレミスの Exchange Server 環境または他のオンプレミス SMTP 電子メール ソリューションにクラウドベースの電子メール保護を提供します。

- Defender for Office 365 を有効にすると、Exchange Online のクラウド ホスト型メールボックスを保護できます。 Exchange Online の詳細については、Exchange Online サービスの [説明を参照してください](exchange-online-service-description/exchange-online-service-description.md)。

- ハイブリッド展開では、Exchange Online Protection と受信電子メール フィルターを組み合わせ、オンプレミスメールボックスとクラウド メールボックスが混在している場合に、メッセージング環境を保護し、メール ルーティングを制御するように Defender for Office 365 を構成できます。

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 可用性

Office 365 プラン 2 用の Microsoft Defender は、Office 365 E5、Office 365 A5、Microsoft 365 E5 Security、および Microsoft 365 E5 に含まれています。 [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) Defender for Office 365 プラン 1 は、Microsoft 365 Business Premium に含まれています。

Defender for Office 365 を次の Exchange および Microsoft 365 サブスクリプション プランに追加できます。

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

Microsoft Defender for Office 365 を購入するには、Microsoft Defender で Office [365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)をご覧ください。

プラン全体で機能を比較するには、エンタープライズをサポートし [、Microsoft](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) [365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)で企業を変革するための強力なツールを参照してください。

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の新機能

Office 365 では、Defender に新機能を継続的に追加しています。 Office 365 (または Microsoft 365 全般) 向け Defender に追加される新機能の詳細については、次のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365 の新機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の要件

Defender for Office 365 は、メール送信エージェントなどの SMTP メール転送エージェントとMicrosoft Exchange Server。 Defender for Office 365 でサポートされているオペレーティング システム、Web ブラウザー、言語については [、Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381)の Exchange 管理センターの「サポートされているブラウザー」と「サポートされる言語」セクションを参照してください。

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Office 365 プランに対する Defender 全体での機能の可用性

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。<br><br>

| 機能 | Defender for Office 365 プラン 1 | Defender for Office 365 プラン 2 | Microsoft 365 E5 / E5 Security|
|:-----|:-----|:-----|:-----|
|*構成、保護、および検出*|
|[添付ファイル保護](#safe-attachments)|はい|はい|必要|
|Teams の安全な添付ファイル|はい|はい|必要|
|[リンク保護](#safe-links)|はい|はい|必要|
|[安全なドキュメント](#safe-documents)|いいえ|いいえ|はい|
|Teams の安全なリンク|はい|はい|必要|
|[SharePoint、OneDrive、Microsoft Teams 用の ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|はい|はい|必要|
|[フィッシング詐欺対策ポリシー](#anti-phishing-policies)|はい|はい|必要|
|[リアルタイム レポート](#real-time-reports)|はい|はい|必要|
|*自動化、調査、修復、教育*|
|[脅威トラッカー](#threat-trackers)|いいえ|はい|必要|
|脅威の調査 (高度な脅威の調査)|[リアルタイムの検出](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[自動インシデント対応](#automated-incident-response)|いいえ|はい|必要|
|[攻撃シミュレータ](#attack-simulator)|いいえ|はい|必要|
|*Microsoft [365 Defender との統合](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|いいえ|はい|必要|

> [!NOTE]
> テナントが Office プラン P2 試用版ライセンス用の Microsoft Defender または Office 365 E5 試用版ライセンスのみを持っている場合、Microsoft 365 Defender のその他の対象となるライセンスがない場合、Microsoft 365 Defender にアクセスできません。 MTP ライセンスについて詳しくは [、Microsoft 365 Defender の要件に関するページをご覧ください](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites)。

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365 の機能

### <a name="safe-attachments"></a>安全な添付ファイル

[「安全な](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 添付ファイル」は未知のマルウェアやウイルスから保護し、メッセージング システムを保護するためのゼロデイ保護を提供します。 既知のウイルス/マルウェア署名を持っていないすべてのメッセージと添付ファイルは、Defender for Office 365 がさまざまな機械学習と分析の手法を使用して悪意を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> 安全な添付ファイルのスキャンは、365 のデータが含Office領域で実行されます。 データ センターの地域の詳細については、「データの場所 [」を参照してください。](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全なリンク

安全 [なリンク機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) は、メッセージまたはドキュメント内の悪意のある URL からユーザー Officeします。 リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

セーフリンクは、次のアプリのURLで使用できます。

- Windows または Mac 上の Microsoft 365 Apps for enterprise

- Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）

- Windows 上の Word、Excel、PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーは、Office 365 の Defender のライセンスを取得し、安全なリンク ポリシーに含める必要があります。また、保護を有効にするためにデバイスでサインインする必要があります。 <sup>\*</sup>
>
> <sup>\*</sup> Office 365 ライセンス用の組織全体の Defender (ATP_ENTERPRISE_FACULTY など) の場合、Office 365 ライセンス用に Defender を個々のユーザーに割り当てる必要はありません。
>
> 安全なリンク保護について詳しくは、「Microsoft Defender の安全なリンク」をご覧ください(Office [365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links))。

### <a name="safe-documents"></a>安全なドキュメント

安全[なドキュメント機能では](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)[、Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)を使用して、保護ビューで開いているドキュメントとファイル[をスキャンします](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)。

はじめに把握しておくべき情報

- 「安全なドキュメント」は、バージョン 2004 (12730.x) Office以上のユーザーが一般に利用できます。 この機能は既定でオフになっているので、セキュリティ管理者が有効にする必要があります。

- この機能は、Microsoft 365 E5 または Microsoft 365 E5 セキュリティ ライセンスを持つユーザーのみ利用できます (Office 365 プランの Defender には含まれていません)。

- Windows 上の Word、Excel、PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーは、Microsoft 365 E5 または Microsoft 365 E5 Security のライセンスを取得し、安全なドキュメント ポリシーに含める必要があります。また、保護を適用するには、デバイスでサインインする必要があります。 <sup>\*</sup>
>
> 安全なドキュメント保護の詳細については [、「Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)の安全なドキュメント」を参照してください。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  用の ATP は、チーム サイトやドキュメント ライブラリで悪意のあるファイルとして識別されたファイルを検出してブロックするのに役立ちます。 さらに、Microsoft Teams のチャネルとチャットで安全なリンク保護を利用できます。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[フィッシング対策は、](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) メッセージがフィッシングの試みである可能性のあるインジケーターについて、受信メッセージをチェックします。 ユーザーが Office 365 ポリシー (安全な添付ファイル、安全なリンク、フィッシング対策) について Defender の対象となる場合、受信メッセージはメッセージを分析する複数の機械学習モデルによって評価され、構成されているポリシーに基づいて適切なアクションが実行されます。

### <a name="real-time-reports"></a>リアルタイム レポート

セキュリティ & コンプライアンス センター ( ) で使用できる監視機能には、セキュリティとコンプライアンスの管理者が、セキュリティ攻撃や疑わしいアクティビティの増加など、優先度の高い問題に集中できるリアルタイムのレポートと分析情報が含まれます。 [https://protection.office.com](https://protection.office.com) [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) スマート レポートと分析情報には、問題領域の強調表示に加えて、推奨事項や、データを表示および探索するためのリンクが含まれており、迅速なアクションも実行できます。

### <a name="explorer"></a>Explorer

エクスプローラー (脅威エクスプローラーとも呼ばれます) は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイムのレポートです。 既定では、このレポートには過去 7 日間のデータが表示されます。ただし、ビューを変更して過去 30 日間のデータを表示できます。

エクスプローラーには、マルウェア (メールとコンテンツ用)、送信、フィッシング、すべての電子メールなどのビューが含まれる。 エクスプローラーとリアルタイムの検出の比較を確認するには、この [PDF をダウンロードしてください](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

エクスプローラー (microsoft Defender for Office 365 プラン 2) とリアルタイム検出 (Microsoft Defender for Office 365 プラン 1)[](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)の詳細については、「脅威エクスプローラー」と「リアルタイム検出」を参照してください。

### <a name="real-time-detections"></a>リアルタイムの検出

リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。 エクスプローラーと同様、既定では、このレポートには過去 7 日間のデータが表示されます。

リアルタイム検出には、マルウェア (メールとコンテンツの場合)、送信、フィッシングなどのビューが含まれる。 リアルタイム検出とエクスプローラーの比較を確認するには、この [PDF をダウンロードしてください](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

エクスプローラー (microsoft Defender for Office 365 プラン 2) とリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「脅威エクスプローラー [(](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)およびリアルタイムの検出)」を参照してください。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威トラッカーは](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 、組織に影響を与える可能性のあるサイバーセキュリティの問題に関するインテリジェンスを承認されたユーザーに提供する情報ウィジェットとビューです。

### <a name="automated-incident-response"></a>自動インシデント対応

[](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) Office 365 プラン 2 の Defender で利用できる自動インシデント対応 (AIR) 機能を使用すると、現在存在する既知の脅威に対応して自動調査プロセスを実行できます。 特定の調査タスクを自動化することで、セキュリティ運用チームは効率的かつ効果的に運用できます。 悪意のある電子メール メッセージの削除などの修復アクションは、セキュリティ運用チームの承認を受け、実行されます。 詳細については、「Office [365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)での AIR のしくみ」を参照してください。

### <a name="attack-simulator"></a>攻撃シミュレータ

[攻撃シミュレータを](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 使用すると、承認されたユーザーは組織で現実的な攻撃シナリオを実行できます。 表示名スピア フィッシング攻撃、パスワード スプレー攻撃、ブルート フォース パスワード攻撃など、さまざまな種類の攻撃を利用できます。
