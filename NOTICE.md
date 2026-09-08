# 素材与组件来源

制作者：温州肯恩大学室内乐团WKCO

制作者图标由用户提供，原样保存为 assets/wkco-logo.png；角色及第三方组件的署名见下文。

WKCO 举旗素材 assets/cycle-wkco_flag.png 使用内置图像生成工具，以既有 cycle-banner.png 为角色参考生成。最终提示词要点：四列两行八帧；蓝发鲸尾女仆正面持旗杆；白旗深蓝字，三行依次为“温州肯恩大学”“室内乐团”“WKCO牛逼”；文字随布面轻微飘动；双手握同一根旗杆、双脚位置固定，绿背景，角色与旗帜完整，无多余手臂。原神横幅继续保留。图标原图未重绘，旗帜为独立新增动作。

本项目是个人用、非官方鲸鱼娘桌宠，与 DeepSeek 官方无隶属或合作关系。

## 角色与动作素材

- 鲸鱼娘原作：上善（Bilibili：上善无形）。
- 女仆装二次设计：ZipZipPipe。
- 本包 10 组 PNG 动作素材与清单摘取自 vlln/whale-girl，未修改图片。
- 来源：https://github.com/vlln/whale-girl/tree/main/lib/assets
- 上游鸣谢：https://github.com/vlln/whale-girl#acknowledgements
- 角色署名链交叉资料：https://dsh.pub/zh/plugins/whale-girl-plus/

上游代码采用 MIT（assets/UPSTREAM-LICENSE）。角色素材遵循原作者的 CC BY-NC-SA 4.0 非商业、署名和相同方式共享要求；代码许可不覆盖角色原作权利。本包按个人非商业使用范围整理，保留署名。作者原始声明优先。
https://creativecommons.org/licenses/by-nc-sa/4.0/

本次新增 acrobatics-green.png 为参照上述角色形象由 ImageGen 生成的跳跃、下落、攀爬与悬挂动作素材。绿色背景仅用于程序运行时色键透明处理，原图保留；衍生角色素材沿用同一署名与非商业、相同方式共享要求。

## 硬件监测

LibreHardwareMonitor v0.9.6 官方 Windows 发行版，MPL-2.0。
https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/releases/tag/v0.9.6
源代码：https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/tree/v0.9.6
许可文件见 sensors/LICENSE.txt 与 THIRD-PARTY-NOTICES.txt。
PawnIO_setup.exe 从同一官方发行版的内嵌资源原样提取；它是可选的硬件访问驱动安装程序，不会由桌宠自动静默安装。

## 窗口与依赖

Qt for Python / PySide6-Essentials 6.6.3.1（LGPLv3 等，随包提供动态库）；psutil 7.2.2（BSD-3-Clause）；Python 3.8（PSF）。第三方许可随程序置于 licenses。
Qt/PySide 源码：https://download.qt.io/official_releases/QtForPython/pyside6/PySide6-6.6.3.1-src/
Qt 源码：https://download.qt.io/archive/qt/6.6/6.6.3/single/
本程序原创 Python 与 C# 源码附在 source，允许个人修改、重建、替换兼容的 LGPL 动态库，以及为调试这些修改进行必要的逆向工程。


交替抓握素材 assets/grip-cycle-green.png 使用内置图像生成工具，以现有鲸鱼娘素材为身份参考生成；用于本项目攀爬和悬挂关键帧。仍遵循角色原作和二次设计的非商业使用要求。提示词摘要：四列两行，保留蓝发鲸尾女仆形象，左向攀爬左右手交替支撑，悬挂左右手交替换握，纯绿背景，每格完整角色和足够留白。


连续动作版本：assets/puppet-body-green.png 由内置图像生成工具参考现有鲸鱼娘角色生成正面和侧面身体底图；动态手臂、抹布、锥子与横幅由程序绘制，保持正文标注的角色使用范围。旧 grip-cycle-green.png 已停用并移出交付包。


本次完整帧版本以 assets/full-grip.png、full-tools.png、full-banner.png、full-wavebox.png 替代程序关节素材。通过内置图像生成工具参考现有角色生成，仍遵循原作与女仆设计使用范围。提示词摘要：保留鲸鱼娘形象，四列两行完整角色序列，攀爬抬膝蹬腿、悬挂摆腿、敲锥子、擦布、空白横幅、挥手伸懒腰，纯绿背景，无字木箱。

V8 连贯性修订：assets/cycle-climb.png、cycle-wipe.png、cycle-banner.png 均由内置图像生成工具参考既有角色重画，四列两行各八帧。提示词摘要：攀爬采用抬手抓握、屈膝、蹬腿的连续小步姿态；擦拭保持同一只手持布往返、双脚站稳；横幅直接写“原神牛逼”，布面微动，只有两只真实持布的手。所有图片纯绿背景，加载时抠除，统一裁切比例；擦拭和横幅按脚底对齐。此前空白横幅上的独立文字叠加与单帧镜像悬挂均已停用。

V9：保留 cycle-climb.png 原图，仅校准播放坐标。新悬挂原图 assets/cycle-hang.png 由内置图像生成工具参考 full-grip.png 的正面鲸鱼娘生成，未使用 CLI。提示词要点：四列两行八帧，正面朝向不变、尾巴始终位于观众右侧，左手支撑右手短距离换握，然后右手支撑左手换握；始终至少一手抓住头顶横向边缘，膝盖轻微交替弯曲，无大幅踢腿，两只手臂两条腿，纯绿背景。后续两次局部修订只修正换握手的高度和一帧多余手臂。grip-registration.json 保存实测的逐帧坐标；水平留边切片保留伸出格子的完整尾巴。

V12 换肤：保留原鲸鱼娘素材与署名，新增《原神》诺艾尔同人皮肤。诺艾尔角色来源为米哈游《原神》，角色权利归原权利人。新增动作图由内置 image_gen.imagegen 工具生成，并非官方原始游戏贴图；未使用 CLI/API 后备生成路径。最终提示词见 assets/skins/noelle/generated/prompts.json，生成原图与定位数据在同目录。处理步骤为格子切片、色键透明化、统一缩放和整帧定位，未拼接程序绘制的手臂。运行时读取透明动作帧，角色皮肤与自主行为独立。
