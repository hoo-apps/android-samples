## Getting Started with Android Studio

#### Download and Installation

Android Studio can be downloaded from the [Android Developer site](http://developer.android.com/sdk/index.html). The site has instructions on how to download and setup Android Studio.

*Note*: For Windows users, installing Android Studio in `C:\Program Files` or `C:\Program Files (x86)` can lead to permissions issues with the SDK and AVD (Android Virtual Device) manager. It might be better set the install location to a different directory on your computer.

#### Android Studio Themes
To change the theme in Android Studio, go `File > Settings > Appearance` and then under `UI Options` select your theme of choice (`Darcula` is recommended)

If none of the built-in themes suit your fancy, other themes can be found at [Color Themes](http://color-themes.com/?view=index). Simple download the `.jar` file and select the file in `File > Import Settings...`

#### Why Android Studio? Why not Eclipse?

Google officially [phased out support for the Eclipse ADT plugin]( http://android-developers.blogspot.com/2015/06/an-update-on-eclipse-android-developer.html) at the end of 2015 to focus on the development of Android Studio. Android Studio is an extension of [IntelliJ](https://www.jetbrains.com/idea/) by JetBrains.

## SDK Manager

#### General Installation (Build Tools, etc.)

To develop for different versions of Android, various versions of the Android API can be downloaded with the SDK Manager. The developer website [provides a guide](http://developer.android.com/sdk/installing/adding-packages.html) on how to install different build tools.

#### Android Virtual Device (AVD) System Images

To use an emulator on your computer, you have to install a system image first. For any given API in the SDK Manager, the there are several different types of system images that you can choose from:

- `ARM EABI v7a`
- `Intel x86 Atom_64`
- `Intel x86 Atom`
- `Google APIs ARM EABI v7a`
- `Google APIs Intel x86 Atom_64`
- `Google APIs Intel x86 Atom`

The `Google APIs Intel x86 Atom_64` and `Google APIs Intel x86 Atom` come with full suport for Google APIs and are hardware excelerated for Intel chips, so they are the best option (assuming your computer has an Intel chip; most do)
