ps aux  -->  List all running process
top -->  real time process monitoring

systemctl status ssh --> shows current ststus of ssh  file
systemctl list-units --type=service --> list all activites that is managed by systemd
systemctl is-active ssh --> tells service status

journalctl -u ssh --> shows log related service
journalctl -n 50  --> shows last 50 logs
