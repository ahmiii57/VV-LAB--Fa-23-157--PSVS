# PSVS Abstractions

## Purpose
This folder contains the high-level abstractions of the Polar Vault Seed Storage System.

## Main Entities
1. Depositor: An institution that deposits seed boxes.
2. Box: A sealed container holding seed samples of one species.
3. Chamber: A freezer chamber used to store seed boxes.
4. Species: The type of crop represented by the seed samples.

## Main Relationships
- A depositor can own multiple boxes.
- Each box belongs to one depositor.
- Each box contains seed samples of one species.
- A chamber can store multiple boxes.

## Main Operations
- Deposit
- Withdraw
- Redeposit
- MoveBox
- DeclareEmergency
