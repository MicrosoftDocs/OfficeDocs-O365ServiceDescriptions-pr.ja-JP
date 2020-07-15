---
title: Exchange Online のセットアップと管理
ms.author: office365servicedesc
author: pamelaar
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
description: この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を常に最新の状態にし、最新の状態に保つために使用できる管理制御とサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133002"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online のセットアップと管理

この記事では、Exchange Online の設定をカスタマイズし、組織の Exchange Online 環境を常に最新の状態にし、最新の状態に保つために使用できる管理制御とサポートについて説明します。 この内容には、セルフ サービスの管理ツールおよび組織が利用可能な機能、Microsoft の管理責任とパフォーマンス コミットメント、そしてサービスおよび製品のアップグレードに関する情報が含まれます。
  
## <a name="self-service-administration-tools"></a>セルフ サービス管理ツール

Microsoft では、すべての Exchange Online データセンターを直接制御し、システム全体のパフォーマンスを管理していますが、ユーザーの総合的な機能を提供するために、組み合わされた要素の一部のみを制御することができます。 組織自体は、データセンター、お客様のワイドエリアネットワーク (WAN)、お客様のローカルエリアネットワーク (Lan) へのネットワーク接続を担当します。 さらに、ユーザーデバイスとその構成を担当します。また、ユーザーが機能にアクセスする必要がある限り、これらの機能を管理する機能に限定するのではなく、必要な機能に対して、ユーザーごとに必要なライセンスを維持する責任もあります。
  
このため Exchange Online は、次に説明するツールをカスタマーの管理者に提供し、メッセージングに関するさまざまなタスクを管理できるようにします。
  
- [Microsoft Office 365 ポータル](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 管理センター](#microsoft-365-admin-center)
    
- [Exchange 管理センター](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 用リモート Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 ポータル

Microsoft Office 365 ポータル ([https://portal.office.com](https://portal.office.com)) は、管理者やパートナーが Office 365 サービスを購入および管理する Web サイトです。ユーザーは、このサイトで Office 365 コラボレーション ツールにアクセスして使用することができます。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 管理センター

Microsoft 365 管理センターは、各企業のサービス管理者が、購読している各 Microsoft サービスのユーザーアカウントと設定を管理できる web ポータルです。 Microsoft 365 管理センターでは、管理者は Exchange 管理センター (EAC) へのリンクをたどって、Exchange Online に固有の設定を管理できます。 Microsoft 365 管理センターを使用した取得と実行の詳細については、「 [Office 365 Enterprise の概要](https://go.microsoft.com/fwlink/p/?LinkId=271806)」を参照してください。
  
### <a name="exchange-admin-center"></a>Exchange 管理センター

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
EAC を使用して Exchange Online を管理する方法の詳細については、「[Exchange Online の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=271807)」を参照してください。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 用リモート Windows PowerShell

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> サービス拒否 (DoS) 攻撃を防止するため、Exchange Online 組織に対して開かれる Windows PowerShell 接続は 3 つに制限されています。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online のセルフ サービス機能

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online でのモバイル デバイスのセキュリティ ポリシー

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online でのメッセージ追跡

配信レポート機能によるメッセージ追跡については、「[レポート機能とトラブルシューティングツール](reporting-features-and-troubleshooting-tools.md)」を参照してください。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online の利用状況レポート

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- 組織内の各ユーザーのメールボックス サイズを表示する。
    
- メールボックスに設定されたカスタム アクセス許可 (代理人アクセス等) を表示する。
    
- モバイル データ アクセスに関するデータを抽出する (どのユーザーが Exchange ActiveSync 経由で接続しているか、ユーザーはどのデバイスを使用しているか、ユーザーの最終接続日時等)。
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Exchange Online で使用する Windows PowerShell コマンドレットの詳細については、「[Exchange Online コマンドレット](https://go.microsoft.com/fwlink/p/?LinkId=271808)」を参照してください。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online での監査

監査ログ機能については、以下のトピック「[レポート機能とトラブルシューティングツール](reporting-features-and-troubleshooting-tools.md)」を参照してください。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online でのサービスおよび製品のアップグレード

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Exchange の主要なバージョンが Microsoft からリリースされた後、カスタマーは最長 12 ヶ月までサービスを最新リリースにアップグレードすることができます。
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  