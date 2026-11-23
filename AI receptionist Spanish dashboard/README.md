# AI Receptionist Spanish Dashboard

Multi-business AI receptionist onboarding and configuration prototype.

## Goal

One reusable AI voice agent, with isolated configurations per business. Supports dental clinics, salons, barbershops, auto repair, restaurants, medical, legal, real estate, home services, and other businesses.

## Files

- `business-onboarding.html`: browser-based editable onboarding dashboard with local JSON export (no server required).
- `example-business.json`: VVS Smilez demo example.

## Safety and scope

This is a configuration prototype, not an integrated production dashboard. It does not change the running LiveKit agent or persist settings to a server. Demo appointments are not real bookings. For production, validate all clinic facts, pricing, permissions, customer data, and industry-specific workflows.

Open `business-onboarding.html` in Chrome or Edge. Fill in the fields and select **Download JSON**. Importing configurations into LiveKit is a later integration step.
