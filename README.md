# Stellar Chat & Pay Website

**The Revolution is a Conversation**

A modern, responsive landing page for Stellar Chat & Pay - the revolutionary platform that transforms conversations into instant global payments.

## 🌟 About

Stellar Chat & Pay is a peer-to-peer payments platform that embeds money transfers directly into chat interfaces. This repository contains the official website and landing page showcasing the product vision, features, and early adopter program.

## 🚀 Live Website

Visit the live website: [stellar-chat-pay.netlify.app](https://stellar-chat-pay.netlify.app)

## ✨ Features

- **Modern Design**: Clean, professional interface with ultraviolet gradient theme
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations and hover effects
- **Early Adopter Program**: Integrated signup form with Supabase backend
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Performance Focused**: Lightweight, fast-loading single-page design

## 🛠 Tech Stack

- **Frontend**: Pure HTML5, CSS3, and Vanilla JavaScript
- **Fonts**: Inter and Space Grotesk from Google Fonts
- **Database**: Supabase for early adopter form submissions
- **Hosting**: Netlify with automatic deployments from GitHub
- **Icons**: Custom SVG icons for scalability and performance

## 📁 Repository Structure

```
stellar-chat-pay-website/
├── index.html          # Main website file (complete single-page application)
├── README.md          # This file
└── .gitignore         # Git ignore rules (optional)
```

## 🎨 Design System

### Color Palette
- **Ultraviolet Primary**: `#5505A6`
- **Purple Deep**: `#290773`  
- **Navy Dark**: `#041A59`
- **Navy Deepest**: `#041340`
- **Blue Electric**: `#0A58BF`

### Typography
- **Primary**: Inter (body text, UI elements)
- **Secondary**: Space Grotesk (headings, display text)

## 🚀 Quick Start

### Prerequisites
- Git installed on your machine
- A modern web browser

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/CarolTea/stellar-chat-pay-website.git
cd stellar-chat-pay-website
```

2. **Open locally**
```bash
# Open with any local server (optional)
python -m http.server 8000
# or
npx serve .
# or simply open index.html in your browser
```

3. **View the website**
Open `http://localhost:8000` in your browser or directly open `index.html`

## 🔧 Configuration

### Supabase Integration
The early adopter form is connected to Supabase. The credentials are already configured in the code:

```javascript
const SUPABASE_URL = 'https://wafpquneawhncjrmqcgb.supabase.co';
const SUPABASE_ANON_KEY = 'your_anon_key_here';
```

### Database Schema
The form submits to the `early_adopters` table with these fields:
- `name` (varchar)
- `email` (varchar, unique)
- `whatsapp` (varchar)
- `country` (varchar)
- `created_at` (timestamp)

## 🚀 Deployment

### Automatic Deployment (Current Setup)
This repository is connected to Netlify for automatic deployments:
- **Trigger**: Every push to `main` branch
- **Build Command**: None (static HTML)
- **Deploy Directory**: `/` (root)

### Manual Deployment Options
- **Netlify**: Drag and drop `index.html`
- **Vercel**: Connect GitHub repository
- **GitHub Pages**: Enable in repository settings
- **Any Static Host**: Upload `index.html` file

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: 320px and up
- **Tablet**: 768px and up
- **Desktop**: 1024px and up
- **Large Desktop**: 1440px and up

## 🎯 Key Sections

1. **Hero Section**: Main value proposition and CTA
2. **Problem Statement**: "The World We Lost"
3. **Solution Overview**: Key features and benefits
4. **How It Works**: 3-step process explanation
5. **Target Audiences**: User personas and use cases
6. **Technology**: Stellar integration details
7. **Development Status**: Current project phase
8. **Early Adopter Program**: Signup form and benefits

## 🔄 Contributing

### Making Changes
1. Edit `index.html` directly
2. Test changes locally
3. Commit and push to `main` branch
4. Netlify will automatically deploy

### Code Style
- Use semantic HTML5 elements
- Follow CSS custom properties (CSS variables)
- Maintain consistent indentation (4 spaces)
- Comment complex CSS sections
- Keep JavaScript functions modular

## 📊 Analytics & Performance

- **Core Web Vitals**: Optimized for LCP, FID, and CLS
- **Accessibility**: Semantic markup and ARIA labels
- **SEO**: Complete meta tags and structured data
- **Performance**: Lightweight assets and minimal dependencies


## 📄 License

This project is the property of ChatPay Go Labs. All rights reserved.

## 📞 Contact

For questions about this website or the Stellar Chat & Pay project:
- **Website**: [stellar-chat-pay.netlify.app](https://stellar-chat-pay.netlify.app)
- **Early Adopter Program**: Use the form on the website
- **Development Team**: hello@chatpaygo.com

---

**"Digital Money, Humanly Simple"**

Made with ♥ by ChatPay Go Labs | 2025