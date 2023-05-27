
# overpaint.js

overpaint.js is a library to facilitate colorful terminal/console outputs for javascript programs.
overpaint.js supports **657 colors** of the html language. [> See all Colors <](#colors) [> See all Styles<](#styles)

## Usage

```js
const overpaint = require('overpaint.js');
// some red text
console.log("Hello World"._Red);
// some text on a red background
console.log("Hello World"._Red_BG);
// some bold & italic red text on a blue background
console.log("Hello World"._bold._italic._Red._Blue_BG);
```
*Note: Upon applying styles and colors, ONLY the last specified from each category will take effect.*
↓ Example ↓
```js
const overpaint = require('overpaint.js');
// this text is blue
console.log("Hello World"._Blue);
// this text is Red
console.log("Hello World".Blue._Red);
// this text is Blue
console.log("Hello World"._Blue._Red._Blue);
```
## Typings

overpaint.js is equipped with rich typings and autocompletion for editors like Visual Studio Code and many others

## Styles

| Style              | Description                              | Supported |
| ------------------ | ---------------------------------------- | --------- |
| `dim`              | Reduces thr brightness                   | *Always*  |
| `bold`             | Increases the font weight                | *Always*  |
| `italic`           | Slightly inclines the text to the right  | *Always*  |
| `inverted`         | Swaps the colors of the fore/background  | *Often*   |
| `invisible`        | Makes the text invisible                 | *Often*   |
| `blinking`         | Animates the text with a blinking effect | *Rarely*  |
| `overline`         | Draws a line above                       | *Rarely*  |
| `underline`        | Draws a line underneath                  | *Always*  |
| `strikethrough`    | Draws a line in the middle               | *Often*   |
| `double_underline` | Draws a double line underneath           | *Rarely*  |

## Colors

| Style | Description | Supported |
|-|-|-|
|$$\color{#000000}Black$$|$$\color{#0C090A}Night$$|$$\color{#34282C}Charcoal$$|
|$$\color{#3B3131}Oil$$|$$\color{#454545}LightBlack$$|$$\color{#413839}BlackCat$$|
|$$\color{#3D3C3A}Iridium$$|$$\color{#463E3F}BlackEel$$|$$\color{#4C4646}BlackCow$$|
|$$\color{#504A4B}GrayWolf$$|$$\color{#565051}VampireGray$$|$$\color{#52595D}IronGray$$|
|$$\color{#5C5858}GrayDolphin$$|$$\color{#625D5D}CarbonGray$$|$$\color{#666362}AshGray$$|
|$$\color{#696969}DimGray$$|$$\color{#686A6C}NardoGray$$|$$\color{#6D6968}CloudyGray$$|
|$$\color{#726E6D}SmokeyGray$$|$$\color{#736F6E}AlienGray$$|$$\color{#757575}SonicSilver$$|
|$$\color{#797979}PlatinumGray$$|$$\color{#837E7C}Granite$$|$$\color{#808080}Gray$$|
|$$\color{#848482}BattleshipGray$$|$$\color{#8D918D}GunmetalGray$$|$$\color{#A9A9A9}DarkGray$$|
|$$\color{#B6B6B4}GrayCloud$$|$$\color{#C0C0C0}Silver$$|$$\color{#C9C0BB}PaleSilver$$|
|$$\color{#D1D0CE}GrayGoose$$|$$\color{#CECECE}PlatinumSilver$$|$$\color{#D3D3D3}LightGray$$|
|$$\color{#DADBDD}SilverWhite$$|$$\color{#DCDCDC}Gainsboro$$|$$\color{#E5E4E2}Platinum$$|
|$$\color{#BCC6CC}MetallicSilver$$|$$\color{#98AFC7}BlueGray$$|$$\color{#838996}RomanSilver$$|
|$$\color{#778899}LightSlateGray$$|$$\color{#708090}SlateGray$$|$$\color{#6D7B8D}RatGray$$|
|$$\color{#657383}SlateGraniteGray$$|$$\color{#616D7E}JetGray$$|$$\color{#646D7E}MistBlue$$|
|$$\color{#566D7E}MarbleBlue$$|$$\color{#737CA1}SlateBlueGrey$$|$$\color{#728FCE}LightPurpleBlue$$|
|$$\color{#4863A0}AzureBlue$$|$$\color{#2B547E}BlueJay$$|$$\color{#36454F}CharcoalBlue$$|
|$$\color{#29465B}DarkBlueGrey$$|$$\color{#2B3856}DarkSlate$$|$$\color{#123456}DeepSeaBlue$$|
|$$\color{#151B54}NightBlue$$|$$\color{#191970}MidnightBlue$$|$$\color{#000080}Navy$$|
|$$\color{#151B8D}DenimDarkBlue$$|$$\color{#00008B}DarkBlue$$|$$\color{#15317E}LapisBlue$$|
|$$\color{#0000A0}NewMidnightBlue$$|$$\color{#0000A5}EarthBlue$$|$$\color{#0020C2}CobaltBlue$$|
|$$\color{#0000CD}MediumBlue$$|$$\color{#0041C2}BlueberryBlue$$|$$\color{#2916F5}CanaryBlue$$|
|$$\color{#0000FF}Blue$$|$$\color{#0002FF}SamcoBlue$$|$$\color{#0909FF}BrightBlue$$|
|$$\color{#1F45FC}BlueOrchid$$|$$\color{#2554C7}SapphireBlue$$|$$\color{#1569C7}BlueEyes$$|
|$$\color{#1974D2}BrightNavyBlue$$|$$\color{#2B60DE}BalloonBlue$$|$$\color{#4169E1}RoyalBlue$$|
|$$\color{#2B65EC}OceanBlue$$|$$\color{#306EFF}BlueRibbon$$|$$\color{#157DEC}BlueDress$$|
|$$\color{#1589FF}NeonBlue$$|$$\color{#1E90FF}DodgerBlue$$|$$\color{#368BC1}GlacialBlueIce$$|
|$$\color{#4682B4}SteelBlue$$|$$\color{#488AC7}SilkBlue$$|$$\color{#357EC7}WindowsBlue$$|
|$$\color{#3090C7}BlueIvy$$|$$\color{#659EC7}BlueKoi$$|$$\color{#87AFC7}ColumbiaBlue$$|
|$$\color{#95B9C7}BabyBlue$$|$$\color{#6495ED}CornflowerBlue$$|$$\color{#6698FF}SkyBlueDress$$|
|$$\color{#56A5EC}Iceberg$$|$$\color{#38ACEC}ButterflyBlue$$|$$\color{#00BFFF}DeepSkyBlue$$|
|$$\color{#3BB9FF}MiddayBlue$$|$$\color{#5CB3FF}CrystalBlue$$|$$\color{#79BAEC}DenimBlue$$|
|$$\color{#82CAFF}DaySkyBlue$$|$$\color{#87CEFA}LightSkyBlue$$|$$\color{#87CEEB}SkyBlue$$|
|$$\color{#A0CFEC}JeansBlue$$|$$\color{#B7CEEC}BlueAngel$$|$$\color{#B4CFEC}PastelBlue$$|
|$$\color{#ADDFFF}LightDayBlue$$|$$\color{#C2DFFF}SeaBlue$$|$$\color{#C6DEFF}HeavenlyBlue$$|
|$$\color{#BDEDFF}RobinEggBlue$$|$$\color{#B0E0E6}PowderBlue$$|$$\color{#AFDCEC}CoralBlue$$|
|$$\color{#ADD8E6}LightBlue$$|$$\color{#B0CFDE}LightSteelBlue$$|$$\color{#C9DFEC}GulfBlue$$|
|$$\color{#D5D6EA}PastelLightBlue$$|$$\color{#E3E4FA}LavenderBlue$$|$$\color{#DBE9FA}WhiteBlue$$|
|$$\color{#E6E6FA}Lavender$$|$$\color{#EBF4FA}Water$$|$$\color{#F0F8FF}AliceBlue$$|
|$$\color{#F8F8FF}GhostWhite$$|$$\color{#F0FFFF}Azure$$|$$\color{#E0FFFF}LightCyan$$|
|$$\color{#CCFFFF}LightSlate$$|$$\color{#9AFEFF}ElectricBlue$$|$$\color{#7DFDFE}TronBlue$$|
|$$\color{#57FEFF}BlueZircon$$|$$\color{#00FFFF}Aqua$$|$$\color{#0AFFFF}BrightCyan$$|
|$$\color{#50EBEC}Celeste$$|$$\color{#4EE2EC}BlueDiamond$$|$$\color{#16E2F5}BrightTurquoise$$|
|$$\color{#8EEBEC}BlueLagoon$$|$$\color{#AFEEEE}PaleTurquoise$$|$$\color{#CFECEC}PaleBlueLily$$|
|$$\color{#B3D9D9}LightTeal$$|$$\color{#81D8D0}TiffanyBlue$$|$$\color{#77BFC7}BlueHosta$$|
|$$\color{#92C7C7}CyanOpaque$$|$$\color{#78C7C7}NorthernLightsBlue$$|$$\color{#7BCCB5}BlueGreen$$|
|$$\color{#66CDAA}MediumAquaMarine$$|$$\color{#AAF0D1}MagicMint$$|$$\color{#93FFE8}LightAquamarine$$|
|$$\color{#7FFFD4}Aquamarine$$|$$\color{#01F9C6}BrightTeal$$|$$\color{#40E0D0}Turquoise$$|
|$$\color{#48D1CC}MediumTurquoise$$|$$\color{#48CCCD}DeepTurquoise$$|$$\color{#46C7C7}Jellyfish$$|
|$$\color{#43C6DB}BlueTurquoise$$|$$\color{#00CED1}DarkTurquoise$$|$$\color{#43BFC7}MacawBlueGreen$$|
|$$\color{#20B2AA}LightSeaGreen$$|$$\color{#3EA99F}SeafoamGreen$$|$$\color{#5F9EA0}CadetBlue$$|
|$$\color{#3B9C9C}DeepSea$$|$$\color{#008B8B}DarkCyan$$|$$\color{#00827F}TealGreen$$|
|$$\color{#008080}Teal$$|$$\color{#007C80}TealBlue$$|$$\color{#045F5F}MediumTeal$$|
|$$\color{#045D5D}DarkTeal$$|$$\color{#033E3E}DeepTeal$$|$$\color{#25383C}DarkSlateGray$$|
|$$\color{#2C3539}Gunmetal$$|$$\color{#3C565B}BlueMossGreen$$|$$\color{#4C787E}BeetleGreen$$|
|$$\color{#5E7D7E}GrayishTurquoise$$|$$\color{#307D7E}GreenishBlue$$|$$\color{#348781}AquamarineStone$$|
|$$\color{#438D80}SeaTurtleGreen$$|$$\color{#4E8975}DullSeaGreen$$|$$\color{#1F6357}DarkGreenBlue$$|
|$$\color{#306754}DeepSeaGreen$$|$$\color{#006A4E}BottleGreen$$|$$\color{#2E8B57}SeaGreen$$|
|$$\color{#1B8A6B}ElfGreen$$|$$\color{#31906E}DarkMint$$|$$\color{#00A36C}Jade$$|
|$$\color{#34A56F}EarthGreen$$|$$\color{#1AA260}ChromeGreen$$|$$\color{#50C878}Emerald$$|
|$$\color{#3EB489}Mint$$|$$\color{#3CB371}MediumSeaGreen$$|$$\color{#7C9D8E}MetallicGreen$$|
|$$\color{#78866B}CamouflageGreen$$|$$\color{#848B79}SageGreen$$|$$\color{#617C58}HazelGreen$$|
|$$\color{#728C00}VenomGreen$$|$$\color{#6B8E23}OliveDrab$$|$$\color{#808000}Olive$$|
|$$\color{#556B2F}DarkOliveGreen$$|$$\color{#4E5B31}MilitaryGreen$$|$$\color{#3A5F0B}GreenLeaves$$|
|$$\color{#4B5320}ArmyGreen$$|$$\color{#667C26}FernGreen$$|$$\color{#4E9258}FallForestGreen$$|
|$$\color{#08A04B}IrishGreen$$|$$\color{#387C44}PineGreen$$|$$\color{#347235}MediumForestGreen$$|
|$$\color{#347C2C}JungleGreen$$|$$\color{#227442}CactusGreen$$|$$\color{#228B22}ForestGreen$$|
|$$\color{#008000}Green$$|$$\color{#006400}DarkGreen$$|$$\color{#056608}DeepGreen$$|
|$$\color{#046307}DeepEmeraldGreen$$|$$\color{#355E3B}HunterGreen$$|$$\color{#254117}DarkForestGreen$$|
|$$\color{#004225}LotusGreen$$|$$\color{#437C17}SeaweedGreen$$|$$\color{#347C17}ShamrockGreen$$|
|$$\color{#6AA121}GreenOnion$$|$$\color{#8A9A5B}MossGreen$$|$$\color{#3F9B0B}GrassGreen$$|
|$$\color{#4AA02C}GreenPepper$$|$$\color{#41A317}DarkLimeGreen$$|$$\color{#12AD2B}ParrotGreen$$|
|$$\color{#3EA055}CloverGreen$$|$$\color{#73A16C}DinosaurGreen$$|$$\color{#6CBB3C}GreenSnake$$|
|$$\color{#6CC417}AlienGreen$$|$$\color{#4CC417}GreenApple$$|$$\color{#32CD32}LimeGreen$$|
|$$\color{#52D017}PeaGreen$$|$$\color{#4CC552}KellyGreen$$|$$\color{#54C571}ZombieGreen$$|
|$$\color{#89C35C}GreenPeas$$|$$\color{#85BB65}DollarBillGreen$$|$$\color{#99C68E}FrogGreen$$|
|$$\color{#A0D6B4}TurquoiseGreen$$|$$\color{#8FBC8F}DarkSeaGreen$$|$$\color{#829F82}BasilGreen$$|
|$$\color{#A2AD9C}GrayGreen$$|$$\color{#9CB071}IguanaGreen$$|$$\color{#8FB31D}CitronGreen$$|
|$$\color{#B0BF1A}AcidGreen$$|$$\color{#B2C248}AvocadoGreen$$|$$\color{#9DC209}PistachioGreen$$|
|$$\color{#A1C935}SaladGreen$$|$$\color{#9ACD32}YellowGreen$$|$$\color{#77DD77}PastelGreen$$|
|$$\color{#7FE817}HummingbirdGreen$$|$$\color{#59E817}NebulaGreen$$|$$\color{#57E964}StoplightGoGreen$$|
|$$\color{#16F529}NeonGreen$$|$$\color{#5EFB6E}JadeGreen$$|$$\color{#36F57F}LimeMintGreen$$|
|$$\color{#00FF7F}SpringGreen$$|$$\color{#00FA9A}MediumSpringGreen$$|$$\color{#5FFB17}EmeraldGreen$$|
|$$\color{#00FF00}Lime$$|$$\color{#7CFC00}LawnGreen$$|$$\color{#66FF00}BrightGreen$$|
|$$\color{#7FFF00}Chartreuse$$|$$\color{#87F717}YellowLawnGreen$$|$$\color{#98F516}AloeVeraGreen$$|
|$$\color{#B1FB17}DullGreenYellow$$|$$\color{#ADF802}LemonGreen$$|$$\color{#ADFF2F}GreenYellow$$|
|$$\color{#BDF516}ChameleonGreen$$|$$\color{#DAEE01}NeonYellowGreen$$|$$\color{#E2F516}YellowGreenGrosbeak$$|
|$$\color{#CCFB5D}TeaGreen$$|$$\color{#BCE954}SlimeGreen$$|$$\color{#64E986}AlgaeGreen$$|
|$$\color{#90EE90}LightGreen$$|$$\color{#6AFB92}DragonGreen$$|$$\color{#98FB98}PaleGreen$$|
|$$\color{#98FF98}MintGreen$$|$$\color{#B5EAAA}GreenThumb$$|$$\color{#E3F9A6}OrganicBrown$$|
|$$\color{#C3FDB8}LightJade$$|$$\color{#C2E5D3}LightMintGreen$$|$$\color{#DBF9DB}LightRoseGreen$$|
|$$\color{#E8F1D4}ChromeWhite$$|$$\color{#F0FFF0}HoneyDew$$|$$\color{#F5FFFA}MintCream$$|
|$$\color{#FFFACD}LemonChiffon$$|$$\color{#FFFFC2}Parchment$$|$$\color{#FFFFCC}Cream$$|
|$$\color{#FFFDD0}CreamWhite$$|$$\color{#FAFAD2}LightGoldenRodYellow$$|$$\color{#FFFFE0}LightYellow$$|
|$$\color{#F5F5DC}Beige$$|$$\color{#FFF8DC}Cornsilk$$|$$\color{#FBF6D9}Blonde$$|
|$$\color{#F7E7CE}Champagne$$|$$\color{#FAEBD7}AntiqueWhite$$|$$\color{#FFEFD5}PapayaWhip$$|
|$$\color{#FFEBCD}BlanchedAlmond$$|$$\color{#FFE4C4}Bisque$$|$$\color{#F5DEB3}Wheat$$|
|$$\color{#FFE4B5}Moccasin$$|$$\color{#FFE5B4}Peach$$|$$\color{#FED8B1}LightOrange$$|
|$$\color{#FFDAB9}PeachPuff$$|$$\color{#FBD5AB}CoralPeach$$|$$\color{#FFDEAD}NavajoWhite$$|
|$$\color{#FBE7A1}GoldenBlonde$$|$$\color{#F3E3C3}GoldenSilk$$|$$\color{#F0E2B6}DarkBlonde$$|
|$$\color{#F1E5AC}LightGold$$|$$\color{#F3E5AB}Vanilla$$|$$\color{#ECE5B6}TanBrown$$|
|$$\color{#E8E4C9}DirtyWhite$$|$$\color{#EEE8AA}PaleGoldenRod$$|$$\color{#F0E68C}Khaki$$|
|$$\color{#EDDA74}CardboardBrown$$|$$\color{#EDE275}HarvestGold$$|$$\color{#FFE87C}SunYellow$$|
|$$\color{#FFF380}CornYellow$$|$$\color{#FAF884}PastelYellow$$|$$\color{#FFFF33}NeonYellow$$|
|$$\color{#FFFF00}Yellow$$|$$\color{#FFEF00}CanaryYellow$$|$$\color{#F5E216}BananaYellow$$|
|$$\color{#FFDB58}MustardYellow$$|$$\color{#FFDF00}GoldenYellow$$|$$\color{#F9DB24}BoldYellow$$|
|$$\color{#FFD801}RubberDuckyYellow$$|$$\color{#FFD700}Gold$$|$$\color{#FDD017}BrightGold$$|
|$$\color{#FFCE44}ChromeGold$$|$$\color{#EAC117}GoldenBrown$$|$$\color{#F6BE00}DeepYellow$$|
|$$\color{#F2BB66}MacaroniandCheese$$|$$\color{#FBB917}Saffron$$|$$\color{#FDBD01}NeonGold$$|
|$$\color{#FBB117}Beer$$|$$\color{#FFAE42}YellowOrangeYellow$$|$$\color{#FFA62F}Cantaloupe$$|
|$$\color{#FFA600}CheeseOrange$$|$$\color{#FFA500}Orange$$|$$\color{#EE9A4D}BrownSand$$|
|$$\color{#F4A460}SandyBrown$$|$$\color{#E2A76F}BrownSugar$$|$$\color{#C19A6B}CamelBrown$$|
|$$\color{#E6BF83}DeerBrown$$|$$\color{#DEB887}BurlyWood$$|$$\color{#D2B48C}Tan$$|
|$$\color{#C8AD7F}LightFrenchBeige$$|$$\color{#C2B280}Sand$$|$$\color{#BCB88A}Sage$$|
|$$\color{#C8B560}FallLeafBrown$$|$$\color{#C9BE62}GingerBrown$$|$$\color{#C9AE5D}BronzeGold$$|
|$$\color{#BDB76B}DarkKhaki$$|$$\color{#BAB86C}OliveGreen$$|$$\color{#B5A642}Brass$$|
|$$\color{#C7A317}CookieBrown$$|$$\color{#D4AF37}MetallicGold$$|$$\color{#E9AB17}BeeYellow$$|
|$$\color{#E8A317}SchoolBusYellow$$|$$\color{#DAA520}GoldenRod$$|$$\color{#D4A017}OrangeGold$$|
|$$\color{#C68E17}Caramel$$|$$\color{#B8860B}DarkGoldenRod$$|$$\color{#C58917}Cinnamon$$|
|$$\color{#CD853F}Peru$$|$$\color{#CD7F32}Bronze$$|$$\color{#C88141}TigerOrange$$|
|$$\color{#B87333}Copper$$|$$\color{#AA6C39}DarkGold$$|$$\color{#A97142}MetallicBronze$$|
|$$\color{#AB784E}DarkAlmond$$|$$\color{#966F33}Wood$$|$$\color{#806517}OakBrown$$|
|$$\color{#665D1E}AntiqueBronze$$|$$\color{#8E7618}Hazel$$|$$\color{#8B8000}DarkYellow$$|
|$$\color{#827839}DarkMoccasin$$|$$\color{#8A865D}KhakiGreen$$|$$\color{#93917C}MillenniumJade$$|
|$$\color{#9F8C76}DarkBeige$$|$$\color{#AF9B60}BulletShell$$|$$\color{#827B60}ArmyBrown$$|
|$$\color{#786D5F}Sandstone$$|$$\color{#483C32}Taupe$$|$$\color{#493D26}Mocha$$|
|$$\color{#513B1C}MilkChocolate$$|$$\color{#3D3635}GrayBrown$$|$$\color{#3B2F2F}DarkCoffee$$|
|$$\color{#43302E}OldBurgundy$$|$$\color{#49413F}WesternCharcoal$$|$$\color{#5C3317}BakersBrown$$|
|$$\color{#654321}DarkBrown$$|$$\color{#704214}SepiaBrown$$|$$\color{#804A00}DarkBronze$$|
|$$\color{#6F4E37}Coffee$$|$$\color{#835C3B}BrownBear$$|$$\color{#7F5217}RedDirt$$|
|$$\color{#7F462C}Sepia$$|$$\color{#A0522D}Sienna$$|$$\color{#8B4513}SaddleBrown$$|
|$$\color{#8A4117}DarkSienna$$|$$\color{#7E3817}Sangria$$|$$\color{#7E3517}BloodRed$$|
|$$\color{#954535}Chestnut$$|$$\color{#9E4638}CoralBrown$$|$$\color{#C34A2C}ChestnutRed$$|
|$$\color{#C04000}Mahogany$$|$$\color{#EB5406}RedGold$$|$$\color{#C35817}RedFox$$|
|$$\color{#B86500}DarkBisque$$|$$\color{#B5651D}LightBrown$$|$$\color{#B76734}PetraGold$$|
|$$\color{#C36241}Rust$$|$$\color{#CB6D51}CopperRed$$|$$\color{#C47451}OrangeSalmon$$|
|$$\color{#D2691E}Chocolate$$|$$\color{#CC6600}Sedona$$|$$\color{#E56717}PapayaOrange$$|
|$$\color{#E66C2C}HalloweenOrange$$|$$\color{#FF6700}NeonOrange$$|$$\color{#FF5F1F}BrightOrange$$|
|$$\color{#F87217}PumpkinOrange$$|$$\color{#F88017}CarrotOrange$$|$$\color{#FF8C00}DarkOrange$$|
|$$\color{#F87431}ConstructionConeOrange$$|$$\color{#FF7722}IndianSaffron$$|$$\color{#E67451}SunriseOrange$$|
|$$\color{#FF8040}MangoOrange$$|$$\color{#FF7F50}Coral$$|$$\color{#F88158}BasketBallOrange$$|
|$$\color{#F9966B}LightSalmonRose$$|$$\color{#FFA07A}LightSalmon$$|$$\color{#E9967A}DarkSalmon$$|
|$$\color{#E78A61}Tangerine$$|$$\color{#DA8A67}LightCopper$$|$$\color{#FF8674}SalmonPink$$|
|$$\color{#FA8072}Salmon$$|$$\color{#F98B88}PeachPink$$|$$\color{#F08080}LightCoral$$|
|$$\color{#F67280}PastelRed$$|$$\color{#E77471}PinkCoral$$|$$\color{#F75D59}BeanRed$$|
|$$\color{#E55451}ValentineRed$$|$$\color{#CD5C5C}IndianRed$$|$$\color{#FF6347}Tomato$$|
|$$\color{#E55B3C}ShockingOrange$$|$$\color{#FF4500}OrangeRed$$|$$\color{#FF0000}Red$$|
|$$\color{#FD1C03}NeonRed$$|$$\color{#FF2400}ScarletRed$$|$$\color{#F62217}RubyRed$$|
|$$\color{#F70D1A}FerrariRed$$|$$\color{#F62817}FireEngineRed$$|$$\color{#E42217}LavaRed$$|
|$$\color{#E41B17}LoveRed$$|$$\color{#DC381F}Grapefruit$$|$$\color{#C24641}CherryRed$$|
|$$\color{#C11B17}ChilliPepper$$|$$\color{#B22222}FireBrick$$|$$\color{#B21807}TomatoSauceRed$$|
|$$\color{#A52A2A}Brown$$|$$\color{#A70D2A}CarbonRed$$|$$\color{#9F000F}Cranberry$$|
|$$\color{#931314}SaffronRed$$|$$\color{#990000}CrimsonRed$$|$$\color{#990012}RedWineRed$$|
|$$\color{#8B0000}DarkRed$$|$$\color{#800000}Maroon$$|$$\color{#8C001A}Burgundy$$|
|$$\color{#7E191B}Vermilion$$|$$\color{#800517}DeepRed$$|$$\color{#660000}RedBlood$$|
|$$\color{#551606}BloodNight$$|$$\color{#560319}DarkScarlet$$|$$\color{#3D0C02}BlackBean$$|
|$$\color{#3F000F}ChocolateBrown$$|$$\color{#2B1B17}Midnight$$|$$\color{#550A35}PurpleLily$$|
|$$\color{#810541}PurpleMaroon$$|$$\color{#7D0541}PlumPie$$|$$\color{#7D0552}PlumVelvet$$|
|$$\color{#872657}DarkRaspberry$$|$$\color{#7E354D}VelvetMaroon$$|$$\color{#7F4E52}RosyFinch$$|
|$$\color{#7F525D}DullPurple$$|$$\color{#7F5A58}Puce$$|$$\color{#997070}RoseDust$$|
|$$\color{#B1907F}PastelBrown$$|$$\color{#B38481}RosyPink$$|$$\color{#BC8F8F}RosyBrown$$|
|$$\color{#C5908E}KhakiRose$$|$$\color{#C48793}LipstickPink$$|$$\color{#C48189}PinkBrown$$|
|$$\color{#C08081}OldRose$$|$$\color{#D58A94}DustyPink$$|$$\color{#E799A3}PinkDaisy$$|
|$$\color{#E8ADAA}Rose$$|$$\color{#C9A9A6}DustyRose$$|$$\color{#C4AEAD}SilverPink$$|
|$$\color{#E6C7C2}GoldPink$$|$$\color{#ECC5C0}RoseGold$$|$$\color{#FFCBA4}DeepPeach$$|
|$$\color{#F8B88B}PastelOrange$$|$$\color{#EDC9AF}DesertSand$$|$$\color{#FFDDCA}UnbleachedSilk$$|
|$$\color{#FDD7E4}PigPink$$|$$\color{#F2D4D7}PalePink$$|$$\color{#FFE6E8}Blush$$|
|$$\color{#FFE4E1}MistyRose$$|$$\color{#FFDFDD}PinkBubbleGum$$|$$\color{#FBCFCD}LightRose$$|
|$$\color{#FFCCCB}LightRed$$|$$\color{#F6C6BD}WarmPink$$|$$\color{#FBBBB9}DeepRose$$|
|$$\color{#FFC0CB}Pink$$|$$\color{#FFB6C1}LightPink$$|$$\color{#FFB8BF}SoftPink$$|
|$$\color{#FAAFBE}DonutPink$$|$$\color{#FAAFBA}BabyPink$$|$$\color{#F9A7B0}FlamingoPink$$|
|$$\color{#FEA3AA}PastelPink$$|$$\color{#E7A1B0}RosePinkRose$$|$$\color{#E38AAE}CadillacPink$$|
|$$\color{#F778A1}CarnationPink$$|$$\color{#E5788F}PastelRose$$|$$\color{#E56E94}BlushRed$$|
|$$\color{#DB7093}PaleVioletRed$$|$$\color{#D16587}PurplePink$$|$$\color{#C25A7C}TulipPink$$|
|$$\color{#C25283}BashfulPink$$|$$\color{#E75480}DarkPink$$|$$\color{#F660AB}DarkHotPink$$|
|$$\color{#FF69B4}HotPink$$|$$\color{#FC6C85}WatermelonPink$$|$$\color{#F6358A}VioletRed$$|
|$$\color{#F52887}HotDeepPink$$|$$\color{#FF007F}BrightPink$$|$$\color{#FF1493}DeepPink$$|
|$$\color{#F535AA}NeonPink$$|$$\color{#FF33AA}ChromePink$$|$$\color{#FD349C}NeonHotPink$$|
|$$\color{#E45E9D}PinkCupcake$$|$$\color{#E759AC}RoyalPink$$|$$\color{#E3319D}DimorphothecaMagenta$$|
|$$\color{#E4287C}PinkLemonade$$|$$\color{#FA2A55}RedPink$$|$$\color{#E30B5D}Raspberry$$|
|$$\color{#DC143C}Crimson$$|$$\color{#C32148}BrightMaroon$$|$$\color{#C21E56}RoseRed$$|
|$$\color{#C12869}RoguePink$$|$$\color{#C12267}BurntPink$$|$$\color{#CA226B}PinkViolet$$|
|$$\color{#CC338B}MagentaPink$$|$$\color{#C71585}MediumVioletRed$$|$$\color{#C12283}DarkCarnationPink$$|
|$$\color{#B3446C}RaspberryPurple$$|$$\color{#B93B8F}PinkPlum$$|$$\color{#DA70D6}Orchid$$|
|$$\color{#DF73D4}DeepMauve$$|$$\color{#EE82EE}Violet$$|$$\color{#FF77FF}FuchsiaPink$$|
|$$\color{#F433FF}BrightNeonPink$$|$$\color{#FF00FF}Fuchsia$$|$$\color{#E238EC}CrimsonPurple$$|
|$$\color{#D462FF}HeliotropePurple$$|$$\color{#C45AEC}TyrianPurple$$|$$\color{#BA55D3}MediumOrchid$$|
|$$\color{#A74AC7}PurpleFlower$$|$$\color{#B048B5}OrchidPurple$$|$$\color{#B666D2}RichLilac$$|
|$$\color{#D291BC}PastelViolet$$|$$\color{#915F6D}MauveTaupe$$|$$\color{#7E587E}ViolaPurple$$|
|$$\color{#614051}Eggplant$$|$$\color{#583759}PlumPurple$$|$$\color{#5E5A80}Grape$$|
|$$\color{#4E5180}PurpleNavy$$|$$\color{#6A5ACD}SlateBlue$$|$$\color{#6960EC}BlueLotus$$|
|$$\color{#5865F2}Blurple$$|$$\color{#736AFF}LightSlateBlue$$|$$\color{#7B68EE}MediumSlateBlue$$|
|$$\color{#7575CF}PeriwinklePurple$$|$$\color{#6667AB}VeryPeri$$|$$\color{#6F2DA8}BrightGrape$$|
|$$\color{#6C2DC7}PurpleAmethyst$$|$$\color{#6A0DAD}BrightPurple$$|$$\color{#5453A6}DeepPeriwinkle$$|
|$$\color{#483D8B}DarkSlateBlue$$|$$\color{#4E387E}PurpleHaze$$|$$\color{#571B7E}PurpleIris$$|
|$$\color{#4B0150}DarkPurple$$|$$\color{#36013F}DeepPurple$$|$$\color{#2E1A47}MidnightPurple$$|
|$$\color{#461B7E}PurpleMonster$$|$$\color{#4B0082}Indigo$$|$$\color{#342D7E}BlueWhale$$|
|$$\color{#663399}RebeccaPurple$$|$$\color{#6A287E}PurpleJam$$|$$\color{#8B008B}DarkMagenta$$|
|$$\color{#800080}Purple$$|$$\color{#86608E}FrenchLilac$$|$$\color{#9932CC}DarkOrchid$$|
|$$\color{#9400D3}DarkViolet$$|$$\color{#8D38C9}PurpleViolet$$|$$\color{#A23BEC}JasminePurple$$|
|$$\color{#B041FF}PurpleDaffodil$$|$$\color{#842DCE}ClematisViolet$$|$$\color{#8A2BE2}BlueViolet$$|
|$$\color{#7A5DC7}PurpleSageBush$$|$$\color{#7F38EC}LovelyPurple$$|$$\color{#9D00FF}NeonPurple$$|
|$$\color{#8E35EF}PurplePlum$$|$$\color{#893BFF}AztechPurple$$|$$\color{#9370DB}MediumPurple$$|
|$$\color{#8467D7}LightPurple$$|$$\color{#9172EC}CrocusPurple$$|$$\color{#9E7BFF}PurpleMimosa$$|
|$$\color{#CCCCFF}Periwinkle$$|$$\color{#DCD0FF}PaleLilac$$|$$\color{#967BB6}LavenderPurple$$|
|$$\color{#B09FCA}RosePurple$$|$$\color{#C8A2C8}Lilac$$|$$\color{#E0B0FF}Mauve$$|
|$$\color{#D891EF}BrightLilac$$|$$\color{#C38EC7}PurpleDragon$$|$$\color{#DDA0DD}Plum$$|
|$$\color{#E6A9EC}BlushPink$$|$$\color{#F2A2E8}PastelPurple$$|$$\color{#F9B7FF}BlossomPink$$|
|$$\color{#C6AEC7}WisteriaPurple$$|$$\color{#D2B9D3}PurpleThistle$$|$$\color{#D8BFD8}Thistle$$|
|$$\color{#DFD3E3}PurpleWhite$$|$$\color{#E9CFEC}PeriwinklePink$$|$$\color{#FCDFFF}CottonCandy$$|
|$$\color{#EBDDE2}LavenderPinocchio$$|$$\color{#E1D9D1}DarkWhite$$|$$\color{#E9E4D4}AshWhite$$|
|$$\color{#EDE6D6}WhiteChocolate$$|$$\color{#FAF0DD}SoftIvory$$|$$\color{#F8F0E3}OffWhite$$|
|$$\color{#F8F6F0}PearlWhite$$|$$\color{#F3E8EA}RedWhite$$|$$\color{#FFF0F5}LavenderBlush$$|
|$$\color{#FDEEF4}Pearl$$|$$\color{#FFF9E3}EggShell$$|$$\color{#FEF0E3}OldLace$$|
|$$\color{#FAF0E6}Linen$$|$$\color{#FFF5EE}SeaShell$$|$$\color{#F9F6EE}BoneWhite$$|
|$$\color{#FAF5EF}Rice$$|$$\color{#FFFAF0}FloralWhite$$|$$\color{#FFFFF0}Ivory$$|
|$$\color{#FFFFF4}WhiteGold$$|$$\color{#FFFFF7}LightWhite$$|$$\color{#F5F5F5}WhiteSmoke$$|
|$$\color{#FBFBF9}Cotton$$|$$\color{#FFFAFA}Snow$$|$$\color{#FEFCFF}MilkWhite$$|

```css
"Published on my 18th birthday"🥳
```
