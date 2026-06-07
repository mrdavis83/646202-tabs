# 646202-tabs

Bridgestone Firestone Store #646202 — Webster, NY  
Tab micro-frontends for the store dashboard at [646202.com](https://646202.com)

## Architecture

`index.html` — 8KB shell: topbar, tab bar, iframe loader  
`tabs/*.html` — 16 standalone tab files, each ~20KB

## Tabs

| File | Description |
|------|-------------|
| tabs/triage.html | Ticket management, tire calculator, quick links |
| tabs/cash.html | End-of-day cash reconciliation |
| tabs/drawer.html | Live drawer tracking throughout the day |
| tabs/phone.html | Contact directory |
| tabs/tires.html | Tire size calculator & reference charts |
| tabs/articles.html | Article number manager |
| tabs/parts.html | VIN decoder & parts reference |
| tabs/fleet.html | Fleet account management |
| tabs/dealers.html | Dealer & wholesale accounts |
| tabs/docs.html | Document quick links |
| tabs/team.html | Team roster & schedule |
| tabs/music.html | YouTube playlist manager |
| tabs/ops.html | Ops terminal & system links |
| tabs/files.html | File browser & uploads |
| tabs/monitor.html | Service health monitor |
| tabs/sms.html | SMS via Twilio |

## Auto-Deploy

Push to this repo → GitHub webhook → n8n → CT100 nginx
