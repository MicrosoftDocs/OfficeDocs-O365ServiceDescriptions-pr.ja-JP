---
title: Exchange Online のセットアップと管理
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: このセクションでは、管理コントロールとは、Exchange Online の設定をカスタマイズしを実行して、組織の Exchange のオンライン環境を保持する利用可能な現在のサポートについて説明します。セルフ サービス管理ツールとしている組織に利用可能な機能に関する情報が含まれていますMicrosoft を管理する責任とコミットメントのパフォーマンスです。およびサービスと製品のアップグレードします。
ms.openlocfilehash: 6b7bb1d68e6d676c39e9ebb254305b2799cc0931
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036221"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online のセットアップと管理

このセクションでは、管理コントロールとは、Exchange Online の設定をカスタマイズしを実行して、組織の Exchange のオンライン環境を保持する利用可能な現在のサポートについて説明します。セルフ サービス管理ツールとしている組織に利用可能な機能に関する情報が含まれていますMicrosoft を管理する責任とコミットメントのパフォーマンスです。およびサービスと製品のアップグレードします。
  
## <a name="self-service-administration-tools"></a>セルフ サービス管理ツール

Microsoft はすべての Exchange Online データ センターを直接制御し、全体的なシステム パフォーマンスの責任を負います。しかし、Microsoft が管理できる要素は、Office 365 ユーザーの全体的なエクスペリエンスを構成する要素の一部でしかありません。データ センター、カスタマーのワイド エリア ネットワーク (WAN)、およびカスタマーのローカル エリア ネットワーク (LAN) へのネットワーク接続は、組織自体が責任を負います。さらに、ユーザーのデバイスと構成の責任を担います。また、任意の必要な機能 (たとえば、ユーザーが対象機能を利用する場合にはその機能を管理する機能など) に関するユーザーごとに必要なライセンスの保守にも責任があります。
  
このため Exchange Online は、次に説明するツールをカスタマーの管理者に提供し、メッセージングに関するさまざまなタスクを管理できるようにします。
  
