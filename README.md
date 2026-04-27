# 星石防线 Starstone Defense

一个 **HTML + Canvas + JavaScript** 编写的伪 3D 电影视角塔防游戏原型，可直接发布到 GitHub Pages。

## 特性

- 单文件运行，无第三方依赖，无图片资源依赖
- 伪 3D 低机位视角，而不是传统俯视塔防
- 战役关卡、关卡解锁、三星评价
- 科技树、成就系统、星石碎片奖励
- 每日挑战，根据日期生成固定挑战词条
- 本地存档 localStorage，支持导出 JSON
- 5 种防御塔、8 种敌人、Boss、治疗、分裂、隐匿机制
- 音效、低频氛围音乐、电影特效、伤害数字、自动开波
- 适合直接作为 GitHub Pages 静态站点发布

## 本地运行

直接双击 `index.html` 即可运行。浏览器第一次播放声音需要先点击页面，这是浏览器限制。

## 发布到 GitHub Pages

1. 新建 GitHub 仓库，例如 `starstone-defense`。
2. 上传本目录所有文件。
3. 进入仓库 `Settings` → `Pages`。
4. Source 选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
5. 等待部署完成后访问 GitHub Pages 地址。

## 快捷键

- `1-5`：选择防御塔
- `Enter`：开始下一波
- `Space`：暂停/继续
- `U`：升级选中的塔
- `S`：出售选中的塔
- `Esc`：返回菜单

## 后续可继续升级方向

- 拆分为 ES Module 工程
- 加入真实美术资源和音频资源
- 增加关卡编辑器
- 加入云存档和在线排行榜
- 使用 Electron/Tauri 打包桌面版

## License

MIT
