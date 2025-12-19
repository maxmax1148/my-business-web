# Netflix Business Website

เว็บไซต์ตัวอย่างสำหรับธุรกิจ Netflix พัฒนาเพื่อการเรียนรู้ **HTML5 + CSS3**  
โดยเน้นการใช้ **CSS Fundamentals, Responsive Design และ Layout Systems** 

---


### 1. Homepage (index.html)
- Header + Logo + Navigation
- Hero Section (Full screen)
- Featured Services
- Footer

### 2. About Page (about.html)
- Company Story
- Team Members (ใช้ `<figure>` และ `<figcaption>`)
- Vision & Mission

### 3. Services Page (services.html)
- Services List (`<section>` + `<article>`)
- Pricing Comparison Table

### 4. Contact Page (contact.html)
- Contact Form (Flex layout)
- Company Address
- Google Maps Embed

---

### CSS Fundamentals
- Universal Selector & Reset
- Element Selectors (`h1–h4`, `p`, `a`)
- Class Selectors (`.hero`, `.card`, `.btn`, `.section`)
- ID Selectors (`#header`, `#footer`)
- Pseudo-classes (`:hover`, `:active`, `:first-child`, `:nth-child`)
- CSS Variables (`:root`)

### CSS Units & Responsive Design
- **px**: border, box-shadow
- **rem**: typography, spacing
- **%**: container width, images
- **vw / vh**: hero section, responsive text
- Responsive images (`max-width: 100%`)

### Colors & Typography
- Custom color palette (primary, secondary, accent, neutral)
- Web-safe fonts
- Font hierarchy (h1 > h2 > h3 > p)
- Line-height 1.6 for readability
- Text effects (uppercase, letter-spacing, shadow optional)

### Box Model
- Padding, margin, border, border-radius
- Card layout with shadow
- Container centered with max-width

### Positioning
- Sticky header navigation
- Absolute positioning for hero content
- Fixed elements (Back to Top, Chat Widget)
- Z-index layering

### Layout Systems
- Flexbox (navigation, services, forms)
- CSS Grid (team members)
- Responsive multi-column layouts

### Hover & Interaction Effects
- Button hover & active effects
- Card hover animation
- Navigation underline animation
- Smooth transitions

---

## Code Quality & Best Practices

- Organized CSS sections with comments
- Kebab-case naming conventions
- Reusable components (`.btn`, `.card`, `.section`)
- No unused CSS rules
- Clean and readable code

---

## Development Tools

- Visual Studio Code
- Live Server Extension
- Git & GitHub

---

## Git Commit Strategy

- Commit ทุกครั้งเมื่อเสร็จแต่ละส่วน
- ใช้ commit message ที่มีความหมาย เช่น:
  - `style: add typography and color palette`
  - `feat: add hover and interaction effects`
  - `refactor: reorganize styles.css`

---

## Deployment

- Push source code ไปยัง GitHub repository
- ใช้ Live Server สำหรับ local development

---

## Author

จัดทำเพื่อการศึกษาในรายวิชา **Web Development (HTML & CSS)**
