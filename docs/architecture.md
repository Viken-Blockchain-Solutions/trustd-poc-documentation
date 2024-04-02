# Trustd POC Architecture Overview

## Introduction

The Trustd Proof of Concept (POC) aims to streamline identity interactions and transactions within the Transport and Logistics industry by leveraging the Self-Sovereign Identity (SSI) model. This model facilitates a decentralized and user-centric approach to identity verification, where individuals or organizations can own, control, and share their credentials securely and with privacy.

## System Components

### Dock.io Platform

The Dock.io platform serves as the backbone of the Trustd POC, enabling the issuance, holding, and verification of Verifiable Credentials (VCs). It provides a decentralized network for secure and verifiable transactions, ensuring the integrity and authenticity of the credentials issued and shared within the Trustd ecosystem.

### Participants

- **Issuer**: An entity, typically a business or organization, that issues digital credentials to individuals or other entities. In the Trustd POC, the issuer is a Trustd Verified business that issues a Vehicle Insurance Certificate to a holder.
- **Holder**: An individual or entity that receives and stores digital credentials in their Dock.io wallet app. The holder can share their credentials with verifiers as needed.
- **Verifier**: An entity that requests and verifies digital credentials from holders to confirm their authenticity and validity. Verifiers in the Trustd ecosystem can also verify credentials belonging to the issuer.

## Architecture Flow

1. **Issuance of 'Trustd Verified Issuer' Credential**: A business becomes 'Trustd Verified', and Trustd issues a 'Trustd Verified Issuer' verifiable credential to the Issuer.
2. **Credential Issuance to Holder**: The issuer issues a Verifiable Credential, such as a Vehicle Insurance Certificate, to the holder through the Dock.io platform. This process involves selecting a Trustd verified user, populating the credential metadata, and either issuing the credential directly to the holder's DID or via email.
3. **Credential Acceptance by Holder**: The holder accepts the credential in their Dock.io wallet app, securely storing it for future verification requests.
4. **Verification Request by Verifier**: A verifier accesses a view where they can verify the credentials of entities appearing in their carrier list. The verifier sends a verification request to the holder.
5. **Credential Presentation and Verification**: The holder presents the requested VC to the verifier, including any selectively disclosed attributes. The verifier confirms the credential's authenticity and validity.

## Key Features

- **Granular and Permissioned Data Sharing**: Holders can control which attributes of their credentials are shared with verifiers, enhancing privacy and data security.
- **Decentralized Identity (DID)**: Utilizes decentralized identifiers (DIDs) for secure and direct identification of entities within the ecosystem.
- **'Trustd Verified' Watermarks**: Credentials and documents presented within the system bear a 'Verified by Trustd' watermark, signifying their verified status.

## Conclusion

The Trustd POC architecture represents a significant advancement in identity verification within the Transport and Logistics industry. By leveraging the SSI model through the Dock.io platform, the Trustd ecosystem facilitates a more efficient, secure, and user-controlled method of sharing and verifying digital credentials.
