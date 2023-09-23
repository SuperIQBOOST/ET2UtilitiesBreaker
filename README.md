# ET2UtilitiesBreaker
去除EnigTech2中的模组限制
# ETutilBreaker食用方法 
前往 [Releases](https://github.com/SuperIQBOOST/ET2UtilitiesBreaker/releases) 下载Releases，然后将jar放在.minecraft或者版本隔离(.Minecraft\Versions\版本游戏名\)下面<br>
前往添加Java虚拟机参数 -javaagent:etutilsBreaker.jar<br>
启动即可一键裂开限制
# 加模组崩端是怎么一回事
mods文件夹下面有个etutil-1.4.jar，会在Forge PreInit的时候历遍bannedModIds数组检查是否有被ban的mod，若存在就会触发<br>
`CrashReport cr = CrashReport.func_85055_a(new IllegalAccessError(), String.format("", new Object[0]));` 抛出一个申秘错误
# GameStage解锁限制与加速火把的ToolTip
加速火把ToolTip修改位置: `.minecraft\scripts\crafttweaker\expert\vanilla\StageThree\torcherio.zs`<br>
GameSatge作弊者之耻解锁限制: `.minecraft\scripts\crafttweaker\events\onCommand.zs`<br>
加速火把列入作弊者之耻神秘文件 `.minecraft\scripts\crafttweaker\expert\mods\modularMachinery\blast_furnaces\blast_furnace_mk6.zs`<br>
将上述文件扬了即可去除限制<br>
