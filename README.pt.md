# Adesivos de todas as 11.064 espécies de aves vivas

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · **Português** · [Русский](README.ru.md) · [العربية](README.ar.md)

11.064 espécies de aves, um adesivo para cada uma, em 44 ordens e 250 famílias. São todas as espécies vivas da IOC World Bird List v15.2 (as 163 espécies extintas não estão incluídas). Cada espécie vem com dados estruturados: taxonomia, nomes em até 43 idiomas, IDs em outras bases de dados e a origem de cada adesivo.

![40 adesivos de 15 ordens de aves](previews/hero.webp)

**Licença em resumo:** você pode usar os adesivos para qualquer fim, inclusive comercial, e também editá-los e redistribuí-los. A única exceção é um aplicativo, site ou serviço de observação de aves, identificação de aves ou guia de campo de aves. Cite huashu-bird-sticker com um link para este repositório e pronto. O texto legal é a [PolyForm Shield 1.0.0](LICENSE.md). Os dados são MIT, e as partes de terceiros estão listadas no [NOTICE](NOTICE.md).

## Galeria

Dezoito dos grupos mais coloridos e característicos, 24 adesivos de cada um, escolhidos para que não haja dois parecidos. Todos os adesivos mostrados aqui atingem o padrão de qualidade.

### Beija-flores · *Trochilidae* — 365 espécies

![Beija-flores](previews/families/trochilidae.webp)

### Papagaios e cacatuas · *Psittaciformes* — 392 espécies

![Papagaios e cacatuas](previews/families/parrots.webp)

### Martins-pescadores · *Alcedinidae* — 116 espécies

![Martins-pescadores](previews/families/alcedinidae.webp)

### Abelharucos, rolieiros e udus · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68 espécies

![Abelharucos, rolieiros e udus](previews/families/coraciiformes.webp)

### Tucanos e barbetas · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134 espécies

![Tucanos e barbetas](previews/families/toucans.webp)

### Aves-do-paraíso e jardineiros · *Paradisaeidae* · *Ptilonorhynchidae* — 69 espécies

![Aves-do-paraíso e jardineiros](previews/families/paradisaeidae.webp)

### Pitas · *Pittidae* — 46 espécies

![Pitas](previews/families/pittidae.webp)

### Tangarás e sanhaços · *Thraupidae* — 393 espécies

![Tangarás e sanhaços](previews/families/thraupidae.webp)

### Suimangas e pica-flores · *Nectariniidae* · *Dicaeidae* — 208 espécies

![Suimangas e pica-flores](previews/families/nectariniidae.webp)

### Cotingas e manaquins · *Cotingidae* · *Pipridae* — 121 espécies

![Cotingas e manaquins](previews/families/cotingas.webp)

### Faisões e perdizes · *Phasianidae* — 185 espécies

![Faisões e perdizes](previews/families/phasianidae.webp)

### Patos, gansos e cisnes · *Anatidae* — 166 espécies

![Patos, gansos e cisnes](previews/families/anatidae.webp)

### Pombos e rolas · *Columbidae* — 339 espécies

![Pombos e rolas](previews/families/columbidae.webp)

### Estrildídeos · *Estrildidae* — 140 espécies

![Estrildídeos](previews/families/estrildidae.webp)

### Gaios e pegas · *Corvidae* — 138 espécies

![Gaios e pegas](previews/families/corvidae.webp)

### Icterídeos do Novo Mundo (xexéus, japins e corrupiões) · *Icteridae* — 107 espécies

![Icterídeos do Novo Mundo (xexéus, japins e corrupiões)](previews/families/icteridae.webp)

### Calaus · *Bucerotidae* — 64 espécies

![Calaus](previews/families/bucerotidae.webp)

### Estorninhos e mainás · *Sturnidae* — 120 espécies

![Estorninhos e mainás](previews/families/sturnidae.webp)

### Um de cada uma das 44 ordens

![Um de cada uma das 44 ordens](previews/orders.webp)

