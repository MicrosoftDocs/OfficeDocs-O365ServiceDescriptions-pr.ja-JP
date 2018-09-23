---
title: Exchange Online の制限
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: アドレス帳の制限、メールボックスの格納域の制限、およびレポートの作成とメッセージの追跡の制限などのさまざまなサービス領域については、Exchange Online の制限事項を確認してください。
ms.openlocfilehash: d366537d8747dcda202f13c65784cb4e0519604a
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036283"
---
# <a name="exchange-online-limits"></a>Exchange Online の制限

アドレス帳の制限、メールボックスの格納域の制限、およびレポートの作成とメッセージの追跡の制限などのさまざまなサービス領域については、Exchange Online の制限事項を確認してください。
  
> [!NOTE]
>  タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: > のヘルプを作成して、電子メールを送信する[電子メール](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US)です。>[ビジネスの管理のヘルプを Office 365 の電子メール](https://go.microsoft.com/fwlink/?linkid=529722)> [を修正する Outlook と Office 365 問題と、マイクロソフトのサポート Office 365 の回復時のアシスタント](https://diagnostics.office.com/)> [Office 365 の配信不能レポートを電子メールで送信](https://go.microsoft.com/fwlink/?linkid=526653)> [交換オンライン ヘルプ](https://go.microsoft.com/fwlink/?linkid=825607)
  
Microsoft Exchange Online での制限は、次のカテゴリのいずれかに収まります。
  
- [アドレス帳の制限](#abl.md)
    
- [メールボックス格納域の制限](#StorageLimits.md)
    
- [容量のアラート](#CapacityAlerts.md)
    
- [メールボックス フォルダーの制限](exchange-online-limits.md#MailboxFolderLimits)
    
- [メッセージの制限](#MessageLimits.md)
    
- [受信および送信の制限](#RecipientLimits.md)
    
- [レポート作成とメッセージ追跡の制限](exchange-online-limits.md#reporting-and-message-trace-limits)
    
- [保持の制限](#RetentionLimits.md)
    
- [配布グループの制限](#DistributionGroupLimits.md)
    
- [ジャーナル、トランスポートおよび受信トレイのルールの制限](#TransportRuleLimits.md)
    
- [モデレートの制限](#ModerationLimits.md)
    
- [Exchange ActiveSync の制限](exchange-online-limits.md#exchange-activesync-limits)
    
> [!IMPORTANT]
>  Microsoft Office 365 組織に適用される制限は、その組織がサービスに登録されている期間に応じて異なる可能性があります。Microsoft データセンターで制限が変更されると、既存のすべてのユーザーにその変更が適用されるまでしばらく時間がかかる可能性があります。 >  これらの制限の大部分は変更できませんが、注意を払う必要があります。 >  これらの制限は内部受信者と外部受信者の両方に適用されます。 >  既定では、Exchange Online Protection (EOP) は Exchange Online メールボックスを保護します。Exchange Online で EOP 機能に適用される制限については、「 [Exchange Online Protection の制限](../exchange-online-protection-service-description/exchange-online-protection-limits.md)」を参照してください。 >  Office 365 グループの制限の詳細については、「 [Office 365 グループについて](https://go.microsoft.com/fwlink/?linkid=846714)」の「グループの管理方法」を参照してください。 
  
## <a name="address-book-limits"></a>アドレス帳の制限
<a name="abl"> </a>

- **アドレス一覧の制限** Exchange Online または Exchange Server 2013 組織内で作成できるアドレス一覧の最大数。この数には、[すべての連絡先] や [すべてのグループ] など、Exchange Online の既定のアドレス一覧が含まれます。 
    
    > [!NOTE]
    > 1 つのオフライン アドレス帳 (OAB) に最大 20 個のアドレス一覧を割り当てることができます。 
  
- **オフライン アドレス帳の制限** Exchange Online または Exchange Server 2013 組織内で作成できるオフライン アドレス帳 (OAB) の最大数。 
    
- **アドレス帳ポリシーの制限** Exchange Online または Exchange Server 2013 組織内で作成できるアドレス帳ポリシー (ABP) の最大数。 
    
- **グローバル アドレス一覧** Exchange Online または Exchange Server 2013 組織内で作成できるグローバル アドレス一覧 (GAL) の最大数。 
    
### <a name="address-book-limits-across-office-365-options"></a>Office 365 オプション全体のアドレス帳の制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|アドレス一覧の制限  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|オフライン アドレス帳 (OAB) の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|アドレス帳ポリシー (ABP) の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|グローバル アドレス一覧の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>スタンドアロン プラン全体のアドレス帳制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|アドレス一覧の制限  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|オフライン アドレス帳 (OAB) の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|アドレス帳ポリシー (ABP) の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|グローバル アドレス一覧の制限  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>メールボックス格納域の制限
<a name="StorageLimits"> </a>

使用できるメールボックス格納域のサイズは、メールボックスのタイプおよびユーザーのサブスクリプション ライセンスによって決まります。管理者は、メールボックスの最大サイズをユーザーごとまたはグローバルに減らすことができます。
  
> [!NOTE]
> ジャーナリング、トランスポート ルール、または自動転送ルールを使用してアーカイブの目的のため、Exchange Online メールボックスにメッセージをコピーすることは許可されていません。ユーザーのアーカイブ メールボックスは、そのユーザー専用です。Microsoft は、ユーザーのアーカイブ メールボックスを使用して他のユーザーのアーカイブ データを格納する、インスタンスでの無制限アーカイブを拒否する権利を有します。 
  
### <a name="storage-limits-across-office-365-options"></a>Office 365 オプションの格納域の制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|ユーザー メールボックス  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|アーカイブ メールボックス<sup>7、8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |無制限<sup>1</sup> <br/> |無制限<sup>1</sup> <br/> |使用不可<sup>4</sup> <br/> |
|共有メールボックス  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|リソース メールボックス  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|サイト メールボックス<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |使用不可  <br/> |
|パブリック フォルダー メールボックス  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB の<sup>6</sup> <br/> |使用不可  <br/> |
|グループ メールボックス  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>各ユーザー最初に受け取る 100 GB のストレージ アーカイブ メールボックスにします。アーカイブの自動拡張を有効にする追加の記憶域は 100 GB のストレージ容量に達すると自動的に追加します。詳細については、 [Office 365 で無制限のアーカイブの概要](https://go.microsoft.com/fwlink/?linkid=844060)を参照してください。可用性の詳細については、 [Office 365 のロードマップ](http://go.microsoft.com/fwlink/?LinkId=509914)を参照してください。> ユーザー、共有メールボックスにアクセスする<sup>2</sup>は、Exchange Online のライセンスを取得する必要があります。共有メールボックスは、別のライセンスを必要としません。ただし、ライセンスのない共有メールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、E3 や E5 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。埋め込みアーカイブを有効にするか、共有メールボックスで、埋め込みを保持または、証拠保全を配置する場合、Exchange のオンライン計画 2 ライセンスまたは、Exchange オンライン計画 1 には、Exchange Online Archiving のライセンスが必要です。インプレース アーカイブと共有されているメールボックスのアーカイブを自動拡張を有効にする場合は、追加の記憶域はアーカイブ メールボックスの 100 GB のストレージ容量に達すると自動的に追加します。> <sup>3</sup>のリソース メールボックスは、ライセンスを必要としません。ただし、ライセンスのない共有メールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、E3 や E5 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。> <sup>4</sup> Exchange Online Kiosk でインプレース アーカイブが含まれていません。ただし、Exchange Online Archiving をアドオンとして購入できます。詳細については、 [Exchange Online Archiving サービスの説明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)を参照してください。> <sup>5</sup>サイトのメールボックスが作成され、SharePoint Online で管理します。詳細については、 [Office 365 のサイトのメールボックスを使用するための準備](http://go.microsoft.com/fwlink/p/?LinkId=299131)を参照してください。> は 50 TB、 <sup>6</sup>の 1,000 個のパブリック フォルダーのメールボックスとパブリック フォルダーのすべてのメールボックスの最大合計サイズに制限されます。> <sup>7</sup>のみのライセンスが適用されている単一のユーザーまたはエンティティ (共有されているメールボックス) などのメールをアーカイブする場所にアーカイブを使用できます。埋め込みアーカイブを使用して複数のユーザーまたはエンティティからのメールを格納するための手段としては禁止されています。などの IT 管理者は共有されているメールボックスを作成し、ユーザーがアーカイブの明示的な目的のため、([cc] または [bcc] フィールド、またはトランスポート ルールを使用) にコピーしていることはできません。複数のユーザーが使用している共有されているメールボックスは格納しないこと実際には個々 のユーザの電子メールに注意してください。複数のユーザーがアクセスを持っているし、共有メールボックスとしてメールを送信します。したがって、共有メールボックスに格納されている唯一の e メールは、こと*と*共有されているメールボックスから送信されたものです。> <sup>8</sup>ユーザーのプライマリ メールボックスが 10 MB よりも大きいだけに、メッセージがユーザーのアーカイブ メールボックスに自動的に移動、Exchange Online のリテンション ・ ポリシーを作成した場合。10 MB 未満のメールボックスのアイテム保持ポリシーは自動的に実行されません。> <sup>9</sup>共有し、リソース メールボックスは、ライセンスを必要としません。ただし、ライセンスのない共有メールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、E3 や E5 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。 
  
### <a name="storage-limits-across-standalone-plans"></a>スタンドアロン プランの格納域に関する制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|ユーザー メールボックス  <br/> |2 GB の<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|アーカイブ メールボックス<sup>8、9</sup> <br/> |100 GB の<sup>1</sup> <br/> |50 GB  <br/> |無制限<sup>2</sup> <br/> |使用不可<sup>5</sup> <br/> |
|共有メールボックス  <br/> |2 GB の<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|リソース メールボックス  <br/> |2 GB の<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4,10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|パブリック フォルダー メールボックス  <br/> |2 GB の<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |使用不可  <br/> |
|グループ メールボックス  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>これは、組織の Exchange Server 2013 の既定のメールボックスのサイズです。管理者は、各組織には、この値を変更できます。オンプレミスのメールボックスの記憶域の最大制限はありません。> <sup>2</sup>各ユーザーがアーカイブ メールボックスに最初に 100 GB のストレージを受信します。アーカイブの自動拡張を有効にする追加の記憶域は 100 GB のストレージ容量に達すると自動的に追加します。詳細については、 [Office 365 で無制限のアーカイブの概要](https://go.microsoft.com/fwlink/?linkid=844060)を参照してください。自動拡張するための可用性の詳細については、 [Office 365 のロードマップ](http://go.microsoft.com/fwlink/?LinkId=509914)を参照してくださいアーカイブします。> ユーザー、共有メールボックスにアクセスするための<sup>3</sup>は、Exchange Online のライセンスを取得する必要があります。共有メールボックスは、別のライセンスを必要としません。ただし、ライセンスのない共有メールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、Exchange オンライン計画 2 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。埋め込みアーカイブを有効にするか、共有メールボックスで、埋め込みを保持または、証拠保全を配置する場合、Exchange のオンライン計画 2 ライセンスまたは、Exchange オンライン計画 1 には、Exchange Online Archiving のライセンスが必要です。インプレース アーカイブと共有されているメールボックスのアーカイブを自動拡張を有効にする場合は、追加の記憶域はアーカイブ メールボックスの 100 GB のストレージ容量に達すると自動的に追加します。> <sup>4</sup>リソース メールボックスは、ライセンスを必要としません。ただし、ライセンスのない共有メールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、Exchange オンライン計画 2 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。> <sup>5</sup> Exchange Online Kiosk でインプレース アーカイブが含まれていません。ただし、Exchange Online Archiving をアドオンとして購入できます。詳細については、 [Exchange Online Archiving サービスの説明](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)を参照してください。> <sup>6</sup>これは、組織の Microsoft Exchange Server 2013 の既定のメールボックスのサイズ。管理者は、各組織には、この値を変更できます。Exchange Server 2013 では、制限されることは、100 のパブリック フォルダーのメールボックスに、すべてのパブリック フォルダーのメールボックスの最大サイズの合計 50 TB です。> <sup>7</sup> Exchange オンライン、1,000 個のパブリック フォルダーのメールボックスに制限されることは、すべてのパブリック フォルダーのメールボックスの最大サイズの合計 50 TB です。> <sup>8</sup>インプレース アーカイブは、ライセンスが適用されているエンティティの 1 つのユーザー宛てのメールをアーカイブする場合にのみ使用できます。埋め込みアーカイブを複数のユーザーまたはエンティティからのメールを保存する手段として使用が禁止されています。たとえば、IT 管理者は共有メールボックスを作成して ([cc] または [bcc] フィールド、またはトランスポート ルールを使用)、共有されているメールボックスをアーカイブの明示的な目的でコピーするユーザーがいることができません。> <sup>9</sup>ユーザーのプライマリ メールボックスが 10 MB よりも大きいだけに、メッセージがユーザーのアーカイブ メールボックスに自動的に移動、Exchange Online のリテンション ・ ポリシーを作成した場合。10 MB 未満のメールボックスのアイテム保持ポリシーは自動的に実行されません。> <sup>10</sup>の共有とリソースのメールボックスに割り当てられるライセンスは不要です。ただし、ライセンスのないこれらのメールボックスは 50 GB に制限します。メールボックスのサイズを増やすには、Exchange オンライン計画 2 のライセンスを割り当てる必要があります。これは、100 gb のメールボックスが増加します。 
  
> [!NOTE]
> 直接のログオンには、共有されているメールボックスは設計されていません。**無効になっている**(または「切断」) に、メールボックスのユーザー アカウント、共有自体を維持する必要があります状態です。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="capacity-alerts"></a>容量のアラート
<a name="CapacityAlerts"> </a>

Exchange Online では、ユーザーのメールボックスが上限に近づくか、または一杯になったときに 3 種類の通知が行われます。
  
- **警告** ユーザーは、メールボックスが最大サイズの制限値に近づいていることを示す警告を電子メールで受信します。この警告は、ユーザーに不要なメールの削除を促すものです。 
    
- **送信禁止** ユーザーは、メールボックスのサイズが制限値に達したときに、送信禁止の通知を電子メールで受信します。ユーザーは、十分な電子メールが削除され、メールボックスのサイズが制限値を下回るまで、新しいメッセージを送信できません。 
    
- **送受信禁止** Exchange Online は、メールボックスのサイズが制限値に達すると、メールの受信を拒否し、送信者に配信不能レポート (NDR) を送信します。送信者には後でメールを再送信するオプションがあります。ユーザーがメッセージを再度受信するには、メールボックスがサイズ制限値を下回るまで、電子メールを削除する必要があります。 
    
### <a name="capacity-alerts-across-office-365-options"></a>Office 365 オプションの容量のアラート

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|警告  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|送信禁止  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|送受信禁止  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>スタンドアロン プランの容量のアラート

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|警告  <br/> |1.9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1.96 GB  <br/> |
|送信禁止  <br/> |2 GB の<sup>1</sup> <br/> |49.5 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|送受信禁止  <br/> |2.3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは Exchange Server 2013 組織の既定値です。管理者は、組織に適用されるこの値を変更できます。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="mailbox-folder-limits"></a>メールボックス フォルダーの制限
<a name="MailboxFolderLimits"> </a>

これらの制限は、メールボックスを Exchange Online でサポート可能な大きさにするためのものです。これらの制約は、フォルダーごとのメールボックス項目数、メールボックスごとのフォルダー数、あるいは Exchange Online 組織ごとのパブリック フォルダー数の無制限な使用を防ぐことを目的としています。実用的には、メールボックス フォルダーの限度は事実上無制限で、Exchange Online へ移行するほとんどの Exchange Online メールボックスや社内メールボックスを十分にサポートしています。
  
- **メールボックス フォルダーごとの最大メッセージ数** メールボックス フォルダーの最大メッセージ数を規定します。この制限値に達すると新規メッセージを配達することも、フォルダーに保存することもできません。 
    
- **メールボックス フォルダーごとの警告を出すメッセージ数** メールボックス フォルダーに保存されたメッセージ数がここで指定した数を超えると、Exchange Online がメールボックス所有者に警告メッセージを送信します。このクォータに達すると、警告メッセージが毎日 1 回送信されます。 
    
- **復元可能アイテム フォルダー内のフォルダーごとの最大メッセージ数** 復元可能アイテム フォルダー内の各フォルダーに保存できる最大メッセージ数を規定します。フォルダーがこの最大数を超えた場合、新しいメッセージを保存できません。たとえば、回復可能なアイテム フォルダーの削除フォルダーがメッセージの最大数を超えた場合、メールボックスの所有者がメールボックスからアイテムを完全に削除しようとしても、削除は失敗します。 
    
- **復元可能アイテム フォルダー内のフォルダーごとの警告を出すメッセージ数** 復元可能アイテム フォルダー内の各フォルダーに保存されるメッセージ数がここで指定した数を超えると、Exchange Online はアプリケーション イベント ログにイベントを記録します。 
    
- **メールボックス フォルダーごとのサブフォルダー数の最大値** メールボックス フォルダー内に作成できるサブフォルダー数の最大値を規定します。この最大数に達すると、メールボックスの所有者は新しいサブフォルダーを作成できません。 
    
- **メールボックス フォルダーごとの警告を出すサブフォルダー数** メールボックス フォルダーに作成するサブフォルダー数がここで指定した数を超えると、Exchange Online がメールボックス所有者に警告メッセージを送信します。このクォータに達すると、警告メッセージが毎日 1 回送信されます。 
    
- **フォルダー階層の深さの最大値** メールボックスのフォルダー階層内のレベルの最大数を指定します。この最大数に達すると、メールボックスの所有者はメールボックス フォルダーの階層内で新たなレベルを作成できなくなります。 
    
- **警告を出すフォルダー階層の深さ** フォルダー階層のレベル数がここで指定した数を超えると、Exchange Online がメールボックス所有者に警告メッセージを送信します。このクォータに達すると、警告メッセージが毎日 1 回送信されます。 
    
- **パブリック フォルダーの最大数** パブリック フォルダー階層全体のパブリック フォルダーの最大数を指定します。この制限に達すると、既存のパブリック フォルダーを削除しないかぎり、新しいパブリック フォルダーを作成できなくなります。 
    
- **パブリック フォルダーごとのサブフォルダー数の最大値** パブリック フォルダー内に作成できるサブフォルダー数の最大値を指定します。この制限値に達すると、パブリック フォルダーに新規サブフォルダーの作成はできません。 
    
- **パブリック フォルダーごとの警告を出すサブフォルダー数** パブリック フォルダーに作成するサブフォルダー数がここで指定した数を超えると、Exchange Online がフォルダー所有者に警告メッセージを送信します。所有者が存在していない場合、警告メッセージは所有者アクセス許可を持つユーザーに送信されます。このクォータに達すると、警告メッセージが毎日 1 回送信されます。 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Office 365 オプションのメールボックス フォルダーの制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|メールボックス フォルダーごとの最大メッセージ数  <br/> |100 万  <br/> |100 万個  <br/> |100 万個  <br/> |100 万個  <br/> |100 万個  <br/> |100 万個  <br/> |
|メールボックス フォルダーごとの警告を出すメッセージ数  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|復元可能アイテム フォルダー内のフォルダーごとの最大メッセージ数  <br/> |300 万  <br/> |300 万  <br/> |300 万  <br/> |300 万  <br/> |300 万  <br/> |300 万  <br/> |
|プライマリ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留ではないもの)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|プライマリ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留である)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|アーカイブ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留ではないもの)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |無制限<sup>2</sup> <br/> |無制限<sup>2</sup> <br/> |30 GB  <br/> |
|アーカイブ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留である)  <br/> |100 GB の<sup>1</sup> <br/> |100 GB の<sup>1</sup> <br/> |100 GB の<sup>1</sup> <br/> |無制限<sup>2</sup> <br/> |無制限<sup>2</sup> <br/> |100 GB の<sup>1</sup> <br/> |
|復元可能アイテム フォルダー内のフォルダーごとの警告を出すメッセージ数  <br/> |275 万  <br/> |275 万  <br/> |275 万  <br/> |275 万  <br/> |275 万  <br/> |275 万  <br/> |
|メールボックス フォルダーごとのサブフォルダー数の最大値  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|メールボックス フォルダーごとの警告を出すサブフォルダー数  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|フォルダー階層の深さの最大値  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|警告を出すフォルダー階層の深さ  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|パブリック フォルダーの最大数  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |使用不可  <br/> |
|パブリック フォルダーごとのサブフォルダーの最大数  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |使用不可  <br/> |
|パブリック フォルダーごとの警告を出すサブフォルダー数  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |使用不可  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは、回復可能なアイテム フォルダーの記憶域のクォータであり、アーカイブ全体のメールボックスのクォータではありません。Exchange Online (プラン 2) のライセンスを持つユーザーや Exchange Online プラン 1 と Exchange Online Archiving の両方のライセンスを持つユーザーは、アーカイブ メールボックスの記憶域のクォータが無制限です。回復可能なアイテムのクォータを増やす方法については、「 [Increase the Recoverable Items quota for mailboxes on hold](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)」を参照してください。 > <sup>2</sup> アーカイブ メールボックスの回復可能なアイテム フォルダーの最初の記憶域のクォータは 100 GB です。自動拡張アーカイブをオンにした場合、回復可能なアイテム フォルダーの記憶域容量に達すると、追加の記憶域が自動的に追加されます。詳細については、「 [Office 365 での無制限アーカイブの概要](https://go.microsoft.com/fwlink/?linkid=844060)」を参照してください。自動拡張アーカイブの可用性について詳しくは、「[Office 365 のロードマップ](http://go.microsoft.com/fwlink/?LinkId=509914)」を参照してください。 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>スタンドアロン プランのメールボックス フォルダーの制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|メールボックス フォルダーごとの最大メッセージ数  <br/> |制限なし<sup>1</sup> <br/> |100 万  <br/> |100 万個  <br/> |100 万個  <br/> |
|メールボックス フォルダーごとの警告を出すメッセージ数  <br/> |制限なし  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|復元可能アイテム フォルダー内のフォルダーごとの最大メッセージ数  <br/> |制限なし  <br/> |300 万  <br/> |300 万  <br/> |300 万  <br/> |
|プライマリ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留ではないもの)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|プライマリ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留である)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|アーカイブ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留ではないもの)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|アーカイブ メールボックスの回復可能なアイテム フォルダーの記憶域のクォータ (保留である)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |無制限<sup>3</sup> <br/> |無制限<sup>3</sup> <br/> |
|復元可能アイテム フォルダー内のフォルダーごとの警告を出すメッセージ数  <br/> |制限なし  <br/> |275 万  <br/> |275 万  <br/> |275 万  <br/> |
|メールボックス フォルダーごとのサブフォルダー数の最大値  <br/> |制限なし  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|メールボックス フォルダーごとの警告を出すサブフォルダー数  <br/> |制限なし  <br/> |900  <br/> |900  <br/> |900  <br/> |
|フォルダー階層の深さの最大値  <br/> |制限なし  <br/> |300  <br/> |300  <br/> |300  <br/> |
|警告を出すフォルダー階層の深さ  <br/> |制限なし  <br/> |250  <br/> |250  <br/> |250  <br/> |
|パブリック フォルダーの最大数  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |使用不可  <br/> |
|パブリック フォルダーごとのサブフォルダーの最大数  <br/> |該当なし  <br/> |1,000  <br/> |1,000  <br/> |使用不可  <br/> |
|パブリック フォルダーごとの警告を出すサブフォルダー数  <br/> |該当なし  <br/> |900  <br/> |900  <br/> |使用不可  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft では、メールボックス フォルダーごとに 1,000,000 個以内のメッセージをお勧めします。 > <sup>2</sup> これは、回復可能なアイテム フォルダーの記憶域のクォータであり、アーカイブ全体のメールボックスのクォータではありません。Exchange Online (プラン 2) のライセンスを持つユーザーや Exchange Online プラン 1 と Exchange Online Archiving の両方のライセンスを持つユーザーは、アーカイブ メールボックスの記憶域のクォータが無制限です。回復可能なアイテムのクォータを増やす方法については、「 [Increase the Recoverable Items quota for mailboxes on hold](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)」を参照してください。 > <sup>3</sup> アーカイブ メールボックスの回復可能なアイテム フォルダーの最初の記憶域のクォータは 100 GB です。自動拡張アーカイブをオンにした場合、回復可能なアイテム フォルダーの記憶域容量に達すると、追加の記憶域が自動的に追加されます。詳細については、「 [Office 365 での無制限アーカイブの概要](https://go.microsoft.com/fwlink/?linkid=844060)」を参照してください。自動拡張アーカイブの可用性の詳細については、「[Office 365 のロードマップ](http://go.microsoft.com/fwlink/?LinkId=509914)」を参照してください。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="message-limits"></a>メッセージの制限
<a name="MessageLimits"> </a>

次の制限は、すべてのメール メッセージに適用されます。
  
- **メッセージのサイズ制限** サイズの大きいメッセージによって他のメッセージの配信がブロックされたり、すべてのユーザーに対するサービスのパフォーマンスに影響が及んだりするのを防ぐには、メッセージ サイズの制限が必要です。これらの制限には添付ファイルも含まれ、組織全体のすべてのメッセージ (受信、送信、および内部) に対して適用されます。この制限値を上回るメッセージは配信されず、送信者に配信不能レポート (NDR) が送られます。メッセージ サイズの制限値を増減したり、ユーザー単位で構成したりできますが、管理者もトランスポート ルールを作成して、個々の添付ファイルの最大サイズを制限できます。詳しくは、「 [Office 365 でサポートされるメール メッセージのサイズが大きくなりました](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)」をご覧ください。
    
    > [!NOTE]
    > 電子メール クライアントによっては、Exchange Online のメッセージ サイズ制限よりも制限値が低い場合や、個別の添付ファイルのサイズを制限できる場合があります。 
  
- **件名の長さの制限** 1 つのメール メッセージの件名に使用できるテキスト文字の最大数。 
    
- **添付ファイル数の制限** 1 つの電子メール メッセージに添付できる添付ファイルの最大数。添付ファイルすべての合計サイズがメッセージ サイズの制限に違反しない場合でも、メッセージに添付できる添付ファイルの数には制限があります。この制限はマルチパート メッセージの制限によって制御されます。 
    
- **添付ファイルのサイズ制限** 1 つの添付ファイルの最大ファイル サイズです。 
    
    > [!NOTE]
    > これは、1 つの添付ファイルの最大ファイル サイズです。Outlook Web App を含む個々のクライアント プログラムでは、添付ファイルのサイズ制限をこの最大値より小さくしている可能性があります。Exchange ActiveSync は、添付ファイルのサイズ制限を個別の添付ファイルごとには実装しません。Exchange ActiveSync メッセージに添付されるすべてのファイルの合計サイズは、メッセージのサイズ制限よりも小さい必要があります。 
  
- **マルチパート メッセージの制限** MIME マルチパート メッセージで許可されるメッセージ本文のパーツの最大数。この制限は、メッセージ内で許可される添付ファイルの最大数も制御します。 
    
- **埋め込みメッセージの深さの制限** 1 つのメール メッセージで許可される転送メール メッセージの最大数。 
    
### <a name="message-limits-across-office-365-options"></a>Office 365 オプションのメッセージの制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|メッセージ サイズの制限 - Outlook  <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|メッセージ サイズの制限 - OWA  <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |
|メッセージ サイズの制限 - Outlook for Mac  <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|メッセージ サイズの制限 - 移行  <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |
|暗号化されたメッセージのサイズ制限 (新しい機能を備えた Office 365 Message Encryption を使用するサブスクライバー向け)<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|暗号化されたメッセージのサイズ制限 (レガシ バージョンの Office 365 Message Encryption を使用するサブスクライバー向け)<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|件名の長さの制限  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |
|添付ファイルの制限  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |
|添付ファイルのサイズ制限 - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|添付ファイルのサイズ制限 - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|添付ファイルのサイズ制限 - Outlook for Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|マルチパート メッセージの制限  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |
|埋め込みメッセージの深さの制限  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |
   
> [!NOTE]
> <sup>1</sup> Office 365 のメールボックスの既定のメッセージの最大サイズは 25 MB です。Office 365 の管理者は、1 MB と 150 MB の間でのユーザー設定の制限を指定できます。ただし、メッセージを送信または受信することができますのサイズは、どのようなソリューション、電子メール クライアントをサポートしているによっても異なります。組織で許可されているメッセージの最大サイズをカスタマイズする方法の詳細については、[サイズの大きい電子メール メッセージをサポートしている Office 365 を今すぐ](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)参照してください。> (場所、メッセージことはありませんから、Office 365 のデータ センター) の Office 365 ユーザー間でメッセージの<sup>2</sup>最大 150 MB を送受信できます。Office 365 のデータ センターの外部でルーティングされるメッセージは予告なしにエンコードする場合、メッセージの最大サイズは 112 MB の増加、追加の 33% 翻訳されることがあります。> <sup>3</sup> OWA は、メッセージは、33% の増加をエンコードする可能性を考慮し、25%、構成されているよりも低い値に送信できるメッセージのサイズを制限します。たとえば、100 MB の最大メッセージ サイズの設定をカスタマイズする場合がメッセージを送信する 75 MB を超える。> <sup>4</sup> Exchange Online に移動するメッセージのサイズは、Exchange のオンラインで計算されます。Exchange Server 2013 の前に Exchange のバージョンによって、項目のサイズを報告する必要があります。ベースの移行のいずれかを使用して Exchange メールボックス レプリケーション サービスのサポートを移動するこの制限が適用されます。(Cutover、段階的な IMAP、PST) の他の移行方法とその他のサード パーティ製ツールは、一般的なメッセージ サイズの制限によって制限されます。> ホームについては、新しい機能により、 <sup>5</sup>では、[情報の保護を Azure 上に構築された、新しい Office 365 のメッセージの暗号化機能の設定](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)を参照してください。> <sup>6</sup> 35 MB を超えると 1 つのファイルを添付することはできません。さらに、まとめて 35 MB を超えるファイルを添付することはできません。たとえば、34 MB の 1 つのファイルを添付する場合のみに追加の 1 MB のファイルを添付できます。 
  
### <a name="message-limits-across-standalone-options"></a>スタンドアロン オプションのメッセージの制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|メッセージ サイズの制限 - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>1、2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|メッセージ サイズの制限 - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1、3</sup> <br/> |112 MB<sup>1、3</sup> <br/> |150 MB<sup>1、2</sup> <br/> |
|メッセージ サイズの制限 - Outlook for Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> ||
|メッセージ サイズの制限 - 移行  <br/> |該当なし  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|暗号化されたメッセージのサイズ制限 (新しい機能を備えた Office 365 Message Encryption を使用するサブスクライバー向け)<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|暗号化されたメッセージのサイズ制限 (レガシ バージョンの Office 365 Message Encryption を使用するサブスクライバー向け)<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|件名の長さの制限  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |255 文字  <br/> |
|添付ファイルの制限  <br/> |1024 添付ファイル<sup>4</sup> <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |250 個の添付ファイル  <br/> |
|添付ファイルのサイズ制限 - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|添付ファイルのサイズ制限 - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|添付ファイルのサイズ制限 - Outlook for Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|マルチパート メッセージの制限  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |250 パーツ  <br/> |
|埋め込みメッセージの深さの制限  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |30 の埋め込みメッセージ  <br/> |
   
> [!NOTE]
> <sup>1</sup> Office 365 の管理者は 1 から 150 MB のカスタムの制限を指定できます。ただし、送信または受信できるメッセージのサイズは、メール クライアントまたはソリューション サポートにも依存します。組織において許可する最大メッセージ サイズのカスタマイズ方法について詳しくは、「 [Office 365 でサポートされるメール メッセージのサイズが大きくなりました](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)」をご覧ください。 > <sup>2</sup> Office 365 のユーザー間で最大 150 MB のメッセージを送受信できます (メッセージが Office 365 データセンターの外部に出ない場合)。Office 365 データセンターの外部にルーティングされるメッセージは、変換エンコードにより 33% 大きいサイズになるため、最大メッセージ サイズは 112 MB になります。 > <sup>3</sup> OWA ではメッセージ サイズがエンコードで 33% 増加する可能性があるため、ユーザーが送信できるメッセージ サイズを構成されているよりも 25% 低い値に制限されます。たとえば、100 MB の最大メッセージ サイズの設定にカスタマイズした場合、送信できるメッセージは 75 MB 以下です。 > <sup>4</sup> これは Exchange Server 2013 組織の既定の制限です。管理者は、組織に適用されるこの値を変更できます。 > <sup>5</sup> Exchange Online に移動するメッセージのサイズは Exchange Online によって計算されます。Exchange Server 2013 より前のバージョンの Exchange では、アイテムのサイズが小さく報告されます。 > <sup>6</sup> 新しい機能を備えた OME については、「 [Azure Information Protection をベースにした新しい Office 365 Message Encryption 機能を構築する](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)」を参照してください。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="receiving-and-sending-limits"></a>受信および送信の制限
<a name="RecipientLimits"> </a>

受信および送信の制限は、スパムや大量メール送信ワームまたはウイルス対策として適用されます。これらの制限は、システムを健全に維持しユーザーの安全を守るために役立ちます。
  
### <a name="receiving-limits"></a>受信の制限

受信の制限は、1 時間あたりにユーザー、グループ、またはパブリック フォルダーが受信できるメッセージの数に対して適用されます。これは、オンプレミスのサーバーからのメッセージと、インターネットからのメッセージの両方に適用されます。受信の制限を超えると、そのメールボックスに送信された電子メールに対して、メールボックスの配信のしきい値が上限を超えたことを伝える配信不能レポートが送信されます。1 時間後に制限が更新され、メールボックスは再びメッセージを受信できるようになります。
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|受信したメッセージ  <br/> |1 時間あたり 3,600 のメッセージ  <br/> |1 時間あたり 3,600 のメッセージ  <br/> |1 時間あたり 3,600 のメッセージ  <br/> |1 時間あたり 3,600 のメッセージ  <br/> |1 時間あたり 3600 のメッセージ  <br/> |1 時間あたり 3600 のメッセージ  <br/> |
   
### <a name="sending-limits"></a>送信の制限

送信側の制限は、ユーザーが自己の Exchange Online アカウントから発信できるメッセージの受信者数、メッセージ数、およびメッセージごとの受信者数に対して適用されます。
  
> [!NOTE]
> 組織のアドレス帳に格納されている配布グループの場合、グループは 1 受信者としてカウントされます。メールボックスの連絡先フォルダーに格納されている配布グループの場合、グループのメンバーは個別にカウントされます。 
  
- **受信者数の制限** Exchange Online には、受信者が送信を要求していないバルク メッセージの配信を防ぐための受信者制限があり、ユーザーおよびアプリケーションによる膨大な数の電子メールの送信を防止しています。これらの制限は、すべての送信メッセージおよび内部メッセージに対してユーザーごとに適用されます。 
    
    > [!NOTE]
    > Exchange Online 正当なバルク メッセージ (たとえば、顧客向けのニュースレター) を送信する必要がある場合は、そのようなサービスに特化したサード パーティ プロバイダーを使用してください。 
  
- **受信者の制限** "宛先:"、"CC:"、"BCC:" の各フィールドに 1 通のメール メッセージで入力できるメッセージ受信者の最大数。 
    
    > [!NOTE]
    > 受信者数の制限と受信者制限の目的で、組織の共有アドレス帳に保存される配布グループは 1 つの受信者としてカウントされます。個人用の配布リストでは、各受信者は個別にカウントされます。 
  
- **メッセージ数の制限** メッセージ数の制限では、指定された期間内に Exchange Online アカウントからユーザーが送信できるメッセージの数を決定します。この制限により、単一の送信者がシステム リソースを過剰に消費するのを防ぐことができます。SMTP クライアント送信でユーザーが送信するメッセージ数がこの制限を超えると、メッセージは拒否され、クライアントで再試行する必要があります。 
    
#### <a name="sending-limits-across-office-365-options"></a>Office 365 の各オプションでの送信の制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|受信者数の制限  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |
|受信者の制限  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |
|受信者のプロキシ アドレスの制限  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|メッセージ レートの制限 (SMTP クライアント発信のみ)  <br/> |1 分あたり 30 個のメッセージ  <br/> |1 分あたり 30 個のメッセージ  <br/> |1 分あたり 30 個のメッセージ  <br/> |1 分あたり 30 個のメッセージ  <br/> |1 分あたり 30 個のメッセージ  <br/> |1 分あたり 30 個のメッセージ  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>スタンドアロンの各オプションでの送信の制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|受信者数の制限  <br/> |制限なし<sup>1</sup> <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |1 日あたり 10,000 の受信者  <br/> |
|受信者の制限  <br/> |500 人<sup>1</sup> <br/> |500 の受信者  <br/> |500 の受信者  <br/> |500 の受信者  <br/> |
|受信者のプロキシ アドレスの制限  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは Exchange Server 2013 組織の既定の制限です。管理者は、組織に適用されるこの値を変更できます。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="reporting-and-message-trace-limits"></a>レポート作成とメッセージ追跡の制限
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

レポート作成とメッセージ追跡の制限については、「[Exchange Online Protection でのレポート作成とメッセージ追跡](http://go.microsoft.com/fwlink/p/?LinkId=394248)」の「レポート作成およびメッセージ追跡データの可用性と遅延」セクションを参照してください。
  
## <a name="retention-limits"></a>保持の制限
<a name="RetentionLimits"> </a>

これらの制限で、受信トレイ内の特定のフォルダー内のアイテムにアクセス可能な時間長を制御します。
  
- **削除済みアイテム フォルダーの保持期間** 自動的に削除されるまで削除済みアイテム フォルダーにアイテムを保持できる最大日数。 
    
- **削除済みアイテム フォルダーから削除されたアイテムの保存期間**完全に削除する前に、削除済みアイテム フォルダーからアイテムを削除する日数の最大値が保持されます。 
    
- **迷惑メール フォルダーの保持期間** 自動的に削除されるまで迷惑メール フォルダーにアイテムを保持できる最大日数。 
    
### <a name="retention-limits-across-office-365-options"></a>Office 365 オプションの保存期限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|削除済みアイテム フォルダーの保存期限  <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |
|削除済みアイテム フォルダーから削除されたアイテムの保存期限  <br/> |14 日間<sup>1</sup> <br/> |14 日間<sup>1</sup> <br/> |14 日間<sup>1</sup> <br/> |14 日間<sup>1</sup> <br/> |14 日間<sup>1</sup> <br/> |14 日間<sup>1</sup> <br/> |
|迷惑メール フォルダーの保存期限  <br/> |30 日  <br/> |30 日  <br/> |30 日  <br/> |30 日  <br/> |30 日  <br/> |30 日  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは既定の制限です。管理者は、組織に適用されるこの値を変更できます。 
  
### <a name="retention-limits-across-standalone-options"></a>スタンドアロン オプションの保存期限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|削除済みアイテム フォルダーの保存期限  <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |制限なし<sup>1</sup> <br/> |
|削除済みアイテム フォルダーから削除されたアイテムの保存期限  <br/> |14 日間<sup>1</sup> <br/> |14 日<sup>2</sup> <br/> |14 日<sup>2</sup> <br/> |14 日<sup>2</sup> <br/> |
|迷惑メール フォルダーの保存期限  <br/> |2 年間<sup>1</sup> <br/> |30 日  <br/> |30 日  <br/> |30 日  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは既定の制限です。管理者は、組織に適用されるこの値を変更できます。 > <sup>2</sup> これは Exchange Online 組織の既定値です。管理者は組織のメールボックスのこの値を最大 30 日に変更できます。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="distribution-group-limits"></a>配布グループの制限
<a name="DistributionGroupLimits"> </a>

これらの制限は、組織の共有アドレス帳に含まれる配布グループに適用されます。
  
- **配布グループのメンバーの最大数**受信者の合計数は、配布グループの展開後に決定されます。 
    
- **大きな配布グループへのメッセージの送信の制限** この制限で指定された数のメンバーを含む配布グループでは、配信の管理またはメッセージの承認のいずれかのオプションを構成する必要があります。配信の管理では、その配布グループにメッセージを送信することが許可される送信者のリストを指定します。メッセージの承認では、その配布グループに送信されるすべてのメッセージを承認する必要があるモデレーターを 1 人以上指定します。 
    
- **大きな配布グループの最大メッセージ サイズ** 5,000 人以上の受信者に送信されるメッセージのサイズの制限です。サイズがこの制限を超えている場合はメッセージが配信されず、送信者に配信不能レポート (NDR) が送信されます。受信者の合計数は、配布グループの展開後に決定されます。 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Office 365 オプションの配布グループの制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|配布グループ メンバーの最大数<sup>1</sup> <br/> |100,000 人  <br/> |100,000 人  <br/> |100,000 人  <br/> |100,000 人  <br/> |100,000 人  <br/> |100,000 人  <br/> |
|大きな配布グループへのメッセージ送信の制限  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |
|5,000 ~ 100,000 のメンバーを持つ配布グループのメッセージの最大サイズ  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|100,000 以上のメンバーを含む配布グループのメッセージの最大サイズ  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|配布グループの所有者の最大数  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10  <br/> |
|ユーザーが作成できるグループの最大数  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Azure Active Directory DirSync を使用している場合、オンプレミスの Active Directory から Azure Active Directory に同期することができる配布グループ メンバーの最大数は、15,000 人です。Azure AD Connect を使用している場合は、この最大数は 50,000 人です。 > <sup>2</sup> この制限は、管理者にも適用されます。 
  
### <a name="distribution-group-limits-across-standalone-options"></a>スタンドアロン オプションの配布グループの制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|配布グループのメンバーの最大数  <br/> |100,000 人<sup>1</sup> <br/> |100,000 人  <br/> |100,000 人  <br/> |100,000 人  <br/> |
|大きな配布グループへのメッセージ送信の制限  <br/> |5,000 人以上<sup>1</sup> <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |5,000 人以上  <br/> |
|配布グループの所有者の最大数  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |
|ユーザーが作成できるグループの最大数  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> これは Exchange Server 2013 組織の既定の制限です。管理者は、組織に適用されるこの値を変更できます。 > <sup>2</sup> この制限は、管理者にも適用されます。 
  
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="journal-transport-and-inbox-rule-limits"></a>ジャーナル、トランスポートおよび受信トレイのルールの制限
<a name="TransportRuleLimits"> </a>

次のリストには、ジャーナル ルール、トランスポート ルール (組織全体のルールとも呼ばれる) に適用される制限や、受信トレイ ルールに適用される制限が含まれます。受信トレイ ルールは個々のユーザーごとに設定され、個々のユーザーのメールボックスで送受信されたメッセージに適用されます。
  
- **ジャーナル ルールの最大数** 組織で使用できるジャーナル ルールの最大数です。 
    
- **トランスポート ルールの最大数** 組織で使用できるルールの最大数です。 
    
- **個々 のトランスポート ルールの最大サイズ**1 つのトランスポート ルールで使用できる文字の最大数です。文字は、条件、例外、およびアクションで使用されます。 
    
- **すべてのトランスポート ルールで使用されているすべての正規表現の最大文字数** 組織のすべてのトランスポート ルールの条件および例外に含まれるすべての正規表現の文字数の合計です。長くて複雑な正規表現を含むルールを少数使用することも、単純な正規表現を含むルールを多数使用することもできます。 
    
- **添付ファイルのコンテンツに対するスキャンの制限** トランスポート ルールの条件を使用して、メッセージの添付ファイルのコンテンツを確認できますが、添付ファイルから抽出されたテキストの最初の 1 MB だけが検査されます。この 1 MB という制限は、添付ファイルのファイル サイズではなく、添付ファイルから抽出されたテキストに適用されます。たとえば、2 MB のファイルに 1 MB 未満のテキストが含まれる場合は、すべてのテキストが検査されます。 
    
- **すべてのトランスポート ルールによってメッセージに追加される受信者の最大数** 1 つのメッセージに複数のトランスポート ルールが適用される場合、メッセージに追加できる受信者の数が制限されます。この制限に達すると、残りの受信者はメッセージに追加されません。また、トランスポート ルールで配布グループをメッセージに追加することはできません。 
    
- **転送者の制限** リダイレクト処理を含む受信トレイ ルールまたはトランスポート ルールに構成できる受信者の最大数。この値よりも多くの受信者にメッセージをリダイレクトするようにルールが構成されている場合、ルールは適用されず、ルールの条件を満たすメッセージはルールで指定されたどの受信者にもリダイレクトされません。 
    
- **メッセージのリダイレクト回数** 受信トレイ ルールに基づいてメッセージを自動的にリダイレクト、転送、または返信する回数。たとえば、ユーザー A に、送信者に基づいてメッセージをユーザー B にリダイレクトとする受信トレイ ルールが設定されているとします。ユーザー B には、件名行のキーワードに基づいてメッセージをユーザー C に転送する受信トレイ ルールが設定されています。リダイレクトが 1 回のみ許可されている場合、これらの条件を両方とも満たすメッセージは、ユーザー B にのみ送信され、ユーザー C には転送されません。この場合は、ユーザー C にメッセージが配信されなかったことを示す配信不能レポート (NDR) がユーザー B に送信されないままメッセージが破棄されます。 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Office 365 オプションのジャーナル、トランスポートおよび受信トレイのルールの制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|ジャーナル ルールの最大数  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |
|トランスポート ルールの最大数  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |
|各トランスポート ルールの最大サイズ  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|すべてのトランスポート ルールで使用されるすべての正規表現の文字に関する制限  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|添付ファイルのコンテンツのスキャンの制限  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|すべてのトランスポート ルールによってメッセージに追加される最大受信者数  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |
|被転送者の制限  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |
|メッセージのリダイレクト回数  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>スタンドアロン オプションのジャーナル、トランスポートおよび受信トレイのルールの制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|ジャーナル ルールの最大数  <br/> |制限なし  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |10 個のルール  <br/> |
|トランスポート ルールの最大数  <br/> |制限なし  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |300 個のルール  <br/> |
|各トランスポート ルールの最大サイズ  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|すべてのトランスポート ルールで使用されるすべての正規表現の文字に関する制限  <br/> |制限なし  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|すべてのトランスポート ルールによってメッセージに追加される最大受信者数  <br/> |制限なし  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |100 の受信者  <br/> |
|被転送者の制限  <br/> |制限なし  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |10 の受信者  <br/> |
|メッセージのリダイレクト回数  <br/> |3 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |1 回のリダイレクト  <br/> |
   
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
## <a name="moderation-limits"></a>モデレートの制限
<a name="ModerationLimits"> </a>

これらの制限は、配布グループとトランスポート ルールに適用されるメッセージの承認のモデレート設定を制御します。
  
- **調停メールボックスの最大サイズ** 調停メールボックスのサイズがこの制限を超えると、モデレートを必要とするメッセージは配信不能レポート (NDR) で送信者に返されます。 
    
- **モデレーターの最大数**または 1 つのモデレート配布グループに割り当てることができるモデレーターの最大数は、1 つのトランスポート ルールを使用してメッセージに追加できます。配布グループをモデレーターとして指定できないことに注意してください。 
    
- **モデレート待ちメッセージの有効期限** 既定では、モデレート待ちのメッセージは 2 日後に期限切れになります。ただし、期限切れモデレート メッセージの処理が 7 日ごとに実行されます。したがって、モデレート メッセージが期限切れになるのは 2 日から 9 日の間になります。 
    
- **期限切れモデレート通知メッセージの最大頻度** この制限は、期限切れモデレート メッセージに関する通知メッセージの 1 時間あたりの最大数を設定します。データセンターのメールボックス データベースごとの制限です。 
    
    負荷が高いときには、一部の送信者に期限切れモデレート メッセージに関する通知メッセージが送信されなくなる可能性がありますが、その場合も、配信レポートで通知を確認できます。
    
### <a name="moderation-limits-across-office-365-options"></a>Office 365 オプションのモデレートの制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|調停メールボックスの最大サイズ  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|最大モデレーター数  <br/> |10 人  <br/> |10 人  <br/> |10 人  <br/> |10 人  <br/> |10 人  <br/> |10 人  <br/> |
|モデレートを待機しているメッセージの有効期限  <br/> |2 日  <br/> |2 日  <br/> |2 日  <br/> |2 日  <br/> |2 日  <br/> |2 日  <br/> |
|期限切れモデレート通知メッセージの最大頻度  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>スタンドアロン オプションのモデレートの制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|調停メールボックスの最大サイズ  <br/> |制限なし<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|最大モデレーター数  <br/> |制限なし  <br/> |10 人  <br/> |10 人  <br/> |10 人  <br/> |
|モデレートを待機しているメッセージの有効期限  <br/> |5 日間<sup>1</sup> <br/> |2 日  <br/> |2 日  <br/> |2 日  <br/> |
|期限切れモデレート通知メッセージの最大頻度  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |1 時間あたり 300 通  <br/> |
   
> [!NOTE]
> <sup>1</sup> これは Exchange Server 2013 組織の既定の制限です。管理者は、組織に適用されるこの値を変更できます。 
  
## <a name="exchange-activesync-limits"></a>Exchange ActiveSync の制限
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

次の制限が、モバイル デバイスと Exchange との間でメールボックス データを同期するクライアント プロトコルである Microsoft Exchange ActiveSync に適用されます。 
  
- **Exchange ActiveSync デバイスの制限** 1 メールボックスあたりの Exchange ActiveSync デバイスの最大数。 
    
- **Exchange ActiveSync デバイス削除の制限** Exchange 管理者が 1 か月で削除できる Exchange ActiveSync デバイスの最大数。 
    
- **Exchange ActiveSync ファイル添付の制限** Exchange ActiveSync デバイスが送受信できるメッセージ ファイル添付の最大サイズ。 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>各 Office 365 オプションの Exchange ActiveSync の制限

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Exchange ActiveSync デバイスの制限  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync デバイス削除の制限  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync ファイル添付の制限  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>各スタンドアロン オプションの Exchange ActiveSync の制限

||||||
|:-----|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Exchange Server 2013** <br/> |**Exchange Online プラン 1** <br/> |**Exchange Online プラン 2** <br/> |**Exchange Online Kiosk** <br/> |
|Exchange ActiveSync デバイスの制限  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync デバイス削除の制限  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync ファイル添付の制限  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
[タスクのサポートが必要なかどうか、または問題のトラブルシューティングを行う場合役に立つ次の記事: 電子メールhttps://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&ampは rs = en-us (英語)&amp;ad = ヘルプを作成して、電子メールの送信用に米国。ビジネスの管理のヘルプを Office 365 の電子メールhttps://go.microsoft.com/fwlink/?linkid=529722Fixマイクロソフトのサポートと Office 365 の回復時のアシスタントで Outlook と Office 365 の問題https://diagnostics.office.com/EmailOffice 365 の配信不能レポートhttps://go.microsoft.com/fwlink/?linkid=526653Exchangeオンライン ヘルプhttps://go.microsoft.com/fwlink/?linkid=825607TheMicrosoft Exchange Online での制限送信 limitsReporting とメッセージ トレース limitsRetention limitsDistribution グループ limitsJournal を次のカテゴリ: アドレス帳 limitsMailbox ストレージ limitsCapacity alertsMailbox フォルダー limitsMessage limitsReceiving のいずれかに適合します。調停 limitsExchange ActiveSync は、Microsoft Office 365 の組織に適用される制限を制限トランスポート、および受信トレイ ルールの制限は、組織がサービスに登録されてどのくらいの期間によって異なる場合があります。制限変更すると、マイクロソフトのデータ ・ センターすべての既存の顧客への変更を適用するのには時間がかかることができます。これらの制限のほとんどを変更することはできませんが、ユーザーが注意すべきことです。これらの制限は、内部および外部の受信者に適用されます。既定では、Exchange オンライン保護 (EOP) は、Exchange Online のメールボックスを保護します。Exchange online では、EOP の機能に適用される制限には、Office 365 のグループの制限については、Exchange のオンライン保護 Limits.For を参照してください、」の管理方法、groups?"Office 365 グループについて理解するを参照してくださいhttps://go.microsoft.com/fwlink/?linkid=846714。](#Top.md)
  
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

