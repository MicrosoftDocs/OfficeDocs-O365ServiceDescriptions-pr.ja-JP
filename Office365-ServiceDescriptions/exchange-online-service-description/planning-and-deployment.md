---
title: 計画と展開
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: 30d1c68976bf450a87ace792af0b219b0fce21d4
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262740"
---
# <a name="planning-and-deployment"></a>計画と展開

## <a name="planning-for-service-changes-and-growth"></a>サービスの変更と拡大の計画

組織は、送信元の電子メール システム、希望する最終的な状態 (完全なホスティングか、あるいは部分的なホスティングか)、移行するユーザーの数、またどの程度の期間で最終的な状態を実現しなければならないのかに基づいて、移行オプションを選択する必要があります。
  
## <a name="deployment-options"></a>展開オプション

- **クラウドのみの展開** お客様の組織では、すべてのユーザー メールボックスを Exchange Online でホストします。 
    
- **Exchange ハイブリッド展開** お客様の組織では、一部のユーザー メールボックスを社内 Exchange 組織でホストし、他のユーザー メールボックスを Exchange Online でホストします。 
    
### <a name="cloud-only"></a>クラウド専用

クラウドのみの展開とは、Exchange Online サービス内の組織が、社内 Exchange 組織とは接続されない展開のことです。すべてのユーザーおよびメールボックスは、Exchange Online と Office 365 でホストおよび管理されます。
  
### <a name="hybrid"></a>ハイブリッド

Microsoft Exchange 2003、Exchange 2007、Exchange 2010 および Exchange 2013 社内組織で利用可能なハイブリッド展開は、社内でホストされる一部のメールボックスと、Exchange Online でホストされる他のメールボックスが長期にわたって共存する構成か、すべてのユーザー メールボックスを Exchange Online でホストするための移行パスを提供します。ハイブリッド展開によって、充実した機能の利用、および既存の社内 Microsoft Exchange 組織に対する管理制御をクラウドにまで拡張することができます。ハイブリッド展開の機能には、安全なメール トランスポート、共有予定表の空き時間情報、および社内組織と Exchange Online 組織間のメッセージ追跡が含まれます。
  
ハイブリッド展開の詳細については、「[Exchange Server のハイブリッド展開](https://go.microsoft.com/fwlink/p/?LinkId=287035)」を参照してください。21Vianet が運用している Office 365 を使用している場合は、「[21Vianet が運用している Office 365 を使用して Exchange ハイブリッド展開機能を構成する](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)」をご覧ください。
  
> [!IMPORTANT]
> オンプレミスの Exchange 2003 組織は、Exchange Online でハイブリッド展開を構成する場合、少なくとも 1 台の Exchange 2010 クライアント アクセス/メールボックス サーバーをインストールする必要があります。オンプレミスの Exchange 2007 組織は、Exchange Online でハイブリッド展開を構成する場合、少なくとも 1 台の Exchange 2010 または Exchange 2013 のクライアント アクセス/メールボックス サーバーをインストールする必要があります。オンプレミスの Exchange 2010 および Exchange 2013 組織は、Exchange Online でのハイブリッド展開をネイティブでサポートします。ハイブリッド展開における Exchange サーバーの互換性の詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/p/?LinkId=243541)」を参照してください。 > オンプレミスの Exchange 組織では、組織をハイブリッド展開用に構成する必要があります。管理者が Exchange Server 展開アシスタントおよびハイブリッド構成ウィザードを使用してハイブリッド展開を構成することを強くお勧めします。詳細については、「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」を参照してください。
  
## <a name="migration-options"></a>移行オプション

組織は、送信元の電子メール システム、希望する最終的な状態 (完全なホスティングか、あるいは部分的なホスティングか)、移行するユーザーの数、またどの程度の期間で最終的な状態を実現しなければならないのかに基づいて、移行オプションを選択する必要があります。実行可能な移行オプションは次のとおりです。
  
- **IMAP 移行** メールボックスのデータを IMAP ベースの電子メール システムから Exchange Online に移行します。 
    
- **Exchange の一括移行** メールボックスを、Exchange Server 2003、Exchange Server 2007、Exchange Server 2010、Exchange 2013 およびホストされる Exchange システムから、1 回の一括移行で Exchange Online に移行します。 
    
- **段階的な Exchange の移行** メールボックスを、Exchange Server 2003 または Exchange Server 2007 から、Web ベースの移行ツールを使用して、最小限の変更で社内インフラストラクチャに段階的に移行します。 
    
