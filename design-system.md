# Blog Automator AI Design System

## Brand Identity

### Mission
Transform content creation from time-consuming to automated through AI-powered WordPress content generation.

### Brand Values
- **Professional Excellence**: Enterprise-grade reliability and quality
- **Innovation**: Cutting-edge AI technology
- **Efficiency**: Automation that saves time and resources
- **Authority**: Research-backed, credible content
- **Scalability**: Unlimited growth potential

---

## Color Palette

### Primary Colors
```
Brand Blue (Primary)
- #2563EB (Main)
- #1E40AF (Dark)
- #3B82F6 (Light)
- #DBEAFE (Subtle)
Usage: CTAs, links, primary actions, brand elements

AI Purple (Secondary)
- #7C3AED (Main)
- #5B21B6 (Dark)
- #8B5CF6 (Light)
- #EDE9FE (Subtle)
Usage: AI features, highlights, premium indicators
```

### Neutral Colors
```
Charcoal (Text)
- #111827 (Headings)
- #374151 (Body)
- #6B7280 (Secondary)
- #9CA3AF (Muted)

Gray Scale
- #F9FAFB (Background Light)
- #F3F4F6 (Background)
- #E5E7EB (Border)
- #D1D5DB (Border Dark)
- #FFFFFF (White)
```

### Semantic Colors
```
Success Green
- #10B981 (Main)
- #D1FAE5 (Background)
Usage: Success states, positive metrics, completion

Warning Amber
- #F59E0B (Main)
- #FEF3C7 (Background)
Usage: Warnings, important notices

Error Red
- #EF4444 (Main)
- #FEE2E2 (Background)
Usage: Errors, destructive actions

Info Blue
- #3B82F6 (Main)
- #DBEAFE (Background)
Usage: Information, tips, neutral highlights
```

### Gradient Overlays
```
Hero Gradient
- Linear: #2563EB → #7C3AED (45deg)

Premium Badge
- Linear: #7C3AED → #EC4899 (135deg)

Dark Overlay
- Linear: rgba(17, 24, 39, 0) → rgba(17, 24, 39, 0.95)
```

---

## Typography

### Font Families
```
Primary (Headings & UI)
- Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
- Clean, modern, professional

Secondary (Body)
- 'Inter', system-ui, sans-serif
- Excellent readability

Monospace (Code)
- 'JetBrains Mono', 'Fira Code', Consolas, monospace
```

### Type Scale
```
Display (Hero)
- Size: 56px / 3.5rem
- Weight: 800 (ExtraBold)
- Line Height: 1.1
- Letter Spacing: -0.02em

H1
- Size: 48px / 3rem
- Weight: 700 (Bold)
- Line Height: 1.2
- Letter Spacing: -0.015em

H2
- Size: 36px / 2.25rem
- Weight: 700 (Bold)
- Line Height: 1.25
- Letter Spacing: -0.01em

H3
- Size: 30px / 1.875rem
- Weight: 600 (SemiBold)
- Line Height: 1.3
- Letter Spacing: -0.005em

H4
- Size: 24px / 1.5rem
- Weight: 600 (SemiBold)
- Line Height: 1.4
- Letter Spacing: 0

H5
- Size: 20px / 1.25rem
- Weight: 600 (SemiBold)
- Line Height: 1.4
- Letter Spacing: 0

H6
- Size: 18px / 1.125rem
- Weight: 600 (SemiBold)
- Line Height: 1.4
- Letter Spacing: 0

Body Large
- Size: 18px / 1.125rem
- Weight: 400 (Regular)
- Line Height: 1.7
- Letter Spacing: 0

Body (Default)
- Size: 16px / 1rem
- Weight: 400 (Regular)
- Line Height: 1.6
- Letter Spacing: 0

Body Small
- Size: 14px / 0.875rem
- Weight: 400 (Regular)
- Line Height: 1.5
- Letter Spacing: 0

Caption
- Size: 12px / 0.75rem
- Weight: 400 (Regular)
- Line Height: 1.4
- Letter Spacing: 0.01em

Overline
- Size: 12px / 0.75rem
- Weight: 700 (Bold)
- Line Height: 1.5
- Letter Spacing: 0.1em
- Transform: uppercase
```

---

## Spacing System

### Base Unit: 4px (0.25rem)

```
Space Scale (8pt Grid)
- 2xs: 4px (0.25rem)   - 1×
- xs:  8px (0.5rem)    - 2×
- sm:  12px (0.75rem)  - 3×
- md:  16px (1rem)     - 4× (base)
- lg:  24px (1.5rem)   - 6×
- xl:  32px (2rem)     - 8×
- 2xl: 48px (3rem)     - 12×
- 3xl: 64px (4rem)     - 16×
- 4xl: 96px (6rem)     - 24×
- 5xl: 128px (8rem)    - 32×
```

### Layout Spacing
```
Section Padding (Vertical)
- Mobile: 48px (3rem)
- Tablet: 64px (4rem)
- Desktop: 96px (6rem)

Section Padding (Horizontal)
- Mobile: 16px (1rem)
- Tablet: 32px (2rem)
- Desktop: 48px (3rem)

Container Max-Width
- Small: 640px
- Medium: 768px
- Large: 1024px
- XL: 1280px
- 2XL: 1536px

Grid Gap
- Mobile: 16px (1rem)
- Tablet: 24px (1.5rem)
- Desktop: 32px (2rem)
```

---

## Elevation & Shadows

```
Level 1 (Subtle)
- box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05)
- Usage: Cards, inputs

Level 2 (Raised)
- box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
              0 2px 4px -1px rgba(0, 0, 0, 0.06)
- Usage: Buttons, hoverable cards

Level 3 (Floating)
- box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
              0 4px 6px -2px rgba(0, 0, 0, 0.05)
- Usage: Dropdowns, popovers

Level 4 (Modal)
- box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1),
              0 10px 10px -5px rgba(0, 0, 0, 0.04)
- Usage: Modals, important overlays

Level 5 (Emphasis)
- box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25)
- Usage: Hero elements, key features

Colored Shadow (CTAs)
- box-shadow: 0 10px 30px -5px rgba(37, 99, 235, 0.3)
- Usage: Primary buttons, standout elements
```

---

## Border Radius

```
- None: 0
- xs: 2px (0.125rem)
- sm: 4px (0.25rem)
- md: 6px (0.375rem)
- lg: 8px (0.5rem)
- xl: 12px (0.75rem)
- 2xl: 16px (1rem)
- 3xl: 24px (1.5rem)
- full: 9999px (pill shape)

Component Usage:
- Buttons: 6px (md)
- Cards: 12px (xl)
- Inputs: 6px (md)
- Badges: 4px (sm) or full
- Modals: 16px (2xl)
- Images: 8px (lg)
```

---

## Breakpoints

```
Mobile First Approach

xs: 0px       - Mobile portrait
sm: 640px     - Mobile landscape
md: 768px     - Tablet
lg: 1024px    - Desktop
xl: 1280px    - Large desktop
2xl: 1536px   - Wide desktop
```

---

## Component Specifications

### Buttons

#### Primary Button
```
Default State:
- Background: #2563EB
- Text: #FFFFFF
- Padding: 12px 24px (vertical horizontal)
- Border Radius: 6px
- Font Weight: 600
- Font Size: 16px
- Shadow: Level 2
- Transition: all 150ms ease

Hover:
- Background: #1E40AF
- Shadow: Level 3
- Transform: translateY(-1px)

Active:
- Background: #1E3A8A
- Shadow: Level 1
- Transform: translateY(0)

Disabled:
- Background: #E5E7EB
- Text: #9CA3AF
- Cursor: not-allowed
- Opacity: 0.6
```

#### Secondary Button
```
Default State:
- Background: Transparent
- Border: 2px solid #2563EB
- Text: #2563EB
- Padding: 10px 22px
- Others: Same as Primary

Hover:
- Background: #EFF6FF
- Border: #1E40AF
```

#### Ghost Button
```
Default State:
- Background: Transparent
- Text: #374151
- Padding: 12px 24px

Hover:
- Background: #F3F4F6
```

### Cards

```
Default Card:
- Background: #FFFFFF
- Border: 1px solid #E5E7EB
- Border Radius: 12px
- Padding: 24px
- Shadow: Level 1

Hover (Interactive):
- Border: 1px solid #D1D5DB
- Shadow: Level 3
- Transform: translateY(-2px)
- Transition: all 200ms ease

Feature Card:
- Same as Default
- Add top border accent: 4px solid #2563EB
```

### Forms

#### Input Fields
```
Default:
- Height: 44px
- Padding: 12px 16px
- Border: 1px solid #D1D5DB
- Border Radius: 6px
- Font Size: 16px
- Background: #FFFFFF

Focus:
- Border: 2px solid #2563EB
- Shadow: 0 0 0 3px rgba(37, 99, 235, 0.1)
- Outline: none

Error:
- Border: 1px solid #EF4444
- Shadow: 0 0 0 3px rgba(239, 68, 68, 0.1)

Disabled:
- Background: #F9FAFB
- Text: #9CA3AF
- Cursor: not-allowed
```

