# Project-Ideas
Project Idea for Competiton

# Project: **“Culture Robot”**

Short Component List (clean & minimal)
Required

Arduino MEGA 2560

IR Proximity Sensor

16x2 LCD (with I2C module)

SG90 Micro Servo

Active Buzzer

3x Push Buttons

Small Breadboard

3x 220Ω Resistors

🔋 Power

USB Power Bank or

5V battery pack

A robot that:

* Detects when someone approaches
* Greets them
* Asks them to choose a culture (Romanian, Japanese, Greek, etc.)
* Tells a short myth, legend, or cultural fact
* Moves while speaking like it has personality

---

## Pick the Board

Use **Arduino MEGA**

* More memory (for storing text/stories)
* More pins
* Easier expansion

UNO would struggle if stories get longer.

---

## How It Works

### IR Sensor

Detects when someone comes close.

### LCD Screen

Displays:

* “Welcome to CulturaBot!”
* “Choose a culture:”
* Shows story text as it talks

### Servo Motor (SG90)

Moves:

* Head turns left/right while speaking
* Or raises a tiny arm dramatically

### Buzzer

Makes:

* Attention sound when someone arrives
* Dramatic “ding” before story
* Soft background rhythm during storytelling

### Optional Upgrade – Huskylens

You can make it:

* Only activate when it sees a face
* Or react differently to different people

---

# Example Theme (Since You're in Romania 👀)

### Romanian Culture Mode:

* Talks about:

  * The legend of **Dracula**
  * The myth of **Mărțișor**
  * Stories from **Transylvania**
* Displays traditional patterns on LCD (ASCII art 👀)

---

# 🇬🇷 Greece

### Mythology

* **Zeus** – King of the gods, throws lightning bolts.
* **Athena** – Goddess of wisdom and strategy.
* The legend of the **Minotaur** in the Labyrinth.

 Robot line idea:
“Welcome to Greece! Land of gods, heroes, and monsters. Beware… the Minotaur still waits in the Labyrinth.”

---

### Ancient Architecture

* The **Parthenon**
* Built over 2,400 years ago in Athens.

Robot movement idea: servo turns slowly like it’s showing a monument.

---

### Theater

* Greece invented drama and theater.
* Tragedy and comedy masks.

Your robot could say:
“Without Greece, there would be no drama today.”

---

# 🇯🇵 Japan

### Samurai

* The warrior code: Bushido.
* Honor, loyalty, discipline.

Mention:

* **Miyamoto Musashi**

Robot line:
“In Japan, the way of the warrior was not just fighting… it was a philosophy.”

---

### Traditions

* Cherry blossom season (Sakura).
* Tea ceremony.
* Shinto shrines.

You could display a little ASCII cherry blossom on the LCD.

---

### Folklore

* Yokai (supernatural spirits).
* Kitsune (fox spirit).

Robot could whisper:
“Some spirits… still walk among humans.”

Spooky servo head turn = chef’s kiss.

---

# 🇫🇷 France

### Landmarks

* The **Eiffel Tower**
* Built in 1889.

Robot line:
“Originally hated… now one of the most loved monuments in the world.”

---

### Culture

* Famous for art, fashion, and cuisine.
* Croissants and baguettes.

Mention:
* **Napoleon Bonaparte**

---

### Art

* The **Louvre Museum**
* Home of the **Mona Lisa**

Robot could say:
“In France, even a smile becomes immortal.”

---

# 🇯🇵 Bonus Upgrade Idea

Make the robot ask:
“Choose a culture: Press 1 for Greece, 2 for Japan, 3 for France.”

Then:

* Servo moves differently for each culture.
* Buzzer plays a tiny pattern unique to each country.
* LCD changes style.

