
<details>

  ```
      1  ls
    2  cd Download
    3  cd Downloads/
    4  ls
    5  sudo whoami
    6  whoami
    7  sudo dpkg
    8  sudo dpkg -i google-chrome-stable_current_amd64.deb 
    9  sudo apt install neofetch
   10  neofetch
   11  cd 
   12  sudo apt install php8.3
   13  sudo apt update 
   14  sudo apt install
   15  sudo apt install php8.3
   16  sudo  apt-get install ca-certificates apt-transport-https software-properties-common
   17  sudo add-apt-repository ppa:ondrej/php
   18  sudo apt-get install php8.3
   19  php -v
   20  php -V
   21  php8.4 --version
   22  sudo apt install php8.3-cli
   23  sudo apt update
   24  sudo add-apt-repository ppa:ondrej/php
   25  sudo apt update
   26  sudo apt install php8.3 php8.3-cli php8.3-common php8.3-curl php8.3-mbstring php8.3-mysql php8.3-xml
   27  lsd b
   28  lsb_release -a
   29  sudo add-apt-repository ppa:ondrej/php
   30  sudo apt update
   31  sudo apt install php8.3
   32  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
   33  sudo apt install curl
   34  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
   35  \. "$HOME/.nvm/nvm.sh"~
   36  echo #Home
   37  echo $Home
   38  echo $HOME
   39  pwd
   40  ls
   41  ls -ll
   42  ls -lah
   43  cd .nvm
   44  ls
   45  ./nvm.sh
   46  sudo sh nvm.sh
   47  nvm install 22
   48  chmod 0777 nvm.sh
   49  ./nvm.sh
   50  nvm install 22
   51  # Download and install nvm:
   52  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
   53  # in lieu of restarting the shell
   54  \. "$HOME/.nvm/nvm.sh"
   55  # Download and install Node.js:
   56  nvm install 22
   57  # Verify the Node.js version:
   58  node -v # Should print "v22.17.1".
   59  nvm current # Should print "v22.17.1".
   60  # Verify npm version:
   61  npm -v # Should print "10.9.2".
   62  cd ..
   63  node -v
   64  php -v
   65  php --ini
   66  sudo apt install php8.3 php8.3-mysql php8.3-zip php8.3-mbstring php8.3-curl php8.3-gd php8.3-dev php8.3-intl php8.3-sqlite
   67  sudo apt install php8.3 php8.3-mysql php8.3-zip php8.3-mbstring php8.3-curl php8.3-gd php8.3-dev php8.3-intl php8.3-sqlite3
   68  sudo apt install php8.3 php8.3-mysql php8.3-mbstring php8.3-curl php8.3-gd php8.3-dev php8.3-intl php8.3-sqlite3
   69  sudo apt install php8.3 php8.3-mysql php8.3-mbstring php8.3-curl php8.3-gd php8.3-dev php8.3-sqlite3
   70  php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
   71  php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'.PHP_EOL; } else { echo 'Installer corrupt'.PHP_EOL; unlink('composer-setup.php'); exit(1); }"
   72  php composer-setup.php
   73  php -r "unlink('composer-setup.php');"
   74  ls
   75  cat composer.phar
   76  ls
   77  sudo mv composer.phar /usr/local/bin/composer
   78  composer
   79  mkdir dev
   80  cd dev
   81  mkdir trabalho
   82  cd trabalho
   83  git clone https://github.com/3pontos-tech/gil-benefits.git
   84  sudo apt install git
   85  git clone https://github.com/3pontos-tech/gil-benefits.git
   86  ls
   87  cd gil-benefits/
   88  source ~/.bashrc
   89  touch blabla
   90  ls
   91  git add .
   92  for pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done
   93  # Add Docker's official GPG key:
   94  sudo apt-get update
   95  sudo apt-get install ca-certificates curl
   96  sudo install -m 0755 -d /etc/apt/keyrings
   97  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
   98  sudo chmod a+r /etc/apt/keyrings/docker.asc
   99  # Add the repository to Apt sources:
  100  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  101    $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  102  sudo apt-get update
  103  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
  104  docker ps
  105  sudo service docker start
  106  sudo docker run hello-world
  107  docker ps
  108  sudo groupadd docker
  109  sudo usermod -aG docker $USER
  110  docker ps
  111  exit
  112  cd ..
  113  cd ~
  114  nano .bashrc
  115  source .bashrc
  116  docker ps
  117  docker run hello-world
  118  reboot
  119  docker ps
  120  htop
  121  sudo apt install htop
  122  htop
  123  btop
  124  sudo snap install btop
  125  btop
  126  curl https://raw.githubusercontent.com/jesseduffield/lazydocker/master/scripts/install_update_linux.sh | bash
  127  lazydocker
  128  ls
  129  source .bashrc
  130  lazydocker
  131  cd dev
  132  nano go.sh
  133  chmod
  134  chmod +x go.sh 
  135  ./go.sh
  136  cd ..
  137  source .bashrc
  138  go
  139  go install github.com/jesseduffield/lazydocker@latest
  140  lazydocker
  141  go env
  142  export PATH=${PATH}:go env GOPATH/bin
  143  export PATH=${PATH}: $(go env GOPATH)/bin
  144  ls
  145  cd go
  146  ls
  147  cd ..
  148  nano .bashrc
  149  source .bashrc
  150  nano .bashrc
  151  source .bashrc
  152  lazydocker 
  153  go install github.com/jesseduffield/lazygit@latest
  154  lazygit 
  155  ls
  156  cd dev
  157  ls
  158  cd trabalho
  159  ls
  160  cd gil-benefits/
  161  lazygit
  162  cd dev/trabalho/gil-benefits/
  163  lazygit
  164  history

```

