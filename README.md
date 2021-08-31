## Check python on Ubuntu
Logado no seu servidor Ubuntu, como um usuário sudo não-root, primeiro atualize seu sistema para garantir que sua versão enviada do Python 3 está em dia.

sudo apt update
sudo apt -y upgrade

## Instaling PIP
sudo apt install -y python3-pip

## Instaling venv
sudo apt install -y python3-venv

- Criar virtual env
python3.8 -m venv env

- Ativar virtual env
source env/bin/activate