Stat System & Custom Unity Editor Tools

This Unity project is a comprehensive Stat System implementation that allows for managing character stats in a highly modular and customizable way.
In addition to the core stat functionality, I've developed custom editor tools to enhance productivity and provide easy-to-use UI for managing stats directly from the Unity Editor.

Features

• Advanced Stat System
• Modular stat architecture that uses ScriptableObjects to define various character stats.
• Supports primary stats (e.g., Strength, Agility) and derived stats (e.g., Health, Damage) that are influenced by other stats.
• Built-in stat modifiers to easily adjust values based on abilities, items, or temporary effects.
• Dependency support for stats, where one stat's value can affect another (e.g., increasing Strength increases Damage).


Custom Editor Tools

• Created a Scriptable Collection Editor for managing stat-related ScriptableObjects directly in the Unity Editor.
• Includes custom inspector views to easily manipulate and visualize stat data without requiring manual code changes.
• Custom UI using UIElements and UI Toolkit for an intuitive workflow.
• Create, duplicate, or remove stats easily within the editor.

In-Depth Stat Customization

• Stat caps and limits to prevent imbalance (e.g., Health capped at a maximum value).
• Stat Progression curves to define how stats evolve as characters level up.
• Buffs and debuffs system for applying temporary modifiers to stats.

Dynamic and Flexible

• Easily extendable to add new stats or features.
• Suitable for a variety of game types, including RPGs, action games, and simulations.

HOW TO USE

Clone the Repository

• Clone this repository to your local machine using Git.

git clone <repository-url>

Open in Unity

• Open the project in Unity. This project was developed using Unity 2021.3.x; using the same or a newer version is recommended.

Using the Stat System

• Navigate to the StatHelperDatabase asset to create or manage existing stats.
• Use the custom editor window under Window > StatHelper > StatHelperDatabase to add, remove, or edit stats.
• Modify stats directly using the editor window. This allows you to see how changes affect your character or game objects in real time.

Extending the System

• To add a new stat, create a new ScriptableObject using the provided tools in the editor.
• To create new modifiers, use the StatModifier class to define new effects for abilities or items.


Future Improvements & Ideas

• Stat-based Abilities: Implement abilities that consume or scale with stats (e.g., magic spells that scale with Intelligence).
• AI Stat Integration: Extend the stat system to enemies and NPCs for a consistent approach to balancing the game.
• UI Integration: Create player-facing UI elements to display stat values, allowing real-time feedback for buffs/debuffs.

I hope you find this project helpful for your game development needs. Feedback and contributions are greatly appreciated!


