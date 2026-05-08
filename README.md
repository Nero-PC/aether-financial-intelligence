# Aether | Financial File Intelligence

![Aether Logo](https://via.placeholder.com/150x50?text=AETHER+INTELLIGENCE)

**Premium institutional-grade financial file intelligence platform** built with Next.js. Features a polished banking aesthetic, powerful client-side analysis, executive dashboards, and seamless exports — all while keeping your sensitive financial data 100% private in the browser.

## ✨ Features

- **Smart File Upload**: Drag-and-drop or click to upload CSV, XLSX, or PDF files (PDF parsing simulated with realistic demo data)
- **AI-Powered Clarifying Questions**: After upload, answers 4 smart questions to tailor the analysis (reporting period, currency, focus area, anomaly sensitivity)
- **Executive KPI Dashboard**: Glanceable cards for Total Inflow/Outflow, Net Cash Flow, Transaction Count, Top Categories, Anomaly Flags with trend indicators and beautiful visualizations
- **Powerful Transactions View**: Sticky header table with sorting, global search, multi-filter chips (type, categories), amount & date range filters, pagination, and quick row drill-down modal with AI insights
- **One-Click Exports**: Export full KPI report as professional PDF or transactions + summary as XLSX
- **Premium UI/UX**: Institutional dark/light mode, gold accents, high-contrast typography, subtle shadows, fully responsive (desktop/tablet/mobile), keyboard accessible, ARIA labels
- **Privacy First**: 100% client-side processing. No data ever leaves your device. Perfect for confidential financial documents
- **Instant Demo**: Load sample portfolio data with one click to explore all features immediately
- **Sensible Defaults**: Dashboard works great even before answering questions

## 🛠 Tech Stack

- Next.js 16 (App Router) + React 19 + TypeScript
- Tailwind CSS 4 with custom premium theme
- TanStack React Table v8 (powerful data table)
- PapaParse, SheetJS (xlsx), jsPDF for file handling & exports
- Lucide React icons
- Fully accessible & responsive design

## 🚀 Getting Started

```bash
git clone https://github.com/Nero-PC/aether-financial-intelligence.git
cd aether-financial-intelligence
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Quick Demo
1. Click **"LOAD SAMPLE PORTFOLIO DATA"**
2. Review the auto-filled clarifying questions (or change them)
3. Click **"GENERATE EXECUTIVE DASHBOARD"**
4. Explore the beautiful KPI cards and switch to the **TRANSACTIONS** tab
5. Try filtering, sorting, searching, and exporting!

## 📦 Deploy to Production

### Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FNero-PC%2Faether-financial-intelligence)

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Nero-PC/aether-financial-intelligence)

**Manual Netlify Setup**:
1. Go to [Netlify](https://app.netlify.com) → "Add new site" → "Import an existing project"
2. Connect GitHub and select this repo
3. Build command: `npm run build`
4. Publish directory: `.next`
5. Deploy!

Netlify has first-class support for Next.js apps.

## 🔒 Security & Trust

- All parsing, normalization, KPI calculations, filtering, and exports happen **entirely in your browser**
- No backend, no API keys, no data exfiltration
- Ideal for banks, funds, accountants, and anyone handling sensitive financial statements
- SOC 2 / GDPR ready architecture (client-only)

## 📸 Screenshots

*Dashboard with KPI cards and category breakdown*

*Transactions table with filters and drill-down*

*(Add real screenshots after deployment)*

## 🤝 Contributing

Pull requests welcome! This is a production-ready starter for financial intelligence tools.

## 📄 License

MIT License

---

Built with ❤️ for institutional finance professionals. Live demo coming soon via Netlify/Vercel deploy.