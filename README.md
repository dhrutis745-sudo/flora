# Flora — Botanical Specimen Showcase & Digital Herbarium

A minimal, cinematic editorial botanical specimen showcase web application built with **React**, **TypeScript**, **Tailwind CSS**, and **Motion**.

Inspired by classical herbarium monographs and luxury editorial design, featuring interactive specimen showcases, taxonomic deep-dives, ambient botanical soundscapes, and fluid slide transitions.

---

## 🌸 Features

- **Cinematic Exhibition Stage**: Floating botanical specimens with subtle ambient levitation and chromatic radial glow.
- **Sleek Editorial Interface**: High-contrast typography (`Italiana`, `Cormorant Garamond`, `Plus Jakarta Sans`) and dual-column taxonomic metadata.
- **Interactive Botanical Inspection Modal**:
  - High-resolution interactive specimen zoom & macro inspection.
  - Comprehensive taxonomic classification (Kingdom, Clade, Order, Family, Genus, Species).
  - Morphological traits, care guides, and cultural symbolism.
- **Curator Notes & Side Gallery**: Glassmorphism preview panels with interactive cards and quick transitions.
- **Herbarium Index & Journal**: Interactive modals exploring curated flora species, historical botanical notes, and preservation archives.
- **Ambient Botanical Synthesizer**: Subtle harmonic audio synthesizer using Web Audio API for sensory immersion.
- **Responsive & Touch-Friendly**: Full keyboard arrow navigation and mobile touch swipe gesture support.

---

## 🚀 Getting Started

### 1. Prerequisites

Ensure you have **Node.js** (v18.0.0 or higher) and **npm** installed on your system.

### 2. Installation

Clone this repository and install the dependencies:

```bash
git clone https://github.com/your-username/flora-herbarium.git
cd flora-herbarium
npm install
```

### 3. Run Locally in Development Mode

```bash
npm run dev
```

Open your browser at `http://localhost:3000` (or the URL printed in the terminal).

### 4. Build for Production

```bash
npm run build
```

This generates an optimized static production build inside the `dist/` directory, ready to deploy to Vercel, Netlify, Cloudflare Pages, or GitHub Pages.

---

## 📁 Repository File Structure

```text
├── index.html              # HTML entry template with custom Google Fonts
├── package.json            # Project dependencies and npm scripts
├── tsconfig.json           # TypeScript configuration
├── tsconfig.app.json       # Application TypeScript settings
├── tsconfig.node.json      # Node/Vite TypeScript settings
├── vite.config.ts          # Vite build configuration with Tailwind plugin
├── .gitignore              # Files and folders ignored by Git
├── README.md               # Project documentation
├── public/                 # Static public assets
└── src/
    ├── main.tsx            # Main React mounting point
    ├── App.tsx             # Root layout, background atmosphere, and modal manager
    ├── index.css           # Tailwind CSS imports, fonts, glass utilities, custom scrollbars
    ├── types.ts            # TypeScript interfaces for botanical data
    ├── vite-env.d.ts       # Asset and Vite TypeScript declarations
    ├── data/
    │   └── flowers.ts      # Botanical specimens data (Dahlia, Lotus, Ruby Rose, White Orchid, etc.)
    ├── utils/
    │   └── audio.ts        # Sensory Web Audio API harmonic sound generator
    └── components/
        ├── Navbar.tsx           # Sleek navigation bar with ambient sound toggle and modals
        ├── Hero.tsx             # Main 12-column exhibition stage with touch & keyboard navigation
        ├── FlowerDisplay.tsx    # Floating centerpiece specimen with dynamic radial glow
        ├── FlowerInfo.tsx       # Title, description, and border-left taxonomic metadata grid
        ├── DetailButton.tsx     # High-contrast 'View Detail' action button
        ├── DetailModal.tsx      # Full-screen botanical monograph with zoom and morphology tabs
        ├── ThumbnailGallery.tsx # Translucent glass preview cards & curator quote
        ├── NavigationDots.tsx   # Pagination slide indicators and arrow controls
        ├── SocialLinks.tsx      # Social actions and quick share link copier
        ├── SpeciesIndexModal.tsx# Archive listing of all botanical specimens
        ├── AboutModal.tsx       # Curator manifesto and botanical archive mission
        └── BlogModal.tsx        # Botanical Journal articles and expedition essays
```

---

## 🛠️ Tech Stack

- **React 19**
- **TypeScript**
- **Tailwind CSS v4**
- **Motion (Framer Motion)**
- **Lucide React** (Icons)
- **Vite**
