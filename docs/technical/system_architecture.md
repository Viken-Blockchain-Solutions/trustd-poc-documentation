# System Architecture

The TrustD Proof of Concept (POC) leverages a system architecture designed to support the secure issuance, management, and verification of Verifiable Credentials (VCs) within the Transport and Logistics industry, using the Dock.io blockchain.

---

## Overview

The TrustD POC architecture is built on several key components that work together to ensure a seamless and secure user experience. This section provides a detailed overview of these components and how they interact within the ecosystem.

---

## Components

### TrustD POC Platform

The central hub for all operations related to the management of issuing and verification of VCs to a insurance holder. It provides interfaces for issuers, and verifiers to interact with the system.

### Dock.io Blockchain

Serves as the underlying technology for the TrustD POC, providing a secure and immutable ledger for recording transactions and credential verifications.

### User Roles

- **Issuers**: Authorized entities that issue VCs to holders.
- **Verifiers**: Parties that request and verify the authenticity of VCs.

---

## Data Flow

1. **Credential Issuance**: Issuers create and issue VCs to holders, by sending the VC through email to the receiver, who scans the QR code to accept and store the VC in their dock wallet app.
2. **Credential Verification**: Verifiers request proof of credential authenticity from a carrier, they choose the correct carrier, and a QR Code is generated and presented for verification.
