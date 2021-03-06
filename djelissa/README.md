# Djelissa - interviex de Marcel Duchamp par Richard Hamilton #

> Mon texte est divisé en deux parties, d'une part l'interview de Marcel Duchamp par Richard Hamilton, d'autre part un échange épistolaire entre les deux hommes. Nous avions évoqué l'idée de trouver deux protocoles différents suivant les deux genres.

> Pour l'interview : il s'agirait de donner une autre lecture du texte, et de créer un dialogue de "sourd" en changeant l'ordre des questions et des réponses pour court-circuiter le sens, en s'inspirant des collages aléatoires de Duchamp. Nous avions évoqué ensemble le fait de créer des paragraphes html pour définir les blocs "Duchamp" et les blocs "Hamilton" pour créer des balises, je n'ai trouvé qu'un tuto pour m'aider, mais j'y suis pas encore parvenue http://helpx.adobe.com/fr/indesign/using/tagging-content-xml.html

> Pour les lettres : cela serait une relecture de ce genre aujourd'hui, la lettre s'est transformée en texto ou en mail, le ton est désormais évoqué par des emoticones.  Ainsi, il faudrait que je génère des smileys en fonction des différentes phrases, mais je ne sais pas vraiment comment les automatiser suivant le sens ?

Pour convertir le texte, passer par un éditeur de code/outil web (dreamweaver par exemple). Coller le texte original dans la fenêtre de création de dreamweaver, la structure des paragraphes devrait apparaître dans la fenêtre de code.

L'HTML étant un XML particulier, il suffit de remplacer les balises `<p>` par des balises `<hamilton>` ou `<duchamp>` suivant le cas de figure.

Une fois ce marquage effectué, importer le texte dans inDesign (Fichier > Importation XML). Une fenêtre structure va alors apparaître avec tout le balisage du contenu, il suffira de faire glisser la balise principale dans le corps de la page. On pourra par la suite faire correspondre automatiquement les balises à des styles indesign.

![Faire correspondre les balises aux styles, clic droit sur l'icône en haut à droite de la fenêtre structure](img/balises-styles.png)

