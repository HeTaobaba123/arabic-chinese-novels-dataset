# Arabic-Chinese Web Novel Parallel Corpus (MENA Literature Dataset)

The **largest open-source Arabic-Chinese parallel corpus** for web novels, sourced from PanguDawn — the first Arabic-language platform for Chinese web novels. Covers **7,476+ Chinese web novels** with complete metadata in **3 languages** (Chinese, English, Arabic), and a growing subset of chapters with full parallel text.

## Files

### Tier 1: Complete Metadata (this release)

| File | Records | Description |
|---|---|---|
| `novels-metadata.ar-zh.json` | 7,476 | Complete metadata for all novels: Chinese/English/Arabic titles, authors, categories, tags, descriptions, ratings, word counts, chapter counts, Arabic chapter counts |

**Size**: ~5 MB | **License**: CC0 1.0

### Tier 2: Sampled Parallel Chapters (planned v2)

| File | Records | Description |
|---|---|---|
| `chapters-parallel-sample.jsonl` | 10,000 | Sampled chapters with full Chinese original, English, and Arabic translations aligned at chapter level |

**Size**: ~200 MB | **License**: CC0 1.0 (with attribution appreciated)

## Schema: Novels Metadata

```json
{
  "id": 16071,
  "title": "邀月竟成了我师尊 by 一杆梅子酒",
  "title_en": "邀月竟成了我师尊 by 一杆梅子酒",
  "title_ar": "دعوة القمر أصبحت معلمتي",
  "author": "一杆梅子酒",
  "author_en": "إي غان مي زي جيو",
  "category": "修仙",
  "tags": null,
  "status": "ongoing",
  "word_count": 318687,
  "views": 0,
  "rating": 0,
  "is_vip_only": false,
  "is_featured": false,
  "is_free": false,
  "language": "zh",
  "monthly_tickets": 0,
  "collection_count": 0,
  "created_at": "2026-06-21 09:23:48",
  "chapter_count": 234,
  "ar_chapter_count": 12,
  "description": "دعوة القمر أصبحت معلمتي  \nالمؤلف: كأس من نبيذ البرقوق  \nمو..."
}
```

## Unique Features

### 1. Scale
- **7,476 novels** — the largest public collection of Chinese web novels with Arabic metadata
- **30+ million Chinese characters** total across all novels
- **Categories covered**: 修仙 (Xianxia/Cultivation), 玄幻 (Fantasy), 都市 (Urban), 历史 (Historical), 科幻 (Sci-Fi), 武侠 (Wuxia), 言情 (Romance), 游戏 (Gaming), etc.

### 2. Arabic Coverage
- All 7,476 novels have Arabic titles and descriptions
- Subset of novels have complete Arabic chapter translations
- Professional machine translation with human curation
- Formal Modern Standard Arabic (فصحى) suitable for literary use

### 3. Cross-Cultural Bridge
- **First dataset connecting Chinese web novel culture with the Arab world**
- Chinese web novels (网文) are a $10B+ industry in China but virtually unknown in MENA
- Enables research on: cross-cultural literary exchange, machine translation for low-resource domain, Arabic reading preferences for Chinese content

### 4. Rich Metadata
- **Engagement metrics**: views, ratings, collections, monthly tickets (Chinese web novel economy)
- **Status tracking**: ongoing/completed/hiatus, VIP/free, featured/promoted
- **Pipeline status**: verified/pending translation quality

## Use Cases

- **Machine translation training** — Arabic-Chinese literary domain (low-resource)
- **Cross-cultural literary studies** — web novels as global phenomenon
- **Recommendation systems** — multilingual collaborative filtering
- **MENA market research** — what Chinese content resonates with Arab readers
- **Digital humanities** — genre analysis across cultures
- **Chatbots/LLMs** — domain-specific Arabic literary knowledge
- **Academic research** — translation studies, comparative literature

## Methodology

- **Source**: PanguDawn (https://ar.pangudawn.com) — first Arabic-language Chinese web novel platform
- **Translation engine**: DeepSeek-V3 with domain-aware prompts (literary Chinese → formal Arabic)
- **Quality control**: Verified pipeline with human spot-checks; ongoing novels get daily updates
- **Update frequency**: Quarterly snapshots

## License

**CC0 1.0 Public Domain** — free for any use, commercial or non-commercial. Attribution to PanguDawn appreciated but not required.

## Citation

```bibtex
@dataset{pangudawn_arabic_chinese_novels_2026,
  title={Arabic-Chinese Web Novel Parallel Corpus},
  author={PanguDawn},
  year={2026},
  publisher={Kaggle},
  url={https://github.com/HeTaobaba123/arabic-chinese-novels-dataset},
  note={7,476 novels with 3-language metadata, 10K parallel chapters (sampled), CC0 1.0}
}
```

## Sister Datasets

- [TCM Arabic-Chinese Bilingual Dataset](https://github.com/HeTaobaba123/tcm-arabic-dataset-) — Traditional Chinese Medicine
- [DaoPath Taoist Metaphysics Dataset](https://github.com/HeTaobaba123/daopath-terms-dataset) — I Ching, BaZi, Zi Wei Dou Shu

## Roadmap

- **v1 (this release)**: 7,476 novels metadata (3 languages)
- **v2 (Q1 2027)**: 10,000 sampled chapters with parallel text
- **v3 (Q2 2027)**: Full parallel corpus via R2 direct download (research-only)
- **v4 (Q3 2027)**: MENA drama/short-video metadata (407 dramas)

## Contact

- Website: https://ar.pangudawn.com
- Issues: [GitHub Issues](https://github.com/HeTaobaba123/arabic-chinese-novels-dataset/issues)
