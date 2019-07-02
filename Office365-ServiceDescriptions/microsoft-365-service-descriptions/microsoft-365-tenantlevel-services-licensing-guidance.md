---
title: Microsoft 365 テナントレベルサービスライセンスガイダンス
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
description: この記事では、Microsoft 365 テナントレベルサービスのライセンスに関するガイダンスを提供します。これは、ライセンスのないアクセスによるサービスの中断の可能性を回避するために役立ちます。
ms.openlocfilehash: dea49f7c6ea3a0082968335586e146a33d4a76cc
ms.sourcegitcommit: 983c4e2b50177883d9369f12b43e09d51e1e5f28
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2019
ms.locfileid: "35411462"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 テナントレベルサービスライセンスガイダンス

この記事では、テナント内のすべてのユーザーに対して、テナント内&mdash;のすべてのユーザー (スタンドアロンまたは Office 365 または Microsoft 365 プランの一部として&mdash;) を購入したときに、テナントレベルのサービスがオンラインサービスになっています。 一部のライセンスのないユーザーは技術的にサービスにアクセスできる可能性がありますが、サービスの利用を目的としているユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナントサービスは、現在、特定のユーザーに対する利点を制限することはできません。 ライセンスを付与されたユーザーにサービスのメリットを制限するための取り組みを実施する必要があります。 これにより、ターゲット機能が使用可能になった場合に、サービスが組織に及ぼす影響を回避できます。

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure active Directory Id 保護 (AYOUR p) は、組織の id に影響を及ぼす可能性のある脆弱性を検出し、検出された疑わしいに対する自動応答を構成できる、Azure Active Directory Premium P2 プランの機能です。組織の id に関連するアクションを確認し、疑わしいインシデントを調査して、それらを解決するための適切な処置を講じます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 セキュリティ、および Azure Active Directory Premium プラン2は、Aお役に立てます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOps アナリストおよびセキュリティ担当者は、コンピューターの学習アルゴリズムに基づいてフラグが設定されたユーザーとリスクイベントを統合して表示するのに役立ちます。 エンドユーザーは、リスクベースの条件付きアクセスと、脆弱性に対処することによって提供されるセキュリティ強化によって提供される自動保護からメリットを得られます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで有効になっています。 Aウン p の構成の詳細については、「 [Azure Active Directory Id 保護を有効にする](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、パスワードのリセットのレベルを定義するリスクポリシーを割り当て、ライセンスされたユーザーのみにアクセスを許可することによって、その範囲を設定できます。 展開のスコープを設定する方法については、「[サインインリスクポリシーを構成](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)する」を参照してください。

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure Advanced Threat Protection (ATP) は、複数の種類の高度なターゲット化されたサイバー攻撃および insider の脅威からエンタープライズハイブリッド環境を保護するために役立つクラウドサービスです。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 セキュリティ、および Azure Advanced Threat Protection を使用すると、Azure ATP からメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOp アナリストおよびセキュリティ担当者は、Azure ATP の機能を利用して、高度な脅威、侵害された id、および悪意のある insider 操作を検出し、調査することができます。 Azure ATP がデータを監視することにより、エンドユーザーはメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Azure ATP 機能がテナントレベルで有効になっています。 Azure ATP の構成の詳細については、「 [AZURE atp インスタンスを作成](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft は、ライセンスが付与されていないユーザーに脅威検出機能を提供することを確約することはありません。 時間の経過とともに、ライセンスチェックまたは対象となるツールが Azure ATP に追加され、Azure ATP 機能がライセンスユーザーにのみ適用されるようになります。

## <a name="azure-information-protection"></a>Azure Information Protection

Azure Information Protection (AIP) は、組織が機密ドキュメントや電子メールを検出、分類、ラベル付け、保護するのに役立ちます。 管理者は、ラベルを自動的に適用するルールと条件を定義できます。ユーザーはラベルを手動で適用する&mdash;ことも、ラベルの適用についてユーザーに推奨事項を与える場合は、2つの組み合わせを使用することもできます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Microsoft 365 F1、Microsoft 365 E3、AIP Plan 1 のライセンスを持つユーザーは、AIP プラン1の恩恵を受けることができます。 Microsoft 365 E5 のライセンスユーザー、Microsoft 365 E5 コンプライアンス、および AIP Plan 2 は AIP Plan 2 からメリットを得られます。

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

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 セキュリティ、Microsoft 365 Business、および Office 365 ATP プラン1と2は、ATP によってメリットを得ることができます。

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

Office 365 E5 にライセンスを付与されたユーザーは、OCAS の恩恵を受けることができます。

詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

OCAS 検出シャドウ IT は、Office 365 に対して脅威を保護し、Office 365 データにアクセスするためのアクセス許可を持つアプリを制御することができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、OCAS 機能はテナント内のすべてのユーザーに対してテナントレベルで有効になっています。

サービスの構成の詳細については、「 [Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、OCAS 展開を適用して、特定のアプリへのアクセス方法を強制し、Office 365 Cloud App Security によって監視されるユーザーグループを制限することができます。 詳細については、「[スコープ付き展開](https://docs.microsoft.com/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) は、組織がクラウドアプリやサービスを使用できるようにするクラウドアクセスセキュリティブローカー (CASB) ソリューションで、サイバーの脅威を識別して対処するための高度な分析を提供し、データの管理を可能にします。クラウド&mdash;アプリ間を移動します。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

MCAS のライセンスユーザー、Enterprise Mobility + Security E5、Microsoft 365 E5、Microsoft 365 E5 セキュリティは、MCAS から恩恵を受けることができます。

Azure AD P1 にライセンスを付与されたユーザーは、MCAS の検出機能からメリットを得ることができます。

MCAS の[条件付きアクセスアプリコントロール](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad)機能を利用するには、enterprise Mobility + Security E3、enterprise Mobility + Security E5、Microsoft 365 E3、microsoft 365 に含まれている Azure Active Directory P1 のユーザーにもライセンスを付与する必要があります。E5、Microsoft 365 E5 セキュリティ。

[自動ラベル付け](https://docs.microsoft.com/cloud-app-security/data-protection-policies)のメリットを得るには、Enterprise Mobility + Security E5、Microsoft 365 E5、Microsoft 365 e5 コンプライアンスに含まれている Azure Information Protection P2 のライセンスをユーザーに付与する必要があります。

詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](http://www.aka.ms/mcaslicensing)」を参照してください。

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

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、ADG の恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ADG を使用すると、ユーザーは特定のデータにラベルを適用して、特定のポリシーを適用したり、コンテンツをレコードとして自動的にラベル付けしたり、完全なレコードプロセスを宣言から廃棄に管理したりできます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで ADG 機能が有効になっています。 ライセンスユーザーの自動ラベル付けとポリシーを適用するように ADG を構成する方法については、「[保持ラベルの概要](https://docs.microsoft.com/office365/securitycompliance/labels)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ADG アイテム保持ポリシーは、自動分類を使用して、特定の場所 (チームサイト、グループサイトなど) のライセンスを持つユーザーに適用できます。 ADG アイテム保持ポリシーの適用手順については、「[組織全体または特定の場所にアイテム保持ポリシーを適用する](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)」を参照してください。

## <a name="office-365-advanced-ediscovery"></a>Office 365 Advanced eDiscovery

上級電子情報開示 Office 365 をエクスポートする前に、組織内の IT および法務部門に対して、調査や訴訟に関連するコンテンツを特定、収集、保存、削減、確認するための調査および電子情報開示ソリューションを提供します。bios.

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced advanced コンプライアンスは、高度な電子情報開示からメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

訴訟や調査の一環として、コンテンツが保留中になっている場合は、Advanced eDiscovery からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、高度な電子情報開示機能は、管理者がセキュリティ & コンプライアンスセンターで電子情報開示のアクセス許可を割り当てるときに、テナント内のすべてのユーザーに対してテナントレベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

組織は、ユーザーごとに高度な電子情報開示を管理し、高度な電子情報開示ケースにユーザーを追加したり、電子情報開示のアクセス許可によって共有の場所に対する編集アクセス権を持つユーザーに提供したりすることができます。 詳細な電子情報開示のアクセス許可をライセンスユーザーに適用する方法については、「[セキュリティ & コンプライアンスセンターで電子情報開示のアクセス許可を割り当てる](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions)」を参照してください。

## <a name="office-365-customer-key"></a>Office 365 の顧客キー

顧客キーを使用して、組織の暗号化キーを制御し、Office 365 を使用して Microsoft のデータセンターで保存されているデータを暗号化するように構成します。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化のレイヤーを追加することができます。 保存データには、Exchange Online と Skype for Business のデータが含まれています。これは、メールボックスや SharePoint Online および OneDrive for business 内のファイルに格納されます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、顧客キーによる恩恵を受けることができます。 顧客キーのすべての利点を得るには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、お客様の組織で提供、管理、管理されている暗号化キーを使用して、アプリケーション層で暗号化されたデータを保存することにより、顧客キーからメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Office 365 顧客キー暗号化キーは、Exchange Online と Skype for business のメールボックス、および SharePoint Online と OneDrive for business のファイルに格納されているすべてのデータに対して有効にすることができます。 保存されているデータを暗号化するために Office 365 の顧客キーを構成する方法については、「[顧客キーを使用して office 365 でデータを管理](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ライセンスを持つユーザーの Office 365 または Microsoft 365 テナント内のデータに暗号化キーを割り当てるには、顧客キーの暗号化キー展開ポリシーに従います。

  - SharePoint Online では、以下の説明に従って、1つ以上のサイト上のファイルを顧客キーを使用して暗号化できます。 [Sharepoint online および OneDrive for business の顧客キーを設定](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)します。

  - Exchange Online と Skype for business Online では、以下の説明に従って、顧客キーを使用してメールボックスを暗号化できます。 [Exchange online と skype for business の顧客キーの設定](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

カスタマーロックボックスは、サービス操作の明示的なアクセス承認を提供する機能をお客様に提供することにより、追加の管理層を提供します。 明示的なデータアクセス承認のために手順が実行されていることを実証することにより、お客様のロックボックスは、組織が HIPAA や FEDRAMP などの特定のコンプライアンス義務を満たすのに役立つ場合があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、お客様のロックボックスからメリットを得ることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

カスタマーロックボックスを使用すると、お客様の明示的な承認なしにサービス操作を実行するために、Microsoft のユーザーが自分のコンテンツにアクセスできないようにすることができます。 顧客ロックボックスコンテンツへのアクセスの要求について、顧客を承認ワークフローに取り込みます。 お客様から報告された問題をトラブルシューティングおよび修正するために、Microsoft のエンジニアがサポートプロセスの間に関与している場合があります。 ほとんどの場合、問題は、Microsoft がサービスに対して設定している広範なテレメトリおよびデバッグツールによって解決されます。 しかし、Microsoft のエンジニアにお客様のコンテンツへのアクセスを要求して、根本原因を特定し、問題を解決する必要がある場合があります。 お客様のロックボックスには、エンジニアが承認ワークフローの最後の手順として顧客からのアクセスを要求する必要があります。 これにより、組織では、これらの要求を承認または拒否するオプションが提供されます。これにより、Microsoft のエンジニアが組織のエンドユーザーデータにアクセスできるかどうかを直接制御することができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Microsoft 365 管理センターでカスタマーロックボックスコントロールをオンにすることができます。 詳細については、「 [Office 365 のカスタマーロックボックス](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)」を参照してください。 カスタマーロックボックスがオンになっている場合は、そのコンテンツにアクセスする前に、Microsoft が組織の承認を取得する必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft は、ライセンスが付与されていないユーザーに対する、カスタマーロックボックスへのアクセス制御の承認要求の提供にはコミットしません。 時間の経過とともに、ライセンスチェックまたは対象となるツールがカスタマーロックボックスに追加され、お客様のロックボックスがライセンスユーザーに確実に割り当てられるようになります。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

特権アクセス管理 (PAM) は、Office 365 の特権のある管理タスクに対するきめ細かいアクセス制御を提供します。 特権アクセス管理を有効にした後は、管理者特権のタスクを完了するために、ユーザーは、高いスコープと時間がバインドされた承認ワークフローを使用してジャストインタイムアクセスを要求する必要があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは PAM の恩恵を受けます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

PAM を有効にすることで、組織はゼロに立った権限で運用できるようになります。 ユーザーは、データへの unfettered アクセスを提供する、独立した管理アクセスから生じる脆弱性に対して、追加された防御層からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで PAM 機能が有効になっています。 PAM ポリシーの構成の詳細については、「 [Office 365 での特権アクセス管理の構成](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

お客様は、承認者グループとアクセスポリシーを使用して、ユーザー単位で PAM を管理することができます。これは、ライセンスを持つユーザーに適用できます。 詳細については、「 [Office 365 での特権アクセス管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)」を参照してください。

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online、OneDrive for business のデータ損失防止

Exchange Online、SharePoint Online、OneDrive for Business のデータ損失防止 (DLP) を使用すると、組織は、電子メールとファイル (Microsoft Teams ファイルに格納されているファイルを含む) で機密情報を識別、監視、および自動保護できます。リポジトリ)。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E3、Microsoft 365 E3、および Office 365 データ損失防止のライセンスを持つユーザーは、Exchange Online、SharePoint Online、OneDrive for Business の DLP から恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

組織の DLP ポリシーに構成されているように、機密情報のメールやファイルが検査されている場合は、Exchange Online、SharePoint Online、および OneDrive for Business の DLP からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Exchange Online の電子メール、SharePoint サイト、および OneDrive アカウントは、これらの DLP 機能の*有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「[データ損失防止の概要](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、[**データ損失防止** > の**場所**] の下にある Office 365 セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。

## <a name="data-loss-prevention-for-teams-chat-and-channel-conversations"></a>Teams チャットおよびチャネル会話のデータ損失防止

Teams チャットおよびチャネル会話のデータ損失防止 (DLP) を使用すると、組織は、金融情報、個人を特定する情報などの機密情報を含むチャットおよびチャネル会話のメッセージをブロックできます。正常性に関する情報、またはその他の機密情報。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、Teams のチャットとチャネルの会話において DLP の恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

送信者は、組織の DLP ポリシーに構成されているように、機密性の高い情報を検査して機密情報を受信することで、機密性の高い情報を得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Teams のチャットとチャネルの会話は、テナント内のすべてのユーザーについて、これらの DLP 機能の*有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「[データ損失防止の概要](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、[**データ損失防止** > の**場所**] の下にある Office 365 セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。

## <a name="information-barriers"></a>情報の障壁

情報障壁は、個人またはグループが相互に通信することを防止するために管理者が構成できるポリシーです。 これは、ある部署が他の部署と共有しないという情報を処理している場合や、グループが外部の連絡先と通信できないようにする必要がある場合に便利です。 情報バリアポリシーでは、検索と検出も禁止されます。 これは、通信しない相手と通信しようとしても、ユーザー選択ウィンドウにそのユーザーが見つからないことを意味します。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、情報の障壁からメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーが他のユーザーとの通信を制限されている場合は、情報バリアの高度なコンプライアンス機能を利用できます。 次に例を示します。

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

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

高度なメッセージ暗号化は、外部の受信者に対してより柔軟な制御と暗号化された電子メールへのアクセスを必要とするコンプライアンス義務を満たすためにお客様を支援します 高度なメッセージ暗号化を使用すると、管理者は機密情報の種類 (個人を識別する情報、財務または正常性 Id など) を検出できる自動ポリシーを使用して、組織外で共有される機密メールを制御することができます。これらのユーザーはキーワードを使用して、セキュリティで保護された web ポータル経由で暗号化された電子メールへのアクセスを有効期限切れにすることで、保護を強化できます。 さらに、管理者は、いつでもアクセスを取り消して、セキュリティで保護された web ポータルを介して外部からアクセスされる暗号化メールを制御できます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Office 365 Advanced コンプライアンスは、高度なメッセージ暗号化の恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

メッセージの送信者は、高度なメッセージ暗号化によって提供される機密メールを追加することによって役立ちます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、メールフロールールの下にある Exchange 管理センターで、高度なメッセージ暗号化ポリシーを作成して管理します。 既定では、これらのルールはテナントのすべてのユーザーに適用されます。 新しいメッセージ暗号化機能のセットアップの詳細については、「 [Office の新しい365メッセージの暗号化機能をセットアップ](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、高度なメッセージ暗号化のメールフロールールをライセンスユーザーにのみ適用する必要があります。 メールフロールールの定義の詳細については、「 [Office のメールメッセージを暗号化するためのメールフロールールを定義する 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。
