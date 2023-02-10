# AltTab

This is a fork of @lwouis's excellent [AltTab app](https://alt-tab-macos.netlify.app/) that adds per-shortcut `previous window` bindings. See [this PR](https://github.com/lwouis/alt-tab-macos/pull/2311) for more info.

## Installation
As of this moment I haven't uploaded any binaries, largely because I don't have an apple developer certificate. I plan to make the app binary available as a download on GitHub when I do. 

Until then, follow [the build instructions](https://alt-tab-macos.netlify.app/contributing) to create a build for your machine:

>This project has minimal dependency on Xcode-only features (e.g. InterfaceBuilder, Playgrounds). You can build it by doing:
>
>- `scripts/codesign/setup_local.sh` to generate a local self-signed certificate, to avoid having to re-check the `System Preferences > Security & Privacy` permissions on every build
>- Either open `alt-tab-macos.xcworkspace` with XCode, or use the cli: `xcodebuild -workspace alt-tab-macos.xcworkspace -scheme Debug` to build the .app with the `Debug` build configuration

Then find the app using Spotlight and optionally move it to your `Applications` directory.
