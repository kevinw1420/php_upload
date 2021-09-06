# php_test
* Unzip php_project.zip
1. docker-compose up -d at docker-compose.yaml file path
2. visit http://localhost:80/helloWorld
3. my new site will be displayed
4. backup script at ./compose/mysql/backup/backup.sh
5. the script will backup up all databases exclude information_schema,performance_schema
6. the script will also delete backup up created over 10 days
7. crontab the script if it's needed
8. url http://localhost:8080 is mysql GUI tool
