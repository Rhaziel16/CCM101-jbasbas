# Mission Reflection

This activity gave me a better idea of how containers work compared to Virtual Machines. Before doing the activity, I knew Docker was used for containers, but I was not yet comfortable with the commands. After using KillerCoda and running the Nginx container, I understood the basic process better.

A Docker container can start faster than installing an operating system on a Virtual Machine. A VM needs an operating system to be installed and started before the application can be used. With Docker, I only needed to pull the Nginx image and run a container from it. The process was much quicker and did not require a separate operating system for the Nginx application.

The `-p 8080:80` part of the Docker command is important because it connects the host port to the port inside the container. In my activity, port 8080 was used on the host while Nginx was using port 80 inside the container. Because of this mapping, I was able to use `curl http://localhost:8080` and receive the Nginx welcome page.

When `docker rm` is used, the container is removed from Docker. Data that exists only inside the removed container may also be lost, so important data should not simply be kept inside a temporary container.

Containerization can also help developers and IT operations teams work together. Developers can prepare an application in a container, and the operations team can run the same container in another environment. This can reduce differences between development and deployment.

My GitHub portfolio is slowly becoming more organized as I add each laboratory activity. For this activity, I added Docker documentation, screenshots, commands, and my reflection. I also experienced a small mistake when I entered `-d` and `-p 8080:80` separately, but it helped me understand that these options belong with the `docker run` command.
