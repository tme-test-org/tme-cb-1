# Content brief on objection handling for platform security

## Goal
To convince the reader of the level of security of the Aviatrix platform and take away any concerns for implementing it in their environment.

## Key take aways

### Mutual TLS
Aviatrix leverages mutual TLS between gateways and the controller. This ensures communication is secure and can only take place between trusted components.

### Security Group Orchestration
Aviatrix orchestrates security groups on all it's platform components. This prevents exposure of it's (public) IP's from any other source than known and trusted sources.