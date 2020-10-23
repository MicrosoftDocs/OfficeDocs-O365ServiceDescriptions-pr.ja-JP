---
title: Exchange Online サービスの説明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 7a83da3c-3b6d-4f86-ad4d-6104707cd0ec
description: Exchange Online を含むサブスクリプションの機能の比較については、こちらを参照してください。 その場合は、Exchange Online サービスの説明記事をご覧ください。 システム要件およびストレージと受信者の要件についても説明しています。
ms.openlocfilehash: ad4107a146ea4c4042cd9c1551110c7ec4ca0632
ms.sourcegitcommit: 9610e71d9e64a2bb0ffdfed8cc7ad51f8829905a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/22/2020
ms.locfileid: "48661285"
---
# <a name="exchange-online-service-description"></a>Exchange Online サービスの説明

Exchange Online を含むサブスクリプションの機能の比較については、こちらを参照してください。 その場合は、Exchange Online サービスの説明記事をご覧ください。 システム要件およびストレージと受信者の要件についても説明しています。
  
> [!NOTE]
> タスクに関してサポートが必要な場合、または問題のトラブルシューティングを行う場合は、次のリソースが役に立ちます。 <br/>
[メールの](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) 作成と送信に関するヘルプを提供します。 <br/> 
[電子メールと予定表を管理する](https://docs.microsoft.com/office365/admin/email/email)<br/> 
[Microsoft サポート/回復アシスタントについて](https://diagnostics.office.com/)<br/> 
[Exchange Online のメール配信不能レポート](https://docs.microsoft.com/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)<br/> 
[Exchange Online のヘルプ](https://docs.microsoft.com/exchange/exchange-online)
  
Microsoft Exchange Online は、Microsoft Exchange Server の機能をクラウドベースのサービスとして提供するホスト型のメッセージング ソリューションです。ユーザーは PC、Web、およびモバイル デバイスから電子メール、カレンダー、連絡先、タスクにアクセスできます。Active Directory と完全に統合するので、管理者がグループ ポリシーを他の管理ツールと共に使用し、環境全体にわたって Exchange Online 機能を管理することができます。
  
Exchange Online をサブスクライブする組織は、ユーザーに提供するメッセージング サービスを管理できますが、社内サーバー ソフトウェアを運用するときのような負荷はありません。 このドキュメントで説明する Exchange Online のホスト型のプランでは、電子メールは、複数のカスタマーを同時にサポートするサーバー上でホストされます。 これらのサーバーは、Microsoft データセンターに格納されており、企業ネットワーク内から、またはインターネット経由でさまざまなデバイスのユーザーがアクセスできます。
  
プラン間で機能を比較するには、「 [エンタープライズをサポートするための強力なツール](https://products.office.com/business/compare-more-office-365-for-business-plans)」を参照してください。 Office 365 Germany のプランを比較するには、[Office 365 Germany のサブスクリプション プラン](https://go.microsoft.com/fwlink/?linkid=839016)をご覧ください。
  
> [!TIP]
> Microsoft サービスの説明では、ページをエクスポート、保存、および印刷することができます。 [コンテンツ検索の結果をエクスポート](https://docs.microsoft.com/office365/securitycompliance/export-search-results)する方法について説明します。 
  
## <a name="whats-new-in-exchange-admin-center"></a>Exchange 管理センターの新機能

Exchange 管理センターの新機能の詳細については、「 [exchange 管理センターの新](https://docs.microsoft.com/exchange/whats-new)機能」を参照してください。
  
## <a name="plans-for-exchange-online"></a>Exchange Online の計画

Microsoft 365 は、組織のニーズを満たすように、さまざまなプランで利用できます。 スタンドアロンプランのオプションや、あるプランから別のプランへの移行に関する情報など、さまざまなプランの詳細については、「 [Office 365 プランのオプション](../office-365-platform-service-description/office-365-plan-options.md)」を参照してください。
  
Exchange Online サービスにアクセスする各ユーザーは、サブスクリプション プランに割り当てられる必要があります。ユーザーのサブスクリプションごとにメールボックスがあります。これらのメールボックスのフォルダーおよびメッセージは、Microsoft データ センターの Exchange Server が実行されているコンピューター上に格納されます。
  
ユーザー サブスクリプションは、会議室および共有メールボックスには必要ありません。これらの特殊な種類のメールボックスには、ログイン資格情報がありません。これらの特殊な種類のメールボックスは、ライセンスを持ち、適切なアクセス許可があるユーザーが委任によって管理とアクセスを行います。

**Microsoft 365 F1 ユーザーメールボックスの使用権限** <br/>
Microsoft 365 F1 には、Exchange メールボックスに対する権限は含まれていません。 完全な Teams 環境を有効にするために、M365 F1 ライセンスには Exchange Online K1 service プランが有効になっている場合があります。 Exchange Online K1 サービスプランによってユーザーのメールボックスがプロビジョニングされますが、M365 F1 ユーザーにはメールボックスを使用する権利がありません。 [これらの手順](https://docs.microsoft.com/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app)を使用して Outlook on the web を無効にして、他の方法を使用して Exchange メールボックスにアクセスしないようにユーザーに依頼することをお勧めします。
  
## <a name="system-requirements-for-exchange-online"></a>Exchange Online のシステム要件

システム要件として、ビジネス、教育、および行政機関で使用可能な月単位のサブスクリプションベースのサービスについては、「 [Microsoft 365 と Office のリソース](https://products.office.com/office-system-requirements/#Office365forBEG)」を参照してください。
  
## <a name="storage-and-recipient-limits-for-exchange-online"></a>Exchange Online のストレージと受信者の制限

Exchange Online サブスクリプションプランで使用可能なストレージと受信者の制限については、「 [Exchange online の制限](exchange-online-limits.md)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

現在、お客様の組織が Office 365 Small Business、Office 365 Small Business Premium、または Office 365 中規模企業へのサブスクリプションを持っている場合は、Microsoft 365 管理センターのメッセージセンターにアクセスするか、プロバイダーに連絡して、新しい Microsoft の365アプリのプランがどのように影響するかの詳細を確認してください。 新しい Microsoft 365 アプリプランファミリーの詳細については、「 [中小企業向けの新しいプラン](https://blogs.microsoft.com/blog/2014/10/02/new-office-365-plans-small-mid-sized-businesses-available-today)」を参照してください。

Microsoft 365 Business Premium で利用できる機能については、「 [microsoft 365 Business premium サービスの説明](../microsoft-365-service-descriptions/microsoft-365-business-service-description.md)」を参照してください。<br/><br/>
  
| 機能 | Exchange Server 2013 | Exchange Server 2016 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](planning-and-deployment.md)**|||||||||
|サポートされているハイブリッド展開|はい|はい|Yes<sup>16</sup>|Yes<sup>16</sup>|はい|はい|はい|Yes<sup>16</sup>|
|サポートされている IMAP 移行|はい|はい|はい|はい|はい|はい|はい|はい|
|カット オーバー移行のサポート|はい|はい|はい|はい|はい|はい|はい|はい|
|サポートされている段階的な移行|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|**[アクセス許可](permissions.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|役割に基づくアクセス許可|はい|はい|はい|はい|はい|はい|はい|いいえ|
|役割グループ|はい|はい|はい|はい|はい|はい|はい|いいえ|
|役割の割り当てポリシー|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[メッセージ ポリシーとコンプライアンス](message-policy-and-compliance.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Exchange Online ベースのメールボックスのアーカイブ| いいえ|いいえ|はい|はい (<sup>9</sup> )|はい (<sup>9</sup> )|はい (<sup>9</sup> )|はい (<sup>9</sup> )|いいえ|
|社内メールボックスのクラウドベースのアーカイブ|はい <sup>1</sup>|はい<sup>1</sup>|いいえ|いいえ|はい|はい|はい|いいえ|
|Messaging Records Management(MRM) |はい|はい|はい|はい|はい|はい|はい|はい|
|手動のアイテム保持ポリシー、ラベル、タグ |いいえ|いいえ|いいえ|いいえ|はい|はい|はい|はい|
|保存中のデータの暗号化 (BitLocker)|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい|はい|はい|はい|はい|はい|
|Azure Information Protection を使用した IRM|いいえ|はい|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい|はい|いいえ<sup>2</sup>|
|Windows Server AD RMS を使用した IRM|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|
|Office 365 Message Encryption|はい<sup>13</sup>|はい<sup>13</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい|はい|いいえ<sup>2</sup>|
|顧客キー<sup>22</sup>|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|はい|いいえ||
|S/MIME|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい|はい|はい|はい|はい|はい||
|インプレース保持と訴訟ホールド|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|インプレース電子情報開示 (eDiscovery)|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|あり|
|Transport rules|はい <sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|はい<sup>4</sup>|
|データ損失防止|はい<sup>5、14</sup>|はい<sup>5、14</sup>|いいえ|いいえ|いいえ|はい|はい|いいえ|
|ジャーナル|はい|はい|はい|はい|はい|はい|はい|はい|
|**[スパム対策とマルウェア対策の保護](anti-spam-and-anti-malware-protection.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|組み込みのスパム対策保護|はい <sup>6</sup>|はい <sup>6</sup>|はい|はい|はい|はい|はい|はい|
|Customize anti-spam policies|はい (ただし、PowerShell 経由のみ)|はい (ただし、PowerShell 経由のみ)|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|組み込みのマルウェア対策保護|はい <sup>8</sup>|はい <sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|
|Customize anti-malware policies|はい|はい|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|検疫 - 管理者による管理|はい|はい|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|検疫 - エンドユーザーによる自己管理|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Advanced Threat Protection|いいえ|はい|いいえ|いいえ|いいえ|いいえ|はい|いいえ|
|**[メール フロー](mail-flow.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|送信メールのカスタムルーティング|はい|はい|はい|はい|はい|はい|はい|はい|
|Secure messaging with a trusted partner|はい|はい|はい|はい|はい|はい|はい|はい|
|Conditional mail routing|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|着信セーフリストへのパートナーの追加|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|ハイブリッド電子メールルーティング|はい|はい|Yes<sup>16</sup>|Yes<sup>16</sup>|はい|はい|はい|はい|
|**[受信者](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|容量のアラート|はい|はい|はい|はい|はい|はい|はい|はい|
|クラッター機能|はい|いいえ|はい|はい|はい|はい|はい|はい|
|メール ヒント|はい|はい|はい|はい|はい|はい|はい|はい|
|代理人アクセス|はい|はい|はい|はい|はい|はい|はい|<sup>24</sup>|
|受信トレイのルール|はい|はい|はい|はい|はい|はい|はい|いいえ|
|接続されているアカウント|はい|はい|はい|はい|Yes<sup>17</sup>|Yes<sup>17</sup>|Yes<sup>17</sup>|Yes<sup>17</sup>|
|非アクティブなメールボックス|いいえ|いいえ|いいえ<sup>9</sup>|いいえ<sup>9</sup>|いいえ<sup>9</sup>|はい|はい|いいえ <sup>9</sup>|
|オフライン アドレス帳|はい|はい|はい|はい|はい|はい|はい|はい|
|アドレス帳ポリシー|はい|はい|はい|はい|はい|はい|はい|はい|
|階層型アドレス帳|はい|はい|はい|はい|はい|はい|はい|いいえ|
|アドレス一覧とグローバルアドレス一覧|はい|はい|はい|はい|はい<sup>18</sup>|はい<sup>18</sup>|はい<sup>18</sup>|はい<sup>18</sup>|
|Microsoft 365 グループ|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|配布グループ|はい|はい|はい|はい|はい|はい|はい|はい|
|外部連絡先 （グローバル）|はい|はい|はい|はい|はい|はい|はい|はい|
|ユニバーサル連絡先カード|はい|はい|はい|はい|はい|はい|はい|はい|
|ソーシャルネットワークを使用した連絡先リンク|はい|はい|はい|はい|はい|はい|はい|はい|
|リソース メールボックス|はい|はい|はい|はい|はい|はい|はい|はい|
|会議室の管理|はい|はい|はい|はい|はい|はい|はい|はい|
|不在時の返信|はい|はい|はい|はい|はい|はい|はい|はい|
|予定表の共有|はい|はい|はい|はい|はい|はい|はい|はい|
|**[レポート機能とトラブルシューティング ツール](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft 365 管理センターのレポート|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Excel レポート作成ブック|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Web サービスレポート|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Message trace|いいえ|はい|はい|はい|はい|はい|はい|はい|
|監査レポート|はい|はい|はい|はい|はい|はい|はい|はい <sup>3</sup>|
|ユニファイド メッセージングのレポート|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|**[共有とコラボレーション](sharing-and-collaboration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|フェデレーションの共有 (予定表の公開を含む)|はい|はい|はい|はい|はい|はい|はい|はい|
|サイト メールボックス|はい (<sup>10</sup> )|はい (<sup>10</sup> )|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|
|パブリック フォルダー|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[クライアントとモバイル デバイス](clients-and-mobile-devices.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Outlook for Windows <sup>21</sup>|はい|はい|はい|はい|はい|はい|はい| いいえ|
|Outlook on the web<sup>21</sup>|はい|はい|はい|はい|はい|はい|はい|はい|
|Outlook for Mac<sup>21</sup>|はい|はい|はい|はい|はい|はい|はい| いいえ|
|Outlook for iOS and Android<sup>21</sup>|はい (<sup>25</sup> )|はい (<sup>25</sup> )|はい|はい|はい|はい|はい|はい|
|Exchange ActiveSync|はい|はい|はい|はい|はい|はい|はい|はい|
|Microsoft 365 の基本的なモビリティとセキュリティ|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|POP と IMAP|はい|はい|はい|はい|はい|はい|はい|はい <sup>12</sup>|
|SMTP|はい|はい|はい|はい|はい|はい|はい|はい|
|EWS アプリケーションのサポート|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[音声メッセージ サービス](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|ボイスメール<sup>23</sup>|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|ボイスメールとサードパーティ<sup>製 FAX の</sup>統合|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|サードパーティボイスメールの相互運用性<sup>23</sup>|はい|はい|はい|はい|はい|はい|はい|はい|
|Skype for Business の統合|はい|はい|はい|はい|はい|はい|はい|はい|
|**[高可用性とビジネス継続性](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|データセンターでのメールボックスレプリケーション|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|削除済みメールボックスの回復|はい|はい|はい|はい|はい|はい|はい|はい|
|削除済みアイテムの回復|はい|はい|はい|はい|はい|はい|はい|はい|
|単一アイテムの回復|はい|はい|はい|はい|はい|はい|はい|いいえ||
|**[相互運用性、接続、および互換性](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|OWA および Outlook の Skype for Business のプレゼンス|はい|はい|はい|はい|はい|はい|はい|はい|
|SharePoint の相互運用性|はい|はい|はい|はい|はい|はい|はい|はい|
|EWS 接続のサポート|はい|はい|はい|はい|はい|はい|はい|いいえ|
|SMTP リレーのサポート|はい|はい|はい|はい|はい|はい|はい|はい|
|**[Exchange Online のセットアップと管理](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft Office 365 ポータルへのアクセス|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Microsoft 365 管理センターへのアクセス|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Exchange 管理センターへのアクセス|はい|はい|はい|はい|はい|はい|はい|はい|
|リモート Windows PowerShell へのアクセス|はい|はい|はい|はい|はい|はい|はい|はい|
|モバイルデバイスの ActiveSync ポリシー|はい|はい|はい|はい|はい|はい|はい|はい|
|利用状況レポート|はい|はい|はい|はい|はい|はい|はい|はい|
|**サービスのカスタマイズ、アドイン、およびリソースの拡張**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Outlook アドインと Outlook MAPI|Yes (<sup>19</sup> )|はい|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|いいえ|

<sup>1</sup> クラウドベースのアーカイブがある社内メールボックスユーザーごとに Exchange Online アーカイブサブスクリプションが必要です。 <br/>
<sup>2</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、microsoft 365 App for enterprise のサブスクリプションが必要です。これは、Microsoft 365 Business Basic、Microsoft 365 Business Standard、Office 365 Enterprise E1、Office 365 エデュケーション、または Office 365 Enterprise F3 に含まれていません。 <br/>
<sup>3</sup> Windows Server AD RMS は、サポートされている IRM 機能を有効にするためには別途購入して管理する必要があるオンプレミスのサーバーです。 <br/>
<sup>4</sup> トランスポートルールは、柔軟な条件で構成されており、条件と例外、および条件に基づいて実行するアクションを定義できます。 使用可能な条件とアクションは Exchange Online と Microsoft Exchange Server 2013 で異なります。 使用可能な条件とアクションのリストについては、製品ごとに該当する条件とアクションのトピックをご覧ください。 <br/>
<sup>5</sup> exchange 2013 では、DLP には Exchange エンタープライズクライアントアクセスライセンス (CAL) が必要です。 Cal とサーバーライセンスの詳細については、「 [Exchange Licensing faq](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)」を参照してください。 <br/>
<sup>6</sup> exchange server 2013 には、exchange server 2010 と同じ組み込みスパム対策機能のほとんどがあります。 オンプレミスのオファーリングでの Exchange ホスト型スパムフィルターの利点については、「exchange [Server 2013 経由の Exchange Online Protection のスパム対策機能のメリット](https://docs.microsoft.com/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)」を参照してください。 <br/>
<sup>7</sup> Exchange 管理センター (EAC) 管理インターフェイスに直接アクセスすることによってのみアクセスできます。 <br/>
<sup>8</sup> Exchange Server 2013 は、Microsoft マルウェア対策エンジンのみを使用します。 Exchange Online は複数のマルウェア対策エンジンを使用して、マルウェアがないかどうか受信メッセージ、送信メッセージ、内部メッセージをスキャンします。 <br/>
<sup>9</sup> eoa サブスクリプションは、非アクティブなメールボックスまたはアーカイブ機能のいずれかが必要なメールボックスごとに個別に購入できます。<br/>
<sup>10</sup> SharePoint をオンプレミスの Exchange 組織に展開する必要があります。 <br/>
<sup>11</sup> SharePoint Online がサブスクリプションプランに含まれている必要があります。 <br/>
<sup>12</sup> POP はサポートされていますが、IMAP はサポートされていません。 <br/>
<sup>13</sup> Azure Information Protection を購入した Exchange Server 2013 オンプレミスのお客様に対してサポートされています。 Office 365 Message Encryption では、電子メールのフィルタリングに Exchange Online Protection を使用するか、またはハイブリッドメールフローを確立することによって、オンプレミスのお客様が Exchange Online を介して電子メールをルーティングする必要があります。 <br/>
<sup>14</sup> Exchange Server 2013 お客様は、OWA およびデバイス用 Owa でドキュメントフィンガープリンティングとポリシーヒントにアクセスするために、SP1 をダウンロードしてインストールする必要があります。 <br/>
<sup>15</sup> BitLocker ドライブ暗号化は Exchange Server 2013 でサポートされていますが、管理者がこの機能を有効にする必要があります。 <br/>
<sup>16</sup> Microsoft 365 business Basic、Microsoft 365 Business Standard、および Office 365 Enterprise F3 は、オンプレミスのサーバーを使用した使用に対するアクセス権を提供しません。 準拠するには、お客様は該当する CAL を購入するか、既に購入しているか、この種のアクセス権を提供する Enterprise SKU にアップグレードする必要があります。 <br/>
<sup>17</sup> 個の接続されたアカウントは POP IMAP アカウントでサポートされてい &amp; ますが、Outlook.com (Hotmail) では無効になっています。 <br/>
<sup>18</sup> Exchange Online PowerShell でコマンドレットを使用して、既定のアドレス一覧および既定のグローバルアドレス一覧 (GAL) をカスタマイズすることはサポートされていません。 <br/>
<sup>19</sup> 一部のサードパーティの web パーツやアドインは使用できない場合があります。 <br/>
<sup>20</sup> 電子情報開示では、オンプレミスとクラウドの間に別のクエリが必要になります。 <br/>
<sup>21</sup> 表は、クライアントが関連付けられたプランを使用して動作するかどうかを示します。 クライアントがこれらのプランを購入する必要があることを示すものではありません。 <br/>
<sup>22</sup> 詳細については、「 [顧客キーによるサービスの暗号化](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)」を参照してください。 <br/>
<sup>23</sup> お客様の操作による直接接続を介したサードパーティ製 PBX システム向けの EXCHANGE Online UM サポートは、2019年4月に終了します。 詳細については、「exchange [Online ユニファイドメッセージングでのセッションボーダーコントローラーのサポート中止](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853) 」を参照してください。 <br/>
<sup>24</sup> F3 ユーザーが自分のメールボックスに代理人を追加することはできませんが、別のメールボックス (共有メールボックスを含む) にアクセスして、それらに委任されたアクションを実行することはできます。<br/>
<sup>25</sup> exchange server 2013 および exchange server 2016 では、Microsoft 365 Apps for enterprise のサブスクリプションも必要です。

## <a name="feature-availability-across-exchange-online-standalone-plans"></a>Exchange Online スタンドアロンの各プランで利用できる機能

| 機能 | Exchange Server 2013 | Exchange Server 2016 | Exchange Online プラン &nbsp; 1 | Exchange Online プラン &nbsp; 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](planning-and-deployment.md)**||||||
|サポートされているハイブリッド展開|はい|はい|はい|はい|Yes<sup>23</sup>|
|サポートされている IMAP 移行|はい|はい|はい|はい|はい|
|カット オーバー移行のサポート|はい|はい|はい|はい|はい|
|サポートされている段階的な移行|いいえ|いいえ|はい|はい|はい|
|**[アクセス許可](permissions.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン 1**|**Exchange Online プラン 2**|**Exchange Online Kiosk**|
|役割に基づくアクセス許可|はい|はい|はい|はい|いいえ|
|役割グループ|はい|はい|はい|はい|いいえ|
|役割の割り当てポリシー|はい|はい|はい|はい|いいえ|
|**[メッセージ ポリシーとコンプライアンス](message-policy-and-compliance.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Exchange Online ベースのメールボックスのアーカイブ|はい|いいえ|はい|はい|いいえ|
|社内メールボックスのクラウドベースのアーカイブ|はい <sup>5</sup>|はい <sup>5</sup>|いいえ|はい|いいえ|
|Messaging Records Management(MRM) |はい|はい|はい|はい|はい|
|手動のアイテム保持ポリシー、ラベル、タグ|いいえ|いいえ|はい|はい|はい|
|保存中のデータの暗号化 (BitLocker)|Yes<sup>16</sup>|Yes<sup>16</sup>|はい|はい|はい|
|Azure Information Protection を使用した IRM|いいえ|はい|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|
|Windows Server AD RMS を使用した IRM|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|
|Office 365 Message Encryption|はい<sup>13</sup>|はい<sup>13</sup>|<sup>11</sup>なし|<sup>11</sup>なし|<sup>11</sup>なし|
|S/MIME|はい (<sup>15</sup> )|はい (<sup>15</sup> )|はい|はい|はい|
|インプレース保持と訴訟ホールド|はい|はい|<sup>17</sup>|はい|いいえ|
|インプレース電子情報開示 (eDiscovery)|Yes<sup>22</sup>|Yes<sup>22</sup>|Yes<sup>22</sup>|Yes<sup>22</sup>|Yes<sup>22</sup>|
|トランスポート ルール|はい <sup>1</sup>|はい <sup>1</sup>|はい <sup>1</sup>|はい <sup>1</sup>|はい <sup>1</sup>|
|データ損失防止|はい<sup>10、14</sup>|はい<sup>10、14</sup>|いいえ|はい|いいえ|
|ジャーナル|はい|はい|はい|はい|はい|
|**[スパム対策とマルウェア対策の保護](anti-spam-and-anti-malware-protection.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|組み込みのスパム対策保護|はい <sup>2</sup>|はい <sup>2</sup>|はい|はい|はい|
|Customize anti-spam policies|はい (PowerShell を使用する必要がある)|はい (PowerShell を使用する必要がある)|はい|はい|はい <sup>8</sup>|
|組み込みのマルウェア対策保護|はい <sup>7</sup>|はい <sup>7</sup>|はい<sup>7</sup>|はい<sup>7</sup>|はい<sup>7</sup>|
|Customize anti-malware policies|はい|はい|はい|はい|はい <sup>8</sup>|
|検疫 - 管理者による管理|はい|はい|はい|はい|はい <sup>8</sup>|
|検疫 - エンドユーザーによる自己管理|いいえ|いいえ|はい|はい|はい|
|**[メール フロー](mail-flow.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|送信メールのカスタムルーティング|はい|はい|はい|はい|はい|
|Secure messaging with a trusted partner|はい|はい|はい|はい|はい|
|Conditional mail routing|いいえ|いいえ|はい|はい|はい|
|着信セーフリストへのパートナーの追加|いいえ|いいえ|はい|はい|はい|
|ハイブリッド電子メールルーティング|はい|はい|はい|はい|はい|
|**[受信者](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|容量のアラート|はい|はい|はい|はい|はい|
|クラッター機能|いいえ|いいえ|はい|はい|はい|
|メール ヒント|はい|はい|はい|はい|はい|
|代理人アクセス|はい|はい|はい|はい|いいえ|
|受信トレイのルール|はい|はい|はい|はい|はい|
|接続されているアカウント|はい|はい|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|Yes (<sup>19</sup> )|
|非アクティブなメールボックス|いいえ|いいえ|いいえ <sup>6</sup>|はい|いいえ <sup>6</sup>|
|オフライン アドレス帳|はい|はい|はい|はい|はい|
|アドレス帳ポリシー|はい|はい|はい|はい|はい|
|階層型アドレス帳|はい|はい|はい|はい|いいえ|
|アドレス一覧とグローバルアドレス一覧|はい|はい|はい (<sup>20</sup> )|はい (<sup>20</sup> )|はい (<sup>20</sup> )|
|Office 365 グループ|いいえ|いいえ|はい<sup>24</sup>|はい<sup>24</sup>|なし|
|配布グループ|はい|はい|はい|はい|はい|
|外部連絡先 （グローバル）|はい|はい|はい|はい|はい|
|ユニバーサル連絡先カード|はい|はい|はい|はい|はい|
|ソーシャルネットワークを使用した連絡先リンク|はい|はい|はい|はい|はい|
|リソース メールボックス|はい|はい|はい|はい|はい|
|会議室の管理|はい|はい|はい|はい|はい|
|不在時の返信|はい|はい|はい|はい|はい|
|予定表の共有|はい|はい|はい|はい|あり <sup>18</sup>|
|**[レポート機能とトラブルシューティング ツール](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft 365 管理センターのレポート|いいえ|いいえ|はい|はい|はい|
|Excel レポート作成ブック|いいえ|いいえ|はい|はい|はい|
|Web サービスレポート|いいえ|いいえ|はい|はい|はい|
|Message trace|いいえ|はい|はい|はい|はい <sup>8</sup>|
|監査レポート|はい|はい|はい|はい|はい <sup>8</sup>|
|ユニファイド メッセージングのレポート|はい|はい|いいえ|はい|いいえ|
|**[共有とコラボレーション](sharing-and-collaboration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|フェデレーションの共有|はい|はい|はい|はい|はい|
|サイト メールボックス|はい <sup>3</sup>|はい <sup>3</sup>|はい <sup>4</sup>|はい <sup>4</sup>|はい <sup>4</sup>|
|パブリック フォルダー|はい|はい|はい|はい|いいえ|
|**[クライアントとモバイル デバイス](clients-and-mobile-devices.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft Outlook|はい|はい|はい|はい|いいえ|
|Outlook on the web|はい|はい|はい|はい|はい|
|Exchange ActiveSync|はい|はい|はい|はい|はい|
|POP と IMAP|はい|はい|はい|はい|はい <sup>9</sup>|
|SMTP|はい|はい|はい|はい|はい|
|EWS アプリケーションのサポート|はい|はい|はい|はい|いいえ|
|Outlook for Mac|はい|はい|はい|はい|いいえ|
|Outlook for iOS and Android<sup>21</sup>|はい (<sup>25</sup> )|はい (<sup>25</sup> )|はい|はい|はい|
|**[音声メッセージ サービス](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|ボイス メール|はい|はい|いいえ|はい|いいえ|
|サードパーティボイスメールの相互運用性|はい|はい|はい|はい|はい|
|Skype for Business の統合|はい|はい|はい|はい|はい|
|**[高可用性とビジネス継続性](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|データ センターでのメールボックス レプリケーション|いいえ|いいえ|はい|はい|はい|
|削除済みメールボックスの回復|はい|はい|はい|はい|はい|
|削除済みアイテムの回復|はい|はい|はい|はい|はい|
|単一アイテムの回復|はい|はい|はい|はい|いいえ|
|**[相互運用性、接続、および互換性](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|OWA および Outlook の Skype for Business のプレゼンス|はい|はい|はい|はい|はい|
|SharePoint の相互運用性|はい|はい|はい|はい|はい|
|EWS 接続のサポート|はい|はい|はい|はい|はい|
|SMTP リレーのサポート|はい|はい|はい|はい|はい|
|**[Exchange Online のセットアップと管理](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft Office 365 ポータルへのアクセス|いいえ|いいえ|はい|はい|はい|
|Microsoft 365 管理センターへのアクセス|いいえ|いいえ|はい|はい|はい|
|Exchange 管理センターへのアクセス|はい|はい|はい|はい|はい <sup>8</sup>|
|リモート Windows PowerShell へのアクセス|はい|はい|はい|はい|はい|
|モバイルデバイスの ActiveSync ポリシー|はい|はい|はい|はい|はい|
|利用状況レポート|はい|はい|はい|はい|はい|
|**Extending the Service - Customization, Add-ins, and Resources**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Web 上の Outlook web パーツ|はい|はい|はい|はい|はい|
|Outlook アドインと Outlook MAPI|はい|はい|はい (<sup>21</sup> )|はい (<sup>21</sup> )|いいえ|

<sup>1</sup> トランスポートルールは柔軟な条件で構成されており、条件と例外、および条件に基づいて実行するアクションを定義できます。 使用可能な条件とアクションは Exchange Online と Microsoft Exchange Server 2013 で異なります。 使用可能な条件とアクションのリストについては、製品ごとに該当する条件とアクションのトピックをご覧ください。 <br/>
<sup>2</sup> 社内での exchange ホスト型スパムフィルターの利点については、「exchange [Server 2013 経由の exchange Online Protection のスパム対策機能のメリット](https://docs.microsoft.com/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)」を参照してください。 <br/>
<sup>3</sup> SharePoint をオンプレミスの Exchange 組織に展開する必要があります。 <br/>
<sup>4</sup> SharePoint Online は、サブスクリプションプランに含まれている必要があります。 <br/>
<sup>5</sup> クラウドベースのアーカイブがある社内メールボックスユーザーごとに Exchange Online アーカイブサブスクリプションが必要です。 <br/>
<sup>6</sup> Exchange Online アーカイブサブスクリプションは、非アクティブなメールボックス機能が必要なメールボックスごとに個別に購入できます。 <br/>
<sup>7</sup> Exchange Server 2013 は、Microsoft マルウェア対策エンジンのみを使用します。 Exchange Online は複数のマルウェア対策エンジンを使用して、マルウェアがないかどうか受信メッセージ、送信メッセージ、内部メッセージをスキャンします。 <br/>
<sup>8</sup> Exchange 管理センター (EAC) 管理インターフェイスに直接アクセスすることによってのみアクセス可能です。 <br/>
<sup>9</sup> IMAP はサポートされていません。 <br/>
<sup>10</sup> exchange 2013 以降の場合、DLP には、Exchange Enterprise クライアントアクセスライセンス (CAL) が必要です。 Cal とサーバーライセンスの詳細については、「 [Exchange Licensing faq](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)」を参照してください。 <br/>
<sup>11</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入し、サポートされている Information Rights MANAGEMENT (IRM) 機能を有効にすることができます。 Azure Information Protection の一部の機能には、microsoft 365 App for enterprise のサブスクリプションが必要です。これは、Microsoft 365 Business Basic、Microsoft 365 Business Standard、Office 365 Enterprise E1、Office 365 エデュケーション、または Office 365 Enterprise F3 に含まれていません。 Office 365 メッセージの暗号化は、Azure Information Protection に依存します。 <br/>
<sup>12</sup> WINDOWS SERVER AD RMS は、サポートされている IRM 機能を有効にするために別途購入して管理する必要があるオンプレミスのサーバーです。 <br/>
<sup>13</sup> Exchange Server 2013 以降を実行しているお客様が Azure Information Protection を購入している。 Office 365 Message Encryption では、電子メールのフィルタリングに Exchange Online Protection を使用するか、またはハイブリッドメールフローを確立することによって、オンプレミスのお客様が Exchange Online を介して電子メールをルーティングする必要があります。 <br/>
<sup>14</sup> Exchange Server 2013 以降を実行しているお客様は、最新の累積的な更新プログラム (CU) または直前の cu をダウンロードしてインストールし、Owa およびデバイス用 Owa のドキュメントフィンガープリンティングとポリシーヒントにアクセスする必要があります。 <br/>
<sup>15</sup> Exchange Server 2013 以降を実行しているお客様が利用できます。 <br/>
<sup>16</sup> BitLocker ドライブ暗号化は Exchange Server 2013 でサポートされていますが、管理者がこの機能を有効にする必要があります。 <br/>
<sup>17</sup> Exchange Online プラン1には [、メールボックスとアーカイブのサイズ制限](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)があります。 Exchange online 用の exchange Online のアーカイブは、クラウドベースのアーカイブと [インプレース保持](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/compliance-and-security-features#in-place-hold-and-litigation-hold)を無制限に追加します。 <br/>
<sup>18</sup> Exchange Online Kiosk の予定表は OWA を介してのみアクセスまたは共有できます。 <br/>
<sup>19</sup> 個の接続されたアカウントは POP IMAP アカウントでサポートされてい &amp; ますが、Outlook.com (Hotmail) では無効になっています。 <br/>
<sup>20</sup> Exchange Online PowerShell でコマンドレットを使用して既定のアドレス一覧および既定のグローバルアドレス一覧 (GAL) をカスタマイズすることはサポートされていません。 <br/>
<sup>21</sup> いくつかのサードパーティの web パーツやアドインは使用できない場合があります。 <br/>
<sup>22</sup> 電子情報開示については、オンプレミスとクラウドについて別のクエリが必要になります。 <br/>
<sup>23</sup> Exchange Online Kiosk は、オンプレミスサーバーの使用に対するアクセス権を提供しません。 準拠するには、お客様は該当する CAL を購入するか、既に購入しているか、この種のアクセス権を提供する Enterprise SKU にアップグレードする必要があります。 <br/>
<sup>24</sup> 個の Microsoft 365 グループが、制限された機能で利用可能です。<br/>
<sup>25</sup> exchange server 2013 および exchange server 2016 では、Microsoft 365 Apps for enterprise のサブスクリプションも必要です。
