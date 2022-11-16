Create a website for CPU scheduling algorithms (FCFS, Priority Scheduling(non preemptive) and Priority Scheduling (Preemptive)). On clicking any algorithm, the page must display the working of the algorithm and have a working model of it. For instance, for priority scheduling, the working model should take input from the user related.


# CPU Scheduling Algorithms
### https://sauravhathi.github.io/cpu-scheduling-algorithms/

e.g. FCFS

## Working

FCFS is a non-preemptive algorithm. It is the simplest of all scheduling algorithms. It simply queues processes in the order they arrive in the ready queue. It is also called First Come First Served Scheduling.

## Working Model

Enter the number of processes: 3\
Enter the arrival time of process 1: 0\
Enter the burst time of process 1: 4\
Enter the arrival time of process 2: 1\
Enter the burst time of process 2: 5\
Enter the arrival time of process 3: 2\
Enter the burst time of process 3: 1\
Process 1:\
Waiting time: 0\
Turnaround time: 4\
Process 2:\
Waiting time: 4\
Turnaround time: 9\
Process 3:\
Waiting time: 9\
Turnaround time: 10\
Average waiting time: 4.333\
Average turnaround time: 7.667

## Time Complexity

O(n^2)

## Space Complexity

O(n)

## FCFS 

![image](https://user-images.githubusercontent.com/61316762/198582313-048c3e81-248a-46d4-aeb3-a7064c536401.png)

![image](https://user-images.githubusercontent.com/61316762/198582372-ba0bf03b-07cc-49a0-be56-1b8fee4a206e.png)

## Priority Scheduling (Non Preemptive)

![image](https://user-images.githubusercontent.com/61316762/194719945-d864dc35-f57c-4be4-b1f4-0db20080079c.png)


## Priority Scheduling (Preemptive)

## How to run

1. Clone the repository

```bash
git clone https://github.com/sauravhathi/cpu-scheduling-algorithms.git
```

2. Open index.html in your browser

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://github.com/sauravhathi/cpu-scheduling-algorithms/blob/main/LICENSE)
