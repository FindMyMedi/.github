# FindMyMedi

**Real-time medicine availability for Sri Lanka.**

Patients waste hours visiting multiple pharmacies looking for medicines. Pharmacies have no digital presence. FindMyMedi fixes both.

---

## What We're Building

A platform that connects patients with nearby pharmacies that actually have their medicines in stock — right now.

**For patients:** Search for a medicine, see which pharmacies near you have it, submit a prescription list, and get a WhatsApp payment link for cash pickup. No more pharmacy hopping.

**For pharmacies:** A simple staff app to receive prescription requests, respond per item, and confirm orders — no tech expertise required.

---

## How It Works

```
Patient searches medicine
        ↓
Nearby pharmacies with stock appear on a map
        ↓
Patient submits prescription list
        ↓
Each pharmacy responds item-by-item
        ↓
WhatsApp bill link sent → patient picks up and pays cash
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Go 1.22 · Gin · GORM · 5 microservices |
| Mobile | Flutter 3.x (patient app + pharmacy staff app) |
| Web | React 18 · TypeScript · Vite · Tailwind CSS |
| Database | PostgreSQL 16 + PostGIS · Redis 7 |
| Notifications | Firebase FCM · WhatsApp Business API |
| Storage | Cloudflare R2 |
| Infrastructure | Docker · Traefik · DigitalOcean |

Android-first. Sri Lanka-first.

---

## Repositories

| Repo | Description |
|---|---|
| `backend` | Go microservices — search, pharmacy, order, notification, auth |
| `mobile` | Flutter apps for patients and pharmacy staff |
| `web` | React dashboard for pharmacy owners and admin |
| `infra` | Docker Compose, Traefik config, deployment scripts |

---

## Status

> **In active development — MVP in progress**

- [x] Architecture and folder structure finalized
- [x] API contracts designed
- [ ] Core backend services
- [ ] Flutter mobile apps
- [ ] React web dashboard
- [ ] Beta launch with pilot pharmacies

---

## The Problem We Solve

Sri Lanka's pharmacy sector is fragmented and offline. Patients with chronic conditions — diabetes, hypertension, thyroid — refill prescriptions every month and often cannot find all their medicines at a single pharmacy. There is no way to check stock before visiting.

FindMyMedi brings real-time inventory visibility to pharmacies of all sizes, starting with a free tier so even small, independent pharmacies can participate.

---

*Built in Sri Lanka. For Sri Lanka.*
