# Mission Reflection

A host-based firewall protects a server by blocking unauthorized connections. Even if attackers bypass the network's main security, the firewall provides extra protection against unwanted access.

Managing open ports is important because they can be entry points for attackers. Closing unused ports reduces security risks and makes the server harder to attack. Only ports needed for important services should remain open.

Leaving MySQL port 3306 open to the public internet is dangerous because attackers can try to access the database from anywhere. If they find a weakness, they might steal, change, or delete important information. This can harm the company and its customers. Database access should be limited to trusted servers and authorized users.

From this activity, I learned that server security needs proper firewall settings and port management. These help prevent unauthorized access and protect important information. Administrators should regularly check open ports and close those that are no longer needed. This helps keep the server secure and reduces possible attacks.
