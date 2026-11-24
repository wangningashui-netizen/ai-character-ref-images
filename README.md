# 如水·角色参考 · 图片存档

这是网站「如水·角色参考」用到的参考图副本。图片放在这个仓库里，网站打开时从这里读取，不再临时去原作者的网站上取图。

每张图都按「原来的网站地址」原样存放。网站只要把开头的网址换成这个仓库的地址，后面的路径不用改。

## 这些图是谁的

图和原始资料属于原作者。这个仓库只是存一份，方便自己的网站还能打开。

| 内容 | 原作者 | 原来的读取地址 |
| --- | --- | --- |
| 姿势白模 | ギア（@giaaibusi） | https://ai-pose-gallery.pages.dev/ |
| 姿势深度图 | ギア（@giaaibusi） | https://ai-pose-depth-gallery.pages.dev/ |
| 写实服装 | ギア（@giaaibusi） | https://ai-costume-gallery.pages.dev/ |
| 人像 | ギア（@giaaibusi） | https://ai-portrait-gallery.pages.dev/ |
| 动漫服装 | ギア（@giaaibusi） | https://ai-costume-anime-gallery.pages.dev/ |
| 二次元服装 | たき AI（@taki_auto，CharaDB） | https://charadb-2fi.pages.dev/ |
| 中国历代服装 | Shisei / wquguru | jsDelivr 上的固定版本，仓库 https://github.com/wquguru/shisei ，版本号 `8f61ceab10e45f8d3afd254900903733a0ba76ee` |

中文目录来自 [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh)。那个项目的代码是 MIT 许可，**只覆盖程序，不覆盖图片**。

Shisei 的服装图是 CC0（可以自由使用），使用时请注明来自 Shisei / wquguru。这些图是人工智能生成的参考，不是专业的历史服饰复原。

## 只能自己参考，不能拿去卖

除了上面单独说明的 Shisei（CC0）以外，这些图按原作者的要求，只供非商业的个人参考。不要拿去出售，不要放进商业产品，不要拿掉署名当作自己的作品。

如果原作者要求删除，这个仓库会马上去掉对应图片。请到本仓库开一个 Issue，或联系仓库主人，写明要删除的内容和你是权利人。

## 文件夹对照

| 本仓库文件夹 | 对应原来的网站 |
| --- | --- |
| `poses/` | 姿势白模 |
| `poses-depth/` | 姿势深度图 |
| `costumes/` | 写实服装 |
| `portraits/` | 人像 |
| `costumes-anime/` | 动漫服装 |
| `charadb/` | 二次元服装 |
| `shisei/` | 中国历代服装 |

每一张图在文件夹里的后半段路径，和原网站地址里的后半段相同。例如原来是 `https://ai-pose-gallery.pages.dev/thumbs/某图.jpg`，这里就是 `poses/thumbs/某图.jpg`。

张数、占用空间、没下成功的地址，写在 `manifest.json`。
