Here
-------

一个 [MCDReforged](https://github.com/Fallen-Breath/MCDReforged) 的插件

当玩家输入 `!!here` 时，玩家的坐标将被显示并且将被发光效果高亮

调整代码中的 `HIGHLIGHT_TIME` 即可控制玩家是否高亮，以及自定义高亮的时长

将代码中的`VOXEL_WAYPOINT`设为`True`以显示一小段含点击事件的文本，点击以高亮坐标，ctrl点击以添加坐标点至Voxelmap

或`XAERO_WAYPOINT`设置为`True`以显示一小段含点击事件的文本，点击以添加坐标点至Xaero's Minimap

将代码中的`CLICK_TO_TP`设为`True`以让显示的坐标可以让玩家点击传送到该位置（实为补全完整的传送命令，由玩家自行执行，以减少或避免非OP传送或意外点击传送等问题）

当 MCDR 启动 rcon 时此插件可使用 rcon 来获得玩家信息，响应更快

![example](https://raw.githubusercontent.com/TISUnion/Here/MCDR/img.png)
