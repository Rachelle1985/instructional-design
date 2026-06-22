# Web Education Services — Brand Standards

---

## 1. Brand Positioning

**Who we serve:** Local, service-based small businesses — tradesmen, contractors, salons, restaurants, realtors, consultants, mortgage brokers, lawyers. Solo operators to teams of 20.

**What we are:** A person, a place, a community you can turn to. An education-first company that makes marketing fun, gives you a process, and supports you with the right tools.

**What we are NOT:** A website agency. A tech company. A faceless vendor.

**Core belief:** A new app doesn't get you leads. Fun processes and tech that supports the process is what does. Education gives people the process. Tools support the process. Community keeps them going.

**Brand personality:** Your marketing neighbor. Energetic, curious, helpful. Makes the complicated feel fun. Modern without the tech hype.

**Tone of voice:**
- Conversational, not corporate
- Curious and excited, not salesy
- Clear, not clever
- Encouraging, not condescending
- "Your neighbor who's genuinely excited to show you something new"

**Product hierarchy (education → tools → outcomes):**
1. Education is the mission (workshops, Launchpad 12, online course, blog tutorials)
2. Tools support the process (myaieditor, Launchpad Writer, website builds)
3. Leads and customers are the outcome

---

## 2. Color Palette

The palette is bright blue + yellow — energetic, optimistic, and fun. Backgrounds are mostly white and light gray to keep the feeling bright and airy.

### Primary — Blue

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ██ | Blue 900 | `#064273` | Dark headings, footer background, nav background |
| ██ | Blue 700 | `#0570B0` | Strong emphasis, active states |
| ██ | Blue 600 | `#0381CC` | **Primary brand blue** — buttons, links, icons |
| ██ | Blue 500 | `#1A9FE0` | Hover states, secondary links |
| ██ | Blue 100 | `#CCE9F9` | Light blue backgrounds, tags, badges |
| ██ | Blue 50 | `#EBF5FC` | Subtle blue wash for alternating sections |

### Accent — Yellow

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ██ | Yellow 600 | `#C9A800` | Dark yellow text on light backgrounds |
| ██ | Yellow 500 | `#FDD618` | **Primary CTA buttons**, highlights, star ratings |
| ██ | Yellow 400 | `#FDE04A` | Hover states on CTA buttons |
| ██ | Yellow 100 | `#FEF6CC` | Light yellow backgrounds, callout boxes |
| ██ | Yellow 50 | `#FFFBE5` | Subtle yellow wash |

### Neutrals

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ██ | Gray 900 | `#111827` | Headings, primary text |
| ██ | Gray 700 | `#374151` | Body text |
| ██ | Gray 500 | `#6B7280` | Secondary text, captions |
| ██ | Gray 300 | `#D1D5DB` | Borders, dividers |
| ██ | Gray 100 | `#F3F4F6` | Alternate section backgrounds |
| ██ | Gray 50 | `#F9FAFB` | Page background |
| ██ | White | `#FFFFFF` | Cards, primary background |

### Color Rules

