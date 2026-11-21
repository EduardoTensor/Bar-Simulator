# Bar Simulator System

> **Note:** This repository is a **study and portfolio project** based on an unreleased/discontinued game prototype. Its primary focus is demonstrating core gameplay mechanics and software architecture concepts in Unreal Engine.

## Technical Details

* **Engine:** Unreal Engine (Originally started in UE 1.1.1 and migrated/updated to **UE 5.8.4**)
* **Status:** Discontinued / Archived (Portfolio Showcase)

## Controls & Core Mechanics

| Key | Action | Description |
| :--- | :--- | :--- |
| **E** | **Grab / Collect** | Takes drinks from the refrigerator and adds them to the player's inventory. |
| **T** | **Sell / Trade** | Sells collected drinks to the NPC. |
| **J** | **Save Game** | Saves the current game state. |
| **L** | **Load Game** | Loads the previously saved game state. |

## Future Improvements & Architectural Retrospective

Looking back at this prototype, if development were to continue into a full production title, the following architectural changes would be prioritized:

* **Modular Architecture (Actor Components):** Decouple core mechanics—such as Inventory, Interaction, and Save/Load systems—from the main Character/Actor classes by migrating them into independent, reusable **Actor Components**.
* **Code Refactoring with Functions:** Break down monolithic logic and complex Blueprints into smaller, single-responsibility **Functions** to keep the codebase clean, readable, and easy to debug.
* **Better System Separation:** Establish clearer architectural boundaries between gameplay systems, data handling, and UI to improve scalability.
