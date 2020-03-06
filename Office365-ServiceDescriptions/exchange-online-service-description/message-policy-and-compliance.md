---
title: メッセージ ポリシーとコンプライアンス
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 03f282d6458c763fc362d2ea680d12f4cf5e2861
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545870"
---
# <a name="message-policy-and-compliance"></a>メッセージ ポリシーとコンプライアンス

## <a name="archiving-exchange-online-based-mailboxes"></a>Exchange Online ベースのメールボックスのアーカイブ

Exchange Online のメールボックスはクラウド内に存在するため、これらのメールボックスをアーカイブするには固有のホスティング環境が必要になります。いくつかのケースでは、Exchange Online を使用して社内メールボックスをクラウドでアーカイブすることもできます。このセクションでは、Exchange Online でのアーカイブ オプションについて説明します。
  
Exchange Online には、ユーザーが古い電子メールメッセージを保存するのに便利な場所を提供するインプレースアーカイブなど、クラウドベースのメールボックス用の組み込みアーカイブ機能が用意されています。 インプレースアーカイブは、Outlook および web 上の Outlook のユーザーのプライマリメールボックスフォルダーと共に表示される特別な種類のメールボックスです。 ユーザーは、アクセスして、プライマリメールボックスを検索するのと同じ方法でアーカイブにアクセスして検索できます。 利用可能な機能は、使用中のクライアントによって異なります。
  
- Outlook **2016、outlook 2013、outlook 2010、web 上の outlook**ユーザーは、アーカイブのすべての機能に加え、保持およびアーカイブポリシーの制御といった関連するコンプライアンス機能を利用できます。 
    
- **Outlook 2007** ユーザーはインプレース アーカイブの基本的な機能を利用できますが、すべてのアーカイブ機能とコンプライアンス機能を利用できるわけではありません。たとえば、ユーザーはメールボックス アイテムに対して保持またはアーカイブ ポリシーを適用できないため、管理者がプロビジョニングするポリシーを使用する必要があります。 
    
管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用し、特定のユーザーに対する個人用アーカイブ機能を有効にします。
  
詳細については、次のトピックを参照してください。
  
