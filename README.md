# 🔧 O&M Appliances Services Inc - Website

Professional appliance repair services website for O&M Appliances Services Inc, serving Yonkers, Westchester, Manhattan, Bronx, and Eastchester areas.

![O&M Appliances Services](https://img.shields.io/badge/Status-Active-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Table of Contents

- [Features](#features)
- [Services](#services)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Configuration](#configuration)
- [Deployment](#deployment)
- [Contact](#contact)
- [License](#license)

## ✨ Features

- **Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- **SEO Optimized** - Schema.org markup, meta tags, and semantic HTML
- **Fast Performance** - Optimized images and lazy loading
- **Accessibility** - WCAG 2.1 AA compliant
- **Multilingual** - English & Spanish support
- **Interactive Elements** - Animated carousels, parallax effects, scroll animations
- **Contact Forms** - EmailJS integration for form submissions
- **Analytics Ready** - Google Analytics 4 integration
- **Booking Integration** - PocketSuite booking system

## 🛠️ Services

- Refrigerator Repair
- Washer & Dryer Repair
- Dishwasher Repair
- Stove & Oven Repair
- Microwave & Hood Repair
- Professional Installation Services

## 🚀 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom animations and transitions
- **TailwindCSS** - Utility-first CSS framework
- **JavaScript (ES6+)** - Modern vanilla JavaScript
- **EmailJS** - Email service integration
- **Google Analytics 4** - Analytics tracking
- **Font Awesome 6.4.0** - Icon library

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/om-appliances-website.git
cd om-appliances-website
```

### 2. Open the Website

Simply open `index.html` in your browser:

```bash
open index.html
```

Or use a local server (recommended):

```bash
# Using Python 3
python3 -m http.server 8000

# Then visit: http://localhost:8000
```

## ⚙️ Configuration

### EmailJS Setup

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Create an email service
3. Create an email template
4. Update the following in `index.html`:

```javascript
// Line ~1819
emailjs.init("YOUR_EMAILJS_PUBLIC_KEY");

// Line ~1850
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams)
```

### Google Analytics Setup

Update your Google Analytics ID:

```javascript
// Line ~1956
gtag('config', 'G-XXXXXXXXXX');
```

Replace with your actual GA4 measurement ID.

### Contact Information

Update these values in the HTML:

- **Phone:** `1-800 284 1616`
- **WhatsApp:** `+13475970420`
- **Email:** `omapplianceservices@gmail.com`
- **PocketSuite:** `https://pocketsuite.io/link/om-appliance-services-inc`

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select branch: `main`
4. Select folder: `/ (root)`
5. Click Save
6. Your site will be live at: `https://YOUR_USERNAME.github.io/om-appliances-website/`

### Netlify

1. Push your code to GitHub
2. Go to [Netlify](https://www.netlify.com/)
3. Click "New site from Git"
4. Select your repository
5. Deploy!

### Custom Domain

1. Add your custom domain in GitHub Pages or Netlify settings
2. Update DNS records:
   - A Record: Point to GitHub/Netlify IP
   - CNAME: www → your-site.github.io

## 📁 File Structure

```
om-appliances-website/
├── index.html                      # Main website file
├── hero-background.jpg.png         # Hero section background image
├── README.md                       # This file
└── INSTRUCCIONES_WORDPRESS.md     # WordPress deployment guide
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Color Scheme

- **Primary Blue:** `#2563EB`
- **Primary Dark:** `#1E40AF`
- **Secondary Amber:** `#F59E0B`
- **Success Green:** `#10B981`
- **Gray Dark:** `#1F2937`

## 📞 Contact

**O&M Appliances Services Inc**

- 📱 Phone: 1-800 284 1616
- 💬 WhatsApp: [Chat with us](https://wa.me/13475970420)
- 📧 Email: omapplianceservices@gmail.com
- 🗓️ Book: [PocketSuite](https://pocketsuite.io/link/om-appliance-services-inc)

**Service Areas:**
- Manhattan, NY
- Yonkers, NY
- Bronx County, NY
- Westchester County, NY
- Eastchester, NY

## 📄 License

© 2025 O&M Appliances Services Inc. All rights reserved.

## 🙏 Acknowledgments

- Icons by [Font Awesome](https://fontawesome.com/)
- Images from [Unsplash](https://unsplash.com/)
- CSS Framework by [TailwindCSS](https://tailwindcss.com/)

---

**Built with ❤️ for O&M Appliances Services Inc**

For questions or support, please contact: omapplianceservices@gmail.com

