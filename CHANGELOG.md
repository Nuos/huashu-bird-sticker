# Changelog / 更新记录

## 2.3.5 — 2026-11-12

**Feet corrected on 8 stickers that kept failing review.** / **8张反复重画仍不过线的贴纸，单独改对了脚。**

- These 8 had toes drawn wrong, and each time the whole bird was generated again, a new problem appeared elsewhere. This time only the feet were regenerated on the approved image; the rest of the bird is unchanged. Each new version again passed review and the toe count. / 这8张脚趾画错，整只鸟重新生成时又总在别处出新问题。这次在已通过审核的图上只重新生成脚，鸟的其他部分不变；新版同样通过了审核和数脚趾。
- Bustards (*Heterotetrax rueppelii*, *Lophotis gindiana*) and buttonquails (*Turnix hottentottus*, *T. worcesteri*): three forward toes, no hind toe. Wood-quail (*Odontophorus gujanensis*), Whyte's Francolin (*Scleroptila whytei*) and Australian Painted-snipe (*Rostratula australis*): a short raised hind toe. Magnificent Frigatebird (*Fregata magnificens*): four toes. / 鸨（鲁氏鸨、黄冠鸨）和三趾鹑（非洲三趾鹑、吕宋三趾鹑）：三趾朝前、没有后趾；云斑林鹑、怀氏鹧鸪、澳洲彩鹬：后趾短小、抬离地面；华丽军舰鸟：四趾。

## 2.3.4 — 2026-11-12

**The stickers shown for each family and order were reviewed again; 252 stickers generated again.** / **复核了代表各科、目的贴纸，252张重新生成。**

