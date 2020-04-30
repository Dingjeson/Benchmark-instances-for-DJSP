# benchmark instances for DJSSP
The repository contains 15 benchmark instances with 15 different total number of random arrival jobs for the dynamic job shop scheduling problem.Suppose N denotes the total number of random arrival jobs, and N is 20,40,60,80,100,120,140,160,180,200,220,240,260,280,300.

In each instance, event type "0" indicates machine breakdown, event type "1" indicates new job arrival, event type "2" indicates change in the processing time of an operation and event type "3" indicates order cancellation. For instance, in the instance of N=20(20.txt), dynamic event D2 means machine 5 breakdowns at the 23th second and it continues for 106s, dynamic event D12 means, a new job arrives at the 193th second and this job’s processed sequence on the machines is M6, M3, M5, M10, M1, M2, M9, M7, M8, M4 and processing times on each machine are 66, 32, 7, 88, 57, 53, 55, 34, 57, 39 respectively, dynamic event D1 means the processing time of operation J24 changes as 70 s and so on, and dynamic event D8 means the remaining processing tasks of job 1 and job 9 are cancelled at the 130th second. 

