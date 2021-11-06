This was created as a result of misunderstanding the n8n docker-compose.yml file - I recommend you use the [official docker-compose.yml file](https://github.com/n8n-io/n8n/blob/master/docker/compose/withPostgres/docker-compose.yml), and manually adjust the version number if necessary.

Once deployed you can only edit the docker-compose.yml file config, and not edit the .env file that contains the credential config.

However when creating an n8n stack you can upload a .env file _there_.
