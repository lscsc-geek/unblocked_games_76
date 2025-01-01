# Unblocked Games 76 - Free Online Gaming Platform

A modern, fast, and user-friendly gaming platform built with Next.js 13+, TypeScript, and Tailwind CSS. This platform offers a wide selection of free online games that are accessible across all devices and browsers. Visit [unblockedgames76.store](https://unblockedgames76.store) to play now!

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Next.js](https://img.shields.io/badge/Next.js-13+-black.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)
![Website](https://img.shields.io/website?url=https%3A%2F%2Funblockedgames76.store)

## 🎮 Features

### Core Features
- **Multi-language Support**: Built-in support for multiple languages including English and Chinese
- **Modern UI/UX**: Clean and responsive design with smooth animations
- **Game Categories**: Well-organized game categories with intuitive navigation
- **Search Functionality**: Advanced search with real-time filtering
- **Game History**: Tracks recently played games for quick access
- **Responsive Design**: Optimized for all screen sizes and devices
- **SEO Optimized**: Built-in SEO best practices with dynamic meta tags
- **Performance Focused**: Optimized loading times and resource management

### Technical Features
- **App Router**: Utilizing Next.js 13+ app router for optimal performance
- **Server Components**: Leveraging React Server Components for better SEO and performance
- **TypeScript**: Full TypeScript support for better development experience
- **Tailwind CSS**: Modern utility-first CSS framework for styling
- **Analytics Integration**: Built-in Google Analytics and Microsoft Clarity support
- **AdSense Ready**: Integrated Google AdSense support
- **Dynamic Sitemap**: Automated sitemap generation for better SEO
- **Content Management**: Structured content organization with i18n support

## 🚀 Getting Started

### Prerequisites
- Node.js 18.0 or later
- npm or yarn package manager
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/unblocked-games-76.git
cd unblocked-games-76
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add the following:
```env
NEXT_PUBLIC_GA_ID=your-google-analytics-id
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) to view the application

### Project Structure

```
├── public/
│   ├── favicon_io/
│   ├── games/
│   └── images/
├── src/
│   ├── app/
│   │   ├── [lang]/
│   │   │   ├── games/
│   │   │   ├── search/
│   │   │   ├── tags/
│   │   │   └── layout.tsx
│   │   └── globals.css
│   ├── components/
│   ├── config/
│   ├── lib/
│   ├── types/
│   └── utils/
├── content/
│   └── games/
├── scripts/
└── locales/
```

## 🛠 Development

### Adding New Games

1. Create a new game directory in `content/games/`:
```bash
mkdir content/games/your-game-name
```

2. Add required game files:
```
your-game-name/
├── config.json
├── thumbnail.webp
└── i18n/
    ├── en.json
    └── zh.json
```

3. Update game configuration in `config.json`:
```json
{
  "id": "unique-game-id",
  "slug": "your-game-name",
  "iframeUrl": "game-url",
  "thumbnail": "/games/your-game-name/thumbnail.webp",
  "tags": ["category1", "category2"],
  "featured": false
}
```

### Localization

Add translations for each supported language in the i18n directory:

```json
{
  "title": "Game Title",
  "description": "Game description...",
  "instructions": "How to play...",
  "metaTitle": "SEO Title",
  "metaDescription": "SEO Description"
}
```

## 📈 Analytics and Monitoring

The platform includes built-in support for:
- Google Analytics 4
- Google AdSense
- Microsoft Clarity

To enable analytics, ensure you have added the correct tracking IDs in your environment variables.

## 🔧 Configuration

### Environment Variables

Required environment variables:
```env
NEXT_PUBLIC_GA_ID=           # Google Analytics ID
NEXT_PUBLIC_BASE_URL=https://unblockedgames76.store  # Production URL
```

### Build Configuration

The project uses Next.js configuration in `next.config.js`:
- Output: Standalone
- TypeScript: Strict mode enabled
- ESLint: Enabled during build
- Experimental features: Server Actions enabled

## 🚀 Deployment

### Production Build

Create a production build:
```bash
npm run build
# or
yarn build
```

### Deployment Platforms

The application can be deployed to:
- Vercel (Recommended)
- AWS
- Google Cloud
- Any platform supporting Node.js

### Vercel Deployment

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables
4. Deploy

## 🔍 SEO

The platform implements various SEO best practices:
- Dynamic meta tags
- Structured data
- Automated sitemap generation
- robots.txt configuration
- Open Graph tags
- Twitter Cards
- Custom domain: unblockedgames76.store
- SSL enabled
- Mobile-first indexing ready

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, please open an issue in the GitHub repository or contact us through [unblockedgames76.store](https://unblockedgames76.store).

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Vercel for hosting and deployment
- All contributors who have helped with the project

---

Built with ❤️ by [Your Name/Team]

© 2024 [unblockedgames76.store](https://unblockedgames76.store). All rights reserved.
