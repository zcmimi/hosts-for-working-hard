# Hosts-for-working-hard
## 描述
用于防止机房聚众颓废的黑名单 hosts / 白名单列表。

各种颓废网站按照类别存放在该类别文件的黑名单文件夹。

各种用于学习的网站按照类别分别存放在白名单文件夹

另外，脚本也可以生成 `.xml` 文件用于极域电子教室导入。

## 使用方式
主要文件：
* `config/*.list`：网站列表。
* `gen.py`：根据网站列表及给定参数生成输出文件。

输出文件：
* `mythware_classroom.xml`：用于极域电子教室导入的配置文件。
* `hosts`：用于替换系统自带的 `hosts` 文件。
  - Linux 下通常位于 `/etc/hosts`。
  - Windows 下通常位于 `C:\WINDOWS\system32\drivers\etc\hosts`。
* `black.list/white.list`：黑/白名单 网站的纯列表。
  
## TODO
* 发现并添加新的颓废网站。
* 发现并添加新的学习网站。

（欢迎大家在 Issues 中补充）

## 创作笔记 by Tsukimaru
颓废和进学是现代 OI 主义的根本矛盾。在这不可调和的矛盾的影响下，STJZOI 正面临着颓废大危机——这样下去，STJZOI 的光辉将一去不复返，新建的机房又将沦为新的网吧。思想不进步，不解放，纵使建造多少的新机房，也终究是充盈着腐朽的风气。

为了拯救危在旦夕（？）的 STJZOI，以 Tsukimaru 为首的极右（极端学习主义，英文：Farly Studism）集团上任，宣布了一项极端的政策：免去无用的颓废！

这一计划被人们称为：机房除草剂（英文：Anti-LeaF Potion）。

---

后来由于这个构想是 JZOI 改革闭关的总设计师——zcmimi 首先提出的，所以名字还是采用了 zcmimi 提供的名字。
