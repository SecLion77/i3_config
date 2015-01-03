I3 Tiling WindowManager Setup
=============================

Configuration files for using the tiling I3 windowmanager.

Install
=======

See INSTALL file for configuration.

Put alle files in ~/.i3/

Configuration is based on:

- http://miek.nl/posts/2014/Mar/08/use-i3/
- https://mke21.wordpress.com/category/nerdy-linux/i3wm/
- http://feeding.cloud.geek.nz/posts/creating-a-modern-tiling-desktop-environment-using-i3/
- https://github.com/benkaiser/i3-wm-config
- http://blog.kaiserapps.com/2014/02/my-killer-i3-setup.htmlA

I3 with GNOME
=============

For using I3 with GNOME use the scripts in '.i3/gnome_install/'
and run : sudo make install.

To disable to bottom panel use dconf-editor (sudo apt-get install dconf-editor)
and adjust:

- org,gnome.gnome-panel.layout.object-id-list -> ['menu-bar', 'indicators']
- org,gnome.gnome-panel.layout.toplevel-id-list -> ['top-panel']

If the indicators are missing select the top-panel with ctl-window button and left-mouse-button and add the indicator panel.

See the following links for more info:

- http://blog.hugochinchilla.net/2013/03/using-gnome-3-with-i3-window-manager/
- https://github.com/lvillani/i3-gnome
