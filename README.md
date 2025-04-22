# About

This is a docker setup for Laravel development and can be used with any of its versions. This example was done with Laravel 10. In addition, it can be used with Inertia and Livewire.

# Development

NodeJS can run on local machine for development.

1. docker compose up -d
2. docker-compose exec app bash
3. Laravel deployment commands (check Laravel docs about deployment)
4. exit 
5. npm run dev
6. Go to localhost:8000
7. Done!

# Errors and solutions:

<p>ERR_CONNECTION_REFUSED</p>
<p>Solution: delete public/hot and rebuild the application</p>

<p>Page reloading after navigation</p>
<p>Solution: change session and cache drivers from database to redis or array</p>





