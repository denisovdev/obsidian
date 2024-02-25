example of docker-compose.yaml
```yaml
services:
	database:
		container_name: database
		image: postgres:latest
		environment:
			POSTGRES_USER: denisovdev
			POSTGRES_PASSWORD: devD2
			POSTGRES_DB: service
		ports:
		- 5432:5432
```

for running a multi-container group
```zsh
docker-compose up --build
```
