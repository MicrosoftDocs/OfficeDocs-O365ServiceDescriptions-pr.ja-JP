---
title: Microsoft Defende for Office 365 サービス説明書
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
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。
ms.openlocfilehash: 5781f34419eb697cb97634c55fa486fd141d76dd
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204844"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defende for Office 365 サービス説明書

Microsoft Defender for Office 365 は、フィッシング、ビジネス メール侵害、マルウェア攻撃など、電子メールやコラボレーション ツールに対する高度な脅威から組織を保護するのに役立つクラウドベースの電子メール フィルター サービスです。 また、セキュリティ チームOffice 365脅威を特定、優先順位付け、調査、および対応するために、調査、捜し、修復機能も提供します。

メッセージ保護に Defender for Office 365 を使用できる基本的な方法として、次のようなものがあります。

- Defender for Office 365 のフィルタリングのみのシナリオでは、Defender for Office 365 はオンプレミスの Exchange Server 環境、その他のオンプレミス SMTP メール ソリューションにクラウドベースのメール保護を提供します。

- Defender for Office 365 は、Exchange Online クラウドにホストされているメールボックスを保護することができます。 Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。

- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信メール フィルタリングに Exchange Online Protection を併用するように Defender for Office 365 を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。

## <a name="available-plans"></a>使用できるプラン

Microsoft Defender for Office 365 のユーザーを有効にするサブスクリプションの詳細なプラン情報については、[完全なサブスクリプション比較表](https://go.microsoft.com/fwlink/?linkid=2139145)を参照してください。

## <a name="feature-availability"></a>機能の可用性

次の表に、複数のプランで利用可能な機能Office 365 Microsoft Defender の主要な一覧を示します。 特定の注意点が適用されます。 詳細については、脚注を参照してください。 この表は、予告なしに変更される場合があります。 プラン全体の機能に関する最新の Microsoft Defender の完全なOffice 365については[、「Microsoft Defender for Office 365 機能](microsoft-defender-for-office-365-features.md)サービスの説明」を参照してください。

| 特徴 | Microsoft Defender for Office 365 プラン 1 | Defender for Office 365 プラン 2 | Microsoft 365 E5 Security または A5 Security |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *構成、保護、検出* | | | |
| 事前設定されたセキュリティ ポリシーと Configuration Analyzer | はい | はい | はい |
| [安全な添付ファイル](microsoft-defender-for-office-365-features.md#safe-attachments) | はい | はい | はい |
| Teams の安全な添付ファイル | はい | はい | はい |
| [安全なリンク](microsoft-defender-for-office-365-features.md#safe-links) | はい | はい | はい |
| [安全なドキュメント](microsoft-defender-for-office-365-features.md#safe-documents) | いいえ | いいえ | はい |
| Teams の安全なリンク | はい | はい | はい |
| レポート メッセージ Add-In | はい | はい | はい |
| [ユーザー、SharePoint、OneDrive、およびMicrosoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | はい | はい | はい |
| [フィッシング詐欺対策ポリシー](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | はい | はい | はい |
| [リアルタイム レポート](microsoft-defender-for-office-365-features.md#real-time-reports) | はい | はい | はい |
| 内部メールの高度な保護 | はい | はい | はい |
| *自動化、調査、修復、教育* | | | |
| [脅威トラッカー](microsoft-defender-for-office-365-features.md#threat-trackers) | いいえ | はい | はい |
| キャンペーン ビュー | いいえ | はい | はい |
| 脅威の調査 (高度な脅威調査) | [リアルタイムの検出](microsoft-defender-for-office-365-features.md#real-time-detections) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [自動調査&応答](microsoft-defender-for-office-365-features.md#automated-investigation--response) | いいえ | はい | はい |
| [攻撃シミュレーション トレーニング](microsoft-defender-for-office-365-features.md#attack-simulation-training) | いいえ | はい | はい |
| *[Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender) との統合* | いいえ | はい | はい |

> [!NOTE]
> Microsoft Defender for Office 365は、ユーザーのMicrosoft 365 Defender。 ドメイン間のセキュリティを自動化する方法の詳細については、「Microsoft 365 Defender要件[Microsoft 365 Defender参照してください](/microsoft-365/security/mtp/prerequisites)。

## <a name="learn-more"></a>詳細情報

Microsoft Defender for Office 365については、以下のリソースを参照してください。

- [Microsoft Docs Office 365の Microsoft Defender](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Defender for Office 365 Web サイト](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Microsoft Defender for Office 365ブログ](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Microsoft Defender for Office 365 フォーラム](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>ライセンス条項

Microsoft 商用ボリューム ライセンス プログラムを通じて購入した製品およびサービスのライセンス条件については、「製品条項」 [サイトを参照してください](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>メッセージング

新機能や変更された機能、計画されたメンテナンス、その他の重要なアナウンスなど、今後の変更について情報を得る場合は、メッセージ センターにアクセスしてください。 詳細については、「メッセージ センター」 [を参照してください](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>アクセシビリティ

Microsoft は、お客様のデータのセキュリティとサービスのアクセシビリティに引き [続きコミット](https://www.microsoft.com/trust-center/compliance/accessibility) しています。 詳細については[、「Microsoft Trust Center」](https://www.microsoft.com/trust-center)および「アクセシビリティ センター Office[参照してください](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
