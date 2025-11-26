# Anagha Venugopal

**Mobility Analyst · Transport Planner · Traffic Engineer**


---

## 👋 About

I’m trained in transportation systems with experience across:

- **Shared mobility & MaaS** – analysing bikeshare, e-scooter and car-sharing data, and their integration with public transport nodes and networks.  
- **Transport planning & traffic engineering** – corridor and network design, signal optimisation, macro-/micro-simulation and multi-modal evaluation.  
- **Human-centred & equity-focused mobility** – accessibility for elderly users, gender-responsive planning, and inclusive service design.  

I’m currently looking for roles as a **Mobility Analyst**, **Transport Planner** or **Traffic/Transport Engineer**, where I can support data-driven planning, modelling and evaluation of sustainable mobility solutions.

---

## 🧰 Skills

### Technical

- Python (pandas, NumPy, matplotlib, geopandas)  
- R (mlogit, regression, factor analysis)  
- GIS: QGIS / ArcGIS – spatial joins, buffers, service areas, isochrones  
- Macro- and microscopic traffic modelling tools (intersection and corridor analysis)  
- Git & GitHub, Markdown, LaTeX  

### Transport Planning & Analysis

- Demand analysis and OD-based planning  
- Shared mobility & first/last-mile integration with PT  
- Public transport network design and performance assessment  
- Intersection analysis, LOS assessment and signal timing concepts  
- Accessibility analysis for specific user groups (elderly, women, PWD)  

### Methods

- Discrete choice modelling (MNL, nested logit, ordered logit)  
- Regression (OLS, lasso), PCA and factor analysis  
- Mixed-integer linear programming (MILP)  
- Heuristics & metaheuristics (e.g. TSP with nearest neighbour and simulated annealing)  
- Indicator design and multi-criteria decision analysis  

### Soft Skills

- Writing clear, structured reports and technical documentation  
- Presenting findings to technical and non-technical audiences  
- Working in interdisciplinary and international teams  
- Organising work under time constraints and coordinating with partners  

---

## 🏗️ Selected Projects

### 1. Shared Mobility at Mobility Points in Munich (Master’s Thesis)

**Keywords:** shared mobility, micromobility, regression, geospatial analysis, PT integration  

Munich plans to roll out around 200 **mobility points (MPs)** that cluster bikeshare, e-scooters and car-sharing at key PT locations. My thesis investigates:

- How **usage patterns** of shared mobility change in the vicinity of these MPs.  
- Which **built-environment and network factors** best explain high or low usage.  

#### What I did

- Collected and processed nearly **two years of operator data** (bikeshare, e-scooters, car-sharing) with 3-minute scraping intervals.  
- Joined this with:
  - A **100×100 m population grid**.  
  - PT accessibility (stops, departures).  
  - Land-use proxies via POIs (commercial, health, education, leisure, residential).  
  - **Cycling infrastructure** (bike lane lengths).  
  - **Weather** data (seasonality, temperature, precipitation).  
- Performed **exploratory data analysis**:
  - Time-of-day and day-of-week profiles around MPs vs non-MP areas.  
  - Spatial clustering of trip starts/ends around mobility points.  
  - Pre-/post-introduction comparisons for selected MPs.  
- Built **panel datasets** (grid × month × mode) and estimated:
  - Stepwise OLS models to identify significant predictors.  
  - **Lasso regression** to handle multicollinearity and variable selection.  

#### Key insights

- Stronger **temporal peaks** at MPs aligned with commuter hours, supporting their role in first/last-mile PT access.  
- Micromobility is particularly sensitive to **PT accessibility, commercial land use and bike infrastructure**, whereas car-sharing usage is more diffuse and less tightly linked to MPs.  
- The introduction of MPs leads to a **gradual** ramp-up in usage influenced by awareness, season and fleet allocation, rather than an instant jump.  



---

### 2. Integrated Transport Planning for Göttingen

**Keywords:** urban road network, ring roads, signal control, PT network design  

This project develops an integrated strategy to improve **private and public transport** in the German city of Göttingen, where heavy through-traffic and a complex bus network cause delays and confusion.

#### What I did

- Built and analysed a **macroscopic model** of the road network:
  - Tested two alternative **ring-road concepts** (inner vs outer ring) to divert through-traffic from the historic centre.  
  - Evaluated link V/C ratios, flows and travel times under each concept.  
- Carried out a **microscopic analysis** of a key intersection:
  - Defined signal groups and phases for different concepts.  
  - Evaluated **queues, delays, emission proxies and LOS** under different cycle times.  
- Contributed to **public transport network redesign**:
  - Simplified the line structure to be more legible while aligning with main OD flows.  
  - Analysed implications for vehicle-kilometres, travel times, transfers and coverage.  

