# guide_docker-nginx
A Guide how to Run Nginx inside docker and manage that via a Stealify Application Server  exposing volumes to it

 ## Example 1
Expose Volume with Inital Nginx Config Complet and Start nginx container

## Example 2
Expose Volume with Application Blocks + Domain Mapping File to Match agains

## Details for 1 and 2
The Init Config no Matter how Supplyed includes server blocks ?
then we can simply return a Server Block for Each Domain or Inject if nothing prefents us from that into the Default and use a domain map file. 

## Example 3 
Simply only Cache what ever our Application server returns and handle more caching to a extra frontend if needed

## Example 4
Serve from a Cache Location Static Application Files.
