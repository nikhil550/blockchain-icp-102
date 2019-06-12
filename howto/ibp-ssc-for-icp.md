---

copyright:
  years: 2019
lastupdated: "2019-05-31"

keywords: Secure Service Container, IBM Cloud Private, IBM Z, LinuxONE

subcollection: blockchain

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:note: .note}
{:important: .important}
{:tip: .tip}
{:pre: .pre}

# Using {{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private
{: #ibp-ssc-for-icp}

{{site.data.keyword.blockchainfull}} Platform has been validated to run in the environment of {{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private. You can import the {{site.data.keyword.blockchainfull_notm}} Platform for {{site.data.keyword.cloud_notm}} Private Helm chart to your {{site.data.keyword.cloud_notm}} Private that is built on the Secure Service Container framework on {{site.data.keyword.IBM_notm}} Z and LinuxONE.
{:shortdesc}

{{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private is a piece of software that provides an encrypted environment with peer to peer and peer to host isolation. It protects container applications from access via Hardware and Operating System admin credentials, whether access is accidental or malicious, internal or external to an organization. It offers pervasive encryption to protect your data at rest and in flight. For more information, see [Secure Service Container for {{site.data.keyword.cloud_notm}} Private documentation](https://www.ibm.com/support/knowledgecenter/en/SSUPZ7_1.1.0/kc_welcome_page.html){: external}.

## Considerations
{: #ibp-ssc-for-icp-considerations}

Before you deploy {{site.data.keyword.blockchainfull_notm}} Platform on Secure Service Container for {{site.data.keyword.cloud_notm}} Private, ensure that you use the following versions of the products.

- **{{site.data.keyword.blockchainfull_notm}} Platform for {{site.data.keyword.cloud_notm}} Private v1.0.1**  
  You can use either one of the following editions:
  - Passport Advantage (PPA). You need to have the required license to access [Passport Advantage Online](https://www.ibm.com/software/passportadvantage/pao_customer.html){: external}. Upon your purchase, technical support for {{site.data.keyword.blockchainfull_notm}} Platform is included.
  - Community Edition. This free version can be accessed through [GitHub](https://github.com/IBM/charts/tree/master/stable/ibm-blockchain-platform-dev){: external}. Note that {{site.data.keyword.IBM_notm}} does not provide support for the Community Edition.
- **{{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private v1.1.0 Feb. 2019 Refresh**  
  For more information, see [Downloading Secure Service Container for {{site.data.keyword.cloud_notm}} Private](https://www.ibm.com/support/knowledgecenter/en/SSUPZ7_1.1.0/topics/retrieve_appliance.html){: external}.
- **{{site.data.keyword.cloud_notm}} Private v3.1.0**  
  For more information, see [{{site.data.keyword.cloud_notm}} Private documentation](https://www.ibm.com/support/knowledgecenter/en/SSBS6K_3.1.0/kc_welcome_containers.html){: external}.

## Installing {{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private
{: #ibp-ssc-for-icp-step1}

Follow the instructions in [{{site.data.keyword.IBM_notm}} Secure Service Container for {{site.data.keyword.cloud_notm}} Private documentation](https://www.ibm.com/support/knowledgecenter/en/SSUPZ7_1.1.0/topics/install_ssc4icp.html){: external} to install your {{site.data.keyword.cloud_notm}} Private on the Secure Service Container framework on {{site.data.keyword.IBM_notm}} Z or LinuxONE.

## Deploying {{site.data.keyword.blockchainfull_notm}} Platform on {{site.data.keyword.cloud_notm}} Private
{: #ibp-ssc-for-icp-step2}

Follow the instructions in [Getting started with {{site.data.keyword.blockchainfull_notm}} Platform for {{site.data.keyword.cloud_notm}} Private](/docs/services/blockchain-icp-102?topic=blockchain-icp-102-get-started-icp#get-started-icp) to configure your {{site.data.keyword.cloud_notm}} Private, import {{site.data.keyword.blockchainfull_notm}} Platform Helm chart, and deploy individual blockchain components.
