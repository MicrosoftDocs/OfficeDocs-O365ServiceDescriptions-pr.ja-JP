---
title: セキュリティとコンプライアンスに関する Microsoft 365 ライセンス &ガイダンス
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、ライセンスのないアクセスによるサービスの中断を回避するために、Microsoft 365 コンプライアンスのライセンス ガイダンスを提供します。
ms.openlocfilehash: bceb0f3648aac36f5e748886240ae3594eac7617
ms.sourcegitcommit: bd0cf8920c64e171967d7dd61b7f988bd093c073
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/02/2021
ms.locfileid: "50080283"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>セキュリティとコンプライアンスに関する Microsoft 365 ライセンス &ガイダンス

この記事の目的上、テナント レベルのサービスは、テナント内の任意のユーザー (スタンドアロンまたは &mdash; Office 365 または Microsoft 365 プランの一部として) を購入すると、テナント内のすべてのユーザーに対して一部または完全にアクティブ化されるオンライン サービスです。 &mdash; 一部のライセンスのないユーザーは技術的にサービスにアクセスできる場合があります。ただし、サービスの恩恵を受けるユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナント サービスでは、現在、特定のユーザーにメリットを制限できません。 サービス特典をライセンスユーザーに限定する取り組みを行う必要があります。 これにより、ターゲット設定機能が利用可能な場合に、組織のサービスが中断される可能性を回避できます。

