in this project we automates the process of apllying yaml/helm to kubernertes and argo cd 
as well conecting jenkins pod to minikube cluster

#step 1 we convert Python application and a nginx static website
from the former project to yaml.file and deploy them 

#step 2 Create a Service for Your nginx static-website
a way to expose an application running on a set of Pods as a network service A Service is an abstract !!

#step 3 Create an Ingress Resource for Your static-website Ingress is a collection of rules that allow inbound connections to reach your Services we used the service yaml.file

#step 4 Configure Resource Restrictions & readiness set up resource restrictions for CPU and memory utilization for your deployments and prevent causing performance issues

#step 5 Set up Horizontal Pod Autoscaler (HPA) configure Horizontal Pod Autoscaler for your deployments
automatically scale your deployments based on resource utilization from our "Resource Restrictions" the HPA in the Kubernetes need to configur in the yaml.file 

#step 6 Createing  a volume and a PVC to store data for the NGINX web server deployment 

#step 7 converting of all the Kubernetes templates that you created into a Helm chart. 
Helm is a package manager for Kubernetes that allows you to define, install, and manage Kubernetes applications 

Section 2:

#step 1  jenkins Kubernetes Cloud i only mange to connect to the jenkins pod manually and not automaticly 
the pos is standing and can be accesseed

#step 2 Create a Jenkins Pipeline for Your Applications becose of conectivi/communication problems the agent terminet with out
astablish agent pod in the jenkins nemespace 
 
#step 3  install Argocd onto your Kubernetes cluster, Argocd is a popular tool for managing Kubernetes deployments 
i usd official installation guide provided by the Argocd project to install it.

#step 4 Configure Argocd is an absolut need to define the applications you want to deploy and their associated parameters and settings. You can do this by creating YAML files that describe the desired state of your Kubernetes resources

#5 cent be done becose of my jenkins conectivi/communication problems
#6 cent be done becose of my jenkins conectivi/communication problems