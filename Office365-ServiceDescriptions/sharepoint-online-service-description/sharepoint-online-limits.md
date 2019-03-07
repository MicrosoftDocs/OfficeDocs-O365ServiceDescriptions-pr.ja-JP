---
title: SharePoint Online の制限
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 Enterprise プランとスタンドアロン プランの場合の SharePoint Online の制限について説明します。
ms.openlocfilehash: c1b6185c46be6f1343e6679a5b887bab5b393708
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467874"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online の制限

Office 365 プランおよび sharepoint Online スタンドアロンプランの sharepoint の制限について説明します。
  
## <a name="limits-by-plan"></a>プランによる制限

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 business Essentials または business Premium** <br/> |**Office 365 Enterprise E1、E3、E5、または SharePoint Online プラン1または2** <br/> | **Office 365 Enterprise F1** <br/> |
|記憶域<sup>1、2</sup> <br/> |1組織につき 1 TB、および購入したライセンスごとに 10 GB  <br/> |1組織につき 1 TB、さらに購入<sup></sup>したライセンスごとに 10 GB <br/> |1 組織につき 1 TB <sup>3</sup> <br/> |
|サイト コレクションの記憶域  <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>5</sup> <br/> |
|組織ごとのサイトコレクション  <br/> |50万<sup>6</sup> <br/> |50万<sup>6</sup> <br/> |500,000<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> SharePoint Online の記憶域を追加で購入できる量に制限はありません。 「 [サブスクリプションの記憶域を変更する](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用される記憶領域は、組織の合計ファイル容量の上限に含まれます。 
<br/> <sup>3</sup> Office 365 サブスクリプションと SharePoint Online スタンドアロン プランを持っている場合は、記憶域の量が追加されます。 
<br/><sup>4</sup> SharePoint Online 管理者は、サイトコレクションとサイトの記憶域の制限を設定できます。
<br/> <sup>5</sup> Kiosk ワーカーは SharePoint Online サイト コレクションを管理できません。 Kiosk サイト コレクションを管理するには、少なくとも 1 つの Enterprise ユーザーのライセンスが必要です。 
<br/> <sup>6</sup> ライセンス ユーザーごとに作成される OneDrive for Business サイト コレクションは含まれません。 
<br/><sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  

  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービス制限

- リスト**とライブラリ内のアイテム**-リストは最大3000万個のアイテムを持つことができ、ライブラリは最大で3000万のファイルとフォルダーを持つことができます。 ビューは最大12個のルックアップ列を持つことができます。 大きなリストを表示するためのその他の制限の詳細については、「 [Office 365 の大規模なリストとライブラリを管理](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)する」を参照してください。 ファイル名に使用できない文字については、「[ファイル名とフォルダー名の無効な文字](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **ファイルサイズとファイルパスの長さ**-15 GB。 新しい onedrive 同期クライアント (onedrive) を使用する際の制限事項と制限の詳細については、「 [onedrive、onedrive for business、および SharePoint の無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **サイトコレクション間での移動とコピー** –操作ごとに 100 GB。 web ブラウザーは開いたままにしておく必要があります。

- **同期**-最適なパフォーマンスを実現するために、1つの OneDrive またはチームサイトライブラリに30万個を超えるファイルを保存することをお勧めします。 SharePoint Online では、ライブラリごとに3000万のドキュメントを格納できますが、最適なパフォーマンスを実現するには、すべてのドキュメントライブラリで30万ファイルを1つ以上同期することをお勧めします。 また、すべてのライブラリのアイテムを同期していない場合でも、同一のパフォーマンスの問題が発生する可能性があります。 以前の OneDrive for business 同期クライアント (Groove) を使用している場合、ライブラリあたりの同期制限は2万アイテム (チームサイトごとの5000アイテムを含む) です。

- **バージョン**-5万メジャーバージョンと511マイナーバージョン。

- **SharePoint グループ**-ユーザーは5000グループに属することができ、各グループは最大5000ユーザーを持つことができます。 サイトコレクションごとに最大で1万グループを割り当てることができます。

- **Managed metadata** -用語ストアの20万用語、1000グローバル用語セット、1000グループ。

- **サブ**サイト-サイトコレクションあたり最大2000。

- **SharePoint でホスト**されるアプリケーション-組織ごとに2万インスタンス。

- **リストまたはライブラリごとの固有のセキュリティスコープ**-5000。 大規模なリストについては、可能な限り固有のアクセス許可を設定するように設計します。

- **ユーザー** -サイトコレクションごとに200万。

> [!NOTE]
> SharePoint Online サイトコレクションに招待できる外部ユーザーの数に制限はありません。 詳細については、「[SharePoint Online 環境の外部共有を管理する](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint Online の検索の制限](/sharepoint/search-limits)