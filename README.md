# rails_crud_api

An Rails application that perform CRUD operation through API calls.

### API request call
Getting all records:
curl localhost:3000/students
--------------------------------------
Insert Record:
curl -H "Content-Type: application/json" -X POST -d '{"name":"xyz","age":20}' http://localhost:3000/students
--------------------------------------
Update Record:
curl -H "Content-Type: application/json" -X PATCH -d '{"name":"new_name","age":30}' http://localhost:3000/students/1
--------------------------------------
Getting Single Record:
curl localhost:3000/students/1
--------------------------------------
Delete Specific Record:
curl -H "Content-Type: application/json" -X DELETE http://localhost:3000/students/1
--------------------------------------
