# Task-7-Configure-Load-Balancing-and-Auto-Scaling-for-a-Web-Application
To understand *scalability and fault tolerance* in cloud computing by setting up a *Load Balancer* and *Auto Scaling group* for a simple web application running on multiple virtual machines.

### I created a managed instance group using a startup script that hosts a simple Apache web page. Then, I configured a global HTTP load balancer to distribute traffic across the instances. Auto Scaling was enabled to maintain CPU utilization at 60%. During load tests, new instances were automatically created, proving that GCP can handle traffic spikes efficiently while ensuring high availability and cost optimization.

# MAIN CONCEPTS

### Load Balancing	: Distributes traffic across multiple servers to ensure availability and performance.

### Auto Scaling :	Automatically adds/removes VM instances based on demand (like CPU usage).

### Instance Template :	A blueprint for VM configuration used by instance groups.

### Managed Instance Group :	A group of identical VMs that can be scaled automatically.

### Health Check	: Periodic test to verify if a backend instance is healthy and responding.

### Scaling Policy :	Defines when to add or remove instances (e.g., CPU > 60%).

## Screenshots

- Backend Instances

- Apache2

- 2 Instances Active

- Load balancer

- Instance Groups

## ⚙️ Step-by-Step Implementation

### 1️⃣ Create a Basic Web App

### 2️⃣ Create a Startup Script (Automates Setup)

### 3️⃣ Create an Instance Template

### 4️⃣ Create a Managed Instance Group

### 5️⃣ Verify VM Instances

### 6️⃣ Create a Load Balancer

### 7️⃣ Configure the Backend

### 8️⃣ Configure the Frontend

### 9️⃣ Review and Create Load Balancer

### 🔟 Test the Load Balancer

### 1️⃣1️⃣ Test Auto Scaling

### 1️⃣2️⃣ Monitor and Clean Up

## Outcome

- By completing this task, I learned to:

- Set up a Load Balancer for multiple VMs

- Implement Auto Scaling for variable traffic

- Use Health Checks for reliability

- Understand scalable architecture design on GCP
