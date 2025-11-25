# AHA Developers & Estate

A modern, mobile-first real estate website for AHA Developers & Estate, featuring a clean public-facing website and a powerful admin panel for property management.

## 🌐 Website Features

### Public Pages
1. **Home** (`/`) - Hero section, featured properties, testimonials, and contact CTAs
2. **About** (`/about`) - Company information and team details
3. **Properties** (`/properties`) - Browse all published properties
4. **Contact** (`/contact`) - Contact information and inquiry form

### Design
- **Brand Colors:** 
  - Primary Blue: `#114B8A`
  - Accent Gold: `#FFC857`
- **Fonts:** Poppins (headings), Inter (body)
- **Mobile-First:** Fully responsive design optimized for all devices

### Contact Integration
- **WhatsApp Floating Button:** Opens chat with Junaid (+92 305 1213339) - appears on all pages
- **Book Consultation Buttons:** All link directly to WhatsApp for instant contact
- **Phone & Email:** Click-to-call and click-to-email functionality throughout

---

## 🔐 Admin Panel Access

### Login
**URL:** `/admin-login`

**Default Credentials:**
```
Username: aha_admin
Password: Aha@2000!
```

⚠️ **IMPORTANT:** Change the password immediately after first login in the Settings tab!

---

## 📝 How to Add Properties (Blogger-Style Editor)

The admin panel features a rich text editor that works **exactly like Blogger**!

### Step-by-Step Guide:

1. **Login** at `/admin-login` with `aha_admin` / `Aha@2000!`
2. Go to the **Properties** tab
3. Click **"Add Property"** button
4. Fill in the property information:

#### Basic Details
- **Title:** Property name (e.g., "Luxury 3 Bedroom Villa in DHA")
- **Price:** Property price in PKR
- **Type:** Sale or Rent
- **Status:** 
  - **Draft** = Not visible on website (work in progress)
  - **Published** = Immediately visible on Properties page ✅
- **Location:** Full address
- **Bedrooms, Bathrooms, Area, Parking**

#### Description (Blogger-Style Editor) ✨
Write your property description **just like writing a blog post!**

**You can:**
- ✅ Make text **Bold**, *Italic*, Underline
- ✅ Add H1, H2, H3 headings
- ✅ Create numbered or bullet lists
- ✅ Change text colors
- ✅ Insert images from URLs (click 🖼️ icon)
- ✅ Add links
- ✅ Format paragraphs
- ✅ Align text left/center/right

**Example:**
```
# Beautiful Family Home

This stunning property features:
- 3 spacious bedrooms
- Modern kitchen with appliances
- Beautiful garden
- Prime location

Contact us today!
```

#### Upload Media
- **Images:** Drag & drop multiple images at once
  - First image = Featured image
  - Hover to delete unwanted images
- **Video:** Paste YouTube or Vimeo URL

#### Features & Tags
- Check off amenities (AC, Pool, Gym, etc.)
- Add tags: `luxury, modern, dha, lahore`

5. **Set Status to "Published"** (Important!)
6. Click **"Create Property"**
7. **Your property is now live!** Visit `/properties` to see it

---

## 🚀 Publishing Properties

### Draft vs Published
- **Draft:** Saved but NOT visible to public
- **Published:** Appears immediately on:
  - Properties page (`/properties`)
  - Home page featured section
  - Property detail page (`/properties/your-slug`)

### To Publish:
1. Set Status to **"Published"**
2. Click **"Create Property"** or **"Update Property"**
3. Property goes live instantly!

---

## ✏️ Editing & Deleting Properties

### Edit
1. Go to Properties tab
2. Click **"Edit"** on any property
3. Make changes
4. Click **"Update Property"**

### Delete
1. Click **"Delete"** button
2. Confirm deletion
3. Property and images removed permanently

---

## 🔒 Admin Panel Features

### 1. Properties Management
- Add, edit, delete properties
- Blogger-style rich text editor
- Drag & drop image uploads
- Video embedding
- Draft/Published status

### 2. Reviews Management
- Approve/deny customer reviews
- Add admin replies
- Feature top reviews

### 3. Settings
- Change admin password
- Update contact information

---

## 📞 Contact Information

### Primary Contact (Junaid)
- **Phone:** +92 305 1213339
- **WhatsApp:** https://wa.me/923051213339
- **Email:** junaidkhanp7@gmail.com

### Website Developer
- **Name:** Muhammad Tahir Raza
- **Phone:** +92 304 4953802
- **WhatsApp:** https://wa.me/923044953802

---

## 🛠️ Technical Stack

- **Frontend:** React, TypeScript, Tailwind CSS
- **Backend:** Lovable Cloud (Supabase)
- **Editor:** ReactQuill (Blogger-style)
- **Database:** PostgreSQL
- **Authentication:** Supabase Auth

---

## 🆘 Troubleshooting

### Can't login?
- Use: `aha_admin` / `Aha@2000!`
- Clear browser cache
- Try incognito/private browsing

### Properties not showing?
- Make sure Status is **"Published"** (not Draft)
- Refresh the Properties page
- Clear cache

### WhatsApp not opening?
- Ensure WhatsApp is installed on your device
- Or use WhatsApp Web in browser
- All links use `https://wa.me/` format

### Images not uploading?
- Keep images under 5MB
- Use JPG, PNG, or WebP
- Try uploading one at a time

### Video not showing?
- Use YouTube or Vimeo URLs only
- Videos appear on property detail pages
- Example: `https://www.youtube.com/watch?v=VIDEO_ID`

---

## 📚 Full Documentation

For detailed admin instructions, see [ADMIN_GUIDE.md](./ADMIN_GUIDE.md)

---

## 🎯 Quick Start Checklist

- [x] Login at `/admin-login`
- [x] Use `aha_admin` / `Aha@2000!`
- [x] Change password in Settings
- [x] Click "Add Property"
- [x] Fill property details
- [x] Write description in Blogger-style editor
- [x] Upload images (drag & drop)
- [x] Add video URL (optional)
- [x] Set Status to "Published"
- [x] Click "Create Property"
- [x] Visit `/properties` to see it live!

---

## 🏢 About AHA Developers & Estate

**Founded:** 2000  
**Founder:** Haji Muhammad Haneef Khan

**Specialization:**
- Residential & Commercial Properties
- Transparent Transactions
- Local Expertise in Pakistan

**Offices:**
- 71-B Central Park Housing Scheme, Lahore
- DHA Phase 6, Lahore
- Ittefaq Market, Khudian Khas

---

## 🔒 Security Notes

**For Production:**
1. ✅ Change default password immediately
2. ✅ Use strong password (8+ chars, mixed)
3. ✅ Enable HTTPS
4. ✅ Backup database regularly
5. ✅ Monitor admin access

---

## 📝 Key Features

✨ **Admin Panel:**
- Blogger-style rich text editor
- Drag & drop image uploads
- Video embedding
- Draft/Publish workflow
- Mobile-friendly interface

🌐 **Public Website:**
- Mobile-first responsive design
- WhatsApp integration on all pages
- Fast loading times
- SEO-optimized
- Clean, modern design

---

**Website Developed by Muhammad Tahir Raza**  
📞 +92 304 4953802 | 💬 https://wa.me/923044953802

---

## 📦 Deployment

Visit [Lovable](https://lovable.dev/projects/92c3aa8e-d63d-45a0-b790-6e036ddb900d) and click **Share → Publish** to deploy your site.

## 🌐 Custom Domain

Navigate to **Project > Settings > Domains** to connect your custom domain.