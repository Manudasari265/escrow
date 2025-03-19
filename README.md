## Solana Escrow Program (Anchor Framework)

# Overview

This repository contains a Solana Escrow Program built using the Anchor framework. The program allows users to create secure, trustless escrow contracts for token exchanges between two parties.

# Features

* Trustless Transactions: Ensures both parties meet conditions before tokens are exchanged.

* Conditional Execution: Tokens are only released when pre-defined conditions are met.

* Anchor-based Security: Uses Anchor for structured accounts and secure execution.

# Approach & Design

* Escrow Account: Holds the depositor's tokens until the conditions are fulfilled.

* Program Instructions:

* Initialize Escrow: Locks assets in the escrow contract.

* Cancel Escrow: Allows the depositor to reclaim funds if conditions aren’t met.

* Fulfill Escrow: Transfers assets to the recipient once the agreement is honored.

* Security Considerations: Ensures only authorized parties can interact with the escrow.

# Installation steps
```
git clone https://github.com/Manudasari265/escrow.git
cd anchor-escrow
anchor build
anchor deploy
```

