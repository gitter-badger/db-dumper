# db-dumper

Ferramenta utilitária para extrair dados da base a partir de um registro origem mantendo a integridade referencial.

Para utilizá-la necessário primeiramente instalar as dependências.

```
npm install
```

Após instalada as dependencias executar o seguinte comando:

```
node main.js -t table_a -H 127.0.0.1 -P 3306 -d test -u root -p root -r
```
