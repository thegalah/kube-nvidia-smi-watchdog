# Overview

kube-nvidia-smi-watchdog is a Kubernetes-based watchdog service designed to monitor NVIDIA GPU health within your cluster nodes. Utilizing NVIDIA's System Management Interface (nvidia-smi), this service continually checks the GPU status and restarts the node if the command does not return a status code of 0.

# Features

GPU Health Monitoring: Regularly checks NVIDIA GPU status using nvidia-smi.
Automatic Node Restart: Automatically restarts the host node if an anomaly or failure is detected.
Integration with Kubernetes: Seamlessly operates within a Kubernetes cluster, providing a robust solution for GPU-dependent applications.

# Prerequisites

Kubernetes cluster with NVIDIA GPU support.
Docker installed on the host node.

# Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

# License

This project is licensed under the MIT License.

# Support

For support, please contact the maintainer or open an issue in the repository.