- [Microsoft Office 365 ポータル](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft Office 365 管理センター](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [Exchange 管理センター](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 用リモート Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 ポータル
<a name="BKMK_MicrosoftOnlineServicesPortal"> </a>

Microsoft Office 365 ポータル ([https://portal.office.com](https://portal.office.com)) は、管理者やパートナーが Office 365 サービスを購入および管理する Web サイトです。ユーザーは、このサイトで Office 365 コラボレーション ツールにアクセスして使用することができます。
  
### <a name="microsoft-office-365-admin-center"></a>Microsoft Office 365 管理センター
<a name="BKMK_Office365admincenterl"> </a>

Microsoft Office 365 管理センターは Web ポータルです。各会社のサービス管理者はこのポータルからユーザー アカウントやサブスクライブする Office 365 の各サービスの設定を管理することができます。Office 365 管理センター内からは管理者が Exchange 管理センター (EAC) へのリンクをたどることができ、Exchange 管理センターで Exchange Online に固有な設定を管理することができます。Office 365 管理センターを使用した稼働の詳細については、次のビデオを参照してください。[ビデオ: あらゆる規模の法人向けプランの Office 365 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=271806)。
  
### <a name="exchange-admin-center"></a>Exchange 管理センター
<a name="BKMK_ExchangeAdministrationCenter"> </a>

Exchange Online には、使いやすく、社内、オンライン、またはハイブリッド展開の管理用に最適化された、統合管理コンソールがあります。Exchange 管理センター (EAC) では、管理者が Exchange に固有の設定を管理することができます。
  
EAC を使用して Exchange Online を管理する方法の詳細については、「[Exchange Online の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=271807)」を参照してください。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 用リモート Windows PowerShell
<a name="BKMK_RemoteWindowsPowerShell"> </a>

リモート Windows PowerShell を使用することにより、管理者は Exchange Online にアクセスして、EAC では使用不可であったり実用的ではない管理タスクを実行できます。これらは、繰り返しタスクの自動化、カスタム レポートからのデータ抽出、ポリシーのカスタマイズ、既存インフラストラクチャおよびプロセスへの Exchange Online の接続などの機能です。詳細については、「[リモート PowerShell による Exchange への接続](https://go.microsoft.com/fwlink/p/?LinkId=308994)」を参照してください。
  
Exchange Online は Exchange Server 2013 と同じ Windows PowerShell コマンドレットを使用しますが、一部のコマンドとパラメーターは Exchange Online には該当しない機能となるため、使用できません。Exchange Online で使用するコマンドレットの一覧については、「[Exchange Online コマンドレット](https://go.microsoft.com/fwlink/p/?LinkId=271808)」を参照してください。
  
管理者はリモート Windows PowerShell を使用するのに、Exchange Server 管理ツールまたは移行ツールをインストールする必要はありません。ただし、管理者のコンピューターは Windows PowerShell v3 と WinRM 3.0 を含む Windows Management Framework 3.0 と Windows .NET Framework 4.5 を実行している必要があります。これらのコンポーネントは、Windows 8 または Windows Server 2012 を実行しているコンピューターにはすでにインストールされています。管理者は Windows 7 または Windows Server 2008 R2 を実行しているコンピューター用にこれらのコンポーネントを手動でダウンロードできます。
  
> [!IMPORTANT]
> サービス拒否 (DoS) 攻撃を防止するため、Exchange Online 組織に対して開かれる Windows PowerShell 接続は 3 つに制限されています。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online のセルフ サービス機能

EAC、リモート Windows PowerShell、およびその他のツールを使用して、Exchange Online を管理する場合に使用可能な重要な機能を以下に挙げます。これらのツールにより、その他の多くの設定も制御可能です (本稿で説明します)。
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online でのモバイル デバイスのセキュリティ ポリシー

Exchange Online では、モバイル デバイス用に Exchange Server 2013 と同じ ActiveSync ポリシーがサポートされます。管理者は、EAC またはリモート Windows PowerShell を使用して、特定のユーザーおよびグループ用にこれらのセキュリティ ポリシーを適用またはカスタマイズできます。
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online でのメッセージ追跡

配信レポート機能によるメッセージ追跡はトピック「Reporting Features and Troubleshooting Tools」で説明します。Reporting Features and Troubleshooting Tools.
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online の利用状況レポート

管理者はリモート Windows PowerShell を使用して、組織内のユーザーが Exchange Online サービスをどのように使用するのかに関する情報を取得できます。取得可能な情報を以下に挙げます。
  
- 組織内の各ユーザーのメールボックス サイズを表示する。
    
- メールボックスに設定されたカスタム アクセス許可 (代理人アクセス等) を表示する。
    
- モバイル データ アクセスに関するデータを抽出する (どのユーザーが Exchange ActiveSync 経由で接続しているか、ユーザーはどのデバイスを使用しているか、ユーザーの最終接続日時等)。
    
"get-" で始まるリモート Windows PowerShell コマンドレットは、Exchange Online システムからデータを取得できます。管理者はさらに、分析したりレポートを作成するため、Windows PowerShell から .csv 形式でこの情報をエクスポートできます。
  
Exchange Online で使用する Windows PowerShell コマンドレットの詳細については、「[Exchange Online コマンドレット](https://go.microsoft.com/fwlink/p/?LinkId=271808)」を参照してください。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online での監査

監査ログ機能はトピック「Reporting Features and Troubleshooting Tools」で説明します。Reporting Features and Troubleshooting Tools.
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online でのサービスおよび製品のアップグレード

Exchange Server の新しいリリースを含め、最新の Exchange テクノロジへの定期的なアップグレードは、Exchange Online のカスタマーにとって有益です。これらのアップグレードは追加料金なしで利用することができ、カスタマーは常に最新の Exchange ソフトウェアを使用できます。
  
Exchange の主要なバージョンが Microsoft からリリースされた後、カスタマーは最長 12 ヶ月までサービスを最新リリースにアップグレードすることができます。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

