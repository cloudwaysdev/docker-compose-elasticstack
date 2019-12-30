sudo systemctl stop docker.service
sudo ip link del docker0
sudo systemctl start docker.service


