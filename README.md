---

# **Projet DevOps - Lina Zili**

---

## **🔹 Description**

Ce projet illustre la mise en place d’un pipeline **DevOps automatisé** pour une application Java.
Il inclut :

* **Gestion de code sur GitHub** avec suivi des commits et Pull Requests
* **CI/CD** avec GitHub Actions et Jenkins
* **Construction, archivage et déploiement automatique** de l’application

---

## **🔹 Structure du dépôt**

Le dépôt contient :

```
Projet-DevOps-ZiliLina/
├─ README.md
├─ hello-devops/          # Code source de l'application
├─ Jenkinsfile            # Définition du pipeline Jenkins
└─ .github/               # Configuration des workflows GitHub Actions
```

📸 **Arborescence du repo sur GitHub** <img width="1634" height="615" alt="image" src="https://github.com/user-attachments/assets/50408111-24c3-4a68-b3d7-8bac92fd87d7" />

---

## **🔹 Workflow GitHub Actions**

Le workflow GitHub Actions automatise :

* Compilation
* Tests unitaires
* Packaging

📸 **Workflow GitHub Actions avec succès** <img width="2228" height="1235" alt="image" src="https://github.com/user-attachments/assets/50012789-7e5a-4aff-88d4-45dc9a704e24" />

---

## **🔹 Pull Request**

Les modifications ont été fusionnées dans la branche `main` via une Pull Request.

📸 **PR dev → main, mergée avec succès** <img width="2227" height="1244" alt="Screenshot 2026-01-11 103523" src="https://github.com/user-attachments/assets/78506237-0c43-48d2-94c5-c4fa31318721" />

---

## **🔹 Jenkins Pipeline**

Le pipeline Jenkins automatise :

1. **Checkout** du code depuis GitHub
2. **Build Maven**
3. **Archivage** du fichier `.jar`
4. **Déploiement**

### 🔸 Pipeline lancé

📸 **Build History avec dernière build verte** <img width="1153" height="905" alt="image" src="https://github.com/user-attachments/assets/88f4ded8-d659-4755-af51-d448a8a2430f" />

### 🔸 Archive

📸 **Last Successful Artifacts** <img width="1428" height="862" alt="image" src="https://github.com/user-attachments/assets/a093a3e3-327f-45ad-a15d-14c0c256ffb4" />

### 🔸 Post actions

📸 **Message Application déployée avec succès** <img width="1762" height="1150" alt="image" src="https://github.com/user-attachments/assets/00a3e9d1-9650-43fd-8b46-30d040cc61b9" />

---

## **🔹 Slack (optionnel)**

J’ai rejoint Slack pour le projet mais **la notification n’a pas été testée**.

<img width="1758" height="913" alt="image" src="https://github.com/user-attachments/assets/5ef952c1-e3ac-41eb-8f3a-4139a5c18ed2" />

---

## **🔹 Conclusion**

Ce projet démontre une intégration complète des pratiques **DevOps** :
**suivi Git**, **CI/CD automatisé**, et **déploiement continu via Jenkins**.

---
