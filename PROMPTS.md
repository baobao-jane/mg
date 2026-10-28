# 「마교가 망했다, 말단 서기인 내가 살린다」 이미지 제작 지시서

> **이 작품은 동양 무협 판타지(고대 중국풍)다. 모든 이미지의 건물·옷·물건·문서는 동양식으로 그린다. 서양 판타지(가죽 책, 양피지, 밀랍 봉인, 중세 성·감옥, 카지노 등)는 절대 쓰지 않는다. 문서·책·간판에는 읽을 수 있는 글자를 넣지 않고, 흐릿한 세로 붓자국이나 빈 종이로만 그린다.**

이 파일은 Cursor 에이전트가 읽고 이미지를 만드는 지시서다. 아래 규칙을 지키며 맨 아래 체크리스트 순서대로 만든다. 한 번에 10장 안팎씩 만들고, 만든 파일은 체크리스트에 [x]로 표시한다.

## 1. 작업 규칙

- 저장 위치: 이 저장소(`mg`)의 `ref/`, `c/`, `p/`, `s/`, `i/` 폴더. 상세 설명용 `d/`는 작업용(크랙 내부 이미지로 올림). 파일명은 체크리스트에 적힌 그대로 쓴다. 인물은 `c/인물코드/번호.webp`, 장소·상황·소품은 `p/번호.webp`처럼 번호로 쓴다.
- 형식: webp. 한 장 300KB 안팎.
- 크기
  - `ref/` 캐릭터 시트: 가로 3:2, 흰 배경.
  - `c/` 캐릭터: 세로 2:3 (예: 1080×1620), 상반신, 인물 한 명만.
  - `p/` 장소, `s/` 상황: 가로 16:9 (예: 1280×720).
  - `i/` 소품: 정사각 1:1 (예: 768×768), 소품 하나만, 단순한 배경.
- 순서
  1. **캐릭터 시트부터 만든다 (13장, 우강·백무현 시트는 다시 만든다).** 공통 스타일 + 인물 설명 + "3-1. 캐릭터 시트 문구"로 `ref/인물_sheet.webp`를 만든다. 사용자가 마음에 드는 시트를 고를 때까지 다음 단계로 넘어가지 않는다.
  2. **캐릭터 이미지(`c/`)는 반드시 그 인물의 시트를 첨부(참조)하고**, 앞에 "인물 고정 문구"를 붙여 만든다.
  3. 인물이 없는 장소·소품 이미지는 아무 시트나 하나를 화풍 참고로만 첨부하고 "풍경 고정 문구"를 붙인다.
  4. 여러 명이 나오는 상황 이미지는 등장하는 인물의 시트를 첨부한다. 한 장에 시트를 여러 개 반영하면 얼굴이 섞일 수 있으니, 어긋난 인물은 한 명씩 고친다.
  6. **이름 없는 사람(순찰대, 토벌대, 사파 부하, 장터 사람, 교도 무리)은 모두 얼굴·나이·체격·머리 모양을 서로 다르게 그린다.** 주요 인물(백무현, 사공휘 등)의 얼굴을 복사하지 않는다. 그 장면에 주요 인물이 직접 나오지 않으면 그 인물의 시트를 첨부하지 않고, 화풍 참고용으로 장소 이미지(p/)를 첨부한다.
  5. 얼굴이나 옷이 시트와 달라지면 "일관성이 깨졌을 때" 문구로 한 가지씩 고친다.
- 모든 프롬프트 앞에 아래 "2. 공통 스타일"을 붙인다.
- `ref/` 시트는 크랙에서 쓰지 않는 작업용이다. 저장소에 올려도 되고 컴퓨터에만 둬도 된다.
- 이미지 안에 글자, 말풍선, 서명, 워터마크를 넣지 않는다.
- 주인공(재무당 서기)은 성별을 정하지 않은 인물이다. 얼굴을 그리지 않는다. 꼭 필요하면 손이나 뒷모습만 그린다.
- 피와 상처는 약하게 표현한다. 잔인한 묘사, 노출, 선정적 묘사를 하지 않는다.
- 진아린은 16세다. 나이에 맞게, 수수하고 단정하게 그린다.
- 다 만든 뒤 add, commit, push 한다.

