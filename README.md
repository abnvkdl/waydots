## My wayland configs

### Programs that I use   
Compositor `sway` `niri`
Launcher `tofi` `rofi`
Terminal `foot` `kitty`
Browser `firefox`   
Notifications `dunst` `mako`  
Text editor `vim` `neovim`
Video player `mpv`
Image-viewer `imv`   
Shell `zsh`   

To take screenshots I use `grim`, to take screenshot of a specific area I use `slurp`   
For recording screen I use `wf-recorder`   

`niri` has builtin screen recording.

For getting realtime network speed as a notification install `wireless_tools`

### To install starship to the current user   

`curl -O https://starship.rs/install.sh`   
`chmod +x install.sh`   
`./install.sh -b ~/.local/bin`   
Paste `starship init fish | source` at the end of `~/.config/fish/config.fish` file   



### Theming   
 
For my convenience I have stored papirus-icon-theme in .icons   
and papirus-folders script in `.local/bin/`   
You can use `nwg-look` program to change gtk specific themes and icons   

`vim` may show behave wrongly in the first time  
to fix this do `:PlugInstall` in vim to fix that

`nvim` shoud install plugins in first launch.
Additionally you could also install
`zoxide` the alternate cd
`fzf` command line fuzzy finder

***Things you may worth noting***   

Make the scripts in ~/.local/bin executable.   
Look into the purticular compositor/window manager config for keyboard shotcuts.
`super+return` launches terminal ig.

I use Arch btw.   

