# Ecommerce
🚀 Excited to share my latest project on AKS! 🎉

Successfully deployed an E-Commerce Project on Azure Kubernetes Service (AKS) leveraging a three-tier architecture. 

Three-Tier Architecture:
1. Presentation Tier: It encompasses the user interface and communication layer, serving as the entry point for user interaction. 🖥️
2. Application Tier: At the core of the architecture, it processes data and executes business logic. ⚙️
3. Data Tier: Here, application data is stored and managed, ensuring persistence and accessibility. 🗃️

Microservice Architecture:
The E-Commerce Project consists of eight microservices:
1. User (Registration) - MongoDB 🧑‍💻
2. Catalogue 📚
3. Cart - MySQL 🛒
4. Payment 💳
5. Shipping 🚚
6. Dispatch 📦
7. Web (Nginx) 🌐
8. Redis (In-Memory Data Store) - Attached with Persistent Volume 🔄

Dockerization:
Each microservice was containerized using Docker. Docker files were meticulously crafted for each service, encapsulating dependencies and configurations. This ensures consistency and portability across different environments. 🐳

Exposure to End Users:
The application was exposed to end users through appropriate endpoints managed by Kubernetes services. Helm, a package manager for Kubernetes, streamlined the deployment process, allowing for easy distribution via Helm charts. 🚀
