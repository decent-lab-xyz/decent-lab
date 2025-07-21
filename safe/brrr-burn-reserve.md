# 🔐 BRRR Burn Reserve — Safe Multisig

This Safe controls treasury operations for the $BRRR protocol.  
It holds ETH for optional burn matching, and is the only entity authorized to execute treasury-related $BRRR burns.

## 🔎 Safe Overview

- **Network**: Ethereum Mainnet  
- **Address**: 0x853d73E33184CFf25d6Fc6ceb7AeF0B6E7Ab59C3 https://safe.global/eth:0x853d73E33184CFf25d6Fc6ceb7AeF0B6E7Ab59C3  
- **Threshold**: 3 of 3 signers required to execute any transaction  
- **Created by**: Decent Lab

## 🧱 Roles + Signers

| Role             | ENS Name           | Description                         |
|------------------|--------------------|-------------------------------------|
| Studio Controller| `decentlab.eth`    | Primary identity + project admin    |
| Burn Admin       | `burnadmin.eth`    | Authorized to execute burns         |
| Proof Signer     | `proofsigner.eth`  | Responsible for public burn proofs  |

> Each ENS resolves to the multisig for public transparency. Individual wallets are rotated only if compromised.

## 🔥 Purpose

- Hold ETH for potential community burn matching  
- Execute manual or timed burns with 3-of-3 approval  
- Sign off-chain proofs tied to burn logs, Safe actions, or repo entries  
- Serve as the canonical treasury controller for Decent Lab protocols

## 🔏 Security Notes

- No contract upgrade authority is held  
- Mint authority for $BRRR is disabled   
- This Safe address is referenced in:
  - GitHub repo (https://github.com/decent-labs-xyz/decent-lab)
  - printergoesbrrr.xyz (https://printergoesbrrr.xyz)
  - On-chain registry and burn logs

## ✅ Signer Commitments

Each signer affirms:

> "No team tokens. No unlocks. Just burns, Safe links, and GitHub receipts."



_Last updated: 2025-07-20

