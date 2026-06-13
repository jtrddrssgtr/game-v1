# ⚔️ Welcome to the Trinket Dungeon!

An immersive, endless text-based rogue-like RPG built natively in Java. Face dangerous enemies, manage your health potions, and push deeper into the dungeon to maximize your final high score!

---

## 🎮 How to Play

### 💻 System Requirements
* **Java:** Java Runtime Environment (JRE) version 8 or higher installed on your machine.
* **Terminal:** A command-line terminal window. 
  *(Tip: Windows users should use **Windows Terminal** or PowerShell instead of the legacy CMD for optimal visual alignment and formatting).*

### 🚀 Running the Game
1. Open your terminal or command prompt.
2. Navigate to the folder containing your compiled `DungeonGame.jar` file:
   ```bash
   cd path/to/your/game/folder
   ```
3. Launch the game using the standard Java archive runner command:
   ```bash
   java -jar DungeonGame.jar
   ```

---

## 🕹️ Gameplay & Controls

The game operates completely via numeric command inputs. Type your number and press `Enter` to execute your choice.

### 🔴 Combat Loop Options
When an enemy blocks your path, you have three tactical choices:
* `1` **Attack:** Strike the enemy. Deals random damage (`10-59`), but exposes you to an immediate enemy counterattack.
* `2` **Drink Health Potion:** Consumes 1 potion to recover `30 HP`. 
* `3` **Run away!:** Safely escape the current encounter and reset into a new room.

### 📦 Loot & Scoring
* **Score System:** Every defeated monster awards you `+10 points`.
* **Potion Drops:** Slain enemies have a `50% chance` to drop a replacement health potion to sustain your journey.
* **Progress Choice:** After every victory, choose `1` to venture deeper into danger or `2` to safely exit the dungeon and record your final score.

---

## 👾 Dungeon Bestiary

Prepare yourself to face random encounters with varying levels of health:
* 💀 **Skeleton**
* 🧟 **Zombie**
* 🐺 **Warrior Wolf**
* 🥷 **Assassin**

---

## 🛠️ Code Structure & Compilation

For developer modifications or manual compilation from source:

* **Main Class:** `DungeonGame.java`
* **Dependencies:** Uses native standard libraries only (`java.util.Scanner`, `java.util.Random`).

### Manual Compilation
To compile the source code file from your terminal:
```bash
javac DungeonGame.java
```
To run the compiled class file directly:
```bash
java DungeonGame
```

---

## 📄 License
This codebase is open-source and free to distribute or modify under the standard MIT License.
