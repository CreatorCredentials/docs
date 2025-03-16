---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Overview

<div data-full-width="true"><figure><img src="../.gitbook/assets/Creator-Credentials-Overview.png" alt="" width="375"><figcaption><p>Creator Credentials – Overview</p></figcaption></figure></div>

## Description

The overview illustrates the process of issuing and managing **Verifiable Credentials (VCs)** for creators and rightsholders within a structured trust framework. The system connects **issuers**, such as media organisations or collective management organisations (CMOs), with **creators**, who seek to verify and manage their digital identities.

The process begins with both issuers and creators signing up and logging into the **Creator Credentials App**. Issuers authenticate themselves using institutional trust mechanisms, such as **SSL/TLS certificates, QWAC, EBSI DIDs, and Qualified Certificates (QCerts for eSeal)**, establishing their legitimacy as trusted entities. Additionally, issuers can verify their authority by **setting up did:web**, which serves as a decentralised identifier for issuing credentials.

Creators, on the other hand, verify their identities through **self-verification methods**, including **domain verification (DNS TXT records), social media account verification, and email verification**. These self-verification options provide increasing levels of **trust and authentication**, with decentralised identity standards such as **did:key** reinforcing security.

Once both parties are verified, a **handshake process** facilitates mutual identification between the creator and the issuer. The creator then selects a **sector-specific credential template**, which defines the type of **Verifiable Credential** they need. The issuer can **issue, manage, and, if necessary, revoke** these credentials. The credentials can be **issued to creators**, allowing them to manage and share their verifiable claims with third parties.

The system ensures **transparency, security, and interoperability** by integrating decentralised identity frameworks and cryptographic verification. This approach empowers creators with **self-sovereign identity management**, while issuers establish **institutional trust**, ensuring that media attributions and rights declarations are verifiable across the digital ecosystem.
