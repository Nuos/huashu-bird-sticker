# Changelog / 更新记录

## 2.2.3 — 2026-11-05

**Every sticker file now says it is AI-generated.** / **每张贴纸文件里都写明了「AI生成」。**

- All 11,064 WebP files carry XMP metadata: IPTC Digital Source Type `trainedAlgorithmicMedia` (the standard "AI-generated" label that Google Images and other tools read), the AI system used, a title with the species name, the CC BY 4.0 license and credit line, and where to report errors. Pixels are unchanged. / 全部11,064个WebP文件都写入了XMP元数据：IPTC数字来源类型 `trainedAlgorithmicMedia`（Google图片等工具识别「AI生成」用的标准字段）、所用AI系统、带鸟种名的标题、CC BY 4.0授权与署名方式、报错地址。图像像素没有改动。
- Check with `exiftool -XMP:all <file>.webp`. / 可以用 `exiftool -XMP:all <文件>.webp` 查看。

## 2.2.2 — 2026-11-05

**179 more stickers redrawn under the stricter review.** / **又按严审标准重画了179张贴纸。**

- Stickers meeting the quality bar: 10,498 → 10,677 (of 11,064 files). / 达到质量线的贴纸：10,498 → 10,677（共11,064个文件）。
- Redrawn under the stricter review so far: 4,299. / 按严审标准累计重画4,299张。

## 2.2.1 — 2026-11-05

**559 more stickers redrawn under the stricter review.** / **又按严审标准重画了559张贴纸。**

- Stickers meeting the quality bar: 9,939 → 10,498 (of 11,064 files). / 达到质量线的贴纸：9,939 → 10,498（共11,064个文件）。
- Redrawn under the stricter review so far: 4,120. / 按严审标准累计重画4,120张。

## 2.2.0 — 2026-11-05

**The stickers are now licensed under CC BY 4.0.** / **贴纸改为CC BY 4.0授权。**

You can now use the stickers for any purpose, including in birding, bird-ID and field-guide apps, sites and services, as long as you give credit. This applies to every sticker file in the repository, including those first published under PolyForm Shield 1.0.0. The data stays MIT.

现在贴纸可以用于任何用途，包括观鸟、识鸟和鸟类图鉴类的App、网站和服务，只要署名。这适用于仓库里的所有贴纸文件，包括此前以PolyForm Shield 1.0.0发布的。数据仍按MIT授权。

- `sticker.license` is now `CC-BY-4.0` for all 11,064 stickers. / 11,064张贴纸的`sticker.license`都改为`CC-BY-4.0`。
- The license text is in `LICENSES/CC-BY-4.0.txt`. / 许可证原文见`LICENSES/CC-BY-4.0.txt`。

## 2.1.1 — 2026-11-05

**523 more stickers redrawn under the stricter review.** / **又按严审标准重画了523张贴纸。**

- Stickers meeting the quality bar: 9,438 → 9,939 (of 11,064 files). / 达到质量线的贴纸：9,438 → 9,939（共11,064个文件）。
- Redrawn under the stricter review so far: 3,561. / 按严审标准累计重画3,561张。

## 2.1.0 — 2026-11-05

**3,038 stickers redrawn under a stricter review.** / **按更严的标准重画了3,038张贴纸。**

We re-checked the stickers as plates for a field guide and redrew the ones that fell short. A redrawn sticker passes only if identification, plumage, bill and eye, legs and feet, and proportions each score at least 3 out of 4, identification scores 4, and the reviewer would accept it as a field-guide plate. Feet now stand flat on an invisible ground line instead of gripping the air. Thanks to everyone who pointed out errors in [#1](../../issues/1) and [#3](../../issues/3).

按图鉴图版的标准重新审核，不达标的重画。重画的贴纸要辨识、羽色与斑纹、喙与眼、腿脚、比例五项都至少3分（满分4分）、辨识4分，并且审核员认可能当图鉴图版，才算过线。脚改为平踩在看不见的地面线上，不再悬空抓握。感谢在[#1](../../issues/1)、[#3](../../issues/3)指出错误的鸟友。

- Stickers meeting the quality bar: 7,670 → 9,438 (of 11,064 files). / 达到质量线的贴纸：7,670 → 9,438（共11,064个文件）。
- `sticker.reviewScore`, `meetsQualityBar` and `reference` are updated for the redrawn stickers. 152 were redrawn from a written description without a reference photo; their `reference` is `null`. / 重画的贴纸已更新`reviewScore`、`meetsQualityBar`、`reference`；其中152张不带参考照、只按文字说明重画，`reference`为`null`。
- Three stickers were redrawn from new reference photos at their photographers' request: *Actinodura ramsayi*, *Carpodacus verreauxii*, *Phylloscopus bonelli*. / 应参考照作者要求，三张贴纸换了参考照重画。
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
  5张贴纸按参考照拍摄地改挂到拆出的新种，母种待重画，见`data/README.md`。
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
