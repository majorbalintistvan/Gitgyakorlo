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
## 7.  Lokális változások feltöltése a távoli repóba
- git push
## 8. távoli repó másolása(klónozása) a lokális repóba
- git clone " távoli repó URL címe"
## 9. Ágak (branches) kezelése.
>Lokáli ágak listázása
- git branch
> Lokális és távoli ágak listázása
- git branch -av
> Ág létrehozása
- git branch új_ág_neve
>Ág létrehozása (-b és váltása)
- git branch -b új_ág_neve
- git checkot -b új_ág_neve
>Váltás egy másik ágra 
- git checkout másik_ág_neve
>Ág törlése
-git branch -d törlendő_ág_neve
> Változások átvezérlése (merge)
- git checkout ág_ahova_kerülnek_a_változások
- git merge ág_ahonnan_áthozzuk_a_változásokat
## 10. Távoli repó váltouásainak letöltése a lokális gépre
-git fetch origin
