# Стикеры для ныне живущих видов птиц мира

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · **Русский** · [العربية](README.ar.md)

<a href="https://birdalbum.com/ru/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker"><img src="previews/birdalbum.webp" alt="Bird Album: все птицы мира, по одному стикеру на каждую. birdalbum.com" width="100%"></a>

**Всю библиотеку в деле можно увидеть на [birdalbum.com](https://birdalbum.com/ru/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker).** Bird Album — бесплатный определитель птиц на основе этих стикеров: ищите любой вид по названию на 15 языках, смотрите, где он обитает и в какие месяцы его можно встретить, и открывайте карту из 8 171 места наблюдения за птицами, где для каждого показано, кого там видят в этом месяце.

11 011 видов птиц в 45 отрядах и 249 семействах по [AviList v2026](https://www.avilist.org/) — единому мировому списку, который в 2025 году заменил списки IOC и Clements. Включены все ныне живущие виды, а также 43 вида, которые AviList помечает как вымершие, вымершие в дикой природе или возможно вымершие, но для которых стикер уже был (см. `extinctionStatus`). Стикер есть у 10 973 видов; остальные 38 были выделены недавно, и их ещё рисуют. К каждому виду прилагаются структурированные данные: систематика, названия на 43 языках (максимум), идентификаторы в других базах данных и происхождение каждого стикера.

> **В версии 2.0 систематика перешла с IOC 15.2 на AviList v2026.** У 82 видов изменилось научное название (а вместе с ним `id` и путь к стикеру), 91 бывший вид стал подвидом другого вида, и 30 новых видов были выделены. Все изменения перечислены в [`data/crosswalk-ioc15.2-avilist2026.csv`](data/crosswalk-ioc15.2-avilist2026.csv), а каждая запись хранит прежний идентификатор IOC в поле `previous`. См. [CHANGELOG](CHANGELOG.md).

![40 стикеров из 15 отрядов птиц](previews/hero.webp)

**Лицензия кратко:** стикеры можно использовать для чего угодно, в том числе в коммерческих целях, а также изменять и распространять. Единственное исключение — приложение, сайт или сервис для наблюдения за птицами, определения птиц или полевого определителя птиц. Укажите huashu-bird-sticker со ссылкой на этот репозиторий, и этого достаточно. Юридический текст — [PolyForm Shield 1.0.0](LICENSE.md). Данные распространяются по лицензии MIT, а части от третьих лиц перечислены в [NOTICE](NOTICE.md).

## Галерея

Восемнадцать самых ярких и характерных групп, по 24 стикера из каждой, подобранных так, чтобы никакие два не были похожи. Все показанные здесь стикеры соответствуют порогу качества.

### Колибри · *Trochilidae* — 361 вид

![Колибри](previews/families/trochilidae.webp)

### Попугаи и какаду · *Psittaciformes* — 391 вид

![Попугаи и какаду](previews/families/parrots.webp)

### Зимородки · *Alcedinidae* — 123 вида

![Зимородки](previews/families/alcedinidae.webp)

### Щурки, сизоворонки и момоты · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 69 видов

![Щурки, сизоворонки и момоты](previews/families/coraciiformes.webp)

### Туканы и бородатки · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 132 вида

![Туканы и бородатки](previews/families/toucans.webp)

### Райские птицы и шалашники · *Paradisaeidae* · *Ptilonorhynchidae* — 67 видов

![Райские птицы и шалашники](previews/families/paradisaeidae.webp)

### Питты · *Pittidae* — 46 видов

![Питты](previews/families/pittidae.webp)

### Танагры · *Thraupidae* — 392 вида

![Танагры](previews/families/thraupidae.webp)

### Нектарницы и цветоеды · *Nectariniidae* · *Dicaeidae* — 207 видов

![Нектарницы и цветоеды](previews/families/nectariniidae.webp)

### Котинги и манакины · *Cotingidae* · *Pipridae* — 120 видов

![Котинги и манакины](previews/families/cotingas.webp)

### Фазаны и куропатки · *Phasianidae* — 185 видов

![Фазаны и куропатки](previews/families/phasianidae.webp)

### Утки, гуси и лебеди · *Anatidae* — 164 вида

![Утки, гуси и лебеди](previews/families/anatidae.webp)

### Голуби · *Columbidae* — 338 видов

![Голуби](previews/families/columbidae.webp)

### Вьюрковые ткачики · *Estrildidae* — 138 видов

![Вьюрковые ткачики](previews/families/estrildidae.webp)

### Сойки и сороки · *Corvidae* — 135 видов

![Сойки и сороки](previews/families/corvidae.webp)

### Трупиалы Нового Света · *Icteridae* — 107 видов

![Трупиалы Нового Света](previews/families/icteridae.webp)

### Птицы-носороги · *Bucerotidae* — 64 вида

![Птицы-носороги](previews/families/bucerotidae.webp)

### Скворцы и майны · *Sturnidae* — 118 видов

![Скворцы и майны](previews/families/sturnidae.webp)

### По одному из каждого отряда

![По одному из каждого отряда](previews/orders.webp)

## Что внутри

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | По одному прозрачному стикеру с белым контуром на вид, около 1000 px по длинной стороне. Файлы `<Genus_species>.<subspecies>.webp` — это 91 дополнительный стикер подвидов, которые раньше считались отдельными видами |
| `data/species.json` | Одна запись на вид, полный набор данных: систематика, названия, идентификаторы, ареал и подвиды, промеры тела и экология, охранный статус, стикер и его источник. Описание полей: [data/README.md](data/README.md) |
| `data/crosswalk-ioc15.2-avilist2026.csv` | Как каждый вид IOC 15.2 соответствует AviList v2026: без изменений, переименован, объединён, разделён |
| `data/species.csv` | То же самое, в плоском виде для электронных таблиц |
| `data/names.csv` | Названия на 43 языках (46 столбцов: у китайского, французского и португальского по два варианта) |
| `data/languages.json` | Коды языков и столбец многоязычного списка IOC, из которого взят каждый из них |
| `data/field-guide.zh-Hans.json` | Заметки полевого определителя на упрощённом китайском (внешность, полевые признаки, пол и возраст, похожие виды) для 1596 видов, CC BY-SA 4.0 |

Запись выглядит так (названия сокращены):

```json
{
  "id": "Accipiter_nisus",
  "scientificName": "Accipiter nisus",
  "authority": "(Linnaeus, 1758)",
  "taxonomy": {"system": "AviList v2026", "seq": 3097, "order": "Accipitriformes", "family": "Accipitridae", "genus": "Accipiter"},
  "names": {"en": "Eurasian Sparrowhawk", "zh-Hans": "雀鹰", "ja": "ハイタカ", "es": "Gavilán común", "fr": "Épervier d'Europe", "…": "…"},
  "ids": {"ebird": "eurspa1", "avibase": "avibase-DB376A66", "wikidata": "Q25380", "gbif": "2480637", "inaturalist": 5106},
  "range": {"text": "lowland to treeline montane forest, open woodland, and urban and suburban parks, from Europe eastward to …", "…": "…"},
  "subspecies": [{"name": "nisus", "authority": "(Linnaeus, 1758)", "range": "breeds Europe to Türkiye and Siberia; winters to Africa"}, "…"],
  "traits": {"massG": 220.8, "wingMm": 207.4, "tailMm": 155.5, "habitat": "Forest", "migration": "partially migratory", "trophicNiche": "Vertivore", "…": "…"},
  "conservation": {"iucn": "LC", "cites": "II", "chinaProtection": "Class II"},
  "taxonConcept": "same",
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

- Названия: английский (AviList) охватывает все виды. Названия на других языках взяты из многоязычного списка IOC и оставлены только там, где понимание вида не изменилось; у 129 видов, границы которых изменились (объединения и разделения) или которые появились заново, старое название может относиться к другой группе птиц, поэтому мы не стали его переносить, а не гадать. Упрощённый китайский охватывает 10 947 видов (каждый изменённый вид проверен вручную); французский, испанский, немецкий, русский, японский и китайский (традиционный) — более 94%. Корейский, арабский, тайский, персидский и некоторые другие охватывают лишь от нескольких сотен до примерно тысячи видов, потому что больше в списке IOC нет. См. `data/names.csv`.
- Русские названия есть у 10 455 из 11 011 видов, они взяты прямо из IOC.
- Идентификаторы: eBird 10 983 и Avibase 11 011, оба взяты из AviList; Wikidata 10 757, GBIF 10 477.
- Стикеры: 10 973 из 11 011 видов и ещё 91 стикер подвидов. 38 видов без стикера указаны с `"sticker": null`.

## Как делались стикеры и насколько они хороши

Все 11 064 файла стикеров — это иллюстрации, созданные ИИ. Для каждого вида мы подбирали эталонную фотографию (а для 453 видов, для которых не нашлось достаточно хорошего одиночного снимка, — подборку из нескольких изображений и текстовое описание), рисовали стикер с помощью GPT-image, увеличивали и вырезали по контуру.

Затем каждый стикер ИИ отдельный рецензент оценивал по эталону с точки зрения полевых признаков: клюв, глаз, ноги и лапы, рисунок и цвет оперения. В последнем раунде ещё 852 пограничных стикера (80–82) прошли вторую, слепую проверку, и 211 из них её не прошли и были перерисованы. Пограничные стикеры из прежних раундов этой второй проверки не проходили.

- **7670 соответствуют нашему порогу качества** (`"meetsQualityBar": true`): стикеры ИИ с оценкой 80 и выше.
- **3394 не соответствуют.** Их перерисовывали до установленного предела, и мы оставили версию с наивысшей оценкой, чтобы ни один вид не остался без картинки. У 3279 оценка 70–79, у 109 — ниже 70, а 6 получили 80 и выше, но не прошли слепую повторную проверку. Сейчас мы работаем над более удачным методом и перерисуем эти стикеры; какие именно ошибки мы исправляем, видно в [issue #1](../../issues/1).

Это иллюстрации, а не таблицы из полевого определителя. Относитесь к ним как к дружелюбному изображению птицы, а прежде чем полагаться на тонкую деталь, сверьтесь с определителем. Если вы заметили ошибку, [создайте issue](../../issues/new/choose): поправки от орнитологов-любителей — самый ценный вклад в этот проект.

## Об эталонных фотографиях

Каждый стикер — это новый рисунок, созданный ИИ, а справочных фотографий в этом репозитории нет. Изображение, по которому нарисован каждый вид (страница, автор и лицензия), записано в `sticker.reference` в файле `data/species.json`, поэтому любой стикер можно проследить до источника. Разбивка по лицензиям справочных фотографий приведена в [data/README.md](data/README.md#reference-photos).

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

- Систематика, английские названия, ареалы, идентификаторы eBird и Avibase: AviList Core Team. 2026. AviList: The Global Avian Checklist, v2026. https://doi.org/10.2173/avilist.v2026, CC BY 4.0.
- Названия на других языках: IOC World Bird List v15.2, Gill, Donsker & Rasmussen (ред.), CC BY 3.0.
- Остальные идентификаторы в других базах данных: Wikidata (CC0).
- Промеры тела и экология: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Авторы эталонных фотографий: указаны по видам в `data/species.json`. Сами эталонные фотографии в этот репозиторий не входят.
- Стикеры нарисованы для 鸣迹 (Mingji) — блокнота наблюдателя птиц для iOS.

Если какой-то стикер сделан по вашему фото и вы этого не хотите, создайте issue или напишите на alchaincyf@gmail.com — мы заменим или удалим его в течение 7 дней.
