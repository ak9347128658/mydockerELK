```bash
#!/bin/bash
sudo apt-get update -y
sudo apt-get install -y docker.io
sudo systemctl enable docker
sudo systemctl start docker
sudo apt-get install -y docker-compose
cd /home/ubuntu
git clone https://github.com/your-repo/elk-stack.git
cd elk-stack
docker-compose up -d
```
