##Inhalt
###TYPO3
###Shopware

##TYPO3
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

##Shopware
###Shopware 6
#### Links zur SW-Doku
composer.json: [[https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa1Fscy1nbEhuZWJfbFlRR3IwNWtTTjhGZ0JEUXxBQ3Jtc0ttQUpScFVIWnBRUlIwRGRHQms5VTZHakY1SGN1N1JwVVE5Rlg4a3NwSHZvRzRqclNodEZiZ0ZIcGdfdjhHTGpadENRN0E2WXZJOWhReVIwY19QS0d2M1JndFVUa1cxTXdyZ1ZVeTUtazlZMVZqMlBYTQ&q=https%3A%2F%2Fdeveloper.shopware.com%2Fdocs%2Fguides%2Fplugins%2Fplugins%2Fplugin-base-guide%23create-the-plugin&v=Bv7zLemqU-o](https://developer.shopware.com/docs/guides/plugins/plugins/plugin-base-guide.html#create-the-plugin)](https://developer.shopware.com/docs/guides/plugins/plugins/plugin-base-guide.html#create-the-plugin)
Theme Doku: https://developer.shopware.com/docs/guides/plugins/themes/theme-configuration.html
#### eigenes Theme
