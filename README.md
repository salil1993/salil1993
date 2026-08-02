<p align="center">
  <img src="./assets/banner.png" alt="Salil Jha — Senior Mobile Engineer" width="100%">
</p>

<p align="center">
  <strong>Senior Mobile Engineer</strong><br>
  React Native · Android · Node.js<br>
  Building production systems since 2017
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/saliljha1993">LinkedIn</a>
  ·
  <a href="mailto:saliljha1993@gmail.com">Email</a>
  ·
  <a href="https://github.com/salil1993">GitHub</a>
</p>

<br>

---

<br>

## Hello

I'm Salil. I write software for phones—and for the systems those phones depend on.

I started as a native Android developer in Java and Kotlin. React Native became my main tool later, not because it was fashionable, but because shipping one product across platforms stopped being optional on most teams I joined.

Seven years in, I still care more about how a system holds up after release than how it looks in a demo.

<br>

## About

Most of my work has been in fintech, crypto, healthcare, enterprise, and consumer products. Different domains, same pattern: unclear requirements, real users, and deadlines that don't wait for perfect architecture.

I usually own features end to end—product discussion, API shape, mobile implementation, testing, store release, and whatever breaks in the weeks after. That ownership changed how I write code. I design for the person who maintains it next, which is often me.

Screens are the easy part. The interesting work is deciding where state lives, how services talk to each other, what fails gracefully, and what needs to be fast.

<br>

## Right now

I'm spending most of my time on systems where the mobile app is one surface among several:

- **Bharat Swasthya Setu** — a healthcare platform spanning doctor tools, clinic operations, patient queues, appointments, and hospital dashboards
- **Trading platform work** — broker integrations, order flows, transaction history, and the edge cases that show up when money moves
- **Native Android again** — Kotlin and Jetpack Compose, alongside React Native's New Architecture

Outside client work I still build small backends and product experiments—mostly so I don't lose the habit of owning both sides.

<br>

## How I tend to build

I don't have a manifesto. A few habits have stuck:

| Prefer | Over |
| --- | --- |
| Clear module boundaries | Clever abstractions |
| Boring, readable code | Impressive one-liners |
| Measuring before optimizing | Guessing at bottlenecks |
| Fixing debt while shipping | Scheduling a rewrite later |
| APIs that survive versioning | APIs that only work for the current screen |
| Releases you can roll back | Releases you hope go fine |

Architecture matters because messy boundaries slow teams down. Performance matters because users notice lag before they can describe it. And I write for maintainability because six months later, I'm often the one opening the file again.

<br>

## Selected work

### Bharat Swasthya Setu

**Healthcare platform** · React Native · Next.js · PHP · MySQL

Clinics and hospitals still run on paper queues, phone calls, and disconnected tools. This platform tries to put patients, doctors, and clinic staff on one system—appointments, digital queues, clinic management, medical marketplace, and hospital-facing dashboards.

The hard part isn't any single feature. It's keeping roles, permissions, and workflows consistent when the same appointment means different things to a doctor, a receptionist, and a patient. I work across the mobile clients and the services behind them, with an eye on flows that won't fall apart when a clinic gets busy.

---

### PlansAround

**Event planning** · React Native · Node.js · Stripe · Firebase · Maps

People plan events in chat threads and spreadsheets. PlansAround turns that into a product: discover events, organize them, invite people, handle payments, and stay notified when something changes.

Engineering-wise, the interesting pieces were auth (Google), payments (Stripe), location and maps, and notification delivery—plus keeping the React Native app and Node backend aligned on the same domain model. Location and payments both fail in boring, real-world ways; most of the work was making those failures recoverable instead of confusing.

---

### Trading platform

**Fintech / crypto** · Mobile + shared business logic

I worked on registration, order execution, portfolio views, transaction history, and broker integrations. Trading UIs look simple until you account for partial fills, delayed confirmations, network drops, and the requirement that the mobile app and web never disagree about an order's state.

A lot of the job was tightening business logic and making edge cases explicit—especially around transaction history and broker responses that don't arrive clean or on time.

---

### BackendCRUD

**Node.js · Express · REST**

A small, public backend I built to practice the parts that usually get rushed: layered architecture, auth, reusable services, and API structure you'd actually deploy. It's not a tutorial dump—it's a reference for how I like backends organized when there's no deadline forcing shortcuts.

<br>

## What I work with

Tools I use regularly:

**Mobile**  
React Native · Android (Java / Kotlin) · Swift · Jetpack Compose · Native Modules

**Backend**  
Node.js · Express · REST APIs · Firebase

**Data**  
MySQL · PostgreSQL · SQLite

**Delivery**  
GitHub Actions · CI/CD · Play Store / App Store releases

I've also spent enough time on maps, push notifications, deep linking, and JWT auth that I treat them as product features, not checklist items.

<br>

## Learning lately

Things I'm actively digging into:

- React Native New Architecture (Fabric / TurboModules)
- Jetpack Compose and modern Android patterns
- Kotlin Multiplatform where it actually reduces duplication
- Mobile performance profiling—startup, lists, and network waterfalls
- AI tooling in the editor—useful for speed, still needs a human reviewing the result

<br>

## On this profile

A fair amount of my professional work sits behind NDAs, so what's public here is incomplete by design.

You'll mostly find mobile apps, Node services, architecture experiments, and utilities. I'm slowly opening more of the personal work. If something looks unfinished, it probably is—I'd rather publish something real than polish a demo forever.

<br>

## Contact

If you're hiring for senior mobile work, building a product that needs someone who can own the stack past the UI, or just want to talk through an engineering problem—reach out.

[LinkedIn](https://www.linkedin.com/in/saliljha1993) · [saliljha1993@gmail.com](mailto:saliljha1993@gmail.com)

<br>

---

<p align="center">
  <em>Ship something you can still maintain a year later.</em>
</p>
