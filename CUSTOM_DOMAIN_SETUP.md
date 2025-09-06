# 🌐 Custom Domain Setup Guide - Hidden Profit Finder™
## Professional Branding for Your GitHub Pages Website

**Transform your GitHub Pages URL from `yourusername.github.io/hpf-assessment-github` to `hiddenprofitfinder.com` or any custom domain you own.**

---

## 🎯 Why Use a Custom Domain?

### Professional Benefits:
- ✅ **Brand Recognition:** `hiddenprofitfinder.com` vs `username.github.io/hpf-assessment-github`
- ✅ **Email Marketing:** Short, memorable URLs for campaigns
- ✅ **Business Credibility:** Professional domain builds trust
- ✅ **SEO Advantage:** Better search engine ranking
- ✅ **Social Media:** Clean URLs for sharing

### Cost-Effective:
- **Domain Cost:** $10-15/year (one-time annual fee)
- **Hosting Cost:** $0 (GitHub Pages remains free)
- **SSL Certificate:** $0 (automatic with GitHub Pages)
- **CDN & Performance:** $0 (included with GitHub Pages)

---

## 📋 Prerequisites

Before starting, you'll need:
- ✅ Your GitHub Pages site already deployed and working
- ✅ A domain name purchased from any registrar (GoDaddy, Namecheap, etc.)
- ✅ Access to your domain's DNS settings

---

## 🚀 Step-by-Step Setup (10 minutes total)

### Step 1: Configure GitHub Pages (2 minutes)

1. **Go to your GitHub repository** (`github.com/yourusername/hpf-assessment-github`)
2. **Click "Settings" tab**
3. **Scroll to "Pages" section** (left sidebar)
4. **In "Custom domain" field:**
   - Enter your domain: `hiddenprofitfinder.com`
   - Or use a subdomain: `finder.yourbusiness.com`
5. **Click "Save"**

### What GitHub Does Automatically:
- ✅ Creates a `CNAME` file in your repository
- ✅ Enables SSL certificate generation
- ✅ Sets up redirect handling

---

### Step 2: Configure Your Domain's DNS (5 minutes)

#### For Root Domain (e.g., hiddenprofitfinder.com):

**Add these A records to your DNS:**
```
Type: A
Name: @ (or leave blank)
Value: 185.199.108.153

Type: A  
Name: @ (or leave blank)
Value: 185.199.109.153

Type: A
Name: @ (or leave blank)  
Value: 185.199.110.153

Type: A
Name: @ (or leave blank)
Value: 185.199.111.153
```

#### For Subdomain (e.g., finder.yourbusiness.com):

**Add this CNAME record:**
```
Type: CNAME
Name: finder (or your chosen subdomain)
Value: yourusername.github.io
```

### Popular DNS Providers Instructions:

#### GoDaddy:
1. Login → My Products → DNS → Manage Zones
2. Click your domain → Add Record
3. Enter the A records or CNAME as shown above

#### Namecheap:
1. Domain List → Manage → Advanced DNS
2. Add New Record → Select A Record or CNAME
3. Enter values as shown above

#### Cloudflare:
1. Select your domain → DNS → Records
2. Add record → Choose A or CNAME
3. Enter values as shown above

---

### Step 3: Verify Setup (3 minutes)

1. **Wait 10-15 minutes** for DNS propagation
2. **Visit your custom domain** in a browser
3. **Check for HTTPS:** URL should show `https://yourdomain.com` with lock icon
4. **Test functionality:**
   - ✅ Landing page loads correctly
   - ✅ "Run Free Hidden Profit Finder" button works
   - ✅ Calendly booking link functions
   - ✅ Mobile responsiveness maintained

---

## 🔧 Recommended Domain Options

### For Hidden Profit Finder™:
- `hiddenprofitfinder.com` ⭐ (Brand-specific)
- `profitfinder.wiltsalexander.com` (Personal brand)
- `tools.alexanderscott.com` (Company subdomain)
- `simulator.evidencebasedstrategy.com` (Methodology focus)

