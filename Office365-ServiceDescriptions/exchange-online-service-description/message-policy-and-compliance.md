---
title: メッセージ ポリシーとコンプライアンス
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132701"
---
# <a name="message-policy-and-compliance"></a>メッセージ ポリシーとコンプライアンス

## <a name="archiving-exchange-online-based-mailboxes"></a>Exchange Online ベースのメールボックスのアーカイブ

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online には、ユーザーが古い電子メールメッセージを保存するのに便利な場所を提供するインプレースアーカイブなど、クラウドベースのメールボックス用の組み込みアーカイブ機能が用意されています。 インプレースアーカイブは、Outlook および web 上の Outlook のユーザーのプライマリメールボックスフォルダーと共に表示される特別な種類のメールボックスです。 ユーザーは、アクセスして、プライマリメールボックスを検索するのと同じ方法でアーカイブにアクセスして検索できます。 利用可能な機能は、使用中のクライアントによって異なります。
  
- Outlook **2016、outlook 2013、outlook 2010、web 上の outlook**ユーザーは、アーカイブのすべての機能に加え、保持およびアーカイブポリシーの制御といった関連するコンプライアンス機能を利用できます。 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用し、特定のユーザーに対する個人用アーカイブ機能を有効にします。
  
詳細については、次のトピックを参照してください。
  
