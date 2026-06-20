# AI商業成長 Landing Page

> 用 AI 打造流量、成交與自動化系統 — 潘珮淩
> 7 天交付 / 30 天見效 / 房仲・醫美・美容 三大主力產業

## 🚀 快速啟動(3 種方式)

### 方式 A:本地預覽(0 秒)
```bash
# 直接雙擊 index.html 就能看
# 或用本地伺服器(推薦,避免 CORS)
cd C:\Users\WIN11\.openclaw\workspace\projects\ai-business-growth-website
python -m http.server 8000
# → http://localhost:8000
```

### 方式 B:Vercel 部署(2 分鐘)
```bash
# 1. 裝 Vercel CLI
npm i -g vercel

# 2. 部署
cd C:\Users\WIN11\.openclaw\workspace\projects\ai-business-growth-website
vercel

# → 照指示登入 → 拿到一個 xxx.vercel.app 網址
# 之後改檔只要 vercel --prod
```

### 方式 C:拖檔部署(0 技術,1 分鐘)
1. 打開 https://vercel.com/new
2. 把整個 `ai-business-growth-website` 資料夾拖進去
3. 完成 → 拿到網址

## 🛠️ 技術棧

| 層 | 技術 | 原因 |
|---|---|---|
| HTML5 | 純語意化標籤 | SEO 友善 |
| Tailwind CSS (CDN) | 零建置 | 改檔即生效 |
| Vanilla JS | IntersectionObserver | 滾動動畫,無依賴 |
| Google Fonts | Noto Sans TC | 繁體中文標準字型 |

## 📁 檔案結構

```
ai-business-growth-website/
├── index.html      ← 主頁(全部內嵌)
├── README.md       ← 本檔
└── vercel.json     ← Vercel 設定
```

## ✏️ 修改指南

| 想改什麼 | 找哪裡 |
|---|---|
| 報價 / 方案 | 搜尋 `NT$` |
| 服務項目 | 搜尋 `SERVICES` |
| 案例數字 | 搜尋 `+312%` |
| 顏色 | `tailwind.config` 區塊的 `colors` |
| 聯絡 Email | 搜尋 `pan.email@example.com`(目前表單是示範) |
| Logo 圖示 | 搜尋 `🦐` 全站替換 |

## 🔌 接表單(下一步)

目前表單送出是前端假成功,需要串接後端才會真的通知你:

| 方案 | 難度 | 費用 |
|---|---|---|
| **Formspree** | ⭐ | 免費 50 次/月 |
| **N8N Webhook** | ⭐⭐ | 免費(自架) |
| **Notion API** | ⭐⭐ | 免費 |
| **Google Sheet** | ⭐ | 免費 |

我可以直接幫你接好 N8N + Notion + Email 三通知,讓表單直接進 CRM。

## 📊 監測(上線後必裝)

```html
<!-- 加到 <head> 內,index.html 第 8 行附近 -->
<!-- Plausible 隱私友善分析 -->
<script defer data-domain="yourdomain.com" src="https://plausible.io/js/script.js"></script>

<!-- 或 Google Analytics 4 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
```

## 🎨 設計原則

- **Dark + Gold**:對齊 NT$ 500-2000 萬年營收定位(避免廉價感)
- **3-3-3 戰術**:主力產業在 Hero 就講清楚
- **單一 CTA**:全站導「免費策略會」,不分散注意力
- **SOP 透明**:5 步流程在 Pricing 旁,讓客戶買得安心

---

_2026-06-20 v1.0 — 蝦董 8 章節交付,5-question filter 全通過_
