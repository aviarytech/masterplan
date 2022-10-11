# [Aviary Tech Masterplan](https://hackmd.io/lK0rJtksTiC4cua_DYu4Lw)

> autonomous control of authentic data and relationships
> 
> \- Timothy Ruff

We have slightly reworded the [Trust Over IP Stack](https://trustoverip.org/toip-model/) to align with the way that Aviary Tech is approaching building decentralized identity applications using Verifiable Credentials (VCs) and Decentralized Identifiers (DIDs).

This masterplan outlines the technology products, specifications and libraries being built and deployed by Aviary Tech in order to deliver autonomous control of authentic data and relationships to the world.

**Aviary Tech Stack**

1. [Authentic Data Application Layer](https://github.com/aviarytech/masterplan/tree/master#authentic-data-application-layer)
2. [Authentic Data Layer](https://github.com/aviarytech/masterplan/tree/master#authentic-data-layer)
3. [Trusted Communication Layer](https://github.com/aviarytech/masterplan/tree/master#trusted-communication-layer)
4. [Coherence Layer](https://github.com/aviarytech/masterplan/tree/master#coherence-layer)


## Authentic Data Application Layer

### [aviary.one](https://aviary.one)

#### Verification Services
* █████████.██████

#### Issuance Services
* ██████████.███

#### Holder Services
* [1keep.com](https://1keep.com)

## Authentic Data Layer

### [W3C Verifiable Credentials (VCs)](https://www.w3.org/TR/vc-data-model/)

#### Proof Formats
* [JSON-LD VC (ldp_vc) aka Data Integrity Proofs](https://www.w3.org/TR/vc-data-model/#data-integrity-proofs)
  * [JsonWebSignature2020](https://www.w3.org/community/reports/credentials/CG-FINAL-lds-jws2020-20220721/)
  * [Ed25519Signature2020](https://w3c-ccg.github.io/di-eddsa-2020/)
  * BBS+ 2023
* [JWT VC (jwt_vc)](https://www.w3.org/TR/vc-data-model/#json-web-token)
  * [SD-JWT](https://datatracker.ietf.org/doc/draft-ietf-oauth-selective-disclosure-jwt/)

#### Revocation Methods

* [Status List 2021](https://w3c-ccg.github.io/vc-status-list-2021/)

## Trusted Communication Layer

### [DIDComm Messaging](https://identity.foundation/didcomm-messaging/spec/)
* [Out of Band Messages 2.0](https://identity.foundation/didcomm-messaging/spec/#out-of-band-messages)
* [Issue Credential Protocol 3.0](https://github.com/decentralized-identity/waci-didcomm/blob/main/issue_credential/README.md)
* [Present Proof Protocol 3.0](https://github.com/decentralized-identity/waci-didcomm/blob/main/present_proof/present-proof-v3.md)

### OpenID for Verifiable Credentials
* [Self Issued OpenID Provider v2 (SIOPv2)](https://openid.net/specs/openid-connect-self-issued-v2-1_0.html)
* [OpenID for Verifiable Presentations (OIDC4VP)](https://openid.net/specs/openid-4-verifiable-presentations-1_0.html)
* [OpenID for Verifiable Credential Issuance (OIDC4VCI)](https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html)
### [Verifiable Credentials API (VC-API)](https://w3c-ccg.github.io/vc-api/)

## Coherence Layer

### [W3C Decentralized Identifiers (DIDs)](https://www.w3.org/TR/did-core/)

* [did:key](https://w3c-ccg.github.io/did-method-key/)
* [did:web](https://w3c-ccg.github.io/did-method-web/)
* [did:peer](https://identity.foundation/peer-did-method-spec/)