### For Your Business:
- `wiltsalexander.com/finder` (Personal brand with path)
- `alexanderscott.com/tools` (Company with tools section) 
- `evidencebasedstrategy.com` (Methodology brand)

---

## 🎯 Professional Email Integration

Once your domain is set up, you can also create professional email addresses:

### Email Options:
- `wilts@hiddenprofitfinder.com`
- `contact@hiddenprofitfinder.com`  
- `strategy@hiddenprofitfinder.com`

### Email Providers:
- **Google Workspace:** $6/month per user (professional choice)
- **Microsoft 365:** $5/month per user
- **Zoho Mail:** $1/month per user (budget option)

---

## 📊 Business Impact of Custom Domain

### Marketing Benefits:
- **Short URLs for business cards:** `hiddenprofitfinder.com`
- **Clean social media sharing:** No long GitHub URLs
- **Professional email signatures:** Links match your domain
- **QR codes:** Easy to remember domain names

### Credibility Enhancement:
- **Client perception:** Professional domain builds trust
- **Email deliverability:** Custom domain improves inbox rates  
- **SEO benefits:** Domain authority for search ranking
- **Brand consistency:** All materials use same domain

### Cost-Benefit Analysis:
```
Annual Investment: $10-15 domain + $72 email (optional)
Benefits: Professional credibility, better conversion rates, 
         improved email deliverability, SEO advantages
ROI: Even 1 additional client covers costs for entire year
```

---

## ⚠️ Troubleshooting Common Issues

### "Domain not found" Error:
- **Wait longer:** DNS propagation can take 24-48 hours
- **Check DNS records:** Verify A records are correct
- **Clear browser cache:** Try incognito/private browsing

### "Not Secure" Warning:  
- **Wait for SSL:** GitHub takes 24 hours to issue SSL certificate
- **Check HTTPS enforcement:** Should be automatically enabled
- **Verify domain ownership:** Ensure CNAME file was created

### Site Not Loading:
- **Check repository name:** Must match exact domain setup
- **Verify GitHub Pages:** Ensure Pages is still enabled
- **Review Actions tab:** Look for deployment errors

### Mixed Content Warnings:
- **Update HTTP links:** Change any `http://` to `https://`
- **Check external resources:** Ensure all CDN links use HTTPS
- **Update API calls:** Verify all external services use HTTPS

---

## 🎉 Success Checklist

When everything is working correctly:

- ✅ **Custom domain loads:** `https://yourdomain.com`
- ✅ **SSL certificate active:** Green lock icon in browser
- ✅ **All functionality works:** Simulator, booking, forms
- ✅ **Mobile responsive:** Perfect on phones and tablets
- ✅ **Fast loading:** Quick response times globally
- ✅ **Professional appearance:** Branded URL everywhere

---

## 📧 Updated Marketing Copy with Custom Domain

### Email Campaign:
```
Subject: Hidden profits most SMBs miss (15-minute finder)

Try our free Hidden Profit Finder™:
https://hiddenprofitfinder.com

Professional analysis in 15 minutes.
Works on any device - no signup required.
```

### Business Card:
```
Wilts Alexander
"The CEO's Locksmith"
Evidence-Based Strategy Coaching™

Free Profit Assessment: hiddenprofitfinder.com
Strategy Session: calendly.com/coachwiltsalexander/30min
```

### Social Media:
```
🎯 New tool: Hidden Profit Finder™
💰 Find cost savings without layoffs  
⏱️ 15-minute business analysis
🔗 Try free: hiddenprofitfinder.com
#SmallBusiness #Strategy #AI
```

---

**🌐 Your Hidden Profit Finder™ now has a professional custom domain that builds credibility and enhances your Evidence-Based Strategy Coaching™ brand!**