- The 357 stickers that stand for a family or an order on [birdalbum.com](https://birdalbum.com) and in the Mingji app were reviewed again against published field-guide plates, with the toes and claws checked most closely. 213 of them were generated again until a new version passed review. / [birdalbum.com](https://birdalbum.com)和鸣迹App里代表各科、目的357张贴纸，对照公开出版的图鉴图版又审了一遍，脚趾和爪子查得最细。其中213张重新生成到新版过线。
- The other 39 were sent back during the toe count in 2.3.3 and passed review after that release. / 另外39张是2.3.3数脚趾时放回重画、在那一版发布后才过线的。
- The reference-photo counts in [data/README.md](data/README.md) are updated to match. / [data/README.md](data/README.md)里参考照片的分类计数随之更新。

## 2.3.3 — 2026-11-11

**Feet checked toe by toe; 295 stickers generated again.** / **逐只脚数了脚趾，295张贴纸重新生成。**

- A reader found a Downy Woodpecker drawn with five toes on each foot. We then counted the toes on every sticker against each family's foot type: zygodactyl (two toes forward, two back) for woodpeckers, parrots, cuckoos, toucans and their relatives; no hind toe for plovers, bustards and others; a short raised hind toe for sandpipers, gamebirds and others. / 有读者发现绒啄木鸟每只脚画了5趾。我们随后按各科的足型逐张数了脚趾：啄木鸟、鹦鹉、杜鹃、巨嘴鸟等是对趾足（两趾向前、两趾向后）；鸻、鸨等没有后趾；鹬、雉等后趾短小、抬离地面。
- 295 stickers with the wrong number or arrangement of toes, or with both feet tangled together, were generated again until a new version passed review, including the Downy Woodpecker (*Dryobates pubescens*) and the Northern Lapwing (*Vanellus vanellus*). A toe count is now part of every review. / 趾数或趾的朝向不对、两只脚缠在一起的295张，重新生成到新版过线，包括绒啄木鸟（*Dryobates pubescens*）和凤头麦鸡（*Vanellus vanellus*）。此后每次审核都会数脚趾。
- Some stickers still show both feet overlapping side by side, so the toes are hard to count. If you find a foot that is wrong, please [report it](../../issues/new?template=sticker-error.yml). / 仍有一些贴纸两只脚前后叠在一起，脚趾不好数。发现脚画错了，欢迎[报错](../../issues/new?template=sticker-error.yml)。

## 2.3.2 — 2026-11-09

- Sulphur-crested Cockatoo (*Cacatua galerita*) generated again with corrections for the folded wing, following [issue #3](../../issues/3). The feather groups of the folded wing still need work. / 葵花鹦鹉（*Cacatua galerita*）按 [issue #3](../../issues/3) 指出的折叠翼问题重新生成；折叠翼的羽区层次仍需继续改进。

## 2.3.1 — 2026-11-09

**Small fixes after release.** / **发版后的小修正。**

- `data/names.csv`: the Indonesian column is now `id-ID`. It was `id`, the same name as the species ID column, so CSV readers mixed the two up. / `data/names.csv`的印尼语列改名为`id-ID`：原来叫`id`，和物种编号列重名，读表时两列会混在一起。
- README and data/README: more careful wording about AviList (Clements/eBird still publishes its own list) and about the 43 species with an extinction flag (two of them are reintroduced to the wild). / README与data/README：AviList的说明改得更准确（Clements/eBird仍在发布自己的名录）；43种带灭绝标记的种里有两种已重新引入野外，说法相应修正。

## 2.3.0 — 2026-11-09

**Every species has a sticker, and every sticker passed the stricter review.** / **每个种都有了贴纸，每张贴纸都通过了更严的审核。**

- The 38 species that had no sticker (species involved in AviList splits, and species new to the list) now have one: all 11,011 species, 11,102 files with the subspecies. / 此前没有贴纸的38种（涉及AviList拆分的种和新收录的种）补上了：11,011种全部有贴纸，含亚种共11,102个文件。
- The 1,622 stickers left from earlier reviews were checked again to the stricter standard: 542 passed as they were, 1,080 were generated again until a new version passed. Stickers meeting the quality bar: 11,043 → 11,102 (all). / 早期审核留下的1,622张按更严的标准重审：542张原样通过，1,080张重新生成到新版过线。达到质量线的贴纸：11,043 → 11,102（全部）。
- Since 5 November we no longer give the image model reference photos with all rights reserved, under Macaulay Library terms, or without a recorded license. 68 stickers generated after that date had been given such photos by mistake; they were generated again with Creative Commons or public-domain photos. The White Tern (*Gygis alba*) reference was also changed from CC BY-NC to CC0 and CC BY photos. / 11月5日起，不再把保留所有权利、Macaulay Library条款或没记录授权的照片交给生图模型。此后生成的贴纸里有68张误用了这类照片，已换CC授权或公有领域照片重新生成。白燕鸥（*Gygis alba*）的参考照也从CC BY-NC换成了CC0和CC BY照片。
- `data/species.json`: stickers made without a reference photo now always have `"reference": null` (369 had left the field out); review scores of 455 stickers updated to the latest review; e-mail addresses removed from three photographer names. / `data/species.json`：没参考照的贴纸一律写`"reference": null`（此前369条省略了这个字段）；455张贴纸的审核分数更新为最近一次审核；3处摄影师署名里的邮箱地址已去掉。
- New: [how the stickers are made](docs/how-the-stickers-are-made.md) (the loop, an example prompt, what we learned), a [family review](../../issues/new?template=family-review.yml) issue template and [CONTRIBUTORS.md](CONTRIBUTORS.md). Takedown requests now go through the [takedown form](../../issues/new?template=takedown.yml) only. / 新增[贴纸是怎么生成的](docs/how-the-stickers-are-made.zh-Hans.md)（流程、提示词案例、经验）、「审一个科」issue模板和[CONTRIBUTORS.md](CONTRIBUTORS.md)。撤图申请统一走[撤图表单](../../issues/new?template=takedown.yml)。
- `data/stickers.json` now covers all 11,011 species. / `data/stickers.json`覆盖全部11,011种。

## 2026-11-07 — one-line use / 一行代码用上

**Every sticker now has a CDN link and a small name index.** / **每张贴纸都有CDN直链和一个小索引。**

- New `data/stickers.json` (2.7 MB): scientific, English and Chinese name, sticker path and the species page on birdalbum.com for all 10,973 stickers. / 新增`data/stickers.json`（2.7 MB），含全部10,973张贴纸的学名、英文名、中文名、路径和birdalbum.com鸟种页。
- README: a short "Use a sticker in one line" section with jsDelivr links and a suggested credit line, in all 11 languages. / README十一种语言都加了「一行代码用上」，含jsDelivr直链和推荐署名。

## 2.2.15 — 2026-11-07

**320 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了320张贴纸。**

- Stickers meeting the quality bar: 10,870 → 11,043 (of 11,064 files). / 达到质量线的贴纸：10,870 → 11,043（共11,064个文件）。
- Regenerated under the stricter review so far: 10,114. / 按严审标准累计重新生成10,114张。

## 2.2.14 — 2026-11-07

**1 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了1张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 9,794. / 按严审标准累计重新生成9,794张。

## 2.2.13 — 2026-11-07

**377 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了377张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 9,793. / 按严审标准累计重新生成9,793张。

## 2.2.12 — 2026-11-07

**463 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了463张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 9,416. / 按严审标准累计重新生成9,416张。

## 2.2.11 — 2026-11-06

**470 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了470张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 8,953. / 按严审标准累计重新生成8,953张。

## 2.2.10 — 2026-11-06

**536 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了536张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 8,483. / 按严审标准累计重新生成8,483张。

## 2.2.9 — 2026-11-06

**163 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了163张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 7,947. / 按严审标准累计重新生成7,947张。

## 2.2.8 — 2026-11-06

**448 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了448张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 7,784. / 按严审标准累计重新生成7,784张。

## 2.2.7 — 2026-11-06

**532 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了532张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 7,336. / 按严审标准累计重新生成7,336张。

## 2.2.6 — 2026-11-06

**357 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了357张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 6,804. / 按严审标准累计重新生成6,804张。

## 2.2.5 — 2026-11-06

**298 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了298张贴纸。**

- Stickers meeting the quality bar: 10,870 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,870 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 6,447. / 按严审标准累计重新生成6,447张。

## 2.2.4 — 2026-11-06

**1,975 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了1,975张贴纸。**

- Stickers meeting the quality bar: 10,677 → 10,870 (of 11,064 files). / 达到质量线的贴纸：10,677 → 10,870（共11,064个文件）。
- Regenerated under the stricter review so far: 6,149. / 按严审标准累计重新生成6,149张。

## 2.2.3 — 2026-11-05

**Every sticker file now says it is AI-generated.** / **每张贴纸文件里都写明了「AI生成」。**

- All 11,064 WebP files carry XMP metadata: IPTC Digital Source Type `trainedAlgorithmicMedia` (the standard "AI-generated" label that Google Images and other tools read), the AI system used, a title with the species name, the CC BY 4.0 license and credit line, and where to report errors. Pixels are unchanged. / 全部11,064个WebP文件都写入了XMP元数据：IPTC数字来源类型 `trainedAlgorithmicMedia`（Google图片等工具识别「AI生成」用的标准字段）、所用AI系统、带鸟种名的标题、CC BY 4.0授权与署名方式、报错地址。图像像素没有改动。
- Check with `exiftool -XMP:all <file>.webp`. / 可以用 `exiftool -XMP:all <文件>.webp` 查看。

## 2.2.2 — 2026-11-05

**179 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了179张贴纸。**

- Stickers meeting the quality bar: 10,498 → 10,677 (of 11,064 files). / 达到质量线的贴纸：10,498 → 10,677（共11,064个文件）。
- Regenerated under the stricter review so far: 4,299. / 按严审标准累计重新生成4,299张。

## 2.2.1 — 2026-11-05

**559 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了559张贴纸。**

- Stickers meeting the quality bar: 9,939 → 10,498 (of 11,064 files). / 达到质量线的贴纸：9,939 → 10,498（共11,064个文件）。
- Regenerated under the stricter review so far: 4,120. / 按严审标准累计重新生成4,120张。

## 2.2.0 — 2026-11-05

**The stickers are now licensed under CC BY 4.0.** / **贴纸改为CC BY 4.0授权。**

You can now use the stickers for any purpose, including in birding, bird-ID and field-guide apps, sites and services, as long as you give credit. This applies to every sticker file in the repository, including those first published under PolyForm Shield 1.0.0. The data stays MIT.

现在贴纸可以用于任何用途，包括观鸟、识鸟和鸟类图鉴类的App、网站和服务，只要署名。这适用于仓库里的所有贴纸文件，包括此前以PolyForm Shield 1.0.0发布的。数据仍按MIT授权。

- `sticker.license` is now `CC-BY-4.0` for all 11,064 stickers. / 11,064张贴纸的`sticker.license`都改为`CC-BY-4.0`。
- The license text is in `LICENSES/CC-BY-4.0.txt`. / 许可证原文见`LICENSES/CC-BY-4.0.txt`。

## 2.1.1 — 2026-11-05

**523 more stickers regenerated under the stricter review.** / **又按严审标准重新生成了523张贴纸。**

- Stickers meeting the quality bar: 9,438 → 9,939 (of 11,064 files). / 达到质量线的贴纸：9,438 → 9,939（共11,064个文件）。
- Regenerated under the stricter review so far: 3,561. / 按严审标准累计重新生成3,561张。

## 2.1.0 — 2026-11-05

**3,038 stickers regenerated under a stricter review.** / **按更严的标准重新生成了3,038张贴纸。**

We re-checked the stickers as plates for a field guide and generated new versions of the ones that fell short. A regenerated sticker passes only if identification, plumage, bill and eye, legs and feet, and proportions each score at least 3 out of 4, identification scores 4, and the reviewer would accept it as a field-guide plate. Feet now stand flat on an invisible ground line instead of gripping the air. Thanks to everyone who pointed out errors in [#1](../../issues/1) and [#3](../../issues/3).

按图鉴图版的标准重新审核，不达标的重新生成。重新生成的贴纸要辨识、羽色与斑纹、喙与眼、腿脚、比例五项都至少3分（满分4分）、辨识4分，并且审核员认可能当图鉴图版，才算过线。脚改为平踩在看不见的地面线上，不再悬空抓握。感谢在[#1](../../issues/1)、[#3](../../issues/3)指出错误的鸟友。

- Stickers meeting the quality bar: 7,670 → 9,438 (of 11,064 files). / 达到质量线的贴纸：7,670 → 9,438（共11,064个文件）。
- `sticker.reviewScore`, `meetsQualityBar` and `reference` are updated for the regenerated stickers. 152 were generated from a written description without a reference photo; their `reference` is `null`. / 重新生成的贴纸已更新`reviewScore`、`meetsQualityBar`、`reference`；其中152张不带参考照、只按文字说明重新生成，`reference`为`null`。
- Three stickers were generated again from new reference photos at their photographers' request: *Actinodura ramsayi*, *Carpodacus verreauxii*, *Phylloscopus bonelli*. / 应参考照作者要求，三张贴纸换了参考照重新生成。
- The preview sheets in `previews/` have not been regenerated yet. / `previews/`里的预览图还没重新生成。

## 2.0.0 — 2026-11-03

**Taxonomy moved from IOC World Bird List v15.2 to AviList v2026.** / **分类从IOC 15.2改为AviList v2026。**

Why: IOC 15.2 was the last IOC list. In 2025 the IOC, Clements/eBird and BirdLife teams merged their work into AviList, the consensus global checklist, which updates every October. Reported in [#2](../../issues/2).

原因：IOC 15.2是IOC的最后一版。2025年IOC、Clements/eBird与BirdLife合并为全球统一名录AviList，每年10月更新。由[#2](../../issues/2)提出。

Breaking changes / 不兼容的变化:

- 82 species have a new scientific name, so a new `id` and sticker path (e.g. `Emberiza_elegans` → `Schoeniclus_elegans`). Old IDs are in each record's `previous` and in `data/crosswalk-ioc15.2-avilist2026.csv`.
  82种学名变了，`id`和贴纸路径随之改变；旧id见各记录的`previous`和对照表。
- 91 former species are now subspecies. Their stickers moved to `<Genus_species>.<subspecies>.webp` and appear under the parent species' `forms`.
  91个原独立种现为亚种，贴纸改名为`<属_种>.<亚种>.webp`，挂在所属种的`forms`下。
- 38 species are new (30 splits, 7 newly recognised, and *Todiramphus gambieri*, which version 0.1 left out by mistake). They have `"sticker": null` until drawn.
  新增38种（30个拆分、7个新确认的种，以及0.1版漏收的土岛翡翠），贴纸画好前为`null`。
- Five stickers moved from a parent species to the species split from it, because their reference photo was taken in the new species' range. The parent is waiting for a new drawing. See `data/README.md`.
  5张贴纸按参考照拍摄地改挂到拆出的新种，母种待重新生成，见`data/README.md`。
- Total: 11,011 species (was 11,064).
  共11,011种（原11,064种）。

Data fixes / 数据修正:

- eBird species codes now come from AviList and match eBird v2026. Before, 306 of the codes taken from Wikidata were no longer valid eBird species codes, and 921 species had none.
  eBird代码改取AviList，与eBird v2026一致。原先从Wikidata转抄的代码有306个已失效，921种缺代码。
- Added Avibase IDs, AviList range statements and subspecies, `extinctionStatus`, `taxonConcept`, `previous`, `dataNotes`, `otherEnglishNames`.
  新增Avibase编号、AviList分布描述与亚种、灭绝状态、分类概念等字段。
- IUCN categories now come from AviList (BirdLife v10) instead of Wikidata.
  IUCN等级改取AviList（BirdLife v10）。
- For species whose boundaries changed, data that described the old set of birds (non-English names other than Simplified Chinese, Wikidata/GBIF/iNaturalist IDs, AVONET traits, body size) was not carried over.
  分类范围变了的种，不再沿用描述旧范围的数据。
- Chinese range summaries use 藏南地区 instead of 阿鲁纳恰尔邦; stray private-use characters removed from a few IOC names.
  中文分布摘要改用「藏南地区」；清理了IOC原表个别鸟名里的乱码字符。

## 0.1.0 — 2026-10-31

First release: 11,064 species following IOC World Bird List v15.2.
首次发布：按IOC 15.2整理的11,064种。