#### Key insights

- The **outer ring concept** achieved better utilisation (higher V/C ratios on ring links) while reducing volumes and conflicts in the city centre.  
- A more efficient signal plan with a shorter cycle time reduced **average delay and queue lengths** without over-saturating approaches.  
- A cleaner, simplified PT network supports the traffic-calming strategy by making PT more competitive and easier to understand.  



---

### 3. Discrete Choice Methods – UAM Airport Shuttle & Car-Sharing Tariffs

**Keywords:** discrete choice modelling, SP survey, multinomial & nested logit, factor analysis  

This work focuses on **behavioural modelling** and experimental design in two contexts: UAM for airport access, and user preferences for car-sharing tariffs.

#### Part A: UAM as an Airport Shuttle

- Designed a **stated-preference (SP) survey** where travellers choose among:
  - Private car  
  - On-demand car service (ride-hailing)  
  - Public transport  
  - Urban Air Mobility (UAM)  
  - “None” alternative  
- Defined attributes such as **in-vehicle time, cost, reliability and waiting time**, with levels based on existing options and realistic UAM assumptions.  
- Cleaned and explored the data, then estimated **multinomial logit models** to:
  - Derive **value-of-time** estimates.  
  - Understand how reliability and waiting time affect UAM attractiveness.  
  - Explore sensitivity across different traveller segments.  

#### Part B: Car-Sharing Payment Schemes

- Analysed survey data on preferences for **different car-sharing tariff structures**.  
- Used **factor analysis / PCA** to reduce many behavioural indicators into latent factors (e.g. cost sensitivity, tech affinity).  
- Estimated:
  - **Multinomial and nested logit** models to account for similarities between response categories.  
  - **Ordered logit** models where the responses were inherently ordered (e.g. “definitely not” to “definitely yes”).  

#### Key insights

- UAM’s competitiveness depends heavily on **reliability and access time**, not just cruise speed.  
- Tariff preferences differ across user segments; some value **simplicity and predictability**, others prefer flexible pay-per-use structures.  



---

### 4. Accessibility to Recreational Green Spaces for the Elderly

**Keywords:** accessibility, elderly, GIS, equity, open space planning  

This project compares how well **elderly residents** in Stuttgart and Hannover can access recreational and green spaces, accounting for different modes and travel times.

#### What I did

- Defined the **target user group** (65+) and relevant accessibility conditions (reasonable walk distances, comfortable gradients, PT access).  
- Used GIS tools to compute:
  - **Walking catchments** around recreational and green spaces (e.g. 15-minute walk).  
  - **PT + walking catchments** (e.g. 30-minute combined journey).  
- Calculated indicators at neighbourhood/grid level:
  - Share of elderly residents within each catchment.  
  - Ratios of accessible to total area/population.  
  - A **composite z-score index** combining multiple indicators into an overall accessibility score.  
- Mapped spatial patterns to highlight **inequalities** and potential areas for intervention.  

#### Key insights

- Both cities have substantial green areas, but distribution and topography create **local disparities**.  
- Some dense neighbourhoods with many elderly residents fall just outside reasonable catchments, suggesting **targeted improvements** (e.g. micro-parks, better paths, PT stops).  
- Demonstrated how simple, transparent indicators can support more **equitable recreational planning**.  


---

### 5. Optimisation for Transportation Systems – Problem Sets

**Keywords:** MILP, TSP, regression, algorithms, performance analysis  

These assignments demonstrate my ability to translate transport problems into **formal optimisation models and algorithms**, and to critically evaluate their performance.

#### Highlights

- **Mixed-Integer Linear Programming (MILP):**  
  - Modelled a **bicycle production planning problem** with multiple product types (A–H), constrained by working hours, raw materials and budget.  
  - Introduced **binary decision variables** to decide whether a product is produced at all, enabling logical constraints (e.g. at most N types, dependencies between products, conditional discounts).  
- **Travelling Salesman Problem (TSP):**  
  - Implemented a **nearest neighbour heuristic** in Python, tested up to 5 000 nodes, and profiled runtimes.  
  - Used a **simulated annealing** approach (2-opt moves, cooling schedule) via `python_tsp` to improve solutions and studied the trade-off between runtime limits and solution quality.  
- **Data fitting for the fundamental diagram:**  
  - Fitted **linear and quadratic models** of flow vs occupancy.  
  - Compared MSE, MAE, RMSE and R², showing why a quadratic form better captures critical density and capacity.  

#### Key insights

- Showed how small modelling choices (binary vs continuous variables, heuristic vs metaheuristic) impact both **solution quality and runtime**.  
- Built intuition for **non-linear relationships** in traffic flow and how to fit them robustly.  


