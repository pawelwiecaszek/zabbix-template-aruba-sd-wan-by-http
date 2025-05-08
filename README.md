# Aruba SD-WAN by HTTP

## Overview

For Zabbix version: 7.0 and higher  
The template to monitor Aruba SD-WAN by Zabbix that work without any external scripts.

## Setup

You must set {$API_KEY} macro and host name to the orchestrator url (xxxxxx-orch-euc1.silverpeak.cloud).

You have to create API token in Orchestrator and use it in {$API_KEY} macro. Read detailed instructions how to create token indocumentation [documentation](https://arubanetworking.hpe.com/techdocs/sdwan/docs/orch/orchestrator/server/api-key/)

## Zabbix configuration

No specific Zabbix configuration is required.

### Macros used

| Name       | Description     | Default |
| ---------- | --------------- | ------- |
| {$API_KEY} | <p>API key.</p> | `.*`    |

## Template links

There are no template links in this template.
