# MelkiCAD Print for Android

This folder packages the repository's web application as an offline Android app using Capacitor.

Run **Build MelkiCAD Print Android APK** from GitHub Actions. The workflow creates an installable debug APK and uploads it as the artifact **MelkiCAD-Print-Preview-Android-APK**.

The APK bundles the HTML, CSS, JavaScript, fonts, icons, and service worker. It does not depend on the Pages website for normal use.

The native SaveFile plugin uses Android's system document picker so users can choose where exported files are saved.