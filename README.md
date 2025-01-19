# Self-hosted

Self-hosted is a collection of Ansible playbooks designed to deploy and update your self-hosted applications. While it can be used directly with Ansible, it was specifically created with [Semaphore](https://semaphoreui.com/) in mind to provide a more user-friendly experience.

## How To

- **OPTIONAL**:Install [Netmaker](https://www.netmaker.io/) to create a mesh VPN between hosts on different networks, allowing them to securely connect and communicate.

- **RECOMMENDED** Install [Semaphore](https://semaphoreui.com/) a web-based interface for managing Ansible automation tasks. It provides a user-friendly, intuitive platform to run, monitor, and manage Ansible playbooks, making automation accessible even for those with limited command-line experience.

    - Set Repository
    - Set credentials in the **Key Store** (github if needed, hosts credentials)
    - Set inventory (hosts you want to target)
    - Set Variable Groups (list of variables to set in env-library)
    - Create  Tasks
    - Schedule updates tasks
    
    
### Playbooks

<details open>
<summary>Gateway Apps</summary>

* Authentik

</details>

<details open>
<summary>Cloud Apps</summary>

* Homepage

</details>

<details open>
<summary>Media Center</summary>

* Jellyfin

</details>

