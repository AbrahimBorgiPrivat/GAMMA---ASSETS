# 🎨 GAMMA - ASSETS

This repository contains shared static assets, images, and resources used across GamMa projects — including newsletters, websites, and internal communication materials.

---

## 📁 Project Structure

```
/res
│
├── /img
│   └── /mails
│       └── GamMa Julefrokost Bjælke.jpg   # Banner image used for GamMa email campaigns
│
└── /src
    └── (reserved for future source files)
```

---

## 🧩 Purpose

The **GAMMA - ASSETS** repository acts as a centralized location for all non-code resources:
- Newsletter and event banner images  
- Icons, logos, and reusable visual elements  
- Static resources shared between GamMa projects

These assets are typically linked in HTML-based newsletters and on the [GamMa website](https://gam-ma.dk).

---

## 📨 Email Banner Example

Example usage of the **GamMa Julefrokost Bjælke** image in an HTML email:

```html
<a href="https://gam-ma.dk/" target="_blank" style="text-decoration:none;display:block;">
  <img src="https://raw.githubusercontent.com/GamMaDK/gamma-assets/main/res/img/mails/GamMa%20Julefrokost%20Bj%C3%A6lke.jpg" 
       alt="GamMa julefrokost banner" 
       width="100%" 
       style="display:block;border:0;outline:none;text-decoration:none;height:auto;">
</a>
```

*(If hosted in this repository, replace the URL with your actual public path.)*

---

## 🧱 Contribution Guidelines

1. Use descriptive filenames and folder names (no spaces preferred).  
2. Store assets in appropriate subdirectories (`/img/mails`, `/img/web`, etc.).  
3. Keep all source files optimized (e.g., compressed `.jpg` or `.png`).  
4. Do **not** store sensitive or personal data in this repository.  

---

## 🗂️ Recommended Naming Convention

Use a consistent pattern for asset filenames:

```
<ProjectName>_<Purpose>_<ShortDescription>.<ext>
```

Example:
```
GamMa_Julefrokost_Bjaelke.jpg
GamMa_Fyraftenscafe_Header.png
```

---

## 🧠 Notes

- If assets are linked externally (e.g., in newsletters), ensure the repository or hosting location is public.  
- Avoid using Base64-encoded images in emails — link directly to hosted files for better deliverability and loading speed.

---

**Maintained by:** [GamMa Alumni Association](https://gam-ma.dk)  
**Last updated:** November 2025
