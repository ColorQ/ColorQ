# Inhalt
### TYPO3 [[(TYPO3.md)](https://github.com/ColorQ/ColorQ/blob/master/TYPO3)](https://github.com/ColorQ/ColorQ/blob/master/TYPO3.md)
### Shopware

## TYPO3
### Typo3 Tipps
#### Update auf v12
##### Kein mailversand nach Update auf T3 v11
Lösung: Set Sender address to the same as [MAIL][defaultMailFromAddress]
Quelle: https://stackoverflow.com/questions/56770424/forms-not-sending-emails-but-it-works-in-install-tools

##### keine Styles
Update auf T3 v11.5:
 - neue htaccess (siehe: https://talk.typo3.org/t/t3-upgrade-10-4-to-11-5-login-to-be-failed/4764 
   bzw. https://github.com/TYPO3/typo3/blob/11.5/typo3/sysext/install/Resources/Private/FolderStructureTemplateFiles/root-htaccess#L284)
Das Konkatenieren und Komprimieren von css musste ausgeschaltet werden, js war nicht betroffen.

## Shopware
### Shopware 6
#### Links zur SW-Doku

##### composer.json: 
https://developer.shopware.com/docs/guides/plugins/plugins/plugin-base-guide.html#create-the-plugin

##### Theme Doku: 
https://developer.shopware.com/docs/guides/plugins/themes/theme-configuration.html

#### Empfohlene PlugIns
nach https://www.youtube.com/watch?v=cbr2ia8C2Po
- HTML Minify Plugin: https://store.shopware.com/frosh35770116184f/html-minify-plugin.html
- Cookie Menü Popup: https://store.shopware.com/mcs7036024486753f/cookie-menue-popup-mit-alle-akzeptieren-button.html
- Entwickler Tool (.env-Datei auf dev umstellen): https://store.shopware.com/frosh14352927691f/hilfreiche-tools-fuer-die-entwicklung.html
- Schnelle Template-Anpassung; https://store.shopware.com/dne5116914822923f/custom-template-manager.html

#### eigenes Theme
