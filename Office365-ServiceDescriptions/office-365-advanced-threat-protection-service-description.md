---
title: Microsoft Defender for Office 365 サービスの説明
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
description: Microsoft Defender for Office 365 は、保護されたゼロ日の保護を提供することによって、不明なマルウェアやウイルスから組織を保護するクラウドベースの電子メールフィルター処理サービスであり、リアルタイムで有害なリンクから組織を保護する機能を備えています。
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519028"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender for Office 365 サービスの説明

Microsoft Defender for Office 365 は、保護されたゼロ日の保護を提供することによって、不明なマルウェアやウイルスから組織を保護するクラウドベースの電子メールフィルター処理サービスであり、リアルタイムで有害なリンクから組織を保護する機能を備えています。 Defender for Office 365 には、組織で発生している攻撃の種類について管理者が洞察できる豊富なレポートおよび URL 追跡機能が用意されています。

次に示すのは、メッセージ保護のために Defender for Office 365 を使用する主な方法です。

- Defender for Office 365 filtering のみのシナリオでは、Defender for Office 365 は、社内の Exchange Server 環境または他の社内 SMTP 電子メールソリューションにクラウドベースの電子メール保護を提供します。

- Exchange Online のクラウドホスト型メールボックスを保護するために、Defender for Office 365 を有効にすることができます。 Exchange Online の詳細については、「 [Exchange online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- ハイブリッド展開では、受信メールフィルター用の Exchange Online Protection でオンプレミスとクラウドメールボックスが混在している場合に、メッセージング環境を保護し、メールルーティングを制御するように、Office 365 の Defender を構成できます。

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 の可用性

Office 365 プラン2は Office 365 E5、Office 365 A5、および Microsoft 365 E5 に含まれています。 Office 用 Defender 365 プラン1は、Microsoft 365 Business Premium に含まれています。

Office 365 の Defender は、次の Exchange および Microsoft 365 サブスクリプションプランに追加できます。

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

Office 365 の Microsoft Defender を購入するには、「 [Microsoft defender For office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)」を参照してください。

プラン間で機能を比較するには、「 [エンタープライズをサポートするための強力なツール](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 」と「 [Microsoft 365 を使用](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)して企業を変換する」を参照してください。

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365 の新機能

Office 365 用の Defender に新機能を追加し続けます。 Office 365 (または Microsoft 365 general) 用に Defender に届く新機能の詳細については、次のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365 の新機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Office 365 の Microsoft Defender の要件

Microsoft Exchange Server などの任意の SMTP メール転送エージェントと共に、Office 365 の Defender を使用できます。 Office 365 の Defender でサポートされているオペレーティングシステム、web ブラウザー、および言語の詳細については、「exchange [Online Protection の exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされるブラウザー」と「サポートされる言語」のセクションを参照してください。

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Office 365 プランの Defender で利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。<br><br>

| 機能 | Office 用 Defender 365 プラン1 | Office 用 Defender 365 プラン2 | Microsoft 365 E5/E5 セキュリティ|
|:-----|:-----|:-----|:-----|
|*構成、保護、および検出*|
|[添付ファイル保護](#safe-attachments)|はい|はい|はい|
|Teams での安全な添付ファイル|はい|はい|はい|
|[リンク保護](#safe-links)|はい|はい|はい|
|[安全なドキュメント](#safe-documents)|いいえ|いいえ|はい|
|Teams の安全なリンク|はい|はい|はい|
|[SharePoint、OneDrive、Microsoft Teams 用の ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|はい|はい|はい|
|[フィッシング詐欺対策ポリシー](#anti-phishing-policies)|はい|はい|はい|
|[リアルタイム レポート](#real-time-reports)|はい|はい|はい|
|*自動化、調査、修復、教育*|
|[脅威トラッカー](#threat-trackers)|いいえ|はい|はい|
|脅威調査 (高度な脅威調査)|[リアルタイムの検出](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[インシデント対応の自動化](#automated-incident-response)|いいえ|はい|はい|
|[攻撃シミュレータ](#attack-simulator)|いいえ|はい|はい|
|*Microsoft 365 Defender との統合*|いいえ|いいえ|はい|

> [!TIP]
> Office 365 プラン1およびプラン2の Defender の間で、ダウンロード可能な違いの一覧が必要ですか。 [PDF を取得](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)します。 

## <a name="defender-for-office-365-capabilities"></a>Office 365 のための Defender の機能

### <a name="safe-attachments"></a>安全な添付ファイル

[安全な添付ファイル](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) は、不明なマルウェアやウイルスから保護し、メッセージングシステムを保護するためのゼロ日の保護を提供します。 既知のウイルスまたはマルウェアの署名を持たないすべてのメッセージと添付ファイルは、特定の環境にルーティングされます。この場合、Defender for Office 365 は、さまざまな machine learning および分析手法を使用して悪意のある目的を検出します。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> 安全な添付ファイルのスキャンは、Office 365 データが存在する地域と同じ地域で行われます。 データセンター地理の詳細については、「[データの保存場所](https://products.office.com/where-is-your-data-located?geo=All)」を参照してください。

### <a name="safe-links"></a>安全なリンク

[安全なリンク](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪意のある url からユーザーを事前に保護します。 リンクを選択した後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

セーフリンクは、次のアプリのURLで使用できます。

- Windows または Mac でのエンタープライズ向け Microsoft 365 アプリ

- Web 用 Office （Web 用 Word、Web 用 Excel、Web 用 PowerPoint、Web 用 OneNote）

- Windows 上の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーが Office 365 の Defender のライセンスを持っている必要があり <sup>\*</sup> ます。安全なリンクポリシーに含める必要があります。また、保護のためには、デバイス上で署名する必要があります。
>
> <sup>\*</sup> 組織全体の Defender for Office 365 ライセンス (ATP_ENTERPRISE_FACULTY など) の場合は、Office 365 のライセンスの Defender を個々のユーザーに割り当てる必要はありません。
>
> 安全リンク保護の詳細については、「 [Microsoft Defender For Office 365」](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)の「安全なリンク」を参照してください。

### <a name="safe-documents"></a>安全なドキュメント

[安全なドキュメント](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)機能は、[エンドポイントに Microsoft Defender](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)を使用して、[保護さ](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)れたビューで開かれたドキュメントやファイルをスキャンします。

はじめに把握しておくべき情報

- Office バージョン 2004 (12730) を使用しているユーザーが、安全なドキュメントを使用できるようになりました。 この機能は既定でオフになっており、セキュリティ管理者が有効にする必要があります。

- この機能は、Microsoft 365 E5 または Microsoft 365 E5 (Office 365 プランに含まれていない) セキュリティライセンスを持つユーザーのみが使用できます。

- Windows 上の Word、Excel、および PowerPoint

- Microsoft Teams チャンネルおよびチャット

> [!NOTE]
> ユーザーは、Microsoft 365 E5 または Microsoft 365 E5 セキュリティのライセンスを持っている必要があり <sup>\*</sup> ます。また、安全なドキュメントポリシーに含める必要があります。また、保護するためには、デバイスでサインインする必要があります。
>
> 安全なドキュメントの保護の詳細については、「 [Microsoft 365 E5 の安全なドキュメント](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)」を参照してください。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、Microsoft Teams 用の ATP は、](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  チームサイトやドキュメントライブラリで悪意のあるものとして識別されたファイルを検出してブロックするのに便利です。 さらに、「安全なリンクの保護」が Microsoft Teams のチャネルとチャットで利用できるようになりました。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

フィッシング[対策](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)は、メッセージがフィッシングである可能性があることを示すインジケーターの受信メッセージをチェックします。 ユーザーが Office 365 ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング対策) に従っている場合、受信メッセージは、メッセージを分析し、構成されたポリシーに基づいて適切なアクションを実行する複数のコンピューター学習モデルによって評価されます。

### <a name="real-time-reports"></a>リアルタイム レポート

セキュリティ & コンプライアンスセンターで利用可能な監視機能には [リアルタイムのレポートと洞察](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) が含まれており、セキュリティおよびコンプライアンスの管理者は、セキュリティ攻撃や不審な活動の増加など、優先度の高い問題に焦点を当てることができます。 スマートレポートと分析には、問題の領域を強調するだけでなく、データを表示して探索したり、簡単なアクションを実行したりするための推奨事項やリンクが含まれています。

### <a name="explorer"></a>Explorer

エクスプローラー (脅威エクスプローラーとも呼ばれます) は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイムのレポートです。 既定では、このレポートには、過去7日間のデータが表示されますが、過去30日間のデータを表示するようにビューを変更できます。

エクスプローラーには、マルウェア (電子メールとコンテンツなど)、送信、フィッシング、すべての電子メールなどのビューが含まれています。 エクスプローラーがリアルタイム検出と比較されることを確認するには、 [この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「 [脅威エクスプローラー」および「リアルタイム検出](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="real-time-detections"></a>リアルタイムの検出

リアルタイムの検出は、許可されたユーザーが最近発生した脅威を特定して分析できるリアルタイム レポートです。 既定では、このレポートには、エクスプローラーと同様に過去7日間のデータが表示されます。

リアルタイム検出には、マルウェア (電子メールとコンテンツなど)、送信、およびフィッシングなどのビューが含まれます。 リアルタイム検出の違いをエクスプローラーと比較するには、 [この PDF をダウンロード](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)してください。

エクスプローラー (Microsoft Defender for Office 365 プラン 2) およびリアルタイム検出 (Microsoft Defender for Office 365 プラン 1) の詳細については、「 [脅威エクスプローラー (およびリアルタイム検出)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)」を参照してください。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威のトラッカー](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) は、組織に影響を与える可能性がある cybersecurity の問題に関するインテリジェンスを承認されたユーザーに提供する情報ウィジェットとビューです。

### <a name="automated-incident-response"></a>インシデント対応の自動化

Defender for Office 365 プラン2で利用できる[自動インシデント対応](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)(エア) 機能により、現在存在している既知の脅威への対応として、自動化された調査プロセスを実行することができます。 自動化された特定の調査タスクによって、セキュリティ運用チームはより効率的かつ効果的に操作できるようになります。 ウイルス対策アクション (悪意のある電子メールメッセージの削除など) は、セキュリティ運用チームによる承認に基づいて行われます。 詳細については、「 [Office 365 での空気の仕組み](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)」を参照してください。

### <a name="attack-simulator"></a>攻撃シミュレータ

[アタックシミュレータ](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) を使用すると、承認されたユーザーが組織内で現実的な攻撃シナリオを実行できます。 表示名のスピアーフィッシング攻撃、パスワードスプレー攻撃、ブルートフォースパスワード攻撃など、さまざまな種類の攻撃が利用可能です。
