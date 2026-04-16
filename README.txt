Fanta Anaar Slice Game - Android-ready mobile-adaptive package

This ZIP includes the latest mobile-adaptive HTML game and the files needed to wrap it in Capacitor so a developer can build an APK quickly.

Included
- www/index.html  -> mobile-adaptive game file
- package.json
- capacitor.config.ts
- android_examples/ -> optional plain WebView sample files

Quick build steps
1. Install Node.js
2. Open terminal in this folder
3. Run:
   npm install
4. Add Android project:
   npx cap add android
5. Sync files:
   npx cap sync android
6. Open in Android Studio:
   npx cap open android
7. In Android Studio:
   - let Gradle sync complete
   - Build > Build Bundle(s) / APK(s) > Build APK(s)

GitHub Actions / online build
- This package is also suitable for a GitHub Actions Android APK workflow.

Notes
- The game is now mobile-adaptive and portrait-first.
- Best score uses local device storage.
- For app icons, splash screen, and signing, configure inside Android Studio.

Alternative
A plain Android WebView example is included in android_examples if the developer prefers not to use Capacitor.
