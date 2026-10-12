# Botched Client

Wrapper updated: 2026-10-12. The linked game archive is a separate, older build.

A browser-based UI prototype for a 1.12-style Eaglercraft client. It explores a
Tuff-inspired module menu, HUD controls, and client settings without embedding or
modifying the compiled game download.

## Run

Open `index.html` in a browser with internet access. It downloads and extracts
the linked Eaglercraft 1.12.2 offline ZIP, then caches the extracted HTML for
later launches. Press `Right Shift` to send Escape to the game and open or close
the overlay. Module switches, HUD visibility, accent color, interface scale, and
the Fullbright level are saved locally.

## About the template

The linked Eaglercraft download is a single compiled offline HTML build, not an
editable source project. The game is loaded at runtime and is not copied into
this repository. Fullbright level 0–9 applies a visual brightness/contrast
filter to the game frame; it does not change Minecraft's internal block-light
values. Other module toggles do not change gameplay because the compiled build
exposes no supported module or FOV API. Use the game's Options screen to adjust
FOV; real gameplay modules require editable source. Anti-cheat bypasses are not
included.

The UI direction was informed by TuffClient's public [mod documentation](https://github.com/TuffNetwork/tufftest/blob/v2/ModDocs.md)
and [build page](https://iaanzhao.github.io/tuffclient/).
