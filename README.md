# SJF_scheduling_algorithm_c
This C program implements the Shortest Job First (SJF) scheduling algorithm.


Here's a breakdown of the code:


Functions

1. findWaitingTime(): Calculates the waiting time for each process.

    - The waiting time for the first process is 0.
    - For subsequent processes, the waiting time is the sum of the previous process's burst time and waiting time.
2. findTurnAroundTime(): Calculates the turnaround time for each process.

    - The turnaround time is the sum of the burst time and waiting time.
3. findAverageTime(): Calculates and prints the average waiting time and average turnaround time.
4. sortProcessesByBurstTime(): Sorts processes by their burst times in ascending order.


Main Function

1. Asks the user to input the number of processes.
2. Initializes arrays for process IDs and burst times.
3. Asks the user to input the burst time for each process.
4. Sorts processes by their burst times using sortProcessesByBurstTime().
5. Calls findAverageTime() to calculate and print the average waiting time and average turnaround time.


Output

The program displays:


- A table with process IDs, burst times, waiting times, and turnaround times.
- The average waiting time.
- The average turnaround time.
