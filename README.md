# 🌱 Green-Sync
Say goodbye to those annoying "Where are you?" texts! Our synchronized event coordination app is designed to perfectly time group arrivals while guiding users into cost-effective, eco-friendly carpools.

# 🚨 The Problem: "The Coordination Tax"
Urban group commutes face two big challenges:

Time Friction: When arrival times are all over the place, it leads to waiting around, endless texting, and plans that just don’t come together.

Economic & Ecological Waste: Often, multiple people heading in the same direction to the same place end up taking separate cabs or cars, wasting money and increasing carbon emissions.

# 💡 The Solution
Green-Sync is your smart arrival hub. Rather than just figuring out solo ETAs, it serves as a central routing engine for the whole group. By looking at everyone’s starting points and modes of transport at once, it sends out synchronized departure alerts and suggests "Eco-Match" route interceptions.

# ✨ Key Features
Synchronized Departure Hub: Users can join an event room where the engine calculates individual ETAs and gives personalized "Leave Now" countdowns, ensuring everyone arrives right on time.

Smart Interception (Eco-Match): The algorithm identifies when a solo rider’s starting point overlaps with a driver’s route, instantly proposing a carpool detour and calculating the extra time versus the money and emissions saved.

Heuristic Fare Engine: Automatically figures out and ranks the cheapest transit options (Metro, Cab, Bus) for users who can’t carpool.

Live Social Dashboard: A real-time map shows all participants in motion, their individual ETAs, and a live tally of the group’s total financial and carbon savings.

# 🛠️ Tech Stack
Frontend: React Native
Backend: Python / FastAPI
APIs & Data: Google Maps Directions & Distance Matrix APIs

Real-Time Sync: Polling / WebSockets for live location and status updates

# 🌍 The Impact
Green-Sync turns solo travel into a collaborative experience. It helps cut down the number of vehicles on the road during peak hours, significantly reducing traffic and emissions.
