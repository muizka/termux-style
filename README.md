# Termux Pro Style - Classic Theme

Repositori ini berisi konfigurasi tema Termux kustom menggunakan Zsh, Oh My Zsh, dan Powerlevel10k dengan gaya *Classic* yang rapi dan profesional.

## 🚀 Cara Instalasi Otomatis (One-Liner)

Buka Termux kamu, lalu salin dan tempel perintah di bawah ini. Perintah ini akan menginstal semua dependensi dan langsung menerapkan tema ini secara instan:

```bash
pkg update && pkg upgrade -y && pkg install git zsh curl figlet neofetch ruby -y && gem install lolcat && sh -c "$(curl -fsSL [https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh](https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh))" "" --unattended && git clone --depth=1 [https://github.com/romkatv/powerlevel10k.git](https://github.com/romkatv/powerlevel10k.git) ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k && curl -fsSL [https://raw.githubusercontent.com/muizka/termux-style/main/.zshrc](https://raw.githubusercontent.com/muizka/termux-style/main/.zshrc) -o ~/.zshrc && curl -fsSL [https://raw.githubusercontent.com/muizka/termux-style/main/.p10k.zsh](https://raw.githubusercontent.com/muizka/termux-style/main/.p10k.zsh) -o ~/.p10k.zsh && chsh -s zsh && zsh
