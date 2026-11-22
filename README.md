# 小游戏合集 Game Box

二十二个纯前端 HTML5 小游戏：贪吃蛇 / 2048 / 打砖块 / 俄罗斯方块 / 扫雷 / 飞翔的小鸟 / 记忆翻牌 / 数字华容道 / 五子棋 / 打地鼠 / 汉诺塔 / 色彩记忆 / 井字棋 / 双人贪吃蛇 / 接水果 / 黑白棋 / 推箱子 / 别踩白块 / 躲避来车 / 算 24 点 / 记数字 / 打字测试。打开即玩，不用安装、不用注册、不用后端；手机浏览器可玩（滑屏操作）。

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
| simon.html | 色彩记忆（Simon，逐关加一盏灯，简单/普通/困难三档，困难含隐藏灯） |
| tic.html | 井字棋（对战电脑/双人同屏） |
| snake2.html | 双人贪吃蛇（P1=WASD，P2=方向键） |
| fruit.html | 接水果（左右移篮子，躲炸弹） |
| othello.html | 黑白棋（对战电脑/双人同屏） |
| sokoban.html | 推箱子（6 关，撤销+最短步参考） |
| piano.html | 别踩白块（经典/限时，慢中快三档） |
| dodge.html | 躲避来车（悠闲/繁忙/噩梦三档） |
| points24.html | 算 24 点（两两合并到 24，简单/普通/含王） |
| digit.html | 记数字（默写记忆，数字/数字+字母） |
| typing.html | 打字测试（中英文，实时速度/准确率） |
| mdi_icons.txt | 首页卡片图标 path（Google MDI，Apache-2.0，来源 Templarian/MaterialDesign） |

零依赖、零构建、零请求——每页自包含（内联样式脚本），推 GitHub Pages 即上线。

## 许可

GPL-3.0（见 LICENSE），禁止闭源商用。反馈：jjonju361999@qq.com
