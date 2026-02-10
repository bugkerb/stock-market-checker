# Stock Market Open/Close Checker

A lightweight, one-page application to check real-time status of major stock exchanges worldwide.

## Features

- ✅ **Real-time Status** - Check if markets are open/closed
- 🌍 **6 Major Markets** - NYSE, NASDAQ, LSE, TSE, HKEX, SSE
- ⏰ **Timezone-Aware** - Uses `date-fns-tz` for accurate local times
- 🔄 **Auto-Refresh** - Updates every 90 seconds (with live clock every second)
- 📱 **Responsive Design** - Works on desktop and mobile
- 🚀 **Fast Loading** - CDN-based libraries, loads in < 2 seconds
- 🔍 **SEO-Optimized** - Proper meta tags for search engines

## Supported Markets

1. **NYSE** (New York Stock Exchange) - America/New_York
2. **NASDAQ** - America/New_York
3. **LSE** (London Stock Exchange) - Europe/London
4. **TSE** (Tokyo Stock Exchange) - Asia/Tokyo
5. **HKEX** (Hong Kong Stock Exchange) - Asia/Hong_Kong
6. **SSE** (Shanghai Stock Exchange) - Asia/Shanghai

## Tech Stack

- **HTML5** - Single-page application
- **JavaScript (Vanilla)** - No framework dependencies
- **date-fns-tz** - Timezone handling via CDN
- **Vercel** - Hosting platform

## Deployment

### Vercel Deployment

1. Create a new project on Vercel
2. Import this repository
3. Deploy (Vercel will detect it as a static site)

### Local Development

Simply open `index.html` in a browser:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

## Constraints Met

- ✅ One-Page Only
- ✅ Fast Loading (< 2 seconds)
- ✅ Auto-refresh every 90 seconds
- ✅ SEO-Friendly with meta tags
- ✅ Responsive design

## Future Enhancements (Phase 2)

- Holiday handling (currently ignored per Phase 1 requirements)
- More markets
- User preferences (favorite markets)
- Notifications for market open/close
- Historical trading hours data

## License

MIT License - Free for commercial and personal use

---

Built with ❤️ for the Incubator Startup Program