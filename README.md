<a id="top"></a>

<h1 align="center">Minimal Hyprland Configuration Version 2</h1>
<h3 align="center">By</h3>
<h2 align="center">Shell Ninja</h2>
<br>

This Hyprland configuration version is not for Dynamic Color Changing. It's a Theme based config, inspired by [HyDE](https://github.com/HyDE-Project/HyDE), but with 'easy to navigate' file structure.

<div align="center">

<br>

<!-- <a href="#screenshots"><kbd> <br> Screenshots <br> </kbd></a>&ensp;&ensp; -->

<a href="#setup"><kbd> <br> Setup <br> </kbd></a>&ensp;&ensp;

<!-- <a href="#update"><kbd> <br> Update <br> </kbd></a>&ensp;&ensp; -->

<a href="#config"><kbd> <br> Configuration <br> </kbd></a>&ensp;&ensp;
<a href="#keyboards"><kbd> <br> keyboard Shortcuts <br> </kbd></a>&ensp;&ensp;

<!-- <a href="#last"><kbd> <br> Last Modified <br> </kbd></a>&ensp;&ensp; -->

<a href="#contrib"><kbd> <br> Contrubution <br> </kbd></a>&ensp;&ensp;
<a href="https://github.com/shell-ninja/hyprconf/wiki"><kbd> <br> Wiki <br> </kbd></a>

</div>

> [!CAUTION]
> Currently, taking screenshot of an area is creating a little problem. It suspends the script and I have no idea why it is happening. As soon as I fix it, I'll update it here. For now, only full screen screenshot is available.

> [!NOTE]
> This is a rolling release configuration. It means, I often make changes, fix bugs and add features. If you want to update to the latest changes, just use this keyboard shortcut to update: `SUPER Shift + U`

<br>

<!-- ######################## ScreenShot Section ############################### -->

<!---->
<!-- <div align="right"> -->
<!--   <br> -->
<!--   <a href="#top"><kbd> <br> 🡅 <br> </kbd></a> -->
<!-- </div> -->
<!---->
<!-- <a id="screenshots"></a> -->
<!---->
<!-- ## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=SCREENSHOTS" width="450"/> -->
<!---->
<!-- <details close> -->
<!-- <summary>Overall</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/1.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/2.png?raw=true" /> <br> -->
<!---->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/3.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/4.png?raw=true" /> -->
<!---->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/5.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/theme/6.png?raw=true" /> -->
<!-- </p> <br> -->
<!-- </details> -->
<!---->
<!-- <details close> -->
<!-- <summary>Menu</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/menu/1.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/menu/2.png?raw=true" /> <br> -->
<!---->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/menu/4.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/menu/3.png?raw=true" /> -->
<!--     <br> -->
<!---->
<!--    <img aligh="center" width="99%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/clipboard.png?raw=true" /> -->
<!-- </p> <br> -->
<!-- </details> -->
<!---->
<!-- <details close> -->
<!-- <summary>Power Menu</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/power/1.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/power/2.png?raw=true" /> <br> -->
<!---->
<!--    <img aligh="center" width="99%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/power/3.png?raw=true" /> -->
<!-- </p> <br> -->
<!-- </details> -->
<!---->
<!-- <details close> -->
<!-- <summary>Wallpaper</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/wallpaper/1.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/wallpaper/2.png?raw=true" /> <br> -->
<!---->
<!--    <img aligh="center" width="99%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/wallpaper/3.png?raw=true" /> -->
<!-- </p> <br> -->
<!-- </details> -->
<!---->
<!-- <details close> -->
<!-- <summary>Lock Screen</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/lockscreen/lock-1.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/lockscreen/lock-2.png?raw=true" /> -->
<!--         <br> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/lockscreen/lock-3.png?raw=true" /> -->
<!--    <img aligh="center" width="49%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/lockscreen/selecttheme.png?raw=true" /> -->
<!-- </p> -->
<!-- </details> -->
<!---->
<!-- <details close> -->
<!-- <summary>Login Screen (sddm)</summary> -->
<!-- <p align="center"> -->
<!--    <img aligh="center" width="99%" src="https://github.com/shell-ninja/Screen-Shots/blob/main/hyprconf/sddm/sddm_theme.jpg?raw=true" /> -->
<!-- </p> -->
<!-- </details> -->

<!-- ######################## ScreenShot Section ############################### -->

<br>

<div align="right">
  <br>
  <a href="#top"><kbd> <br> 🡅 <br> </kbd></a>
</div>

<a id="features"></a>

## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=FEATURES" width="450"/>

