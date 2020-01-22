# DockerPython
Sample Docker Windows Python Container

## Docker Python Images Hub ##
<a href="https://hub.docker.com/_/python" target="_blank">https://hub.docker.com/_/python</a>

## Docker Commands ##
### Build ###
````
docker build -t python-carb-demo:latest .
````
### Run ###
````
docker run -it python-carb-demo
````
### Connect to container's powershell instance ###
````
docker run -it python-carb-demo powershell
````
#### Powershell command to check container's disk size ####
````
Get-WmiObject -Class Win32_logicaldisk
````
