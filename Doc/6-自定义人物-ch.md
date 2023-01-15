- 自定义人物可以通过添加自己的图片实现其它人物的添加
- 在 `Data` 建一个名为 `Character` 的文件夹，用来存放相关文件

# 加载

- 命令 `load ch {nameId} {y} {scale} {chName}`
- 示例 `load ch Tairitsu 4.5 2 7.png`
- y 设置 Y 轴位置用来对齐
- scale 缩放图片到合适大小

# 其余命令同 spr 但需注意

- 要把 spr 用 ch 代替，如 `ch show Tairitsu` 设置了自定义图片的出现
- ch 没有 state 命令，`ch state Tairitsu 01` 是无效的，因为自定义图片没有此类数据
