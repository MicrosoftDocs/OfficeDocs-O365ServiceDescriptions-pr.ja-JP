---
title: セキュリティ/コンプライアンス センター
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5a693243-2f13-4c7e-af1a-779c0752ae35
description: セキュリティ コンプライアンス &amp; センターは、組織の 365 全体のコンプライアンスOfficeを管理するために設計されています。 既存の SharePoint および Exchange のコンプライアンス機能へのリンクにより、Office 365 全体のコンプライアンス機能を一つにまとめます。
ms.openlocfilehash: 4daf754f5472620482eced63a9970b05a4e61a6c
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460196"
---
# <a name="security-amp-compliance-center"></a>セキュリティ/コンプライアンス センター

セキュリティ [コンプライアンス &amp; センターは](https://protection.office.com/) 、組織の 365 全体のコンプライアンスOfficeを管理するために設計されています。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

2020 年 4 月 1 日の Microsoft 365 コンプライアンス機能のメリットをユーザーにライセンスするためのオプションを確認するには、詳細な Microsoft 365 コンプライアンス ライセンス比較をダウンロードしてください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>ビジネス &amp; およびエンタープライズ プランのセキュリティ コンプライアンス センターの可用性

| 機能 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1、 Office 365 US Government G1 | Office 365 E3, Office 365 US Government G3 | Office 365 E5 | Office 365 F3、 Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |
|[Exchange Online、SharePoint Online、OneDrive for Business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup>のデータ損失防止 | いいえ | いいえ  |はい   | はい | はい | はい | いいえ  |
|[手動の感度ラベル](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | いいえ | いいえ  |いいえ   | はい | はい | はい | いいえ  |
|[電子情報開示のケース](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |
|[電子情報開示ホールド (クエリ ベースの電子情報開示ホールドを含む)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |いいえ   |いいえ   |いいえ  |いいえ   |はい   |はい   |いいえ   |
|[電子情報開示のエクスポート](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |はい   |いいえ   |
|[基本監査](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |はい   |はい   |はい|はい   |はい   |はい   |はい   |
|[Office 365 メッセージ暗号化 (OME) Basic](https://docs.microsoft.com/microsoft-365/compliance/ome)  |いいえ   |いいえ   |いいえ   |いいえ   |はい  |はい   |いいえ   |

<sup>1</sup> 基本監査 (E5 を除く) を含むすべてのプランの監査ログは、90 日間保持されます。 E5 には高度な監査が含まれるため、監査ログは最大 1 年間保持されます。 また [、365 管理アクティビティ API Office使用](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) して、統合監査ログからイベントを取得できます。

<sup>2</sup> 365 Office防止アドオンが必要です。

<sup>3</sup> つの感度ラベルは、Azure Information Protection P1 および P2 にも含まれています。

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>スタンドアロン &amp; プランのセキュリティ コンプライアンス センターの可用性

| 機能 | Exchange Online プラン 1 | Exchange Online プラン 2 | Exchange Online Kiosk | SharePoint Online プラン 1 | SharePoint Online プラン 2 | OneDrive for Business プラン 1 | OneDrive for Business (プラン 2) | Skype for Business Online プラン 1 | Skype for Business Online プラン 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |はい   |
|[メール フィルター](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)やマルウェア対策などの脅威管理   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |
|[フィッシング キャンペーンの](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)脅威エクスプローラーなど、高度な脅威管理   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ  |
|[カスタマー ロックボックス](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[モバイル デバイス管理](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |
|[Exchange Online、SharePoint Online、OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>のデータ損失防止  |いいえ   |はい   |いいえ   |いいえ   |はい <sup>7<sup>  |いいえ  |は<sup>い 10</sup> |いいえ   |はい   |
|[Microsoft Teams の通信データ損失防止](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[情報障壁](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[情報ガバナンス](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |はい<sup>2</sup>  |はい   |はい   |はい   |はい   |は<sup>い 10</sup>  |は<sup>い 10</sup>  |はい   |はい   |
|[高度な情報ガバナンス](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[コンテンツ検索](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |はい   |はい   |はい   |はい   |はい  | は<sup>い 10</sup>  |は<sup>い 10</sup>  |はい   |はい   |
|[電子情報開示のケース](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |はい   |はい   |はい   |はい   |はい   |は<sup>い 10</sup>  |は<sup>い 10</sup>  |いいえ   |いいえ   |
|[電子情報開示のエクスポート](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |いいえ   |はい   |いいえ   |いいえ   |はい   |いいえ  |は<sup>い 10</sup> |いいえ<sup>4</sup>  |いいえ<sup>4</sup>  |
|[電子情報開示ホールド (クエリ ベースの電子情報開示ホールドを含む)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |いいえ   |はい   |いいえ   |いいえ   |はい   |いいえ  |は<sup>い 10</sup> |いいえ<sup>4</sup>  |いいえ<sup>4</sup>  |
|[Advanced eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[Exchange Online の制限](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |いいえ   |はい   |いいえ   |はい   |はい   |は<sup>い 10</sup> |は<sup>い 10</sup>  |いいえ   |いいえ   |
|[基本監査](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|はい|はい|はい|はい|はい|は<sup>い 10</sup>|は<sup>い 10</sup>|いいえ|いいえ|
|高度な監査|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|
|[コミュニケーション コンプライアンス (監督ポリシー)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[Office 365 Message Encryption (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |いいえ   |はい   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|
|[Office 365 Advanced Message Encryption](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|
|[特権アクセス管理](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|

<sup>1 情報</sup> ガバナンスを使用すると、ユーザーはドキュメントにラベルを作成、発行、手動で適用できます。ドライブの出荷またはネットワークを使用してデータをインポートします。 これらの機能は E3 および E5 で利用できます。E1 の可用性は限られています。 E1、E3、および E5 で使用可能な機能の完全な一覧については、詳細な Microsoft 365 コンプライアンス ライセンス比較を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> アドオンの購入Exchange Online Archiving必要です。

<sup>3</sup> 高度な情報ガバナンスを使用すると、保持ポリシーまたは削除ポリシーまたは両方に基づいて情報を分類することにより、重要な情報を保持し、重要な情報を削除できます。 これには、ポリシーの推奨、データへのラベルの自動適用、機密データ型またはクエリに基づくラベルの適用、廃棄レビュー、スマート インポート フィルターの使用などのインテリジェント/自動化されたアクションが含まれます。 また、セキュリティとコンプライアンスの目的で従業員のコミュニケーションを確認する監督機能も含まれています。

<sup>4</sup> Skype の会話はメールボックスの一部として格納されます。

<sup>5</sup> Advanced eDiscovery には、Office 365 E5 またはアドオン ライセンスが必要です。

<sup>6</sup> Skype アーカイブは、ユーザーのメールボックス内です。

<sup>7</sup> Microsoft Teams リポジトリに格納されているファイルが含まれます。

<sup>8</sup> 基本監査を含むすべてのプランの監査ログは、90 日間保持されます。 また [、365 管理アクティビティ API Office使用](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) して、統合監査ログからイベントを取得できます。

<sup>9</sup> 365 Office防止アドオンが必要です。

<sup>10</sup> OneDrive for Business に保存されているファイルに制限されています。

<sup>11</sup> アイテム保持ポリシーを使用してユーザー メールボックスを保留にExchange Online Archiving Exchange Online プラン 2 またはユーザー ライセンスが必要です。
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

コンプライアンス センターは、21Vianet がOffice 365 の E3 プランで利用できます。
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

セキュリティ &コンプライアンス センターは、365 ドイツOffice利用できます。 365 ドイツOfficeについては [、「365 germany Officeを参照してください](office-365-germany.md)。
