# Example of usage for conda in docker.



1. List the require packages in the file `requirements.txt`

2. Build the docker image: `docker build -t mycondaimage .` (use the name of your choice instead of mycondaimage)

3. Run : `docker run mycondaimage python3 --version`


On github, an action is configured to automatically build and deploy the docker image. It can be downloaded with the following commands (remember to change the path with your name and project'name):

# Docker: 
`docker pull ghcr.io/arnaudceol/docker-conda-template:main`

# singularity:
`singularity pull docker://ghcr.io/arnaudceol/docker-conda-template:main`
