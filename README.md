# azure
compose.. yay.   

..  

```
services.traefik.networks.default contains unsupported option: 'external'
ERROR: Service "traefik" uses an undefined network "traefik-net"

NETWORK ID          NAME                DRIVER              SCOPE
80be9ac0c479        bridge              bridge              local
d6bc305d6048        docker_gwbridge     bridge              local
e6efe76b883c        host                host                local
87xaofl61j9b        ingress             overlay             swarm
944a7e4c50a4        none                null                local
hqpkpm7zl0o3        traefik-net         overlay             swarm
```