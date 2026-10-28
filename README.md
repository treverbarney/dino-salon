# Dino Salon

**Enhanced open-source appointment system focused on salons, spas, barbershops, and tattoo studios. Built from free open-source forks. More abilities than Dino Booking.**

## Base Forks Used

- **Primary base**: [clawnify/OpenSalon](https://github.com/clawnify/OpenSalon) (AGPL, Preact + Tailwind + Hono + SQLite) — day calendar with staff columns, client DB, services, inventory, AI agent mode.
- **Additional patterns**: Multi-staff rules from Easy!Appointments, payments/WhatsApp ideas from NexCal and Pronto.

Zero cloud dependencies. Runs locally with SQLite. Self-hostable.

## Why It's Better Than Dino Booking

| Feature | Dino Booking | Dino Salon |
|---------|--------------|------------|
| Staff calendar with columns | Partial | Full day view with colored blocks + click-to-book |
| Client database | Yes | Full notes, preferences, history, search |
| Inventory | Limited | Product catalog + low-stock alerts |
| AI agent mode | Limited | Dual human + AI-agent UI (`?agent`) |
| Lightweight / zero-cloud | No | Yes — SQLite, no external services required |
| Portable day sheets | No | CSV export of day's appointments |
| Status workflow | Basic | booked → confirmed → in progress → completed |
| Tattoo / salon focus | Partial | Purpose-built for appointment businesses |

**Extra abilities**: AI-agent optimized UI, zero-cloud local run, portable exports, stronger staff column calendar.

## Quick Start

```bash
git clone https://github.com/treverbarney/dino-salon.git
cd dino-salon
# Follow OpenSalon quickstart once code is synced, or:
pnpm install
pnpm run dev
```

Open http://localhost:5174

Data persists in `data.db`.

## Tech Stack

- Preact + TypeScript + Vite
- Tailwind CSS v4 + shadcn/ui
- Hono backend
- SQLite (better-sqlite3)
- Zod validation

## Roadmap / Enhancements

- [x] OpenSalon base
- [ ] Dino branding (sage/cream palette)
- [ ] Payments integration patterns
- [ ] Stronger multi-staff booking rules
- [ ] Public booking page polish
- [ ] Document / aftercare templates for tattoo

## License

AGPL-3.0 — free for personal and commercial use with source sharing requirements for network use.

---

Part of the Dino Booking family. Lightweight, focused, and ready for appointment-based businesses.
