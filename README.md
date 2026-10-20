# Aura TV Launcher

**A lightweight, remote-friendly Android launcher concept for compatible Android TV boxes and low-resource devices.**

Aura TV Launcher is intended to provide a simple home screen with app shortcuts, directional remote navigation, and quick access to system utilities.

> **Note:**  Compatibility and performance depend on the device and firmware.

## Features

- Native Android interface designed to keep the experience simple.
- TV remote navigation using directional buttons and selection.
- App discovery intended to support standard Android and TV launcher activities.
- Dark home-screen design with app cards and utility shortcuts.
- Intended to avoid unnecessary telemetry; verify permissions and source code before making privacy claims.

## Downloads

Download published builds from the [GitHub Releases page](https://github.com/sam4duh/Aura-TV-Launcher/releases).

Release assets are intended to include:

- `AuraTV-Launcher-v1.0.apk` — Android application package.
- `AuraTV-Launcher-Source.zip` — Android Studio project source archive.

If no release is published yet, the files may not be available at the link above.

## Installation

1. Download the APK from the Releases page.
2. Transfer it to your Android TV or TV box if needed.
3. Open it with the device's file manager or package installer.
4. If Android prompts you, allow installation for the app you are using to open the APK.
5. Install and launch Aura TV Launcher.

Only install APKs from sources you trust.

## Set as the default launcher

If your device supports third-party default home apps:

1. Open system settings.
2. Find the default Home app or launcher setting.
3. Select Aura TV Launcher, if available.
4. Test the remote's Home button.

Some manufacturer-modified firmware restricts third-party launchers. The steps and availability vary by device.

## Restore the original launcher

Aura TV Launcher is intended to be installed as a regular app, not as a firmware replacement. If needed, use Android settings to select the original launcher or uninstall Aura TV Launcher. Exact behavior depends on your device.

## Build from source

1. Download or clone this repository.
2. Extract `AuraTV-Launcher-Source.zip` if you downloaded the source archive from Releases.
3. Open the project directory in a compatible version of Android Studio.
4. Allow Gradle synchronization to complete.
5. Build the project using its configured build variant.

The required Android Studio, JDK, Gradle, and SDK versions should be taken from the actual project build files. Do not assume they are verified until a clean build succeeds.

## Compatibility

The project is described as targeting Android 5.0 (API 21) and later. Actual compatibility must be confirmed from the source project's build configuration and tested on target devices. Modified Android firmware can change launcher selection, package visibility, and remote-control behavior.

## Security and privacy

Before installing or distributing a build, review the manifest, requested permissions, package visibility declarations, network access, and third-party dependencies. Do not make claims such as “zero tracking,” “no network access,” or a specific RAM footprint unless verified from the actual APK and source.

## License

See [LICENSE](LICENSE) for the project's license. Third-party trademarks, logos, and other assets may have separate terms.

## AI Disclosure

This project was developed by (AI) tools. The code, functionality, and compatibility may require further testing and improvement.
