---
aliases:
  - /fr/integrations/azure_notificationhubs
categories:
  - cloud
  - azure
ddtype: crawler
dependencies: []
description: Surveillez des métriques clés d'Azure Notification Hubs.
doc_link: 'https://docs.datadoghq.com/integrations/azure_notification_hubs/'
git_integration_title: azure_notification_hubs
has_logo: true
integration_title: Microsoft Azure Notification Hubs
is_public: true
kind: integration
manifest_version: 1
name: azure_notification_hubs
public_title: Intégration Datadog/Microsoft Azure Notification Hubs
short_description: Surveillez des métriques clés d'Azure Notification Hubs.
version: 1
---
## Présentation

Azure Notification Hubs est un service de notifications Push facile à utiliser et évolutif qui vous permet d'envoyer des notifications vers n'importe quelle plateforme (iOS, Android, Windows, Kindle, Baidu, etc.) depuis n'importe quel backend (cloud ou local).

Utilisez l'intégration Datadog/Azure pour recueillir des métriques d'Azure Notification Hubs.

## Implémentation
### Installation

Si vous ne l'avez pas déjà fait, configurez d'abord [l'intégration Microsoft Azure][1]. Aucune autre procédure d'installation n'est requise.

## Données collectées
### Métriques
{{< get-metrics-from-git "azure_notification_hubs" >}}


### Événements
L'intégration Azure Notification Hubs n'inclut aucun événement.

### Checks de service
L'intégration Azure Notification Hubs n'inclut aucun check de service.

## Dépannage
Besoin d'aide ? Contactez [l'assistance Datadog][2].



{{< get-dependencies >}}
[1]: https://docs.datadoghq.com/fr/integrations/azure
[2]: https://docs.datadoghq.com/fr/help