- **リモート移動移行** Exchange のハイブリッド展開で社内の Exchange メールボックスを Exchange Online に移行します。リモート移動移行を使用するには Exchange ハイブリッド展開を実装しておく必要があります。 
    
Exchange Online への電子メールおよびメールボックスの移行の詳細については、「[Exchange Online へのメールボックスの移行](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)」を参照してください。
  
### <a name="imap-migration"></a>IMAP 移行

Exchange Online は、IMAP をサポートする電子メールシステムからメールボックスのデータを移行するための Web ベースのツールを提供します。管理者はこのツールにより、次の手順で移行を進めることができます。 
  
1. 組織内のユーザー用のクラウドに空のメールボックスを作成します (通常は CSV ファイルをアップロードするか、リモート Windows PowerShell を使用することにより実行できます)。
    
2. リモート サーバー接続の設定を入力します。
    
3. CSV ファイルを使用して、Exchange Online のメールボックスにデータを移行するメールボックスを指定します。
    
4. この情報が入力されると、Exchange Online は、メールボックスのコンテンツを IMAP 経由で移行し始めます (予定表アイテム、連絡先、タスクなど、メール以外のアイテムは移行されません)。
    
IMAP 移行の詳細については、「[IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481)」と「[他の種類の IMAP メールボックスを Office 365 に移行する](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)」を参照してください。
  
> [!IMPORTANT]
> 移行時のリモート サーバーのリソースや帯域幅の過剰な使用を避けるため、Exchange Online では、作成する IMAP サーバーへの接続を 10 未満に抑えます。 
  
### <a name="cutover-exchange-migration"></a>Exchange の一括移行

Exchange Online は、社内の Exchange Server 2003、Exchange Server 2007、または Exchange Server 2010 環境からデータを移行するための Web ベースのツールを提供します。管理者はこのツールにより、次の手順で移行を進めることができます。
  
1. Exchange Online では、電子メール アドレスと社内管理者アカウントのための資格情報を使用して、社内電子メール組織に自動検出サービスで接続します。
    
2. Exchange Online では、RPC/HTTP 接続を使用してリモート サーバーからディレクトリ情報を読み取り、Exchange Online にメールボックスを作成します。
    
3. Exchange Online は、メールボックスのコンテンツとクラウド メールボックスを同期します。データは Exchange Online に移行されますが、ユーザーは引き続き元のメールボックスに接続されます。
    
4. 最初の移行が完了した後、管理者が移行バッチを停止または削除するまで、すべての変更は 24 時間ごとにクラウドに同期されます。
    
管理者は、Office 365 をポイントするようにユーザーの MX レコードを構成し、Outlook のユーザー プロファイルを再構成して、ユーザーをクラウド メールボックスに切り替えます。ユーザーがクラウド メールボックスに切り替わると、ローカルのオフライン フォルダー (OST ファイル) が再同期され、移行されたメールがクライアント ワークステーションにダウンロードされます。移行が完了すると、ユーザーはメールボックス内の古いメッセージに返信できます。
  
Exchange の一括移行の詳細については、「[Office 365 への一括メール移行について知っておくべきこと](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)」を参照してください。
  
> [!IMPORTANT]
> 組織が Exchange の一括移行を使用してクラウドに移行できる Exchange 2003、Exchange 2007、Exchange 2010、または Exchange 2013 のメールボックスの最大数は 2,000 です。 > Exchange Online は社内の Exchange Server に接続しなければならないため、社内サーバーには、信頼できる証明機関の発行する証明書とパブリック IP アドレスが必要です。 
  
### <a name="staged-exchange-migration"></a>段階的な Exchange の移行

段階的な移行の場合、Web ベースの Exchange 移行ツールとディレクトリ同期ツールを使用してユーザーをクラウドに移行することができます。このとき、すべてのユーザーを同時に移行するのではなく、Exchange の一括移行のように、管理者は数回に分けてユーザーを移行します。この移行は、CSV ファイルをアップロードし、移行するユーザーの一覧の一部を指定することで実行されます。段階的な移行の場合、組織内のすべてのユーザーは、同じ電子メールのドメイン名を共有することができます。
  
段階的な Exchange の移行では、管理者が Online Services のディレクトリ同期ツールを使用する必要があります。このツールは、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧 (GAL) をユーザーに提供します。
  
Exchange での段階的な移行の詳細については、「[Office 365 への段階的メール移行について知っておくべきこと](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)」を参照してください。
  
