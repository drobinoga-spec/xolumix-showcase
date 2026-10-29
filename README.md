# Xolumix 📊

**Turn an Excel or CSV sheet into a small team app — list, form, board and summary. No coding.**

🔗 **Live:** [xolumix.ximplex.app](https://xolumix.ximplex.app) · [Español](https://xolumix.ximplex.app/es) · [Português](https://xolumix.ximplex.app/pt)
🧁 **Interactive demo (no login):** [xolumix.ximplex.app/demo](https://xolumix.ximplex.app/demo)
💳 **Pricing:** [xolumix.ximplex.app/pricing](https://xolumix.ximplex.app/pricing)

> This is a public showcase. The source code lives in a private repository.

## The problem

Most small businesses run on one spreadsheet that slowly outgrows itself: duplicated rows, phone numbers that lose their leading zero, totals that turn into `#REF!`, and five people editing the same file.

## What Xolumix does

Upload one sheet and Xolumix builds a small app on top of it, with four "burners":

- 📋 **List** — search, filter and open a card for every record, with its change history
- 📱 **Form** — add or edit records from a phone
- 🗂️ **Board** — move cards between statuses (Kanban), when the sheet has a status column
- 📊 **Summary** — group by a column and sum or count, with a simple chart

Under the hood: column type detection (text, number, date, yes/no, options), clean-up on import (trims spaces, flags duplicates, keeps leading zeros as text), and export back to Excel at any time. Your data stays yours.

## Status

- ✅ Landing page, pricing and legal pages in **English, Spanish and Portuguese**, with day/night mode
- ✅ **Interactive demo**: a messy bakery sheet ("Sweet Crumb") becomes an app, with an import report, list, board, summary, edit form and a real CSV export
- 🛠️ **In progress**: the real app — Supabase database, shared Ximplex login, team invites by magic link, roles, history and subscriptions

## Stack

Next.js 16 · React · TypeScript · Tailwind CSS 4 · next-intl (EN/ES/PT) · Supabase (Postgres) · Resend · Vercel · Paddle

## How I build it

I build Xolumix with **Claude Code** as my daily pair programmer:

- Separate Claude Code sessions for each area (product, marketing, admin dashboard), each with