#### Labels
```
- Font Size: 14px
- Font Weight: 600
- Color: #374151
- Margin Bottom: 6px
```

### Badges

```
Default Badge:
- Padding: 4px 12px
- Border Radius: 4px or full
- Font Size: 12px
- Font Weight: 600
- Letter Spacing: 0.05em

Variants:
- Success: #10B981 text, #D1FAE5 background
- Warning: #F59E0B text, #FEF3C7 background
- Error: #EF4444 text, #FEE2E2 background
- Info: #3B82F6 text, #DBEAFE background
- Premium: Gradient background, white text
```

### Alerts

```
Structure:
- Padding: 16px
- Border Radius: 8px
- Border Left: 4px solid (semantic color)
- Display: flex
- Gap: 12px

Variants:
- Info: #DBEAFE background, #3B82F6 border
- Success: #D1FAE5 background, #10B981 border
- Warning: #FEF3C7 background, #F59E0B border
- Error: #FEE2E2 background, #EF4444 border
```

---

## Icons

### Style
- Line icons (Lucide, Heroicons, or Feather)
- Stroke width: 2px
- Rounded corners
- 24×24px default size
- Sizes: 16px, 20px, 24px, 32px, 48px

### Usage
- Always paired with labels for accessibility
- Use consistent icon set throughout
- Color: Inherit from parent or semantic colors

---

## Animation & Transitions

### Timing Functions
```
- Ease In Out: cubic-bezier(0.4, 0, 0.2, 1)
- Ease Out: cubic-bezier(0, 0, 0.2, 1)
- Ease In: cubic-bezier(0.4, 0, 1, 1)
- Bounce: cubic-bezier(0.68, -0.55, 0.265, 1.55)
```

### Duration
```
- Instant: 100ms
- Fast: 150ms
- Normal: 200ms
- Slow: 300ms
- Slower: 500ms
```

### Common Animations
```
Fade In:
- Opacity: 0 → 1
- Duration: 200ms
- Timing: ease-out

Slide Up:
- Transform: translateY(10px) → translateY(0)
- Opacity: 0 → 1
- Duration: 300ms
- Timing: ease-out

Scale In:
- Transform: scale(0.95) → scale(1)
- Opacity: 0 → 1
- Duration: 150ms
- Timing: ease-out

Hover Lift:
- Transform: translateY(0) → translateY(-2px)
- Shadow: Level 2 → Level 3
- Duration: 200ms
- Timing: ease-out
```

---

## Accessibility

### Contrast Ratios
- Normal text: Minimum 4.5:1
- Large text (18px+): Minimum 3:1
- UI components: Minimum 3:1

### Focus States
- Always visible
- 2px solid outline or 3px shadow
- Color: #2563EB
- Never remove outline without replacement

### Touch Targets
- Minimum: 44×44px
- Recommended: 48×48px
- Spacing: Minimum 8px between targets

### Text
- Minimum font size: 14px (body text)
- Maximum line length: 75 characters
- Line height: Minimum 1.5 for body text

---

## Grid System

### 12-Column Grid
```
Mobile (< 768px):
- Columns: 4
- Gap: 16px
- Margin: 16px

Tablet (768px - 1024px):
- Columns: 8
- Gap: 24px
- Margin: 32px

Desktop (1024px+):
- Columns: 12
- Gap: 32px
- Margin: 48px
```

---

## Content Patterns

### Hero Section
```
Structure:
- Full-width container
- Max-width: 1280px centered
- Padding: 96px vertical (mobile: 48px)
- Background: Gradient or solid
- Text: Centered or left-aligned

Elements:
- Display heading (56px)
- Subheading (18-20px)
- Primary CTA button
- Secondary CTA button (optional)
- Hero image or illustration
```

### Feature Sections
```
Layout Options:
- 3-column grid (desktop)
- 2-column (tablet)
- 1-column (mobile)

Card Structure:
- Icon (48px) or image
- Heading (H3 or H4)
- Description (body)
- Optional CTA link
```

### Pricing Cards
```
Structure:
- Vertical card layout
- Highlighted "Popular" variant
- Badge for discounts/labels

Elements:
- Plan name (H3)
- Price (Display or H1)
- Period (caption)
- Feature list with checkmarks
- CTA button (full-width)
```

### Testimonials
```
Card Style:
- Quote text (body large)
- Avatar image (48px circle)
- Name (font-weight: 600)
- Role/Company (caption, muted)
- Star rating (optional)
```

---

## Voice & Tone

