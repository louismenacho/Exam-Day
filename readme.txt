Exam Day
Simulates an exam day utilizing threads and a client-server model.
Developed monitors to synchronize the threads in the context of the problem.
Client threads connect to server to participate in story.
Created a server that spawned threads to handle clients accordingly.

How to run:
1.Run server.jar
2.Run client.jar

Commands to JAR:
To launch Server: java -jar server.jar portNumber
To launch Client: java -jar client.jar hostName portNumber numStudent capacity numSeats

Example:
java -jar server.jar 1026
java -jar client.jar localhost 1026 16 12 3

A welcome message (Welcome to ExamDay) will be displayed to any client that connects.
When all methods finish executing, the client will terminate.

Simulation:
Server socket created on port 1025
[0] Timer-: It is 12:00 pm now
[0] Timer-: Exam 1 scheduled at 01:00 pm (at 6000 ms)
[0] Timer-: Exam 2 scheduled at 03:00 pm (at 18000 ms)
[0] Timer-: Exam 3 scheduled at 05:00 pm (at 30000 ms)
[0] Timer-: Exam 4 scheduled at 07:00 pm (at 42000 ms)
[2506] Student-05: Door is locked, waits in front of classroom
[3512] Student-15: Door is locked, waits in front of classroom
[3873] Student-02: Door is locked, waits in front of classroom
[3879] Student-07: Door is locked, waits in front of classroom
[4143] Student-10: Door is locked, waits in front of classroom
[4504] Instructor-: Unlocked the classroom, exam will begin in 15 min(1.5 sec)
[4502] Student-10: Entered classroom
[4503] Student-15: Entered classroom
[4502] Student-02: Entered classroom
[4502] Student-07: Entered classroom
[4503] Student-15: Sat in table 1
[4503] Student-07: Sat in table 1
[4504] Student-05: Entered classroom
[4504] Student-02: Sat in table 1
[4504] Student-05: Sat in table 2
[4504] Student-10: Sat in table 2
[4700] Student-11: Entered classroom
[4701] Student-11: Sat in table 2
[5232] Student-16: Entered classroom
[5232] Student-16: Sat in table 3
[5672] Student-06: Entered classroom
[5673] Student-06: Sat in table 3
[5742] Student-08: Entered classroom
[5743] Student-08: Sat in table 3
[5982] Student-01: Entered classroom
[5982] Student-01: Sat in table 4
[6004] Timer-: Exam 1 has begun
[5999] Instructor-: Handed out the exams
[5997] Student-02: Began exam
[5997] Student-01: Began exam
[5997] Student-10: Began exam
[5997] Student-06: Began exam
[5997] Student-08: Began exam
[5997] Student-11: Began exam
[5998] Student-16: Began exam
[5997] Student-05: Began exam
[5997] Student-15: Began exam
[5997] Student-07: Began exam
[6191] Student-09: Missed the exam, waits in front of classroom
[6482] Student-12: Missed the exam, waits in front of classroom
[6953] Student-04: Missed the exam, waits in front of classroom
[7023] Student-14: Missed the exam, waits in front of classroom
[7174] Student-13: Missed the exam, waits in front of classroom
[7898] Student-03: Missed the exam, waits in front of classroom
[12005] Timer-: Exam 1 has ended
[11998] Student-07: Is checking their notes
[11998] Student-05: Is checking their notes
[11998] Student-16: Is checking their notes
[11998] Student-11: Is checking their notes
[11998] Student-15: Is checking their notes
[11999] Student-06: Is checking their notes
[11998] Student-08: Is checking their notes
[11999] Student-01: Is checking their notes
[11999] Student-10: Is checking their notes
[11999] Student-02: Is checking their notes
[12503] Student-07: Returned exam
[12503] Student-16: Returned exam
[12503] Student-06: Returned exam
[12504] Student-01: Returned exam
[12504] Student-10: Returned exam
[12506] Instructor-: Is checking an exam...
[12504] Student-02: Returned exam
[12504] Student-08: Returned exam
[12505] Student-15: Returned exam
[12505] Student-11: Returned exam
[12505] Student-05: Returned exam
[12711] Instructor-: Graded an exam (1)
[12712] Instructor-: Is checking an exam...
[12710] Student-16: Got grade: 50
[12916] Instructor-: Graded an exam (2)
[12916] Instructor-: Is checking an exam...
[12914] Student-07: Got grade: 92
[13120] Instructor-: Graded an exam (3)
[13120] Instructor-: Is checking an exam...
[13118] Student-02: Got grade: 0
[13323] Instructor-: Graded an exam (4)
[13323] Instructor-: Is checking an exam...
[13321] Student-01: Got grade: 66
[13525] Instructor-: Graded an exam (5)
[13525] Instructor-: Is checking an exam...
[13523] Student-10: Got grade: 0
[13730] Instructor-: Graded an exam (6)
[13730] Instructor-: Is checking an exam...
[13728] Student-06: Got grade: 91
[13930] Instructor-: Graded an exam (7)
[13931] Instructor-: Is checking an exam...
[13929] Student-08: Got grade: 7
[14133] Instructor-: Graded an exam (8)
[14133] Instructor-: Is checking an exam...
[14131] Student-15: Got grade: 10
[14337] Instructor-: Graded an exam (9)
[14337] Instructor-: Is checking an exam...
[14335] Student-11: Got grade: 100
[14537] Instructor-: Graded an exam (10)
[14536] Student-05: Got grade: 0
[14536] Student-14: Capacity reached, waits in front of classroom
[14536] Student-13: Entered classroom
[14536] Student-13: Sat in table 4
[14536] Student-03: Entered classroom
[14536] Student-04: Capacity reached, waits in front of classroom
[14536] Student-12: Capacity reached, waits in front of classroom
[14536] Student-03: Sat in table 4
[14536] Student-09: Capacity reached, waits in front of classroom
[18007] Timer-: Exam 2 has begun
[18002] Instructor-: Handed out the exams
[18001] Student-15: Began exam
[18001] Student-03: Began exam
[18001] Student-08: Began exam
[18001] Student-02: Began exam
[18001] Student-11: Began exam
[18001] Student-05: Began exam
[18001] Student-16: Began exam
[18001] Student-06: Began exam
[18001] Student-13: Began exam
[18001] Student-07: Began exam
[18001] Student-01: Began exam
[18001] Student-10: Began exam
[24011] Timer-: Exam 2 has ended
[24005] Student-10: Is checking their notes
[24004] Student-01: Is checking their notes
[24005] Student-07: Is checking their notes
[24005] Student-13: Is checking their notes
[24006] Student-06: Is checking their notes
[24006] Student-16: Is checking their notes
[24006] Student-05: Is checking their notes
[24006] Student-11: Is checking their notes
[24006] Student-02: Is checking their notes
[24006] Student-08: Is checking their notes
[24007] Student-03: Is checking their notes
[24007] Student-15: Is checking their notes
[24508] Student-01: Returned exam
[24508] Student-13: Returned exam
[24508] Student-06: Returned exam
[24509] Student-11: Returned exam
[24509] Student-15: Returned exam
[24511] Instructor-: Is checking an exam...
[24509] Student-03: Returned exam
[24509] Student-08: Returned exam
[24510] Student-02: Returned exam
[24510] Student-16: Returned exam
[24510] Student-05: Returned exam
[24510] Student-07: Returned exam
[24510] Student-10: Returned exam
[24715] Instructor-: Graded an exam (1)
[24715] Instructor-: Is checking an exam...
[24714] Student-01: Got grade: 24
[24917] Instructor-: Graded an exam (2)
[24917] Instructor-: Is checking an exam...
[24915] Student-13: Got grade: 8
[25121] Instructor-: Graded an exam (3)
[25121] Instructor-: Is checking an exam...
[25119] Student-06: Got grade: 64
[25324] Instructor-: Graded an exam (4)
[25324] Instructor-: Is checking an exam...
[25322] Student-11: Got grade: 59
[25526] Instructor-: Graded an exam (5)
[25526] Instructor-: Is checking an exam...
[25524] Student-15: Got grade: 69
[25729] Instructor-: Graded an exam (6)
[25729] Instructor-: Is checking an exam...
[25728] Student-03: Got grade: 33
[25931] Instructor-: Graded an exam (7)
[25932] Instructor-: Is checking an exam...
[25930] Student-08: Got grade: 26
[26132] Instructor-: Graded an exam (8)
[26132] Instructor-: Is checking an exam...
[26130] Student-02: Got grade: 87
[26336] Instructor-: Graded an exam (9)
[26336] Instructor-: Is checking an exam...
[26334] Student-16: Got grade: 88
[26541] Instructor-: Graded an exam (10)
[26541] Instructor-: Is checking an exam...
[26543] Student-05: Got grade: 5
[26744] Instructor-: Graded an exam (11)
[26745] Instructor-: Is checking an exam...
[26743] Student-07: Got grade: 34
[26945] Instructor-: Graded an exam (12)
[26943] Student-09: Capacity reached, waits in front of classroom
[26943] Student-10: Got grade: 76
[26944] Student-12: Capacity reached, waits in front of classroom
[26944] Student-04: Capacity reached, waits in front of classroom
[26944] Student-14: Capacity reached, waits in front of classroom
[30017] Timer-: Exam 3 has begun
[30013] Instructor-: Handed out the exams
[30011] Student-07: Began exam
[30011] Student-16: Began exam
[30011] Student-02: Began exam
[30011] Student-08: Began exam
[30011] Student-10: Began exam
[30011] Student-15: Began exam
[30011] Student-01: Began exam
[30011] Student-03: Began exam
[30011] Student-11: Began exam
[30011] Student-06: Began exam
[30011] Student-13: Began exam
[30011] Student-05: Began exam
[36021] Timer-: Exam 3 has ended
[36015] Student-05: Is checking their notes
[36015] Student-13: Is checking their notes
[36015] Student-11: Is checking their notes
[36015] Student-03: Is checking their notes
[36015] Student-06: Is checking their notes
[36015] Student-01: Is checking their notes
[36015] Student-10: Is checking their notes
[36015] Student-15: Is checking their notes
[36015] Student-08: Is checking their notes
[36015] Student-02: Is checking their notes
[36015] Student-07: Is checking their notes
[36015] Student-16: Is checking their notes
[36516] Student-05: Returned exam
[36516] Student-15: Returned exam
[36516] Student-07: Returned exam
[36518] Instructor-: Is checking an exam...
[36516] Student-16: Returned exam
[36517] Student-02: Returned exam
[36517] Student-08: Returned exam
[36517] Student-01: Returned exam
[36517] Student-10: Returned exam
[36517] Student-06: Returned exam
[36517] Student-03: Returned exam
[36517] Student-13: Returned exam
[36517] Student-11: Returned exam
[36723] Instructor-: Graded an exam (1)
[36723] Instructor-: Is checking an exam...
[36721] Student-05: Got grade: 21
[36721] Student-05: Left classroom
[36721] Student-09: Entered classroom
[36721] Student-09: Sat in table 2
ClientHelper for StudentClient-05 terminated
[36926] Instructor-: Graded an exam (2)
[36926] Instructor-: Is checking an exam...
[36924] Student-07: Got grade: 31
[36924] Student-07: Left classroom
[36924] Student-12: Entered classroom
[36924] Student-12: Sat in table 1
ClientHelper for StudentClient-07 terminated
[37128] Instructor-: Graded an exam (3)
[37128] Instructor-: Is checking an exam...
[37126] Student-15: Got grade: 100
[37127] Student-15: Left classroom
[37127] Student-04: Entered classroom
[37127] Student-04: Sat in table 1
ClientHelper for StudentClient-15 terminated
[37329] Instructor-: Graded an exam (4)
[37329] Instructor-: Is checking an exam...
[37327] Student-16: Got grade: 36
[37327] Student-16: Left classroom
[37327] Student-14: Entered classroom
[37327] Student-14: Sat in table 3
ClientHelper for StudentClient-16 terminated
[37532] Instructor-: Graded an exam (5)
[37533] Instructor-: Is checking an exam...
[37531] Student-02: Got grade: 26
[37531] Student-02: Left classroom
ClientHelper for StudentClient-02 terminated
[37735] Instructor-: Graded an exam (6)
[37735] Instructor-: Is checking an exam...
[37733] Student-08: Got grade: 91
[37733] Student-08: Left classroom
ClientHelper for StudentClient-08 terminated
[37935] Instructor-: Graded an exam (7)
[37935] Instructor-: Is checking an exam...
[37933] Student-01: Got grade: 85
[37934] Student-01: Left classroom
ClientHelper for StudentClient-01 terminated
[38136] Instructor-: Graded an exam (8)
[38136] Instructor-: Is checking an exam...
[38134] Student-10: Got grade: 49
[38134] Student-10: Left classroom
ClientHelper for StudentClient-10 terminated
[38336] Instructor-: Graded an exam (9)
[38336] Instructor-: Is checking an exam...
[38334] Student-06: Got grade: 63
[38334] Student-06: Left classroom
ClientHelper for StudentClient-06 terminated
[38537] Instructor-: Graded an exam (10)
[38537] Instructor-: Is checking an exam...
[38535] Student-03: Got grade: 79
[38739] Instructor-: Graded an exam (11)
[38739] Instructor-: Is checking an exam...
[38737] Student-13: Got grade: 2
[38942] Instructor-: Graded an exam (12)
[38940] Student-11: Got grade: 37
[38941] Student-11: Left classroom
ClientHelper for StudentClient-11 terminated
[42026] Timer-: Exam 4 has begun
[42021] Instructor-: Handed out the exams
[42019] Student-04: Began exam
[42019] Student-09: Began exam
[42019] Student-14: Began exam
[42019] Student-13: Began exam
[42019] Student-12: Began exam
[42019] Student-03: Began exam
[48026] Timer-: Exam 4 has ended
[48020] Student-03: Is checking their notes
[48020] Student-12: Is checking their notes
[48020] Student-14: Is checking their notes
[48020] Student-13: Is checking their notes
[48020] Student-09: Is checking their notes
[48020] Student-04: Is checking their notes
ClientHelper for TimerClient terminated
[48525] Student-12: Returned exam
[48525] Student-09: Returned exam
[48525] Student-04: Returned exam
[48527] Instructor-: Is checking an exam...
[48525] Student-03: Returned exam
[48526] Student-13: Returned exam
[48526] Student-14: Returned exam
[48729] Instructor-: Graded an exam (1)
[48729] Instructor-: Is checking an exam...
[48727] Student-12: Got grade: 97
[48727] Student-12: Left classroom
ClientHelper for StudentClient-12 terminated
[48931] Instructor-: Graded an exam (2)
[48931] Instructor-: Is checking an exam...
[48930] Student-09: Got grade: 3
[48930] Student-09: Left classroom
ClientHelper for StudentClient-09 terminated
[49136] Instructor-: Graded an exam (3)
[49137] Instructor-: Is checking an exam...
[49135] Student-04: Got grade: 89
[49135] Student-04: Left classroom
ClientHelper for StudentClient-04 terminated
[49341] Instructor-: Graded an exam (4)
[49341] Instructor-: Is checking an exam...
[49339] Student-03: Got grade: 86
[49339] Student-03: Left classroom
ClientHelper for StudentClient-03 terminated
[49546] Instructor-: Graded an exam (5)
[49546] Instructor-: Is checking an exam...
[49544] Student-14: Got grade: 2
[49545] Student-14: Left classroom
ClientHelper for StudentClient-14 terminated
[49748] Instructor-: Graded an exam (6)
[49746] Student-13: Got grade: 95
[49746] Student-13: Left classroom
ClientHelper for StudentClient-13 terminated
<<<<<<<<<<<<<GRADEBOOK>>>>>>>>>>>>
Student ## Grades:	E1	E2	E3	E4
Student 01 Grades:	66	24	85	00
Student 02 Grades:	43	87	26	00
Student 03 Grades:	00	33	79	86
Student 04 Grades:	00	00	00	89
Student 05 Grades:	00	05	21	00
Student 06 Grades:	91	64	63	00
Student 07 Grades:	92	34	31	00
Student 08 Grades:	07	26	91	00
Student 09 Grades:	00	00	00	03
Student 10 Grades:	47	76	49	00
Student 11 Grades:	100	59	37	00
Student 12 Grades:	00	00	00	97
Student 13 Grades:	00	08	02	95
Student 14 Grades:	00	00	00	02
Student 15 Grades:	10	69	100	00
Student 16 Grades:	50	88	36	00
[49855] Instructor-: Left classroom
ClientHelper for InstructorClient terminated
