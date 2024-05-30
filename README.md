## Prerequisites
- [Docker Engine Installation](https://docs.docker.com/engine/install/)
- [Nvidia Drivers Installation](https://www.nvidia.com/Download/index.aspx?lang=en-us)
- [Nvidia Container Toolkit Installation](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)
- [Nvidia CUDA Toolkit Installation](https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html)

- Set data paths in .env

## Have Fun
```bash
cd docker/ollama
docker compose up -d
```

- UI http://localhost:3000

- Navigate to the UI, go into settings, download models

- API http://localhost:11434/api

## Used Projects
- [open webui](https://github.com/open-webui/open-webui)
- [ollama api](https://ollama.com/)