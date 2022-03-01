# sonarqube

## Käyttö

Lataa [sonarqube](https://www.sonarqube.org/downloads/) ilmainen Community-versio ja asenna se C:\sonarqube\-kansioon. 
Aja C:\sonarqube\bin\windows-x86-64>StartSonar.bat
![Kuva](./images/sonarqube.JPG)
avaa selaimessa localhost:9000
![Kuva](./images/sonarqube_localhost9000.JPG)
Luo uusi projekti "Create Project" 
Loppu vaiheessa kyselee skannattavan koodia ja tietokaneen käyttöjärjestelmää ja 
antaa kommennon, joka ajetaan skannattavan koodin juuressa. 
![Kuva](./images/executeScanner.JPG)
Lataa [sonar-scanner](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/) Windows 64-bit-versio ja 
asenna se C:\sonar-scanner\-kansioon.
Menee skannattavan koodin juureen ja lisää sinne sonarqubesta saatu komentojono.
![Kuva](./images/sonar-scanner.JPG)
Kun skannaus on suoritettu onnistuneesti, mene sonarqube-sivustolle (http://localhost:9000/)
![Kuva](./images/sonarqube_result.JPG)
![Kuva](./images/sonarqube_bugs.JPG)

