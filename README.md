# Mediquick-Emergency-Resource-Allocator-DAA-Mini-Project2
MediQuick: Emergency Resource Allocator

Problem Identification & Relevance

Problem Statement

Late one evening, a person meets with a serious road accident at a busy intersection in the city. He is badly injured and needs to be taken to a hospital immediately. Several ambulances are available across the city, but they are at different distances, some stuck in traffic, and the nearby hospitals vary in bed availability and capacity.

In such a critical situation, manually deciding which ambulance should reach the patient and which hospital should admit him often leads to confusion and delay. The injured person may not receive timely help because the nearest ambulance might already be engaged, or the chosen hospital might be full.

To address this real-world issue, there is a need for a smart emergency management system that can quickly identify the most suitable ambulance to reach the patient and the best hospital for immediate treatment — ensuring the fastest response time and efficient use of medical resources.

About the Project

MediQuick is a simulation-based emergency resource allocator that optimizes the process of ambulance and hospital assignment using algorithmic techniques. It integrates Greedy, Dynamic Programming, and Backtracking strategies to make intelligent, fast, and adaptive decisions during emergencies.

This project highlights the real-world relevance of algorithm design and analysis in life-critical situations, making it both educational and impactful.

Algorithmic / Technical Concepts

Algorithm Used Purpose Type

Greedy Algorithm Assigns the nearest available ambulance to each patient. Optimization Dynamic Programming Allocates hospitals to patients while minimizing total travel + load cost. DP Backtracking Reallocates patients if hospitals exceed their capacity. Search / Correction

These three techniques together ensure efficient, fair, and real-time allocation of emergency resources.

Design & Methodology

1:Flow of the System

2:Randomly generate data for patients, ambulances, and hospitals.

3:Apply Greedy Algorithm to assign ambulances based on minimum distance.

4:Use Dynamic Programming to allocate hospitals with least load and minimum total cost.

5:Apply Backtracking to reassign patients if any hospital exceeds capacity.

Display all allocation details in a user-friendly Tkinter GUI.

User Interface

Built using Tkinter and ttk for a clean and modern interface.

Two main buttons:

▶ Run Simulation – Starts a new allocation scenario.

♻ Reallocate Resources – Adjusts assignments based on new updates.

Log panel shows all allocation steps in real time. [17:36, 11/4/2025] Pranaya: 🚑 MediQuick – Emergency Resource Allocator

Problem Statement

In emergency situations, multiple patients require immediate medical attention. Ambulances must be assigned efficiently to reach patients, and patients must be allocated to hospitals with limited capacity in minimal time. This project, MediQuick, is a Python-based simulation that optimizes emergency ambulance and hospital allocation using algorithms like:

Greedy Algorithm – For ambulance-to-patient assignment (nearest ambulance first).

Dynamic Programming (Knapsack-based) – For optimal hospital selection minimizing distance and capacity overload.

Backtracking – For reallocation when hospitals exceed their capacity or new emergencies arise.

The project provides an interactive Tkinter UI that simulates these processes dynamically.

Algorithms Used

Algorithm Type Description Example

Greedy Algorithm Assigns the nearest available ambulance to each patient. Based on Activity Selection principle. Dynamic Programming (0/1 Knapsack) Allocates patients to hospitals minimizing total travel and load. Each hospital acts like a “bag” with capacity limits. Backtracking Reassigns patients if hospitals are overloaded or unavailable. Rebalances assignments efficiently.

Technologies Used

Language: Python

Libraries: tkinter, math, random

Concepts: Greedy approach, Dynamic Programming, Backtracking, GUI design

How to Run

Open VS Code.

1:Create a folder named MediQuick.

2:Inside it, create the following files:

main.py

ui.py

(optional) greedy_algorithm.py, dp_algorithm.py, backtracking.py

README.md

3:Paste your code into the respective files.

4:Run the app using:

5:python main.py

The Tkinter window will open showing:
Hospitals and their capacities

Ambulances and patient positions

Real-time allocation and reallocation simulation

Features

Smart ambulance dispatch system

Dynamic hospital assignment with capacity check

Backtracking-based reallocation for real-time updates

Clean, pastel-colored Tkinter UI



