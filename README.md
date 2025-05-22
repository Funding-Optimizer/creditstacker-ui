# 🚀 TheLoanStacker

**Live URL**: [https://theloanstacker.netlify.app](https://theloanstacker.netlify.app)  
**Custom Domain**: [https://theloanstacker.com](https://theloanstacker.com)  
**Host**: Netlify  
**Owner**: brian@fundedfi.com

[![Netlify Status](https://api.netlify.com/api/v1/badges/35160756-4dc8-42d1-a425-696e1342965b/deploy-status)](https://app.netlify.com/sites/theloanstacker/deploys)

---

## 📦 Project Overview

TheLoanStacker is a consumer-facing funding platform designed to deliver pre-qualified credit solutions through intelligent stacking strategies. Powered by CreditStacker logic and FundingGauge scoring.

---

## 🛠 Setup Instructions

### Local Development

```bash
git clone https://github.com/fundedfi/theloanstacker-ui.git
cd theloanstacker-ui
npm install
npm run dev
```

### Build for Production

```bash
npm run build
```

---

## 🌐 Deployment (Netlify)

### CLI Deployment

```bash
npm install -g netlify-cli
netlify deploy --prod
```

Follow the CLI to:
- Link to existing project: `theloanstacker`
- Set build output folder (e.g., `dist` or `build`)

### Continuous Deployment (Optional)
1. Connect GitHub → Netlify under **Site Settings > Build & Deploy**
2. Enable auto-deploy from `main` branch

---

## 🌍 DNS Setup

**GoDaddy (Recommended Records):**

| Type | Name | Value |
|------|------|-------|
| CNAME | www | theloanstacker.netlify.app |
| A     | @   | 75.2.60.5 |
| A     | @   | 99.83.190.102 |

✅ Remove any conflicting old A/CNAME records.

---

## 🔒 SSL Setup

1. Go to Netlify → **Site Settings > Domain > HTTPS**
2. Click **Provision Certificate**
3. Auto-protects with Let’s Encrypt SSL

---

## 📌 To Do Next

- [ ] Add Favicon & Social Share Image
- [ ] Embed MysticStack visuals or opt-in form
- [ ] Track conversions using Netlify Forms or Webhooks
- [ ] Launch SEO-optimized landing page for `theloanstacker.com`

---

## 📎 Linked Projects

- **CreditStacker**: Core optimization tools
- **FundingGauge**: Score UI + backend logic
- **LoanStacker AI**: Future scoring enhancement

---

## 🧠 Maintained by

**Optimizer (Owner)**  
**GPT (Infra/Automation)**  
**Claude (Brand/UX Copy)**
