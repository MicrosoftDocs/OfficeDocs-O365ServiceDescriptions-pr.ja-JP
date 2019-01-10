---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 01/02/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
ms.openlocfilehash: f8a44cdebebafe575f5c22a3a491671f57b05d49
ms.sourcegitcommit: d1d7309e864398e7d029956231cbaee054a2a0cf
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/09/2019
ms.locfileid: "27784869"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection サービスの説明

Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
  
分析ツールを使用して、メッセージの保護のための主な方法は、次のように。
  
- Office 365 ATP のフィルタリングのみのシナリオ ATP は、オンプレミスの Exchange Server 2013 環境、従来の Exchange Server バージョン、その他のオンプレミス SMTP メール ソリューションにクラウドベースのメール保護を提供します。
    
- Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。
    
- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 Advanced Threat Protection (ATP) の可用性

Office 365 エンタープライズ E5、Office 365 の教育 A5、および Microsoft 365 のビジネスでは、分析ツールが含まれます。 
  
> [!NOTE]
> Microsoft 365 ビジネスでクライアントに依存する分析ツールの機能を利用可能な夏の 2018 となります。 
  
ATP は、次の Exchange と Office 365 サブスクリプション プランに追加できます。 
  
- Exchange Online プラン 1
    
- Exchange Online プラン 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Office 365 Advanced Threat Protection を購入するには、「[Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)」を参照してください。
  
各プランの機能を比較するには、「[プランを選ぶ](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」をご覧ください。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の新機能

分析ツールの新機能については、[分析ツールの新機能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)を参照してください。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の要件

ATP は、Microsoft Exchange Server 2013 などのあらゆる SMTP メール転送エージェントと一緒に使用できます。ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Advanced Threat Protection (ATP) の各プランで利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。
  
|**機能**|**ATP スタンドアロン**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|リンク保護  <br/> |はい  <br/> |いいえ  <br/> |
|添付ファイル保護  <br/> |はい  <br/> |いいえ  <br/> |
|スプーフィング インテリジェンス  <br/> |はい  <br/> |いいえ  <br/> |
|検疫  <br/> |はい  <br/> |はい  <br/> |
|高度なフィッシング詐欺対策機能  <br/> |はい  <br/> |いいえ  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Advanced Threat Protection (ATP) の機能

### <a name="safe-links"></a>リンク保護

ATP リンク保護機能は、メッセージ内の悪質なハイパーリンクから予防的にユーザーを保護します。リンクをクリックした後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。
  
### <a name="safe-attachments"></a>添付ファイル保護

添付ファイル保護は、未知のマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、ATP がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。 
  
### <a name="spoof-intelligence"></a>スプーフィング インテリジェンス

スプーフィングのインテリジェンスは、送信者が組織のドメインのいずれか 1 つまたは複数のユーザー アカウントの代理でメールを送信するときを検出します。自分のドメインのなりすましは、すべての送信者を確認し、続行するか、送信者をブロックする送信者を許可するを選択しすることができます。スプーフィングのインテリジェンスは、セキュリティで利用可能な&amp;、スパム対策の設定] ページ上のコンプライアンス センターです。
  
### <a name="quarantine"></a>検疫

スパム、バルク メール、フィッシング詐欺メール、マルウェアを含んだメールとして Office 365 サービスが識別したメッセージや、メール フロー ルールに一致しているために Office 365 サービスが識別したメッセージは、検疫に送ることができます。既定では、Office 365 は、フィッシング詐欺メッセージとマルウェアを含むメッセージを検疫に直接送信します。許可されているユーザーは、検疫に送信された電子メール メッセージを確認、削除、管理できます。
  
### <a name="advanced-anti-phishing-capabilities"></a>高度なフィッシング詐欺対策機能

この機能は、フィッシング詐欺メッセージを検出するために、機械学習モデルを使用します。 
  
