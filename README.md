# delicious-api
An API in Django for serving and managing delicious recipes.

## Running
The app is set up to run inside a Docker container. To start the app, execute the following command from the project root:
```shell
docker compose up
```
You can then test the api by going to `localhost:8000/api/docs`. This is the path to the Swagger documentation, which lets you test all endpoints right from your browser.

## Testing
To run all unit tests, execute the following command from the project root:
```shell
docker compose run --rm app sh -c "python manage.py test"
```
