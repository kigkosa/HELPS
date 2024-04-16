# How to install HappyHUD

## Itemadder & HappyHUD Setup

1. If you have an old 'HappyHUD' folder, please delete it and install the new one
2. Disable [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. Disable [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  In the `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```


5. Run command `/happyhud reload`
6. run command `/iazip`

## Oraxen & HappyHUD Setup:

1. If you have an old 'HappyHUD' folder, please delete it and install the new one
2. Set `hide_scoreboard_numbers: false` in your settings.yml file.
3. Delete `Oraxen/pack/shaders/core/rendertype_text.json` and `rendertype_text.vsh` if they exist.
4.  In the HappyHud config.yml set `copy-resource-pack` to `enabled: true` and make the path `path: Oraxen/pack/assets`.

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"
    ```


5. Run command /happyhud reload
6. run command /o reload all

## Defualt Resoure Pack & HappyHUD Setup:

1. If you have an old 'HappyHUD' folder, please delete it and install the new one
2.  In the `HappyHud/config.yml` set `copy-resource-pack to enabled: false`\


    ```yaml
    copy-resource-pack:
      enabled: false
    ```


3. Run command /happyhud reload
4. Copy the files from "HappyHUD\built-pack" and paste them into the resource pack folder.
5. Put the resoure pack to Minecraft or Reload the Minecraft resoure pack
