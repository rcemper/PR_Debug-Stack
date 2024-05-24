# Cache-Debug-Stack
A class that enables you to create a stack of information for debugging in InterSystems Cache and Ensemble

Installation:
Import the xml file. It contains an include, the debug stack class and an example.

## Docker    

### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/rcemper/PR_Debug-Stack.git
```
to build and start the container run     
```
$ docker compose up -d && docker compose logs -f
```
A examples are ready to be used.   

To open IRIS Terminal do:   
```
$ docker-compose exec iris iris session iris 
USER>
```
or using **WebTerminal**     
http://localhost:42773/terminal/      

To access IRIS System Management Portal   
http://localhost:42773/csp/sys/UtilHome.csp    

