# PRD — Platinum Pools Website

*Generated with AI from PROPOSAL.md, per MP1 Milestone 0 requirements.*

## Overview

A three-page static marketing site for Platinum Pools, an owner-operated
pool service company in Rowley, MA. The site replaces a basic WordPress
page with a clean, mobile-friendly presence optimized for one outcome:
getting customers to call.

## Goals

1. Make the phone number visible on every page without scrolling
2. Clearly list all service areas so customers know the company
   handles everything from chemical drops to full installations
3. Look professional on a phone, since most local searches happen there

## Non-Goals

- No online booking or forms (client prefers phone contact and does
  not regularly check email during the day)
- No e-commerce, blog, or CMS
- No JavaScript — static HTML/CSS only (MP1 scope)

## Users

Homeowners with pools on the Massachusetts North Shore, typically
searching on mobile for "pool service near me." They need to know:
does this company do what I need, do they cover my town, and how do
I reach them.

## Features

### F1 — Persistent header with click-to-call
Every page shares a header with the business name, three nav links,
and the phone number as a tappable `tel:` link styled as a button.

### F2 — Home page
Hero with the company tagline ("We handle all your pool needs"),
short about section emphasizing owner-operated service, a services
teaser, and a service-area strip — because "do you service my town"
is the top customer question.

### F3 — Services page
Weekly service explained as a what's-included list (the second most
common customer question), plus cards for openings/closings with
scheduling guidance, water testing and chemicals, repairs and
equipment, and installations. Cards use Flexbox and wrap to a column
on screens under 600px. A photo gallery is built but commented out
until the client provides images.

### F4 — Contact page
Phone number first (client's stated preference), street address,
and the service-area town list.

## Technical Requirements

- Semantic HTML5: `header`, `nav`, `main`, `section`, `footer`
- One external stylesheet, Flexbox layout, one mobile media query
- SVG favicon
- Deployed via GitHub Pages from the repo root

## Success Criteria

- Client approves the live site (Conversation 2 documented in proposal)
- Lighthouse accessibility score 80+
- All MP1 base requirements met by Friday 6/12
