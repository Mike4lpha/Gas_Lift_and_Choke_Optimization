# Gas_Lift_and_Choke_Optimization

The Gas Lift & Choke Optimization project successfully integrates petroleum engineering principles with modern machine learning techniques to solve a high-value production challenge. By combining well site data with ensemble ML models such as Decision Tree, Random Forest and XGBoost, the system can accurately predict oil production and determine optimal operating parameters for gas lift and choke settings. The approach demonstrates significant potential for boosting production efficiency, reducing manual intervention, and supporting data-driven decision-making in the field.

The project’s emphasis on reproducible workflows make it suitable for both academic teaching and industrial adaptation. Its framework’s flexibility allows for future integration of real-time SCADA data and advanced AI methods such as reinforcement learning. Ultimately, this work showcases how physics-aware ML can enhance operational performance, maximize economic returns, and prepare engineers for the evolving digital oilfield.

#### Part A: Gas Lift Systems
Purpose: Gas injection reduces hydrostatic pressure, allowing reservoir pressure to push fluids to surface

Key Variables:
* Gas injection rate (too little = insufficient lift, too much = waste + instability)
* Wellhead pressure (back-pressure on system)
* Reservoir pressure (driving force)
* Water cut (affects fluid density)
* Well depth (affects hydrostatic head)
   
Optimization: Increasing gas injection, does not always increase oil production. There is an optimal point. Too much gas creates turbulence and can actually reduce flow.

#### Part B: Choke Flow
Purpose: Chokes are production control devices. They can increase or decrease the flow rate and wellhead pressure by changing the orifice diameter.

Key Concepts:
* Critical Flow: When pressure drop is high enough, flow becomes sonic.
* Choke Size: Measured in 64ths of an inch.

Key Variables:

* Upstream/downstream pressure (driving force)
* Fluid properties (density, viscosity)
* Gas-liquid ratio (affects flow patterns)
* Optimization: In the field, engineers often adjust chokes based on intuition. We can use data and ML to find the optimal point and do better.
