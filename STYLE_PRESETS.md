# Frontend Dashboard Style Presets

When generating dashboards, use these meticulously curated styles. Apply the colors exactly as defined to avoid the "generic AI" look.

## 1. Modern SaaS (The Default)
*Clean, trustworthy, high-contrast, designed for modern B2B web applications.*

- **Vibe**: Silicon Valley startup, Stripe/Vercel inspired, clean and highly legible.
- **Typography**: `Inter` or system UI fonts.
- **Background**: Very light gray (`#F8FAFC`).
- **Cards**: Pure white (`#FFFFFF`) with a very subtle, soft shadow (`box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);`), rounded corners (`border-radius: 12px;`).
- **Primary Text**: Slate 900 (`#0F172A`).
- **Secondary Text**: Slate 500 (`#64748B`).
- **Chart Palette**: 
  - Primary: Indigo 500 (`#6366F1`)
  - Secondary: Sky 500 (`#0EA5E9`)
  - Accent: Emerald 500 (`#10B981`)
- **Key Details**: Use subtle borders (`1px solid #E2E8F0`) around cards.

---

## 2. Cyberpunk Monitor (NOC / IT)
*Dark, glowing, high-density, designed for real-time monitoring and hacker aesthetics.*

- **Vibe**: Matrix, Network Operations Center, terminal hacker.
- **Typography**: `Roboto Mono`, `Fira Code`, or any monospace font.
- **Background**: Very dark slate/black (`#050505` to `#111827`).
- **Cards**: Slightly lighter dark (`#1F2937`) with a sharp, 1px bright border (`border: 1px solid #374151;`).
- **Primary Text**: Bright Tech Green (`#10B981`) or Cyan (`#06B6D4`).
- **Secondary Text**: Dimmed Gray (`#9CA3AF`).
- **Chart Palette**:
  - Primary: Neon Green (`#22C55E`)
  - Secondary: Cyber Pink (`#EC4899`)
  - Accent: Electric Cyan (`#06B6D4`)
- **Key Details**: Use `box-shadow` to create glowing effects on text or borders. No rounded corners (`border-radius: 0;`).

---

## 3. Executive Financial 
*Serious, dense, print-inspired, designed for high-stakes reporting.*

- **Vibe**: Wall Street Journal, Financial Times, highly authoritative.
- **Typography**: Serif for headings (`Merriweather` or `Playfair Display`), Sans-serif for data (`Helvetica Neue`).
- **Background**: Warm Paper (`#FDFBF7`).
- **Cards**: Transparent or slightly offset with thick, stark black borders (`border: 2px solid #111`).
- **Primary Text**: True Black (`#000000`).
- **Secondary Text**: Dark Gray (`#4A4A4A`).
- **Chart Palette**:
  - Primary: Deep Navy (`#1E3A8A`)
  - Secondary: Burgundy Red (`#991B1B`)
  - Accent: Forest Green (`#166534`)
- **Key Details**: Emphasize horizontal rules (`<hr>`) for separating sections. High reliance on typography size and weight for hierarchy, minimal use of background colors for distinction.

---

## 4. Glassmorphism Analytics
*Trendy, colorful, blurred backgrounds, Apple-esque.*

- **Vibe**: MacOS Big Sur, VisionOS, highly modern and spatial.
- **Typography**: `SF Pro Display`, `Outfit`, or `Poppins`.
- **Background**: A vibrant CSS gradient (e.g., `linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%)` or a highly blurred colorful background image).
- **Cards**: Translucent white (`rgba(255, 255, 255, 0.7)`) with background blur (`backdrop-filter: blur(10px);`).
- **Primary Text**: Dark Blue/Purple (`#1E1B4B`).
- **Chart Palette**:
  - Primary: Violet (`#8B5CF6`)
  - Secondary: Fuchsia (`#D946EF`)
  - Accent: Amber (`#F59E0B`)
- **Key Details**: Soft, semi-transparent white borders on cards (`1px solid rgba(255,255,255,0.5)`). Use gentle micro-animations on hover.
