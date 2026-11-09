# Changelog

## v1.0.14

- Redesigned Home and Settings with a green orb, curved wireframe backdrop and beveled menu rows inspired by the original Xbox dashboard.
- Added global FXAA and CRT presets and per-game overrides for aspect ratio, filtering, FXAA and CRT.
- Added per-game IPS selection and support for a user-supplied OgXHD widescreen database. Patches apply to a separate ISO copy.
- Added startup update offers and Windows installation with ZIP digest verification and an executable backup.
- Fixed valid final-page texture ranges in OpenGL and Vulkan.
- Implemented Xbox Pentium III timestamp-register reads and writes and verified them with a guest ROM.

## v1.0.13

- Fixed stale OpenGL textures when textures or palettes share a VRAM page.
- Corrected Vulkan draw-batch tracking to avoid unnecessary GPU waits.
- Fall back to SDL presentation when Windows DXGI cannot retrieve or unlock a frame.
- Handled empty Xbox audio stream descriptors without aborting emulation.
- The OpenGL test build ran the Woodward Camp demo in Dave Mirra Freestyle BMX 2. The intermittent skybox flicker remains unconfirmed.

## v1.0.12

- Fixed a snapshot restore crash that could wake the Xbox audio worker before the saved audio state was loaded. Verified by loading an existing Dave Mirra Freestyle BMX 2 snapshot from the in-app list.

## v1.0.11

- Fixed a graphics queue lock when saving snapshots while the Xbox is paused. Corrected snapshot thumbnail rendering and added checks for invalid snapshot metadata.
- On Windows, Vulkan selects an adapter that can share frames with the OpenGL display GPU. Fixed DirectX framebuffer sharing and added a fallback to SDL presentation when the adapters differ.

## v1.0.10

- Simplified the dashboard navigation, aligned the Games toolbar, and grouped game actions under Play, Library, and Artwork.
- Improved spacing and title previews in cover search.

## v1.0.9

- Added cover search and preview by title, region, and edition.
- Added profile ZIP backup and restore for the game library, covers, controller settings, and display preferences.

## v1.0.8

- Added Continue playing to reopen the last game launched from the library.

## v1.0.7

- Added Favorites and named game collections.
- Added a first-run setup wizard for Xbox firmware, virtual storage, and the games folder.

## v1.0.6

- Added a dashboard clock toggle and 12-hour or 24-hour time formats for the Games and game details screens.

## v1.0.5

- Added a Vulkan graphics card selector with an Automatic option. The OpenGL panel shows the active GPU and links to Windows graphics settings.

## v1.0.4

- Added a manual update check under **Settings → About XDesk** that opens the Windows ZIP for a newer stable release.
- Improved automatic and manual cover matching using disc title, region, and filename with the Libretro Xbox artwork catalog.

## v1.0.3

- Added a cover grid, redesigned game details, and a built-in cartoon Xbox dashboard background.
- Saved downloaded artwork under `covers` and copied user-selected artwork to `covers/custom`. Games without artwork show **Choose cover image** below **Play**.

## v1.0.2

- Matched the Settings submenu to the dashboard and corrected the Windows title bar and file version.
- Added independent DualSense L2 and R2 trigger effects, plus separate toggles for gameplay effects and diagnostics.

## v1.0.1

- Added custom home backgrounds using PNG, JPEG, or BMP images, and applied XDesk branding to the controller diagram and Windows icon.
- Added DualSense input monitoring and tests for vibration, lighting, and adaptive triggers.
- Added Analog, Short pull, and Digital Xbox trigger input modes.
- Hid the on-screen Dashboard button during gameplay. F1 reopens the dashboard.

## v1.0.0

- Initial Windows release with automatic cover downloads, a dashboard accessible by F1 or an on-screen button, and separate XDesk settings.
