Protokol   
MacanovicRadovan   
2024-11-28    
1AHIF

## Install Git

1.Gehen Sie auf die Website https://git-scm.com/downloads/win  
2.Installiern sie die Standalone Installer 64-bit Git for Windows Set Version   
3.Wenn sie es installiert haben drücken sie oben links auf die datei und akzeptierren sie alle nutzungsbedingungen
4.Dann drücken sie die ganze zeit next bis es sie fragt mit welcher app sie Git öffnen wollen     
5.Prüfen sie mit : git --version ob sie die richtige version installiert haben schauen sie ob die version über 2 ist

## Terminal 
  1.schreibe : git config --global user.name "Dein Name"    
2.schreibe : git config --global user.email "deine.email@example.com"   
3.überprüfe die eingaben mit : git config --list

 
## Anmelden in github    

1.Gehen sie auf sign up   
2.Geben sie ihre email adresse ein und dann erstellen sie ein Passwort   
3.bestätigen sie ihr account dann bekommen sie eine nummer in ihre e-mail die sie dann in github eingeben dann beantworten sie die fragen

## Beispiel 

1.Drücken sie Windows cmd  
2.schreiben sie : mkdir MeinProjekt ---> mkdir = makedirectory es erstellt ein Verzeichnis  
3.schreiben sie : git init   ---> git init = macht eine neue Git repository   
4.schreibe : echo "Das ist mein erstes Git-Projekt." > readme.txt ---> fügt text     
5.schreibe : git add readme.txt ---> Erstellt eine Datei für Commit   
6.schreibe : git commit -m "Erste Version von readme.txt hinzugefügt" ---> -m steht für message   
7.schreibe : git remote add origin https://github.com/deinBenutzername/MeinProjekt.git ---> das verbindet dein git mit github   
8.schreibe : git push -u origin main ---> macht datein in github rein    
9.schreibe : git pull ---> wenn du willst das jemand noch an deinem projekt weiter arbeitet



  