1. **Primary actions** (main CTA buttons): Yellow 500 background, Blue 900 text (dark on yellow for contrast). Hover → Yellow 400.
2. **Secondary actions** (secondary buttons, links): Blue 600. Hover → Blue 500.
3. **Navigation & footer**: Blue 900 background, white text.
4. **Section alternation**: White → Gray 50 or Blue 50 → White. Never stack two colored sections.
5. **Text on dark backgrounds**: Always white (#FFFFFF).
6. **Text on yellow backgrounds**: Always Blue 900 (#064273) for readability.
7. **Body text**: Gray 700 on white/light backgrounds. Never use pure black (#000000).
8. **Headings**: Gray 900 or Blue 900 — choose one per page and be consistent.

---

## 3. Typography

### Font Families

**Headings:** Plus Jakarta Sans (weights 600, 700, 800)
- Modern geometric sans-serif with soft, rounded terminals
- Feels confident and approachable — not cold or corporate
- Download: Google Fonts, self-host as .woff2

**Body:** Inter (weights 400, 500, 600)
- Industry-standard readability, excellent at small sizes
- Clean and neutral — lets the content speak
- Download: Google Fonts, self-host as .woff2

### CSS Custom Properties

```css
--font-heading: 'Plus Jakarta Sans', 'Plus Jakarta Sans Fallback', Arial, sans-serif;
--font-body: 'Inter', 'Inter Fallback', Arial, sans-serif;
```

### Type Scale

| Element | Font | Weight | Size (desktop) | Size (mobile) | Line Height |
|---------|------|--------|----------------|---------------|-------------|
| H1 (hero) | Plus Jakarta Sans | 800 | 56px / 3.5rem | 36px / 2.25rem | 1.1 |
| H2 (section) | Plus Jakarta Sans | 700 | 40px / 2.5rem | 28px / 1.75rem | 1.2 |
| H3 (card/sub) | Plus Jakarta Sans | 700 | 24px / 1.5rem | 20px / 1.25rem | 1.3 |
| H4 | Plus Jakarta Sans | 600 | 20px / 1.25rem | 18px / 1.125rem | 1.4 |
| Body | Inter | 400 | 17px / 1.0625rem | 16px / 1rem | 1.7 |
| Body bold | Inter | 600 | 17px | 16px | 1.7 |
| Small/caption | Inter | 400 | 14px / 0.875rem | 13px / 0.8125rem | 1.5 |
| Nav link | Inter | 500 | 15px | 15px | 1 |
| Button | Inter | 600 | 16px | 16px | 1 |

### Typography Rules

1. **One H1 per page.** Always in the hero section.
2. **Never skip heading levels.** H1 → H2 → H3, in order.
3. **Body text max-width:** 720px for readability. Use a container.
4. **Letter-spacing:** -0.02em on H1, -0.01em on H2. Normal on everything else.
5. **All caps:** Use sparingly — only for eyebrow text above headings (e.g., "LEARN"). Inter 600, 13px, letter-spacing 0.08em, Blue 600 or Yellow 600 color.

---

## 4. Spacing & Layout

### Spacing Scale

| Token | Value | Usage |
|-------|-------|-------|
| --space-xs | 4px | Inline spacing, icon gaps |
| --space-sm | 8px | Tight padding, small gaps |
| --space-md | 16px | Standard padding, card gaps |
| --space-lg | 24px | Section padding (inner) |
| --space-xl | 32px | Between content blocks |
| --space-2xl | 48px | Between sections |
| --space-3xl | 64px | Major section breaks |
| --space-4xl | 96px | Hero vertical padding |

### Layout Rules

1. **Max content width:** 1200px, centered.
2. **Section padding:** 80px top/bottom on desktop, 48px on mobile.
3. **Card grids:** 3 columns on desktop, 2 on tablet, 1 on mobile. Gap: 24px.
4. **Whitespace is a feature.** When in doubt, add more space. The brand is "bright and airy."
5. **Mobile-first responsive.** Base styles are mobile, scale up with min-width breakpoints.

### Breakpoints

| Name | Width | Target |
|------|-------|--------|
| sm | 640px | Large phones |
| md | 768px | Tablets |
| lg | 1024px | Small desktops |
| xl | 1280px | Full desktops |

---

## 5. Components

### Buttons

**Primary CTA:**
- Background: Yellow 500 (`#FDD618`)
- Text: Blue 900 (`#064273`), Inter 600, 16px
- Padding: 14px 28px
- Border-radius: 8px
- Hover: Yellow 400 (`#FDE04A`), slight translateY(-1px) lift
- Box-shadow: `0 2px 8px rgba(253, 214, 24, 0.3)`

**Secondary:**
- Background: Blue 600 (`#0381CC`)
- Text: White, Inter 600, 16px
- Padding: 14px 28px
- Border-radius: 8px
- Hover: Blue 500 (`#1A9FE0`)

**Outline/Ghost:**
- Background: transparent
- Border: 2px solid Blue 600
- Text: Blue 600
- Hover: Blue 600 background, white text

### Cards

- Background: White
- Border-radius: 12px
- Box-shadow: `0 1px 3px rgba(0,0,0,0.08), 0 1px 2px rgba(0,0,0,0.06)`
- Padding: 32px
- Hover (if clickable): shadow grows to `0 4px 12px rgba(0,0,0,0.1)`, translateY(-2px)

### Navigation

- Background: Blue 900 (`#064273`)
- Height: 72px desktop, 64px mobile
- Logo: `images/logo-horizontal.png` on dark, or text wordmark
- Links center or right, CTA button (yellow) far right
- Mobile: hamburger menu, full-screen overlay
- Active link: Yellow 500 underline or color
- **Returning user links**: "My Editor" and "Toolbox" as utility links (smaller, top-right)

### Footer

- Background: Blue 900 (`#064273`)
- Text: White, with Gray 300 for secondary
- Links: White, hover Yellow 400
- 4-column layout: Learn, Services, Company, Contact
- Bottom bar: copyright, privacy, terms

### Section Eyebrow

Small text above section headings to provide category context:
- Font: Inter 600, 13px
- Letter-spacing: 0.08em
- Text-transform: uppercase
- Color: Blue 600 or Yellow 600
- Margin-bottom: 8px

---

## 6. Multi-Audience Architecture

The site serves 4 audiences. The architecture must serve all without confusing any.

### Audience Segments

| Segment | Entry Point | Primary Need | Nav Access |
|---------|-------------|-------------|------------|
| **New visitors** | Homepage hero | Understand 3 paths, pick one | Main nav + hero cards |
| **Workshop returnees** | Direct/bookmark | Replays, blogs, tools (toolbox) | "Toolbox" in nav or utility bar |
| **Course students** | Direct/bookmark | Structured lessons | "My Course" → Reach360 link |
| **Website clients** | Direct/bookmark | Edit their site | "My Editor" → myaieditor.com |

### The 3 Paths (for new visitors)

Presented as clear, equal options on the homepage:

1. **Learn & Explore** — Free Friday workshops, blog tutorials, AI marketing tools
   - Barrier: Free
   - CTA: "Join a Free Workshop" or "Browse Resources"
   - Target: Curious, not ready to commit

2. **Get Trained** — Launchpad 12 (12 weeks, 1-on-1), online course (self-paced)
   - Barrier: $23/mo or $2,500
   - CTA: "Start Launchpad 12" or "Enroll in the Course"
   - Target: Ready to commit to learning marketing

3. **Get a Website** — Custom website build + AI-powered editing via myaieditor
   - Barrier: $450-$1,950 build + $50/mo
   - CTA: "Get a Custom Website"
   - Target: Need a website now, want ongoing AI management

### Navigation Structure

```
[Logo] ............. [Learn ▼] [Services ▼] [Pricing] [Blog] [Contact] [Get Started ★]
                                                                         (yellow CTA)

Utility bar (small, above or integrated):
[My Editor] [Toolbox] [My Course]

Learn dropdown:
  - Free Friday Workshops
  - Launchpad 12 (12-week program)
  - Online Course ($23/mo)

Services dropdown:
  - Website Builds
  - AI Website Editor
  - MLO Websites
  - Consulting & Automation
```

### SEO Strategy (brand + education on homepage, services on service pages)

| Page | Target Keywords | Search Intent |
|------|----------------|---------------|
| Homepage | "web education services", brand queries | Navigational |
| /services/websites | "small business website design", "website design Tampa" | Commercial |
| /services/ai-editor | "AI website editor", "AI-powered website management" | Commercial |
| /services/mlo-websites | "MLO website", "mortgage website design" | Commercial |
| /launchpad-12 | "marketing training small business", "marketing course" | Commercial |
| /sign-up | "free marketing workshop Tampa" | Local/informational |
| Blog posts | Long-tail AI tutorials (existing traffic engine) | Informational |

---

## 7. Imagery

### Hero Image
- **Primary hero**: `images/imgi_50_YouTube+Banner-84ddc91b-1920w.jpg` — the existing collage of people learning + notes + local main street. Keep for brand recognition.
- Used as hero background with Blue 900 gradient overlay for text readability

### Style
- **Bright, airy, and minimal** — lots of white space and light
- **Blue and yellow accents** in illustrations and UI screenshots
- **Real people preferred** over stock when possible — especially local business owners learning, discovering, having fun
- **Blog post images**: Bright, airy, minimalistic illustrations with blue and yellow accents (current blog style — keep this)
- **No generic handshake photos, no suits around a conference table**

### Photo Treatment
- Slight warm tone (not cold/blue-shifted)
- High brightness, natural lighting preferred
- If overlaying text: use a gradient overlay (Blue 900 at 60-70% opacity)

### Icons
- Use the custom SVG library from `icon-library/icons/icons.js`
- All icons use `stroke="currentColor"` — color them with CSS
- Standard icon size: 24px for inline, 32px for cards, 48px for feature sections
- Icon color: Blue 600 for informational, Yellow 500 for highlights

---

## 8. Logo

**Existing logo**: `images/logo-horizontal.png` (horizontal version) and `images/logo-square.png` (square version)
- Features the laptop icon with swoosh in blue + yellow
- Text: "WEB" (bold) "Education Services" with tagline "WE TEACH YOU HOW TO MARKET"
- Colors: Blue (#0381CC range) + Yellow (#FDD618 range) — matches brand palette

**Logo usage:**
- **Nav bar (dark bg)**: Use horizontal logo image, or white text wordmark
- **Mobile**: Square logo icon only (laptop+swoosh)
- **Favicon**: Square logo, 32x32
- Minimum width: 120px
- Clear space: 16px on all sides
- Never stretch, rotate, or add effects

---

## 9. Voice & Messaging

### Headlines

Write for the business owner, not the developer. Make them curious:
- **Yes:** "Learn the Marketing Strategy That Gets Leads"
- **No:** "Comprehensive Digital Marketing Bootcamp with Advanced Analytics"
- **Yes:** "Your Website, Updated in Seconds"
- **No:** "AI-Powered CMS with Real-Time Deployment Pipeline"
- **Yes:** "Try Something New This Friday"
- **No:** "Register for our upcoming webinar series"

### Value Language

| Instead of... | Say... |
|--------------|--------|
| AI-powered platform | Edit your site by typing what you want |
| Scalable infrastructure | Your site grows with your business |
| Full-stack development | A website built right, from the ground up |
| Conversion optimization | More customers from your website |
| SEO services | Show up when people search for you |
| Digital transformation | Get your business online the smart way |
| Comprehensive curriculum | A fun process that actually works |
| Proprietary technology | Tools built for business owners, not developers |

### Social Proof
- Lead with numbers: "140+ websites managed"
- Use client industry, not just names: "Helped a Tampa dental practice double their appointment requests"
- Feature the business type the reader identifies with
- Lead with transformation: "I came for a website. I stayed because I learned to market my business."

---

## 10. CSS Custom Properties (Implementation Reference)

```css
:root {
  /* Colors — Blue */
  --blue-900: #064273;
  --blue-700: #0570B0;
  --blue-600: #0381CC;
  --blue-500: #1A9FE0;
  --blue-100: #CCE9F9;
  --blue-50: #EBF5FC;

  /* Colors — Yellow */
  --yellow-600: #C9A800;
  --yellow-500: #FDD618;
  --yellow-400: #FDE04A;
  --yellow-100: #FEF6CC;
  --yellow-50: #FFFBE5;

  /* Colors — Neutrals */
  --gray-900: #111827;
  --gray-700: #374151;
  --gray-500: #6B7280;
  --gray-300: #D1D5DB;
  --gray-100: #F3F4F6;
  --gray-50: #F9FAFB;
  --white: #FFFFFF;

  /* Typography */
  --font-heading: 'Plus Jakarta Sans', 'Plus Jakarta Sans Fallback', Arial, sans-serif;
  --font-body: 'Inter', 'Inter Fallback', Arial, sans-serif;

  /* Spacing */
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 16px;
  --space-lg: 24px;
  --space-xl: 32px;
  --space-2xl: 48px;
  --space-3xl: 64px;
  --space-4xl: 96px;

  /* Borders */
  --radius-sm: 6px;
  --radius-md: 8px;
  --radius-lg: 12px;
  --radius-xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: 0 1px 2px rgba(0,0,0,0.06);
  --shadow-md: 0 1px 3px rgba(0,0,0,0.08), 0 1px 2px rgba(0,0,0,0.06);
  --shadow-lg: 0 4px 12px rgba(0,0,0,0.1);
  --shadow-xl: 0 8px 24px rgba(0,0,0,0.12);

  /* Layout */
  --container-max: 1200px;
  --content-max: 720px;
}
```

---

## 11. Do's and Don'ts

### Do
- Use plenty of white space — the brand breathes
- Lead with curiosity and fun — make people want to try something new
- Feature the education/process before the tools
- Show real results and real businesses when possible
- Use blue as the dominant color, yellow as the energy that draws the eye
- Keep imagery bright, warm, and natural
- Use the existing hero banner image for brand recognition
- Serve returning users with quick-access utility links (My Editor, Toolbox, My Course)

### Don't
- Don't position WES as a website agency — lead with education
- Don't use dark themes or dark hero sections as default (keep it bright, hero excepted)
- Don't use jargon the business owner won't understand
- Don't use more than 2 accent colors on a single page
- Don't use stock photos of corporate offices, suits, or handshakes
- Don't make the site feel like a tech startup — it should feel like a helpful community
- Don't center-align body text (left-align always, center only for short headings and CTAs)
- Don't use gradients on text
- Don't use animations that delay content visibility
- Don't forget that returning users (workshop members, students, website clients) need fast paths to their stuff
