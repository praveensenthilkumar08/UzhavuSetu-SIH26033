UzhavuSetu: Pre-Order Based Farm-to-Institution Vegetable Marketplace

SIH Problem Statement: SIH 26033, Multiple intermediaries reduce farmers' earnings and increase consumer prices

Organization: Ministry of Consumer Affairs, Food & Public Distribution
Theme: Agriculture, FoodTech & Rural Development


Author: Praveen S 

Reference No.: 26000307

Date: 24 November 2026

1. Problem

Many intermediaries (commission agents, wholesalers, transporters, retailers) sit between farmers and consumers. Farmers get a small share of the final price, consumers pay more, and produce is lost to poor logistics and unplanned supply.

2. Proposed Solution

UzhavuSetu ("Uzhavu" means farming in Tamil) connects FPOs and small vegetable farmers around Chennai directly with hostels, college canteens, hotels and apartment communities. It follows a "sell before you harvest" model: buyers pre-order, orders are pooled, and farmers harvest only what is already sold.

Key Features
Demand-locked harvest: pre-orders and weekly subscriptions placed 2 to 3 days before harvest
Tamil voice-first app and WhatsApp bot: listing and accepting orders by speaking in Tamil
AI Price Advisor: fair price band from Agmarknet/e-NAM prices, weather and local demand
AI demand forecasting: learns each buyer's weekly pattern and guides FPO planning
Hub-based pooled logistics: existing FPO centres, cooperatives and Uzhavar Sandhai act as hubs; route optimization pools pickups into one delivery run
Rupee Trail bill: shows farmer share, transport cost, platform fee and buyer price on every order
UPI escrow payment: released to the farmer after delivery confirmation (target 24 to 48 hours)
AI quality grading: photo-based grading of size, colour and visible defects
How It Addresses the Problem
Problem	UzhavuSetu solution
Many intermediaries add margins	Direct farmer-to-buyer ordering with a small, visible platform fee
Farmers don't know fair prices	AI Price Advisor using live mandi data
Unsold produce and price crashes	Pre-orders and demand forecasting match supply to demand
High transport cost and spoilage	Pooled pickups, local hubs, optimized routes
Inflated consumer prices	Fewer layers, lower final price, fresher produce
Delayed payments	Escrow with fast release after delivery
Innovation and Uniqueness
Sell-before-harvest model that guarantees demand instead of only listing produce
Rupee Trail bill that makes margins visible
Reuses existing hubs instead of building new infrastructure
Tamil voice-first design for low digital literacy
Focus on institutional buyers with regular, predictable demand
Works alongside e-NAM and Agmarknet by using their data
3. System Flow Chart

System Flow Chart

<img width="967" height="2858" alt="image" src="https://github.com/user-attachments/assets/e9b557f5-1883-4580-8355-6688aaab81f1" />

4. System Architecture

<img width="2422" height="1290" alt="image" src="https://github.com/user-attachments/assets/e3bc61a7-443f-4f7e-9ce4-dc6e22c30cd9" />


5. Tech Stack
Layer	Technology
Frontend	React Native (mobile), React (web), WhatsApp Business bot
Backend	Python (FastAPI), PostgreSQL, Redis
AI/ML	XGBoost/LSTM (price and demand), CNN MobileNet (grading), Bhashini APIs (Tamil speech and translation)
Data sources	Agmarknet/e-NAM, IMD weather
Logistics	Google OR-Tools, Google Maps API, GPS tracking
Payments	UPI with escrow-style hold and release
Traceability (optional)	QR code per batch showing farm, harvest date and delivery
Cloud	AWS/Azure/GCP with offline-first caching
6. Implementation Plan
Phase	Timeline	Activities
1	Months 1 to 2	Interviews with farmers, FPOs and hostel/canteen managers; UI/UX design
2	Months 3 to 4	Core app: pre-orders, listing, escrow payment, Rupee Trail bill
3	Months 5 to 6	AI price advisor, demand forecasting, quality grading, route pooling
4	Months 7 to 8	Pilot with 1 FPO and 2 to 3 vegetables (tomato, brinjal, lady's finger) serving Chennai hostels/canteens
5	After pilot	Measure results, refine, extend to more crops and districts
7. Feasibility and Viability
Technical: proven tools and open government data (Agmarknet, e-NAM, IMD, Bhashini)
Operational: starts with one FPO, a few crops and a few institutional buyers in one city
Economic: small transaction fee (target about 3%, to be validated in the pilot), margin on pooled delivery, institutional subscriptions
Policy fit: Digital India, e-NAM, FPO scheme, Agri-Stack
Challenges and Strategies
Challenge	Strategy
Low digital literacy	Tamil voice interface, WhatsApp bot, village "Kisan Mitra" helpers
Trust in a new platform	Escrow payments, ratings, working through trusted FPOs
Spoilage	Short harvest-to-delivery window, nearby hubs, pooled routes
Poor connectivity	Offline-first app with SMS/IVR fallback
Buyer adoption	Weekly subscriptions, consistent quality, clear price bill
Middleman resistance	Offer roles as hub operators and delivery partners
8. Impact and Benefits
Farmers/FPOs: larger share of final price, assured demand before harvest, faster payment
Institutional buyers and consumers: fresher vegetables, lower prices, steady supply, clear pricing
Rural communities: new work as hub operators, graders and delivery partners
Social: fair market access with a voice in their own language
Economic: better farmer income, lower buyer cost, fewer supply chain inefficiencies
Environmental: less postharvest waste and fewer transport trips

Pilot success metrics: farmer price per kg vs mandi price, buyer cost vs retail, spoilage percentage, payment settlement time, repeat buyers.

9. References
Agmarknet: https://agmarknet.gov.in
e-NAM: https://enam.gov.in
Bhashini: https://bhashini.gov.in
India Meteorological Department: https://mausam.imd.gov.in
Google OR-Tools: https://developers.google.com/optimization
Ministry of Agriculture & Farmers Welfare and NITI Aayog publications on agricultural marketing reforms
