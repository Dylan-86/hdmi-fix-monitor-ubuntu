# hdmi-fix-monitor-ubuntu
fix ubuntu HDMI external monitors and displays when they don't work


Open terminal and run


xrandr --newmode "1920x1080_50.00"  141.50  1920 2032 2232 2544  1080 1083 1088 1114 -hsync +vsync
xrandr --addmode HDMI-1 "1920x1080_50.00"
xrandr --output HDMI-1 --mode "1920x1080_50.00"
