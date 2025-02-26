// hey so this is my 1st time on github so i will make the repo better later

// base sway took from mohammad https://github.com/MubinMuhammad/MinimalSwayFX

// took waybar from there https://github.com/Pipshag/dotfiles_nord

// this repo is just for me

this has wofi, oh-my-zsh,sway and waybar configs

// i dont claim any of those configs as my own bcs i may stole it from somewhere and forget
 make sure you have autism before using this

bindings:

bindsym $mod+Return exec $term
bindsym $mod+d exec wofi
bindsym $mod+q kill
bindsym $mod+Shift+c reload
bindsym $mod+Shift+e exec $HOME/.config/sway/exit_sway.sh
bindsym $mod+$left focus left
bindsym $mod+$down focus down
bindsym $mod+$up focus up
bindsym $mod+$right focus right
bindsym $mod+Left focus left
bindsym $mod+Down focus down
bindsym $mod+Print exec /home/sepi/.config/sway/scripts/screenshot.sh
bindsym $mod+Up focus up
bindsym $mod+Right focus right
bindsym $mod+Shift+$left move left
bindsym $mod+Shift+$down move down
bindsym $mod+Shift+$up move up
bindsym $mod+Shift+$right move right
bindsym $mod+Shift+Left move left
bindsym $mod+Shift+Down move down
bindsym $mod+Shift+Up move up
bindsym $mod+Shift+Right move right
bindsym $mod+1 workspace number 1
bindsym $mod+2 workspace number 2
bindsym $mod+3 workspace number 3
bindsym $mod+4 workspace number 4
bindsym $mod+5 workspace number 5
bindsym $mod+6 workspace number 6
bindsym $mod+7 workspace number 7
bindsym $mod+8 workspace number 8
bindsym $mod+9 workspace number 9
bindsym $mod+0 workspace number 10
bindsym $mod+Shift+1 move container to workspace number 1
bindsym $mod+Shift+2 move container to workspace number 2
bindsym $mod+Shift+3 move container to workspace number 3
bindsym $mod+Shift+4 move container to workspace number 4
bindsym $mod+Shift+5 move container to workspace number 5
bindsym $mod+Shift+6 move container to workspace number 6
bindsym $mod+Shift+7 move container to workspace number 7
bindsym $mod+Shift+8 move container to workspace number 8
bindsym $mod+Shift+9 move container to workspace number 9
bindsym $mod+Shift+0 move container to workspace number 10
bindsym $mod+Shift+v floating toggle
bindsym Print exec grim ~/Pictures/screenshot-$(date +'%Y-%m-%d_%H-%M-%S').png
bindsym $mod+b splith
bindsym $mod+Shift+Z swaymsg reload
bindsym $mod+v splitv
bindsym $mod+s layout stacking
bindsym $mod+w layout tabbed
bindsym $mod+e layout toggle split
bindsym $mod+f fullscreen
bindsym $mod+space focus mode_toggle
bindsym $mod+a focus parent
bindsym $mod+r mode "resize"
