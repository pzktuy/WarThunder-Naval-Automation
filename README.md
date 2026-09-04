此智驾系统源自战争雷霆苹果派助手，https://github.com/JerryLikePie/WT-ApplePie-Assistant，但很显然已经经过了Adobe_Hit_乐的爆改。
仅用作实验自动驾驶，无法刷钱刷分（并非）。 
A ship AI driving system based on the War Thunder ApplePie Naval Assistant,(https://github.com/JerryLikePie/WT-ApplePie-Assistant), but has clearly undergone extensive modifications by Adobe_Hit_乐.
It is intended solely for testing automated driving and cannot be used to farm Silver Lions or score (not really).

————————————————重大更新——————————————————
启动后能够全自动运行获取银狮。
对局内遇到搁浅、走出小地图时能够自动识别避障。
能够自动跟踪游戏内测距后得到的提前量

建议安装 Tesseract-OCR 引擎，可获得额外功能：
计算获得的银狮收益

* Once started, the script can run fully automatically to earn Silver Lions.
* Automatically detects and avoids obstacles when the ship runs aground or leaves the minimap.
* Automatically tracks the lead calculated from the in-game rangefinder.

**Tesseract-OCR engine is recommended** for additional features:
* Calculate the Silver Lions earned.
——————————————————————————————————————

需要进行的战争雷霆设置
▶图像设定：
　分辨率：1270x720
　显示模式：窗口模式
　UI大小：100%

▶主要参数->海战设置：
　AI攻击模式：任意目标
　自动锁定目标：开

▶按键设置->海战：
　目标跟踪（海战）：=
　手动瞄准修正：左侧shift
　停车：b
　海战瞄准控制X轴：
　　增加数值：]
　　减少数值：[
　视角缩放：鼠标右键

▶队列设置：在队列中放入一条船并选中
▶游戏模式：海战历史
▶界面语言：中文

**War Thunder settings required:**
▶ Graphics Settings:
　Resolution: 1270x720
　Display Mode: Windowed
　UI Scale: 100%

▶ Main Parameters -> Naval Settings:
　AI Attack Mode: Any Target
　Auto-Lock Target: On

▶ Key Bindings -> Naval:
　Target Tracking (Naval): =
　Manual Aim Correction: Left Shift
　Stop: B
　Naval Aim Control — X-Axis:
　　Increase Value: ]
　　Decrease Value: [
　View Zoom: Right Mouse Button

▶ Queue Settings: Put one ship in the queue and select it.

▶ Game Mode: Naval Historical Battles

▶ Interface Language: Chinese

将游戏处于车库（船坞）的界面下，打开终端进入到（VScode打开文件夹）autoscriptVxxx文件夹下，运行autoscriptVxxx.py
With the game at the Garage (Dock) screen, open a terminal and navigate to the `autoscriptVxxx` folder (open the folder in VS Code), then run `autoscriptVxxx.py`.

当图形界面弹出后选择船只类型（如巡洋舰），然后切换回战争雷霆界面即可
When the graphical interface appears, select the ship type (e.g., Cruiser), then switch back to War Thunder.

使用脚本有概率被封号，尤其是长时间运行！(我的账号曾因为连续数天运行脚本已在2026年8月健康行动中被封禁！)因此在最新的更新中加入了限制运行时间等一系列优化与人性化的修改。
**Using this script carries a risk of account suspension, especially when running it for extended periods!** (My account was banned after continuously running the script for serveral days during the August 2026 Health Action!)Therefore, the latest update includes runtime limits and a series of other optimizations and user-friendly improvements.

请到右侧release区域下载最新的程序
To download the Program please go to the Release area