- [Exchange Online のアーカイブ メールボックス](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [ Exchange Online のアーカイブ メールボックスを有効または無効にする ](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>アーカイブのサイズ

個々の個人用アーカイブには、1 人のユーザーのメッセージ データを保存できます。 ストレージの割り当ては、次のようにサブスクリプション プランによって異なります。 アーカイブメールボックスのサイズの詳細については、「 [Exchange Online の制限](exchange-online-limits.md)」の「メールボックスの格納域の制限」セクションを参照してください。
  
> [!IMPORTANT]
> - ジャーナリング、トランスポート ルール、または自動転送ルールを使用してアーカイブの目的のため、Exchange Online メールボックスにメッセージをコピーすることは許可されていません。 Microsoft は、メールボックスアーカイブが個人のシナリオで使用されていない場合や不適切な使用がある場合に、無制限のアーカイブを拒否する権利を留保します。
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online では、管理者が作成した .pst ファイルを個人用アーカイブにインポートするために、Exchange Server 2010 Service Pack 1 以降の_New-mailboximportrequest_ Windows PowerShell コマンドレットをサポートしていません。 ユーザーのプライマリ メールボックスとアーカイブの両方が Exchange Online にある場合、管理者は PST Capture (無料ツール) を使用してユーザーのプライマリ メールボックスまたはアーカイブに .pst ファイルのデータをインポートすることができます。

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>社内メールボックスのクラウドベースのアーカイブ

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> 管理フォルダー ポリシーが適用された Exchange 2010 メールボックス サーバー上の社内メールボックスを使用するユーザーでは、社内またはクラウドベースのインプレース アーカイブを有効にすることはできません。 
  
## <a name="retention-tags-and-retention-policies"></a>保持タグおよびアイテム保持ポリシー

Exchange Online で提供される保持ポリシーは、組織における電子メールおよびその他の通信に関連する負担を軽減するのに役立ちます。 これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。 管理者は、ユーザーにアイテム保持ポリシーのメニューを提供して、Outlook 2010 以降または web 上の Outlook を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。
  
Exchange Online では、管理者は Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用してアイテム保持ポリシーを管理します。
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
Outlook 2010 以降および web 上の Outlook では、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用することができます。 また、メッセージに適用済みのアイテム保持ポリシーや削除日を表示することもできます。 他の電子メール クライアントのユーザーは、管理者が設定したサーバー側のアイテム保持ポリシーに基づいて電子メール メッセージの削除またはアーカイブを行うことができます。
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> 管理フォルダー (Exchange Server 2007 で導入された古いメッセージング レコード管理方式) は Exchange Online では利用できません。 
  
詳細については、「[保持タグおよびアイテム保持ポリシー](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)」を参照してください。
  
## <a name="encryption-of-data-at-rest"></a>保管中データの暗号化

保存されている顧客データの暗号化は、BitLocker、DKM、Azure Storage Service の暗号化、Exchange Online、Skype for business、OneDrive for Business、および SharePoint Online のサービス暗号化など、複数のサービス側テクノロジによって提供されます。 Office 365 Service Encryption には、Azure Key Vault に格納され、顧客によって管理される暗号化キーを使用するオプションがあります。 この顧客管理キーオプション ( [Customer キー](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697)と呼ばれる) は、Exchange Online、SharePoint Online、OneDrive for business で使用できます。 
  
### <a name="bitlocker"></a>BitLocker

Microsoft サーバーは、BitLocker を使用して、お客様のデータが保存されているディスクドライブをボリュームレベルで暗号化します。 BitLocker 暗号化は、Windows に組み込まれているデータ保護機能です。 BitLocker は、顧客データが含まれるディスクに何者かが物理的にアクセスできるようになりかねない過失がプロセスや制御 (アクセス制御またはハードウェアのリサイクルなど) で生じた場合に、脅威から安全に保護するために使用されるテクノロジの 1 つです。 その場合、BitLocker は、コンピューターやディスクの紛失、盗難、または不適切な廃棄によるデータの盗難や漏洩などの脅威の可能性を低減します。 
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

In addition to BitLocker, we use a technology called Distributed Key Manager (DKM). DKM is a client-side functionality that uses a set of secret keys to encrypt and decrypt information. Only members of a specific security group in Active Directory Domain Services can access those keys to decrypt the data that is encrypted by DKM. In Exchange Online, only certain service accounts under which the Exchange processes run are part of that security group. As part of standard operating procedure in the datacenter, no human is given credentials that are part of this security group and therefore no human has access to the keys that can decrypt these secrets.
  
## <a name="customer-key"></a>顧客キー

顧客キーを使用して、組織の暗号化キーを制御し、Microsoft のデータセンターで保存されているデータを暗号化するように構成します。 保存データには、メールボックスに保存されている Exchange Online および Skype for Business からのデータと、SharePoint Online および OneDrive for Business に保存されているファイルが含まれます。 詳細については、「顧客キーを[使用してデータを管理する](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)」および「[顧客キーの FAQ](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq)」を参照してください。
  
## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption allows email users to send encrypted email messages to anyone. We announced new capabilities in Office Message Encryption that leverage the protection features in Azure Information Encryption. These new capabilities provided enhanced end user experiences that make it easier to share and collaborate on protected messages with anyone inside or outside the organization. The new Office Message Encryption capabilities have some setup requirements. See Set up new Office 365 Message Encryption capabilities built on top of Azure Information Protection. Customers on legacy Office 365 Message Encryption do not get the new capabilities without following the set up guidance provided above. Please read the [FAQ](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) for more details on what's included in the new vs. legacy Office 365 Message Encryption capabilities. 

Office 365 Advanced Message Encryption では、メッセージの有効期限と失効を許可することによって、追加の保護を提供します。  組織から送信される暗号化メール用に複数のテンプレートを作成することもできます。  高度なメッセージの暗号化は、Microsoft 365 E5、Office 365 E5、Microsoft 365 E5 (非営利スタッフの価格)、Office 365 Enterprise E5 (非営利スタッフの価格)、または Office 365 教育 A5 に含まれています。 Office 365 Advanced Message Encryption を含まないサブスクリプションが組織にある場合は、Microsoft 365 E5 コンプライアンスまたは Office 365 Advanced コンプライアンス SKU をアドオンとして購入できます。

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME は Microsoft Edge および Internet Explorer 11 でサポートされています。 現在、S/MIME は Firefox、Opera、および Chrome でサポートされていません。 詳細については、「[S/MIME によるメッセージの署名と暗号化](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019)」を参照してください。
  
## <a name="in-place-hold-and-litigation-hold"></a>インプレース保持と訴訟ホールド

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
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
  
詳細については、「[インプレース保持と訴訟ホールド](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds)」を参照してください。
  
## <a name="in-place-ediscovery"></a>インプレース電子情報開示 (eDiscovery)

Exchange Online を使用すると、ユーザーは web ベースのインターフェイスを使用して、組織全体のメールボックスの内容を検索できます。 インプレースの電子情報開示検索の実行を許可された管理者やコンプライアンス担当者およびセキュリティ担当者は、(割り当てにより) 電子メール メッセージ、添付ファイル、予定表の予定、タスク、連絡先、およびその他のアイテムを検索できます。 インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。 KQL 構文に加えて、送信者、受信者、メッセージの種類、送信/受信日付、およびカーボン コピー/ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。 検索結果には、検索クエリに一致した削除済みアイテム フォルダー内のアイテムも含まれます。
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
管理者は、Exchange 管理センターまたはリモート Windows PowerShell を使用して、インプレース電子情報開示検索で一度に最大 10,000 のメールボックスを検索できます。 
  
Exchange Online では、権限のあるユーザーがインプレース電子情報開示を実行して次の操作のいずれかを選択できます。
  
- **検索結果の推定** 検索によって返されるメッセージ数の見積もりを返します。これには、検索で使用されたキーワードの有効性を判断するキーワードの統計および必要に応じて検索パラメーターの微調整が含まれます。 
    
- **検索結果のプレビュー**
    
- 検索結果に返されたメッセージを検出メールボックスにコピーします。
    
詳細については、「[インプレース電子情報開示 (eDiscovery) (このページは英語の可能性があります)](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)」を参照してください。
  
## <a name="mail-flow-rules"></a>メール フロー ルール

You can use mail flow rules to look for specific conditions on messages that pass through your organization and act on them. Mail flow rules let you apply messaging policies to email messages, secure messages, protect messaging systems, and prevent information leakage.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- 不適切なコンテンツが組織に侵入したり組織から発信されたりしないようにする
    
- 組織の機密情報をフィルター処理する
    
- 特定の個人によって送受信されるメッセージを追跡またはコピーする
    
- 配信する前に、検査のために受信メッセージと送信メッセージをリダイレクトする
    
- メッセージが組織を通過するときに免責事項を適用する
    
> [!IMPORTANT]
> Attachment file types that require installation of third-party iFilters on the email server (such as Adobe .pdf) cannot be inspected using mail flow rules until after an appropriate iFilter is installed. For more information about file types that are supported by mail flow rules, see [Use mail flow rules to inspect message attachments in Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
メール フロー ルールの詳細については、「[Exchange 2016 でのメール フロー ルール](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019)」をご覧ください。
  
## <a name="data-loss-prevention"></a>データ損失防止

データ損失防止 (DLP) 機能は、詳細なコンテンツ分析によって組織内の機密情報を特定、監視、保護するのに役立ちます。 DLP は、ビジネスに不可欠なメールには保護する必要がある機密データが含まれているため、エンタープライズメッセージシステムにとってますます重要になるプレミアム機能です。 Exchange Online の DLP 機能を使用すると、ワーカーの生産性に影響を与えることなく機密データを保護できます。
  
DLP ポリシーは Exchange 管理センター (EAC) の管理インターフェイスで構成できます。この管理インターフェイスでは、次の操作を行うことができます。 
  
- PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。
    
- 既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。
    
- DLP ポリシーを完全に実施する前にその効果をテストできます。
    
- 独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。
    
- メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、Exchange Online で処理を実行する信頼レベルを調整できます。
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- ポリシーヒントを追加します。これにより、Outlook 2016、Outlook 2013、Outlook on the web、およびデバイスユーザー用 OWA に通知が表示されるので、データの損失を減らすことができます。また、誤報告を許可することで、ポリシーの有効性を向上させることもできます。 
    
- インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。
    
DLP の詳細については、「[データ損失防止](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)」を参照してください。
  
## <a name="journaling"></a>ジャーナリング

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
信頼性の高いジャーナリングを実現するには、次のタスクをすべて実行する必要があります。
  
- ジャーナリングの送信先が Exchange Online のメールボックスになっていないことを確認します。
    
- カスタマーのディレクトリにジャーナリングで使用する SMTP ターゲット メール アドレスの連絡先オブジェクトを作成します。
    
- もう 1 つ別の連絡先オブジェクトを作成します。これは、プライマリのジャーナル メールボックスが使用できないときにジャーナル レポートを受け取る代替用のジャーナル メールボックスです。
    
- SMTP ターゲットの適切な管理、冗長性、可用性、パフォーマンス、および機能レベルを維持して、いつでもメッセージを正常に受信できるようにします。
    
- メッセージ形式、送信者/受信者情報の統合、および適切なコンテンツ変換など、Exchange Server および Exchange トランスポートでの相互運用性を実現します。
    
ジャーナルの詳細については、「[Exchange Online でのジャーナリング](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

