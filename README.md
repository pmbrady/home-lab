# Home-Lab

## NAS
- **Host:** [NAS Sign-In](http://192.168.4.39:5000/#/signin)  
- **Credentials:** 1Password NAS  

## Proxmox
- **Host:** [Proxmox Dashboard](https://192.168.4.49:8006/#v1:0:18:4:::::::)  
- **Credentials:** 1Password Proxmox  

  ### Virtual Machines:
  - **Home Assistant:**
    - **Host:** [Home Assistant Dashboard](http://192.168.4.50:8123/)  
    - **Credentials:** 1Password NAS  
    - **Ingress Services:**
      - **Sonarr:**  
        [Sonarr Dashboard](http://192.168.4.50:8123/db21ed7f_sonarr_nas/ingress)  
      - **Radarr:**  
        [Radarr Dashboard](http://192.168.4.50:8123/db21ed7f_radarr_nas/ingress)  

  - **Docker VM:**
    - **Purpose:** Hosts multiple containers.  
    - **Key Containers:**
      - **Immich:**  
        - A high-performance self-hosted photo and video backup solution.  
        - More details: Add link or description here if applicable.

  ### Features:
  - **Shell:** Cloudflared for secure tunneling  
  - **VM Management:** Create, delete, and snapshot virtual machines  

## SabNzb
(Add details as needed)  

## QbitTorrent
(Add details as needed)  

## Plex
(Add details as needed)  
