---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。
ms.openlocfilehash: 3295bf261c9412f5881a16e3bc17088f32b4a18e
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734175"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection サービスの説明

Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。

メッセージ保護に対して ATP を使用する主な方法は次のとおりです。

- Office 365 ATP のフィルター処理のみのシナリオでは、オンプレミスの Exchange Server 環境またはその他の社内 SMTP 電子メールソリューションに対して、クラウドベースの電子メール保護を ATP が提供します。

- Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 Advanced Threat Protection (ATP) の可用性

ATP は、Office 365 Enterprise E5、Office 365 エデュケーション A5、および Microsoft 365 Business に含まれています。

ATP は、次の Exchange と Office 365 サブスクリプション プランに追加できます。

- Exchange Online プラン 1

- Exchange Online プラン 2

- Exchange Online Kiosk

- Exchange Online Protection

- Office 365 Business Essentials

- Office 365 Business Premium

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F1

- Office 365 A1

- Office 365 A3

Office 365 Advanced Threat Protection を購入するには、「[Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)」を参照してください。

プランの機能を比較するには、「 [Office 365 For Business プランの比較](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」を参照して、[適切な Microsoft 365 Enterprise ソリューションを見つけ](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)てください。

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の新機能

引き続き Office 365 ATP に新機能を追加しています。 ATP (または Microsoft 365 全般) に出てくる新機能の詳細については、以下のリソースを参照してください。

- [Microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP の新機能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の要件

ATP は、Microsoft Exchange Server などの任意の SMTP メール転送エージェントで使用できます。 ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Advanced Threat Protection (ATP) の各プランで利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。

|**機能**|**ATP プラン1**<br>(旧称 ATP スタンドアロン)|**ATP プラン2**<br>(以前の脅威インテリジェンス <br>スタンドアロン| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*構成、保護、および検出*|
|添付ファイル保護|はい|はい|はい|
|リンク保護|はい|はい|はい|
|フィッシング対策ポリシー|はい|はい|はい|
|SharePoint、OneDrive、Microsoft Teams 用の ATP|はい|はい|はい|
|Teams での安全な添付ファイル|はい|はい|はい|
|Teams での安全なリンク|いいえ|いいえ|いいえ|
|リアルタイムレポート|はい|はい|はい|
|*自動化、調査、修復、教育*|
|脅威トラッカー|いいえ|はい|はい|
|エクスプローラー (高度な脅威調査)|いいえ|はい|はい|
|インシデント対応の自動化|いいえ|はい|はい|
|アタックシミュレータ|いいえ|はい|はい|

## <a name="advanced-threat-protection-atp-capabilities"></a>Advanced Threat Protection (ATP) の機能

### <a name="safe-attachments"></a>添付ファイル保護

[ATP の安全な添付ファイル](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)は、不明なマルウェアやウイルスから保護され、メッセージングシステムを保護するためのゼロ日の保護を提供します。 既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、ATP がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。

> [!NOTE]
> ATP の安全な添付ファイルのスキャンは、Office 365 データが存在する地域と同じ地域で行われます。 データセンター地理の詳細については、「[データの保存場所](https://products.office.com/where-is-your-data-located?geo=All)」を参照してください。

### <a name="safe-links"></a>安全なリンク

[ATP の安全なリンク](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪意のある url からユーザーを予防的に保護します。 リンクを選択するたびに保護は保持されます。悪意のあるリンクは、適切なリンクにアクセスできるように、動的にブロックされます。

安全なリンクは、次のアプリの Url に対して使用できます。

- Office 365 ProPlus on Windows または Mac

- Web 用 Office (web 用の Word、web 用の Excel、web 用の PowerPoint、web 用の OneNote)

- Windows 上の Word、Excel、PowerPoint、および Visio と、iOS および Android デバイス上の Office アプリ

> [!NOTE]
> ユーザーが ATP<sup>\*</sup>のライセンスを持っている必要があり、Atp の安全なリンクポリシーに含まれている必要があります。また、保護のためにデバイス上でサインインする必要があります。

<sup>\*</sup>組織全体にわたる ATP のライセンス (ATP_ENTERPRISE_FACULTY など) の場合、ATP のライセンスを個々のユーザーに割り当てる必要はありません。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[ATP のフィッシング対策](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)は、メッセージがフィッシングである可能性があることを示すインジケーターの受信メッセージをチェックします。 ユーザーが ATP ポリシー (「安全な添付ファイル」、「安全なリンク」、または「フィッシング対策」) でカバーされている場合、受信メッセージは、メッセージを分析し、構成されたポリシーに基づいて適切なアクションを実行する複数の machine learning モデルによって評価されます。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、Microsoft Teams 用の ATP は、](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)チームサイトやドキュメントライブラリで悪意のあるものとして識別されたファイルを検出してブロックするのに便利です。

### <a name="real-time-reports"></a>リアルタイムレポート

Office 365 セキュリティ & コンプライアンスセンターで利用可能な監視機能には[リアルタイムのレポートと洞察](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)が含まれており、セキュリティおよびコンプライアンスの管理者が、セキュリティ攻撃などの優先度の高い問題に焦点を当てることができます。疑わしいアクティビティ。 スマートレポートと分析には、問題の領域を強調するだけでなく、データを表示して探索したり、簡単なアクションを実行したりするための推奨事項やリンクが含まれています。

### <a name="threat-trackers"></a>脅威トラッカー

[脅威のトラッカー](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)は、組織に影響を与える可能性がある cybersecurity の問題に関するインテリジェンスを承認されたユーザーに提供する情報ウィジェットとビューです。

### <a name="explorer"></a>Explorer

エクスプローラー (脅威エクスプローラーとも呼ばれます) はリアルタイムレポートで、承認されたユーザーが最近の脅威を識別して分析できるようにします。 既定では、このレポートには過去7日間のデータが表示されます。ただし、過去30日間のデータを表示するようにビューを変更することはできます。

エクスプローラー (Office 365 Advanced Threat Protection プラン 2) およびリアルタイム検出 (Office 365 Advanced Threat Protection プラン 1) の詳細については、「[脅威エクスプローラー (およびリアルタイム検出)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer)」を参照してください。

### <a name="attack-simulator"></a>アタックシミュレータ

[アタックシミュレータ](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)を使用すると、承認されたユーザーが組織内で現実的な攻撃シナリオを実行できます。 表示名のスピアーフィッシング攻撃、パスワードスプレー攻撃、ブルートフォースパスワード攻撃など、さまざまな種類の攻撃が利用可能です。
