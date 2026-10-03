# フォーエバーヤング · Forever Young — Codex 桌宠 v2

基于 Cygames《ウマ娘 プリティーダービー》角色「フォーエバーヤング」官方决胜服制作的非官方个人同人桌宠。v2 保留 v1 的九组动作，并新增 16 个头部与眼睛视线方向。

## Codex 原生桌宠

先下载并解压仓库根目录的 `forever-young-codex-pet-v2.zip`，再把解压出的 `package/forever-young-v2` 整个文件夹复制到 `${CODEX_HOME}/pets/`；未设置 CODEX_HOME 时，目标目录为 `~/.codex/pets/forever-young-v2/`。目录中应直接包含 `pet.json` 和 `spritesheet.webp`。

在 Codex 设置的 Pets 页面点击 Refresh / 刷新，然后选择「フォーエバーヤング v2」。九组动作包括待机、左右跑动、挥手、跳跃、失落、等待回应、专注工作和审阅。v2 图集为 1536×2288、8 列×11 行、每格 192×208，共 73 个有效格（原动作 57 格 + 视线 16 格）。

## 鼠标与语音预览

仓库根目录旧的 `package/forever-young/` 是 v1 包；v2 安装包在 `forever-young-codex-pet-v2.zip` 中。解压 v2 压缩包后，在浏览器打开其中的 `preview.html` 可体验交互预览：页面内视线跟随鼠标、每次悬停只跳一次、点击播放官方原始语音并挥手。浏览器预览只接收页面内鼠标位置；这三项交互不属于 Codex 原生桌宠接口。原生客户端的视线目标来自其提供的 Computer Use 光标或输入框插入点，不能跟随普通桌面鼠标，也不能设置悬停单跳或点击语音。

## 文件与来源

- `forever-young-codex-pet-v2.zip`：v2 完整成品压缩包。
- `forever-young-codex-pet-v2.zip.sha256`：压缩包 SHA-256 校验值。
- `README.en.md`：English README.
- `CREDITS.md`：角色、语音和制作来源。

角色与官方素材权利归 Cygames 等权利人。本项目为非官方、非商业的个人粉丝作品。
