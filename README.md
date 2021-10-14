# Example of usage for conda in docker.



1. List the require packages in the file `requirements.txt`

2. Build the docker image: `docker build -t mycondaimage .` (use the name of your choice instead of mycondaimage)

3. Run : `docker run mycondaimage python3 --version`
