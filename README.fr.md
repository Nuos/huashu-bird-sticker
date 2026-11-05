# Des autocollants pour les espèces d'oiseaux actuelles du monde

<img src="previews/header.webp" alt="huashu-bird-sticker: specimen drawer, body-size lineup and family plates" width="100%">

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · **Français** · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

<a href="https://birdalbum.com/fr/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker"><img src="previews/birdalbum.webp" alt="Bird Album : tous les oiseaux du monde, un autocollant pour chacun. birdalbum.com" width="100%"></a>

**Découvrez toute la bibliothèque en situation sur [birdalbum.com](https://birdalbum.com/fr/?utm_source=github&utm_medium=readme&utm_campaign=bird-sticker).** Bird Album est un guide des oiseaux gratuit construit sur ces autocollants : cherchez n'importe quelle espèce par son nom dans 15 langues, voyez où elle vit et à quels mois on peut la croiser, et ouvrez une carte de 8 171 sites d'observation qui montre ce que les gens observent ce mois-ci à chacun.

11 011 espèces d'oiseaux réparties en 45 ordres et 249 familles, d'après [AviList v2026](https://www.avilist.org/), la liste mondiale unifiée qui a remplacé en 2025 les listes de l'IOC et de Clements. Toutes les espèces vivantes sont incluses, plus 43 qu'AviList signale comme éteintes, éteintes à l'état sauvage ou possiblement éteintes mais qui avaient déjà un autocollant (voir `extinctionStatus`). 10 973 espèces ont un autocollant ; les 38 autres ont été scindées récemment et sont en cours de dessin. Chaque espèce est accompagnée de données structurées : taxonomie, noms dans jusqu'à 43 langues, identifiants dans d'autres bases de données et provenance de chaque autocollant.

> **La version 2.0 a fait passer la taxonomie de l'IOC 15.2 à AviList v2026.** 82 espèces ont changé de nom scientifique (donc d'`id` et de chemin d'autocollant), 91 anciennes espèces sont désormais des sous-espèces d'une autre espèce et 30 nouvelles espèces ont été scindées. Tous les changements sont listés dans [`data/crosswalk-ioc15.2-avilist2026.csv`](data/crosswalk-ioc15.2-avilist2026.csv), et chaque fiche conserve son ancien identifiant IOC dans `previous`. Voir le [CHANGELOG](CHANGELOG.md).

![40 autocollants de 15 ordres d’oiseaux](previews/hero.webp)

**Licence en bref :** les autocollants sont sous licence [CC BY 4.0](LICENSE.md) : vous pouvez les utiliser pour tout, y compris en usage commercial, les modifier et les redistribuer, à condition de citer huashu-bird-sticker avec un lien vers ce dépôt. Les données sont sous licence MIT, et les éléments provenant de tiers sont listés dans [NOTICE](NOTICE.md).

## Galerie

Dix-huit des groupes les plus colorés et les plus caractéristiques, 24 autocollants pour chacun, choisis pour que deux d'entre eux ne se ressemblent jamais. Tous les autocollants montrés ici atteignent le seuil de qualité.

### Colibris · *Trochilidae* — 361 espèces

![Colibris](previews/families/trochilidae.webp)

### Perroquets et cacatoès · *Psittaciformes* — 391 espèces

![Perroquets et cacatoès](previews/families/parrots.webp)

### Martins-pêcheurs · *Alcedinidae* — 123 espèces

![Martins-pêcheurs](previews/families/alcedinidae.webp)

### Guêpiers, rolliers et motmots · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 69 espèces

![Guêpiers, rolliers et motmots](previews/families/coraciiformes.webp)

### Toucans et barbus · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 132 espèces

![Toucans et barbus](previews/families/toucans.webp)

### Paradisiers et jardiniers · *Paradisaeidae* · *Ptilonorhynchidae* — 67 espèces

![Paradisiers et jardiniers](previews/families/paradisaeidae.webp)

### Brèves · *Pittidae* — 46 espèces

![Brèves](previews/families/pittidae.webp)

### Tangaras · *Thraupidae* — 392 espèces

![Tangaras](previews/families/thraupidae.webp)

### Soui-mangas et dicées · *Nectariniidae* · *Dicaeidae* — 207 espèces

![Soui-mangas et dicées](previews/families/nectariniidae.webp)

### Cotingas et manakins · *Cotingidae* · *Pipridae* — 120 espèces

![Cotingas et manakins](previews/families/cotingas.webp)

### Faisans et perdrix · *Phasianidae* — 185 espèces

![Faisans et perdrix](previews/families/phasianidae.webp)

### Canards, oies et cygnes · *Anatidae* — 164 espèces

![Canards, oies et cygnes](previews/families/anatidae.webp)

### Pigeons et tourterelles · *Columbidae* — 338 espèces

![Pigeons et tourterelles](previews/families/columbidae.webp)

### Astrilds et capucins · *Estrildidae* — 138 espèces

![Astrilds et capucins](previews/families/estrildidae.webp)

### Geais et pies · *Corvidae* — 135 espèces

![Geais et pies](previews/families/corvidae.webp)

### Ictéridés du Nouveau Monde (carouges, orioles, caciques) · *Icteridae* — 107 espèces

![Ictéridés du Nouveau Monde (carouges, orioles, caciques)](previews/families/icteridae.webp)

### Calaos · *Bucerotidae* — 64 espèces

![Calaos](previews/families/bucerotidae.webp)

### Étourneaux et mainates · *Sturnidae* — 118 espèces

![Étourneaux et mainates](previews/families/sturnidae.webp)

### Un de chaque ordre

![Un de chaque ordre](previews/orders.webp)

## Contenu

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | Un autocollant transparent avec contour blanc par espèce, d'environ 1 000 px sur le grand côté. Les `<Genus_species>.<subspecies>.webp` sont 91 autocollants supplémentaires de sous-espèces qui étaient auparavant des espèces distinctes |
| `data/species.json` | Une fiche par espèce, le jeu de données complet : taxonomie, noms, identifiants, aire de répartition et sous-espèces, mesures corporelles et écologie, statut de conservation, autocollant et sa provenance. Description des champs : [data/README.md](data/README.md) |
| `data/crosswalk-ioc15.2-avilist2026.csv` | Comment chaque espèce de l'IOC 15.2 correspond à AviList v2026 : identique, renommée, regroupée, scindée |
| `data/species.csv` | La même chose, mise à plat pour les tableurs |
| `data/names.csv` | Les noms dans 43 langues (46 colonnes : le chinois, le français et le portugais ont chacun deux variantes) |
| `data/languages.json` | Les codes de langue et la colonne multilingue de l'IOC dont chacun provient |
| `data/field-guide.zh-Hans.json` | Notes de guide de terrain en chinois simplifié (aspect, critères de terrain, sexes et âges, espèces proches) pour 1 596 espèces, CC BY-SA 4.0 |

Voici à quoi ressemble une fiche (noms abrégés) :

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

## Couverture

- Noms : l'anglais (AviList) couvre toutes les espèces. Les autres langues viennent de la liste multilingue de l'IOC et ne sont conservées que là où le concept d'espèce n'a pas changé ; pour les 129 espèces dont les limites ont changé (regroupements et scissions) ou qui sont nouvelles, un ancien nom peut désigner un autre ensemble d'oiseaux, nous l'avons donc omis plutôt que de deviner. Le chinois simplifié couvre 10 947 espèces (chaque espèce modifiée a été vérifiée à la main) ; le français, l'espagnol, l'allemand, le russe, le japonais et le chinois traditionnel dépassent 94 %. Le coréen, l'arabe, le thaï, le persan et quelques autres ne couvrent que de quelques centaines à environ mille espèces, car c'est ce que contient la liste de l'IOC. Voir `data/names.csv`.
- Identifiants : eBird 10 983 et Avibase 11 011, tous deux repris d'AviList ; Wikidata 10 757, GBIF 10 477.
- Autocollants : 10 973 sur 11 011 espèces, plus 91 autocollants de sous-espèces. Les 38 espèces qui n'en ont pas encore sont listées avec `"sticker": null`.

## Comment les autocollants ont été faits, et leur qualité

Les 11 064 fichiers d'autocollants sont des illustrations générées par IA. Pour chaque espèce, nous avons trouvé une photo de référence (ou, pour les 453 espèces où aucune photo seule n'était assez bonne, une planche de plusieurs images accompagnée d'une description écrite), dessiné l'autocollant avec GPT-image, l'avons agrandi puis détouré.

Chaque autocollant IA a ensuite été noté par un relecteur distinct, en le comparant à la référence sur les critères de terrain : bec, œil, pattes et pieds, motif et couleur du plumage. Au dernier tour, 852 autocollants limites (80–82) ont en plus subi une seconde relecture en aveugle ; 211 d'entre eux l'ont échouée et ont été redessinés. Les autocollants limites des tours précédents n'ont pas eu cette seconde relecture. En novembre 2026, nous avons réexaminé les autocollants selon un critère plus strict, comme des planches de guide de terrain, et en avons redessiné 6 804. Un autocollant redessiné ne réussit la relecture que si chacun des cinq critères — identification, plumage, bec et œil, pattes et pieds, proportions — obtient au moins 3 sur 4, si l'identification obtient 4 et si le relecteur l'accepterait comme planche de guide de terrain.

- **10 870 atteignent notre seuil de qualité** (`"meetsQualityBar": true`) : les autocollants qui ont réussi la relecture plus stricte décrite ci-dessus ou ont obtenu une note de 80 ou plus lors de la relecture précédente.
- **194 ne l'atteignent pas.** Nous avons gardé la version la mieux notée pour qu'aucune espèce ne reste sans image : 190 sont notés entre 70 et 79 et 4 en dessous de 70. Nous sommes en train de les redessiner ; voir le [ticket n° 1](../../issues/1) et le [ticket n° 3](../../issues/3) pour les types d'erreurs que nous corrigeons.

Ce sont des illustrations, pas des planches de guide de terrain. Voyez-les comme une image sympathique de l'oiseau, et consultez un guide de terrain avant de vous fier à un détail fin. Si vous repérez une erreur, [ouvrez un ticket](../../issues/new/choose) : les corrections des ornithologues amateurs sont la contribution la plus précieuse que ce projet puisse recevoir.

## À propos des photos de référence

**À quoi sert une référence.** Un autocollant montre à quoi ressemble une espèce : les couleurs et les motifs du plumage, le bec, l'œil, les pattes et les proportions. Ce sont des faits sur l'oiseau, les mêmes qu'un guide de terrain décrit avec des mots. Une description écrite ne suffit souvent pas au modèle d'image pour les rendre correctement ; nous utilisons donc des photos de référence.

**Comment nous l'utilisons.** Pour chaque espèce, on montre au modèle d'image une ou plusieurs photos de référence avec une description écrite des critères d'identification, et il dessine une nouvelle illustration. Nous ne reprenons ni la composition, ni l'arrière-plan, ni la lumière de la photo : les autocollants redessinés depuis novembre 2026 adoptent tous la même posture de profil standard, fixée par nous, sur un fond uni, quelle que soit l'attitude de l'oiseau sur la photo. Un relecteur distinct vérifie ensuite le dessin au regard des critères d'identification. Désormais, nous utilisons autant que possible des photos de plusieurs observateurs pour chaque espèce, afin qu'un autocollant reflète l'espèce plutôt qu'une image en particulier. Ce dépôt ne contient aucune photo de référence.

**Crédits et retrait.** Les photos de référence de chaque autocollant (page, auteur et licence) sont listées dans `sticker.reference`, dans `data/species.json` : chaque autocollant peut donc être relié à ses sources. Une répartition selon la licence des photos de référence se trouve dans [data/README.md](data/README.md#reference-photos). Si l'une de vos photos a servi de référence et que vous préférez qu'elle ne le soit pas, ouvrez un ticket ou écrivez à alchaincyf@gmail.com : nous remplacerons l'autocollant sous 7 jours.

## Utilisation

Les fichiers bruts peuvent être chargés directement :

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

Le dépôt pèse environ 700 Mo. Pour ne récupérer que les données et quelques autocollants :

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## Crédits

- Taxonomie, noms anglais, aires de répartition et identifiants eBird et Avibase : AviList Core Team. 2026. AviList: The Global Avian Checklist, v2026. https://doi.org/10.2173/avilist.v2026, CC BY 4.0.
- Noms dans les autres langues : IOC World Bird List v15.2, Gill, Donsker et Rasmussen (dir.), CC BY 3.0.
- Autres identifiants entre bases de données : Wikidata (CC0).
- Mesures corporelles et écologie : AVONET, Tobias et al., 2022, *Ecology Letters*, CC BY 4.0.
- Photographes des images de référence : mentionnés espèce par espèce dans `data/species.json`. Les photos de référence ne sont pas incluses dans ce dépôt.
- Autocollants dessinés pour 鸣迹 (Mingji), un carnet d'observation des oiseaux pour iOS.

Si l'une de vos photos a servi de référence pour un autocollant et que vous préférez qu'elle ne le soit pas, ouvrez un ticket ou écrivez à alchaincyf@gmail.com : nous remplacerons l'autocollant sous 7 jours.
