# devsecops2

# Project Documentatie

## Overzicht

Dit project beschrijft de implementatie van een geautomatiseerde DevOps-omgeving voor applicatiebeheer, inclusief installatie, versiebeheer, monitoring, CI/CD-pipelines en containerhosting.

## Onderdelen

### Gitea-installatie

Ik heb Gitea geautomatiseerd geïnstalleerd met Ansible. Hierdoor kan ik Gitea consistent en zonder handmatige stappen opzetten, wat zorgt voor een betrouwbare versiebeheersetup.

### Branching en versiebeheer

Ik gebruik semantische versioning om mijn releases te beheren. De versie "2.0.2" staat ingesteld in `package-lock.json`, zodat elke wijziging overzichtelijk en traceerbaar is.

### Monitoring

Ik heb monitoring opgezet voor de volledige infrastructuur met Prometheus en Grafana. Hiermee kan ik statistieken zoals CPU-gebruik in de gaten houden. Alerting is op dit moment nog niet toegevoegd.

### Automatische pipeline

Ik heb Gitea Actions gebruikt om een CI/CD-pipeline in te richten. Deze pipeline voert automatisch builds, tests en deployments uit bij elke codewijziging, wat het ontwikkelproces versnelt en fouten vermindert.

### Pipeline gebruik

De pipeline doorloopt de stappen voor build, test en deploy. Dit zorgt ervoor dat de applicatie snel en zonder handmatige acties naar productie kan.

### Applicatie hosting

De applicatie draait in een container en is toegankelijk via een webinterface. Voor nu sla ik versies nog niet op in Docker Hub, maar de applicatie is operationeel en makkelijk te beheren.

## Conclusie

Deze opzet biedt een efficiënte en consistente workflow voor applicatiebeheer en -implementatie.
