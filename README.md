# Verziókezelés alapjai
## 1. git letöltése
- [git for wimdows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. Konfigurációs parancsok
- git config --global user.name majorbalintistvan
- git config --global user.email major.balint.istvan@students.jedlik.eu
- git config --global credential.helper wincred
## Repository létrehozása
- git init
## Állomány hozzáadása a stagehez(stageing area)
> A stagen lévő állományokról tudunk állapotfelvételt (commit-ot) készíteni.
> Üres mappa nem kerül stage-re.
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
- git commit  -m "commit message"
## 6. Git állapot és log lekérdezése
- git status
- git log