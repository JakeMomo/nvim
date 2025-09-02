fait un git clone dans ~/.config

# raccourcis pop os : 

## déplacer fenêtre : 
	entre écrans : super + shift + flèche droite/gauche
	entre workspace : super + ctrl + flèche haut/bas
	dans l'écran : super (+ ctrl) + flèche gauche/droite

## redimensionner fenêtre : super + entrée pour activer mode édition
	déplacer fenêtre : flèches, puis entrée pour valider / échap annuler
	redimensionner : shift + flèche
	échanger fenêtres : ctrl + flèche
	
changer fenêtre : super + flèche droite/gauche
changer appli : alt + tab

dossiers : super + f
afficher applis : super + A

nouveau wizterm : ctrl + shift + n

voir clavier / raccourcis pour le reste !


# NEOVIM
https://neovim.io/doc/user/quickref.html

## modes : 
- ;; = échap
- v : visual mode, pour sélectionner du texte

## édition :
- (imode) leader+n : autocomplétion, navigation avec C-n/p

## navigation : 
### nmode
-  w pour avancer d'un mot, b pour reculer d'un mot
- C-t nouveau buffer
- C-v/x split horizontal/vertical
- "-" pour remonter d'un dossier
- :bd ferme un buffer
- shift+flèche pour chanegr de buffer
- $ fin de ligne
- ^ début de ligne
- ( début de phrase courant (ou précédent si déjà au début)
- ) fin de phrase courante / suivante si déjà en fin
- gj : ligne affiché du dessus
- gk : ligne affichée du dessous
- u : undo
- ctrl + r : redo
- g + _ : dernier caractère non vide de la ligne

### vmode
- d : supprimer texte sélectionné
- y copier sélection
- c supprime sélection et lance mode insertion
- p remplace sélectionner par clipboard

## navigateur de fichiers : 
https://github.com/nvim-tree/nvim-tree.lua?tab=readme-ov-file#custom-mappings
- leader+e pour toggle le navigateur
- a créer un fichier/dossier
- d supprimer fichier/dossier

## Recherches
- leader+ff : recherche grep
- leader + fg : recherche dans les noms de fichiers


g
