# beatitud-mail


### Start Mailu
You may now start Mailu. Move the to the Mailu directory and run:

```commandline
docker-compose up -d
```
Finally, you must create the initial admin user account:
```commandline
docker-compose run --rm admin python manage.py admin root example.net password
```

This will create a user named root@example.net with password password and administration privileges. Connect to the Web admin interface and change the password to a strong one.