## 2. 공통 스타일 (모든 프롬프트 앞에 붙인다)

```
Bright Korean wuxia webtoon style, clean bold lineart, soft cel shading, warm vivid colors, expressive faces, ancient Chinese martial-arts world (murim), all objects, clothes and buildings in ancient East Asian style, no Western fantasy elements, consistent character design, high quality illustration, no text, no letters or characters anywhere (documents and books show only faint unreadable brush strokes or blank paper), no speech bubbles, no watermark, no gore.
```

- 캐릭터(`c/`)에 더 붙이는 문구: `upper body portrait, single character, facing viewer, simple soft background in the character's theme color`
- 장소(`p/`)에 더 붙이는 문구: `wide establishing shot, background art, ancient Chinese architecture and props only, no Western fantasy or medieval European elements, no people or only tiny distant figures`
- 상황(`s/`)에 더 붙이는 문구: `wide cinematic scene, characters small to medium in frame, ancient Chinese setting and clothing (hanfu), no Western fantasy elements`
- 소품(`i/`)에 더 붙이는 문구: `single object, centered, item illustration, plain light background, ancient East Asian (Chinese wuxia era) object, traditional materials like hanji paper, bamboo, wood, jade, bronze, no Western fantasy style, no leather-bound books, no parchment, no wax seals`

## 3. 인물 기준 설명 (13명)

인물 이미지마다 이 설명을 그대로 넣는다.

| 코드 | 인물    | 설명 (프롬프트용)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---- | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| dan  | 단도원  | Dan Dowon, man, 31, tall, short tied black hair, dark gray eyes, scarred hands, worn black martial-arts robe, sword with red cord wrapped on the hilt, stern and serious face, theme color dark crimson                                                                                                                                                                                                                                                                                                                                               |
| seo  | 서은결  | Seo Eungyeol, woman, 28, long dark blue-black hair in a single braid, pale lilac eyes, pale skin, always wearing gloves, white physician's outer robe, cool cynical expression, theme color light purple                                                                                                                                                                                                                                                                                                                                              |
| heo  | 허류    | Heo Ryu, man, 27, slim, messy brown hair half tied up, amber eyes, flashy silk outer robe over black fitted clothes, gold earrings, sly grin, theme color crimson red                                                                                                                                                                                                                                                                                                                                                                                 |
| myo  | 묘연    | Myoyeon, woman, 25, long pale pink hair, gray eyes, theatrical troupe costume, folding fan, red makeup at the corners of the eyes, playful look, theme color pink                                                                                                                                                                                                                                                                                                                                                                                     |
| ma   | 마대산  | Ma Daesan, man, 26, huge muscular build, buzz-cut reddish brown hair, brown eyes, sleeveless martial-arts outfit, bandaged bare arms, simple honest face, theme color orange                                                                                                                                                                                                                                                                                                                                                                          |
| seok | 석란    | Seok Ran, woman, 23, small build, ash-white bob hair, deep green eyes, dirt-stained gray Taoist robe, small flags and stones for formations at her waist, expressionless quiet face, theme color moss green                                                                                                                                                                                                                                                                                                                                           |
| jin  | 진아린  | Jin Arin, girl, 16, short black hair with a white hair ribbon, clear sky-blue eyes, black clothes of an unorthodox sect with long sleeves, small talisman tucked in her robe, wary look, modest and age-appropriate, theme color sky blue                                                                                                                                                                                                                                                                                                             |
| ok   | 옥 할멈 | Granny Ok, woman, late 60s, graying hair in a bun with one hairpin, small sharp eyes, slightly bent back, oil-stained apron, ladle tucked in her belt, tough but warm grandmother, theme color dark brown                                                                                                                                                                                                                                                                                                                                             |
| wu   | 우강    | Woo Gang, handsome man, 34, tall and well-built, sharp jawline, defined features, short neat black hair, calm dark brown eyes with clearly visible pupils and light reflections (not solid black, not like sunglasses), worn cult-member martial robe, leather wrist guards, large saber on his back, quiet and reserved but dependable look, theme color ink gray                                                                                                                                                                                    |
| so   | 소칠    | So Chil, young man, 19, skinny, messy brown hair under a headband, lively brown eyes, peddler's clothes, backpack frame and a well-worn abacus, chatty friendly look, theme color mustard yellow                                                                                                                                                                                                                                                                                                                                                      |
| baek | 백무현  | Baek Muhyeon, man, 35, slender and elegant build, long straight black hair falling loose past the shoulders with only the top part held by a small silver hair crown, sharp narrow eyes in deep navy blue with visible pupils, fair skin, refined noble face with thin lips and no scars, upright posture, flowing white martial robe with a blue sash, orthodox alliance token at his waist, principled cold look, theme colors white and blue. Must look clearly different from Dan Dowon (who has short tied hair, gray eyes, rugged scarred look) |
| sa   | 사공휘  | Sagong Hwi, man, 29, slender, sleek slicked-back black hair, golden eyes that narrow when he smiles, black silk robe with gold thread embroidery, three gold rings on his fingers, gentle but calculating smile, theme color gold                                                                                                                                                                                                                                                                                                                     |
| eom  | 엄상    | Elder Eom Sang, man, early 60s, neatly groomed white beard, thin eyes that look kind, tidy elder's long robe, prayer beads in his hand, gentle smile hiding cunning, theme color navy                                                                                                                                                                                                                                                                                                                                                                 |

