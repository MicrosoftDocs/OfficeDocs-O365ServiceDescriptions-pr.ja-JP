---
title: セキュリティ & コンプライアンスのための Microsoft 365 ライセンスガイダンス
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: この記事では、Microsoft 365 コンプライアンスのライセンスに関するガイダンスを提供します。これは、ライセンスのないアクセスによるサービスの停止の可能性を回避するのに役立ちます。
ms.openlocfilehash: 71ea60a2041118a13f5ff304c0b3b8c86f089ae9
ms.sourcegitcommit: a4afd9739559c0735e167e758d04b7f676b89190
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/18/2020
ms.locfileid: "49330264"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>セキュリティ & コンプライアンスのための Microsoft 365 ライセンスガイダンス

この記事では、テナント内の &mdash; &mdash; すべてのユーザーに対して、テナント内のすべてのユーザー (スタンドアロンまたは Office 365 または Microsoft 365 プランの一部として) を購入したときに、テナントレベルのサービスがオンラインサービスになっています。 一部のライセンスのないユーザーは技術的にサービスにアクセスできる可能性がありますが、サービスの利用を目的としているユーザーにはライセンスが必要です。

> [!NOTE]
> 一部のテナントサービスは、現在、特定のユーザーに対する利点を制限することはできません。 ライセンスを付与されたユーザーにサービスのメリットを制限するための取り組みを実施する必要があります。 これにより、ターゲット機能が使用可能になった場合に、サービスが組織に及ぼす影響を回避できます。

