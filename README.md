# awesome-vault-tools
Awesome tools around HashiCorp Vault

# UI
- https://github.com/djenriquez/vault-ui Vault-UI — A beautiful UI to manage your Vault, written in React
- https://github.com/Caiyeon/goldfish - A HashiCorp Vault UI panel written with VueJS and Vault native Go API 
  - Demo: https://vault-ui.io
- https://github.com/nyxcharon/vault-ui -  A webapp for working with Hashicorp's Vault

# Plugins
- https://github.com/nhuff/vault-plugin-auth-chefnode - The "chef-node" auth backend allows Nodes registered with a Chef server to authenticate using their private keys.
- https://github.com/fcantournet/kubernetes-flexvolume-vault-plugin - A kubernetes flexvolume plugin that injects vault tokens at pod creation
- https://github.com/sethvargo/vault-secrets-gen - A Vault secrets plugin for generating high entropy passwords and passphrases.
- https://github.com/sethvargo/vault-auth-slack - The Vault Auth Slack method is a Vault auth method plugin for authenticating users via Slack. The plugin can run in multiple different "modes" depending on your desired user workflow and risk tolerance. This is both a real custom Vault auth method, and an example of how to build, install, and maintain your own Vault auth plugin.
- https://github.com/gites/vault-auth-file - HashiCorp Vault authentication plugin for authenticating via Unix password like file.

# Ops
- https://github.com/UKHomeOffice/vaultctl - Vaultctl is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
- https://github.com/cloudwatt/vault-sync - Vault-sync is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
- https://github.com/jaxxstorm/unseal - **[deprecated]** A command line tool to unseal multiple Hashicorp Vault servers quickly
- https://github.com/jaxxstorm/hookpick - A tool to manage some operational concepts of Hashicorp Vault
- https://github.com/paywithcurl/vault-update - The vault client does not allow for a single key in a secret to be updated, the current work around is

# Users
- https://github.com/Mykolaichenko/gotools/tree/master/vaulter - Vaulter extends default Hashicorp Vault client, implements additional methods like list all backend path, dynamically read value, search in all backend and so on.
- https://github.com/apptio/breakglass - Breakglass is a tool that will make API calls to Hashicorp Vault servers and then retrieve credentials for you. It's designed to ease the process of getting elevated login credentials for a variety of servers. It currently supports MySQL servers and SSH Command line access.

# K8s
*Note: There is now official plugin for k8s: https://www.vaultproject.io/docs/auth/kubernetes.html*
- https://github.com/keyparty/vault-init - K8s Init Container for Vault Token Generation and Retrieval
- https://github.com/kelseyhightower/vault-controller - The Vault Controller automates the creation of Vault tokens for Kubernetes Pods. This repo includes a set of hands-on tutorials and example programs you can use to try out the Vault Controller.
- https://github.com/Boostport/kubernetes-vault - The Kubernetes-Vault project allows pods to automatically receive a Vault token using Vault's AppRole auth backend.

# Other
- https://github.com/asteris-llc/vaultfs - VaultFS mounts arbitrary Vault prefixes in a FUSE filesystem. It also provides a Docker volume plugin to the do the same for your containers.
