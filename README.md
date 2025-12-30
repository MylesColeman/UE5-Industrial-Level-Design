# UE5: Industrial Level Design Showcase
**University Year 1 | Game Creation Module**

A technical level design showcase in Unreal Engine 5, focused on environment blockout, Blueprint-driven interactions, and physics-based set pieces.

## 📺 Project Showcase
[!["Abandoned Industrial Showcase"](https://img.youtube.com/vi/vIX6xYS-bbo/0.jpg)](https://www.youtube.com/watch?v=vIX6xYS-bbo)
> **[🔗 View the full technical breakdown on my Portfolio](https://sites.google.com/view/myles-coleman/projects/unreal-engine-level-design)**

---

## 🕹️ Project Overview
This project demonstrates a blend of environmental storytelling and technical scripting. Developed during my first year, it features two distinct scenarios designed to test player navigation through logic-based and physics puzzles.

## 🛠️ Key Technical Features

### Technical Scripting & Interaction
* **Dynamic Interaction System:** Developed a Blueprint-based interaction system for world objects, including a functional tower crane that lifts a vehicle via a **Timeline**-driven animation.
* **Camera Blending & Cutscenes:** Implemented `SetViewTargetWithBlend` logic for a security monitor interaction. Activating the monitor triggers a camera shift to highlight a toll bar opening elsewhere in the level, providing visual feedback for player progression.
* **Logic Gates:** Engineered a "flip-flop" door puzzle where a single input toggles the state of two warehouse doors simultaneously (one opening while the other closes).

### Physics & Hazards
* **Chaos Destruction:** Utilised Unreal's **Chaos Physics** system to create a destructible window set-piece. The glass fractures and is propelled outward by a physics impulse, creating a new traversal path.
* **Health & Hazard System:** Scripted a damage-over-time system for environmental hazards (spikes), dealing 10 damage per second. This is integrated with a respawn system that resets the player and level state upon death.

### UI & UX
* **UMG HUD:** Developed a custom HUD to display health and objective updates.
* **Readable Assets:** Created a "Note" system where players can view 2D assets (such as exit codes) to solve progression puzzles.

## 📂 Asset Attribution
* **Custom Models:** Garage doors, security fencing, crates, and pylons were modelled by me in **Autodesk Maya**.
* **Custom Textures:** Generated multiple textures in **Adobe Substance 3D Painter**.
* **Engine Tools:** Environment blockout utilised **CubeGrid**.
* **Audio:** Interaction sound effects implemented via the internal Unreal Audio Engine.

## 💻 Technical Specs
* **Engine:** Unreal Engine 5.3
* **Scripting:** Blueprints (Visual Scripting)
* **Frameworks:** Chaos Physics, UMG (UI), Blueprint Interfaces
