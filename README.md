# HOI4moddingT

A mod for Hearts of Iron IV (HOI4).

## Features

- **Custom National Focus Tree** for Germany with three focuses:
  - *Industrial Expansion* — boosts factory output and construction speed
  - *Military Buildup* — grants army experience and land doctrine bonuses
  - *Diplomatic Outreach* — grants political power
- **National Idea** — *Industrial Spirit*: increases industrial capacity and production speed
- **Custom Event** — *Industrial Breakthrough*: triggered event with two outcome options
- **Localisation** — English text for all mod content

## Installation

1. Copy the `HOI4moddingT` folder and the `descriptor.mod` file into your Hearts of Iron IV mods directory:
   - **Windows:** `%USERPROFILE%\Documents\Paradox Interactive\Hearts of Iron IV\mod\`
   - **Linux:** `~/.local/share/Paradox Interactive/Hearts of Iron IV/mod/`
   - **macOS:** `~/Documents/Paradox Interactive/Hearts of Iron IV/mod/`
2. Launch the HOI4 Launcher.
3. Enable **HOI4moddingT** in the mod list.
4. Start a new game.

## Directory Structure

```
HOI4moddingT/
├── descriptor.mod                          # Mod descriptor
├── common/
│   ├── country_tags/
│   │   └── HOI4moddingT_tags.txt          # Custom country tags
│   ├── ideas/
│   │   └── HOI4moddingT_ideas.txt         # National ideas/spirits
│   └── national_focus/
│       └── HOI4moddingT_focus.txt         # Focus tree
├── events/
│   └── HOI4moddingT_events.txt            # Events
└── localisation/
    └── english/
        └── HOI4moddingT_l_english.yml     # English localisation
```

## Supported Version

Hearts of Iron IV `1.14.*`

## Contributing

Feel free to open issues or pull requests to suggest new features or report bugs.
