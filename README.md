# How to install happyhud



## Itemadder & HappyHUD Setup



1. If you have an old 'HappyHUD' folder, please delete it and install the new one
2. Disable [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. Disable [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  In the `HappyHud\config.yml`\


    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```


5. Run command `/happyhud reload`
6. run command `/iazip`

