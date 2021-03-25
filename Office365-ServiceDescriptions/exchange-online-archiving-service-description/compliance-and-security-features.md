---
title: コンプライアンスとセキュリティ機能 (Exchange Online Archiving
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
description: この記事では、アーカイブで使用できるコンプライアンス機能についてMicrosoft Exchange Onlineしてください。
ms.openlocfilehash: db2a6c515e5d438dce98a9a14d880ea40c25f505
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173312"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>コンプライアンスとセキュリティ機能 (Exchange Online Archiving

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving のコンプライアンス機能

この記事では、アーカイブのコンプライアンスMicrosoft Exchange Online説明します。
  
### <a name="retention-policies"></a>アイテム保持ポリシー

Exchange Online Archivingは、組織が電子メールや他の通信に関連する負債を減らすのに役立つ保持ポリシーを提供します。 これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。 管理者は、ユーザーにアイテム保持ポリシーのメニューを提供し、Outlook 2010 以降または Outlook on the web を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。 管理者Exchange Online Archivingオンプレミス インフラストラクチャからアイテム保持ポリシーを管理します。
  
Exchange Online Archiving は、アーカイブと削除の 2 種類のポリシーを提供します。両方のポリシーを同じアイテムまたはフォルダーに適用できます。たとえば、ユーザーは、電子メール メッセージにタグを付けて、電子メール メッセージが指定された日数に到達した時点で自動的に個人用アーカイブに移動され、さらに一定の日数が経過すると削除されるようにすることができます。
  
Outlook 2010 以降と Outlook on the web を使用すると、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用し、メッセージに適用された保持ポリシーと予想される削除日を表示することもできます。 他の電子メール クライアントのユーザーは、管理者が準備したサーバー側のアイテム保持ポリシーに基づいて電子メールを削除またはアーカイブできますが、同じレベルの表示および管理機能は使用できません。
  
Exchange Online Archiving で提供されるアイテム保持ポリシー機能は、Exchange Server 2010 Service Pack 2 (SP2) 以降で提供される機能と同じです。 管理者は、社内の Exchange Server 2010 以降の環境からアイテム保持ポリシーを管理できます。 管理対象フォルダー (Exchange 2007 で導入されたメッセージング レコード管理に対する従来のアプローチ) は Exchange Online Archiving と互換性がないため、利用できません。 詳細については、「[保持タグおよびアイテム保持ポリシー](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)」を参照してください。
  
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
  
詳細については、「[インプレース保持と訴訟ホールド](/exchange/security-and-compliance/in-place-and-litigation-holds)」を参照してください。
  
> [!NOTE]
> Exchange Online Archiving ユーザーの場合、回復可能なアイテム フォルダーの既定のクォータは 100 GB です。 
  
### <a name="in-place-ediscovery"></a>インプレース電子情報開示 (eDiscovery)

Exchange Online Archiving は、組織内のメールボックスの内容を検索するためのインフレース電子情報開示をサポートしています。 社内の Exchange 2013 サーバーから Exchange 管理センターまたはリモート Windows PowerShell を使用している管理者または認定証拠開示管理者は、電子メール メッセージ、添付ファイル、予定、タスク、連絡先などのさまざまなメールボックス アイテムを検索できます。 インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。 Keyword Query Language (KQL) 構文に加えて、送信者、受信者、メッセージの種類、送信日、受信日、カーボン コピー、ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。 詳細については、「[インプレース電子情報開示 (eDiscovery)](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)」を参照してください。
  
Exchange 管理センターとリモート Windows PowerShell を使用すると、インプレース電子情報開示検索で最大 5,000 個のメールボックスを同時に検索できます。リモート Windows PowerShell を使用してインプレース電子情報開示検索を実行する方法については、「[New-MailboxSearch](/powershell/module/exchange/new-mailboxsearch)」を参照してください。 
  
> [!NOTE]
> リモート Windows PowerShell では、 `Search-Mailbox` コマンドレットを使用して 5,000 個を超えるメールボックスを検索できます。リモート Windows PowerShell を使用して大量のメールボックスを検索する場合の詳細については、「 [Search-Mailbox](/powershell/module/exchange/search-mailbox)」を参照してください。 
  
インプレース電子情報開示検索の結果は、Exchange 管理センターでプレビューしたり, .pst ファイルにエクスポートしたり、探索メールボックスという特殊なメールボックスにコピーしたりできます。管理者またはコンプライアンス担当役員は、探索メールボックスに接続してメッセージを確認できます。詳細については、「[インプレース電子情報開示検索を作成する](/microsoft-365/compliance/content-search)」を参照してください。
  
> [!NOTE]
> 社内およびクラウド ベースのメールボックスまたはアーカイブに対して実行されたインプレース電子情報開示検索の結果をコピーする場合は、社内探索メールボックスを選択する必要があります。社内のプライマリ メールボックスとクラウド ベースのアーカイブからのメッセージは、社内の探索メールボックスにコピーされます。 
  
管理者は、組織全体の複数のメールボックスに送信された不適切な電子メール メッセージを検索して削除することもできます。たとえば、機密扱いの給与情報が誤ってすべての従業員に電子メールで送信された場合は、管理者がユーザーのメールボックスからその電子メールを削除できます。この種の検索は、Exchange 管理センターでは使用できません。リモート PowerShell を使用して実行する必要があります。ユーザーのメールボックスからメッセージを削除する方法については、「[Exchange 2016 でメッセージを検索して削除する](/Exchange/policy-and-compliance/ediscovery/delete-messages)」を参照してください。
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving のセキュリティ機能

以下のセクションでは、Microsoft Exchange Online Archiving のセキュリティ機能について説明します。
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>社内サーバーと Exchange Online Archiving 間の暗号化

TLS は、電子メール サーバー間の接続を暗号化して、スプーフィングの回避を支援したり、伝送中のメッセージの機密性を確保したりするために使用されます。 TLS は、Microsoft データセンターへのオンプレミスのメール サーバー トラフィックをセキュリティで保護するためにも使用Exchange Online Archiving。
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>クライアントと Exchange Online Archiving 間の暗号化

Exchange Online Archiving へのクライアント接続は、以下の暗号化方法を使用してセキュリティを強化します。
  
- SSL は、TCP ポート 443 を使用して Outlook、Outlook on the Web、および Exchange Web Services トラフィックをセキュリティ保護するために使用されます。
    
- 社内のサーバーへのクライアント接続は、Exchange Online Archiving の導入によって変更されません。
    
### <a name="encryption-smime-and-pgp"></a>暗号化: S/MIME と PGP

Exchange Online Archiving は、Secure/Multipurpose Internet Mail Extension (S/MIME) メッセージを保存します。ただし、Exchange Online Archiving が S/MIME 機能または公開キーをホストしたり、キー リポジトリ、キー管理、キー ディレクトリ サービスを提供したりすることはありません。これは、これらのサービスのすべてが社内の Exchange インフラストラクチャに附属しているためです。
  
同様に、Exchange Online Archiving は Pretty Good Privacy (PGP) などのクライアント側のサード パーティ暗号化ソリューションを使用して暗号化されたメッセージを保存します。
  
### <a name="information-rights-management"></a>Information Rights Management

Exchange Online Archiving はホスト型 Information Rights Management (IRM) サービスを提供しませんが、管理者は社内の Active Directory Rights Management Services (AD RMS) を使用できます。AD RMS サーバーが展開されている場合、Outlook はそのサーバーと直接通信できるため、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。AD RMS サーバーと社内の Exchange 環境間の相互運用性が構成されていれば、ユーザーは IRM 保護メッセージの作成と読み取りを行うことができます。
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Outlook on the web での IRM のサポート

ユーザーは、Outlook と同じ方法で、Outlook on the web で IRM で保護されたメッセージをネイティブに読み取り、作成できます。 Outlook on the web の IRM で保護されたメッセージには、Internet Explorer、Firefox、Safari、および Chrome からアクセスできます (プラグインは必要ありません)。 このメッセージには、フルテキスト検索、スレッド ビュー、プレビュー ウィンドウが含まれています。 Active Directory Rights Management サービス サーバーと社内の Exchange 環境間の相互運用性を有効にするように構成する必要があります。
  
#### <a name="irm-search"></a>IRM 検索

IRM で保護されたメッセージは、ヘッダー、件名、本文、添付ファイルなど、インデックスが作成され、検索できます。 ユーザーは Outlook と Outlook on the web で IRM で保護されたアイテムを検索できます。管理者は In-Place 電子情報開示または **Search-Mailbox** コマンドレットを使用して IRM で保護されたアイテムを検索できます。
  
### <a name="auditing"></a>監査

Exchange Online Archiving は、2 種類の組み込み監査機能を提供します。
  
- **管理者監査ログ** - 管理者監査ログを使用すると、管理者が Exchange Online Archiving 環境で行った変更 (RBAC の役割や Exchange ポリシーや設定の変更など) を追跡できます。 
    
- **メールボックス監査ログ** - メールボックス監査ログを使用すると、ユーザーはメールボックス所有者以外のユーザーによるメールボックスへのアクセスを追跡できます。 
    
Exchange 管理センターで、管理者の役割の変更、訴訟ホールド、所有者以外のメールボックス アクセスなどのいくつかの定義済みの監査レポートを利用できます。管理者は、日付や役割でレポートをフィルター処理したり、特定のメールボックスに対するすべての監査イベントを XML 形式でエクスポートして長期保存やカスタム レポート作成に利用したりできます。
  
管理者監査ログは既定でオンになっており、メールボックス監査ログは既定でオフになっています。管理者は、リモート Windows PowerShell を使用して、組織内の一部またはすべてのメールボックスに対してメールボックス監査ログを有効にすることができます。詳細については、「[Exchange 監査レポート](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online Archiving [参照してください](exchange-online-archiving-service-description.md)。
