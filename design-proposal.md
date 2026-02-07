# Design Proposal: Claudia Garcia

## Analisis
- Profesion: Contract Manager & Construction Lawyer
- Industria: Legal / Construction / Infrastructure
- Audiencia objetivo: Recruiters, law firms, corporate partners in Canada
- Vibe deseado: Professional, prestigious, international

## Current State (V1)
- Template: minimal-mono with premium additions (circular photo, legal symbols)
- accentColor: #4A90A4 (turquesa only)
- Font: IBM Plex Mono (monospace - feels too dev/tech for a lawyer)
- Missing: Languages, Bar Admissions, Certifications sections
- Missing: Scroll reveal animations
- Missing: Lavanda tones (client asked for lavanda + azul claro + turquesa)
- Favicon: Generic code brackets (not personalized)

## Improvements for V2

### 1. Color Palette Upgrade
- Primary: #4A90A4 (turquesa - keep, matches form request)
- Secondary: #8B7EB8 (lavanda - client specifically asked for lavanda)
- Background: #FFFFFF (white, clean)
- Surface: #F8F7FC (very light lavanda tint for cards/sections)
- Text Primary: #1a1a2e (dark navy)
- Text Secondary: #6b7280 (gray)
- Accent gradient: turquesa-to-lavanda for hero

### 2. Typography Upgrade
- Headings: Source Serif 4 (elegant serif, conveys legal authority)
- Body: Inter (clean, modern, highly readable)
- Mono: Keep IBM Plex Mono only for numbered items (01, 02, etc.)

### 3. New Sections
- **Bar Admissions**: Ontario Bar (2020), RMMF member
- **Languages**: 5 languages with proficiency levels
- **Certifications**: Columbia, Osler, Alstom

### 4. Section Order (updated)
1. Hero (name, title, photo, social)
2. About Me (brief, 2-3 sentences)
3. Notable Matters (key cases/deals)
4. Experience (timeline)
5. Education (cards)
6. Bar Admissions & Certifications (new)
7. Languages (new)
8. Footer (contact)

### 5. Motion Design
- Hero: fade-in + translateY stagger (existing, keep)
- Sections: IntersectionObserver scroll reveal (translateY 30px + opacity)
- Cards: hover shadow elevation
- Skill badges: subtle hover scale
- Reduced motion: respect prefers-reduced-motion

### 6. Favicon
- CG initials in turquesa (#4A90A4) on white/transparent background
- Rounded rectangle

## Seleccion Final
Keep existing template base but upgrade with:
- Dual-color palette (turquesa + lavanda)
- Typography upgrade
- Two new sections (Bar Admissions, Languages)
- Scroll reveal animations
- Custom CG favicon
