# Mission Reflection

Writing a docker-compose.yml file makes the cloud engineer's job easier because the configuration for the containers is placed in one file. Instead of manually typing commands for each container, Docker Compose can use the file to deploy the application together.

YAML indentation is important because the file uses spaces to show the structure of the configuration. If the indentation is incorrect or a Tab is used instead of Spaces, Docker Compose may not be able to read the file correctly. This can cause an error when trying to deploy the containers.

Environment variables such as MYSQL_PASSWORD are used to provide the information needed by the application and database. In this activity, they provide the database password, database name, username, and database host. This allows the Nextcloud container to connect to the MariaDB container.

Deploying Nextcloud in just a few minutes showed me how useful Docker Compose can be. After creating the configuration file and running the deployment command, I was able to access the Nextcloud setup page through the browser. It made the deployment process easier to understand.

Since Mission 1, my understanding of Cloud Computing has improved. I learned that cloud computing is not only about using online services. I also learned about containers, deployment, configuration files, and Infrastructure as Code. This activity helped me understand how different parts of an application can work together in a cloud environment.