### Writing Principles
1. **Professional but Approachable**: Expert without being intimidating
2. **Action-Oriented**: Focus on outcomes and benefits
3. **Clear & Concise**: Respect user's time
4. **Value-Focused**: Lead with benefits, not features

### Headings
- Start with action verbs or benefits
- Keep under 10 words
- Use sentence case (except acronyms)

### Body Copy
- Short paragraphs (2-3 sentences)
- Use bullet points for lists
- Active voice preferred
- Second person ("you") when addressing users

### CTAs
- Start with action verbs
- Be specific about outcome
- Create urgency when appropriate
- Examples: "Start Free Trial", "Get Pro Now", "See Pricing"

---

## Brand Assets

### Logo Usage
```
Minimum Size:
- Digital: 120px width
- Print: 1 inch width

Clear Space:
- Minimum: Logo height × 0.25

Variations:
- Full color (primary)
- White (on dark backgrounds)
- Black (single color applications)
```

### Imagery Style
```
Photography:
- Professional, high-quality
- Natural lighting preferred
- Diverse representation
- Real people over stock poses

Illustrations:
- Modern, minimal style
- Use brand colors
- Consistent stroke weights
- Abstract or conceptual

Screenshots:
- Clean UI/UX
- Show actual product
- Highlight key features
- High resolution
```

---

## Code Implementation

### CSS Custom Properties
```css
:root {
  /* Colors - Primary */
  --color-primary: #2563EB;
  --color-primary-dark: #1E40AF;
  --color-primary-light: #3B82F6;
  --color-primary-subtle: #DBEAFE;

  /* Colors - Secondary */
  --color-secondary: #7C3AED;
  --color-secondary-dark: #5B21B6;
  --color-secondary-light: #8B5CF6;
  --color-secondary-subtle: #EDE9FE;

  /* Colors - Neutral */
  --color-gray-900: #111827;
  --color-gray-700: #374151;
  --color-gray-500: #6B7280;
  --color-gray-300: #D1D5DB;
  --color-gray-100: #F3F4F6;
  --color-gray-50: #F9FAFB;
  --color-white: #FFFFFF;

  /* Colors - Semantic */
  --color-success: #10B981;
  --color-warning: #F59E0B;
  --color-error: #EF4444;
  --color-info: #3B82F6;

  /* Typography */
  --font-primary: Inter, -apple-system, BlinkMacSystemFont, sans-serif;
  --font-mono: 'JetBrains Mono', Consolas, monospace;

  /* Font Sizes */
  --text-display: 3.5rem;
  --text-h1: 3rem;
  --text-h2: 2.25rem;
  --text-h3: 1.875rem;
  --text-h4: 1.5rem;
  --text-base: 1rem;
  --text-sm: 0.875rem;
  --text-xs: 0.75rem;

  /* Spacing */
  --space-xs: 0.5rem;
  --space-sm: 0.75rem;
  --space-md: 1rem;
  --space-lg: 1.5rem;
  --space-xl: 2rem;
  --space-2xl: 3rem;
  --space-3xl: 4rem;

  /* Radius */
  --radius-sm: 0.25rem;
  --radius-md: 0.375rem;
  --radius-lg: 0.5rem;
  --radius-xl: 0.75rem;
  --radius-2xl: 1rem;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
  --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
  --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
  --shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1);

  /* Transitions */
  --transition-fast: 150ms ease;
  --transition-base: 200ms ease;
  --transition-slow: 300ms ease;
}
```

---

## Design Checklist

### Every Component Should Have:
- [ ] Defined default, hover, active, disabled states
- [ ] Mobile-responsive behavior
- [ ] Keyboard navigation support
- [ ] ARIA labels where needed
- [ ] Sufficient color contrast
- [ ] Appropriate spacing (8pt grid)
- [ ] Consistent with design system
- [ ] Loading/error states (if applicable)

### Every Page Should Have:
- [ ] Clear visual hierarchy
- [ ] Consistent spacing rhythm
- [ ] Mobile-first responsive design
- [ ] Semantic HTML structure
- [ ] Optimized images (WebP, lazy loading)
- [ ] Accessible color combinations
- [ ] Clear CTAs
- [ ] Fast load time optimization

---

## Resources & Tools

### Design Tools
- Figma (recommended)
- Adobe XD
- Sketch

### Color Tools
- Coolors.co (palette generation)
- Contrast Checker (accessibility)

### Typography Tools
- Google Fonts
- Adobe Fonts

### Icon Libraries
- Heroicons (recommended)
- Lucide Icons
- Feather Icons

### Development
- Tailwind CSS (utility-first CSS)
- CSS Custom Properties
- PostCSS

---

*Design System Version 1.0 | Last Updated: 2025*