### 3-1. 캐릭터 시트 문구 (`ref/`, 인물마다 1장)

공통 스타일 + 인물 설명 + 아래 문구.

```
Character design sheet on a plain white background. The same character shown twice side by side: full-body front view and full-body side view. Clothes, accessories and hairstyle must be identical in both views. Default expression. No text, no watermark.
```

### 3-2. 고정 문구

**인물 고정 문구** (`c/` 이미지 프롬프트 앞에 붙인다. 그 인물의 시트를 첨부한다)

```
Keep the exact art style and character design of the attached character sheet. Do not change the face, hairstyle, clothes or accessories. Bright Korean wuxia webtoon style, clean bold lineart, soft cel shading. Vertical 2:3. No text, no watermark.
```

**풍경 고정 문구** (인물이 없는 `p/`, `i/` 이미지 앞에 붙인다. 시트는 화풍 참고로만 첨부한다)

```
Use the attached image only as an art style reference. Do not draw any characters from it. Bright Korean wuxia webtoon style, clean bold lineart, soft cel shading, warm vivid colors. No text, no watermark.
```

**일관성이 깨졌을 때**

```
In the last image, [바뀐 부분] is different from the attached character sheet. Keep everything else the same and fix only [바뀐 부분] to match the sheet exactly.
```

## 4. 인물 이미지 번호 (`c/인물코드/번호.webp`)

| 번호 | 감정               | 프롬프트용                                                                                                        |
| ---- | ------------------ | ----------------------------------------------------------------------------------------------------------------- |
| 1    | 기본               | neutral default expression, calm pose                                                                             |
| 2    | 웃음               | smiling happily, relaxed                                                                                          |
| 3    | 화남               | angry, frowning, tense                                                                                            |
| 4    | 슬픔               | sad, downcast eyes                                                                                                |
| 5    | 놀람               | shocked, wide eyes, mouth open                                                                                    |
| 6    | 당황               | flustered, sweating, awkward                                                                                      |
| 7    | 진지               | grave and serious, determined eyes                                                                                |
| 8    | 심마 (제자 여섯만) | 아래 "심마 장면" 참고                                                                                             |
| 9    | 변장 (묘연만)      | Myoyeon in disguise as a different stage character, different hair and makeup, but same gray eyes and folding fan |

