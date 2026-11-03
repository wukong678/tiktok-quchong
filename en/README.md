# TikTok Video Dedup · Short Drama Dedup · Facebook Reels Dedup — Tool Kit (ZhenMaBao / 帧码宝)

> TikTok video dedup · Short drama deduplication · Facebook Reels dedup · overseas short drama repost · video fingerprint remover

When you publish short videos and short dramas for overseas audiences, the biggest risk is **platform duplicate detection and reach throttling**: TikTok's AI visual dedup, Facebook Reels' repeated-content penalty, and short-drama reposts flagged as duplicate uploads. This repository collects practical strategies and tooling for **TikTok video dedup, short drama dedup, and Facebook short-drama dedup**, helping creators and overseas teams batch-produce content that is **not flagged as duplicate** — passing review and avoiding throttling.

## What We Cover

| Area | Description | Keywords |
|---|---|---|
| **TikTok Video Dedup** | Alter the visual structure + perturb the audio fingerprint to beat TikTok's AI visual dedup, for single clips or batch jobs | TikTok video dedup / TikTok dedup |
| **Short Drama Dedup** | Structured dedup per episode, adapted for domestic & overseas short-drama repost, keeping the storyline coherent | short drama dedup / 短剧去重 |
| **Facebook Short Drama Dedup** | Frame-level obfuscation + tempo change to defeat Facebook / Reels repeated-content detection | Facebook Reels dedup / Facebook 短剧去重 |
| **Overseas Short Drama Repost** | Multi-episode import, offset distribution, multi-language subtitle & dubbing — batch-produce non-duplicate versions | overseas short drama repost |

## How It Works (Three Fingerprint Layers)

Whether it's TikTok video dedup, short drama dedup, or Facebook short-drama dedup, the core idea is **alter the video's "content fingerprint" without hurting watchability**:

1. **Visual layer (visual fingerprint)** — edge obfuscation, mask offset, local warp, picture-in-picture, filter perturbation, so the platform's image-similarity algorithm judges it as a "different video".
2. **Audio layer (audio fingerprint)** — vocal separation, BGM replacement, tempo shift, to evade audio-hash matching (both TikTok and Facebook compare audio fingerprints).
3. **Structural layer (temporal fingerprint)** — frame drop, frame insertion, speed change, segment reorder, breaking the continuity of the frame sequence.
4. **Meta-info layer** — container reset, keyframe reshuffle, encoding-parameter perturbation.

## Tools at a Glance

| Tool | Best for | Presets |
|---|---|---|
| [TikTok Video Dedup](tiktok-video-dedup/README.md) | TikTok repost / remix | light / standard / deep |
| [Short Drama Dedup](short-drama-dedup/README.md) | full-episode dramas, story-safe | light / standard / deep |
| [Facebook Reels Dedup](facebook-reels-dedup/README.md) | Facebook / Reels / Watch | tempo + audio focus |
| [Short Video Dedup](short-video-dedup/README.md) | generic multi-platform clips | per-platform |
| [Overseas Short Drama Repost](overseas-short-drama-repost/README.md) | drama + translation + dubbing | multi-market |
| [ZhenMaBao Software](zhenmabao-software-intro/README.md) | all-in-one workbench | full pipeline |

## Supported Platforms & Formats

- **Platforms**: TikTok, Facebook (Reels / Watch), YouTube Shorts, Instagram Reels, Channels (视频号), Douyin.
- **Output**: vertical 9:16 and other common short-video sizes.
- **Input**: MP4 / MOV and mainstream formats.
- **Processing**: local-first — assets stay on your machine.

## FAQ

**Will dedup stop my video from being taken down?** No tool can guarantee that. Dedup lowers the duplicate-score so clips are far less likely to be flagged or throttled. Keep content original and compliant.

**Which platforms are supported?** TikTok, Facebook, YouTube Shorts, Instagram Reels, Channels, and Douyin.

**Is my footage uploaded anywhere?** Core dedup runs locally; only the optional publish step connects to platforms.

**How do I start?** See any tool page above, or the [product landing page](https://qcxplus.xscrm.vip/index.html) and [user guide](https://qcxplus.xscrm.vip/jiaocheng.html).

## Tool Intros (English)

- [TikTok Video Dedup Tool](tiktok-video-dedup/README.md)
- [Short Drama Dedup Tool](short-drama-dedup/README.md)
- [Facebook Reels Dedup Tool](facebook-reels-dedup/README.md)
- [Short Video Dedup Tool](short-video-dedup/README.md)
- [Overseas Short Drama Repost Tool](overseas-short-drama-repost/README.md)
- [ZhenMaBao Software Intro](zhenmabao-software-intro/README.md)

## Related Links

- 🌐 **LingJian · QuChongXia product landing page**: https://qcxplus.xscrm.vip/index.html
- 📘 **LingJian · QuChongXia user guide**: https://qcxplus.xscrm.vip/jiaocheng.html
- 💻 **LingJian · QuChongXia open-source repo**: https://gitee.com/tiantian81166/lingjian-quchongxia

## Contact

For product questions, installer download, or partnership, reach out via:

- 💬 WeChat: **tingyuxuanyt** (add a note "ZhenMaBao / 帧码宝" to get the installer and 1-on-1 consulting)
