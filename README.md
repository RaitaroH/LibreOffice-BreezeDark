# LibreOffice-BreezeDark

![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Writer.png)

# Icons
The icons are the breeze icons for LibreOffice from ![here](https://github.com/DarkknightAK/breeze-icon-theme/tree/master/LibreOffice_Breeze).
### Instalation:
```
git clone https://github.com/RaitaroH/LibreOffice-BreezeDark.git
sudo cp LibreOffice-BreezeDark/images_breeze_dark.zip /usr/lib/libreoffice/share/config
```

# Color palette
I provide the breeze dark colors, deepdark colors and even some extra ones. 
### Instalation:
```
git clone https://github.com/RaitaroH/LibreOffice-BreezeDark.git
mv ~/.config/libreoffice/4/user/config/standard.soc ~/.config/libreoffice/4/user/config/standard.soc.back
cp LibreOffice-BreezeDark/standard.soc ~/.config/libreoffice/4/user/config/standard.soc
```

# Color scheme
### Instalation:
I do not know if this works actually.
I do advice to change this stuff manually, but here is the code I got:
```
git clone https://github.com/RaitaroH/LibreOffice-BreezeDark.git
cp ~/.config/libreoffice/4/user/registrymodifications.xcu ~/.config/libreoffice/4/user/registrymodifications.xcu.back
cat LibreOffice-BreezeDark/standard.soc >> ~/.config/libreoffice/4/user/registrymodifications.xcu
```
Alternatively you can do it manually. Here are some screenshots to help you.
![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Scheme1.png)
![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Scheme2.png)


# Results
![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Calc.png)
Please be careful that cutting cells can leave white spaces in their place. It is best to try and fill every cell with the background color.  I suggest to go to: Styles and formating > Cell Styles > Default > Modify. There you can do the needed changes. 
Also keep in mind that you will have to manually change charts.

![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Impress.png)
Export in pdf keeps the background and colors:
![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Impress-export.png)

The export from WRITER in pdf changes the background to white and text to black AS LONG AS it is AUTOMATIC. Any further changes to the colors will be exported.
![alt tag](https://raw.githubusercontent.com/RaitaroH/LibreOffice-BreezeDark/master/Images/Writer-export.png)
