# *install ripgrep:*

sudo apt install ripgrep

# *install gcc:*

sudo apt update

sudo apt install build-essential

# *cfg ssh git:*
ssh-keygen -t ed25519 -C "seu-email@example.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_ed25519

cat ~/.ssh/id_ed25519.pub

# *link nvim:*
sudo ln -s /opt/nvim/nvim /usr/local/bin/nvim

# *install pynvim:*

sudo apt install unzip

sudo apt install python3-pynvim -y
