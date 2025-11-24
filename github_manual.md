# Um Github og Github Desktop:

-   **GitHub** er vefthjonusta sem gerir ther klaift ad geyma koda,
    fylgjast med breytingum og vinna med odrum i verkefnum med hjalp
    Git. Thar getur thu sett verkefni thin i geymslur, haldid utan um
    utgafur og unnid med teymum a einfaldan og oruggan hatt.

-   **GitHub Desktop** er forrit sem gerir thetta enn audveldara med
    myndraenu vidthmoti, thar sem thu getur unnid med Git an
    skipanalinu, gert breytingar, sent thar a netid og stjornad
    verkefnum a einfaldan hatt.

## Uppsetning reikninga a GitHub

Til ad stofna GitHub-adgang ferduth a github.com, smellir a **Sign up**
og slaerd inn netfang, lykilord og notendanafn. Thu stadfestir svo
adganginn med tolvuposti og getur tha strax byrad ad nota GitHub og
tengt hann vidth GitHub Desktop.

Til ad skra sig inn i GitHub Desktop opnardhu forritid og velur **Sign
in to GitHub**. Tha birtist innskraningar gluggi thar sem thu slaerd inn
notandanafn og lykilord fyrir GitHub-adganginn thin. Eftir stadfestingu
tengist forritid reikningnum og thu getur farid ad vinna med geymslurnar
thinar beint.

## Grunnadgerdir i GitHub Desktop

### Cloning in Desktop

-   Veldu **File \> Clone Repository**.
-   Slaerdhu inn slodina eda veldu ur listanum.
-   Veldu moppu og smelltu **Clone**.

### Commit in Desktop

-   Veldu skrarnar sem thu breyttir.
-   Skrifadu lysingu i **Summary**.
-   Smelltu **Commit to main**.

### Push in Desktop

-   Smelltu **Push origin** til ad senda breytingar.

### Pull in Desktop

-   Smelltu **Fetch origin** og svo **Pull** til ad saekja breytingar.

## Pull Requests og Code Review

### Hvad er Pull Request?

Pull Request er beidni um ad sameina breytingar milli greina.

### Hvenaer er hann notadur?

Thegar thu vinnur i serstoku branchi og vilt fa breytingar yfirfarnar
adur en thar fara i main.

### Hvernig virkar hann?

Thu push-ar branchinu, opnar Pull Request, lysir breytingunum og bidur
um yfirferd.

### Code Review

Adrir i teyminu skoda koda thinn til ad tryggja gaedi og samraemi.

## Lausn a Merge Conflict

Daemi: tver breyta **somu linu i somu skra**. Thu tharft ad velja hvada
utgafa a ad nota og sameina handvirkt.

## Algeng vandamal og lausnir

-   Gleyma ad gera commit adur en push: vista breytingar fyrst.
-   Lenda i merge conflicts: tveir breyta somu linu.
-   Vinna a rongu branchi: alltaf athuga virkt branch.
-   Gera git fetch, og svo merch
  

## Ymist um Commands

### Repositories

-   `git init`
-   `git clone <repository_URL>`

### Skrar og breytingar

-   `git add .`
-   `git commit -m "Initial commit"`
-   `git status` - Leyfir þér að skoða status á repo 
-   `git log`
-   `git checkout -- <file_name>`

### Branches og merging

-   `git checkout -b <branch_name>`
-   `git checkout <branch_name>`
-   `git merge <source_branch>`

### Collaboration

-   Fork
-   Pull Request

### Remote repositories

-   `git remote add <name> <repository_URL>`
-   `git fetch <remote_name>`
-   `git pull <remote_name> <branch_name>`
-   `git push <remote_name> <branch_name>`
