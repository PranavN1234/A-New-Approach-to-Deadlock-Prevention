# A-New-Approach-to-Deadlock-Prevention
A modified approach to deadlock prevention which is an optimized bankers Algorithm. This is our operating systems project which we submitted. This new approach solves cases where Bankers fails to excecute. 

Algorithm Used:-

  1) We first apply Bankers algorithm to check whether it
  is successful in generating a safe sequence or not.
  2) If Bankers algorithm fails in generating a safe
  sequence, we check which process is causing deadlock.
  3) Then we check which resources of the process are
  exceeding the limit.
  4) Now we preempt that process which has most
  instances of the resource causing the deadlock.
  5) Thus the deadlock is removed.
  6) The process remains in unsafe state if the resource
  required by that process exceeds the total number of
  resources of that type held by all the other processes.
