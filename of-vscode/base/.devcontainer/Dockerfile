# Start from the official devcontainers base image
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Use a non-interactive frontend for package installs
ARG DEBIAN_FRONTEND=noninteractive

# Update the package list and install git
# --no-install-recommends reduces the image size
RUN apt-get update && apt-get -y install --no-install-recommends git

# Clean up the apt cache to save space
RUN apt-get clean && rm -rf /var/lib/apt/lists/*