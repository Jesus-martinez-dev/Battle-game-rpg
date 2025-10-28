 ⚔️ RPG Battle System: Deterministic Logic Engine (Core Engine)
📝 Project Description: Web3 Ready
This repository houses the Core Engine designed for role-playing game (RPG) battle simulation. The project's focus is on a deterministic and auditable code architecture, ideal for applications where transparency and verifiability of state (such as in blockchain technology) are crucial.

It demonstrates a solid grasp of algorithm design to manage event sequencing, damage calculation, and secure game state manipulation.

🚀 Implementation Technologies and Languages
The project uses web-based technologies for lightweight and demonstrable execution:

JavaScript (ES6+): Used for Object-Oriented Programming (OOP) in the core battle logic.

HTML5 and CSS3: Implementation of the user interface to visualize the battle simulation.

✨ Features and Implemented Logic (Determinism)
The engine's internal logic is structured to ensure maximum transparency in each turn of the battle:

Turn System and Action Queue:

Implementation of a strict execution queue, defined by the Speed/Initiative statistic, ensuring that the order of attacks is deterministic and predictable.

Centralized Entity Model:

Use of robust classes for Characters and Enemies with essential attributes (Health, Mana/Resources, Attack, Defense). The manipulation of these entities follows strict state mutation rules.

Damage Calculation Algorithm:

Function that processes the numerical interaction between the aggressor's attack and the target's defense.

Management of random variables (Luck/Critical) contained within the function to maintain control over the source of randomness, which is vital for verification in smart contract environments.

Battle State Monitoring:

Logic for continuous monitoring of Victory/Loss conditions, ending the simulation once the termination condition is met.

Battle Transparency: Strict damage and turn calculation logic can be audited, allowing key actions (battle start, movements, results) to be securely and verifiably recorded on-chain through the Hive network.

Decentralized Resource Management: Character and resource statistics (Mana/Resources) can be directly mapped to tokens or digital assets managed by the blockchain.

🤝 Collaborative Project
This engine is part of a larger collaborative project: https://github.com/Starling74?tab=repositories.
