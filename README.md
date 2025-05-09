# kubernetes-infra-notes
Kubernetes:
Definition: Automates container deployment, scaling, and management.
Why Use It?

Auto-scaling: Handles traffic spikes.

High Availability: Restarts failing containers.

Easy Deployments: Simplifies updates/rollbacks.

Efficient Resources: Optimizes hardware use
.
Less Complexity: Automates container management.

Dev Focus: Lets developers build, not manage.

Consistent Platform: Works anywhere.

Before Kubernetes (Traditional):


Manual: Deployment and scaling were manual.

Inconsistent: Environments varied.

Low Resource Use: Servers often underutilized.

Downtime Risk: Failures meant manual fixes.

Complex: Managing distributed apps was hard.

![image](https://github.com/user-attachments/assets/2bc3e189-edba-404f-9872-5cba2f4759d7)



Control Plane (Master Node):


Client (kubectl, UI, CLI): Tools that users interact with to manage the Kubernetes cluster.

API SERVER: The central control plane component that exposes the Kubernetes API.

Scheduler: Assigns newly created pods to nodes for execution.

ETCD: A distributed key-value store that serves as Kubernetes' backing store for all cluster data.


Controller Manager: Runs controller processes that regulate the state of the Kubernetes cluster.
MASTER: The control plane node(s) that manage the Kubernetes cluster.

Worker Node:


Kubelet: An agent that runs on each node and ensures that containers are running in pods.

Kube-proxy: A network proxy that runs on each node, implementing Kubernetes service concepts.

Container-runtime: The underlying software (e.g., Docker, containerd) that runs containers.

Worker Node: A machine in the Kubernetes cluster that runs your applications in pods.

Container Node: Another term often used interchangeably with "Worker Node," referring to a machine that runs containers managed by Kubernetes.

Kubernetes Object:


Pod: The smallest deployable unit in Kubernetes, representing a group of one or more containers that share storage and network resources.

Documentation:


https://kubernetes.io/docs/concepts/architecture/


Youtube video in English :


https://youtu.be/B_X4l4HSgtc?si=gCUD8hgKItndTTb3


Youtybe Video in Urdu:


https://youtu.be/7ZObcqEq7hU?si=IQMkn_DiXzKygZ5h

![image](https://github.com/user-attachments/assets/fc52dc72-6f28-4db9-a98a-de494e410906)

