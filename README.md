# Tool Launcher

Tool Launcher is a customizable Windows desktop launcher for organizing applications into visual categories. It combines application management, a configurable hardware dashboard, theme presets, local image processing, and a complete AI-assisted wallpaper studio alongside tools for icons and banners.

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
- Design personal desktop wallpapers with the guided AI Background Generator.
- Start instantly with 1,840 built-in scene motifs when no custom scene description is entered.
- Export finished backgrounds to the computer in multiple aspect ratios and resolutions, or apply them directly to the launcher.
- Use the system tray, start minimized, enable Windows autostart, and configure a global launcher hotkey.
- Back up and restore launcher data and important appearance settings as JSON.

## Screenshots

These screenshots were captured from the real Version 1.0 application. The launcher can be presented with a plain background, custom artwork, different themes, and individually generated application banners or icons.

### AI Background Generator — From an Idea to a Finished Wallpaper

![AI Background Generator with guided scene creation, target resolution, prompt transfer, image preview, local upscaling, saving, and launcher application](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20203828.png?raw=true)

The Background Generator is one of Tool Launcher's central creative features. It guides the user through subject, style, mood, composition, and refinement, prepares the final prompt for ChatGPT or Gemini, and provides a workspace for importing and finishing the generated image. The result can be saved to the computer as a standalone wallpaper or applied directly as a global or category background inside Tool Launcher.

#### Explore and Control the Visual Style

![Background Generator Style step with Sketch selected, render-style previews, strength controls, and a completed 4K wallpaper](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/background-generator-style.png?raw=true)

The Style step makes the artistic direction visible before the prompt is transferred. It includes Cinematic, Realistic, Dark Premium, Concept Art, Anime, Oil Painting, Sketch, Pixel Art, Low Poly, and Surreal looks. Render Strength can be set to Natural, Stylized, or Extreme, allowing anything from a subtle influence to a strongly expressive transformation.

### Launcher and Themes

#### Custom — The Default Launcher Appearance

![Tool Launcher with its customizable default appearance, personal gaming background, application banners, and hardware dashboard](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/launcher-custom-default.png?raw=true)

Custom is the standard appearance used by Tool Launcher. It combines a personal background, application banners or icons, dashboard modules, and individually adjustable colors, typography, transparency, blur, animations, and layout options.

#### Complete Theme Presets

| Steam-inspired | GOG-inspired | Razer Cortex-inspired |
| --- | --- | --- |
| ![Tool Launcher with Steam-inspired theme](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202015.png?raw=true) | ![Tool Launcher with GOG-inspired theme](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202214.png?raw=true) | ![Tool Launcher with Razer Cortex-inspired theme](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20202234.png?raw=true) |

#### Appearance Settings

![Appearance settings with custom controls and selectable theme presets](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/appearance-theme-settings.png?raw=true)

Users can switch between complete presets or stay with Custom and experiment with accent colors, fonts, font weight, application presentation, backgrounds, overlays, transparency, animations, and other visual effects. Changes are applied immediately.

### Create and Organize Your Own Categories

Categories are not a fixed set imposed by Tool Launcher. Create as many as you need, give each one a personal name, and organize the launcher around your own applications and workflow.

| Open the Launcher menu | Name the new category |
| --- | --- |
| ![Launcher menu with Add app, Add category, and Settings](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/category-menu.png?raw=true) | ![Add category dialog with a freely editable category name](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/add-category-dialog.png?raw=true) |

Every category can have its own collection of applications and its own visual identity. The examples below are personal configurations, not built-in category requirements.

| Personal Games category | Personal Benchmark category |
| --- | --- |
| ![A personally configured Games category with its own application banners and background](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/launcher-custom-default.png?raw=true) | ![A personally configured Benchmark category with its own application banners and background](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/category-benchmark-custom.png?raw=true) |

<p align="center">
  <img src="https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/category-context-menu.png?raw=true" alt="Category context menu with Rename, Background, Generate AI background, and Delete" width="430">
</p>

The category context menu keeps the most important actions close at hand: rename the category, select an existing background, open the AI Background Generator for that category, or delete it. Categories can also be reordered, so the navigation follows your priorities rather than a predefined structure.

### From an App to Its Own Icon or Banner

<p align="center">
  <img src="https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/app-context-menu.png?raw=true" alt="Application context menu with banner editing and AI Banner Generator access" width="430">
</p>

Right-click an application to open its actions. Alongside launching as administrator, properties, renaming, and deleting, the menu provides access to the current icon or banner and opens the matching AI creation workflow directly for that launcher entry.

| AI Icon Generator | AI Banner Generator |
| --- | --- |
| ![AI Icon Generator with Adobe Acrobat selected as the target application](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20204351.png?raw=true) | ![AI Banner Generator with Adobe Acrobat selected as the target application](https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/Screenshot%202026-08-11%20205446.png?raw=true) |

