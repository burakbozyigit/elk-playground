### Purpose
This project should install ELK with desired replicas and then setup Kibana with appropriate secret.
I'll be trying to install 3 node elastic cluster with Kibana reading its data from my own docker image.

### Done
* Created desired number of elastic replicas with deployments.
* Installed plain, not secured kibana with the docker image.

### Problems
* ElasticSearch is not persisting its data, yet. Which is a bit frustrating. 
* Had trouble with setting Kibana with creds is challenging then I imagined before. 
* I wasn't tried to create my own docker image as it seemed a bit easier then other stuuf that I should do, so i left it to the end.