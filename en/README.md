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
