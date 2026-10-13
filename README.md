# Suzuka‘s Grenadier rotation v1.0.0

让 E/GL-21 掷弹兵防卫墙在操控时整体水平旋转 360°：炮、底座和墙体一起转，不再卡在左右约 90°。

## 安装

1. 需要 Bingus Shared Loader v15 或更新版本。
2. 在 Mod 管理器导入本 ZIP，并启用它和 Bingus Shared Loader。
3. 如果装过 Grenadier Battlement Whole Rotation 的测试版，本包会直接替换它们。请同时禁用旧的“Grenadier Battlement 360”模板版。
4. 重启游戏。

## 操作

- 上墙操控后，鼠标瞄准超过约 25° 范围时，整座墙会跟着转向。
- 按住 A 左转，按住 D 右转。两键同时按下时停止转动；松开后恢复鼠标跟转。按键固定为 A/D，不跟随游戏的键位重绑定。
- 最高转速 90°/秒，带平滑加减速。
- 可以部署多座墙，只有你正在操控的那一座会转动。

## 说明

- 只读取游戏状态，并调用引擎的单位旋转接口；不修改游戏文件、模板或代码。
- 游戏版本校验不匹配时自动停用，不会执行旋转。
- 联机时队友端能否看到同步的转向尚未验证。
- 日志：`%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\SuzukaGrenadierRotation.log`。反馈问题时请附上该日志。

## 卸载

退出游戏后，在 Mod 管理器中禁用本包。
