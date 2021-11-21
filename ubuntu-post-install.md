# OBLIGATORIO

1. REALIZAR ACTUALIZACIONES
2. Activar canonical partners
3. INSTALAR CODECDS
	- sudo add-apt-repository multiverse
	- sudo apt install ubuntu-restricted-extras
4. INSTALAR CODECS DE AUDIO
	- sudo apt-get install ffmpeg


# EXTRAS A ELEGIR

## PARA DESCARGAR MUSICA Y VIDEOS DE YOUTUBE

> choice one
- sudo curl -L https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -o /usr/local/bin/yt-dlp
- sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp

### default settings

- sudo chmod a+rx /usr/local/bin/yt-dlp


## PARA PERSONALIZAR LA TERMINAL
> GIT
- sudo apt-get install git

> ZSH
- sudo apt-get install zsh

> OH-MY-ZSH
- sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

    > PLUGINS PARA OH-MY-ZSH 
    ### zsh-syntax-highlighting
        - git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ### zsh-autosuggestions
        - git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ### COLORLS (colores para TERMINAL)
        - sudo apt-get install gem
        - sudo apt install ruby-full
        - sudo apt install ruby-dev gcc make
        - sudo gem install colorls

> PONER POR DEFECTO OH-MY-ZSH
- chsh -s $(which zsh)

> instalar PowerLevel10k
- git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

> Cambiar el tema y reiniciar la terminal para personalizar la terminal
- nano ~/.zshrc
    modificar: ZSH_THEME="powerlevel10k/powerlevel10k"

> CAMBIAR DE FUENTES A GUSTO
    - https://www.nerdfonts.com/font-downloads
