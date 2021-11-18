utilizando camunda modeler nós desenhamos um processo
criamos um projeto java com camunda initializer
pegamos o xml do processo e jogamos dentro do projeto
quando projeto builda ele sobe uma ui completa de administração do camunda no localhost
e é possivel tambem fazer todas as atividades da ui por api!

doc da api:

POST

http://localhost:8080/mba/process-definition/key/Process_1f0z70k/start

{ "variables": { "nome": { "value": "Jose da Silva", "type": "String" }, "aprovado": { "value": true, "type": "Boolean" } } }