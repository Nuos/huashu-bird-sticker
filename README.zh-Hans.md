# 花叔开源：全球鸟类贴纸库

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · **简体中文** · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

[花叔](https://github.com/alchaincyf)开源的全球鸟类贴纸库，贴纸出自花叔做的观鸟App「鸣迹」。全世界现存的11064种鸟，每种一张白边贴纸，共44目250科，覆盖IOC世界鸟类名录v15.2里的全部现生物种（163个灭绝种不在其中）。每种鸟都配有结构化数据：分类、最多43种语言的鸟名、各大数据库的编号，以及每张贴纸的来历。

![40张贴纸，来自15个目](previews/hero.webp)

**授权一句话：** 贴纸可以免费用于任何用途，包括商用、修改和再分发；唯一不行的是拿去做观鸟、识鸟或鸟类图鉴类的App、网站或服务。使用时注明来自huashu-bird-sticker并附上仓库链接就可以。法律文本是[PolyForm Shield 1.0.0](LICENSE.md)，数据按MIT授权，第三方部分见[NOTICE](NOTICE.md)。

## 画廊

18个最多彩、长相最有特点的类群，每组24张，尽量挑彼此长得不一样的。这里展示的都是达到质量线的贴纸。

### 蜂鸟 · *Trochilidae* — 365种

![蜂鸟](previews/families/trochilidae.webp)

### 鹦鹉 · *Psittaciformes* — 392种

![鹦鹉](previews/families/parrots.webp)

### 翠鸟 · *Alcedinidae* — 116种

![翠鸟](previews/families/alcedinidae.webp)

### 蜂虎、佛法僧与翠鴗 · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68种

![蜂虎、佛法僧与翠鴗](previews/families/coraciiformes.webp)

### 巨嘴鸟与拟啄木鸟 · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134种

![巨嘴鸟与拟啄木鸟](previews/families/toucans.webp)

### 极乐鸟与园丁鸟 · *Paradisaeidae* · *Ptilonorhynchidae* — 69种

![极乐鸟与园丁鸟](previews/families/paradisaeidae.webp)

### 八色鸫 · *Pittidae* — 46种

![八色鸫](previews/families/pittidae.webp)

### 裸鼻雀 · *Thraupidae* — 393种

![裸鼻雀](previews/families/thraupidae.webp)

### 太阳鸟与啄花鸟 · *Nectariniidae* · *Dicaeidae* — 208种

![太阳鸟与啄花鸟](previews/families/nectariniidae.webp)

### 伞鸟与娇鹟 · *Cotingidae* · *Pipridae* — 121种

![伞鸟与娇鹟](previews/families/cotingas.webp)

### 雉鸡 · *Phasianidae* — 185种

![雉鸡](previews/families/phasianidae.webp)

### 鸭、雁与天鹅 · *Anatidae* — 166种

![鸭、雁与天鹅](previews/families/anatidae.webp)

### 鸠鸽 · *Columbidae* — 339种

![鸠鸽](previews/families/columbidae.webp)

### 梅花雀与文鸟 · *Estrildidae* — 140种

![梅花雀与文鸟](previews/families/estrildidae.webp)

### 鸦科：松鸦与鹊 · *Corvidae* — 138种

![鸦科：松鸦与鹊](previews/families/corvidae.webp)

### 拟鹂与酋长鹂 · *Icteridae* — 107种

![拟鹂与酋长鹂](previews/families/icteridae.webp)

### 犀鸟 · *Bucerotidae* — 64种

![犀鸟](previews/families/bucerotidae.webp)

### 椋鸟与八哥 · *Sturnidae* — 120种

![椋鸟与八哥](previews/families/sturnidae.webp)

### 44个目，各一只

![44个目，各一只](previews/orders.webp)

## 里面有什么

| | |
|---|---|
| `stickers/<目>/<科>/<属_种>.webp` | 11064张透明底白边贴纸，长边约1000像素 |
| `data/species.json` | 每种一条记录，最完整的数据：分类、鸟名、编号、分布与亚种、形态与生态、保护等级、贴纸及其来历。字段说明见[data/README.md](data/README.md) |
| `data/species.csv` | 同上，摊平成表格，方便用Excel打开 |
| `data/names.csv` | 43种语言的鸟名（46列：中文、法文、葡萄牙文各有两个版本） |
| `data/languages.json` | 语言代码，以及每种语言对应IOC表里的哪一列 |
| `data/field-guide.zh-Hans.json` | 1596种鸟的中文图鉴文字（一句话印象、辨识要点、雌雄幼鸟、相似种、小知识），CC BY-SA 4.0 |

记录的结构见[英文说明](README.md#whats-inside)里的示例。

## 覆盖情况

- 鸟名：英文覆盖全部物种，法文、简体中文只差个别（简体中文缺23个近年新拆分的种，IOC还没给中文名）；日文、繁体中文、俄文、德文、西班牙文、波兰文、荷兰文、瑞典文等十几种欧洲语言超过90%；塞尔维亚文、匈牙利文、爱沙尼亚文在50%到75%之间；韩文、阿拉伯文、泰文、波斯文等目前只有几百到一千来种，因为IOC名录里只有这么多。
- 繁体中文直接取自IOC，台湾、香港的常用鸟名有时不同，欢迎补充。
- 编号：Wikidata 10939种，GBIF 10649种，eBird 10052种。
- 贴纸：11064种，一种不缺。

## 贴纸怎么来的，质量如何

11064张是AI绘制。每种鸟先找一张参考照片（有453种找不到一张合用的照片，就用几张图拼成参考板，加上文字描述），用GPT-image画成贴纸，再放大、抠图。

每张AI贴纸画完后，由另一位审核员对照参考照逐项核对辨识特征并打分：喙、眼、腿脚、羽色和斑纹。最后一轮里，852张80到82分压线的贴纸又由另一人盲审一遍，其中211张没通过，打回重画。更早几轮的压线贴纸没有做这道盲审。

- **7668张达到我们的质量线**（`"meetsQualityBar": true`）：80分及以上的AI贴纸。
- **3396张没有达到。** 已经重画到次数上限，为了不让任何一种鸟没有图，保留了得分最高的那一版。其中3281张在70到79分，109张低于70分，另有6张初审80分以上但没通过盲审。

这些是插画，不是图鉴图版。当作一张友好的鸟的画像来用；涉及细节辨识，请以图鉴为准。发现画错了，欢迎[提issue](../../issues/new/choose)。鸟友的纠错，是这个项目最需要的贡献。

## 参考照片

每张贴纸都是AI重新绘制的，仓库里不含任何参考照片。每种鸟参照了哪张图（页面、作者、许可）写在`data/species.json`的`sticker.reference`里，每张都能追溯到出处；按参考照许可的分类统计见[data/README.md](data/README.md#reference-photos)。

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

- 分类与多语种鸟名：IOC世界鸟类名录v15.2，Gill、Donsker与Rasmussen编，CC BY 3.0。
- 数据库编号：Wikidata（CC0）。
- 形态与生态数据：AVONET，Tobias等，2022，《Ecology Letters》，CC BY 4.0。
- 参考照片的摄影师：逐种写在`data/species.json`里。参考照片本身不在仓库中。
- 贴纸为观鸟记录App「鸣迹」绘制。

如果某张贴纸参照的是你的照片，而你不希望我们使用，请提issue或发邮件到alchaincyf@gmail.com，我们会在7天内替换或撤下。
