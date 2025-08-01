GeoDots edited for me
> [!NOTE]
> This will only work for Arch Linux Based distros (tested Arch, CachyOS, Endeavour). This MAY change in the future, no guarantees though.



### 🌟 INSTALLATION:


  ```
  bash <(curl -fsSL "https://geodearc.github.io/GeoDots/install.sh")
  ```
  <p></p>

  > If the above command doesnt work, you are likely using a non-standard shell (like fish). Try running this command instead (assumes bash is installed, install `bash` with pacman otherwise).

  ```
  bash -c "$(curl -fsSL https://geodearc.github.io/GeoDots/install.sh)"
  ```

</details> 
<details> 
  <summary>⌨ Manual(ish)</summary>

  <p></p>

  - 🗃️ Ensure dependencies & update
  ```
  sudo pacman -Syu
  sudo pacman -S --needed git base-devel
  ```
  - 💾 Begin Installation!
  > Needs to be in home folder for now! May make the script better/adaptive if i feel like it
  ```
  cd
  git clone https://github.com/GeodeArc/GeoDots/
  cd GeoDots
  ./install.sh
  ```
</details> 

<details> 
  <summary>🐧 Actually Manual</summary>

  <p></p>
    
  - 🗃️ Head over the the gh-pages branch, and install the dependencies in the text files labeled 'pkg'

  - 🔶 Go to each config folder in /.config/, and put a config (e.g light alt waybar, GTK hyprland.conf), and move it to the root of that config folder

  - 💾 Copy folders from /.config/ to your .config folder

  - 🏠 Copy the /Dots folder to your home directory
