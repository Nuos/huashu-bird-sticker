# Pegatinas de todas las 11 064 especies de aves vivas del mundo

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · **Español** · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

11 064 especies de aves, una pegatina por cada una, en 44 órdenes y 250 familias. Son todas las especies vivas de la IOC World Bird List v15.2 (las 163 especies extintas no se incluyen). Cada especie viene con datos estructurados: taxonomía, nombres en hasta 43 idiomas, identificadores de otras bases de datos y el origen de cada pegatina.

![40 pegatinas de 15 órdenes de aves](previews/hero.webp)

Las pegatinas se pueden usar gratis para casi cualquier fin, incluido el comercial, bajo la licencia [PolyForm Shield 1.0.0](LICENSE.md). Lo único que no se puede hacer es usarlas en un producto que compita con nuestra aplicación de aves (otra aplicación o sitio de observación de aves, identificación de aves o guía de campo). Los datos están bajo licencia MIT. Lea [NOTICE](NOTICE.md) para conocer las partes que provienen de terceros, y [Sobre las fotografías de referencia](#sobre-las-fotografías-de-referencia) más abajo.

## Galería

Dieciocho de los grupos más coloridos y característicos, 24 pegatinas de cada uno, elegidas para que no haya dos que se parezcan. Todas las pegatinas que se muestran aquí cumplen el nivel de calidad.

### Colibríes · *Trochilidae* — 365 especies

![Colibríes](previews/families/trochilidae.webp)

### Loros y cacatúas · *Psittaciformes* — 392 especies

![Loros y cacatúas](previews/families/parrots.webp)

### Martines pescadores · *Alcedinidae* — 116 especies

![Martines pescadores](previews/families/alcedinidae.webp)

### Abejarucos, carracas y momotos · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68 especies

![Abejarucos, carracas y momotos](previews/families/coraciiformes.webp)

### Tucanes y barbudos · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134 especies

![Tucanes y barbudos](previews/families/toucans.webp)

### Aves del paraíso y ptilonorrincos · *Paradisaeidae* · *Ptilonorhynchidae* — 69 especies

![Aves del paraíso y ptilonorrincos](previews/families/paradisaeidae.webp)

### Pitas · *Pittidae* — 46 especies

![Pitas](previews/families/pittidae.webp)

### Tangaras · *Thraupidae* — 393 especies

![Tangaras](previews/families/thraupidae.webp)

### Suimangas y picaflores · *Nectariniidae* · *Dicaeidae* — 208 especies

![Suimangas y picaflores](previews/families/nectariniidae.webp)

### Cotingas y saltarines · *Cotingidae* · *Pipridae* — 121 especies

![Cotingas y saltarines](previews/families/cotingas.webp)

### Faisanes y perdices · *Phasianidae* — 185 especies

![Faisanes y perdices](previews/families/phasianidae.webp)

### Patos, gansos y cisnes · *Anatidae* — 166 especies

![Patos, gansos y cisnes](previews/families/anatidae.webp)

### Palomas · *Columbidae* — 339 especies

![Palomas](previews/families/columbidae.webp)

### Estríldidos · *Estrildidae* — 140 especies

![Estríldidos](previews/families/estrildidae.webp)

### Arrendajos y urracas · *Corvidae* — 138 especies

![Arrendajos y urracas](previews/families/corvidae.webp)

### Ictéridos del Nuevo Mundo (turpiales y oropéndolas) · *Icteridae* — 107 especies

![Ictéridos del Nuevo Mundo (turpiales y oropéndolas)](previews/families/icteridae.webp)

### Cálaos · *Bucerotidae* — 64 especies

![Cálaos](previews/families/bucerotidae.webp)

### Estorninos y mainás · *Sturnidae* — 120 especies

![Estorninos y mainás](previews/families/sturnidae.webp)

### Una de cada uno de los 44 órdenes

![Una de cada uno de los 44 órdenes](previews/orders.webp)

## Contenido

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | 11 064 pegatinas transparentes con borde blanco, de unos 1000 px en el lado largo |
| `data/species.json` | Un registro por especie, el conjunto de datos completo: taxonomía, nombres, identificadores, distribución y subespecies, medidas corporales y ecología, estado de conservación, pegatina y su origen. Descripción de los campos: [data/README.md](data/README.md) |
| `data/species.csv` | Lo mismo, aplanado para hojas de cálculo |
| `data/names.csv` | Nombres en 43 idiomas (46 columnas: el chino, el francés y el portugués tienen dos variantes cada uno) |
| `data/languages.json` | Códigos de idioma y la columna de la IOC de la que procede cada uno |
| `data/field-guide.zh-Hans.json` | Notas de guía de campo en chino simplificado (aspecto, marcas de campo, sexos y edades, especies parecidas) de 1596 especies, CC BY-SA 4.0 |

Un registro tiene este aspecto (nombres abreviados):

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

## Cobertura

- Nombres: el inglés cubre todas las especies, y el francés y el chino simplificado todas menos unas pocas (el chino simplificado aún no tiene nombre para 23 especies separadas recientemente); el japonés, el chino tradicional, el ruso, el alemán, el español, el polaco, el neerlandés, el sueco y una docena más de idiomas europeos superan el 90 %. El serbio, el húngaro y el estonio están entre el 50 % y el 75 %. El coreano, el árabe, el tailandés, el persa y algunos más cubren por ahora solo desde unos cientos hasta alrededor de mil especies, porque es lo que ofrece la lista de la IOC. Véase `data/names.csv`.
- De los nombres en español, 10 877 de las 11 064 especies proceden de la IOC.
- Identificadores: Wikidata 10 939, GBIF 10 649, eBird 10 052.
- Pegatinas: 11 064 de 11 064.

## Cómo se hicieron las pegatinas y qué calidad tienen

11 064 pegatinas son ilustraciones hechas con IA. Para cada especie buscamos una fotografía de referencia (o, en las 453 especies para las que ninguna foto por sí sola era suficientemente buena, un tablero con varias imágenes y una descripción escrita), dibujamos la pegatina con GPT-image, la ampliamos y la recortamos.

Después, un revisor independiente puntuó cada pegatina de IA frente a la referencia en cuanto a las marcas de campo: pico, ojo, patas y pies, patrón y color del plumaje. En la última ronda, 852 pegatinas límite (80–82) tuvieron además una segunda revisión a ciegas, y 211 de ellas no la superaron y se volvieron a dibujar. Las pegatinas límite de rondas anteriores no pasaron por esta segunda revisión.

- **7668 cumplen nuestro nivel de calidad** (`"meetsQualityBar": true`): las pegatinas de IA con 80 puntos o más.
- **3396 no lo cumplen.** Se volvieron a dibujar hasta el límite de intentos y nos quedamos con la versión de mayor puntuación para que ninguna especie quede sin imagen. 3281 puntúan entre 70 y 79, 109 puntúan por debajo de 70 y 6 obtuvieron 80 o más pero no superaron la segunda revisión a ciegas.

Son ilustraciones, no láminas de guía de campo. Tómelas como un dibujo amable del ave y consulte una guía de campo antes de fiarse de un detalle fino. Si encuentra un error, [abra una incidencia](../../issues/new/choose): las correcciones de observadores de aves son la contribución más valiosa que puede recibir este proyecto.

## Sobre las fotografías de referencia

La referencia de cada pegatina figura en `sticker.reference`, con su página, autor y licencia. Se reparten así (pegatinas de IA, por especie):

| Referencia | Especies |
|---|---|
| Foto con licencia abierta (CC0, dominio público, CC BY, CC BY-SA) | 2020 |
| Tablero de imágenes con licencia abierta, o solo una descripción escrita | 46 |
| Foto con licencia no comercial o sin obras derivadas (CC BY-NC, -ND, …) | 5071 |
| Foto con todos los derechos reservados, o bajo las condiciones de Macaulay Library | 1500 |
| Foto cuya licencia no registramos | 2017 |
| Tablero que mezcla imágenes con condiciones distintas | 410 |

Las pegatinas son dibujos nuevos, no copias, y las fotografías de referencia no se distribuyen aquí. Si un dibujo hecho a partir de una foto queda sujeto a la licencia de esa foto es una cuestión jurídica sin resolver. Si le afecta para lo que va a hacer, filtre por `sticker.reference.license`.

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

- Taxonomía y nombres multilingües: IOC World Bird List v15.2, Gill, Donsker y Rasmussen (eds.), CC BY 3.0.
- Identificadores entre bases de datos: Wikidata (CC0).
- Medidas corporales y ecología: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Fotógrafos de las imágenes de referencia: se citan por especie en `data/species.json`. Las fotografías de referencia no se incluyen en este repositorio.
- Pegatinas dibujadas para 鸣迹 (Mingji), una libreta de observación de aves para iOS.

Si una pegatina se basa en una foto suya y prefiere que no sea así, abra una incidencia o escriba a alchaincyf@gmail.com y la sustituiremos o la retiraremos en un plazo de 7 días.
