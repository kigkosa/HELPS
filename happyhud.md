# วิธีติดตั้ง HappyHUD

### วิธีติดตั้ง HappyHUD ลง Itemadder:

1. ถ้าคุณมีโฟลเดอร์ 'HappyHUD' เก่าอยู่ ให้ลบออกแล้วติดตั้งโฟลเดอร์ใหม่
2. ปิดใช้งาน [ItemsAdder Text Effects](https://itemsadder.devs.beer/plugin-usage/text-effects-1.17+).
3. ปิดใช้งาน [ItemsAdder Hide Scoreboard Numbers](https://itemsadder.devs.beer/plugin-usage/scoreboard/hide-scoreboard-numbers-1.17+).
4.  แก้ไขไฟล์ `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "ItemsAdder/contents"
        happyhud: "ItemsAdder/contents"
    ```
5. รันคำสั่ง `/happyhud reload`
6. รันคำสั่ง `/iazip`

### วิธีติดตั้ง HappyHUD ลง Oraxen :

1. ถ้าคุณมีโฟลเดอร์ 'HappyHUD' เก่าอยู่ ให้ลบออกแล้วติดตั้งโฟลเดอร์ใหม่
2. ตั้งค่า `hide_scoreboard_numbers: false` ในไฟล์ settings.yml
3. ลบไฟล์ `Oraxen/pack/shaders/core/rendertype_text.json` และ `rendertype_text.vsh` ถ้าหากมี
4.  แก้ไขไฟล์ `HappyHud/config.yml`

    ```yaml
    copy-resource-pack:
      enabled: true
      namespaces:
        minecraft: "Oraxen/pack/assets"
        happyhud: "Oraxen/pack/assets"
    ```
5. รันคำสั่ง /happyhud reload
6. รันคำสั่ง /o reload all

### วิธีติดตั้ง HappyHUD ลงดีฟอลรีซอลแพ็ค :

1. ถ้าคุณมีโฟลเดอร์ 'HappyHUD' เก่าอยู่ ให้ลบออกแล้วติดตั้งโฟลเดอร์ใหม่
2. แก้ไขไฟล์ `HappyHud/config.yml`

```yaml
copy-resource-pack:
  enabled: false
```

3\. รันคำสั่ง /happyhud reload

4\. คัดลอกไฟล์ "HappyHUD\built-pack" และนำไปวางในรีซอลแพ็คของท่าน

5\. รีโหลดรีซอลแพ็ค
