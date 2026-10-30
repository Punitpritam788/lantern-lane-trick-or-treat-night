# 🎃 Lantern Lane: Trick-or-Treat Night

### IT'S HALLOWEEN. THE GHOSTS ARE AWAKE. AND THEY REMEMBER YOU. ☠️

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)
[![Halloween](https://img.shields.io/badge/Halloween-October%2031-FF7518?style=for-the-badge&logo=ghost&logoColor=white)](#)

**Happy Halloween! 🎃 October 31, 2026**

Looking for something spooky to play tonight?

Welcome to **Lantern Lane: Trick-or-Treat Night**, a browser-based 3D Halloween survival game built with JavaScript and Three.js.

Step into Old Hollow Graveyard as a little lantern-witch. Collect candy, escape restless ghosts, discover haunted surroundings and awaken Baron Gourdo, the terrifying pumpkin boss.

But there's something much worse than the ghosts themselves.

**THEY REMEMBER YOU.**

A ghost that hurts you can become a named Nemesis. It can evolve, gain supernatural traits, grow stronger and return in future runs to hunt you again.

This Halloween, your enemies aren't just obstacles. They're personal.

🕯️ Light your lantern.  
🍬 Collect the candy.  
👻 Survive the graveyard.  
☠️ Face the ghosts that remember you.

---

## 🎮 PLAY THIS HALLOWEEN

### Your Halloween-night challenge starts here!

🎃 **[PLAY THE GAME - LIVE DEMO](https://YOUR-USERNAME.github.io/lantern-lane-trick-or-treat-night/)**

💻 **[EXPLORE THE GITHUB REPOSITORY](https://github.com/YOUR-USERNAME/lantern-lane-trick-or-treat-night)**

*Replace the placeholder URLs with your actual published links.*

---

## 🌙 THREE WAYS TO SURVIVE THE NIGHT

### 🎃 1. STORY MODE - TRICK OR TREAT?

It's Halloween night, and Old Hollow Graveyard is full of ghosts guarding the candy they never got to eat.

Your mission is to collect 20 pieces of candy, survive three hearts' worth of danger and awaken Baron Gourdo.

Once the pumpkin boss appears, use your lantern pulse to hit him nine times.

Can you defeat him before the ghosts claim you?

**Three possible endings:**

- 🌟 Perfect Night - Defeat Baron Gourdo without losing a heart.
- 🎃 Sweet Victory - Defeat the boss after losing at least one heart.
- 👻 Defeat - The graveyard wins this time.

### ♾ 2. ENDLESS SIEGE - THE NIGHT NEVER ENDS

Think you can survive Halloween?

Forget the candy target. Fight through wave after wave of restless ghosts.

- Increasingly challenging waves.
- Health recovery after clearing a wave.
- Progressive lantern pulse improvements.
- Baron Gourdo returns every fifth wave.
- Persistent nemeses can stalk you.
- Personal best wave and score tracking.

The graveyard never ends. How long can you last?

### 📅 3. DAILY SIEGE - ONE DAILY CHALLENGE

Take on a daily survival challenge.

- Daily world seed based on the UTC date.
- Same daily seed for players entering the mode on the same date.
- Personal daily score tracking.
- Best wave and score records.

Challenge yourself to beat your previous result.

*Daily results are currently stored locally. There is no online leaderboard.*

---

## ☠️ THE NEMESIS SYSTEM - THEY REMEMBER YOU

### What if the ghost that defeated you came back?

This is the central gameplay experiment behind Lantern Lane.

When a ghost manages to hurt you, it can become a named Nemesis.

Unlike ordinary enemies, Nemeses can persist between runs.

They can:

- Receive randomly generated identities and names.
- Grow stronger through repeated encounters.
- Reach Level 5.
- Develop different supernatural traits.
- Remember previous encounters.
- Taunt you during gameplay.
- Return in future runs.
- Potentially return stronger after being banished.

The roster can hold up to eight nemeses.

### Five supernatural traits

| Trait | Behaviour |
|---|---|
| 💨 Swift | Increased movement speed |
| 🛡️ Armored | Additional health |
| 🫥 Sneaky | Uses stealth-like visibility behaviour |
| 🌀 Phasing | Can reposition close to the player |
| 😱 Wailing | Causes fear effects and slows movement |

Banish them using repeated lantern pulses.

But don't celebrate too early. Some can return with an even stronger grudge.

**The real Halloween horror is meeting the same ghost twice.**

---

## 🏮 COMBAT AND SURVIVAL

### Lantern Pulse

Your primary weapon against the supernatural.

- Expanding energy pulse.
- Damages nearby ghosts.
- Attacks Baron Gourdo.
- Damages powerful Nemeses.
- Recharge cooldown.
- Upgradeable pulse radius and recharge speed.

### 💨 Dash

When the ghosts get too close, escape.

- Quick movement burst.
- Brief invulnerability.
- Cooldown-based activation.
- Useful for avoiding enemy contact.

### ⬆️ XP AND LEVEL PROGRESSION

Collect candy, defeat enemies and clear waves to earn experience.

Level up and choose an upgrade.

Nine available upgrades:

| Upgrade | Gameplay effect |
|---|---|
| Wider Pulse | Increases pulse radius |
| Quick Wick | Reduces pulse cooldown |
| Fleet Foot | Increases movement speed |
| Spare Heart | Increases maximum health |
| Wisp Step | Reduces dash cooldown |
| Ember Aura | Damages nearby ghosts |
| Candy Magnet | Attracts nearby candy |
| Bright Mind | Increases XP gain |
| Cozy Sweater | Restores health |

Your upgrade choices can change how you approach the next encounter.

---

## 🌲 EXPLORE OLD HOLLOW GRAVEYARD

The graveyard is generated dynamically using a chunk-based procedural world system.

Explore an environment featuring:

- Gravestones and tombstones.
- Haunted pumpkins.
- Trees and graveyard decorations.
- Crypt-like structures.
- Procedural ground textures.
- Moonlit lighting.
- Atmospheric fog.
- Floating visual effects.

Nearby sections are generated as the player explores, while distant chunks are removed to manage the active environment.

### Procedural graphics

The current implementation generates its main game characters, ghosts, boss, textures and environment elements through code using Three.js geometry and CanvasTextures.

It does not require a collection of external 3D character models or texture packs.

---

## 👁️ DYNAMIC CAMERA AND HORROR EFFECTS

The camera reacts to nearby threats.

When an enemy approaches, the camera transitions towards a first-person view and faces the nearest danger.

Additional visual effects include:

- Third-person to first-person camera transitions.
- Camera movement and screen shake.
- Fear vignette.
- Damage effects.
- Lantern pulse animations.
- Particle bursts.
- Character animations.
- Atmospheric lighting and fog.
- Intro and ending cinematics.

---

## 🔊 PROCEDURAL AUDIO

The game generates its musical sequences and sound effects using the Web Audio API.

Included audio elements:

- Procedural background music.
- Lantern pulse effects.
- Ghost attack sounds.
- Candy collection sounds.
- Dash effects.
- Boss encounter sounds.
- Victory sequences.
- Volume and mute controls.

No separate music or sound-effect files are required by the current implementation.

---

## 🏆 ACHIEVEMENTS

There are 11 unlockable achievements.

- First Zap
- Sweet Tooth
- Ghost Buster
- Baron Slayer
- Flawless
- Nemesis Hunter
- Survivor
- Wave Rider
- Daily Dedication
- Leveled Up
- Slippery

Complete different challenges, improve your survival skills and unlock them all.

---

## 📤 SHARE YOUR HALLOWEEN SCORE

Finished a run?

Generate a score card that includes:

- Your score.
- Candy collected or wave reached.
- Ghosts zapped.
- Survival time.
- Nemesis information.
- World seed.

Share your results and challenge others to beat your run.

---

## 🎮 CONTROLS

### Desktop

| Action | Controls |
|---|---|
| Movement | WASD / Arrow Keys |
| Lantern Pulse | Space / Left Mouse Click |
| Dash | Shift / Q |
| Pause | P / Escape |
| Mute | M |
| Select Upgrade | 1 / 2 / 3 |

### Mobile

| Action | Controls |
|---|---|
| Movement | Drag on the left side |
| Lantern Pulse | 🏮 Button |
| Dash | 💨 Button |

### Gamepad

The browser Gamepad API is supported, including analog movement, attack, dash and pause inputs.

---

## 📱 PERFORMANCE AND GRAPHICS

The game includes:

- Automatic graphics quality.
- Low and High graphics options.
- Adaptive pixel ratio adjustment based on measured performance.
- Reduced camera shake and screen effects.
- Responsive display sizing.
- Touch-specific rendering adjustments.
- Cached procedural textures.
- Device-aware rendering settings.
- Chunk creation and cleanup.

---

## 💾 SAVE SYSTEM

The game uses browser LocalStorage to retain available player progression.

Saved information includes:

- Nemesis roster.
- Achievement progress.
- Best score.
- Highest Endless Siege wave.
- Daily results.
- Gameplay statistics.
- Audio settings.
- Graphics preferences.

No account or remote backend is required.

**Note:** Progress is browser-specific and can be lost when browser data is cleared. Progress is not synchronised across devices.

---

## 🛠️ TECHNOLOGY STACK

| Technology | Purpose |
|---|---|
| HTML5 | Game structure |
| CSS3 | User interface |
| JavaScript | Game logic |
| Three.js r128 | 3D rendering |
| WebGL | Hardware-accelerated graphics |
| Canvas API | Procedural textures and score cards |
| Web Audio API | Procedural audio |
| LocalStorage | Player progression |
| Pointer Events | Mouse and touch |
| Gamepad API | Controller support |

### Architecture

Lantern Lane is implemented as a single-file browser game.

- No separate frontend build process.
- No backend server.
- No database server.
- No account registration.
- No API keys.

Three.js is loaded through the cdnjs CDN, so an internet connection is required to retrieve the library.

---

## 💻 RUN LOCALLY

### Requirements

- A modern web browser.
- WebGL-capable graphics hardware.
- Internet access to load Three.js.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/lantern-lane-trick-or-treat-night.git
```

### 2. Enter the project directory

```bash
cd lantern-lane-trick-or-treat-night
```

### 3. Rename the main game file

Ensure the file is named:

```text
index.html
```

### 4. Start a local server

```bash
python -m http.server 8000
```

On Windows:

```bash
py -m http.server 8000
```

### 5. Open the game

```text
http://localhost:8000
```

---

## 🌐 DEPLOY WITH GITHUB PAGES

1. Upload `index.html` and `README.md` to the repository.
2. Open repository Settings.
3. Select Pages.
4. Choose Deploy from a branch.
5. Select `main` and `/root`.
6. Save.
7. Open your published GitHub Pages URL.

---

## 🎯 PROJECT GOALS

Lantern Lane explores:

- Browser-based 3D game development.
- Procedural environment generation.
- Persistent enemy progression.
- Survival gameplay and dynamic difficulty.
- XP and upgrade systems.
- Multi-mode replayability.
- Gamepad and mobile controls.
- Procedural audio and visuals.
- Local player progression.
- Performance-aware rendering.

The central design idea:

**An enemy should feel more memorable when it remembers the player.**

---

## 🔮 FUTURE DEVELOPMENT POSSIBILITIES

Potential expansion ideas include:

- Additional graveyard environments.
- More ghost types and bosses.
- Expanded Nemesis personalities.
- More lantern abilities and upgrades.
- Additional story chapters and endings.
- Online leaderboards.
- Competitive daily challenges.
- More environmental interactions.

These are future possibilities, not features currently claimed as implemented.

---

## 📜 CREDITS AND ATTRIBUTION

**3D Graphics:** [Three.js](https://threejs.org/)

**Reference:** [mrdoob/three.js](https://github.com/mrdoob/three.js)

**Game development practices:** [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills)

The source references Three.js r128 under the MIT License and performance optimization practices from the GameDev Agent Skills collection.

The original game code does not currently declare a separate project license. Add a license file before permitting reuse or redistribution.

---

## ❤️ HAPPY HALLOWEEN!

If you enjoyed your visit to Old Hollow:

- ⭐ Star the GitHub repository.
- 🎮 Play all three modes.
- 🍬 Collect all 20 candies.
- 🎃 Defeat Baron Gourdo.
- ☠️ Encounter and banish your Nemeses.
- ♾️ Survive as many waves as possible.
- 🏆 Unlock all 11 achievements.
- 📤 Share your score card.

Share your highest score, your best wave and the name of the ghost that gave you the most trouble.

---

# 🕯️ THE FINAL HALLOWEEN CHALLENGE

**It's October 31. The graveyard is awake. The lantern is fading.**

You have three hearts.

Twenty candies are waiting.

Baron Gourdo is watching.

And somewhere in the darkness, a ghost remembers exactly what you did last time.

### 🎃 HAPPY HALLOWEEN. SEE YOU IN OLD HOLLOW.

**Collect the candy. Protect your lantern. Never trust a ghost.**
