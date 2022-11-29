```
docker build -t your-app .
docker images 


docker build -t your-app:your-tag .
docker images 


docker run -it quay.io/practicalopenshift/hello-world
docker ps
docker kill 

-p (host port) : (container port)
-p 8080:80

netstat -ano | findstr
docker run -it -p 8080:8080 quay.io/practicalopenshift/hello-world

curl localhost:8080

docker run -it -p 8085:8080 quay.io/practicalopenshift/hello-world
                    ---
curl localhost:8085

```

#---==== container checklist ===--- 
- FROM 
- ENV 
- RUN 
- EXPOSE 
- CMD 


# Users & projects 
https://quay.io/
https://gitlab.com/
https://console-openshift-console.apps.sandbox.x8i5.p1.openshiftapps.com/topology/ns/atest6066-dev?view=graph


oc login -u atest6066



Turned off Hyper-V and rebooted
Uninstalled Docker for Windows
Went into the Device Manager and removed all obsolete Hyper-V switches and adapters
Turned on Hyper-V, rebooted and reinstalled Docker for Windows


https://forums.docker.com/t/error-response-from-daemon-dial-tcp-10-0-75-2-2375-connectex-a-connection-attempt-failed-because-the-connected-party-did-not-properly-respond-after-a-period-of-time-or-established-connection-failed-because-connected-host-has-failed-to-respond/9425/11

https://www.youtube.com/watch?v=mklu2H3gxM8