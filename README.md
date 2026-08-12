# Tool Launcher

Tool Launcher is a customizable Windows desktop launcher for organizing applications into visual categories. It combines application management, a configurable hardware dashboard, theme presets, local image processing, and AI-assisted prompt workflows for backgrounds, icons, and banners.

Tool Launcher 1.0 is designed for Windows and stores its launcher configuration locally. The AI creation tools in this release help compose prompts and import finished images; they do not generate images directly inside the application.

## Features

- Organize applications in custom categories.
- Add `.exe`, `.bat`, `.cmd`, and `.lnk` files by file picker or drag and drop.
- Reorder categories and applications by drag and drop.
- Move applications between categories.
- Launch applications normally or as administrator.
- Configure launch arguments, working directories, and per-app administrator behavior.
- Rename applications and categories and assign custom icons, banners, and backgrounds.
- Use compact, standard, or wide layouts with multiple tile sizes.
- Switch between banner-only and icon-only presentation.
- Configure colors, fonts, overlays, blur, transparency, animations, and hover effects.
- Use the system tray, start minimized, enable Windows autostart, and configure a global launcher hotkey.
- Back up and restore launcher data and important appearance settings as JSON.

## Screenshots

### Launcher and themes

![Tool Launcher with Steam-inspired theme](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202214.png?raw=true)

| Custom appearance | Razer-inspired theme |
| --- | --- |
| ![Tool Launcher custom appearance](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202015.png?raw=true) | ![Tool Launcher Razer-inspired theme](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202234.png?raw=true) |

### Categories

| Gaming Tools | Graphics |
| --- | --- |
| ![Gaming Tools category](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20230900.png?raw=true) | ![Graphics category](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20230906.png?raw=true) |

![Benchmark category](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20230911.png?raw=true)

### Dashboard and AI artwork tools

| Dashboard settings | AI Background Generator |
| --- | --- |
| ![Dashboard settings](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20203020.png?raw=true) | ![AI Background Generator](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20203828.png?raw=true) |

| AI Icon Generator | AI Banner Generator |
| --- | --- |
| ![AI Icon Generator](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20204351.png?raw=true) | ![AI Banner Generator](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20205446.png?raw=true) |




## Themes & Customization

Version 1.0 includes the following selectable presets:

- Custom
- Steam
- GOG Galaxy
- Razer Cortex

Users can also configure accent colors, banner color strength, font family and weight, animations, hover effects, transitions, application name visibility, tile size, layout width, category backgrounds, overlays, blur, and transparency.

The Theme Preset Studio is a development-only tool and is not available in the packaged Version 1.0 application.

## Hardware Dashboard

The configurable dashboard displays locally collected Windows hardware information:

- CPU usage
- GPU usage
- Memory usage
- Network download and upload activity
- Logical and physical drive usage and activity
- History graphs

Dashboard modules can be shown, hidden, reordered, renamed, and placed on either side of the launcher. Opacity and refresh interval can also be adjusted.

Additional temperature and sensor values may be read from a separately installed HWiNFO CSV log or AIDA64 shared sensor data. HWiNFO and AIDA64 are optional third-party applications and are not bundled with Tool Launcher.

## Languages

The launcher contains 16 user-interface languages:

- English
- German
- French
- Spanish
- Italian
- Dutch
- Portuguese
- Polish
- Czech
- Hungarian
- Russian
- Turkish
- Ukrainian
- Japanese
- Korean
- Chinese

The installer interface is available in English and German. The initial launcher language can be selected from all 16 languages during installation.

## Installation

