# CPU-Scheduler

Getdata method contains the user input for no. of process and burst time for process. Fcfs method calculates First come First served Algorithm and show the Total and Average Weighting Time. Sjf method calculates Shortest job First Algorithm, SjfNp is Shortest job First Algorithm with Non Preemptive, SjfP is Shortest job First Algorithm with Preemption and RoundRobin method is Round Robin Algorithm  and show the Total and Average Weighting Time.

The main function, in the main function there is a infinity loop with a termination point. When the user enters an choice the with the following number the program goes to the corresponding method call the Algorithm or User Input for calculation.

## Method definition:

- ### fcfs()
Step 1: it loops through all the burst time process.

Step 2: now it store weight in the array.

Step 3: after that, the third loop in the method calculates the total weight time and we can divide the total time with the no. of process to find the average time.

- ### sjf()
Step 1: firstly the program loops through the time for process then

Step 2: it sort the burst time process and

Step 3: calculate the weight by adding the previous value of weight and the burst time which stored inside the array.

Step 4: finally the total weighting time is calculate by adding the current time and weight

- ### sjfNp()
Step 1: in the beginning of the method it prints out the burst time for the process and gets the input from the arrival time of the process.

Step 2: after that the burst array and arrival time array sort their position by ascending order.

Step 3: now program prints the burst time and arrival time.

Step 4: the total weighting time is calculate by adding the current time with the result of weight subtracting by the arrival time.

Step 5: finally the average weight calculation, total weight divide by the number of processes.

- ### Priority()
Step 1: shows Burst time and get input from the priority for process from the user

Step 2: it calculate the weight by w=w+B[i] if current value of P equals to j

Step 3: then the method loop through the current time and adding the time with all weights in the array to find the total time and divide by the processes will show the average time.

- ### sjfP()
Step 1: in the beginning of the method it prints out the burst time for the process and gets the input from the arrival time of the process and we calculate assign the biggest value of arrival time in the time variable.

Step 2: now while the t is less than Time and if arrival time is less or equal t and burst time not equals zero then the program prints the weight. Next for burst time is zero the program loop through with the condition of j is less then n and the flag is not equal zero and if (S[j]!='F' && B[i]>B[j] && A[j]<=t && i!=j) this satisfies then the program set the flag to 0 and add weight in the weight array.

Step 3: then the program prints the remaining burst time

Step 4: after that the weight info shows in the console by loop

Step 5: now after subtracting the arrival time with the weight the program calculate the total time and average time.

- ### RoundRobin()
Step 1: in the beginning of the method it prints out the burst time.

Step 2: get the time Quantum.

Step 3: m = max / tq + 1 TO find the dimension of the Rrobin array

Step 4: Now, initializing Robin array by a two dimensional array.

Step 5: placing value in the Rrobin array

Step 6: Display the robin array.

Step 7: calculate the weighting time, total time and average time.
