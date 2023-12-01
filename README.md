𝒜 𝓇𝑜𝓊𝓃𝒹 𝓇𝑜𝒷𝒾𝓃 𝓈𝒸𝒽𝑒𝒹𝓊𝓁𝒾𝓃𝑔 𝒶𝓁𝑔𝑜𝓇𝒾𝓉𝒽𝓂 𝑜𝓅𝓉𝒾𝓂𝒾𝓏𝑒𝒹 𝒷𝓎 𝓊𝓈𝒾𝓃𝑔 𝒹𝓎𝓃𝒶𝓂𝒾𝒸 𝓉𝒾𝓂𝑒 𝓆𝓊𝒶𝓃𝓉𝓊𝓂.
<!-- > - *Round Robin scheduling algorithm is the widely used scheduling algorithm in multitasking and real time environment. It is the most popular algorithm due to its fairness and starvation free nature towards the processes, which is achieved by using the time quantum.*
> - *Each scheduling algorithm has its own advantages and disadvantages. Similarly classical RR has a drawback which increases average waiting time, average turnaround time and minimizes the throughput, known as Context switch. The processes in RR are assigned with a time quantum which is static by nature.*
> - *Dynamic time quantum refers to changing time quantum based on the burst times of processes present in ready queue.*

 - *In our proposed algorithm, we are arranging the processes in ascending order according to their burst time present in the ready queue. For finding an optimal time quantum, median method is followed.* -->

<!-- $$
median(M)=\begin{equation}
\begin{cases} 
  \frac{Y(n+2)}{2} \text{, if n is odd;}\\
  \frac{1}{2}(Y\frac{n}{2} + \frac{Y (1+n)}{2}))\text{, if n is even.}
\end{cases}
\end{equation}
% \text{where n is the number of processes, and Y is the number in the middle when in ascending order.}    
$$ -->

<!-- $$
\text{optimal time quantum}=\frac{\text{highest burst time} + \begin{equation}
\begin{cases} 
  \frac{Y(n+2)}{2} \text{, if n is odd;}\\
  \frac{1}{2}(Y\frac{n}{2} + \frac{Y (1+n)}{2})\text{, if n is even.}
\end{cases}
\end{equation}
% \text{where n is the number of processes, and Y is the number in the middle when in ascending order.}
}{2}
$$ -->
