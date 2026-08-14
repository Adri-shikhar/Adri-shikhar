```
┌─────────────────────────────────────────────────────────────────────────────┐
│  FIG. 01  ·  OPERATOR PROFILE                                SHEET 01 / 03  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ADRISHIKHAR BARUA                                SCOPE                    │
│   ├───────────────┤                                ├── FRONTEND             │
│   FULL-STACK ENGINEER                              ├── BACKEND              │
│                                                    └── DATABASE             │
│   CSE UNDERGRAD · IIUC · CHITTAGONG, BD                                     │
│                                                                             │
├─────────────────────────────────────────────────────────────────────────────┤
│  @ADRI-SHIKHAR                                 SCALE 1:1     REV 2026.08    │
└─────────────────────────────────────────────────────────────────────────────┘
```

> **GENERAL NOTES**
> 1. Full-stack engineer. CSE undergrad at International Islamic University Chittagong.
> 2. Builds role-based web platforms &mdash; identity, payments, dashboards, live state.
> 3. This sheet is drawn by hand. No badge services, no generators, no third-party cards.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  FIG. 02  ·  CAPABILITY MATRIX                               SHEET 02 / 03  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│  LANGUAGE      TypeScript · JavaScript · Python · C++ · HTML5 · CSS3        │
│                                                                             │
│  FRAMEWORK     Next.js 16 (App Router, Server Components, Server Actions)   │
│                React 19 · Node.js · Express.js                              │
│                                                                             │
│  INTERFACE     Tailwind CSS 4 · HeroUI · DaisyUI · Flowbite React           │
│                Framer Motion · Swiper · Vite · responsive + dark mode       │
│                                                                             │
│  DATA          MongoDB · Mongoose · Prisma · SQLite · Firebase              │
│                                                                             │
│  IDENTITY      Better Auth · Firebase Auth · Google OAuth                   │
│                role-based access control · protected routes                 │
│                                                                             │
│  PAYMENT       Stripe Checkout · bKash                                      │
│                credit ledger · pending holds · auto-refund                  │
│                                                                             │
│  TOOLING       Git · GitHub · Vercel · Postman · VS Code · imgBB            │
│                                                                             │
├─────────────────────────────────────────────────────────────────────────────┤
│  ALSO          700+ problems solved on Codeforces  ·  DSA in C++            │
└─────────────────────────────────────────────────────────────────────────────┘
```

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  FIG. 03  ·  SYSTEM ARCHITECTURE / TYPICAL BUILD             SHEET 03 / 03  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│ ┌──────────────────┐       ┌───────────────────┐        ┌─────────────────┐ │
│ │ A · PRESENTATION │       │ B · APPLICATION   │        │ C · PERSISTENCE │ │
│ ├──────────────────┤ write ├───────────────────┤  read  ├─────────────────┤ │
│ │ CLIENT           │ ────> │ SERVER            │  ────> │ STORE           │ │
│ │ Next.js 16       │       │ Server Actions    │        │ MongoDB         │ │
│ │ React 19         │       │ Route Handlers    │        │ Mongoose        │ │
│ │ Tailwind 4       │       │ Express.js        │        │ Prisma / SQLite │ │
│ └────────┬─────────┘       └─────────┬─────────┘        └─────────────────┘ │
│          │                           │                                      │
│          └─────────────┬─────────────┘                                      │
│                        │                                                    │
│                 ┌──────┴────────┐                                           │
│                 │ CROSS-CUTTING │  Better Auth · Stripe · bKash             │
│                 └───────────────┘                                           │
│                                                                             │
├─────────────────────────────────────────────────────────────────────────────┤
│  DEPLOY        Vercel  ·  serverless functions  ·  edge runtime             │
└─────────────────────────────────────────────────────────────────────────────┘
```

## `FIG. 04` &mdash; PROJECT SCHEDULE

| REF | ASSEMBLY | FUNCTION | DRAWINGS |
|:---|:---|:---|:---|
| **P&#8209;01** | **TICKIFY**<br><sub>`Next.js 16` `React 19` `MongoDB` `Stripe`</sub> | Multi-vendor travel ticketing across bus, train, launch and flight. Three role surfaces: customers book and track transactions, vendors post trips and watch revenue, admins gate approvals. Server Actions end to end, Better Auth for identity, Stripe for checkout. | [live](https://tickify-psi.vercel.app) &middot; [client](https://github.com/Adri-shikhar/tickify) &middot; [server](https://github.com/Adri-shikhar/tickify-server) |
| **P&#8209;02** | **FUNDSPRING**<br><sub>`Next.js 16` `TypeScript` `Firebase` `Stripe`</sub> | Credit-based crowdfunding. Pledges are *held*, not spent &mdash; creators approve or reject, and rejected pledges auto-refund to the backer's balance. Withdrawals clear at a 200-credit floor against a 20:1 USD rate. Supporter, creator and admin dashboards, each role-guarded. | [repo](https://github.com/Adri-shikhar/crowfunding-platform) |
| **P&#8209;03** | **MEDIQUEUE**<br><sub>`Next.js 16` `Express` `MongoDB` `Better Auth`</sub> | Tutor discovery and session booking. Availability is a live counter &mdash; slots decrement on booking and restore on cancellation, so two students can't claim the same hour. Separate tutor and student dashboards over an Express/MongoDB service. | [live](https://mediqueue-tutor-booking-system.vercel.app) &middot; [client](https://github.com/Adri-shikhar/mediqueue_tutor_booking_system) &middot; [server](https://github.com/Adri-shikhar/mediqueue_server) |

## `FIG. 05` &mdash; INDEX OF ADDITIONAL SHEETS

<table>
<tr>
<td width="33%" valign="top">

**WANDERLUST**<br>
<sub>Travel platform &middot; MERN</sub><br>
[live](https://wanderlust-client-4ghv.vercel.app) &middot; [repo](https://github.com/Adri-shikhar/wanderlust-client)

</td>
<td width="33%" valign="top">

**SKILLSPHERE**<br>
<sub>Learning platform &middot; Next.js</sub><br>
[live](https://skillsphere-learning-platform.vercel.app) &middot; [repo](https://github.com/Adri-shikhar/skillsphere-learning-platform)

</td>
<td width="33%" valign="top">

**HIRELOOP**<br>
<sub>Hiring platform &middot; Next.js</sub><br>
[client](https://github.com/Adri-shikhar/hireloop_client) &middot; [server](https://github.com/Adri-shikhar/hireloop_server)

</td>
</tr>
</table>

## `FIG. 06` &mdash; TITLE BLOCK

| FIELD | VALUE |
|:---|:---|
| **EMAIL** | [adrishikharbarua77452@gmail.com](mailto:adrishikharbarua77452@gmail.com) |
| **LINKEDIN** | [/in/adri-shikhar-barua](https://www.linkedin.com/in/adri-shikhar-barua/) |
| **CODEFORCES** | [700+ problems solved](https://codeforces.com/profile/YOUR_HANDLE) |
| **LOCATION** | Chittagong, Bangladesh |
| **STATUS** | Open to internships and freelance work |

<sub>`SHEET 03/03`&nbsp;&nbsp;&middot;&nbsp;&nbsp;`SCALE 1:1`&nbsp;&nbsp;&middot;&nbsp;&nbsp;`REV 2026.08`</sub>
