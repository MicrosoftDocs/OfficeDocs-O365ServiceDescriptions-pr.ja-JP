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
description: セキュリティ コンプライアンス &amp; センターは、組織の Office 365 全体でコンプライアンス機能を管理するのに役立ちます。 既存の SharePoint および Exchange のコンプライアンス機能へのリンクにより、Office 365 全体のコンプライアンス機能を一つにまとめます。
ms.openlocfilehash: 4537008977f19ef947ea0bae9a4164cfbe9991d4
ms.sourcegitcommit: ee08ab6a47235054d5029807ab79fba546326273
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/31/2020
ms.locfileid: "49740968"
---
# <a name="security-amp-compliance-center"></a>セキュリティ/コンプライアンス センター

セキュリティ [コンプライアンス &amp; センターは、](https://protection.office.com/) 組織の Office 365 全体でコンプライアンス機能を管理するのに役立ちます。 Links to existing SharePoint and Exchange compliance features bring together compliance capabilities across Office 365.
  
> [!NOTE]
> Currently, many of the compliance features are still accessible through service-specific management interfaces, such as the Exchange admin center (EAC). However, this will change in the future as more service-independent compliance features are added to the Security &amp; Compliance Center.

2020 年 4 月 1 日現在の Microsoft 365 コンプライアンス機能の恩恵を受けるユーザーにライセンスを提供するためのオプションを確認するには、詳細な Microsoft 365 コンプライアンス ライセンス比較をダウンロードしてください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)
  
## <a name="security-amp-compliance-center-availability-for-business-and-enterprise-plans"></a>ビジネス &amp; および企業向けプランのセキュリティ コンプライアンス センターの可用性

