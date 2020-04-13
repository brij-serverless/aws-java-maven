# aws-java-maven Basic hello word application
docker-compose up 

docker-compose down 

mvn clean install

sls deploy --stage local

sls invoke local --function hello
