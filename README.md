# 日出伺服器材質包說明

此材質包為日出伺服器所使用，整合了 QualityArmory 與 IceTea 的自訂模型與材質。

## 涵蓋的插件

### QualityArmory
QualityArmory 會新增武器、載具、裝備、背包與其他特殊物品。當這些物品使用下方列出的自訂物品 ID 時，表示它們需要以此材質包進行材質替換。

### IceTea
IceTea 會新增飲品類物品。當這些物品使用下方列出的自訂物品 ID 或 CustomModelData 值時，表示它們需要套用本材質包。

### Custom Addon
Custom Addon 會心增各種伺服器自訂物品，目前為止新增的為各類型的烤鴨。當這些物品使用下方列出的 CustomModelData 值時，表示他們需要套用本材質包。

## 如何判斷哪些物品需要替換材質

可依照以下方式判斷：

- 如果物品不是原版 Minecraft 的標準物品，且在此材質包中有對應模型定義，則它屬於自訂物品，可能需要替換材質。
- 如果物品使用自訂命名空間 qualityarmory，表示它屬於 QualityArmory 的內容，需要套用對應模型與材質。
- 如果物品使用自訂命名空間 icetea，表示它屬於 IceTea 的內容，需要套用對應模型與材質。
- IceTea 飲品可透過物品 ID 與 CustomModelData 來辨識，對應關係如下：
  - ice_water → 520000
  - melon_icetea → 520001
  - apple_icetea → 520002
  - carrot_icetea → 520003
  - pumpkin_icetea → 520004
  - icetea → 520005
- CustomAddon 烤鴨可透過 CustomModelData 來辨識，對應關係如下：
  - 碳烤烤鴨 → 610000
  - 鐵板烤鴨 → 610001
  - 黃金烤鴨 → 610002
  - 鑽石烤鴨 → 610003
  - 翡翠烤鴨 → 610004
  - 銅板烤鴨 → 610005
  - 獄碴烤鴨 → 610006

## 使用說明

- 此材質包僅覆蓋上方列出的自訂物品。
- 若物品未出現在清單中，則視為原版或與本材質包無關的內容。
- 材質包應放入 Minecraft 的 resourcepacks 資料夾中，並在遊戲內啟用。
