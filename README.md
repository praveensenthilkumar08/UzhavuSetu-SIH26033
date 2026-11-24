# UzhavuSetu-SIH26033
Pre-order based farm-to-institution vegetable marketplace for Tamil Nadu with AI pricing, demand forecasting and pooled logistics (SIH 26033)
# UzhavuSetu: Pre-Order Based Farm-to-Institution Vegetable Marketplace

[README.md](https://github.com/user-attachments/files/35357901/README.md)

# UzhavuSetu: Pre-Order Based Farm-to-Institution Vegetable Marketplace

**SIH Problem Statement:** SIH 26033, Multiple intermediaries reduce farmers' earnings and increase consumer prices
**Organization:** Ministry of Consumer Affairs, Food & Public Distribution
**Theme:** Agriculture, FoodTech & Rural Development
**Author:** Praveen S (Ref. No. 26000307)
**Date:** 24 November 2026

## Idea
UzhavuSetu connects FPOs and small vegetable farmers in Tamil Nadu directly with hostels, canteens, hotels and apartment communities through a "sell before you harvest" model. Buyers pre-order, and farmers harvest only what is already sold.

## Key Features
- Pre-orders and weekly subscriptions (demand-locked harvest)
- Tamil voice-first app and WhatsApp bot
- AI Price Advisor using Agmarknet/e-NAM data
- AI demand forecasting
- Hub-based pooled logistics with route optimization
- Rupee Trail bill showing where every rupee goes
- UPI escrow payments
- AI photo-based quality grading

## Tech Stack
React Native, React, Python (FastAPI), PostgreSQL, Redis, XGBoost/LSTM, CNN (MobileNet), Bhashini APIs, Google OR-Tools, UPI

## System Flow
Buyer pre-order -> Orders pooled -> AI price and demand forecast -> Farmer accepts by voice -> AI quality grade -> Pooled pickup and delivery -> Buyer confirms -> Escrow released -> Rupee Trail bill

## Implementation Plan
1. Months 1-2: Research and design
2. Months 3-4: Core app and payments
3. Months 5-6: AI models and route optimization
4. Months 7-8: Pilot with 1 FPO and Chennai institutional buyers
5. After pilot: Refine and scale

## References
- Agmarknet: https://agmarknet.gov.in
- e-NAM: https://enam.gov.in
- Bhashini: https://bhashini.gov.in
- IMD: https://mausam.imd.gov.in
- Google OR-Tools: https://developers.google.com/optimization
