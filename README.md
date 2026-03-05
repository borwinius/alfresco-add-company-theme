# alfresco-add-company-theme
add a companytheme in blue colors with Loginscreen

#### Zweck:
individueller Anmeldebildschirm mit blauem Theme
#### Voraussetzungen:  
- linux
- maven
#### Konfiguration:
ersezten der Bilder `company.svg`und `companybackground.png`mit den eigenen Bildern in `src/main/amp/web/themescompanTheme/images/`
#### Ausführung:
  `cd alfresco-add-company-theme`  
  `mvn clean package`
dan die entstandene `target/add-company-theme-1.0-SNAPSHOT.amp` in das share_amp-Verzeichnis kopieren und in Alfresco integrieren
#### Erfahrungen:
Alfresco 26.1



