# fleming-sample


Points:

1. If I have mentioned port mapping in docker option n using bluegreen deployMethod then we cant run more than one-image/replica. Once we deploy one image that ll start running in the port n port is occupied. So next-image/replica will fail. MAKE SURE DOCKER OPTION WHICH HAVE PORT MAPPING DOESNOT HAVE MORE THAN ONE-IMAGE/REPLICA-COUNT
2. **Entry point image** have some configs and **driftking image** have some configs set by Vishnu while deploying image. So **"we cant test entry point n working dir docker option in same image"**
