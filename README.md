# Mum Muyassir's Sew Fashion & Fabrics — Digital Marketing & CRM Capstone

Cc-HUB Gateway Program: Digital Marketing Track capstone project.

## Overview

Mum Muyassir's Sew Fashion & Fabrics is a Nigerian fashion and fabrics SME selling through
WhatsApp, Instagram and Facebook. Before this project, customer enquiries were
scattered across channels with no central record, follow-up depended on memory,
and there was no way to tell a new enquirer from a returning customer.

This project builds a working digital CRM and automation system to fix that —
while keeping WhatsApp and social media as the business's real customer-facing
channels. The system works behind them, not instead of them.

## What's in this repo

| Path | Contents |
|---|---|
| `docs/capstone-report.pdf` | Full project report — business overview, system architecture, results, limitations |
| `docs/demo-video-script.pdf` | Script used to record the demo video |
| `automation/make-blueprint.json` | Exported Make.com scenario — the lead capture and returning-customer automation |
| `assets/` | Dashboard and system screenshots |

## Live links

- **Demo video:** [Mum Muyassir's Sew Fashion & Fabrics](https://youtu.be/KPrgDLXMrx4?si=QnSQ5xCGKS9enMGc)
- **CRM workbook (view-only):** [MUM MUYASSIR'S SEW Fashion & Fabrics CRM](https://docs.google.com/spreadsheets/d/10iu7iWy6hfZcIcz2BfT25TfCTHcCVumQ_X11FGebeXE/edit?usp=drivesdk)
- **Lead capture form:** [Customer Enquiry Form ](https://docs.google.com/forms/d/e/1FAIpQLScd1RGHyLVsdZTJdMz41KEYr1GIklxJo10UHQhiB9aWie5J3Q/viewform?usp=sharing&ouid=108672187969354715425)

## System summary

A 7-sheet Google Sheets CRM (Leads, Customers, Interactions, Products, Orders,
Campaigns, Dashboard), connected by auto-generated IDs, fed by a Google
Form → Make.com automation that:

1. Logs every enquiry as a Lead
2. Matches the enquirer against existing customers **by phone number**
3. Creates a new Customer record, or marks an existing one "Returning"
4. Links the resulting Interaction to the correct Customer ID
5. Feeds a live Dashboard — 12 KPIs computed directly from the data, not typed in

See `docs/capstone-report.pdf` for the full writeup, including known
limitations and what was deliberately left as a labeled example (campaign-level
attribution) versus fully computed.

## Tech stack

Google Sheets · Google Forms · Make.com
