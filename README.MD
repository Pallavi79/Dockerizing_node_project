Open your working directory and clone the project

run command to build the project
```
docker build -t dockerizing-node-project .
```

run the below command to run the project
```
docker run -it --init --publish <yourport>:<containerport> dockerizing-node-project
```
