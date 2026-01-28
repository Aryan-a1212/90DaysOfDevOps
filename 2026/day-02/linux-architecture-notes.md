1). Core Components of Linux

Kernel
     Heart of the Linux OS
     Manages CPU, memory, disk, and devices
     Talks directly to hardware
Shell
    Where users and applications run
  Includes:
    User space cannot access hardware directly → must go via kernel
Init / systemd
    First process started by kernel (PID 1)
    Brings the system to a usable state
    Manages services, boot order, logs, restarts


2). Process Management in Linux
A running instance of a program is called as Process. Each process has PID,State.

Process States
   Running (R) – Executing on CPU
   Sleeping (S) – Waiting for input/resource
   Stopped (T) – Paused manually (Ctrl+Z)
   Zombie (Z) – Process finished but parent didn’t clean it


3). What systemd Does?
 It start the service,stop the service,reboot the service ,easy debuging. 
