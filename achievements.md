[« Back to Resume](./README.md)
# Achievements

- [Achievements](#achievements)
    - [Webby Wonder](#webby-wonder)
    - [DevOS](#devos-personal-ai-agent)
    - [Car Rental Platform](#car-rental-platform)
    - [Developer Portfolio](#developer-portfolio)

### Webby Wonder
Two products: CountryStateCity (developer API) and MakeMySiteLive (static-site hosting).

**2026 Achievements** _(Junior Web Developer Intern, Apr 2026 - Present)_

_CountryStateCity_
- Maintain and extend the developer API: endpoints, data integrity, versioning
- Contribute to the API dashboard and documentation

_MakeMySiteLive_
- Built deploy pipelines and versioned rollbacks
- Designed wildcard subdomain routing and multi-tenant, host-based routing
- Tested versioning and rollbacks end to end by deploying a car rental landing page and a terminal-style portfolio to the platform
- Explored the architecture (Cloudflare R2 storage, NextAuth, Stripe and Razorpay billing) and scoped billing with Stripe, Razorpay and Dodo Payments

_Launch and Tooling_
- Drafted and spam-tested a launch email for about 50,000 API users: 9.8/10 spam score before handoff to an email service provider
- Built a Chrome extension (Manifest V3) that exports WhatsApp chats
- Created HTML email templates in two styles and a cross-promotion plan for the two products

_Recognition_
- `[unknown: feedback, awards or shout-outs from Webby Wonder]`

### DevOS, Personal AI Agent
- Built an AI command center for Gmail, Google Calendar, Notion, GitHub, Trello and Slack on free-tier Gemini 2.5 Flash and Groq Llama 3.3 APIs
- Wrote an LLM router that falls back from Gemini to Groq on rate limits
- Designed a morning digest where 6 sub-agents run in parallel on a schedule and post to Slack
- Built email triage with P1/P2/P3 priority scoring and auto-drafted replies with one-tap approve and send
- Added calendar conflict detection, focus-block protection and pre-meeting briefs
- Built a task sync layer across Notion tasks, GitHub PR staleness and Trello cards
- Added an intent-classification chat layer and a persistent memory store for voice, VIP contacts and preferences

### Car Rental Platform
- Built a full MERN booking and payments platform with JWT authentication
- Integrated Stripe and Razorpay; Cloudinary for vehicle images; Winston for structured logging
- Deployed as a Vite monorepo on Vercel and worked through Razorpay's onboarding process

### Developer Portfolio
- Built with Next.js 16, React 19, Tailwind CSS 4, Framer Motion; dark and light mode
- Saves contact form messages to Neon PostgreSQL through Prisma 7 and sends email notifications with Resend
- Added a live view counter per project page
- Set up CI/CD: dev branch, build, PR, merge, automatic Vercel deploy, branch protection on main
- Resolved Prisma 7 breaking changes (Neon driver adapter, build-time queries in generateStaticParams)
