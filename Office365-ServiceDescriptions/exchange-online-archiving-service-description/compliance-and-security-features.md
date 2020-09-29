---
title: Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
description: この記事では、Microsoft Exchange Online アーカイブで利用できるコンプライアンス機能について説明します。
ms.openlocfilehash: 0826a2677dcc3d8c336ecea3901ed7486c71eda3
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293623"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online アーカイブのコンプライアンス機能とセキュリティ機能

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving のコンプライアンス機能

この記事では、Microsoft Exchange Online アーカイブのコンプライアンス機能について説明します。
  
### <a name="retention-policies"></a>アイテム保持ポリシー

Exchange Online アーカイブは、組織が電子メールやその他の通信に関連する負債を低減するのに役立つアイテム保持ポリシーを提供します。 これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。 管理者は、ユーザーにアイテム保持ポリシーのメニューを提供して、Outlook 2010 以降または web 上の Outlook を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。 Exchange Online のアーカイブでは、管理者がオンプレミスのインフラストラクチャからアイテム保持ポリシーを管理します。
  
Exchange Online Archiving は、アーカイブと削除の 2 種類のポリシーを提供します。両方のポリシーを同じアイテムまたはフォルダーに適用できます。たとえば、ユーザーは、電子メール メッセージにタグを付けて、電子メール メッセージが指定された日数に到達した時点で自動的に個人用アーカイブに移動され、さらに一定の日数が経過すると削除されるようにすることができます。
  
Outlook 2010 以降と web 上の Outlook では、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用し、メッセージに適用されているアイテム保持ポリシーと予期される削除日を表示することもできます。 他の電子メール クライアントのユーザーは、管理者が準備したサーバー側のアイテム保持ポリシーに基づいて電子メールを削除またはアーカイブできますが、同じレベルの表示および管理機能は使用できません。
  
