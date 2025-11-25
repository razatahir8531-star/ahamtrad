# AHA Developers & Estate - Admin Panel Guide

## Accessing the Admin Panel

### Login Page
Navigate to: `/admin-login`

**Default Credentials:**
- Username: `aha_admin`
- Password: `Aha@2000!`

After successful login, you'll be redirected to the admin dashboard at `/admin`.

---

## Admin Dashboard Features

### 1. Properties Tab
Manage all property listings from this section.

#### Adding a New Property

Click "Add Property" to open the Blogger-style property editor with the following sections:

**Basic Information:**
- Title (required)
- Slug (auto-generated from title, but editable)
- Price in PKR (required)
- Type: Sale or Rent
- Status: Draft or Published (only Published properties appear on the Properties page)
- Location Address (required)

**Property Details:**
- Bedrooms
- Bathrooms
- Area (sq ft)
- Parking spaces
- Furnishing: Furnished/Semi-Furnished/Unfurnished

**Features:**
Select from checkboxes:
- Air Conditioning
- Heating
- Balcony
- Garden
- Swimming Pool
- Gym
- Security System
- Parking
- Elevator
- Furnished
- Pet Friendly
- Internet/WiFi

**Description (Blogger-Style Editor):**
- Short Excerpt: Brief summary (150-200 characters)
- Full Description: Rich text editor with formatting toolbar
  - Bold, Italic, Underline, Strike-through
  - Headers (H1, H2, H3)
  - Ordered and Bullet Lists
  - Text Color and Background Color
  - Text Alignment
  - Links and Images (insert from URL)
- Tags: Comma-separated (e.g., "luxury, modern, spacious")

**Media:**
- Images: Click or drag & drop to upload multiple images
  - First image becomes the featured image automatically
  - Remove unwanted images with the X button
- Video URL: Paste YouTube or Vimeo link

**Publishing:**
- Click "Create Property" to save as Draft
- Set Status to "Published" before saving to make it visible on the Properties page
- After saving, published properties immediately appear on `/properties`

#### Editing Properties
- Click on any property in the list to edit
- All fields can be updated
- Click "Update Property" to save changes

#### Deleting Properties
- Click the delete button on any property
- Confirm deletion in the modal
- Property and all associated images will be removed

---

### 2. Reviews Tab
Manage customer reviews submitted through the website.

- Approve or deny pending reviews
- Add admin replies to reviews
- Mark reviews as featured

---

### 3. Settings Tab
Update your admin account settings:

**Change Password:**
If you see "Password Change Required" notification on first login, go to Settings to update your password.

**Contact Information:**
Update the admin contact email and phone number.

---

## How Properties Appear on the Website

1. **Draft Properties:** Saved but NOT visible on the public Properties page
2. **Published Properties:** Immediately visible at `/properties` after saving

The Properties page shows:
- Property title
- Price
- Location
- Featured image
- Short excerpt
- View Details button → links to individual property detail page

---

## Property Detail Pages

Each published property gets its own detail page with:
- Image gallery (all uploaded images)
- Full description with formatting (from WYSIWYG editor)
- Property features
- Video (if YouTube/Vimeo URL provided)
- Location map
- Contact buttons (WhatsApp, Phone, Inquiry)

---

## Troubleshooting

### Login Issues
- Make sure you're using: `aha_admin` / `Aha@2000!`
- If login fails, check the browser console for errors
- Clear browser cache and try again

### Properties Not Showing
- Verify Status is set to "Published" (not "Draft")
- Check browser console for any errors
- Make sure you saved the property successfully (look for "Success" notification)

### Image Upload Issues
- Supported formats: JPG, PNG, WEBP
- Multiple images can be uploaded at once
- Images are displayed as thumbnails in the editor

---

## Security Notes

**IMPORTANT for Production:**
1. Change the default password immediately after first login
2. Use a strong password (min 8 characters, mix of letters, numbers, symbols)
3. Keep your credentials secure
4. Do not share admin access

---

## Contact Support

For technical issues or questions:
- Developer: Muhammad Tahir Raza
- WhatsApp: +92 304 4953802
- Email: Contact via WhatsApp

---

## Quick Reference

| Action | Path |
|--------|------|
| Login | `/admin-login` |
| Dashboard | `/admin` |
| Public Properties | `/properties` |
| View Property Detail | `/properties/:id` |

**Default Credentials:**
```
Username: aha_admin
Password: Aha@2000!
```
