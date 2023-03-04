# dockerize-laravelboilerplate
This is repo could be use for testing deploy laravel-boilerplate (https://github.com/rappasoft/laravel-boilerplate) via docker containter technology



### Usage
-> Copy this 4 file (.env, docker-compose.yml, Dockerfile, nginx_app.conf) to your local root repo folder 

-> Run command 
```docker-compose up -d```

-> After everything run (no error) run migration with this command 
```docker exec boilerplate php artisan migrate```

-> And execute seeding database can use this command 
```docker exec boilerplate php artisan db:seed```

-> The laravel can be access in browser with url http://localhost/


### Note
- docker and docker-compose has to be installed first
- tested in wsl ubuntu windows 11