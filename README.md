# Minecraft_advancement_diable_tool
disable the advancements in folder

一键隐藏 Minecraft Java 版原版进度。适用于 RPG、解谜地图或纯净数据包开发，彻底移除原版进度干扰，同时保留自定义进度树完整显示。

## 使用方法

1. 抽取或者任意一个 `advancement` 文件夹（允许有子文件夹）
2. 将` DisableAdvancements.ps1` 和`advancement` 文件夹放在一个文件夹中
3. 运行` DisableAdvancements.ps1` 
4. `advancement` 被成功无效化

## 注意
1. 记得备份原进度以防后悔
2. 被无效化的进度内容全都变为
   ` {
  "criteria": {
    "impossible": {
      "trigger": "minecraft:impossible"
    }
  }
}` 
这意味着只能通过命令获得和解除，并且不显示在进度界面中

## 例子
这里有一个处理好的1.21.10的原版进度文件供参考
