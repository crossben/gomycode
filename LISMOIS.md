STRUCTURE DU CODE :
    model : MVC
    fichier : 
        controller : code metier pour la validation des donnees
        config : fichier de configuration (connection a la base de donnee)
        js : ficher javascript
        style : ficher css et bootstrap
        view : ensemble des vue 
        index.html : point d'entree du site web
        LISMOI : documentation

CONFIGURATION 
    git : 
        installation
        access a la CMD : 
            configuration du nom d'utilisateur (les quotes son obligatoire) : git config --global user.name "votre nom"
            configuration de l'address email (les quotes son obligatoire) : git config --global user.email "votre email"
            tester: 
                git config user.name
                git config user.email
        initialisation du projet git :
            git init 
            git commit -m "first commit"
            git branch -M main
            git remote add origin https://github.com/crossben/gomycode.git
            git push -u origin main

        pour ajouter votre code sur le repo git
            git add .
            git status
            git commit -m "message"
            git push origin main

        pour recuper les modification faites par les autres
            git clone + lien
            git pull origin main

DOCUMENTATION 
    liens :
        html special character : https://www.w3schools.com/html/html_symbols.asp