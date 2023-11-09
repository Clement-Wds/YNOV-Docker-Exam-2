# Rendu pour l'examen 2
## Sommaire

- Liste du groupe
- Rendu

## Liste du groupe

Clément WALSH de SERRANT - Clément DUFOUR-LAMARTINIE - Mohamed Ali DHOUIB

## Rendu
<hr>
Connexion à la machine virtuelle en SSH : <br><br>
<img width="582" alt="image" src="https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/71884576/f4c5f3a1-941e-4812-b99e-dbc300753ffa">
<br>

<hr>
Création du docker-compose-build.yml : <br><br>
<img width="709" alt="image" src="https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/71884576/ba50ed7b-7780-4994-af9e-2c2da30767d3">
<br>
<hr>
Copie des fichiers sur la VM en SSH : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/95042471-efa0-4213-b5ac-b50d6003940d)

<br>
<hr>
On peut constater que les fichiers sont bien passés : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/88f78bb1-3560-4c16-bf95-023d35c652c7)
<br>
<hr>
Création d'image : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/5808a723-55fa-416c-884e-2b33bc438d23)
<br>
<hr>
Liste des images crées :<br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/027c41a0-a22d-4d4c-b227-24e336bf3999)
<br>
<hr>
Création des tags : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/3dbe44e6-f355-459d-899b-78472faf09fb)
<br>
<hr>
Vérification des tags : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/d8b929b6-c924-47ef-b1c2-8a40ad5f4850)
<br>
<hr>

Creation du front pour afficher les registry<br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/da31c8bb-ead8-40a6-9834-cf4640f94d8c)
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/ffad7f24-3698-4f9f-a001-98da6a121efe)
<br>
<hr>



Push des images dans le registry <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/ac2e0be4-30d7-43dd-ad7d-f550fd55162c)
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/6105ca84-76f7-437b-88cd-da9e5026648d)
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/4af0a31a-b91c-40d3-b5ce-f2ccd4a8c50c)

<br>
<hr>


Liste des images apres les push : <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/2c086456-b101-4c41-9433-b6402ccbd90f)


<br>
<hr>


On a créé le fichier compose.yml, on va le copier coller sur la VM : <br><br>

<br>
<hr>

copie des fichiers sur la VM en SSH : <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/f1935739-3b64-4213-b598-350b6fcc406a)

<br>

On peut voir qu'il est bien présent sur la VM : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/c51ea975-f740-48cb-9d0d-57024ec112db)


<br>
<hr>


Création de tout les conteneurs : <br><br>

![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/e6bb9309-acd1-43ed-af3c-762282146907)
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/cba33a95-cada-4153-8fd8-b87df1c1544f)


<br>
<hr>

Ajout des ports dans les paramètres de la VM: <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/df040ea5-a11a-4b37-930c-decbadb923c7)

<br>
<hr>

Résultat de l'operation avec docker PS : <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/b76519e7-4c0e-40d2-a6d5-01e86a03e5dd)

<br>
<hr>

Application Vote : <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/7d39aaf4-65c1-4e96-ab76-4d12d968cabc)

<br>
<hr>

Application Résultat : <br><br>
![image](https://github.com/Clement-Wds/YNOV-Docker-Exam-2/assets/56402465/020e1dd2-ddfa-4a49-864d-d7325c4ca1eb)

<br>
<hr>







