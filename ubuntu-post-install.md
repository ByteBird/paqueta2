# OBLIGATORIO

#### 1. Realizar actualizaciones
#### 2. Activar canonical partners
#### 3. Instalar codecs de video
	- sudo add-apt-repository multiverse
	- sudo apt install ubuntu-restricted-extras
#### 4. Instalar codecs de audio
	- sudo apt-get install ffmpeg


# EXTRAS A ELEGIR

### Para descargar musica y videos de Youtube

#### Elije uno
	- sudo curl -L https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -o /usr/local/bin/yt-dlp
	- sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp

#### Para poder usar el yt-dlp
	- sudo chmod a+rx /usr/local/bin/yt-dlp


## Para personalizar la terminal
##### GIT
	- sudo apt-get install git

##### ZSH
	- sudo apt-get install zsh

##### OH-MY-ZSH
	- sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
##### PONER POR DEFECTO OH-MY-ZSH
	- chsh -s $(which zsh)
### PLUGINS PARA OH-MY-ZSH 
#### zsh-syntax-highlighting
	- git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
#### zsh-autosuggestions
	- git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
#### COLORLS (colores para TERMINAL)
	- sudo apt-get install gem
	- sudo apt install ruby-full
	- sudo apt install ruby-dev gcc make
	- sudo gem install colorls



#### Instalar PowerLevel10k
	- git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

#### Cambiar el tema y reiniciar la terminal para personalizar la terminal
	- nano ~/.zshrc
>Modificar: ZSH_THEME="powerlevel10k/powerlevel10k"**

#### CAMBIAR DE FUENTES A GUSTO
    - https://www.nerdfonts.com/font-downloads
