🚦 Roundabout Traffic Simulation with SUMO
This project models and analyzes vehicle traffic flow through a multi-entry roundabout using SUMO (Simulation of Urban Mobility). It integrates real-world traffic data, simulates vehicle behavior, and explores optimization strategies for urban traffic management.

📁 Project Structure
|  |  | 
| roundabout1.net.xml |  | 
| roundabout_update.rou.xml |  | 
| roundabout.sumocfg |  | 
| tripinfo.xml |  | 
| summary.xml |  | 



✅ Completed Tasks
- Vehicle Data Integration
Updated the route file with accurate vehicle counts from Excel for the 7:00–7:15 PM interval.
- Simulation Configuration
Configured SUMO to output tripinfo.xml and summary.xml for traffic analysis.
- Simulation Execution
Successfully ran the simulation in SUMO-GUI, confirming correct vehicle behavior and flow.

📊 Analysis Outputs
- tripinfo.xml: Includes trip duration, delay, speed, and departure/arrival times for each vehicle.
- summary.xml: Provides aggregate statistics such as total vehicles, average speed, and simulation time.
