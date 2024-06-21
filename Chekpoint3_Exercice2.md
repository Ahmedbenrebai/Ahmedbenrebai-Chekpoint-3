### Q.2.1.1
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.1.1.png)

### Q.2.1.2
### Pour sécuriser le compte utilisateur

- **Sécurité du mot de passe** : Choisissez un mot de passe fort en utilisant une combinaison de lettres majuscules et minuscules, chiffres et caractères spéciaux.
- **Mises à jour régulières** : Effectuez les mises à jour de sécurité régulièrement pour maintenir le système à jour et protéger contre les vulnérabilités connues.

### Q.2.2.1
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.2.1.png)

### Q.2.2.2
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.2.2.png)

### Q.2.2.3
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.2.3.png)

### Q.2.3.1
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.3.1.png)

### Q.2.3.2
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.3.2.png)

### Q.2.3.3
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.3.3.png)

### Q.2.4.1 

1. **bareos-dir**
   - **Rôle :** Gère et orchestre les sauvegardes et restaurations.

2. **bareos-sd**
   - **Rôle :** Gère les périphériques de stockage où les sauvegardes sont écrites.
  
3. **Daemon bareos-fd**
   - **Rôle :** S'exécute sur les machines à sauvegarder et envoie les données au Storage Daemon.
  
 ### Q.2.5.1      
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.5.1.png)

 ### Q.2.5.2
![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.5.2.png)

 ### Q.2.5.4
 ![Description de la photo](https://github.com/Ahmedbenrebai/Ahmedbenrebai-Chekpoint-3/blob/main/2.5.4.png)
     

 ### Q.2.6.1
  
sudo grep "Failed password" /var/log/auth.log | tail -n 10 | awk '{print $1, $2, $3, $11, $13}'


