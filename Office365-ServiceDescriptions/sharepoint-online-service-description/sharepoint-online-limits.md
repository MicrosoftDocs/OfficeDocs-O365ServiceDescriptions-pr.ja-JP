---
title: SharePoint Online の制限
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 Enterprise プランとスタンドアロン プランの場合の SharePoint Online の制限について説明します。
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848692"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online の制限

Office 365 の計画および SharePoint Online のスタンドアロン プランの SharePoint の制限を検索します。
  
## <a name="limits-by-plan"></a>計画での制限

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 には、ビジネスに関する重要事項またはビジネス プレミアム** <br/> |**1 または 2 office 365 エンタープライズ E1、E3、E5、または SharePoint のオンライン プラン** <br/> | **Office 365 Enterprise F1** <br/> |
|記憶域<sup>1、2</sup> <br/> |1 組織につき 1 TB とライセンスの購入に 10 GB  <br/> |1 組織につき 1 TB と 1 ライセンスあたり 10 GB<sup>3</sup>を購入しました。 <br/> |1 組織につき 1 TB <sup>3</sup> <br/> |
|サイト コレクションの記憶域  <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>5</sup> <br/> |
|組織ごとのサイト コレクション  <br/> |500,000<sup>6</sup> <br/> |500,000<sup>6</sup> <br/> |500,000<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> SharePoint のオンライン ストレージの追加の無制限の量を購入することができます。[サブスクリプションの記憶域の変更](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)を参照してください。<br/><sup>2</sup>をごみ箱を監視し、定期的に空にすることお勧めします。使用する記憶領域は、組織の合計のファイルの格納域の制限の一部です。<br/> <sup>3</sup> Office 365 サブスクリプションと SharePoint Online スタンドアロン プランを持っている場合は、記憶域の量が追加されます。<br/><sup>4</sup> SharePoint Online の管理者は、サイト コレクションおよびサイトの記憶域の制限を設定できます。<br/> <sup>5</sup>キオスク ワーカーは、SharePoint Online サイト コレクションを管理することはできません。キオスクのサイト コレクションを管理するために少なくとも 1 つのエンタープライズ ユーザーのライセンスが必要です。<br/> <sup>6</sup> ライセンス ユーザーごとに作成される OneDrive for Business サイト コレクションは含まれません。<br/><sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  

  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

- **リストおよびライブラリ内の項目**の一覧は、最大 30 個のアイテムを持つことができ、ライブラリは、最大 30 個のファイルとフォルダーを持つことができます。ビューには、最大 12 のルックアップ列を持つことができます。大規模なリストを表示するための他の制限に関する詳細については、 [Office 365 の大規模なリストとライブラリの管理](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)を参照してください。ファイル名に使用できない文字については、[ファイルとフォルダー名に無効な文字](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)を参照してください。

- **ファイルのサイズとファイル パスの長さ**が 15 GB です。新しい OneDrive 同期クライアント (OneDrive.exe) を使用する場合の制限と制限の詳細については、[無効なファイル名と OneDrive、ビジネス、および SharePoint の OneDrive 内のファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)を参照してください。

- **同期**の最適なパフォーマンスを得るには、お勧め 300,000 台を超えることはないのファイルを格納する単一の OneDrive またはチーム サイトのライブラリにします。SharePoint Online を格納できるライブラリあたりのドキュメント数 3,000万を最適なパフォーマンスをお勧め 300,000 を超えるファイルをすべてのドキュメント ライブラリの間で同期します。さらに、これらのライブラリのすべてのアイテムを同期ができない場合でも 300,000 項目以上、同期するすべてのライブラリがある場合、同じパフォーマンスの問題が発生します。ビジネス同期クライアント (Groove.exe) の前の OneDrive を使用する場合 (チーム サイトごとに 5,000 のアイテムを含む)、20,000 個のアイテムは、1 つのライブラリの同期の制限。

- **バージョン**- 50,000 のメジャー バージョンとマイナー バージョンが 511。

- **SharePoint グループ**にユーザーが 5,000 のグループに属することができ、各グループは、最大 5,000 人のユーザーを持つことができます。サイト コレクションごとに最大 10,000 のグループを持つことができます。

- **管理されたメタデータ**の用語ストア、1,000 のグローバル用語セットでは、1,000 のグループで 200,000 の用語です。

- **サブサイト**のサイト コレクションごとの 2,000 までです。

- **SharePoint でホストされているアプリケーション**- 1 組織につき 20,000 個のインスタンスです。

- **リストまたはライブラリごとに一意のセキュリティ スコープ**- 5,000 です。大規模なリストは、可能な限り少ない権限を持つをデザインします。

- **ユーザー**のサイト コレクションごとに 200万。

> [!NOTE]
> SharePoint Online のサイト コレクションに招待できる外部ユーザーの数に制限はありません。詳細については、「[SharePoint Online 環境の外部共有を管理する](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint Online の検索制限](/sharepoint/search-limits)