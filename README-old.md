# Adapta-X [Ubuntu Unity Version for OS-X style of Buttons]
My Spin On The Adapta GTK Theme :

Adapta is a beautiful GTK+ Theme that I love. But Adapta generally comes with shitty Close/Minimize/Maximize buttons so I decided to hack it into something more OS-X like. Adapta is one of those precompiled themes so it's not easy to tweak it through regular methods and you can break your Unity/Gnome setup by doing so but there is a workaround.

I love the OS-X style Control buttons so those would be good to have. Compare the Max/Min/Close in below Screenshots.

Adapta
![Alt text](https://raw.githubusercontent.com/himanshuxd/Adapta-X/master/Screenshot%20from%202017-11-20%2016-06-30.png "Adapta GTK+")

Adapta-X
![Alt text](https://raw.githubusercontent.com/himanshuxd/Adapta-X/master/Screenshot%20from%202017-11-20%2016-05-44.png "Adapta-X")



How to Get OS-X style Control Button's (Max/Min/Close) + Adapta Theme :

1) Use this to install Adapta Theme on your Ubuntu Desktop
```Bash
    sudo add-apt-repository ppa:tista/adapta
    sudo apt-get update
    sudo apt-get install adapta-gtk-theme
```

2) Head over to Unity-Tweak-Tool and apply Adapta Theme.

3) Copy `/usr/share/themes/Adapta` to `~/.themes`

```Bash
    cp -r /usr/share/themes/Adapta /home/$USER/.themes/xyz
```
4) Rename it as `Adaptax` so that now you have a folder `~/.themes/Adaptax`

```Bash
    mv /home/$USER/.themes/xyz /home/$USER/.themes/Adaptax
```

5) Copy and Replace entire contents of downloaded folder Unity to `~/.themes/Adaptax/Unity`

```Bash
    
```

6) Go Ahead to Unity-Tweak-Tool now there will be an Entry named Adaptax, click on it and exit, your old shabby Max/Min/Close buttons have been replaced with Modern OS-X style buttons.




Optional : For a windows 10 Icon instead of Default Unity Dash Icon Like :
![Alt text](https://raw.githubusercontent.com/himanshuxd/Adapta-X/master/Screenshot%20from%202017-11-20%2016-06-48.png "Unity Dash Changed")
Copy and Replace the file in Extra to `~/.themes/Adaptax/Unity`



How The New Firefox Quantum Looks (Firefox 57) :
![Alt text](https://raw.githubusercontent.com/himanshuxd/Adapta-X/master/Screenshot%20from%202017-11-20%2016-07-53.png "Fox")

![Alt text](https://raw.githubusercontent.com/himanshuxd/Adapta-X/master/Screenshot%20from%202017-11-20%2016-08-02.png "About")



The Original Adapta Theme is hosted at : https://github.com/adapta-project/adapta-gtk-theme be sure to check whether your distro is supported, and do support their efforts by starring their Repo.
