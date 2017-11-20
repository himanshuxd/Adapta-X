# Adapta-X [Ubuntu Version for Unity Enhancement of Buttons]
My Spin On The Adapta GTK Theme :

Adapta is a beautiful GTK+ Theme that I love. But Adapta generally comes with shitty Close/Minimize/Maximize buttons so I decided to hack it into something bearable. Adapta is one of those precompiled themes so it's not easy to tweak it through regular methods and you can break your Unity/Gnome setup by doing so but there is a workaround.

I love the OS-X style Control buttons so those would be good to have.

Result :

![Alt text](Screenshot from 2017-11-20 16-06-30.png?raw=tue "Adapta GTK+")


How to Get OS-X style Control Button's (Max Min Close) + Adapta Theme :

1) Use this to install Adapta Theme on your Ubuntu Desktop
```Bash
    sudo add-apt-repository ppa:tista/adapta
    sudo apt-get update
    sudo apt-get install adapta-gtk-theme
```

2) Head over to Unity-Tweak-Tool and apply Adapta Theme.

3) Copy `/usr/share/themes/Adapta` to `~/.themes`

4) Rename it as `Adaptax` so that now you have a folder `~/.themes/Adaptax`

5) Copy and Replace entire contents of downloaded folder Unity to `~/.themes/Adaptax/Unity`

6) Go Ahead to Unity-Tweak-Tool now there will be an Entry named Adaptax, click on it and exit, your old shabby Max/Min/Close buttons have been replaced with Modern OS-X style buttons.

The Original Adapta Theme is hosted at : https://github.com/adapta-project/adapta-gtk-theme be sure to check whether your distro is supported, and do support their efforts by starring their Repo.
