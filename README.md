# 🐵 localgov-oss-example-monkeyhunter

This repository documents an open-source case study of a wildlife damage reporting system developed during **Tokyo OSS Party! 2023**, where it won the **Grand Prize**.  
The system has since been officially adopted by Okutama Town and expanded to nearby municipalities including Ome City.

> 🌱 This repository serves as a **non-code companion** to the actual implementation, focusing on lessons learned, project background, and OSS adoption in local government.

---

## 📌 Project Summary

- 🎯 **Purpose**: Support rural municipalities in capturing and visualizing wildlife damage incidents through citizen participation
- 🏛️ **Used by**: Okutama Town (Tokyo), Ome City (from 2025)
- 🧑‍🌾 **Tools**: LINE bot (for residents), Web dashboard (for municipal staff)
- 🛠️ **Tech**: Node.js, Supabase, AWS S3, Vercel
- 🔓 **OSS Compliance**: Published under Tokyo Metropolitan Government OSS Guidelines

---

## 🔗 Key Links

| Type | Link |
|------|------|
| 📦 Technical Implementation | [vermin-network-bot](https://github.com/dx-junkyard/vermin-network-bot) |
| 📄 Project Summary (JP) | [Protopedia - モンキーハンター](https://protopedia.net/prototype/3745) |
| 📽️ Demo Video | [YouTube Demo](https://youtu.be/KglGfMF1-y4) |
| 🎤 Presentation Recording | [YouTube Presentation (start at 33:46)](https://www.youtube.com/live/5nZW4lGoQg0?si=l7WUtq4ACzvzqemQ&t=2026) |

---

## 📖 What This Repository Contains

- `docs/project_overview_ja.md`: 日本語によるプロジェクト背景と成果の詳細解説
- `docs/transcript_summary.md`: 発表・講評・質疑応答の要旨まとめ
- `docs/slides.pdf`: 発表スライド（PDF形式）
- `docs/screenshots/`: システム構成図・UIワイヤーフレーム画像
- `README.md`: 英語中心の概要と目的整理（本ファイル）

---

## 💡 Lessons Learned

- OSS development is not about perfection, but about transparency and reusability
- Even non-engineers can join meaningful development using tools like ChatGPT
- Designing with both generalization and localization in mind is crucial for reuse
- User-friendly interfaces significantly boost adoption by residents and staff
- Accumulating incident data (photos + metadata) opens new possibilities for long-term analysis and broader use

---

## 🪧 License

This repository and its documentation are released under the MIT License.  
See [LICENSE](./LICENSE) for details.

> 📌 **Note**:  
> The source code for the actual LINE bot and backend implementation is maintained separately at  
> [dx-junkyard/vermin-network-bot](https://github.com/dx-junkyard/vermin-network-bot)  
> and may be licensed under different terms.
