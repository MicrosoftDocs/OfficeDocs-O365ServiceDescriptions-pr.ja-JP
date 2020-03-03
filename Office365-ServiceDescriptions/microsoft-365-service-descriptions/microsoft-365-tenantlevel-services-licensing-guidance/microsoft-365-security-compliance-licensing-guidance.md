---
title: セキュリティ & コンプライアンスのための Microsoft 365 ライセンスガイダンス
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、Microsoft 365 security & コンプライアンスのライセンスに関するガイダンスを提供します。これは、ライセンスのないアクセスによるサービスの停止の可能性を回避するのに役立ちます。
ms.openlocfilehash: 4cb0c741ba7029fbb2420554dc9fa34f3f12b54d
ms.sourcegitcommit: d86c5af19ca1f361820bcc8d6c86560053d67f5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/03/2020
ms.locfileid: "42374164"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>セキュリティ & コンプライアンスのための Microsoft 365 ライセンスガイダンス

この記事では、テナント内のすべてのユーザーに対して、テナント内&mdash;のすべてのユーザー (スタンドアロンまたは Office 365 または Microsoft 365 プランの一部として&mdash;) を購入したときに、テナントレベルのサービスがオンラインサービスになっています。 一部のライセンスのないユーザーは技術的にサービスにアクセスできる可能性がありますが、サービスの利用を目的としているユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナントサービスは、現在、特定のユーザーに対する利点を制限することはできません。 ライセンスを付与されたユーザーにサービスのメリットを制限するための取り組みを実施する必要があります。 これにより、ターゲット機能が使用可能になった場合に、サービスが組織に及ぼす影響を回避できます。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure active Directory Id 保護 (AYOUR p) は、組織の id に影響を及ぼす可能性のある脆弱性を検出し、検出された疑わしいに対する自動応答を構成することができる Azure Active Directory Premium P2 プランの機能です。組織の id に関連するアクションを確認し、疑わしいインシデントを調査して、それらを解決するための適切な処置を講じます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、および Azure Active Directory Premium プラン2は、お役に立てます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOps アナリストおよびセキュリティ担当者は、コンピューターの学習アルゴリズムに基づいてフラグが設定されたユーザーとリスクイベントを統合して表示するのに役立ちます。 エンドユーザーは、リスクベースの条件付きアクセスと、脆弱性に対処することによって提供されるセキュリティ強化によって提供される自動保護からメリットを得られます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで有効になっています。 Aウン p の詳細については、「 [Azure Active Directory Id 保護とは](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、パスワードのリセットのレベルを定義するリスクポリシーを割り当て、ライセンスされたユーザーのみにアクセスを許可することによって、その範囲を設定できます。 展開のスコープを設定する方法については、「[サインインリスクポリシーを構成](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)する」を参照してください。

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure Advanced Threat Protection (ATP) は、複数の種類の高度なターゲット化されたサイバー攻撃および insider の脅威からエンタープライズハイブリッド環境を保護するために役立つクラウドサービスです。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティ、および Azure Advanced Threat Protection を使用すると、Azure ATP からメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOp アナリストおよびセキュリティ担当者は、Azure ATP の機能を利用して、高度な脅威、侵害された id、および悪意のある insider 操作を検出し、調査することができます。 Azure ATP がデータを監視することにより、エンドユーザーはメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Azure ATP 機能がテナントレベルで有効になっています。 Azure ATP の構成の詳細については、「 [AZURE atp インスタンスを作成](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft では、ライセンスを持つユーザーの脅威検出機能を提供しています。

## <a name="azure-information-protection"></a>Azure Information Protection

Azure Information Protection (AIP) は、組織が機密ドキュメントや電子メールを検出、分類、ラベル付け、保護するのに役立ちます。 管理者は、ラベルを自動的に適用するルールと条件を定義できます。ユーザーはラベルを手動で適用する&mdash;ことも、ラベルの適用についてユーザーに推奨事項を与える場合は、2つの組み合わせを使用することもできます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Microsoft 365 F1、microsoft 365 Business、Microsoft 365 E3/A3/G3、AIP Plan 1 のライセンスを持つユーザーは、AIP プラン1の恩恵を受けることができます。 Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、AIP Plan 2 のライセンスを持つユーザーは、AIP Plan 2 から恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

AIP スキャナー機能は、オンプレミスのファイルリポジトリに存在するファイルを自動的に分類、ラベル付け、保護します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで AIP 機能が有効になっています。 ライセンスを持つユーザーの AIP ポリシーの構成の詳細については、「 [Azure Rights Management をアクティブ化](https://docs.microsoft.com/azure/information-protection/activate-service)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

AIP の機能のポリシー (スキャナー機能を除く) は、特定のグループまたはユーザーに限定できます。レジストリを編集して、ライセンスのないユーザーが AIP 分類またはラベル機能を実行できないようにすることができます。 AIP の展開のスコープを設定する方法については、「 [Azure Information Protection ポリシーの構成](https://docs.microsoft.com/azure/information-protection/configure-policy)」を参照してください。

AIP スキャナー機能の場合、Microsoft はライセンスされていないユーザーにファイル分類、ラベル付け、または保護機能を提供することをコミットしません。 時間の経過と共に、ライセンスチェックまたは対象となるツールが AIP に追加され、スキャナー機能がライセンスユーザーに確実に割り当てられるようになります。

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

Advanced Threat Protection (ATP) は、フィッシングやゼロデイマルウェアなどの高度な攻撃から組織を保護します。 また、潜在的な脅威に対処する方法を特定し、優先度を設定し、推奨事項を提示することにより、さまざまなデータの信号を関連付けて、実用的な洞察を提供します。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office のライセンスユーザー 365 E5/A5/G5、Microsoft 365 E5/A5/G5、microsoft 365 E5/a5/G5 セキュリティ、microsoft 365 Business、および Office 365 ATP プラン1と2は、ATP からメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ATP は、フィッシングやゼロデイマルウェアなどの高度な攻撃からユーザーを保護します。 プラン1およびプラン2で提供されるサービスの完全な一覧については、「 [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで ATP 機能が有効になっています。 ライセンス供与されたユーザーに対して ATP ポリシーを構成する方法については、「 [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ATP の範囲を適用するには、安全なリンクと安全な添付ファイルの展開ポリシーに従います。

- ライセンスを持つユーザーに対して安全なリンクを構成する方法については、「 [Office 365 ATP セーフリンクポリシー](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)をセットアップする」を参照してください。

- ライセンスユーザーに対して安全な添付ファイルを構成する方法については、「 [Office 365 ATP の安全な添付ファイルのポリシー](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)をセットアップする」を参照してください。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) は、Microsoft Cloud App Security の一部であり、機能は Office 365 に制限されており、サードパーティのクラウドアプリおよび IaaS サービスに対して追加のセキュリティを使用することはできません。

OCAS は、組織の生産性を向上させるクラウドアプリやサービスを組織に可視化し、サイバーの脅威を特定して対処する&mdash;洗練された分析を提供し、Office 365 でのデータ転送を制御することができます。

機能を比較するには、「 [Microsoft Cloud App security And Office 365 Cloud App security の相違](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)」を参照してください。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5 のライセンスユーザーは、OCAS から恩恵を受けることができます。

詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

OCAS 検出シャドウ IT は、Office 365 に対して脅威を保護し、Office 365 データにアクセスするためのアクセス許可を持つアプリを制御することができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、OCAS 機能はテナント内のすべてのユーザーに対してテナントレベルで有効になっています。

サービスの構成の詳細については、「 [Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、OCAS 展開を適用して、特定のアプリへのアクセス方法を強制し、Office 365 Cloud App Security によって監視されるユーザーグループを制限することができます。 詳細については、「[スコープ付き展開](https://docs.microsoft.com/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) は、クラウドアプリとサービスを組織に表示し、サイバーの脅威を特定して対処する洗練された分析を提供し、クラウドアプリ間でデータを転送&mdash;する方法を制御できる、クラウドアクセスセキュリティブローカー (casb) ソリューションです。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 の各セキュリティは、MCAS からメリットを得られます。

Azure AD P1 にライセンスを付与されたユーザーは、MCAS の検出機能からメリットを得ることができます。

MCAS の[条件付きアクセスアプリコントロール](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)機能を活用するには、Azure Active Directory P1 に対するライセンスも必要です。これは、enterprise Mobility + security E3/A3/G3、enterprise Mobility + security E5/A5/G5、Microsoft 365 E3/A3/G5、Microsoft 365 E5/A5/G5、および Microsoft 365 E5/A5/セキュリティに含まれます。

[自動ラベル付け](https://docs.microsoft.com/cloud-app-security/data-protection-policies)のメリットを得るために、ユーザーは、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 e5/A5/G5 コンプライアンスに含まれている Azure Information Protection P2 のライセンスを持っている必要があります。

詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

MCAS は、シャドウ IT を検出して評価し、第1およびサードパーティのクラウドアプリでの脅威保護を提供し、最初のおよびサードパーティのクラウドアプリ間で情報を保護します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで MCAS 機能が有効になっています。

ライセンスを持つユーザーに対して Microsoft Cloud App Security ポリシーを構成する方法については、「 [Microsoft Cloud App security の概要](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、サービスで利用できるスコープ付き展開機能を使用して、ライセンスを持つユーザーに MCAS 展開の範囲を設定できます。 詳細については、「[スコープ付き展開](https://docs.microsoft.com/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="office-365-advanced-data-governance"></a>Office 365 アドバンスト データ ガバナンス

Advanced Data ガバナンス (ADG) は、組織が情報ガバナンスの要件をポリシーに適合させることにより、保存と削除を可能にします。 ADG を使用すると、組織は機密情報の種類に基づいてコンテンツを自動的にラベル付けし、そのコンテンツにガバナンスポリシーを適用することができます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、ADG の恩恵を受けられます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ADG を使用すると、ユーザーは特定のデータにラベルを適用して、特定のポリシーを適用したり、コンテンツをレコードとして自動的にラベル付けしたり、完全なレコードプロセスを宣言から廃棄に管理したりできます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで ADG 機能が有効になっています。 ライセンスユーザーの自動ラベル付けとポリシーを適用するように ADG を構成する方法については、「[保持ラベルの概要](https://docs.microsoft.com/office365/securitycompliance/labels)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ADG アイテム保持ポリシーは、自動分類を使用して、特定の場所 (チームサイト、グループサイトなど) のライセンスを持つユーザーに適用できます。 ADG アイテム保持ポリシーの適用手順については、「[組織全体または特定の場所にアイテム保持ポリシーを適用する](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)」を参照してください。

## <a name="advanced-ediscovery"></a>Advanced eDiscovery

Advanced eDiscovery は、企業内の IT および法務部門向けの調査および電子情報開示ソリューションを提供して、Office 365 からエクスポートする前に調査または訴訟に関連するコンテンツを特定、収集、保存、削減、レビューします。bios.

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスは、高度な電子情報開示の恩恵を受けられます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーがケースのデータ保管担当者 (ドキュメントまたは電子ファイルの管理者の制御を持つユーザー) として選択されている場合、高度な電子情報開示によるユーザーの利点があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、高度な電子情報開示機能は、管理者がセキュリティ & コンプライアンスセンターで電子情報開示のアクセス許可を割り当てるときに、テナント内のすべてのユーザーに対してテナントレベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

電子情報開示管理者は、「 [Add 保管担当者 to The Advanced ediscovery case](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)」の説明に従って、高度な電子情報開示の組み込みの保管担当者管理ツールを使用して、特定のユーザーをデータ保管担当者として選択できます。

## <a name="office-365-customer-key"></a>Office 365 の顧客キー

顧客キーを使用して、組織の暗号化キーを制御し、Office 365 を使用して Microsoft のデータセンターで保存されているデータを暗号化するように構成します。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化のレイヤーを追加することができます。 保存データには、Exchange Online と Skype for Business のデータが含まれています。これは、メールボックスや SharePoint Online および OneDrive for business 内のファイルに格納されます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、お客様キーを利用することができます。 顧客キーのすべての利点を得るには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、お客様の組織で提供、管理、管理されている暗号化キーを使用して、アプリケーション層で暗号化されたデータを保存することにより、顧客キーからメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Office 365 顧客キー暗号化キーは、Exchange Online と Skype for business のメールボックス、および SharePoint Online、OneDrive for Business、および Teams の各ファイルに格納されているすべてのデータに対して有効にすることができます。 保存されているデータを暗号化するために Office 365 の顧客キーを構成する方法については、「[顧客キーを使用して office 365 でデータを管理](https://docs.microsoft.com/microsoft-365/compliance/controlling-your-data-using-customer-key)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ライセンスを持つユーザーの Office 365 または Microsoft 365 テナント内のデータに暗号化キーを割り当てるには、顧客キーの暗号化キーの展開手順に従います。

- SharePoint Online、OneDrive for Business、Teams の各ファイルでは、次のように、顧客キーを使用して1つ以上のサイト上のファイルを暗号化できます。 [SharePoint Online と OneDrive for business の顧客キーを設定](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)します。

- Exchange Online と Skype for Business では、以下の説明に従って、顧客キーを使用してメールボックスを暗号化できます。 [Exchange online と skype for business の顧客キーの設定](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

カスタマーロックボックスは、サービス操作の明示的なアクセス承認を提供する機能をお客様に提供することにより、追加の管理層を提供します。 明示的なデータアクセス承認のために手順が実行されていることを実証することにより、お客様のロックボックスは、組織が HIPAA や FEDRAMP などの特定のコンプライアンス義務を満たすのに役立つ場合があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、お客様のロックボックスを利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

カスタマーロックボックスを使用すると、お客様の明示的な承認なしにサービス操作を実行するために、Microsoft のユーザーが自分のコンテンツにアクセスできないようにすることができます。 顧客ロックボックスコンテンツへのアクセスの要求について、顧客を承認ワークフローに取り込みます。 お客様から報告された問題をトラブルシューティングおよび修正するために、Microsoft のエンジニアがサポートプロセスの間に関与している場合があります。 ほとんどの場合、問題は、Microsoft がサービスに対して設定している広範なテレメトリおよびデバッグツールによって解決されます。 しかし、Microsoft のエンジニアにお客様のコンテンツへのアクセスを要求して、根本原因を特定し、問題を解決する必要がある場合があります。 お客様のロックボックスには、エンジニアが承認ワークフローの最後の手順として顧客からのアクセスを要求する必要があります。 これにより、組織では、これらの要求を承認または拒否するオプションが提供されます。これにより、Microsoft のエンジニアが組織のエンドユーザーデータにアクセスできるかどうかを直接制御することができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Microsoft 365 管理センターでカスタマーロックボックスコントロールをオンにすることができます。 詳細については、「 [Office 365 のカスタマーロックボックス](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)」を参照してください。 カスタマーロックボックスがオンになっている場合は、そのコンテンツにアクセスする前に、Microsoft が組織の承認を取得する必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft では、Office 365 組織のユーザーに対するカスタマーロックボックスのアクセス制御の承認要求を提供しています。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

特権アクセス管理 (PAM) は、Office 365 の特権のある管理タスクに対するきめ細かいアクセス制御を提供します。 PAM を有効にした後は、管理者特権のタスクを完了するために、ユーザーは、高いスコープと時間がバインドされた承認ワークフローを使用してジャストインタイムアクセスを要求する必要があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、PAM の恩恵を受けられます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

PAM を有効にすることで、組織はゼロに立った権限で運用できるようになります。 ユーザーは、データへの unfettered アクセスを提供する、独立した管理アクセスから生じる脆弱性に対して、追加された防御層からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで PAM 機能が有効になっています。 PAM ポリシーの構成の詳細については、「 [Office 365 での特権アクセス管理の構成](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

お客様は、承認者グループとアクセスポリシーを使用して、ユーザー単位で PAM を管理することができます。これは、ライセンスを持つユーザーに適用できます。 詳細については、「 [Office 365 での特権アクセス管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)」を参照してください。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online、OneDrive for business のデータ損失防止

Exchange Online、SharePoint Online、OneDrive for Business のデータ損失防止 (DLP) を使用すると、組織は、電子メールとファイル (Microsoft Teams ファイルに格納されているファイルを含む) で機密情報を識別、監視、および自動保護できます。リポジトリ)。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E3/A3/G3、Microsoft 365 Business、Microsoft 365 A1/E3/A3/G3、および Office 365 データ損失防止のライセンスを持つユーザーは、Exchange Online、SharePoint Online、OneDrive for business の DLP からメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

組織の DLP ポリシーに構成されているように、機密情報のメールやファイルが検査されている場合は、Exchange Online、SharePoint Online、および OneDrive for Business の DLP からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Exchange Online の電子メール、SharePoint サイト、および OneDrive アカウントは、これらの DLP 機能の*有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「[データ損失防止の概要](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、[**データ損失防止** > の**場所**] の下にある Office 365 セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Teams チャットおよびチャネルメッセージのデータ損失防止

Teams チャットおよびチャネルメッセージのデータ損失防止 (DLP) を使用すると、組織は、金融情報、個人を特定できる情報、健康関連の情報などの機密情報を含むチャットおよびチャネルメッセージをブロックできます。その他の機密情報。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/a5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスは、Teams のチャットおよびチャネルメッセージに DLP を使用してメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

送信者は、組織の DLP ポリシーで構成されているように、機密性の高い情報があることを調査して、送信したチャットとチャネルメッセージに機密情報を含めることによって得られます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Teams チャットおよびチャネルメッセージは、テナント内のすべてのユーザーについて、これらの DLP 機能の*有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「[データ損失防止の概要](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、[**データ損失防止** > の**場所**] の下にある Office 365 セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。

## <a name="information-barriers"></a>情報障壁

情報障壁は、個人またはグループが相互に通信することを防止するために管理者が構成できるポリシーです。 これは、ある部署が他の部署と共有しないという情報を処理している場合や、グループが外部の連絡先と通信できないようにする必要がある場合に便利です。 情報バリアポリシーでは、検索と検出も禁止されます。 これは、通信しない相手と通信しようとしても、ユーザー選択ウィンドウにそのユーザーが見つからないことを意味します。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、情報の障壁から恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーが他のユーザーとの通信を制限されている場合は、情報バリアの高度なコンプライアンス機能を利用できます。 例:

| シナリオ                                                                                                                                                                                                              | ライセンスを必要とするのはだれですか? |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 2つのグループ (グループ1とグループ 2) は相互に通信できません (つまり、グループ1のユーザーはグループ2ユーザーとの通信を制限され、グループ2ユーザーはグループ1ユーザーとの通信を制限されます。 | グループ1とグループ2の両方のユーザー                    |
| グループ1のユーザーは、会社の他のユーザーとの通信を制限されます。                                                                                                                                       | グループ1のユーザーのみ                                |
| 会社の残りの部分は、グループ1との通信から制限されています。                                                                                                                                                 | グループ1以外のすべてのユーザー                    |
| グループ1ユーザーはグループ2ユーザーとの通信を制限されていますが、グループ2ユーザーはグループ1ユーザーと通信できます。                                                                                              | グループ1のユーザーのみ                                |

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、セキュリティ & コンプライアンスセンターで PowerShell コマンドレットを使用して、情報バリアポリシーを作成および管理します。 情報バリアポリシーを作成するには、管理者に Microsoft 365 Enterprise グローバル管理者、Office 365 グローバル管理者、またはコンプライアンス管理者の役割が割り当てられている必要があります。 既定では、これらのポリシーはテナント内のすべてのユーザーに適用されます。 情報の障壁の詳細については、「 [Microsoft Teams の情報障壁](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、Office 365 セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。 たとえば、すべてのユーザーに Office 365 E3 のライセンスが付与されており、Office 365 Advanced コンプライアンス/E5 のライセンスを持っていない場合は、組織の情報バリアポリシーを作成する必要はありません。 詳細については、「 [Microsoft Teams の情報障壁](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)」を参照してください。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption (OME) は、Azure Rights Management (Azure RMS) で構築され、宛先のメール アドレス (Gmail、Yahoo! Mail、Outlook.com など) に関係なく、暗号化された電子メールを組織内外の宛先に送信できるようにするサービスです。

暗号化メッセージを表示するために、受信者は 1 回限りのパスコードを取得するか、Microsoft アカウントでサインインするか、Office 365 に関連付けられている職場または学校のアカウントでサインインできます。 受信者は暗号化された返事を送信することもできます。 暗号化されたメッセージを表示したり、暗号化された返信を送信するのに、受信者は Office 365 サブスクリプションを必要としません。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E3/A3/G3、Microsoft 365 E3/A3/G3、および Azure Information Protection Plan 1 のライセンスユーザーは、Office 365 Message Encryption を利用することができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

メッセージの送信者は、Office 365 メッセージの暗号化によって提供される機密メールを追加することによって役立ちます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Exchange 管理センターで**メールフロー** > **ルール**の下に Office 365 メッセージ暗号化ポリシーを作成して管理します。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しい Office 365 メッセージ暗号化機能のセットアップの詳細については、「 [365 office の新しいメッセージの暗号化機能をセットアップ](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、ライセンスを持つユーザーにのみ Office 365 メッセージ暗号化のメールフロールールを適用する必要があります。 メールフロールールの定義の詳細については、「 [Office のメールメッセージを暗号化するためのメールフロールールを定義する 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

高度なメッセージ暗号化は、外部の受信者に対してより柔軟な制御と暗号化された電子メールへのアクセスを必要とするコンプライアンス義務を満たすためにお客様を支援します 高度なメッセージ暗号化を使用すると、管理者は機密情報の種類 (個人を識別する情報、財務または正常性 Id など) を検出できる自動ポリシーを使用して、組織外で共有される機密メールを制御することができます。これらのユーザーはキーワードを使用して、セキュリティで保護された web ポータル経由で暗号化された電子メールへのアクセスを有効期限切れにすることで、保護を強化できます。 さらに、管理者は、いつでもアクセスを取り消して、セキュリティで保護された web ポータルを介して外部からアクセスされる暗号化メールを制御できます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスは、高度なメッセージ暗号化による恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

メッセージの送信者は、高度なメッセージ暗号化によって提供される機密メールを追加することによって役立ちます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、メールフロールールの下にある Exchange 管理センターで、高度なメッセージ暗号化ポリシーを作成して管理します。 既定では、これらのルールはテナントのすべてのユーザーに適用されます。 新しいメッセージ暗号化機能のセットアップの詳細については、「 [Office の新しい365メッセージの暗号化機能をセットアップ](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、高度なメッセージ暗号化のメールフロールールをライセンスユーザーにのみ適用する必要があります。 メールフロールールの定義の詳細については、「 [Office のメールメッセージを暗号化するためのメールフロールールを定義する 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="supervision-policies"></a>監督ポリシー

Office 365 の監督ポリシーでは、指定されたレビュー担当者による調査のために従業員の通信を取得できます。 組織内の内部および外部の電子メール、Microsoft Teams、またはサードパーティの通信をキャプチャする特定のポリシーを定義できます。 その後、レビュー担当者がメッセージを調べて、組織のメッセージ標準に準拠していることを確認し、分類型を使用してそれらを解決できます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Office 365 Advanced コンプライアンスは、監督ポリシーからメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、監督ポリシーによって通信を監視することによって、サービスからメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者セキュリティ & コンプライアンスセンターで監督ポリシーを作成します。 これらのポリシーでは、組織内で検討する必要のある通信およびユーザーを定義し、通信で満たす必要のあるカスタム条件を定義し、レビューを実行するユーザーを指定します。
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、監督ポリシーに含める特定のユーザーまたはグループを選択します。 グループを選択するときに、監督ポリシーから除外するグループ内の特定のユーザーを選択することもできます。 監督ポリシーの詳細については、「 [Office 365 の監督ポリシー](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies)」を参照してください。

## <a name="conditional-access-policies"></a>条件付きアクセスポリシー

条件付きアクセスとは、シグナルを取り込んで、意思決定を行い、組織のポリシーを適用するために Azure Active Directory によって使用されるツールです。 条件付きアクセスは、identity 被制御面の中心になります。 最も単純な条件付きアクセスポリシーは、if-then ステートメントです。 ユーザーがリソースにアクセスする場合は、アクションを実行する必要があります。 例: 給与管理者は、給与アプリケーションにアクセスする必要があり、それにアクセスするために多要素認証を実行する必要があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E3、Security E3/A3/G3、Microsoft 365 F1/E3/A3/G3、および Azure Active Directory Premium プラン1のライセンスを持つユーザーは、条件付きアクセスポリシーからメリットを得られます。 Enterprise Mobility + Security E5/A5/G5 のライセンスユーザー、Microsoft 365 E5/A5/G5、Microsoft E5 セキュリティ、および Azure Active Directory Premium プラン2は、Id 保護 (リスクベースの条件付きアクセスポリシー) からメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

セキュリティ運用アナリストおよびセキュリティ担当者は、組織のポリシーをユーザーに適用して、企業のコンテンツへのアクセスを許可する前に、特定の条件を満たす必要があることによってメリットを得ることができます。 エンドユーザーは、組織の資産を保護する一方で、いつでもどこでも自分の作業にアクセスできるという利点があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで条件付きアクセス機能が有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

具体的には、Id 保護と条件付きアクセスの場合、ユーザーはグループに含めるか、条件付きアクセスポリシーに追加する必要があります。 条件付きアクセスポリシーでは、ユーザーとグループの条件は必須です。 ポリシーでは、[**すべてのユーザー** ] または [特定のユーザーとグループ] のどちらかを選択できます。 適切にライセンスされたユーザーとグループのみを選択する必要があります。 詳細については、「 [Azure Active Directory の条件付きアクセスの条件](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)について」を参照してください。

## <a name="advanced-audit"></a>詳細な監査

Microsoft 365 の高度な監査では、ユーザーと管理者のアクティビティについて1年間の監査ログの保持が提供され、他の Microsoft 365 サービスの監査ログの保持を管理するためのカスタム監査ログ保持ポリシーを作成する機能が提供されます。 また、調査のための重要なイベントへのアクセス、および Office 365 Management Activity API への高帯域幅アクセスを提供します。 詳細については、「 [Microsoft 365 の詳細な監査](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)」を参照してください。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンスは、高度な監査からメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

Microsoft 365 サービスのユーザーアクティビティに関連する監査レコードは、最大1年間保持できるため、ユーザーは高度な監査からメリットを得られます。 さらに、ユーザーのメールボックス内のアイテムにアクセスまたは読み取りが行われたときなど、高価値の監査イベントがログに記録されます。 詳細については、「[高価値の監査イベント](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit#high-value-audit-events)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Office 365 または Microsoft 365 E5 サブスクリプションを持つすべての組織のために、テナントレベルで Advanced Audit が有効になっており、アクティビティ (適切なライセンスを持つユーザーによって実行される) の監査ログの1年間の保持が自動的に提供されます。Azure Active Directory、Exchange、および SharePoint。 さらに、組織は監査ログの保持ポリシーを使用して、他の Microsoft 365 サービスのアクティビティによって生成された監査レコードの保持期間を管理できます。 詳細については、「[監査ログ保持ポリシーを管理する](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

監査ログの1年間の保持、および重要なイベントの監査は、適切なライセンスを持つユーザーにのみ適用されます。 さらに、管理者は監査ログ保持ポリシーを使用して、特定のユーザーの監査ログの保存期間を短くすることができます。