## O que há aqui

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | 11.064 adesivos transparentes com contorno branco, com cerca de 1.000 px no lado maior |
| `data/species.json` | Um registro por espécie, o conjunto de dados completo: taxonomia, nomes, IDs, distribuição e subespécies, medidas corporais e ecologia, estado de conservação, adesivo e sua origem. Descrição dos campos: [data/README.md](data/README.md) |
| `data/species.csv` | O mesmo conteúdo, achatado para planilhas |
| `data/names.csv` | Nomes em 43 idiomas (46 colunas: chinês, francês e português têm duas variantes cada) |
| `data/languages.json` | Códigos de idioma e a coluna do IOC de onde cada um vem |
| `data/field-guide.zh-Hans.json` | Notas de guia de campo em chinês simplificado (aparência, marcas de campo, sexos e idades, espécies semelhantes) para 1.596 espécies, CC BY-SA 4.0 |

Um registro tem este formato (nomes abreviados):

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

- Nomes: o inglês cobre todas as espécies, e o francês e o chinês simplificado todas, exceto algumas (o chinês simplificado ainda não tem nomes para 23 espécies recém-divididas); japonês, chinês tradicional, russo, alemão, espanhol, polonês, holandês, sueco e cerca de uma dúzia de outros idiomas europeus passam de 90%. Sérvio, húngaro e estoniano ficam entre 50% e 75%. Coreano, árabe, tailandês, persa e alguns outros cobrem, por enquanto, de algumas centenas a cerca de mil espécies, porque é isso que a lista do IOC oferece. Veja `data/names.csv`.
- Os nomes em português do Brasil (coluna `pt-x-lusophone` do IOC) cobrem 11.039 das 11.064 espécies.
- IDs: Wikidata 10.939, GBIF 10.649, eBird 10.052.
- Adesivos: 11.064 de 11.064.

## Como os adesivos foram feitos e qual é a qualidade

11.064 adesivos são ilustrações feitas por IA. Para cada espécie, procuramos uma foto de referência (ou, nas 453 espécies em que nenhuma foto isolada era boa o bastante, uma prancha com várias imagens e uma descrição escrita), desenhamos o adesivo com o GPT-image, ampliamos e recortamos.

Depois, cada adesivo de IA recebeu a nota de um revisor independente, que o comparou com a referência quanto às marcas de campo: bico, olho, pernas e pés, padrão e cor da plumagem. Na última rodada, 852 adesivos limítrofes (80–82) passaram também por uma segunda revisão às cegas, e 211 deles foram reprovados e redesenhados. Os adesivos limítrofes de rodadas anteriores não passaram por essa segunda revisão.

- **7.668 atingem nosso padrão de qualidade** (`"meetsQualityBar": true`): adesivos de IA com nota 80 ou mais.
- **3.396 não atingem.** Foram redesenhados até o limite de tentativas, e ficamos com a versão de maior nota para que nenhuma espécie fique sem imagem. 3.281 têm nota de 70 a 79, 109 ficam abaixo de 70, e 6 tiraram 80 ou mais mas foram reprovados na segunda revisão às cegas.

São ilustrações, não pranchas de guia de campo. Veja-as como um desenho simpático da ave e consulte um guia de campo antes de confiar em algum detalhe fino. Se encontrar um erro, [abra uma issue](../../issues/new/choose): correções de observadores de aves são a contribuição mais valiosa que este projeto pode receber.

## Sobre as fotos de referência

Cada adesivo é um desenho novo feito com IA, e este repositório não inclui nenhuma foto de referência. A imagem usada como base para desenhar cada espécie (página, autor e licença) está registrada em `sticker.reference`, em `data/species.json`, então todo adesivo pode ser rastreado até a sua fonte. Um detalhamento por licença das fotos de referência está em [data/README.md](data/README.md#reference-photos).

## Como usar

Os arquivos podem ser carregados diretamente:

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

O repositório tem cerca de 700 MB. Para baixar apenas os dados e alguns adesivos:

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## Créditos

- Taxonomia e nomes multilíngues: IOC World Bird List v15.2, Gill, Donsker & Rasmussen (orgs.), CC BY 3.0.
- IDs entre bases de dados: Wikidata (CC0).
- Medidas corporais e ecologia: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Fotógrafos das imagens de referência: creditados por espécie em `data/species.json`. As fotos de referência não estão incluídas neste repositório.
- Adesivos desenhados para o 鸣迹 (Mingji), um caderno de observação de aves para iOS.

Se um adesivo se baseia em uma foto sua e você prefere que não seja assim, abra uma issue ou escreva para alchaincyf@gmail.com, e nós o substituiremos ou removeremos em até 7 dias.
