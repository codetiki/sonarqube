# sonarqube

## Käyttöohje

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
A) JS-koodin skannaus
Menee skannattavan koodin juureen ja lisää sinne sonarqubesta saatu komentojono.
![Kuva](./images/sonar-scanner.JPG)
Kun skannaus on suoritettu onnistuneesti (INFO: EXECUTION SUCCESS), 
mene sonarqube-sivustolle (http://localhost:9000/) katsomaan tuloksia
![Kuva](./images/sonarqube_result.JPG)
![Kuva](./images/sonarqube_bugs.JPG)
B) C#-koodin skannaus
.NET-projektissa täytyy asentaa ensin dotnet-sonarscanner, jonka jälkeen 
varsinainen skannaus onnistuu
![Kuva](./images/executeScanner_Csharp.JPG)
Skannaus lisää sonarqube-kansion koodiin.
![Kuva](./images/sonarqubeKansio.JPG)
Tulokset C#-projektista
![Kuva](./images/sonarqube_result_Csharp.JPG)


