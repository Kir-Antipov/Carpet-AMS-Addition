

### [ 中文 | [English](/carpetamsaddition/en_us/Commands_en) ]

# <center>------ 指 令 ------</center>

&emsp;

### 区块加载控制（commandPlayerChunkLoadController）

`/playerChunkLoading [true/false]`

开关玩家自身加载。


### 禁用铁砧交互（commandAnvilInteractionDisabled)

`/anvilInteractionDisabled [true/false]`

控制玩家是否可与铁砧交互。

### 更新抑制崩溃修复（amsUpdateSuppressionCrashFix）

`/amsUpdateSuppressionCrashFixForceMode [true/false]`

控制是否在开启 `自定义方块更新抑制器（customBlockUpdateSuppressor）` 规则开启时是否强制开启。

### 自定义方块爆炸抗性（commandCustomBlockBlastResistance）

- `/customBlockBlastResistance set <block> <hardness>`

  添加或修改方块及其爆炸抗性。

  

- `/customBlockBlastResistance remove <block>`

  从列表中移除方块。

  

- `/customBlockBlastResistance removeAll`

  移除列表中的所有方块。

  

- `/customBlockBlastResistance list`

  显示所有添加的方块。

### 我在哪（commandHere）

- `/here`

发送当前自身所在维度、坐标、对应的主世界/下界坐标，同时给予自身30s的发光效果。

### 你在哪（commandWhere）

- `/where`

获取指定玩家所在维度、坐标、对应的主世界/下界坐标，同时给予目标玩家30s的发光效果。