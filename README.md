# What is Docker ?
Docker allows you to package an application with its dependencies so it runs consistently across different environments.
Resolves "Works on my machine" issue

## Image 
it acts as blueprint for docker container, instructions how to create container

## Container
running instance of Image, this is a actual running app

## Dockerfile
it's a text file that says, which base software to use, what files to copy, how to start the app

## Port mapping
Port mapping connects a port inside the container to a port on your laptop.
It creates a bridge between your machine(host) and container
<img width="993" height="462" alt="image" src="https://github.com/user-attachments/assets/1abfdb94-45a6-4cdc-a537-7e2c344c42fd" />
<img width="1006" height="521" alt="image" src="https://github.com/user-attachments/assets/c53dc007-5883-42ff-b68c-476080e3b14f" />



## docker-compose.yml
Docker Compose is a manager that starts multiple Docker containers together using one file and one command.
think it as remote control for many containers
it's a configuration file that tells docker
1) Which containers are needed
2) How they connect
3) Which ports to use
4) Environment variables
5) Startup order

<img width="1015" height="407" alt="image" src="https://github.com/user-attachments/assets/6545f73e-6926-407d-a968-48127ed16acb" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="1919" height="576" alt="image" src="https://github.com/user-attachments/assets/6c516bea-e2db-4d9d-94db-e3bab9d05d98" />

----------------------------------------------------------------------------------------------------------------------------------

<img width="1907" height="817" alt="image" src="https://github.com/user-attachments/assets/9030929d-37fd-4215-8d62-f89bd8835b95" />
