# Calgary Home Emergency Connect

Premium conversion-optimized emergency call-routing website for Calgary homeowners.

---

## Psychological Conversion Principles Applied

### 1. **Urgency & Scarcity**
- Live "Available Now" banner with pulsing indicator
- Time-pressure copy ("Every minute matters", "The clock is ticking")
- Consequences of waiting prominently featured

### 2. **Reduced Friction**
- Single CTA (phone call) — no forms, no chat, no decisions
- Sticky mobile CTA always visible
- "60 seconds to connection" messaging reduces perceived effort

### 3. **Social Proof & Trust**
- "Available Now" badges signal demand
- Clean, premium design signals legitimacy
- Transparency about being a connector builds trust

### 4. **Loss Aversion**
- Headlines focus on what's at risk (frozen pipes, mold, health)
- "Don't wait until it gets worse" leverages fear of regret

### 5. **Visual Hierarchy**
- Orange CTAs pop against dark background
- Phone number is largest text element
- Glowing animation draws eye to action

### 6. **Color Psychology**
- Dark background = seriousness, trust
- Orange accent = urgency, warmth, action
- Green "available" indicators = positive, go signal

---

## File Structure

```
calgary-emergency-connect/
├── index.html              # Homepage with emergency selector
├── styles.css              # Shared styles (conversion-optimized)
├── no-heat.html            # Furnace emergency (403-555-0101)
├── basement-flooding.html  # Water emergency (403-555-0102)
├── no-ac.html              # Cooling emergency (403-555-0103)
├── electrical-emergency.html # Electrical (403-555-0104)
└── README.md
```

---

## Phone Number Configuration

### Current Numbers (Placeholders)

| Page | Number | Purpose |
|------|--------|---------|
| Homepage | 403-555-0100 | General |
| No Heat | 403-555-0101 | Heating |
| Flooding | 403-555-0102 | Water |
| No AC | 403-555-0103 | Cooling |
| Electrical | 403-555-0104 | Electrical |

### Updating Numbers

Each page has the phone number in **4 locations**:
1. Header CTA (top right)
2. Hero CTA (main button)
3. Final CTA (bottom section)
4. Sticky mobile CTA (fixed bottom)

**Find & replace** the number in each file. Update both:
- `href="tel:403-555-XXXX"` (the link)
- The visible display number

---

## Design Features

### Premium Dark Theme
- Trust-building dark palette
- Subtle grid background texture
- Gradient accents per emergency type

### Mobile-First
- Sticky bottom CTA on mobile
- Touch-friendly button sizing (min 48px)
- Responsive typography

### Micro-Animations
- Pulsing "available" indicators
- Glowing CTA buttons
- Phone icon "ring" animation
- Hover state feedback on cards

### Color-Coded Emergencies
- Heat: Red/Orange gradients
- Water: Blue gradients
- Cool: Cyan gradients
- Electric: Yellow gradients

---

## Conversion Optimizations

### Above the Fold
- Clear value proposition
- Immediate CTA visibility
- "Available Now" social proof
- Zero scroll required to call

### Copy Patterns
- Problem → Agitation → Solution
- Specific consequences (frozen pipes, mold timeline)
- Action-oriented headlines
- "You" focused language

### CTA Design
- High contrast orange on dark
- Animated glow effect
- Phone icon with ring animation
- Two-line format (action + number)

### Trust Elements
- Transparency box explaining service model
- Footer disclaimer (liability protection)
- No fake reviews or claims
- Honest "connection service" positioning

---

## Adding New Emergency Types

1. Copy closest existing page
2. Update:
   - Phone number (all 4 locations)
   - Hero headline and gradient colors
   - "Why call" benefit cards
   - Page title and meta description
3. Add to footer nav on all pages
4. Add card to homepage grid

### Suggested Additions
- Garage door stuck
- Locksmith / locked out
- Roof leak
- Gas smell (with 911 safety notice)
- Sewer backup

---

## Seasonal Rotation

### Winter (Oct-Mar)
- Feature No Heat prominently
- Move No AC lower or hide

### Summer (Jun-Aug)
- Feature No AC prominently
- Move No Heat lower

**To rotate:** Reorder cards in `index.html` emergency grid.

---

## Deployment

Static HTML — deploy anywhere:
- Netlify
- Vercel
- Cloudflare Pages
- Any static host

### URL Structure
Configure server to serve without `.html`:
- `/no-heat` → `no-heat.html`
- `/basement-flooding` → `basement-flooding.html`
- etc.

---

## Key Metrics to Track

1. **Call Rate** — % of visitors who call
2. **Time to Call** — seconds from page load to call
3. **Page Performance** — calls per emergency type
4. **Device Split** — mobile vs desktop calls
5. **Bounce Rate** — leaving without action

---

## Liability Protection

All pages include:
- Clear "connection service only" messaging
- Transparency about independent contractors
- No guarantees about service outcomes
- Direct relationship disclaimer
- Footer legal disclosure

---

Built for one KPI: **Did a stressed Calgary homeowner call immediately?**
