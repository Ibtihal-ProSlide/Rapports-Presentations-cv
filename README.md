# ProSlide.ma – Freelance Services Website 🇲🇦

A **mobile-first, one-page** freelance services website written entirely in **Darija** (Moroccan dialect in Latin script). Built for a professional offering presentations, reports, and CV services.

---

## ✅ Completed Features

- **Hero Section** – Big title, description, animated floating cards, stats, dual CTA buttons
- **Services Section** – 6 service cards (PPT, Rapport de stage, Rapports, Slides, CV Pro, Pack Complet) with WhatsApp CTAs
- **How It Works** – 3-step visual process guide
- **Portfolio/Khadmati** – 6 portfolio cards with hover overlay & WhatsApp CTA
- **Why Choose Me** – 4 reason cards with icons
- **Testimonials** – 3 client reviews with 5-star ratings
- **CTA Section** – Final call-to-action with gradient background
- **Floating WhatsApp Button** – Always visible, pulsing animation
- **Mobile-first responsive design** – Works on all screen sizes
- **Hamburger mobile menu** – Smooth open/close
- **Scroll reveal animations** – Elements fade in as user scrolls
- **Navbar scroll effect** – Shadow on scroll
- **Active nav link highlight** – Highlights current section

---

## 📌 Entry URIs

| Path | Description |
|------|-------------|
| `/` or `index.html` | Main one-page site |
| `#home` | Hero section |
| `#services` | Services cards |
| `#how-it-works` | Process steps |
| `#portfolio` | Portfolio gallery |
| `#why-me` | Reasons to choose |
| `#testimonials` | Client testimonials |
| `#cta` | Final call-to-action |

---

## ⚙️ Configuration

In `index.html`, update the following in the `<script>` section:

```javascript
const PHONE_NUMBER = "212600000000"; // ← Replace with your real WhatsApp number (no +)
```

All WhatsApp links auto-generate a pre-filled message like:
> _"Salam, bghit service dyal CV Pro 🙏 Wa9ash 7adar?"_

---

## 🎨 Design System

- **Primary color**: `#6C63FF` (Purple)
- **Accent**: `#FF6584` (Pink)
- **Success/WhatsApp**: `#25D366` (Green)
- **Font**: Poppins + Cairo
- **Mobile-first breakpoints**: 500px, 768px, 900px

---

## 🚀 Next Steps (Recommended)

1. **Replace phone number** with real WhatsApp number
2. **Add real portfolio images** (replace emoji placeholders with actual work screenshots)
3. **Add Google Analytics** for tracking
4. **Customize colors** to match personal brand
5. **Add pricing section** if desired
6. **Connect a contact form** (Formspree or Netlify Forms)
7. **Add real client photos** in testimonials section
