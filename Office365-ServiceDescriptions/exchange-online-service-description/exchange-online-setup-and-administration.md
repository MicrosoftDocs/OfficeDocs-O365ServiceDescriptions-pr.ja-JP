---
title: Exchange Online のセットアップと管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を稼働、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
ms.openlocfilehash: 56d7dbc7e5e6300172d120bbf1464fd2bbf0daf0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652731"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online のセットアップと管理

この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を稼働、最新の状態に保つために使用できる管理コントロールとサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
  
## <a name="self-service-administration-tools"></a>セルフ サービス管理ツール

Microsoft は、すべての Exchange Online データ センターを直接制御し、システム全体のパフォーマンスを担当しますが、ユーザーに全体的なエクスペリエンスを提供するために組み合わせる要素の一部のみを制御できます。 組織自体は、データ センターへのネットワーク接続、顧客のワイド エリア ネットワーク (WAN)、および顧客のローカル エリア ネットワーク (LAN) を担当します。 さらに、ユーザー デバイスとその構成を担当します。また、ユーザーが機能にアクセスする必要がある限り、これらの機能を管理する機能を含むが、これらに限定されない任意の機能に対して、ユーザーごとに必要なライセンスを維持する責任があります。
  
このため Exchange Online は、次に説明するツールをカスタマーの管理者に提供し、メッセージングに関するさまざまなタスクを管理できるようにします。
  
- [Microsoft Office 365 ポータル](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 管理センター](#microsoft-365-admin-center)
    
- [Exchange 管理センター](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 用リモート Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 ポータル

Microsoft Office 365 ポータル ([https://portal.office.com](https://portal.office.com)) は、管理者やパートナーが Office 365 サービスを購入および管理する Web サイトです。ユーザーは、このサイトで Office 365 コラボレーション ツールにアクセスして使用することができます。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 管理センター

Microsoft 365 管理センターは、各会社のサービス管理者が購読する各 Microsoft サービスのユーザー アカウントと設定を管理できる Web ポータルです。 Microsoft 365 管理センター内から、管理者は Exchange 管理センター (EAC) へのリンクに従って、Exchange Online 固有の設定を管理できます。 Microsoft 365 管理センターを使用した立ち上げと実行の詳細については、次のビデオ「 [365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806)の概要」を参照Officeしてください。
  
### <a name="exchange-admin-center"></a>Exchange 管理センター

Exchange Online には、使いやすく、社内、オンライン、またはハイブリッド展開の管理用に最適化された、統合管理コンソールがあります。Exchange 管理センター (EAC) では、管理者が Exchange に固有の設定を管理することができます。
  
EAC を使用して Exchange Online を管理する方法の詳細については、「[Exchange Online の Exchange 管理センター](/exchange/exchange-admin-center)」を参照してください。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 用リモート Windows PowerShell

リモート Windows PowerShell を使用することにより、管理者は Exchange Online にアクセスして、EAC では使用不可であったり実用的ではない管理タスクを実行できます。これらは、繰り返しタスクの自動化、カスタム レポートからのデータ抽出、ポリシーのカスタマイズ、既存インフラストラクチャおよびプロセスへの Exchange Online の接続などの機能です。詳細については、「[リモート PowerShell による Exchange への接続](/powershell/exchange/connect-to-exchange-online-powershell)」を参照してください。
  
Exchange Online は Exchange Server 2013 と同じ Windows PowerShell コマンドレットを使用しますが、一部のコマンドとパラメーターは Exchange Online には該当しない機能となるため、使用できません。Exchange Online で使用するコマンドレットの一覧については、「[Exchange Online コマンドレット](/powershell/exchange/exchange-online-powershell)」を参照してください。
  
管理者はリモート Windows PowerShell を使用するのに、Exchange Server 管理ツールまたは移行ツールをインストールする必要はありません。ただし、管理者のコンピューターは Windows PowerShell v3 と WinRM 3.0 を含む Windows Management Framework 3.0 と Windows .NET Framework 4.5 を実行している必要があります。これらのコンポーネントは、Windows 8 または Windows Server 2012 を実行しているコンピューターにはすでにインストールされています。管理者は Windows 7 または Windows Server 2008 R2 を実行しているコンピューター用にこれらのコンポーネントを手動でダウンロードできます。
  
> [!IMPORTANT]
> サービス拒否 (DoS) 攻撃を防止するため、Exchange Online 組織に対して開かれる Windows PowerShell 接続は 3 つに制限されています。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online のセルフ サービス機能

EAC、リモート Windows PowerShell、およびその他のツールを使用して、Exchange Online を管理する場合に使用可能な重要な機能を以下に挙げます。これらのツールにより、その他の多くの設定も制御可能です (本稿で説明します)。
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online でのモバイル デバイスのセキュリティ ポリシー

Exchange Online では、モバイル デバイス用に Exchange Server 2013 と同じ ActiveSync ポリシーがサポートされます。管理者は、EAC またはリモート Windows PowerShell を使用して、特定のユーザーおよびグループ用にこれらのセキュリティ ポリシーを適用またはカスタマイズできます。
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online でのメッセージ追跡

配信レポート機能によるメッセージ追跡については、次のトピック「レポート機能とトラブルシューティング [ツール」で説明します](reporting-features-and-troubleshooting-tools.md)。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online の利用状況レポート

管理者はリモート Windows PowerShell を使用して、組織内のユーザーが Exchange Online サービスをどのように使用するのかに関する情報を取得できます。取得可能な情報を以下に挙げます。
  
- 組織内の各ユーザーのメールボックス サイズを表示する。
    
- メールボックスに設定されたカスタム アクセス許可 (代理人アクセス等) を表示する。
    
- モバイル データ アクセスに関するデータを抽出する (どのユーザーが Exchange ActiveSync 経由で接続しているか、ユーザーはどのデバイスを使用しているか、ユーザーの最終接続日時等)。
    
"get-" で始まるリモート Windows PowerShell コマンドレットは、Exchange Online システムからデータを取得できます。管理者はさらに、分析したりレポートを作成するため、Windows PowerShell から .csv 形式でこの情報をエクスポートできます。
  
Exchange Online で使用する Windows PowerShell コマンドレットの詳細については、「[Exchange Online コマンドレット](/powershell/exchange/exchange-online-powershell)」を参照してください。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online での監査

監査ログ機能については、次のトピック「レポート機能と [トラブルシューティング ツール」で説明します](reporting-features-and-troubleshooting-tools.md)。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online でのサービスおよび製品のアップグレード

Exchange Server の新しいリリースを含め、最新の Exchange テクノロジへの定期的なアップグレードは、Exchange Online のカスタマーにとって有益です。これらのアップグレードは追加料金なしで利用することができ、カスタマーは常に最新の Exchange ソフトウェアを使用できます。
  
Exchange の主要なバージョンが Microsoft からリリースされた後、カスタマーは最長 12 ヶ月までサービスを最新リリースにアップグレードすることができます。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online サービスの説明 [」を参照してください](exchange-online-service-description.md)。
