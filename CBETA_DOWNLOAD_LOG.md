# CBETA Download Log

**Date**: 2026-09-22
**Source**: CBETA XML P5 (GitHub: cbeta-org/xml-p5)
**Method**: Downloaded TEI P5 XML from GitHub raw URLs, extracted body text via Python XML parser

## Texts Downloaded

### Primary Dunhuang Meditation Texts

| # | Title | CBETA ID | Volume | File | Chars | Status |
|---|-------|----------|--------|------|-------|--------|
| 1 | 最上乘論 (修心要論) | T2011 | T48 | `修心要论_T2011.txt` | ~4,581 | ✅ Complete |
| 2 | 觀心論 | T2833 | T85 | `观心论_T2833.txt` | ~5,259 | ✅ Complete |
| 3 | 大乘無生方便門 (大乘五方便) | T2834 | T85 | `大乘五方便_T2834.txt` | ~9,289 | ✅ Complete |

### Additional Texts

| # | Title | CBETA ID | Volume | File | Chars | Status |
|---|-------|----------|--------|------|-------|--------|
| 4 | 曆代法寶記 | T2075 | T51 | `历代法宝记_T2075.txt` | ~35,660 | ✅ Complete |
| 5 | 楞伽師資記 | T2837 | T85 | `楞伽师资记_T2837.txt` | ~16,108 | ✅ Complete |

## Source URLs

- T2011: `https://raw.githubusercontent.com/cbeta-org/xml-p5/master/T/T48/T48n2011.xml`
- T2833: `https://raw.githubusercontent.com/cbeta-org/xml-p5/master/T/T85/T85n2833.xml`
- T2834: `https://raw.githubusercontent.com/cbeta-org/xml-p5/master/T/T85/T85n2834.xml`
- T2075: `https://raw.githubusercontent.com/cbeta-org/xml-p5/master/T/T51/T51n2075.xml`
- T2837: `https://raw.githubusercontent.com/cbeta-org/xml-p5/master/T/T85/T85n2837.xml`

## Notes

- **T2011 最上乘論**: Attributed to 5th Patriarch Hongren (弘忍). Also known as 修心要論. Full text extracted.
- **T2833 觀心論**: Attributed to Bodhidharma (pseudo.). Dunhuang manuscript text on mind-watching meditation.
- **T2834 大乘無生方便門**: Northern School meditation manual (大乘五方便 / 北宗五方便). Contains the five expedient gates.
- **T2075 曆代法寶記**: Record of the Dharma-Treasure Through the Generations. Multi-juan narrative text (~35K chars).
- **T2837 楞伽師資記**: Record of Masters and Disciples of the Laṅkāvatāra. Hagiographic with practice details.
- Extracted text preserves line breaks from original. XML apparatus notes (`<note>`) were stripped. Some CBETA gaiji references (`[#CB...]`) may appear for rare characters.
- CBETA copyright: texts are open for academic use per CBETA's license terms.