> [!IMPORTANT]
> Exchange の段階的な移行では、Exchange 2010 および Exchange 2013 のメールボックスは移行できません。組織内の Exchange 2010 または Exchange 2013 メールボックスが 2,000 未満である場合は、Exchange の一括移行を使用できます。Exchange 2010 または Exchange 2013 メールボックスが 2,000 を超える場合は、ハイブリッド展開を実装することができます。 > 移行の際、管理者は、Online Services のディレクトリ同期ツールを使用して、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧 (GAL) をユーザーに提供する必要があります。 
  
## <a name="migration-tools"></a>移行ツール

Microsoft は、既存の電子メール環境を Exchange Online に移行するのに役立ついくつかのツールを提供しています。どのツールが適切かは、組織の現在の環境と展開目標によって異なります。
  
- **移行ダッシュボード** 管理者は、Exchange 管理センターで移行ダッシュボードを使用して、Exchange の一括移行または段階的な移行で、メールボックスの Exchange Online への移行を管理できます。管理者は、移行ダッシュボードを使用して、ユーザーのメールボックスのコンテンツを社内 IMAP サーバーから既存の Exchange Online メールボックスに移行することもできます。管理者は移行ダッシュボードにより、次のことが行えます。 
    
  - **複数の移行バッチを作成し、開始する** 管理者は、最大 100 個の移行バッチを作成して、キューに入れることができます。一度に実行できる移行バッチは 1 つのみですが、管理者は複数のバッチをキューに入れることができるため、1 つの移行バッチの実行が完了すると、キュー内の次のバッチが開始されます。 
    
  - **エラーを含む移行バッチの再開** 移行バッチに対する最初の同期の後、社内メールボックスから各ユーザーのクラウド メールボックスに移行バッチでアイテムがコピーされますが、一部のメールボックスの同期が失敗する場合があります。このとき管理者は、その移行バッチを再開して、失敗したメールボックスの同期を試行できます。 
    
  - **スキップされたアイテムの詳細情報を取得する** IMAP 移行、一括移行、および段階的な移行の場合、移行ダッシュボードには、スキップされたアイテムの情報が表示されます。この情報には、アイテムがユーザーのメールボックス内に置かれた理由と場所が含まれます。 
    
  - **移行レポートを開く** 管理者は、移行バッチの移行統計情報または移行エラー レポートをダッシュボードから開くことができます。 
    
  - **移行バッチを編集する** 段階的な Exchange の移行または IMAP 移行のための移行バッチが移行キューに含まれているものの現時点で実行されていない場合、管理者は移行バッチを編集することができます。 
    
- **Azure Active Directory 同期ツール** この Azure Active Directory 同期ツール は、移行の際に、Exchange Online と社内 Exchange Server の両方を利用する電子メール シナリオをハイブリッド化する重要な役割を果たします。このツールは、社内 Active Directory から Exchange Online への一方向の同期を実行します。管理者は、移行が完了した後、Exchange Online のみを使用して Active Directory ユーザーおよびグループを管理できます。また、このツールは、オンライン環境と社内環境が継続的に同期される統合グローバル アドレス一覧をユーザーに提供します。 
    
    Azure Active Directory 同期ツール の詳細については、「[オンプレミス ID と Azure Active Directory の統合](https://go.microsoft.com/fwlink/p/?LinkId=287034)」を参照してください。
    
- **ハイブリッド構成ウィザード** ハイブリッド構成ウィザードは、社内および Exchange Online 構成の機能とサービスを簡素化することにより、ハイブリッド展開プロセスを効率化します。Exchange Server 2010 Service Pack 2 の一部として導入されたハイブリッド構成ウィザードは、社内組織でのみ実行され、次のコンポーネントを備えています。 
    
  - 管理者によるハイブリッド展開の構成をエンドツーエンドのプロセスでサポートする Exchange 管理センター (EAC) のウィザード。
    
  - 構成プロセスを調整する一連の Exchange 管理シェル (EMS) コマンド。
    
    ハイブリッド構成ウィザードの詳細については、「[ハイブリッド構成ウィザード](https://go.microsoft.com/fwlink/p/?LinkId=271734)」を参照してください。
    
- **リモート Windows PowerShell** リモート Windows PowerShell は、Exchange Online 2011 Service Update の一部として、移行エラーのトラブルシューティングに使用できます。たとえば管理者は、移行バッチの診断情報や、プライマリ SMTP アドレスに基づくユーザーの移行統計情報および診断情報を表示できます。 
    
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

