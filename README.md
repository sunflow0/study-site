# Language Study 💙

## Files
- `index.html` — updated page with search by Chinese, pinyin, POS, and English meaning.
- `data.json` — keeps the original English vocabulary and grammar content.

## Deploy
1. Download this folder or the ZIP.
2. Replace the existing `index.html` and `data.json` in the root of your GitHub repository with these versions.
3. Commit and push the changes. If Netlify is connected to the repository, it should redeploy automatically.

## Chinese HSK vocabulary
The page loads the HSK 3.0 Level 1–5 vocabulary list from a public machine-readable dataset when the site opens, and combines it with English glosses where available. An internet connection is required for the full HSK list. If the source is unavailable, the page falls back to the sample Chinese words already in `data.json`.

Attribution:
- HSK vocabulary and pinyin/POS: https://github.com/ivankra/hsk30
- English glosses: Zhongdex / CC-CEDICT, https://github.com/saymei/zhongdex
- The English gloss data is CC BY-SA 4.0. The page displays attribution to the source.

Note: the uploaded PDFs provide English meanings, not Thai translations or POS tags. The web version therefore displays English glosses and POS tags from the linked structured sources rather than inventing Thai meanings.
