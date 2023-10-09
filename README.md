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

