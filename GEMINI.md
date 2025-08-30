# GEMINI.md

## Directory Overview

This directory contains the rules and design documents for **Tumult**, a narrative campaign for the tabletop wargame **Warhammer: The Old World**. This is not a software project, but a collection of documents that describe a ruleset for a map-based campaign.

## Development Workflow

The core design work for this project happens in the `design` directory. The documents within this directory contain the design goals, mechanics, and rules that are being developed and refined.

The root `README.md` file is the user-facing output of this design work. It should be considered the "release" version of the rules. As such, **the `README.md` file should not contain any information that is not present in the `design` directory.**

When making changes, always start by editing the relevant files in the `design` directory. Once the changes are finalized, they can be integrated into the main `README.md`.

## Key Files

### Design Documents

*   `design/README.md`: This file provides a high-level overview of the design goals for the campaign. **It is very important to keep these goals in mind when making any changes.**
*   `design/map_supply.md`: This document details the campaign map, the concept of "Supply" for determining army sizes, and the "Decimal Contribution System" for calculating it.
*   `design/turn_phases.md`: This document provides a detailed breakdown of the five phases of a campaign turn: Downtime, Secret Orders, Order Resolution, Battle, and Resolution.
*   `design/progression_traits.md`: This document explains the hero progression system, which is based on acquiring "Traits" that provide bonuses and sometimes thematic downsides.

### User-Facing Rulebook

*   `README.md`: This is the main rulebook for the campaign. It contains a comprehensive overview of the rules, including the campaign turn structure, army management, battle size calculation, and hero progression.

## Usage

The contents of this directory are intended to be used as a rule set for playing the Tumult Warhammer narrative campaign. The `README.md` file is the primary document to read for the current rules, while the files in the `design` directory provide the underlying design and rationale.