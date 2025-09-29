# Task-Queue-System-
This is a lightweight task queue system written in Python.
Functions:
<br>

Register tasks (functions/jobs) with the queue.

Execute tasks using worker threads.

Schedule periodic tasks that run every X seconds.

Assign priority to tasks (urgent tasks run before normal ones).

Monitor the status of tasks via a CLI.
<br>
<br>



## --Execution-- 

Task class: Represents a single task. Stores name, status, priority, timestamps, and contains run() method.

TaskQueue class: Manages the task queue. Handles adding tasks, getting the next task, and showing task list.

Worker class: Thread that continuously picks tasks from the queue and executes them.

PeriodicTask class: Thread that periodically adds a task to the queue at fixed intervals.
<br>
<br>


## --Technologies / Concepts Used--

Python 3

OOP (Classes, Objects)

Threading

Locks (threading.Lock)

Heap Queue (heapq)

CLI / User Input

Periodic Scheduling
