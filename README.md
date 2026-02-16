# Chip8Emulator
High-performance Chip-8 interpreter written in C++17 &amp; SDL2. Features a scratch-built GUI renderer, live disassembler, and debug tools.



# Chip8Emulator
**Сhip8Emulator** is a high-performance Chip-8 emulator featuring a custom-built, sci-fi inspired user interface. Written in C++ using SDL2.

![Screenshot](screenshot.png) 

## ✨ Key Features
*   **Custom UI Engine:** No heavy UI libraries (like Qt or ImGui). All buttons, panels, chamfered borders, and vector fonts are rendered manually using raw SDL2 primitives.
*   **Cyberpunk Aesthetic:** Glass-morphism panels, pixel-grid effects, and neon accents.
*   **Real-time Disassembler:** View memory opcodes and assembly instructions while the game is running.
*   **Robust Core:** Full implementation of the Chip-8 instruction set (Opcode support).
*   **Modern Controls:** WASD support mapped to the original 4x4 keypad.

## 🎮 Controls
| Key | Action |
| :--- | :--- |
| **W / A / S / D** | Movement (Keypad 2, 4, 8, 6) |
| **SPACE** | Action / Fire (Keypad 5) |
| **1 / 2 / 3** | Other Keypad functions |
| **P** | Pause / Resume |
| **ESC** | Stop Emulation |

## 🛠 Tech Stack
*   **Language:** C++17
*   **Graphics:** SDL2 (Simple DirectMedia Layer)
*   **Platform:** Windows (easily portable to Linux/macOS)

## 🚀 How to Build
1.  Install **Visual Studio 2022** (Desktop development with C++).
2.  Install **SDL2** library (via NuGet or manually).
3.  Open the solution, ensure `SDL2.dll` is in the output directory.
4.  Build in **Release (x64)** mode for best performance.

---
*Developed as a study project to explore emulation and low-level UI rendering.*
