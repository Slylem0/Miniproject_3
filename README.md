# Miniproject_3
# MiniProject_3 - Pokémon Battle System (MVC Version)

**MiniProject_3** marks a major evolution from previous iterations. This version fully implements the **Model-View-Controller (MVC)** architectural pattern, delivering a clean separation of responsibilities, improved scalability, and maintainable code design for a turn-based Pokémon battle system.

---

## 👥 Authors

- **Pablo Nicolás Marín** – 2459440  
- **Nicolle López Colonia** – 2259630  
- **Juan Fernando Jiménez** – 2459394

---

## 🆕 What's New in This Version?

- ✅ Full **MVC architecture**: Separation of concerns between Model, View, and Controller layers.
- ✅ **Modular structure** with clearly defined packages (`models`, `view`, `controller`).
- ✅ Functional **graphical user interface (GUI)** using Java Swing.
- ✅ Pokémon logic includes attributes, attacks, damage handling, and battle turns.
- ✅ Trainer selection and random Pokémon assignment.
- ✅ Trainer images included (Pokémon images coming soon!).
- ✅ Clean and documented source code with object-oriented best practices.

---

## 🗂️ Architecture Overview

```plaintext
📦 src
 ┣ 📂 controller         → Handles user interaction and links View ↔ Model
 ┣ 📂 models             → Business logic: Pokémon, Trainers, Battle, Attacks
 ┃ ┣ 📂 batallas
 ┃ ┣ 📂 entrenadores
 ┃ ┗ 📂 pokemon
 ┣ 📂 view               → GUI using Swing (Battle setup, battle screen, trainer images)
 ┃ ┗ 📂 Gui
 ┗ main.java            → Entry point of the application


# 1. Compila todos los archivos .java que están organizados en subdirectorios bajo /src
javac -d bin src/**/*.java

# 2. Ejecuta la clase principal (main.java) desde la carpeta de salida
java main