1. Download `Tool.Launcher.Setup.1.0.0.exe` from the [official GitHub release](https://github.com/Bobic1983/Tool-Launcher/releases/latest).
2. Run the installer.
3. Choose the destination folder and optional desktop, Start menu, and autostart settings.
4. Select the initial launcher language.
5. Start Tool Launcher when installation is complete.

The Version 1.0 installer is not digitally signed. Windows SmartScreen may therefore display an unknown-publisher warning. Verify that the installer came from the official project release before continuing.

The installer is per-user and does not require a machine-wide installation. The uninstaller can optionally remove local Tool Launcher user data; that option is disabled by default.

## System Requirements

- Windows x64 system compatible with the packaged Electron 39 application
- Recommended display work area of at least 1100 × 720 pixels
- Approximately 500 MB of free disk space for the installed application, plus space for user images and backups
- PowerShell and standard Windows CIM/WMI services for hardware monitoring
- Vulkan-capable GPU and compatible driver only when using local Real-ESRGAN upscaling
- Internet connection only when opening external AI or support services, or importing an image from a URL

The exact oldest supported Windows release has not yet been formally established. This must be confirmed before publishing a strict minimum operating-system claim.

## Usage

Use the launcher menu to add applications or categories. Applications can also be dropped directly into the launcher. Right-click an application or category to open the available actions, including properties, administrator launch, image changes, generator shortcuts, rename, and delete.

Open Settings to configure general behavior, appearance, themes, dashboard modules, languages, backup and restore, and support links. The default global hotkey is `Alt+Space`, and alternative hotkeys are available in Settings.

The Create menu opens the Background Generator, Icon Generator, or Banner Generator.

## Configuration / Data Location

Tool Launcher stores its user data under:

```text
%APPDATA%\tool-launcher
```

The application also handles the legacy-compatible path `%APPDATA%\Tool Launcher` during cleanup. Stored data can include launcher categories and applications, settings, window state, hotkey configuration, language overrides, AI prompt settings, and logs.

Backups are portable JSON files created through the Backup function. Personal images remain in locations selected by the user or in the local application data used by the launcher.

## Support / Bug Reports

Please use the [Tool Launcher GitHub Issues page](https://github.com/Bobic1983/Tool-Launcher/issues) to report bugs. Include the Tool Launcher version, Windows version, steps to reproduce the problem, and relevant screenshots or log information.

## Support Development

Development can be supported through the links included in the application:

- [PayPal](https://paypal.me/WladimirReischeld)
- [Buy Me a Coffee](https://buymeacoffee.com/bobiclabs)

These links open external websites in the default browser.

## Privacy

Launcher configuration, hardware readings, backups, imported images, and local upscaling are processed on the user's computer. No application telemetry or active automatic update service was found in Version 1.0.

Tool Launcher opens approved external websites only for actions initiated by the user, such as ChatGPT, Gemini, PayPal, and Buy Me a Coffee. Those services are governed by their own privacy policies. Supplying a remote image URL instructs Tool Launcher to fetch that URL. Local and private network destinations are rejected, redirects are revalidated, and downloads are limited to 25 MB. Direct OpenAI API image generation and ComfyUI generation are disabled in the packaged Version 1.0 application.

## License

Tool Launcher is proprietary software. The source code is not distributed, and no permission to copy, modify, or redistribute the application or its source code is granted unless the project owner gives explicit written permission. All rights reserved.

The application uses third-party components with their own licenses. See `THIRD_PARTY_NOTICES.md` before distribution.

## Credits / Third-Party Components

Major components include Electron, React, Sharp/libvips, Real-ESRGAN NCNN Vulkan, and the bundled Inter, Cinzel, Lato, Roboto, and Roboto Condensed fonts. Optional sensor integration is available for separately installed HWiNFO and AIDA64.

Original Tool Launcher artwork was generated using ChatGPT and selected, reviewed, and integrated by the project owner. See `ASSET_PROVENANCE.md` for the recorded scope and exclusions.

Tool Launcher can open ChatGPT and Gemini as external services but does not include or operate those services. Steam, GOG Galaxy, Razer Cortex, ChatGPT, Gemini, HWiNFO, AIDA64, PayPal, and Buy Me a Coffee are names or trademarks of their respective owners. No affiliation or endorsement is claimed.

See `THIRD_PARTY_NOTICES.md` for the current component inventory and unresolved licensing checks.

