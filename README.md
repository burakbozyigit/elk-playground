### Purpose
This project should install ELK with desired replicas and then setup Kibana with appropriate secret.
I'll be trying to install 3 node elastic cluster with Kibana reading its data from my own docker image.

### Done
* Create a helm template then produces these finalized.yaml file for `kubectl` to use in any k8s env.
* Created finalized.yaml with command `helm template .|tee finalized.yaml` and applied with `k apply -f finalized.yaml`
* Created desired number of elastic replicas with deployments.
* Installed plain, not secured kibana with the docker image.
### Problems
* ElasticSearch is not persisting its data, yet. Which is a bit frustrating. 
* Had troubles with setting Kibana with creds is challenging then I imagined before. 
* I wasn't tried to create my own docker image as it seemed a bit easier than other stuff that I should do, so i left it to the end.