# Burrito Palace Website

## Project overview

This repository contains the lightweight static website for Burrito Palace. The current implementation uses plain HTML, CSS, and JavaScript with the existing Burrito Palace branding, logo assets, color palette, Plus Jakarta Sans typography, food imagery, and menu content.

## Current business information

- Restaurant name: Burrito Palace
- Address: 1100 Marshall Road, Vacaville, CA 95687
- Phone: (707) 447-1250
- Telephone URI: `tel:+17074471250`
- Hours:
  - Monday–Saturday: 9:00 AM–7:30 PM
  - Sunday: 9:00 AM–1:00 PM
- Time zone: America/Los_Angeles
- Directions: <https://www.google.com/maps/search/?api=1&query=1100+Marshall+Road+Vacaville+CA+95687>
- DoorDash: <https://www.doordash.com/store/burrito-palace-restaurant-vacaville-260476/1788766/?pickup=true>
- Grubhub: <https://www.grubhub.com/restaurant/burrito-palace-1100-marshall-rd-vacaville/7580688?pickup=true>

## Deployment notes

The site is static and can be deployed from the repository root to any static web host. Serve it through HTTP/HTTPS rather than relying on `file://` URLs so root-relative links such as `/menu.html` and `/images/...` resolve correctly.

No build step, package manager, database, analytics, cookies, or third-party JavaScript libraries are required for this first-pass relaunch.

## Information Needed Before Final Launch

- [ ] Confirm production domain
- [ ] Confirm current menu prices
- [ ] Confirm current specials
- [ ] Confirm the correct category for Huevos Con Chorizo
- [ ] Confirm the correct category for Mexican Omelet
- [ ] Confirm whether catering is offered
- [ ] Confirm approved contact email
- [ ] Confirm approved social media accounts
- [ ] Confirm whether pickup=true should remain the default on both ordering links
- [ ] Confirm whether holiday hours differ
- [ ] Confirm restaurant approval of homepage copy