- 석란은 감정이 얼굴에 거의 드러나지 않는 인물이다. 표정 변화를 작게 하고, 눈썹과 눈빛으로만 구분한다.
- 사공휘와 엄상은 웃는 얼굴에도 속셈이 보이게 한다.

**심마 장면 (8번)**

| 파일          | 내용 (프롬프트용)                                                                                    |
| ------------- | ---------------------------------------------------------------------------------------------------- |
| c/dan/8.webp  | dark crimson killing aura leaking from his body, eyes glowing faintly red, people around would choke |
| c/seo/8.webp  | plants and objects near her hands withering and turning purple, poison mist, pained face             |
| c/heo/8.webp  | coughing a small amount of blood, collapsing to one knee, crimson shadows around him (mild, no gore) |
| c/myo/8.webp  | confused face, multiple faint ghostly masks floating around her, unsure who she is                   |
| c/ma/8.webp   | furious, veins glowing orange, smashing wooden furniture                                             |
| c/seok/8.webp | trapped inside her own glowing formation circle of flags and stones, unable to move                  |

## 5. 장소 (`p/번호.webp`, 15장)

| 파일      | 이름              | 프롬프트용                                                                                                                                                |
| --------- | ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| p/1.webp | 본산 1단계 (폐허) | ruined ancient Chinese mountain sect headquarters of a demonic cult, wooden palace halls with curved tiled roofs and red pillars, burnt main hall with half the roof tiles gone, collapsed paifang-style main gate, stone steps and stone lanterns, ash and rubble, gloomy but not horror |
| p/2.webp | 본산 2단계 | the same Chinese mountain headquarters partly repaired, a few halls with new grey roof tiles, bamboo scaffolding, workers' wooden tools, piles of timber and tiles |
| p/3.webp | 본산 3단계 | the same Chinese mountain headquarters mostly rebuilt, stone-paved martial training courtyard and wooden living quarters ready, long cloth banners being hung on poles |
| p/4.webp | 본산 4단계 | the same Chinese mountain headquarters fully restored and grand, red pillars and gold-trimmed curved roofs, rows of red paper lanterns, stone courtyard prepared for a ceremony |
| p/5.webp | 재무당 금고 | small finance office of the cult in ancient Chinese style, one standing pillar, empty wooden treasure chest with brass fittings, piles of thread-bound ledgers, an abacus on a low wooden desk |
| p/6.webp | 주방 | warm old Chinese kitchen in the ruins, earthen brick stove with big iron woks, bamboo steamers releasing steam, firewood, clay jars, the only cozy place in the ruins |
| p/7.webp | 밤의 정문 | the broken Chinese-style main gate of the sect at night, wooden gate with curved tiled roof, moonlight, long shadows, quiet and suspicious mood |
| p/8.webp | 장터 | busy ancient Chinese village market street, wooden stalls under cloth awnings, baskets of herbs, salt and bolts of cloth, hanging paper lanterns, lively crowd in hanfu |
| p/9.webp | 사파 방회 | luxurious hall of an unorthodox sect gang in ancient Chinese style, dark lacquered wood, gold carvings, folding screens, red lanterns, low tables where men play dice in bowls and Chinese gambling games with bamboo tallies and copper coins, guards in black, no Western casino, no cards, no roulette |
| p/10.webp | 정파 감옥 | ancient Chinese government prison of the orthodox alliance, thick wooden cell bars, rough earthen walls, straw on the floor, oil lamp light, no medieval European dungeon |
| p/11.webp | 남쪽 마을 의원 | small ancient Chinese clinic in a southern village, wooden medicine cabinet with many small drawers, herbs drying on bamboo trays, a low table with acupuncture needles |
| p/12.webp | 밀수 나루터 | night river ferry dock in ancient China for smuggling, wooden piers, small flat-bottomed wooden boats with bamboo awnings, stacked wooden crates and straw sacks, paper lanterns |
| p/13.webp | 극단 무대 | traveling Chinese opera troupe stage in a village square, wooden open-air stage with curved roof, red and gold curtains, painted opera masks and costumes |
| p/14.webp | 내기 격투장 | underground betting fight pit in ancient China, a dirt and stone sunken circle surrounded by wooden railings, shouting crowd in hanfu waving copper coins, torches, broken iron pieces on the ground, no Western boxing ring, no ropes |
| p/15.webp | 산골 오두막 | lonely thatched-roof mountain hut deep in a misty East Asian pine forest, stone formation markers and small flags around it |