- [Exchange Online のアーカイブ メールボックス](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [ Exchange Online のアーカイブ メールボックスを有効または無効にする ](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>アーカイブのサイズ

個々の個人用アーカイブには、1 人のユーザーのメッセージ データを保存できます。 ストレージの割り当ては、次のようにサブスクリプション プランによって異なります。 アーカイブメールボックスのサイズの詳細については、「 [Exchange Online の制限](exchange-online-limits.md)」の「メールボックスの格納域の制限」セクションを参照してください。
  
> [!IMPORTANT]
> - ジャーナリング、トランスポート ルール、または自動転送ルールを使用してアーカイブの目的のため、Exchange Online メールボックスにメッセージをコピーすることは許可されていません。 Microsoft は、メールボックスアーカイブが個人のシナリオで使用されていない場合や不適切な使用がある場合に、無制限のアーカイブを拒否する権利を留保します。
> - インプレース アーカイブには、Outlook ユーザーに対する特定のライセンス要件があります。Outlook 2007 ユーザーが個人用アーカイブにアクセスするためには、Office 2007 の 2011 年 2 月の累積的な更新プログラムが必要です。 
> - Exchange Online では、管理者が作成した .pst ファイルを個人用アーカイブにインポートするために、Exchange Server 2010 Service Pack 1 以降の_New-mailboximportrequest_ Windows PowerShell コマンドレットをサポートしていません。 ユーザーのプライマリ メールボックスとアーカイブの両方が Exchange Online にある場合、管理者は PST Capture (無料ツール) を使用してユーザーのプライマリ メールボックスまたはアーカイブに .pst ファイルのデータをインポートすることができます。

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>社内メールボックスのクラウドベースのアーカイブ

Microsoft のホスト型のアーカイブ ソリューションである Microsoft Exchange Online Archiving では、Exchange Online を使用して Exchange Server 2010 以降の社内メールボックスをクラウドベースでアーカイブすることができます。これを行うには、社内組織がハイブリッド モードになっているか、Exchange Online Archiving 用にセットアップされている必要があります。
  
> [!IMPORTANT]
> 管理フォルダー ポリシーが適用された Exchange 2010 メールボックス サーバー上の社内メールボックスを使用するユーザーでは、社内またはクラウドベースのインプレース アーカイブを有効にすることはできません。 
  
## <a name="retention-tags-and-retention-policies"></a>保持タグおよびアイテム保持ポリシー

Exchange Online で提供される保持ポリシーは、組織における電子メールおよびその他の通信に関連する負担を軽減するのに役立ちます。 これらのポリシーを使用すると、管理者はユーザーの受信トレイ内の特定のフォルダーに保持設定を適用できます。 管理者は、ユーザーにアイテム保持ポリシーのメニューを提供して、Outlook 2010 以降または web 上の Outlook を使用して、特定のアイテム、会話、またはフォルダーにポリシーを適用することもできます。
  
Exchange Online では、管理者は Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用してアイテム保持ポリシーを管理します。
  
Exchange Online では、アーカイブ ポリシーと削除ポリシーの 2 つのタイプのポリシーが利用できます。同じアイテムまたはフォルダーに対して両方のタイプを組み合わせて使用することができます。たとえば、ユーザーは指定した日数後に電子メール メッセージをインプレース アーカイブに自動的に移動し、さらに一定の期間が経過した後に削除するように電子メール メッセージにタグ付けできます。
  
Outlook 2010 以降および web 上の Outlook では、ユーザーはフォルダー、会話、または個々のメッセージにアイテム保持ポリシーを適用することができます。 また、メッセージに適用済みのアイテム保持ポリシーや削除日を表示することもできます。 他の電子メール クライアントのユーザーは、管理者が設定したサーバー側のアイテム保持ポリシーに基づいて電子メール メッセージの削除またはアーカイブを行うことができます。
  
Exchange Online で利用できるアイテム保持ポリシーの機能は、Exchange Server 2010 Service Pack 2 RU4 で利用できる機能と同じです。管理者はリモート Windows PowerShell を使用して、アイテム保持ポリシーを Exchange Server 2010 以降の社内環境から Exchange Online に移行できます。
  
> [!IMPORTANT]
> 管理フォルダー (Exchange Server 2007 で導入された古いメッセージング レコード管理方式) は Exchange Online では利用できません。 
  
詳細については、「[保持タグおよびアイテム保持ポリシー](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)」を参照してください。
  
## <a name="encryption-of-data-at-rest"></a>保管中データの暗号化

Office 365 の顧客保存データの暗号化は、Exchange Online、Skype for Business、OneDrive for Business、SharePoint Online での複数のサービス側テクノロジ (BitLocker、DKM、Azure Storage Service Encryption、およびサービス暗号化を含む) によって提供されます。Office 365 Service Encryption には、Azure Key Vault に格納され、顧客によって管理される暗号化キーを使用するオプションがあります。この顧客管理キー オプションは [Office 365 顧客キー](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697)と呼ばれ、Exchange Online、SharePoint Online、OneDrive for Business で使用できます。 
  
### <a name="bitlocker"></a>BitLocker

Office 365 サーバーは BitLocker を使用して、顧客保存データが含まれるディスク ドライブをボリューム レベルで暗号化します。BitLocker 暗号化は、Windows に組み込まれているデータ保護機能です。BitLocker は、顧客データが含まれるディスクに何者かが物理的にアクセスできるようになりかねない過失がプロセスや制御 (アクセス制御またはハードウェアのリサイクルなど) で生じた場合に、脅威から安全に保護するために使用されるテクノロジの 1 つです。その場合、BitLocker は、コンピューターやディスクの紛失、盗難、または不適切な廃棄によるデータの盗難や漏洩などの脅威の可能性を低減します。  
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

BitLocker に加え、Distributed Key Manager (DKM) と呼ばれるテクノロジも使用しています。DKM は、一連の秘密キーを使用して情報を暗号化および復号化するクライアント側の機能です。Active Directory ドメイン サービス内の特定のセキュリティ グループのメンバーのみが、DKM によって暗号化されたデータを解読するためにこれらのキーにアクセスできます。Exchange Online では Exchange プロセスの実行に使用する特定のサービス アカウントだけが、そのセキュリティ グループに属します。データセンター内の標準運用手順の一環として、このセキュリティ グループに属する資格情報は人間には付与されないため、人間はだれもこれらの機密情報を解読できるキーにアクセスできません。
  
## <a name="customer-key"></a>顧客キー

顧客キーによって、組織の暗号化キーを制御し、Microsoft のデータ センターにある保存データの暗号化にそれを使用するよう Office 365 を構成できます。保存データには、メールボックスに保存されている Exchange Online および Skype for Business からのデータと、SharePoint Online および OneDrive for Business に保存されているファイルが含まれます。詳しくは、「[顧客キーを使用して Office 365 のデータを制御する](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)」および「[Office 365 の顧客キーによるサービスの暗号化に関してよく寄せられる質問](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq)」を参照してください。
  
## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption によって、電子メール ユーザーは暗号化された電子メールを任意の宛先に送信できます。Azure Information Encryption の保護機能を活用する Office Message Encryption の新機能を発表しました。これらの新機能ではエンド ユーザー エクスペリエンスが拡張されており、それによって組織内外のだれとでも保護されたメッセージを簡単に共有し、共同作業をすることが可能になります。新しい Office Message Encryption 機能のセットアップにはいくつかの要件があります。Azure Information Protection をベースにビルドされている新しい Office 365 Message Encryption 機能のセットアップ情報を参照してください。従来の Office 365 Message Encryption を使用しているお客様は、上記のガイダンスに基づいてセットアップを行わない限り、新機能をご利用になれません。Office 365 Message Encryption の新旧それぞれの機能の詳細については、[FAQ](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) を参照してください。 

Office 365 Advanced Message Encryption では、メッセージの有効期限と失効を許可することによって、追加の保護を提供します。  組織から送信される暗号化メール用に複数のテンプレートを作成することもできます。  高度なメッセージの暗号化は、Microsoft 365 E5、Office 365 E5、Microsoft 365 E5 (非営利スタッフの価格)、Office 365 Enterprise E5 (非営利スタッフの価格)、または Office 365 教育 A5 に含まれています。 Office 365 の高度なメッセージ暗号化が含まれていない Office 365 サブスクリプションが組織にある場合は、Microsoft 365 E5 コンプライアンスまたは Office 365 Advanced コンプライアンス SKU をアドオンとして購入できます。

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME を使用すれば、組織内で署名して暗号化した電子メールを送信することにより、機密情報を保護することができます。管理者は、PKI 証明書を設定してユーザーに発行した後で、リモート Windows PowerShell を使用して S/MIME をセットアップすることができます。この証明書は、社内の Active Directory 証明書サービスから同期する必要があります。
  
S/MIME は Microsoft Edge および Internet Explorer 11 でサポートされています。 現在、S/MIME は Firefox、Opera、および Chrome でサポートされていません。 詳細については、「[S/MIME によるメッセージの署名と暗号化](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019)」を参照してください。
  
## <a name="in-place-hold-and-litigation-hold"></a>インプレース保持と訴訟ホールド

訴訟となる可能性がある程度見込まれる場合、組織では、訴訟に関連する電子メールを含めた電子的に格納された情報 (ESI) を保持する必要があります。訴訟の詳細が明らかになる前に訴訟の可能性を予測する場合もあるため、保持の対象が広範囲にわたることもあります。組織では、特定の問題に関するすべての電子メールを保存したり、特定の個人に関するすべての電子メールを保存したりします。
  
Exchange Online では、次の目標を達成するためにインプレース保持または訴訟ホールドを使用できます。
  
- ユーザーを保持の状態にしてメールボックス アイテムを変更しないで維持する
    
- ユーザーまたは自動削除プロセス (MRM など) によって削除されたメールボックス アイテムを維持する
    
- 元のアイテムのコピーを保存して、メールボックス アイテムを改ざん、ユーザーによる変更、または自動プロセスから保護する
    
- アイテムを無期限にまたは特定の期間維持する
    
- MRM を中断する必要をなくしユーザーが保持を意識しないで済むようにする
    
- インプレース電子情報開示を使用して、保留中のアイテムを含むメールボックス アイテムを検索する
    
加えて、インプレース保持を以下の目的に使用できます。
  
- 指定した条件と一致するアイテムを検索して保持する
    
- さまざまなケースまたは調査に対応できるようユーザーに複数のインプレース保持を設定する
    
> [!NOTE]
> メールボックスのインプレース保持または訴訟ホールドを有効にすると、プライマリ メールボックスとアーカイブ メールボックスの両方に保持 (ホールド) が適用されます。 
  
詳細については、「[インプレース保持と訴訟ホールド](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds)」を参照してください。
  
## <a name="in-place-ediscovery"></a>インプレース電子情報開示 (eDiscovery)

Exchange Online を使用すると、ユーザーは web ベースのインターフェイスを使用して、組織全体のメールボックスの内容を検索できます。 インプレースの電子情報開示検索の実行を許可された管理者やコンプライアンス担当者およびセキュリティ担当者は、(割り当てにより) 電子メール メッセージ、添付ファイル、予定表の予定、タスク、連絡先、およびその他のアイテムを検索できます。 インプレース電子情報開示では、プライマリ メールボックスとアーカイブを同時に検索できます。 KQL 構文に加えて、送信者、受信者、メッセージの種類、送信/受信日付、およびカーボン コピー/ブラインド カーボン コピーなどの豊富なフィルタリング機能が利用できます。 検索結果には、検索クエリに一致した削除済みアイテム フォルダー内のアイテムも含まれます。
  
インプレース電子情報開示検索の結果は、Web ベースのインターフェイスでプレビューし、PST ファイルにエクスポートし、探索メールボックスと呼ばれる特殊なメールボックスにコピーすることができます。探索メールボックスには、検索結果を格納するための 50 GB のクォータが割り当てられています。また、管理者は Outlook を探索メールボックスに接続して検索結果にアクセスし、検索結果を .pst ファイルにエクスポートすることもできます。
  
管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用して、複数メールボックス検索を実行できます。Exchange 管理センターでは、検索結果の読み取り専用のプレビューを利用できます。これにより、管理者は検索をすばやく確認し、必要に応じて、別のパラメーターで検索を実行し直すことができます。検索を最適化した後に、管理者は検索結果を探索メールボックスにコピーできます。
  
既定では各組織に 1 つの探索メールボックスが作成されますが、管理者はリモート Windows PowerShell を使用して追加の探索メールボックスを作成することができます。インプレース電子情報開示検索の結果を格納する以外の目的に探索メールボックスを使用することはできません。
  
管理者は Exchange 管理センターまたはリモート Windows PowerShell を使用して、インプレース電子情報開示検索を実行できます。Exchange 管理センターでは、検索結果の読み取り専用のプレビューを利用できます。これにより、管理者は検索をすばやく確認し、必要に応じて、別のパラメーターで検索を実行し直すことができます。検索を最適化した後に、管理者は検索結果を探索メールボックスにコピーしたり、検索結果を PST ファイルにエクスポートしたりできます。
  
管理者は、Exchange 管理センターまたはリモート Windows PowerShell を使用して、インプレース電子情報開示検索で一度に最大 10,000 のメールボックスを検索できます。 
  
Exchange Online では、権限のあるユーザーがインプレース電子情報開示を実行して次の操作のいずれかを選択できます。
  
- **検索結果の推定** 検索によって返されるメッセージ数の見積もりを返します。これには、検索で使用されたキーワードの有効性を判断するキーワードの統計および必要に応じて検索パラメーターの微調整が含まれます。 
    
- **検索結果のプレビュー**
    
- 検索結果に返されたメッセージを検出メールボックスにコピーします。
    
詳細については、「[インプレース電子情報開示 (eDiscovery) (このページは英語の可能性があります)](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)」を参照してください。
  
## <a name="mail-flow-rules"></a>メール フロー ルール

メール フロー ルールを使用すると、組織を通過するメッセージを、特定の条件に基づいて確認し、処理することができます。メール フロー ルールによって、電子メール メッセージにメッセージング ポリシーを適用し、メッセージおよびメッセージング システムを保護し、情報漏洩を防ぐことができます。
  
今日、多くの組織では、組織の内部および外部にいる受信者と送信者の間の通信を制限するメッセージング ポリシーを適用することが、法律、規制要件、または企業ポリシーによって要求されています。一部の組織では、個人間、組織内の各部門のグループ間、および組織外のエンティティ間の通信を制限するだけでなく、以下のようなメッセージング ポリシーの要件も満たす必要があります。
  
- 不適切なコンテンツが組織に侵入したり組織から発信されたりしないようにする
    
- 組織の機密情報をフィルター処理する
    
- 特定の個人によって送受信されるメッセージを追跡またはコピーする
    
- 配信する前に、検査のために受信メッセージと送信メッセージをリダイレクトする
    
- メッセージが組織を通過するときに免責事項を適用する
    
> [!IMPORTANT]
> 電子メール サーバー上にサードパーティの iFilter をインストールする必要のある添付ファイルの種類 (Adobe .pdf など) では、適切な iFilter をインストールしない限りメール フロー ルールを使用して検査できません。メール フロー ルールでサポートされているファイルの種類の詳細については、「[Office 365 で、メール フロー ルールを使用してメッセージの添付ファイルを検査する](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)」を参照してください。
  
メール フロー ルールの詳細については、「[Exchange 2016 でのメール フロー ルール](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019)」をご覧ください。
  
## <a name="data-loss-prevention"></a>データ損失防止

データ損失防止 (DLP) 機能は、詳細なコンテンツ分析によって組織内の機密情報を特定、監視、保護するのに役立ちます。 DLP は、ビジネスに不可欠なメールには保護する必要がある機密データが含まれているため、エンタープライズメッセージシステムにとってますます重要になるプレミアム機能です。 Exchange Online の DLP 機能を使用すると、ワーカーの生産性に影響を与えることなく機密データを保護できます。
  
DLP ポリシーは Exchange 管理センター (EAC) の管理インターフェイスで構成できます。この管理インターフェイスでは、次の操作を行うことができます。 
  
- PCI DSS データ、グラム リーチ ブライリー法データ、またはロケール固有の個人情報 (PII) などの特定の種類の機密情報を検出するのに役立つ構成済みのポリシー テンプレートを利用することができます。
    
- 既存のトランスポート ルールの条件と処理をフルに活用し、新しいトランスポート ルールを追加することができます。
    
- DLP ポリシーを完全に実施する前にその効果をテストできます。
    
- 独自のカスタム DLP ポリシー テンプレートや機密情報の種類を組み込むことができます。
    
- メッセージの添付ファイル、本文テキスト、または件名に含まれる機密情報を検出し、Exchange Online で処理を実行する信頼レベルを調整できます。
    
- ドキュメントのフィンガープリント機能を使って機密性の高いフォーム データを検出できます。ドキュメントのフィンガープリント機能を使用すると、テキスト ベースのフォームを基に、機密情報のカスタム タイプを手早く作成し、トランスポート ルールと DLP ポリシーを定義できます。
    
- ポリシーヒントを追加します。これにより、Outlook 2016、Outlook 2013、Outlook on the web、およびデバイスユーザー用 OWA に通知が表示されるので、データの損失を減らすことができます。また、誤報告を許可することで、ポリシーの有効性を向上させることもできます。 
    
- インシデント レポートの生成アクションを使用して、DLP レポートでのインシデント データの確認や独自のレポートの追加を行うことができます。
    
DLP の詳細については、「[データ損失防止](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)」を参照してください。
  
## <a name="journaling"></a>ジャーナリング

Exchange Online は、SMTP を介してメッセージを受信できる任意の外部メールボックスに電子メールのコピーをジャーナリングするように構成することができます。ジャーナリングは、受信および送信電子メールを記録することで、組織が法律、規則、および組織の準拠要件に応答するのに役立ちます。メッセージのアイテム保持および準拠の計画をする場合、ジャーナリングについて、どのように組織の準拠ポリシーに適合するかを理解することは重要です。
  
ジャーナル ルールは、Exchange 管理センターまたはリモート Windows PowerShell を使用して管理できます。ユーザー単位および配布リスト単位でジャーナリングを構成し、内部メッセージのみ、外部メッセージのみ、または内部メッセージと外部メッセージの両方をジャーナリングするように選択できます。ジャーナリングされたメッセージには、元のメッセージだけでなく、送信者、受信者、コピー、およびブラインド コピーについての情報も含まれます。
  
信頼性の高いジャーナリングを実現するには、次のタスクをすべて実行する必要があります。
  
- ジャーナリングの送信先が Exchange Online のメールボックスになっていないことを確認します。
    
- カスタマーのディレクトリにジャーナリングで使用する SMTP ターゲット メール アドレスの連絡先オブジェクトを作成します。
    
- もう 1 つ別の連絡先オブジェクトを作成します。これは、プライマリのジャーナル メールボックスが使用できないときにジャーナル レポートを受け取る代替用のジャーナル メールボックスです。
    
- SMTP ターゲットの適切な管理、冗長性、可用性、パフォーマンス、および機能レベルを維持して、いつでもメッセージを正常に受信できるようにします。
    
- メッセージ形式、送信者/受信者情報の統合、および適切なコンテンツ変換など、Exchange Server および Exchange トランスポートでの相互運用性を実現します。
    
ジャーナルの詳細については、「[Exchange Online でのジャーナリング](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling)」を参照してください。
  
## <a name="feature-availability"></a>機能の可用性

Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。
  

