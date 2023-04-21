git init -> inicializálom a gitet
git clone https://github.com/szabopeter92/git-vizsga.git -> klónozoma a saját meghajtómra a projektet
touch README.md -> létrehozom a README.md fájl-t
touch .gitignore -> létrehozom a .gitignore fájl-t
git status -> leellenőzöm a státuszát a projekten belüli fájloknak
git add . -> hozzáadtam az új fájlokat
git commit -m "létrehoztam a README.md és a .gitignore fájlt" -> megjegyzést fűztem az add parancshoz
git branch console -> létrehoztam a console ágat
git checkout console -> átléptema  console ágba
git add . -> hozzáadtam az app.js fájlban történő változtatásokat
git commit -m "A js fájlban való változások" -> megjegyzést fűztem az add parancshoz
git add . -> hozzáadtam az style.css fájlban történő változtatásokat
git commit -m "A css fájlban lévő változtatások" -> megjegyzést fűztem az add parancshoz
git add . -> hozzáadtam az README.md fájlban történő változtatásokat
git commit -m "A README fájl mentése" -> megjegyzést fűztem az add parancshoz
git remote add origin https://github.com/morvaimate99/GIT-vizsga.git -> távoli gyűjtemény megadása
git push -u origin console -> Githubra történő feltöltés