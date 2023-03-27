# compactfox
modifications for a more compact firefox

# Installation
1. Make sure you've got a firefox version where you can disable extension signature verification like Nightly or ESR
2. Open about:config
3. Search for "xpin" and set xpinstall.signatures.required to false
4. Open about:addons
5. Click the gear in the top right corner and select "Install Addon from file" to install the xpi files
6. Follow the guide at https://www.userchrome.org/how-create-userchrome-css.html and use the provided userChrome.css file
