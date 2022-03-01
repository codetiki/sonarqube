# sonarqube

## Käyttö

Lataa [sonarqube](https://www.sonarqube.org/downloads/) ilmainen Community-versio ja asenna se C:\sonarqube\-kansioon. 
Aja C:\sonarqube\bin\windows-x86-64>StartSonar.bat
![Kuva](C:/Users/OMISTAJA/OneDrive/Kuvat/sonarqube.JPG)
avaa selaimessa localhost:9000
![Kuva](C:/Users/OMISTAJA/OneDrive/Kuvat/sonarqube_localhost9000.JPG)
Luo uusi projekti "Create Project" 
Loppu vaiheessa kyselee skannattavan koodia ja tietokaneen käyttöjärjestelmää ja 
antaa kommennon, joka ajetaan skannattavan koodin juuressa. 
![Kuva](C:/Users/OMISTAJA/OneDrive/Kuvat/executeScanner.JPG)
Lataa [sonar-scanner](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/) Windows 64-bit-versio ja 
asenna se C:\sonar-scanner\-kansioon.
Menee skannattavan koodin juureen ja lisää sinne sonarqubesta saatu komentojono.
![Kuva](C:/Users/OMISTAJA/OneDrive/Kuvat/sonar-scanner.JPG)
Kun skannaus on suoritettu onnistuneesti, mene sonarqube-sivustolle (http://localhost:9000/)
![Kuva](C:/Users/OMISTAJA/OneDrive/Kuvat/sonarqube_result.JPG)
