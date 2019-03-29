---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 03/28/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
ms.openlocfilehash: e07691851cdad9bce3f2989e2e6f1665569ec2b5
ms.sourcegitcommit: de7d615d8967b1acc98a077337a0a2939c782481
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/29/2019
ms.locfileid: "30955756"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection サービスの説明

Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
  
メッセージ保護に対して ATP を使用する主な方法は次のとおりです。
  
- Office 365 atp のフィルター処理のみのシナリオでは、オンプレミスの Exchange Server 環境またはその他の社内 SMTP 電子メールソリューションに対して、クラウドベースの電子メール保護を ATP が提供します。
    
- Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。
    
- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 Advanced Threat Protection (ATP) の可用性

ATP は、office 365 Enterprise E5、office 365 エデュケーション A5、および Microsoft 365 Business に含まれています。 
  
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
    
Office 365 Advanced Threat Protection を購入するには、「[Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)」を参照してください。
  
各プランの機能を比較するには、「[プランを選ぶ](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)」をご覧ください。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の新機能

引き続き Office 365 ATP に新機能を追加しています。 次に示すいくつかの新機能の一覧を示します。これは、ATP ポリシーを確認して更新するための呼び出しの一部です。 ATP (または microsoft 365 全般) に出てくる新機能の詳細については、 [microsoft 365 ロードマップ](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)を参照してください。

