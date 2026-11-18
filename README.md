# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/gonjol178/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/gonjol178/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A newspaper front page summing up the world news of **Wednesday 18 November 2026** in one 1024×1024 image: the U.S.–Iran tanker war widening overnight, Ukraine's record 1,441-drone swarm against the Crimea Bridge, Gaza's displaced facing a deadly winter, Israel's president asking Eisenkot to form a government, and the day's one-liners from Manila, Antalya, Siberia, Seoul and Hollywood. The three photographs are AI-generated editorial panels; every headline is set in type by `build_frontpage.py` (Pillow), so no text in the image can garble.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

That validates `entry.png` (whole-PNG check: signature, chunk CRCs, final IEND) and copies it to `out/entry.png`. It runs offline and writes identical bytes on every run.

---

<sub>Entered on [make.fun](https://make.fun/?ref=1k4fvxxj&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
