# POK — Streetwear Concept Store

A fictional streetwear brand site with a clean, design-led front end and a
database-backed product search.

## Overview
A secondary-school project: the front end was built in vwo 4 (2021–22), and a
database module added in vwo 5 lets the "Database" page query a product
catalogue by table and filter by maximum price, rendering the results with
images.

## Tech
HTML · CSS · PHP · MySQL

## Features
- A design-focused landing page and shop, with a custom logo treatment and
  consistent brand styling.
- A product database page: choose a table, set a maximum price, and the page
  runs a `SELECT` query and displays the matching products (name, brand, price,
  image).

## Run it
- The static front end (HTML/CSS) can be hosted on **GitHub Pages** — live link
  in the About box.
- The database page uses **PHP/MySQL**, which needs a server to run (it won't
  execute on GitHub Pages), so the screenshot shows that part in action.

## Notes
A non-commercial student project — some images are third-party placeholder art
used purely to mock up the design. An early-PHP caveat: user input on the
search should be parameterised to guard against SQL injection (a fix I'd apply
revisiting it today).
