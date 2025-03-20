# SolanaLaunchToken
Docker file, combined with a Linux .sh executable to quicky have all tools at hand to launch Solana SPL-tokens

## Docker Installation
Docker is my favorite way to deploy pretty much anything. It’s available on all platforms and very easy to install.

- **Mac**: [Install Docker](https://docs.docker.com/desktop/setup/install/mac-install/)
- **Linux/Windows (WSL)**: [Install Docker](https://docs.docker.com/engine/install/)
- **Ubuntu**: [Install Docker on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)

## Clone This Repository and Build the docker container
Instead of manually setting up the Dockerfile, simply clone this repo and build the docker container:

```sh
git clone https://github.com/your-repo/solana-token.git
cd solana-token
chmod +x run.sh
chmod +x build.sh
./build.sh
```

---

## Run the container
It's time to run the container! By executing the ```run.sh``` file, the container will run and you will automatically navigate inside of the container. On exit the container will automatically dispose, and your files will be kept because of the mounted volumes.

```sh
./run.sh
```

[Guide on creating a Solana token](https://blog.networkchuck.com/posts/create-a-solana-token/)