2020 年 4 月 1 日現在の Microsoft 365 コンプライアンス機能の恩恵を受けるユーザーにライセンスを提供するためのオプションを確認するには、詳細な Microsoft 365 コンプライアンス ライセンス比較をダウンロードしてください。 [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  | [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection は、Azure Active Directory Premium P2 プランの機能です。これにより、組織の ID に影響を与える可能性のある脆弱性を検出し、組織の ID に関連する疑わしいアクションを検出するための自動応答を構成し、疑わしいインシデントを調査し、それらを解決するための適切なアクションを実行できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOps アナリストとセキュリティ担当者は、フラグ付きユーザーとリスク イベントを機械学習アルゴリズムに基づいて統合して表示できます。 エンド ユーザーは、リスクベースの条件付きアクセスによって提供される自動保護と、脆弱性に対応することで提供される強化されたセキュリティの恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 Security、Azure Active Directory Premium プラン 2 は、Azure Active Directory Identity Protection の恩恵を受ける権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Azure AD Identity Protection 機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 Azure AD Identity Protection の詳細については [、「Identity Protection とは」を参照してください。](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、パスワードのリセットのレベルを定義するリスク ポリシーを割り当て、ライセンスユーザーにのみアクセスを許可することで、Azure AD Identity Protection のスコープを設定できます。 Azure AD Identity Protection の展開をスコープ設定する方法については、「リスク ポリシーを構成および有効化する方法 [」を参照してください](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)。

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance を使用すると、セキュリティと従業員の生産性に対する組織の必要性と、適切なプロセスと可視性のバランスを取る必要があります。 権利管理、アクセス レビュー、特権 ID 管理、利用規約ポリシーを使用して、適切なユーザーが適切なリソースに適切なアクセス権を持っている必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Azure Active Directory Identity Governance は、1 つのアクセス パッケージでアプリ、グループ、Microsoft Teams へのアクセスを要求しやすくすることで、ユーザーの生産性を向上させます。 ユーザーは、管理者が関与することなく、承認者として構成できます。 アクセス レビューでは、ユーザーはグループのメンバーシップを確認し、スマートな推奨事項を使用して定期的にアクションを実行できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 Security、Azure Active Directory Premium プラン 2 は、Azure Active Directory Identity Governance の恩恵を受ける権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Azure AD Id ガバナンス機能はテナント レベルで有効になりますが、ユーザーごとに実装されます。 Azure AD Identity Governance の詳細については [、「Azure AD Identity Governance とは」を参照してください。](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、アクセス パッケージ、アクセス レビュー、または特権 ID 管理をライセンス ユーザーにのみ割り当て、Azure AD Identity Governance のスコープを設定できます。 Azure AD Identity Governance の展開をスコープ設定する方法については、以下を参照してください。

- [Azure ADの権利管理ライセンス要件](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD アクセス レビュー ライセンス要件](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Privileged Identity Management を使用するライセンス要件](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (旧 Azure Advanced Threat Protection) は、複数の種類の高度な標的型サイバー攻撃やインサイダー脅威からエンタープライズ ハイブリッド環境を保護するクラウド サービスです。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOp アナリストとセキュリティ専門家は、高度な脅威、侵害された ID、悪意のあるインサイダーアクションを検出して調査する Microsoft Defender for Identity の機能を利用できます。 エンド ユーザーは、Microsoft Defender が ID 用にデータを監視することでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 Security、および Microsoft Defender for Identity for Users は、Id 用 Microsoft Defender のメリットを得る権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Microsoft Defender for Identity 機能はテナント内のすべてのユーザーのテナント レベルで有効になっています。 Azure ATP の構成の詳細については、「Id インスタンス用に Microsoft Defender を作成する [」を参照してください](https://docs.microsoft.com/defender-for-identity/install-step1)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

現在、Id サービス用 Microsoft Defender は、特定のユーザーに機能を制限する機能はありません。 特典を受ける予定のすべてのユーザーにライセンスを割り当てなければならない。

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Microsoft Defender for Office 365 (旧 Office 365 Advanced Threat Protection) は、フィッシングやゼロデイ マルウェアなどの高度な攻撃から組織を保護します。 Microsoft Defender for Office 365 は、さまざまなデータからのシグナルを関連付け、潜在的な脅威に対処する方法を特定、優先順位付け、推奨事項を提供することで、操作可能な分析情報も提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft Defender for Office 365 は、フィッシングやゼロデイ マルウェアなどの高度な攻撃からユーザーを保護します。 プラン 1 とプラン 2 で提供されるサービスの完全な一覧については [、Microsoft Defender for Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)をご覧ください。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか? 

microsoft Defender for Office 365 Plans 1 and 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, and Microsoft 365 Business Premium は、ユーザーに Office 365 用 Microsoft Defender のメリットを提供する権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Microsoft Defender for Office 365 の機能は、テナント内のすべてのユーザーのテナント レベルで有効になっています。 ライセンスを取得したユーザーの Office 365 ポリシー用に Microsoft Defender を構成する方法については [、「Microsoft Defender for Office 365」](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Microsoft Defender のスコープを Office 365 に設定するには、安全なリンクと安全な添付ファイルの展開ポリシーに従います。

- ライセンスを取得したユーザーの安全なリンクを構成する方法については [、「Microsoft Defender for Office 365」](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)を参照してください。

- ライセンスされたユーザーの安全な添付ファイルを構成する方法については [、「Microsoft Defender](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)で安全な添付ファイルを構成する」をOfficeしてください。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) は Microsoft Cloud App Security のサブセットであり、機能は Office 365 に制限され、サード パーティ製のクラウド アプリと IaaS サービスに対する追加のセキュリティは必要とされます。

OCAS を使用すると、組織は生産性クラウド アプリとサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、データが Office 365 全体を移動する方法を制御できます。 &mdash;

機能を比較するには [、「Microsoft Cloud App Security と Office 365 Cloud App Security の違い」を参照してください](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

OCAS はシャドウ IT を検出し、Office 365 全体の脅威保護を提供し、データにアクセスするアクセス許可を持つアプリを制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Office 365 E5/A3/A5/G5 は、ユーザーに OCAS の恩恵を受ける権利を提供します。
詳細については [、Microsoft Cloud App Security Licensing データシートを参照してください](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、OCAS 機能はテナント内のすべてのユーザーのテナント レベルで有効になっています。

サービスの構成の詳細については、「Cloud App Security の基本的 [なセットアップ」を参照してください](https://docs.microsoft.com/cloud-app-security/general-setup)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は OCAS 展開のスコープを設定して、特定のアプリへのアクセス方法を適用し、Office 365 Cloud App Security によって監視されるユーザー グループを制限できます。 詳細については、「スコープ指定された [展開」を参照してください](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) はクラウド アクセス セキュリティ ブローカー (CASB) ソリューションで、組織はクラウド アプリとサービスを可視化し、サイバー脅威を特定して対処するための高度な分析を提供し、データがクラウド アプリ間を移動する方法を制御できます。 &mdash;

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

MCAS はシャドウ IT を検出して評価し、ファースト パーティとサード パーティのクラウド アプリ間で脅威保護を提供し、ファースト パーティとサード パーティのクラウド アプリ間で情報を保護します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、Microsoft 365 E5/A5/G5 Compliance、Microsoft 365 Information Protection and Governance は、MCAS のメリットをユーザーに提供します。

Azure AD P1 は、MCAS の検出機能を利用する権限をユーザーに提供します。

MCAS の条件付きアクセス アプリ制御機能を利用するには、Enterprise Mobility + Security E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E3/A3/G3、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 セキュリティに含まれる Azure Active Directory P1 のライセンスも必要です。

クライアント側の自動ラベル付けを利用するには、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、および Microsoft 365 Information Protection and Governance に含まれる Azure Information Protection P2 のライセンスがユーザーに必要です。

> [!NOTE]
> サーバー側の自動ラベル付けには、365 Office - プレミアム ライセンス (または) の情報保護が `MIP_S_CLP2` 必要です `efb0351d-3b08-4503-993d-383af8de41e3` 。 リファレンスについては、「ライセンス [の製品名とサービス プラン識別子」を参照してください](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-service-plan-reference)。

詳細については [、Microsoft Cloud App Security Licensing データシートを参照してください](https://www.aka.ms/mcaslicensing)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、MCAS 機能はテナント内のすべてのユーザーのテナント レベルで有効になっています。

ライセンスを取得したユーザー向け Microsoft Cloud App Security ポリシーの構成については、「Microsoft Cloud App Security overview」 [を参照してください](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、サービスで利用できるスコープ指定された展開機能を使用して、MCAS 展開をライセンスされたユーザーに範囲指定できます。 詳細については、「スコープ指定された [展開」を参照してください](https://docs.microsoft.com/cloud-app-security/scoped-deployment)。

## <a name="compliance-manager"></a>コンプライアンス マネージャー

コンプライアンス マネージャーを使用して、コンプライアンスを簡素化し、リスクを軽減します。 コンプライアンス マネージャーは、組織が規制、標準、会社のポリシー、その他の必要なコントロール フレームワークの要件を満たすのに役立ちます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

コンプライアンス マネージャー サービスのユーザーに対する利点を次に示します。

- 複雑な規制、標準、会社のポリシー、その他の必要なコントロール フレームワークを単純な言語に変換します。
- 独自のコンプライアンス ニーズを満たすために、組み込み可能な評価とカスタム評価の膨大なライブラリへのアクセスを提供します。
- 規制コントロールを推奨される改善アクションにマップする
- 規制要件を満たすためにソリューションを実装する方法に関するステップ バイ ステップのガイダンスを提供します。
- ユーザーが各アクションにスコアを関連付け、組織のコンプライアンスに最も大きな影響を与えるアクションに優先順位を付けるのに役立ちます

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

E1 ライセンスと E3 ライセンスをお持ちのお客様は、既定のデータ保護基準評価にのみアクセスできます。 Office 365 E5/A5 ライセンスと Microsoft 365 E5/A5 ライセンス (コンプライアンス、情報保護ガバナンス、電子情報開示と監査 SKU を含む) をお持ちのお客様は、データ保護ベースライン &amp; 、GDPR、NIST 800-53、ISO 27001 の標準評価にアクセスできます。 カスタム評価機能とプレミアム評価は、365 E5/A5 Office Microsoft 365 E5/A5 のお客様向けに予約されています。 プレミアム評価は、2021 年上半期から VL、CSP、および WebDirect を通じて購入できます。 

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

コンプライアンス マネージャーは、テナントに対して既定でプロビジョニングされます。 管理者は、組織内の管理者以外のユーザーがコンプライアンス マネージャーの使用を開始できるよう、ユーザーのアクセス許可を設定し、役割を割り当てます。 詳細については、「コンプライアンス マネージャーの使用を開始する: ユーザーのアクセス許可 [を設定し、役割を割り当てる」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

コンプライアンス マネージャーへのアクセスは、ユーザーのアクセス許可を設定し、ロールを割り当てによって制御されます。 詳細については、「コンプライアンス マネージャーの使用を開始する: ユーザーのアクセス許可 [を設定し、ロールを割り当てる」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)。

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender for Endpoint

Microsoft Defender for Endpoint (旧 Microsoft Defender ATP) は、リスクベースの脆弱性管理と評価を含むエンドポイント セキュリティ ソリューションです。攻撃表面の縮小機能動作ベースとクラウドベースの次世代の保護エンドポイントの検出と応答 (EDR)自動調査と修復および管理されたハンティング サービス。 詳 [しくは、Microsoft Defender for Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) のページをご覧ください。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Windows 10 Enterprise E5、Windows 10 Education A5、Microsoft 365 E5 (M365 E5) のライセンスを持つユーザーは、Windows 10 Enterprise E5、Microsoft 365 E5 Security、Microsoft 365 A5 (M365 A5) を含む Microsoft Defender for Endpoint を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

SecOps アナリストとセキュリティ担当者は、Microsoft Defender for Endpoint のエンドポイント セキュリティ機能を活用して、予防的な保護、侵害後の検出、自動調査、高度な脅威への対応を行います。 エンド ユーザーは、Microsoft Defender for Endpoint によって悪意のあるイベントを監視することでメリットを得る。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Microsoft Defender for Endpoint の機能は、テナント内のすべてのユーザーのテナント レベルで有効になっています。 展開の詳細については、「展開 [フェーズ」を参照してください](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Microsoft Defender for Endpoint 管理者は、役割ベースのアクセス制御 (RBAC) を使用してセキュリティ運用チーム内に役割とグループを作成し、Microsoft Defender セキュリティ センターへの適切なアクセスを許可できます。 詳細については、「役割ベースのアクセス [制御を使用したポータル アクセスの管理」を参照してください](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)。

## <a name="information-protection"></a>情報保護

情報保護は、組織が機密性の高いドキュメントやメールを検出、分類、ラベル付け、保護するのに役立ちます。 管理者は、ラベルを自動的に適用するルールと条件を定義したり、ユーザーが手動でラベルを適用したり、2 つの組み合わせを使用してラベルの適用に関する推奨事項をユーザーに提供したりすることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、機密ラベルを手動でコンテンツに適用したり、コンテンツを自動的に分類したりすることでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5/E3/G3/F3/F1/Business Premium、Enterprise Mobility + Security F3/E3/E5、Office 365 E5/A5/E3/A3/F3、AIP プラン 1、および AIP プラン 2 は、ユーザーに手動の機秘ラベル付けによるメリットを提供する権限を提供します。

Microsoft 365 E5/A5/G5/E3/A3/F3/F3/Business Premium、Enterprise Mobility + Security F3/E3/E5、AIP プラン 1、および AIP プラン 2 は、Power BI で機度ラベルを適用および表示し、Power BI から Excel、PowerPoint、PDF にエクスポートするときにデータを保護する権限をユーザーに提供します。 

> [!NOTE]
> Power BI は Microsoft 365 E5/A5/G5 に含まれています。その他のすべてのプランでは、Power BI に個別にライセンスを与えなければならない。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 情報保護およびガバナンス、Office 365 E5、Office 365 Advanced Compliance、Enterprise Mobility + Security E5、および AIP プラン 2 は、自動機秘ラベル付けによるメリットをユーザーに提供します。

ライセンス別の特定の権利については、詳細な Microsoft 365 コンプライアンス ライセンスの比較を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)機械学習 (トレーニング可能な分類子) に基づく自動分類に対する権限は含められない。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、情報保護機能はテナント内のすべてのユーザーのテナント レベルで有効になっています。 ライセンスを持つユーザーのポリシーの構成については、「Azure Rights Management のアクティブ化」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

AIP スキャナー機能を使用する場合を除き、ポリシーを特定のグループに範囲指定したり、ユーザーやレジストリを編集して、ライセンスのないユーザーが分類機能やラベル付け機能を実行したりすることはできません。 AIP 展開をスコープ設定する方法については、「Azure Information Protection ポリシーの構成」 [を参照してください](https://docs.microsoft.com/azure/information-protection/configure-policy)。

AIP スキャナー機能の場合、Microsoft はライセンスを取得していないユーザーにファイル分類、ラベル付け、または保護機能を提供するとはコミットしていない。

## <a name="information-governance"></a>情報ガバナンス

情報ガバナンスは、組織がデータの検出、分類、ラベル付け、管理を通じてリスクを管理するのに役立ちます。 情報ガバナンスにより、組織はビジネスおよび規制要件を満たすだけでなく、Microsoft 365 およびサード パーティのデータ全体で保持および削除機能を提供することで攻撃の表面を減らします。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、特定のポリシーと規制を維持するために保持目的のデータを分類できるメリットがあります。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 F3/Business Premium、Office 365 E1/A1/F3、およびスタンドアロンの Exchange プランは、メールボックス データにレコード以外の保持ラベルを手動で適用するメリットをユーザーに提供します。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3、スタンドアロンの SharePoint プランは、SharePoint または OneDrive のファイルにレコード以外の保持ラベルを手動で適用するメリットをユーザーに提供します。 

Microsoft 365 E5/A5/E3/A3/Business Premium、Office 365 E5/A5/E3/A3、Exchange プラン 2、および Exchange Online Archiving は、基本的な組織全体または場所全体のメールボックス保持ポリシーを利用したり、レコード以外の保持ラベルをメールボックス データに手動で適用したりする権限をユーザーに提供します。

Microsoft 365 E5/A5/E3/A3、Office 365 E5/A5/E3/A3、および SharePoint プラン 2 は、基本的な SharePoint または OneDrive アイテム保持ポリシーを利用したり、レコード以外の保持ラベルを SharePoint または OneDrive のファイルに手動で適用したりする権限をユーザーに提供します。

Microsoft 365 E5/A5/E3/A3 および Office 365 E5/A5/E3/A3 は、Teams アイテム保持ポリシーの恩恵を受ける権限をユーザーに提供します。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、 Office 365 Advanced Compliance は、保持ラベルまたはポリシーの自動適用、既定の保持ラベルまたはポリシーの適用、カスタム イベントに基づく保持ラベルの保持期間の開始、ラベルの保持期間の最後に手動による廃棄レビューのトリガー、ネイティブ データ コネクタによるサード パーティデータのインポート、ファイルの宣言、ラベル付けされたコンテンツの検出、およびラベル付けアクティビティの監視をユーザーに提供します。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護、ガバナンスは、トレーニング可能な分類子に基づいて保持ラベルを自動的に適用するメリットをユーザーに提供します。

ライセンス別の特定の権利については、詳細な Microsoft 365 コンプライアンス ライセンスの比較を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、情報ガバナンス機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスを取得したユーザーに対して自動ラベル付けとポリシーを適用するための情報ガバナンスの構成については [、「Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)の Microsoft Information Governance」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

情報ガバナンス機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスを取得したユーザーに対して自動ラベル付けとポリシーを適用するための情報ガバナンスの構成については [、「Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)の Microsoft Information Governance」を参照してください。

## <a name="records-management"></a>レコード管理

レコード管理は、組織が Microsoft 365 およびサード パーティのデータ全体で削除機能を検出、分類、ラベル付け、保持、および延期することで、ビジネスおよび規制上の記録保持の義務を果たすのに役立ちます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5/G5、 Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 Information Protection and Governance、Office 365 E5/A5/G5、Office 365 Advanced Compliance は、アイテムをレコードまたは規制記録として宣言し、保持またはレコード ラベルを自動的に適用し、廃棄レビュー プロセスを実行する (トレーニング可能な分類子に基づいて保持ラベルを自動的に適用しない) など、レコード管理のメリットをユーザーに提供します。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 情報保護とガバナンスは、トレーニング可能な分類子に基づいて保持ラベルまたはレコード ラベルを自動的に適用するメリットをユーザーに提供します。

ライセンス別の特定の権利については、詳細な Microsoft 365 コンプライアンス ライセンスの比較を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、コンテンツをレコードとして宣言し、ポリシーの定義と宣言から、延期可能な廃棄を通じて完全なレコード プロセスを管理できるという利点があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、レコード管理機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。 ライセンスを持つユーザーに適用するレコード管理の構成の詳細については [、「Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management)のレコード管理について」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

レコード管理機能は、特定の場所 (チーム サイト、グループ サイトなど) のライセンスユーザーに適用できます。 ライセンスを持つユーザーに適用するレコード管理の構成の詳細については [、「Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management)でのレコード管理について」を参照してください。

## <a name="data-connectors"></a>データ コネクタ 

Microsoft は、Microsoft 365 コンプライアンス センターで構成できるサードパーティのデータ コネクタを提供しています。 Microsoft が提供するデータ コネクタの一覧については、サード パーティのデータ コネクタの [表を参照](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) してください。 この表では、Microsoft 365 でデータをインポートおよびアーカイブした後にサード パーティのデータに適用できるコンプライアンス ソリューションと、各コネクタの詳しい手順へのリンクも示します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft 365 でデータ コネクタを使用してサード パーティのデータをインポートおよびアーカイブする主な利点は、データのインポート後にさまざまな Microsoft 365 コンプライアンス ソリューションをデータに適用できる点です。 これにより、組織の Microsoft 以外のデータが、組織に影響を与える規制と基準に準拠している必要があります。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

次のライセンスは、データ コネクタを利用する権限をユーザーに提供します。

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 情報保護およびガバナンス
- Microsoft 365 E5/A5 コンプライアンス
- Microsoft 365 E5/A5 Insider Risk Management
- Microsoft 365 E5/A5 の電子情報開示と監査
- Office 365 E5/A5
- Office 365 Advanced Compliance

Microsoft パートナーが提供する M365 セキュリティ & コンプライアンス センターのデータ コネクタの場合、それらのコネクタを展開する前に、組織はパートナーとのビジネス上の関係を必要とします。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

コネクタは、セキュリティ センター コンプライアンス センター&カタログを使用して構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Data Connectors サービスはテナント レベルの値です。 このサービスの恩恵を受けるすべてのユーザーには、ライセンスが必要です。

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Teams データ損失防止 (DLP) 用 Microsoft Graph API

今年の初めに、Teams のメッセージに関する [Microsoft Graph 変更通知 API のパブリック プレビューを発表しました](https://go.microsoft.com/fwlink/?linkid=2143888)。 この API を使用すると、開発者は Microsoft Teams のメッセージをほぼリアルタイムで聞き取り、顧客と ISV の両方に対して DLP シナリオの実装を可能にするアプリを作成できます。 さらに、Microsoft Graph Patch API を使用すると、Teams メッセージに DLP アクションを適用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

[データ損失防止 (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) 機能は、特に組織がリモート作業に移行する中で、Microsoft Teams で広く使用されています。 組織に DLP がある場合は、Microsoft Teams チャネルまたはチャット セッションでユーザーが機密情報を共有するポリシーを定義できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Teams チャットで DLP 保護のサポートを取得するには、次のいずれかの E5 ライセンスが必要です。

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 コンプライアンス
- Microsoft 365 E5/A5 情報保護とガバナンス
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

API アクセスはテナント レベルで構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Microsoft Graph API for Teams DLP はテナント レベルの値です。 このサービスの恩恵を受けるすべてのユーザーには、ライセンスが必要です。

## <a name="ediscovery"></a>電子情報開示

電子情報開示は、Microsoft 365 システムからエクスポートする前に、調査または訴訟に関連するコンテンツを特定、収集、保持、削減、および確認するために、企業内の IT 部門および法務部門向け調査および電子情報開示ソリューションを提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーがケースのデータ 保管担当者 (ドキュメントまたは電子ファイルの管理制御を持つ人物) として選択された場合、ユーザーは Advanced eDiscovery を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/G3、および Office 365 Advanced Compliance は、コア電子情報開示を利用する権利をユーザーに提供します。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/A5 電子情報開示と監査、Office 365 E5/A5/G5、および Office 365 Advanced Compliance は、Advanced eDiscovery のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Advanced eDiscovery 機能は、管理者がセキュリティ/コンプライアンス センターで電子情報開示のアクセス許可を割り当てると、テナント内のすべてのユーザーのテナント レベル&されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

「Advanced [eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)ケースに保管担当者を追加する」の説明に従って、電子情報開示管理者は Advanced eDiscovery の組み込みの保管担当者管理ツールを使用して、特定のユーザーをケースのデータ 保管担当者として選択できます。

## <a name="office-365-customer-key"></a>Office 365 カスタマー キー

顧客キーを使用すると、組織の暗号化キーを制御し、Microsoft データ センターで保存されているデータを暗号化するためにそれらを使用Office 365 を構成します。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化のレイヤーを追加できます。 保存データには、メールボックスと SharePoint Online および OneDrive for Business 内のファイルに格納されている Exchange Online および Skype for Business からのデータが含まれます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、自分の組織によって提供、制御、および管理される暗号化キーを使用して、アプリケーション層で保存データを暗号化することで、顧客キーのメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、および Office 365 Advanced Compliance は、ユーザーが顧客キーを利用する権利を提供します。 顧客キーを完全に利用するには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Office 365 カスタマー キー暗号化キーは、Exchange Online および Skype for Business メールボックスに保存されているデータすべて、および SharePoint Online、OneDrive for Business、および Teams ファイルに対して有効にできます。 開始方法など、Office 365 顧客キーの詳細については、「顧客キーによるサービスの暗号化」を [参照してください](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Exchange Online と Skype for Business では、顧客キーを使用してメールボックスを暗号化できます。 顧客キーを 365 用に使用する前に、Azure をOfficeがあります。 Office [](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) 365 で必要な Azure リソースを作成および構成するために従う必要がある手順と、顧客キーを設定する手順については、「顧客キーのセットアップ」を参照してください。 Azure のセットアップが完了したら、どのポリシー、つまり組織内のメールボックスとファイルに割り当てるキーを決定します。 ポリシーを割り当てないメールボックスとファイルは、Microsoft によって制御および管理される暗号化ポリシーを使用します。 顧客キーの詳細、または一般的な概要については、「顧客キーによるサービスの暗号化」を [参照してください](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)。

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

カスタマー ロックボックスは、お客様にサービス操作に対する明示的なアクセス承認を提供することで、追加の制御層を提供します。 カスタマー ロックボックスは、明示的なデータ アクセスの承認のための手順が実施された場合に、組織が HIPAA や FEDRAMP などの特定のコンプライアンス義務を果たすのに役立つ場合があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

カスタマー ロックボックスを使用すると、Microsoft のユーザーは、お客様の明示的な承認なしに、お客様のコンテンツにアクセスしてサービス操作を実行できます。 カスタマー ロックボックスを使用すると、顧客はコンテンツにアクセスする要求の承認ワークフローに取り込む必要があります。 Microsoft のエンジニアがサポート プロセス中に、お客様から報告された問題のトラブルシューティングと修正を行う場合があります。 ほとんどの場合、問題は、Microsoft がサービスのために用意した広範な利用統計情報とデバッグ ツールによって修正されます。 ただし、根本原因を特定して問題を解決するために、Microsoft のエンジニアが顧客のコンテンツにアクセスする必要がある場合があります。 カスタマー ロックボックスでは、承認ワークフローの最終ステップとして、エンジニアが顧客にアクセス要求を行う必要があります。 これにより、組織はこれらの要求を承認または拒否できます。これにより、Microsoft のエンジニアが組織のエンド ユーザー データにアクセスできるかどうかを直接制御できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 Insider Risk Management、および Office 365 Advanced Compliance は、ユーザーがカスタマー ロックボックスの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Microsoft 365 管理センターでカスタマー ロックボックスを有効にできます。 詳細については、Office [365 のカスタマー ロックボックスを参照してください](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)。 カスタマー ロックボックスをオンにすると、Microsoft はコンテンツにアクセスする前に組織の承認を得る必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

現在、カスタマー ロックボックス サービスを特定のユーザーに制限する必要があります。 特典を受ける予定のすべてのユーザーにライセンスを割り当てなければならない。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

[Privileged Access Management (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) は、365 で特権管理タスクに対する詳細なアクセスOfficeします。 PAM を有効にした後、昇格されたタスクと特権付きタスクを完了するには、ユーザーは、高度にスコープが設定され、時間にバインドされた承認ワークフローを通じて Just-In-Time アクセスを要求する必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

PAM を有効にすると、組織は永続的な特権をゼロで操作できます。 ユーザーは、データへの無防備なアクセスを提供する永続的な管理アクセスによって生じる脆弱性に対する防御層を追加して恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか? 

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 E5/A5 情報保護とガバナンスは、PAM のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、PAM 機能はテナント内のすべてのユーザーのテナント レベルで有効になっています。 PAM ポリシーの構成の詳細については、「特権アクセス管理の [使用を開始する」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

お客様は、承認者グループとアクセス ポリシーを通じて、ユーザー単位で PAM を管理できます。このポリシーは、ライセンスを持つユーザーに適用できます。 詳細については、「Office [365」](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)を参照してください。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 の二重キー暗号化 

Microsoft 365 の二重キー暗号化を使用すると、機密性の高いデータを保護して、特別な要件を満たし、暗号化キーのフル コントロールを維持できます。 二重キー暗号化では、2 つのキーを使用してデータを保護します。コントロール内に 1 つのキーを、2 つ目のキーを Microsoft Azure によって安全に保存します。 データを表示するには、両方のキーにアクセスできる必要があります。 Microsoft は 1 つのキーにしかアクセスできないので、キーとデータは Microsoft では使用できなくなったので、データのプライバシーとセキュリティを完全に制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、暗号化されたデータをクラウドに移行することで、二重キー暗号化の恩恵を受けるので、キーがユーザーの制御を維持している限り、サード パーティのアクセスを防止できます。 ユーザーは、他の区別ラベルで保護されたコンテンツと同様に、二重キー暗号化コンテンツを保護して使用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、および Office 365 Advanced Compliance は、ユーザーが二重キー暗号化を利用する権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Double Key Encryption は、Windows 用のデスクトップ バージョンの Microsoft Officeをサポートします。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

ライセンスを持つユーザーの Office 365 組織内または Microsoft 365 組織内のデータに暗号化キーを割り当てるには、二重キー暗号化の展開手順に従います。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office、SharePoint Online、OneDrive for Business の 365 データ損失防止

Exchange Online、SharePoint Online、OneDrive for Business の Office 365 データ損失防止 (DLP) を使用すると、組織は電子メールとファイル (Microsoft Teams ファイル リポジトリに保存されているファイルを含む) 全体の機密情報を特定、監視、および自動的に保護できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

組織の DLP ポリシーで構成されている電子メールとファイルで機密情報が検査されている場合、ユーザーは Exchange Online、SharePoint Online、OneDrive for Business の DLP を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E3/A3/Business Premium、Office 365 E3/A3、および Office 365 データ損失防止は、Exchange Online、SharePoint Online、OneDrive for Business の Office 365 DLP を利用する権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Exchange Online の電子メール、SharePoint サイト、および OneDrive アカウントは、テナント内のすべてのユーザーに対してこれらの DLP 機能の有効な場所 *(ワークロード)* です。 DLP ポリシーの使用の詳細については、「データ損失防止の概要 [」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ/コンプライアンス センターの [データ損失防止の場所] で、場所 (ワークロード)、含まれるユーザー、除外されたユーザー&**を**  >  **カスタマイズできます**。

## <a name="communication-data-loss-prevention-for-teams"></a>Teams の通信データ損失防止

Teams の通信 DLP を使用すると、組織は、財務情報、個人を特定する情報、健康関連情報、その他の機密情報などの機密情報を含むチャットやチャネル メッセージをブロックできます。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 Information Protection and Governance、および Office 365 Advanced Compliance のライセンスユーザーは、Teams の通信 DLP を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

送信者は、組織の DLP ポリシーで構成されている、送信チャットおよびチャネル メッセージで機密情報を検査することでメリットを得る。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Teams チャットおよびチャネル メッセージは、テナント内のすべてのユーザーに対してこれらの DLP 機能の有効な場所 *(ワークロード)* です。 DLP ポリシーの使用の詳細については、「データ損失防止の概要 [」を参照してください](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ/コンプライアンス センターの [データ損失防止の場所] で、場所 (ワークロード)、含まれるユーザー、除外されたユーザー&**を**  >  **カスタマイズできます**。

## <a name="information-barriers"></a>情報バリア

情報バリアは、個人またはグループが互いに通信し合うのを防ぐために管理者が構成できるポリシーです。 これは、たとえば、ある部署が他の部署と共有してはいけない情報を処理している場合や、グループが外部の連絡先と通信できない必要がある場合に便利です。 情報バリア ポリシーは、検索と検出も防止します。 つまり、通信しない相手と通信しようとすると、ユーザー選択でそのユーザーが見つからなされます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、他のユーザーとの通信が制限されている場合に、情報障壁の高度なコンプライアンス機能を活用できます。 例:<br><br>

| シナリオ | ライセンスが必要なユーザー |
|:------|:------|:------|
| 2 つのグループ (グループ 1 とグループ 2) は互いに通信できません (つまり、グループ 1 のユーザーはグループ 2 ユーザーとの通信を制限され、グループ 2 のユーザーはグループ &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 のユーザーとの通信が制限されます)。 | グループ &nbsp; 1 とグループ &nbsp; 2 の両方のユーザー |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 Insider Risk Management、Office 365 E5/A5、および Office 365 Advanced Compliance は、ユーザーに情報バリアの恩恵を受ける権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、セキュリティ/コンプライアンス センターの PowerShell コマンドレットを使用して、情報バリア &管理します。 情報バリア ポリシーを作成するには、管理者に Microsoft 365 Enterprise グローバル管理者、Office 365 グローバル管理者、またはコンプライアンス管理者の役割が割り当てられている必要があります。 既定では、これらのポリシーはテナント内のすべてのユーザーに適用されます。 情報バリアの詳細については [、「Microsoft Teams の情報バリア」を参照してください](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、セキュリティ/コンプライアンス センターで、場所 (ワークロード)、含まれるユーザー、および除外されたユーザー&カスタマイズできます。 たとえば、すべてのユーザーが Office 365 E3 のライセンスを取得し、Office 365 Advanced Compliance/E5 のライセンスが割り当てらない場合、組織の情報バリア ポリシーを作成する必要はなされません。 詳細については [、「Microsoft Teams の情報バリア」を参照してください](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption (OME) は、Azure Rights Management (Azure RMS) で構築され、宛先のメール アドレス (Gmail、Yahoo! Mail、Outlook.com など) に関係なく、暗号化された電子メールを組織内外の宛先に送信できるようにするサービスです。

暗号化メッセージを表示するために、受信者は 1 回限りのパスコードを取得するか、Microsoft アカウントでサインインするか、Office 365 に関連付けられている職場または学校のアカウントでサインインできます。 受信者は暗号化された返事を送信することもできます。 暗号化されたメッセージを表示したり、暗号化された返信を送信したりするためにサブスクリプションを必要としません。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

メッセージ送信者は、365 Message Encryption によって提供される機密性の高いOffice制御を利用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E3/A3、Office 365 E3/A3、および Azure Information Protection プラン 1 は、ユーザーに Office 365 Message Encryption のメリットを提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Exchange 管理センター Officeメール フロー ルールの下で、365 Message Encryption ポリシーを作成 **および管理**  >  **します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しい Office 365 Message Encryption 機能のセットアップの詳細については、「新しいメッセージ暗号化機能をセットアップする」を [参照してください](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、365 Message Encryption Officeメール フロー ルールを、ライセンスを持つユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については、「電子メール メッセージを暗号化するためのメール フロー [ルールの定義」を参照してください](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)。

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryption は、外部の受信者と暗号化された電子メールへのアクセスに対するより柔軟な制御を必要とするコンプライアンスの義務を満たすのに役立ちます。 Advanced Message Encryption を使用すると、管理者は機密情報の種類 (個人を特定する情報、財務や健康の識別の識別など) を検出できる自動ポリシーを使用して組織外で共有される機密メールを制御したり、カスタムの電子メール テンプレートを適用したり、セキュリティで保護された Web ポータルを介して暗号化された電子メールへのアクセスを期限切れにしたりして、キーワードを使用して保護を強化できます。 さらに、管理者は、セキュリティで保護された Web ポータルを通じて外部からアクセスされる暗号化された電子メールをいつでも取り下らかにすることで、さらに制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

メッセージ送信者は、Advanced Message Encryption によって提供される機密性の高い電子メールに対する追加の制御の恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、および Office 365 Advanced Compliance は、Advanced Message Encryption のメリットをユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Exchange 管理センターの [メール フロー ルール] で Advanced Message Encryption ポリシー **を作成および管理**  >  **します**。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しい Message Encryption 機能の設定の詳細については [、「Set up new Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、Advanced Message Encryption のメール フロー ルールを、ライセンスを持つユーザーにのみ適用する必要があります。 メール フロー ルールの定義の詳細については [、「365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)で電子メール メッセージを暗号化するためのメール フロー ルールの定義Office参照してください。

## <a name="communication-compliance"></a>通信コンプライアンス

Microsoft 365 の通信コンプライアンスは、組織内の不適切なメッセージの検出、キャプチャ、修復アクションの実行を支援することで、通信リスクを最小限に抑えるのに役立ちます。 組織内の内部および外部の電子メール、Microsoft Teams、またはサードパーティの通信をキャプチャする特定のポリシーを定義できます。 レビュー担当者は適切な修復アクションを実行して、組織のメッセージ標準に準拠している必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

コンプライアンス スペシャリストは、通信コンプライアンス ポリシーによって組織の通信を監視することで、サービスの恩恵を受ける。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 Insider Risk Management は、通信コンプライアンスの恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者とコンプライアンス スペシャリストは、Microsoft 365 コンプライアンス センターで通信コンプライアンス ポリシーを作成します。 これらのポリシーは、組織内でレビューの対象となる通信とユーザーを定義し、通信が満たす必要があるカスタム条件を定義し、レビューを実行するユーザーを指定します。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

管理者は、通信コンプライアンス ポリシーに含める特定のユーザーまたはグループを選択します。 グループを選択するときに、グループ内の特定のユーザーを選択して、通信コンプライアンス ポリシーから除外できます。 通信コンプライアンス ポリシーの詳細については [、「Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)の通信コンプライアンスの概要」を参照してください。

## <a name="insider-risk-management"></a>インサイダー リスク管理

インサイダー リスク管理は Microsoft 365 のソリューションであり、組織内の危険なアクティビティを検出、調査、およびアクションを実行することで、内部リスクを最小限に抑えるのに役立ちます。

カスタム ポリシーを使用すると、必要に応じて、Microsoft Advanced eDiscovery へのケースのエスカレーションなど、組織内の悪意のある危険なアクティビティや不注意による危険なアクティビティを検出してアクションを実行できます。 組織内のリスク アナリストは、ユーザーが組織のコンプライアンス基準に確実に準拠できるよう、迅速に適切なアクションを実行できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

ユーザーは、アクティビティにリスクを監視することでメリットを得る。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスの恩恵を受ける権利を提供するライセンスは何ですか?

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 Insider Risk Management は、インサイダー リスク管理の恩恵を受ける権利をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Insider Risk Management ポリシーは、Microsoft 365 コンプライアンス センターで作成し、ユーザーに割り当てる必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

Microsoft 365 コンプライアンス センターでポリシーを作成する場合は、[ユーザーとグループの選択] ページで 、[ユーザーまたはグループの選択] を選択してライセンスユーザーのみを選択するか、すべてのユーザーにライセンスが与えらた場合は 、[すべてのユーザーとメールが有効なグループ] チェック ボックスをオンにできます。  詳細については、「インサイダー リスク [管理の使用を開始する」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)。

## <a name="conditional-access-policies"></a>条件付きアクセス ポリシー

条件付きアクセスは、シグナルをまとめ、決定を下し、組織のポリシーを適用するために Azure Active Directory で使用されるツールです。 条件付きアクセスは、ID ベースの制御の中心です。 条件付きアクセス ポリシーは、最も単純な if-then ステートメントです。 ユーザーがリソースにアクセスする場合は、アクションを完了する必要があります。 例: 給与管理者は給与アプリケーションにアクセスする必要があります。このアプリケーションにアクセスするには多要素認証を実行する必要があります。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Enterprise Mobility + Security E3/A3、Microsoft 365 F3/E3/A3/Business Premium、Azure Active Directory Premium プラン 1 のライセンスユーザーは、条件付きアクセス ポリシーを利用できます。 Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5、Microsoft E5 Security、Azure Active Directory Premium プラン 2 のライセンスユーザーは、Id 保護 (リスクベースの条件付きアクセス ポリシー) を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

セキュリティ運用アナリストとセキュリティ担当者は、組織のポリシーをユーザーに適用し、企業コンテンツへのアクセスを許可する前に特定の条件を満たす必要があります。 エンド ユーザーは、組織の資産を保護しながら、どこにいてもいつでも作業にアクセスできるメリットがあります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、条件付きアクセス機能はテナント内のすべてのユーザーに対してテナント レベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

特に、ID 保護と条件付きアクセスの場合、ユーザーはグループに含めるか、条件付きアクセス ポリシーに追加する必要があります。 条件付きアクセス ポリシーでは、ユーザーとグループの条件が必須です。 ポリシーでは、[すべてのユーザー] または [特定 **のユーザー** とグループ] を選択できます。 適切なライセンスを持つユーザーとグループのみを選択する必要があります。 詳細については、「条件付きアクセス [: 条件」を参照してください](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)。

## <a name="advanced-audit"></a>高度な監査

Microsoft 365 の高度な監査では、ユーザーと管理者のアクティビティに対して監査ログを 1 年間保持できます。また、他の Microsoft 365 サービスの監査ログ保持を管理するためのカスタム監査ログ保持ポリシーを作成する機能も提供します。 また、調査のための重要なイベントへのアクセスと、Office 365 マネージメント アクティビティ API への高帯域幅アクセスも提供します。 詳細については [、「Microsoft 365 の高度な監査」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

アドオン SKU を使用して、10 年間の保持期間を有効にできます。 アドオン SKU は 2021 年初めから必要になります。

### <a name="which-users-benefit-from-the-service"></a>どのユーザーがサービスの恩恵を受けるか。

Office 365 E5、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Microsoft 365 電子情報開示と監査のライセンスユーザーは、高度な監査を利用できます。

高度な監査と 10 年間の監査ログ保持アドオンを持つライセンスを持つユーザーは、10 年間の監査ログ保持の恩恵を受ける可能性があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスのメリットを得る方法

Microsoft 365 サービスのユーザー アクティビティに関連する監査レコードは最大 1 年間保持できるので、ユーザーは高度な監査を利用できます。 さらに、ユーザーのメールボックス内のアイテムがアクセスまたは読み取りされる場合など、価値の高い監査イベントがログに記録されます。 詳細については [、「Microsoft 365 の高度な監査」を参照してください](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、高度な監査は、Office 365 または Microsoft 365 E5 サブスクリプションを持つすべての組織のテナント レベルで有効にされ、Azure Active Directory、Exchange、および SharePoint のアクティビティ (適切なライセンスを持つユーザーによって実行される) の監査ログの 1 年間の保持を自動的に提供します。 さらに、組織は監査ログ保持ポリシーを使用して、他の Microsoft 365 サービスのアクティビティによって生成された監査レコードの保持期間を管理できます。 同じアイテム保持ポリシーを使用して、10 年間の監査ログ保持機能も有効になります。 詳細については、「[監査ログ保持ポリシーを管理する](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが割り当てらたテナント内のユーザーにのみサービスを適用する方法

監査ログの 1 年間の保持と重要なイベントの監査は、適切なライセンスを持つユーザーにのみ適用されます。 さらに、管理者は監査ログ保持ポリシーを使用して、特定のユーザーの監査ログの保持期間を短く指定できます。

監査ログの 10 年間の保持は、適切なアドオン ライセンスを持つユーザーにのみ適用されます。 アドオン SKU は 2021 年初めから必要になります。
