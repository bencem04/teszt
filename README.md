# mizu cica
echo "# test" >> README.md #fájl létrehoz első sor test
git init #mappa inici
git add README.md #vált ment
git commit -m "first commit" #vált jóváhagy
git branch -M main #fejl ág megnev main-re
git remote add origin https://github.com/bencem04/teszt.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/bencem04/teszt.git
git branch -M main
git push -u origin main #feltölti az origin távoli repobe a commitokat
további terminál parancsok
git pull origin main #a friss repo letöltésee
git remote -v #aktuális távoli repo lekérdezése
git status #change, stage, commit, állapot lekérdezése
git config --global --list #globális beáll lístázása
cd #change directory
cd .. #egy mappával feljebb
mkdir <directoryname> #makedirectory
rmdir <dn> #remove
ls #könyvtár listázásáa
git commit -am ""message" #git #összes változtatás és commit egyben