</details>


## 🗓️ **Diário Técnico – Instalações e Configurações (24 de Julho de 2025)**

### 📌 **Resumo do que você aprendeu hoje:**

* Como instalar e configurar:

  * Google Chrome
  * PHP 8.3 com Composer
  * Node.js com NVM
  * Docker e docker-compose
  * Ferramentas de monitoramento: `neofetch`, `htop`, `btop`
  * Ferramentas visuais: `lazydocker` e `lazygit`
* Como adicionar repositórios e ajustar variáveis de ambiente no `.bashrc`
* Como criar estrutura de diretórios de trabalho e clonar repositórios Git


#### ✅ **1. Instalação do Google Chrome**

* Instalou o Google Chrome via pacote `.deb` usando:

  ```bash
  sudo dpkg -i google-chrome-stable_current_amd64.deb
  ```

#### ✅ **2. Personalização e informações do sistema**

* Instalou o **neofetch** para visualizar informações do sistema.

  ```bash
  sudo apt install neofetch
  neofetch
  ```

#### ✅ **3. Instalação do PHP 8.3**

* Adicionou o repositório do PHP (`ppa:ondrej/php`).
* Instalou o PHP 8.3 com os módulos principais:

  ```bash
  sudo apt install php8.3 php8.3-cli php8.3-mysql php8.3-mbstring php8.3-curl php8.3-xml php8.3-zip php8.3-gd php8.3-dev php8.3-intl php8.3-sqlite3
  ```
* Verificou a versão e configuração:

  ```bash
  php -v
  php --ini
  ```

#### ✅ **4. Instalou o Composer (gerenciador de dependências PHP)**

* Baixou, verificou hash, instalou e moveu para `/usr/local/bin`:

  ```bash
  php composer-setup.php
  sudo mv composer.phar /usr/local/bin/composer
  ```

#### ✅ **5. Instalou e configurou o NVM (Node Version Manager) + Node.js 22**

* Instalou o NVM e carregou no shell com:

  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
  \. "$HOME/.nvm/nvm.sh"
  ```
* Instalou o Node.js v22:

  ```bash
  nvm install 22
  node -v
  npm -v
  ```

#### ✅ **6. Instalou o Docker**

* Removeu possíveis pacotes antigos, adicionou chave GPG e repositório oficial:

  ```bash
  sudo apt-get install ca-certificates curl
  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
  echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  sudo apt-get update
  ```
* Instalou Docker + docker-compose plugin:

  ```bash
  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
  ```
* Testou execução:

  ```bash
  sudo docker run hello-world
  ```
* Adicionou seu usuário ao grupo `docker` para evitar usar `sudo`.

#### ✅ **7. Instalou ferramentas de monitoramento**

* Instalou `htop` e `btop`:

  ```bash
  sudo apt install htop
  sudo snap install btop
  ```

#### ✅ **8. Instalou ferramentas de interface para Docker e Git**

* Instalou o **Lazydocker**:

  ```bash
  curl https://raw.githubusercontent.com/jesseduffield/lazydocker/master/scripts/install_update_linux.sh | bash
  ```
* Instalou o **Lazygit** via `go install`:

  ```bash
  go install github.com/jesseduffield/lazygit@latest
  ```

#### ✅ **9. Configurações de ambiente Go**

* Tentou ajustar o `PATH` para incluir o `GOPATH/bin`, para rodar lazygit/lazydocker diretamente:

  ```bash
  export PATH=${PATH}:$(go env GOPATH)/bin
  ```
* Usou `nano` para editar e adicionar isso ao `.bashrc`.

#### ✅ **10. Organização de Projetos**

* Criou diretórios `dev/trabalho`, clonou repositório do GitHub:

  ```bash
  git clone https://github.com/3pontos-tech/gil-benefits.git
  ```

---
