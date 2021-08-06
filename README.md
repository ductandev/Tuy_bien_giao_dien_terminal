# Tùy Biến giao diện terminal
**Những links liên quan :**
- **Theme:**
- Dracula: https://draculatheme.com/gnome-terminal
- One Dark: https://github.com/denysdovhan/one-gn...
- Nord: https://github.com/arcticicestudio/no...
- Powerlevel10k: https://github.com/romkatv/powerlevel10k
- Nerd Fonts: https://github.com/ryanoasis/nerd-fon...
- Dark-flat: https://github.com/QuentinWatt/dark-flat-iterm-colors
- Gogh: https://github.com/Mayccoll/Gogh **hoặc** https://mayccoll.github.io/Gogh/
- ohmyzsh: https://github.com/ohmyzsh/ohmyzsh
- **Video hướng dẫn** https://www.youtube.com/watch?v=8rAYABZChkQ

# 1. Tải nerd-fonts cho ubuntu
- **Tải về** https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/UbuntuMono.zip \
Sau đó nhấp đúp vào file đã tải và chọn 4 font như hình dưới rồi nhấn ![image](https://user-images.githubusercontent.com/42485856/128306160-53737dec-83e0-4387-94cc-ad471bcae349.png) 

![image](https://user-images.githubusercontent.com/42485856/128305797-e8ce1b11-6a3c-4bf1-b1a0-2d452005ff11.png) \
Mở **"Terminal"** chọn ![image](https://user-images.githubusercontent.com/42485856/128304713-72938258-e650-4284-b9d1-47b920f4037e.png) --> chọn ![image](https://user-images.githubusercontent.com/42485856/128304968-4a889bff-6810-4676-a556-ba6514dd0b8c.png)--> tạo Profiles tên Dracula ![image](https://user-images.githubusercontent.com/42485856/128305336-d84ec592-6a60-4b6f-a4e4-c1acb167c80a.png) \
![image](https://user-images.githubusercontent.com/42485856/128304211-7770f3ad-90a3-41e4-a57a-41efd3e38c93.png) \
Tích vào ô 
- [x] **Custom font** và chọn font như hình và chọn **Selected**  \
![image](https://user-images.githubusercontent.com/42485856/128306493-864c3839-2725-4f79-8f29-92a16128e388.png)

Sau đó --> chọn them **Dracula** và chọn --> **"Set as default"**


# 2. Cài đặt theme Dracula
### Trang chủ Daracula https://draculatheme.com --> còn nhiều thứ hấp dẫn ở đây
Link cài đặt : https://draculatheme.com/gnome-terminal
```
$ sudo apt-get install dconf-cli
$ git clone https://github.com/dracula/gnome-terminal
$ cd gnome-terminal
$ ./install.sh
$ 1
$ 1
$ yes
$ 2
```
**Tùy chỉnh màu** \
![image](https://user-images.githubusercontent.com/42485856/128316103-4d335361-8ca7-4f48-a52a-854380869cb1.png)

# 3. Cài đặt zsh
- **ohmyzsh:** https://github.com/ohmyzsh/ohmyzsh
- **Hướng dẫn** https://tecadmin.net/how-to-install-zsh-on-ubuntu-20-04/
```
$ sudo apt install zsh
```
Chuyển đổi qua zsh (bước này nếu muốn về terminal cũ ban đầu thì thực hiện bước này và đổi **zsh** thành **bash**)
```
$ chsh -s  /bin/zsh
$ zsh
```
có thể chuyển qua lại bash(terminal như cũ) và zsh( mới) bằng 2 lệnh sau
```
$ bash
$ zsh
```

sau đó **"Log out"** và mở lại **Terminal** và chọn **2**
```
$ 2
```
**cách xóa zsh** \
For unistall zsh from Ubuntu 20.04 LTS
```
$ sudo apt-get --purge remove zsh
$ sudo apt autoremove
```

# 4. Cài Powerlevel10k
Powerlevel10k: https://github.com/romkatv/powerlevel10k
```
$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
$ echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
$ zsh
```
Muốn tùy biến custom sang một loại khác sữ dụng lệnh 
```
$ p10k configure
```
# 5. Tùy chỉnh chuyển theme hoặc một số thức khác
```
$ nano ~/.zshrc
$ nano ~/.p10k.zsh
```

**Kết quả:** \
![image](https://user-images.githubusercontent.com/42485856/128347392-8cde5cf8-fea0-491d-9ca1-791fe33ac8ec.png)