- Similar to my [hyprconf](https://github.com/shell-ninja/hyprconf) setup, but it's not has the dynamic color changing feature. I has colors palets based on some popular themes

<br>

<a id="config"></a>

<div align="right">
  <br>
  <a href="#top"><kbd> <br> 🡅 <br> </kbd></a>
</div>

> [!TIP]
>
> ### Hyprland
>
> To configure hyprland settings, you can visit to `~/.config/hypr` directory. Inside it, you will fine `configs` dir, holding all the configuration files; `scripts` dir for all the scripts.
> Wallpapers are stored in the `~/.config/hypr/Wallpapers/__theme_name/` directory. Just copy your favourite wallpapers into this directory.
>
> ### Rofi
>
> All the Rofi configs are inside the `~/.config/rofi` dir. Inside this, you will find <i>menu</i>, <i>power_option</i> and <i>theme</i> dir. Inside each directory, all the necessary configs are available.
>
> ### Waybar
>
> Visit to `~/.config/waybar` directory.
> You will fine <i>configs</i> dir holding all the configurations.
> A <i>style</i> dir holding all the <b>css</b> files.
> A <i>moduled</i> dir for all the modules.
>
> ### Fastfetch
>
> Fastfetch config files will be stored in your `~/.local/share/fastfetch` directory.
> Visit there and change the presets according to your need.
> If you haven't choose from the shells while running the installation script, just add these lines in your <b>`.bashrc, .zshrc or config.fish`</b> configs. <br><b> `fastfetch --config hypr` </b><br> <b>hypr</b> is the preset name. You will find presets inside your `~/.local/share/fastfetch/presets` directory

<br>

<a id="setup"></a>

<div align="right">
  <br>
  <a href="#top"><kbd> <br> 🡅 <br> </kbd></a>
</div>

## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=SETUP" width="450"/>

<h4>To install and setup this hyprland configuration automaticly, just follow these stpes...</h4>

- Clone this Repository

```shell
   git clone --depth=1 https://github.com/shell-ninja/hyprconf-v2.git
```

- Now run this commands:

```shell
  cd ~/hyprconf-v2
  chmod +x hyprconf-v2.sh
  ./hyprconf-v2.sh
```

<br>

<!-- <a id="update"></a> -->
<!---->
<!-- <div align="right"> -->
<!--   <br> -->
<!--   <a href="#top"><kbd> <br> 🡅 <br> </kbd></a> -->
<!-- </div> -->
<!---->
<!-- ## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=UPDATE" width="450"/> -->
<!---->
<!-- <h4>To Update into the latest commit. jusr run this command in your tarminal..</h4> -->
<!---->
<!-- ```shell -->
<!-- bash -c "$(wget -q  https://raw.githubusercontent.com/shell-ninja/hyprconf/main/update.sh -O -)" -->
<!-- ``` -->

<!-- ## -----------(O_O)----------- -->
<!---->
<!-- #### Well if you want to automate the required packages installation process and setup this config automaticly. then you should visit [This Repository](https://github.com/shell-ninja/hyprconf-install.git). I will automate the process for you. -->
<!---->
<!-- <br> -->

<br>

<a id="keyboards"></a>

<div align="right">
  <br>
  <a href="#top"><kbd> <br> 🡅 <br> </kbd></a>
</div>

## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=KEYBOARD-SHORTCUTS" width="450"/>

> [!IMPORTANT]
>
> After installation, just press the `SUPER + Shift + h`. It will show you all the keybinds.

<br>

<!-- <a id="last"></a> -->
<!---->
<!-- <div align="right"> -->
<!--   <br> -->
<!--   <a href="#top"><kbd> <br> 🡅 <br> </kbd></a> -->
<!-- </div> -->
<!---->
<!-- ## Check the last modifications [here](https://github.com/shell-ninja/hyprconf/blob/main/UPDATES.md) -->
<!---->
<!-- <br> -->

<a id="contrib"></a>

<div align="right">
  <br>
  <a href="#top"><kbd> <br> 🡅 <br> </kbd></a>
</div>

## <img src="https://readme-typing-svg.herokuapp.com?font=Lexend+Giga&size=25&pause=1000&color=90EE90&vCenter=true&width=435&height=25&lines=CONTRIBUTING" width="450"/>

<h4> If you want to add your ideas in this project, just do some steps. </h4>

1. Fork this repository. Make sure to uncheck the `Copy the main branch only`. This will also copy other branches ( if available ).
2. Now clone the forked repository in you machine. <br> Example command:

```shell
git clone --depth=1 --branch=development https://github.com/your_user_name/hyprconf.git
```

3. Create a branch by your user_name. <br> Example command:

```shell
git checkout -b your_user_name
```

4. Now add your ideas and commit to github. <br> Make sure to commit with a detailed test message. For example:

```shell
git commit -m "fix: Fixed a but in the "example.sh script"
```

```shell
git commit -m "add: Added this feature. This will happen if the user do this."
```

```shell
git commit -m "delete: Deleted this. It was creating this example problem"
```

4. While pushing the new commits, make sure to push it to your branch. <br> For example:

```shell
git push origin your_branch_name
```

5. Now you can create a pull request in the main repository.<br> But make sure to create the pull request in the `development` branch, no the `main` branch.

## Reference

#### I would like to thank [JaKooLit](https://github.com/JaKooLit). I was inspired from his Hyprland installation scripts and prepared my script. I took and modified some of his scripts and used here.
