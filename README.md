# iesa-2015-a3-mobile

* https://github.com/melanie2b4/iesa-2015-a3-mobile/new/master?readme=1 (Melanie Waroux)


git status = liste les fichiers que git ne connait pas
Faire un git add + nom du fichier pour la mise à jour
Refaire un git status pour qu'il prenne les fichiers en compte


git commit -am "hello"
git push = fait un commit dans github




Changer image au lancement de l'appli:

général -> launch images
regarder la référence de l'iphone et sa resource
aller dans le fichier hello/platforms/ios/HelloWorld/Resources/splash et changer l'image associée
restart xcode et lancer l'appli dans le simulateur, si celle-ci a déjà été ouverte ctrl + cmd + h pour la fermer et relancer.




- Penser à se placer dans le bon répertoire

- 1 balise root par fichier

- pas de configuration du plugin sur ios

- cordova plugins ls = liste tous les plugins présents

- pwd = arborescence

- open . = ouvre xcode


git clone https://github.com/melanie2b4/iesa-2015-a3-mobile.git (lien git ssh)

sudo xcode-select -switch /Applications/Xcode.app

cd hello


getelementbyid + injecter les éléments

Ouvrir le dossier dans xCode -> hello/platforms/ios/HelloWorld.xcodeproj


cordova prepare = avant de simuler