

1) Process Management

 Command     Usage 

 ps aux --> Show all running processes 
 ps -ef --> Full-format process listing 
 top --> Live CPU & memory usage 
 htop --> Better interactive process viewer 
 pidof process --> Get PID of a process 
 kill PID --> Gracefully stop a process 
 kill -9 PID --> Force kill a process 
 pkill name --> Kill process by name 
 nice -n 10 cmd --> Set process priority 
 uptime --> System running time & load 



2)  File System & Disk

 Command    Usage 

 ls -lah --> List files with size & permissions 
 pwd --> Show current directory 
 cd /path --> Change directory 
 du -sh dir --> Directory size 
 df -h --> Disk usage 
 stat file --> File metadata 
 chmod 755 file --> Change permissions 
 chown user:group file --> Change ownership 
 find / -name file --> Search files 
 mount --> Show mounted filesystems 



3) Logs & Monitoring

 Command      Usage 

journalctl` --> View system logs 
journalctl -u service --> Logs for specific service 
tail -f file --> Live log monitoring 
less file --> Scroll large files 
grep "error" file --> Search logs 
dmesg --> Kernel messages 

---

4) Networking & Troubleshooting

 Command     Usage 

ping google.com --> Check connectivity 
ip addr --> Show IP addresses 
ip route --> Routing table 
ss -tulnp --> Listening ports 
curl url --> Test HTTP endpoint 
dig domain.com --> DNS lookup 
traceroute host --> Network path 

