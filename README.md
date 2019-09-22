# Pull Request – Creating a Pull Request
How to create a pull request from a branch to the master branch, which is the first step in incorporating .do file updates in the master templates (_Français ci-dessous_)

_Video:_ [Pull Requests-Creating a Pull Request](https://www.youtube.com/watch?v=q7hdBEMgZXE&list=PLaCCIQf3NY979c70cnegKx8Cmo3Wltkia&index=10&t=0s)

### Summary 
How to create a pull request to integrate changes made in one branch to a master branch. There are three main reasons why you might want to create a pull request:
1. When files have been updated in a .do file update branch and those changes need to be integrated into the master branch
2. Updates to the template .do files in the PMA DM Organization or a Country Organization need to be integrated into another organization
3. When a country-specific .do file has been created for a module and that .do file needs to be added to the country specific .do file catalog 

_A pull request represents the end of a .do file editing branch. Once you have created a pull request, and that pull request has been approved, you should create a new branch before commencing any new work._


### By the end of this video, you should be able to:
- Identify when to make a pull request from a branch to the master
- Identify when to make a pull request from one organization repository to another organization repository
- Start a pull request by dragging a branch to the master
- Start a pull request by right/control clicking on the most recent commit
- Start a pull request by clicking on the green plus sign next to pull request
- Select the From Repo/Branch
- Select the To Repo/Branch
- Follow PMA protocols for naming the pull request
- Follow PMA protocols for writing the description for the pull request
- Follow PMA protocols for assigning the pull request to the right person
- Submit a pull request
- Verify pull request submission


### How Tos
#### How to Create a Pull Request:
Before you can make a pull request, make sure that you have committed all changes and that you are in the correct repository.  There are three ways to make a pull request using GitKraken:
1. Drag and Drop – Local to Remote
   - Click on the branch where the changes were made in the local menu
   - Drag and drop it on the branch where you would like to integrate the changes
   - Select “Start a Pull Request” from the menu
   - This opens the pull request menu
   - Once you have filled out the pull request menu (instructions below), click on “Create a Pull Request”
2. Commit Graph
   - Right Click, or Control Click, on the commit in the commit graph
   - Select “Start a Pull Request” from the menu
   - This opens the pull request menu
   - Once you have filled out the pull request menu (instructions below), click on “Create a Pull Request”
3. Pull Request in the left panel
   - Click on the “+” sign next to pull request on the left panel
   - This opens the pull request menu
   - Once you have filled out the pull request menu (instructions below), click on “Create a Pull Request”
   
#### How to fill out the Pull Request Menu
- From Repository: Organization and repository where the change was made
- From Branch: Branch where the change was made
- To Repository: Organization and repository where the change should be integrated
  - If you are making a pull request from one organization to another, make sure your “to organization” is different from your “from organization”
- To Branch: Branch where the changes should be integrated
  - Mostly the master branch
- Title: Should be the same as your branch name
- Description: A description that outlines the changes that were made, and justifies the changes
- Reviewer: Not required, but can be someone who you would like to review the changes, but will not be assigned to approve the changes
- Assignee: The person who will be in charge of approving the changes
  - To identify the correct assignee, see the PMA GitHub SOPs


### Glossary of terms:
| Term | Definition |
| ---- | ---------- |
| Branch | A branch is a parallel version of a repository that allows you to work freely without disrupting the master version of a file. PMA uses branches to update .do file content and prepare .do files for round specific data collection |
| Commit | A commit is a way to save a change to a file that also stores information on what changes were made, when and by who. PMA uses commits to systematically document changes to .do files |
| Local | Files and changes that are saved on a local computer within a working directory |
| Master | The default branch that is made each time a new repository is created. At PMA, the master branch contains the template of any give .do file. No changes should be made in the master branch |
| Organization | A workspace where teams can collaborate across many projects at once. PMA uses organizations to organize .do files by purpose and country. |
| Pull Request | Proposed changes to a repository submitted by a user and accepted or rejected by the repository’s collaborators. PMA uses pull requests to integrate updates to .do files into the templates and share between countries. |
| Remote | The version of a something (repository/branch/file) that is hosted on GitHub. All PMA repositories, branches and .do files have a remote version on the GitHub server |
| Repository | Contains all of the project files and documentation and stores each file’s revision history. Can have multiple collaborators. PMA keeps its .do files in repositories that are organized by survey type and action |



_________________________________________________________________




# Pull Requests – Créer une Pull Request
Comment créer une pull request à partir d’une branch vers la master branch, première étape de l’incorporation des mises à jour des .do files aux modèles master 

_Vidéo:_ [Les Pull Requests - Créer une Pull Request](https://www.youtube.com/watch?v=Q8FZi_O8f4w&list=PLaCCIQf3NY97bYG9q4ha8mEUlM8W7kJpE&index=10&t=0s)

### Résumé  
Comment créer une pull request pour intégrer des modifications faites dans une branch à une master branch. Vous pourriez devoir créer une pull request pour trois raisons principales :
1. Lorsque des fichiers ont été mis à jour dans une branche de .do file de mise à jour et que ces modifications doivent être intégrées à une master branch
2. Lorsque les mises à jour des .do files modèles dans l’Organization PMA_DM ou une Organization de pays doivent être intégrées à une autre Organization
3. Lorsqu’un .do file d’un pays en particulier a été créé pour un module et que le .do file doit être ajouté au catalogue des .do files du pays

_Une pull request est l’aboutissement d’une branche de mise à jour d’un .do file. Une fois que vous avez créé une pull request, et que cette pull request a été autorisée, vous devrez créer une nouvelle branch avant de commencer un nouveau travail._


#### A la fin de la vidéo, vous devriez être en mesure de :
- Quand effectuer une pull request d’une branch vers la master
- Quand effectuer une pull request d’un repository d’Organization à une autre repository d’Organization
- Commencer une pull request en faisant glisser une branch et en la déposant dans la master
- Commencer une pull request en cliquant droit/contrôle sur le dernier commit
- Commencer une pull request en cliquant sur le symbole « + » à côté de pull request
- Sélectionner le Repo/Branch d’origine
- Sélectionner le Repo/Branch de destination
- Suivre les protocoles de PMA pour nommer la pull request
- Suivre les protocoles de PMA pour rédiger une description de la pull request
- Suivre les protocoles de PMA pour assigner la pull request à la bonne personne
- Envoyer votre pull request
- Vérifier l’envoi de votre pull request 


### Comment Faire
#### Comment Créer une Pull Request:
Avant d’effectuer une pull request, assurez-vous que toutes les modifications soient engagées (commit) et que vous vous trouvez dans le bon repository.  Vous pouvez effectuer une pull request avec GitKraken de trois manières différentes :
1. Glisser-déposer – De Local à Remote
   - Cliquez sur la branch où les modifications ont été faites dans le menu local 
   - Faites-la glisser et déposez-la dans la branch où vous souhaitez intégrer les modifications 
   - Sélectionnez “Start a Pull Request” (Commencer une pull request) dans le menu
   - Cela ouvrira le menu de la pull request 
   - Une fois que vous avez renseigné le menu de la pull request (instructions ci-dessous), cliquez sur “Create a Pull Request” (Créer une pull request)
2. Graphique des Commits
   - Cliquez-droit, ou cliquez contrôle, sur le commit dans le graphique des commits
   - Sélectionnez “Start a Pull Request” )Commencer une pull request) dans le menu
   - Cela ouvrira le menu de la pull request 
   - Une fois que vous avez renseigné le menu de la pull request (instructions ci-dessous), cliquez sur “Create a Pull Request” (Créer une pull request)
