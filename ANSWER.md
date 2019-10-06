# Answers

Nom : Soyeux 
Prénom : olivier

# 1.
Qu'est-ce qu'une instance EC2 ?
Une instance EC2 est un serveur virtuel hébergé dans Elastic Compute Cloud (EC2) pour exécuter des applications sur l'infrastructure Amazon Web Services (AWS).

AWS est une plateforme de Cloud computing ; EC2 est un service qui permet d'exécuter des programmes applicatifs. Le service EC2 peut servir de parc à un nombre quasiment illimité de machines virtuelles.

# 2.
Qu'est-ce qu'un VPC ?

 Un Virtual Private Cloud (VPC) est un groupe de ressources informatiques configurables à la demande dans un environnement de cloud public, qui fournit un certain niveau d'isolement entre les différentes organisations ( utilisateurs) qui utilisent ces ressources. L'isolation entre le VPC et les autres utilisateurs du cloud est habituellement obtenue par l'utilisation d'un sous-réseau IP et d'un mécanisme de communication virtuel (tel qu'un VLAN ou un groupe de canaux chiffrés) pour chaque utilisateur.
  Dans un VPC, le mécanisme pour fournir une isolation dans le cloud est complété par un service de VPN (pour chaque utilisateur) qui garantit la sécurité de l'accès des utilisateurs à distance aux ressources, grâce à un système d'authentification et de cryptographie.
  Grâce à ces mécanismes d'isolement, l'organisation qui utilise le service travaille actuellement sur un 'nuage privé virtuel' d'où le nom VPC.
  Les VPC sont couramment utilisés dans le contexte de l'infrastructure en tant que service (IaaS). Dans ce contexte, le fournisseur d'infrastructure (nuage) et le fournisseur de services VPC sur cette infrastructure pourraient être des entreprises différentes.

# 3.
A quoi sert un NSG ?

Les NGS ou bien Network Security Group correspondent à ce que l’on appelle des matrices de flux. Il s’agit  d’un pare-feu logiciel qui s’applique sur différents éléments azure:

Cartes réseaux/serveurs
Base de données
Passerelle VPN
Sous réseau
Tag/balise (depuis le 15 janvier)

# 4.
Quelles sont les 5 propriétés désirables du cloud ?

Paiement à l'usage
Elastique
Ouvert
Mutualisé
Libre-service

# 5.
Qu'est-ce que l'A/B Testing ?

L’A/B testing consiste à comparer deux versions d’une page web ou d’une application afin de vérifier laquelle est la plus performante. Ces variations, dénommées A et B, sont présentées de manières aléatoires aux utilisateurs. Une partie d’entre eux sera alors dirigée vers la première version tandis que l’autre sera affectée à la seconde.

# 6.
Comment programmer le cloud ?
avec infra as code

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?

Le Zero Downtime Deployment (ZDD) est une technique qui permet de déployer une nouvelle version d'un système sans intérompre le service. Le Blue/Green Deployment, le Canary Release et le Dark Launch sont différente variantes qui reprennent cette technique

# 8.
Qu'est-ce que le Canary release ?

permet de confronter la version N+1 à une population restreinte d’utilisateurs, tandis que la majorité des utilisateurs ont accès à la version N. Les mécanismes sont identiques au Blue/Green Deployment.

# 9.
Comment changer de taille de machine virtuelle ?
ouvrir le gestionnaire de machine, puis aller dans menu Fichier, Gestionnaire de médias. Ici selectionner le disque dur dont vous souhaitez moodifier la taille et cliquer sur "propriétés". pour finir, aller dans l'onglet "attributs".  Il suffit de choisir la taille du disque que l'on souhaite l'appliquer.

# 10.
Qu'est-ce que le Blue/Green deployment ?
pattern classique de ZDD. Il suppose que l’application soit hébergé sur au moins deux chaînes applicatives, puisque l’objectif est de déployer la version N+1 d’une application sur une des chaînes, tandis que le service est maintenu sur les chaînes encore en version N.

