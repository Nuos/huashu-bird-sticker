# 現生の鳥11,064種すべてのステッカー

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · **日本語** · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

鳥11,064種、1種につき1枚のステッカー。44目250科にわたります。IOC World Bird List v15.2の現生種すべてにあたります（絶滅した163種は含みません）。各種には、分類、最大43言語の名前、各データベースのID、そしてステッカーごとの由来といった構造化データが付いています。

![15の目から選んだ40枚のステッカー](previews/hero.webp)

**ライセンスを一言で:** ステッカーは商用を含むどんな用途にも使え、加工や再配布もできます。例外は、バードウォッチング、鳥の識別、野鳥図鑑のアプリ・サイト・サービスだけです。huashu-bird-stickerの名前とこのリポジトリへのリンクを添えれば問題ありません。法的な文面は[PolyForm Shield 1.0.0](LICENSE.md)です。データはMITで、第三者に由来する部分は[NOTICE](NOTICE.md)に記載しています。

## ギャラリー

色彩が豊かで特徴のある18のグループを、それぞれ24枚ずつ、互いに似て見えないように選びました。ここに載せたステッカーはすべて品質基準を満たしています。

### ハチドリ · *Trochilidae* — 365 種

![ハチドリ](previews/families/trochilidae.webp)

### オウム・インコ · *Psittaciformes* — 392 種

![オウム・インコ](previews/families/parrots.webp)

### カワセミ · *Alcedinidae* — 116 種

![カワセミ](previews/families/alcedinidae.webp)

### ハチクイ・ブッポウソウ・ハチクイモドキ · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68 種

![ハチクイ・ブッポウソウ・ハチクイモドキ](previews/families/coraciiformes.webp)

### オオハシ・ゴシキドリ · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134 種

![オオハシ・ゴシキドリ](previews/families/toucans.webp)

### フウチョウ・ニワシドリ · *Paradisaeidae* · *Ptilonorhynchidae* — 69 種

![フウチョウ・ニワシドリ](previews/families/paradisaeidae.webp)

### ヤイロチョウ · *Pittidae* — 46 種

![ヤイロチョウ](previews/families/pittidae.webp)

### フウキンチョウ · *Thraupidae* — 393 種

![フウキンチョウ](previews/families/thraupidae.webp)

### タイヨウチョウ・ハナドリ · *Nectariniidae* · *Dicaeidae* — 208 種

![タイヨウチョウ・ハナドリ](previews/families/nectariniidae.webp)

### カザリドリ・マイコドリ · *Cotingidae* · *Pipridae* — 121 種

![カザリドリ・マイコドリ](previews/families/cotingas.webp)

### キジ・ウズラ · *Phasianidae* — 185 種

![キジ・ウズラ](previews/families/phasianidae.webp)

### カモ・ガン・ハクチョウ · *Anatidae* — 166 種

![カモ・ガン・ハクチョウ](previews/families/anatidae.webp)

### ハト · *Columbidae* — 339 種

![ハト](previews/families/columbidae.webp)

### カエデチョウ · *Estrildidae* — 140 種

![カエデチョウ](previews/families/estrildidae.webp)

### カケス・カササギ · *Corvidae* — 138 種

![カケス・カササギ](previews/families/corvidae.webp)

### 新世界のムクドリモドキ・オオツリスドリ · *Icteridae* — 107 種

![新世界のムクドリモドキ・オオツリスドリ](previews/families/icteridae.webp)

### サイチョウ · *Bucerotidae* — 64 種

![サイチョウ](previews/families/bucerotidae.webp)

### ムクドリ・キュウカンチョウ · *Sturnidae* — 120 種

![ムクドリ・キュウカンチョウ](previews/families/sturnidae.webp)

### 44の目から1枚ずつ

![44の目から1枚ずつ](previews/orders.webp)

## 収録内容

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | 白い縁取り付きの透過ステッカー11,064枚。長辺は約1,000 px |
| `data/species.json` | 1種につき1レコード。完全なデータセットで、分類、名前、ID、分布と亜種、体の計測値と生態、保全状況、ステッカーとその出典を含みます。フィールドの説明は[data/README.md](data/README.md) |
| `data/species.csv` | 同じ内容を表計算ソフト向けに平坦化したもの |
| `data/names.csv` | 43言語の名前（46列：中国語、フランス語、ポルトガル語はそれぞれ2種類ある） |
| `data/languages.json` | 言語コードと、それぞれがIOCの表のどの列に由来するか |
| `data/field-guide.zh-Hans.json` | 1,596種の簡体字中国語によるフィールドガイドの解説（外見、識別点、雌雄・年齢、似た種）、CC BY-SA 4.0 |

レコードはこのような形です（名前は一部省略）。

