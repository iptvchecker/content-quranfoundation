# QuranFoundation commentary and word audio

Individual original files used for Quran reading and study:

- **77,429 Hafs word recordings** under `wbw/`, retaining their original MP3 filenames and bytes.
- **6,789 commentary responses** under `api/v4/tafsirs/`, for resource IDs 14, 15, 157, 159, 160 and 818. JSON response bytes and grouped-ayah mappings are unchanged.

`SOURCE-FILES.json` records each file's original source URL, byte size and SHA-256. Original response archives and audio backup assets are also retained.

The captured Arabic responses still lack 31 per-ayah recovery responses for resource 14 and 40 for resource 15. The Urdu responses retain the provider's grouped responses and explicit unavailable entries. No adjacent commentary is substituted for missing source mappings.

Original sources: [Quran.com](https://quran.com/), [Quran Foundation audio](https://audio.qurancdn.com/), and the [Quran.com API](https://api.quran.com/api/v4/).
API documentation: https://api-docs.quran.com/

Retrieval dates are distinct from original publication dates.
