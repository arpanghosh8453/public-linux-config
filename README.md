## Sources

-   **Linux distro tryout**: [https://www.onworks.net/](https://www.onworks.net/)
    

  

-   **Useful Packages**: [links collection](https://github.com/rothgar/awesome-tuis) and [sorted list](https://github.com/ibraheemdev/modern-unix)
    


-   **Docker container configurations**: [Check here](https://github.com/arpanghosh8453/public-docker-config)



-   **Test out docker containers online**: [Here](https://labs.play-with-docker.com/)

-   **Proxmox helper scripts**: [Here](https://tteck.github.io/Proxmox/)
  

##  Essential
    


-   [Zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH) : Better version of bash shell
    
-   [Oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) : zsh plugin manager
```bash
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
    
-   [Powerlevel10k](https://github.com/romkatv/powerlevel10k) : Awesome zsh prompt theme
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
    
-   [Zsh-z](https://github.com/agkozak/zsh-z) : directory jumping
```bash
git clone https://github.com/agkozak/zsh-z ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z
```
    
-   [Zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) : 
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
    
-   [Zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete) : 
```bash
git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autocomplete
```
    
-   [Neovim](https://github.com/neovim/neovim) : Best CLI Text editor [apt]
```bash
sudo add-apt-repository ppa:neovim-ppa/unstable && sudo apt-get update && sudo apt-get install neovim
```

-   [NvChad](https://github.com/NvChad/NvChad) : Customized neovim [bob]
```bash
git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```
    
-   [vim-plug](https://github.com/junegunn/vim-plug) : neovim plugin panager
```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
-   [Docker](https://docs.docker.com/get-docker/) : Running services within containers
```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
```
-   [Docker-compose](https://docs.docker.com/compose/) : Running docker with yaml files
```bash
sudo apt-get remove docker-compose; VERSION=$(curl --silent https://api.github.com/repos/docker/compose/releases/latest | grep -Po '"tag_name": "\K.*\d') && DESTINATION=/usr/local/bin/docker-compose && sudo curl -L https://github.com/docker/compose/releases/download/${VERSION}/docker-compose-$(uname -s)-$(uname -m) -o $DESTINATION && sudo chmod 755 $DESTINATION
```

-   [Speedtest](https://www.speedtest.net/apps/cli) : Internet speed testing CLI
```bash
sudo apt-get remove speedtest-cli ; curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash && sudo apt-get update && sudo apt-get install speedtest
```

-   [Tailscale](https://tailscale.com/download/linux/rpi): For Tailnet connection among self devices over the internet
    
-   [Bat](https://github.com/sharkdp/bat): Better cat functionality
    
-   [Fzf](https://github.com/junegunn/fzf): fuzzy search
    
-   [Tmux](https://github.com/tmux/tmux/wiki): Better terminal, with multi-device session restore support [apt]
    
-   [Ripgrep](https://github.com/BurntSushi/ripgrep): more efficient than grep [apt]
    
-   [Lsd](https://github.com/Peltoche/lsd)  or [Exa](https://github.com/ogham/exa): better ls functionality
    
-   [Duf](https://github.com/muesli/duf): Better disk space analysis ( df )
    
-   [Ranger](https://github.com/ranger/ranger) or [Browsr](https://github.com/juftin/browsr): File browser and content preview [apt]
    
-   [Ncdu](https://dev.yorhel.nl/ncdu) or [dua](https://github.com/Byron/dua-cli/releases) or [Dust](https://github.com/bootandy/dust) : disk usage utility | dua<Dust=ncdu
    
-   [Git](https://git-scm.com/download/linux) : for git clone
    
-   [Btop](https://github.com/aristocratos/btop) & [Bottom](https://github.com/clementtsang/bottom) : better than top and htop : system viewer
    
-   [Nala](https://gitlab.com/volian/nala/) : Package manager ( Better version of apt )
    
-   [Navi](https://github.com/denisidoro/navi) : a cheatsheet manager
    
-   [Pueue](https://github.com/Nukesor/pueue) : Background parallel task manager
    
-   [Fd](https://github.com/sharkdp/fd) : Uset friendly alternative to find command
    
-   [Thefuck](https://github.com/nvbn/thefuck) : corrects errors in previous console commands with [zsh plugin](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/thefuck/README.md)

-   [Lnav](https://github.com/tstack/lnav) or [Toolong](https://github.com/Textualize/toolong) : Terminal log file navigator
    
-   [Lazydocker](https://github.com/jesseduffield/lazydocker)  : Docker container TUI
    
-   [Ctop](https://github.com/bcicen/ctop) : top like interface for docker containers
    
-   [Lazygit](https://github.com/jesseduffield/lazygit) : Git TUI

-   [Deb-get](https://github.com/wimpysworld/deb-get) : for easy instralling and updating 3rd party .deb packages

-   [tre](https://github.com/dduan/tre) : For directory tree generator

-   [hyperfine](https://github.com/sharkdp/hyperfine) : For comparing command runtime (benchmarking)

-   [atuin](https://atuin.sh) : For database driven history search

-   [httpie](https://httpie.io/cli) : Better curl or wget

-   [Czkawka](https://github.com/qarmin/czkawka) : File duplication finder
  
-   [jq](https://github.com/jqlang/jq) : Command line JSON processor
  

## Optional
    

  
-   [Lynis](https://github.com/CISOfy/lynis) : Security auditing tool for Linux

-   Cockpit: web console for raspberry pi
    
-   Glances: for system data collection
    
-   [Cloudflare](https://dev.to/omarcloud20/a-free-cloudflare-tunnel-running-on-a-raspberry-pi-1jid)  : For internet tunneling and remote usage
    
-   Bash-snippets:  [https://github.com/alexanderepstein/Bash-Snippets](https://github.com/alexanderepstein/Bash-Snippets)
    
-   [Visidata](https://github.com/saulpw/visidata): csv file reader and manipulator in commandline
    
-   Rsync: copy and sync files utility
    
-   [Cowsay:](https://opensource.com/article/18/12/linux-toy-cowsay) Cows says text [apt]
    
-   [Curl](https://curl.se/): request and download from internet [apt]
    
-   [FFmpeg](https://ffmpeg.org/): CLI video management [apt]
    
-   [Figlet](https://ubunlog.com/en/figlet-banners-ascii-terminal/#:~:text=install%20figlet%20toilet-,Using%20FIGlet,to%20select%20the%20font%20directory.): for ASCII text art [apt]
    
-   [Imagemagick](https://imagemagick.org/index.php): CLI image manipulations [apt]
    
-   [Flameshot](https://flameshot.org/): Screenshot utility
    
-   Hollywood: fancy hacker screen
    
-   [Lolcat](https://github.com/busyloop/lolcat): Colored output from other commands [apt]
    
-   [Micro](https://micro-editor.github.io/): simple text editor on terminal [apt]
    
-   [Neofetch](https://github.com/dylanaraps/neofetch): system details viewer on terminal [apt]
    
-   [Moc](https://github.com/jonsafari/mocp) : Music player on console [apt]
    
-   Xclip : X-11 based clipboard management
    
-   [No-more-secrets](https://github.com/bartobri/no-more-secrets) : fancy encrypted text effect on terminal
    
-   Protonvpn-cli : Vpn service
    
-   [Synaptic package manager](https://itsfoss.com/synaptic-package-manager/) : Package manager
    
-   [Fsearch](https://github.com/cboxdoerfer/fsearch): GUI search utility
    
-   [Pensor](https://www.tecmint.com/psensor-monitors-hardware-temperature-in-linux/): Sensors data collection
    
-   [Copyq](https://hluk.github.io/CopyQ/): GUI clipboard manager
    
-   [ddTerm](https://extensions.gnome.org/extension/3780/ddterm/) : collapsible terminal - Gnome shell extention
    
-   [Qalc](https://installati.one/ubuntu/21.04/qalc/) : Easy unit conversions and mathematical operations on terminal [apt]
    
-   [Httpie](https://github.com/httpie/httpie) : [User friendly interaction](https://httpie.io/docs/cli/examples) with HTTP servers and APIs from the terminal

-   [Gping](https://github.com/orf/gping) : ping with a graph TUI

-   [Cronitor-cli](https://github.com/cronitorio/cronitor-cli) or [Healthchecks](https://healthchecks.io/): Effective cronjob testing and monitoring

-   [Motion](https://github.com/Motion-Project/motion) : easy to setup webcam livestream server 

    <details>
        <summary>configuration parameters in /etc/motion/motion.conf file</summary>
    
        stream_quality 80
        stream_maxrate 5
        stream_port <your_port>
        stream_localhost off
        output_pictures off
        framerate 5
        ffmpeg_video_codec mpeg4
        width 640
        height 480
        auto_brightness off
        contrast 0
        saturation 0
        stream_auth_method 1
        stream_authentication <any_username>:<any_password>                   
    
    </details>
    
 -   [Rmlint](https://github.com/sahib/rmlint) : Detect and remove duplicate/empty files/directories 
 
 -   [Rclone](https://github.com/rclone/rclone) : sync files and directories to and from different cloud storage providers
 
 -   [Nfty](https://github.com/dschep/ntfy) : A utility for sending push notifications to phone or desktop on demand and when commands finish
 
 -   [Pdd](https://github.com/jarun/pdd) : Calculates date and time difference. Also works as a timer and stopwatch. Can be installed directly with apt package manager
 
 -   [Grc](https://github.com/garabik/grc) and [Colortail](https://github.com/joakim666/colortail) : command line utility with colorized text output [ stdout, stderr, file contents, ping, ps, logfile ]
