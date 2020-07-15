---
title: Skype for Business Online の制限
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- skype-for-business-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: bf5b04bf-8506-40e1-a6b6-7503fe24b37b
description: Skype for Business Online の制限は、次のカテゴリに分類されます。
ms.openlocfilehash: 6f9cf165c2b0bf9408ce0801740bb3abf0caa5a4
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131021"
---
# <a name="skype-for-business-online-limits"></a>Skype for Business Online の制限

Skype for Business Online の制限は、以下のカテゴリに分類されます。
  
- [ピアツーピア制限](skype-for-business-online-limits.md#peer-to-peer-limits)
    
- [会議の制限](skype-for-business-online-limits.md#meeting-limits)
    
- [会議の保存期限](skype-for-business-online-limits.md#meeting-retention-limits)
    
- [分数の制限](skype-for-business-online-limits.md#minute-limits)
    
> [!NOTE]
> Microsoft 365 組織に適用される制限は、その組織がサービスに登録されている期間によって異なる場合があります。 Microsoft データセンターで制限が変更されると、既存のすべてのユーザーにその変更が適用されるまでしばらく時間がかかる可能性があります。 
  
## <a name="peer-to-peer-limits"></a>ピアツーピア制限
<a name="bkmk_P2P_LyncOnlineLimits"> </a>

- **File transfer limit** The maximum size of a file that can be transferred in a Skype for Business Online IM conversation. To learn which file types are blocked for file transfer, see the Microsoft Support article about [sending and receiving files or attachments in Skype for Business Online](https://go.microsoft.com/fwlink/?LinkId=398280).
    
- **開かれたタブ付き会話数の制限** Skype for Business ユーザーが同時に開くことのできる会話タブの最大数。 
    
### <a name="peer-to-peer-limits"></a>ピアツーピア制限 

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Skype for Business Server 2015** <br/> |**Microsoft 365 Business Basic** <br/> |**Microsoft 365 Business Standard** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise F3** <br/> |
|ファイル転送制限  <br/> |無制限  <br/> |制限なし  <br/> |制限なし  <br/> |制限なし  <br/> |制限なし  <br/> |該当なし  <br/> |
|会話数の制限<sup>1</sup> <br/> |99  <br/> |99  <br/> |99  <br/> |99  <br/> |99  <br/> |99  <br/> |
|開かれたタブ付き会話数の制限  <br/> |50  <br/> |50  <br/> |50  <br/> |50  <br/> |50  <br/> |該当なし  <br/> |
   
> [!NOTE]
> <sup>1</sup> A client can start a chat with up to 99 users by either manually adding them or sending an instant message from the context menu of a group or distribution list. For more information about instant messaging in Skype for Business Online, see [Send an IM in Skype for Business](https://go.microsoft.com/fwlink/?linkid=533412). 
  
### <a name="peer-to-peer-limits-across-standalone-options"></a>スタンドアロンの各オプションでのピアツーピア制限

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Skype for Business Server 2015** <br/> |**Skype for Business Online スタンドアロン プラン 1** <br/> |**Skype for Business Online スタンドアロン プラン 2** <br/> |
|ファイル転送制限  <br/> |無制限  <br/> |制限なし  <br/> |制限なし  <br/> |
|会話数の制限<sup>1</sup> <br/> |99  <br/> |99  <br/> |99  <br/> |
|開かれたタブ付き会話数の制限  <br/> |50  <br/> |50  <br/> |50  <br/> |
   
> [!NOTE]
> <sup>1</sup> A client can start a chat with up to 99 users by either manually adding them or sending an instant message from the context menu of a group or distribution list. For more information about instant messaging in Skype for Business Online, see [Send an IM in Skype for Business](https://go.microsoft.com/fwlink/?linkid=533412). 
  
## <a name="meeting-limits"></a>会議の制限

- **ファイルのアップロード制限** 配布資料や PowerPoint プレゼンテーションなど、Skype for Business 会議にアップロードできるファイルの最大サイズ。 
    
- **Skype for Business 会議の参加者数** 単一の Skype for Business 会議に参加できる参加者 (プレゼンターを含む) の最大数。 
    
- **Skype for Business 会議のプレゼンター数** 単一の Skype for Business 会議でのプレゼンターの最大数。 
    
- **Skype for Business Web アプリ会議の参加者数** 会議に参加できる Skype for Business Web アプリ会議参加者の最大数。 
    
- **Skype for Business Web アプリの匿名参加者数** 会議に匿名で参加できる Skype for Business Web アプリ会議参加者の最大数。 
    
- **電話で参加するゲスト数** 会議に電話で参加できるゲストの最大数。 
    
### <a name="meeting-limits"></a>会議の制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Skype for Business Server 2015** <br/> |**Microsoft 365 Business Basic** <br/> |**Microsoft 365 Business Standard** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise F3** <br/> |
|ファイルのアップロード制限  <br/> |500 MB  <br/> |500 MB  <br/> |500 MB  <br/> |500 MB  <br/> |500 MB  <br/> |該当なし  <br/> |
|Skype for Business 会議の参加者数<sup>1</sup> <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |該当なし  <br/> |
|Skype for Business 会議のプレゼンター数  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |該当なし  <br/> |
|Skype for Business Web アプリ会議の参加者数  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |該当なし  <br/> |
|Skype for Business Web アプリの匿名参加者数  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |該当なし  <br/> |
|電話で参加するゲスト  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |該当なし  <br/> |
|チーム呼び出しグループ内の個人  <br/> |まで  <br/> |まで  <br/> |まで  <br/> |まで  <br/> |まで  <br/> |該当なし  <br/> |
   
> [!NOTE]
> <sup>1</sup> If the number of participants in a Skype for Business meeting exceeds 75 participants, then the participant list (presenters and attendees) in the meeting roster will be truncated so that an individual attendee sees only the presenters and the individual attendee's own name. The full participant list remains visible to the presenters in the meeting. Also, Gallery View and IM errors are hidden from the attendees. 
  
### <a name="meeting-limits-across-standalone-options"></a>スタンドアロンの各オプションでの会議の制限

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Skype for Business Server 2015** <br/> |**Skype for Business Online スタンドアロン プラン 1** <br/> |**Skype for Business Online スタンドアロン プラン 2** <br/> |
|ファイルのアップロード制限  <br/> |500 MB  <br/> |該当しない  <br/> |500 MB  <br/> |
|Skype for Business 会議の参加者数  <br/> |250  <br/> |該当なし  <br/> |250  <br/> |
|Skype for Business 会議のプレゼンター数  <br/> |250  <br/> |該当なし  <br/> |250  <br/> |
|Skype for Business Web アプリ会議の参加者数  <br/> |250  <br/> |該当なし  <br/> |250  <br/> |
|Skype for Business Web アプリの匿名参加者数  <br/> |250  <br/> |該当なし  <br/> |250  <br/> |
|電話で参加するゲスト  <br/> |250  <br/> |該当なし  <br/> |250  <br/> |
|チーム呼び出しグループ内の個人  <br/> |まで  <br/> |該当なし  <br/> |まで  <br/> |
   
## <a name="meeting-retention-limits"></a>会議の保存期限

- **会議コンテンツの保存期限** 最後のユーザーが会議を退席してから、アップロードされた会議コンテンツが完全に削除されるまで Skype for Business に保持される時間。 
    
- **会議の有効期限** 会議が終了した後でユーザーが会議にアクセスできる時間。 
    
### <a name="meeting-retention-limits-across-plans"></a>プラン間での会議の保存制限

> [!NOTE]
> 各ユーザーは、いつでも最大 1,000 件の会議をデータベースに保存できます。 
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**会議の種類** <br/> |**説明** <br/> 
|1 回限りの会議| 会議は、スケジュールされた時刻または最後の会議の更新、または最後の会議の更新のうち14日以内にアクセス可能になります。
|終了日が設定された定期的な会議| 少なくとも、最後の会議が予定されている終了時刻以降、または最後の会議の更新または最後の会議の更新のうち14日後に、会議にアクセスできるようになります。
|終了日を含まない定期的な会議| 新しい会議の参加 (ライセンス認証) がある場合、または1年に1回以上のスケジュール更新が行われた場合、常に会議にアクセスできるようになります。
|即時会議|少なくとも8時間、会議にアクセスできるようになります。

## <a name="minute-limits"></a>分数の制限

国内通話プランまたは国際通話プランの分数の制限については、「[電話会議と通話プランの国および地域の可用性](https://docs.microsoft.com/microsoftteams/country-and-region-availability-for-audio-conferencing-and-calling-plans/country-and-region-availability-for-audio-conferencing-and-calling-plans)」を参照してください。
  