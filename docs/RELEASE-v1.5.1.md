# VRChat Lingua v1.5.1 Beta

> **Unofficial test build. This is not a stable release.**

A standalone Windows companion for VRChat with translated captions, screenshot translation, a SteamVR overlay, and outgoing translated speech.

## What's changed

- Fixed an error that prevented the voice license dialog from opening on the first preview of multilingual built-in voices.
- The outgoing language picker now shows only languages with a usable female narrator. Unusable Windows voices are hidden without uninstalling system voice packs.
- Both offline speech model packs are embedded in the executable. All **159 built-in female presets across 32 languages** were individually tested for audible synthesis.
- The Beta-labeled portable build shows the unofficial release status in the title bar and Preferences.

## Portable download

In [v1.5.1 Beta → Assets](https://github.com/LinguaNeko/VRChat-Lingua/releases/tag/v1.5.1), choose the **Windows x64 portable EXE** and run it directly. No application installation, separate DLL, or voice pack is needed.

The release page lists the available portable builds and their SHA-256 checksums. The original `VRChatLingua-Neko-v1.5.1.exe` was built before the in-app Beta label.

Requires Windows 10/11 x64 and .NET Framework 4.8. Close the running app before replacing its EXE. Local voice previews do not need VB-CABLE. To route translated speech into VRChat, configure the paired virtual cable separately.

See the [English user guide](USAGE.md) and [four-language guide](LANGUAGES.md) in English (US), Simplified Chinese, Japanese, and Korean.
