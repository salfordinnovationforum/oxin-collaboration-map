# Interactive Collaboration Map — Salford Innovation Forum

**Status:** Active
**Lead:** Artur Grzybowski, Innovation Director, Salford Innovation Forum
**Priority:** High
**Deliverable:** WordPress-embeddable interactive web map for PR campaign

---

## Vision

An interactive, beautifully designed map that makes visible how Salford Innovation Forum sits at the heart of a thriving Greater Manchester innovation ecosystem. Not just a building with offices — a connected hub linking 47+ businesses to universities, councils, industry partners, accelerators, and each other.

This is a PR tool. It needs to look stunning, feel premium, and tell a story: that OXIN and SIF are catalysts connecting Salford's innovators to the wider city-region and beyond.

## Why This Matters

- **PR campaign centrepiece** — A shareable, embeddable asset that tells the SIF story visually
- **Demonstrates ecosystem value** — Shows prospective tenants, partners, and funders that SIF creates real connections, not just desk space
- **Positions SIF within Greater Manchester** — Highlights how one centre connects to MediaCityUK, University of Salford, Salford Royal, the Innovation Triangle, and the wider GM ecosystem
- **Showcases OXIN network** — Links SIF to the other 4 GM centres (Stockport BIC, Merchants House, Merseyway, Ashton Old Baths) and the national network of 31+ centres
- **Supports funding bids** — Visual evidence of economic impact and ecosystem building for Salford City Council, GMCA, and Innovate UK conversations
- **Customer engagement** — Customers see themselves as part of something bigger than their office

---

## Scope: Three Layers of Connection

### Layer 1 — SIF Customers (The Core)

All 47 businesses at Salford Innovation Forum, visualised as nodes:

**Sectors represented (11+):**
- Technology & Software (9) — XpertRule Software, Qumulus, Code Maze, XE Business, XN Global Systems, IPEX Soft, Lumine Soft, Luwasuite, Josiah Lekundayo
- Charity & Social Enterprise (7) — Rio Ferdinand Foundation, Unlimited Potential, Inspiring Communities Together, Manchester City Mission, Lifeline NW CIC, Ready 4 Home, Advocacy Focus
- Education & Training (4) — Emotional Intelligence Academy, Jamie Ryder Spotlight Training, JC Academy of Finance, Ready 4 Work
- Health, Care & Wellbeing (4) — Honey-Serenity Care Solutions, V Care Health Supplies, Intimacy Insights, Centric Support
- Real Estate & Property (4) — Murphy Waldron Estates, BlueFin Management, U&S Investment, Big Easy Services
- Professional Services (4) — New Square Law, Braiden Acoustics, NWUPC, Unizen Recruitment
- Creative & Media (3) — Salford Media Works / Further Works, Saz Media, IvonMeldaByNwanne
- Employment Support (3) — Employment & Regen Partnerships, Salford Supply Desk, Ready 4 Work
- Retail & E-commerce (2) — Manchester Furniture Supplies, Numlock
- Marketing (1) — Optimo
- Other (4+) — Suja Driving School, Microrama, Green Chamber, ABEKS, A-Z Communities

**Known customer-to-customer connections:**
- IPEX Soft ↔ Murphy Waldron Estates (website development partnership)
- Rio Ferdinand Foundation ↔ The Manchester College (youth programme collaboration)
- Ready 4 Home ↔ Ready 4 Work (shared leadership: Paula White & Tom Nawn)

### Layer 2 — The Greater Manchester Ecosystem

Key institutions and partners that SIF businesses connect to:

