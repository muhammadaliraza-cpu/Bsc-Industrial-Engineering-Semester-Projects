# Job Shop Sequencing Optimization with a Hardware Prototype

A manufacturing scheduling project combining Genetic Algorithm optimization, Python programming, and a physical hardware prototype.

## Project Overview

This project investigated job shop sequencing using production data from **Crescent Textile Mills Ltd**.

We implemented a **Genetic Algorithm (GA)** in Python using Google Colab to search for job sequences that minimize **makespan**—the total time required to complete all scheduled operations.

We also constructed a physical hardware prototype to demonstrate job sequencing concepts alongside the software analysis.

## Objectives

- Minimize makespan through computational scheduling.
- Examine operation sequences and machine assignments.
- Visualize production schedules and algorithm performance.
- Demonstrate scheduling concepts through a physical prototype.

## Production Data

The dataset included production lots, operations, machine assignments, processing times, and lot sizes.

The demonstrated scheduling instance contained:

- **3 production lots**
- **3 machines**
- **9 operations**

## Methodology

1. Organized production records in Microsoft Excel.
2. Implemented the Genetic Algorithm in Python.
3. Executed the scheduling workflow in Google Colab.
4. Evaluated candidate schedules using makespan.
5. Tracked scheduling performance across generations.
6. Generated operation schedules, Gantt charts, and convergence plots.

## Physical Hardware Prototype

We built a physical prototype incorporating microcontroller-based hardware, an LCD module, interface connections, and wiring within a protective enclosure.

The prototype provided a practical demonstration component alongside the computational scheduling work.

![Job shop sequencing hardware prototype](hardware-prototype.png)

## Reported Results

| Measure | Result |
|---|---|
| Production lots | 3 |
| Machines | 3 |
| Scheduled operations | 9 |
| Best recorded makespan | 7,264 model time units |
| Visualizations | Gantt chart and GA convergence plot |

The reported makespan represents the best schedule found in the demonstrated run.

## Tools and Techniques

- Python
- Google Colab
- Microsoft Excel
- Genetic Algorithm
- Job Shop Scheduling
- Gantt Charts
- Hardware Prototyping

## Academic Information

**Course:** Planning and Scheduling in Manufacturing  
**Program:** BSc Industrial Engineering  
**Institution:** University of Engineering and Technology, Taxila  
**Project Contributor:** Muhammad Ali Raza — 21-IE-21
