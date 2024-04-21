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

# Cómo instalar HappyHUD

### Configuración de Itemadder y HappyHUD

1. Si tiene una carpeta 'HappyHUD' antigua, elimínela e instale la nueva.
2. Desactivar [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. Desactivar [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  Editar archivo `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```
5. Ejecutar comando `/happyhud reload`
6. Ejecutar comando`/iazip`

### Configuración de Oraxen y HappyHUD:

1. Si tiene una carpeta 'HappyHUD' antigua, elimínela e instale la nueva.
2. Establezca hide\_scoreboard\_numbers: false en su archivo settings.yml.
3. Elimine Oraxen/pack/shaders/core/rendertype\_text.json y rendertype\_text.vsh si existen.
4.  Editar archivo HappyHud/config.yml

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"
    ```
5. Ejecutar comando /happyhud reload
6. Ejecutar comando /o reload all

### Paquete de recursos predeterminado y configuración de HappyHUD:

1. Si tiene una carpeta 'HappyHUD' antigua, elimínela e instale la nueva.
2.  Editar archivo `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: false
    ```
3. Ejecutar comando /happyhud reload
4. Copie los archivos de "HappyHUD\built-pack" y péguelos en la carpeta del paquete de recursos.
5. Coloque el paquete de recursos en Minecraft o vuelva a cargar el paquete de recursos de Minecraft
