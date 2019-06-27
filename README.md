# benchmark instances for DJSSP
The repository contains 15 benchmark instances for dynamic job shop scheduling problem.

Appendix A. The dynamic job shop instances used in our experiments
In each instance, event type “0” indicates machine breakdown, event type ‘‘1” indicates new job arrival, event type ‘‘2” indicates change in the processing time of an operation and event type ‘‘3” indicates order cancellation. For instance, in Table 7, dynamic event D5 means machine 1 breakdowns at the 12th second and it continues for 3 s, dynamic event D4 means, a new job J6 arrives at the 5th second and this job’s processed sequence on the machines is M3, M5, M2, M4, M1 and processing times on each machine are 7, 3, 6, 1, 4 respectively, dynamic event D1 means the processing time of job J4 on machine M1 changes as 6 s, and dynamic event D8 means job5’s remaining processing tasks are cancelled at the 23th second. 

################################################

Data of 5×5 dynamic job scheduling problem.
Machine sequences and processing times
Jobs	Machine sequences and processing times (s)
J1	M3(2)	M1(8)	M2(4)	M4(6)	M5(7)
J2	M2(6)	M3(5)	M5(4)	M1(3)	M4(2)
J3	M1(7)	M5(8)	M4(4)	M3(9)	M2(3)
J4	M4(4)	M3(5)	M2(5)	M1(4)	M5(3)
J5	M5(5)	M3(7)	M1(3)	M2(6)	M4(4)

Dynamic events
Dynamic events	Occurrence time	Event type	Information about dynamic events
D1		0		2		J4 M1 6
D2		0		2		J1 M5 10
D3		0		2		J3 M2 5 
D4		5		1		J6 M3 7 M5 3 M2 6 M4 1 M1 4
D5		12		0		M2 3
D6		18		1		J7 M4 8 M3 5 M2 3 M1 6 M5 7
D7		23		0		M4 6
D8		23		3		J5 
