# Smart Plastic Buyback System

A concept for encouraging plastic-bottle returns through a refundable deposit, with a roadmap toward an IoT-enabled collection system.

## Overview

A small refundable deposit is added when a bottle is purchased. Returning the bottle enables the customer to reclaim that deposit. The original concept uses LKR 20 as an example amount; it is not a fixed operational price. Unclaimed deposits could help support recycling.

## Proposed workflow

1. Record a bottle purchase and its refundable deposit.
2. Identify the bottle when it is returned.
3. Validate the return and prevent duplicate claims.
4. Record the refund and collection event.

## Repository status

This repository currently contains concept documentation only. Firmware, collection hardware, a payment integration, and a deployed refund service are not included.

## Development roadmap

- Define bottle identification and deposit records.
- Prototype QR-code scanning and IR-based bottle detection.
- Design the collection unit and its IoT connectivity.
- Build a refund workflow with duplicate-return checks.
- Validate the complete prototype with documented test results.

These are planned development steps, not implemented features.

## Author

[Umesh R.D.S](https://github.com/umeshRD) — Electrotechnology undergraduate, Wayamba University of Sri Lanka.
