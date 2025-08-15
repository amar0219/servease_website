# Servease - Local Services Website

A modern, responsive website for Servease, a local services startup platform. Built with Next.js, TypeScript, and Tailwind CSS.

## 🎨 Design Features

- **Color Scheme:**
  - Primary: #2C5F2D (Forest Green)
  - Secondary 1: #A7C957 (Soft Lime Green)
  - Secondary 2: #F2F2F2 (Light Grey)

- **Typography:** Inter and Poppins fonts
- **Design:** Minimal and modern with excellent UX
- **Responsive:** Fully responsive across all devices

## 🚀 Features

- **Hero Section:** Compelling headline with call-to-action buttons
- **Services Showcase:** 6 main service categories with detailed descriptions
- **Features Section:** Platform benefits and how it works
- **Testimonials:** Customer reviews and ratings
- **Contact Form:** Interactive contact form with validation
- **Responsive Navigation:** Mobile-friendly navigation with hamburger menu
- **Modern Footer:** Comprehensive footer with links and social media

## 🛠️ Tech Stack

- **Framework:** Next.js 14 with App Router
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Fonts:** Inter and Poppins (Google Fonts)
- **Icons:** Emoji icons and SVG icons
- **Responsive Design:** Mobile-first approach

## 📦 Installation

1. **Install Node.js** (if not already installed):
   - Download from [nodejs.org](https://nodejs.org/)
   - Recommended version: 18.x or higher

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
servease-website/
├── src/
│   ├── app/
│   │   ├── globals.css          # Global styles and Tailwind imports
│   │   ├── layout.tsx           # Root layout component
│   │   └── page.tsx             # Homepage component
│   └── components/
│       ├── Header.tsx           # Navigation header
│       ├── Hero.tsx             # Hero section
│       ├── Services.tsx         # Services showcase
│       ├── Features.tsx         # Features and benefits
│       ├── Testimonials.tsx     # Customer reviews
│       ├── Contact.tsx          # Contact form
│       └── Footer.tsx           # Footer component
├── tailwind.config.js           # Tailwind configuration
├── next.config.js               # Next.js configuration
├── package.json                 # Dependencies and scripts
└── README.md                    # This file
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Customization

### Colors
The color scheme is defined in `tailwind.config.js`:
```javascript
colors: {
  primary: '#2C5F2D',      // forest green
  secondary1: '#A7C957',   // soft lime green
  secondary2: '#F2F2F2',   // light grey
}
```

### Content
- Update service categories in `src/components/Services.tsx`
- Modify testimonials in `src/components/Testimonials.tsx`
- Change contact information in `src/components/Contact.tsx`
- Update company details in `src/components/Footer.tsx`

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Development

### Adding New Components
1. Create new component in `src/components/`
2. Import and use in `src/app/page.tsx`
3. Follow the existing component structure

### Styling
- Use Tailwind CSS classes for styling
- Follow the established color scheme
- Maintain responsive design principles

## 🚀 Deployment

### Vercel (Recommended)
1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy automatically

### Other Platforms
- Netlify
- AWS Amplify
- DigitalOcean App Platform

## 📄 License

This project is created for demonstration purposes.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or support, please contact:
- Email: hello@servease.com
- Phone: (555) 123-4567

---

**Servease** - Connecting communities with trusted local service providers.
