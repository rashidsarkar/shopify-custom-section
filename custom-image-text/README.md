# Shopify Custom Section - Image & Text Split

This is a **Shopify section** that displays an image and text side-by-side, with dynamic alignment and responsive behavior.  
You can configure the image width, alignment (left/right), text alignment, button, and colors directly in the Shopify editor.

---

## 📸 Preview

![Preview](assets/preview.png)

---

## 📂 Installation

1. Copy the file `custom-image-text.liquid` into your theme’s **sections** folder.
2. Go to Shopify **Theme Editor** → **Add Section**.
3. Search for **Custom-image-text** and add it to your page.
4. Configure:
   - Upload desktop & mobile images
   - Adjust image width (%)
   - Set text alignment (left, center, right)
   - Choose colors for text and button
   - Add optional button with link

---

## ⚙️ Features
- ✅ Responsive (desktop + mobile support)  
- ✅ Adjustable image width (30–70%)  
- ✅ Vertical & horizontal text alignment options  
- ✅ Supports kicker text, title, body, and CTA button  
- ✅ Uses Shopify schema settings for customization  

---

## 🖼️ Schema Example
The section comes with full **JSON schema** for Shopify customization.

```json
{
  "name": "Custom-image-text",
  "settings": [
    { "type": "image_picker", "id": "image", "label": "Desktop Image" },
    { "type": "image_picker", "id": "image_mobile", "label": "Mobile Image" },
    { "type": "range", "id": "image_width", "label": "Image width (%)", "min": 30, "max": 70, "default": 50 }
  ]
}
