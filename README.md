# Buddy Electrical Plant Simulation

This project involves the analysis and simulation of the current and proposed layouts for the manufacturing plant of **Buddy Electrical**. The aim is to evaluate production efficiency and costs for an 8-hour shift, comparing the performance of the current plant layout with the newly proposed automated layout.

## Overview

The current layout was analyzed to determine production rates, resource utilization, and associated costs. Based on this analysis, a new automated layout was proposed, incorporating advanced resource management strategies and automation technologies. Using **ExtendSim**, the new layout was simulated to quantify its impact on the number of cars produced and the overall cost efficiency.

### Current Layout Structure

The **Buddy Electric manufacturing plant layout** consists of **nine principal stations**, which are:

1. Suspensions  
2. Dashboard  
3. Elbox  
4. Batteries  
5. Body Work  
6. Interior 1  
7. Interior 2  
8. Doors  
9. Testing  

#### Simulation Process
- The proposed layout was simulated using **ExtendSim** to determined the produced cars and production costs.
- The simulation begins with the input of materials (e.g., the vehicle chassis). 
- The workflow proceeds through several operations, including queue processes (buffers) for each station. 
- Each station has its own **operation time** and **cost** associated with the manufacturing or assembly process.

### Proposed Layout Structure
The **proposed manufacturing plant layout** adopts a **cellular layout**, where specific processes are carried out at designated stations or areas, but following a continuous workflow. The layout consists of four main stations, categorized and numbered as follows:

1. **Chassis, Suspension, Steering, and Brakes**
2. **Dashboard, Electrical Box, Batteries**
3. **Interior 1 & 2**
4. **Bodywork, Doors, Exteriors**

#### Simulation Process
The proposed layout was simulated using **ExtendSim** to model the continuous workflow between the main stations.
1. **Four Main Stations**:
   - Each station is modeled as a **hierarchical block** representing its entire process.
   - Each block includes a **buffer** to manage resource allocation and ensure smooth flow between stations.
2. **Resource Allocation**:
   - Buffers request resources (two operators and one AGV) to proceed with processing.
   - Resources are dynamically assigned based on availability.
3. **Transportation Simulation**:
   - Before entering a station, cars are transported by an AGV using a process block.
4. **Synchronization**:
   - A car proceeds to the next station only when the required resources are available and the next station is free.

#### Simulation Process
- The proposed layout was simulated using **ExtendSim** to model the continuous workflow between the main stations.
- Each station operates with an automated system that optimizes resource usage (e.g., two operators and one AGV).
- Buffers are used to manage the flow of materials between stations, ensuring that each station only processes the car when the required resources are available.

#### Key Features of the Proposed Layout
- **Cellular structure** for more efficient flow.
- **Automated transportation** and resource allocation.
- Improved **synchronization** between processes to reduce idle time and bottlenecks.
- **Continuous production** with minimal downtime between stations.

### Simulation Objectives

1. **Cost Analysis**:
   - Evaluate the costs associated with both the current and proposed layouts.
2. **Production Rate**:
   - Determine the number of cars produced during an 8-hour shift.
3. **Optimization**:
   - Identify bottlenecks and areas for further improvement in the proposed layout.

## How to Run the Simulation

1. Open the ExtendSim project file for the proposed layout.
2. Run the simulation for an 8-hour period using the pre-configured settings.
3. Analyze the results displayed in the simulation dashboard, including:
   - Total production.
   - Cost breakdown.

## Results

The simulation results provide insights into the following:
- **Improved production efficiency** with automated processes.
- **Cost reductions** due to optimized resource management.
- Identification of potential bottlenecks for future improvement.

## Contact

For questions or further details, please contact the project team:
- Email: [support@buddyelectrical.com](mailto:support@buddyelectrical.com)
