
<p align="center">
  <img src="./logo-cinza.png" alt="fjunior-dev logo" width="300"/>
</p>

# ☁️ Loruki – Cloud Hosting for Everyone

**Educational Front-End Project** – A simulated cloud hosting platform landing page built with HTML5, CSS3, and responsive design principles.

---

## 🧭 1. Introduction / Overview

**Loruki** is an educational front-end project designed to emulate a modern cloud hosting platform.  
The goal is to demonstrate a professional and responsive landing page structure, using semantic HTML and modular CSS.

🔗 **Live Demo:** [loruki-web-app.netlify.app](https://loruki-web-app.netlify.app/)

### Key Highlights
- Semantic HTML5 structure  
- CSS Grid + Flexbox layout  
- Responsive design across devices  
- Integrated contact form via **Netlify Forms**  
- Modern typography (**Google Fonts – Lato**)  
- Visual icons from **Font Awesome**

---

## 🎯 2. Objectives & Scope

### Objectives
- Build a **modern, modular landing page** using only HTML and CSS.  
- Apply **responsive and reusable design principles**.  
- Integrate form handling using **Netlify**.  
- Showcase **visual hierarchy** and animation basics.

### Scope
Includes:
- Single-page structure (`index.html`)  
- Reusable utility CSS (`utilities.css`)  
- Responsive components for all sections  

Excludes:
- Backend integration  
- Dynamic API data  

---

## 🧱 3. Architecture & Technical Design

### Folder Structure
```
loruki-web-app/
│
├── index.html
├── estilos/
│   ├── style.css
│   └── utilities.css
└── images/
    ├── cli.png
    ├── cloud.png
    ├── logos/
    │   ├── node.png
    │   ├── python.png
    │   ├── csharp.png
    │   ├── ruby.png
    │   ├── php.png
    │   ├── scala.png
    │   └── clojure.png
```

### Technologies
| Technology | Description |
|-------------|-------------|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, layout, responsiveness |
| **Font Awesome** | Icon set integration |
| **Google Fonts (Lato)** | Typography |
| **Netlify Forms** | Form submission handling |
| **Flexbox & Grid** | Layout and alignment |

---

## 🧩 4. Interface & User Experience (UI / UX)

| Section | Description |
|----------|-------------|
| **Navbar** | Fixed top menu with links (Home, Features, Docs). |
| **Hero** | Headline, CTA button, and contact form. |
| **Stats** | Data-driven cards displaying deployments, storage, and projects. |
| **CLI Section** | Emphasizes simplicity with command-line illustration. |
| **Cloud Section** | Promotes cloud hosting services with CTA. |
| **Languages** | Grid of supported programming language logos. |
| **Footer** | Repeated navigation and social links. |

### 🎨 Color Palette

- **Primary:** `#047aed` <span style="display:inline-block; width:15px; height:15px; background-color:#047aed; border:1px solid #ccc; margin-left:6px;"></span>  
- **Secondary:** `#1c3fa8` <span style="display:inline-block; width:15px; height:15px; background-color:#1c3fa8; border:1px solid #ccc; margin-left:6px;"></span>  
- **Dark:** `#002240` <span style="display:inline-block; width:15px; height:15px; background-color:#002240; border:1px solid #ccc; margin-left:6px;"></span>  
- **Light:** `#f4f4f4` <span style="display:inline-block; width:15px; height:15px; background-color:#f4f4f4; border:1px solid #ccc; margin-left:6px;"></span>  

### Typography
- Font: **Lato**, 300 weight  
- High contrast white-on-blue text for readability

---

## ⚙️ 5. Implementation / Code

### Example – Hero Section
```html
<section class="hero">
  <div class="container grid">
    <div class="hero-text">
      <h1>Easier Deployment</h1>
      <p>Deploy web apps of all kinds...</p>
      <a href="features.html" class="btn btn-outline">Read More</a>
    </div>

    <div class="hero-form card">
      <h2>Request a Demo</h2>
      <form name="contact" netlify>
        <input type="text" name="name" placeholder="Name" required>
        <input type="text" name="company" placeholder="Company Name" required>
        <input type="email" name="email" placeholder="Email" required>
        <input type="submit" value="Send" class="btn btn-primary">
      </form>
    </div>
  </div>
</section>
```

### CSS Utilities (`utilities.css`)
Reused classes for quick spacing and layout:
```css
.my-2 { margin: 1.5rem 0; }
.py-3 { padding: 2rem 0; }
.alert { background-color: var(--light-color); padding: 10px 20px; }
```

### Animations
Defined keyframes:
- `slideInFromLeft`  
- `slideInFromRight`  
- `slideInFromTop`  
- `slideInFromBottom`

Used in hero and stats sections for soft entry effects.

---

## 📱 6. Responsiveness & Compatibility

| Device | Behavior |
|---------|-----------|
| **Desktop (≥1024px)** | Multi-column layout, sidebar form visible |
| **Tablet (768–1024px)** | Grids collapse, centered content |
| **Mobile (≤500px)** | Vertical stacking, simplified navbar |

Breakpoints:
```css
@media (max-width: 768px) { ... }
@media (max-width: 500px) { ... }
```

---

## 🧪 7. Testing & Quality

**Tested on:**
- ✅ Chrome, Edge, Firefox  
- ✅ Mobile (320px–1440px)  
- ✅ Netlify form submission  
- ✅ HTML and CSS validation (W3C)  

**Pending:**  
- Accessibility (ARIA roles)  
- Automated testing

---

## ☁️ 8. Deployment / Hosting / Infrastructure

**Platform:** [Netlify](https://www.netlify.com)  

**Steps:**
1. Push repository to GitHub  
2. Connect Netlify → select repo  
3. Netlify auto-builds static files  
4. Form handled by `netlify` attribute in `<form>`  

**Production URL:**  
🔗 [https://loruki-web-app.netlify.app/](https://loruki-web-app.netlify.app/)

---

## 🔧 9. Maintenance & Future Enhancements

| Area | Suggestions |
|-------|-------------|
| **Design** | Add dark mode |
| **Functionality** | Implement JS menu toggle |
| **Accessibility** | Improve ARIA labels |
| **Optimization** | Compress images, minify CSS |
| **Scalability** | Add multi-page routing |

---

## 🧾 10. References / Credits

- **Inspiration:** Front-End Crash Course – *Brad Traversy*  
- **Icons:** [Font Awesome](https://fontawesome.com)  
- **Fonts:** [Google Fonts – Lato](https://fonts.google.com/specimen/Lato)  
- **Hosting:** [Netlify](https://www.netlify.com)  
- **Developed by:** *FJunior Dev · 2025*  

---
