# Self-hosted

Self-hosted is a collection of Ansible playbooks designed to deploy and update your self-hosted applications. While it can be used directly with Ansible, it was specifically created with [Semaphore](https://semaphoreui.com/) in mind to provide a more user-friendly experience.

## How To

- **OPTIONAL**:Install [Netmaker](https://www.netmaker.io/) to create a mesh VPN between hosts on different networks, allowing them to securely connect and communicate.
    - Install NetClient on the hosts you want to designate as nodes
    - Add Egress Rules to be allow communication between networks
    - Add Gateway to connect devices as clients. **(Note)**: you might need to design a custom DNS for it to work proprely.

- **RECOMMENDED** Install [Semaphore](https://semaphoreui.com/) a web-based interface for managing Ansible automation tasks. It provides a user-friendly, intuitive platform to run, monitor, and manage Ansible playbooks, making automation accessible even for those with limited command-line experience.

    - Set Repository
    - Set credentials in the **Key Store** (github if needed, hosts credentials)
    - Set inventory (hosts you want to target)
    - Set Variable Groups (list of variables to set in env-library)
    - Create  Tasks
    - Schedule updates tasks
    
    ### Playbooks

- **Gateway Apps**

- [Authentik](https://goauthentik.io/): SSO Provider
- (To be added)[Nginx-Proxy-Manager](https://nginxproxymanager.com/): Reverse Proxy
- [wg-easy](https://github.com/wg-easy/wg-easy): Wireguard VPN + GUI (alternative to Netmaker client)
- (To be added)[DDNS-go](https://github.com/jeessy2/ddns-go) Public IP updater


