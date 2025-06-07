# Home-Lab

## NAS
- **Host:** [NAS Dashboard](http://192.168.4.39:5000/#/signin)  
- **Credentials:** 1Password NAS  

## Proxmox
- **Host:** [Proxmox Dashboard](https://192.168.4.49:8006/#v1:0:18:4:::::::)  
- **Credentials:** 1Password Proxmox

  ### Shell:
    - **CloudflareD:**

  ### Virtual Machines:
  - **Home Assistant:**
    - **Host:** [Home Assistant Dashboard](http://192.168.4.50:8123/)  
    - **Credentials:** 1Password NAS  
    - **Ingress Services:**
      - **Sonarr:**  
        [Sonarr Dashboard](http://192.168.4.50:8123/db21ed7f_sonarr_nas/ingress)  
      - **Radarr:**  
        [Radarr Dashboard](http://192.168.4.50:8123/db21ed7f_radarr_nas/ingress)
      - **SabNAB:**  
        [SabNAB Dashboard](http://192.168.4.50:8089/)  
        Credentials 1Password SabNZB
      - **qBitTorrent:**  
        [qBitTorrent Dashboard](http://192.168.4.50:8082/#//)

  - **Plex:**
    [Plex Dashboard](http://192.168.4.61:32400/web/index.html#!/)

  - **Docker:**
    - **Host:** 192.168.4.73
    - **Credentials:** 1Password docker server (proxmox)
    - Containers
      - **Immich:**  
        [Immich Dashboard](http://192.168.4.67:2283/)
        Credentials 1Password Immich web





