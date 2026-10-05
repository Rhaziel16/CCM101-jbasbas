# Mission Reflection

Checking the host server's resources is important even when the containers are running properly because the container still depends on the host server. If the server has low memory, low storage, or high CPU usage, the application can still become slow or stop working. Checking the resources first gives us an idea of the server's condition before handling more users.

The `docker logs` command can also help when a user cannot log into a web application. It shows the requests and errors made by the application. By checking the logs, we can look for failed requests, error codes, or other information that can help us find the possible cause of the login problem.

Logs and metrics are different because they show different types of information. Logs show events and messages that happened inside the application, such as successful requests and errors. Metrics show numbers about the system, such as CPU usage, memory usage, and network activity. Both are useful because logs can help explain a problem while metrics can show the current condition of the container.

Large companies can monitor thousands of containers by using monitoring tools such as Prometheus and Grafana. These tools can collect and display information from many containers in one place. This makes it easier for administrators and engineers to notice problems and monitor the overall system.

This activity also improved my ability to troubleshoot Linux environments. I learned how to check memory, disk space, and running processes using Linux commands. I also learned how to deploy an Nginx container, create HTTP requests, check Docker logs, and monitor container resources. Instead of guessing what is wrong, I can now use commands and system information to investigate a problem.
