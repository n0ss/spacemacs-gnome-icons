# spacemacs-gnome-icons
Useful PNGs/SVG icons to blend spacemacs into Gnome. Tested and used in Gnome 3.36.0

# Installation in Gnome

* Clone this repo using : 
  ```
  > git clone https://github.com/n0ss/spacemacs-gnome-icons/
  ```

  Tip : applications' icons are located by default in **/usr/share/icons/hicolor**


* Copy git folder content to that repo using admin rights :

  ```
  > cd spacemacs-gnome-icons
  > sudo cp -r * /usr/share/icons/hicolor
  ```
  
* Using your favorite text-editor, modify **/usr/share/applications/emacs.desktop**. For example :

  ```
  > sudo gedit /usr/share/applications/emacs.desktop
  ```
  Then modify __Icon=emacs__ into __Icon=spacemacs__.
  
  (*optional* : You can also change __Name=Emacs__ into __Name=Spacemacs__ fitting your personal preferences.)


* Run **gtk-update-icon-cache**. Simply type :

  ```
  > gtk-update-icon-cache
  ```
  
* Reload Gnome : **ALT+F2** type **r** hit **ENTER**
  
* You're done.
  
The PNG files contained is this repo were made using cairosvg CLI tool : https://cairosvg.org/documentation/
 
 ![Spacemacs Logo](https://camo.githubusercontent.com/b39bdab925b8da08ecaf08eda877b01b8421b619/68747470733a2f2f7777772e6e61737365722e73706163652f696d67732f73706163656d6163732d6c6f676f2e706e67)




<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/StillImage" property="dct:title" rel="dct:type">
This repo was made from <a xmlns:cc="http://creativecommons.org/ns#" href="http://www.nass3r.com" property="cc:attributionName" rel="cc:attributionURL">Nasser Alshammari</a>'s work and original logo. It is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
Original work : https://github.com/nashamri/spacemacs-logo
