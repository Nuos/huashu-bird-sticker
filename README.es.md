# Pegatinas de las especies de aves vivas del mundo

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **Español** · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

<a href="https://birdalbum.com/es/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker"><img src="previews/birdalbum.webp" alt="Bird Album: todas las aves del mundo, una pegatina por cada una. birdalbum.com" width="100%"></a>

**Vea toda la biblioteca en uso en [birdalbum.com](https://birdalbum.com/es/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker).** Bird Album es una guía de aves gratuita creada con estas pegatinas: busque cualquier especie por su nombre en 15 idiomas, consulte dónde vive y en qué meses se la puede ver, y abra un mapa de 8171 puntos de observación de aves que muestra lo que la gente está viendo en cada uno este mes.

11 011 especies de aves en 45 órdenes y 249 familias, según [AviList v2026](https://www.avilist.org/), la lista global unificada que en 2025 sustituyó a las listas de la IOC y de Clements. Están todas las especies vivas, más 43 que AviList marca como extintas, extintas en estado silvestre o posiblemente extintas pero que ya tenían pegatina (véase `extinctionStatus`). 10 973 especies tienen pegatina; las otras 38 se separaron hace poco y se están dibujando. Cada especie viene con datos estructurados: taxonomía, nombres en hasta 43 idiomas, identificadores de otras bases de datos y el origen de cada pegatina.

> **La versión 2.0 pasó la taxonomía de la IOC 15.2 a AviList v2026.** 82 especies cambiaron de nombre científico (y con ello su `id` y la ruta de su pegatina), 91 antiguas especies son ahora subespecies de otra especie y se separaron 30 especies nuevas. Todos los cambios están en [`data/crosswalk-ioc15.2-avilist2026.csv`](data/crosswalk-ioc15.2-avilist2026.csv), y cada registro conserva su antiguo identificador de la IOC en `previous`. Véase el [CHANGELOG](CHANGELOG.md).

![40 pegatinas de 15 órdenes de aves](previews/hero.webp)

**Licencia en breve:** las pegatinas tienen licencia [CC BY 4.0](LICENSE.md): puede usarlas para cualquier fin, incluido el comercial, y también editarlas y redistribuirlas, siempre que mencione huashu-bird-sticker con un enlace a este repositorio. Los datos están bajo licencia MIT y las partes de terceros figuran en [NOTICE](NOTICE.md).

## Galería

Dieciocho de los grupos más coloridos y característicos, 24 pegatinas de cada uno, elegidas para que no haya dos que se parezcan. Todas las pegatinas que se muestran aquí cumplen el nivel de calidad.

### Colibríes · *Trochilidae* — 361 especies

![Colibríes](previews/families/trochilidae.webp)

### Loros y cacatúas · *Psittaciformes* — 391 especies

![Loros y cacatúas](previews/families/parrots.webp)

### Martines pescadores · *Alcedinidae* — 123 especies

![Martines pescadores](previews/families/alcedinidae.webp)

### Abejarucos, carracas y momotos · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 69 especies

![Abejarucos, carracas y momotos](previews/families/coraciiformes.webp)

### Tucanes y barbudos · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 132 especies

![Tucanes y barbudos](previews/families/toucans.webp)

### Aves del paraíso y ptilonorrincos · *Paradisaeidae* · *Ptilonorhynchidae* — 67 especies

![Aves del paraíso y ptilonorrincos](previews/families/paradisaeidae.webp)

### Pitas · *Pittidae* — 46 especies

![Pitas](previews/families/pittidae.webp)

### Tangaras · *Thraupidae* — 392 especies

![Tangaras](previews/families/thraupidae.webp)

### Suimangas y picaflores · *Nectariniidae* · *Dicaeidae* — 207 especies

![Suimangas y picaflores](previews/families/nectariniidae.webp)

### Cotingas y saltarines · *Cotingidae* · *Pipridae* — 120 especies

![Cotingas y saltarines](previews/families/cotingas.webp)

### Faisanes y perdices · *Phasianidae* — 185 especies

![Faisanes y perdices](previews/families/phasianidae.webp)

### Patos, gansos y cisnes · *Anatidae* — 164 especies

![Patos, gansos y cisnes](previews/families/anatidae.webp)

### Palomas · *Columbidae* — 338 especies

![Palomas](previews/families/columbidae.webp)

### Estríldidos · *Estrildidae* — 138 especies

![Estríldidos](previews/families/estrildidae.webp)

### Arrendajos y urracas · *Corvidae* — 135 especies

![Arrendajos y urracas](previews/families/corvidae.webp)

### Ictéridos del Nuevo Mundo (turpiales y oropéndolas) · *Icteridae* — 107 especies

![Ictéridos del Nuevo Mundo (turpiales y oropéndolas)](previews/families/icteridae.webp)

### Cálaos · *Bucerotidae* — 64 especies

![Cálaos](previews/families/bucerotidae.webp)

### Estorninos y mainás · *Sturnidae* — 118 especies

![Estorninos y mainás](previews/families/sturnidae.webp)

### Una de cada orden

![Una de cada orden](previews/orders.webp)

## Contenido

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | Una pegatina transparente con borde blanco por especie, de unos 1000 px en el lado largo. Los `<Genus_species>.<subspecies>.webp` son 91 pegatinas adicionales de subespecies que antes eran especies independientes |
| `data/species.json` | Un registro por especie, el conjunto de datos completo: taxonomía, nombres, identificadores, distribución y subespecies, medidas corporales y ecología, estado de conservación, pegatina y su origen. Descripción de los campos: [data/README.md](data/README.md) |
| `data/crosswalk-ioc15.2-avilist2026.csv` | Cómo se corresponde cada especie de la IOC 15.2 con AviList v2026: igual, rebautizada, fusionada, dividida |
| `data/species.csv` | Lo mismo, aplanado para hojas de cálculo |
| `data/names.csv` | Nombres en 43 idiomas (46 columnas: el chino, el francés y el portugués tienen dos variantes cada uno) |
| `data/languages.json` | Códigos de idioma y la columna multilingüe de la IOC de la que procede cada uno |
| `data/field-guide.zh-Hans.json` | Notas de guía de campo en chino simplificado (aspecto, marcas de campo, sexos y edades, especies parecidas) de 1596 especies, CC BY-SA 4.0 |

Un registro tiene este aspecto (nombres abreviados):

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
    "license": "CC-BY-4.0",
    "reference": {"type": "photo", "page": "https://commons.wikimedia.org/wiki/File:…", "author": "Dion Art", "license": "CC BY-SA 4.0"}
  }
}
```

## Cobertura

- Nombres: el inglés (AviList) cubre todas las especies. Los demás idiomas proceden de la lista multilingüe de la IOC y se conservan solo donde el concepto de especie no cambió; en las 129 especies cuyos límites cambiaron (fusiones y divisiones) o que son nuevas, un nombre antiguo puede referirse a otro conjunto de aves, así que lo omitimos en lugar de adivinar. El chino simplificado cubre 10 947 especies (cada especie modificada se comprobó a mano); el francés, el español, el alemán, el ruso, el japonés y el chino tradicional superan el 94 %. El coreano, el árabe, el tailandés, el persa y algunos más cubren solo desde unos cientos hasta alrededor de mil especies, porque es lo que ofrece la lista de la IOC. Véase `data/names.csv`.
- Identificadores: eBird 10 983 y Avibase 11 011, ambos tomados de AviList; Wikidata 10 757, GBIF 10 477.
- Pegatinas: 10 973 de 11 011 especies, más 91 pegatinas de subespecies. Las 38 especies que aún no tienen pegatina figuran con `"sticker": null`.

## Cómo se hicieron las pegatinas y qué calidad tienen

Los 11 064 archivos de pegatinas son ilustraciones hechas con IA. Para cada especie buscamos una fotografía de referencia (o, en las 453 especies para las que ninguna foto por sí sola era suficientemente buena, un tablero con varias imágenes y una descripción escrita), dibujamos la pegatina con GPT-image, la ampliamos y la recortamos.

Después, un revisor independiente puntuó cada pegatina de IA frente a la referencia en cuanto a las marcas de campo: pico, ojo, patas y pies, patrón y color del plumaje. En la última ronda, 852 pegatinas límite (80–82) tuvieron además una segunda revisión a ciegas, y 211 de ellas no la superaron y se volvieron a generar. Las pegatinas límite de rondas anteriores no pasaron por esta segunda revisión. En noviembre de 2026 volvimos a revisar las pegatinas con un criterio más estricto, como láminas de guía de campo, y volvimos a generar 10114 de ellas. Una pegatina generada de nuevo solo supera la revisión si la identificación, el plumaje, el pico y el ojo, las patas y los pies, y las proporciones obtienen al menos 3 puntos de 4 en cada apartado, la identificación obtiene 4 y el revisor la aceptaría como lámina de guía de campo.

- **11043 cumplen nuestro nivel de calidad** (`"meetsQualityBar": true`): las pegatinas que superaron la revisión más estricta descrita arriba u obtuvieron 80 puntos o más en la revisión anterior.
- **21 no lo cumplen.** Nos quedamos con la versión de mayor puntuación para que ninguna especie quede sin imagen: 17 puntúan entre 70 y 79 y 4 puntúan por debajo de 70. Estamos generando de nuevo estas pegatinas; véanse la [incidencia n.º 1](../../issues/1) y la [incidencia n.º 3](../../issues/3) para ver los tipos de error que estamos corrigiendo.
- **Algunas se generaron solo a partir de una descripción escrita**, sin foto de referencia (`"reference": null` en `data/species.json`; el número está en [data/README.md](data/README.md#reference-photos)). Es más probable que tengan errores que las pegatinas cotejadas con una foto. En [birdalbum.com](https://birdalbum.com/), la página de la especie lleva un aviso adicional para estas pegatinas y para las que no alcanzan el umbral de calidad.

Son ilustraciones, no láminas de guía de campo. Tómelas como un dibujo amable del ave y consulte una guía de campo antes de fiarse de un detalle fino. Si encuentra un error, [abra una incidencia](../../issues/new/choose): las correcciones de observadores de aves son la contribución más valiosa que puede recibir este proyecto.

## Sobre las fotografías de referencia

**Para qué sirve una referencia.** Una pegatina muestra cómo es una especie: los colores y las marcas del plumaje, el pico, el ojo, las patas y las proporciones. Son hechos sobre el ave, lo mismo que una guía de campo describe con palabras. Una descripción escrita a menudo no basta para que el modelo de imagen los acierte, así que usamos fotografías de referencia.

**Cómo la usamos.** Para cada especie, al modelo de imagen se le muestran una o varias fotografías de referencia junto con una descripción escrita de los rasgos de identificación, y dibuja una ilustración nueva. No usamos la composición, el fondo ni la iluminación de la foto: las pegatinas generadas de nuevo desde noviembre de 2026 usan todas la misma postura estándar de perfil que fijamos nosotros, sobre un fondo liso, haga lo que haga el ave en la foto. Después, un revisor independiente comprueba el dibujo según los rasgos de identificación. A partir de ahora usamos, siempre que podemos, fotos de varios observadores para cada especie, de modo que la pegatina refleje la especie y no una imagen concreta. Este repositorio no incluye ninguna fotografía de referencia.

**Créditos y retirada.** Las fotografías de referencia de cada pegatina (página, autor y licencia) figuran en `sticker.reference`, dentro de `data/species.json`, así que cada pegatina se puede rastrear. Un desglose por licencia de las fotografías de referencia está en [data/README.md](data/README.md#reference-photos). Si una de sus fotos se usó como referencia y prefiere que no sea así, abra una incidencia o escriba a alchaincyf@gmail.com y sustituiremos la pegatina en un plazo de 7 días.

## Cómo usarlo

Los archivos se pueden cargar directamente:

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

El repositorio pesa unos 700 MB. Para descargar solo los datos y unas pocas pegatinas:

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## Créditos

- Taxonomía, nombres en inglés, distribución e identificadores de eBird y Avibase: AviList Core Team. 2026. AviList: The Global Avian Checklist, v2026. https://doi.org/10.2173/avilist.v2026, CC BY 4.0.
- Nombres en otros idiomas: IOC World Bird List v15.2, Gill, Donsker y Rasmussen (eds.), CC BY 3.0.
- Otros identificadores entre bases de datos: Wikidata (CC0).
- Medidas corporales y ecología: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Fotógrafos de las imágenes de referencia: se citan por especie en `data/species.json`. Las fotografías de referencia no se incluyen en este repositorio.
- Pegatinas dibujadas para 鸣迹 (Mingji), una libreta de observación de aves para iOS.

Si una de sus fotos se usó como referencia para una pegatina y prefiere que no sea así, abra una incidencia o escriba a alchaincyf@gmail.com y sustituiremos la pegatina en un plazo de 7 días.
