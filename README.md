## Typo3 Tipps
### Update auf v12
#### Kein mailversand nach Update auf T3 v11
Lösung: Set Sender address to the same as [MAIL][defaultMailFromAddress]
Quelle: https://stackoverflow.com/questions/56770424/forms-not-sending-emails-but-it-works-in-install-tools

#### keine Styles
Update auf T3 v11.5:
 - neue htaccess (siehe: https://talk.typo3.org/t/t3-upgrade-10-4-to-11-5-login-to-be-failed/4764 
   bzw. https://github.com/TYPO3/typo3/blob/11.5/typo3/sysext/install/Resources/Private/FolderStructureTemplateFiles/root-htaccess#L284)
Das Konkatenieren und Komprimieren von css musste ausgeschaltet werden, js war nicht betroffen.
