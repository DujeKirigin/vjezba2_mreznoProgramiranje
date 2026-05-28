## Objašnjenja rezultata

### Zadatak 1 - Postavljanje GitHub Workspaces okruženja

Naredba `git --version` ispisuje instaliranu verziju Gita u Workspaces/Codespaces okruženju.  
Naredbe `git config --global user.name` i `git config --global user.email` postavljaju ime i e-mail koji će se prikazivati uz commitove.

### Zadatak 2 - Kreiranje i inicijalizacija repozitorija

Naredba `git init` inicijalizira novi lokalni Git repozitorij.  
Datoteka `README.md` služi za osnovni opis projekta.  
Naredba `git add README.md` dodaje datoteku u staging područje, a `git commit` sprema promjene kao novu verziju projekta.

### Zadatak 3 - Povezivanje s GitHub repozitorijem i slanje promjena

Naredba `git remote add origin` povezuje lokalni repozitorij s GitHub repozitorijem.  
Naredba `git push -u origin main` šalje lokalne commitove na GitHub, tako da su promjene dostupne online.

### Zadatak 4 - Rad s granama i spajanje promjena

Naredba `git branch dev` kreira novu granu, a `git checkout dev` prebacuje rad na tu granu.  
Datoteka `feature.txt` predstavlja novu funkcionalnost.  
Naredba `git merge dev` spaja promjene iz razvojne grane u glavnu granu `main`.  
Naredba `git branch -d dev` briše lokalnu granu nakon što su promjene spojene.

### Zadatak 5 - Povlačenje promjena s GitHub-a

Naredba `git pull origin main` preuzima najnovije promjene s GitHuba u lokalni repozitorij.  
Naredba `git status` prikazuje trenutno stanje repozitorija i pokazuje ima li nepraćenih, izmijenjenih ili commitanih datoteka.

### Zadatak 6 - Resetiranje i vraćanje promjena

Naredba `git checkout -- README.md` vraća lokalne izmjene u datoteci na zadnju spremljenu verziju.  
Naredba `git reset HEAD README.md` uklanja datoteku iz staging područja, ali ne briše njezin sadržaj.  
Naredba `git reset --hard HEAD~1` briše zadnji commit i vraća projekt na prethodno stanje.

### Zadatak 7 - Rad s tagovima

Naredba `git tag -a v1.0 -m "Prva verzija"` dodaje oznaku verzije projektu.  
Naredba `git push origin v1.0` šalje tag na GitHub.  
Naredba `git tag` prikazuje sve dostupne tagove u repozitoriju.