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

# HappyHUD 설치 방법

### Oraxen 및 HappyHUD 설정:

1. **이전의 'HappyHUD' 폴더가 있다면 삭제하고 새로운 것을 설치하세요.**
2. 기능을 비활성화하십시오 [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. 기능을 비활성화하십시오 [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  **파일을 편집해 주세요** `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```
5. 채팅에 명령을 입력하십시오 `/happyhud reload`
6. 채팅에 명령을 입력하십시오 `/iazip`

### Oraxen 및 HappyHUD 설정:

1. **이전의 'HappyHUD' 폴더가 있다면 삭제하고 새로운 것을 설치하세요.**
2. Set `hide_scoreboard_numbers: false` in your settings.yml file.
3. "Oraxen/pack/shaders/core/rendertype\_text.json" 및 "rendertype\_text.vsh"가 있는 경우 삭제합니다.
4.  **파일을 편집해 주세요** `HappyHud/config.yml`&#x20;

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"
    ```
5. 채팅에 명령을 입력하십시오 `/happyhud reload`
6. 채팅에 명령을 입력하십시오 `/o reload all`

### 기본 리소스 팩 및 HappyHUD 설정:

1. **이전의 'HappyHUD' 폴더가 있다면 삭제하고 새로운 것을 설치하세요.**
2.  **파일을 편집해 주세요** `HappyHud/config.yml`&#x20;

    ```yaml
    copy-resource-pack:
      enabled: false
    ```
3. 채팅에 명령을 입력하십시오 /happyhud reload
4. "HappyHUD\build-pack"에서 파일을 복사하여 리소스 팩 폴더에 붙여넣습니다.
5. 리소스 팩을 Minecraft에 넣거나 Minecraft 리소스 팩을 다시 로드하세요.
