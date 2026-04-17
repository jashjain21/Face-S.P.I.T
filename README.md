# 🎓 F.A.C.E. — S.P.I.T. Computer Engineering Committee Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-3-7952B3?logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-3.2-0769AD?logo=jquery&logoColor=white)

## 🚀 Overview

The official website for F.A.C.E. (the techno-cultural committee of the Computer Engineering Department at S.P.I.T. — Sardar Patel Institute of Technology, Mumbai). A single-page responsive website showcasing the committee's events, team members, image gallery, testimonials, and contact information. Built with Bootstrap, jQuery, and CSS animations.

## ✨ Features

- **Single-Page Scrolling Navigation** — Smooth-scroll navbar linking to Home, About, Gallery, Team, Events, Upcoming Events, and Contact sections
- **Parallax Hero Header** — Background image with parallax scrolling effect using `data-intensity` attributes
- **About Section** — Committee description covering tech events, workshops/webinars, and non-tech events (monsoon trek, FACE Cup, Branch Day)
- **Animated Counters** — Stats section with animated counters: Founded 2012, 50+ successful events, 1000+ participants, 11 team members
- **Image Gallery** — Filterable portfolio grid with Fancybox lightbox for full-size image viewing
- **Team Section** — 12 team member cards with photos and roles
- **Testimonials Carousel** — Owl Carousel slider with committee member testimonials
- **Events Section** — Blog-style event cards with descriptions
- **Contact Form** — Name, email, and message fields
- **Preloader** — Animated loading screen before content renders
- **CSS Animations** — WOW.js + Animate.css for scroll-triggered fade-in/slide-up animations

## 🛠 Tech Stack

| Component | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3, Bootstrap 3 |
| Animations | Animate.css, WOW.js |
| Carousel | Owl Carousel |
| Lightbox | jQuery Fancybox |
| Scrolling | jQuery Easing, parallax |
| Fonts | Google Fonts (Lato, Lobster, Oleo Script, Marck Script) |
| Icons | Font Awesome |

## 🏗 Structure

```
Face-S.P.I.T/
├── index.html              # Main single-page website
├── css/                    # Stylesheets (Bootstrap, theme, animations)
├── js/                     # jQuery, Fancybox, Owl Carousel, WOW.js
├── images/                 # Team photos, gallery, backgrounds
├── font-awesome/           # Icon fonts
└── dsahathemes.in/         # Original template source (dark theme)
```

## ⚡ Getting Started

```bash
git clone https://github.com/jashjain21/Face-S.P.I.T.git
cd Face-S.P.I.T

# Open in browser
open index.html
```

No build step or server required — it's a static HTML site.

## 📌 Sections

| Section | Description |
|---|---|
| Home | Parallax hero with committee name and CTA |
| About | Committee mission — tech events, workshops, non-tech activities |
| Services | Event categories: Tech, Non-Tech, Workshops/Webinars |
| Counter | Animated stats: est. 2012, 50+ events, 1000+ participants, 11 team members |
| Gallery | Filterable image grid with Fancybox lightbox |
| Team | 12 member cards with photos and designations |
| Testimonials | Owl Carousel with member quotes |
| Events | Event cards with descriptions |
| Upcoming Events | Pricing-style cards for upcoming activities |
| Contact | Contact form (name, email, message) |

## 🔍 What This Project Demonstrates

- **Responsive Web Design** — Bootstrap grid system with mobile-first layout and collapsible navbar
- **Frontend Animation** — Scroll-triggered animations via WOW.js + Animate.css, parallax scrolling, and animated number counters
- **jQuery Plugin Integration** — Owl Carousel for testimonials, Fancybox for image lightbox, smooth scrolling with jQuery Easing
- **Single-Page Architecture** — Section-based navigation with scroll-spy for active nav highlighting

## 🚧 Limitations / Future Improvements

- **Static Content** — All content is hardcoded in HTML; a CMS or headless backend would make updates easier for non-technical committee members
- **No Form Backend** — The contact form has no server-side handler; integrating Formspree or a serverless function would enable actual message delivery
- **Template-Based** — Built on the DeeTemplate theme from dsahathemes.in; customization is primarily content and styling rather than structural
- **No SEO Optimization** — Missing meta descriptions, Open Graph tags, and structured data
- **Large Asset Size** — Images are not optimized for web; compression would improve load times
