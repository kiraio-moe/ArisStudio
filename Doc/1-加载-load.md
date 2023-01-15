# 人物加载

学生文件放在 `Data/Spr` 文件夹中

- 命令 `load spr {nameId} {sprName}`
- 例 `load spr midori midori_spr`

## 以通信状态加载

- 命令 `load sprC {nameId} {sprName}`
- 例 `load sprC midoriC midori_spr`
- 通信状态加载的学生可以用 `spr` 命令使用

## [自定义人物](./6-%E8%87%AA%E5%AE%9A%E4%B9%89%E4%BA%BA%E7%89%A9-ch)

# 背景加载

背景文件放在 `Data/Image/Background` 文件夹中

- 命令 `load bg {nameId} {bgName}`
- 例 `load bg GameDevRoom_Night BG_GameDevRoom_Night.jpg`

# 覆盖图片加载

覆盖图片放在 `Data/Image/Cover` 文件夹中

- 命令 `load cover {nameId} {coverName}`
- 例 `load cover Player popup02.png`

# 背景音乐加载

背景音乐放在 `Data/Bgm` 文件夹中

- 命令 `load bgm {nameId} {bgmName}`
- 例 `load bgm Theme_64 Theme_64.ogg`

# 音效加载

音效放在 `Data/Se` 文件夹中

- 命令 `load se {nameId} {seName}`
- 例 `load se Granted SE_Granted_01.wav`

# 结束加载

- 命令 `load end`
- 例 `load end`
- 此命令必须存在于加载结束后
