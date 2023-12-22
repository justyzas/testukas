# testukas

Kuriame parduotuvės aplikaciją įmonei UAB "Fiktyvas".

# Projekto pasileidimas pirma karta

$ npm install (pirma karta ir atsinaujinant moduliams)

$ npm run dev

# Projekto pasileidimas produkcijos aplinkoje

$ npm install (pirma karta ir atsinaujinant moduliams)

$ npm run prod

# Figma linkas

https://www.figma.com/file/AF88VqgMhwW8Px4vIq8g81/Desktop-sign-up-and-login-pages-by-EditorM-(Community)?type=design&node-id=1%3A83&mode=design&t=lhlXVD6DCCcL5p4s-1

# Projekto struktura

.......

# Git komandos:

$ git clone https://github.com/justyzas/testukas.git -b develop-team-3

Nuklonuoja remote repozitoriją su nurodytu adresu ir nurodytu branchu (be -b develop-team-3 nuklonuoja pagrindini brancha)

$ git pull origin <branch>

Jau sukurtoje lokalioje repozitorijoje bando gauti atnaujinimus iš remote repozitorijos ir prijungia prie lokalios repozitorijos (nebereikia commitint)

$ git fetch

Jau sukurtoje lokalioje repozitorijoje bando gauti atnaujinimus iš remote repozitorijos, bet neprijungia prie lokalios repozitorijos. Tam reikalinga komanda:

$ git merge

Parsisiustus pakitimus prijungia prie lokalios repozitorijos

# Naujos lokalios repozitorijos kūrimas bei prijungimas prie remote repozitorijos

$ git init

Sukuria naują, tuščią lokalią repozitoriją

$ git add <failo pavadinimas>

Prideda pakitimus prie lokalios repozitorijos (tam kad prideti visus reikia naudoti: $ git add \*)

$ git status

Parodo pasikeitimus lokalioje repozitorijoje ir ar tie pakitimai yra išsaugoti.

$ git commit -m "zinute"

Išsaugo pakeitimus lokalioje repozitorijoje.

$ git remote add origin "https://github.com/justyzas/testukas.git"

Prilinkina remote repozitoriją prie lokalios

# Branchingas

$ git push -u origin develop-team-3

Išsaugo lokalią repozitoriją į githubą

$ git branch develop-team-3

Prideda prie lokalios repozitorijos branchą develop-team-3

$ git branch

Parodo pridėtus branchus lokalioje repozitorijoje

$ git checkout develop-team-3

Parenka dabar aktyvų branchą su kuriuo dirbsime lokalioje repozitorijoje (reikia kad būtų pridėtas su git branch <Šakos pavadinimas>)
Jei toks branchas egzistuoja remote repozitorijoje - atsiunčia viską iš jos ir pradedamas editinimas nuo remote repozitorijoje esančių failų

Turėkite omenyje, kad prieš pradedant dirbti su kitu branchu reikia bent jau lokaliai commitinti pakitimus, kadangi atsisiuntus kitą atšaką jie išnyks!!

$ git branch -D develop-team-3

Lokaliai ištrina branchą. (privaloma turėti bent vieną kitą branchą ir jį but pasirinkus))