**The Innovation Triangle (Salford's three poles):**
- University of Salford — Strategic partner, research collaborations, graduate talent pipeline
- MediaCityUK — BBC, ITV, 250+ SMEs, immersive tech hub (MITIH), Unlock the Future accelerator
- Salford Royal Hospital — Health tech connections, NHS partnerships

**Local Government & Development:**
- Salford City Council — SIF building owner, Crescent Development Framework partner
- Greater Manchester Combined Authority (GMCA) — £33M Innovation Accelerator, regional strategy
- English Cities Fund — Joint venture partner on Crescent Innovation masterplan

**Universities:**
- University of Salford — Direct SIF partner, campus proximity, Future Homes Project
- University of Manchester — Oxford Road Corridor, ID Manchester (£1.5B innovation district), Turing Innovation Hub
- Manchester Metropolitan University
- The Manchester College — Youth programmes with Rio Ferdinand Foundation

**Business Support & Innovation:**
- The Growth Company — GM's dedicated business support organisation
- Oxford Innovation Finance Angel Network — 7 annual showcase events for SIF businesses
- GROWTHmapper — Digital diagnostic tool used across OXIN network
- Innovate UK — Smart Grants, Knowledge Transfer Partnerships
- Bruntwood SciTech — Manchester Science Partnerships, co-investment

**Other Innovation Hubs & Programmes:**
- Google for Startups / Microsoft Accelerating Startups / AWS
- Barclays Eagle Labs
- HOST (digital inclusion)
- MITIH (MediaCity Immersive Technologies Innovation Hub)

### Layer 3 — The OXIN Greater Manchester Network

SIF as one of five Oxford Innovation Space centres across the city-region:

| Centre | Location | Specialism |
|---|---|---|
| **Salford Innovation Forum** | Salford (Frederick Road) | Health tech, science, robotics, engineering |
| **Stockport Business & Innovation Centre** | Stockport | Pioneer 10 accelerator, 4,000+ businesses supported |
| **Merchants House** | Stockport (Market Square) | Small business incubation |
| **Merseyway Innovation Centre** | Stockport (Town Centre) | ~50 businesses, opened 2023 |
| **Ashton Old Baths** | Tameside | Digital/creative/tech hub, Digital Dozen accelerator |

The map should show how these five centres form a connected OXIN cluster across Greater Manchester, with SIF as the focal point.

---

## Design Direction

### Aesthetic

The map should be **beautiful, modern, and on-brand for SIF** — not a generic data visualisation. Think:

- Abstract, stylised map of Greater Manchester as the canvas — recognisable geography but artistically rendered (not a Google Maps screenshot)
- Clean, modern sans-serif typography aligned with OXIN brand
- SIF brand tone: direct, friendly, community-first, innovation-positive
- Colour palette derived from SIF/OXIN branding, with sector-coding for customer nodes
- Premium feel suitable for a PR campaign — something people want to share and explore

### Interaction Design

Must support:
- **Zoom in/out** — From GM-wide view down to individual business detail
- **Pan** — Navigate across the map freely
- **Full screen** — Immersive viewing mode
- **Click/tap nodes** — Reveal business summary cards (name, sector, what they do, connections)
- **Hover highlights** — Show connection lines when hovering over a node
- **Filter/toggle layers** — By sector, by connection type, by business stage
- **Search** — Find a specific business or organisation
- **Animated transitions** — Smooth zoom, pan, node expansion

### Visual Elements

**Nodes:**
- SIF customers — Primary nodes, colour-coded by sector, sized by team or engagement
- Ecosystem partners — Secondary nodes (universities, MediaCity, councils, etc.)
- OXIN centres — Tertiary nodes showing the GM network
- Click any node for a summary card

**Edges (Connections):**
- Customer-to-customer collaborations (solid lines)
- Customer-to-ecosystem-partner links (dashed lines)
- OXIN centre-to-centre network links (dotted lines)
- Colour or thickness indicates connection strength/type

**Geographic Anchors:**
- Stylised River Irwell / Manchester Ship Canal
- Key landmarks: MediaCityUK, University of Salford campus, Salford Crescent station, Salford Royal
- The Innovation Triangle overlay
- SIF building as the central anchor point

---

## Technical Requirements

### WordPress Integration (Critical)

The final deliverable must be embeddable in a WordPress website:
- Self-contained HTML/CSS/JS package (or iframe-ready deployment)
- Responsive — works on desktop, tablet, and mobile
- Lightweight enough for reasonable page load times
- No server-side dependencies (static/client-side only)
- Deliverable as files that the marketing team can implement
- Must work within WordPress page builders (Elementor, Gutenberg, etc.)

### Technology

- **D3.js** or **Mapbox GL JS** for the interactive visualisation
- Canvas or SVG rendering (SVG preferred for crisp scaling)
- Vanilla JS or lightweight framework — no heavy dependencies
- JSON data file for easy updates (add/remove businesses without code changes)
- Consider WebGL for performance if node count grows significantly

### Export & Sharing

- Static image export (PNG/SVG) for reports and presentations
- Shareable URL with deep-linking to specific nodes/views
- Social media preview (Open Graph metadata)
- Print-friendly view for stakeholder decks

---

## Data Sources

- **Customer profiles** (`profile.md` files) — Sector, stage, description, goals
- **Session notes** — Introductions made, referrals given during mentoring
- **Event attendance** — Club 51 events, workshops, shared activities
- **The Wire** — Digital interactions between SIF members (when onboarded)
- **Direct customer survey** — "Who at SIF have you worked with? Who outside SIF?"
- **Public research** — Published partnerships, press releases, LinkedIn activity
- **OXIN network data** — Cross-centre connections, Angel Network participation

---

## Phases

### Phase 1 — Data Collection & Design Concepts (Current)
- Expand collaboration fields in customer profiles
- Survey customers on their connections (internal and external)
- Map known referrals, partnerships, and ecosystem links
- Research publicly available collaborations
- Produce 2-3 design concepts for review
- Define colour palette, node styles, interaction patterns

### Phase 2 — Build the Interactive Map
- Build the core visualisation engine
- Implement all three layers (customers, ecosystem, OXIN network)
- Add interaction: zoom, pan, fullscreen, click, filter, search
- Apply SIF brand design and polish animations
- Create the JSON data structure for easy updates
- Test across devices and browsers

### Phase 3 — WordPress Integration & PR Launch
- Package as WordPress-embeddable component
- Work with marketing team to integrate on SIF website
- Create static exports for presentations and reports
- Prepare social media assets and Open Graph previews
- Brief PR campaign materials around the map launch
- Coordinate launch with Salford City Council / GMCA comms teams

### Phase 4 — Maintain & Expand
- Update after mentoring sessions where new connections form
- Add new customers as they join SIF
- Expand to show cross-centre connections as other OXIN centres adopt the tool
- Present to OXIN network as a replicable model

---

## Replicability

The map tool should be built so any OXIN centre can:
1. Populate their own customer and ecosystem data (via JSON)
2. Apply their own centre branding (colours, logos, typography)
3. Generate their own collaboration map
4. Contribute to a potential network-wide map showing all 31+ OXIN centres and their ecosystems
5. Embed on their own WordPress site with minimal technical effort

---

## Success Metrics

- Map is live on SIF WordPress site
- Shared in at least one PR campaign / press release
- Used in stakeholder presentations to Salford City Council and GMCA
- At least 20 of 47 customers have visible connections mapped
- Positive feedback from customers ("I didn't know we were connected to all this")
- At least one other OXIN centre expresses interest in replicating
