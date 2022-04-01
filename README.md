# Django Rest Framework Shell

This is a VS Code devcontainer for developing a DRF API with Postgres.

The Django project is called `app` and there is a an app called 
`core` for building application models and core functionality.

You need to setup the SECRET_KEY environment variable.  Change to the `app` subdirectory
and run the following command to generate a unique SECRET_KEY.

`python -c 'from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())'`

Create a file called `.env` in the `.devcontainer` folder with the following content replacing *output from the command above* with your secret key.:

```
SECRET_KEY=*output from the command above*
```

replacing *output from the command above* with your secret key.

