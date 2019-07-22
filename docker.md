- good command for cleaning up images in terminal
```docker rmi -f $(docker images | grep "<none>" | awk "{print \$3}")```
