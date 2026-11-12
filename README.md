# NEON RUN 🏃‍♂️⚡

**NEON RUN** is an original, lightweight, offline three-lane endless runner for Android, inspired by the *genre* of Temple Run and Subway Surfers. It does not use their artwork, branding, or game assets.

## Features
- 🎮 Three-lane obstacle dodging
- 👆 Swipe left/right to change lanes, up to jump, down to slide
- 💎 Collect crystals and increase your score
- 🚀 Gradually increasing running speed
- 🏆 Persistent local best score
- 📱 Portrait-friendly touch gameplay
- 🌐 Runs offline with HTML5 Canvas inside an Android WebView
- 🔒 No login, analytics, ads, or network permission

## How to play
Avoid pink walls by jumping and purple low barriers by sliding. Collect golden crystals for bonus points. Survive as long as you can.

| Action | Touch | Keyboard |
| --- | --- | --- |
| Move left/right | Swipe left/right | ← / → or A / D |
| Jump | Swipe up | ↑ or W |
| Slide | Swipe down | ↓ or S |

## Download an APK
1. Open the [Actions tab](https://github.com/iamAdarshAnand/Neon-Run/actions).
2. Select **Build Android APK**.
3. Run the workflow or open a successful run.
4. Download the **Neon-Run-debug-apk** artifact.
5. Extract the artifact ZIP and install `app-debug.apk` on Android.

The debug APK is intended for testing, not Play Store publication. The APK is only available after a successful workflow run.

## Build locally
Requirements: JDK 17, Android SDK Platform 35, Build Tools 35, Gradle 8.10.2.

```bash
gradle assembleDebug
```

Output: `app/build/outputs/apk/debug/app-debug.apk`

## Project structure
```
.github/workflows/android-apk.yml  # CI APK build
app/src/main/assets/index.html     # Offline game
app/src/main/java/dev/adarsh/neonrun/MainActivity.java
app/src/main/AndroidManifest.xml
app/build.gradle
build.gradle
settings.gradle
```

## Technology
HTML5 Canvas, vanilla JavaScript, Android Java WebView, Gradle, GitHub Actions. No external game engine or runtime asset downloads.

## Roadmap
Sound effects, character skins, power-ups, richer 3D-style scenery, pause menu, improved accessibility and gameplay balancing.

## Author
**Adarsh Anand** · [GitHub](https://github.com/iamAdarshAnand) · [Portfolio](https://adarshanand.is-a.dev)

## License
MIT. See [LICENSE](LICENSE).
