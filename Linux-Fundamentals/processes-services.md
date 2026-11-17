# Command	               Purpose
ps	                       Current processes
ps aux	                   All running processes
top	Live                   process monitoring
htop	                   Interactive process monitoring
pgrep apache2	           Process ID search
kill PID	               Process terminate
free -h	                   Memory usage
uptime	                   System running time


Service management:
# Command	                            Purpose
systemctl status apache2	            Service status
sudo systemctl start apache2    	    Start service
sudo systemctl stop apache2	            Stop service
sudo systemctl restart apache2	        Restart service
sudo systemctl enable apache2	        Enable at boot
sudo systemctl disable apache2   	    Disable at boot
systemctl list-units --type=service 	List active services
