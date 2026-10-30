# 현생 조류 11,064종 전부의 스티커

[English](README.md) · [简体中文](README.zh-Hans.md) · [繁體中文](README.zh-Hant.md) · [日本語](README.ja.md) · **한국어** · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Русский](README.ru.md) · [العربية](README.ar.md)

새 11,064종, 종마다 스티커 한 장, 44개 목 250개 과에 걸쳐 있습니다. IOC World Bird List v15.2의 현생종 전부에 해당합니다(멸종한 163종은 포함하지 않았습니다). 각 종에는 분류, 최대 43개 언어의 이름, 여러 데이터베이스의 ID, 스티커별 출처 같은 구조화된 데이터가 함께 들어 있습니다.

![15개 목에서 고른 스티커 40장](previews/hero.webp)

스티커는 [PolyForm Shield 1.0.0](LICENSE.md)에 따라 상업적 이용을 포함해 거의 모든 용도로 자유롭게 쓸 수 있습니다. 금지되는 것은 단 하나, 우리 탐조 앱과 경쟁하는 제품(다른 탐조, 새 식별, 도감 앱이나 사이트)에 쓰는 일입니다. 데이터는 MIT입니다. 제3자에게서 온 부분은 [NOTICE](NOTICE.md)를, 참고 사진에 관해서는 아래 「참고 사진 안내」를 읽어 주세요.

## 갤러리

가장 색이 화려하고 특징 있는 18개 무리를 무리마다 24장씩, 서로 비슷해 보이지 않도록 골랐습니다. 여기 실린 스티커는 모두 품질 기준을 충족합니다.

### 벌새 · *Trochilidae* — 365 종

![벌새](previews/families/trochilidae.webp)

### 앵무와 코카투 · *Psittaciformes* — 392 종

![앵무와 코카투](previews/families/parrots.webp)

### 물총새 · *Alcedinidae* — 116 종

![물총새](previews/families/alcedinidae.webp)

### 벌잡이새·파랑샛과·모트모트 · *Meropidae* · *Coraciidae* · *Brachypteraciidae* · *Momotidae* · *Todidae* — 68 종

![벌잡이새·파랑샛과·모트모트](previews/families/coraciiformes.webp)

### 큰부리새와 바벳 · *Ramphastidae* · *Capitonidae* · *Semnornithidae* · *Megalaimidae* · *Lybiidae* — 134 종

![큰부리새와 바벳](previews/families/toucans.webp)

### 극락조와 바우어새 · *Paradisaeidae* · *Ptilonorhynchidae* — 69 종

![극락조와 바우어새](previews/families/paradisaeidae.webp)

### 팔색조 · *Pittidae* — 46 종

![팔색조](previews/families/pittidae.webp)

### 풍금조 · *Thraupidae* — 393 종

![풍금조](previews/families/thraupidae.webp)

### 태양새와 꽃쪼기새 · *Nectariniidae* · *Dicaeidae* — 208 종

![태양새와 꽃쪼기새](previews/families/nectariniidae.webp)

### 코팅가와 마나킨 · *Cotingidae* · *Pipridae* — 121 종

![코팅가와 마나킨](previews/families/cotingas.webp)

### 꿩과 자고새 · *Phasianidae* — 185 종

![꿩과 자고새](previews/families/phasianidae.webp)

### 오리·기러기·고니 · *Anatidae* — 166 종

![오리·기러기·고니](previews/families/anatidae.webp)

### 비둘기 · *Columbidae* — 339 종

![비둘기](previews/families/columbidae.webp)

### 납부리새 · *Estrildidae* — 140 종

![납부리새](previews/families/estrildidae.webp)

### 어치와 까치 · *Corvidae* — 138 종

![어치와 까치](previews/families/corvidae.webp)

### 신대륙 꾀꼬리·오로펜돌라 · *Icteridae* — 107 종

![신대륙 꾀꼬리·오로펜돌라](previews/families/icteridae.webp)

### 코뿔새 · *Bucerotidae* — 64 종

![코뿔새](previews/families/bucerotidae.webp)

### 찌르레기와 구관조 · *Sturnidae* — 120 종

![찌르레기와 구관조](previews/families/sturnidae.webp)

### 44개 목에서 한 장씩

![44개 목에서 한 장씩](previews/orders.webp)

## 구성

| | |
|---|---|
| `stickers/<Order>/<Family>/<Genus_species>.webp` | 흰 테두리가 있는 투명 스티커 11,064장, 긴 변 기준 약 1,000 px |
| `data/species.json` | 종마다 레코드 하나, 전체 데이터셋. 분류, 이름, ID, 분포와 아종, 신체 측정값과 생태, 보전 상태, 스티커와 그 출처가 들어 있습니다. 필드 설명은 [data/README.md](data/README.md) |
| `data/species.csv` | 같은 내용을 스프레드시트용으로 평평하게 편 것 |
| `data/names.csv` | 43개 언어의 이름(46개 열: 중국어, 프랑스어, 포르투갈어는 각각 두 가지 변종이 있음) |
| `data/languages.json` | 언어 코드와, 각 언어가 IOC 표의 어느 열에서 왔는지 |
| `data/field-guide.zh-Hans.json` | 1,596종에 대한 중국어 간체 도감 해설(생김새, 식별 특징, 성별·연령, 비슷한 종), CC BY-SA 4.0 |

레코드는 이런 모양입니다(이름은 줄임).

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

## 포함 범위