ユーザーにライセンスを付与するためのオプションを確認するには、2020年4月1日現在、Microsoft 365 のコンプライアンス機能を利用できるようにするため、詳細な Microsoft 365 コンプライアンスライセンスの比較をダウンロードしてください。 [(PDF)](https://www.microsoft.com/download/details.aspx?id=102270)  | [(Excel)](https://www.microsoft.com/download/details.aspx?id=102287)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Id 保護は、組織の id に影響を与える可能性のある潜在的な脆弱性を検出し、組織の id に関連する、検出された疑わしいアクションに対する自動応答を構成し、疑わしいインシデントを調査して解決するための適切な処置を行うことができる、Azure Active Directory Premium P2 プランの機能です。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOps アナリストおよびセキュリティ担当者は、コンピューターの学習アルゴリズムに基づいてフラグが設定されたユーザーとリスクイベントを統合して表示するのに役立ちます。 エンドユーザーは、リスクベースの条件付きアクセスと、脆弱性に対処することによって提供されるセキュリティ強化によって提供される自動保護からメリットを得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 セキュリティ、および Azure Active Directory Premium プラン2は、Azure Active Directory Id 保護からメリットを得るための権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで Azure AD Identity Protection 機能が有効になっています。 Azure AD Id 保護の詳細については、「 [Azure Active Directory Id 保護とは](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、パスワードのリセットのレベルを定義するリスクポリシーを割り当て、ライセンスされたユーザーのみにアクセスを許可することにより、Azure AD Id 保護を適用できます。 Azure AD Identity Protection の展開の範囲を設定する方法については、「 [サインインリスクポリシーを構成](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)する」を参照してください。

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure Advanced Threat Protection (ATP) は、複数の種類の高度なターゲット化されたサイバー攻撃および insider の脅威からエンタープライズハイブリッド環境を保護するために役立つクラウドサービスです。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOp アナリストおよびセキュリティ担当者は、Azure ATP の機能を利用して、高度な脅威、侵害された id、および悪意のある insider 操作を検出し、調査することができます。 Azure ATP がデータを監視することにより、エンドユーザーはメリットを得ることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Enterprise Mobility + Security E5/A5、Microsoft 365 E5/A5、Microsoft 365 E5/A5 セキュリティ、および Azure Advanced Threat Protection を使用することで、Azure ATP からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Azure ATP 機能がテナントレベルで有効になっています。 Azure ATP の構成の詳細については、「 [AZURE atp インスタンスを作成](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

現時点では、Azure ATP サービスは、特定のユーザーに対して機能を制限することはできません。 利点を得るには、すべてのユーザーにライセンスを付与する必要があります。

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

Advanced Threat Protection (ATP) は、フィッシングやゼロデイマルウェアなどの高度な攻撃から組織を保護します。 また、ATP は、潜在的な脅威に対処する方法について特定し、優先度を設定し、推奨事項を提供することにより、さまざまなデータの信号を関連付けて、実用的な洞察を提供します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ATP は、フィッシングやゼロデイマルウェアなどの高度な攻撃からユーザーを保護します。 プラン1およびプラン2で提供されるサービスの完全な一覧については、「 [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection)」を参照してください。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。 

Office 365 Advanced Threat Protection、Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、Microsoft 365 Business Premium、および Office 365 ATP プラン1および2は、高度な脅威保護からメリットを得るためのユーザーの権利を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで ATP 機能が有効になっています。 ライセンス供与されたユーザーに対して ATP ポリシーを構成する方法については、「 [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ATP の範囲を適用するには、安全なリンクと安全な添付ファイルの展開ポリシーに従います。

- ライセンスを持つユーザーに対して安全なリンクを構成する方法については、「 [Office 365 ATP セーフリンクポリシー](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies)をセットアップする」を参照してください。

- ライセンスユーザーに対して安全な添付ファイルを構成する方法については、「 [Office 365 ATP の安全な添付ファイルのポリシー](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies)をセットアップする」を参照してください。

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) は、Microsoft Cloud App Security の一部であり、機能は Office 365 に制限されており、サードパーティのクラウドアプリおよび IaaS サービスに対して追加のセキュリティを使用することはできません。

OCAS は、組織の生産性を向上させるクラウドアプリやサービスを組織に可視化し、サイバーの脅威を特定して対処する洗練された分析を提供し、Office 365 でのデータ転送を制御することができ &mdash; ます。

機能を比較するには、「 [Microsoft Cloud App security And Office 365 Cloud App security の相違](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)」を参照してください。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

OCAS 検出シャドウ IT は、Office 365 全体での脅威保護を提供し、データにアクセスするアクセス許可を持つアプリを制御することができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Office 365 E5/A5/G5 は、ユーザーが OCAS の恩恵を受けるための権限を提供します。
詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、OCAS 機能はテナント内のすべてのユーザーに対してテナントレベルで有効になっています。

サービスの構成の詳細については、「 [Basic setup For Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、OCAS 展開を適用して、特定のアプリへのアクセス方法を強制し、Office 365 Cloud App Security によって監視されるユーザーグループを制限することができます。 詳細については、「 [スコープ付き展開](https://docs.microsoft.com/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) は、クラウドアプリとサービスを組織に表示し、サイバーの脅威を特定して対処する洗練された分析を提供し、 &mdash; クラウドアプリ間でデータを転送する方法を制御できる、クラウドアクセスセキュリティブローカー (CASB) ソリューションです。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

MCAS は、シャドウ IT を検出して評価し、第1およびサードパーティのクラウドアプリでの脅威保護を提供し、最初のおよびサードパーティのクラウドアプリ間で情報を保護します。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

MCAS、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 Security、microsoft 365 E5/A5/G5 コンプライアンス、および Microsoft 365 Information Protection and ガバナンスは、ユーザーが MCAS から恩恵を受けるための権限を提供します。

Azure AD P1 は、ユーザーが MCAS の検出機能を利用できるようにするための権限を提供します。

MCAS の条件付きアクセスアプリコントロール機能を活用するには、Azure Active Directory P1 に対するライセンスも必要です。これは、Enterprise Mobility + Security E3/A3/G3、Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E3/A3/G5、Microsoft 365 E5/A5/G5、および Microsoft 365 E5/A5/セキュリティに含まれます。

自動ラベル付けのメリットを得るには、Azure Information Protection P2 のライセンスが必要です。これは Enterprise Mobility + Security E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/a5/G5 コンプライアンス、および Microsoft 365 情報保護とガバナンスに含まれています。

詳細については、「 [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで MCAS 機能が有効になっています。

ライセンスを持つユーザーに対して Microsoft Cloud App Security ポリシーを構成する方法については、「 [Microsoft Cloud App security の概要](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、サービスで利用できるスコープ付き展開機能を使用して、ライセンスを持つユーザーに MCAS 展開の範囲を設定できます。 詳細については、「 [スコープ付き展開](https://docs.microsoft.com/cloud-app-security/scoped-deployment)」を参照してください。

## <a name="compliance-manager"></a>コンプライアンス マネージャー

コンプライアンスマネージャーを使用して、コンプライアンスを簡素化し、リスクを軽減します。 コンプライアンスマネージャーは、組織が規制、基準、会社のポリシー、その他の必要な統制フレームワークの要件を満たすのに役立ちます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

コンプライアンスマネージャーサービスのユーザーには、次のような利点があります。

- 複雑な規制、標準、会社のポリシー、その他の必要な制御フレームワークをシンプルな言語に翻訳します。
- 固有のコンプライアンス要件を満たすための、標準の評価とカスタム評価の豊富なライブラリへのアクセスを提供します。
- 推奨される改善アクションに規制制御をマップします。
- 規制要件を満たすソリューションを実装する方法について、ステップごとのガイダンスを提供します。
- 各アクションにスコアを関連付けることで、組織のコンプライアンスに最も大きな影響を与えるアクションを優先順位付けすることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Office 365 E5/A5 および Microsoft 365 E5/A5 ライセンスを使用しているお客様は、データ保護基準、GDPR、NIST 800-53、および ISO 27001 の評価にアクセスできます。また、カスタム評価機能を利用することもできます。 プレミアム評価は、2021の前半で Office 365 E5/A5 および Microsoft 365 E5/A5 お客様に購入できるようになります。 VL、CSP、WebDirect を使用して購入できます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

コンプライアンスマネージャーは、テナントに対して既定でプロビジョニングされます。 管理者は、ユーザーのアクセス許可を設定して、組織内の管理者以外のユーザーがコンプライアンスマネージャーの使用を開始できるように、役割を割り当てます。 詳細については、「コンプライアンスマネージャーの使用を開始する」を参照してください [。ユーザーの権限を設定し、役割を割り当て](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)ます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

コンプライアンスマネージャーへのアクセスは、ユーザーのアクセス許可の設定と役割の割り当てによって制御されます。 詳細については、「コンプライアンスマネージャーの使用を開始する」を参照してください [。ユーザーの権限を設定し、役割を割り当て](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)ます。

## <a name="microsoft-defender-atp"></a>Microsoft Defender ATP

Microsoft Defender ATP は、リスクベースの脆弱性管理と評価を含むエンドポイントセキュリティソリューションです。攻撃対象領域の削減機能。動作ベースの、クラウドを利用した次世代の保護。エンドポイントの検出と応答 (EDR)、自動調査と修復。および管理対象のお探しのサービス。 詳細については、「 [Microsoft DEFENDER ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) 」ページを参照してください。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Windows 10 Enterprise E5 のライセンスユーザー、windows 10 エデュケーション A5、Microsoft 365 E5 (M365 E5) (Windows 10 Enterprise E5 を含む)、microsoft 365 E5 セキュリティ、Microsoft 365 A5 (M365 A5) は Microsoft Defender ATP から恩恵を受けます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

SecOps アナリストおよびセキュリティ担当者は、Microsoft Defender ATP のエンドポイントのセキュリティ機能を利用して、予防的保護、ブリーチ後の検出、自動調査、高度な脅威への対応を行うことができます。 Microsoft Defender ATP では、悪意のあるイベントを監視することにより、エンドユーザーにメリットをもたらすことができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Microsoft Defender ATP 機能はテナント内のすべてのユーザーに対してテナントレベルで有効になっています。 展開の詳細については、「 [deployment guide](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft Defender ATP 管理者は、 [役割ベースのアクセス制御 (RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) を利用して、Microsoft Defender セキュリティセンターへの適切なアクセス権を付与するために、セキュリティ運用チーム内で役割とグループを作成できます。

## <a name="information-protection"></a>情報保護

情報保護は、機密ドキュメントや電子メールの検索、分類、ラベル付け、保護を組織にサポートします。 管理者は、ラベルを自動的に適用するためのルールと条件を定義でき、ユーザーはラベルを手動で適用することも、ラベルの適用に関する推奨事項を使用することもできます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、機密ラベルをコンテンツに手動で適用したり、コンテンツを自動的に分類することでメリットを得ることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium、Enterprise Mobility + Security F3/e3/E5、Office 365 E5/A5/E3/A3/F3、AIP Plan 1、および AIP Plan 2 は、ユーザーが手動による感度のラベル付けを利用できるようにするための権限を提供します。

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium、Enterprise Mobility + Security F3/E3/E5、AIP Plan 1、および AIP Plan 2 は、power BI で機密ラベルを適用および表示し、Power BI から Excel、PowerPoint、または PDF にエクスポートするときにデータを保護するための権限を提供します。 

> [!NOTE]
> Power BI は、Microsoft 365 E5/A5/G5 に含まれています。他のすべてのプランでは、Power BI は個別にライセンスされている必要があります。

Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 情報保護、ガバナンス、Office 365 E5、Office 365 Advanced コンプライアンス、Enterprise Mobility + Security E5、および AIP プラン2は、ユーザーが自動秘密情報のラベル付けによる恩恵を受けるための権限を提供します。

ライセンスによる特定の権限については、「Microsoft 365 コンプライアンスライセンスの詳細な比較」を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)には、Machine Learning (trainable 分類子) に基づく自動分類に対する権限は含まれていません。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで情報保護機能が有効になっています。 ライセンスユーザーのポリシーを構成する方法については、「Azure Rights Management をアクティブ化する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

AIP スキャナー機能を使用している場合を除き、ポリシーは特定のグループまたはユーザーに限定され、レジストリを編集して、ライセンスのないユーザーが分類またはラベル機能を実行するのを防ぐことができます。 AIP の展開のスコープを設定する方法については、「 [Azure Information Protection ポリシーの構成](https://docs.microsoft.com/azure/information-protection/configure-policy)」を参照してください。

AIP スキャナー機能の場合、Microsoft はライセンスされていないユーザーにファイル分類、ラベル付け、または保護機能を提供することをコミットしません。

## <a name="information-governance"></a>情報ガバナンス

情報ガバナンスは、組織がデータを検出、分類、ラベル付け、管理することによってリスクを管理するのに役立ちます。 情報ガバナンスにより、組織は、Microsoft 365 およびサードパーティのデータに対して保存と削除の機能を提供することにより、ビジネスおよび規制の要件を満たし、攻撃の面を縮小することができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

特定のポリシーや規制を遵守するために、保存のためにデータを分類できるため、ユーザーはメリットを得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 F3/Business Premium、Office 365 E1/A1/F3、およびスタンドアロン Exchange プランは、ユーザーがメールボックスデータに非レコード保持ラベルを手動で適用することによるメリットを得られるようにするための権限を提供します。

Microsoft 365 F3/F1/Business Premium、Office 365 E1/A1/F3、およびスタンドアロンの SharePoint プランは、ユーザーが SharePoint または OneDrive のファイルに非レコード保持ラベルを手動で適用することによる利点を得るための権限を提供します。 

Microsoft 365 E5/A5/E3/A3/Business Premium、Office 365 E5/A5/E3/A3、Exchange Plan 2、および Exchange Online アーカイブは、組織全体または場所全体にわたる基本的なメールボックス保持ポリシーの使用、またはメールボックスデータへの非レコード保持のラベルを手動で適用するための権限をユーザーに提供します。

Microsoft 365 E5/A5/E3/A3、Office 365 E5/A5/E3/A3、および SharePoint プラン2は、ユーザーが基本的な SharePoint または OneDrive のアイテム保持ポリシーから恩恵を受けたり、非レコード保持ラベルを SharePoint または OneDrive のファイルに手動で適用したりするための権限を提供します。

Microsoft 365 E5/A5/E3/A3 および Office 365 E5/A5/E3/A3 は、ユーザーが Teams のアイテム保持ポリシーの恩恵を受けるための権限を提供します。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、および Office 365 Advanced コンプライアンスでは、保持ラベルまたはポリシーを自動的に適用することによるメリットを得ることができるユーザーの権限が提供されます。既定の保持ラベルまたはポリシーの適用、カスタムイベントに基づく保持ラベルの保持期間の開始、ラベルの保持期間の最後における手動による廃棄レビューのトリガー、ネイティブデータコネクタを介したサードパーティデータのインポート、ファイル a レコードの宣言、ラベル付きコンテンツの検出、ラベル付けアクティビティの監視を行います。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護、ガバナンスユーザーが trainable 分類子に基づいて保持ラベルを自動的に適用することによるメリットを得られるようにするための権限をユーザーに提供します。

ライセンスによる特定の権限については、「Microsoft 365 コンプライアンスライセンスの詳細な比較」を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで情報ガバナンス機能が有効になっています。 ライセンスユーザーの autolabeling とポリシーを適用するための情報ガバナンスを構成する方法については、「 [Manage Information ガバナンス](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

情報ガバナンス機能は、特定の場所 (チームサイト、グループサイトなど) のライセンスユーザーに適用できます。 ライセンスユーザーの autolabeling とポリシーを適用するための情報ガバナンスを構成する方法については、「 [Manage Information ガバナンス](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)」を参照してください。

## <a name="records-management"></a>レコード管理

レコード管理により、組織は Microsoft 365 およびサードパーティのデータにわたって、検出、分類、ラベル付け、保存、およびディフェンシブの削除機能を使用して、ビジネスおよび規制の記録保持義務を満たすことができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5、Microsoft 365 E5/a5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、Office 365 Advanced コンプライアンスは、アイテムをレコードとして宣言したり、保持またはレコードのラベルを自動的に適用したり、廃棄レビュープロセスを実行したり (trainable 分類子に基づいて保持ラベルを自動的に適用する場合を除く)

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護、ガバナンスは、trainable 分類子に基づいて、保持またはレコードのラベルを自動的に適用することによるユーザーのための権限を提供します。

ライセンスによる特定の権限については、「Microsoft 365 コンプライアンスライセンスの詳細な比較」を参照してください。 [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  | [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、コンテンツをレコードとして宣言し、ディフェンシブ廃棄を使用して、ポリシー定義と宣言から完全なレコードプロセスを管理できるので便利です。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルでレコード管理機能が有効になっています。 ライセンスを付与されたユーザーに適用するレコード管理の構成の詳細については、「 [Microsoft 365 のレコード管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

レコード管理機能は、特定の場所 (チームサイト、グループサイトなど) にあるライセンスユーザーに適用できます。 ライセンスを付与されたユーザーに適用するレコード管理の構成の詳細については、「 [Microsoft 365 のレコード管理](https://docs.microsoft.com/microsoft-365/compliance/records-management)」を参照してください。

## <a name="data-connectors"></a>データコネクタ 

Microsoft は、Microsoft 365 コンプライアンスセンターで構成できるサードパーティのデータコネクタを提供しています。 Microsoft によって提供されるデータコネクタの一覧については、 [サードパーティのデータコネクタ](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) の表を参照してください。 また、この表には、Microsoft 365 でデータをインポートおよびアーカイブした後にサードパーティのデータに適用できるコンプライアンスソリューションの概要と、各コネクタのステップごとの手順へのリンクも含まれています。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

データコネクタを使用して、Microsoft 365 でサードパーティのデータをインポートおよびアーカイブする主な利点は、インポート後にさまざまな Microsoft 365 コンプライアンスソリューションを適用できることです。 これにより、組織の Microsoft 以外のデータが、組織に影響する規制および標準に準拠していることを確認できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

次のライセンスは、ユーザーがデータコネクタから恩恵を受けるための権限を提供します。

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Info Protection & ガバナンス
- Microsoft 365 E5/A5 コンプライアンス
- Microsoft 365 E5/A5 Insider リスク管理
- Microsoft 365 E5/A5 電子情報開示と監査
- Office 365 E5/A5
- Office 365 Advanced Compliance

Microsoft のパートナーのいずれかによって提供される M365 セキュリティ & コンプライアンスセンターのデータコネクタについては、組織でパートナーとのビジネス上の関係が必要になります。そのためには、これらのコネクタを展開する必要があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

コネクタは、セキュリティ & コンプライアンスセンターおよびコネクタカタログを使用して構成されます。

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

データコネクタサービスは、テナントレベルの値です。 このサービスを利用することを目的としているすべてのユーザーは、ライセンスを持っている必要があります。

## <a name="microsoft-graph-apis-for-teams-dlp"></a>Teams DLP の Microsoft Graph Api

今年前半に、 [Teams のメッセージに関する Microsoft Graph 変更通知 API のパブリックプレビューを発表しました](https://go.microsoft.com/fwlink/?linkid=2143888)。 この API を使用すると、開発者は、Microsoft Teams のメッセージをほぼリアルタイムで聴いて、お客様と Isv の両方の DLP シナリオ実装を有効にできるアプリを構築することができます。 さらに、Microsoft Graph Patch API を使用すると、Teams のメッセージに DLP アクションを適用することができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

Microsoft Teams では、[データ損失防止 (DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams)機能がよく使用されています。これは、組織がリモート作業に移行したためです。 組織に DLP がある場合は、Microsoft Teams チャネルまたはチャットセッションで機密情報を共有できないようにするポリシーを定義できるようになりました。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Teams チャットでのデータ損失防止 (DLP) 保護をサポートするには、次の E5 ライセンスのいずれかが必要です。

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 コンプライアンス
- Microsoft 365 E5/A5 情報の保護とガバナンス
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

API アクセスは、テナントレベルで構成されます。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft Graph API for Teams DLP は、テナントレベルの値です。 このサービスを利用することを目的としているすべてのユーザーは、ライセンスを持っている必要があります。

## <a name="ediscovery"></a>電子情報開示

電子情報開示では、企業内の IT および法務部門向けの調査および電子情報開示ソリューションを提供して、Microsoft 365 システムからエクスポートする前に調査または訴訟に関連するコンテンツを特定、収集、保存、削減、確認します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーがケースのデータ保管担当者 (ドキュメントまたは電子ファイルの管理者の制御を持つユーザー) として選択されている場合、高度な電子情報開示によるユーザーの利点があります。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5/G5/E3/A3/G3、Office 365 E5/A5/G5/E3/A3/、および Office 365 Advanced コンプライアンスは、コア電子情報開示からメリットを得るための権限をユーザーに提供します。
Microsoft 365 E5/A5/G5、Microsoft 365 E5/A5/G5 コンプライアンス、Microsoft 365 E5/a5/、Office 365 E5/a5/G5、および Office 365 Advanced コンプライアンスは、高度な電子情報開示からメリットを得るためのユーザーの権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、高度な電子情報開示機能は、管理者がセキュリティ & コンプライアンスセンターで電子情報開示のアクセス許可を割り当てるときに、テナント内のすべてのユーザーに対してテナントレベルで有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

電子情報開示管理者は、「 [Add 保管担当者 to The Advanced ediscovery case](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)」の説明に従って、高度な電子情報開示の組み込みの保管担当者管理ツールを使用して、特定のユーザーをデータ保管担当者として選択できます。

## <a name="office-365-customer-key"></a>Office 365 の顧客キー

顧客キーを使用して、組織の暗号化キーを制御し、Office 365 を使用して Microsoft のデータセンターで保存されているデータを暗号化するように構成します。 つまり、顧客キーを使用すると、独自のキーを使用して、自分に属する暗号化のレイヤーを追加することができます。 保存データには、Exchange Online と Skype for Business のデータが含まれています。これは、メールボックスや SharePoint Online および OneDrive for business 内のファイルに格納されます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーは、お客様の組織で提供、管理、管理されている暗号化キーを使用して、アプリケーション層で暗号化されたデータを保存することにより、顧客キーからメリットを得ることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、および Office 365 Advanced コンプライアンスは、ユーザーが顧客キーから恩恵を受けるための権限を提供します。 顧客キーのすべての利点を得るには、Azure Key Vault のサブスクリプションも必要です。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Office 365 顧客キー暗号化キーは、Exchange Online と Skype for business のメールボックス、および SharePoint Online、OneDrive for Business、および Teams の各ファイルに格納されているすべてのデータに対して有効にすることができます。 Office 365 の顧客キーの詳細については、「Office の使用を開始する方法」を参照してください。「 [office のキーを使用したサービスの暗号化365」](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Exchange Online と Skype for Business では、顧客キーを使用してメールボックスを暗号化できます。 Office 365 の顧客キーを使用するには、事前に Azure をセットアップする必要があります。 必要な Azure リソースを作成して構成する手順については、「 [Set Up Customer key](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up?view=o365-worldwide) 」および「Office 365 で顧客キーを設定する手順」を参照してください。 Azure のセットアップを完了した後、組織内のメールボックスとファイルに割り当てるポリシーとそのためのキーを決定します。 ポリシーを割り当てていないメールボックスとファイルでは、Microsoft によって制御および管理されている暗号化ポリシーが使用されます。 顧客キーの詳細、または一般的な概要については、「 [Office 2010 での顧客キーを使用したサービスの暗号化 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview?view=o365-worldwide)」を参照してください。

## <a name="office-365-customer-lockbox"></a>Office 365 カスタマー ロックボックス

カスタマーロックボックスは、サービス操作の明示的なアクセス承認を提供する機能をお客様に提供することにより、追加の管理層を提供します。 明示的なデータアクセス承認のために手順が実行されていることを実証することにより、お客様のロックボックスは、組織が HIPAA や FEDRAMP などの特定のコンプライアンス義務を満たすのに役立つ場合があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

カスタマーロックボックスを使用すると、お客様の明示的な承認なしにサービス操作を実行するために、Microsoft のユーザーが自分のコンテンツにアクセスできないようにすることができます。 顧客ロックボックスコンテンツへのアクセスの要求について、顧客を承認ワークフローに取り込みます。 お客様から報告された問題をトラブルシューティングおよび修正するために、Microsoft のエンジニアがサポートプロセスの間に関与している場合があります。 ほとんどの場合、問題は、Microsoft がサービスに対して設定している広範なテレメトリおよびデバッグツールによって解決されます。 しかし、Microsoft のエンジニアにお客様のコンテンツへのアクセスを要求して、根本原因を特定し、問題を解決する必要がある場合があります。 カスタマー ロックボックスでは、承認ワークフローの最終ステップとして、エンジニアが顧客にアクセス要求を行う必要があります。 これにより、組織では、これらの要求を承認または拒否するオプションが提供されます。これにより、Microsoft のエンジニアが組織のエンドユーザーデータにアクセスできるかどうかを直接制御することができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Office 365 E5/A5/G5、Microsoft 365 E5/A5/G5、Microsoft 365 E5/a5/G5 コンプライアンス、microsoft 365 Insider リスク管理、および Office 365 Advanced コンプライアンスは、カスタマーロックボックスからメリットを得るための権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Microsoft 365 管理センターでカスタマーロックボックスコントロールをオンにすることができます。 詳細については、「 [Office 365 のカスタマーロックボックス](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)」を参照してください。 カスタマーロックボックスがオンになっている場合は、そのコンテンツにアクセスする前に、Microsoft が組織の承認を取得する必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

カスタマーロックボックスサービスは、現在、特定のユーザーに制限されることはありません。 利点を得るには、すべてのユーザーにライセンスを付与する必要があります。

## <a name="privileged-access-management-in-office-365"></a>Office 365 での特権アクセス管理

[特権アクセス管理 (PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) は、Office 365 の特権のある管理タスクに対するきめ細かいアクセス制御を提供します。 PAM を有効にした後は、管理者特権のタスクを完了するために、ユーザーは、高いスコープと時間がバインドされた承認ワークフローを使用してジャストインタイムアクセスを要求する必要があります。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

PAM を有効にすることで、組織はゼロに立った権限で運用できるようになります。 ユーザーは、データへの unfettered アクセスを提供する、独立した管理アクセスから生じる脆弱性に対して、追加された防御層からメリットを得ることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。 

Office 365 E5/A5、Microsoft 365 E5/a5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 E5/A5 Information Protection and ガバナンスは、ユーザーが PAM から恩恵を受けるための権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで PAM 機能が有効になっています。 PAM ポリシーの構成の詳細については、「 [特権アクセス管理の概要](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

お客様は、承認者グループとアクセスポリシーを使用して、ユーザー単位で PAM を管理することができます。これは、ライセンスを持つユーザーに適用できます。 詳細については、「 [Office 365 での特権アクセス管理](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)」を参照してください。

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 の二重キー暗号化 

Microsoft 365 の二重キー暗号化により、非常に機密性の高いデータを保護し、特殊な要件を満たし、暗号化キーのフルコントロールを維持することができます。 二重キー暗号化は、2つのキーを使用してデータを保護し、1つのキーをコントロールに、2番目のキーをセキュリティで保護された Microsoft Azure に格納します。 データを表示するには、両方のキーへのアクセス権を持っている必要があります。 Microsoft は1つのキーにしかアクセスできないため、Microsoft はそのキーとデータを利用できないため、データのプライバシーとセキュリティを完全に制御できるようにしています。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

暗号化されたデータをクラウドに移行して、キーがユーザーの制御にとどまる限り、サードパーティからのアクセスを防止することにより、2つのキー暗号化を利用できるようになります。 エンドユーザーは、他の機密ラベルで保護されたコンテンツと同じように、二重の重要な暗号化コンテンツを保護して使用できます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 情報保護とガバナンス、Office 365 E5/A5、および Office 365 Advanced コンプライアンスは、ユーザーが二重のキー暗号化を利用できるようにするための権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Double キー暗号化は、Microsoft Office for Windows のデスクトップバージョンをサポートしています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

ライセンスを付与されたユーザーのために、Office 365 または Microsoft 365 組織内のデータに暗号化キーを割り当てるには、キー暗号化展開の手順2に従います。

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online、SharePoint Online、OneDrive for business の Office 365 データ損失防止

Exchange Online、SharePoint Online、OneDrive for Business の Office 365 データ損失防止 (DLP) を使用すると、組織は、電子メールとファイル (Microsoft Teams ファイルリポジトリに格納されているファイルを含む) 全体で機密情報を識別、監視、および自動保護することができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

組織の DLP ポリシーに構成されているように、機密情報のメールやファイルが検査されている場合は、Exchange Online、SharePoint Online、および OneDrive for Business の DLP からメリットを得ることができます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 A1/E3/A3/Business、Office 365 E3/A3、および Office 365 データ損失防止を使用すると、ユーザーは、Exchange Online、SharePoint Online、OneDrive for business の Office 365 DLP からメリットを得ることができます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、Exchange Online の電子メール、SharePoint サイト、および OneDrive アカウントは、これらの DLP 機能の *有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「 [データ損失防止の概要](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、**データ損失防止** の場所の下にあるセキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます  >  **Locations**。

## <a name="communication-data-loss-prevention-for-teams"></a>Teams の通信データ損失防止

Teams の通信 DLP を使用すると、組織は、金融情報、個人を特定できる情報、健康関連の情報、その他の機密情報などの機密情報を含むチャットおよびチャネルメッセージをブロックできます。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5/A5、Microsoft 365 E5/A5、Microsoft 365 情報保護とガバナンス、および Office 365 Advanced コンプライアンスのライセンスを持つユーザーは、Teams のコミュニケーション DLP の恩恵を受けることができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

送信者は、組織の DLP ポリシーで構成されているように、機密性の高い情報があることを調査して、送信したチャットとチャネルメッセージに機密情報を含めることによって得られます。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Teams チャットおよびチャネルメッセージは、テナント内のすべてのユーザーについて、これらの DLP 機能の *有効な場所 (ワークロード)* です。 DLP ポリシーの使用の詳細については、「 [データ損失防止の概要](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、**データ損失防止** の場所の下にあるセキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます  >  **Locations**。

## <a name="information-barriers"></a>情報バリア

情報障壁は、個人またはグループが相互に通信することを防止するために管理者が構成できるポリシーです。 これは、ある部署が他の部署と共有しないという情報を処理している場合や、グループが外部の連絡先と通信できないようにする必要がある場合に便利です。 情報バリアポリシーでは、検索と検出も禁止されます。 これは、通信しない相手と通信しようとしても、ユーザー選択ウィンドウにそのユーザーが見つからないことを意味します。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーが他のユーザーとの通信を制限されている場合は、情報バリアの高度なコンプライアンス機能を利用できます。 以下に例を示します。<br><br>

| シナリオ | ライセンスを必要とするのはだれですか? |
|:------|:------|:------|
| 2つのグループ (グループ &nbsp; 1 とグループ &nbsp; 2) は相互に通信できません (つまり、グループ1のユーザーは &nbsp; グループ &nbsp; 2 ユーザーとの通信を制限され、グループ2ユーザーはグループ1ユーザーとの通信を制限され &nbsp; &nbsp; ます。 | グループ &nbsp; 1 とグループ2の両方のユーザー &nbsp; |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 Insider リスク管理、Office 365 E5/A5、および Office 365 Advanced コンプライアンスは、ユーザーが情報の障壁から恩恵を受けるための権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、セキュリティ & コンプライアンスセンターで PowerShell コマンドレットを使用して、情報バリアポリシーを作成および管理します。 情報バリアポリシーを作成するには、管理者に Microsoft 365 Enterprise グローバル管理者、Office 365 グローバル管理者、またはコンプライアンス管理者の役割が割り当てられている必要があります。 既定では、これらのポリシーはテナント内のすべてのユーザーに適用されます。 情報の障壁の詳細については、「 [Microsoft Teams の情報障壁](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、セキュリティ & コンプライアンスセンターで、場所 (ワークロード)、含めるユーザー、除外ユーザーをカスタマイズできます。 たとえば、すべてのユーザーに Office 365 E3 のライセンスが付与されており、Office 365 Advanced コンプライアンス/E5 のライセンスを持っていない場合は、組織の情報バリアポリシーを作成する必要はありません。 詳細については、「 [Microsoft Teams の情報障壁](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)」を参照してください。

## <a name="office-365-message-encryption"></a>Office 365 Message Encryption

Office 365 Message Encryption (OME) は、Azure Rights Management (Azure RMS) で構築され、宛先のメール アドレス (Gmail、Yahoo! Mail、Outlook.com など) に関係なく、暗号化された電子メールを組織内外の宛先に送信できるようにするサービスです。

暗号化メッセージを表示するために、受信者は 1 回限りのパスコードを取得するか、Microsoft アカウントでサインインするか、Office 365 に関連付けられている職場または学校のアカウントでサインインできます。 受信者は暗号化された返事を送信することもできます。 暗号化されたメッセージを表示したり、暗号化された応答を送信したりするためにサブスクリプションを必要としません。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

メッセージの送信者は、Office 365 メッセージの暗号化によって提供される機密メールを追加することによって役立ちます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E3/A3、Office 365 E3/A3、および Azure Information Protection Plan 1 は、Office 365 Message Encryption からメリットを得るための権限をユーザーに提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、Exchange 管理センターで **メールフロー** ルールの下に Office 365 メッセージ暗号化ポリシーを作成して管理し  >  **Rules** ます。 既定では、これらのルールはテナント内のすべてのユーザーに適用されます。 新しい Office 365 メッセージ暗号化機能のセットアップの詳細については、「 [365 office の新しいメッセージの暗号化機能をセットアップ](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、ライセンスを持つユーザーにのみ Office 365 メッセージ暗号化のメールフロールールを適用する必要があります。 メールフロールールの定義の詳細については、「 [Office のメールメッセージを暗号化するためのメールフロールールを定義する 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="office-365-advanced-message-encryption"></a>Office 365 Advanced Message Encryption

Office 365 Advanced Message Encryption を使用すると、お客様は、外部の受信者により柔軟な制御と暗号化されたメールへのアクセスを必要とするコンプライアンス義務を満たすことができます。 高度なメッセージ暗号化を使用すると、管理者は機密情報の種類 (個人の識別情報、金融または健康 Id など) を検出できる自動ポリシーを使用して、組織の外部で共有される機密メールを制御することができます。また、キーワードを使用して、カスタムの電子メールテンプレートを適用し、セキュリティ保護された web ポータル さらに、管理者は、いつでもアクセスを取り消して、セキュリティで保護された web ポータルを介して外部からアクセスされる暗号化メールを制御できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

メッセージの送信者は、高度なメッセージ暗号化によって提供される機密メールを追加することによって役立ちます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Office 365 E5/A5、Microsoft 365 E5/a5、Microsoft 365 E5/A5 コンプライアンス、Microsoft 365 Information Protection and ガバナンス、および Office 365 Advanced コンプライアンスは、高度なメッセージ暗号化からメリットを得るための権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者は、メールフロールールの下にある Exchange 管理センターで、高度なメッセージ暗号化ポリシーを作成して管理します。 既定では、これらのルールはテナントのすべてのユーザーに適用されます。 新しいメッセージ暗号化機能のセットアップの詳細については、「 [Office の新しい365メッセージの暗号化機能をセットアップ](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)する」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、高度なメッセージ暗号化のメールフロールールをライセンスユーザーにのみ適用する必要があります。 メールフロールールの定義の詳細については、「 [Office のメールメッセージを暗号化するためのメールフロールールを定義する 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)」を参照してください。

## <a name="communication-compliance"></a>通信コンプライアンス

Microsoft 365 の通信コンプライアンスは、組織内の不適切なメッセージに対する修復措置を検出、取得、および解決するのに役立つため、コミュニケーションリスクを最小限に抑えることができます。 組織内の内部および外部の電子メール、Microsoft Teams、またはサードパーティの通信をキャプチャする特定のポリシーを定義できます。 レビュー担当者は、組織のメッセージ標準に準拠しているかどうかを確認するために、適切な修復処置を行うことができます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

コンプライアンスの専門家は、コミュニケーションコンプライアンスポリシーによって組織の通信を監視することにより、サービスからメリットを得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Office 365 E5/A5、Microsoft 365 E5/a5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 Insider リスク管理は、コミュニケーションへの対応のためのユーザーの権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

管理者およびコンプライアンスの専門家は、Microsoft 365 コンプライアンスセンターで通信コンプライアンスポリシーを作成します。 これらのポリシーは、組織内で検討する必要のある通信およびユーザーを定義し、通信が満たす必要があるカスタム条件を定義し、レビューを実行するユーザーを指定します。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

管理者は、特定のユーザーまたはグループを選択して、通信コンプライアンスポリシーに含めることができます。 グループを選択するときに、通信コンプライアンスポリシーから除外するグループ内の特定のユーザーを選択することもできます。 通信コンプライアンスポリシーの詳細については、「 [Microsoft 365 の通信コンプライアンス](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)」を参照してください。

## <a name="insider-risk-management"></a>インサイダー リスクの管理

Insider リスク管理は、組織内のリスクのあるアクティビティを検出、調査、処理を実行できるようにすることによって、内部的なリスクを最小限に抑えるために役立つ Microsoft 365 のソリューションです。
カスタムポリシーを使用すると、必要に応じて Microsoft Advanced eDiscovery にエスカレーションした場合を含めて、組織内の悪意のある、誤ったリスクのあるアクティビティを検出し、アクションを実行できます。 組織内のリスクアナリストは、ユーザーが組織のコンプライアンス標準に準拠していることを確認するために、適切なアクションを迅速に実行できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

ユーザーのアクティビティを監視してリスクを監視することでメリットが得られます。

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>ユーザーがサービスを利用するための権限を提供するライセンスはどれですか。

Microsoft 365 E5/A5、Microsoft 365 E5/A5 コンプライアンス、および Microsoft 365 Insider リスク管理は、ユーザーが Insider リスク管理から恩恵を受けるための権限を提供します。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

Insider リスク管理ポリシーは、Microsoft 365 コンプライアンスセンターで作成し、ユーザーに割り当てる必要があります。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

Microsoft 365 コンプライアンスセンターでポリシーを作成する場合は、[ **ユーザーとグループの選択** ] ページで、[ **ユーザーまたはグループ** の選択] を選択してライセンスユーザーのみを選択するか、すべてのユーザーがライセンスを持っている場合は [ **すべてのユーザー] および [メールが有効なグループ** ] チェックボックスをオンにします。 詳細については、「 [insider リスク管理の概要](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)」を参照してください。

## <a name="conditional-access-policies"></a>条件付きアクセス ポリシー

条件付きアクセスとは、シグナルを取り込んで、意思決定を行い、組織のポリシーを適用するために Azure Active Directory によって使用されるツールです。 条件付きアクセスは、identity 被制御面の中心になります。 最も単純な条件付きアクセスポリシーは、if-then ステートメントです。 ユーザーがリソースにアクセスする場合は、アクションを実行する必要があります。 例: 給与管理者は、給与アプリケーションにアクセスする必要があり、それにアクセスするために多要素認証を実行する必要があります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Enterprise Mobility + Security E3/Security E3、Security E3/A3、Microsoft 365 F3/E3/A3/Business Premium、および Azure Active Directory Premium プラン1は、条件付きアクセスポリシーを利用することができます。 Enterprise Mobility + Security E5/G5 のライセンスユーザー、Microsoft 365 E5/A5、Microsoft E5 セキュリティ、および Azure Active Directory Premium プラン2は、Id 保護 (リスクベースの条件付きアクセスポリシー) によってメリットを得られます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

セキュリティ運用アナリストおよびセキュリティ担当者は、組織のポリシーをユーザーに適用して、企業のコンテンツへのアクセスを許可する前に、特定の条件を満たす必要があることによってメリットを得ることができます。 エンドユーザーは、組織の資産を保護する一方で、いつでもどこでも自分の作業にアクセスできるという利点があります。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、テナント内のすべてのユーザーについて、テナントレベルで条件付きアクセス機能が有効になっています。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

具体的には、Id 保護と条件付きアクセスの場合、ユーザーはグループに含めるか、条件付きアクセスポリシーに追加する必要があります。 条件付きアクセスポリシーでは、ユーザーとグループの条件は必須です。 ポリシーでは、[ **すべてのユーザー** ] または [特定のユーザーとグループ] のどちらかを選択できます。 適切にライセンスされたユーザーとグループのみを選択する必要があります。 詳細については、「 [Azure Active Directory の条件付きアクセスの条件](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)について」を参照してください。

## <a name="advanced-audit"></a>高度な監査

Microsoft 365 の高度な監査では、ユーザーと管理者のアクティビティについて1年間の監査ログの保持が提供され、他の Microsoft 365 サービスの監査ログの保持を管理するためのカスタム監査ログ保持ポリシーを作成する機能が提供されます。 また、調査のための重要なイベントへのアクセス、および Office 365 Management Activity API への高帯域幅アクセスを提供します。 詳細については、「 [Microsoft 365 の詳細な監査](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)」を参照してください。

アドオン SKU を使用して、10年間の保持期間を有効にすることもできます。 アドオン SKU は、2021の初期段階で必要になります。

### <a name="which-users-benefit-from-the-service"></a>サービスからメリットを得られるのはどのユーザーか。

Office 365 E5 のライセンスユーザー、Microsoft 365 E5、Microsoft 365 E5 コンプライアンス、および Microsoft 365 電子情報開示と監査は、高度な監査からメリットを得られます。

高度な監査と10年の監査ログ保持アドオンを使用したライセンスユーザーは、10年の監査ログの保持を利用できます。

### <a name="how-do-users-benefit-from-the-service"></a>ユーザーがサービスを利用するにはどうすればよいですか?

Microsoft 365 サービスのユーザーアクティビティに関連する監査レコードは、最大1年間保持できるため、ユーザーは高度な監査からメリットを得られます。 さらに、ユーザーのメールボックス内のアイテムにアクセスまたは読み取りが行われたときなど、高価値の監査イベントがログに記録されます。 詳細については、「 [Microsoft 365 の詳細な監査](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)」を参照してください。

### <a name="how-is-the-service-provisioneddeployed"></a>サービスのプロビジョニング/展開方法

既定では、Office 365 または Microsoft 365 E5 サブスクリプションを持つすべての組織のテナントレベルで Advanced Audit が有効になっており、Azure Active Directory、Exchange、および SharePoint のアクティビティ (適切なライセンスを持つユーザーによって実行される) の監査ログの1年の保持期間が自動的に付与されます。 さらに、組織は監査ログの保持ポリシーを使用して、他の Microsoft 365 サービスのアクティビティによって生成された監査レコードの保持期間を管理できます。 同じアイテム保持ポリシーを使用して、10年間の監査ログ保持機能を有効にすることもできます。 詳細については、「[監査ログ保持ポリシーを管理する](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)」を参照してください。

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>サービスのライセンスが付与されているテナント内のユーザーにのみ、サービスを適用することができますか。

監査ログの1年間の保持、および重要なイベントの監査は、適切なライセンスを持つユーザーにのみ適用されます。 さらに、管理者は監査ログ保持ポリシーを使用して、特定のユーザーの監査ログの保存期間を短くすることができます。

監査ログの10年間の保持は、適切なアドオンライセンスを持つユーザーにのみ適用されます。 アドオン SKU は、2021の初期段階で必要になります。
