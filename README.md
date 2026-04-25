## Hi, I'm Aqib 👋

I'm a full-stack engineer based in Bangladesh. Most of my work lives somewhere between a well-designed database and a fast, content-driven frontend — usually in Next.js with Payload CMS as the backbone.

Right now I'm the sole engineer on **Utilian** at Streams Tech, a SaaS platform for U.S. customers. I handle the full engineering side — system design, data modelling, API, UI, and production on Vercel. It's the kind of work I enjoy most — translating designs and business decisions into a system that actually ships.

---

### What I actually build

My default setup is **Next.js 16** (App Router), **Payload CMS 3** for the content and data layer, **Drizzle ORM** on Postgres, and **oRPC** for end-to-end types. Auth is almost always **Better Auth**. Deployments go to **Vercel** or **Cloudflare Workers** depending on what the project needs.

I also build native mobile apps with **Expo** — the Qibla app (pinned below) is a mosque-finder for iOS and Android that shares a Cloudflare Workers backend via a Turborepo monorepo.

---

### A few things I've shipped

**Utilian** — Production SaaS at my day job. Built a Payload CMS content pipeline that cut the marketing team's update cycle from days to minutes. Integrated Elavon payments and a custom license management system. Deployed on Vercel.

**Jack's Burger Admin** — Multi-branch restaurant management and POS platform. 28 data models, 100+ API endpoints, branch-scoped multi-tenant architecture, PostGIS delivery zones, RBAC across 5 roles, full inventory and POS backend. One of the more complex systems I've designed from scratch.

**TrainBook** — Bangladesh railway booking platform. Real-time seat maps, a dual-layer reservation system with optimistic locking and FIFO queues to handle concurrent bookings cleanly, Stripe Connect for operator payouts. 12,000+ lines of code.

**Qibla** *(pinned)* — iOS and Android mosque-finder. Map discovery, prayer times, qibla compass, push reminders. Expo on the native side, TanStack Start on Cloudflare Workers for the API, Drizzle on Neon Postgres.

---

### Stack

| | |
|---|---|
| **Web** | Next.js 16, TanStack Start, React 19, Tailwind CSS 4, shadcn/ui |
| **CMS** | Payload CMS 3 |
| **API** | oRPC, Node.js, Cloudflare Workers, Convex |
| **Database** | PostgreSQL (+ PostGIS), Neon, Drizzle ORM, MongoDB |
| **Auth / Payments** | Better Auth, Clerk · Stripe Connect, Elavon |
| **Mobile** | Expo SDK 54, React Native, Expo Router, NativeWind, EAS |
| **Infra** | Vercel, Cloudflare Workers + R2, Dokploy, Turborepo, Bun |

---

BSc CSE from IUT · CGPA 3.93 / 4.00 🎓

**aqibrime@gmail.com** · [LinkedIn](https://linkedin.com/in/aqibrime)
