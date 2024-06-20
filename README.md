# CPU-Scheduler

In this project, various CPU scheduling algorithms have been implemented.
Whats it is? -> CPU Scheduling is a process that allows one process to use the CPU while another process is delayed (in standby) due to unavailability of any resources such as I / O etc, thus making full use of the CPU.
Purpose? -> The purpose of CPU Scheduling is to make the system more efficient, faster, and fairer.

Types: Preeemptive and Non-preemptive scheduling
Following 5 algorithms have been implemented:
1) First Come First Serve (FCFS): Simplest CPU scheduling algorithm that schedules according to arrival times of processes. The first come first serve scheduling algorithm states that the process that requests the CPU first is allocated the CPU first. It is implemented by using the FIFO queue.
2) Round Robin (RR): A round-robin scheduling algorithm is used to schedule the process fairly for each job a time slot or quantum and the interrupting the job if it is not completed by then the job come after the other job which is arrived in the quantum time that makes these scheduling fairly.
3) Priority (Preemptive): Preemptive Priority CPU Scheduling Algorithm is a pre-emptive method of CPU scheduling algorithm that works based on the priority of a process. In this algorithm, the scheduler schedules the tasks to work as per the priority, which means that a higher priority process should be executed first.
4) Priority (Non-Preemptive): In the Non Preemptive Priority scheduling, The Processes are scheduled according to the priority number assigned to them. Once the process gets scheduled, it will run till the completion.
5) Highest Response Ratio Next (HRRN scheduling is non-preemptive scheduling, i.e. Non-preemptive scheduling is scheduling in which priority of each job depends on its estimated run time and the amount of time spent on waiting. The longer they wait they gain higher priority which prevents the process of starvation. i.e. The Response ratio should be concerned with requested to serve time and waiting time. HRRN does not suitable for priority systems.


References Used:
1) https://www.youtube.com/watch?v=zFnrUVqtiOY&list=PLGF9VeuyJzDfFEeiK2N9NYhHedyEHQHxI
2) https://www.youtube.com/watch?v=AiVKIdGheEU&list=PLIY8eNdw5tW_lHyageTADFKBt9weJXndE
