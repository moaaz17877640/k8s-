#k8s-recap-tests


## Overview
This project involves deploying and managing a Node.js application using Kubernetes. The Docker image node is exposed on port 3000. If you need to edit ports in the deployment and service, rebuild the image to expose another port.

## Folder Structure
- **k8s-service**: Contains deployment and service configurations for Kubernetes.

## Getting Started
### Prerequisites
- Docker
- Kubernetes

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/moaaz17877640/k8s-.git
   cd k8s-
   ```

### Running the Application
1. Build the Docker image:
   ```
   docker build -t your-image-name .
   ```

2. Deploy to Kubernetes:
   ```
   kubectl apply -f k8s-service/
   ```

3. Access the application on port 3000.

### Configuration
To change the port, modify the deployment and service files in the `k8s-service` folder and rebuild the Docker image.

## Contributing
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.


Feel free to add more specific details or sections as needed.
