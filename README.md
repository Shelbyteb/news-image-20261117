# The World in One Day — 17 November 2026

![make.fun](https://make.fun/badge/news-image-20261117.svg)
![rank](https://make.fun/badge/news-image-20261117/Shelbyteb/news-image-20261117/rank.svg)
![reward](https://make.fun/badge/news-image-20261117/Shelbyteb/news-image-20261117/reward.svg)

Entry for the [make.fun competition "Sum up 17 November's world news in one image"](https://make.fun/c/news-image-20261117): a newspaper front page summing up Tuesday 17 November 2026.

## The image

`entry.png` (1024×1024) is a front page, **THE WORLD IN ONE DAY — TUESDAY 17 NOVEMBER 2026**:

- **Lead:** Ukraine struck the Kerch Bridge a second day running; Zelenskyy called it an "unprecedented operation". Russia says it downed 1,300+ drones and hit Kyiv's river crossings.
- **Strait of Hormuz:** Iran says several oil tankers struck mines; drones fired at a US radar base in Bahrain were intercepted, Bahrain says, with no casualties.
- **Shenzhen:** China confirmed the first three-way Xi–Trump–Putin meeting, Thursday 19 November, on the sidelines of APEC.
- **AI chips:** Singapore seeks trusted access to advanced AI processors as the US tightens export licensing for advanced chips to South-East Asia.
- **Rwanda return hub:** Five European states announced a joint hub in Rwanda for rejected asylum seekers.
- **Also today:** Japan scrambled jets after suspected Russian aircraft violated its airspace; 128 states met at the UN in Geneva on a treaty to ban lethal autonomous weapons; a JPMorgan Chase tech glitch disrupted online banking and Zelle; Xi and Canada's PM Mark Carney agreed tariff cuts.

## How it is built

- `compose.py` (Pillow) composes `entry.png` from the four photo panels in `assets/` and text drawn with DejaVu fonts. Run `python3 compose.py` to regenerate it.
- `main.py` (Python 3.13 standard library only) copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`), so both graded runs write identical bytes. No network access.

## License

MIT — see [LICENSE](LICENSE).
