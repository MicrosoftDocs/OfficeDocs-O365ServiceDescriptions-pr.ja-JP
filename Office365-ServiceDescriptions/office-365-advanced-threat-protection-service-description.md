---
title: Office 365 Advanced Threat Protection サービスの説明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884198"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection サービスの説明

Microsoft Office 365 Advanced Threat Protection (ATP) は、クラウドベースの電子メール フィルタリング サービスであり、堅牢なゼロデイ保護を提供して未知のマルウェアやウイルスから組織を保護するのに役立ち、リアルタイムで有害なリンクから組織を保護する機能が含まれています。ATP には多機能なレポート機能と URL トレース機能があるので、管理者は組織内で発生する攻撃の種類を見極めることができます。
  
分析ツールを使用して、メッセージの保護のための主な方法は、次のように。
  
- Office 365 の ATP のフィルタ リング専用シナリオでは、ATP は、オンプレミスの Exchange Server 環境、またはその他の設置型 SMTP 電子メール ソリューションをクラウド ベースの電子メールの保護を提供します。
    
- Office 365 ATP は Exchange Online クラウド ホスト型メールボックスを保護するために有効にすることができます。Exchange Online の詳細については、「[Exchange Online サービスの説明](exchange-online-service-description/exchange-online-service-description.md)」を参照してください。
    
- ハイブリッド展開でオンプレミスのメールボックスとクラウドのメールボックスが混在している場合は、受信電子メール フィルタリングに Exchange Online Protection を併用するように ATP を構成し、メッセージング環境の保護やメール ルーティングの制御が行えます。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 Advanced Threat Protection (ATP) の可用性

Office 365 エンタープライズ E5、Office 365 の教育 A5、および Microsoft 365 のビジネスでは、分析ツールが含まれます。 
  
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

2019 の 2 月に開始し、今後数か月にロールアウト、ATP ように脅威インテリジェンス機能が追加されています。さらに、組織が現在 ATP を持たない場合がありますこれを考慮すると、新しいオプション計画 1 の ATP ATP 計画 2 など。詳細については、 [Office 365 の高度な脅威保護の計画と価格設定](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content)と[高度な脅威保護 (ATP) の計画で使用可能な機能](#feature-availability-across-advanced-threat-protection-atp-plans)を参照してください。

分析ツールの新機能については、[分析ツールの新機能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)を参照してください。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 Advanced Threat Protection (ATP) の要件

ATP は、Microsoft Exchange Server 2013 などのあらゆる SMTP メール転送エージェントと一緒に使用できます。ATP でサポートされているオペレーティング システム、Web ブラウザー、言語については、「[Exchange Online Protection の Exchange 管理センター](https://go.microsoft.com/fwlink/p/?LinkId=282381)」の「サポートされているブラウザー」と「サポートされている言語」をご覧ください。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Advanced Threat Protection (ATP) の各プランで利用できる機能

各機能を以下に列挙します。Exchange Online という記述は、主に、Office 365 Enterprise サービス ファミリを指しています。
  
|**機能**|**ATP プラン 1**<br>(以前は ATP スタンドアロン)|**ATP プラン 2**<br>(以前脅威インテリジェンス <br>スタンドアロン) | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *構成、保護、および検出* | 
|添付ファイル保護 |はい|はい |はい|
|リンク保護 |はい|はい |はい | 
|フィッシング詐欺対策ポリシー |はい |はい |はい |
|SharePoint、OneDrive、およびマイクロソフトのチームの分析ツール |はい |はい |はい|
|チームでの安全なリンク |はい|はい |はい |
|リアルタイム レポート |はい |はい |はい|
|*オートメーション、調査、修復、および教育* |
|トラッカーの脅威 |いいえ |はい |はい |
|(脅威の調査を高度な) エクスプ ローラー |いいえ |はい |はい |
|自動化された調査および応答  |いいえ |はい |はい |
|攻撃シミュレータ |いいえ |はい |はい |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Advanced Threat Protection (ATP) の機能

### <a name="safe-attachments"></a>添付ファイル保護

[ATP の安全な添付ファイル](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)は不明なマルウェアやウイルスから保護し、メッセージング システムを保護するゼロデイ保護を提供します。すべてのメッセージと既知のウイルス/マルウェアの署名のない添付ファイルは、ATP がさまざまなマシンの学習と分析手法を使用して悪意のある意図を検出するために特別な環境にルーティングされます。不審なアクティビティが検出されない場合、メッセージがメールボックスへの配信に解放されます。 

### <a name="safe-links"></a>リンク保護

[ATP の安全なリンク](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)機能は、メッセージまたは Office ドキュメント内の悪意のある Url から、ユーザーをプロアクティブに保護します。保護の適切なリンクにアクセスできるときに、悪意のあるリンクは動的にブロックされているため、リンクをクリックするたびにままです。

### <a name="anti-phishing-policies"></a>フィッシング詐欺対策ポリシー

[ATP フィッシング詐欺対策](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)は、インジケーターには、メッセージはフィッシング詐欺である可能性があります受信メッセージをチェックします。については、ユーザーと ATP のポリシー (安全な添付ファイル、安全なリンクまたはフィッシング詐欺対策)、受信メッセージを評価して、メッセージを分析するモデルを学習する複数のコンピューターで適切なアクションを実行すると、構成済みのポリシーに基づきます。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint、OneDrive、Microsoft Teams 用の ATP

[SharePoint、OneDrive、およびマイクロソフトのチームの分析ツール](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)は、検出し、チーム サイトおよびドキュメント ライブラリで悪意あるコードとして指定されているファイルをブロックすることができます。

### <a name="real-time-reports"></a>リアルタイム レポート

監視機能は、Office 365 のセキュリティで利用可能な & コンプライアンス センターには、[リアルタイムのレポートと情報](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)セキュリティ攻撃の優先度の高い課題に注力する、セキュリティとコンプライアンスの管理者を有効にするか、不審なアクティビティが増加します。問題領域を強調表示するだけでなく洗練されたレポートと情報の推奨事項と表示し、データを表示してもクイック処理へのリンクを含めます。 
  
### <a name="threat-trackers"></a>トラッカーの脅威

[トラッカーの脅威](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)は、ウィジェットが役に立つと、組織に影響を与える可能性があります cybersecurity の問題に関する情報と権限を持つユーザーを提供するビューです。

### <a name="explorer"></a>エクスプ ローラー

[エクスプ ローラー](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)(脅威のエクスプ ローラーとも呼ばれます) ことにより権限のあるユーザーを識別し、最新の脅威を分析するリアルタイムのレポートです。既定では、データの表示、過去 7 日間です。ただし、過去 30 日間のデータを表示するビューを変更できます。 

### <a name="attack-simulator"></a>攻撃シミュレータ
  
[攻撃のシミュレータ](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)では、組織内で現実的な攻撃のシナリオを実行する権限を持つユーザーを使用できます。攻撃のいくつかのさまざまな種類がある、表示名のスピアー フィッシング攻撃、パスワード スプレーの攻撃、ブルート フォース パスワード攻撃などです。