# 🚗 Son Cars Game

**Son Cars Game** is a browser-based car racing game designed for both **Android mobile devices and desktop computers**. The project is built using pure **HTML, CSS, and JavaScript**, without requiring React, WordPress, or other frameworks.

The game focuses on fast-paced highway racing, touch controls, speed selection, realistic-looking CSS cars, traffic, scoring, lives, distance tracking, and nitro acceleration.

---

## 🎮 Features

### 🏠 Home Menu

* Son Cars Game branding
* Game selection menu
* Responsive design
* Mobile-friendly interface
* Easy navigation between games

### 🏎️ Highway Racer

* Highway racing gameplay
* Multiple traffic cars
* Collision detection
* Score system
* Lives system
* Distance counter
* Increasing difficulty
* Speed display
* Nitro acceleration
* Android touch controls
* Keyboard controls for desktop

### 🪙 Coin Rush

* Collect coins while driving
* Avoid traffic
* Score points
* Lives system
* Mobile touch controls
* Swipe steering
* Increasing speed

### ⚡ Speed Selection

Players can select their preferred speed before starting a race:

* 🐢 **Slow** – Beginner friendly
* 🚗 **Normal** – Recommended
* 🏎️ **Fast** – For experienced players
* 🚀 **Turbo** – Extreme speed

### 📱 Mobile Support

The game is designed to work on:

* Android phones
* Android tablets
* Desktop computers
* Laptops
* Touch-screen devices

The interface automatically adjusts to different screen sizes.

---

# 📁 Project Structure

```text
son-cars-game/
│
├── index.html
└── README.md
```

### `index.html`

The main homepage of Son Cars Game.

It contains:

* Game title
* Game menu
* Game selection
* Car presentation
* Navigation buttons

### `highway-racer.html`

The main highway racing game.

Features include:

* Speed selection
* Player car
* Traffic cars
* Collision detection
* Score
* Lives
* Distance
* Nitro
* Mobile controls

### `coin-rush.html`

Coin collection racing game.

Features include:

* Coins
* Traffic
* Score
* Lives
* Touch controls
* Swipe controls

---

# 🛠️ Technologies Used

The project uses:

### HTML5

Used to create the structure of the game.

### CSS3

Used for:

* Game interface
* Responsive design
* Car designs
* Road
* Animations
* Buttons
* HUD
* Mobile layout
* Visual effects

### JavaScript

Used for:

* Game logic
* Player movement
* Traffic generation
* Collision detection
* Score calculation
* Speed control
* Nitro
* Lives
* Distance
* Game loop
* Touch controls

---

# 🚀 How to Run the Game

## Method 1 – Computer

1. Download or clone the project.
2. Open the project folder.
3. Double-click:

```text
index.html
```

4. The game will open in your browser.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

---

# 📱 Method 2 – Android

You can run the game directly from a web server or hosting service.

For local testing:

1. Put the project files on a web server.
2. Open the website using Chrome on Android.
3. Open:

```text
index.html
```

4. Select a game.
5. Select your speed.
6. Start racing.

The game supports touch controls.

---

# 🎮 Controls

## Android

### Steering

```text
◀       ▶
```

Use the left and right buttons to control the car.

You can also swipe:

```text
Swipe Left  → Move Left

Swipe Right → Move Right
```

### Nitro

Press:

```text
NITRO
```

to temporarily increase your speed.

---

## Desktop

Use:

```text
← Left Arrow
→ Right Arrow
```

to steer the car.

---

# 🏁 Highway Racer Gameplay

The objective is to drive as far as possible without crashing.

You earn points by successfully passing traffic cars.

Example:

```text
Traffic passed = +10 points
```

The game becomes more challenging as the race continues.

---

# ❤️ Lives

The player starts with:

```text
❤️ ❤️ ❤️
```

Each collision removes one life.

When all lives are lost:

```text
GAME OVER
```

is displayed.

The player can then choose:

```text
PLAY AGAIN
```

or

```text
HOME
```

---

# ⚡ Nitro System

Nitro temporarily increases the vehicle's speed.

Normal speed:

```text
Game Speed × 1
```

Nitro:

```text
Game Speed × 1.8
```

Nitro can be used strategically to overtake traffic and increase the distance covered.

---

# 🏎️ Speed System

Before starting a race, the player chooses one of four speed levels.

| Mode      | Speed | Difficulty |
| --------- | ----: | ---------- |
| 🐢 Slow   |     3 | Easy       |
| 🚗 Normal |     5 | Medium     |
| 🏎️ Fast  |     7 | Hard       |
| 🚀 Turbo  |    10 | Extreme    |

The game also displays the current speed in the HUD.

Example:

```text
SPEED
100 km/h
```

---

# 🎨 Car Design

The current version uses CSS to create detailed car graphics.

The car includes:

* Car body
* Bonnet
* Roof
* Windshield
* Mirrors
* Headlights
* Grille
* Wheels
* Body shading
* Reflections
* Shadows

Different traffic cars use different colors.

---

# 📊 Game HUD

During gameplay, the interface displays:

```text
SON CARS

SCORE       SPEED       DISTANCE       LIVES
 100        120 km/h       450m        ❤️❤️❤️
```

This allows the player to monitor their performance during the race.

---

# 🔧 Customization

Developers can modify the game by editing the CSS and JavaScript.

You can change:

* Car colors
* Road colors
* Speed
* Traffic frequency
* Number of lives
* Nitro power
* Score rewards
* Game difficulty
* Button styles
* Background
* Game title

---

# 🔮 Future Development

The project can be expanded into a complete racing game with features such as:

* 🏎️ Realistic car images
* 🚘 Multiple selectable cars
* 🏆 Championship mode
* 🏁 Racing against AI opponents
* 🗺️ Multiple tracks
* 🌆 City racing
* 🌧️ Rain weather
* 🌙 Night racing
* 🔥 Car damage system
* ⛽ Fuel system
* 🪙 Coins and virtual currency
* 🛠️ Car upgrades
* 🎨 Car customization
* 🚀 Advanced nitro system
* 🎵 Engine sounds
* 🔊 Sound effects
* 🎶 Background music
* 🏆 Leaderboards
* 💾 Local player profiles
* 📈 High-score storage
* 🌐 Online multiplayer
* 📱 Android APK version
* 🎮 Gamepad support
* 🥇 Achievements
* 🚗 3D car models
* 🌍 Different countries and roads

---

# 📌 Recommended Next Upgrade

The biggest visual improvement would be replacing the CSS cars with **realistic car image assets or 3D models**.

A future version could provide a garage such as:

```text
             SON CARS GARAGE

       🚗         🚘         🏎️

    SON GT      SON R8      SON X

    $5,000      $15,000     $30,000

       [SELECT]   [SELECT]   [LOCKED]
```

Players could then earn coins from races and use them to purchase and upgrade cars.

---

# 👨‍💻 Developer

**Son Cars Game**

Developed using:

```text
HTML5
CSS3
JavaScript
```

---

# 📄 License

This project can be modified and customized for personal or educational purposes.

You may add your own:

* Cars
* Tracks
* Sounds
* Logos
* Game modes
* Features
* Branding

---

# ⭐ Project Vision

**Son Cars Game** aims to become a modern mobile racing game combining:

> **Speed + Cars + Competition + Fun**

🏁 **Drive Fast. Race Smart. Become the Champion.**

**SON CARS GAME**
