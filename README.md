### Cloud • DevOps • Cybersecurity

Profile artwork by [Paper and Cat](https://www.instagram.com/paperandcat/)

### Sentinel

|Topic|Description|
|---|---|
|[Event collection to Sentinel](https://github.com/joetanx/sentinel/blob/main/collection/)|Various topics on events ingestion to Sentinel|
|[Windows security events collected by Sentinel](https://github.com/joetanx/sentinel/blob/main/collection/windows-security-events.md)|Write-up on the events collected by Sentinel Windows security DCR when configured for All, Common or Minimal set of Windows security events|
|[Windows event forwarding](https://github.com/joetanx/sentinel/blob/main/collection/windows-event-forwarding.md)|Windows event forwarding between machines in separate domains or WORKGROUP environments|
|[Logs ingestion API](https://github.com/joetanx/sentinel/blob/main/logs-ingestion-api/)|Ingest events to Sentinel using logs ingestion API|
|[File hash hunting](https://github.com/joetanx/sentinel/blob/main/detection/hunting-file-hash.md)|Threat hunting in Sentinel for file hash indicators with Sysmon events|
|[Domain name hunting](https://github.com/joetanx/sentinel/blob/main/detection/hunting-domain-name.md)|Threat hunting in Sentinel for domain name indicators using Sysmon and syslog events|
|[Sentinel in Defender portal](https://github.com/joetanx/sentinel/blob/main/defender-portal.md)|Walk through on connecting Sentinel workspace to Defender portal|
|[Data lake](https://github.com/joetanx/sentinel/blob/main/data-lake.md)|Write-up on Sentinel data lake use cases|

### Defender

|Topic|Link|
|---|---|
|Unified RBAC|https://github.com/joetanx/defender/blob/main/unified-rbac.md|
|Multi-tenant management|https://github.com/joetanx/defender/blob/main/mto.md|

### Microsoft Lab

|Topic|Link|
|---|---|
|Notes on setting up Configuration Manager (System Center) and other system roles to support the Endpoint Protection feature|https://github.com/joetanx/mslab/tree/main/ConfigMgr<br>|
|OAuth 2.0 flows with Entra identity|https://github.com/joetanx/mslab/blob/main/oauth-2.0-flows.md|
|Secure Azure VM access with Bastion and internet connection with Azure Firewall|https://github.com/joetanx/mslab/blob/main/firewall-bastion-natgw.md|
|Onboard VM credentials to Azure key vault to secure VM access via bastion|https://github.com/joetanx/mslab/blob/main/key-vault.md|
|Setup Azure Arc connection for on-premise Windows and Linux machines|https://github.com/joetanx/mslab/blob/main/arc.md|
|Create Azure OpenAI resource (for use with tools like n8n)|https://github.com/joetanx/mslab/blob/main/azure-openai.md|

### Cribl

|Topic|Link|
|---|---|
|Setup Cribl to ingest Windows events and Linux syslog|https://github.com/joetanx/cribl/blob/main/setup.md|
|Configure Cribl to send events to Sentinel|https://github.com/joetanx/cribl/blob/main/sentinel.md|
|Cribl pipeline examples|https://github.com/joetanx/cribl/blob/main/pipelines.md|

### Applications

|Topic|Link|
|---|---|
|Observability stack with OpenTelemetry (colllector), Prometheus (Metrics), Tempo (Traces), Loki (Logs) and Grafana (Visualization)<br>+ Node.js demo app adapted from [OpenTelemetry](https://opentelemetry.io/docs/languages/js/getting-started/nodejs/)|https://github.com/joetanx/o11y-lab|
|UsersApp Node.js|<https://github.com/joetanx/usersapp/>|
|CityApp PHP|<https://github.com/joetanx/cityapp-php/>|
|Notes and examples on using Node.js|<https://github.com/joetanx/node.js/>|
|Serverless application on AWS<br>• AJAX client end page<br>• API Gateway<br>• Lambda (Node.js)<br>• RDS (MySQL)<br>• EC2 examples with Python and Node.js|Secrets Manager: <https://github.com/joetanx/aws-rds-sm/><br>IAM Authentication: <https://github.com/joetanx/aws-rds-iam-authn/>|

### Others

|Topic|Description|
|---|---|
|[Lab Certs](https://github.com/joetanx/lab-certs)|All the lab certificates and openssl commands for self-signed certificate chain|
|[Podman](https://github.com/joetanx/setup/blob/main/podman/)|Podman setup and notes on the nuances of container networking and volume mounts|
|[Kubernetes](https://github.com/joetanx/setup/blob/main/kubernetes/)|Single-node Kubernetes setup on Ubuntu with Helm, cert-manager, Traefik and Kubernetes dashboard|
|[Traefik](https://github.com/joetanx/setup/blob/main/traefik/)|Setup Traefik for lab traffic routing; nuances on Traefik routing under [routing-notes](https://github.com/joetanx/setup/blob/main/traefik/routing-notes.md)|
|[Nginx](https://github.com/joetanx/setup/blob/main/nginx/)|Setup Nginx for reverse proxy and TLS offloading|
|[Databases](https://github.com/joetanx/setup/blob/main/databases/)|Running PostgreSQL in container for the lab services (and MySQL maybe in the future)|
|[Agent Runners](https://github.com/joetanx/setup/blob/main/agent-runners/)|Setting up n8n and Langflow for agentic AI lab|
|[OpenCTI](https://github.com/joetanx/setup/blob/main/opencti/)|Setup OpenCTI lab and various connectors|
|[Lab Services](https://github.com/joetanx/setup/blob/main/lab-services/)|Setup demo services: SmartMail SMTP, GitLab CI/CD and Keycloak IdP|
|[Web Request](https://github.com/joetanx/setup/blob/main/notes/web-request.md)|Notes on using cURL and PowerShell to make web requests|

### Archived: CyberArk stuff

|Topic|Link|
|---|---|
|Hashicorp Vault and Boundary|<https://github.com/joetanx/hashicorp>|
|Delinea Secret Server|<https://github.com/joetanx/delinea-secret-server>|
|Teleport|<https://github.com/joetanx/teleport>|
|Elastic SOC Lab + Suricata and CyberArk PAM integration|<https://github.com/joetanx/setup/blob/main/soc-lab.md>|
|Load Balancing CyberArk Servers|<https://github.com/joetanx/load-balancing-cyberark/>|

#### Conjur Setup

|Topic|Link|
|---|---|
|Setup standalone Conjur Enterprise leader on Podman on RHEL 9|<https://github.com/joetanx/setup/blob/main/conjur.md>|
|Setup Conjur Enterprise cluster and followers + Podman + RHEL 9 + Keepalived + Nginx|<https://github.com/joetanx/conjur-cluster/>|
|Setup Conjur Open Source Suite on RHEL with Podman|<https://github.com/joetanx/conjur-oss/>|

#### CyberArk Secrets Manager Integrations

|Topic|Link|
|---|---|
|Kubernetes|cje: <https://github.com/joetanx/conjur-k8s/><br>cjc: <https://github.com/joetanx/cjc-k8s/>|
|GitLab|cje <https://github.com/joetanx/conjur-gitlab/><br>cjc: <https://github.com/joetanx/cjc-gitlab/>|
|Openshift|<https://github.com/joetanx/conjur-ocp/>|
|Jenkins|<https://github.com/joetanx/conjur-jenkins/>|
|Terraform|<https://github.com/joetanx/conjur-terraform/>|
|Ansible Automation Platform|<https://github.com/joetanx/cybr-aap/>|
|Ansible Core|<https://github.com/joetanx/conjur-ansible/>|
|Puppet|<https://github.com/joetanx/conjur-puppet/>|
