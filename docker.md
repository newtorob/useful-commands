- good command for cleaning up images in terminal
```docker rmi -f $(docker images | grep "<none>" | awk "{print \$3}")```

- want to get rid of a bunch of containers at once? 
```docker rm $(docker ps -a -q)```

- also, this is pretty fucking nice, it cleans up all your shit
```docker prune system```
