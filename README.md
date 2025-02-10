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
