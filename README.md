## My wayland configs

### Programs that I use   
Compositor `sway`   
Launcher `tofi`   
Terminal `foot`   
Browser `firefox`   
Notifications `dunst`   
Text editor `vim`   
Video player `mpv`   
Image-viewer `imv`   
Shell `zsh`   

To take screenshots I use `grim`, to take screenshot of a specific area I use `slurp`   
For recording screen I use `wf-recorder`   

For getting realtime network speed as a notification install `wireless_tools`

### To install starship to the current user   

`curl -O https://starship.rs/install.sh`   
`chmod +x install.sh`   
`./install.sh -b ~/.local/bin`   
Paste `starship init fish | source` at the end of `~/.config/fish/config.fish` file   

### Theming   

I use catppuccin mocha lavender theme throughout. Papirus icons for icons theme.   
I also use papirus-folder script to change papirus folder colors.   
For my convenience I have stored papirus-icon-theme in .icons   
and papirus-folders script in `.local/bin/`   
You can use `nwg-look` program to change gtk specific themes and icons   

vim may show behave wrongly in the first time  
to fix this do `:PlugInstall` in vim to fix that


***Things you may worth noting***   

Make the scripts in ~/.local/bin executable.   
`super + Return` launches terminal   
`super + p` launches powermenu   
`super + s` launches tofi   
`super + x` to close a program    
`Print` shows the screenshot menu   

Check sway config file for all the keybindings   

The font I use is Maple Mono.   

I use Arch btw.   

