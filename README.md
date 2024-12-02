# Buddy Electrical Plant Simulation

This project involves the analysis and simulation of the current and proposed layouts for the manufacturing plant of **Buddy Electrical**. The aim is to evaluate production efficiency and costs for an 8-hour shift, comparing the performance of the current plant layout with the newly proposed automated layout.

## Overview

The current layout was analyzed to determine production rates, resource utilization, and associated costs. Based on this analysis, a new automated layout was proposed, incorporating advanced resource management strategies and automation technologies. Using **ExtendSim**, the new layout was simulated to quantify its impact on the number of cars produced and the overall cost efficiency.

### Proposed Layout Structure

The proposed layout consists of:
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

### Simulation Objectives

1. **Cost Analysis**:
   - Evaluate the costs associated with both the current and proposed layouts.
   - Include resource costs, transportation, and downtime.
2. **Production Rate**:
   - Determine the number of cars produced during an 8-hour shift.
3. **Optimization**:
   - Identify bottlenecks and areas for further improvement in the proposed layout.

## How to Run the Simulation

1. Open the ExtendSim project file for the proposed layout.
2. Ensure all required data files are in the same directory as the project file.
3. Run the simulation for an 8-hour period using the pre-configured settings.
4. Analyze the results displayed in the simulation dashboard, including:
   - Total production.
   - Resource utilization rates.
   - Cost breakdown.

## Results

The simulation results provide insights into the following:
- **Improved production efficiency** with automated processes.
- **Cost reductions** due to optimized resource management.
- Identification of potential bottlenecks for future improvement.

## Contributing

If you wish to improve or extend the simulation:
1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a detailed explanation of your updates.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or further details, please contact the project team:
- Email: [support@buddyelectrical.com](mailto:support@buddyelectrical.com)
