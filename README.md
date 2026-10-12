# gamjeongdogam-fonts

Korean fonts that the 감정도감 (Emotion Dex) app downloads on demand, served through jsDelivr:

```
https://cdn.jsdelivr.net/gh/SynInaSoft/gamjeongdogam-fonts@pack<N>-v1/fonts/<file>
```

jsDelivr serves at most 50 MB per GitHub tag, and all the fonts together are about 100 MB. So the fonts are split into three packs. Each pack is a separate commit, not on `main`, tagged `pack1-v1`, `pack2-v1` and `pack3-v1`, and holds only its own fonts plus this README and `licenses/`. `main` has every file.

- pack1: GamjaFlower, HiMelody, Dongle, PoorStory, NanumPenScript, SingleDay
- pack2: Stylish, BlackAndWhitePicture, GowunBatang, NanumBrushScript, NanumMyeongjo
- pack3: GowunDodum, MaruBuri, RIDIBatang, LINESeedKR, IBMPlexSansKR, NanumGothic

Every font here is licensed under the SIL Open Font License 1.1. Each font keeps its own copyright notice; see `licenses/`.

| File | Font | Copyright holder | Source | License file |
|---|---|---|---|---|
| GowunDodum-Regular.ttf | Gowun Dodum | The Gowun Dodum Project Authors | Google Fonts | licenses/gowundodum-OFL.txt |
| LINESeedKR-Rg.ttf | LINE Seed Sans KR | LY Corporation | seed.line.me | licenses/OFL-1.1.txt |
| IBMPlexSansKR-Regular.ttf | IBM Plex Sans KR | IBM Corp. | Google Fonts | licenses/ibmplexsanskr-OFL.txt |
| NanumGothic-Regular.ttf | Nanum Gothic | NHN Corporation (NAVER) | Google Fonts | licenses/nanumgothic-OFL.txt |
| GowunBatang-Regular.ttf | Gowun Batang | The Gowun Batang Project Authors | Google Fonts | licenses/gowunbatang-OFL.txt |
| MaruBuri-Regular.ttf | MaruBuri 2.000 | NAVER Corp., NAVER Cultural Foundation | NAVER (WOFF2 unpacked to TTF, glyphs unchanged) | licenses/OFL-1.1.txt |
| RIDIBatang-Regular.ttf | RIDIBatang | RIDI Corporation | noonnu (WOFF unpacked; CFF outlines converted to TrueType and the empty name table filled so iOS can register it) | licenses/OFL-1.1.txt |
| NanumMyeongjo-Regular.ttf | Nanum Myeongjo | NHN Corporation (NAVER) | Google Fonts | licenses/nanummyeongjo-OFL.txt |
| NanumPenScript-Regular.ttf | Nanum Pen Script | NHN Corporation (NAVER) | Google Fonts | licenses/nanumpenscript-OFL.txt |
| NanumBrushScript-Regular.ttf | Nanum Brush Script | NHN Corporation (NAVER) | Google Fonts | licenses/nanumbrushscript-OFL.txt |
| HiMelody-Regular.ttf | Hi Melody | YoonDesign Inc. | Google Fonts | licenses/himelody-OFL.txt |
| GamjaFlower-Regular.ttf | Gamja Flower | YoonDesign Inc. | Google Fonts | licenses/gamjaflower-OFL.txt |
| PoorStory-Regular.ttf | Poor Story | YoonDesign Inc. | Google Fonts | licenses/poorstory-OFL.txt |
| SingleDay-Regular.ttf | Single Day | DXKorea Inc. | Google Fonts | licenses/singleday-OFL.txt |
| Dongle-Regular.ttf | Dongle | The Dongle Project Authors | Google Fonts | licenses/dongle-OFL.txt |
| Stylish-Regular.ttf | Stylish | AsiaSoft Inc. | Google Fonts | licenses/stylish-OFL.txt |
| BlackAndWhitePicture-Regular.ttf | Black And White Picture | AsiaSoft Inc. | Google Fonts | licenses/blackandwhitepicture-OFL.txt |

Files are never changed under an existing tag. A changed file gets a new file name or a new tag (pack1-v2 and so on), so cached copies stay valid. The first tag `v1` holds all fonts and is over the jsDelivr limit; do not use it.
