<h1>Stuff for my i3 config</h1>

<strong>Fake dirty screenies as an example:</strong>
<a href="http://imgur.com/LPpoNXk"><img src="http://i.imgur.com/LPpoNXk.png" title="source: imgur.com" /></a>
<a href="http://imgur.com/MJSHxye"><img src="http://i.imgur.com/MJSHxye.png" title="source: imgur.com" /></a>

<br>
<br>
<strong>Descripton:</strong>
<p>This i3 theme was designed to fit around the background image. It is under constant development for small tweeks that I want to make as they appear. See the "todo" list to view the current tweeks that I'm planning to make. 

<br>
<strong>Required Packages (Interdependent packages not listed):</strong>
<ul>
<li>imagemagic
<li>compton
<li>i3-gaps
<li>xrdb
<li>i3blocks
<li>pamixer
<li>i3lock
<li>feh
<li>nm-applet
<li>pulse audio
<li>acpi
<li>bc
<li>lm_sensors
<li>openvpn
<li>playerctl:
<li>sysstat
<li>alsa-utils
<li>rofi
</ul>

<br>
<strong>Fonts used:</strong>
<ul>
<li>Nato Mono
<li>Font Awesome
</ul>

<br>
<strong>Locations For Files:</strong>
<pre>/home/$USER
	\
	|- .Xresources
	|- bg.png
	|- .i3blocks.conf
	\- .config
		\- gtk-3.0
			\
			|- settings.ini
		\- i3
			\
			|- compton.conf
			|- config
			|- i3lock.sh
	
</pre>

<strong>Stuff Being Worked on in This Branch:</strong>
<ul>
<li>Switch out i3-lock for something more beautiful.
<li>implement xautolock to auto lock the screen.
<li>Get better icons for nm-applet and pa-applet
<li>Git mv the bg picture and .i3blocks.conf to the i3 folder (possibly moving to symlinking the git repo to my local files).
<li>Update the pictures on this page with better examples.
<li>Install script..? hmmm
