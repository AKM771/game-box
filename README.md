# 小游戏合集 Game Box

四个纯前端 HTML5 小游戏：贪吃蛇 / 2048 / 打砖块 / 俄罗斯方块。打开即玩，不用安装、不用注册、不用后端；手机浏览器可玩（滑屏操作）。

在线玩：`https://akm771.github.io/game-box/`（GitHub Pages）

## 本地跑

双击 `index.html` 就行（file:// 直开），或者：

```
python -m http.server 8000
# http://127.0.0.1:8000/
```

## 文件

| 文件 | 说明 |
|---|---|
| index.html | 首页卡片墙 |
| snake.html | 贪吃蛇（方向键/滑屏，最高分 localStorage） |
| 2048.html | 2048（方向键/WASD/滑屏） |
| breakout.html | 打砖块（鼠标/滑屏挡板，3 命进关） |
| tetris.html | 俄罗斯方块（←→↑空格 P/R，手机滑屏） |

零依赖、零构建、零请求——每页自包含（内联样式脚本），推 GitHub Pages 即上线。

## 许可

GPL-3.0，见 [LICENSE](LICENSE)。反馈：jjonju361999@qq.com
