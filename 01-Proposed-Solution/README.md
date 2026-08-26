# AASRA – Proposed Solution

This folder contains the detailed proposed solution of the AASRA project.
# Problem statement
Design a solution that goes beyond disaster alerting and provides real-time, actionable relocation support to flood-affected citizens — helping them find the nearest available shelter (with live occupancy data),
locate food/essential-aid points, and navigate a safe route to reach them, while remaining functional even under low or no network conditions.

# The real problem
During floods and other disaster events, India's existing systems like SACHET (Common Alerting Protocol-based alert dissemination) are effective
at warning citizens about an incoming hazard, but they stop there. Once a flood hits, affected people face a much harder second problem: where do I go, is it safe to get there, and will there be space and food when I arrive? Existing alert systems don't answer this.
People often travel toward the nearest known shelter only to find it full, poorly stocked, or unreachable because the route is waterlogged or blocked. 
In low-connectivity conditions — common during disasters when towers go down or networks get congested — even the alert itself may not reach everyone reliably.

# Core Idea

"A flood relief navigation and shelter occupancy platform that helps affected people 
find the nearest available shelter, food point, and safe route in real time, even during low-network 
conditions."


# Why This Matters
Alert-only systems create awareness but leave people to figure out logistics themselves during the most chaotic moments of a disaster.
Shelters can reach capacity quickly; without occupancy visibility, people waste critical time traveling to a full shelter.
Roads become hazardous during floods (waterlogging, fallen trees, live electrical risk) — generic navigation apps don't account for this.
Rural and heavily affected areas often lose data connectivity first, exactly when people need guidance most.

## Target Users
Flood-affected residents (individuals and families, including elderly, children, women, and persons with disabilities)
Shelter/relief camp administrators and ward officers
Volunteers assisting with on-ground verification
Disaster management authorities coordinating relief.

# Proposed Solution: Aasra
Aasra (meaning "shelter/support" in Hindi) is a mobile application prototype that acts as a decision-support layer on top of disaster alerts — helping people act on a warning,
not just receive it.

# What Makes Aasra Different
Existing Systems (e.g. SACHET)	Aasra
Sends alerts	Provides actionable relocation support
No shelter data	Live shelter occupancy tracking
No route guidance	Safe-route navigation avoiding hazards
Assumes network availability	SMS fallback for no-network conditions

This shifts the app's role from "awareness" to "decision support during displacement" — the gap current systems leave open.

## Key Features (Novelty / Wow Factor)
Shelter Occupancy Meter — green/orange/red status based on remaining capacity, updated live.
Food & Essentials Layer — shows nearby community kitchens, relief camps, medical aid, and water points.
Safe-Route Navigation — routes around waterlogged roads, blocked streets, fallen trees, and electrical-risk zones.
Family Mode — tailors shelter suggestions based on group composition (elderly, children, women, disabled members).
SMS Fallback — sends/receives shelter info via SMS when data connectivity fails, aligned with India's geo-targeted disaster messaging approach.
Admin Live Update Panel — shelter managers update bed count, food stock, and status in real time.
Crowd Verification — volunteers/ward officers confirm shelter status (open/full/out of supplies) for accuracy.
Priority Recommendation Engine — recommends the best shelter (not just nearest) factoring in capacity, distance, family needs, and route safety.

## How It Works
Official flood/storm alert is issued.
User opens Aasra or receives an SMS alert.
App fetches the user's current location.
It queries nearby shelters and food points from the live database.
Full or inaccessible shelters are filtered out.
The app displays the best route to the nearest available shelter.
If there's no internet, the user receives an SMS with the top nearby shelters, their occupancy status, and a helpline number-.

## CONCLUSION:
"Unlike alert-only systems, Aasra answers the next critical question during floods: where is the nearest safe shelter with actual space and food, and how do I reach it safely — right now?"
