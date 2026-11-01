# Стикеры для всех 11 064 ныне живущих видов птиц

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · **Русский** · [العربية](README.ar.md)

11 064 вида птиц, по одному стикеру на каждый, в 44 отрядах и 250 семействах. Это все ныне живущие виды из IOC World Bird List v15.2 (163 вымерших вида не включены). К каждому виду прилагаются структурированные данные: систематика, названия на 43 языках (максимум), идентификаторы в других базах данных и происхождение каждого стикера.

![40 стикеров из 15 отрядов птиц](previews/hero.webp)

Стикеры можно бесплатно использовать почти для чего угодно, в том числе в коммерческих целях, на условиях [PolyForm Shield 1.0.0](LICENSE.md). Запрещено только одно: использовать их в продукте, конкурирующем с нашим приложением о птицах (другим приложением или сайтом для наблюдения за птицами, определения птиц или полевого определителя). Данные распространяются по лицензии MIT. О материалах, происходящих от третьих лиц, читайте в [NOTICE](NOTICE.md), а о справочных фотографиях — в разделе [Об эталонных фотографиях](#об-эталонных-фотографиях) ниже.

## Галерея

Восемнадцать самых ярких и характерных групп, по 24 стикера из каждой, подобранных так, чтобы никакие два не были похожи. Все показанные здесь стикеры соответствуют порогу качества.

### Колибри · *Trochilidae* — 365 видов

![Колибри](previews/families/trochilidae.webp)

### Попугаи и какаду · *Psittaciformes* — 392 вида

![Попугаи и какаду](previews/families/parrots.webp)

### Зимородки · *Alcedinidae* — 116 видов

![Зимородки](previews/families/alcedinidae.webp)

### Щурки, сизоворонки и момоты · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68 видов

![Щурки, сизоворонки и момоты](previews/families/coraciiformes.webp)

### Туканы и бородатки · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134 вида

![Туканы и бородатки](previews/families/toucans.webp)

### Райские птицы и шалашники · *Paradisaeidae* · *Ptilonorhynchidae* — 69 видов

![Райские птицы и шалашники](previews/families/paradisaeidae.webp)

### Питты · *Pittidae* — 46 видов

![Питты](previews/families/pittidae.webp)

### Танагры · *Thraupidae* — 393 вида

![Танагры](previews/families/thraupidae.webp)

### Нектарницы и цветоеды · *Nectariniidae* · *Dicaeidae* — 208 видов

![Нектарницы и цветоеды](previews/families/nectariniidae.webp)

### Котинги и манакины · *Cotingidae* · *Pipridae* — 121 вид

![Котинги и манакины](previews/families/cotingas.webp)

### Фазаны и куропатки · *Phasianidae* — 185 видов

![Фазаны и куропатки](previews/families/phasianidae.webp)

### Утки, гуси и лебеди · *Anatidae* — 166 видов

![Утки, гуси и лебеди](previews/families/anatidae.webp)

### Голуби · *Columbidae* — 339 видов

![Голуби](previews/families/columbidae.webp)

### Вьюрковые ткачики · *Estrildidae* — 140 видов

![Вьюрковые ткачики](previews/families/estrildidae.webp)

### Сойки и сороки · *Corvidae* — 138 видов

![Сойки и сороки](previews/families/corvidae.webp)

### Трупиалы Нового Света · *Icteridae* — 107 видов

![Трупиалы Нового Света](previews/families/icteridae.webp)

### Птицы-носороги · *Bucerotidae* — 64 вида

![Птицы-носороги](previews/families/bucerotidae.webp)

### Скворцы и майны · *Sturnidae* — 120 видов

![Скворцы и майны](previews/families/sturnidae.webp)

### По одному из каждого из 44 отрядов

![По одному из каждого из 44 отрядов](previews/orders.webp)

## Что внутри

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | 11 064 прозрачных стикера с белым контуром, около 1000 px по длинной стороне |
| `data/species.json` | Одна запись на вид, полный набор данных: систематика, названия, идентификаторы, ареал и подвиды, промеры тела и экология, охранный статус, стикер и его источник. Описание полей: [data/README.md](data/README.md) |
| `data/species.csv` | То же самое, в плоском виде для электронных таблиц |
| `data/names.csv` | Названия на 43 языках (46 столбцов: у китайского, французского и португальского по два варианта) |
| `data/languages.json` | Коды языков и столбец таблицы IOC, из которого взят каждый из них |
| `data/field-guide.zh-Hans.json` | Заметки полевого определителя на упрощённом китайском (внешность, полевые признаки, пол и возраст, похожие виды) для 1596 видов, CC BY-SA 4.0 |

Запись выглядит так (названия сокращены):

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

## Охват

- Названия: английский охватывает все виды, французский и китайский (упрощённый) — все, кроме нескольких (в упрощённом китайском пока нет названий для 23 недавно выделенных видов); японский, китайский (традиционный), русский, немецкий, испанский, польский, нидерландский, шведский и ещё около дюжины европейских языков — более 90%. Сербский, венгерский и эстонский — от 50% до 75%. Корейский, арабский, тайский, персидский и некоторые другие пока охватывают лишь от нескольких сотен до примерно тысячи видов, потому что больше в списке IOC нет. См. `data/names.csv`.
- Русские названия есть у 10 614 из 11 064 видов, они взяты прямо из IOC.
- Идентификаторы: Wikidata 10 939, GBIF 10 649, eBird 10 052.
- Стикеры: 11 064 из 11 064.

## Как делались стикеры и насколько они хороши

11 064 стикеров — это иллюстрации, созданные ИИ. Для каждого вида мы подбирали эталонную фотографию (а для 453 видов, для которых не нашлось достаточно хорошего одиночного снимка, — подборку из нескольких изображений и текстовое описание), рисовали стикер с помощью GPT-image, увеличивали и вырезали по контуру.

Затем каждый стикер ИИ отдельный рецензент оценивал по эталону с точки зрения полевых признаков: клюв, глаз, ноги и лапы, рисунок и цвет оперения. В последнем раунде ещё 852 пограничных стикера (80–82) прошли вторую, слепую проверку, и 211 из них её не прошли и были перерисованы. Пограничные стикеры из прежних раундов этой второй проверки не проходили.

- **7668 соответствуют нашему порогу качества** (`"meetsQualityBar": true`): стикеры ИИ с оценкой 80 и выше.
- **3396 не соответствуют.** Их перерисовывали до установленного предела, и мы оставили версию с наивысшей оценкой, чтобы ни один вид не остался без картинки. У 3281 оценка 70–79, у 109 — ниже 70, а 6 получили 80 и выше, но не прошли слепую повторную проверку.

Это иллюстрации, а не таблицы из полевого определителя. Относитесь к ним как к дружелюбному изображению птицы, а прежде чем полагаться на тонкую деталь, сверьтесь с определителем. Если вы заметили ошибку, [создайте issue](../../issues/new/choose): поправки от орнитологов-любителей — самый ценный вклад в этот проект.

## Об эталонных фотографиях

Эталон каждого стикера указан в `sticker.reference` вместе со страницей, автором и лицензией. Они распределяются так (стикеры ИИ, по видам):

| Эталон | Видов |
|---|---|
| Фото под открытой лицензией (CC0, общественное достояние, CC BY, CC BY-SA) | 2020 |
| Подборка изображений под открытыми лицензиями или только текстовое описание | 46 |
| Фото под некоммерческой лицензией или лицензией без производных произведений (CC BY-NC, -ND, …) | 5071 |
| Фото с сохранением всех прав или на условиях Macaulay Library | 1500 |
| Фото, лицензию которого мы не записали | 2017 |
| Подборка из изображений на разных условиях | 410 |

Стикеры — это новые рисунки, а не копии, и эталонные фотографии здесь не распространяются. Связан ли рисунок, сделанный по фотографии, лицензией этой фотографии, юридически не решено. Если это важно для вашей задачи, отфильтруйте данные по `sticker.reference.license`.

## Как пользоваться

Файлы можно загружать напрямую:

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

Репозиторий занимает около 700 МБ. Чтобы получить только данные и несколько стикеров:

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## Источники

- Систематика и многоязычные названия: IOC World Bird List v15.2, Gill, Donsker & Rasmussen (ред.), CC BY 3.0.
- Идентификаторы в других базах данных: Wikidata (CC0).
- Промеры тела и экология: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Авторы эталонных фотографий: указаны по видам в `data/species.json`. Сами эталонные фотографии в этот репозиторий не входят.
- Стикеры нарисованы для 鸣迹 (Mingji) — блокнота наблюдателя птиц для iOS.

Если какой-то стикер сделан по вашему фото и вы этого не хотите, создайте issue или напишите на alchaincyf@gmail.com — мы заменим или удалим его в течение 7 дней.
