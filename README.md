# fastai-notes
A series of JupyterNotebooks noting the things I learnt while going through FastAI v3 MOOC. The notebooks and source codes were developed using customer JupyterNotebook Docker container, which can be pulled directly from DockerHub with Docker image id `jctc/torch:latest`. You can setup your local environment to run these notebooks via the docker command: 
`docker run -d --name [YourContainerName] -v $PWD:/projects -p 8000:8888 -p 6000:6006 jctc/torch:latest` 

This runs a docker container in the background (in detached mode). You can get list of your JupyterNotebook instance(s) runner via:
`docker exec [YourContainerNameSameAsAbove] jupyter notebook list`

Obtain the token output by running the command above. Go to localhost:8000 and paste in token and it should allow you to login into your local instance of notebook server.