3. Pull Request dans le panel de gauche
   - Cliquez sur le symbole “+” à côté de la pull request sur le panel de gauche
   - Cela ouvrira le menu de la pull request 
   - Une fois que vous avez renseigné le menu de la pull request (instructions ci-dessous), cliquez sur “Create a Pull Request” (Créer une pull request)

#### Comment renseigner le menu de la Pull Request
- « From repository » (Repository d’origine) : Organization et repository où la modification a été effectuée 
- « From branch » (Branch d’origine) : Branch où la modification a été faite 
- « To Repository » (Repository de destination) : Organization et repository où la modification devrait être intégrée
  - Si vous effectuez une pull request d’une Organization à une autre, assurez-vous que votre Organization de destination soit différente de votre Organization d’origine. 
- « To Branch » (Branch de destination) : Branch où la modification devrait être intégrée
  - Principalement la master branch
- « Title » (Titre) : Doit être le même que le nom de votre branch 
- « Description » : Description expliquant et justifiant les modifications qui ont été faites
- « Reviewer » (Examinateur/trice) : Pas obligatoire, mais peut être quelqu’un dont vous aimeriez qu’il/elle relise les modifications, bien que cette personne ne pourra les approuver.
- « Assignee » (Assigné[e]) : Personne qui aura la responsabilité d’autoriser les modifications 
  - Pour identifier les « assignees » adéquats, consultez les Procédures opérationnelles standards de GitHub de PMA


### Glossaire :
| Terme | Definition |
| ---- | ---------- |
| Branch | Version parallèle d’un repository permettant de travailler librement sans perturber la version master d’un fichier. PMA utilise des branches pour mettre à jour le contenu des dofiles et les préparer pour la collecte de données d’une vague d’enquête spécifique. |
| Commit | Manière de sauvegarder une modification d’un fichier en stockant aussi des informations sur les changements qui ont été faits, quand et par qui. PMA utilise des commits pour documenter systématiquement les modifications des .do files |
| Local | Les fichiers et modifications sont sauvegardés sur un ordinateur en local dans un working directory. |
| Master | Branch par défaut générée à chaque fois qu’un nouveau repository est créé. À PMA, la master branch contient le modèle de chaque .do file. Aucune modification ne devrait être apportée à la master branch |
| Organization | Espace de travail où les équipes peuvent collaborer sur différents projets en même temps. PMA utilise des organizations pour organiser ses .do files selon leur objectif et par pays |
| Pull Request | Modifications proposées pour un repository par un(e) utilisateur/trice et acceptées ou rejetées par les collaborateurs du repository. PMA utilise les pull requests pour intégrer les mises à jour des .do files aux modèles et les partager entre les pays. |
| Remote | La version de quelque chose (repository/branch/fichier) hébergée sur GitHub. Tous les repositories, branches et .do files de PMA ont une version remote sur le serveur GitHub. |
| Repository | Contient tous les fichiers et la documentation du projet, et stocke l’historique de révision de chaque fichier. Peut avoir plusieurs collaborateurs. PMA garde ses .do files dans des repositories organisés par type d’enquête et d’action |
