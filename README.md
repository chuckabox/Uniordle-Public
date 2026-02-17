# 🎓 Uniordle

**Uniordle** is a high-stakes, academic-themed word puzzle game built with Flutter. Unlike standard clones, Uniordle features a full progression system where players earn their way from Undergraduate to Bachelor and beyond through specialised majors and merit-based ranking.

[Play Uniordle here](https://uniordle.com)

## Key Features

* **Academic Progression:** Earn **Merits** to rank up and **Credits** to unlock new **Majors** (word categories).
* **The Grind:** * **Level Up:** Every 5 levels earns you a Credit.
* **Rank Up:** Every 10 levels increases your academic standing.


* **High Stakes:** Abandoning a game or losing results in a scaling penalty—the higher your level, the more you stand to lose.
* **Mastery System:** Solve every word in a major to for mastery. Master every major for a major reward.
* **Cross-Platform:** Smooth performance on Web and Windows via Flutter.

## How to Play

1. **Select a Major:** Choose your starting category from the Home Menu.
2. **Choose your settings** Pick the number of attempts and length of word to be guessed.
3. **Solve the Puzzle:** Guess the hidden university-themed word.
* 🟩 **Green:** Correct letter, correct spot.
* 🟨 **Yellow:** Correct letter, wrong spot.
* ⬛ **Grey:** Letter not in the word.


4. **Advance:** Accumulate Merits to rank up and gain various bonuses.

## Installation & Setup

### Prerequisites

* [Flutter SDK](https://docs.flutter.dev/get-started/install)
* [Dart SDK](https://dart.dev/get-dart)
* Visual Studio with "Desktop development with C++" (for Windows builds)

### Quick Start

```bash
# Clone the repo
git clone https://github.com/chuckabox/uniordle.git

# Install dependencies
cd uniordle
flutter pub get

# Run on Web
flutter run -d chrome

# Run on Windows
flutter run -d windows

```

## Roadmap

* [ ] **Social Auth:** Integration for Google and Facebook logins.
* [ ] **Profile Customization:** User-editable profiles (username, password, avatar).
* [ ] **Google/Apple Stores** Policies, store page etc.
* [ ] **Autoplay Music** Does not autoplay sometimes on web.
* [ ] **Polishing:** Audio cues for UI feedback and password strength validation.
* [ ] **Words:** Increase possible word lists for each major.
* [ ] **Forgot Password:** Add password resetting (two screens: forgot, and reset)
* [ ] **Anti-Cheat Logic:** Implement "Active Game" session tracking to prevent users from refreshing the browser to avoid a loss or reset their streak.
* [ ] **Bug** Refreshing in-game while in-game music is playing -> Get sent back to home screen -> in-game music doesn't switch to menu music
* [ ] **Bug** Attempt at preventing cheating by navigating to home screen ok refresh causes the play button in game setup to redirect to home screen
* [ ] **Feature** Need to indicate user on which length words have been mastered or progressed through since its currently unknown
* [ ] **Bug** Typing fast when game loads has keyboard sounds all play at once eventually
* [ ] **Update** Improve appearance of dialog of sync conflict
* [ ] **Bug** Exiting game while submitting causes crash
* [ ] **Feautre** Switch where leaderboard and game transcript are between stats and profile
* [ ] **Bug** Ratelimit accounts made
* [ ] 
© 2026 Peter Ma. All Rights Reserved.
