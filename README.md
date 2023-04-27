# Camunda8.2-Changes
Step1:execute docker-compose up -d
step2:check if  All containers are up
operate:
http://localhost:8080/swagger-ui/index.html#/ProcessDefinition/search_2
![image](https://user-images.githubusercontent.com/80270057/234452242-c3d0306e-3aca-4c41-ab4d-5893ac7c3e29.png)

tasklist:
http://localhost:8081/swagger-ui/index.html#/Task/getTaskById
![image](https://user-images.githubusercontent.com/80270057/234452766-7fe4419d-3189-4aef-b5fa-54532233b024.png)

getTasksfrompocessInstanceid:
![image](https://user-images.githubusercontent.com/80270057/234719583-4959cf10-97a1-4857-8ebc-a5c9b8a9a8a8.png)


http://localhost:8081/v1/tasks/search
method:post
body:
{
 
  "processInstanceKey": "2251799813685259"
 
}
