#HomeLab est. may 2019


Core Router / Firewall 
      Palo P220 
      
Lab Switch 
      
   Cisco SG200 
         managed L3 switch to provide connectivity to Lab
r720
  
   Vmware - Esxi 7 
  
      VM0 - Hiemdall
            Linux Ubuntu Server 18.04LTS
              Docker
              PiHole - DNS Black Hole (network wide add block)
              OpenVPN server
                
        VM1 - Odin v2
              Linux Ubuntu Server 18.04LTS
               Running
                 Plex
                 Docker
                  Portainer
                  Netdata
                  watchtower
                  Transmission w/open VPN
                  jackett
                  sonarr
                  radarr
        VM2 - Thor
              Windows Server 2016
                General Microsoft server test platform
         
        VM3 - SARL
              Linux Ubuntu 18.04 desktop
                General Linux test platform
              
        VM4 - SOC  
              QRadar
                log collection from all devices along with Palo feeds
        
        VM5 - Kenny
              Windows 10 64bit
                windows test platform (to be killed are redeployed regularly)
        
        VM6 - Yoda
              Kali box
                
r710
  Vmware - Esxi 6.5 
  
      VM0 - Veeam 
      
Dlink 2 bay NAS
     
     offline backups
            
