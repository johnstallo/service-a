# Sample service-a
In order to work with this repo, you must first build and publish service-b to an Azure Container Registry. Once that is done, update the reference to service-b in the docker-compose.ci.service-tests.yml file by replacing "myreg" and "myuser" with the registry name and your GitHub user.