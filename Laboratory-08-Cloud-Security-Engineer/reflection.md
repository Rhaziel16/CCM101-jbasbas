# Mission Reflection

A host-based firewall protects a server by blocking unauthorized network connections. Even if attackers bypass the network's main security, the firewall provides another layer of protection. It helps prevent unwanted access to the server and its services.

Managing open network ports is important because each open port can be a possible entry point for attackers. Closing unused ports reduces security risks and makes the server harder to attack. Administrators should only allow ports needed for important services.

Leaving MySQL port 3306 open to the public internet is dangerous because attackers can try to connect to the database from anywhere. They may attempt to guess passwords or exploit security weaknesses. If they gain access, they could steal, change, or delete important company and customer information. This can cause serious problems for the business.

To prevent these risks, database access should be limited to trusted servers and authorized users. Strong passwords, firewall rules, and regular security updates can also help protect the database.

From this activity, I learned that server security requires proper firewall settings and careful port management. Administrators should regularly check open ports and close those that are no longer needed. These practices help reduce possible attacks and keep important information safe.
