# Mission Reflection

This laboratory helped me understand why monitoring is important when managing cloud servers and containers. Before this activity, I mostly focused on whether an application was running or not. I learned that a container can be running properly while the host server can still have problems with its CPU, memory, or storage.

Checking the host server's resources is important because containers still depend on the resources of the machine where they are running. If the server runs out of memory or disk space, the application can become slow or stop working even if the container itself looks normal.

The `docker logs` command can also help when a user cannot log into a web application. The logs can show requests, errors, and other information that happened inside the container. By checking them, I can look for errors related to the user's problem instead of guessing what went wrong.

Logs and metrics are different because logs show events or messages that happened in the application, while metrics give numbers about the system's current condition. In this activity, the logs showed the successful requests and the 404 error, while Docker metrics showed the CPU and memory being used by the container.

For large companies, monitoring thousands of containers manually would not be practical. They can use tools such as Prometheus and Grafana to collect and display information from many systems in one place. These tools can help engineers notice problems faster.

My Linux troubleshooting skills improved because I practiced using commands to check system resources, inspect Docker containers, create test traffic, and find errors in logs. I also learned that troubleshooting is easier when I use actual system information instead of just guessing the cause of a problem.
