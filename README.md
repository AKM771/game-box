# 小游戏合集 Game Box

十二个纯前端 HTML5 小游戏：贪吃蛇 / 2048 / 打砖块 / 俄罗斯方块 / 扫雷 / 飞翔的小鸟 / 记忆翻牌 / 数字华容道 / 五子棋 / 打地鼠 / 汉诺塔 / 色彩记忆。打开即玩，不用安装、不用注册、不用后端；手机浏览器可玩（滑屏操作）。

在线玩：`https://akm771.github.io/game-box/`（GitHub Pages）

## 本地跑

双击 `docs/index.html` 就行（file:// 直开），或者：

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
| minesweeper.html | 扫雷（三档难度，右键/长按插旗，首点安全） |
| flappy.html | 飞翔的小鸟（点/空格扇翅膀，钻管道） |
| memory.html | 记忆翻牌（4×4/6×6 配对，步数计数） |
| puzzle.html | 数字华容道（3×3/4×4 滑块，必可解洗牌） |
| gomoku.html | 五子棋（人机三档难度，黑先手） |
| whack.html | 打地鼠（30 秒抢分，金色 +3，递进加速） |
| hanoi.html | 汉诺塔（3/4/5 层，悔棋+最短解演示） |
| simon.html | 色彩记忆（Simon，逐关加一盏灯） |
| mdi_icons.txt | 首页卡片图标 path（Google MDI，Apache-2.0，来源 Templarian/MaterialDesign） |

零依赖、零构建、零请求——每页自包含（内联样式脚本），推 GitHub Pages 即上线。

## 许可

GPL-3.0（见 LICENSE），禁止闭源商用。反馈：jjonju361999@qq.com
