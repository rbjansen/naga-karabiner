# naga-karabiner

This repository contains an example of how to configure a Razer Naga mouse on macOS for VS Code keybindings with Karabiner-Elements.

## Installation

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/).
2. Ensure the mouse is recognized by Karabiner-Elements and check the `Device` tab to see if the device ID matches the one in the `naga-karabiner.json` file.
3. Edit `naga-karabiner.json` to your liking. Read the [Karabiner-Elements documentation](https://karabiner-elements.pqrs.org/docs/json/) for other options. You can see which key-codes are triggered by the mouse with Karabiner-EventViewer.
4. Copy the JSON into Karabiner config:

```shell
cp naga-karabiner.json ~/.config/karabiner/assets/complex_modifications
```

5. Open Karabiner-Elements, go to the `Complex Modifications` tab, and open `Add predefined rule`. You should see the new rules in the list here. Enable the ones you want to use.
