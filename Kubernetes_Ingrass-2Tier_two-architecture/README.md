📢 Exciting Project Showcase: Real-Time Chat App with Kubernetes Ingress on AWS! 🚀

I'm thrilled to share a comprehensive project I've just completed - a scalable, real-time chat application leveraging modern cloud-native technologies. This project demonstrates a robust two-tier architecture deployed on AWS using Kubernetes.

🔧 Tech Stack & Architecture:
• Frontend: React (containerized)
• Backend: Node.js with Socket.IO for real-time communication
• Containerization: Docker for consistent environments
• Orchestration: Kubernetes on Amazon EKS
• Container Registry: Amazon ECR
• DNS & Routing: ALB Ingress Controller
• SSL: Automated certificate management with cert-manager

🛠️ Key Tools & Technologies:
• Development: Visual Studio Code
• Kubernetes Management: kubectl, eksctl
• Cloud Interaction: AWS CLI
• Package Management: Helm
 
🔑 Key Features & Implementations:
• Scalable two-tier architecture separating frontend and backend
• Real-time bidirectional communication using WebSockets
• Efficient routing with Kubernetes Ingress and ALB
• Automated SSL certificate provisioning and renewal
• Containerized applications for consistency across environments
• Load balancing for high availability
• Continuous Integration and Deployment pipeline

⚙️ Notable Kubernetes Resources Used:
• Deployments for managing application replicas
• Services for internal communication
• Ingress for routing external traffic
• ClusterIssuer for automated SSL management

🔥 Highlighted Commands:
# Create EKS cluster
$eksctl create cluster --name chat-app-cluster --region us-east-1 --node-type t3.medium --nodes 2
# Apply Kubernetes configurations
$kubectl apply -f backend-deployment.yaml
$kubectl apply -f frontend-deployment.yaml
$kubectl apply -f ingress.yaml
# Install AWS Load Balancer Controller
helm install aws-load-balancer-controller eks/aws-load-balancer-controller -n kube-system --set clusterName=chat-app-cluster
# Install cert-manager
kubectl apply -f https://lnkd.in/dFXpvvsv

For more details ,checkout below links
🔗 GitHub Repo: https://lnkd.in/dm5hyXsK

📝 Full Tutorial: https://lnkd.in/d-m4c7cZ

I'm excited to discuss this project further! feel free to reach out. Let's connect and share knowledge! 💡