- 1~4는 같은 장소다. 구도와 산 모양을 똑같이 두고 복구 정도만 바꾼다. 1을 먼저 만들고 나머지는 1을 참고한다.

## 6. 상황 (`s/번호.webp`, 9장)

| 파일     | 이름        | 프롬프트용                                                                                                                                                           |
| -------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| s/1.webp | 식사        | a small group of ragged cult survivors eating together around a low table in the warm kitchen, simple food, laughing, cozy                                           |
| s/2.webp | 장터 장사 | peddler selling goods at an ancient Chinese market stall, copper coins with square holes changing hands, busy and comic |
| s/3.webp | 협상 | tense negotiation across a low wooden table in a dim ancient Chinese room, porcelain tea cups, a cloth pouch of silver ingots in the middle |
| s/4.webp | 빚 독촉 | gang members in black hanfu at the ruined Chinese gate demanding a debt, one holding a hanji-paper debt document, menacing but comic. Gang members are anonymous extras, each with a clearly different face, age, body type and hairstyle; none of them looks like Sagong Hwi or any main character. |
| s/5.webp | 정파 순찰 | Baek Muhyeon leading the patrol in front, face visible, white martial robe with blue sash matching his sheet. Follower guards behind him wear **orthodox alliance white hanfu** (each cut and layer slightly different from Baek's robe, no blue sash on extras) and **white cloth face masks (복면)** covering their faces completely. Ancient Chinese village street, people hiding behind wooden doors, tense. Attach `ref/baek_sheet.webp` and `p/8.webp` (화풍·거리). |
| s/6.webp | 습격 | Baek Muhyeon leading the assault in front with torch, face visible, white robe and blue sash matching his sheet. Followers wear **orthodox alliance white hanfu** (each slightly different from Baek, no blue sash) and **white cloth face masks (복면)**. Storming the ruined Chinese mountain headquarters at night, chaos, smoke, no gore. Attach `ref/baek_sheet.webp` and `p/1.webp` (화풍·본산). |
| s/7.webp | 수상한 만남 | two cloaked figures secretly meeting outside the broken gate at night, seen from behind, faces and body shapes completely hidden by cloaks and shadow                |
| s/8.webp | 제자 합류   | a martial artist seen from behind walking through the broken gate toward a small welcoming group, sunrise, hopeful                                                   |
| s/9.webp | 즉위식 | grand inauguration ceremony at the restored Chinese mountain headquarters, seven martial artists standing in a row on the stone steps seen from far away, crowd of cult members, red banners and lanterns, triumphant. Background characters are anonymous extras, each with a clearly different face, age, body type and hairstyle; none of them looks like Baek Muhyeon or any main character. |

- 7번(수상한 만남)은 비밀을 숨기는 장면이다. 두 사람의 얼굴, 체격, 무기, 옷 색이 드러나지 않게 한다.
- 무리가 나오는 장면은 얼굴이 작게 보이게 넓게 잡는다.
- **5·6번(정파 순찰·습격):** 대장은 **백무현** 한 명만 얼굴을 그리고 `ref/baek_sheet.webp`에 맞춘다. 나머지 정파 무사는 **흰색 정파 복장**(백무현과 디테일은 다르게)과 **흰 복면**으로 얼굴을 가린다.

## 7. 소품 (`i/번호.webp`, 12장)

| 파일      | 이름         | 프롬프트용                                                                                       |
| --------- | ------------ | ------------------------------------------------------------------------------------------------ |
| i/1.webp | 장부 | old Chinese thread-bound ledger book (线装 서책), soft yellowed hanji paper cover with visible side stitching, slightly burnt edges, pages slightly open but completely blank with no writing, no brush strokes, no readable text |
| i/2.webp  | 주판         | worn wooden abacus with dark beads                                                               |
| i/3.webp  | 은자 주머니  | cloth purse full of silver ingots and coins                                                      |
| i/4.webp | 차용증 | East Asian debt contract on a single sheet of plain blank hanji paper, completely empty with no writing and no brush strokes, only a red thumbprint and a small red square seal stamp, partly folded, no wax, no parchment, no scroll rods |
| i/5.webp | 비급 한 권 | one old Chinese martial-arts secret manual as a thread-bound 线装 서책, plain dark blue hanji paper cover, blank with no title text, one edge torn as if split from a set, faint dark aura, not a Western leather tome |
| i/6.webp | 비급 일곱 권 | seven ancient Chinese hand scrolls (卷轴) with wooden rods at both ends, scroll surfaces in seven different colors, arranged in a circle, their torn edges fitting together, glowing softly, no Western books |
| i/7.webp  | 국자         | big old iron ladle, dented, with a wooden handle                                                 |
| i/8.webp  | 영패         | white jade token of the orthodox alliance with a blue tassel                                     |
| i/9.webp  | 약재         | bundle of medicinal herbs wrapped in cloth and tied with string                                  |
| i/10.webp | 밀서 | ancient Chinese secret letter as a rolled hand scroll (卷轴) tied with a thin dark cord, small black seal stamp on the outside, completely blank scroll surface with no writing, no wax seal, no readable text |
| i/11.webp | 염주         | dark wooden prayer beads                                                                         |
| i/12.webp | 인장 | official seal of the cult leader, Chinese-style square black jade seal with a carved beast-shaped handle, beside a round red cinnabar ink paste box |

## 8. 체크리스트 (시트 13장 + 크랙용 134장)

### 캐릭터 시트 ref/ (13장, 우강·백무현만 다시)

- [x] ref/dan_sheet.webp
- [x] ref/seo_sheet.webp
- [x] ref/heo_sheet.webp
- [x] ref/myo_sheet.webp
- [x] ref/ma_sheet.webp
- [x] ref/seok_sheet.webp
- [x] ref/jin_sheet.webp
- [x] ref/ok_sheet.webp
- [x] ref/wu_sheet.webp
- [x] ref/so_sheet.webp
- [x] ref/baek_sheet.webp
- [x] ref/sa_sheet.webp
- [x] ref/eom_sheet.webp

### 캐릭터 c/ (98장)

**단도원 (dan)**

- [x] c/dan/1.webp
- [x] c/dan/2.webp
- [x] c/dan/3.webp
- [x] c/dan/4.webp
- [x] c/dan/5.webp
- [x] c/dan/6.webp
- [x] c/dan/7.webp
- [x] c/dan/8.webp

**서은결 (seo)**

- [x] c/seo/1.webp
- [x] c/seo/2.webp
- [x] c/seo/3.webp
- [x] c/seo/4.webp
- [x] c/seo/5.webp
- [x] c/seo/6.webp
- [x] c/seo/7.webp
- [x] c/seo/8.webp

**허류 (heo)**

- [x] c/heo/1.webp
- [x] c/heo/2.webp
- [x] c/heo/3.webp
- [x] c/heo/4.webp
- [x] c/heo/5.webp
- [x] c/heo/6.webp
- [x] c/heo/7.webp
- [x] c/heo/8.webp

**묘연 (myo)**

- [x] c/myo/1.webp
- [x] c/myo/2.webp
- [x] c/myo/3.webp
- [x] c/myo/4.webp
- [x] c/myo/5.webp
- [x] c/myo/6.webp
- [x] c/myo/7.webp
- [x] c/myo/8.webp
- [x] c/myo/9.webp

**마대산 (ma)**

- [x] c/ma/1.webp
- [x] c/ma/2.webp
- [x] c/ma/3.webp
- [x] c/ma/4.webp
- [x] c/ma/5.webp
- [x] c/ma/6.webp
- [x] c/ma/7.webp
- [x] c/ma/8.webp

**석란 (seok)**

- [x] c/seok/1.webp
- [x] c/seok/2.webp
- [x] c/seok/3.webp
- [x] c/seok/4.webp
- [x] c/seok/5.webp
- [x] c/seok/6.webp
- [x] c/seok/7.webp
- [x] c/seok/8.webp

**진아린 (jin)**

- [x] c/jin/1.webp
- [x] c/jin/2.webp
- [x] c/jin/3.webp
- [x] c/jin/4.webp
- [x] c/jin/5.webp
- [x] c/jin/6.webp
- [x] c/jin/7.webp

**옥 할멈 (ok)**

- [x] c/ok/1.webp
- [x] c/ok/2.webp
- [x] c/ok/3.webp
- [x] c/ok/4.webp
- [x] c/ok/5.webp
- [x] c/ok/6.webp
- [x] c/ok/7.webp

**우강 (wu)**

- [x] c/wu/1.webp
- [x] c/wu/2.webp
- [x] c/wu/3.webp
- [x] c/wu/4.webp
- [x] c/wu/5.webp
- [x] c/wu/6.webp
- [x] c/wu/7.webp

**소칠 (so)**

- [x] c/so/1.webp
- [x] c/so/2.webp
- [x] c/so/3.webp
- [x] c/so/4.webp
- [x] c/so/5.webp
- [x] c/so/6.webp
- [x] c/so/7.webp

**백무현 (baek)**

- [x] c/baek/1.webp
- [x] c/baek/2.webp
- [x] c/baek/3.webp
- [x] c/baek/4.webp
- [x] c/baek/5.webp
- [x] c/baek/6.webp
- [x] c/baek/7.webp

**사공휘 (sa)**

- [x] c/sa/1.webp
- [x] c/sa/2.webp
- [x] c/sa/3.webp
- [x] c/sa/4.webp
- [x] c/sa/5.webp
- [x] c/sa/6.webp
- [x] c/sa/7.webp

**엄상 (eom)**

- [x] c/eom/1.webp
- [x] c/eom/2.webp
- [x] c/eom/3.webp
- [x] c/eom/4.webp
- [x] c/eom/5.webp
- [x] c/eom/6.webp
- [x] c/eom/7.webp

### 장소 p/ (15장)

- [x] p/1.webp (본산 1단계 (폐허)) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/2.webp (본산 2단계) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/3.webp (본산 3단계) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/4.webp (본산 4단계) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/5.webp (재무당 금고) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/6.webp (주방) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/7.webp (밤의 정문) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/8.webp (장터) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/9.webp (사파 방회)
- [x] p/10.webp (정파 감옥) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/11.webp (남쪽 마을 의원) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/12.webp (밀수 나루터) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/13.webp (극단 무대) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] p/14.webp (내기 격투장)
- [x] p/15.webp (산골 오두막) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)

