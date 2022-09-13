# infraarr
The goal of infraarr is to help deploy and automate the entire platform for a homelab environment.

First run docker-compose-yml in ansible to correctly configure hosts with docker.
Second run infraarr.yml to configure hosts correctly with approriate users and groups.
Third run the docker-compose.yml file to deploy all the containers.
