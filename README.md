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

|Topic|Description|
|---|---|
|[Defender access control](https://github.com/joetanx/defender/blob/main/unified-rbac.md)|Granular access control in Defender with Unified RBAC, device groups and cloud scopes|
|[Multi-tenant management](https://github.com/joetanx/defender/blob/main/mto.md)|Setup multi-tenant Defender for B2B tenants|

### Microsoft Lab

|Topic|Description|
|---|---|
|[Microsoft Foundry](https://github.com/joetanx/mslab/blob/main/foundry.md)|• Setup AI resources in Azure<br>• Connect to models via API endpoint and key (for use with tools like n8n and Langflow)|
|[Entra OAuth 2.0 flows](https://github.com/joetanx/mslab/blob/main/oauth-2.0-flows.md)|Flow sequence diagram and examples for:<br>• Client credential flow with client secrets ant certificate<br>• Authorization code flow|
|[Azure perimeter network](https://github.com/joetanx/mslab/blob/main/firewall-bastion-natgw.md)|Secure Azure virtual network:<br>• VM access with Bastion<br>• Outbound internet connection with Azure Firewall and NAT gateway|
|[Key vault](https://github.com/joetanx/mslab/blob/main/key-vault.md)|Onboard VM credentials to key vault to secure VM access via bastion|
|[Azure Arc](https://github.com/joetanx/mslab/blob/main/arc.md)|Connect on-premise Windows and Linux machines for Azure hybrid cloud management|
|[Configuration manager](https://github.com/joetanx/mslab/tree/main/ConfigMgr/)|• Setup Configuration Manager and system roles<br>• Setup Endpoint Protection feature|

### Cribl

|Topic|Description|
|---|---|
|[Setup Cribl](https://github.com/joetanx/cribl/blob/main/setup.md)|Install Cribl and configure syslog and WEF data sources|
|[Cribl to Sentinel](https://github.com/joetanx/cribl/blob/main/sentinel.md)|• Setup Entra app registration for Cribl<br>• Setup data collection endpoint/rule<br>• Configure Sentinel data destination<br>• Routing events to Sentinel|
|[Cribl pipelines](https://github.com/joetanx/cribl/blob/main/pipelines.md)|• Pipeline to process syslog and WEF events<br>• Map parameters to schema of Sentinel native `Syslog` and `SecurityEvent` tables|

### Applications

|Topic|Description|
|---|---|
|[Observability lab](https://github.com/joetanx/o11y-lab)|Observability stack with:<br>• OpenTelemetry (collector)<br>• Prometheus (metrics)<br>• Tempo (traces<br>• Loki (logs)<br>• Grafana (visualization)<br>+ Node.js demo app adapted from [OpenTelemetry](https://opentelemetry.io/docs/languages/js/getting-started/nodejs/)|
|[UsersApp](https://github.com/joetanx/usersapp/)|Example Node.js application on user authentication service<br>• Publish web app through Express framework<br>• Example user pages and API endpoints<br>• Backend databases on both MySQL and PostgreSQL<br>• User credential hashing with bcrypt<br>• Session management with JWT cookie<br>• Deployment methods: Kubernetes, Podman quadlets and manual install|
|[CityApp](https://github.com/joetanx/cityapp-php/)|Simple PHP application: fetch a random row from example world database|
|CityApp in Node.js and Python with:<br>• [Secrets Manager](https://github.com/joetanx/aws-rds-sm/)<br>• [IAM Authentication](https://github.com/joetanx/aws-rds-iam-authn/)|Serverless application on AWS<br>• AJAX client-end web page<br>• API Gateway<br>• Lambda (Node.js)<br>• Database on RDS (MySQL)<br>+ EC2 examples with Python and Node.js|
|[Node.js notes](https://github.com/joetanx/node.js/)|• Understanding functions and variables<br>• Using exports and module.exports<br>• Using callbacks and promises<br>•	Connecting node.js to MySQL database|

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
|Elastic SOC Lab + Suricata and CyberArk PAM integration|<https://github.com/joetanx/setup/blob/main/archived/soc-lab.md>|
|Load Balancing CyberArk Servers|<https://github.com/joetanx/load-balancing-cyberark/>|

#### Conjur Setup

|Topic|Link|
|---|---|
|Setup standalone Conjur Enterprise leader on Podman on RHEL 9|<https://github.com/joetanx/setup/blob/main/archived/conjur.md>|
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
