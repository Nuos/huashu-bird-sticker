# 花叔开源：全球鸟类贴纸库

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · **简体中文** · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

<a href="https://birdalbum.com/zh/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker"><img src="previews/birdalbum-zh.webp" alt="Bird Album：世界上每一种鸟，一种一张贴纸。birdalbum.com" width="100%"></a>

**这套贴纸的完整用法，去[birdalbum.com](https://birdalbum.com/zh/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker)看。** Bird Album是用这个贴纸库做的免费鸟类网站：15种语言都能搜鸟名，看每种鸟分布在哪、几月能见到；地图上有8,171个观鸟点，每处都列出这个月大家常记录的鸟。

[花叔](https://github.com/alchaincyf)开源的全球鸟类贴纸库，贴纸出自花叔做的观鸟App「鸣迹」。按全球统一鸟类名录[AviList v2026](https://www.avilist.org/)整理，共11011种鸟、45目249科。AviList是IOC与Clements两份名录在2025年合并而成的共识名录。全部现生种都在其中，另有43种已有贴纸、但被AviList标为灭绝、野外灭绝或可能灭绝的种也保留了。10973种已有贴纸，另外38种是近年新拆分的种，正在画。每种鸟都配有结构化数据：分类、最多43种语言的鸟名、各大数据库的编号，以及每张贴纸的来历。

> **2.0版把分类从IOC 15.2换成了AviList v2026。** 82种改了学名（`id`和贴纸路径随之改变），91个原独立种现在是别种的亚种，另有30个新种从原有物种中拆出。每一处变化都列在[`data/crosswalk-ioc15.2-avilist2026.csv`](data/crosswalk-ioc15.2-avilist2026.csv)里，每条记录的`previous`保留了旧的IOC编号。详见[更新记录](CHANGELOG.md)。

![40张贴纸，来自15个目](previews/hero.webp)

**授权一句话：** 贴纸按[CC BY 4.0](LICENSE.md)授权，可以免费用于任何用途，包括商用、修改和再分发，只要注明来自huashu-bird-sticker并附上仓库链接。数据按MIT授权，第三方部分见[NOTICE](NOTICE.md)。

## 画廊

18个最多彩、长相最有特点的类群，每组24张，尽量挑彼此长得不一样的。这里展示的都是达到质量线的贴纸。

### 蜂鸟 · *Trochilidae* — 361种

![蜂鸟](previews/families/trochilidae.webp)

### 鹦鹉 · *Psittaciformes* — 391种

![鹦鹉](previews/families/parrots.webp)

### 翠鸟 · *Alcedinidae* — 123种

![翠鸟](previews/families/alcedinidae.webp)

### 蜂虎、佛法僧与翠鴗 · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 69种

![蜂虎、佛法僧与翠鴗](previews/families/coraciiformes.webp)

### 巨嘴鸟与拟啄木鸟 · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 132种

![巨嘴鸟与拟啄木鸟](previews/families/toucans.webp)

### 极乐鸟与园丁鸟 · *Paradisaeidae* · *Ptilonorhynchidae* — 67种

![极乐鸟与园丁鸟](previews/families/paradisaeidae.webp)

### 八色鸫 · *Pittidae* — 46种

![八色鸫](previews/families/pittidae.webp)

### 裸鼻雀 · *Thraupidae* — 392种

![裸鼻雀](previews/families/thraupidae.webp)

### 太阳鸟与啄花鸟 · *Nectariniidae* · *Dicaeidae* — 207种

![太阳鸟与啄花鸟](previews/families/nectariniidae.webp)

### 伞鸟与娇鹟 · *Cotingidae* · *Pipridae* — 120种

![伞鸟与娇鹟](previews/families/cotingas.webp)

### 雉鸡 · *Phasianidae* — 185种

![雉鸡](previews/families/phasianidae.webp)

### 鸭、雁与天鹅 · *Anatidae* — 164种

![鸭、雁与天鹅](previews/families/anatidae.webp)

### 鸠鸽 · *Columbidae* — 338种

![鸠鸽](previews/families/columbidae.webp)

### 梅花雀与文鸟 · *Estrildidae* — 138种

![梅花雀与文鸟](previews/families/estrildidae.webp)

### 鸦科：松鸦与鹊 · *Corvidae* — 135种

![鸦科：松鸦与鹊](previews/families/corvidae.webp)

### 拟鹂与酋长鹂 · *Icteridae* — 107种

![拟鹂与酋长鹂](previews/families/icteridae.webp)

### 犀鸟 · *Bucerotidae* — 64种

![犀鸟](previews/families/bucerotidae.webp)

### 椋鸟与八哥 · *Sturnidae* — 118种

![椋鸟与八哥](previews/families/sturnidae.webp)

### 每个目各一只

![每个目各一只](previews/orders.webp)

## 里面有什么

| | |
|---|---|
| `stickers/<目>/<科>/<属_种>.webp` | 每种一张透明底白边贴纸，长边约1000像素。`<属_种>.<亚种>.webp`是91张亚种贴纸，它们原本是独立种 |
| `data/species.json` | 每种一条记录，最完整的数据：分类、鸟名、编号、分布与亚种、形态与生态、保护等级、贴纸及其来历。字段说明见[data/README.md](data/README.md) |
| `data/species.csv` | 同上，摊平成表格，方便用Excel打开 |
| `data/crosswalk-ioc15.2-avilist2026.csv` | IOC 15.2的每个种在AviList v2026里对应什么：不变、改名、并入、拆分 |
| `data/names.csv` | 43种语言的鸟名（46列：中文、法文、葡萄牙文各有两个版本） |
| `data/languages.json` | 语言代码，以及每种语言对应IOC多语种表里的哪一列 |
| `data/field-guide.zh-Hans.json` | 1596种鸟的中文图鉴文字（一句话印象、辨识要点、雌雄幼鸟、相似种、小知识），CC BY-SA 4.0 |

记录的结构见[英文说明](README.md#whats-inside)里的示例。

## 覆盖情况

- 鸟名：英文用AviList的英文名，覆盖全部物种。其他语种来自IOC多语种名录，只在分类范围没变的种上沿用；有129种因为合并、拆分改变了范围或是新种，旧名可能指的是另一群鸟，我们宁可空着也不硬套。简体中文覆盖10947种，范围变了的种逐条人工核过；法文、西班牙文、德文、俄文、日文、繁体中文都超过94%；韩文、阿拉伯文、泰文、波斯文等只有几百到一千来种，因为IOC名录里只有这么多。
- 繁体中文直接取自IOC，中国台湾、中国香港的常用鸟名有时不同，欢迎补充。
- 编号：eBird 10983种、Avibase 11011种，都取自AviList；Wikidata 10757种，GBIF 10477种。
- 贴纸：11011种里有10973种，另有91张亚种贴纸。还没有贴纸的38种，记录里写`"sticker": null`。

## 贴纸怎么来的，质量如何

全部11064个贴纸文件都是AI绘制。每种鸟先找一张参考照片（有453种找不到一张合用的照片，就用几张图拼成参考板，加上文字描述），用GPT-image画成贴纸，再放大、抠图。

每张AI贴纸画完后，由另一位审核员对照参考照逐项核对辨识特征并打分：喙、眼、腿脚、羽色和斑纹。最后一轮里，852张80到82分压线的贴纸又由另一人盲审一遍，其中211张没通过，打回重新生成。更早几轮的压线贴纸没有做这道盲审。2026年11月，我们按图鉴图版的更严标准重新审核了这些贴纸，并重新生成了9416张。重新生成的贴纸只有在辨识、羽色与斑纹、喙与眼、腿脚、比例五项评分均至少3分（每项满分4分），辨识项达到4分，且审核员认可其可用作图鉴图版时，才算过线。

- **10870张达到我们的质量线**（`"meetsQualityBar": true`）：通过上述更严审核，或在此前审核中达到80分及以上的贴纸。
- **194张没有达到。** 为了不让任何一种鸟没有图，我们保留了得分最高的那一版：其中190张在70到79分，4张低于70分。我们正在重新生成这些贴纸；要修的是哪类错误，可以看[issue #1](../../issues/1)和[issue #3](../../issues/3)。
- **少数贴纸只依据文字描述生成**，没有用参考照片（`data/species.json` 里 `"reference": null`，数量见 [data/README.md](data/README.md#reference-photos)）。它们比对照过照片的贴纸更容易画错。在 [birdalbum.com](https://birdalbum.com/) 上，这些贴纸和没达到质量线的贴纸，鸟种页面都会另外提示。

这些是插画，不是图鉴图版。当作一张友好的鸟的画像来用；涉及细节辨识，请以图鉴为准。发现画错了，欢迎[提issue](../../issues/new/choose)。鸟友的纠错，是这个项目最需要的贡献。

## 参考照片

**参考照用来做什么**。一张贴纸要表现的是这种鸟长什么样：羽色与斑纹、喙、眼、腿脚和身体比例。这些是关于这种鸟的事实，也是野外图鉴用文字描述的同一批内容。只靠文字说明，生图模型常常画不准，所以我们使用参考照片。

**我们怎么用参考照**。画每一种鸟时，生图模型会看到一张或几张参考照片和一段辨识特征的文字说明，然后画出一张新的插画。我们不使用照片的构图、背景和光线：2026年11月起重新生成的贴纸，不管照片里的鸟是什么姿态，一律画成我们定的同一种正侧面标准姿势，背景留空。画完后由另一个审核模型按辨识特征检查。今后我们会尽量为每种鸟采用多位观测者的照片，让贴纸反映的是这个物种，而不是某一张照片。仓库里不含任何参考照片。

**署名与撤下**。每张贴纸用到的参考照片（页面、作者、许可）写在`data/species.json`的`sticker.reference`里，每张都能追溯来源；按参考照许可的分类统计见[data/README.md](data/README.md#reference-photos)。如果你的照片被用作参考，而你不希望这样，请提issue或发邮件到alchaincyf@gmail.com，我们会在7天内替换这张贴纸。

## 怎么用

单张图可以直接引用：

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

整个仓库约700MB。只想要数据和某一个目的贴纸，可以这样拉：

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## 致谢

- 分类、英文名、分布、eBird与Avibase编号：AviList Core Team. 2026. AviList: The Global Avian Checklist, v2026. https://doi.org/10.2173/avilist.v2026，CC BY 4.0。
- 其他语种鸟名：IOC世界鸟类名录v15.2，Gill、Donsker与Rasmussen编，CC BY 3.0。
- 其他数据库编号：Wikidata（CC0）。
- 形态与生态数据：AVONET，Tobias等，2022，《Ecology Letters》，CC BY 4.0。
- 参考照片的摄影师：逐种写在`data/species.json`里。参考照片本身不在仓库中。
- 贴纸为观鸟记录App「鸣迹」绘制。

如果你的照片被用作某张贴纸的参考，而你不希望这样，请提issue或发邮件到alchaincyf@gmail.com，我们会在7天内替换这张贴纸。
