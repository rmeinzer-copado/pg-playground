# pg-playground

https://www.postgresql.org/docs/16/tutorial.html

To run in CodeSpaces (vs. locally)
docker ps
docker start my-postgres
cd tutorial
psql -h localhost -p 5432 -U postgres -d mydb-s
mydb=> \i basics.sql