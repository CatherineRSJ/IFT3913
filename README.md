# IFT3913 - Qualité du logiciel 

Ce cours est offert à l'automne 2024. Il est organisé suivant le calendrier ci-dessous.

Avec ce cours, les étudiant(e)s auront acquis les compétences suivantes: 
* évaluation automatique de la qualité logicielle
* concepts fondamentaux du test logicel: données, scénarios, oracles
* apprentissage par diverses sources de connaissances
* curiosité et humour pour le logiciel

Les étudiant(e)s sont évalué(e)s sur la base de 3 [tâches](https://github.com/umontreal-diro/IFT3913/blob/main/README.md#t%C3%A2ches), suivant les [critères](https://github.com/umontreal-diro/IFT3913/blob/main/README.md#crit%C3%A8res-d%C3%A9valuation) énoncés ci-dessous.


## Semaine #1 jeudi 5 septembre: Introduction
- présentation du cours et des modalités
- matériel préparatoire: [Operational Excellence](https://dl.acm.org/doi/pdf/10.1145/3155112.3171529)
 
## Semaine #2 jeudi 12 septembre: Études de cas
- Cas d'études: qualité pour le logiciel open source
- matériel préparatoire: [How Developers Engineer Test Cases: An Observational Study]([https://github.com/apache/pdfbox](https://azaidman.github.io/publications/anicheTSE2022.pdf))
 
## Semaine #3 jeudi 19 septembre: [Test unitaire](https://github.com/umontreal-diro/IFT3913/issues/2)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Unit Tests for SQL](https://ieeexplore.ieee.org/iel7/52/10372482/10372508.pdf)
 
## Semaine #4 jeudi 26 septembre: [Couverture de code](https://github.com/umontreal-diro/IFT3913/issues/3)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Code Coverage Best Practices](https://testing.googleblog.com/2020/08/code-coverage-best-practices.html)
 
## Semaine #5 jeudi 3 octobre: [Test unitaire avancé](https://github.com/umontreal-diro/IFT3913/issues/4) 
- Introduction + présentations d'étudiants
- matériel préparatoire: [Handling Flaky Unit Tests in Java](https://www.uber.com/en-CA/blog/handling-flaky-tests-java/)
 
## Semaine #6 jeudi 10 octobre: [Couverture de code avancée](https://github.com/umontreal-diro/IFT3913/issues/5)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Testing beyond coverage](https://increment.com/reliability/testing-beyond-coverage/)

## Semaine #7 jeudi 17 octobre: [Test statique](https://github.com/umontreal-diro/IFT3913/issues/6)
- Introduction + présentations d'étudiants
- matériel préparatoire: [What is Clean Code?](https://www.sonarsource.com/blog/what-is-clean-code/)

## Semaine #8 jeudi 31 octobre: [Gestion des dépendances](https://github.com/umontreal-diro/IFT3913/issues/7)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Surviving software dependencies](https://dl.acm.org/doi/pdf/10.1145/3347446)
 
## Semaine #9 jeudi 7 novembre: [Tester la diversité d'environnements](https://github.com/umontreal-diro/IFT3913/issues/8)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Cross Browser Testing Overview](https://www.datadoghq.com/knowledge-center/cross-browser-testing/)
 
## Semaine #10 jeudi 14 novembre: [Test et humour](https://github.com/umontreal-diro/IFT3913/issues/9)
- Introduction + présentations d'étudiants
- matériel préparatoire: [With Great Humor Comes Great Developer Engagement](https://arxiv.org/pdf/2312.01680)
 
## Semaine #11 jeudi 21 novembre: [Tester dans un domaine spécifique](https://github.com/umontreal-diro/IFT3913/issues/10)
- Introduction + présentations d'étudiants
- matériel préparatoire: [Mobile Game Testing: Types, Tools, and More](https://game-ace.com/blog/mobile-game-testing/)
 
## Semaine #12 jeudi 28 novembre: [Test en production](https://github.com/umontreal-diro/IFT3913/issues/11)
- Introduction + présentations d'étudiants
- matériel préparatoire: [I test in prod](https://increment.com/testing/i-test-in-production/)
 
## Semaine #13 jeudi 5 décembre: conclusion + tampon 
- Présentations d'étudiants
- matériel préparatoire: [On the Costs and Benefits of Adopting Lifelong Learning for Software Analytics](https://dl.acm.org/doi/pdf/10.1145/3639477.3639717)

# Tâches
- tâche #1: présentation individuelle (40%). date limite: jour du cours
- tâche #2: augmentation d'une suite de tests automatique (30%). date limite: jeudi 10 octobre, 17h EST 
- tâche #3: automatisation des tests sur divers environnements. date limite: jeudi 14 novembre, 17h EST

# Critères d'évaluation

## Tâche #1: présentation

| critère | description |
|-------------------------------------------- | ----|
|temps | la présentation dure entre 6.30 min et 7.30 min (limite stricte)|
|structure | la présentation est bien structurée et la structure est annoncée et visible |
|introduction | la présentation inclut une introduction qui motive l'importance du sujet pour la qualité logicielle|
|contenu | la présentation inclut une partie technique avec des extraite de codes, lisibles|
|originalité | la présentation inclut un point original |
|réflection | la présentation inclut une partie réflection / recul sur le sujet|
|conclusion | le dernier slide inclut un message clair et pratique pour l'audience|
|compréhension | l'orat(rice.eur) montre une maitrise et compréhension claire du sujet et peut répondre aux questions de l'audience |
|élocution | l'orat(rice.eur) parle clairement, avec assurance, et interagit avec l'audience. le sens de l'humour responsable est apprécié  |
|slides | les slides sont lisibles, n'incluent pas trop de texte et contiennent des illustrations |
|sources | la présentation s'appuie sur au moins 3 sources extérieures qui sont citées en bas de page et sont publiquement accessibles|


La limite de temps est obligatoire. Tous les autres critères comptent pour un point.

## Tâche #2: tests unitaires automatiques

| critère | description |
|-------------------------------------------- | ----|
| tests 		| 10 nouveaux tests qui n'étaient pas présents dans la version initiale du repo| 
| oracle		| chaque test inclut un oracle qui vérifie, automatiquement, que le programme a le comportement attendu| 
| intention 	| chaque test a une intention claire documentée dans un commentaire| 
| structure 	| les tests sont organisés en suivant le pattern AAA (arrange-act-assert)| 
| documentation 	| le repo inclut une page qui documente où se trouvent les nouveaux tests et justifie les choix des méthodes testées| 
| qualité 	| la mesure de la couverture est automatisée et l'exécution des nouveaux tests augmente la couverture de code| 
| exécution 	| les tests, y compris les 10 nouveaux, s'exécutent avec succès dans une Github action| 

Le critère d'exécution est très fortement conseillé, et chaque critère compte pour un point.

Si l'action ne s'exécute pas correctement, la note maximale pour cette tâche ne pourra pas dépasser 4/10.

Bonus: l'action exécute une analyse par mutation.


## Tâche #3: test sur divers environnements

| critère | description |
|-------------------------------------------- | ----|
| flags | l'action exécute le build (y compris les tests) avec 5 flags différents de la JVM |
| scénario | le repo indique clairement comment exécuter l'action sur la version initiale du repo et sur la version avec les nouveaux tests|
| documentation | le repo de l'action inclut une page qui documente les différents éléments du repo |
| structure | l'action génère des logs clairs qui documente quels flags sont exécutés |
| intention | l'intention de qualité est clairement documentée: le choix de chaque flag est justifiée vis-à-vis de son impact possible sur la qualité |
| qualité | la mesure de la couverture est automatisée et le taux de couverture avec chaque flag est documenté |
| humour | le repo inclut un élément d'humour responsable |
| exécution | l'action s'exécute avec succès sur le repo initial et sur le repo avec les nouveaux tests |

Le critère d'exécution est très fortement conseillé, et chaque critère compte pour un point.

Si l'action ne s'exécute pas correctement, la note maximale pour cette tâche ne pourra pas dépasser 4/10.

Bonus: les commits pour développer cette action sont documentés avec [lolcommits](https://github.com/lolcommits/lolcommits).

