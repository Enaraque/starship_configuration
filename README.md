# starship configuration
Starship configuration for warp.

After install Warp whe have to innstall starship with the following command:
``` curl -sS [https://starship.rs/install.sh](https://starship.rs/install.sh) | sh ```

When starship is install, next we have to do, is edit the ``` ~/.zshrc ``` adding this line to the end of the file:
``` eval "$(starship init zsh)" ```.

Once do that, we see that our warp prompt is quite different. Now we going to customize starship to look with a prettier style.

To do that we're going to modify two diferent file.
In one hand, there is ```starship.toml``` file which we have to add it in ```~/.config/``` path (like this: ~/.config/starship.toml). This one, is where we're going to customize the prompt of our warp terminal.
In other hand, there is ``` coolnight_configure``` folder which we have to add it in ``` ~/.warp/themes/``` path (like this: ```~/.warp/themes/coolnight_configure```). In this folder we'll find two files, one contains the different colors that will customize our
warp terminal and the other is the wallpaper of it. 


To end, when we have finished to configure starship, in Warp, go into Settings > Appearance, Theme, and type in “coolnight”. Click the theme that appears. 

If the propt doesn't shows the icons that we add in the ```starship.toml``, try to use other font like 'caskydiacCove'. This font can be download [here](https://www.nerdfonts.com/font-downloads).
