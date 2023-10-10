# curso-mongoDB QA.Coders T11
## Principais comandos

```
show dbs
```
- Exibe os bancos de dados

```
use nomedobanco
```
 - Faz um switched para um database, mas ele não cria uma estrutura se não houver uma collection.

```
db.alunos.save()
```
- Cria uma datase. O mongoDB só irá criar a database se exsitir uma coleção de dados a ser gravada. Caso contrário ele não irá criar.

```
db.alunos.save({name:"Qa.Coders"})
```
- Para se criar deve-se usar o mesmo comando passando uma chave e um valor conforme exemplo acima.

```
db.dropDatabase()
```
- Para excluir uma database é necessário antes, acessar a database antes através do comando use. E estando dentro da database, você excuta o comando acima.

```
db.getCollectionNames()
```
- Consulta todas as collection.

```
db.createCollection("Veiculos")
```
- Criar uma collection.

### DB.DROP COLLECTION
```
db.alunos.drop()
```
- Remove collection do database.

# Manipulação do banco, consultas e comandos:

Comando find()

Sintaxe:
```
db.alunos.find()
```

Esse comando retorna um arquivo JSON como este:

![image](https://github.com/Fabricioperrone/curso-mongoDB/assets/69866913/7d4a42e9-f58c-4eab-9b57-b16b8e2ad0f3)

 
A ID destaca é criada automaticamente pelo mongo.



Listando apenas um registro.

Sintaxe:
```
Db.alunos.findOne()
```
 ![image](https://github.com/Fabricioperrone/curso-mongoDB/assets/69866913/92f3ad6f-b269-4bb0-83a5-a57dccd936c3)


Identando a busca.

Sintaxe:
```
Db.alunos.find().pretty()
```
![image](https://github.com/Fabricioperrone/curso-mongoDB/assets/69866913/16bd5a94-f610-465d-9fc3-c151556f658d)


# Operadores lógicos de comparação

Seis principais operadores lógicos:

![image](https://github.com/Fabricioperrone/curso-mongoDB/assets/69866913/562553fe-ad34-499e-bb7b-33d716222e88)



