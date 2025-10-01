# ArmoryEpicLootCompat

Мод, який дозволяє зброї з **ValheimArmory** випадати з мобів через систему **EpicLoot** з можливістю задавати шанс 50/50.

## Установка

1. Копіюй `ArmoryEpicLootCompat.dll` у папку `BepInEx/plugins/`.
2. Запусти гру один раз — створиться файл `BepInEx/config/com.ditus.ArmoryEpicLootCompat.cfg`.
3. У конфіг-фаїлі налаштуй:
   ```ini
   [General]
   ArmoryChance = 50
   VanillaChance = 50
