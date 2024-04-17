---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Comment installer HappyHUD

### Configuration de Itemadder et HappyHUD

1. Si vous avez un ancien dossier « HappyHUD », supprimez-le et installez le nouveau.
2. Désactiver [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. Désactiver [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  In the `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```
5. Exécuter la commande `/happyhud reload`
6. Exécuter la commande `/iazip`

### Configuration de Oraxen et HappyHUD&#x20;

1. Si vous avez un ancien dossier « HappyHUD », supprimez-le et installez le nouveau.
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
5. Exécuter la commande /happyhud reload
6. Exécuter la commande /o reload all

### Pack de ressources par défaut et configuration HappyHUD

1. Si vous avez un ancien dossier « HappyHUD », supprimez-le et installez le nouveau.
2.  In the `HappyHud/config.yml` set `copy-resource-pack to enabled: false`\\

    ```yaml
    copy-resource-pack:
      enabled: false
    ```
3. Exécuter la commande /happyhud reload
4. Copy the files from "HappyHUD\built-pack" and paste them into the resource pack folder.
5. Put the resoure pack to Minecraft or Reload the Minecraft resoure pack
