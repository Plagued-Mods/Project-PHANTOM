# Project P.H.A.N.T.O.M.

**Preservation of Hardware, Archives, and Networked Technology - Operational Manufacturing**

A conceptual design document and collaborative pitch for a Fallout 4 mod project exploring pre-War technology preservation, archived knowledge recovery, networked systems, and autonomous manufacturing capabilities designed to enhance survival after catastrophic loss.

> ⚠️ **Prototype System** — This is a design concept / pitch document, not a finished mod.

🔗 [View the live concept page](https://plagued-mods.github.io/Project-PHANTOM/)

## Core Concept

A pre-War military research project attempted to preserve critical manufacturing capability after a catastrophic event. Rather than storing finished weapons and equipment, the project focused on preserving the *ability to rebuild* lost technology.

> The player does not find a new weapon.
> The player restores the ability to create one.

The **Reconstruction Fabricator** is a damaged prototype manufacturing system. It requires recovered components, recovered research data, and recovered schematics before it can produce anything meaningful. The system was abandoned before completion — the player finishes the work.

The concept also proposes an "item set" style stacked bonus system (e.g. Armor + Weapon = additional perks, using both while sneaking grants further bonuses, etc.), intended to be implemented through scripting and custom hidden perks.

## Quest: Project P.H.A.N.T.O.M.

### Discovery Location
Possible locations for the quest to begin:
- Federal research facility
- Military technology laboratory
- Former DARPA-style installation
- Vault-Tec research annex
- Robotics development center

**Recommended theme:** A secure military research facility hidden beneath a civilian research site.

### The Player Discovers
- Damaged fabrication equipment
- Incomplete research terminals
- Security logs
- Destroyed prototype components

### Terminal Archive: Reconstruction Project Archive

- **Entry 001 – Project Overview:** Explains the purpose of Project P.H.A.N.T.O.M. — preserving critical defense manufacturing capability in the event of catastrophic infrastructure failure, since industrial capacity, supply chains, and manufacturing expertise are all vulnerable.
- **Entry 002 – Development Status:** A table tracking system status (Prototype Fabricator Unit: Operational, Pattern Database: Incomplete, Material Processing System: Damaged, Manufacturing Core: Missing, Security Authorization: Required). Overall project status: **Suspended**.
- **Entry 003 – Final Log:** The facility's last transmission before evacuation, emphasizing that the Reconstruction Fabricator must not be destroyed so the Commonwealth may one day rebuild.

## Recovery Components

The player must recover missing components required to restore the Reconstruction Fabricator:

| Component | Location | Purpose |
|---|---|---|
| Fabrication Core | Industrial or robotics facility | Central processing system that translates recovered schematics into manufacturing instructions |
| Power Regulation Assembly | Energy facility | Stabilizes the fabrication process |
| Pattern Storage Module | Military installation | Contains partial manufacturing data |
| Material Processing Unit | Factory or manufacturing facility | Allows the machine to process modern scavenged materials |

## Machine Activation Terminal

Once restored, the Reconstruction Fabricator Control System comes online with a warning that manufacturing patterns are incomplete and additional recovery operations are required. Available functions include:
- Restore archived schematics
- Manufacture recovered patterns
- Process replacement components

## Recipe System

The Reconstruction Fabricator does not use traditional recipes — it restores archived manufacturing patterns. The machine does not cook food or assemble weapons in a conventional sense; it *reconstructs lost production methods*.

### Category 1: Preservation Manufacturing (Common)
Basic fabricator patterns providing useful settlement production capability:
- **Preserved Salisbury Steak** — Inputs: Salisbury Steak, Plastic, Fertilizer, Antiseptic, Adhesive
- **Preserved Sugar Bombs** — Inputs: Sugar Bombs, Plastic, Adhesive, Antiseptic
- **Preserved Mac & Cheese** — Inputs: BlamCo Mac & Cheese, Plastic, Oil, Adhesive
- **Stimpak** — Inputs: Blood Pack, Antiseptic, Steel
- **Refreshing Beverage** — Inputs: Purified Water, Blood Pack, Stimpak, RadAway
- **Purified Water** — Inputs: Dirty Water, Antiseptic

### Category 2: Military Reconstruction (Restricted)
Restricted patterns requiring recovered schematics and authorization. These are not standard recipes — they are recovered manufacturing archives.

## Restricted Reconstruction Patterns (Unique Items)

These patterns represent incomplete experimental technology. The fabricator requires recovered components before manufacturing authorization is granted, and unique reconstruction patterns are limited — the system restores lost technology, it does not create unlimited copies of experimental equipment.

### PHANTOM Shotgun Reconstruction
An experimental close-quarters weapons platform intended for advanced suppression, hostile environment response, and tactical force multiplication — performance optimized with paired PHANTOM technology.

**Pattern requirements (recover):**
- Damaged shotgun frame
- Toxic delivery system
- Conversion assembly
- Weapon schematic

**Component Recovery Locations:**
- **National Guard Armory** — Recovered shotgun frame, modified beyond standard military specifications; not designed for conventional ammunition.
- **Chem Research Facility** — Toxic delivery system; the weapon was designed around specialized payload delivery (chemical compatibility testing incomplete).
- **Vault Research Site** — Conversion system; an experimental modification package originally intended to let the weapon function as a specialized battlefield suppression platform.

**Output:** PHANTOM Shotgun

### PHANTOM Recon Armor Reconstruction
Prototype stealth armor system.

**Pattern requirements (recover):**
- Armor frame
- Optical systems
- Power interface
- Stealth technology database

The design philosophy: *the objective was not invisibility — the objective was survival.* A soldier who cannot be detected cannot be targeted; a soldier who cannot be targeted cannot be eliminated.

**Output:** PHANTOM Recon Armor (manufacturing pattern incomplete — additional production will require replacement components)

## Final Quest Completion

Upon completion, the terminal reports:
- STATUS: ONLINE
- Pattern archive: RECOVERED
- Recovery protocol: COMPLETE
- Manufacturing capability restored — no further action required.

## About This Repository

This repo contains the design document/pitch as a static HTML page (styled with Bootstrap 5 and Font Awesome), intended as a concept for collaborative development into a full Fallout 4 mod.

- `index.html` — the full design document/pitch page
- `css/phantom.css` — custom theme styling for the document

## Contributing

This is an open concept pitch. Ideas, feedback, and collaboration on turning this into a full mod (quest design, scripting, assets) are welcome.
