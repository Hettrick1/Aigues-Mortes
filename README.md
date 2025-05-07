the axel version : https://pdftobrainrot.org/share/5bfaa149c34e4a9fb15d478c2ccf4671

# 🇫🇷 `Français`
`English below` 

# 🏹 Guide d'utilisation de GitHub pour le projet Aigues-Mortes! 🏹

## 🎯 Objectifs
Comprendre les bases de GitHub
Utiliser GitHub Desktop pour gérer les versions facilement.
Créer et gérer des issues.
Contribuer au projet via des pull requests.

## 🔗 Liens
[Miro](https://miro.com/app/board/uXjVLCamjk0=/)  
    
Si tu n'es pas sûr d'avoir compris quelque chose ou que tu veux des informations plus approfondies sur un sujet tu peux aller voir sur le [Wiki 📖](https://github.com/Mathys-Hymon/GhostnGoblinsRemake/wiki) du projet.

## 🛠️ Prérequis
Avant de commencer, assure toi d'avoir :
- [GitHub Desktop 📥](https://desktop.github.com/download/) d'installé.
- Ton compte GitHub de connecté sur le site de GitHub et aussi sur l'application.
- Cloné le projet.

## 🔎 Comment cloner le dépôt du projet ?
*` Simple petit rappel au cas où tu aurais oublié comment cloner le dépôt git`*

1. Ouvre GitHub Desktop.
2. Clique sur File > Clone repository en haut a gauche de l'application.  
 
![Screenshot 2024-11-26 114120](https://github.com/user-attachments/assets/c3f3d0af-c37b-4236-9908-9559deb85952)
---

3. Écris juste le nom du projet dans la barre de recherche.
  
![Capture d'écran 2024-11-25 210558](https://github.com/user-attachments/assets/45d32030-cac9-45e8-a799-86d8782aa3a8)
---
4. Au cas ou ça ne fonctionnerait pas, tu peux coller ce liens dans l'onglet URL :  
   ` https://github.com/Mathys-Hymon/GhostnGoblinsRemake.git `
---
 
## 🚀 Comment contribuer ?

Avant pour contribuer, chacun devais créer sa branch et travailler de son coté puis tenter de merge avec le main, ce qui cassais souvent et parfois des gens restaient sur le main pour travailler !
![Main](https://github.com/user-attachments/assets/d5fb5b75-985b-41da-aedc-7f61ba7e5a42)


Cette période est révolue !  
Désormais plus personne n'a de branch attitrée, quand tu voudra travailler il te faudra suivre ce process :

### 1️⃣ Créer une issue 📝
*`Les issues servent à discuter d'idées, signaler des bugs, proposer des améliorations ou ajouter des features`*
#### 1. Va sur la page internet du projet.
#### 2. Clique sur **Issues** *en haut du dépôt*.
    
![issues Screen](https://github.com/user-attachments/assets/caf5f6a4-8a69-4882-a346-278551068b0f)
---
#### 3. Clique sur New Issue.
    
![issue Button screen](https://github.com/user-attachments/assets/52e74a98-783c-4810-a2b5-11df6ef75035)
---
#### 4. Choisi entre un des 2 templates :
      
- `Bug Report` te permet de report un bug pour qu'on puisse le corriger au plus vite.
- `Feature Request` te permet de soit demander, soit t'assigner une tache.  

*Dans le cadre d'une contribution, on va partir sur la Feature Request.*  

#### 5. Donne un titre clair 🟢 et décris ton besoin en remplissant le template.
         
- `🚀 Description`  décris brièvement ce que tu comptes faire, 2/3 lignes max.  
- `🔍 Blueprints used` note tous les assets que tu compte utiliser (BP, Map, static mesh, textures, materials, etc.) Sans exception ! Car les personnes qui ouvrirons des issues après toi vérifierons de ne pas éditer les mêmes fichiers que toi.

---
⚠️**ATTENTION**⚠️ Avant de créer ton issue et de remplir Blueprints used, vérifie dans les issues notées comme "active" qu'elles n'utilisent pas les même fichiers que toi !!!
      
![Check issues](https://github.com/user-attachments/assets/0309a652-e5d2-4495-882d-f0beaa61fd1d)

---
#### Par exemple en cliquant sur l'issue `Add player Dash #17` on vois que Max utilise le BP_Player, tant que l'issue n'es pas fermée il est donc impossible d'utiliser le BP_Player  
![Capture d'écran 2024-11-25 220728](https://github.com/user-attachments/assets/3fda5551-9eee-443f-b796-70bda4c8064a)
---
 `Ces 2 dernières catégories ne sont pas obligatoires si tu crée cette issue pour travailler dessus mais est recommandée si il s'agit d'une requête.`
       
- `🎯 Purpose of the feature` décris en quoi consiste ta feature, par exemple : le dash permet de se "téléporter" vers l'avant pour éviter les projectiles.
- `📝 Expected features` précise exactement ce que tu attend, par exemple : -un dash, un hud du cooldown du dash, un data asset pour le dash etc.

---
#### 6. Rempli les informations sur la droite

![Labels](https://github.com/user-attachments/assets/56957908-eeb4-4d28-a804-2fc1ab342f3a)
---
- `Assignees` Si tu souhaite travailler sur cette issue, clique sur "assign yourself" sinon laisse vide si c'est une requête.
- `Labels` Les labels sont les tag de ton issue, tu dois cocher l'état de ton issue : `active` ou `pending` puis à qui cette request est adressée avec `Prog`, `Level Design`, `Game Design`, `Game Artists`

  ⚠️Pour ce qui est des `Projects` ou `Milestone` tu n'as pas a t'en soucier !
---
#### 7. Le moment de vérité ! 
- Une fois que toutes les info ont été rempli c'est le grand moment ! Tu peux cliquer en bas a droite sur `Submit new Issue`.
- Pour te créer une branche et pouvoir commencer à travailler, clique sur `create a branch` dans la catégorie `Development`  
      
![Create branch screen](https://github.com/user-attachments/assets/6b46238b-a5c3-4655-a122-2263b3879b8b)
---
- Ne touche aucun réglages et clique sur `create branch`
      
![Final branch creation](https://github.com/user-attachments/assets/15b0b867-b4fc-444f-b615-2fe1092096ff)
---
#### 8. Fin !!! 
C'est bon, tout est fini et ta branch t'attend sur GitHub desktop, il te suffit de fetch origin et elle devrai apparaitre, met toi dessus et fais ce que tu veux !

---
### 2️⃣ Faire une pull request (PR) ✨
Vous pensiez en avoir fini avec le tuto ? loin de la désolé. Créer une Issue et travailler dessus c'est bien joli mais une fois la task terminée, il faut bien l'envoyer sur le main pour en faire profiter tout le monde.  
*`Les pull request servent à envoyer ton travail sur le main une fois ton issue terminée`*

#### 1. Va sur la page internet du projet.
#### 2. Dans l'onglet des branch sélectionne la tienne.  
      
![Select branch](https://github.com/user-attachments/assets/fc080ccb-cd0b-4ebc-a80a-5cf9cc2b1e61)
 
---
#### 3. Ouvre une Pull Request.
Dans l'onglet `Contribute` sélectionne `Open pull request`  
      
![Capture d'écran 2024-11-25 230812](https://github.com/user-attachments/assets/aca537ef-2ee4-49cd-860a-7e6ea238cba7)

---
#### 4. Remplir les informations.
Comme pour l'issue, ajoute un titre, une petite description de ce que tu as fais et appuie sur `Create pull request` (pas besoin de remplir les `Assignees`, `Labels` ou autre)  
      
![Capture d'écran 2024-11-25 231904](https://github.com/user-attachments/assets/0b3f5aae-b602-432d-a9aa-5a5c6f851e40)

---
#### 5. Attendre.
Ta pull request à bien été soumise aux Développeurs (nous) et sera examinée au plus vite, c'est juste une mesure de sécurité pour s'assurer qu'une mauvaise manip ne risque pas de compromettre une partie du projet.  
      
![Capture d'écran 2024-11-25 231937](https://github.com/user-attachments/assets/6044e442-d76f-46dd-9942-65467449afc0)

---
#### 6. Confirmer le Merge
Une fois validée tu aura le choix de soit continuer à travailler dessus pour régler les soucis relevé ou alors de merge avec le main si le merge à été autorisé, ce qui aura pour conséquences de fermer ton issue.
      
![Capture d'écran 2024-11-25 232123](https://github.com/user-attachments/assets/32a38170-1525-4dfd-9692-07c8ab8994d4)
---
#### 6. Supprimer ta branch
Maintenant que le merge à été fait, tu n'a plus qu'a cliquer sur `Delete branch` pour supprimer ta branch inutile  
      
![Capture d'écran 2024-11-25 232329](https://github.com/user-attachments/assets/7364b884-5d07-4305-ae41-09d26f23b3c4)

---
  ⚠️ N'oublie pas de la supprimer sur GitHub Desktop car elle reste stocké en local !
![Capture d'écran 2024-11-25 233042](https://github.com/user-attachments/assets/667d417f-a6e5-4e73-af7b-375f24b0af27)
---

### 📝 Récapitulatif
1. Crée une issue et décris ton idée.
2. Assigne toi la tâche et crée une branche.
3. Travaille sur ta branche en local.
4. Ouvre une pull request une fois terminé.
5. Attends la validation avant de merger.

---
# 🇬🇧 `English`


# 🏹 GitHub user guide for the ghost and goblins remake! 🏹

## 🎯 Objectives
Understanding the basics of GitHub
Using GitHub Desktop to manage versions easily.
Creating and managing issues.
Contribute to the project via pull requests.

## 🔗 Links
[Miro](https://miro.com/app/board/uXjVLCamjk0=/)  
    
If you're not sure you've understood something, or if you want more in-depth information on a subject, you can check out the project's [Wiki 📖](https://github.com/Mathys-Hymon/GhostnGoblinsRemake/wiki).

## 🛠️ Prerequisites
Before you start, make sure you have :
- [GitHub Desktop 📥](https://desktop.github.com/download/) installed.
- Your GitHub account connected to the GitHub site and also to the application.
- Clone the project.

## 🔎 How do I clone the project repository?
*` Just a reminder in case you've forgotten how to clone the git repository`*

1. Open GitHub Desktop.
2. Click on File > Clone repository at the top left of the application.  
 
![Clone repository](https://github.com/user-attachments/assets/8c155212-a7f3-4c4f-8e77-437ba27437aa)
---
3. Enter the name of the project in the search bar.
  
![Capture d'écran 2024-11-25 210558](https://github.com/user-attachments/assets/45d32030-cac9-45e8-a799-86d8782aa3a8)
---
4.  If that doesn't work, you can paste this link into the URL tab:  
   ` https://github.com/Mathys-Hymon/GhostnGoblinsRemake.git `
---
 
## 🚀 How to contribute ?

Before, to contribute, everyone had to create their own branch and work on their own then try to merge with the main, which often broke down and sometimes people stayed on the main to work!
![Main](https://github.com/user-attachments/assets/d5fb5b75-985b-41da-aedc-7f61ba7e5a42)


Those days are gone!  
When you want to work, you'll have to follow this process:

### 1️⃣ Create an issue 📝
*`Les issues servent à discuter d'idées, signaler des bugs, proposer des améliorations ou ajouter des features`*
#### 1. Go to the project website.
#### 2. Click on **Issues** *at the top of the repository*.
    
![issues Screen](https://github.com/user-attachments/assets/caf5f6a4-8a69-4882-a346-278551068b0f)
---
#### 3. Click on New Issue.
    
![issue Button screen](https://github.com/user-attachments/assets/52e74a98-783c-4810-a2b5-11df6ef75035)
---
#### 4. Choose between 2 templates :
      
- `Bug Report` allows you to report a bug so that we can fix it as quickly as possible.
- `Feature Request` allows you to either request or assign a task.  

*As part of a contribution, we're going to use the Feature Request.*  

#### 5. Give it a clear title 🟢 and describe your needs by filling in the template.
        
- `🚀 Description`  briefly describe what you intend to do, 2/3 lines max..  
- `🔍 Blueprints used` make a note of all the assets you intend to use (BP, Map, static mesh, textures, materials, etc.) - no exceptions! Because people who open issues after you will check that they are not editing the same files as you.

---
⚠️**WARNING**⚠️ Before creating your issue and filling in Blueprints used, check in the issues marked as ‘active’ that they are not using the same files as you!
      
![Check issues](https://github.com/user-attachments/assets/0309a652-e5d2-4495-882d-f0beaa61fd1d)

---
#### For example, if you click on the `Add player Dash #17` issue, you will see that Max is using the BP_Player, so it is impossible to use the BP_Player until the issue is closed.  
![Capture d'écran 2024-11-25 220728](https://github.com/user-attachments/assets/3fda5551-9eee-443f-b796-70bda4c8064a)
---
 `These last 2 categories are not compulsory if you are creating this issue to work on it, but are recommended if it is a request.`
       
- `🎯 Purpose of the feature` ddescribe your feature, for example: the dash lets you ‘teleport’ forward to avoid projectiles.
- `📝 Expected features` specify exactly what you want, for example: -a dash, a hud of the dash's cooldown, a data asset for the dash, etc.

---
#### 6. Fill in the information on the right

![Labels](https://github.com/user-attachments/assets/56957908-eeb4-4d28-a804-2fc1ab342f3a)
---
- `Assignees`If you want to work on this issue, click on ‘assign yourself’, otherwise leave it blank if it's a request.
- `Labels` The labels are the tags for your issue. You need to check the status of your issue: `active` or `pending` and then who this request is addressed to with `Prog`, `Level Design`, `Game Design`, `Game Artists`.

  ⚠️As for `Projects` or `Milestone`, you don't have to worry about them!
---
#### 7. The moment of truth!
- Once all the information has been filled in, it's the big moment! You can click on `Submit new Issue` at the bottom right.
- To create a branch and start working, click on `create a branch` in the `Development` category.  
      
![Create branch screen](https://github.com/user-attachments/assets/6b46238b-a5c3-4655-a122-2263b3879b8b)
---
- Do not change any settings and click on `create branch`
      
![Final branch creation](https://github.com/user-attachments/assets/15b0b867-b4fc-444f-b615-2fe1092096ff)
---
#### 8. The End !!! 
All done, everything is finished and your branch is waiting for you on GitHub Desktop. Just fetch the origin and it should appear. Switch to it and do whatever you want!

---
### 2️⃣ Create a pull request (PR) ✨
You thought you were done with the tutorial? Far from it, sorry. Creating an Issue and working on it is all well and good, but once the task is finished, you need to merge it into the main branch so everyone can benefit from it.
*`Pull requests are used to send your work to the main branch once your issue is completed.`*

#### 1. Go to the project's webpage.
#### 2. In the "Branches" tab, select your branch.
      
![Select branch](https://github.com/user-attachments/assets/fc080ccb-cd0b-4ebc-a80a-5cf9cc2b1e61)
 
---
#### 3. Open a Pull Request.
In the `Contribute` tab, select `Open pull request`  
      
![Capture d'écran 2024-11-25 230812](https://github.com/user-attachments/assets/aca537ef-2ee4-49cd-860a-7e6ea238cba7)

---
#### 4. Fill in the information.
As with the issue, add a title, a brief description of what you've done, and click on `Create pull request` (no need to fill in the `Assignees`, `Labels` or other fields).  
      
![Capture d'écran 2024-11-25 231904](https://github.com/user-attachments/assets/0b3f5aae-b602-432d-a9aa-5a5c6f851e40)

---
#### 5. Wait.
Your pull request has been successfully submitted to the developers (us) and will be reviewed as soon as possible. It's just a safety measure to ensure that no mistakes risk compromising part of the project.  
      
![Capture d'écran 2024-11-25 231937](https://github.com/user-attachments/assets/6044e442-d76f-46dd-9942-65467449afc0)

---
#### 6. Confirm the merge.
Once validated, you will have the option to either continue working on it to fix the issues raised, or merge it with the main branch if the merge has been approved, which will result in closing your issue.  
      
![Capture d'écran 2024-11-25 232123](https://github.com/user-attachments/assets/32a38170-1525-4dfd-9692-07c8ab8994d4)
---
#### 6. Delete your branch
Now that the merge has been done, all you need to do is click on `Delete branch` to remove your unnecessary branch.  
      
![Capture d'écran 2024-11-25 232329](https://github.com/user-attachments/assets/7364b884-5d07-4305-ae41-09d26f23b3c4)

---
  ⚠️ Don't forget to delete it on GitHub Desktop as well, since it remains stored locally!
![Capture d'écran 2024-11-25 233042](https://github.com/user-attachments/assets/667d417f-a6e5-4e73-af7b-375f24b0af27)
---

### 📝 Summary
1. Create an issue and describe your idea.
2. Assign yourself the task and create a branch.
3. Work on your branch locally.
4. Open a pull request once you're done.
5. Wait for the approval before merging.
