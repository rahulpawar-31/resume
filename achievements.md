[« Back to Resume](./README.md)
# Achievements

- [Achievements](#achievements)
    - [Webby Wonder](#webby-wonder)
    - [DevOS](#devos-personal-ai-agent)
    - [Car Rental Platform](#car-rental-platform)
    - [Lineup](#lineup)
    - [Developer Portfolio](#developer-portfolio)
    - [More Projects](#more-projects)

### Webby Wonder
Three products: CountryStateCity (developer API), MakeMySiteLive (static-site hosting) and RemoteGig (remote job board).

**2026 Achievements** _(Junior Web Developer Intern, Apr 2026 - Present)_

_By the numbers (GitHub, Oct 2026)_
- 200+ merged pull requests across 8 repositories: RemoteGig 69, MakeMySiteLive 63, CountryStateCity app 23, docs 18, website 13, open source database 10, export tool 4, plus Lineup 3
- 590+ commits across these repositories

_CountryStateCity: API_
- Location autocomplete and nearby search endpoints
- Localized place names and translated search
- Data change feed and a data-version route and header
- Unified error format with reset time in rate-limit responses
- Classified cities as settlement, administrative, section or unknown
- Added a GraphQL API for geographic data (Phase 1)
- Postcode Lookup and Search API; fixed geo search indexes and postcode coordinate types after imports
- Added missing database indexes for bulk geo endpoints; batched pricing lookups to speed up at-risk account detection
- Release-tagged Sentry and added dashboard error reporting
- Tracked the npm-to-API conversion funnel
- Added a Growth and Ops Agent (Phase 1)

_CountryStateCity: Dashboard, Billing, Export Tool and Website_
- Introduced annual billing plans; started a grace period for on-hold and failed subscriptions
- Export tool: region and subregion filters, translation locale support, tiered field pricing, CSV and SQL type fixes, a public credits pricing endpoint
- Website: redesign, live stats from the API, SEO fixes (canonical URLs, sitemap), privacy policy and a cookie notice that loads analytics only after consent
- Docs: wrote 18 documentation pull requests covering errors and rate limits, TypeScript SDK, CLI, autocomplete, nearby search, localized names, change feed, postcode search and GraphQL

_Open source: countries-states-cities-database_
- Added a Parquet export format and npm and PyPI package tables to the README
- Fixed postcode duplicate detection; corrected data for Germany, India, Mexico and a Russian translation

_MakeMySiteLive: Hosting Platform_
- Deploy pipelines, versioned rollbacks, ZIP download of any version, share links for password-protected sites
- One-time upload links for large ZIPs from MCP clients; opt-in background deploys
- Custom domains with automatic DNS setup (Domain Connect)
- Deploy security check (Autopilot) and a pre-share Preflight check with a Fix it button
- Serve a site's own 404 page, fix trailing-slash URLs, redirect www
- Pinned Comments: backend, browser overlay, MCP tools and owner controls
- Microsites with PWA settings, never indexed by search engines; convert a microsite to a full site
- Site Growth Tools: WhatsApp button, analytics, page views, SEO and social tags

_MakeMySiteLive: AI and MCP_
- MCP guides and prompt templates for Claude, ChatGPT and Cursor
- Fixed the ChatGPT MCP connector sign-in (cookie loss across hosts)
- Admin-only MCP tools for site review, moderation, reports and analytics
- Tracked which surface creates each site: web, MCP or API

_MakeMySiteLive: Admin, Billing and Growth_
- Admin dashboard: review notes, user detail, storage, per-site views, last sign-in, real payment status
- Fixed a billing currency mismatch; volume discount tiers and per-site billing
- Led a seven-phase redesign: foundations and shared components, home, screenshot guides, owner dashboard, admin, emails
- Published 18+ SEO blog posts and 2 compare pages aimed at Search Console keyword gaps

_RemoteGig: Job Board_
- Static job site with search, filters, feed importers and scheduled refresh
- Redesigned the site in teal and saffron: home, header, footer, logo, favicon
- India pages and a data annotation page; closed-job and gone-job pages
- Feedback and Report pages and listing reports in the API
- Tailor page and a resume reader for years, roles, tools and AI skills
- SEO work on titles, descriptions, headings, company pages and category pages
- Deploy fixes: send the zip once and poll after a 524, fail early over 2,000 files, keep the site under the host's file limit

_Launch and Tooling_
- Drafted and spam-tested a launch email for about 50,000 API users: 9.8/10 spam score before handoff to an email service provider
- Built a Chrome extension (Manifest V3) that exports WhatsApp chats
- Created HTML email templates in two styles and a cross-promotion plan for the two products

_Recognition_
- `[unknown: feedback, awards or shout-outs from Webby Wonder]`

### DevOS, Personal AI Agent
- 120+ commits; built an AI command center for Gmail, Google Calendar, Notion, GitHub, Trello and Slack on free-tier Gemini 2.5 Flash and Groq Llama 3.3 APIs
- Wrote an LLM router that falls back from Gemini to Groq on rate limits
- Designed a morning digest where 6 sub-agents run in parallel on a schedule and post to Slack
- Built email triage with P1/P2/P3 priority scoring and auto-drafted replies with one-tap approve and send; send is gated while drafts stay immediate
- Added calendar conflict detection, focus-block protection and pre-meeting briefs
- Built a task sync layer across Notion tasks, GitHub PR staleness and Trello cards
- Added an intent-classification chat layer and a persistent memory store for voice, VIP contacts and preferences
- Added multi-user accounts with an admin page showing connected services and saved keys per account
- Security hardening: security headers, rate limits, limit on failed sign-ins, server-side session end at logout, validation of user-supplied URLs, one validated email helper, and key rotation that keeps saved keys readable
- Fixed a chat outage by replacing retired AI models and reporting provider failures clearly
- Redesigned every page and made the app usable on phones: calendar, tab bar, mail list, chat

### Car Rental Platform
- 50+ commits; built a full MERN booking and payments platform with JWT authentication
- Integrated Stripe and Razorpay; Cloudinary for vehicle images; Winston for structured logging
- Hardened auth: strict rate limits, cookie-only web auth, no access token in localStorage, password-change check on optional auth
- Added zod request validation to booking and payment routes
- Added CI with a dependency audit gate and a Playwright end-to-end smoke test
- Deployed as a Vite monorepo on Vercel and worked through Razorpay's onboarding process

### Lineup
Multi-tenant salon booking platform (team project).
- Built the multi-tenant base: salons, console, impersonation, per-salon payments and URLs, billing, plan and trial defaults
- Service-based booking: pick a service, dynamic start times, advance payment
- Manual refunds, cancel reason with UPI, rolling 7-day booking window, live walk-in status and a customer profile page
- Widened barber login to salon-wide staff access
- Replaced a deploy workflow with lint and build checks in CI

### Developer Portfolio
- 75+ commits; built with Next.js 16, React 19, Tailwind CSS 4, Framer Motion; dark and light mode
- Saves contact form messages to Neon PostgreSQL through Prisma 7 and sends email notifications with Resend
- Added a live view counter per project page
- Set up CI/CD: dev branch, build, PR, merge, automatic Vercel deploy, branch protection on main
- Resolved Prisma 7 breaking changes (Neon driver adapter, build-time queries in generateStaticParams)

### More Projects
- **Payload E-commerce** (47 commits): Payload CMS and Next.js storefront with roles, cart, orders and Dodo Payments
- **Library Management System**: Express 5 and MongoDB REST API with JWT, OTP password reset, roles and image uploads
- **Jev Job Scorer**: Flask and SQLite app that fetches live remote jobs and scores them against a resume