The selected application is carried into the generator, where its name, presentation type, composition, background, and visual style can be prepared. After generating the artwork through ChatGPT or Gemini and importing the result, it can be saved separately or applied directly to the selected launcher tile.

### A Configurable Hardware Dashboard

<p align="center">
  <img src="https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/dashboard-sidebar.png?raw=true" alt="Hardware dashboard sidebar with live graphs for CPU, GPU, memory, network, and drives" width="20%">
  &nbsp;&nbsp;
  <img src="https://github.com/Bobic1983/Tool-Launcher/blob/main/screenshots/dashboard-settings.png?raw=true" alt="Dashboard settings with layout, live modules, refresh rate, and optional sensor sources" width="76%">
</p>

The dashboard is more than decoration: it provides live CPU, GPU, memory, network, and drive information without leaving the launcher. Modules can be shown or hidden, renamed, reordered, and positioned on either side. Transparency, overlay strength, and refresh rate are adjustable, while optional HWiNFO or AIDA64 integration can add further sensor data when those applications are installed separately.

## AI Creation Tools

Tool Launcher 1.0 includes AI-assisted prompt and image workflows. Direct image generation inside the application is disabled in this release. Prompts can be transferred to supported external AI services, and the resulting image can then be imported into Tool Launcher.

### Background Generator

The Background Generator is a full guided workflow for creating artwork for both Tool Launcher and the Windows desktop. It is designed to turn an initial idea into a carefully structured image prompt and then help prepare the returned image for practical use.

The five-step studio covers:

- **Basis:** choose a main category, content type, preset, aspect ratio, and target resolution, or describe a completely custom scene.
- **Style:** select the visual language and rendering style of the image.
- **Mood:** control atmosphere, lighting, color world, and emotional direction.
- **Composition:** decide how the scene is framed and where visual space should remain free for desktop icons or launcher tiles.
- **Refine:** add final details and exclusions before creating the finished prompt.

Prompts can be copied or saved and transferred to ChatGPT or Gemini in the default browser. A custom scene description is optional: when the field is left empty, Tool Launcher automatically chooses a fitting scene from a library of 1,840 prepared motifs across Nature, Sci-Fi, Fantasy, Urban, Lifestyle, Automotive, and Gaming. The dice button can immediately reroll the motif, while Random Inspiration can also vary the wider creative setup and provide a completely new starting point.

Generated or existing PNG, JPEG, and WebP images can be pasted from the clipboard, dropped into the workspace, selected from disk, or fetched from a supplied image URL. Tool Launcher previews the result and can crop and resize it to the selected target format. Optional local AI upscaling can prepare a smaller source image for the requested output size on a compatible Vulkan GPU.

The finished image can then be:

- saved locally to any chosen folder and used as a normal Windows wallpaper;
- applied as the global Tool Launcher background;
- assigned to a specific launcher category;
- retained as an independent image rather than being tied to the launcher.

#### Wallpaper Formats and Resolutions

| Format | HD | 2K | 4K |
| --- | --- | --- | --- |
| 16:9 desktop | 1920×1080 | 2560×1440 | 3840×2160 |
| 21:9 ultrawide | 2560×1080 | 3440×1440 | 5120×2160 |
| 32:9 super ultrawide | 3840×1080 | 5120×1440 | 7680×2160 |
| 9:16 portrait | 1080×1920 | 1440×2560 | 2160×3840 |
| 1:1 square | 1024×1024 | 1536×1536 | 2048×2048 |

Custom width and height values are also supported, making the generator useful for standard monitors, ultrawide and dual-screen setups, portrait displays, square artwork, and other personal formats.

### Icon Generator

The Icon Generator helps prepare prompts for application icons. It includes options for application type, visual style, background, logo treatment, and text placement. An existing launcher application can be selected as the target, and an imported result can be saved or applied to that application.

### Banner Generator

The Banner Generator uses the same assisted workflow in a wide-format mode intended for application banners and background artwork. It supports prompt preparation, external AI services, image import, preview, saving, and application to launcher entries.

### Local Upscaling

The Background Generator includes local image upscaling based on Real-ESRGAN NCNN Vulkan. The processing runs on the local computer and requires a Vulkan-capable GPU and a compatible graphics driver. It is not a CPU-based fallback and is not required for the rest of Tool Launcher.

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

1. Download `Tool Launcher Setup 1.0.2.exe` from the [official GitHub release](https://github.com/Bobic1983/Tool-Launcher/releases/latest).
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

The Create menu opens the Background Generator, Icon Generator, or Banner Generator. In the Background Generator, move through Basis, Style, Mood, Composition, and Refine, transfer the completed prompt to ChatGPT or Gemini, and import the resulting image back into the preview. From there it can be saved to the computer for use as a Windows wallpaper or applied directly to Tool Launcher.

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
