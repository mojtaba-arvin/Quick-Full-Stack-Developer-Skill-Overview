### Amazon EKS Basics:
- **Managed Kubernetes Service:** Understand Amazon EKS as a fully managed Kubernetes service provided by AWS for deploying, managing, and scaling containerized applications using Kubernetes orchestration.
- **Kubernetes Control Plane:** Learn about the Kubernetes control plane components managed by Amazon EKS, including the API server, controller manager, scheduler, and etcd cluster for cluster management and coordination.
- **Worker Nodes:** Provision and manage worker nodes in Amazon EKS clusters using Amazon EC2 instances, which run the Kubernetes kubelet agent and container runtime (e.g., Docker, containerd) for hosting application workloads.
- **Networking:** Configure networking for Amazon EKS clusters using Amazon VPC (Virtual Private Cloud) networking, subnets, security groups, and VPC endpoint services for secure communication and isolation of Kubernetes resources.

### Cluster Management:
- **Cluster Creation:** Create Amazon EKS clusters using the AWS Management Console, AWS CLI, or AWS CloudFormation templates with a few simple steps, including cluster configuration, networking, IAM roles, and Kubernetes version selection.
- **Cluster Scaling:** Scale Amazon EKS clusters horizontally by adding or removing worker nodes dynamically based on workload demand, auto scaling policies, and cluster autoscaler integration for optimal resource utilization and cost efficiency.
- **Cluster Upgrades:** Upgrade Kubernetes versions and patch levels for Amazon EKS clusters using rolling updates, managed upgrades, and maintenance windows to apply security patches, feature enhancements, and bug fixes.

### Node Groups and Instance Types:
- **Node Groups:** Create and manage node groups in Amazon EKS clusters to provision, scale, and manage groups of EC2 instances as worker nodes with similar configurations, instance types, and lifecycle policies.
- **Instance Types:** Choose appropriate EC2 instance types (e.g., t3, m5, c5) for worker nodes in Amazon EKS clusters based on workload requirements, performance characteristics, CPU/memory resources, and cost considerations.

### Security and Access Control:
- **IAM Integration:** Integrate Amazon EKS with AWS Identity and Access Management (IAM) for authentication and authorization of Kubernetes API requests, cluster resources, and worker node access using IAM roles, policies, and service-linked roles.
- **RBAC Policies:** Define role-based access control (RBAC) policies and Kubernetes RBAC roles to grant granular permissions and privileges to users, groups, and service accounts for accessing, managing, and operating Kubernetes resources in Amazon EKS clusters.

### Application Deployment:
- **Deployments:** Deploy containerized applications to Amazon EKS clusters using Kubernetes Deployments, which manage replica sets, rolling updates, and lifecycle management of application pods, containers, and configurations.
- **Services:** Expose Kubernetes services as network endpoints for accessing application pods and services within Amazon EKS clusters using Kubernetes Services (e.g., ClusterIP, NodePort, LoadBalancer) for internal or external communication and load balancing.
- **Ingress Controllers:** Configure Kubernetes Ingress resources and ingress controllers (e.g., AWS ALB Ingress Controller, NGINX Ingress Controller) for routing external traffic, host-based routing, SSL termination, and application routing rules in Amazon EKS clusters.

### Monitoring and Logging:
- **CloudWatch Integration:** Integrate Amazon EKS clusters with Amazon CloudWatch for monitoring cluster metrics, logs, events, and alarms using CloudWatch Container Insights, CloudWatch Logs, and CloudWatch Events for operational visibility and insights.
- **Prometheus Integration:** Deploy Prometheus monitoring and alerting stack on Amazon EKS clusters for collecting, aggregating, and visualizing custom metrics, application metrics, and Kubernetes metrics using Prometheus Operator and Grafana dashboards.

### Autoscaling and HPA:
- **Cluster Autoscaler:** Enable cluster autoscaling for Amazon EKS clusters to automatically adjust the number of worker nodes based on CPU/memory utilization, pod scheduling, and pending pod requests to ensure optimal cluster capacity and resource availability.
- **Horizontal Pod Autoscaler (HPA):** Implement horizontal pod autoscaling in Amazon EKS clusters to automatically scale the number of application pods based on CPU/memory metrics, target utilization thresholds, and scaling policies defined in Kubernetes HPA objects.

### High Availability and Fault Tolerance:
- **Multi-AZ Deployment:** Deploy Amazon EKS clusters across multiple availability zones (AZs) for high availability, fault tolerance, and disaster recovery using multi-AZ networking, redundant control plane components, and distributed etcd clusters.
- **Node Termination Handling:** Configure node termination handlers, eviction policies, and pod disruption budgets (PDBs) in Amazon EKS clusters to gracefully handle EC2 instance terminations, node failures, and maintenance events without impacting application availability.

### CI/CD Integration:
- **GitOps Workflows:** Implement GitOps principles and practices for continuous integration and continuous delivery (CI/CD) pipelines on Amazon EKS clusters using Git repositories, version control, declarative configuration, and automated deployment with tools like Flux or Argo CD.
- **Container Registry Integration:** Integrate Amazon ECR (Elastic Container Registry) with Amazon EKS for storing, managing, and deploying container images, artifacts, and Docker containers in CI/CD pipelines, build processes, and development workflows.

### Cost Optimization:
- **Spot Instances:** Utilize EC2 Spot Instances for worker nodes in Amazon EKS clusters to reduce compute costs, leverage spare capacity, and achieve cost savings for non-critical, fault-tolerant, and batch processing workloads.
- **Reserved Instances:** Purchase EC2 Reserved Instances (RIs) or Savings Plans for predictable and sustained workloads running on Amazon EKS clusters to benefit from discounted pricing, cost predictability, and long-term savings on compute resources.
