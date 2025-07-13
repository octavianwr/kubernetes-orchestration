# Kubernetes Orchestration

This project provides example Kubernetes YAML manifests for orchestrating deployments and pods. It is designed to help users understand and implement basic Kubernetes resource management using declarative configuration files.

## Project Structure

- `1-create-deployment.yaml`: Example manifest to create a Kubernetes Deployment.
- `2-create-pod.yaml`: Example manifest to create a standalone Pod.

## Usage

1. **Prerequisites:**
   - Kubernetes cluster (local or remote)
   - `kubectl` CLI installed and configured

2. **Apply the manifests:**
   - To create a deployment:
     ```sh
     kubectl apply -f 1-create-deployment.yaml
     ```
   - To create a pod:
     ```sh
     kubectl apply -f 2-create-pod.yaml
     ```

3. **Verify resources:**
   - List deployments:
     ```sh
     kubectl get deployments
     ```
   - List pods:
     ```sh
     kubectl get pods
     ```

## License

This project is licensed under the terms of the MIT License. See the `LICENSE` file for details.

