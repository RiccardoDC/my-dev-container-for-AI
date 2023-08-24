# My container

### Brief recapp
[Github codespace, or simply codespace, is a cloud-based development environment that runs your code in a container] [1]. More specifically, whenever you work in a codespace, you are using a **development container,** also called dev container, on a virtual machine. A **development container** is a type of **Docker container** that is specifically configured to provide a fully featured development environment. 

The primary file in a dev container configuration is the **devcontainer.json** file.

The contents of **devcontainer.json** defines what a dev container should include such as frameworks, tools, extensions, and port forwarding. The **devcontainer.json** file usually contains a reference to a **Dockerfile**, which is typically located alongside the **devcontainer.json** file. [3]

A **Dockerfile** is a text file that contains a series of instructions for building a **Docker image**. It serves as a blueprint for creating a container that includes the application code, dependencies, and configuration settings. [1]

In general, containers are using the underlying operating system resources and drivers, so Windows containers can run on Windows only, and Linux containers can run on Linux only. Docker for Windows allows you to simulate running Linux containers on Windows, but under the hood a Linux VM is created, so still Linux containers are running on Linux, and Windows containers are running on Windows. [5]

### References
* [1]: https://bea.stollnitz.com/blog/vscode-ml-project/