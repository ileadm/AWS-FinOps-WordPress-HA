# Déploiement de WordPress High Availability by Bitnami avec le nouveau AWS Quick Start

Publié le : 17 septembre 2018

Ce Quick Start déploie WordPress High Availability by Bitnami, qui comprend WordPress avec Amazon Aurora, dans un environnement hautement disponible sur AWS en environ 40 minutes.

## À propos de WordPress High Availability by Bitnami

WordPress est une plate-forme de publication web pour l’intégration de blogs et de sites web. Elle peut être personnalisée via un large choix de thèmes, d’extensions et de plugins. WordPress High Availability by Bitnami installe l’application WordPress sur de nombreuses instances Amazon EC2 dans l’AWS Cloud pour une performance et une disponibilité élevées. Il définit également la base de données relationnelle Amazon Aurora afin de vous aider à réduire les coûts, à simplifier les tâches de configuration et à la mettre à l’échelle facilement. La base de données et l’application WordPress sont configurées sur différentes instances EC2 pour améliorer la sécurité et le contrôle d’accès.

## Public cible

Ce Quick Start est prévu pour les architectes d’infrastructure, les administrateurs et les professionnels DevOps qui planifient de mettre en place ou d’étendre leurs charges de travail WordPress sur l’AWS Cloud.

## Pour commencer

- Consultez [l'architecture et les détails](lien_vers_l_architecture_et_les_details)
- Consultez le [manuel de déploiement](lien_vers_le_manuel_de_deploiement) pour obtenir des instructions détaillées

## Étapes pour Exécuter
Pour lancer l'ensemble de la pile et déployer un site WordPress sur AWS, cliquez sur l'un des liens ***Lancer la Pile*** ci-dessous ou téléchargez le modèle principal et lancez-le localement.

Vous pouvez lancer cette pile CloudFormation, en utilisant votre compte, dans les régions AWS suivantes :

| Code de la région AWS | Nom | Lancement |
| --- | --- | --- 
| us-east-1 |US Est (Virginie du Nord)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |
| us-east-2 |US Est (Ohio)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |
| us-west-2 |US Ouest (Oregon)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |
| eu-west-1 |UE (Irlande)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |
| eu-central-1 |UE (Francfort)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |
| ap-southeast-2 |AP (Sydney)| [![cloudformation-launch-stack](images/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/new?stackName=FORM-AWS-FinOps-WordPress-HA-XXX&templateURL=https://s3.eu-west-3.amazonaws.com/detailled-report.ilki.fr/Template/wordpress-master.template) |


Vous pouvez également télécharger les modèles AWS CloudFormation qui automatisent le déploiement à partir de [GitHub](lien_vers_le_repo_GitHub).


Les Quick Starts sont des déploiements de référence automatisés qui utilisent les modèles AWS CloudFormation pour déployer des technologies clés sur AWS, conformément aux bonnes pratiques AWS. Ce démarrage rapide a été construit par Bitnami en collaboration avec les architectes des solutions AWS. Bitnami est un partenaire technologique avancé des services AWS.