### 상황 s/ (9장)

- [x] s/1.webp (식사)
- [x] s/2.webp (장터 장사) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] s/3.webp (협상) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] s/4.webp (빚 독촉) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] s/5.webp (정파 순찰)
- [x] s/6.webp (습격)
- [x] s/7.webp (수상한 만남)
- [x] s/8.webp (제자 합류)
- [x] s/9.webp (즉위식) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)

### 소품 i/ (12장)

- [x] i/1.webp (장부) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] i/2.webp (주판)
- [x] i/3.webp (은자 주머니)
- [x] i/4.webp (차용증)
- [x] i/5.webp (비급 한 권) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] i/6.webp (비급 일곱 권) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] i/7.webp (국자)
- [x] i/8.webp (영패)
- [x] i/9.webp (약재)
- [x] i/10.webp (밀서) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] i/11.webp (염주)
- [x] i/12.webp (인장) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)

## 9. 상세 설명 이미지 (`d/번호.webp`, 5장)

크랙 작품 페이지의 상세 설명에 넣는 이미지다. 채팅에는 쓰지 않는다. **이 5장은 GitHub에 올리지 않고 크랙 내부 이미지(크랙 미디어)로 올린다.** `d/` 폴더에는 작업용으로만 저장하고, 크랙에는 아래 "크랙 이름"으로 등록한다.

