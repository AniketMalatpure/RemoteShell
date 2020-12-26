# RemoteShell
Secure, open protocol remote shell to run commands on personal computers hosted behind NAT, Firewall with no network changes needed

# Components
This project has 3 components as seen below:
| Name | Role |
|------|------|
| Worker | Is installed on the computer you wish to manage remotely <br/> This computer needs outbound access to Azure. <br/> In most cases the above connectivity is present <br/> No firewall or NAT changes for inbound internet connectivity are needed |
| Controller | Is installed on the computer from which you manage other workers <br/> This computer needs outbound access to Azure. <br/> In most cases the above connectivity is present <br/> No firewall or NAT changes for inbound internet connectivity are needed |
| Hybrid Connector | An instance of Azure Relay Service is setup to facilitate bidirectional communication between the Controller and its worker nodes |

# Installation

## Setup Hybrid Connector

### Pre-requisites

### Steps

### Verification

## Setup Worker

### Pre-requisites

### Steps

### Verification

## Setup Controller

### Pre-requisites

### Steps

### Verification

## End to End Verification

# Typical Usage