---

### 6. Gender-Responsive Public Transport & Public Spaces in India

**Keywords:** gender, mobility gaps, safety, policy, equity  

This seminar project explores why women in Indian cities travel significantly **less** than men and what that implies for transport planning.

#### What I did

- Reviewed **time-use and mobility studies** showing that many women record **no trips** on survey days, in contrast to men.  
- Synthesised literature and case examples on:
  - Safety and harassment in PT and public spaces.  
  - The “**pink tax**” where women pay more for safer modes.  
  - Interactions between transport, labour-force participation and gender norms.  
- Translated findings into a framework for **gender-responsive mobility**, including:
  - Data collection (sex-disaggregated and time-of-day-sensitive).  
  - Design of vehicles, stations and public spaces (lighting, visibility, escape options).  
  - Operational measures (staffing, reporting channels, service patterns).  

#### Key insights

- Many women’s mobility choices are **constrained**, not just “different preferences”.  
- Policy responses must go beyond a few women-only coaches to a **systemic rethinking** of infrastructure, operations and safety culture.  



---

### 7. Future Mobility Concepts – Ottobahn & Urban Air Mobility in Würmtal

**Keywords:** innovative modes, indicators, multi-criteria evaluation, sustainability  

#### Ottobahn in Würmtal

**Concept:** an elevated autonomous cabin system with small vehicles on a track above the ground, offering on-demand, point-to-point trips.

##### What we did

- Defined indicators for **three modes** – Ottobahn, S-Bahn and car – along three dimensions:
  - **Quality of space:** land take, safety, user acceptance.  
  - **Quality of time:** waiting times, in-vehicle times, door-to-door considerations.  
  - **Quality of air/noise:** energy use, CO₂ emissions, noise levels.  
- Calculated and compared indicator values along a **tangential corridor** (Germering–Stockdorf).  

##### Key insights

- Ottobahn can **reduce CO₂ and land consumption** while offering competitive travel times, but requires careful integration with existing PT and local context.  



---
#### 8. Urban Air Mobility (UAM) in Würmtal

**Concept:** electric vertical-takeoff aircraft providing fast connections between Pasing, Gauting, Starnberg and surrounding areas.

##### What we did

- Modelled **door-to-door travel times** (start-up, hover, climb, cruise, descent) and compared them to car/PT.  
- Built indicators for:
  - **Inconvenience time** (access, egress, waiting).  
  - **Land consumption and cost per daily user** (vertihubs vs road space).  
  - **Noise and visual exposure** along corridors.  
  - **Life-cycle GHG emissions** per passenger and passenger-km.  
- Performed a **multi-criteria assessment** to compare UAM to the status quo.  

##### Key insights

- While UAM reduces line-haul time, its overall performance is often **worse than the road-based baseline** once emissions, costs and inconvenience are fully accounted for.  
- Highlights how important it is to use a **holistic indicator set** when evaluating new mobility modes.  



---

### 9. euMOVE 2024 – Commuting from Suburban Areas (Genoa, Italy)

**Keywords:** MaaS, on-demand services, accessibility, user research, qualitative methods  

As part of **euMOVE 2024**, I joined a team exploring commuting from suburban to urban areas in Genoa and Turin, focusing on **MaaS and on-demand services**.

#### What we did

- Developed **personas** representing different mobility needs (e.g. pregnant woman, older man with limited mobility, blind traveller) to keep accessibility central.  
- Conducted:
  - **Interviews** with NGOs, authorities, operators and users.  
  - An **online survey** on transport use and perceived service quality.  
  - **Think-aloud sessions** where participants booked trips using on-demand and shared mobility apps.  
- Documented **barriers and opportunities** in integrating on-demand services with existing PT, especially for vulnerable users.  
- Helped translate findings into **concepts for more accessible services** that could inspire improvements in other cities (including Munich).  

#### Key insights

- Technical solutions (apps, platforms) alone are insufficient; **inclusive design, information and physical accessibility** remain crucial for real-world adoption.  
- User research methods like personas and think-aloud protocols are powerful complements to purely quantitative analysis.  


---

## 🎓 Education & Interests

**Education**  

- M.Sc. in Transportation Systems – Technical University of Munich, Germany  
- B.Tech. in Civil Engineering – University of Kerala, India

---

## 📬 Contact

- **Email:** [anaghav1219@gmail.com]  
- **LinkedIn:** [https://www.linkedin.com/in/anagha-venugopal-28b124142/]

I’m happy to connect about opportunities in **mobility analytics, transport planning or traffic/transport engineering**, or to collaborate on data-driven mobility projects.
