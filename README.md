# ansible-tasks

install docker + docker-compose on a fresh vm. Make sure to change inventory.yaml file in main directory accordingly.

Make sure ansible is installed first:
```
# make sure ~/.local/bin exists and is on your PATH
mkdir -p ~/.local/bin
echo 'PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
## install pip3
sudo apt install python3-pip -y
## install ansible with pip3
pip3 install --user ansible
# check that ansible has been installed
ansible --version
```
