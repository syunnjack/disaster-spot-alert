# Disaster Spot Alert

災害・悪天候時の避難/営業中スポット通知

## Repository

Recommended repository name: `disaster-spot-alert`

## Domain candidates

Confirmed domain: `disasterspot.jp`

Other candidates:

- `disasterspot.jp`
- `hinanspot.jp`
- `weatheropen.jp`
- `safeopen.jp`

## Concept

災害、悪天候、交通停止時に避難、営業中、充電、トイレ、宿泊スポットを通知する地域SaaS。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 防災広告
- 自治体SaaS
- 企業契約
- 店舗送客
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
