---
title: 計画と展開
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132661"
---
# <a name="planning-and-deployment"></a>計画と展開

## <a name="planning-for-service-changes-and-growth"></a>サービスの変更と拡大の計画

組織は、送信元の電子メール システム、希望する最終的な状態 (完全なホスティングか、あるいは部分的なホスティングか)、移行するユーザーの数、またどの程度の期間で最終的な状態を実現しなければならないのかに基づいて、移行オプションを選択する必要があります。
  
## <a name="deployment-options"></a>展開オプション

- **クラウドのみの展開** お客様の組織では、すべてのユーザー メールボックスを Exchange Online でホストします。 
    
- **Exchange ハイブリッド展開** お客様の組織では、一部のユーザー メールボックスを社内 Exchange 組織でホストし、他のユーザー メールボックスを Exchange Online でホストします。 
    
### <a name="cloud-only"></a>クラウド専用

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>ハイブリッド

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>移行オプション

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **IMAP 移行** メールボックスのデータを IMAP ベースの電子メール システムから Exchange Online に移行します。 
    
- **Exchange の一括移行** メールボックスを、Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 およびホストされる Exchange システムから、1 回の一括移行で Exchange Online に移行します。 
    
- **段階的な Exchange の移行** メールボックスを、Exchange Server 2003 または Exchange Server 2007 から、Web ベースの移行ツールを使用して、最小限の変更で社内インフラストラクチャに段階的に移行します。 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Exchange Online への電子メールおよびメールボックスの移行の詳細については、「[Exchange Online へのメールボックスの移行](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)」を参照してください。
  
### <a name="imap-migration"></a>IMAP 移行

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. 組織内のユーザー用のクラウドに空のメールボックスを作成します (通常は CSV ファイルをアップロードするか、リモート Windows PowerShell を使用することにより実行できます)。
    
2. リモート サーバー接続の設定を入力します。
    
3. CSV ファイルを使用して、Exchange Online のメールボックスにデータを移行するメールボックスを指定します。
    
4. この情報が入力されると、Exchange Online は、メールボックスのコンテンツを IMAP 経由で移行し始めます (予定表アイテム、連絡先、タスクなど、メール以外のアイテムは移行されません)。
    
IMAP 移行の詳細については、「[IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)」と「[他の種類の IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)」を参照してください。
  
> [!IMPORTANT]
> 移行時のリモート サーバーのリソースや帯域幅の過剰な使用を避けるため、Exchange Online では、作成する IMAP サーバーへの接続を 10 未満に抑えます。 
  
### <a name="cutover-exchange-migration"></a>Exchange の一括移行

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Exchange Online では、電子メール アドレスと社内管理者アカウントのための資格情報を使用して、社内電子メール組織に自動検出サービスで接続します。
    
2. Exchange Online では、RPC/HTTP 接続を使用してリモート サーバーからディレクトリ情報を読み取り、Exchange Online にメールボックスを作成します。
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. 最初の移行が完了した後、管理者が移行バッチを停止または削除するまで、すべての変更は 24 時間ごとにクラウドに同期されます。
    
ユーザーをクラウドメールボックスに切り替えるには、管理者が Microsoft をポイントするように MX レコードを構成し、Outlook でユーザーのプロファイルを再構成します。 ユーザーがクラウド メールボックスに切り替わると、ローカルのオフライン フォルダー (OST ファイル) が再同期され、移行されたメールがクライアント ワークステーションにダウンロードされます。 移行が完了すると、ユーザーはメールボックス内の古いメッセージに返信できます。
  
Exchange の一括移行の詳細については、「[Office 365 への一括メール移行について知っておくべきこと](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)」を参照してください。
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>段階的な Exchange の移行

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Exchange での段階的な移行の詳細については、「[Office 365 への段階的メール移行について知っておくべきこと](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)」を参照してください。
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>移行ツール

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **スキップされたアイテムの詳細情報を取得する** IMAP 移行、一括移行、および段階的な移行の場合、移行ダッシュボードには、スキップされたアイテムの情報が表示されます。この情報には、アイテムがユーザーのメールボックス内に置かれた理由と場所が含まれます。 
    
  - **移行レポートを開く** 管理者は、移行バッチの移行統計情報または移行エラー レポートをダッシュボードから開くことができます。 
    
  - **移行バッチを編集する** 段階的な Exchange の移行または IMAP 移行のための移行バッチが移行キューに含まれているものの現時点で実行されていない場合、管理者は移行バッチを編集することができます。 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Azure Active Directory 同期ツール の詳細については、「[オンプレミス ID と Azure Active Directory の統合](https://go.microsoft.com/fwlink/p/?LinkId=287034)」を参照してください。
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - 管理者によるハイブリッド展開の構成をエンドツーエンドのプロセスでサポートする Exchange 管理センター (EAC) のウィザード。
    
  - 構成プロセスを調整する一連の Exchange 管理シェル (EMS) コマンド。
    
    ハイブリッド構成ウィザードの詳細については、「[ハイブリッド構成ウィザード](https://go.microsoft.com/fwlink/p/?LinkId=271734)」を参照してください。
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

