# CONTEXT.md — consolog-website (Consolog Inc 子公司網站)

AI 接續協定: 收到 `resume` → 讀此檔 → 摘要 Current State → 開工。離開前更新並 commit+push。

---

## 🎯 Current State
- **Status**: paused (antigravity 版為最終版, 用戶確認喜歡)
- **Branch**: `master`
- **Last session**: remove hero badge company name
- **Working on**: 完成
- **Next step**: 待使用者指示
- **Blockers**: 無

## 🗂 Project Overview
- **Purpose**: Consolog Inc (康盛供應鏈) 形象網站
- **Stack**: HTML 純前端 (GitHub Pages)
- **Key paths**:
  - `antigravity.html` — 最終版 (深色 glassmorphism + EN/ZH/KR)
  - `merged.html` — Gemini layout + Claude SVG
  - `gemini-version.html` — Gemini 純生成版
  - `index.html` — Claude 初版
- **Entry points**: https://cph0512.github.io/consolog-website/antigravity.html

## 🔑 Key Decisions
- **antigravity 深色 glassmorphism** — 用戶偏好 (vs. 藍白)
- **EN/ZH/KR 三語**, 全頁切換不混合
- **移除 workflow 區塊** — UX 簡化
- **SVG 線條圖標** — 每個服務不同顏色

## 🚧 Pending / TODO
- [ ] 待使用者給方向

## 🐛 Known Issues
- 無

## 📎 External Refs
- GitHub: cph0512/consolog-website (public)
- Prod: https://cph0512.github.io/consolog-website/antigravity.html
- 參考: bbtruck.cc (母公司), lxpantos.com
- 資料: ~/Downloads/美國網站Consolog製作/

## 公司資訊
- **名稱**: CONSOLOG INC 康盛供應鏈有限公司
- **地址**: 13975 Central Ave Unit B, Chino, CA 91710
- **電話**: 626-866-8911 / 626-866-9904
- **Email**: shipping@consologusa.com / cs@consologusa.com
- **服務**: 國際海運(FCL/LCL) / 空運 / 倉儲 / 港口提櫃 / 全美運輸 / 快遞(UPS/FedEx/DHL)
- **語言**: 中文, 英文, 韓文

## 🖥 Environment
- GitHub Pages (自動部署自 master)

## 📜 Session Log
### 2026-04-19 22:30 (m4pro, claude)
- 建立 CONTEXT.md 納入 Resume Protocol (遠端寫入)
- 下次從: 等使用者新需求

### 2026-03-28 (近期 commits)
- 4e4aef7 remove hero badge company name
- e8290d5 antigravity: add EN/ZH/KR + remove inline Chinese
- 88227c2 add antigravity version: dark theme
- f0ff546 add merged version: Gemini layout + Claude icons + i18n
- 2248245 fix: add real gemini version + fix contact
