# My container

### Brief overview of codespace and container

Github codespace, or simply codespace, is a cloud-based development environment that runs your code in a container.

More specifically, whenever you work in a codespace, you are using a **development container,** also called dev container, on a virtual machine. A **development container** is a type of **Docker container** that is specifically configured to provide a fully featured development environment. 

The primary file in a dev container configuration is the **devcontainer.json** file.

The contents of **devcontainer.json** defines what a dev container should include such as frameworks, tools, extensions, and port forwarding. The **devcontainer.json** file usually contains a reference to a **Dockerfile**, which is typically located alongside the **devcontainer.json** file. 

A **Dockerfile** is a text file that contains a series of instructions for building a **Docker image**. It serves as a blueprint for creating a container that includes the application code, dependencies, and configuration settings. 

A full list of available docker images can be found [here](https://github.com/devcontainers/images/tree/main) in the src folder.

In general, containers are using the underlying operating system resources and drivers, so Windows containers can run on Windows only, and Linux containers can run on Linux only. Docker for Windows allows you to simulate running Linux containers on Windows, but under the hood a Linux VM is created, so still Linux containers are running on Linux, and Windows containers are running on Windows. 

### References
1. https://www.datacamp.com/tutorial/containerization-docker-and-kubernetes-for-machine-learning
2. https://www.datacamp.com/cheat-sheet/docker-for-data-science-cheet-sheet
3. https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers
4. https://bea.stollnitz.com/blog/vscode-ml-project/
5. https://stackoverflow.com/questions/42158596/can-windows-containers-be-hosted-on-linux