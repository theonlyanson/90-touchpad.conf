# i3wm-touchpad-gesture

###clone this project in /etc/X11/xorg.conf.d/


##Method 1:

Step 1: cd /etc/X11/xorg.conf.d/
Step 2: git clone https://github.com/theonlyanson/i3wm-touchpad-gesture.git


##Method 2:
sudo mkdir -p /etc/X11/xorg.conf.d && sudo tee <<'EOF' /etc/X11/xorg.conf.d/90-touchpad.conf 1> /dev/null

Now logout and login
