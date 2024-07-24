# About

This is a container setup for Laravel and Inertia.

# Production

1. docker compose up -d
2. docker-compose exec app bash
3. npm install
4. Laravel deployment commands - https://laravel.com/docs/10.x/deployment
5. npm run build
6. Go to localhost:8989
7. Done!

# Development

NodeJS can run on local machine for development.

1. docker compose up -d
2. docker-compose exec app bash
3. Laravel deployment commands - https://laravel.com/docs/10.x/deployment
4. exit 
5. npm run dev
6. Go to localhost:8989
7. Done!

# Errors and solutions:

<p>ERR_CONNECTION_REFUSED</p>
<p>Solution: delete public/hot and rebuild the application</p>






