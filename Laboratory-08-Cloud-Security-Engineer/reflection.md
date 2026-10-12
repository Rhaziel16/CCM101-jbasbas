# Mission Reflection

A host-based firewall protects a server by blocking unauthorized network connections. Even if attackers get past the network's main security, the firewall can still help protect the server from unwanted access.

Managing open ports is important because unused ports can become entry points for attackers. Closing unnecessary ports reduces security risks and makes the server harder to attack. Administrators should only keep the ports needed for important services.

Leaving MySQL port 3306 open to the public internet is dangerous because attackers can try to access the database from anywhere. They may steal, change, or delete important information if they find a weakness. This can cause problems for the company and its customers. To avoid this, database access should only be allowed for trusted servers or authorized users.

From this activity, I learned that server security requires more than just protecting the network. Firewalls and proper port management help prevent unauthorized access and protect important data. Administrators should regularly check their firewall settings and close ports that are no longer needed. These practices help keep servers safer and reduce the chances of security problems.