Exchange Online Archiving で提供されるアイテム保持ポリシー機能は、Exchange Server 2010 Service Pack 2 (SP2) 以降で提供される機能と同じです。 管理者は、社内の Exchange Server 2010 以降の環境からアイテム保持ポリシーを管理できます。 管理対象フォルダー (Exchange 2007 で導入されたメッセージング レコード管理に対する従来のアプローチ) は Exchange Online Archiving と互換性がないため、利用できません。 詳細については、「[保持タグおよびアイテム保持ポリシー](https://go.microsoft.com/fwlink/p/?LinkID=314153)」を参照してください。
  
### <a name="in-place-hold-and-litigation-hold"></a>インプレース保持と訴訟ホールド

訴訟となる可能性がある程度見込まれる場合、組織では、訴訟に関連する電子メールを含めた電子的に格納された情報 (ESI) を保持する必要があります。訴訟の詳細が明らかになる前に訴訟の可能性を予測する場合もあるため、保持の対象が広範囲にわたることもあります。組織では、特定の問題に関するすべての電子メールを保存したり、特定の個人に関するすべての電子メールを保存したりします。
  
Exchange Online では、次の目標を達成するためにインプレース保持または訴訟ホールドを使用できます。
  
- ユーザーを保持の状態にしてメールボックス アイテムを変更しないで維持する
    
- ユーザーまたは自動削除プロセス (MRM など) によって削除されたメールボックス アイテムを維持する
    
- 元のアイテムのコピーを保存して、メールボックス アイテムを改ざん、ユーザーによる変更、または自動プロセスから保護する
    
- アイテムを無期限にまたは特定の期間維持する
    
- MRM を中断する必要をなくしユーザーが保持を意識しないで済むようにする
    
- インプレース電子情報開示を使用して、保留中のアイテムを含むメールボックス アイテムを検索する
    
加えて、インプレース保持を以下の目的に使用できます。
  
- 指定した条件と一致するアイテムを検索して保持する
    
- さまざまなケースまたは調査に対応できるようユーザーに複数のインプレース保持を設定する
    
> [!NOTE]
> メールボックスのインプレース保持または訴訟ホールドを有効にすると、プライマリ メールボックスとアーカイブ メールボックスの両方に保持 (ホールド) が適用されます。 
  
詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。
  
> [!NOTE]
> Exchange Online Archiving ユーザーの場合、回復可能なアイテム フォルダーの既定のクォータは 100 GB です。 
  
### <a name="in-place-ediscovery"></a>インプレース電子情報開示 (eDiscovery)

Exchange Online Archiving は、組織内のメールボックスの内容を検索するためのインフレース電子情報開示をサポートしています。 社内の Exchange 2013 サーバーから Exchange 管理センターまたはリモート Windows PowerShell を使用している管理者または認定証拠開示管理者は、電子メール メッセージ、添付ファイル、予定、タスク、連絡先などのさまざまなメールボックス アイテムを検索できます。 インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。 Keyword Query Language (KQL) 構文に加えて、送信者、受信者、メッセージの種類、送信日、受信日、カーボン コピー、ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。 詳細については、「[インプレース電子情報開示 (eDiscovery)](https://go.microsoft.com/fwlink/p/?LinkId=314169)」を参照してください。
  
Exchange 管理センターとリモート Windows PowerShell を使用すると、インプレース電子情報開示検索で最大 5,000 個のメールボックスを同時に検索できます。リモート Windows PowerShell を使用してインプレース電子情報開示検索を実行する方法については、「[New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)」を参照してください。 
  
> [!NOTE]
> リモート Windows PowerShell では、 `Search-Mailbox` コマンドレットを使用して 5,000 個を超えるメールボックスを検索できます。リモート Windows PowerShell を使用して大量のメールボックスを検索する場合の詳細については、「 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)」を参照してください。 
  
インプレース電子情報開示検索の結果は、Exchange 管理センターでプレビューしたり, .pst ファイルにエクスポートしたり、探索メールボックスという特殊なメールボックスにコピーしたりできます。管理者またはコンプライアンス担当役員は、探索メールボックスに接続してメッセージを確認できます。詳細については、「[インプレース電子情報開示検索を作成する](https://go.microsoft.com/fwlink/p/?LinkId=314172)」を参照してください。
  
> [!NOTE]
> 社内およびクラウド ベースのメールボックスまたはアーカイブに対して実行されたインプレース電子情報開示検索の結果をコピーする場合は、社内探索メールボックスを選択する必要があります。社内のプライマリ メールボックスとクラウド ベースのアーカイブからのメッセージは、社内の探索メールボックスにコピーされます。 
  
管理者は、組織全体の複数のメールボックスに送信された不適切な電子メール メッセージを検索して削除することもできます。たとえば、機密扱いの給与情報が誤ってすべての従業員に電子メールで送信された場合は、管理者がユーザーのメールボックスからその電子メールを削除できます。この種の検索は、Exchange 管理センターでは使用できません。リモート PowerShell を使用して実行する必要があります。ユーザーのメールボックスからメッセージを削除する方法については、「[Exchange 2016 でメッセージを検索して削除する](https://go.microsoft.com/fwlink/p/?LinkId=314173)」を参照してください。
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving のセキュリティ機能

以下のセクションでは、Microsoft Exchange Online Archiving のセキュリティ機能について説明します。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>社内サーバーと Exchange Online Archiving 間の暗号化

TLS は、電子メール サーバー間の接続を暗号化して、スプーフィングの回避を支援したり、伝送中のメッセージの機密性を確保したりするために使用されます。 TLS は、Exchange Online アーカイブ用に Microsoft データセンターへの社内メールサーバートラフィックをセキュリティで保護するためにも使用されます。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>クライアントと Exchange Online Archiving 間の暗号化

Exchange Online Archiving へのクライアント接続は、以下の暗号化方法を使用してセキュリティを強化します。
  
- SSL は、TCP ポート443を使用して Outlook、Outlook on the web、および Exchange Web サービスのトラフィックを保護するために使用されます。
    
- 社内のサーバーへのクライアント接続は、Exchange Online Archiving の導入によって変更されません。
    
### <a name="encryption-smime-and-pgp"></a>暗号化: S/MIME と PGP

Exchange Online Archiving は、Secure/Multipurpose Internet Mail Extension (S/MIME) メッセージを保存します。ただし、Exchange Online Archiving が S/MIME 機能または公開キーをホストしたり、キー リポジトリ、キー管理、キー ディレクトリ サービスを提供したりすることはありません。これは、これらのサービスのすべてが社内の Exchange インフラストラクチャに附属しているためです。
  
同様に、Exchange Online Archiving は Pretty Good Privacy (PGP) などのクライアント側のサード パーティ暗号化ソリューションを使用して暗号化されたメッセージを保存します。
  
### <a name="information-rights-management"></a>Information Rights Management

Exchange Online Archiving はホスト型 Information Rights Management (IRM) サービスを提供しませんが、管理者は社内の Active Directory Rights Management Services (AD RMS) を使用できます。AD RMS サーバーが展開されている場合、Outlook はそのサーバーと直接通信できるため、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。AD RMS サーバーと社内の Exchange 環境間の相互運用性が構成されていれば、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Outlook on the web での IRM のサポート

ユーザーは、Outlook 上の Outlook で、IRM で保護されたメッセージを Outlook の場合と同じように、読み取りおよび作成を行うことができます。 Web 上の Outlook の IRM で保護されたメッセージには、Internet Explorer、Firefox、Safari、および Chrome を介してアクセスできます (プラグインは必要ありません)。 このメッセージには、フルテキスト検索、スレッド ビュー、プレビュー ウィンドウが含まれています。 Active Directory Rights Management サービス サーバーと社内の Exchange 環境間の相互運用性を有効にするように構成する必要があります。
  
#### <a name="irm-search"></a>IRM 検索

IRM で保護されたメッセージは、ヘッダー、件名、本文、添付ファイルなどのインデックスが作成され、検索可能になります。 ユーザーは、Outlook と web 上の Outlook で IRM で保護されたアイテムを検索でき、管理者はインプレース電子情報開示または **検索-メールボックス** コマンドレットを使用して irm で保護されたアイテムを検索できます。
  
### <a name="auditing"></a>監査

Exchange Online Archiving は、2 種類の組み込み監査機能を提供します。
  
- **管理者監査ログ** -管理者監査ログを使用すると、ユーザーは、RBAC の役割または exchange のポリシーと設定の変更を含め、exchange Online のアーカイブ環境で管理者によって加えられた変更を追跡できます。 
    
- **メールボックス監査ログ** -メールボックス監査ログを使用すると、メールボックスの所有者以外のユーザーがメールボックスへのアクセスを追跡できます。 
    
Exchange 管理センターで、管理者の役割の変更、訴訟ホールド、所有者以外のメールボックス アクセスなどのいくつかの定義済みの監査レポートを利用できます。管理者は、日付や役割でレポートをフィルター処理したり、特定のメールボックスに対するすべての監査イベントを XML 形式でエクスポートして長期保存やカスタム レポート作成に利用したりできます。
  
管理者監査ログは既定でオンになっており、メールボックス監査ログは既定でオフになっています。管理者は、リモート Windows PowerShell を使用して、組織内の一部またはすべてのメールボックスに対してメールボックス監査ログを有効にすることができます。詳細については、「[Exchange 監査レポート](https://go.microsoft.com/fwlink/p/?LinkId=314175)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。
  

