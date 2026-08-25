# Password Generator

Password Generator: build with HTML/CSS/Flexbox/Vanilla JavaScript

[Live demo](https://github.com/Flammendeingo-85/passwordgenerator)

![Screenshot](./assets/design/Scherm­afbeelding%202026-08-25%20om%2021.13.29.png)

## Features

- Generate two different passwords
- Click-to-Copy

## Tech Stack

- HTML
- Vanilla JavaScript
- CSS Flexbox
- Prisma + PostgreSQL

## Getting Started

- One of th things i learned when creating this project:
  'Math.random() is "predictable enough that someone who knows when you generated it could narrow down the result." That's me embellishing. MDN's actual position is simpler and stronger: Math.random() does not provide cryptographically secure random numbers and should not be used for anything security-related — use the Web Crypto API's Crypto.getRandomValues() instead'.
  So when going live with a live app, make sure the Web Crypto API's Crypto.getRandomValues() is used.

### Prerequisites

### Environment variables

Create a `.env` file in the root: