# background_location_fixed

A patched version of the original [`background_location`](https://github.com/almoullim/background_location) Flutter plugin, updated to be compatible with **Flutter 3.24+** and the latest Android Gradle Plugin (AGP).

## ✨ What's Updated

- ✅ Added `namespace` to `build.gradle` (required for Android Gradle Plugin 7.0+).
- ✅ Removed deprecated `registerWith(Registrar)` method (which is no longer supported in newer Flutter versions).
- ✅ Ensured compatibility with modern Flutter plugin embedding (v2).

## 📦 How to Use (in your `pubspec.yaml`)

```yaml
dependencies:
  background_location:
    git:
      url: https://github.com/burakyilmaz/background_location_fixed.git
      ref: master