- 이름: 영어는 모든 종을 포함하고, 프랑스어와 중국어 간체도 몇 종을 뺀 모두를 포함합니다(중국어 간체에는 최근 분할된 23종의 이름이 아직 없습니다). 일본어, 중국어 번체, 러시아어, 독일어, 스페인어, 폴란드어, 네덜란드어, 스웨덴어를 비롯해 십여 개 유럽 언어가 90%를 넘습니다. 세르비아어, 헝가리어, 에스토니아어는 50~75%입니다. 한국어, 아랍어, 태국어, 페르시아어 등은 IOC 목록에 있는 만큼만 담겨 있어서 아직은 수백 종에서 1,000종 안팎입니다. 자세한 내용은 `data/names.csv`를 보세요.
- 한국어 이름은 11,064종 중 566종에만 있어 아직 적습니다. 보태 주시는 기여를 환영합니다.
- ID: Wikidata 10,939, GBIF 10,649, eBird 10,052.
- 스티커: 11,064종 중 11,064종.

## 스티커를 만든 방법과 품질

11,030장은 AI 일러스트입니다. 종마다 참고 사진을 찾고(사진 한 장으로 충분하지 않은 453종은 여러 이미지를 모은 참고판과 글로 된 설명을 사용), GPT-image로 스티커를 그린 뒤 해상도를 키우고 오려 냈습니다. 34장은 실제 사진에서 오려 낸 것이며, 원본 사진과 대조하는 블라인드 검수를 통과했습니다.

모든 AI 스티커는 이후 별도의 검수자가 참고 자료와 대조해 야외 식별 특징을 채점했습니다. 부리, 눈, 다리와 발, 깃털의 색과 무늬입니다. 마지막 라운드에서는 경계선(80~82점)의 스티커 852장이 블라인드로 한 번 더 검수를 받았고, 그중 211장이 탈락해 다시 그렸습니다. 이전 라운드의 경계선 스티커는 이 두 번째 검수를 받지 않았습니다.

- **7,676장이 품질 기준을 충족합니다**(`"meetsQualityBar": true`). 80점 이상의 AI 스티커와 사진에서 오려 낸 34장입니다.
- **3,388장은 충족하지 못합니다.** 다시 그리기 한도까지 반복한 뒤 가장 높은 점수의 버전을 남겼습니다. 그림이 없는 종이 생기지 않게 하기 위해서입니다. 3,273장은 70~79점, 109장은 70점 미만이며, 6장은 80점 이상이었으나 블라인드 2차 검수에서 탈락했습니다.

이것은 일러스트이지 도감의 도판이 아닙니다. 새의 모습을 친근하게 보여 주는 그림으로 보시고, 세부 특징에 의존할 때는 도감으로 확인해 주세요. 잘못된 부분을 발견하면 [이슈를 열어](../../issues/new/choose) 주세요. 탐조인의 정정은 이 프로젝트가 받을 수 있는 가장 값진 기여입니다.

## 참고 사진 안내

각 스티커의 참고 자료는 `sticker.reference`에 페이지, 작자, 라이선스와 함께 적혀 있습니다. 종 수 기준(AI 스티커)으로 나누면 다음과 같습니다.

| 참고 자료 | 종 수 |
|---|---|
| 공개 라이선스 사진(CC0, 퍼블릭 도메인, CC BY, CC BY-SA) | 1,986 |
| 공개 라이선스 이미지로 만든 참고판, 또는 글 설명만 있는 경우 | 46 |
| 비영리 또는 변경 금지 라이선스의 사진(CC BY-NC, -ND 등) | 5,071 |
| 모든 권리 보유 사진, 또는 Macaulay Library 약관이 적용되는 사진 | 1,500 |
| 라이선스를 기록하지 않은 사진 | 2,017 |
| 조건이 다른 이미지가 섞인 참고판 | 410 |

스티커는 새로 그린 그림이며 복제본이 아니고, 참고 사진은 이 저장소에서 배포하지 않습니다. 사진을 보고 그린 그림이 그 사진의 라이선스에 구속되는지는 법적으로 아직 정리되지 않았습니다. 사용 목적상 중요하다면 `sticker.reference.license`로 걸러서 쓰세요.

## 사용하기

원본 파일은 바로 불러올 수 있습니다.

```
https://raw.githubusercontent.com/alchaincyf/huashu-bird-sticker/main/stickers/Accipitriformes/Accipitridae/Accipiter_nisus.webp
```

```python
import json
species = json.load(open("data/species.json"))["species"]
by_name = {s["scientificName"]: s for s in species}
print(by_name["Pica pica"]["names"]["ja"], by_name["Pica pica"]["sticker"]["file"])
```

저장소 전체는 약 700 MB입니다. 데이터와 일부 스티커만 받으려면 다음과 같이 합니다.

```bash
git clone --filter=blob:none --sparse https://github.com/alchaincyf/huashu-bird-sticker
cd huashu-bird-sticker && git sparse-checkout set data stickers/Strigiformes
```

## 출처 표기

- 분류와 다국어 이름: IOC World Bird List v15.2, Gill, Donsker & Rasmussen(편), CC BY 3.0.
- 데이터베이스 간 ID: Wikidata(CC0).
- 신체 측정값과 생태: AVONET, Tobias 외, 2022, *Ecology Letters*, CC BY 4.0.
- 참고 사진 촬영자: 종별로 `data/species.json`에 표기했습니다. 참고 사진은 이 저장소에 포함되어 있지 않습니다.
- 스티커는 iOS용 탐조 기록 앱 鸣迹(Mingji)를 위해 그렸습니다.

어떤 스티커가 당신의 사진을 바탕으로 만들어졌고 그것을 원하지 않는다면, 이슈를 열거나 alchaincyf@gmail.com으로 메일을 보내 주세요. 7일 안에 교체하거나 삭제하겠습니다.
