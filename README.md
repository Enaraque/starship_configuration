# Starship Configuration
Starship configuration for warp.

After installing Warp we have to install starship using the following command:
``` curl -sS [https://starship.rs/install.sh](https://starship.rs/install.sh) | sh ```

Once starship is installed, the next step is edit the ``` ~/.zshrc ``` adding this line to the end of the file:
``` eval "$(starship init zsh)" ```.

After doing that, you will notice that our Warp prompt looks quite different. Now, let's customize Starship to have a prettier style.

To do that we'll modify two diferent files.

First, there is ```starship.toml``` file which needs to be added to the ```~/.config/``` path (e.g., ```~/.config/starship.toml```). This is where we will customize the prompt of our warp terminal.
Second, there is ```coolnight_configure``` folder which needs to be added to the ```~/.warp/themes/``` path (e.g., ```~/.warp/themes/coolnight_configure```). Inside this folder we'll find two files, one contains the different colors that will customize our
warp terminal and the other is the wallpaper fof it. 


Lastly, when we have finished configuring starship, go to Warp's Settings > Appearance, Theme, and type "coolnight". Then, click on the theme that appears.

If the propt doesn't display the icons that we added in the ```starship.toml```, try using  a different font like 'caskydiacCove'. This font can be download [here](https://www.nerdfonts.com/font-downloads).
