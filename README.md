# P3project 

Cloud Simulator

Cloud Service Providers such as Amazon Web Services or Google Compute Engine offer computing, storage, and network infrastructure to businesses and entrepreneurs. Your task is to model the assignment and execution of applications on computing infrastructure.

A Cloud is generally composed of a set physical machines which allow the execution of Applications encapsulated as either Virtual Machines or Containers. A physical machine allows for only one type of virtualization (VM or Container). Multiple Applications can be run on the same physical machine if enough resources are available (CPU, RAM). Each application requires some amount of CPU and RAM and has a run time. You can consider an application uses the same amount of CPU and memory during its execution. Optional: You can have an execution file per Application, representing the amount of CPU and RAM used for each minute of execution. In this case, the requirements of the Application define the maximum values.

A Scheduler is an important component of the Cloud Simulator, determining the placement of Applications on corresponding physical machines.
The Scheduler should maintain a queue of pending Applications from which it chooses the next Application to be executed on the physical machines.

Requirements:
(1p) – Create a Class Diagram modelling the entities.
(3p) – Implement the entities described above as Java Classes, Interfaces or Enumerations.
(1p) – Present the average utilization of the Cloud (average of all physical machines) in 5 minute intervals for the duration of an experiment.
(1p) – Allow for multiple Scheduling Policies (FIFO, Shortest Running Time First, etc..)
(2p) – The Simulator should save its state incrementally to a file, such that in case of a crash the simulation can be reloaded from the last known state.
(1p) – Use command line arguments to determine if a new simulation must be started or if the user wants to reload from a simulation state file.
(1p) – Document your code
