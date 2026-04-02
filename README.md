# Match-Analysis-Croatia-vs-Brazil-International-Friendly-Shot-Efficiency-Tactical-Insights
# Objective

To analyze and compare the attacking performance of Croatia and Brazil using shot data, with a focus on shot quality, efficiency, and tactical shot patterns.

This project answers a key question:

How can two teams with similar shot volume produce drastically different outcomes?

# Data Used

The dataset includes:

Shot outcomes (goal, save, block, miss)
Shot coordinates (x, y)
Distance to goal
Shot situations (assisted, fast-break, set-piece, penalty)
Player-level shot contributions
# Tools & Technologies
Python
Pandas (data manipulation)
NumPy (calculations)
Matplotlib (visualization)
mplsoccer (football pitch plotting)
# Key Findings
1️⃣ Shooting Efficiency Was the Deciding Factor
Brazil: 13 shots → 7 on target (53.85% accuracy)
Croatia: 12 shots → 3 on target (25.00% accuracy)

📌 Despite similar shot volume, Brazil produced more than double the shooting accuracy.

2️⃣ Chance Quality Was Similar — Execution Was Not
Brazil avg shot distance: 19.8m
Croatia avg shot distance: 20.8m

👉 Both teams created chances from similar ranges, but:

Brazil: 3 goals (23% conversion)
Croatia: 1 goal (8% conversion)

📌 This highlights the importance of finishing quality over chance quantity.

3️⃣ Brazil Focused on Central High-Value Zones
Majority of Brazil’s shots came from central areas (x ≈ 10–18)
Goals originated from:
Fast-break transitions
Central attacking positions
Penalty situations

📌 Brazil consistently accessed high-probability scoring zones.

4️⃣ Croatia Lacked Central Penetration
Shots were more widely distributed
Higher number of:
Missed shots (5)
Blocked attempts (4)

# Indicates:

Lower shot quality
Defensive pressure at the moment of shooting
5️⃣ Game Context Favoured Brazil’s Chance Creation
Brazil scored from:
Fast breaks
Structured attacking plays
A penalty
Croatia:
Relied mainly on assisted build-up
Generated no high-impact transition chances

Brazil created higher-leverage scoring situations.

📈 Visuals
Shot Map Insights:
Brazil:
Clustered shots in central zones
Higher proportion of on-target attempts
Croatia:
More dispersed shot locations
Lower shot efficiency

(Include your mplsoccer shot maps here — home vs away or separate visuals)

# Tactical Implications
# 🇧🇷 Brazil

Strengths:

Efficient shot selection
Strong central penetration
Effective use of transitions

Areas to Improve:

Reduce blocked shots (predictable shooting lanes)
Add more width to diversify attack
# 🇭🇷 Croatia

Weaknesses:

Low shooting accuracy (25%)
Poor shot selection under pressure
Limited central attacking presence

Recommendations:

Improve shot selection (reduce low-probability attempts)
Increase central overloads and combination play
Create more transition opportunities
Enhance decision-making in the final third
# Conclusion

Brazil’s victory was driven not by shot volume, but by superior shot efficiency, central penetration, and high-quality chance creation.

Similar shots: 13 vs 12
Similar distances: ~20m
But:
Accuracy: 53.85% vs 25%
Goals: 3 vs 1

👉 The key difference was how and where the shots were taken.

# Project Value

This project demonstrates:

Ability to translate raw data into tactical football insights
Strong use of data visualization (mplsoccer)
Understanding of performance analysis in football
🔗 Next Steps / Improvements
Integrate Expected Goals (xG) model
Add pass sequences leading to shots
Build an interactive Streamlit dashboard
Compare multiple matches for pattern recognition
# Author Note

This project is part of my journey into football data analytics, combining Python, visualization, and tactical understanding to uncover insights beyond the scoreline.