- 크기: 세로 2:3 (예: 1080×1620). 웹툰 표지처럼 한 장으로도 눈에 띄게.
- 인물이 나오는 장은 그 인물의 `ref/` 시트를 첨부하고 "인물 고정 문구"를 붙인다. 인물이 없는 장은 "풍경 고정 문구"를 붙인다. 고정 문구의 비율은 세로 2:3으로 둔다.
- 주인공(서기)은 뒷모습이나 손만 그린다.

| 파일     | 첨부할 시트             | 내용 (프롬프트용)                                                                                                                                                                                                                                                                                                                                                                                                                 |
| -------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| d/1.webp | dan_sheet (화풍 참고만) | Webtoon cover style. The ruined ancient Chinese mountain headquarters of a demonic cult at dusk, burnt wooden main hall with curved tiled roof and broken Chinese-style gate. In the foreground, a lone scribe seen only from behind, holding a thick East Asian thread-bound ledger and an abacus, looking up at the ruins. On the distant mountain ridges, seven tiny glowing figures in seven different colors (dark crimson, light purple, crimson, pink, orange, moss green, sky blue). Hopeful but lonely mood. |
| d/2.webp | ok, wu, so | Warm old Chinese kitchen in the ruins, brick stove and iron woks. Granny Ok scolding with her ladle raised, Woo Gang standing quietly by the door with his saber, So Chil chattering and shaking his abacus. At the table, the scribe seen from behind counting a small pile of 50 silver coins. Comic, cozy, lively. |
| d/3.webp | dan_sheet (화풍 참고만) | Seven torn pages of an old Chinese thread-bound martial-arts secret manual (hanji paper with vertical brush-written columns, not readable, not Western parchment) floating in a circle against a dark background. Each page glows in one color (dark crimson, light purple, crimson, pink, orange, moss green, sky blue) and shows a small dark silhouette of a different martial artist. The torn edges almost fit together. Mysterious, epic. |
| d/4.webp | sa | Ancient Chinese (East Asian wuxia) setting only. Sagong Hwi sitting in a luxurious ancient Chinese gang hall of dark lacquered wood, gold carvings and folding screens, smiling gently while holding out a single sheet of plain blank hanji paper as a debt contract: completely empty white rice paper with no writing and no brush strokes at all, only a red thumbprint and a small red square seal stamp, no letters, no scroll rods, no Western parchment, no wax seal, no quill. Gold rings on his fingers. Gang members in black hanfu stand behind him. In the foreground, only the scribe's hands reaching for a heavy cloth pouch of silver ingots. Charming but menacing. |
| d/5.webp | ok, wu, so | The broken Chinese-style wooden main gate with a curved tiled roof at night under moonlight. Three people seen only as dark silhouettes, each equally suspicious: one carrying a cloth bundle out of the gate, one standing still and staring into the dark, one counting coins in the shadow of a wall. Faces not visible. Quiet suspense. |

- d/5는 셋이 똑같이 수상해 보여야 한다. 어느 한 명만 더 어둡거나 크게 그리지 않는다.

### 상세 설명 d/ (5장)

- [x] d/1.webp → 크랙 이름 상세::표지 (폐허와 서기, 먼 산의 일곱 빛) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] d/2.webp → 크랙 이름 상세::식구들 (주방의 식구들) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] d/3.webp → 크랙 이름 상세::일곱비급 (일곱 조각의 비급) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
- [x] d/4.webp → 크랙 이름 상세::사파빚 (사공휘와 차용증)
- [x] d/5.webp → 크랙 이름 상세::수상한셋 (밤의 정문, 수상한 셋) ← 설명 수정됨 (서양풍으로 나왔다면 다시 만들기)
