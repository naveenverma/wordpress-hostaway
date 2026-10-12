# WordPress ↔ Hostaway Integration

Bridge between WordPress and the [Hostaway Public API](https://api.hostaway.com/) for short-term rental operators.

## Capabilities

| Area | Operations |
|------|------------|
| **Listings** | Create, update, delete |
| **Reservations** | Create, update, delete |
| **Calendars** | Read listing availability |
| **Blocks** | Block / unblock calendar days |

All traffic is **HTTPS + JSON** against Hostaway’s REST API (no unofficial scrapers).

## Stack

PHP · WordPress · Hostaway Public API (REST)

## Typical use

Property managers who run marketing or booking flows on WordPress but keep inventory and calendars in Hostaway — sync listings and reservations without re-keying.

## Status

Public reference repo for the Hostaway WordPress bridge. For a production install or custom field mapping, contact [Haatch Media](https://www.haatchmedia.com).
