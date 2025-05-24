# Cubicka
A 3D Voxel Engine made in LWJGL. This is a adventure exploration game made by a team of 3. Project is a demo.

[Download and Play the Demo!](https://www.bluetorchgames.com/cubicka)

Cubicka is a fully custom 3D voxel engine built with LWJGL and OpenGL, focused on shader-driven graphics, intuitive UI/UX, and efficient terrain rendering.
Inspired by games like Minecraft, but tailored for performance, customization, and creative expansion.

Designed and Developed by: <br>
Liam Speakman <br>
Liam Kade <br>
Timothy Johnson <br>

Date: September 2020 to May 2021

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;Cubicka is an exploration game that allows the player to adventure through biomes and glide across the world to see procedurally generated voxels and structures. Survive as you traverse different biomes and uncover hidden secrets while escaping from lurking enemy creatures.


🛠️ Features

    🌍 Chunk-Based Voxel Terrain – Procedural terrain using noise functions and customizable biomes.

    🧱 3D Block World – Dynamic block ID array generation per chunk with VBO/VAO GPU rendering.

    💡 Lighting & Shaders – Custom GLSL shaders and lighting with directional lights.

    🧭 Biomes & Structures – Biome-specific structures and entities (e.g., mushrooms, cypress trees).

    🔁 Chunk Culling – Only visible chunks are rendered using frustum culling for performance.

    👁️ Camera & Controls – Entity-driven camera and player movement.

    🧪 Entity System – Flexible system for adding trees, mobs, structures, etc.

    🖱️ UI/UX First – Clean interaction systems and debug tools.

🎮 Gameplay

Explore a procedurally generated voxel world with structure and survive. Travel through different biomes while exploring an ever-expanding world around you.

### Controls:

| Key   | Action     |
| ------------ | -------------- |
| ↑ / W        | Move Foward    |
| ↓ / S        | Move Backward  |
| ← / A        | Move Left      |
| → / D        | Move Right     |
| Shift        | Sprint         |
| Space        | Jump           |
| LEFT Control | Hang Glider    |
| Left Mouse   | Interact       |
| E            | Backpack       |
| C            | Character      |
| f1           | Stats          |
| f2           | Controls       |
| f3           | Hide HUD       |
| f4           | Screenshot     |

📁 Code Structure

. <br>
├── Main.java &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Main <br>
├── res/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Resources folder (sprites, backgrounds, AI.txt) <br>
│   ├── Down.png <br>
    
🖼️ Screenshots / Visuals

![cubbanner](https://github.com/user-attachments/assets/b62cc790-2c3a-4d37-ad42-394e73944d7b)

🔧 Technologies Used

    ☕ Java 17

    🧱 LWJGL 3 (OpenGL bindings)

    📐 JOML (math library)

    🎨 GLSL (custom shaders)

    🔂 Buffered VBO/VAO rendering

    🧠 Perlin/Simplex Noise for procedural terrain

🚀 Getting Started

    To Play Cubicka:
    
    Download java 8 - Required
    [Java Download](https://www.java.com/en/download/)

    To run Cubicka:

    1. Clone or download the project.

        git clone https://github.com/MrTimmyJ/Cubicka.git
        cd Cubicka

    2. Use a Java IDE (e.g., IntelliJ, Eclipse).

    3. Ensure LWJGL libraries are properly linked.
    
    4. Run the main entry point in Main.java.

🪪 License

Cubicka is copyrighted under Blue Torch Games.

