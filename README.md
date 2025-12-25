# zsh and bash

My custom .bashrc file inspired by parrot os 

### Installing autin and ble.sh for bashrc

[https://docs.atuin.sh/guide/installation/](https://docs.atuin.sh/guide/installation/)
 - curl --proto '=https' --tlsv1.2 -LsSf https://setup.atuin.sh | sh
 - echo 'eval "$(atuin init bash)"' >> ~/.bashrc

[https://github.com/akinomyoga/ble.sh](https://github.com/akinomyoga/ble.sh)
 - curl -L https://github.com/akinomyoga/ble.sh/releases/download/nightly/ble-nightly.tar.xz | tar xJf -
 - bash ble-nightly/ble.sh --install ~/.local/share
 - echo 'source ~/.local/share/blesh/ble.sh' >> ~/.bashrc

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

sudo pacman -S python python-pip
sudo apt install python3 python3-pip

curl -fsSL https://pyenv.run | bash
