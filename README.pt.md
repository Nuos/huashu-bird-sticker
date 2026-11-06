# Adesivos das espécies de aves vivas do mundo

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · **Português** · [Русский](README.ru.md) · [العربية](README.ar.md)

<a href="https://birdalbum.com/pt-br/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker"><img src="previews/birdalbum.webp" alt="Bird Album: todas as aves do mundo, um adesivo para cada uma. birdalbum.com" width="100%"></a>

**Veja a biblioteca inteira em uso em [birdalbum.com](https://birdalbum.com/pt-br/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker).** O Bird Album é um guia de aves gratuito feito com estes adesivos: procure qualquer espécie pelo nome em 15 idiomas, veja onde ela vive e em quais meses aparece, e abra um mapa com 8.171 pontos de observação de aves que mostra o que as pessoas estão vendo em cada um neste mês.

11.011 espécies de aves em 45 ordens e 249 famílias, segundo a [AviList v2026](https://www.avilist.org/), a lista global unificada que substituiu as listas do IOC e do Clements em 2025. Todas as espécies vivas estão incluídas, além de 43 que a AviList marca como extintas, extintas na natureza ou possivelmente extintas, mas que já tinham adesivo (veja `extinctionStatus`). 10.973 espécies têm adesivo; as outras 38 foram divididas recentemente e estão sendo desenhadas. Cada espécie vem com dados estruturados: taxonomia, nomes em até 43 idiomas, IDs em outras bases de dados e a origem de cada adesivo.

> **A versão 2.0 passou a taxonomia do IOC 15.2 para a AviList v2026.** 82 espécies mudaram de nome científico (e, com ele, de `id` e de caminho do adesivo), 91 antigas espécies agora são subespécies de outra espécie e 30 espécies novas foram separadas. Todas as mudanças estão listadas em [`data/crosswalk-ioc15.2-avilist2026.csv`](data/crosswalk-ioc15.2-avilist2026.csv), e cada registro guarda o antigo ID do IOC em `previous`. Veja o [CHANGELOG](CHANGELOG.md).

![40 adesivos de 15 ordens de aves](previews/hero.webp)

**Licença em resumo:** os adesivos estão sob a licença [CC BY 4.0](LICENSE.md): você pode usá-los para qualquer fim, inclusive comercial, e também editá-los e redistribuí-los, desde que cite huashu-bird-sticker com um link para este repositório. Os dados são MIT, e as partes de terceiros estão listadas no [NOTICE](NOTICE.md).

## Galeria

Dezoito dos grupos mais coloridos e característicos, 24 adesivos de cada um, escolhidos para que não haja dois parecidos. Todos os adesivos mostrados aqui atingem o padrão de qualidade.

### Beija-flores · *Trochilidae* — 361 espécies

![Beija-flores](previews/families/trochilidae.webp)

### Papagaios e cacatuas · *Psittaciformes* — 391 espécies

![Papagaios e cacatuas](previews/families/parrots.webp)

### Martins-pescadores · *Alcedinidae* — 123 espécies

![Martins-pescadores](previews/families/alcedinidae.webp)

### Abelharucos, rolieiros e udus · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 69 espécies

![Abelharucos, rolieiros e udus](previews/families/coraciiformes.webp)

### Tucanos e barbetas · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 132 espécies

![Tucanos e barbetas](previews/families/toucans.webp)

### Aves-do-paraíso e jardineiros · *Paradisaeidae* · *Ptilonorhynchidae* — 67 espécies

![Aves-do-paraíso e jardineiros](previews/families/paradisaeidae.webp)

### Pitas · *Pittidae* — 46 espécies

![Pitas](previews/families/pittidae.webp)

### Tangarás e sanhaços · *Thraupidae* — 392 espécies

![Tangarás e sanhaços](previews/families/thraupidae.webp)

### Suimangas e pica-flores · *Nectariniidae* · *Dicaeidae* — 207 espécies

![Suimangas e pica-flores](previews/families/nectariniidae.webp)

### Cotingas e manaquins · *Cotingidae* · *Pipridae* — 120 espécies

![Cotingas e manaquins](previews/families/cotingas.webp)

### Faisões e perdizes · *Phasianidae* — 185 espécies

![Faisões e perdizes](previews/families/phasianidae.webp)

### Patos, gansos e cisnes · *Anatidae* — 164 espécies

![Patos, gansos e cisnes](previews/families/anatidae.webp)

### Pombos e rolas · *Columbidae* — 338 espécies

![Pombos e rolas](previews/families/columbidae.webp)

### Estrildídeos · *Estrildidae* — 138 espécies

![Estrildídeos](previews/families/estrildidae.webp)

### Gaios e pegas · *Corvidae* — 135 espécies

![Gaios e pegas](previews/families/corvidae.webp)

### Icterídeos do Novo Mundo (xexéus, japins e corrupiões) · *Icteridae* — 107 espécies

![Icterídeos do Novo Mundo (xexéus, japins e corrupiões)](previews/families/icteridae.webp)

### Calaus · *Bucerotidae* — 64 espécies

![Calaus](previews/families/bucerotidae.webp)

### Estorninhos e mainás · *Sturnidae* — 118 espécies

![Estorninhos e mainás](previews/families/sturnidae.webp)

### Um de cada ordem

![Um de cada ordem](previews/orders.webp)

## O que há aqui

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | Um adesivo transparente com contorno branco por espécie, com cerca de 1.000 px no lado maior. Os arquivos `<Genus_species>.<subspecies>.webp` são 91 adesivos extras de subespécies que antes eram espécies separadas |
| `data/species.json` | Um registro por espécie, o conjunto de dados completo: taxonomia, nomes, IDs, distribuição e subespécies, medidas corporais e ecologia, estado de conservação, adesivo e sua origem. Descrição dos campos: [data/README.md](data/README.md) |
| `data/crosswalk-ioc15.2-avilist2026.csv` | Como cada espécie do IOC 15.2 corresponde à AviList v2026: igual, renomeada, agrupada, dividida |
| `data/species.csv` | O mesmo conteúdo, achatado para planilhas |
| `data/names.csv` | Nomes em 43 idiomas (46 colunas: chinês, francês e português têm duas variantes cada) |
| `data/languages.json` | Códigos de idioma e a coluna da lista multilíngue do IOC de onde cada um vem |
| `data/field-guide.zh-Hans.json` | Notas de guia de campo em chinês simplificado (aparência, marcas de campo, sexos e idades, espécies semelhantes) para 1.596 espécies, CC BY-SA 4.0 |

Um registro tem este formato (nomes abreviados):

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

- Nomes: o inglês (AviList) cobre todas as espécies. Os outros idiomas vêm da lista multilíngue do IOC e foram mantidos apenas onde o conceito da espécie não mudou; nas 129 espécies cujos limites mudaram (agrupamentos e divisões) ou que são novas, um nome antigo pode se referir a outro conjunto de aves, então preferimos omiti-lo a adivinhar. O chinês simplificado cobre 10.947 espécies (cada espécie alterada foi conferida à mão); francês, espanhol, alemão, russo, japonês e chinês tradicional passam de 94%. Coreano, árabe, tailandês, persa e alguns outros cobrem de algumas centenas a cerca de mil espécies, porque é isso que a lista do IOC oferece. Veja `data/names.csv`.
- Os nomes em português do Brasil (coluna `pt-x-lusophone` do IOC) cobrem 10.857 das 11.011 espécies.
- IDs: eBird 10.983 e Avibase 11.011, ambos vindos da AviList; Wikidata 10.757, GBIF 10.477.
- Adesivos: 10.973 de 11.011 espécies, mais 91 adesivos de subespécies. As 38 espécies sem adesivo aparecem com `"sticker": null`.

## Como os adesivos foram feitos e qual é a qualidade

Todos os 11.064 arquivos de adesivo são ilustrações feitas por IA. Para cada espécie, procuramos uma foto de referência (ou, nas 453 espécies em que nenhuma foto isolada era boa o bastante, uma prancha com várias imagens e uma descrição escrita), desenhamos o adesivo com o GPT-image, ampliamos e recortamos.

Depois, cada adesivo de IA recebeu a nota de um revisor independente, que o comparou com a referência quanto às marcas de campo: bico, olho, pernas e pés, padrão e cor da plumagem. Na última rodada, 852 adesivos limítrofes (80–82) passaram também por uma segunda revisão às cegas, e 211 deles foram reprovados e gerados de novo. Os adesivos limítrofes de rodadas anteriores não passaram por essa segunda revisão. Em novembro de 2026, reavaliamos os adesivos com um critério mais rigoroso, como pranchas de guia de campo, e geramos de novo 7.336 deles. Um adesivo gerado de novo só passa na revisão se identificação, plumagem, bico e olho, pernas e pés, e proporções receberem pelo menos 3 pontos de 4 em cada item, a identificação receber 4 e o revisor o aceitar como prancha de guia de campo.

- **10.870 atingem nosso padrão de qualidade** (`"meetsQualityBar": true`): adesivos que passaram pela revisão mais rigorosa descrita acima ou receberam nota 80 ou mais na revisão anterior.
- **194 não atingem.** Ficamos com a versão de maior nota para que nenhuma espécie fique sem imagem: 190 têm nota de 70 a 79 e 4 ficam abaixo de 70. Estamos gerando de novo esses adesivos; veja a [issue #1](../../issues/1) e a [issue #3](../../issues/3) para conhecer os tipos de erro que estamos corrigindo.
- **Alguns foram gerados só a partir de uma descrição escrita**, sem foto de referência (`"reference": null` em `data/species.json`; o número está em [data/README.md](data/README.md#reference-photos)). Eles têm mais chance de conter erros do que os adesivos conferidos com uma foto. No [birdalbum.com](https://birdalbum.com/), a página da espécie traz um aviso extra para esses adesivos e para os que não atingem o padrão de qualidade.

São ilustrações, não pranchas de guia de campo. Veja-as como um desenho simpático da ave e consulte um guia de campo antes de confiar em algum detalhe fino. Se encontrar um erro, [abra uma issue](../../issues/new/choose): correções de observadores de aves são a contribuição mais valiosa que este projeto pode receber.

## Sobre as fotos de referência

**Para que serve uma referência.** Um adesivo mostra como é uma espécie: as cores e os padrões da plumagem, o bico, o olho, as pernas e os pés, e as proporções. São fatos sobre a ave, as mesmas coisas que um guia de campo descreve em palavras. Uma descrição escrita sozinha muitas vezes não basta para o modelo de imagem acertá-las, então usamos fotos de referência.

**Como usamos.** Para cada espécie, o modelo de imagem vê uma ou mais fotos de referência junto com uma descrição escrita das marcas de identificação e desenha uma ilustração nova. Não usamos a composição, o fundo nem a iluminação da foto: os adesivos gerados de novo desde novembro de 2026 usam todos a mesma pose padrão de perfil definida por nós, sobre um fundo liso, não importa o que a ave esteja fazendo na foto. Depois, um revisor separado confere o desenho com base nas marcas de identificação. De agora em diante, sempre que possível, usamos fotos de vários observadores para cada espécie, para que o adesivo reflita a espécie e não uma única imagem. Este repositório não inclui nenhuma foto de referência.

**Créditos e remoção.** As fotos de referência de cada adesivo (página, autor e licença) estão listadas em `sticker.reference`, em `data/species.json`, então todo adesivo pode ser rastreado. Um detalhamento por licença das fotos de referência está em [data/README.md](data/README.md#reference-photos). Se uma foto sua foi usada como referência e você prefere que não seja assim, abra uma issue ou escreva para alchaincyf@gmail.com, e substituiremos o adesivo em até 7 dias.

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

- Taxonomia, nomes em inglês, distribuição e IDs do eBird e do Avibase: AviList Core Team. 2026. AviList: The Global Avian Checklist, v2026. https://doi.org/10.2173/avilist.v2026, CC BY 4.0.
- Nomes em outros idiomas: IOC World Bird List v15.2, Gill, Donsker & Rasmussen (orgs.), CC BY 3.0.
- Demais IDs entre bases de dados: Wikidata (CC0).
- Medidas corporais e ecologia: AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Fotógrafos das imagens de referência: creditados por espécie em `data/species.json`. As fotos de referência não estão incluídas neste repositório.
- Adesivos desenhados para o 鸣迹 (Mingji), um caderno de observação de aves para iOS.

Se uma foto sua foi usada como referência para um adesivo e você prefere que não seja assim, abra uma issue ou escreva para alchaincyf@gmail.com, e substituiremos o adesivo em até 7 dias.
