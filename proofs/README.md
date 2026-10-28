# PSVS Proofs

## Purpose
This folder contains informal reasoning and verification evidence for the Polar Vault Seed Storage System.

## Proof 1: Chamber Capacity
Requirement: S3

Argument:
Every chamber must respect its specified maximum capacity.
Chambers 1-3 must not exceed 50,000 boxes each.
Chamber 4 must not exceed 20,000 boxes.
A deposit must be rejected if it would exceed the chamber capacity.

## Proof 2: Box Ownership
Requirement: S4

Argument:
Every box must have exactly one depositor as its owner.
A normal withdrawal is allowed only when the requesting depositor owns the box.
Emergency release requires a separately defined authorization rule.

## Proof 3: Temperature
Requirements: S7 and S8

Argument:
The chamber temperature must not rise above -18°C during normal operation.
During authorized maintenance, the temperature may reach 0°C.
The maintenance exception must be clearly defined and verified.

## Verification Status
These are informal proof arguments, not machine-checked formal proofs.