| 機能 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Microsoft 365 Business Premium | Office 365 E1、Office 365 US Government G1 | Office 365 E3、Office 365 US Government G3 | Office 365 E5 | Office 365 F3、Office 365 US Government F3|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |はい   |はい   |はい   |はい   |はい   |はい   |必要   |
|[Exchange Online、SharePoint Online、OneDrive for Business](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)<sup>2</sup>のデータ損失防止 | いいえ | いいえ  |いいえ   | はい | はい | 必要 | いいえ  |
|[手動の区別ラベル](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)<sup>3</sup> | いいえ | いいえ  |いいえ   | はい | はい | 必要 | いいえ  |
|[電子情報開示のケース](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |はい   |はい   |はい   |はい   |はい   |はい   |必要   |
|[電子情報開示の保留 (クエリ ベースの電子情報開示の保留を含む)](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-4-place-content-locations-on-hold)  |いいえ   |いいえ   |いいえ  |いいえ   |はい   |必要   |いいえ   |
|[電子情報開示のエクスポート](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |必要   |いいえ   |
|[基本監査](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>1</sup> |はい   |はい   |はい|はい   |はい   |はい   |必要   |
|[Office 365 Message Encryption (OME) Basic](https://docs.microsoft.com/microsoft-365/compliance/ome)  |いいえ   |いいえ   |いいえ   |いいえ   |はい  |必要   |いいえ   |

<sup>基本監査</sup> (E5 を除く) を含むすべてのプランの監査ログは、90 日間保持されます。 E5 には高度な監査が含まれるため、監査ログは最大 1 年間保持されます。 また、Office [365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) 管理アクティビティ API を使用して、統合監査ログからイベントを取得できます。

<sup>2</sup> 365 Officeデータ損失防止アドオンが必要です。

<sup>3</sup> つの Sensitivity ラベルも Azure Information Protection P1 および P2 に含まれています。

## <a name="security-amp-compliance-center-availability-for-standalone-plans"></a>スタンドアロン &amp; プランのセキュリティ コンプライアンス センターの可用性

| 機能 | Exchange Online プラン 1 | Exchange Online プラン 2 | Exchange Online Kiosk | SharePoint Online プラン 1 | SharePoint Online プラン 2 | OneDrive for Business プラン 1 | OneDrive for Business (プラン 2) | Skype for Business Online プラン 1 | Skype for Business Online プラン 2|
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|[Access to the Security &amp; Compliance Center](https://docs.microsoft.com/office365/securitycompliance/go-to-the-securitycompliance-center)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |必要   |
|[Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |はい   |
|[脅威の](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)管理 (メール フィルターやマルウェア対策など)   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |必要   |
|[高度な脅威管理](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)(フィッシング キャンペーンの脅威エクスプローラーなど)   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ  |
|[カスタマー ロックボックス](https://docs.microsoft.com/office365/securitycompliance/customer-lockbox-requests)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[モバイル デバイス管理](https://support.office.com/article/set-up-mobile-device-management-mdm-in-office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)  |はい   |はい   |はい   |はい   |はい   |はい   |はい   |はい   |必要   |
|[Exchange Online、SharePoint Online、OneDrive for Business](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)<sup>9</sup>のデータ損失防止  |いいえ   |はい   |いいえ   |いいえ   |はい <sup>7<sup>  |いいえ  |は<sup>い 10</sup> |いいえ   |はい   |
|[Microsoft Teams の通信データ損失防止](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[情報障壁](https://docs.microsoft.com/office365/securitycompliance/information-barriers)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[情報ガバナンス](https://docs.microsoft.com/office365/securitycompliance/retention-policies)<sup>1</sup>  |はい<sup>2</sup>  |はい   |はい   |はい   |必要   |は<sup>い 10</sup>  |は<sup>い 10</sup>  |はい   |必要   |
|[高度な情報ガバナンス](https://docs.microsoft.com/office365/securitycompliance/labels)<sup>3</sup>  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[コンテンツ検索](https://docs.microsoft.com/office365/securitycompliance/search-for-content)  |はい   |はい   |はい   |はい   |必要  | は<sup>い 10</sup>  |は<sup>い 10</sup>  |はい   |必要   |
|[電子情報開示のケース](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases)  |はい   |はい   |はい   |はい   |必要   |は<sup>い 10</sup>  |は<sup>い 10</sup>  |いいえ   |いいえ   |
|[電子情報開示のエクスポート](https://docs.microsoft.com/office365/securitycompliance/ediscovery-cases#step-6-export-the-results-of-a-content-search-associated-with-a-case)  |いいえ   |はい   |いいえ   |いいえ   |はい   |いいえ  |は<sup>い 10</sup> |いいえ<sup>4</sup>  |いいえ<sup>4</sup>  |
|[電子情報開示の保留 (クエリ ベースの電子情報開示の保留を含む)](https://support.office.com/article/eDiscovery-cases-in-the-Office-365-Security-Compliance-Center-8dd335ab-29d0-41c3-8dd8-9f7c7481e60c#step3_1)  |いいえ   |はい   |いいえ   |いいえ   |はい   |いいえ  |は<sup>い 10</sup> |いいえ<sup>4</sup>  |いいえ<sup>4</sup>  |
|[Advanced eDiscovery](https://docs.microsoft.com/office365/securitycompliance/compliance20/overview-ediscovery-20)<sup>5</sup>  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[Exchange Online の制限](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)<sup>6</sup>  |いいえ   |はい   |いいえ   |はい   |必要   |は<sup>い 10</sup> |は<sup>い 10</sup>  |いいえ   |いいえ   |
|[基本監査](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)<sup>8</sup>|はい|はい|はい|はい|必要|は<sup>い 10</sup>|は<sup>い 10</sup>|いいえ|いいえ|
|高度な監査|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|
|[通信コンプライアンス (監督ポリシー)](https://docs.microsoft.com/office365/securitycompliance/supervision-policies)  |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |いいえ   |
|[Office 365 Message Encryption (OME)](https://docs.microsoft.com/microsoft-365/compliance/ome)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|
|[Office 365 Advanced Message Encryption](https://docs.microsoft.com/microsoft-365/compliance/ome-advanced-message-encryption)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|
|[特権アクセスの管理](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-overview)  |いいえ   |いいえ   |いいえ   |いいえ   |はい   |いいえ   |いいえ|いいえ|いいえ|

<sup>1 情報</sup> ガバナンスにより、ユーザーはドキュメントにラベルを作成、発行、手動で適用できます。ドライブの配送またはネットワークを使用したデータのインポート。 これらの機能は E3 および E5 で使用できます。E1 では限定的な可用性しか備えられません。 E1、E3、および E5 で使用可能な機能の完全な一覧については、Microsoft 365 コンプライアンス ライセンスの比較を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

<sup>2</sup> アドオンの購入Exchange Online Archiving必要です。

<sup>3</sup> 高度な情報ガバナンスを使用すると、保持ポリシーまたは削除ポリシー、あるいはその両方に基づいて情報を分類することにより、重要な情報を保持し、重要な情報を削除できます。 これには、ポリシーの推奨、データへのラベルの自動適用、機密データの種類またはクエリに基づくラベルの適用、廃棄レビュー、スマート インポート フィルターの使用など、インテリジェント/自動化されたアクションが含まれます。 また、セキュリティとコンプライアンスの目的で従業員の通信を確認する監督機能も含まれています。

<sup>4</sup> つの Skype 会話は、メールボックスの一部として保存されます。

<sup>5</sup> Advanced eDiscovery には、Office 365 E5 またはアドオン ライセンスが必要です。

<sup>6</sup> Skype アーカイブがユーザーのメールボックス内にある。

<sup>7 Microsoft</sup> Teams リポジトリに保存されているファイルが含まれます。

<sup>8 基本</sup> 監査を含むすべてのプランの監査ログは 90 日間保持されます。 また、Office [365](https://docs.microsoft.com/office/office-365-management-api/office-365-management-activity-api-reference) 管理アクティビティ API を使用して、統合監査ログからイベントを取得できます。

<sup>9</sup> 365 Officeデータ損失防止アドオンが必要です。

<sup>10</sup> OneDrive for Business に保存されているファイルに限定されます。

<sup>11</sup> アイテム保持ポリシーを使用Exchange Online Archivingメールボックスを保持するには、Exchange Online プラン 2 または exchange Online プラン 2 または exchange Exchange Online Archivingライセンスが必要です。
  
## <a name="security-amp-compliance-center-availability-in-office-365-operated-by-21vianet"></a>Security &amp; Compliance Center availability in Office 365 operated by 21Vianet

コンプライアンス センターは、21Vianet が運用している Office 365 の E3 プランで利用できます。
  
## <a name="security-amp-compliance-center-availability-in-office-365-germany"></a>Security &amp; Compliance Center availability in Office 365 Germany

Security & Compliance Center は、365 Germany Office利用できます。 365 Germany Officeについては、「365 Germany [Office参照してください](office-365-germany.md)。
