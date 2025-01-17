---
categories:
  - cloud
  - aws
ddtype: crawler
dependencies: []
description: "Surveillez des métriques clés d'Amazon\_Elemental\_MediaConvert."
doc_link: 'https://docs.datadoghq.com/integrations/amazon_mediaconvert/'
git_integration_title: amazon_mediaconvert
has_logo: true
integration_title: "Amazon\_Elemental\_MediaConvert"
is_public: true
kind: integration
manifest_version: 1
name: amazon_mediaconvert
public_title: "Intégration Datadog/Amazon\_Elemental_MediaConvert"
short_description: "Surveillez des métriques clés d'Amazon\_Elemental\_MediaConvert."
version: 1
---
## Présentation
Amazon Elemental MediaConvert est un service de transcodage et de compression de contenu vidéo hors ligne en vue de leur diffusion sur une télévision ou un appareil connecté.

Activez cette intégration pour visualiser dans Datadog toutes vos métriques d'Elemental MediaConvert.

## Implémentation
### Installation
Si vous ne l'avez pas déjà fait, configurez d'abord [l'intégration Amazon Web Services][1].

### Collecte de métriques
1. Dans le [carré d'intégration AWS][2], assurez-vous que l'option `MediaConvert` est cochée dans la section concernant la collecte des métriques.

2. Installez l'[intégration Datadog/Amazon Elemental MediaConvert][3].

## Données collectées
### Métriques
{{< get-metrics-from-git "amazon_mediaconvert" >}}


### Événements
L'intégration Amazon Elemental MediaConvert n'inclut aucun événement.

### Checks de service
L'intégration Amazon Elemental MediaConvert n'inclut aucun check de service.

## Dépannage
Besoin d'aide ? Contactez [l'assistance Datadog][5].

[1]: https://docs.datadoghq.com/fr/integrations/amazon_web_services
[2]: https://app.datadoghq.com/account/settings#integrations/amazon_web_services
[3]: https://app.datadoghq.com/account/settings#integrations/amazon-mediaconvert
[4]: https://github.com/DataDog/dogweb/blob/prod/integration/amazon_mediaconvert/amazon_mediaconvert_metadata.csv
[5]: https://docs.datadoghq.com/fr/help/


{{< get-dependencies >}}