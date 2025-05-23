# Ubuntu-Version-22.04

## Requirements: 
- ⚙️ KVM Support.
- ⚙️ Docker Installed.

## Login Username and Password for VM:
- 👤 Username: root
- 🔑 Password: root

## Installation: 
```# Clone the Repository:
git clone https://github.com/NotRayy01/Ubuntu-Version-22.04

cd ubuntu22.04

# Build the Docker Image:
docker build -t ubuntu-vm

# Run the Container:

docker run --privileged -p 6080:6080 -p 2221:2222 -v $PWD/vmdata:/data ubuntu-vm```

