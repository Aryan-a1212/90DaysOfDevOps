1] Environment basics

  Uname -a --> Print kernel information
  Os release 
         cat /etc/os-release --> shows linux istribution details

2] Filesystem Sanity

  mkdir folder --> create the folder
  cp folder1 folder2 --> copy all content from folder1 to folder2

3] CPU & Memory 

  top --> Shows live system performance
  ps -o pid --> Shows process status output format in process id.
  free -h --> Shows total memory
  df -h --> shows disk space

4] Network

  ss -tulpn | grep ssh --> shows listenting ports.
  curl -I http://localhost --> Connectivity check
  journalctl ctc -u ssh -n 50 --> shows the last 50 lines of logs
  tail -n 50 /var/log/auth.log --> shows last 50 lines of logs
