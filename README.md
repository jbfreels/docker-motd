# docker-motd
I use this motd script to show me highlevel docker stats.  

# deploy
Place ``11-docker`` into `/etc/update-motd.d/` folder.  Shouldn't conflict with existing messages.  
Log out and back in to see updated motd.

# output
```
## DOCKER STATS #################
#
# 7 container(s) running.
# 1 container(s) exited.
# 37 images.
#
## SWARM #######################
#
# 4 service(s) running.
#
################################
```
