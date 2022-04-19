```conf
## Copyright (C) 2008-2022 Sazumi Viki <hi@sazumiviki.com>
## Everyone is permitted to copy and distribute copies of this file under GNU-GPL3

#========================= Corners =========================#

corner-radius = 8;
rounded-corners-exclude = [
#	"window_type = 'normal'",
	"class_g ?= 'rofi'",
	"class_g ?= 'polybar'",
	"class_g ?= 'tint2'"
];

round-borders = 0;
round-borders-exclude = [
	"class_g = 'TelegramDesktop'"
];

# Specify a list of border width rules, in the format `PIXELS:PATTERN`, 
# Note we don't make any guarantee about possible conflicts with the
# border_width set by the window manager.
#
# example:
#    round-borders-rule = [ "2:class_g = 'URxvt'" ];
#
round-borders-rule = [
	"2:class_g ?= 'URxvt'",
	"2:class_g ?= 'Alacritty'",
	"0:class_g ?= 'firefox'"
];
```
<a href="https://cdn.jsdelivr.net/gh/SazumiVicky/Picom-Config-@main/picom.conf">View More</a>
