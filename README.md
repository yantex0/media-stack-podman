# media-stack-podman
<h3>Media Stack Configuration for use for in Podman (or idk, where ever)</h3>

So I have been making a Kubernetes YAML, I dont know the first thing about Kubernetes but Podman has a cross compatibility allowing it you use Kubernetes YAML files. So if you use Podman Desktop, go to Pods on the left and click 'Play Kubernetes YAML' and use the code from 'pod.yaml' from in the GitHub Gist below it will make a Pod which contains all of containers in it. The YAML makes the Pod and all the containers do start up and are accessible, so that works!

Podman can also be fully compatible with Docker commands and Docker Run and Compose. So you can just start a bunch of containers with Docker Compose files, then in Podman in containers (above the pods tab) select the containers you want to group, then towards the top click 'Create Pod'. Then go to the Pods tab click on the settings of the Pod and click 'Generate Kube' and Podman will make you a YAML file like the pod.yaml (without all the nice formatting and comments and it also adds unneeded fields) but it is still a fully working YAML to start a Pod.

<br/>

<h4>Play Kubernetes YAML Location</h4>

![Untitled](https://github.com/user-attachments/assets/52f2ca8f-f9c7-4026-802b-97225cd2b431)
