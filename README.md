# Skylimit Computers Website

A modern, responsive website for Skylimit Computers - a leading computer service center in Gaborone, Botswana.

## 📋 Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern Interface**: Clean and professional UI with smooth animations
- **Product Management**: Admin panel to add, edit, and manage products for sale
- **Image Gallery**: Display of repair services and work samples
- **WhatsApp Integration**: Direct WhatsApp contact button (+267 760 565)
- **SEO Optimized**: Comprehensive keyword optimization for search engines
- **Admin Dashboard**: Password-protected admin panel for product uploads
- **Slider**: Automatic image carousel on homepage
- **Fast Loading**: Optimized for performance

## 📁 Project Structure

```
skylimit-computers/
├── index.html              # Homepage with slider and featured products
├── about.html             # About Skylimit Computers page
├── services.html          # Detailed services page
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── main.js            # JavaScript functionality
├── admin/
│   ├── login.html         # Admin login page
│   └── dashboard.html     # Admin dashboard for managing products
└── README.md             # This file
```

## 🚀 Quick Start

### 1. Download the Website

1. Go to: https://github.com/EltonMatare/skylimit-computers
2. Click the green **Code** button
3. Select **Download ZIP**
4. Extract the downloaded file

### 2. Run Locally

#### Option A: Using VS Code (Recommended)
1. Open the folder in VS Code
2. Install **Live Server** extension
3. Right-click `index.html` and select **Open with Live Server**
4. Website opens at `http://localhost:5500`

#### Option B: Using Python
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```
Then open: http://localhost:8000

#### Option C: Using Node.js
```bash
npm install -g http-server
http-server
```
Then open the URL shown in terminal

### 3. Access Admin Panel

1. Navigate to: `http://localhost:5500/admin/login.html`
2. **Default Login:**
   - Username: `admin`
   - Password: `admin`
3. Click "Login" to access the dashboard

## 👨‍💼 Admin Panel Guide

### Features:
- **Dashboard**: View total products and stock
- **Add Product**: Upload new items with images and descriptions
- **Manage Products**: Edit or delete existing products
- **Change Password**: Update admin password
- **Logout**: Exit admin panel

### Adding Products:

1. Go to **Admin Panel** → **Add Product**
2. Fill in:
   - Product Name (e.g., "Lenovo IdeaPad 3")
   - Category (Laptops, Hardware, etc.)
   - Price
   - Stock Quantity
   - Description
   - Image URL (use free images from Unsplash)
3. Click **Add Product**
4. Product appears automatically on homepage

### Getting Product Images:

**Free Image Sources:**
- https://unsplash.com (search: laptop, printer, repair)
- https://pexels.com
- https://pixabay.com

**Example URLs:**
```
https://images.unsplash.com/photo-1588872657840-790ff3bde126?w=400&h=300&fit=crop
https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=400&h=300&fit=crop
```

## 🌐 Deploy to Internet

### Option 1: GitHub Pages (Free)

1. Already uploaded to GitHub? Skip to step 2
2. Go to repository **Settings**
3. Select **Pages**
4. Set Branch to **main**
5. Save
6. Website live at: `https://EltonMatare.github.io/skylimit-computers`

### Option 2: Netlify (Recommended)

1. Go to: https://netlify.com
2. Click **Drop site folder here** or connect GitHub
3. Upload the entire folder
4. Website is live immediately!
5. Get free domain or use custom domain

### Option 3: Vercel

1. Go to: https://vercel.com
2. Click **New Project**
3. Import from GitHub or upload folder
4. Deploy in seconds!

### Option 4: Traditional Hosting

1. Get hosting from: Hostinger, Bluehost, GoDaddy, etc.
2. Use FTP client (FileZilla) to upload all files
3. Keep exact folder structure
4. Website live at your domain

## 📱 Contact Information

- **Phone/WhatsApp**: +267 760 565
- **Email**: moses@skylimitcomputers.com
- **Location**: Main Mall, Gaborone (Next to KFC), Botswana

## 🔒 Security Notes

⚠️ **Important for Production:**
- Change default admin password immediately
- Use HTTPS when deployed online
- For production, implement proper backend authentication
- Never hardcode passwords in client-side code

### Change Default Password:

1. Open `admin/login.html`
2. Find this line: `const DEFAULT_PASSWORD_HASH = '8c6976e5b5410415bde908bd4dee15dfb167a9c873fc4bb8a81f6f2ab448a918'`
3. Use an online SHA256 hasher: https://www.tools.md5hashgenerator.com/
4. Hash your new password
5. Replace the hash value
6. Save file

## 🔍 SEO Keywords

The website includes 1000+ SEO keywords targeting:
- Laptops for sale (Gaborone, Botswana)
- Brand names: Lenovo, HP, Dell, ASUS
- Services: Laptop repair, screen replacement, data recovery
- Locations: Gaborone, Main Mall, Botswana towns
- Products: Desktop, SSD, RAM, Printer, POS equipment
- Repairs: Motherboard, keyboard, cellphone, software installation

### Manual SEO Optimization:

1. **Google Search Console**: https://search.google.com/search-console
   - Add your domain
   - Upload `sitemap.xml`
   - Submit for indexing

2. **Bing Webmaster Tools**: https://www.bing.com/webmasters
   - Add your domain
   - Verify ownership

3. **Local SEO**:
   - Add to Google My Business
   - Add to Apple Maps
   - Create Facebook Business Page

## 📊 Analytics

Add Google Analytics to track visitors:

1. Go to: https://analytics.google.com
2. Sign in with Gmail
3. Create new property
4. Copy tracking ID
5. Add to all HTML pages in `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_ID');
</script>
```

## 🔧 Customization

### Change Business Details:

1. **Phone/WhatsApp**: Search for `+267760565` or `77060565`
2. **Email**: Search for `moses@skylimitcomputers.com`
3. **Business Name**: Search for `Skylimit Computers`
4. **Location**: Search for `Gaborone` or `Main Mall`

### Change Colors:

Edit `css/style.css`:
```css
:root {
    --primary-color: #0066cc;    /* Change blue */
    --secondary-color: #ff6b6b;  /* Change red */
    --dark-bg: #1a1a1a;          /* Change dark */
}
```

### Change Fonts:

Edit `css/style.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

## 📧 Contact & Support

For questions or customization:
- Email: moses@skylimitcomputers.com
- WhatsApp: +267 760 565
- Phone: +267 760 565

## 📄 License

This website is created for Skylimit Computers. All rights reserved.

## 🎓 Tutorial Videos

- [How to Use Admin Panel](#)
- [Adding Products](#)
- [Deploying Online](#)
- [SEO Optimization](#)

---

**Created with ❤️ for Skylimit Computers**
**Gaborone, Botswana | 2024**