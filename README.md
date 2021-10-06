## Instructions
1. Get Docker running on machine
2. run "docker compose up" to build 
3. Run mysql script file to populate database

### WIP:
Need to run script in mysql container
Resources:
https://nextbreakpoint.com/posts/article-run-mysql-in-docker-container.html


### Troubleshooting:

To run Mysql on Docker I had to enable Hyper-V via powershell as Administrator. 

```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All

```

I am also unsure of whether or not this project needed a Dockerfile but I pulled this same Dockerfile from another project.
