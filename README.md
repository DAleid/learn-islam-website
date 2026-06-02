# Noor Al-Islam

A multilingual website introducing Islam to a general audience, built with Next.js 14. Supports English and Arabic with full RTL layout.

## Overview

Noor Al-Islam offers a clear, accessible introduction to the fundamentals of Islam — what it is, its five pillars, and answers to frequently asked questions. Designed to be welcoming, readable, and culturally respectful.

## Pages

| Route | Description |
|-------|-------------|
| `/` | Hero section with Quranic verse and site introduction |
| `/what-is-islam` | Overview of Islamic beliefs and values |
| `/pillars` | The five pillars of Islam explained |
| `/faq` | Common questions and answers about Islam |

## Features

- Bilingual support: **English** and **Arabic**
- Full **RTL layout** for Arabic
- Dynamic i18n routing (`/en/...`, `/ar/...`)
- Responsive design with **Tailwind CSS**
- SEO-friendly with **Next.js App Router**

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Framework | Next.js 14 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS |
| i18n | next-intl |
| Deployment | Vercel |

## Getting Started

```bash
git clone https://github.com/DAleid/islam-dawah-site.git
cd islam-dawah-site
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Project Structure

```
app/
  [locale]/
    page.tsx          # Home
    what-is-islam/    # What is Islam
    pillars/          # Five Pillars
    faq/              # FAQ
locales/
  en.json             # English translations
  ar.json             # Arabic translations
components/           # Navbar, Footer, HeroSection, ...
```

## License

MIT License