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
description: Exchange Online を含むサブスクリプションの機能比較をお探しの場合 その場合は、Exchange Online サービスの説明記事をご覧ください。 システム要件およびストレージと受信者の要件についても説明しています。
ms.openlocfilehash: 7b43af4d2938eea638670f15d807cef53d963d1e
ms.sourcegitcommit: bab0eaae59d5c801f88eadbd29fd0d16de387c82
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/07/2021
ms.locfileid: "49780021"
---
# <a name="exchange-online-service-description"></a>Exchange Online サービスの説明

Exchange Online を含むサブスクリプションの機能比較をお探しの場合 その場合は、Exchange Online サービスの説明記事をご覧ください。 システム要件およびストレージと受信者の要件についても説明しています。
  
> [!NOTE]
> タスクのサポートが必要な場合、または問題のトラブルシューティングを行う場合は、次のリソースが役立つ可能性があります。 <br/>
[メール](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) の作成と送信に関するメール。 <br/> 
[メールと予定表を管理する](https://docs.microsoft.com/office365/admin/email/email)<br/> 
[Microsoft サポート/回復アシスタントについて](https://diagnostics.office.com/)<br/> 
[Exchange Online のメール配信不可レポート](https://docs.microsoft.com/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)<br/> 
[Exchange Online ヘルプ](https://docs.microsoft.com/exchange/exchange-online)
  
Microsoft Exchange Online は、Microsoft Exchange Server の機能をクラウドベースのサービスとして提供するホスト型のメッセージング ソリューションです。ユーザーは PC、Web、およびモバイル デバイスから電子メール、カレンダー、連絡先、タスクにアクセスできます。Active Directory と完全に統合するので、管理者がグループ ポリシーを他の管理ツールと共に使用し、環境全体にわたって Exchange Online 機能を管理することができます。
  
Exchange Online をサブスクライブする組織は、ユーザーに提供するメッセージング サービスを管理できますが、社内サーバー ソフトウェアを運用するときのような負荷はありません。 このドキュメントで説明する Exchange Online のホスト型のプランでは、電子メールは、複数のカスタマーを同時にサポートするサーバー上でホストされます。 これらのサーバーは Microsoft データ センターに収容され、企業ネットワーク内から、またはインターネットを使用して、幅広いデバイスのユーザーがアクセスできます。
  
プラン全体で機能を比較するには、エンタープライズ [をサポートするための強力なツールを参照してください](https://products.office.com/business/compare-more-office-365-for-business-plans)。 Office 365 Germany のプランを比較するには、[Office 365 Germany のサブスクリプション プラン](https://go.microsoft.com/fwlink/?linkid=839016)をご覧ください。
  
> [!TIP]
> Microsoft サービスの説明でページをエクスポート、保存、印刷できます。 コンテンツ検索の結果 [をエクスポートする方法について学習します](https://docs.microsoft.com/office365/securitycompliance/export-search-results)。 
  
## <a name="whats-new-in-exchange-admin-center"></a>Exchange 管理センターの新機能

Exchange 管理センターの新機能の詳細については、「Exchange 管理センターの [新機能」を参照してください](https://docs.microsoft.com/exchange/whats-new)。
  
## <a name="plans-for-exchange-online"></a>Exchange Online のプラン

Microsoft 365 には、組織のニーズに最適なさまざまなプランが用意されています。 スタンドアロン プランのオプションや、別のプランへの移行に関する情報など、さまざまなプランの詳細については、「Office [365 プラン](../office-365-platform-service-description/office-365-plan-options.md)のオプション」を参照してください。
  
Exchange Online サービスにアクセスする各ユーザーは、サブスクリプション プランに割り当てられる必要があります。ユーザーのサブスクリプションごとにメールボックスがあります。これらのメールボックスのフォルダーおよびメッセージは、Microsoft データ センターの Exchange Server が実行されているコンピューター上に格納されます。
  
ユーザー サブスクリプションは、会議室および共有メールボックスには必要ありません。これらの特殊な種類のメールボックスには、ログイン資格情報がありません。これらの特殊な種類のメールボックスは、ライセンスを持ち、適切なアクセス許可があるユーザーが委任によって管理とアクセスを行います。

**Microsoft 365 F1 ユーザー メールボックスの使用権** <br/>
Microsoft 365 F1 には、Exchange メールボックスに対する権限は含されません。 Teams の完全なエクスペリエンスを有効にするために、M365 F1 ライセンスは Exchange Online K1 サービス プランが有効になっている場合があります。 Exchange Online K1 サービス プランはユーザーのメールボックスをプロビジョニングしますが、M365 F1 ユーザーはメールボックスを使用できません。 次の手順を実行して Outlook on [](https://docs.microsoft.com/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app) the web を無効にし、他の方法で Exchange メールボックスにアクセスしなけってユーザーに確認することをお勧めします。
  
## <a name="system-requirements-for-exchange-online"></a>Exchange Online のシステム要件

システム要件、ビジネス、教育、および政府機関が利用できる月次サブスクリプション ベースのサービスについては [、Microsoft 365](https://products.office.com/office-system-requirements/#Office365forBEG)および Office リソースを参照してください。
  
## <a name="storage-and-recipient-limits-for-exchange-online"></a>Exchange Online のストレージと受信者の制限

Exchange Online サブスクリプション プランで使用可能なストレージと受信者の制限については [、「Exchange Online の制限」を参照してください](exchange-online-limits.md)。
  
## <a name="feature-availability"></a>機能の可用性

現在、組織が Office 365 Small Business、Office 365 Small Business Premium、または Office 365 Midsize Business のサブスクリプションを持っている場合は、Microsoft 365 管理センターのメッセージ センターにアクセスするか、新しい Microsoft 365 Apps プランがユーザーに与える影響の詳細についてプロバイダーに問い合わせください。 新しい Microsoft 365 Apps プラン ファミリの詳細については、中小企業向けの新しいプラン [を参照してください](https://blogs.microsoft.com/blog/2014/10/02/new-office-365-plans-small-mid-sized-businesses-available-today)。

Microsoft 365 Business Premium の機能の可用性については [、Microsoft 365 Business Premium](../microsoft-365-service-descriptions/microsoft-365-business-service-description.md)サービスの説明を参照してください。<br/><br/>
  
| 機能 | Exchange Server 2013 | Exchange Server 2016 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](planning-and-deployment.md)**|||||||||
|サポートされているハイブリッド展開|はい|はい|は<sup>い 16</sup>|は<sup>い 16</sup>|はい|はい|はい|は<sup>い 16</sup>|
|サポートされている IMAP 移行|はい|はい|はい|はい|はい|はい|はい|はい|
|カット オーバー移行のサポート|はい|はい|はい|はい|はい|はい|はい|はい|
|サポートされている段階的な移行|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|**[アクセス許可](permissions.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|役割に基づくアクセス許可|はい|はい|はい|はい|はい|はい|はい|いいえ|
|役割グループ|はい|はい|はい|はい|はい|はい|はい|いいえ|
|役割の割り当てポリシー|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[メッセージ ポリシーとコンプライアンス](message-policy-and-compliance.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Exchange Online ベースのメールボックスのアーカイブ| いいえ|いいえ|はい|は<sup>い 9</sup>|は<sup>い 9</sup>|は<sup>い 9</sup>|は<sup>い 9</sup>|いいえ|
|社内メールボックスのクラウドベースのアーカイブ|はい <sup>1</sup>|はい<sup>1</sup>|いいえ|いいえ|はい|はい|はい|いいえ|
|Messaging Records Management(MRM) |はい|はい|はい|はい|はい|はい|はい|はい|
|手動保持ポリシー、ラベル、およびタグ |いいえ|いいえ|いいえ|いいえ|はい|はい|はい|はい|
|保存中のデータの暗号化 (BitLocker)|は<sup>い 15</sup>|は<sup>い 15</sup>|はい|はい|はい|はい|はい|はい|
|Azure Information Protection を使用した IRM|いいえ|はい|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい|はい|いいえ<sup>2</sup>|
|Windows Server AD RMS を使用した IRM|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|はい<sup>3</sup>|
|Office 365 Message Encryption|はい<sup>13</sup>|はい<sup>13</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|いいえ<sup>2</sup>|はい|はい|いいえ<sup>2</sup>|
|顧客キー<sup>22</sup>|いいえ|いいえ|いいえ|いいえ|いいえ|いいえ|はい|いいえ||
|S/MIME|は<sup>い 15</sup>|は<sup>い 15</sup>|はい|はい|はい|はい|はい|はい||
|インプレース保持と訴訟ホールド|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|インプレース電子情報開示 (eDiscovery)|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|あり|
|Transport rules|はい <sup>4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|は<sup>い 4</sup>|
|データ損失防止|はい<sup>5、14</sup>|はい<sup>5、14</sup>|いいえ|いいえ|いいえ|はい|はい|いいえ|
|ジャーナル|はい|はい|はい|はい|はい|はい|はい|はい|
|**[スパム対策とマルウェア対策の保護](anti-spam-and-anti-malware-protection.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|組み込みのスパム対策保護|はい <sup>6</sup>|はい <sup>6</sup>|はい|はい|はい|はい|はい|はい|
|Customize anti-spam policies|はい (ただし、PowerShell 経由のみ)|はい (ただし、PowerShell 経由のみ)|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|組み込みのマルウェア対策保護|はい <sup>8</sup>|はい <sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|はい<sup>8</sup>|
|Customize anti-malware policies|はい|はい|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|検疫 - 管理者による管理|はい|はい|はい|はい|はい|はい|はい|はい <sup>7</sup>|
|検疫 - エンドユーザーによる自己管理|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Microsoft Defender for Office 365|いいえ|はい|いいえ|いいえ|いいえ|いいえ|はい|いいえ|
|**[メール フロー](mail-flow.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|送信メールのカスタム ルーティング|はい|はい|はい|はい|はい|はい|はい|はい|
|Secure messaging with a trusted partner|はい|はい|はい|はい|はい|はい|はい|はい|
|Conditional mail routing|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|受信セーフ リストへのパートナーの追加|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|ハイブリッド 電子メール ルーティング|はい|はい|は<sup>い 16</sup>|は<sup>い 16</sup>|はい|はい|はい|はい|
|**[受信者](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|容量のアラート|はい|はい|はい|はい|はい|はい|はい|はい|
|クラッター機能|はい|いいえ|はい|はい|はい|はい|はい|はい|
|メール ヒント|はい|はい|はい|はい|はい|はい|はい|はい|
|代理人アクセス|はい|はい|はい|はい|はい|はい|はい|No<sup>24</sup>|
|受信トレイのルール|はい|はい|はい|はい|はい|はい|はい|はい|
|接続されているアカウント|はい|はい|はい|はい|は<sup>い 17</sup>|は<sup>い 17</sup>|は<sup>い 17</sup>|は<sup>い 17</sup>|
|非アクティブなメールボックス|いいえ|いいえ|いいえ<sup>9</sup>|いいえ<sup>9</sup>|いいえ<sup>9</sup>|はい|はい|いいえ <sup>9</sup>|
|オフライン アドレス帳|はい|はい|はい|はい|はい|はい|はい|はい|
|アドレス帳ポリシー|はい|はい|はい|はい|はい|はい|はい|はい|
|階層型アドレス帳|はい|はい|はい|はい|はい|はい|はい|いいえ|
|アドレス一覧とグローバル アドレス一覧|はい|はい|はい|はい|は<sup>い 18</sup>|は<sup>い 18</sup>|は<sup>い 18</sup>|は<sup>い 18</sup>|
|Microsoft 365 グループ|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|配布グループ|はい|はい|はい|はい|はい|はい|はい|はい|
|外部連絡先 （グローバル）|はい|はい|はい|はい|はい|はい|はい|はい|
|ユニバーサル連絡先カード|はい|はい|はい|はい|はい|はい|はい|はい|
|ソーシャル ネットワークへの連絡先のリンク|はい|はい|はい|はい|はい|はい|はい|はい|
|リソース メールボックス|はい|はい|はい|はい|はい|はい|はい|はい|
|会議室の管理|はい|はい|はい|はい|はい|はい|はい|はい|
|不在時の返信|はい|はい|はい|はい|はい|はい|はい|はい|
|予定表の共有|はい|はい|はい|はい|はい|はい|はい|はい|
|**[レポート機能とトラブルシューティング ツール](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft 365 管理センターレポート|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Excel レポート ブック|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Web サービス レポート|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Message trace|いいえ|はい|はい|はい|はい|はい|はい|はい|
|監査レポート|はい|はい|はい|はい|はい|はい|はい|はい <sup>3</sup>|
|ユニファイド メッセージングのレポート|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|**[共有とコラボレーション](sharing-and-collaboration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|フェデレーション共有 (予定表の公開を含む)|はい|はい|はい|はい|はい|はい|はい|はい|
|サイト メールボックス|は<sup>い 10</sup>|は<sup>い 10</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|はい<sup>11</sup>|
|パブリック フォルダー|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[クライアントとモバイル デバイス](clients-and-mobile-devices.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Outlook for Windows <sup>21</sup>|はい|はい|はい|はい|はい|はい|はい| いいえ|
|Outlook on the web<sup>21</sup>|はい|はい|はい|はい|はい|はい|はい|はい|
|Outlook for Mac<sup>21</sup>|はい|はい|はい|はい|はい|はい|はい| いいえ|
|Outlook for iOS and Android<sup>21</sup>|は<sup>い 25</sup>|は<sup>い 25</sup>|はい|はい|はい|はい|はい|はい|
|Exchange ActiveSync|はい|はい|はい|はい|はい|はい|はい|はい|
|Microsoft 365 の基本的なモビリティとセキュリティ|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|POP と IMAP|はい|はい|はい|はい|はい|はい|はい|はい <sup>12</sup>|
|SMTP|はい|はい|はい|はい|はい|はい|はい|はい|
|EWS アプリケーションのサポート|はい|はい|はい|はい|はい|はい|はい|いいえ|
|**[音声メッセージ サービス](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|ボイス メール<sup>23</sup>|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|ボイス メールとサードパーティ FAX<sup>23</sup>の統合|はい|はい|いいえ|いいえ|いいえ|はい|はい|いいえ|
|サードパーティボイス メールの相互運用<sup>性 23</sup>|はい|はい|はい|はい|はい|はい|はい|はい|
|Skype for Business の統合|はい|はい|はい|はい|はい|はい|はい|はい|
|**[高可用性とビジネス継続性](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|データ センターでのメールボックス レプリケーション|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|削除済みメールボックスの回復|はい|はい|はい|はい|はい|はい|はい|はい|
|削除済みアイテムの回復|はい|はい|はい|はい|はい|はい|はい|はい|
|単一アイテムの回復|はい|はい|はい|はい|はい|はい|はい|いいえ||
|**[相互運用性、接続、および互換性](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|OWA および Outlook での Skype for Business プレゼンス|はい|はい|はい|はい|はい|はい|はい|はい|
|SharePoint の相互運用性|はい|はい|はい|はい|はい|はい|はい|はい|
|EWS 接続サポート<sup>26</sup>|はい|はい|はい|はい|はい|はい|はい|はい|
|SMTP リレーのサポート|はい|はい|はい|はい|はい|はい|はい|はい|
|**[Exchange Online のセットアップと管理](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft Office 365 ポータルへのアクセス|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Microsoft 365 管理センターへのアクセス|いいえ|いいえ|はい|はい|はい|はい|はい|はい|
|Exchange 管理センターへのアクセス|はい|はい|はい|はい|はい|はい|はい|はい|
|リモート Windows PowerShell へのアクセス|はい|はい|はい|はい|はい|はい|はい|はい|
|モバイル デバイス用の ActiveSync ポリシー|はい|はい|はい|はい|はい|はい|はい|はい|
|利用状況レポート|はい|はい|はい|はい|はい|はい|はい|はい|
|**サービスの拡張 - カスタマイズ、アドイン、およびリソース**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Outlook アドインと Outlook MAPI|は<sup>い 19</sup>|はい|は<sup>い 19</sup>|は<sup>い 19</sup>|は<sup>い 19</sup>|は<sup>い 19</sup>|は<sup>い 19</sup>|いいえ|

<sup>1</sup> クラウドベースのExchange Online Archivingを持つ各オンプレミス メールボックス ユーザーのサブスクリプションを作成する必要があります。 <br/>
<sup>2</sup> つの Azure Information Protection は含まれていませんが、個別のアドオンとして購入できます。また、サポートされる Information Rights Management (IRM) 機能を有効にできます。 一部の Azure Information Protection 機能には、Microsoft 365 Apps for enterprise のサブスクリプションが必要です。Microsoft 365 Business Basic、Microsoft 365 Business Standard、Office 365 Enterprise E1、Office 365 Education、または Office 365 Enterprise F3 には含まれていません。 <br/>
<sup>3</sup> Windows Server AD RMS は、サポートされている IRM 機能を有効にするためには別途購入して管理する必要があるオンプレミスのサーバーです。 <br/>
<sup>4</sup> つのトランスポート ルールは、条件と例外を定義できる柔軟な条件と、条件に基づいて実行するアクションで構成されます。 使用可能な条件とアクションは Exchange Online と Microsoft Exchange Server 2013 で異なります。 使用可能な条件とアクションのリストについては、製品ごとに該当する条件とアクションのトピックをご覧ください。 <br/>
<sup>5</sup> For Exchange 2013, DLP requires an Exchange Enterprise Client Access License (CAL). CALs とサーバー ライセンスの詳細については、Exchange ライセンスに関する [FAQ を参照してください](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。 <br/>
<sup>6 Exchange Server</sup> 2013 には、2010 年とほとんど同じ組み込みのスパム対策機能Exchange Serverがあります。 オンプレミス製品に対する Exchange ホスト型スパム フィルターの利点については、「Exchange Online [Protection Over Exchange Server 2013](https://docs.microsoft.com/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)」を参照してください。 <br/>
<sup>7</sup> Exchange 管理センター (EAC) 管理インターフェイスへの直接アクセスによってのみアクセス可能。 <br/>
<sup>8 Exchange Server</sup> 2013 では、Microsoft マルウェア対策エンジンのみを使用します。 Exchange Online は複数のマルウェア対策エンジンを使用して、マルウェアがないかどうか受信メッセージ、送信メッセージ、内部メッセージをスキャンします。 <br/>
<sup>9</sup> EOA サブスクリプションは、非アクティブなメールボックスまたはアーカイブ機能を必要とするメールボックスごとに個別に購入できます。<br/>
<sup>10</sup> SharePoint をオンプレミスの Exchange 組織に展開する必要があります。 <br/>
<sup>11</sup> SharePoint Online がサブスクリプション プランに含まれている必要があります。 <br/>
<sup>12</sup> POP がサポートされますが、IMAP はサポートされていません。 <br/>
<sup>13</sup> Azure Information Protection Exchange Server 2013 オンプレミスのお客様がサポートされます。 Office 365 Message Encryption では、オンプレミスのお客様が Exchange Online 経由で電子メールをルーティングする必要があります。電子メール フィルター処理に Exchange Online Protection を使用するか、ハイブリッド メール フローを確立します。 <br/>
<sup>14</sup> Exchange Server 2013 のお客様は、OWA およびデバイス用 OWA のドキュメント フィンガープリントとポリシー ヒントにアクセスするために SP1 をダウンロードしてインストールする必要があります。 <br/>
<sup>2013</sup> 年 15 月の BitLocker ドライブ暗号化Exchange Serverサポートされますが、管理者は機能を有効にする必要があります。 <br/>
<sup>16</sup> Microsoft 365 Business Basic、Microsoft 365 Business Standard、および Office 365 Enterprise F3 は、オンプレミス サーバーでの使用に関するアクセス権を提供しません。 準拠するには、お客様は該当する CAL を購入するか、既に購入しているか、この種のアクセス権を提供する Enterprise SKU にアップグレードする必要があります。 <br/>
POP IMAP アカウントでは<sup>17</sup>の接続済みアカウントがサポートされますが、Outlook.com &amp; (Hotmail)。 <br/>
<sup>18</sup> Exchange Online PowerShell のコマンドレットを使用して既定のアドレス一覧をカスタマイズし、既定のグローバル アドレス一覧 (GAL) はサポートされていません。 <br/>
<sup>19</sup> 一部のサード パーティ製 Web パーツとアドインは使用できない場合があります。 <br/>
<sup>20</sup> 電子情報開示の場合は、オンプレミスとクラウドの別々のクエリが必要です。 <br/>
<sup>21</sup> この表は、クライアントが関連付けられているプランを使用するかどうかを示します。 クライアントがこれらのプランを購入する必要があることを示すものではありません。 <br/>
<sup>22 詳細については</sup> 、「顧客キーによる [サービスの暗号化」を参照してください](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)。 <br/>
<sup>23</sup> お客様が運用する SPC からの直接接続によるサードパーティ PBX システムの Exchange Online UM サポートは、2019 年 4 月に終了します。 詳細については、Exchange Online ユニファイド メッセージングでのセッション ボーダー コントローラーのサポートの中止に関する Exchange チーム ブログ [を参照してください](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853)。 <br/>
<sup>24</sup> F3 ユーザーは自分のメールボックスに代理人を追加できませんが、別のメールボックス (共有メールボックスを含む) にアクセスして、委任された操作を実行できます。<br/>
<sup>2013</sup> 年および 2016 年 12 月には、Microsoft 365 Apps for enterprise Exchange ServerサブスクリプションExchange Server必要です。<br/>
<sup>26</sup> EWS アプリケーションのサポートが EWS アプリケーションの偽装に適用されます。

## <a name="feature-availability-across-exchange-online-standalone-plans"></a>Exchange Online スタンドアロンの各プランで利用できる機能

| 機能 | Exchange Server 2013 | Exchange Server 2016 | Exchange Online プラン &nbsp; 1 | Exchange Online プラン &nbsp; 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|
|**[計画と展開](planning-and-deployment.md)**||||||
|サポートされているハイブリッド展開|はい|はい|はい|はい|は<sup>い 23</sup>|
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
|手動保持ポリシー、ラベル、およびタグ|いいえ|いいえ|はい|はい|はい|
|保存中のデータの暗号化 (BitLocker)|は<sup>い 16</sup>|は<sup>い 16</sup>|はい|はい|はい|
|Azure Information Protection を使用した IRM|いいえ|はい|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|Windows Server AD RMS を使用した IRM|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|はい<sup>12</sup>|
|Office 365 Message Encryption|はい<sup>13</sup>|はい<sup>13</sup>|No<sup>11</sup>|No<sup>11</sup>|No<sup>11</sup>|
|S/MIME|は<sup>い 15</sup>|は<sup>い 15</sup>|はい|はい|はい|
|インプレース保持と訴訟ホールド|はい|はい|No<sup>17</sup>|はい|いいえ|
|インプレース電子情報開示 (eDiscovery)|は<sup>い 22</sup>|は<sup>い 22</sup>|は<sup>い 22</sup>|は<sup>い 22</sup>|は<sup>い 22</sup>|
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
|送信メールのカスタム ルーティング|はい|はい|はい|はい|はい|
|Secure messaging with a trusted partner|はい|はい|はい|はい|はい|
|Conditional mail routing|いいえ|いいえ|はい|はい|はい|
|受信セーフ リストへのパートナーの追加|いいえ|いいえ|はい|はい|はい|
|ハイブリッド 電子メール ルーティング|はい|はい|はい|はい|はい|
|**[受信者](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|容量のアラート|はい|はい|はい|はい|はい|
|クラッター機能|いいえ|いいえ|はい|はい|はい|
|メール ヒント|はい|はい|はい|はい|はい|
|代理人アクセス|はい|はい|はい|はい|いいえ|
|受信トレイのルール|はい|はい|はい|はい|はい|
|接続されているアカウント|はい|はい|は<sup>い 19</sup>|は<sup>い 19</sup>|は<sup>い 19</sup>|
|非アクティブなメールボックス|いいえ|いいえ|いいえ <sup>6</sup>|はい|いいえ <sup>6</sup>|
|オフライン アドレス帳|はい|はい|はい|はい|はい|
|アドレス帳ポリシー|はい|はい|はい|はい|はい|
|階層型アドレス帳|はい|はい|はい|はい|いいえ|
|アドレス一覧とグローバル アドレス一覧|はい|はい|は<sup>い 20</sup>|は<sup>い 20</sup>|は<sup>い 20</sup>|
|Office 365 グループ|いいえ|いいえ|は<sup>い 24</sup>|は<sup>い 24</sup>|なし|
|配布グループ|はい|はい|はい|はい|はい|
|外部連絡先 （グローバル）|はい|はい|はい|はい|はい|
|ユニバーサル連絡先カード|はい|はい|はい|はい|はい|
|ソーシャル ネットワークへの連絡先のリンク|はい|はい|はい|はい|はい|
|リソース メールボックス|はい|はい|はい|はい|はい|
|会議室の管理|はい|はい|はい|はい|はい|
|不在時の返信|はい|はい|はい|はい|はい|
|予定表の共有|はい|はい|はい|はい|あり <sup>18</sup>|
|**[レポート機能とトラブルシューティング ツール](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft 365 管理センターレポート|いいえ|いいえ|はい|はい|はい|
|Excel レポート ブック|いいえ|いいえ|はい|はい|はい|
|Web サービス レポート|いいえ|いいえ|はい|はい|はい|
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
|Outlook for iOS and Android<sup>21</sup>|は<sup>い 25</sup>|は<sup>い 25</sup>|はい|はい|はい|
|**[音声メッセージ サービス](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|ボイス メール|はい|はい|いいえ|はい|いいえ|
|サード パーティボイス メールの相互運用性|はい|はい|はい|はい|はい|
|Skype for Business の統合|はい|はい|はい|はい|はい|
|**[高可用性とビジネス継続性](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|データ センターでのメールボックス レプリケーション|いいえ|いいえ|はい|はい|はい|
|削除済みメールボックスの回復|はい|はい|はい|はい|はい|
|削除済みアイテムの回復|はい|はい|はい|はい|はい|
|単一アイテムの回復|はい|はい|はい|はい|いいえ|
|**[相互運用性、接続、および互換性](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|OWA および Outlook での Skype for Business プレゼンス|はい|はい|はい|はい|はい|
|SharePoint の相互運用性|はい|はい|はい|はい|はい|
|EWS 接続サポート<sup>26</sup>|はい|はい|はい|はい|はい|
|SMTP リレーのサポート|はい|はい|はい|はい|はい|
|**[Exchange Online のセットアップと管理](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft Office 365 ポータルへのアクセス|いいえ|いいえ|はい|はい|はい|
|Microsoft 365 管理センターへのアクセス|いいえ|いいえ|はい|はい|はい|
|Exchange 管理センターへのアクセス|はい|はい|はい|はい|はい <sup>8</sup>|
|リモート Windows PowerShell へのアクセス|はい|はい|はい|はい|はい|
|モバイル デバイス用の ActiveSync ポリシー|はい|はい|はい|はい|はい|
|利用状況レポート|はい|はい|はい|はい|はい|
|**Extending the Service - Customization, Add-ins, and Resources**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online プラン &nbsp; 1**|**Exchange Online プラン &nbsp; 2**|**Exchange Online Kiosk**|
|Outlook on the web Web パーツ|はい|はい|はい|はい|はい|
|Outlook アドインと Outlook MAPI|はい|はい|は<sup>い 21</sup>|は<sup>い 21</sup>|いいえ|

<sup>1</sup> トランスポート ルールは柔軟な条件で構成され、条件と例外を定義し、条件に基づいて実行するアクションを定義できます。 使用可能な条件とアクションは Exchange Online と Microsoft Exchange Server 2013 で異なります。 使用可能な条件とアクションのリストについては、製品ごとに該当する条件とアクションのトピックをご覧ください。 <br/>
<sup>2</sup> オンプレミス製品に対する Exchange ホスト型スパム フィルターの利点については、「Exchange [Online Protection over Exchange Server 2013](https://docs.microsoft.com/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)」を参照してください。 <br/>
<sup>3</sup> つの SharePoint をオンプレミスの Exchange 組織に展開する必要があります。 <br/>
<sup>4</sup> つの SharePoint Online がサブスクリプション プランに含まれている必要があります。 <br/>
<sup>5</sup> クラウドベースのExchange Online Archivingを持つ各オンプレミス メールボックス ユーザーのサブスクリプションが必要です。 <br/>
<sup>6</sup> 非Exchange Online Archiving機能を必要とするメールボックスごとに、1 つのサブスクリプションを個別に購入できます。 <br/>
<sup>7 Exchange Server</sup> 2013 では、Microsoft マルウェア対策エンジンのみを使用します。 Exchange Online は複数のマルウェア対策エンジンを使用して、マルウェアがないかどうか受信メッセージ、送信メッセージ、内部メッセージをスキャンします。 <br/>
<sup>8</sup> Exchange 管理センター (EAC) 管理インターフェイスへの直接アクセスによってのみアクセス可能。 <br/>
<sup>9</sup> IMAP はサポートされていません。 <br/>
<sup>10</sup> For Exchange 2013 or later, DLP requires an Exchange Enterprise Client Access License (CAL). CALs とサーバー ライセンスの詳細については、Exchange ライセンスに関する [FAQ を参照してください](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)。 <br/>
<sup>11</sup> Azure Information Protection は含まれていませんが、個別のアドオンとして購入できます。また、サポートされる Information Rights Management (IRM) 機能を有効にできます。 一部の Azure Information Protection 機能には、Microsoft 365 Apps for enterprise のサブスクリプションが必要です。Microsoft 365 Business Basic、Microsoft 365 Business Standard、Office 365 Enterprise E1、Office 365 Education、または Office 365 Enterprise F3 には含まれていません。 Office 365 Message Encryption は Azure Information Protection に依存します。 <br/>
<sup>12</sup> 台の Windows Server AD RMS は、サポートされている IRM 機能を有効にするには、別途購入して管理する必要があるオンプレミス サーバーです。 <br/>
<sup>13</sup> Azure Information Protection を購入した Exchange Server 2013 以降を実行しているお客様に対してサポートされます。 Office 365 Message Encryption では、オンプレミスのお客様が Exchange Online 経由で電子メールをルーティングする必要があります。電子メール フィルター処理に Exchange Online Protection を使用するか、ハイブリッド メール フローを確立します。 <br/>
<sup>14</sup> Exchange Server 2013 以降を実行しているお客様は、OWA およびデバイス用 OWA のドキュメント フィンガープリントとポリシー ヒントにアクセスするには、最新の累積的な更新プログラム (CU) または前の CU をダウンロードしてインストールする必要があります。 <br/>
<sup>15 2013</sup> 以降をExchange Serverのお客様が利用できます。 <br/>
<sup>16</sup> BitLocker ドライブ暗号化は 2013 年 10 月 2013 Exchange Serverサポートされますが、管理者は機能を有効にする必要があります。 <br/>
<sup>17</sup> Exchange Online プラン 1 には、メールボックス [とアーカイブのサイズ制限があります](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits)。 Exchange Online Archiving Exchange Online アドオンの場合、無制限のクラウドベースのアーカイブと [イン Place Hold が追加されます](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/compliance-and-security-features#in-place-hold-and-litigation-hold)。 <br/>
<sup>18</sup> Exchange Online Kiosk OWA 経由でのみアクセスまたは共有できます。 <br/>
POP IMAP アカウントでは<sup>19</sup>の接続済みアカウントがサポートされますが、Outlook.com &amp; (Hotmail)。 <br/>
<sup>20</sup> Exchange Online PowerShell のコマンドレットを使用して既定のアドレス一覧をカスタマイズし、既定のグローバル アドレス一覧 (GAL) はサポートされていません。 <br/>
<sup>21</sup> 一部のサード パーティ製 Web パーツとアドインは使用できない場合があります。 <br/>
<sup>22</sup> 電子情報開示の場合は、オンプレミスとクラウドのクエリを個別に実行する必要があります。 <br/>
<sup>23</sup> Exchange Online Kioskは、オンプレミス サーバーでの使用に関するアクセス権を提供しません。 準拠するには、お客様は該当する CAL を購入するか、既に購入しているか、この種のアクセス権を提供する Enterprise SKU にアップグレードする必要があります。 <br/>
<sup>機能が制限された 24</sup> の Microsoft 365 グループを利用できます。<br/>
<sup>2013</sup> 年および 2016 年 12 月には、Microsoft 365 Apps for enterprise Exchange ServerサブスクリプションExchange Server必要です。<br/>
<sup>26</sup> EWS アプリケーションのサポートが EWS アプリケーションの偽装に適用されます。
