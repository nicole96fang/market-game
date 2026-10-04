小镇杂货铺 · 3D经营版 V7（手机显示修复版）

本版修复：
1. 补回 V6 脚本已经调用、但页面漏放的「批发市场」「小镇委托」「经营账簿」三个按钮。
   原来的 JavaScript 在找不到这些按钮时会报错，导致 3D 动画循环没有启动，
   所以页面只显示背景和欢迎提示，看不到杂货店。
2. 优化 iPhone Safari 的 3D 画布宽高设置与旋转屏幕后的尺寸更新。
3. 保留 V6 的经营功能、库存、顾客、采购、委托、账簿和自动保存。

部署：
- 解压 ZIP。
- 将 index.html 上传到 GitHub Pages 仓库根目录，覆盖旧 index.html。
- Commit changes，等待 GitHub Pages 更新后，在 iPhone Safari 重新载入网页。
- 建议完全关闭旧网页后重新打开；游戏存档仍保存在浏览器本机 LocalStorage。

注意：首次打开需要网络连接以加载 Three.js CDN 模块。
