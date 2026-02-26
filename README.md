# Hexlet ДЗ: Vagrant + Port Forwarding

## Multipass (M1)
multipass launch 24.04 --name vagrant-dev
multipass mount . vagrant-dev:/vagrant
./deploy.sh

## Тест
curl localhost:8080

