# 日出伺服器材質包說明

此材質包為日出伺服器所使用，整合了 QualityArmory 與 IceTea 的自訂模型與材質。

## 涵蓋的插件

### QualityArmory
QualityArmory 會新增武器、載具、裝備、背包與其他特殊物品。當這些物品使用下方列出的自訂物品 ID 時，表示它們需要以此材質包進行材質替換。

### IceTea
IceTea 會新增飲品類物品。當這些物品使用下方列出的自訂物品 ID 或 CustomModelData 值時，表示它們需要套用本材質包。

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

## 自訂物品 ID

### IceTea
- apple_icetea
- carrot_icetea
- icetea
- ice_water
- melon_icetea
- pumpkin_icetea

### QualityArmory
- aa12
- aiming
- ak47
- ak47u
- aliens
- ambulance
- ammo40m
- ammo50cal
- ammo556
- ammo762
- ammo9mm
- ammobag
- ammofusion
- ammomininuke
- ammomusketball
- ammorpg
- ammoshotgun
- arcgun
- assaultmask
- astronauthelmet
- asval
- auto9
- awp
- awp2
- b2plane
- backpackblack
- backpackblue
- backpackgreen
- backpackorange
- backpackparachute
- backpackpink
- barrett
- blackcap
- bluecap
- bmw
- bumpercarred
- bus
- cadillac62
- chicken
- civilboat1
- crown
- ctar21
- deagle
- debug
- dis9
- dp27
- dragunov
- enfield
- famas
- farmhat
- fatman
- firemanhat
- firetruck
- fivesevenfive
- flamer
- flashbang
- fnfal
- fnp90
- fo10mm
- fueltank
- galil
- garbagetruck
- grenade
- halo
- haloalien
- halofalcon
- headcrab
- headphones
- hearse
- heli
- heliblade
- heliorange
- henry
- homingrpg
- incendiarygrenade
- instituterifle
- jeep
- kar98k
- ladaniva
- lamborghini
- lazerrifle
- lightsaberblack
- lightsaberblue
- lightsabergreen
- lightsaberorange
- lightsaberpurple
- lightsaberred
- lightsaberwhite
- m16
- m1garand
- m32a1
- m40
- m4a1s
- m79
- mac10
- magnum
- makarov
- mark19
- mauser
- medkit
- mig1
- minigun
- molotov
- moskvitch
- motorcycle
- mp40
- mp5
- musketpistol
- musketrifle
- ncrmask
- needler
- newsvan
- nursecap
- overwatchpulsegun
- p30
- p30sil
- pancorjackhammer
- pandaears
- parachutewhite
- pig
- pimphat
- pinktophat
- pkp
- policehat
- policeveh
- polikarpov
- ppsh41
- preslimo
- privateplane
- proxymine
- purpleheadphones
- redcap
- remmington
- rpg
- rpk
- sawshotgun
- schoolbus
- sg553
- sgthat
- shoppingcart
- skimask
- skorpion
- sks
- smokegrenade
- spas
- spear
- squid
- steampunk
- stengun
- stg44
- streetsweep
- sw1911
- swatvan
- swblaster
- swlandspeeder
- swspeederbike
- tankcannon
- tankisbase
- taxi
- thatgun
- tophat
- trolly
- truck
- ufo
- ump
- unmarkedvan
- ushankahat
- uzi
- uzicorn
- vera
- warthog
- whitecap
- whitetophat
- witchhat
- wolfhead
- yellowcap

## 使用說明

- 此材質包僅覆蓋上方列出的自訂物品。
- 若物品未出現在清單中，則視為原版或與本材質包無關的內容。
- 材質包應放入 Minecraft 的 resourcepacks 資料夾中，並在遊戲內啟用。
