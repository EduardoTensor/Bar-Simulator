# Bar Simulator System

> **Note:** This repository is a **study and portfolio project** based on an unreleased/discontinued game prototype. Its primary focus is demonstrating core gameplay mechanics and software architecture concepts in Unreal Engine.

## Technical Details

* **Engine:** Unreal Engine (Originally started in UE 1.1.1 and updated to **UE 5.8.4**)
* **Implementation:** 100% **Blueprints**
* **Status:** Discontinued / Archived (Portfolio Showcase)

## How to Run

1. Download or clone this repository.
2. Move the project folder into your local **Unreal Projects** directory.
3. Open the `.uproject` file using **Unreal Engine 5.8.4** (or compatible).

## Controls & Core Mechanics

| Key | Action | Description |
| :--- | :--- | :--- |
| **E** | **Grab / Collect** | Takes drinks from the refrigerator and adds them to the player's inventory. |
| **T** | **Sell / Trade** | Sells collected drinks to the NPC. |
| **J** | **Save Game** | Saves the current game state. |
| **L** | **Load Game** | Loads the previously saved game state. |

## Future Improvements & Next Project Practices

Looking back at this prototype, the following architectural and workflow improvements are planned for future projects:

* **Modular Architecture (Actor Components):** Decouple core mechanics—such as Inventory, Interaction, and Save/Load systems—from the main Character/Actor classes by migrating them into independent, reusable **Actor Components**.
* **Code Refactoring with Functions:** Break down monolithic logic and complex Blueprints into smaller, single-responsibility **Functions** to keep the visual scripting clean, readable, and easy to debug.
* **Better System Separation:** Establish clearer architectural boundaries between gameplay systems, data handling, and UI to improve scalability.
* **Technical Documentation (GDD / TDD):** Create a dedicated **Technical Design Document** (or a structured PDF overview) alongside future repositories to clearly explain system flows, Blueprint architecture, and design decisions.


## Next Project: CombatFX-Lite

Our next project will be **CombatFX-Lite**, a lightweight combat feedback system developed in Unreal Engine 5 using 100% Blueprints.

This project represents our next step in developing gameplay systems, focusing on combat feedback mechanics, damage visualization, health bars, and Blueprint integration.

Building on the experience gained from Bar Simulator System, we aim to improve our development practices, system organization, and technical implementation.