```json
{
  "id": "Accipiter_nisus",
  "scientificName": "Accipiter nisus",
  "authority": "(Linnaeus, 1758)",
  "taxonomy": {"system": "IOC 15.2", "seq": 2872, "order": "Accipitriformes", "family": "Accipitridae", "genus": "Accipiter"},
  "names": {"en": "Eurasian Sparrowhawk", "zh-Hans": "雀鹰", "ja": "ハイタカ", "es": "Gavilán común", "fr": "Épervier d'Europe", "…": "…"},
  "ids": {"wikidata": "Q25380", "ebird": "eurspa1", "gbif": "2480637", "inaturalist": 5106},
  "range": {"breedingRegion": "PAL", "breeding": "widespread", "nonbreeding": "OR, ne AF"},
  "subspecies": [{"name": "nisus", "range": "Europe to sw Siberia and c Asia"}, "…"],
  "traits": {"massG": 220.8, "wingMm": 207.4, "tailMm": 155.5, "habitat": "Forest", "migration": "partially migratory", "trophicNiche": "Vertivore", "…": "…"},
  "conservation": {"iucn": "LC", "cites": "II"},
  "sticker": {
    "file": "stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp",
    "kind": "ai-illustration",
    "reviewScore": 91,
    "meetsQualityBar": true,
    "license": "PolyForm-Shield-1.0.0",
    "reference": {"type": "photo", "page": "https://commons.wikimedia.org/wiki/File:…", "author": "Dion Art", "license": "CC BY-SA 4.0"}
  }
}
```

## 収録範囲

- 名前：英語は全種をカバーし、フランス語と簡体字中国語もごくわずかな種を除いてカバーしています（簡体字中国語は、近年分割された23種の名前がまだありません）。日本語、繁体字中国語、ロシア語、ドイツ語、スペイン語、ポーランド語、オランダ語、スウェーデン語など、ほかにも十数のヨーロッパ言語は90%以上です。セルビア語、ハンガリー語、エストニア語は50〜75%です。韓国語、アラビア語、タイ語、ペルシア語などは、IOCのリストにある分だけなので、今のところ数百種から1,000種ほどにとどまります。詳しくは`data/names.csv`を見てください。
- 日本語名はIOCのリストから直接取っており、11,064種のうち10,566種に付いています。
- ID：Wikidata 10,939、GBIF 10,649、eBird 10,052。
- ステッカー：11,064種中11,064種。

## ステッカーの作り方と品質

11,064枚はAIイラストです。種ごとに参考写真を探し（単独で十分な写真がない453種は、複数の画像を並べた参考ボードと文章での説明を用意）、GPT-imageでステッカーを描き、拡大して切り抜きました。

AIステッカーはすべて、別の審査者が参考資料と照らし合わせ、野外での識別点を採点しました。嘴、目、脚と足、羽色と模様です。最後のラウンドでは、境界線上（80〜82点）の852枚がさらに盲検でもう一度審査され、そのうち211枚が不合格となり描き直しました。それ以前のラウンドの境界線上のステッカーには、この二次審査は行っていません。

- **7,668枚が品質基準を満たしています**（`"meetsQualityBar": true`）。80点以上のAIステッカーです。
- **3,396枚は満たしていません。** 描き直しの上限まで繰り返したうえで、最高点の版を残しました。絵のない種を作らないためです。内訳は、70〜79点が3,281枚、70点未満が109枚、80点以上だったが盲検の二次審査で不合格になったものが6枚です。

これらはイラストであり、フィールドガイドの図版ではありません。鳥の雰囲気を伝える絵として扱い、細部に頼る場合は図鑑で確認してください。間違いを見つけたら[issueを立てて](../../issues/new/choose)ください。バードウォッチャーからの訂正は、このプロジェクトにとって何よりありがたい貢献です。

## 参考写真について

ステッカーはすべてAIで新しく描いたもので、このリポジトリに参考写真は含まれていません。各種を描くときに参照した画像（ページ、作者、ライセンス）は`data/species.json`の`sticker.reference`に記録してあり、どのステッカーも出典までたどれます。参考写真のライセンス別の内訳は[data/README.md](data/README.md#reference-photos)にあります。

## 使い方

ファイルはそのまま読み込めます。

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

リポジトリ全体は約700 MBあります。データと一部のステッカーだけを取得するには次のようにします。

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## クレジット

- 分類と多言語の名前：IOC World Bird List v15.2、Gill、Donsker & Rasmussen（編）、CC BY 3.0。
- データベース間のID：Wikidata（CC0）。
- 体の計測値と生態：AVONET、Tobias他、2022年、*Ecology Letters*、CC BY 4.0。
- 参考写真の撮影者：種ごとに`data/species.json`に記載しています。参考写真はこのリポジトリには含まれていません。
- ステッカーは、iOS向けのバードウォッチング記録アプリ「鸣迹（Mingji）」のために描いたものです。

あなたの写真をもとにしたステッカーがあり、そうしてほしくない場合は、issueを立てるか alchaincyf@gmail.com までメールをください。7日以内に差し替えるか削除します。