|機能の更新  |アクションアイテム  |
|---------|---------|
|[Office 365 脅威インテリジェンス](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)(TI) の機能は、ATP プラン2の一部として脅威調査および応答機能になりました。 自動化された[調査と応答](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)、[脅威エクスプローラー](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)の拡張などの新機能は、ロールアウトしています。<br/>現在、組織が atp を持っていない場合、または atp ではなく、atp を使用していない場合は、atp プラン1と atp plan 2 を利用できるように、いくつかのオプションを考慮する必要があります。 詳細については、「 [advanced threat protection (ATP) プラン](#feature-availability-across-advanced-threat-protection-atp-plans)(この記事)」および「 [Office 365 advanced threat protection プランと料金](https://products.office.com/exchange/advance-threat-protection)」の「機能の可用性」を参照してください。 |組織のサブスクリプションを確認し、必要に応じて[アドオンを購入または編集](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)します。  |
|ユーザーが outlook または outlook Web アプリケーション (OWA) を使用している場合、 [ATP の安全なリンク](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)は元の url をレンダリングし、書き換えられた url は表示しません。 (このネイティブリンクレンダリングを呼び出しています)。<br>組織がネイティブリンクレンダリングを使用できる場合、この機能は Outlook 365 (クイック実行)、OWA、および Windows および Mac OS で機能します。 |なし         |
|[Office 365 ATP の警告ページ](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages)には、新しい配色、詳細、および警告と推奨事項があるにもかかわらずサイトを継続する機能があります。 |なし         |
|[ATP の安全なリンク](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護は、office Online (Word online、Excel online、PowerPoint online、および OneNote online) および office 365 ProPlus on Mac の url に適用されるように拡張されています。   |[ATP の安全なリンクポリシーを確認および編集する](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|セキュリティ&amp; /コンプライアンスセンターの検疫機能は、 [SharePoint Online、OneDrive for business、Microsoft Teams 用の ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)に拡張されています。 |[ATP の安全な添付ファイルポリシーの確認と編集](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|[ATP の安全なリンク](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護は、組織内のユーザー間で送信される電子メールに適用されるように拡張されています。 |[ATP の安全なリンクポリシーを確認および編集する](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|[ATP の安全なリンク](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護は、電子メールの url、Word、Excel、PowerPoint、Visio などの office 365 ProPlus ドキュメント、iOS および Android デバイス上の office アプリに適用されるように拡張されています。  |[Office の先進認証](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016)を使用していることを確認する |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の要件

ATP は、Microsoft Exchange Server などの任意の SMTP メール転送エージェントで使用できます。 ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Advanced Threat Protection (ATP) の各プランで利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。
  
|**機能**|**ATP プラン1**<br>(旧称 ATP スタンドアロン)|**ATP プラン2**<br>(以前の脅威インテリジェンス <br>スタンドアロン | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *構成、保護、および検出* | 
|添付ファイル保護 |あり|はい |はい|
|リンク保護 |あり|はい |はい | 
|フィッシング対策ポリシー |あり |はい |はい |
|SharePoint、OneDrive、Microsoft Teams 用の ATP |あり |はい |はい|
|Teams での安全なリンク |あり|はい |はい |
|リアルタイムレポート |あり |はい |はい|
|*自動化、調査、修復、教育* |
|脅威トラッカー |いいえ |あり |はい |
|エクスプローラー (高度な脅威調査) |いいえ |あり |はい |
|自動調査および対応  |いいえ |あり |はい |
|アタックシミュレータ |いいえ |あり |はい |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Advanced Threat Protection (ATP) の機能

### <a name="safe-attachments"></a>添付ファイル保護

[ATP の安全な添付ファイル](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)は、不明なマルウェアやウイルスから保護され、メッセージングシステムを保護するためのゼロ日の保護を提供します。 既知のウイルス/マルウェア署名がないすべてのメッセージと添付ファイルは、ATP がさまざまな機械学習および分析テクノロジを使用して悪意を検出する特別な環境にルーティングされます。 不審な動作が検出されないと、メッセージが解放されてメールボックスに配信されます。 

### <a name="safe-links"></a>リンク保護

[ATP の安全なリンク](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪意のある url からユーザーを予防的に保護します。 リンクをクリックした後も保護は毎回継続し、悪意のあるリンクは動的にブロックされ、適切なリンクにはアクセスできます。

### <a name="anti-phishing-policies"></a>フィッシング対策ポリシー

[ATP のフィッシング対策](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)は、メッセージがフィッシングである可能性があることを示すインジケーターの受信メッセージをチェックします。 ユーザーが ATP ポリシー (安全な添付ファイル、安全なリンク、またはフィッシング対策) でカバーされている場合、受信メッセージは、メッセージを分析し、構成されたポリシーに基づいて適切なアクションを実行する複数のマシン学習モデルによって評価されます。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、Microsoft Teams 用の ATP は、](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)チームサイトやドキュメントライブラリで悪意のあるものとして識別されたファイルを検出してブロックするのに便利です。

### <a name="real-time-reports"></a>リアルタイムレポート

Office 365 security & コンプライアンスセンターで利用可能な監視機能には[リアルタイムのレポートと洞察](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)が含まれており、セキュリティおよびコンプライアンスの管理者が、セキュリティ攻撃などの優先度の高い問題に焦点を当てることができるようにしたり、疑わしいアクティビティの増加。 スマートレポートと分析には、問題の領域を強調するだけでなく、データを表示して探索したり、簡単なアクションを実行したりするための推奨事項やリンクが含まれています。 
  
### <a name="threat-trackers"></a>脅威トラッカー

[脅威のトラッカー](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)は、組織に影響を与える可能性がある cybersecurity の問題に関するインテリジェンスを承認されたユーザーに提供する情報ウィジェットとビューです。

### <a name="explorer"></a>Explorer

[エクスプローラー](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)(脅威エクスプローラーとも呼ばれます) は、承認されたユーザーが最近の脅威を特定して分析できるようにするリアルタイムレポートです。 既定では、このレポートには過去7日間のデータが表示されます。ただし、過去30日間のデータを表示するようにビューを変更することはできます。 

### <a name="attack-simulator"></a>アタックシミュレータ
  
[アタックシミュレータ](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)は、承認されたユーザーが組織内で現実的な攻撃シナリオを実行できるようにします。 表示名のスピアーフィッシング攻撃、パスワードスプレー攻撃、ブルートフォースパスワード攻撃など、さまざまな種類の攻撃が利用可能です。