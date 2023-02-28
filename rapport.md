# Rapport de contribution - EC Développement Logiciel Libre

Axel LABARRE Théo MONTAIGU  
25 février 2023

# Introduction

Il s'agit d'une application mobile Android open source d'une simple calculatrice "Simple-Calculator" faisant partie d'une suite complète de plusieurs autres applications "SimpleMobileTools".  

## Repository Github

* **URL** : [GitHub Simple-Calculator](https://github.com/SimpleMobileTools/Simple-Calculator)  

* **Issue** : Input is lost when the screen rotates #299
* **Lien de l'issue** : [https://github.com/SimpleMobileTools/Simple-Calculator/issues/299](https://github.com/SimpleMobileTools/Simple-Calculator/issues/299)
* **Lien Pull Request** : [https://github.com/SimpleMobileTools/Simple-Calculator/pull/305](https://github.com/SimpleMobileTools/Simple-Calculator/pull/305)

## Description de l'issue

Lorsque l'on utilise la calculatrice et qu'on affiche une formule ou un résultat, lors de la rotation du mobile, toutes les donnés précédentes sont perdues. Cela provient du fait que la rotation du téléphone provoque la fin de l'activité courante (qui contient les données de calcul), et la création d'une nouvelle activité. Cette suite d'évènements est normale pour une application mobile. Cependant il est nécessaire d'implémenter une sauvegarde et une transmission des données entre les activités si nous ne voulons pas que le calcul courant soit écraser lors de la rotation.

### Environement technique

* **Logiciel IDE** : Android Studio 2022  
(Runtime version : 11.0.15  
VM : Op enJDK 64-Bit Server VM by JetBrains s.r.o.)  
* **Langage** : Kotlin 221-1.8.0-release-for-android-studio-AS5591.52
* **Conventions à respecter** :
  - camelCase,  
  - Formattage de code (Build.Editor Android Studio),  
  - Suppression des imports inutiles (Android Studio)  
  
* **Règles de contribution** : [Règles de contribution](https://github.com/SimpleMobileTools/General-Discussion#how-do-i-suggest-an-improvement-ask-a-question-or-report-an-issue)

# Fil de contribution

# vers une Pull Request

# Conclusion personnelle
