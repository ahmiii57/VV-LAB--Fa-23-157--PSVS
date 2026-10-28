# PSVS Models

## Purpose
This folder contains models for the Polar Vault Seed Storage System.

## Main Entities
- Depositor
- Box
- Chamber
- Species

## Main State Information
- Box owner
- Box location
- Box status
- Seed species
- Chamber capacity
- Chamber temperature
- Maintenance mode

## Main Constraints
- Only registered depositors can deposit boxes.
- Every box belongs to exactly one depositor.
- Chamber load must not exceed its capacity.
- Chamber temperature must follow the approved temperature rules.
- Withdrawals must follow ownership and annual quota rules.
