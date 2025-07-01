# Accuknox-Assignments
Product Management Trainee Assignment


Problem Statement for Product Manager

Problem Statement 1:
Title: Product Requirement and Low-Fidelity Wireframes
Background/Task:
A security product requires scanning container images and showing users the findings.
Container images contain applications with their dependencies and all these components
might have known vulnerabilities.
As a user:
I need to understand which container images have vulnerabilities and how severe they are.
If there are any critical or high vulnerabilities, I need to fix them and thus need to identify
which images have to be fixed.
I have thousands of images in my repository.
Help us build a product requirements/wireframe that can help users solve the above
problems.
Deliverables:
Create a Product Requirements document for the above.
Create low-fidelity wireframes for the user interface for this product.
(Bonus/Optional Task) Identify development action items that can be discussed with the
development team

Problem Statement 2:
Title: Kubernetes Security Scan
Background/Task:
Install local K8s cluster (such as Minikube, K3s, Kind, etc) and use a tool such as Kubescape (or
any other tool) to scan for findings and send the list of the findings.
Deliverables:
A JSON file containing the k8s findings.

Problem Statement 3 (Technical):
Step #1:
Create a GoLang Program which reflects the current date & time and host it on GitHub
Push that code to DockerHub
In other words: Use docker to create a web application with date & time as the only content
Step #2:
Using the declarative approach to deploy the container with 2 replicas to k8s
Step #3:
Expose the app to the Internet (on WAN)
Resource Hint/Help:
For k8s resources, you can use Qwiklabs (https://www.qwiklabs.com/ (https://www.qwiklabs.com/)) it
gives you around 30 to 60 mins of k8s resources or you can use your own GCP account or any
online available platform like https://labs.play-with-k8s.com (https://labs.play-with-k8s.com), etc
