#   ports.md — Network Ports


# Port ek communication endpoint hai jo identify karta hai ke server par kaunsi service communicate kar rahi hai.
Port	 Service
22      	SSH
53      	DNS
80      	HTTP
443     	HTTPS
3306	    MySQL
3000	    Node.js application (common default)
8080	   Jenkins (common default)



Practical commands:
#  Command                         	Purpose
ss -tuln                    	Listening TCP/UDP ports
ss -tulnp	                    Listening ports with process info (permissions may limit details)
sudo lsof -i -P -n	            Network connections and ports
nc -zv SERVER_IP 22	            Test port connectivity
curl -I http://SERVER_IP       	Test HTTP response
sudo ss -tulnp               	Check listening applications
