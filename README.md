# Away, re-imagined

An interactive prototype of a trust-first travel booking flow.

**Live demo → https://ashish221singh.github.io/away-reimagined/**

> Best viewed on a phone (or as a centered phone frame on desktop).
> Hard-refresh to replay the intro.

## The idea

Every booking app shows you a low price and charges you a higher one — taxes,
fees, and the seat you either pay for or gamble on at the gate. So you end up
hopping across five apps comparing final prices.

Away flips that: **speak your trip, and it negotiates one final all-in price for
you** — seat, taxes, fees included. The price you see is the price you pay, and
the negotiation is shown item-by-item so you can trust it and adjust it.

## The flow

Splash → say your trip → Away negotiates → three curated flights →
trip detail (seat map, transparent negotiation breakdown, honest welcome
offer) → book → instant confirmation in your Bookings.

## Tech

A single self-contained `index.html` — no build step. WebGL splash (three.js),
GSAP-driven motion, Fraunces + Instrument Sans. Served via GitHub Pages.
`home.html` is the working source; `index.html` is the deployed copy.
